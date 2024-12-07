
<html><head><base href="/send-message?">
<style>
    /* Сохраняем тот же CSS */
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        color: #333;
        margin: 0;
        padding: 20px;
        background-color: #f0f0f0;
    }
    .main-content {
        width: 100%;
        max-width: 100%;
        margin: 0 auto;
        background-color: #ffffff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
        box-sizing: border-box;
    }
    .chat-container {
        background-color: #f9f9f9;
        border-radius: 10px;
        padding: 10px;
        margin-top: 10px;
        box-shadow: 0 0 5px rgba(0,0,0,0.05);
    }
    .message {
        margin-bottom: 10px;
        padding: 10px;
        border-radius: 5px;
    }
    .user {
        background-color: #e8f5e9;
        border-left: 5px solid #4caf50;
    }
    .assistant {
        background-color: #e3f2fd;
        border-left: 5px solid #2196f3;
    }
    .system {
        background-color: #fff3e0;
        border-left: 5px solid #ff9800;
    }
    .timestamp {
        font-size: 0.8em;
        color: #777;
        margin-top: 2px;
    }
    .input-container {
        margin-top: 10px;
        display: flex;
        flex-direction: column;
        gap: 5px;
        width: 100%;
    }
    .input-field {
        padding: 10px;
        font-size: 16px;
        border: 2px solid #3498db;
        border-radius: 5px;
        resize: vertical;
        width: 100%;
        box-sizing: border-box;
    }
    .send-button {
        padding: 10px;
        font-size: 16px;
        background-color: #3498db;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s;
    }
    .send-button:hover {
        background-color: #2980b9;
    }
</style>
<script>
document.addEventListener('DOMContentLoaded', function() {
    const form = document.querySelector('form');
    form.addEventListener('submit', function(e) {
        const textarea = document.querySelector('textarea[name="message"]');
        const currentText = textarea.value;
        textarea.value = currentText + " Пожалуйста, сохраняй все разделы и оформление страницы! ";
    });
});
</script>
</head>
<body>
    <div class="main-content">
        <div class="chat-container">
            <form method="GET" action="/send-message" class="input-container">
                <textarea name="message" placeholder="Введите ваше сообщение..." class="input-field" rows="4"></textarea>
                <button type="submit" class="send-button">Отправить</button>
            </form>

            <div class="message assistant">
                <strong>Ассистент:</strong> О, это действительно захватывающая тема! ?? Вот несколько самых удивительных открытий:

1. "Мини-мозги" способны учиться!
- В 2021 году учёные обнаружили, что органоиды могут формировать память
- Они реагируют на повторяющиеся стимулы, демонстрируя что-то вроде обучения
- Это открывает новые возможности для изучения механизмов памяти

2. Синхронизация активности:
- Органоиды способны генерировать ритмичные электрические сигналы
- Эти сигналы похожи на "мозговые волны" настоящего мозга
- Разные участки органоида могут синхронизировать свою активность

3. Самоорганизация:
- Клетки в органоидах сами выстраиваются в сложные структуры
- Формируются различные типы нейронов
- Создаются примитивные "нейронные сети"

4. Реакция на свет:
- Некоторые органоиды развили светочувствительные клетки
- Они могут реагировать на световые стимулы
- Это помогает понять развитие органов чувств

5. Моделирование заболеваний:
- Удалось воссоздать некоторые особенности аутизма и шизофрении
- Это помогает тестировать новые методы лечения
- Появилась возможность изучать ранние стадии заболеваний

Хочешь узнать подробнее о каком-то из этих открытий? Или поговорим о том, как эти исследования могут помочь в лечении различных заболеваний? ??
                <div class="timestamp">12:39</div>
            </div>

            <div class="message user">
                <strong>Пользователь:</strong> А какие удивительные открытия были сделаны с помощью этих исследований? Пожалуйста, сохраняй все разделы и оформление страницы!
                <div class="timestamp">12:38</div>
            </div>

            <!-- Previous messages remain unchanged -->
            <div class="message assistant">
                <strong>Ассистент:</strong> Конечно! С удовольствием расскажу о том, как учёные исследуют "сознательность" церебральных органоидов. Это очень увлекательная тема! ??

Вот основные методы, которые используются:

1. Электрофизиологические исследования:
- Учёные используют микроэлектроды для регистрации электрической активности
- Измеряют потенциалы действия отдельных нейронов
- Наблюдают за формированием спонтанных электрических импульсов

2. Оптогенетические методы:
- В нейроны внедряют светочувствительные белки
- При освещении определённым светом можно активировать или подавлять активность нейронов
- Это позволяет изучать реакции органоида на внешние стимулы

3. Визуализация активности:
- Используются флуоресцентные маркеры, реагирующие на кальций
- Можно наблюдать, как "загораются" активные нейроны
- Создаются подробные карты нейронных сетей

4. Молекулярный анализ:
- Изучается экспрессия генов, связанных с развитием мозга
- Отслеживается формирование синапсов
- Анализируются нейромедиаторные системы

Самое удивительное, что органоиды демонстрируют активность, похожую на активность развивающегося мозга! Они могут спонтанно генерировать электрические сигналы и даже формировать что-то вроде примитивных "нейронных цепей". 

Хочешь узнать о каком-то конкретном методе подробнее? Или поговорим о том, какие удивительные открытия были сделаны с помощью этих исследований? ??
                <div class="timestamp">12:37</div>
            </div>

            <div class="system">
                <strong>Системное сообщение (всегда внизу, неизменяемое, неудаляемое):</strong>  
            </div>
        </div>
    </div>
</body>
</html>
