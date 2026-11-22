# 🚀 WaFlow CRM — WhatsApp Web CRM & CS Assistant

Official Release Repository untuk **WaFlow CRM**, ekstensi Chrome untuk mengubah WhatsApp Web menjadi CRM Enterprise, otomasi Customer Service, manajemen Lead/Funnel, Quick Reply, AI Assistant, dan Cetak Invoice PDF.

[![Release](https://img.shields.io/github/v/release/marifindev/WAFlow-ext?color=emerald&label=Latest%20Release)](https://github.com/marifindev/WAFlow-ext/releases/latest)
[![Chrome MV3](https://img.shields.io/badge/Manifest-V3-blue)](https://developer.chrome.com/docs/extensions/mv3/intro/)
[![License](https://img.shields.io/badge/License-Proprietary-orange)](#)

---

## 📥 Unduh Versi Terbaru

Kunjungi halaman **[Releases Terbaru](https://github.com/marifindev/WAFlow-ext/releases/latest)** untuk mengunduh:

* 📦 **`waflow-crm-vX.X.X.zip`** *(Disarankan)*: Format folder ekstensi siap ekstrak.
* 🧩 **`waflow-crm-vX.X.X.crx`**: Format paket ekstensi Chrome packed.

---

## 🛠️ Panduan Instalasi

### Metode 1: Menggunakan File ZIP (Paling Stabil & Direkomendasikan)
1. Unduh file `waflow-crm-vX.X.X.zip` dari [Releases](https://github.com/marifindev/WAFlow-ext/releases/latest).
2. Ekstrak file ZIP tersebut ke folder di komputer Anda (misal: di `Documents/waflow-crm`).
3. Buka browser **Google Chrome** atau **Microsoft Edge**, lalu buka alamat:
   ```text
   chrome://extensions/
   ```
4. Aktifkan **Developer mode** (Mode Pengembang) di pojok kanan atas.
5. Klik tombol **Load unpacked** (Muat yang belum dibongkar) di pojok kiri atas.
6. Pilih folder hasil ekstrak tadi.
7. Buka [web.whatsapp.com](https://web.whatsapp.com) dan refresh halaman. WaFlow CRM siap digunakan! 🎉

---

### Metode 2: Menggunakan File CRX
1. Unduh file `waflow-crm-vX.X.X.crx` dari [Releases](https://github.com/marifindev/WAFlow-ext/releases/latest).
2. Buka `chrome://extensions/` dan pastikan **Developer mode** aktif.
3. *Drag & drop* (seret dan lepas) file `.crx` ke jendela `chrome://extensions`.
4. Klik **Add Extension** pada pop-up konfirmasi.

---

## 🔄 Panduan Update Tanpa Kehilangan Data

Semua data WaFlow CRM (kontak, funnel, tag, riwayat invoice, follow-up, quick replies) disimpan secara lokal di browser (`chrome.storage.local`).

> ⚠️ **PENTING: JANGAN KLIK "REMOVE / HAPUS" PADA EKSTENSI LAMA!**
> Menghapus ekstensi akan menghapus database lokal browser. Ikuti langkah aman berikut:

### Langkah Update yang Benar:
1. *(Opsional tapi disarankan)* Buka WaFlow CRM di WhatsApp Web → Tab **Tools / Pengaturan** → Klik **Backup JSON** untuk mengamankan data Anda.
2. Unduh file `.zip` rilis terbaru.
3. Ekstrak dan **timpa file lama di folder yang sama**.
4. Buka `chrome://extensions/` lalu klik tombol **Reload / Refresh (🔄)** pada kartu WaFlow CRM.
5. Refresh tab WhatsApp Web Anda. Semua data tetap utuh 100%!

---

## ✨ Fitur Utama WaFlow CRM

* 📊 **Dashboard Analitik & Kanban Funnel**: Kelola prospek mulai dari Cold, Warm, Hot, Menunggu Transfer, Closing, hingga Repeat Order.
* 🏷️ **Contact Management & Multi-Tag**: Label kontak, catatan kustom, riwayat project, dan timeline interaksi.
* ⚡ **Quick Reply & Dynamic Variables**: Balas pesan cepat dengan variabel `{nama}`, `{salam}`, `{project}`, `{rekening}`, `{invoice}`.
* 🧾 **Katalog Produk & PDF Invoice Otomatis**: Buat dan unduh/kirim invoice profesional langsung dari WhatsApp Web.
* 🚚 **Cek Ongkir Terintegrasi**: Perhitungan ongkos kirim kurir instan di sidebar chat.
* 🤖 **AI Assistant (Google Gemini)**: Generator balasan cerdas terintegrasi Knowledge Base toko/bisnis Anda.
* 📅 **Jadwal & Follow-Up Reminder**: Pengingat berkala untuk follow-up pelanggan tepat waktu.
* 🔒 **Anti-Intip (Privacy Blur)**: Sensor nama, nomor, pesan, dan foto profil saat sedang screen sharing / presentasi.

---

## 🔒 Privasi & Keamanan Data

* **100% Client-Side Local Storage**: Semua database kontak dan chat tersimpan di perangkat lokal browser Anda.
* **Tanpa Database Server Pihak Ketiga**: WaFlow CRM tidak mengirimkan kontak atau percakapan WhatsApp Anda ke server manapun.

---

## 📞 Bantuan & Dukungan

Jika Anda memiliki pertanyaan, kendala, atau permintaan fitur:
* Hubungi pengembang di: **[ReogDigital By Arifindev](https://arifindev.my.id)** / **[reogdigital.com](https://reogdigital.com)**
