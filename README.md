![logoUPB](gambar1/logo.png)

# Latihan18

Repository ini dibuat untuk memenuhi tugas Pertemuan 4 - Bahasa Pemrograman.

**NAMA : Abdul Aziz Anaoval** 

**NIM : 312010049**

**KELAS : TI.20.A.1**

## Langkah-Langkah Penggunaan Git

* Dwonload Git terlebih dahulu, dengan link berikut ini : [click here](https://git-scm.com) <br>

![gitscm](gambar1/GitScm.png)

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini :[Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) <br>

![installing git](gambar1/installing.png)

* Setelah installasi selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan **versi**, dengan mengetik syntax berikut : <br> 

`git --version` <br>

![GitVersion](gambar1/GitVersion.png)

* Jika muncul tampilan **git version**, berarti Git sudah **berhasil di install** dan **bisa digunakan**. Langkah pertama kita harus **mengkonfigurasi user nama dan email di Git**, dengan mengetikkan syntax berikut : <br>

`git config --global user.name "masukan nama anda"` <br>
`git config --global user.email "masukan email anda"` <br>

![Git Config](gambar1/GitConfig.png)

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut :

`git config --global user.name` <br>
`git config --global user.email` <br>

![Git User](gambar1/GitUser.png)

* Buat akun di **GitHub**,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar. <br>

* Jika akun **GitHub** sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: **Penjelasan** <br> 

> * `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)` <br>

> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)` <br> 

> * `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)` <br>

> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda` <br>

> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.` <br>

> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan` <br>

![Nama Repositori](gambar1/NamaRepositori.png)

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini : <br>

![hasil repositori yang di buat](gambar1/hasilfile.png)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link *URL git* kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.