---

# **Instruksi Tugas Praktikum**

## **Tujuan Tugas**
Lakukan pemindaian jaringan menggunakan Nmap untuk menemukan jumlah server, detail informasi layanan, dan distribusi Linux beserta versinya dalam jaringan **10.132.28.0/25**.

## **Langkah-langkah**
1. **Lakukan pemindaian jaringan lengkap** menggunakan perintah Nmap pada subnet **10.132.28.0/25**.
2. Identifikasi perangkat dalam jaringan yang berfungsi sebagai server (ditandai dengan banyaknya layanan yang aktif di perangkat tersebut).
3. **Catat data berikut** untuk setiap server yang ditemukan:
   - **Jumlah server** yang terdeteksi.
   - **Port yang terbuka** pada setiap server.
   - **Jenis layanan** yang berjalan pada port tersebut.
   - **Versi layanan** (service version) yang digunakan.
   - **Deteksi OS** (Operating System) dari server tersebut.
   - **Distribusi Linux** dan versi yang digunakan (jika server menggunakan Linux).  
     > *Gunakan opsi tambahan Nmap atau telusuri header layanan untuk menemukan informasi ini.*

## **Contoh Output yang Diharapkan**

- **Server 1**:
  - **IP Address**: 10.132.28.126
  - **Ports**: 22/tcp, 80/tcp, 443/tcp
  - **Services**: SSH, HTTP, HTTPS
  - **Service Version**: OpenSSH 7.4p1, Apache 2.4.29
  - **OS Detected**: Linux 4.15 - 4.18
  - **Linux Distribution**: Ubuntu 18.04

- **Server 2**:
  - (dan seterusnya untuk server lain yang ditemukan)

## **Catatan**
- Pastikan untuk menyusun laporan hasil scan dengan rapi dan jelas.  
- **Sertakan output hasil pemindaian sebagai bukti.**  
- Jika tidak dapat mendeteksi distribusi Linux melalui Nmap, gunakan pendekatan manual seperti memeriksa banner layanan atau meminta administrator server untuk informasi lebih lanjut.

---
