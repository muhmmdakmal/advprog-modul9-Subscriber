## AdvProg - Tutorial Module 09
<h2>
Nama   : Muhammad Akmal Abdul Halim

Kelas  : B

NPM    : 2306245125
</h2>

**a. What is amqp?**

AMQP (Advanced Message Queuing Protocol) adalah protokol standar terbuka pada lapisan aplikasi yang digunakan untuk middleware berorientasi pesan. Protokol ini memungkinkan aplikasi untuk berkomunikasi satu sama lain dengan mengirimkan pesan antar aplikasi, terlepas dari platform atau bahasa pemrograman yang digunakan untuk membangunnya. AMQP menyediakan fitur-fitur penting seperti pengiriman pesan yang andal, antrian pesan yang dapat disimpan hingga aplikasi penerima siap memprosesnya, kemampuan routing untuk mengarahkan pesan ke aplikasi penerima berdasarkan aturan tertentu, dukungan untuk transaksi dan konfirmasi, serta fitur keamanan seperti otentikasi dan enkripsi. Protokol ini banyak digunakan dalam sistem pesan enterprise dan broker pesan seperti RabbitMQ, Apache ActiveMQ, dan Azure Service Bus, menjadikannya pilihan populer untuk membangun sistem terdistribusi yang handal dan dapat diskalakan.

**b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what
is the second guest, and what is localhost:5672 is for?**

String "guest:guest@localhost:5672" adalah format URL koneksi yang digunakan untuk terhubung ke broker AMQP seperti RabbitMQ. Pada format ini, "guest" pertama merupakan username yang digunakan untuk autentikasi ke server AMQP. Sedangkan "guest" kedua adalah password yang digunakan untuk autentikasi tersebut. "guest:guest" umumnya merupakan kredensial default yang disediakan oleh broker AMQP seperti RabbitMQ untuk koneksi lokal. Bagian "localhost" menunjukkan alamat host atau server tempat broker AMQP berjalan, dalam kasus ini merujuk ke komputer lokal pengguna sendiri. Sementara angka "5672" adalah nomor port yang digunakan oleh broker AMQP untuk menerima koneksi dari klien. Port 5672 merupakan port standar yang digunakan oleh protokol AMQP untuk komunikasi tanpa enkripsi.