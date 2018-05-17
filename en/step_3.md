## Setup your SD Card

If you brought an SD card that wasn't pre-installed with Raspbian or you want to reset your Raspberry Pi you can install it yourself.

### Install Raspbian using NOOBS

Using NOOBS is the easiest way to install Raspbian on your SD card. To get hold of a copy of NOOBS:

#### Download NOOBS

+ Visit [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Downloads page](images/downloads-page.png)

+ You should see a box with a link to the NOOBS files. Click on the link.

![Click on NOOBS](images/click-noobs.png)

+ The simplest option is to download the zip archive of the files.

![Download zip](images/download-zip.png)

#### Format the SD Card

If the SD card on which you wish to install Raspbian currently has an older version of Raspbian on it, you may wish to back up the files from the card first, as they will be overwritten during this process.

--- task ---

Visit the SD Association’s website and download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) for Windows or Mac.

--- /task ---

--- task ---

Follow the instructions to install the software.

--- /task ---

--- task ---

Insert your SD card into the computer or laptop’s SD card reader and make a note of the drive letter allocated to it, e.g. `F:/`.

--- /task ---

--- task ---

In SD Formatter, select the drive letter for your SD card, and format it.

--- /task ---


#### Extract NOOBS from the zip archive

Next, you will need to extract the files from the NOOBS zip archive you downloaded from the Raspberry Pi website.

--- task ---

Go to your *Downloads* folder and find the zip file you downloaded.

--- /task ---

--- task ---

Extract the files and keep the resulting Explorer/Finder window open.

--- /task ---

#### Copy the files

--- task ---

Now open another Explorer/Finder window and navigate to the SD card. It's best to position the two windows side by side.

--- /task ---

--- task ---

Select all the files from the *NOOBS* folder and drag them onto the SD card.

![copy 2](images/copy2.png)

--- /task ---

--- task ---

Once the files have been copied over you can eject the SD card.

--- /task ---

