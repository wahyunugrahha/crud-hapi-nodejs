# Project Front-End Notes App Back-End Fundamentals

Aplikasi catatan sederhana dengan front-end dan back-end yang terpisah, dibangun menggunakan Node.js dan npm.

## Struktur Proyek

Proyek ini terdiri dari dua direktori utama:

- `nama-direktori-frontend/`: Berisi kode untuk antarmuka pengguna (front-end).
- `nama-direktori-backend/`: Berisi kode untuk logika sisi server (back-end).

Pastikan Anda menjalankan perintah di direktori yang sesuai.

## Prasyarat

- **Node.js**: Versi 16.x atau yang lebih baru (termasuk npm).

## Instalasi

### 1. Instalasi Backend

a. **Masuk ke direktori backend**:
`bash
       cd notes-app-backend-1
       `
b. **Instal Dependensi Backend**:
`bash
       npm install
       `

### 2. Instalasi Frontend

a. **Masuk ke direktori frontend**:
(Dari direktori root proyek)
`bash
       cd notes-app-frontend-1
       `
b. **Instal Dependensi Frontend**:
`bash
       npm install
       `

## Menjalankan Proyek

### 1. Menjalankan Backend

a. **Pastikan Anda berada di direktori backend**:
`bash
       # Jika belum, navigasi ke:
       # cd path/ke/notes-app-backend-1
       `
b. **Jalankan Server Backend**:
`bash
       npm run start
       `
Server backend akan berjalan (misalnya di `http://localhost:PORT_BACKEND`).

### 2. Menjalankan Frontend (Produksi)

a. **Pastikan Anda berada di direktori frontend**:
`bash
       # Jika belum, navigasi ke:
       # cd path/ke/notes-app-frontend-1
       `
b. **Build Proyek Frontend**:
`bash
       npm run build
       `
c. **Jalankan Server Frontend (atau layani file hasil build)**:
Perintah ini mungkin berbeda tergantung bagaimana frontend Anda di-deploy setelah build. Bisa jadi `npm run start` jika ada server produksi untuk frontend, atau Anda mungkin perlu melayani direktori `build`/`dist` secara manual.
`bash
       npm run start
       `
Aplikasi frontend akan berjalan (misalnya di `http://localhost:PORT_FRONTEND`).

## Skrip Utama NPM (Per Direktori)

Setiap direktori (frontend dan backend) akan memiliki file `package.json` sendiri dengan skrip berikut (atau serupa):

### Untuk Backend (`notes-app-backend-1/`):

- `npm install`: Instal dependensi backend.
- `npm run start`: Jalankan server backend.
- `(Opsional) npm run dev`: Jalankan server backend dalam mode pengembangan.

### Untuk Frontend (`notes-app-frontend-1/`):

- `npm install`: Instal dependensi frontend.
- `npm run build`: Build proyek frontend untuk produksi.
- `npm run start`: Jalankan server produksi frontend (jika ada).
- `(Opsional) npm run dev`: Jalankan frontend dalam mode pengembangan.

---

_Ganti `<URL_REPOSITORI_ANDA>`, `nama-direktori-frontend`, `nama-direktori-backend`, `PORT_FRONTEND`, dan `PORT_BACKEND` sesuai dengan proyek Anda._
_Pastikan untuk menyesuaikan perintah `npm run start` untuk frontend jika cara menjalankannya setelah build berbeda._
