# Mini Project - Data Visualization using R
Terdapat sejumlah data tentang karyawan di perusahaan A. Lalu aku diminta untuk mempresentasikan sebagian data itu kepada pimpinan. Salah satu data yang hendak ditampilkan adalah jumlah karyawan berdasarkan jenis kelamin dalam kelompok usia tertentu. Pimpinan perusahaan ingin melihat postur jumlah karyawan laki-laki dan perempuan berdasarkan rentang usia mereka.
Aku pun diminta menampilkan grafik yang simpel, tetapi padat informasi. Grafik itu membandingkan banyaknya jumlah karyawan laki-laki dan perempuan dalam setiap kelompok umur yang sama.

Tantangannya adalah, grafik tersebut harus menunjukkan postur jumlah karyawan berdasarkan jenis kelamin dan rentang usianya sekaligus.

Dengan menggunakan Microsoft Excel, tentunya aku bisa dengan mudah membuat grafik seperti pada gambar dibawah ini. Sayangnya, grafik ini boros tempat karena banyaknya kategori rentang usia membuatnya melebar. Ukuran huruf untuk keterangan pada masing-masing sumbu pun menjadi kecil dan kurang terbaca.

![dv1](https://user-images.githubusercontent.com/20991856/133715703-7ef86712-71f6-45d3-b516-cb7ebafd639f.PNG)

Selain itu, pembaca sulit melihat postur jumlah karyawan berdasarkan jenis kelamin karena jarak antarkolom jenis kelamin yang sama tampak berjauhan.

 

Bagaimana mengubah grafik ini menjadi lebih ringkas dan mudah terbaca?

Target
Grafik yang lebih simpel dan hemat ruang.
Komparasi jumlah karyawan laki-laki dan perempuan berdasarkan rentang usia.

Berikut adalah data karyawan di perusahaan A.

![dv1 2](https://user-images.githubusercontent.com/20991856/133716033-ced66332-a19b-495e-af96-c3a1f74c0bb9.PNG)

Dengan menggunakan data karyawan di atas, aku bisa mengerjakan dengan menggunakan applikasi Google spreadsheet, Excel, LibreOffice atau OpenOffice untuk memplotkan data ini, tentunya di laptop/komputer ku nantinya. 

Akan tetapi kali ini aku akan melakukannya dengan menggunakan ggplot (salah satu library plotting bahasa pemrograman R).
