# Materi-SSL
PENGERTIAN SSL


SSL, atau Secure Sockets Layer, adalah protokol keamanan yang digunakan untuk mengamankan komunikasi antara web server dan browser. Protokol ini mengenkripsi data yang dikirimkan, sehingga mencegah pihak ketiga mengakses informasi sensitif, seperti kata sandi atau nomor kartu kredit. 

SSL kini sebagian besar telah digantikan oleh TLS (Transport Layer Security), yang merupakan versi yang lebih aman dan diperbarui. Penggunaan SSL/TLS umumnya ditandai dengan "https://" di depan URL website, yang menunjukkan bahwa koneksi tersebut aman.






CARA KERJA SSL

Handshake: Proses dimulai dengan "handshake" antara klien dan server. Klien mengirimkan permintaan untuk menghubungkan dengan server. Server kemudian mengirimkan sertifikat digital yang berisi kunci publiknya.

Verifikasi Sertifikat: Klien memverifikasi sertifikat yang diterima. Jika sertifikat valid dan dikeluarkan oleh otoritas sertifikasi yang terpercaya, klien melanjutkan ke langkah berikutnya.

Membuat Kunci Sesi: Klien dan server menghasilkan kunci sesi yang akan digunakan untuk enkripsi. Kunci sesi ini biasanya dihasilkan menggunakan algoritma enkripsi simetris.

Enkripsi Data: Setelah kunci sesi dibuat, semua data yang ditransfer antara klien dan server akan dienkripsi. Ini melindungi data dari penyadapan selama transmisi.

Penyelesaian: Setelah handshake selesai, komunikasi dapat dimulai dengan data yang sudah dienkripsi. Kedua belah pihak dapat berkomunikasi dengan aman hingga sesi ditutup.

Dengan menggunakan SSL, data yang dikirimkan aman dari serangan seperti penyadapan atau manipulasi oleh pihak ketiga. Sekarang, banyak protokol SSL telah digantikan oleh TLS , tetapi istilah SSL masih sering digunakan secara umum.





     Berikut adalah kelebihan dan kekurangan SSL
-Kelebihan SSL
Keamanan Data: SSL mengenkripsi data yang dikirimkan antara klien dan server, melindunginya dari penyadapan dan manipulasi.

Kepercayaan Pengguna: Situs yang menggunakan SSL menunjukkan tanda kunci atau "https://" di URL, meningkatkan kepercayaan pengguna.

Autentikasi: Sertifikat SSL memastikan bahwa pengguna terhubung dengan server yang benar dan bukan situs palsu.

Kepatuhan: Banyak regulasi dan standar industri (seperti PCI-DSS untuk transaksi pembayaran) mengharuskan penggunaan SSL untuk melindungi data sensitif.

SEO: Mesin pencari, seperti Google, memberikan peringkat lebih baik untuk situs yang menggunakan HTTPS.

-Kekurangan SSL
Biaya: Meskipun ada sertifikat SSL gratis, beberapa jenis sertifikat premium bisa mahal, terutama untuk bisnis besar.

Kompleksitas: Mengimplementasikan dan mengelola sertifikat SSL bisa menjadi rumit, terutama untuk organisasi yang memiliki banyak subdomain.

Kinerja: Proses enkripsi dan dekripsi dapat memperlambat waktu respons server, meskipun dampaknya biasanya kecil.

Pembaruan Sertifikat: Sertifikat SSL memiliki masa berlaku terbatas dan perlu diperbarui secara berkala, yang bisa menjadi beban administratif.

Risiko Kualitas Sertifikat: Tidak semua sertifikat SSL memiliki tingkat kepercayaan yang sama, dan sertifikat yang buruk dapat mengurangi keamanan
