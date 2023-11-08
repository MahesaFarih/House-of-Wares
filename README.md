## Tugas 7 PBP

1. Perbedaan antara stateless widget dengan statefull widge. Stateless widget adalah sebuah widget dalam Flutter dimana widget tersebut tidak akan berubah, contoh dari stateless widget adalah icon, text, snackbar, dan warna yang digunakan dalam penugasan PBP No.7 ini. Berikutnya adalah stateful widget adalah widget dari Flutter yang bersifat dinamik atau dapat mengalami perubahan ketika ada input dari pengguna, cotohnya adalah inkwell dalam penugasan ini dan floatting button untuk merubah nilai $count dalam template dasar saat penggunaan flutter create <app>.

2.  Widget yang digunakan
* Material: Digunakan untuk implementasi desain yang digunakan untuk membuat aplikasi tersebut
* InkWell: Digunakan untuk button aktivasi dari button
* Snackbar: Digunakan untuk popup jenis button yang ditekan
* Container: Sebagai wadah untuk menampung widget widget lainnya
* Center: Agar widget dalam satu kontainer ada di center
* Column: Digunakan sebagai layout dimana 3 button itu ada pada satu baris
* Icon: Icon digunakan untuk menampilkan ikon. Dalam kode ini, ia menampilkan ikon yang terkait dengan setiap item toko.
* Text: Text digunakan untuk menampilkan teks. Ini menampilkan nama setiap item toko.
* Scaffold: Scaffold adalah struktur dasar yang memberikan kerangka kerja untuk seluruh halaman. Biasanya berisi AppBar dan body.
* AppBar: AppBar digunakan untuk membuat bilah aplikasi atas dengan judul.
* Text: Text digunakan untuk menampilkan judul "House of Wares" di AppBar.
* SingleChildScrollView: SingleChildScrollView digunakan untuk membuat widget yang dapat di-scroll dan memungkinkan Anda untuk menggulir konten di dalamnya.
* Padding: Padding digunakan untuk menambahkan padding ke konten di dalam widget.
* GridView: GridView digunakan untuk membuat tata letak grid untuk menampilkan item toko dalam grid.
* GridView.count: GridView.count adalah jenis khusus dari GridView yang membuat grid dengan jumlah kolom yang tetap.
* ShopCard: ShopCard adalah widget kustom yang didefinisikan dalam kode Anda. Ini mewakili kartu dengan ikon dan teks.
* ShopItem: ShopItem adalah kelas yang digunakan untuk mewakili item toko individu dengan nama, ikon, dan warna.

3. Cara membuat:
    1. Jalankan ```Flutter Start <app name>```
    2. Buka file demo flutter yang sudah dibuat
    3. Pindahkan class selain MyApp() ke file baru yang bernama manu.dart dalam folder lib 
    4. Ubah class MyHomePage menjadi Stateless widget
    5. Buat class Shop item untuk implementasi button
    6. Buatlah class container yang diisi oleh desain button
    7. Buatlah InkWell dan snackbar sebagai onTap() dari button tersebut beserta pop up berupa snackbar
