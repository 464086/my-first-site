<html><head><base href="/" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Мой проект</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}

body {
    background: #f0f7f4; /* Soft mint green background */
}

.header {
    background: linear-gradient(135deg, #2c3e50, #3498db);
    color: white;
    padding: 2rem;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.project-title {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
}

.tabs-container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
}

.tabs {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
}

.tab-button {
    background: #e3edf7; /* Soft blue for inactive tabs */
    border: none;
    padding: 12px 20px;
    border-radius: 8px;
    cursor: pointer;
    flex: 1;
    min-width: 150px;
    font-size: 1rem;
    transition: all 0.3s ease;
    box-shadow: 0 2px 5px rgba(0,0,0,0.08);
    color: #2c3e50;
}

.tab-button:hover {
    background: #d1e3f6;
    transform: translateY(-2px);
}

.tab-button.active {
    background: linear-gradient(135deg, #34495e, #2980b9);
    color: white;
}

.tab-content {
    background: #ffffff; /* Clean white for content */
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    min-height: 300px;
    display: none;
    line-height: 1.6;
    color: #2c3e50;
}

.tab-content.active {
    display: block;
    animation: fadeIn 0.5s ease;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
}

/* Responsive Design */
@media (max-width: 768px) {
    .tab-button {
        width: calc(50% - 5px);
        min-width: unset;
    }
    
    .project-title {
        font-size: 2rem;
    }
}

@media (max-width: 480px) {
    .tab-button {
        width: 100%;
    }
    
    .project-title {
        font-size: 1.5rem;
    }
}
</style>
</head>
<body>
    <header class="header">
        <h1 class="project-title">Мой проект</h1>
    </header>

    <div class="tabs-container">
        <div class="tabs">
            <button class="tab-button active" data-tab="tab1">Главная</button>
            <button class="tab-button" data-tab="tab2">О проекте</button>
            <button class="tab-button" data-tab="tab3">Документация</button>
            <button class="tab-button" data-tab="tab4">Галерея</button>
            <button class="tab-button" data-tab="tab5">Блог</button>
            <button class="tab-button" data-tab="tab6">Команда</button>
            <button class="tab-button" data-tab="tab7">Загрузки</button>
            <button class="tab-button" data-tab="tab8">FAQ</button>
            <button class="tab-button" data-tab="tab9">Контакты</button>
            <button class="tab-button" data-tab="tab10">Поддержка</button>
        </div>

        <div class="tab-content active" id="tab1">
            <h2>Добро пожаловать на главную страницу</h2>
            <p>Здесь размещается основная информация о проекте.</p>
        </div>

        <div class="tab-content" id="tab2">
            <h2>О проекте</h2>
            <p>Подробная информация о целях и задачах проекта.</p>
        </div>

        <div class="tab-content" id="tab3">
            <h2>Документация</h2>
            <p>Техническая документация и руководства.</p>
        </div>

        <div class="tab-content" id="tab4">
            <h2>Галерея</h2>
            <p>Фотографии и изображения проекта.</p>
        </div>

        <div class="tab-content" id="tab5">
            <h2>Блог</h2>
            <p>Новости и обновления проекта.</p>
        </div>

        <div class="tab-content" id="tab6">
            <h2>Команда</h2>
            <p>Информация о участниках проекта.</p>
        </div>

        <div class="tab-content" id="tab7">
            <h2>Загрузки</h2>
            <p>Файлы и материалы для скачивания.</p>
        </div>

        <div class="tab-content" id="tab8">
            <h2>FAQ</h2>
            <p>Часто задаваемые вопросы.</p>
        </div>

        <div class="tab-content" id="tab9">
            <h2>Контакты</h2>
            <p>Контактная информация.</p>
        </div>

        <div class="tab-content" id="tab10">
            <h2>Поддержка</h2>
            <p>Техническая поддержка и помощь.</p>
        </div>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const tabButtons = document.querySelectorAll('.tab-button');
    const tabContents = document.querySelectorAll('.tab-content');

    tabButtons.forEach(button => {
        button.addEventListener('click', () => {
            // Remove active class from all buttons and contents
            tabButtons.forEach(btn => btn.classList.remove('active'));
            tabContents.forEach(content => content.classList.remove('active'));

            // Add active class to clicked button and corresponding content
            button.classList.add('active');
            const tabId = button.getAttribute('data-tab');
            document.getElementById(tabId).classList.add('active');
        });
    });

    // Add hover effect
    tabButtons.forEach(button => {
        button.addEventListener('mouseover', () => {
            if (!button.classList.contains('active')) {
                button.style.transform = 'translateY(-2px)';
            }
        });

        button.addEventListener('mouseout', () => {
            if (!button.classList.contains('active')) {
                button.style.transform = 'translateY(0)';
            }
        });
    });
});
</script>

</body></html>
