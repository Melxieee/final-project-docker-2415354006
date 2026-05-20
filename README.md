# Laporan Hasil Praktikum: Final Project Aplikasi Berbasis Container

## Identitas Mahasiswa

- **Nama:** Moses Christian Adi
- **NIM:** 2415354006
- **Kelas/Rombel:** 4B TRPL
- **Tanggal Praktikum:** 20 Mei 2026

---

## Teknologi & Tools yang Digunakan

- **Sistem Operasi:** Mac OS Ventura
- **Containerization:** Docker & Docker Hub
- **Bahasa Pemrograman / Framework:** Node.js
- **Tools Lain:** VS Code, Git, Postman

---

## Langkah-Langkah Praktikum & Dokumentasi

## Langkah 1: Membuat Struktur Project Backend

Pada langkah ini dilakukan pembuatan struktur project backend menggunakan Node.js dan Express. Struktur project terdiri dari folder backend yang berisi file app.js, Dockerfile, package.json, dan node_modules.
**Dokumentasi/Screenshot:**
<img width="863" height="1025" alt="image" src="https://github.com/user-attachments/assets/0db0e398-bfe0-49c0-91d2-7fca23dc547f" />
<img width="717" height="520" alt="image" src="https://github.com/user-attachments/assets/ab390107-4d6a-49c7-9c62-95a3c99b8bde" />

## Langkah 2: Membuat File Environment Variable (.env)

Pada langkah ini dibuat file .env untuk menyimpan konfigurasi aplikasi dan database.
**Dokumentasi/Screenshot:**
<img width="801" height="480" alt="image" src="https://github.com/user-attachments/assets/93ee7cf1-fec0-4ade-ad95-fd78cbd1af5c" />

## Langkah 3: Membuat Backend API Express.js

Pada langkah ini dibuat backend API menggunakan Express.js dan MySQL2. API digunakan untuk operasi CRUD data users.Membuat app.js Backend menggunakan hostname mysql karena mysql adalah nama service pada Docker Compose.
Endpoint /users digunakan untuk mengambil data dari database MySQL.

**Dokumentasi/Screenshot:**
<img width="473" height="1051" alt="image" src="https://github.com/user-attachments/assets/07bd2db0-bc4c-4344-9869-171dc82ccb5b" />

## Langkah 4: Membuat Dockerfile

Pada langkah ini dibuat Dockerfile untuk melakukan containerization aplikasi backend Node.js.
**Dokumentasi/Screenshot:**
<img width="645" height="405" alt="image" src="https://github.com/user-attachments/assets/1656a96f-0071-40ab-a022-b97e8e62e186" />

## Langkah 5: Membuat Docker Compose

Pada langkah ini dibuat file docker-compose.yml untuk menjalankan multi-container application yang terdiri dari backend dan MySQL.
**Dokumentasi/Screenshot:**
<img width="767" height="1080" alt="image" src="https://github.com/user-attachments/assets/23cb5e94-8249-44ce-8205-efbb9e0d18d1" />

## Langkah 6: Menjalankan Docker Compose

Pada langkah ini dilakukan build dan menjalankan seluruh container menggunakan Docker Compose.
**Dokumentasi/Screenshot:**
<img width="1007" height="407" alt="image" src="https://github.com/user-attachments/assets/27a52425-b432-47ec-9f62-99a3a44e79cf" />

## Pengujian Praktikum

1. Pengujian Docker Compose, Volume, Network, Container
   
   **Pengujian Docker Compose**
   <img width="1918" height="1140" alt="image" src="https://github.com/user-attachments/assets/9c4c0883-6d97-45be-85e2-d0a334619ae1" />
   **Pengujian Docker Volume**
   <img width="1918" height="1135" alt="image" src="https://github.com/user-attachments/assets/50fb73b5-c327-4cee-aea2-f3b1e8bb92ae" />
   **Pengujian Container**
   <img width="1607" height="400" alt="image" src="https://github.com/user-attachments/assets/83cf5c9a-7dfa-4351-ac93-326c215fad92" />
   **Pengujian Network Docker**
   <img width="1918" height="1140" alt="image" src="https://github.com/user-attachments/assets/1c18a980-d597-4ed6-8aea-f190996536c5" />
   
2.⁠ ⁠⁠Pengujian Endpoint -> Request dan Response (Browser, Postman)

   **GET**
    <img width="1918" height="958" alt="image" src="https://github.com/user-attachments/assets/39481b2a-403f-476f-952c-521bbc769a7b" />
    **POST**
      <img width="1917" height="952" alt="image" src="https://github.com/user-attachments/assets/52c99b3c-c3e6-4900-a4c8-2c000296330b" />
     **PUT**
     <img width="1917" height="856" alt="image" src="https://github.com/user-attachments/assets/4d173aec-dbe6-455d-95df-1bb76b7dcab7" />
     **DELETE**
     <img width="1918" height="767" alt="image" src="https://github.com/user-attachments/assets/6f779577-c920-40f1-8b52-faa0b288fddd" />
     
⁠⁠3. Pengujian upload ke Docker Hub

   **Uji Docker HUB**
   <img width="1918" height="761" alt="image" src="https://github.com/user-attachments/assets/91a3be9a-9232-4ace-8d7e-63662b87af0e" />
   <img width="1918" height="1107" alt="image" src="https://github.com/user-attachments/assets/a28817a5-d0f9-41d5-8519-10b6b46e6faa" />
   
4. Pengujian Lainnya yang diperlukan
   
   **Docker Dekstop**
   <img width="1918" height="977" alt="image" src="https://github.com/user-attachments/assets/b96d221a-6eab-4e5e-8fea-1380e48ff1fd" />





   

   
