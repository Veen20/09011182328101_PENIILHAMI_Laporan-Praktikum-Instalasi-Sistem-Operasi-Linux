# Laporan-Praktikum-Instalasi-Sistem-Operasi-Linux

<div align="center">

## LAPORAN PRAKTIKUM INSTALASI SISTEM OPERASI LINUX

*Dosen Pengampu:*\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Sutarno, M.T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Dr. Ahmad Zarkarsi, M. T.



<img src="https://github.com/user-attachments/assets/b086809c-d41c-4331-a4f6-93500d076a9c" alt="Alt Text" width="400">

*Disusun Oleh:*\
NAMA        : PENI ILHAMI\
NIM         : 09011182328101\
KELAS       : SK3B

*PRODI SISTEM KOMPUTER*  
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
  > [Landasan Teori](#landasan-teori)

>
*[Alat dan Bahan](#alat-dan-bahan)*
  > [Alat](#alat)\
  > [Bahan](#bahan)

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

Dalam era digital yang terus berkembang, penguasaan terhadap sistem operasi (OS) menjadi keahlian yang sangat diperlukan, terutama bagi mereka yang terlibat dalam bidang teknologi informasi. Linux, sebagai salah satu sistem operasi open-source yang paling populer, memiliki berbagai distribusi yang digunakan secara luas, salah satunya adalah Ubuntu. Versi Ubuntu 22.04.4 LTS, menawarkan peningkatan dalam performa, stabilitas, dan fitur keamanan yang membuatnya menjadi pilihan yang menarik bagi pengguna dari berbagai kalangan, mulai dari pengembang perangkat lunak hingga administrator sistem.\
Virtualisasi adalah salah satu teknologi yang memainkan peran penting dalam pengembangan dan pengujian perangkat lunak. Dengan menggunakan perangkat lunak virtualisasi seperti VirtualBox 7.0.20. Melalui praktikum ini, diharapkan dapat menguasai langkah-langkah instalasi, pengaturan konfigurasi dasar, serta troubleshooting dasar yang sering dihadapi selama instalasi. \
Dengan pemahaman ini, diharapkan dapat meningkatkan keterampilan teknis dalam mengolah dan memelihara lingkungan sistem operasi berbasis Linux, yang pada gilirannya akan memperluas peluang dalam dunia kerja yang semakin kompetitif.


### Tujuan
•	Mampu mengetahui prosedur instalasi pada sistem operasi Linux Ubuntu menggunakan VirtualBox.
•	Mengenalkan konsep virtualisasi menggunakan VirtualBox.
•	Mampu menguasai langkah-langkah instalasi, pengaturan konfigurasi dasar, serta troubleshooting dasar yang sering dihadapi selama instalasi.

### Landasan Teori
-	Ubuntu merupakan salah satu distribusi Linux yang terkenal dan banyak digunakan karena kestabilan, keamanan, dan dukungan komunitas yang kuat. Versi 24.04.4 LTS (Long Term Support) dari Ubuntu dirancang untuk memberikan dukungan jangka panjang, termasuk pembaruan keamanan dan perbaikan bug selama lima tahun setelah dirilis. Dengan antarmuka pengguna yang mudah digunakan dan dukungan untuk berbagai jenis perangkat keras, Ubuntu menjadi pilihan yang ideal untuk server, desktop.
-	VirtualBox adalah perangkat lunak virtualisasi yang memungkinkan pengguna menjalankan sistem operasi lain di dalam lingkungan komputer yang sudah ada tanpa perlu melakukan instalasi langsung pada perangkat keras. Perangkat lunak ini mendukung berbagai sistem operasi seperti Linux, Windows, dan macOS, serta memungkinkan pengguna melakukan pengujian atau pengembangan perangkat lunak dalam lingkungan yang terisolasi.
- Proses instalasi sistem operasi di VirtualBox melibatkan beberapa langkah, dimulai dengan pembuatan mesin virtual yang mengalokasikan sumber daya komputer seperti CPU, RAM, dan ruang dis untuk sistem operasi yang akan diinstal.Setelah mesin virtual siap, pengguna dapat memuat file ISO Ubuntu 24.04.4 LTS untuk memulai instalasi, yang mencakup pengaturan bahasa, partisi disk, dan konfigurasi awal sistem.
-	Vistualisasi menawarkan berbagai keuntungan, seperti kemudahan dalam mengelola lingkungan pengujian, isolasi sistem yang aman, dan kemampuan untuk menjalankan beberapa sistem operasi sekaligus. Namun, terdapat juga tantangan, seperti performa yang mungkin lebih rendah dibandingkan dengan instalasi langsung pada perangkat keras, serta kebutuhan sumber daya yang lebih besar pada komputer host.


</div>

<div align="center">
<br>
<br>

## Alat dan Bahan

</div>

<div align="justify">

### Alat dan Bahan
•	Seperangkat PC atau laptop\
•	Modul praktikum\
•	Software Virtual Box\
•	ISO Linux (22.04.4 LTS)\
•	Jaringan Internet\
•	Ruang Penyimpanan



</div>

<div align="center">
<br>
<br>

## Langkah-langkah

</div>

<div align="justify">

1. Instal VirtualBox dari situs oracle VirtualBox dan unduh file ISO Ubuntu Versi 24.04.4 LTS dari sumber yang ada.
2. Buka aplikasi VirtualBox, kemudian pilih opsi Baru/New.
   
   <img width="315" alt="Langkah pertama" src="https://github.com/user-attachments/assets/25e850d8-9bbc-471a-bbed-0250be9b739d">

4. Setelah tampil seperti ini,tentukan Nama, folder penyimpanan, serta masukan ISO Ubuntu 24.04.4 LTS. Kemudian klik lanjut

   <img width="315" alt="Langkah Kedua" src="https://github.com/user-attachments/assets/f91f8886-d654-4bbf-8813-c6c850db01a8">

6. Tuliskan nama pengguna dan kata sandi yang diinginkan

   <img width="315" alt="langkah ketiga" src="https://github.com/user-attachments/assets/85e527dc-d6c4-4de0-a8ac-e74c5f66ce99">

7. Kemudian tentukan besaran Penyimpanan yang akan di alokasikan sesuai dengan spesifikasi laptop

   <img width="315" alt="Langkah keempat" src="https://github.com/user-attachments/assets/275a35f2-8832-4edb-9712-398043534770">

8. Kemudian akan muncul tampilan ringkasan, cukup klik selesai

   <img width="315" alt="langkah kelima" src="https://github.com/user-attachments/assets/d47df5e6-6d73-41cb-a7ca-b4d20621018d">

9. Setelah itu masuk ke pengaturan, ke opsi jaringan dan bagian adaptor 1 di ganti jaringan internal
    
   <img width="315" alt="langkah keenam" src="https://github.com/user-attachments/assets/78cc6d6a-790e-42d1-8ab0-cde9025229f7">

11. Kemudian pilih opsi start atau tampilkan, akan muncul banyak pilihan bahasa, pilih english
    
   <img width="315" alt="langkah ketujuh" src="https://github.com/user-attachments/assets/2092ea74-ef06-43cf-ab8a-d16061a466c2">

12. Klik pada peta Indonesia, Jakarta

    <img width="315" alt="langkah kedelapan" src="https://github.com/user-attachments/assets/7561761d-04a5-40e9-a97e-bca92780cb67">

13. Masukan nama pengguna beserta kata sandi yang dibuat di awal

    <img width="315" alt="langkah kesembilan" src="https://github.com/user-attachments/assets/7352e6a0-2cfc-4cd8-8136-d21849189e17">

12. Pada tampilan seperti ini pilih opsi Restart Now
    
    <img width="315" alt="langkah kesepuluh" src="https://github.com/user-attachments/assets/71db9009-0ef1-4a91-961e-15bcfebe79a2">

14. Tunggu hingga muncul nama pengguna lalu klik di bagian nama pengguna kemudian masukan kata sandi
   
    <img width="315" alt="Langkah ke sebelas" src="https://github.com/user-attachments/assets/aacb7bb0-2dab-4b68-9a7d-63bf1a7b743b">

14. Tunggu beberapa saat, akan muncul beberapa opsi cukup di next in saja sampai muncul done

    <img width="315" alt="langkah ke duabelas" src="https://github.com/user-attachments/assets/75b855c5-f80b-48ca-957a-27788d854179">

15. Ubuntu 24.04.4 LTS telah selesai di instal, ketika telah selesai digunakan jangan lupa untuk mematikan mesin virtualnya.

    <img width="315" alt="Ubuntu" src="https://github.com/user-attachments/assets/d8f3a332-1ff8-4423-83bc-cd346220816a">

</div>

   
<div align="center">
<br>
<br>

## Hasil dan Pembahasan

</div>

<div align="justify">

### Hasil
Hasil dari praktikum ini adalah sebagai berikut:
-	[x] Berhasil menginstal dan mengkonfigurasi Oracle VM VirtualBox pada komputer host.
-	[x] Berhasil membuat mesin virtual baru dengan spesifikasi yang sesuai untuk Ubuntu:
    - Alokasi RAM: 5199 MB
    -	Alokasi penyimpanan: 20 GB
    -	Jumlah core prosesor: 1
-	[x] Berhasil menginstal Ubuntu 24.04 LTS pada mesin virtual yang telah dibuat.
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

- Praktikum instalasi Ubuntu pada mesin virtual memberikan pengalaman hands-on yang berharga dalam manajemen sistem operasi dan virtualisasi. Melalui proses ini, mahasiswa memperoleh pemahaman praktis tentang konsep-konsep kunci seperti alokasi sumber daya, partisi disk, dan konfigurasi sistem. Penggunaan VirtualBox mendemonstrasikan keuntungan virtualisasi dalam pembelajaran dan eksperimen sistem operasi.
- Keberhasilan instalasi Ubuntu menunjukkan kemampuan mahasiswa dalam menerapkan pengetahuan teoritis ke dalam praktek nyata. Pengalaman ini juga memperkenalkan mahasiswa pada ekosistem open-source, yang penting dalam pengembangan software modern.
- Keterampilan yang diperoleh dari praktikum ini akan sangat bermanfaat dalam studi lanjutan tentang sistem operasi, jaringan komputer, dan pengembangan software. Selain itu, pemahaman tentang sistem Linux seperti Ubuntu semakin relevan dalam industri teknologi informasi saat ini.

</div>

<div align="center">
<br>
<br>

## Daftar Pustaka

</div>

<div align="justify">

- Praktikum 1	Sistem Operasi Linux
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System Concepts (10th ed.). Wiley.
- Tanenbaum, A. S., & Bos, H. (2014). Modern Operating Systems (4th ed.). Peason.
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 2

## Informasi Mahasiswa
- *Nama:* 
- *NIM:*
- *Kelas:*

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi *mount point*?

![Mount Point Selection](https://github.com/SyaifulKaromah/foto-repo/blob/e433532cee5da6d4afdc9639eebc9ae06a79300b/Mount.png)

<br>

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi *mount point*:

1. Tanda "/" merupakan direktori root, yang mana merupakan tempat tertinggi dalam struktur sistem file. Jadi, ketika dipilih "/" sebagai mount point, maka sebenarnya kita memasang sistem operasi di direktori root.

2. Pilihan "/" membuat kita bisa mengakses semua file dan folder di System. Misalnya ketika ingin membuka file di Desktop, Jalur lengkapnya adalah "/Desktop". Jadi dengan di pilihnya "/" sebagai mount point, maka semua jalur file dapat diakses dengan mudah.

3. Karena hampir semua distribusi Linux menggunakan "/" sebagai direktori root.

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 3

## Informasi Mahasiswa
- *Nama:*
- *NIM:* 
- *Kelas:* 

<br>

<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

*1. ext4:*
  - Penerus dari ext3 dengan peningkatan performa dan fitur
  - Mendukung volume dan file berukuran sangat besar
  - Memiliki fitur journaling untuk mencegah kerusakan data

*2. ext3:*
  - Versi sebelumnya dari ext4
  - Menambahkan fitur journaling ke ext2
  - Kompatibel dengan ext2 dan ext4

*3. swap:*
  - Bukan sistem file, melainkan ruang pada hard drive yang digunakan sebagai memori virtual
  - Membantu sistem ketika RAM fisik penuh

*4. NTFS:*
  - New Technology File System, dikembangkan oleh Microsoft
  - Digunakan pada sistem operasi Windows modern
  - Mendukung fitur keamanan, kompresi, dan enkripsi

*5. FAT32:*
  - File Allocation Table 32-bit
  - Sistem file lama namun masih kompatibel dengan banyak perangkat
  - Memiliki batasan ukuran file maksimal 4GB

*6. Btrfs:*
  - B-tree File System, dikembangkan untuk Linux
  - Menawarkan fitur canggih seperti snapshots, kompresi, dan RAID
  - Fokus pada toleransi kesalahan dan kemudahan pengelolaan penyimpanan

</dir>
