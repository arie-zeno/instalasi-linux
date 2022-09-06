# Toturial Instalasi Linux ke Flashdisk

## Bahan yang disiapkan
- File iso linux
- 2 buah flashdisk 
- Softwere untuk bootable

# 
## Membuat bootable flashdisk

Disini saya menggunakan softwere rufus, bisa di download [disini](https://rufus.ie/en/)

![rufus](/rufus.png)

- ## Masukkan salah 1 flashdisk, sehingga pada menu Device akan terdeteksi flashdisk yang akan di bootable

![rufus](/rufus2.png)

- ## Klik menu SELECT kemudian pilih iso linux yang akan di bootable

![rufus](/rufus3.png)
> disini saya menggunakan iso debian, bisa di download [disini (debian 11)](https://www.debian.org/CD/http-ftp/)  atau [disini (debian 10)](https://drive.google.com/drive/folders/1mEa3kUJXpmctbNY4j49FTdtQC5j5emj2?usp=sharing) 

- ## Setelah itu silahkan pilih skema partisi MBR atau GPT ( bios / UEFI )

![rufus](/partisiSkema.png)

- ## Kemudian klik start
- ## Jika muncul pop up, terima saja semuanya 

![rufus](/rufus4.png)

![rufus](/rufus5.png)

![rufus](/rufus6.png)

- ## Tunggu hingga proses selesai

![rufus](/rufus7.png)

![rufus](/rufusReady.png)

## Booting Dengan Flashdisk
- ## Silahkan restart laptop kalian
- ## Pada saat layar hidup tekan __f2__ maka akan di arahkan ke menu bios, klik arah kanan (->) pada keyboard sampai ke menu boot

    > Tombol paling umum yang bisa anda gunakan untuk masuk BIOS adalah DEL, F1, F2, F10 atau Fn+F2, tergantung jenis laptop dan motherboard anda.

- ## Pada menu boot prioritaskan flasdisk dengan memindahkannya ke paling atas
    
    > Tampilan bios akan berbeda tergantung motherboard yang anda gunakan

- ## Simpan kemudian keluar dari menu bios
- ## Maka booting akan menggunakan flashdisk

#

# Langkah - langkah instalasi ke flashdisk


