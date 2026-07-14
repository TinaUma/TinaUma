# Привет, я Тина Юмашева 👋

[![QA Portfolio](https://img.shields.io/badge/QA_Portfolio-qa--portfolio-2ECC71?style=flat&logo=checkmarx&logoColor=white)](https://github.com/TinaUma/qa-portfolio)
[![Telegram](https://img.shields.io/badge/Telegram-@tina__yuma-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/tina_yuma)
[![GitHub](https://img.shields.io/badge/GitHub-TinaUma-181717?style=flat&logo=github)](https://github.com/TinaUma)

Архитектор по образованию → AI-разработчик по практике → **QA Engineer по выбору**.

Тестирую продукты так, как это редко делают на старте карьеры: понимая, что происходит под капотом — от API-контракта и SQL-запроса до логов бэкенда. Ищу позицию **Junior QA Engineer**.

---

## 🎯 QA Engineering — основной фокус

→ **[Полное портфолио: qa-portfolio](https://github.com/TinaUma/qa-portfolio)**

Флагманский кейс: сквозное тестирование одного флоу (регистрация/авторизация) на 5 архитектурных слоях подряд — UI → API → база данных → логи backend → мобильный веб/PWA.

- **14 задокументированных дефектов** (2 Critical/Blocker, 5 Major, 7 Minor) — каждый подтверждён минимум двумя независимыми источниками доказательств, не предположением
- **Пример многослойного расследования:** один и тот же тестовый ввод вскрыл два разных бага в разных слоях — симптом на UI и архитектурную первопричину в коде — наглядно, почему нельзя тестировать только через интерфейс
- **Инструменты:** Chrome DevTools (Network + Device Mode), Postman, DBeaver/SQL, `docker compose logs` + `grep`, Android Studio + Logcat, Lighthouse
- **Методология:** тест-анализ (классы эквивалентности, граничные значения), чек-листы, регрессия, exploratory-тестирование по чартеру, баг-репорты в стандартном формате (Severity/Priority/Steps/Evidence)

---

## ⚡ Технический бэкграунд как УТП

Большинству junior-специалистов в QA продукт виден только снаружи. Я до QA собирала full-stack продукты сама — от идеи до публичного деплоя — и это меняет то, как я тестирую:

- Понимаю, что REST API, БД и Docker-инфраструктура значат **для разработчика**, поэтому вижу, где именно и почему что-то может сломаться — не просто иду по чек-листу вслепую
- 10+ продуктов в проде: FastAPI, React/Next.js, PostgreSQL, Docker, интеграции LLM API (Claude, OpenAI, Groq) — реальный стек, с которым буду сталкиваться, тестируя AI-продукты
- Комфортно использую AI-инструменты в рабочем процессе — не как замену суждению, а как ускоритель, при этом умею проверить и объяснить то, что они выдают, а не слепо доверять
- Архитектурное образование (МАРХИ) — структурное мышление и внимание к деталям, перенесённое из проектирования зданий в проектирование тест-кейсов

---

## 🗂 Избранные проекты (полный стек — построено и продакшн-задеплоено)

**[SignDrop](https://github.com/TinaUma/signdrop)** — инструмент наложения подписи на PDF/JPEG/PNG, полностью локально. FastAPI + React + Docker + Tauri (Windows .exe), публичный деплой.

**[VisionStyle](https://github.com/TinaUma/VisionStyle)** — анализатор визуального стиля по фото через Claude Vision API. FastAPI + Next.js, HuggingFace-деплой.

**[VoiceScribe](https://github.com/TinaUma/voicescribe)** — Telegram-бот транскрипции голоса через Groq Whisper API, 30 pytest-тестов.

**[h3llo-vpn-demo](https://github.com/TinaUma/h3llo-vpn-demo)** — переиспользуемый инфраструктурный контейнер (Docker, healthcheck, алерты).

→ Остальные проекты и полный стек-лист — на [tinacodes.space](https://tinacodes.space)

---

## 🎨 Дизайн-бэкграунд

Высшее образование — Московский Архитектурный Институт (МАРХИ). UI/UX-дизайн: Figma, Photoshop, Procreate. Дизайн-мышление как часть подхода к тестированию — вижу продукт и с точки зрения пользователя, и с точки зрения его структуры.
