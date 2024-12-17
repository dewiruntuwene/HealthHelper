# 🚀 Health Helper

**Health Helper** adalah sistem manajemen kesehatan modern berbasis teknologi **AI** yang membantu pengguna menjaga gaya hidup sehat. Sistem ini memungkinkan pengguna untuk berkonsultasi tentang **kesehatan**, **kalori makanan**, serta merencanakan **pola makan** dan **olahraga** dengan bantuan **LLM (Large Language Model)** berbasis **GPT-4o**.

🌐 **[Kunjungi Website Health Helper di sini](https://frontend-health-helper.vercel.app/)**  

---

## 📝 **Fitur Utama**

### 1. Konsultasi Kesehatan Interaktif 💬  
Pengguna dapat bertanya seputar informasi **kesehatan**, **nutrisi**, **kalori makanan**, dan **aktivitas olahraga** melalui sistem pesan yang didukung oleh **GPT-4o**.

### 2. Food Planner 🍎  
Memberikan saran **rencana pola makan harian atau mingguan** melalui pesan, yang nantinya akan ditampilkan di dashboard.

### 3. Exercise Planner 🏃‍♂️  
Memberikan saran **jadwal olahraga** yang sesuai dengan kebutuhan pribadi melalui pesan, yang akan tersimpan di dashboard sebagai **pengingat**.

### 4. Sistem Autentikasi Pengguna 🔐  
Fitur **registrasi** dan **login** memastikan **keamanan** dan **privasi data** pengguna.

### 5. Dashboard Pribadi 📊  
Semua **rencana pola makan** dan **jadwal olahraga** akan ditampilkan di dashboard agar mudah diakses dan dipantau oleh pengguna.

---

## 💻 **Teknologi yang Digunakan**

### **Frontend**  
- Framework: **Vue.js** **TypeScript** dengan **TaiwindCSS**  
- Deployment: **Vercel**  

### **Backend**  
- Framework: **Node.js** **Express.js** dengan **Prisma**  
- Deployment: **Vercel**  

### **Database**  
- **PostgreSQL** menggunakan **Supabase** sebagai layanan backend.  

### **AI & LLM**  
- Large Language Model: **GPT-4o**  

---

## 🛠️ **Arsitektur Sistem**

```mermaid
flowchart TD
    User -->|Interaksi| Frontend[Frontend (Vue.js + TypeScript)]
    Frontend -->|Permintaan/Respons| Backend[Backend (Node.js + Express.js)]
    Backend -->|Koneksi Data| Database[Database (Supabase)]
    Backend -->|Integrasi| GPT4o[GPT-4o (Large Language Model)]
