# Aplikasi-Chatbot-Restoran-WhatsApp

**Project Latihan Mandiri Pembuatan Aplikasi Chatbot Restoran Untuk WhatsApp Berbasis Python Dengan Flask dan Twilio sebagai API untuk menyambungkan chatbot kita dengan layanan WhatsApp.**

Dalam proyek ini, kita membangun chatbot yang dapat membantu pelanggan dalam melakukan interaksi dengan pihak restoran secara otomatis melalui WhatsApp. Kita di sini menggunakan Flask untuk sebagai API Backend dari bot untuk menyambungkan bot kita ke server dan Twilio untuk menyambungkan bot dan server kita ke bot Twilio yang ada di WhatsApp. Dalam implementasi ini, chatbot ini dirancang untuk mampu merespons berbagai pertanyaan pelanggan secara real-time, seperti menampilkan menu, menanyakan rekomendasi makanan berdasarkan hari dan mood, hingga memberikan informasi terkait jam operasional restoran. Dengan integrasi antara Flask dan Twilio, setiap pesan yang masuk dari pelanggan melalui WhatsApp akan diteruskan ke server Flask, diproses oleh logika bot, dan kemudian dikembalikan ke pelanggan melalui platform Twilio.



## GET STARTED

Untuk memulai aplikasi chatbot ini, ada beberapa langkah-langkah yang harus dilakukan.

**1. Install Flask di folder chatbot_engine sebagai folder dari mesin chatbotnya**

Untuk menginstall Flask di folder chatbot_engine ini, bisa dengan memasukkan command berikut di dalam folder chatbot_engine

```
pip install flask
```

*Note: Masuk ke direktori folder dari chatbot_engine untuk menginstall flasknya*

Contoh seperti ini:

```
C:\aplikasi-chatbot-restoran-whatsapp>

cd chatbot_engine

C:\aplikasi-chatbot-restoran-whatsapp\chatbot_engine>

```

Lalu

```
C:\aplikasi-chatbot-restoran-whatsapp\chatbot_engine>pip install flask
```

Maka Flask akan terinstall di dalam chatbot_engine kita

============================================================================================

