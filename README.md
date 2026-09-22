# Cisco-packet-Tracer-Designed-LAN-to-MAN-Simulation

# Simulasi Metropolitan Area Network (MAN) dengan Static Routing

Repositori ini berisi proyek simulasi jaringan komputer menggunakan **Cisco Packet Tracer**, yang menghubungkan dua subnetwork LAN yang berbeda melalui arsitektur multi-router menggunakan rute statis (*static routing*).

## 📋 Detail Topologi & Konfigurasi
* **LAN 1:** `192.168.1.0/24` (Gateway: `192.168.1.1`)
* **LAN 2:** `192.168.2.0/24` (Gateway: `192.168.2.1`)
* **Jalur Antar-Router (MAN):** `10.0.0.0/24`
  * Router0 Interface G0/1: `10.0.0.2`
  * Router1 Interface G0/1: `10.0.0.1`

## 🚀 Cara Menggunakan
1. Pastikan kamu sudah menginstal aplikasi **Cisco Packet Tracer**.
2. Unduh atau *clone* repositori ini.
3. Buka file `.pkt` yang tersedia di dalam aplikasi Cisco Packet Tracer.
4. Lakukan uji coba pengiriman paket (*ping*) antar PC dari subnet yang berbeda untuk memverifikasi keberhasilan koneksi.
