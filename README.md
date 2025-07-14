# 📦 InfoTech Backend API

A secure and scalable backend API for the official InfoTech company website. Built with **FastAPI**, powered by **JWT authentication**, and connected to a relational database via **SQLAlchemy**.

---

## 🔧 Tech Stack

- ⚡ **FastAPI** – Modern, high-performance Python web framework
- 🛡️ **JWT Auth** – Secure login with token-based authentication
- 🗃️ **SQLAlchemy + SQLite** – ORM and lightweight database
- 📦 **Pydantic** – For request validation and response models
- 🌐 **CORS** – Enabled for frontend integration
- 🔄 **Swagger UI** – Auto-generated API docs at `/docs`

---

## 📁 Project Structure

infotech-website-backend/
├── main.py # FastAPI entry point
├── models.py # SQLAlchemy models
├── database.py # DB session and engine setup
├── requirements.txt # Dependencies
├── README.md


---

## 📦 Features

- ✅ User Signup and Login
- ✅ JWT Token Authentication
- ✅ Protected `/profile` route
- ✅ File Upload Endpoint
- ✅ Auto API docs via `/docs`
- ✅ Dark-mode-ready frontend integration

---

## 🧪 API Endpoints

| Method | Route         | Description           |
|--------|---------------|-----------------------|
| POST   | `/signup`     | Register new users    |
| POST   | `/login`      | Authenticate user, get token |
| GET    | `/profile`    | Protected, returns user info |
| POST   | `/upload`     | Upload file           |
| GET    | `/status`     | Health check          |

---

## 🛠️ Local Setup

```bash
git clone https://github.com/your-username/infotech-backend.git
cd infotech-backend
pip install -r requirements.txt
uvicorn main:app --reload

```

> 🔗 **Swagger docs available at**: [ http://127.0.0.1:8000/docs](#)  
