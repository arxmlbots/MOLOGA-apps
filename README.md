# MOLOGA-apps
MOLOGA - Game timer &amp; alarm app for Android. Set duration, package, get alerts with vibration &amp; notifications.

# MOLOGA - Mode Clock Games

MOLOGA adalah aplikasi timer dan alarm untuk Android, dirancang untuk membantu mengatur durasi bermain game.  
Aplikasi ini dibangun menggunakan **Android Java 7** (AIDE compatible), dengan interface yang simpel dan fitur custom yang fleksibel.

---

## Fitur Utama
- Set durasi bermain: jam dan menit.
- Input **package name** aplikasi/game yang ingin dipantau.
- **Alarm peringatan 5 menit** sebelum waktu habis.
- **Alarm akhir** saat durasi habis, dilengkapi:
  - **Looping sound** (end.mp3)
  - **Vibrasi**
  - **Notifikasi**
- Tampilan transparan dan minimalis.
- Presisi timer dengan cek **detik 00**.
- Bisa dijalankan di background dengan notifikasi aktif.

---

## Permissions
- `android.permission.VIBRATE` → Untuk vibrasi saat alarm.
- `android.permission.DISABLE_KEYGUARD` baca yang di bawah 👇🏼
- Device Administrator ( DA ) → ini di gunakan untuk mengunci layar setelah alarm habis
- Tidak ada permission tambahan lain karena **tidak langsung membuka aplikasi lain** (sifat universal & manual).

---

## Layout
- Menggunakan `LinearLayout` vertikal.
- Tampilan minimalis, warna transparan di beberapa EditText dan Button.
- Terdapat **AnalogClock**, input package, durasi main, dan tombol START/STOP.
- Transparansi tombol & input memudahkan tampilan fullscreen.

---

## Lisensi
Apache License 2.0 — bebas digunakan dengan mencantumkan copyright.

---

## Catatan
- **Universal package input:** User bebas memasukkan package mana pun.
- **Tidak auto-launch aplikasi:** Tujuannya agar timer bekerja terlepas dari aplikasi yang dipantau.
- **Mode Kapokin Adek:** Bisa digunakan untuk mengingatkan durasi bermain game.
