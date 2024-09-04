<div align="center">

## LAPORAN PRAKTIKUM SISTEM OPERASI

## INSTALASI SISTEM OPERASI LINUX (UBUNTU)

*Dosen Pengampu :*\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Dr. Ahmad Zarkarsi, M. T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Sutarno, M.T.

![Logo Universitas Sriwijaya](https://github.com/user-attachments/assets/779b597e-6a81-451b-b849-34d7648e8998)
)

*Disusun Oleh:*\
Nama: Resta Gustina\
NIM : 09011282328110

*JURUSAN SISTEM KOMPUTER*  
*FAKULTAS ILMU KOMPUTER*  
*UNIVERSITAS SRIWIJAYA*  
*2024*
<br>
<br>

## Daftar Isi

</div>

> 
*[Pendahuluan](#pendahuluan)*
  > [Latar Belakang](#latar-belakang)\
  > [Tujuan](#tujuan)\
  > [Dasar Teori](#dasar-teori)

> 
*[Alat dan Bahan](#alat-dan-bahan)*

> 
*[Prosedur](#prosedur)*

> 
*[Hasil dan Pembahasan](#hasil-dan-pembahasan)*
  > [Hasil](#hasil)\
  > [Pembahasan](#pembahasan)

> 
*[Kesimpulan](#kesimpulan)*

> 
*[Daftar Pustaka](#daftar-pustaka)*

<div align="center">
<br>
<br>

## Pendahuluan

</div>

### Latar Belakang

<div align="justify">

Dalam era digital saat ini, pemahaman tentang sistem operasi menjadi semakin penting, terutama bagi mahasiswa di bidang ilmu komputer. Linux, sebagai salah satu sistem operasi open source yang populer, menawarkan berbagai keunggulan seperti fleksibilitas, keamanan, dan kustomisasi yang tinggi. Praktikum instalasi sistem operasi Linux Ubuntu ini dilakukan untuk memberikan pengalaman langsung kepada mahasiswa dalam proses instalasi dan penggunaan sistem operasi berbasis open source.
Ubuntu, sebagai salah satu distribusi Linux yang terkenal, dipilih dalam praktikum ini karena kemudahan penggunaannya dan dukungan komunitas yang luas. Melalui praktikum ini, mahasiswa diharapkan dapat memahami konsep dasar sistem operasi Linux, proses instalasi, dan konfigurasi awal. Selain itu, penggunaan VirtualBox sebagai platform virtualisasi memungkinkan mahasiswa untuk melakukan eksperimen tanpa risiko merusak sistem utama mereka.
Keahlian dalam menginstal dan mengkonfigurasi sistem operasi Linux merupakan keterampilan yang sangat berharga di dunia teknologi informasi saat ini. Dengan pemahaman yang baik tentang proses ini, mahasiswa akan lebih siap menghadapi tantangan di dunia kerja, terutama dalam lingkungan yang menggunakan sistem operasi berbasis Linux.

### Tujuan
- Mampu menggunakan sistem operasi berbasis Open Source (Linux Ubuntu)\Mengetahui dan mampu menganalisis proses instalasi sistem operasi linux menggunakan VirtualBox
- Memperdalam wawasan mengenai teknologi virtualisasi dan kegunaannya dalam mempelajari berbagai sistem operasi. 
- Menciptakan wadah eksperimen yang terisolasi dan aman untuk menjelajahi sistem Linux tanpa berisiko merusak sistem operasi utama.
- Mengaplikasikan keterampilan konfigurasi sistem Ubuntu, termasuk penyesuaian parameter pasca-instalasi, pembentukan akun pengguna, dan pengalokasian sumber daya virtual seperti RAM, penyimpanan, dan core prosesor.

### Dasar Teori
Sistem Operasi adalah kumpulan program terstruktur yang mengelola sumber daya perangkat keras (hardware) dan menyediakan layanan umum untuk aplikasi perangkat lunak (software). Sistem operasi merupakan komponen paling vital dalam sistem komputer. Beberapa aspek utama dari sistem operasi meliputi pengelolaan memori, proses, file, dan antarmuka pengguna.
Linux adalah sistem operasi open source yang gratis dan dapat disebarkan di bawah lisensi GNU. Linux merupakan turunan dari Unix dan dapat berfungsi pada berbagai jenis perangkat keras komputer. Kebebasan utama dari Linux adalah hak untuk mengakses kode sumber dan mengubahnya. Linux dapat dikendalikan melalui antarmuka baris perintah (Command Line Interface atau CLI) berbasis teks, serta memiliki antarmuka pengguna grafis (Graphics User Interface atau GUI) yang umumnya digunakan pada versi desktop. Inti dari Linux adalah KERNEL, yang menghubungkan perangkat keras dengan perangkat lunak. Salah satu distribusi Linux yang populer adalah Ubuntu.
Oracle VM VirtualBox adalah perangkat lunak virtualisasi yang memungkinkan kita menjalankan sistem operasi “tambahan” di dalam sistem operasi “utama”. Misalnya, jika Anda memiliki sistem operasi MS Windows di komputer, Anda dapat menjalankan sistem operasi lain di dalamnya tanpa mengganggu sistem yang sudah ada. Fungsi ini sangat berguna untuk uji coba dan simulasi instalasi tanpa risiko kehilangan data. Selain VirtualBox, ada juga aplikasi serupa seperti VMware dan Microsoft Virtual PC. VirtualBox dapat digunakan pada berbagai sistem operasi, termasuk Linux, Mac OS X, Windows Vista, Windows 7, Windows 8, Solaris, dan OpenSolaris.
Pada praktikum kali ini kita menggunakan Sistem Operas Linux (Ubuntu 22.04 LTS). Nama “Linux” berasal dari pembuatnya, Linus Torvalds, yang memperkenalkannya pada tahun 1991. Linux menggunakan komponen dari sistem operasi GNU (GNU’s Not UNIX), yang diumumkan oleh Richard Stallman pada tahun 1983. Kontribusi dari proyek GNU menjadi dasar bagi nama alternatif “GNU/Linux.” Linux telah lama dikenal untuk penggunaannya di server dan didukung oleh perusahaan-perusahaan komputer terkemuka seperti Intel, Dell, Hewlett-Packard, IBM, Novell, Oracle Corporation, Red Hat, dan Sun Microsystems. Selain itu, Linux digunakan sebagai sistem operasi pada berbagai jenis perangkat keras, termasuk komputer desktop, superkomputer, serta perangkat tertanam seperti pembaca buku elektronik, konsol permainan video seperti PlayStation 2, PlayStation 3, Xbox, dan juga telepon genggam serta router.


</div>

<div align="center">
<br>
<br>

## Alat dan Bahan

</div>

<div align="justify">

- PC atau Laptop
- Software Virtual Box
- ISO Linux (Ubuntu 22.04 LTS)

</div>

<div align="center">
<br>
<br>

## Prosedur

</div>

<div align="justify">

1. Buka virtual box, pilih New
   
   ![Langkah 1](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/bukak%20vitual%20box.png)
   
2. Beri nama virtual yang akan dibuat, type dan versi, disini saya memberi nama Linux-Ubuntu
   
   ![Langkah 2](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/create%20virtual%20machine%202.png)
   
3. Kemudian pada Memory Size, kita setting memory yang akan kita sediakan

   ![Langkah 3](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/memory%20size.png)
   
4. Kemudian pada Hard Disk File Type ubah pilih VHD (Virtual Hard Disk)

   ![Langkah 4](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/hardisk%20file%20type.png)

5. Lalu klik Next, dan pada File Location And Size setting sesuaikan space yang dibutuhkan

   ![Langkah 5](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/file%20locatio%20and%20size.png)

6. Pilih Create. Lalu, klik Optical Drive pada Storage virtual box untuk memasukkan file iso ubuntu nya

   ![Langkah 6](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/isi%20file%20iso%20ubuntu.png)



7. Tahap berikutnya yaitu instalasi ubuntu. Klik Star, setelah muncul menu Welcome Dan pilih bahasa instalasi dan bahasa sistem operasi kemudian klik option Install Ubuntu. Jika hanya ingin mencoba tanpa instalasi ubuntu, pilih option Try Ubuntu


8. Pada tampilan berikutnya Installation Type, kita pilih Erase disk and install Ubuntu. Selanjutnya pilih Continue.

   ![Langkah 8](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/installation%20type.png)

9. Pada time zone pilih lokasi nya sesuai yang digunakan, kemudian pilih Continue

    ![Langkah 9](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/tempat.png)

10. Kemudian kita akan menginputkan username dan password yang digunakan utnuk login ke sistem operasi. Setelah selesai silakan klik Continue
    Pada pengaturan login sistem operasi, terdapat dua pilihan utama:\
    •	"Log in automatically" memungkinkan pengguna untuk langsung mengakses desktop sistem operasi tanpa perlu memasukkan kredensial. Ketika komputer dinyalakan, sistem akan melewati proses autentikasi dan pengguna dapat segera menggunakan perangkatnya.\
    •	"Require my password to log in" mengharuskan pengguna untuk melakukan verifikasi identitas sebelum dapat mengakses sistem. Saat komputer dihidupkan, layar login akan muncul, meminta pengguna untuk memasukkan nama pengguna dan kata sandi sebelum dapat melanjutkan ke antarmuka desktop.


    ![Langkah 10](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/input%20nama%20dan%20password%20linux.png)

11. Tahap selanjutnya adalah proses transfer dan instalasi file. File-file penting disalin ke lokasi yang tepat dalam sistem berkas, sementara komponen perangkat lunak diinstal dan diatur. Langkah ini menyiapkan sistem operasi agar berfungsi optimal setelah instalasi.

![Langkah 11](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/copy%20ubuntu%20install.png)

12. Setelah proses Installation Complete, klik Restart Now.

![Langkah 12](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/restart%20ubuntu.png)

13. Untuk masuk klik user pada sistem operasi, masukkan password yang telah di buat saat proses instalasi. Klik Enter

![Langkah 13](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/loin%20menggunakan%20pw.png)

14. Maka akan muncul tampilannya akan seperti pada gambar di bawah ini :

![Langkah 14](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/5e1891f268f8f841c6435f9486aaf6a32ef3d679/tampilan%20selesai%20desktop.png)


<br>
<br>

## Hasil dan Pembahasan

</div>

<div align="justify">

### Hasil
Hasil dari praktikum ini adalah sebagai berikut:
-	[x] Berhasil menginstal dan mengkonfigurasi Oracle VM VirtualBox pada komputer host.
-	[x] Berhasil membuat mesin virtual baru dengan spesifikasi yang sesuai untuk Ubuntu:
    - Alokasi RAM: 4096 MB
    -	Alokasi penyimpanan: 40 GB
    -	Jumlah core prosesor: 1
-	[x] Berhasil menginstal Ubuntu 22.04 LTS pada mesin virtual yang telah dibuat.
-	[x] Berhasil melakukan konfigurasi awal Ubuntu, termasuk:
    -	Pemilihan bahasa dan zona waktu
    -	Pembuatan akun pengguna
    -	Pengaturan koneksi jaringan
-	[x] Berhasil melakukan boot ke sistem operasi Ubuntu yang baru diinstal dan memverifikasi fungsionalitas dasarnya.

### Pembahasan
-	Persiapan dan Konfigurasi VirtualBox:\
Penggunaan VirtualBox memungkinkan instalasi Ubuntu tanpa mempengaruhi sistem operasi host. Ini memberikan lingkungan yang aman untuk eksperimen dan pembelajaran. Alokasi sumber daya (RAM, penyimpanan, core prosesor) harus dipertimbangkan dengan cermat untuk memastikan kinerja yang optimal dari sistem virtual.

-	Proses Instalasi Ubuntu:\
Instalasi Ubuntu berjalan lancar tanpa kendala signifikan. Antarmuka instalasi Ubuntu yang user-friendly memudahkan proses, bahkan bagi pengguna yang baru mengenal Linux. Pemilihan opsi "Try or Install Ubuntu" memungkinkan pengguna untuk mencoba sistem sebelum melakukan instalasi penuh, yang merupakan fitur yang berguna untuk pengenalan awal.

-	Konfigurasi Sistem:\
Proses konfigurasi awal Ubuntu, termasuk pemilihan bahasa, pengaturan zona waktu, dan pembuatan akun pengguna, berjalan dengan baik. Ini mendemonstrasikan fleksibilitas Ubuntu dalam menyesuaikan dengan kebutuhan pengguna dari berbagai latar belakang dan lokasi geografis.

-	Performa Sistem:\
Setelah instalasi, Ubuntu berjalan dengan baik di lingkungan virtual. Meskipun ada sedikit penurunan performa dibandingkan dengan instalasi pada hardware langsung, hal ini wajar dalam lingkungan virtualisasi. Penggunaan Guest Additions VirtualBox dapat meningkatkan performa dan integrasi antara sistem host dan guest.

-	Pembelajaran dan Implikasi:\
Praktikum ini memberikan wawasan berharga tentang proses instalasi sistem operasi dan manajemen sumber daya komputer. Mahasiswa dapat melihat secara langsung bagaimana sistem operasi diinstal dan dikonfigurasi, yang penting untuk pemahaman yang lebih dalam tentang cara kerja sistem operasi.

-	Tantangan dan Solusi:\
Beberapa tantangan yang mungkin dihadapi termasuk masalah kompatibilitas hardware virtual dan alokasi sumber daya yang tidak mencukupi. Solusinya melibatkan penyesuaian pengaturan VirtualBox dan alokasi sumber daya yang tepat.

-	Penerapan Konsep Sistem Operasi:\
Praktikum ini mengilustrasikan konsep-konsep penting dalam sistem operasi seperti manajemen memori, penjadwalan prosesor, dan sistem file. Mahasiswa dapat melihat bagaimana konsep-konsep ini diterapkan dalam konteks nyata instalasi dan konfigurasi sistem.


</div>

<div align="center">
<br>
<br>

## Kesimpulan

</div>

<div align="justify">

Berdasarkan praktikum yang telah dilakukan, dapat disimpulkan :
1.	Proses instalasi Ubuntu 22.04 LTS pada VirtualBox dapat dilakukan dengan langkah-langkah yang sistematis dan relatif mudah diikuti.
2.	Penggunaan VirtualBox sebagai platform virtualisasi memungkinkan eksperimen dengan sistem operasi Linux tanpa mempengaruhi sistem utama, memberikan lingkungan belajar yang aman dan fleksibel.
3.	Pemahaman tentang berbagai sistem berkas seperti ext4, swap, dan btrfs sangat penting dalam proses instalasi dan manajemen sistem Linux.
4.	Konfigurasi awal seperti pemilihan bahasa, pengaturan zona waktu, dan pembuatan akun pengguna merupakan langkah penting dalam menyesuaikan sistem operasi dengan kebutuhan pengguna.
5.	Pemilihan mount point "/" memiliki peran krusial dalam struktur dan fungsi sistem operasi Linux.
6.	Praktikum ini memberikan dasar yang kuat bagi mahasiswa untuk memahami proses instalasi dan konfigurasi dasar sistem operasi Linux, yang merupakan keterampilan penting dalam bidang teknologi informasi.
Melalui praktikum ini, mahasiswa tidak hanya memperoleh pengetahuan teknis tentang instalasi Linux, tetapi juga mengembangkan keterampilan pemecahan masalah dan adaptasi terhadap teknologi baru. Pengalaman ini akan sangat berharga dalam menghadapi tantangan di dunia teknologi informasi yang terus berkembang.


</div>

<div align="center">
<br>
<br>

## Daftar Pustaka

</div>

<div align="justify">

- Modul.Praktikum 1 Sistem Operasi
- Ubuntu Documentation. (2024). Official Ubuntu Documentation. https://help.ubuntu.com/
- Ubuntu Documentation. (2024). Linux Filesystems (ext4, ext3, btrfs).
- Sobell, M. G. (2021). A Practical Guide to Ubuntu Linux (5th ed.). Addison-Wesley.
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers



</div>

----
<br>
<br>


## Informasi Mahasiswa
- *Nama:* Resta Gustina
- *NIM:* 09011282328110
- *Kelas:* SK3B

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi *mount point*?

![Mount Point Selection](https://github.com/Restagustina/Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux-Ubuntu-_Resta-Gustina/blob/ad289803a14b4fbcec16d937db26914cf67e987b/Tugas1/image.png)

<br>

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi *mount point*:

1. Root filesystem : "/" merepresentasikan root filesystem atau direktori utama dalam sistem Linux. Semua direktori lain berada di bawahnya.
2. Titik awal hierarki : Ini menjadi titik awal dari seluruh struktur direktori sistem operasi.
3. Penempatan sistem : Memilih "/" memastikan bahwa seluruh sistem operasi dan file-file pentingnya akan diinstal pada partisi ini.
4. Akses sistem : Tanpa mount point "/", sistem tidak akan memiliki lokasi dasar untuk mengakses file dan direktori penting.
5. Fungsionalitas : Ini penting untuk memastikan sistem operasi dapat berjalan dan berfungsi dengan benar setelah instalasi.

Dengan memilih "/" sebagai Mount Point, Anda menentukan lokasi utama di mana Ubuntu akan menginstal dan menyimpan semua komponen sistem yang diperlukan untuk operasi yang tepat.


</div>

----
<br>
<br>


<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

*1. ext4:*
  - Sistem berkas standar untuk banyak distribusi Linux
  - Mendukung volume besar hingga 1 exabyte
  - Fitur journaling untuk integritas data
  - Kinerja tinggi dan efisiensi alokasi ruang


*2. ext3:*
  - Pendahulu ext4, masih digunakan di beberapa sistem lama
  - Memiliki journaling tetapi dengan batasan ukuran dan fitur dibanding ext4
  - Kompatibel dengan ext2


*3. swap:*
  - Bukan sistem berkas, melainkan ruang pada disk untuk memori virtual
  - Digunakan ketika RAM fisik penuh
  - Meningkatkan kapasitas memori sistem, tapi lebih lambat dari RAM


*4. NTFS (New Technology File System):*
  - Sistem berkas standar untuk Windows
  - Mendukung file dan volume besar
  - Fitur keamanan dan kompresi built-in
  - Kurang optimal untuk sistem Linux


*5. FAT32:*
  - Sistem berkas sederhana, kompatibel dengan banyak sistem
  - Batasan ukuran file maksimal 4GB
  - Sering digunakan untuk perangkat penyimpanan portabel
  - Tidak memiliki fitur keamanan lanjutan


*6. Btrfs6(B-tree File System):*
  - Sistem berkas modern untuk Linux dengan fitur canggih
  - Mendukung snapshot, kompresi, dan RAID software
  - Fokus pada skalabilitas dan toleransi kesalahan
  - Masih dalam pengembangan aktif


</dir>
