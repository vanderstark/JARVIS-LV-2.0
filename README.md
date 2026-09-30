# 🤖 JARVIS-LV-2.0 — Asisten AI Personal Cross-Platform

**JARVIS-LV-2.0** adalah asisten AI personal yang nyata, bisa mendengar, melihat, berbicara, mengingat, dan mengontrol komputer.

> **Mark LV** adalah asisten gaya JARVIS yang dibuat dengan **Python, PyQt6, dan Google Gemini Live API**. Menyediakan interaksi voice real-time, kendali komputer, memori yang konsisten, pengawasan visual, pencarian web, dan HUD holografis.

> **Mendukung:** Windows, macOS, dan Linux.

---

## 📌 Status Proyek

> **🟢 Dalam Pengembangan Aktif — Mark LV (55)**

| Komponen                     | Status      |
| ---------------------------- | ----------- |
| 🤖 Asisten AI Utama          | 🟢 Berjalan   |
| 🎙️ Gemini Live Voice         | 🟢 Berjalan   |
| 🖥️ PyQt6 HUD                 | 🟢 Berjalan   |
| 🧑‍🎤 Avatar Holografis        | 🟢 Berjalan   |
| 👄 Lip Sync                   | 🟢 Berjalan   |
| 🧠 Memori Persisten            | 🟢 Berjalan   |
| 🖥️ Kendali Komputer           | 🟢 Berjalan   |
| 📂 Manajemen File             | 🟢 Berjalan   |
| 🌐 Kendali Browser            | 🟢 Berjalan   |
| 🔎 Pencarian Web              | 🟢 Berjalan   |
| 📺 Video HUD                   | 🟢 Berjalan   |
| 🔌 Sistem Plugin               | 🟢 Berjalan   |
| ↩️ Undo & Konfirmasi           | 🟢 Berjalan   |
| 🎙️ Wake Word                  | 🟢 Berjalan   |
| 📊 Pemantauan Sistem          | 🟢 Berjalan   |
| 🌍 Dukungan Cross-Platform     | 🟡 Testing Berlangsung |
| 🎙️ Pemutusan Voice            | 🔅 Direncanakan |
| 💬 Riwayat Conversasi Penuh   | 🔅 Direncanakan |
| 📱 Integrasi Tambahan          | 🔅 Direncanakan |

**Rilis Saat Ini:** Mark LV (55)  
**Pengembangan:** Aktif  
**Jenis Proyek:** Asisten AI Personal / Agen Desktop  
**Arsitektur:** Modular + Plugin-Based + Cross-Platform

> 🚧 **Mark LV adalah proyek yang terus berkembang.** Beberapa fitur canggih dan kemampuan khusus platform masih dalam pengembangan dan mungkin perilakunya berbeda tergantung sistem operasi dan hardware.

---

## ✨ Fitur

* 🎙️ **Voice AI Real-time** — Konversasi natural menggunakan Gemini Live API
* 🧑‍🎤 **Avatar Holografis** — AI face software-rendered dengan ekspresi wajah
* 👄 **Lip Sync** — Animasi mulut speech-to-realtime
* 👁️ **Vision** — Kesadaran layar dan webcam
* 🧠 **Memori Persisten** — Memori lokal untuk jangka panjang
* 🖥️ **Kendali Komputer** — Aplikasi, volume, kecerahan, shortcut, jendela
* 📂 **Manajemen File** — Buat, pindah, gantikan, kopi, hapus, dan organisir file
* 🌐 **Kendali Browser** — Buka URL, navigasi, dan interaksi dengan browser
* 🔎 **Pencarian Web** — Pencarian, berita, riset, dan mode perbandingan
* 📺 **Video HUD** — YouTube, file lokal, dan URL video langsung
* 🪜 **Model Fallback** — Gemini model fallback otomatis dengan cooldown
* ↩️ **Undo** — Membatalkan tindakan yang didukung
* ⚠️ **Human Konfirmasi** — Konfirmasi pengguna untuk tindakan yang tidak bisa dikembalikan
* 🎙️ **Wake Word** — Deteksi "Hey Jarvis" lokal
* 🎚️ **Push-to-Talk** — `Ctrl + Space`
* 📊 **Pemantauan Hardware** — CPU, RAM, GPU dan suhu
* 🌤️ **Weather** — Informasi cuaca live
* ⏰ **Reminders** — Reminder nativi OS
* 🌅 **Morning Briefing** — Waktu, aktivitas sebelumnya, dan update
* 🔔 **Proactive AI** — Interaksi asisten yang sadar konteks
* 🔌 **Plugin System** — Tambahkan keterampilan kustom melalui plugin Python
* 📱 **Remote Dashboard** — Kendali Mark LV dari telepon
* 🎨 **Live Theming** — Sesuaikan warna HUD dan tampilan
* 🚀 **Auto-Start** — Launch otomatis saat sistem dimulai

---

## 🧠 Arsitektur

```text
User
 │
 ├── 🎙️ Voice
 ├── ⌨️ Keyboard
 └── 👁️ Vision
       │
       ▼
┌─────────────────────┐
│    Gemini Live AI   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│     Mark LV Core    │
└──────────┬──────────┘
           │
    ┌──────┼──────┐
    ▼      ▼      ▼
Computer Memory Plugins
Control
    │
    └──────┬──────┘
           ▼
      PyQt6 HUD
           │
     ┌─────┴─────┐
     ▼           ▼
Avatar       Video
     │
     ▼
Voice Response
```

