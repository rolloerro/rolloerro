# 👨‍⚕️ Владимир Копылов – Digital WM Core

Основатель **Digital WM Core** | Экстренная медицина и системы искусственного интеллекта

💬 «Код — это тоже инструмент реанимации, если он спасает человека».

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
🚀 Digital-WM Cloud Microservices Platform
██████╗ ██╗ ██████╗ ██╗████████╗ █████╗ ██╗     
██╔══██╗██║██╔════╝ ██║╚══██╔══╝██╔══██╗██║     
██████╔╝██║██║  ███╗██║   ██║   ███████║██║     
██╔═══╝ ██║██║   ██║██║   ██║   ██╔══██║██║     
██║     ██║╚██████╔╝██║   ██║   ██║  ██║███████╗
╚═╝     ╚═╝ ╚═════╝ ╚═╝   ╚═╝   ╚═╝  ╚═╝╚══════╝
     DIGITAL–WM CLOUD MICROSERVICES STACK

🛰 ⭐ Бейджи единой экосистемы
<p align="center"> <img src="https://img.shields.io/badge/Microservices-7-green?style=for-the-badge&logo=icloud" /> <img src="https://img.shields.io/badge/Cloud%20Native-Kubernetes-blue?style=for-the-badge&logo=kubernetes" /> <img src="https://img.shields.io/badge/Observability-Prometheus-orange?style=for-the-badge&logo=prometheus" /> <img src="https://img.shields.io/badge/Workers-Rust%2FTokio-orange?style=for-the-badge&logo=rust" /> <img src="https://img.shields.io/badge/REST-API-yellow?style=for-the-badge&logo=swagger" /> <img src="https://img.shields.io/badge/Webhooks-Ingestion-purple?style=for-the-badge&logo=webhooks" /> <img src="https://img.shields.io/badge/Security-API--Keys-red?style=for-the-badge&logo=security" /> </p>
🧩 Архитектурная диаграмма всей платформы
          ┌──────────────────────────────────────────┐
          │         Universal REST API Template       │
          │  (базовый REST-каркас: Kotlin/Rust/Ruby) │
          └──────────────────────────────────────────┘
                           │
                           ▼
     ┌────────────────────────────────────────────────────────────┐
     │                     API Gateway / Nginx                    │
     └────────────────────────────────────────────────────────────┘
                           │
     ┌───────────────┬───────────────┬─────────────────┬──────────┐
     ▼               ▼               ▼                 ▼          ▼
┌───────────┐  ┌──────────────┐  ┌───────────────┐  ┌──────────┐ ┌──────────┐
│ JSON Echo │  │ Webhook       │  │ APIKey Auth    │  │ File     │ │ Metrics  │
│ Service   │  │ Receiver      │  │ Service        │  │ Upload   │ │ Health   │
└───────────┘  └──────────────┘  └───────────────┘  └──────────┘ └──────────┘
                                   │
                                   ▼
                       ┌─────────────────────┐
                       │ Task Worker (Rust)  │
                       │ async jobs / queue  │
                       └─────────────────────┘

                     <All services monitored by Prometheus / Grafana>

🔥 Сверхкратко о каждом сервисе
Сервис	Роль
JSON Echo Service	Тестовый API для отладки сетей и прокси.
Webhook Receiver	Приём входящих вебхуков из внешних систем.
APIKey Auth Service	Проверка API-ключей, безопасность.
File Upload Service	Загрузка, валидация и хранение файлов.
Task Worker Template	Асинхронный воркер на Rust для тяжёлых задач.
Metrics Healthcheck Service	Метрики, liveness, readiness.
Universal REST API Template	База для создания новых сервисов.
🧭 Общая структура Digital-WM Cloud Stack
digital-wm-cloud/
 ├── universal-rest-api-template/
 ├── json-echo-service/
 ├── webhook-receiver/
 ├── apikey-auth-service/
 ├── file-upload-service/
 ├── task-worker-template/
 └── metrics-healthcheck-service/

Я разработал собственный Cloud Native-стек из 7 микросервисов, включая систему вебхуков, API-ключей, REST-каркас, сервис загрузки файлов, метрики и worker-движок на Rust.
Архитектура полностью совместима с Kubernetes, Prometheus и CI/CD.
Каждый сервис оформлен как самостоятельный production-ready репозиторий.

🚀 Digital-WM Cloud Microservices Platform

Набор из 7 production-ready микросервисов, которые формируют мою облачную архитектуру:

API-каркас

Webhook-ингестор

Авторизация по API-ключам

Загрузчик файлов

Асинхронный Rust-воркер

Метрики / здоровье

Базовые REST-шаблоны для любых новых сервисов

Архитектура полностью Cloud Native, совместима с:

✔ Kubernetes
✔ Prometheus / Grafana
✔ Docker
✔ CI/CD
✔ Event-Driven workflow
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

