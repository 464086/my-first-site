<html><head><base href="/" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Мой GitHub блог</title>
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
    background: #24292e;
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
    display: flex;
    align-items: center;
    gap: 10px;
}

.github-icon {
    fill: white;
    width: 24px;
    height: 24px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #6cc644;
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
    border: 1px solid #e1e4e8;
}

.post-title {
    color: #24292e;
    margin-bottom: 10px;
}

.post-meta {
    color: #586069;
    font-size: 0.9rem;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
    gap: 10px;
}

.github-stats {
    display: flex;
    gap: 15px;
    margin-top: 10px;
}

.stat {
    display: flex;
    align-items: center;
    gap: 5px;
    color: #586069;
}

.comments-section {
    margin-top: 20px;
    border-top: 1px solid #e1e4e8;
    padding-top: 20px;
}

.comment {
    background: #f6f8fa;
    padding: 15px;
    border-radius: 6px;
    margin-bottom: 10px;
    border: 1px solid #e1e4e8;
}

.comment-form {
    margin-top: 20px;
}

.comment-form textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    margin-bottom: 10px;
    resize: vertical;
}

.btn {
    background: #2ea44f;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    transition: background 0.3s;
}

.btn:hover {
    background: #2c974b;
}

.subscribe-form {
    background: white;
    padding: 20px;
    border-radius: 8px;
    margin-top: 20px;
    border: 1px solid #e1e4e8;
}

.info-box {
    background: #f1f8ff;
    border: 1px solid #c8e1ff;
    border-radius: 6px;
    padding: 15px;
    margin: 20px 0;
}

</style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <svg class="github-icon" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
                </svg>
                Мой GitHub блог
            </div>
            <div class="nav-links">
                <a href="https://github.com/username">GitHub профиль</a>
                <a href="https://github.com/username/blog/issues">Issues</a>
                <a href="https://github.com/username/blog/wiki">Wiki</a>
            </div>
        </nav>
    </header>

    <div class="container">
        <main class="main-content">
            <div class="info-box">
                <h3>📝 О GitHub Pages</h3>
                <p>Этот блог размещен на GitHub Pages - бесплатном хостинге от GitHub. Вы можете:</p>
                <ul style="margin-left: 20px; margin-top: 10px;">
                    <li>Использовать Markdown для форматирования постов</li>
                    <li>Управлять контентом через Git</li>
                    <li>Использовать систему Issues для комментариев</li>
                    <li>Настроить свой домен</li>
                </ul>
            </div>

            <article class="post">
                <h2 class="post-title">Мой первый пост на GitHub Pages</h2>
                <div class="post-meta">
                    <svg height="16" width="16" viewBox="0 0 16 16">
                        <path fill="#586069" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zm.5 4.75a.75.75 0 00-1.5 0v3.5a.75.75 0 00.471.696l2.5 1a.75.75 0 00.557-1.392L8 7.742V4.75z"/>
                    </svg>
                    Опубликовано: 1 января 2024
                </div>
                <div class="post-content">
                    <p>Это мой первый пост в блоге на GitHub Pages. Здесь будет размещаться основной контент.</p>
                </div>
                
                <div class="github-stats">
                    <div class="stat">
                        <svg height="16" width="16" viewBox="0 0 16 16">
                            <path fill="#586069" d="M8 16A8 8 0 108 0a8 8 0 000 16zm.25-11.25a1.25 1.25 0 11-2.5 0 1.25 1.25 0 012.5 0zm1.5 7.25a.75.75 0 01-.75.75h-2a.75.75 0 110-1.5h.75v-2h-.75a.75.75 0 010-1.5h2a.75.75 0 01.75.75v2.75h.75a.75.75 0 010 1.5z"/>
                        </svg>
                        3 issues
                    </div>
                    <div class="stat">
                        <svg height="16" width="16" viewBox="0 0 16 16">
                            <path fill="#586069" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/>
                        </svg>
                        2 forks
                    </div>
                    <div class="stat">
                        <svg height="16" width="16" viewBox="0 0 16 16">
                            <path fill="#586069" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25z"/>
                        </svg>
                        5 stars
                    </div>
                </div>
                
                <div class="comments-section">
                    <h3>Комментарии через GitHub Issues</h3>
                    <div class="comment">
                        <p><strong>@username</strong>: Отличная статья! Можно добавить еще информации про Jekyll.</p>
                    </div>
                    
                    <a href="https://github.com/username/blog/issues/new" class="btn" style="display: inline-block; margin-top: 10px; text-decoration: none;">
                        Добавить комментарий через GitHub Issues
                    </a>
                </div>
            </article>

            <div class="subscribe-form">
                <h3>Следить за обновлениями</h3>
                <p>Получайте уведомления о новых публикациях через GitHub</p>
                <div style="margin-top: 15px;">
                    <a href="https://github.com/username/blog/subscription" class="btn" style="text-decoration: none;">
                        Watch репозиторий
                    </a>
                </div>
            </div>
        </main>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    // Добавление анимации при наведении на статистику
    const stats = document.querySelectorAll('.stat');
    stats.forEach(stat => {
        stat.addEventListener('mouseover', function() {
            this.style.transform = 'translateY(-2px)';
            this.style.transition = 'transform 0.2s';
        });
        stat.addEventListener('mouseout', function() {
            this.style.transform = 'translateY(0)';
        });
    });

    // Подсветка активной ссылки в навигации
    const navLinks = document.querySelectorAll('.nav-links a');
    navLinks.forEach(link => {
        if (window.location.href === link.href) {
            link.style.color = '#6cc644';
        }
    });
});
</script>

</body></html>
