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
    padding: 1rem; /* Reduced from 2rem to 1rem */
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project-title {
    font-size: 2.5rem;
    margin-bottom: 0.5rem; /* Reduced from 1rem to 0.5rem */
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
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    min-height: 300px;
    display: none;
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
            <p>Здесь размещается основная информация о проекте.Винокуров И.В., Непомнящий Н.Н. Люди и феномены В книге представлены самые разные категории необычных людей: от несчастных жертв редкостных анатомических аномалий до загадочных обладателей умственной и парапсихологической феноменальности. Почему везет везунчикам? Что нас поражает в близнецах? Кто "главная ведьма России"? Где и как обрести собственную феноменальность? Ответы на эти и многие другие интригующие вопросы читатель найдет в предлагаемой книге. Людмиле Барановой, наделенной феноменально выраженным даром исцелять страждущих Вместо предисловия "Человек есть тайна. Ее надо разгадать, и ежели будешь ее разгадывать всю жизнь, то не говори, что потерял время..." Слова эти принадлежат Ф. М. Достоевскому. Немало времени прошло с тех пор, как они были сказаны, и немало было сделано, чтобы разгадать загадку человека, но природа все продолжает скрывать от него самого свою самую великую тайну: что есть человек? Выражение, а вместе с тем и понятие "феномен человека" ввел в научный оборот выдающийся французский мыслитель Пьер Тейяр де Шарден (1881-1955). Оно впервые прозвучало в названии его самой, пожалуй, известной книги - "Феномен человека" (Париж, 1955). На русском языке этот труд незаурядного ученого издавался дважды - в 1965 и 1987 годах. К введенному им понятию ученый обращается уже на самых первых страницах книги: "Итак, феномен человека. Это слово взято не случайно.  Во-первых, я этим утверждаю, что человек в природе есть настоящий факт, к которому приложим ы (по крайней мере, частично) требования и методы науки. Во-вторых, я даю понять, что из всех фактов, с какими имеет дело наше познание, ни один не является столь необыкновенным и столь озаряющим". Вместе с тем французский мыслитель дает понять и то, что феномен человека, говоря современным языком, явление многоплановое, многомерное, к тому же необыкновенное, и его изучение должно носить не дробный, а целостный характер: "Изучаемый сам по себе в узком плане антропологами и юристами, человек - нечто весьма малое и даже умаляющее. Слишком выделяющаяся индивидуальность человека маскирует собой целостность, и наш рассудок, рассматривая человека, склонен дробить природу ". Однако, как бы в ответ на столь своевременно высказанную П. Тейяром де Шарденом мысль о необходимости целостного подхода при изучении феномена человека - и это убедительно показывают российские исследователи М. Я. Бобров, П. В. Ушаков и Е. В. Ушакова', - примерно с начала 50-х годов текущего столетия отдельные направления изучения человека в разных областях знания (антропные ' Бобров М. Я., Ушаков П. ВД Ушакова Е. В. Причины, пути и перспективы антропного движения в социологии и философии XX века. - Барнаул: Алтайский государственный университет, 1996. ния) начинают проявлять тенденцию к слиянию. Впоследствии это привело к возникновению и дальнейшему развитию антропного движения, в рамках которого процесс познания феномена человека, его особенностей тайн и загадок приобрел целостный, синтетический, комплексный характер. И вот тому яркий пример: в России создан Институт человека Российско,й академии наук, формируется новая отрасль научного знания человековедение. Тем не менее стоит отметить, что человек как явление природы одновременно несет в себе черты не только целостности, но и уникальности: все мы - люди, но каждый из нас неповторим. В ряде случаев особенности отдельного человека носят столь редкостный и необычный характер, что о таких личностях говорят не иначе как о людях-феноменах, чудо-людях. Наша книга именно о них. Что же заставило нас обратиться к людям-феноменам? Дело в том, что процесс познания сути, природы человека носит двойственный характер: с одной стороны, синтетический (антропное движение), с другой аналитический (отдельные антропные исследования). Но каждая из сторон, несмотря на перспективность синтетического подхода на данном этапе, имеет свои преимущества. Ни одну из них не следует абсолютизировать. В противном случае мы, образно говоря, либо за лесом не увидим деревьев (абсолютизация синтетического подхода), либо за деревьями не заметим леса (абсолютизация подхода аналитического). Важен и еще один момент. Известно, что перенос внимания исследователя на всяческие крайности, отклонения от нормы зачастую помогает значительно глубже проникнуть в суть



, чем сосредоточение только на специфике нормы. Именно поэтому мы обратились не к норме (кто способен сказать, что такое норма?), а к отклонениям от нее, то есть к людям-феноменам. Думается, что изучение подобного рода уникумов углубит наши представления о том, что считать нормой применительно к человеку. Возможно, в каких-то случаях понятие "норма" будет сужено, в каких-то - расширено. Последнее, скорее всего, произойдет в отношении тех не признаваемых академической наукой способностей человека, которые принято называть парапсихологическими...</p>
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
            // Remove active class from all contents
            tabContents.forEach(content => content.classList.remove('active'));

            // Add active class to corresponding content
            const tabId = button.getAttribute('data-tab');
            document.getElementById(tabId).classList.add('active');
            
            // Update all buttons (both top and bottom)
            updateAllButtons(tabId);
        });

        // Add hover effect
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
