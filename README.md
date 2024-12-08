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
    background: #c8e6c9;
}

.header {
    background: #24292e;
    color: white;
    padding: 1rem;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project-title {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    max-width: 100%;
    margin-left: auto;
    margin-right: auto;
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
        <h1 class="project-title">Мой проект</h1>
    </header>

    <div class="tabs-container">
        <div class="tabs">
            <button class="tab-button active" data-tab="tab1">Главная</button>
            <button class="tab-button" data-tab="tab2">Лунные дни</button>
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
            <br>
            <h3>Информация о размерах страницы:</h3>
            <p>Теперь контентная область занимает всю ширину экрана (100%).</p>
            <p>При этом:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>На всех размерах экрана контент занимает 100% доступной ширины</li>
                <li>Кнопки вкладок теперь не имеют боковых отступов</li>
                <li>Контент вкладок растягивается на всю ширину без боковых отступов</li>
            </ul>
            <p style="margin-top: 20px;">Заголовок "Мой проект" расположен в блоке header, который:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Имеет темно-серый фон (#24292e)</li>
                <li>Содержит отступы по 1rem (16px) сверху и снизу</li>
                <li>Занимает всю ширину экрана</li>
                <li>Имеет тень внизу для визуального отделения от контента</li>
            </ul>
            <p style="margin-top: 10px;">Сам текст заголовка:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Теперь занимает всю доступную ширину (100%)</li>
                <li>Центрируется внутри header с помощью margin: auto</li>
                <li>Имеет размер шрифта:</li>
                <ul style="margin-left: 20px; margin-top: 5px;">
                    <li>2.5rem (40px) на больших экранах</li>
                    <li>2rem (32px) на средних экранах</li>
                    <li>1.5rem (24px) на мобильных устройствах</li>
                </ul>
            </ul>
        </div>

        <div class="tab-content" id="tab2">
            <h2>Лунные дни</h2>
            <p>Привет! 🌙 Лунные дни — это особые периоды в лунном месяце, которые связаны с фазами Луны и её влиянием на Землю и людей. Они считаются важной частью лунного календаря, используемого в астрологии, духовных практиках и иногда в бытовых вопросах, таких как выбор времени для посадки растений или важных начинаний. Давай разберёмся подробнее!

### Что такое лунный день?
Лунный день — это промежуток времени, соответствующий одному обороту Луны вокруг Земли относительно Солнца. Лунный месяц состоит из **29 или 30 лунных дней**, которые начинаются с новолуния и заканчиваются перед следующим. Каждый из этих дней имеет свои энергетические особенности, символы, рекомендации и даже ограничения.

---

### Основные этапы лунного цикла:
1. **Новолуние (1-й лунный день)**  
   Символизирует начало нового цикла. Это время для планирования, анализа и постановки целей. Энергия низкая, поэтому лучше не спешить с активными действиями.  

2. **Растущая Луна (2-14 лунные дни)**  
   Энергия постепенно нарастает. Это благоприятное время для развития, обучения, новых начинаний и накопления ресурсов. Особенно важны дни первой четверти (7-8 лунные дни).  

3. **Полнолуние (15-й лунный день)**  
   Энергетический пик месяца. Важно быть осторожным с эмоциями, так как они могут быть сильнее, чем обычно. Это хорошее время для завершения дел и получения результатов.  

4. **Убывающая Луна (16-29 лунные дни)**  
   Энергия постепенно снижается. Это период очищения, анализа, избавления от ненужного. Можно завершать дела, проводить медитативные практики и заниматься здоровьем.  

---

### Особенности лунных дней:
Каждый лунный день имеет свою символику:  
- **1-й день** — создание намерения, планирование (символ: светильник).  
- **5-й день** — день трансформации, нужно следить за рационом (символ: единорог).  
- **9-й день** — осторожность с негативом и конфликтами (символ: летучая мышь).  
- **19-й день** — время анализа и устранения сомнений (символ: паук).  

Каждый из них несёт свою энергетику, подходящую для определённых действий или, наоборот, для уединения.

---

### Как применять знания о лунных днях?
1. **Планирование дел**:  
   - Начинай что-то новое в период растущей Луны.  
   - Завершай проекты на убывающей Луне.  

2. **Уход за собой**:  
   - В дни полнолуния или перед новолунием лучше избегать лишних нагрузок.  
   - Хорошо проводить детокс и очищение.  

3. **Эмоциональная настройка**:  
   Луна влияет на настроение, поэтому её фазы могут помочь лучше понять свои эмоциональные состояния.

---

Если хочешь узнать конкретный лунный день для сегодняшнего числа или подробнее о каком-то из них, скажи, и я помогу! 🌕✨.</p>
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
            <button class="tab-button" data-tab="tab10">Поддержка</button>
        </div>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const tabButtons = document.querySelectorAll('.tab-button');
    const tabContents = document.querySelectorAll('.tab-content');

    function updateAllButtons(tabId) {
        tabButtons.forEach(btn => {
            if(btn.getAttribute('data-tab') === tabId) {
                btn.classList.add('active');
            } else {
                btn.classList.remove('active');
            }
        });
    }

    tabButtons.forEach(button => {
        button.addEventListener('click', () => {
            tabContents.forEach(content => content.classList.remove('active'));
            const tabId = button.getAttribute('data-tab');
            document.getElementById(tabId).classList.add('active');
            updateAllButtons(tabId);
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
});
</script>

</body></html>
