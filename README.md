# NEXUS-CLI

# Nexus Network Testnet II - Kontribusi via CLI

## 📌 Pendahuluan
Nexus Network Testnet II memungkinkan kamu berkontribusi dengan menyediakan sumber daya komputasi melalui CLI.

## 🔧 Instalasi & Konfigurasi

### 1️⃣ Install Rust
Jalankan perintah berikut di terminal:
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Tambahkan target `riscv32i`:
```bash
rustup target add riscv32i-unknown-none-elf
```

### 2️⃣ Install Nexus Network CLI
Gunakan skrip instalasi cepat:
```bash
curl https://cli.nexus.xyz/ | sh
```

### 3️⃣ Setup & Konfigurasi
Jalankan CLI pertama kali:
```bash
nexus-cli
```
- Terima **Terms of Use**.
- Pilih mode proving:
  - **Linked Proving (Rekomendasi)**: Hubungkan akun di [app.nexus.xyz](https://app.nexus.xyz) agar bisa mendapatkan **NEX Points**.
  - **Anonymous Proving**: Kontribusi tanpa akun, tetapi tidak mendapatkan **NEX Points**.

## 🚀 Jalankan Node & Berkontribusi
Setelah konfigurasi selesai, jalankan perintah berikut:
```bash
nexus-cli start
```
Perintah ini akan memulai proses kontribusi komputasi ke Nexus Network.

## 📊 Cek Status & Monitoring
- Untuk melihat status node:
  ```bash
  nexus-cli status
  ```
- Untuk melihat leaderboard dan poin yang diperoleh, kunjungi [app.nexus.xyz](https://app.nexus.xyz).

---
✅ **Sekarang kamu siap untuk berkontribusi ke Nexus Network!** 🚀
