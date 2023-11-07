## 1.1 Latar Belakang

 Sebagai seorang mahasiswa yang hidup jauh dari orang tua kita dituntut untuk bisa hidup mandiri salah satunya dapat me manage keuangan pribadi mulai dari kebutuhan makan sehari hari, kebutuhan kuliah dan sebagainya. Sayapun sering mendengar keluh kesah teman2 saya bahkan saya sendiri pun mengalami nya "kemana sih perginya uang saya kok cepat habis, gaada jejak nya??!!".
 Dengan berbagai kemudahan di era modern ini kita dapat melakukan apapun, kapanpun, dan dimanapun hanya dengan menggunakan smartphone dan internet. Dengan alat itu kita juga dapat mencatat pemasukan dan pengeluaran kita setiap hari agar kita dapat mengetahui untuk apa uang kita digunakan dan berapa rata-rata pengeluaran kita.


## 1.2. Deksripsi Teknologi Informasi
1.Database menggunakan JSON (Jenis ini memungkinkan para pengguna dapat melakukan, melihat, dan memodifikasi data.) 
2.Frontend menggunakan HTML, CSS, javascript
3.Backend menggunakan javascript frameworknya tailwindcss (mempermudah kamu untuk mempertahankan konsistensi di seluruh desain. Dengan sistem skalanya yang terintegrasi, kamu dapat memastikan padding, margin, warna, dan elemen lainnya seragam di semua bagian dan dirancang untuk lebih ringan dalam hal ukuran file.)
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
 |pengguna | melihat rating produk | sehingga mengetahui rekomendasi produk favorit| ⭐⭐⭐⭐
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
 *Hardware-> mesin komputasi 
          -> sensor
          -> res
 *software

## 5. Teknologi, Library, dan Framework
teknologi pendukung saya menggunakan Visual Studio Code kemudian untuk framework menggunakan lavarel(Laravel adalah framework PHP yang open source dan dirancang untuk memudahkan pengembangan web dengan sintaks yang mudah dipelajari.) dan untuk library menggunakan lavarel

## 6. Desain User Experience dan User Interface

![Prototype web](/desain.png)

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
