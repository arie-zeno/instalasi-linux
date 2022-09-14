# Toturial Instalasi Linux ke Flashdisk / eksternal hardisk

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
> disini saya menggunakan iso debian, bisa di download [disini (debian 11)](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/11.5.0-live+nonfree/amd64/iso-hybrid/) silahkan pilih DE sesuai selera (GNOME, XFCE, KDE dll)

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

# Langkah - langkah instalasi ke flashdisk / eksternal hardisk

Setelah berhasil boot melalui flashdisk klik saja enter untuk menjalankan live usb 

![debian](/debian1.png)

- Masukkan dulu flashdisk yang akan diinstall linux / hardisk eksternal 

- Kemudian klik icon install debian, maka akan muncul pop up debian installer (calamares) dan klik saja next

![debian](/debian2.png)

- Silahkan atur region untuk menyesuaikan waktu setempat

![debian](/debian3.png)

- Untuk keyboard gunakan yang default saja

![debian](/debian4.png)

- Pengaturan partisi klik yang manual

![debian](/debian5.png)

- Pilih flashdisk / ekternal hardisk yang menjadi tujuan instalasi

![debian](/debian7.jpeg)

    Jangan sampai salah memilih tujuan instalasi ke hardisk utama atau ke flashdisk untuk bootable

![debian](/debian6.png)

- Klik new partition table (pilih saja mbr/gpt)

![debian](/debian8.png)

- Jika memilih GPT klik create partisi sebesar 500mb, tipe fat32, mount /bios/efi dan flag centang boot

![debian](/debian9.png)

- Kemudian create lagi untuk file system, gunakan saja semuanya untuk jadi satu partisi. mount /, flag root

![debian](/debian10.png)

![debian](/debian11.png)

- Setelah itu silahkan atur user dan password

![debian](/debian12.png)

- Next kemudian klik install

![debian](/debian13.png)

- Tunggu sampai proses selesai

![debian](/debian14.png)

- Setelah selesai klik done maka laptop akan reboot. Jangan lupa untuk mencabut flashdisk bootable dan setting lagi bios agar booting dengan flashdisk yang sudah terinstall linux

![debian](/debian15.png)

