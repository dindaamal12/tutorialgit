# Version Control System
Adalah sebuah kumpulan perangkat lunak yang sudah terintegrasi dan digunakan untuk membantu software engineer mengelola perubahan dalam source code dari waktu ke waktu.

## GIT
![image](https://user-images.githubusercontent.com/92708806/138216394-3c7dbb0c-c5b4-4a1d-a7af-bb089865a823.png)
<p>Merupakan alat pengontrol versi yangbertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.
  
 ### Instalasi GIT
1.Download GIT pada link berikut:
https://git-scm.com/downloads
  
  <img width="377" alt="2" src="https://user-images.githubusercontent.com/92708806/138261617-34e82785-a49c-4cee-b296-4cb1c70f2bc1.PNG">
  
  
  
Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >> sampai muncul sebagai berikut:
  
  Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.
  ![21](https://user-images.githubusercontent.com/92708806/138262820-dfb1e0ed-2f98-47db-bb71-4f82018ee05d.jpg)

  

Setelah selesai, kita bisa langsung klik finish.
  
  ![22](https://user-images.githubusercontent.com/92708806/138263067-2834c352-bce6-461b-b26c-f54a7aa21e7c.jpg)


Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah
  
  ![23](https://user-images.githubusercontent.com/92708806/138263701-a955ee01-70a5-4ea5-b97f-38fbcd4aeb13.JPG)
  
  ![6](https://user-images.githubusercontent.com/92708806/138263820-0d895426-c7f4-455c-a3c6-eabe371d0404.jpg)
  
 
  
  ### Cara penggunaan Git
  Setelah berhasil install ke Git, selanjutnya
  
  ### Login Git
  masukkan username & email Git menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
  ![24](https://user-images.githubusercontent.com/92708806/138264634-c742b661-ca4e-45b3-81e1-e16b956edcc8.JPG)
  
  
  Selanjutnya untuk memastikan proses login berhasil, masukkan perintah berikut.
  ![25](https://user-images.githubusercontent.com/92708806/138265013-db43e6f9-410c-4b80-a141-5bdd0af5a646.JPG)

  
  ![7](https://user-images.githubusercontent.com/92708806/138265084-b10bc9de-9349-4e64-9166-39f2a5e73bf2.JPG)

  
  ### Login Github
  Langkah kedua menggunakan Git adalah harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.
  ![26](https://user-images.githubusercontent.com/92708806/138265408-66a75e06-9117-4849-bc5f-83e5b4391a5d.jpg)

  
  ### Buat Repository
  Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
  ![8](https://user-images.githubusercontent.com/92708806/138265645-5b90eeb0-89ed-4e10-8fe9-7e31c3938093.JPG)

  
  Kemudian akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini. perlu mengisi detail informasi berikut:

Nama Repository : digunakan untuk identitas repository yang dibuat.
Deskripsi Repository : berfungsi untuk deskripsi dari repository yang dibuat.
Jenis Repository : jenis repository dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda. Setelah mengisi detail informasi di atas,
klik Create Repository.
  ### Buat Folder pada Windows
  Selanjutnya, perlu membuat folder pada local disk komputer. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah di buat.
  ![9](https://user-images.githubusercontent.com/92708806/138265951-8727b0d5-0806-445d-b1f1-6a335f6d4392.JPG)
  
  
  ### Buka Folder Menggunakan Git Bash
  ![10](https://user-images.githubusercontent.com/92708806/138266124-4bbcfef4-e727-4488-940c-340502dd1f4f.jpg)
  
  
  Setelah berhasil membuat folder pada local disk komputer, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini.
  ![11](https://user-images.githubusercontent.com/92708806/138266451-b4063371-746a-47c9-8846-c30ea35e1690.JPG)

  
  ### Ubah Folder Menjadi Repository
Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:
  
  ![27](https://user-images.githubusercontent.com/92708806/138266770-66313de3-d062-4b9b-8e72-a9197ba2ef9d.JPG)
  
  
  ![12](https://user-images.githubusercontent.com/92708806/138267011-5891ac94-713d-42a4-a911-f7e74f7812c5.JPG)
  
  
  ### Tambahkan File ke Repository
  Untuk bisa menambahkan file ke repository GitHub,perlu menerapkan langkah-langkah di bawah ini:

Buat file di folder yang sudah dibuat (Eza-Git). Contohnya, di sini membuat file javascript : index.php Buka GitBash lalu masukkan perintah berikut:
  
  
![28](https://user-images.githubusercontent.com/92708806/138267463-c3437808-4a15-420b-b9d8-2b914daea466.JPG)
  
  Perintah tersebut tidak akan menghasilkan output apa pun.
  
  ### Buat Commit
  Selanjutnya, perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:
  
  ![29](https://user-images.githubusercontent.com/92708806/138267815-10fe4340-01be-41a6-ba6f-403fa5713d27.JPG)

  
  bebas membuat membuat nama Commit apa saja.
  
  ### Remote Repository Github
  
  Remote repository berfungsi untuk mengupload file yang telah di buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:
  
 ![31](https://user-images.githubusercontent.com/92708806/138269256-1ce5a379-0c2b-46b1-8b17-4b5360d91b02.JPG)

  
  Perintah di atas tidak akan menghasilkan output apa pun.
  
  ### Push ke GitHub
  Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:
  
  ![32](https://user-images.githubusercontent.com/92708806/138269660-6fe5852a-655f-40ce-8018-4846f722af85.JPG)
  
  
  
  Perintah di atas akan menampilkan pop up sign in GitHub.
login untuk melanjutkan proses push ke GitHub.

Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah:
![13](https://user-images.githubusercontent.com/92708806/138269836-3e4bd3f1-6251-4dac-9367-531a93b1a2e4.JPG)
  
  
  ### Cek File
  Setelah itu, cek repository yang telah di buat. akan mendapati file-file yang telah ditambahkan sebelumnya. Pada tutorial ini kami menambahkan tiga file, yaitu index.php, ScreenShot/, dan README.md.

![14](https://user-images.githubusercontent.com/92708806/138270038-60f13acb-4ac3-4633-8596-b8da419acb8c.JPG)

  
  ### Kesimpulan
  
  Cara menggunakan Git ini wajib diketahui dan dikuasai oleh semua developer karena akan sangat membantu dalam mengerjakan project pembuatan website. Demikian penjelasan tentang cara menggunakan Git. Jika masih ada pertanyaan, jangan sungkan untuk meninggalkan di kolom komentar. Jangan lupa juga subscribe untuk mendapatkan informasi terbaru dari kami.


  



  
  
