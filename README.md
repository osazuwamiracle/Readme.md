# 🎓 Postgraduate Result System

A complete web system for Postgraduate Result & CGPA Management.

Built by **Nícholas H O Okunwe**

## ✨ Features

- ✅ GPA & CGPA Calculator (Public - no login needed)
- ✅ Admin / Lecturer Login
- ✅ Student Login (Students see ONLY their own result)
- ✅ Add Students + Auto-create Student Login (Reg No / DOB)
- ✅ Enter Results per Semester
- ✅ Automatic Transcript + Classification (Distinction / Merit / Credit / Pass)
- ✅ Download Transcript as Excel
- ✅ Permanent PostgreSQL Database (Render)
- ✅ Automatic Nightly Backup to Email (11 PM)
- ✅ Manual Backup Download

## 🔐 Demo Logins

| Role | Login Link | Username | Password |
| :--- | :--- | :--- | :--- |
| **Admin** | `/login` | `admin` | `admin123` |
| **Lecturer** | `/login` | `lecturer` | `lecturer123` |
| **Student** | `/student/login` | `Reg No` | `DOB without dashes` |

Example Student: Reg No `PG/TEST/001` / Password `20000515` (if DOB is 15 May 2000)

## 🚀 Live Demo

**Live Link:** https://pg-result-system.onrender.com

- Staff: `/login`
- Student: `/student/login`
- CGPA: `/cgpa`

## 🛠️ Run Locally

```bash
pip install -r requirements.txt
python app.py
