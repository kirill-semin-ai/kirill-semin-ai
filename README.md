# Кирилл Семин

Начинающий AI / LLM / ML Engineer. Интересуюсь машинным обучением, NLP, LLM, AI-агентами, локальными нейросетевыми системами и внедрением AI-моделей в реальные продукты.

Сейчас развиваюсь в направлении **Junior AI Engineer / Junior LLM Engineer / ML/NLP Intern**. Ищу стажировку, trainee-позицию или junior-задачи, где смогу расти в Python, ML, NLP, LLM, RAG, AI agents и MLOps/LLMOps.

---

## Портфолио

### JarvisCore — локальная AI-agent платформа

[Открыть проект](https://github.com/kirill-semin-ai/jarviscore-ai-agent-showcase)

JarvisCore — локальный AI-ассистент, построенный вокруг OpenAI-compatible API, OpenWebUI и локальных LLM-моделей.

Проект объединяет:

* диалоговый интерфейс;
* маршрутизацию пользовательских запросов;
* безопасное выполнение задач;
* чтение источников;
* память и контекст;
* smoke/regression tests;
* snapshot/rollback workflow;
* технические проверки состояния API, модели и очереди задач.

Проект показывает практический опыт проектирования AI-agent системы, интеграции локальных LLM, работы с API, тестирования поведения ассистента, контроля fake success и безопасного выполнения задач.

### AI Assistant Intent Classifier — ML/NLP intent classifier

[Открыть проект](https://github.com/kirill-semin-ai/ai-assistant-intent-classifier)

Небольшой ML/NLP-проект для классификации пользовательских команд AI-ассистента.

Проект использует:

* Python;
* pandas;
* scikit-learn;
* TF-IDF;
* Logistic Regression;
* train/test split;
* classification metrics;
* joblib.

Модель классифицирует пользовательские сообщения по интентам: обычный диалог, поиск информации, чтение источников, технические команды, AI-agent задачи и потенциально небезопасные запросы.

Текущий результат baseline-модели после расширения датасета:

* dataset: 120 labeled examples;
* accuracy: 0.833;
* macro avg F1-score: 0.83;
* weighted avg F1-score: 0.83.

---

## Что было реализовано в JarvisCore

* Локальный OpenAI-compatible API для взаимодействия с моделью через OpenWebUI.
* Интеграция локальных LLM через LM Studio.
* Маршрутизация запросов между обычным диалогом, source reader, safe execution и служебными режимами.
* Safe execution pipeline с dry-run, backup, apply, final verification и rollback-подходом.
* Source reader для чтения ссылок, формирования кратких сводок и сохранения карточек источников.
* Regression gates и smoke-tests для проверки стабильности ключевых сценариев.
* Технические отчёты, JSON-логи, readiness checks и command/status center.

---

## Стек и технологии

### AI / LLM

* Local LLMs
* LM Studio
* OpenWebUI
* OpenAI-compatible API
* Prompt engineering
* AI agents
* RAG basics
* Source reader

### ML / NLP

* Python для AI/ML-задач
* pandas
* scikit-learn
* TF-IDF
* Logistic Regression
* train/test split
* classification metrics
* базовая оценка качества модели

### Programming / Backend

* Python
* JSON
* CLI tools
* REST API basics
* PowerShell
* Git / GitHub

### Testing / Reliability

* Smoke tests
* Regression gates
* Snapshot / rollback workflow
* Structured reports
* API/model/queue checks
* Проверка fake success

---

## Что изучаю сейчас

* Python для AI/ML-задач
* NumPy, pandas, scikit-learn
* PyTorch
* NLP и Transformers
* RAG и AI agents
* FastAPI / REST API
* MLOps / LLMOps basics
* Тестирование и проверка качества AI-систем

---

## Ближайшие цели

* Развить AI Assistant Intent Classifier: добавить русскоязычные примеры, сравнение моделей и FastAPI endpoint.
* Добавить отдельный файл с результатами экспериментов для ML/NLP-проекта.
* Углубиться в PyTorch, Transformers, fine-tuning и оценку качества моделей.
* Подготовить резюме под стажировки и junior-позиции в AI/ML/NLP/LLM-направлении.
* Найти стажировку, trainee-позицию или junior-задачи, где можно развиваться в AI/ML/NLP.

---

## Контакты

* Email: [kurull630@gmail.com](mailto:kurull630@gmail.com)
* Telegram: @kirillSemin
