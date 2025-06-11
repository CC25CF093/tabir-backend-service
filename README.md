# 🔐 Backend - Real-time Sign Language Detection

Backend ini berfungsi untuk menangani autentikasi pengguna dan manajemen token (access dan refresh token) yang digunakan pada aplikasi **TaBir: Real-time Sign Language Detection**.

Aplikasi frontend akan terhubung ke backend ini untuk melakukan proses login, refresh token, dan logout. Sistem ini dibangun menggunakan **Hapi.js** dan dideploy menggunakan **Railway**.

---

## ⚙️ Tech Stack

- **Hapi.js** – Framework Node.js untuk membangun RESTful API yang modular dan scalable.
- **JWT (JSON Web Token)** – Digunakan untuk mengelola sistem autentikasi dengan access token dan refresh token.
- **PostgreSQL** – Database utama untuk menyimpan data pengguna.
- **Railway** – Platform deployment yang simpel dan cepat untuk backend.
- **MobileNetV2 (TensorFlow.js)** – Model machine learning ringan yang digunakan di sisi frontend untuk mendeteksi gesture bahasa isyarat secara efisien dan real-time.

---
