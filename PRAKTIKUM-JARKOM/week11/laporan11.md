# LAPORAN PRAKTIKUM JARKOM MODUL 11 DHCP

## Tujuan
Mahasiswa dapat mengamati dan memahami cara kerja protokol DHCP menggunakan Wireshark.

## Langkah-Langkah
1. IPCONFIG/RELEASE
![Gambar 1](../assets/image/w11_1.png)
2. IPCONFIG/RENEW
![Gambar 2](../assets/image/w11_2.png)
3. DHCP REQUEST
![Gambar 3](../assets/image/w11_3.png)
4. DHCP ACK
Pada percobaan DHCP di Windows, hanya paket DHCP Request dan DHCP ACK yang berhasil ditangkap. Kondisi ini disebabkan oleh adanya lease IP yang masih tersimpan pada sistem, sehingga klien melakukan proses pembaruan (renewal) alamat IP tanpa menjalankan seluruh tahapan DHCP dari awal.
![Gambar 4](../assets/image/w11_4.png)