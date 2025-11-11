# 👋 Hi! I'm Alex - Python Backend Developer

![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104-green?style=flat-square&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue?style=flat-square&logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-Ready-blue?style=flat-square&logo=docker)

## 🚀 About Me

I develop backend applications in Python with a focus on **Clean Architecture** and modern technologies. I specialize in API development, database integration, and Telegram bot development.

## 🛠️ Tech Stack

**Backend & API:**
- Python 3.12, FastAPI, SQLAlchemy
- PostgreSQL, Redis
- JWT Authentication, RBAC
- Async/await programming

**DevOps & Tools:**
- Docker, Docker Compose
- Git, GitHub Actions
- pytest for testing

**Telegram Development:**
- aiogram 3.x
- FSM (Finite State Machine)
- API integration

## 📊 Key Projects

### 🏥 [Medical Management System](https://github.com/aleks2008-dev/medical-app-fastapi)
**Enterprise-level medical system with Clean Architecture**

- ⚡ **FastAPI** + **SQLAlchemy** + **PostgreSQL**
- 🏗️ **Clean Architecture** with complete layer separation
- 🔐 **JWT authentication** with role-based access control
- 🐳 **Docker** containerization
- ✅ **65 tests** with comprehensive coverage
- 📊 **SOLID principles** and design patterns

```python
# Clean Architecture Example
class CreateAppointmentUseCase:
    def __init__(self, appointment_repo: AppointmentRepository):
        self.appointment_repo = appointment_repo
    
    async def execute(self, appointment_data: AppointmentCreate) -> Appointment:
        # Business logic for appointment creation
```

### 🤖 [Medical Telegram Bot](https://github.com/aleks2008-dev/medical-telegram-bot)
**Interactive bot for medical appointments**

- 🎯 **aiogram 3.3** with FSM states
- 📅 **Interactive calendar** for date selection
- 🔄 **API integration** with backend system
- ⚡ **Async HTTP** client
- 💬 **FAQ system** with quick replies

```python
# FSM States Example
class AppointmentStates(StatesGroup):
    choosing_doctor = State()
    choosing_date = State()
    choosing_time = State()
```

## 📈 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=aleks2008-dev&show_icons=true&theme=default&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aleks2008-dev&layout=compact&theme=default&hide_border=true)

## 🎯 Skills & Expertise

- ✅ REST API design with FastAPI
- ✅ Database work (PostgreSQL, SQLAlchemy)
- ✅ Asynchronous programming
- ✅ Clean Architecture & SOLID principles
- ✅ Docker containerization
- ✅ Testing with pytest
- ✅ Telegram bot development
- ✅ Git workflow & CI/CD

## 🔍 Looking for Opportunities

Open to **Junior Python Developer** positions at companies that value:
- Quality code and architecture
- Modern technologies
- Professional growth

## 📫 Contact Me

- 📧 Email: [sansanhc2008@gmail.com](mailto:sansanhc2008@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- 🐱 GitHub: [@aleks2008-dev](https://github.com/aleks2008-dev)

---

⭐ **Interesting projects? Give them a star!** ⭐