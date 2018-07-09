## Sediakan kad SD anda

Jika anda mempunyai kad SD yang tidak mempunyai sistem operasi Raspbian di atasnya, atau jika anda mahu menetapkan semula Ras Raspberry Pi anda, anda boleh dengan mudah memasang Raspbian sendiri. Untuk berbuat demikian, anda memerlukan komputer yang mempunyai port kad SD - kebanyakan komputer riba dan komputer desktop mempunyai satu.

### Sistem operasi Raspbian melalui NOOBS

Menggunakan perisian NOOBS adalah cara paling mudah untuk memasang Raspbian pada kad SD anda.

#### Muat turun NOOBS

+ Lawati [Raspberry Pi muat turun halaman](https://www.raspberrypi.org/downloads).

![Halaman muat turun](images/downloads-page.png)

+ Anda harus melihat kotak yang menghubungkan ke fail NOOBS. Klik pada kotak.

![Klik pada NOOBS](images/click-noobs.png)

+ Pilihan paling mudah adalah untuk memuat turun arkib zip fail. Pastikan untuk memberi perhatian kepada tempat anda menyimpan arkib, supaya anda dapat menemukannya dengan cepat.

![Muat turun zip](images/download-zip.png)

#### Format kad SD

Apa-apa sahaja yang disimpan pada kad SD akan ditulis ganti semasa pemformatan. Oleh itu, jika kad SD yang anda mahu pasang Raspbian kini mempunyai sebarang fail di atasnya, contohnya dari versi lama Raspbian, anda mungkin mahu memulangkan fail-fail ini terlebih dahulu untuk tidak kehilangannya secara kekal.

+ Lawati laman web Persatuan SD dan muat turun [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) untuk Windows atau Mac.

+ Ikut arahan untuk memasang perisian.

+ Masukkan kad SD anda ke dalam slot kad SD komputer atau komputer riba dan tulis nota huruf drive yang diberikan kepadanya, mis. `F: /`.

+ Dalam Formatter SD, pilih huruf pemacu untuk kad SD anda, dan formatkan kad itu.

#### Ekstrak NOOBS dari arkib zip

Seterusnya, anda perlu mengeluarkan fail dari arkib zip NOOBS yang anda muat turun dari laman web Raspberry Pi.

+ Cari arkib yang dimuat turun - secara lalai, ia perlu berada di dalam anda `Downloads` folder.

+ Klik dua kali untuk mengekstrak fail, dan jadikan window Explorer / Finder yang terhasil terbuka.

#### Salin fail

+ Sekarang buka tetingkap Explorer / Finder lain dan navigasi ke kad SD. Adalah lebih baik untuk meletakkan kedua-dua tingkap itu berdampingan.

+ Pilih semua fail dalam folder `NOOBS` dan seretnya ke dalam tetingkap kad SD untuk menyalinnya ke kad.

![tingkap salinan](images/copy3.png)

![salinan macos](images/macos_copy.png)

+ Setelah semua fail disalin, anda boleh mengeluarkan kad SD.