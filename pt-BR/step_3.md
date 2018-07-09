## Configure seu cartão SD

Se você tiver um cartão SD que ainda não tenha o sistema operacional Raspbian, ou se quiser redefinir seu Raspberry Pi, você poderá instalar o Raspbian facilmente. Para fazer isso, você precisa de um computador com porta de cartão SD - a maioria dos computadores de mesa e laptops tem um.

### O sistema operacional Raspbian via NOOBS

Usando o software NOOBS é a maneira mais fácil de instalar o Raspbian no seu cartão SD.

#### Download NOOBS

+ Visit the [Raspberry Pi downloads page](https://www.raspberrypi.org/downloads).

![Downloads page](images/downloads-page.png)

+ You should see a box linking to the NOOBS files. Click on the box.

![Click on NOOBS](images/click-noobs.png)

+ The simplest option is to download the zip archive of the files. Make sure to pay attention to where you save the archive, so that you can find it again quickly.

![Download zip](images/download-zip.png)

#### Format the SD card

Anything that's stored on the SD card will be overwritten during formatting. So if the SD card on which you want to install Raspbian currently has any files on it, e.g. from an older version of Raspbian, you may wish to back these files up first to not lose them permanently.

+ Visit the SD Association’s website and download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) for Windows or Mac.

+ Follow the instructions to install the software.

+ Insert your SD card into the computer or laptop’s SD card slot and make a note of the drive letter allocated to it, e.g. `F:/`.

+ In SD Formatter, select the drive letter for your SD card, and the format the card.

#### Extract NOOBS from the zip archive

Next, you will need to extract the files from the NOOBS zip archive you downloaded from the Raspberry Pi website.

+ Find the downloaded archive — by default, it should be in your `Downloads` folder.

+ Double-click on it to extract the files, and keep the resulting Explorer/Finder window open.

#### Copy the files

+ Now open another Explorer/Finder window and navigate to the SD card. It's best to position the two windows side by side.

+ Select all the files in the `NOOBS` folder and drag them into the SD card window to copy them to the card.

![windows copy](images/copy3.png)

![macos copy](images/macos_copy.png)

+ Once the files have all been copied over, you can eject the SD card.