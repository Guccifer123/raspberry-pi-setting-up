## Siapkan kartu SD Anda

Jika Anda memiliki kartu SD yang belum memiliki sistem operasi Raspbian, atau jika Anda ingin mengatur ulang Raspberry Pi Anda, Anda dapat dengan mudah menginstal Raspbian sendiri. Untuk melakukannya, Anda memerlukan komputer yang memiliki port kartu SD - kebanyakan laptop dan komputer desktop memilikinya.

### Sistem operasi Raspbian melalui NOOBS

Menggunakan perangkat lunak NOOBS adalah cara termudah untuk menginstal Raspbian pada kartu SD Anda.

#### Unduh NOOBS

+ Kunjungi halaman unduh [Raspberry Pi](https://www.raspberrypi.org/downloads).

![Halaman unduhan](images/downloads-page.png)

+ Anda harus melihat kotak yang menghubungkan ke file NOOBS. Klik pada kotak.

![Klik pada NOOBS](images/click-noobs.png)

+ Opsi paling sederhana adalah mengunduh arsip zip file. Pastikan untuk memperhatikan di mana Anda menyimpan arsip, sehingga Anda dapat menemukannya lagi dengan cepat.

![Unduh zip](images/download-zip.png)

#### Format kartu SD

Apa pun yang disimpan di kartu SD akan ditimpa selama pemformatan. Jadi jika kartu SD yang Anda inginkan untuk menginstal Raspbian saat ini memiliki file di dalamnya, misalnya dari versi Raspbian yang lebih lama, Anda mungkin ingin memundurkan file ini terlebih dahulu agar tidak kehilangannya secara permanen.

+ Kunjungi situs web SD Association dan unduh [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) untuk Windows atau Mac.

+ Ikuti instruksi untuk menginstal perangkat lunak.

+ Masukkan kartu SD Anda ke dalam slot kartu SD komputer atau laptop dan buat catatan huruf drive yang dialokasikan untuknya, misalnya `F: /`.

+ Di SD Formatter, pilih huruf drive untuk kartu SD Anda, dan format kartu.

#### Ambil NOOBS dari arsip zip

Selanjutnya, Anda perlu mengekstrak file dari arsip zip NOOBS yang Anda unduh dari situs web Raspberry Pi.

+ Temukan arsip yang diunduh - secara default, ini harus ada di folder `Unduhan`.

+ Klik dua kali untuk mengekstrak file, dan biarkan jendela Explorer / Finder terbuka.

#### Salin file

+ Sekarang buka jendela Explorer / Finder lain dan arahkan ke kartu SD. Yang terbaik adalah memposisikan dua jendela berdampingan.

+ Pilih semua file dalam folder `NOOBS` dan seret ke dalam jendela kartu SD untuk menyalinnya ke kartu.

![salinan jendela](images/copy3.png)

![salinan macos](images/macos_copy.png)

+ Setelah semua file disalin, Anda dapat mengeluarkan kartu SD.