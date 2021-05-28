# Notes API
Repository ini dibuat untuk menyimpan kode dan juga dokumentasi dari Proyek Kedua pada Mata Kuliah "Pemrograman Integratif" di Institut Teknologi Sepuluh Nopember. Pada proyek kali ini, saya ditugaskan untuk melakukan pembuatan **API** atau kepanjangannya **Application Programming Interface**. Pada proyek ini, saya memanfaatkan penggunaan API untuk melakukan pembuatan **Notes** atau dalam Bahasa Indonesianya adalah **Catatan**. 

Dalam Readme ini akan dijelaskan mengenai apa itu Notes API, struktur repository, Method dan framework apa saja yang digunakan, cara instalasi, dokumentasi penggunaan, dan juga tempat hosting dari Notes API ini. Proyek ini sudah dilakukan testing dan tidak ditemukan adanya Bug ataupun error yang mengganggu. Terima kasih atas waktu dan perhatiannya.

## Penjelasan Notes API
Proyek Notes API ini dituliskan dalam Bahasa Pemrograman [**JAVASCRIPT**](https://www.javascript.com/) dengan standard **EcmaScript 6** dikarenakan banyaknya kegunaan bahasa ini dalam melakukan pembuatan Web Server dan juga Web Application dan saya memanfaatkan kegunaan ini untuk membuat Notes API ini. Pembuatan Proyek ini juga dilakukan dengan memanfaatkan [**NodeJS**](https://nodejs.org/en/) sebagai runtime yang memungkinkan Javascript untuk bisa dijalankan di berbagai macam Environment yang tidak terbatas pada lingkungan Browser saja.

Proyek ini nanti akan memungkinkan user untuk membuat, membaca, melakukan editing, dan juga menghapus (**CRUD**) berbagai macam catatan yang tersimpan di dalam API. API ini akan dilakukan hosting sehingga nanti bisa langsung dilakukan akses menggunakan [**POSTMAN**](https://www.postman.com/) ataupun menggunakan pembuatan **Website Front-end** yang memanfaatkan caching API. Nantinya Server dan juga Client akan melakukan transaksi data melalui protokol HTTP.

## Struktur Repository  
- **Folder references** : berisi 2 folder yaitu code yang menyimpan referensi dan juga latihan penulisan kode Javascript dan juga Framework Hapi untuk mewujudkan API ini, dan juga folder documentation yang berisi gambar-gambar untuk dimasukkan ke dalam readme ini.
- **Folder src** : berisi kode utama API dalam bahasa Javascript dalam Framework Hapi
- package.json : berisi informasi package apa saja yang digunakan dalam pembuatan API ini

## Method dan Framework yang Digunakan  
Ada 4 Method yang digunakan dalam pembuatan Proyek ini yaitu:
- **POST** : Digunakan untuk menambahkan catatan ke dalam API untuk dilakukan penyimpanan
- **GET** : Digunakan untuk menampilkan catatan yang telah tersimpan di API agar bisa dibaca
- **PUT** : Digunakan untuk melakukan editing atau update terhadap isi catatan yang tersimpan di API
- **DELETE** : Digunakan untuk menghapus catatan yang tersimpan di API

Proyek ini menggunakan Framework [**HAPI**](https://hapi.dev/) karena menyediakan environment yang lengkap untuk mengembangkan web server yang kompleks. Bila menggunakan Hapi, kita tak perlu tools lain untuk menerapkan layer **authentication, tokenize, cors,** dan lain sebagainya. 

Selain itu Proyek ini akan menggunakan Package Manager bawaan NodeJS yaitu [**NPM**](https://www.npmjs.com/) yang digunakan untuk melakukan pengaturan package agar lebih mudah diatur dan diawasi. Ada juga beberapa package Dependencies yang digunakan agar API ini bisa berjalan yang nantinya akan terinstall secara otomatis yaitu **ESlint** yang digunakan untuk melakukan perapian dan pemaksaan **Code Styling Javascript**, **nodemon** yang digunakan untuk memastikan Server berjalan terus-menerus meskipun ada penggantian kode, **Hapi** yang tentu saja digunakan sebagai Framework dari API ini, dan juga **nanoid** yang digunakan untuk memastikan ID setiap catatan yang ada pasti unique.

## Cara melakukan Instalasi (Windows)
1. Pastikan anda sudah mempunyai Git terinstall dalam Mesin anda, jika masih belum punya bisa melakukan instalasi dengan melakukan download di [sini](https://git-scm.com/)  
2. Pastikan Git sudah terinstall dengan menuliskan di Command Prompt
```shell
git --version
```
3. Buka Git dan tuliskan 
```shell
git clone https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda.git
```
4. Pastikan anda sudah mempunyai NodeJS terinstall dalam Mesin anda, jika masih belum punya bisa melakukan instalasi dengan melakukan download di [sini](https://nodejs.org/en/)
5. Pastikan Node sudah terinstall dengan menuliskan di Command Prompt
```shell
node -v
```
6. Pastikan NPM juga sudah terinstall dengan menuliskan di Command Prompt
```shell
npm -v
```
7. Masuk ke folder hasil clone dari Git anda menggunakan Command Prompt (ketikkan `cd` sampai masuk ke folder project-2-BryanYehuda)
8. Tuliskan di dalam Command Prompt dan tunggu sampai prosesnya selesai
```shell
npm install
```
9. Anda sudah berhasil melakukan instalasi Notes API, untuk mejalankan API ini di localhost anda tuliskan
```shell
node ./src/server.js
```

## Cara melakukan Instalasi (Linux)
1. Pastikan anda sudah mempunyai Git terinstall dalam Mesin anda, jika masih belum punya bisa melakukan instalasi dengan mengetikkan  
```shell
sudo apt install git-all
```
2. Pastikan Git sudah terinstall dengan menuliskan di Terminal
```shell
git --version
```
3. Buka Git dan tuliskan 
```shell
git clone https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda.git
```
4. Pastikan anda sudah mempunyai NodeJS dan NPM terinstall dalam Mesin anda, jika masih belum punya bisa melakukan instalasi dengan mengetikkan  
```shell
sudo apt install nodejs
sudo apt install npm
```
5. Pastikan Node sudah terinstall dengan menuliskan di Terminal
```shell
node -v
```
6. Pastikan NPM juga sudah terinstall dengan menuliskan di Terminal
```shell
npm -v
```
7. Masuk ke folder hasil clone dari Git anda menggunakan Terminal (ketikkan `cd` sampai masuk ke folder project-2-BryanYehuda)
8. Tuliskan di dalam Terminal dan tunggu sampai prosesnya selesai
```shell
npm install
```
9. Anda sudah berhasil melakukan instalasi Notes API, untuk mejalankan API ini di localhost anda tuliskan
```shell
npm run start-prod
```

## Dokumentasi Penggunaan Post
**Menggunakan Method Post untuk menambahkan catatan A**  
Bisa dilihat response mengembalikan OK 200
![Post A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PostA.png)
**Menggunakan Method Post untuk menambahkan catatan B**  
Bisa dilihat response mengembalikan OK 200
![Post B](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PostB.png)

## Dokumentasi Penggunaan Get
**Menggunakan Method Get untuk melihat semua Catatan**  
Bisa dilihat response mengembalikan OK 200
![Get All](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetAll.png)
**Menggunakan Method Get dengan link parameter ID A untuk melihat Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Get A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetA.png)
**Menggunakan Method Get dengan link parameter ID yang tidak ada**  
Bisa dilihat response mengembalikan NOT FOUND 404
![Get A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetTidakAda.png)

## Dokumentasi Penggunaan Put
**Menggunakan Method Put untuk mengedit isi dari Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Put A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PutA.png)
**Menggunakan Method Get untuk melihat perubahan setelah diedit**  
Bisa dilihat response mengembalikan OK 200
![Put A After](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PutAAfter.png)

## Dokumentasi Penggunaan Delete
**Menggunakan Method Delete untuk menghapus Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Put A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/Delete.png)

## Hosting
API ini dilakukan hosting pada alamat http://54.197.182.218:5000
