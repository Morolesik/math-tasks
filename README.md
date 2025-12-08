# MathTasks — Educational Platform for Kids

MathTasks is a small educational platform for publishing math problems for children and tracking their learning progress.  
The project is built as a backend service with a simple web interface and API.

This project is part of my Go developer portfolio.

---

## 🧩 Features

- Create, edit, and delete math tasks (full CRUD)
- Difficulty levels: easy, medium, hard
- Task classification by school grade (1–12)
- REST API for managing tasks
- Simple web interface (planned)
- (Planned) Telegram bot integration for sending daily tasks
- (Planned) User accounts and progress tracking

---

## 🛠️ Technologies

- Language: **Go**
- Framework: **Buffalo**
- Database: **PostgreSQL**
- API style: **REST**
- Other: **Docker**, **docker-compose**

---

## 🗄️ Data Model (Task)

Each task contains:

- `id` — unique identifier
- `title` — short task title
- `description` — full problem description
- `solution` — correct answer or explanation
- `difficulty` — `easy | medium | hard`
- `grade` — school grade (1–12)
- `created_at`
- `updated_at`

---

## 🚀 How to Run (Local Development)



