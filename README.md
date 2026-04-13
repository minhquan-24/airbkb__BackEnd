# 🏡 AirBKB - Booking Platform (Fullstack)

A fullstack web application inspired by Airbnb, allowing users to browse, book, and manage rental properties.

---

# 🧩 System Architecture

```text
Frontend (Next.js)
        ↓
 REST API (Backend - Nest.js)
        ↓
   Database (SQL)
```

- Frontend handles UI/UX and user interactions  
- Backend handles API, authentication, and business logic  
- Database stores users, listings, bookings, and reviews  

---

# 🚀 Features

## 🖥️ Frontend
- Browse and search listings  
- View listing details  
- Booking interface  
- Authentication (Login/Register)  

---

## ⚙️ Backend
- RESTful API  
- Authentication & authorization  
- Listing management (CRUD)  
- Booking system  
- Role-based access (Host / Guest)  

---

# 🛠️ Tech Stack

## 🎨 Frontend
- Next.js  
- TailwindCSS  

## ⚙️ Backend
- Nest.js  
 
## 🗄️ Database
- MySQL  

---

# 🔗 API Overview

| Method | Endpoint        | Description        |
|--------|---------------|--------------------|
| POST   | /auth/login    | Login user         |
| POST   | /auth/register | Register user      |
| GET    | /listings      | Get listings       |
| POST   | /bookings      | Create booking     |

---

# ⚙️ Installation

## 1. Clone project

```bash
git clone https://github.com/tantailuong099-cloud/airbkb__FrontEnd.git
git clone https://github.com/tantailuong099-cloud/airbkb__BackEnd.git
```

---

## 2. Setup Backend

```bash
cd airbkb__BackEnd
npm install
npm start
```

---

## 3. Setup Frontend

```bash
cd airbkb__FrontEnd
npm install
npm start
```

---

# 🔄 Data Flow

1. User interacts with UI  
2. Frontend sends request  
3. Backend processes  
4. Database returns data  
5. Frontend renders UI  

---

# 👨‍💻 Author

- GitHub: https://github.com/minhquan-24

---

# ⭐ Support

Give this project a ⭐ if you like it!