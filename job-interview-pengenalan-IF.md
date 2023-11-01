## 1.1 Latar Belakang

Online shop kini menjadi trend karena kemudahan nya untuk berbelanja tanpa harus keluar rumah dan dapat meminimalisir biaya dengan itu saya tertarik membuat website ini untuk memudahkan konsumen bertransaksi dengan mudah, dengan menggunakan website ini user dapat melihat berbagai macam jenis produk yang tersedia dan jika ingin membeli sangat mudah, dapat melihat rating sehingga konsumen mengetahui produk mana yang menjadi favorit
Cara kerja:
1. menggunakan website dengan sistem online agar memudahkan pembeli yang berada di luar kota tanpa harus datang ke toko
2. menggunakan perangkat komputer yg tersedia di dalam toko yang digunakan untuk melakukan pemesanan barang dengan sistem self service

## 1.2. Deksripsi Teknologi Informasi
1.Database menggunakan JSON (Jenis ini memungkinkan para pengguna dapat melakukan, melihat, dan memodifikasi data.) (javascript)
2.Frontend menggunakan HTML, CSS, JAVASCRIPT
3.Backend menggunakan java dan javascript frameworknya Angular (apk/web yang berinteraksi dengan pengguna dengan secara dinamis menulis ulang halaman web saat ini dengan data baru dari server web, bukan metode default browser web yang memuat seluruh halaman baru.)
4.Untuk Design/gambaran awal aplikasinya saya menggunakan FIGMA
5.Untuk Membuat programnya menggunakan Visual Studio Code
6.Operasi OS menggunakan Windows
## 1.3. Branding
merek: KLINIK DURIAN
tagline : 
campaign : 
*~membuat (website/tampilan) di dalam komputer dengan sistem self service & website online (untuk pembeli luar kota) membuat pengguna dapat melihat, membaca detail produk kemudian dapat memesan sesuai keinginan pembeli dan (di dalamnya dapat mengetahui jumlah barang, total harga, diskon, dan kembalian)
pengguna sasaran :
~20 sesorang yang sudah memiliki pekerjaan/uang tetap (karena harga produk yg cukup mahal)
seseorang yang menyukai kuliner 
seseorang yang menyukai durian

tema:
~mudah
~sederhana
~efisien
~cepat

## 2. User Story  
 |pengguna | melihat daftar produk | sehingga mengetahui produk mana yg diinginkan | ⭐⭐⭐⭐⭐
 |pengguna | melihat detail produk | sehingga mengetahui deskripsi,ukuran,harga produk| ⭐⭐⭐⭐⭐
 |pengguna | memesan produk  | sehingga dapat langsung mengetahui berapa jumlah yg dibeli,diskon yang didapatkan, harga yg harus dibayar, kembalian  | ⭐⭐⭐⭐
 |pengguna | melihat rating produk | sehingga mengetahui rekomendasi produk| ⭐⭐⭐⭐
 |pengguna | mencari produk | sehingga memudahkan pengguna menemukan produk yg dicari| ⭐⭐⭐⭐
 |pengguna | menambahkan produk ke favorit | sehingga memudahkan pengguna untuk mencari produk favorit nya| ⭐⭐⭐⭐
 |pengguna | memasukan nama | sehingga dapat mengetahui siapa pemesan| ⭐⭐⭐⭐⭐
 |pengguna | keterangan member | sehingga dapat mengetahui apakah dia terdaftar sebagai member atau belum| ⭐⭐⭐⭐
 |pengguna | kode barang| sehingga memudahkan pengguna menemukan produk yg dicari| ⭐⭐⭐
 |pengguna | total harga | sehingga dapat mengetahui berapa yang harus dibayarkan| ⭐⭐⭐⭐⭐
 |pengguna | kembalian | sehingga dapat mengetahui kembalian dari uang yang dibayarkan| ⭐⭐⭐⭐
 |pengguna |  menambahkan alamat | sehingga dapat mengetahui kemana produk akan dikirimkan| ⭐⭐⭐⭐⭐

*## 3. Struktur Data

erDiagram
   HOME PAGE ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }

## 4. Arsitektur Sistem

flowchart TD
    id1[(Database: MySQL)] <--> id2[Aplikasi Web Backend: Javascript - Laravel] <--> id3[Web Server: Javascript - Laravel]  


## 5. Teknologi, Library, dan Framework
teknologi pendukung saya menggunakan Visual Studio Code kemudian untuk framework menggunakan lavarel(Laravel adalah framework PHP yang open source dan dirancang untuk memudahkan pengembangan web dengan sintaks yang mudah dipelajari.) dan untuk library menggunakan lavarel

## 6. Desain User Experience dan User Interface

![Prototype web](/Screenshot 2023-10-26 080523.png)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
