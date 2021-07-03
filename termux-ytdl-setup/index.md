# TERMUX UNTUK DOWNLOAD VIDEO DARI YOUTUBE, INSTAGRAM, DLL

Aplikasi pengunduh YouTube sudah banyak tersedia di Android, namun
terkadang aplikasi tersebut dipenuhi oleh banyak iklan dan juga _tracker_
yang mengganggu ketenangan dan privasi digital anda.

Salah satu cara yang bisa dilakukan untuk mengatasi hal ini adalah dengan
[Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en&gl=US) yang dapat diunduh di Google Play Store.
Bagi yang belum pernah tahu Termux, Termux adalah aplikasi yang
mengemulasikan terminal atau console GNU/Linux di dalam Android. Termux ini
multifungsi, dan bisa melakukan hampir segala hal, termasuk untuk mengunduh
video dari internet.

## First-time Setup

Silahkan untuk membuka aplikasi Anda. Untuk setup pertama, cukup _copy_ dan
_paste_ kode BASH berikut ini ke dalam Termux, lalu tekan enter di keyboard
ponsel android anda.

```bash
curl -sL https://git.io/Jcuhy -o setup.sh
chmod 777 setup.sh
./setup.sh
```

Proses akan memakan waktu beberapa menit. Dibutuhkan koneksi internet untuk
menjalankan kode instalasi tersebut, pastikan kuota data anda mencukupi
(mengunduh file sekitar 70MB), dan juga pastikan ruang penyimpanan anda
mencukupi.

Jika anda mempunyai Termux yang _fresh-Install_ Kemungkinan pada saat
proses, anda akan disuguhi beberapa dialog CLI. Untuk mengatasi hal
tersebut, cukup ketik "y" dan ENTER pada dialog pertama lalu ENTER pada
dialog kedua dan ketiga.

- Dialog Pertama
![apt Confirmation Dialog 1](images/pertama.png)
Langsung ketik "y" lalu ENTER

- Kedua dan Ketiga (sama)
![apt Confirmation Dialog 2](images/kedua.png)
Langsung tap ENTER pada keyboard

Untuk menyimpan video yang akan anda unduh, Termux memerlukan izin kepada
penyimpanan Internal Android. Ketika dialog ini muncul, maka silahkan untuk
mengetuk "Allow" atau "Izinkan" pada dialog tersebut

![Termux Storage Permission Dialog](images/ss-storage-dialog.png)

Setelah itu tunggu beberapa saat sampai semua proses terselesaikan.

## Download Video dari YouTube, atau sumber lainnya

Setelah setup selesai, anda langsung bisa menggunakan Termux untuk
mengunduh video, baik dari Instagram, YouTube atau aplikasi-aplikasi lain
yang didukung. Cukup dengan mengetuk tombol bagikan lalu pilih Termux

<img src="images/unduh-demo.png" width=50%>

## Wrapping Up

Karena kebutuhan akan privasi digital dan perlindungan data pribadi yang
semakin meningkat, maka menggunakan aplikasi Open-Source adalah sebuah
kebutuhan. Dengan menggunakan pengunduh YouTube Termux ini, anda telah
mengamankan sedikit banyak privasi digital anda, dari pada menggunakan
aplikasi pihak-ketiga yang banyak iklannya.

> With a great power, comes a great Responsibility

Termux memang _powerfull_ namun, anda harus tetap menghargai hak cipta
pembuat konten yang anda unduh. Silahkan simpan video tersebut untuk
konsumsi pribadi.
