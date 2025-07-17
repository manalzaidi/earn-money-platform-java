
# Earn Money Platform (Java + HTML + CSS)

## 📁 Project Structure

- `frontend/` - HTML, CSS, JS for User & Admin UI
- `backend/` - Java Spring Boot API
- `database/` - MySQL schema and seed data

## 🧭 Deployment Instructions

### 🔹 FRONTEND (Netlify/Vercel)
1. Upload `frontend/` folder to Netlify or Vercel.
2. Set `index.html` as root entry.

### 🔹 BACKEND (Render/Railway)
1. Create a new Spring Boot service.
2. Connect GitHub repo or upload ZIP.
3. Add environment variables (DB config).
4. Deploy backend.

### 🔹 DATABASE (PlanetScale/MySQL)
1. Import `schema.sql` in MySQL.
2. Insert admin user:

```sql
INSERT INTO users (email, password, role) VALUES ('admin@admin.com', 'admin123', 'ADMIN');
```

## ✅ Admin Login
- Email: `admin@admin.com`
- Password: `admin123`

## 🎯 Features
- Sign up/Login
- Wallet with balance
- Recharge via UPI
- Levels & Plans
- Task (YouTube video rewards)
- Withdraw money
- Admin dashboard

Enjoy building 🚀
