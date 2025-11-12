# 🧩 Konfigurasi VLAN & Trunk Antar Switch di Cisco Packet Tracer | Praktikum Jaringan Komputer

## 📘 Deskripsi Proyek  
Proyek ini merupakan simulasi praktikum jaringan computer menggunakan Cisco Packet Tracer, dengan fokus pada konfigurasi VLAN (Virtual Local Area Network) dan trunking antar switch.  
Topologi jaringan terdiri dari 2 switch (S1 dan S2) serta 3 PC (PC-A, PC-B, dan PC-C) yang masing-masing ditempatkan pada VLAN berbeda untuk mempelajari cara segmentasi jaringan dan komunikasi antar VLAN.

## ⚙️ Tujuan  
- Memahami konsep dasar VLAN dan fungsinya dalam memisahkan jaringan.  
- Mengonfigurasi VLAN pada masing-masing switch.  
- Membangun koneksi trunk antar switch agar VLAN yang sama bisa berkomunikasi lintas switch.  
- Melakukan pengujian konektivitas antar perangkat menggunakan perintah ping.

## 🧱 Topologi Jaringan  
- Switch 1 (S1) terhubung ke PC-A dan PC-C.  
- Switch 2 (S2) terhubung ke PC-B.  
- Koneksi trunk dibuat antara S1 dan S2 agar VLAN dapat saling terhubung.  

## 💻 Perangkat yang Digunakan  
- 2 Switch (S1 dan S2)  
- 3 PC (PC-A, PC-B, PC-C)  
- Kabel UTP (Straight dan Cross sesuai kebutuhan)  

## 🧪 Hasil Pengujian  
| Pengujian              | Hasil | Keterangan |
|------------------------|:-----:|-------------|
| PC-A → PC-B            | ✅ | Berhasil (satu VLAN yang sama) |
| PC-A → S1              | ❌ | Berbeda domain VLAN / belum konfigurasi IP management |
| PC-B → S2              | ❌ | Berbeda VLAN tanpa trunk aktif |
| S1 → S2                | ✅ | Berhasil melalui port trunk |

## 🧠 Kesimpulan  
Konfigurasi VLAN membantu dalam pembagian jaringan menjadi beberapa segmen yang lebih aman dan efisien. Dengan penambahan trunk link, komunikasi antar VLAN pada switch yang berbeda dapat dilakukan dengan lancar.  
Simulasi ini menunjukkan pentingnya konfigurasi VLAN dan trunk untuk membangun jaringan yang terstruktur dan mudah dikelola.

## 👩‍💻 Video Youtube  
📥 [Download File Cisco Packet Tracer (.pkt)](https://youtu.be/tlQ4CRy2s9g)  

## 👩‍💻 File Packet Tracer
📥 [Youtube Saskiya Dwi Septiani](https://github.com/SaskiyaDwiSeptiani/Tugas-Akhir-Praktikum-Jaringan-Komputer/blob/59ee3e829e705691cf36514e6fecd1f83279547b/TAJudul3/TAJudul3.pkt)

