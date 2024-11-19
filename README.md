---


---

<hr>
<h1 id="instruksi-tugas-praktikum">Instruksi Tugas Praktikum</h1>
<h3 id="tujuan-tugas">Tujuan Tugas</h3>
<p>Lakukan pemindaian jaringan menggunakan Nmap untuk menemukan jumlah server dan detail informasi layanan dalam jaringan <strong>172.16.100.0/24</strong>.</p>
<h3 id="langkah-langkah">Langkah-langkah</h3>
<ol>
<li>Lakukan pemindaian jaringan lengkap menggunakan perintah Nmap pada subnet <strong>172.16.100.0/24</strong>.</li>
<li>Identifikasi perangkat dalam jaringan yang berfungsi sebagai server (ditandai dengan banyaknya layanan yang aktif di perangkat tersebut).</li>
<li>Catat data berikut untuk setiap server yang ditemukan:
<ul>
<li><strong>Jumlah server</strong> yang terdeteksi.</li>
<li><strong>Port yang terbuka</strong> pada setiap server.</li>
<li><strong>Jenis layanan</strong> yang berjalan pada port tersebut.</li>
<li><strong>Versi layanan</strong> (service version) yang digunakan.</li>
<li><strong>Deteksi OS</strong> (Operating System) dari server tersebut.</li>
</ul>
</li>
</ol>
<h3 id="contoh-output-yang-diharapkan">Contoh Output yang Diharapkan</h3>
<ul>
<li>
<p><strong>Server 1</strong>:</p>
<ul>
<li><strong>IP Address</strong>: 172.16.100.10</li>
<li><strong>Ports</strong>: 22/tcp, 80/tcp, 443/tcp</li>
<li><strong>Services</strong>: SSH, HTTP, HTTPS</li>
<li><strong>Service Version</strong>: OpenSSH 7.4p1, Apache 2.4.29</li>
<li><strong>OS Detected</strong>: Linux 4.15 - 4.18</li>
</ul>
</li>
<li>
<p><strong>Server 2</strong>:</p>
<ul>
<li>(dan seterusnya untuk server lain yang ditemukan)</li>
</ul>
</li>
</ul>
<h3 id="catatan">Catatan</h3>
<p>Pastikan untuk menyusun laporan hasil scan dengan rapi dan jelas, serta menyertakan output hasil pemindaian sebagai bukti.</p>
<hr>

