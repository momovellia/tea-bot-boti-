# tea-bot-boti-

## Instalasi
Ikuti langkah-langkah berikut untuk menginstal dan menjalankan skrip:

### 1. Clone Repository
```sh
git clone https://github.com/yogiprayoga1313/Tea-auto.git
cd Tea-auto
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Konfigurasi Private Key
edit `.env` tambahkan private key Ethereum Anda:
```sh
PRIVATE_KEY=your_private_key_here
```
**Peringatan:** Jangan pernah membagikan private key Anda kepada siapa pun!

### 4. Menjalankan Skrip
Jalankan salah satu perintah berikut untuk menjalankan skrip:

- **Kirim token ke alamat-alamat yang ditentukan:**
  ```sh
  node index.js
  ```

- **Menggunakan skrip tambahan (`sendTokenpengguna.js`) untuk mengirim ke pengguna yang telah terdaftar:**
  ```sh
  node sendTokenCreatedUser.js
  ```

## Catatan
- Pastikan akun Ethereum yang digunakan memiliki saldo TEA yang cukup untuk mengirim airdrop.
- Gunakan skrip ini dengan bijak dan hanya pada alamat yang benar.
- Mengirimkan 0.01 TEA

Jika ada pertanyaan atau kendala, silakan buka *issue* di repository ini. 🚀
