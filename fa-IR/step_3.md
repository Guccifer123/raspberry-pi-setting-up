## کارت SD خود را تنظیم کنید

اگر شما یک کارت SD دارید که سیستم عامل Raspbian را در آن نصب نکرده اید، یا اگر می خواهید Raspberry Pi خود را دوباره تنظیم کنید، می توانید به راحتی Raspbian خود را نصب کنید. برای انجام این کار، شما نیاز به یک کامپیوتر با پورت کارت SD - اکثر لپ تاپ ها و رایانه های رومیزی یکی هستند.

### سیستم عامل Raspbian از طریق NOOBS

با استفاده از نرم افزار NOOBS، ساده ترین راه برای نصب Raspbian بر روی کارت SD شما است.

#### دانلود NOOBS

+ صفحه</a>[Raspberry Pi را ببینید. صفحه ](https://www.raspberrypi.org/downloads) .

![صفحه های دانلود](images/downloads-page.png)

+ شما باید جعبه پیوند به فایل های NOOBS را ببینید. روی جعبه کلیک کنید

![روی NOOBS کلیک کنید](images/click-noobs.png)

+ ساده ترین گزینه دانلود آرشیو فایل های فشرده است. اطمینان حاصل کنید که به جایی که آرشیو را ذخیره می کنید، به طوری که بتوانید آن را سریعا پیدا کنید.

![دانلود فایل زیپ](images/download-zip.png)

#### کارت SD را فرمت کنید

هر چیزی که بر روی کارت SD ذخیره می شود، در هنگام قالببندی تغییر خواهد کرد. بنابراین اگر کارت SD که شما می خواهید نصب Raspbian در حال حاضر هر گونه فایل در آن، به عنوان مثال از نسخه های قدیمی Raspbian، شما ممکن است بخواهید برای اولین بار این فایل ها را به عقب برگردانید تا آنها را به طور دائم از دست ندهید.

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