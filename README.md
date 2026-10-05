# Zalo Mini App - Fullstack Project

Dự án Zalo Mini App được tổ chức theo kiến trúc Fullstack:

```text
├── frontend/   # Zalo Mini App Client (React + TypeScript + Zalo SDK)
├── backend/    # Server API (REST API / Authentication / Database)
└── database/   # Database scripts (Schema, Migrations, Docker Compose)
```

## 🚀 Hướng dẫn khởi chạy

### 1. Frontend (Zalo Mini App)
```bash
cd frontend
npm install
npm start
```
* Xem trên Zalo Mini App Studio hoặc thiết bị thật qua QR Code.

### 2. Backend (Server API)
```bash
cd backend
# Cài đặt và khởi chạy server của bạn
```

## ⚙️ Cấu hình Môi trường (.env)
- **Frontend:** Copy `frontend/.env.example` thành `frontend/.env` và cấu hình `VITE_API_URL`.
- **Backend:** Copy `backend/.env.example` thành `backend/.env` và cấu hình Database, Zalo Secret Keys.
