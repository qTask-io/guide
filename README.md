# Guide
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Моя веб-страница</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Ваши стили остаются без изменений */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 10px;
        }
        .gallery-item {
            flex: 1 1 300px;
            margin: 10px;
            max-width: 300px;
            box-sizing: border-box;
        }
        .gallery-item img {
            width: 100%;
            height: auto;
        }
        .gallery-item p {
            text-align: center;
            padding: 5px;
        }
        @media (max-width: 600px) {
            .gallery-item {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>

    <div class="gallery">
        <!-- Изображение 1 -->
        <div class="gallery-item">
            <img src="1.jpg" alt="Описание изображения 1">
            <p>Текст для изображения 1</p>
        </div>
        <!-- Изображение 2 -->
        <div class="gallery-item">
            <img src="2.jpg" alt="Описание изображения 2">
            <p>Текст для изображения 2</p>
        </div>
        <!-- Изображение 3 -->
        <div class="gallery-item">
            <img src="3.jpg" alt="Описание изображения 3">
            <p>Текст для изображения 3</p>
        </div>
        <!-- Изображение 4 -->
        <div class="gallery-item">
            <img src="4.jpg" alt="Описание изображения 4">
            <p>Текст для изображения 4</p>
        </div>
        <!-- Изображение 5 -->
        <div class="gallery-item">
            <img src="5.jpg" alt="Описание изображения 5">
            <p>Текст для изображения 5</p>
        </div>
        <!-- Изображение 6 -->
        <div class="gallery-item">
            <img src="6.jpg" alt="Описание изображения 6">
            <p>Текст для изображения 6</p>
        </div>
        <!-- Изображение 7 -->
        <div class="gallery-item">
            <img src="7.jpg" alt="Описание изображения 7">
            <p>Текст для изображения 7</p>
        </div>
        <!-- Изображение 8 -->
        <div class="gallery-item">
            <img src="8.jpg" alt="Описание изображения 8">
            <p>Текст для изображения 8</p>
        </div>
    </div>

</body>
</html>
