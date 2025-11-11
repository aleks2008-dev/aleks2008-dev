# 👋 Привет! Я Алекс - Python Backend Developer

![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104-green?style=flat-square&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue?style=flat-square&logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-Ready-blue?style=flat-square&logo=docker)

## 🚀 О себе

Разрабатываю backend приложения на Python с фокусом на **Clean Architecture** и современные технологии. Специализируюсь на создании API, интеграции с базами данных и разработке Telegram ботов.

## 🛠️ Технический стек

**Backend & API:**
- Python 3.12, FastAPI, SQLAlchemy
- PostgreSQL, Redis
- JWT Authentication, RBAC
- Async/await programming

**DevOps & Tools:**
- Docker, Docker Compose
- Git, GitHub Actions
- pytest для тестирования

**Telegram Development:**
- aiogram 3.x
- FSM (Finite State Machine)
- API интеграция

## 📊 Ключевые проекты

### 🏥 [Medical Management System](https://github.com/aleks2008-dev/medical-app-fastapi)
**Enterprise-level медицинская система с Clean Architecture**

- ⚡ **FastAPI** + **SQLAlchemy** + **PostgreSQL**
- 🏗️ **Clean Architecture** с полным разделением слоев
- 🔐 **JWT авторизация** с ролевой моделью
- 🐳 **Docker** контейнеризация
- ✅ **65 тестов** с полным покрытием
- 📊 **SOLID принципы** и паттерны проектирования

```python
# Пример Clean Architecture
class CreateAppointmentUseCase:
    def __init__(self, appointment_repo: AppointmentRepository):
        self.appointment_repo = appointment_repo
    
    async def execute(self, appointment_data: AppointmentCreate) -> Appointment:
        # Бизнес-логика создания записи
```

### 🤖 [Medical Telegram Bot](https://github.com/aleks2008-dev/medical-telegram-bot)
**Интерактивный бот для записи к врачам**

- 🎯 **aiogram 3.3** с FSM состояниями
- 📅 **Интерактивный календарь** для выбора даты
- 🔄 **API интеграция** с backend системой
- ⚡ **Async HTTP** клиент
- 💬 **FAQ система** с быстрыми ответами

```python
# Пример FSM состояний
class AppointmentStates(StatesGroup):
    choosing_doctor = State()
    choosing_date = State()
    choosing_time = State()
```

## 📈 GitHub статистика

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=aleks2008-dev&show_icons=true&theme=default&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aleks2008-dev&layout=compact&theme=default&hide_border=true)

## 🎯 Что умею

- ✅ Проектирование REST API с FastAPI
- ✅ Работа с базами данных (PostgreSQL, SQLAlchemy)
- ✅ Асинхронное программирование
- ✅ Clean Architecture и SOLID принципы
- ✅ Контейнеризация с Docker
- ✅ Написание тестов (pytest)
- ✅ Разработка Telegram ботов
- ✅ Git workflow и CI/CD

## 🔍 Ищу возможности

Открыт для позиций **Junior Python Developer** в компаниях, которые ценят:
- Качественный код и архитектуру
- Современные технологии
- Профессиональный рост

## 📫 Связаться со мной

- 📧 Email: [sansanhc2008@gmail.com](mailto:sansanhc2008@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- 🐱 GitHub: [@aleks2008-dev](https://github.com/aleks2008-dev)

---

⭐ **Интересные проекты? Ставьте звездочки!** ⭐