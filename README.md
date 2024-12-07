<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой блог</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .post {
            margin-bottom: 20px;
        }
        .post h2 {
            color: #555;
        }
        .comment-section {
            margin-top: 30px;
        }
        .comment-section h3 {
            margin-bottom: 10px;
        }
        textarea {
            width: 100%;
            height: 100px;
            margin-bottom: 10px;
        }
        button {
            background: #5cb85c;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #4cae4c;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Добро пожаловать в мой блог!</h1>

        <div class="post">
            <h2>Первая публикация</h2>
            <p>Это мой первый пост. Здесь я расскажу о своих интересах, проектах и идеях!</p>
        </div>

        <div class="comment-section">
            <h3>Оставьте комментарий</h3>
            <textarea placeholder="Ваш комментарий..."></textarea>
            <button>Отправить</button>
        </div>
    </div>
</body>
</html>
