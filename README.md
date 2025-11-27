# 👨‍⚕️ Владимир Копылов – Digital WM Core

Основатель **Digital WM Core** | Экстренная медицина и системы искусственного интеллекта

💬 «Технология становится инструментом только в руках того, кто помогает людям».

---

## 🌐 Цифровая экосистема WM

| Направление | Суть | Технологии |
|-------------|------|------------|
| 🩺 **ФДТ / PDT** | Фотодинамическая терапия и моделирование проявлений | Python, LangChain, OpenAI API |
| 🚨 **СМП / EMS** | Экстренные алгоритмы и медицинские протоколы | Node.js, TypeScript, Telegraf |
| 💬 **PANIC** | Офлайн-боты и помощники при панических атаках | Kotlin, C#, Flutter |

---

## 🧩 Проекты и боты

### 🩺 ФДТ / PDT Tools & Bots

| Проект / Бот | Описание | Ссылка |
|--------------|----------|--------|
| **OpenPDT Toolkit** | Планирование, моделирование и оптимизация ФДТ | [GitHub](https://github.com/rolloerro/openpdt-toolkit) |
| **PDT-LightSim** | Симулятор распространения света | [GitHub](https://github.com/rolloerro/pdt-lightsim) |
| **PDT-Kinetics-Library** | Моделирование кинетики фотосенсибилизаторов | [GitHub](https://github.com/rolloerro/pdt-kinetics) |
| **PDT Clinical Assistant Bot** | Англоязычный бот по ФДТ | [GitHub](https://github.com/rolloerro/PDT-Clinical-Assistant-Bot) |
| **fdtcalc01_bot** | Расчёт мощности лазера, дозы, времени экспозиции | [Telegram](https://t.me/fdtcalc01_bot) |
| **radapharma_bot** | Информационно-обучающий бот по препарату Радахлорин | [Telegram](https://t.me/radapharma_bot) |
| **CG-carcinoma_bot** | Алгоритмы для врачей при онкологических случаях | [Telegram](https://t.me/CG_carcinoma_bot) |
| **fdtliason_bot** | Вспомогательный бот для клинической поддержки | [Telegram](https://t.me/fdtliason_bot) |
| **fdt_urolog_bot2** | Помощник по урологическим протоколам ФДТ | [Telegram](https://t.me/fdt_urolog_bot2) |
| **fdtauro_bot** | Поддержка ФДТ при урологических и гинекологических задачах | [Telegram](https://t.me/fdtauro_bot) |
| **fdt_ginecolog_bot** | Клинические сценарии для гинекологии | [Telegram](https://t.me/fdt_ginecolog_bot) |
| **fdt_assessment_bot** | Оценка эффективности ФДТ | [Telegram](https://t.me/fdt_assessment_bot) |
| **FDT_CalcBot** | Расчёт дозы, времени и мощности для ФДТ | [Telegram](https://t.me/FDT_CalcBot) |

---

### 🚨 СМП / EMS Bots

| Проект / Бот | Описание | Ссылка |
|--------------|----------|--------|
| **stepspeedhelp_bot** | Алгоритмы экстренной помощи | [GitHub](https://github.com/rolloerro/stepspeedhelp_bot) |
| **Drug_poisoning_bot** | Алгоритмы при отравлениях | [GitHub](https://github.com/rolloerro/Drug_poisoning_bot) |

---

### 💬 PANIC / Offline Helpers

| Проект / Бот | Описание | Ссылка |
|--------------|----------|--------|
| **PANIC Offline** | Самопомощь при панических атаках (MVP) | [GitHub](https://github.com/rolloerro/PANIC-Offline) |

---
☁️ Digital-WM Cloud Microservices Platform
Production-ready Cloud Native архитектура из 7 сервисов

Я создаю собственную облачную инфраструктуру на основе микросервисов — для медицинских ботов, AI-модулей, обработчиков вебхуков, асинхронных задач и мониторинга.
Стек полностью совместим с Kubernetes, Docker, Prometheus и CI/CD.

🔧 Технологии

Kotlin · Rust · Ruby · Node.js · Docker · Kubernetes · Prometheus · Grafana · OpenAPI

🧩 Сервисы экосистемы
Сервис	Описание
Universal REST API Template	База для создания быстрых продакшен-микросервисов.
JSON Echo Service	Тестовый API для дебага прокси, сетей, логов и клиентов.
Webhook Receiver	Приём и маршрутизация вебхуков из Telegram, CRM, AI-систем.
APIKey Auth Service	Генерация, валидация и безопасность API-ключей.
File Upload Service	Загрузка, валидация и обработка файлов.
Task Worker Template (Rust)	Асинхронный worker для тяжёлых задач и очередей.
Metrics & Healthcheck Service	Метрики / здоровье / readiness для Kubernetes.
🛰 Архитектура платформы
          API Gateway
               ↓
   ┌──────────────────────────┐
   │ Universal REST Template  │
   └──────────────────────────┘
               ↓
 ┌────────┬─────────┬─────────┬──────────┐
 │ JSON   │ Webhook │ APIKey  │ File     │
 │ Echo   │ Receiver│ Auth    │ Upload   │
 └────────┴─────────┴─────────┴──────────┘
               ↓
        Rust Task Worker
               ↓
        Metrics + Health

🏷 Бейджи Cloud Native
<p align="left"> <img src="https://img.shields.io/badge/Kubernetes-Ready-blue?style=for-the-badge&logo=kubernetes" /> <img src="https://img.shields.io/badge/Prometheus-Metrics-orange?style=for-the-badge&logo=prometheus" /> <img src="https://img.shields.io/badge/Docker-Compose-blue?style=for-the-badge&logo=docker" /> <img src="https://img.shields.io/badge/Rust-Workers-orange?style=for-the-badge&logo=rust" /> <img src="https://img.shields.io/badge/CI/CD-GitHub_Actions-black?style=for-the-badge&logo=githubactions" /> </p>
🎤 

Я разрабатываю собственную Cloud Native платформу из 7 микросервисов: от рецепторов вебхуков и API-ключей до Rust-воркеров, загрузчиков файлов и сервисов метрик. Это ядро цифровой инфраструктуры для моих медицинских AI-проектов и ботов. Архитектура совместима с Kubernetes, Docker, Prometheus и CI/CD.
---

## ⚙️ Технологический стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,nodejs,js,kotlin,cs,flutter,docker,postgres,redis,tensorflow,pytorch,openai,github,tailwind,react&theme=dark" />
</p>

<p align="center">🧩 От кода — к клинической практике.<br/>⚙️ От медицинского алгоритма — к цифровому протоколу спасения.</p>

---

### 📊 GitHub статистика

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rolloerro&show_icons=true&count_private=true&theme=radical&hide_border=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rolloerro&theme=radical&hide_border=true" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rolloerro&layout=compact&theme=radical&hide_border=true" width="48%"/>
  <img src="https://github-profile-trophy.vercel.app/?username=rolloerro&theme=onedark&row=1&column=4" width="48%"/>
</p>

---

---

## 🧬 ФДТ Расчёты (пример)

Примеры формул и областей применения:
```text
Dose (J/cm²) = Power (W) × Time (s) / Spot Area (cm²)


