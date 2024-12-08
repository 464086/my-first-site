<html><head><base href="/" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Лунные дни - что это?</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}

body {
    background: #c8e6c9;
}

.header {
    background: #24292e;
    color: white;
    padding: 0.25rem; /* Changed from 0.5rem to 0.25rem */
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project-title {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    max-width: 100%;
    margin-left: auto;
    margin-right: auto;
    cursor: pointer;
    transition: all 0.3s ease;
    background-color: #1a237e;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    display: inline-block;
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.7);
}

.project-title.active {
    background-color: #ff5252;
    color: white;
    box-shadow: 0 0 15px #ffeb3b;
}

.tabs-container {
    width: 100%;
    margin: 20px auto;
    padding: 0;
}

.tabs {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
    padding: 0;
}

.bottom-tabs {
    margin-top: 20px;
    margin-bottom: 40px;
}

.tab-button {
    background: #1a237e;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 5px;
    cursor: pointer;
    flex: 1;
    min-width: 150px;
    font-size: 1rem;
    transition: all 0.3s ease;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.tab-button:hover {
    opacity: 0.9;
    transform: translateY(-2px);
}

.tab-button.active {
    background: #ff5252;
    color: white;
    box-shadow: 0 0 15px #ffeb3b;
}

.tab-content {
    background: #e3f2fd;
    padding: 20px;
    border-radius: 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    min-height: 300px;
    display: none;
    width: 100%;
}

.tab-content.active {
    display: block;
    animation: fadeIn 0.5s ease;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

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
        <h1 class="project-title">Лунные дни - что это?</h1>
    </header>

    <div class="tabs-container">
        <div class="tabs">
            <button class="tab-button" data-tab="tab1">Главная</button>
            <button class="tab-button" data-tab="tab2">О проекте</button>
            <button class="tab-button" data-tab="tab3">Документация</button>
            <button class="tab-button" data-tab="tab4">Галерея</button>
            <button class="tab-button" data-tab="tab5">Блог</button>
            <button class="tab-button" data-tab="tab6">Команда</button>
            <button class="tab-button" data-tab="tab7">Загрузки</button>
            <button class="tab-button" data-tab="tab8">FAQ</button>
            <button class="tab-button" data-tab="tab9">Контакты</button>
            <button class="tab-button" data-tab="tab10">Ответы Ассистента</button>
        </div>

        <div class="tab-content" id="tab1">
            <h2>Главная страница</h2>
            <p>Добро пожаловать в проект "Лунные дни"</p>
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
            <h2>Ответы Ассистента</h2>
            <p>История изменений и текущие параметры сайта:</p>
            <br>
            <h3>Текущие параметры страницы:</h3>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Все страницы занимают 100% ширины экрана</li>
                <li>Кнопки вкладок расположены без боковых отступов</li>
                <li>Кнопки вкладок продублированы внизу страницы</li>
                <li>Неактивные вкладки имеют темно-синий цвет (#1a237e)</li>
                <li>Активная вкладка имеет ярко-красный цвет (#ff5252) с желтым ореолом (#ffeb3b)</li>
                <li>Заголовок "Лунные дни - что это?" расположен в шапке с отступами 0.25rem (4px)</li>
                <li>Шапка имеет темно-серый фон (#24292e) и тень</li>
                <li>Заголовок является кликабельным и ведет на собственную страницу</li>
                <li>При неактивном состоянии заголовок имеет темно-синий фон (#1a237e) и белый цвет текста</li>
                <li>При активном состоянии заголовок имеет красный фон (#ff5252) с желтым ореолом и белый цвет текста</li>
            </ul>
        </div>

        <div class="tab-content active" id="lunnyedni">
            <h2>Лунные дни - что это?</h2>
            <p>Лунные дни - это особые периоды времени, связанные с движением Луны. Каждый лунный день имеет свои уникальные характеристики и влияние на различные аспекты нашей жизни.</p>
            <br>
            <p>В лунном календаре существует 29-30 лунных дней, которые не совпадают с солнечными сутками. Первый лунный день начинается в момент новолуния и длится до восхода Луны следующих суток.</p>
            <br>
            <p>Знание особенностей каждого лунного дня помогает:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Планировать важные дела</li>
                <li>Понимать свое эмоциональное состояние</li>
                <li>Выбирать благоприятное время для начинаний</li>
                <li>Гармонизировать свою жизнь в соответствии с природными циклами</li>
            </ul>
        </div>

        <div class="tabs bottom-tabs">
            <button class="tab-button" data-tab="tab1">Главная</button>
            <button class="tab-button" data-tab="tab2">О проекте</button>
            <button class="tab-button" data-tab="tab3">Документация</button>
            <button class="tab-button" data-tab="tab4">Галерея</button>
            <button class="tab-button" data-tab="tab5">Блог</button>
            <button class="tab-button" data-tab="tab6">Команда</button>
            <button class="tab-button" data-tab="tab7">Загрузки</button>
            <button class="tab-button" data-tab="tab8">FAQ</button>
            <button class="tab-button" data-tab="tab9">Контакты</button>
            <button class="tab-button" data-tab="tab10">Ответы Ассистента</button>
        </div>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const tabButtons = document.querySelectorAll('.tab-button');
    const tabContents = document.querySelectorAll('.tab-content');
    const projectTitle = document.querySelector('.project-title');

    // Set initial state
    projectTitle.classList.add('active');

    function updateAllButtons(tabId) {
        tabButtons.forEach(btn => {
            if(btn.getAttribute('data-tab') === tabId) {
                btn.classList.add('active');
            } else {
                btn.classList.remove('active');
            }
        });
    }

    function switchToTab(tabId) {
        tabContents.forEach(content => content.classList.remove('active'));
        document.getElementById(tabId).classList.add('active');
        updateAllButtons(tabId);
        projectTitle.classList.remove('active');
    }

    tabButtons.forEach(button => {
        button.addEventListener('click', () => {
            const tabId = button.getAttribute('data-tab');
            switchToTab(tabId);
        });

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

    projectTitle.addEventListener('click', () => {
        tabContents.forEach(content => content.classList.remove('active'));
        document.getElementById('lunnyedni').classList.add('active');
        tabButtons.forEach(btn => btn.classList.remove('active'));
        projectTitle.classList.add('active');
    });
});
</script>

</body></html>
