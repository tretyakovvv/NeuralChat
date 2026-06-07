# NeuralChat

## Русский

NeuralChat — это одностраничное AI-веб-приложение с премиальным тёмным интерфейсом, историей диалогов и мультимодельной архитектурой.

### Что умеет сайт

- Вести диалог в формате современного AI-чата
- Подключаться к `Polza AI`
- Использовать модель `deepseek/deepseek-r1-distill-llama-70b`
- Хранить историю чатов локально в браузере
- Показывать код в отдельном визуальном окне с нумерацией строк и кнопкой копирования
- Поддерживать русский и английский интерфейс
- Открывать админ-панель для ключей провайдеров и настроек YooKassa
- Показывать меню покупки токенов
- Работать как single-file приложение на чистом `HTML + CSS + JavaScript`

### Интерфейс

Проект оформлен в стиле dark luxury:

- стеклянный тёмный sidebar
- акцентные фиолетово-розовые градиенты
- анимированный empty state
- streaming-ответы модели
- адаптивный layout для desktop и mobile

### Основные разделы

1. Sidebar с историей диалогов
2. Основная зона чата
3. Админка для ключей и платёжных настроек
4. Раздел покупки токенов через YooKassa

### Технологии

- `HTML`
- `CSS`
- `Vanilla JavaScript`
- `Polza AI API`
- `YooKassa UI draft flow`

### Запуск локально

Откройте `index.html` в браузере или поднимите простой локальный сервер:

```bash
python3 -m http.server 4173
```

После этого приложение будет доступно по адресу:

```text
http://localhost:4173/
```

---

## English

NeuralChat is a single-page AI web application with a premium dark interface, chat history, and a multi-model-ready architecture.

### What the website does

- Provides a modern AI chat experience
- Connects to `Polza AI`
- Uses the `deepseek/deepseek-r1-distill-llama-70b` model
- Stores chat history locally in the browser
- Renders code inside a dedicated visual code window with line numbers and copy action
- Supports both Russian and English UI
- Includes an admin panel for provider keys and YooKassa settings
- Includes a token purchase menu
- Runs as a single-file app built with plain `HTML + CSS + JavaScript`

### Interface style

The product follows a dark luxury design direction:

- glass-style dark sidebar
- purple-to-pink accent gradients
- animated empty state
- streaming model responses
- responsive layout for desktop and mobile

### Main sections

1. Sidebar with conversation history
2. Main chat workspace
3. Admin panel for provider and payment settings
4. Token purchase area for YooKassa flow

### Tech stack

- `HTML`
- `CSS`
- `Vanilla JavaScript`
- `Polza AI API`
- `YooKassa UI draft flow`

### Run locally

Open `index.html` directly in a browser or start a simple local server:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173/
```
