Health Helper 🚀
Health Helper adalah sistem manajemen kesehatan modern berbasis teknologi AI yang membantu pengguna dalam menjaga gaya hidup sehat. Sistem ini memungkinkan pengguna untuk berkonsultasi tentang kesehatan, mengelola kalori makanan, serta merencanakan pola makan dan olahraga dengan bantuan LLM (Large Language Model) berbasis GPT-4o.

🌐 Kunjungi Website Health Helper di sini

Fitur Utama 📝
Konsultasi Kesehatan Interaktif

Pengguna dapat bertanya seputar informasi kesehatan, nutrisi, kalori makanan, dan aktivitas olahraga melalui sistem pesan yang didukung oleh GPT-4o.
Food Planner 🍎

Pengguna dapat membuat rencana pola makan harian atau mingguan melalui pesan yang nantinya ditampilkan di dashboard.
Exercise Planner 🏃‍♂️

Pengguna bisa membuat jadwal olahraga yang sesuai dengan kebutuhan pribadi, yang akan tersimpan di dashboard sebagai pengingat.
Sistem Autentikasi Pengguna 🔐

Fitur registrasi dan login memastikan keamanan dan privasi data pengguna.
Dashboard Pribadi 📊

Semua rencana pola makan dan jadwal olahraga akan ditampilkan di dashboard agar mudah diakses dan dipantau oleh pengguna.
Teknologi yang Digunakan 💻
Frontend
Framework: Vue.js dengan TypeScript
Deployment: Vercel
Backend
Framework: Node.js dengan Express.js
Deployment: Vercel
Database
PostgreSQL menggunakan Supabase sebagai layanan backend.
AI & LLM
Large Language Model: GPT-4o
Arsitektur Sistem 🛠️
scss
Copy code
User ↔ Frontend (Vue.js + TypeScript) ↔ Backend (Node.js + Express.js) ↔ Database (Supabase)  
     ↕  
GPT-4o (LLM Integration)
Frontend: Mengelola antarmuka pengguna (UI/UX) untuk interaksi dan tampilan data di dashboard.
Backend: Mengatur logika bisnis, integrasi GPT-4o, autentikasi, dan koneksi database.
Database: Menyimpan data pengguna, food planner, exercise planner, dan riwayat konsultasi.
GPT-4o: Memberikan respons cerdas dan interaktif melalui sistem pesan pengguna.
