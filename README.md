# Notes API

## English
This repository was created to store the code and documentation of the Second Project on the "Integrative Programming" Course at the Sepuluh Nopember Institute of Technology. In this project, I was assigned to make **API** or **Application Programming Interface**. In this project, I use the API to make **Notes** or in Indonesian it is **Notes**.

### What is Notes API?
This Notes API project is written in the [**JAVASCRIPT**](https://www.javascript.com/) Programming Language with **EcmaScript 6** standard due to the many uses of this language in making Web Servers and also Web Applications and I took advantage of this utility to create this Notes API. Making this project is also done by utilizing [**NodeJS**](https://nodejs.org/en/) as a runtime that allows Javascript to be run in various environments that are not limited to the browser environment only.

This project will later allow users to create, read, edit, and also delete (**CRUD**) various kinds of records stored in the API. This API will be hosted so that later it can be directly accessed using [**POSTMAN**](https://www.postman.com/) or using the creation of **Front-end Website** that utilizes the caching API. Later the Server and Client will conduct data transactions via the HTTP protocol.

### Repository Tree
- **References folder** : contains 2 folders, namely code that stores references and exercises for writing Javascript code and also the Hapi Framework to realize this API, and also a documentation folder containing images to be included in this readme.
- **Folder src** : contains the main API code in Javascript in the Hapi Framework
- package.json : contains any package information used in making this API

### Method and Framework Used
There are 4 methods used in making this project, namely:
- **POST** : Used to add notes to the API for storage
- **GET** : Used to display records that have been stored in the API so that they can be read
- **PUT** : Used to edit or update the contents of records stored in the API
- **DELETE** : Used to delete records stored in the API

This project uses the [**HAPI**](https://hapi.dev/) Framework because it provides a complete environment for developing complex web servers. When using Hapi, we don't need other tools to apply the **authentication, tokenize, cors,** layers and so on.

In addition, this project will use NodeJS's default Package Manager, namely [**NPM**](https://www.npmjs.com/) which is used to make package settings to make it easier to manage and monitor. There are also several package dependencies that are used to make this API run which will be installed automatically, namely **ESlint** which is used to perform fire and coercion **Code Styling Javascript**, **nodemon** which is used to ensure the server is running continuously despite code changes, **Hapi** which of course is used as the Framework of this API, and also **nanoid** which is used to ensure the ID of each existing record must be unique.

### How to do the Installation (Windows)
1. Make sure you already have Git installed on your machine, if you don't have it, you can install it by downloading it at [here](https://git-scm.com/)
2. Make sure Git is installed by typing in Command Prompt
```shell
git --version
```
3. Open Git and write
```shell
git clone https://github.com/2021-IT-Integrative-Programming/project-2-BryanYehuda.git
```
4. Make sure you already have NodeJS installed on your machine, if you don't have it, you can install it by downloading it here (https://nodejs.org/en/)
5. Make sure Node is installed by writing in Command Prompt
```shell
node -v
```
6. Make sure NPM is also installed by writing in Command Prompt
```shell
npm -v
```
7. Go to the cloned folder from your Git using the Command Prompt (type `cd` until it enters the project-2-BryanYehuda folder)
8. Write it in Command Prompt and wait until the process is complete
```shell
npm install
```
9. You have successfully installed the Notes API, to run this API on your localhost write
```shell
node ./src/server.js
```

### How to install (Linux)
1. Make sure you already have Git installed on your machine, if you still don't have it, you can install it by typing
```shell
sudo apt install git-all
```
2. Make sure Git is installed by typing in Terminal
```shell
git --version
```
3. Open Git and write
```shell
git clone https://github.com/2021-IT-Integrative-Programming/project-2-BryanYehuda.git
```
4. Make sure you already have NodeJS and NPM installed on your machine, if you still don't have it, you can install it by typing
```shell
sudo apt install nodejs
sudo apt install npm
```
5. Make sure Node is installed by writing in Terminal
```shell
node -v
```
6. Make sure NPM is also installed by writing in Terminal
```shell
npm -v
```
7. Go to the cloned folder from your Git using Terminal (type `cd` until it enters the project-2-BryanYehuda folder)
8. Write it in Terminal and wait for the process to finish
```shell
npm install
```
9. You have successfully installed the Notes API, to run this API on your localhost write
```shell
npm run start-prod
```

### License
This Repository has **MIT License.**   
This license allows the user to make any changes to the program code. This license only requires the user to include the license and author's copyright in the redistributed code and there is no prohibition against using the trademark of the original author. In addition, the user also has no right to sue the manufacturer when there is damage to the software.

## Bahasa
Repository ini dibuat untuk menyimpan kode dan juga dokumentasi dari Proyek Kedua pada Mata Kuliah "Pemrograman Integratif" di Institut Teknologi Sepuluh Nopember. Pada proyek kali ini, saya ditugaskan untuk melakukan pembuatan **API** atau kepanjangannya **Application Programming Interface**. Pada proyek ini, saya memanfaatkan penggunaan API untuk melakukan pembuatan **Notes** atau dalam Bahasa Indonesianya adalah **Catatan**. 

Dalam Readme ini akan dijelaskan mengenai apa itu Notes API, struktur repository, Method dan framework apa saja yang digunakan, cara instalasi, dokumentasi penggunaan, dan juga tempat hosting dari Notes API ini. Proyek ini sudah dilakukan testing dan tidak ditemukan adanya Bug ataupun error yang mengganggu. Terima kasih atas waktu dan perhatiannya.

### Penjelasan Notes API
Proyek Notes API ini dituliskan dalam Bahasa Pemrograman [**JAVASCRIPT**](https://www.javascript.com/) dengan standard **EcmaScript 6** dikarenakan banyaknya kegunaan bahasa ini dalam melakukan pembuatan Web Server dan juga Web Application dan saya memanfaatkan kegunaan ini untuk membuat Notes API ini. Pembuatan Proyek ini juga dilakukan dengan memanfaatkan [**NodeJS**](https://nodejs.org/en/) sebagai runtime yang memungkinkan Javascript untuk bisa dijalankan di berbagai macam Environment yang tidak terbatas pada lingkungan Browser saja.

Proyek ini nanti akan memungkinkan user untuk membuat, membaca, melakukan editing, dan juga menghapus (**CRUD**) berbagai macam catatan yang tersimpan di dalam API. API ini akan dilakukan hosting sehingga nanti bisa langsung dilakukan akses menggunakan [**POSTMAN**](https://www.postman.com/) ataupun menggunakan pembuatan **Website Front-end** yang memanfaatkan caching API. Nantinya Server dan juga Client akan melakukan transaksi data melalui protokol HTTP.

### Struktur Repository  
- **Folder references** : berisi 2 folder yaitu code yang menyimpan referensi dan juga latihan penulisan kode Javascript dan juga Framework Hapi untuk mewujudkan API ini, dan juga folder documentation yang berisi gambar-gambar untuk dimasukkan ke dalam readme ini.
- **Folder src** : berisi kode utama API dalam bahasa Javascript dalam Framework Hapi
- package.json : berisi informasi package apa saja yang digunakan dalam pembuatan API ini

### Method dan Framework yang Digunakan  
Ada 4 Method yang digunakan dalam pembuatan Proyek ini yaitu:
- **POST** : Digunakan untuk menambahkan catatan ke dalam API untuk dilakukan penyimpanan
- **GET** : Digunakan untuk menampilkan catatan yang telah tersimpan di API agar bisa dibaca
- **PUT** : Digunakan untuk melakukan editing atau update terhadap isi catatan yang tersimpan di API
- **DELETE** : Digunakan untuk menghapus catatan yang tersimpan di API

Proyek ini menggunakan Framework [**HAPI**](https://hapi.dev/) karena menyediakan environment yang lengkap untuk mengembangkan web server yang kompleks. Bila menggunakan Hapi, kita tak perlu tools lain untuk menerapkan layer **authentication, tokenize, cors,** dan lain sebagainya. 

Selain itu Proyek ini akan menggunakan Package Manager bawaan NodeJS yaitu [**NPM**](https://www.npmjs.com/) yang digunakan untuk melakukan pengaturan package agar lebih mudah diatur dan diawasi. Ada juga beberapa package Dependencies yang digunakan agar API ini bisa berjalan yang nantinya akan terinstall secara otomatis yaitu **ESlint** yang digunakan untuk melakukan perapian dan pemaksaan **Code Styling Javascript**, **nodemon** yang digunakan untuk memastikan Server berjalan terus-menerus meskipun ada penggantian kode, **Hapi** yang tentu saja digunakan sebagai Framework dari API ini, dan juga **nanoid** yang digunakan untuk memastikan ID setiap catatan yang ada pasti unique.

### Cara melakukan Instalasi (Windows)
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

### Cara melakukan Instalasi (Linux)
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

### Dokumentasi Penggunaan Post
**Menggunakan Method Post untuk menambahkan catatan A**  
Bisa dilihat response mengembalikan OK 200
![Post A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PostA.png)
**Menggunakan Method Post untuk menambahkan catatan B**  
Bisa dilihat response mengembalikan OK 200
![Post B](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PostB.png)

### Dokumentasi Penggunaan Get
**Menggunakan Method Get untuk melihat semua Catatan**  
Bisa dilihat response mengembalikan OK 200
![Get All](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetAll.png)
**Menggunakan Method Get dengan link parameter ID A untuk melihat Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Get A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetA.png)
**Menggunakan Method Get dengan link parameter ID yang tidak ada**  
Bisa dilihat response mengembalikan NOT FOUND 404
![Get A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/GetTidakAda.png)

### Dokumentasi Penggunaan Put
**Menggunakan Method Put untuk mengedit isi dari Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Put A](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PutA.png)
**Menggunakan Method Get untuk melihat perubahan setelah diedit**  
Bisa dilihat response mengembalikan OK 200
![Put A After](https://github.com/2021-IT-Pemrograman-Integratif/project-2-BryanYehuda/blob/master/references/documentation/PutAAfter.png)

### Dokumentasi Penggunaan Delete
**Menggunakan Method Delete untuk menghapus Catatan A**  
Bisa dilihat response mengembalikan OK 200
![Delete](https://github.com/BryanYehuda/NotesAPI/blob/main/references/documentation/Delete.png)

### Lisensi
Repository ini memiliki **Lisensi MIT.**      
Lisensi ini membolehkan pengguna untuk melakukan perubahan apapun pada kode program. Lisensi ini hanya mewajibkan pengguna untuk menyertakan lisensi dan copyright pembuat pada kode yang didistribusikan ulang dan tidak ada larangan untuk menggunakan trademark dari pembuat asli. Selain itu pengguna juga tidak berhak untuk menuntut pembuat ketika terjadi kerusakan pada perangkat lunak tersebut.