---

## 🛠️ Tumpukan Teknologi

* **Python 3.11–3.13**
* **Google Gemini Live API**
* **PyQt6**
* **yt-dlp**
* **PortAudio**
* **OpenWakeWord**
* **MediaPipe Face Model**
* **JSON Local Storage**
* **OS-native automation**

---

## 💻 Persyaratan Sistem

| Persyaratan | Detail |
| ----------- | ------ |
| **OS** | Windows 10/11, macOS, Linux |
| **Python** | 3.11 / 3.12 / 3.13 |
| **Microphone** | Diperlukan |
| **Speakers** | Diperlukan |
| **API Key Gemini** | Diperlukan |
| **GPU** | Bukan diperlukan |
| **Internet** | Diperlukan untuk fitur AI/web |

---

## 🚀 Memulai Cepat

### 1. Clone

```bash
git clone https://github.com/ritesh-coder404/JARVIS-LV-2.0.git
cd JARVIS-LV-2.0
```

### 2. Install

```bash
python setup.py
```

Atau:

```bash
pip install -r requirements.txt
```

### 3. Jalankan

```bash
python main.py
```

> **Tambahkan kunci API Gemini saat diminta.**

---

## ⚙️ Konfigurasi

Konfigurasi lokal disimpan di:

```text
config/api_keys.json
```

Memori disimpan di:

```text
memory/long_term.json
```

> ⚠️ **AJAR KOMIT API key, sertifikat, atau file memori pribadi ke GitHub.**

`.gitignore` disarankan:

```gitignore
config/api_keys.json
config/certs/
memory/long_term.json
```

---

## 📁 Struktur Proyek

```text
Mark-LV/
├── main.py
├── ui.py
├── setup.py
├── .gitignore
│
├── actions/
│   ├── computer_control.py
│   ├── file_controller.py
│   ├── browser_control.py
│   ├── web_search.py
│   ├── video_player.py
│   ├── weather_report.py
│   └── system_monitor.py
│
├── core/
│   ├── gemini.py
│   ├── avatar.py
│   ├── viseme.py
│   ├── undo.py
│   ├── confirm.py
│   ├── plugin_loader.py
│   └── wake_word.py
│
├── plugins/
├── memory/
└── config/
```

---

## � Privasi

JARVIS-LV-2.0 mengikuti **approach local-first** untuk konfigurasi dan memori.

*Konfigurasi, memori, dan sertifikat lokal:*

* **Disimpan di mesin Anda.**

> **Voice di-stream ke API Live Gemini Google sementara sesi aktif.**

---

## 🛡️ Keamanan & Kontrol

JARVIS-LV-2.0 memisahkan **keputusan AI** dari tindakan sensitif komputer.

> **Contoh:**

```text
AI meminta tindakan
      ↓
Tampilkan konfirmasi
      ↓
Penggunnya konfirmasi
      ↓
Tindakan dieksekusi
```

Ini membantu mencegah eksekusi tidak sengaja dari operasi yang tidak bisa dikembalikan.

Tindakan yang bisa dikembalikan juga dapat menggunakan sistem **Undo**.

---

## 🗺️ Jalur Pengembangan (Roadmap)

### Rencana

* 🎙️ **Voice interruption** — Pemutusan voice
* 💬 **Full conversation history** — Riwayat conversation yang utuh
* 📱 **Telegram remote control** — Kendali remote via Telegram
* 📂 **Advanced file access** — Akses file lanjutan
* 📹 **Security camera integration** — Integrasi kamera keamanan
* 📝 **Obsidian integration** — Integrasi dengan Obsidian
* 🤖 **Additional AI models** — Model AI tambahan
* 🔌 **More plugins** — Plugin lebih banyak
* 👁️ **Advanced computer vision** — Computer vision yang canggih
* 🧠 **Advanced agentic planning** — Perencanaan agen yang canggih
* 🔐 **Enhanced security controls** — Kontrol keamanan yang ditingkatkan

---

## 🤝 Kontribusi

Kontribusi sangat dihargai!

Anda bisa berkontribusi melalui:

* 🐛 **Laporan bug**
* � **Permintaan fitur**
* 🔌 **Plugin baru**
* 🔧 **Pull requests**
* 📖 **Dokumentasi**
* ⚡ **Improvements performa**
* 🌍 **Perbaikan cross-platform**

---

## ⭐ Dukung Proyek

Jika Anda menemukan **Mark LV** berguna:

⭐ **Star repository**  
🐛 **Lapor issue**  
💡 **Suggest fitur**  
🔌 **Kontribusi**  
📢 **Bagikan proyek**

---

## 👨‍💻 Author

### Ritesh Thakur

GitHub:
```text
https://github.com/Ritesh-coder404
```

Repository:
```text
https://github.com/Ritesh-coder404/JARVIS-LV-2.0
```

---

## 🙏 Pengakuan

Dibangun dengan bantuan:

* Google Gemini
* Gemini Live API
* PyQt6
* yt-dlp
* MediaPipe
* Python
* PortAudio
* OpenWakeWord
* Masyarakat open-source

---

## 📜 Lisensi

Tambahkan lisensi proyek aktual di sini.

> **JARVIS-LV-2-0— Hear. See. Remember. Think. Act. 🤖**