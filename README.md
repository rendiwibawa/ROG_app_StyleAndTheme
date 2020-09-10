# Praktikum MyViewsAndViews

> Gaya dan tema di Android memungkinkan Anda memisahkan detail desain aplikasi Anda dari struktur dan perilaku UI, mirip dengan stylesheet dalam desain web.

Gaya adalah sekumpulan atribut yang menentukan penampilan untuk satu Tampilan. Gaya dapat menentukan atribut seperti warna font, ukuran font, warna latar belakang, dan banyak lagi.

Tema adalah kumpulan atribut yang diterapkan ke seluruh aplikasi, aktivitas, atau hierarki tampilan — bukan hanya tampilan individual. Saat Anda menerapkan tema, setiap tampilan dalam aplikasi atau aktivitas menerapkan setiap atribut tema yang didukungnya. Tema juga dapat menerapkan gaya ke elemen non-tampilan, seperti bilah status dan latar belakang jendela.

Gaya dan tema dideklarasikan dalam file sumber daya gaya di res / values ​​/, biasanya dinamai styles.xml.


Gambar 1. Dua tema diterapkan ke aktivitas yang sama: Theme.AppCompat (kiri) dan Theme.AppCompat.Light (kanan)

Tema versus Gaya
Tema dan gaya memiliki banyak kesamaan, tetapi digunakan untuk tujuan yang berbeda. Tema dan gaya memiliki struktur dasar yang sama — pasangan nilai-kunci yang memetakan atribut ke sumber daya.

Gaya menentukan atribut untuk jenis tampilan tertentu. Misalnya, satu gaya mungkin menetapkan atribut tombol. Setiap atribut yang Anda tentukan dalam gaya adalah atribut yang bisa Anda setel di file tata letak. Dengan mengekstrak semua atribut ke sebuah gaya, maka mudah untuk menggunakan dan memeliharanya di beberapa widget.

Tema mendefinisikan kumpulan sumber daya bernama yang bisa dirujuk oleh gaya, tata letak, widget, dan sebagainya. Tema menetapkan nama semantik, seperti colorPrimary, ke sumber daya Android.

Gaya dan tema dimaksudkan untuk bekerja sama. Misalnya, Anda mungkin memiliki gaya yang menetapkan bahwa satu bagian tombol harus colorPrimary, dan bagian lainnya harus colorSecondary. Definisi sebenarnya dari warna-warna tersebut disediakan dalam tema. Saat perangkat masuk ke mode malam, aplikasi Anda dapat beralih dari tema "terang" ke tema "gelap", mengubah nilai untuk semua nama sumber daya tersebut. Anda tidak perlu mengubah gaya, karena gaya menggunakan nama semantik dan bukan definisi warna tertentu.
Contoh komponen viewgroup adalah:

>  LinearLayout

>  FrameLayout

>  RelativeLayout

>  TableLayout

## Tampilan 

![ALT TEXT](https://github.com/rendiwibawa/MyViewsAndViews/blob/master/atas.jpeg)

## Tampilan

![ALT TEXT](https://github.com/rendiwibawa/MyViewsAndViews/blob/master/deskripsi.jpeg)

## Tampil FULL

![ALT TEXT](https://github.com/rendiwibawa/MyViewsAndViews/blob/master/full.jpeg)





