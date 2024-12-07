<html><head><base href="/" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Мой блог</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}

body {
    background: #f5f5f5;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background: #2c3e50;
    color: white;
    padding: 1rem;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.nav-links a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
}

.main-content {
    margin-top: 2rem;
}

.post {
    background: white;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.post-title {
    color: #2c3e50;
    margin-bottom: 10px;
}

.post-meta {
    color: #7f8c8d;
    font-size: 0.9rem;
    margin-bottom: 15px;
}

.comments-section {
    margin-top: 20px;
}

.comment {
    background: #f9f9f9;
    padding: 15px;
    border-radius: 5px;
    margin-bottom: 10px;
}

.comment-form {
    margin-top: 20px;
}

.comment-form textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin-bottom: 10px;
}

.btn {
    background: #3498db;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s;
}

.btn:hover {
    background: #2980b9;
}

.subscribe-form {
    background: white;
    padding: 20px;
    border-radius: 8px;
    margin-top: 20px;
}

</style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Мой блог</div>
            <div class="nav-links">
                <a href="https://myblog.com/home">Главная</a>
                <a href="https://myblog.com/about">О блоге</a>
                <a href="https://myblog.com/contact">Контакты</a>
            </div>
        </nav>
    </header>

    <div class="container">
        <main class="main-content">
            <article class="post">
                <h2 class="post-title">Добро пожаловать в мой блог!</h2>
                <div class="post-meta">
                    Опубликовано: 1 января 2024 | Автор: Администратор
                </div>
                <div class="post-content">
                    <p>Это пример первой записи в блоге. Здесь будет размещаться основной контент.</p>
                </div>
                
                <div class="comments-section">
                    <h3>Комментарии</h3>
                    <div class="comment">
                        <p><strong>Иван</strong>: Отличная статья!</p>
                    </div>
                    
                    <form class="comment-form">
                        <textarea placeholder="Оставьте свой комментарий..." rows="4"></textarea>
                        <button class="btn">Отправить комментарий</button>
                    </form>
                </div>
            </article>

            <div class="subscribe-form">
                <h3>Подписаться на обновления</h3>
                <p>Получайте уведомления о новых записях</p>
                <form id="subscribe">
                    <input type="email" placeholder="Ваш email" style="padding: 10px; margin: 10px 0; width: 100%;">
                    <button class="btn">Подписаться</button>
                </form>
            </div>
        </main>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    // Обработка формы комментариев
    const commentForm = document.querySelector('.comment-form');
    commentForm.addEventListener('submit', function(e) {
        e.preventDefault();
        const textarea = this.querySelector('textarea');
        if (textarea.value.trim() !== '') {
            const commentsSection = document.querySelector('.comments-section');
            const newComment = document.createElement('div');
            newComment.className = 'comment';
            newComment.innerHTML = `<p><strong>Гость</strong>: ${textarea.value}</p>`;
            commentsSection.insertBefore(newComment, commentForm);
            textarea.value = '';
        }
    });

    // Обработка формы подписки
    const subscribeForm = document.getElementById('subscribe');
    subscribeForm.addEventListener('submit', function(e) {
        e.preventDefault();
        const email = this.querySelector('input[type="email"]').value;
        if (email) {
            alert('Спасибо за подписку! Вы будете получать уведомления о новых публикациях.');
            this.reset();
        }
    });
});
</script>

</body></html>

Это базовый шаблон блога с основными функциями. Для полноценной работы вам потребуется:

1. Хостинг для размещения сайта
2. База данных для хранения постов и комментариев
3. Серверная часть (например, на PHP, Python или Node.js) для:
   - Управления контентом
   - Хранения комментариев
   - Отправки уведомлений подписчикам
   - Аутентификации пользователей

Рекомендую рассмотреть следующие варианты создания блога:

1. WordPress - популярная CMS с множеством готовых тем и плагинов
2. Ghost - современная платформа для блогинга
3. Medium - готовая платформа для публикации статей
4. Jekyll + GitHub Pages - для технически подкованных пользователей

Какой вариант вас больше интересует? Я могу подробнее рассказать о любом из них.
