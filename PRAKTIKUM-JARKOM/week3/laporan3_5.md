# Laporan Praktikum Jarkom 3_5 HTTP CONDITIONAL GET/response interaction

## Tujuan Praktikum
Memahami cara kerja protokol HTTP menggunakan Wireshark.

## Langkah percobaan
1. Buka aplikasi Wireshark.
2. Lalu pilih WiFi.
3. Buka browser, lalu hapus cache & history.
4. Klik Start untuk mulai.
5. Kemudian buka URL ini: http://gaia.cs.umass.edu/wireshark-labs/protected_pages/HTTP-wireshark-file5.html
6. Lalu masukan username wireshark-students dan password network.
7. Setelah itu kembali ke Wireshark, lalu klik Stop.
8. Ketik http di kolom filter atas.
9. Username dan password yang telah dimasukkan sebelumnya, dikodekan dalam string karakter (d2lyZXNoYXJrLXN0dWRlbnRzOm5ldHdvcms=).
10. Untuk mengetahui string tersebut, klik paket HTTP GET setelah respon 401 Unauthorized (misalnya paket No. 735).
11. Lihat bagian tengah (Packet Details) dan klik bagian HTTP.
12. Cari tulisan Authorization: Basic.
13. Di situ ada kode seperti ini: d2lyZXNoYXJrLXN0dWRlbnRzOm5ldHdvcms=
14. Buka website decode Base64 http://www.motobit.com/util/base64-decoder-encoder.asp dan masukkan string yang disandikan base64 d2lyZXNoYXJrLXN0dWRlbnRz dan decode.

## Lampiran
Hasil Percobaan:
![Hasil Percobaan](../assets/image/week3_5.png)