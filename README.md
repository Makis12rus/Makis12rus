<h1 align="center">⚡ Максим Щеглов</h1>
<p align="center">
  <a href="#">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=00E050&center=true&vCenter=true&width=800&lines=AI-Native+Python+%26+Automation+Engineer;Multi-Agent+Systems+Architect;RAG+%26+High-Load+Data+Pipelines;PySide6+%26+Desktop+Automation" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://t.me/makis_tlg"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:shcheglov.max@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://alion.io/user/maksim-shcheglov"><img src="https://img.shields.io/badge/Alion--Профиль-Verified_Talent-00E050?style=for-the-badge" /></a>
</p>

<p align="center">
  <i>Проектирование отказоустойчивых ИИ-агентов, RAG-архитектур, асинхронных бэкендов и десктоп-систем на PySide6.</i>
</p>

<p align="center">
  <a href="#">
    <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,docker,git,linux,js,vscode,pycharm&perline=10" />
  </a>
</p>

---

### 🧠 Стек технологий и ИИ-экосистема

| Категория | Технологии и инструменты |
| :--- | :--- |
| **ИИ и LLM Оркестрация** | `LiteLLM Proxy` `PostgreSQL + pgvector` `Qwen Embeddings` `RAG` `AI Agents` `n8n` `Prompt Engineering` |
| **ИИ-воркфлоу и IDE** | `Claude Code` `Cursor` `Windsurf` `DeepSeek V3/R1` `ChatGPT` `Google AI Studio` `Google Gemini` |
| **Бэкенд и Автоматизация** | `Python 3.12+` `FastAPI` `Asyncio` `PostgreSQL` `Redis` `Docker` `Docker Compose` |
| **Парсинг и Стелс-защита** | `Playwright` `Patchright` `Selenium` `curl_cffi (WAF Bypass)` `BeautifulSoup4` `pydantic` |
| **Десктоп-разработка** | `PySide6` `PyQt6` `WinAPI (ctypes)` `Windows Credential Manager` `Компиляция Nuitka` |
| **Web3 и Инфраструктура** | `Web3.py` `Ethereum` `Gost SOCKS5` `Chisel WebSocket Tunnels` `Linux / WSL2` |

---

### 🏛️ Главные архитектурные проекты

#### 🤖 1. J.A.R.V.I.S. — Мульти-агентный ИИ-каркас
* **Архитектура:** Модульная экосистема с изоляцией личностей (Юрист, Рекрутер, Маркетолог, Оркестратор), развернутая в WSL2 с локальным GPU-инференсом.
* **Стек технологий:** `Python`, `AI Agents`, `LiteLLM`, `PostgreSQL + pgvector`, `Redis`, `Patchright`, `RAG`.
* **Ключевые фичи:** Гибридный RAG-поиск (Qwen 1024d векторы + FTS), каскадные фоллбэки моделей и трансляция мыслей `<tg-thinking>` в Telegram Rich Messages.

#### 🏛️ 2. GOSTorgi — Высоконагруженная AI-платформа мониторинга госзакупок
* **Архитектура:** Асинхронная сервисная система для круглосуточного сбора и ИИ-анализа государственных торгов 24/7.
* **Стек технологий:** `Python`, `FastAPI`, `Asyncio`, `PostgreSQL (JSONB/GIN)`, `LLM`, `curl_cffi`, `Docker`.
* **Ключевые фичи:** Стелс-обход WAF-защит, автоматическое извлечение сущностей из документов через LLM, DaaS Export API с Zero-Memory потоками (CSV/Parquet) и паттерн Atomic Outbox.

#### 🛠️ 3. Python Script Compiler — Оболочка компилятора Nuitka
* **Архитектура:** Десктопная IDE-среда для компиляции Python-скриптов в нативные исполняемые файлы (.exe).
* **Стек технологий:** `Python`, `PyQt6`, `AST-анализ`, `Asyncio`, `PowerShell Bridge`, `WinAPI`.
* **Ключевые фичи:** Кастомный рендеринг QPainter Glassmorphism, 6-шаговый Мастер состояний (State Machine), статический AST-анализ кода и автоматическая цифровая подпись Windows.

#### ⚙️ 4. Dobrynya AI Helper — Стейтфул ИИ-ассистент
* **Архитектура:** Отказоустойчивый мультимодельный Telegram-помощник с микросервисной оркестрацией.
* **Стек технологий:** `n8n v2.27.4`, `LiteLLM Proxy`, `PostgreSQL`, `Redis`, `Docker Compose`.
* **Ключевые фичи:** Паттерн Planner-Synthesizer, автоматический фоллбэк между 25+ LLM-моделями и асинхронная компрессия контекста Hybrid Rolling Summary.

#### 📊 5. PDF Editor — Высокопроизводительный парсер таблиц
* **Архитектура:** Многопроцессорный потоковый ETL-конвейер для обработки PDF-документов объемом 10 000+ страниц.
* **Стек технологий:** `Python 3.13+`, `Multiprocessing`, `Dual-Engine (pdfplumber / C-engine)`, `ETL`.
* **Ключевые фичи:** Потоковая Micro-batching обработка страниц без утечек ОЗУ (OOM), атомарные WAL-чекпоинты (`.progress.json`) и изолятор ошибок в карантин (DLQ / `rejected_rows.csv`).

#### 🔒 6. ADSProfile Manager & NetTool — Десктопные комплексы автоматизации
* **Архитектура:** Модульные PySide6 приложения для автоматизации антидетект-браузеров и прозрачного сетевого проксирования.
* **Стек технологий:** `PySide6`, `Selenium`, `ZeroMQ (IPC)`, `WinAPI`, `Windows Credential Manager`.
* **Ключевые фичи:** Сканирование Shadow DOM, JS-эмуляция ввода React, шифрование оперативной памяти (AES-GCM) и Watchdog-контроль интерфейса.

---

### 📊 Телеметрия GitHub

<p align="center">
  <a href="#">
    <img src="https://streak-stats.demolab.com?user=Makis12rus&theme=dark&hide_border=true" />
  </a>
</p>
<p align="center">
  <a href="#">
    <img src="https://img.shields.io/github/followers/Makis12rus?label=Подписчики&style=for-the-badge&color=00E050&logo=github" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/github/stars/Makis12rus?label=Звезды&style=for-the-badge&color=FFD700&logo=github" />
  </a>
</p>
