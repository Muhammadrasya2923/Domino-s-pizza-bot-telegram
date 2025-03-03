# Domino's Pizza Duren Sawit Chatbot

Proyek ini bertujuan untuk mengembangkan chatbot cerdas berbasis Natural Language Processing (NLP) guna meningkatkan layanan pelanggan Domino’s Pizza di Duren Sawit. Chatbot ini dapat membantu pelanggan dengan memberikan informasi tentang menu, metode pembayaran, promo terbaru, dan detail pemesanan secara otomatis.

## Fitur
- **Menampilkan menu** – Memberikan daftar menu lengkap beserta harga.
- **Informasi promo** – Menampilkan promo terbaru yang tersedia.
- **Detail pemesanan** – Membantu pelanggan dalam proses pemesanan.
- **Metode pembayaran** – Memberikan informasi mengenai opsi pembayaran yang tersedia.
- **Dukungan Natural Language Processing (NLP)** – Memungkinkan chatbot memahami dan merespons pertanyaan pelanggan secara alami.

## Teknologi yang Digunakan
- **Python** – Bahasa pemrograman utama.
- **Telegram Bot API** – Untuk menghubungkan chatbot ke Telegram.
- **Dialogflow / Rasa** – Untuk implementasi NLP.
- **Flask / FastAPI** – Sebagai backend aplikasi.
- **SQLite / Firebase** – Untuk penyimpanan data.

## Instalasi dan Konfigurasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/dominos-chatbot.git
   cd dominos-chatbot
   ```
2. Buat virtual environment dan instal dependensi:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Untuk macOS/Linux
   venv\Scripts\activate     # Untuk Windows
   pip install -r requirements.txt
   ```
3. Konfigurasi variabel lingkungan:
   - Buat file `.env` dan tambahkan:
     ```
     TELEGRAM_BOT_TOKEN=your_telegram_bot_token
     DIALOGFLOW_PROJECT_ID=your_dialogflow_project_id
     DATABASE_URL=your_database_url
     ```
4. Jalankan aplikasi:
   ```bash
   python app.py
   ```

## Cara Menggunakan
- Buka Telegram dan cari chatbot Domino’s Pizza Duren Sawit.
- Ketik pertanyaan seperti "Apa saja menu yang tersedia?" atau "Ada promo apa hari ini?".
- Ikuti petunjuk chatbot untuk mendapatkan informasi lebih lanjut.

## Kontribusi
Kami menerima kontribusi dari siapa pun yang tertarik untuk mengembangkan proyek ini lebih lanjut. Silakan buat pull request atau buka issue untuk memberikan masukan.

## Lisensi
Proyek ini dirilis di bawah lisensi MIT. Silakan lihat file `LICENSE` untuk detail lebih lanjut.

---
**Kontak:** Jika ada pertanyaan atau kendala, silakan hubungi [email@example.com](mailto:email@example.com).
