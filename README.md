# 🌀 RT FastAPI Application

A FastAPI-based backend application integrated with Request Tracker (RT), Sentry for monitoring, Slack for notifications, and a PostgreSQL database via SQLAlchemy. This app handles authentication, webhook events, ticket processing, and user management.

---

## 🚀 Features

- JWT-based authentication
- User creation and login with hashed passwords
- Secure admin user auto-creation at startup
- Slack webhook notifications on ticket creation
- Survey API callouts on ticket resolution
- Sentry integration for error monitoring
- SQLAlchemy ORM with PostgreSQL
- RT API integration to fetch ticket/user/group data

---

## 🧰 Tech Stack

- Python 3.10+
- FastAPI
- SQLAlchemy
- PostgreSQL
- Sentry SDK
- OAuth2 + JWT
- Docker & Docker Compose
- dotenv (`.env`) for config

---

## 📁 Project Structure

```bash
.
├── main.py              # Main FastAPI app
├── models.py            # SQLAlchemy models
├── schemas.py           # Pydantic schemas
├── database.py          # DB connection setup
├── security.py          # Auth, password hashing & token logic
├── rt/                  # RT integration module
├── .env                 # Environment variables
├── Dockerfile
├── docker-compose.yml
└── README.md
```
### Installation
