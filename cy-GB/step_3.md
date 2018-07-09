## Gosodwch eich cerdyn SD

Os oes gennych gerdyn SD nad oes ganddo'r system weithredu Raspbian arno eto, neu os ydych am ailosod eich Mws Môr, gallwch chi osod Raspbian eich hun yn rhwydd. I wneud hynny, mae arnoch angen cyfrifiadur sydd â phorthladd cerdyn SD - mae gan y rhan fwyaf o gyfrifiaduron laptop a bwrdd gwaith un.

### Y system weithredu Raspbian trwy NOOBS

Defnyddio meddalwedd NOOBS yw'r ffordd hawsaf i osod Raspbian ar eich cerdyn SD.

#### Lawrlwythwch NOOBS

+ Ewch i dudalennau downloads [Raspberry Pi tudalen](https://www.raspberrypi.org/downloads).

![Tudalen lwytho i lawr](images/downloads-page.png)

+ Dylech weld blwch sy'n cysylltu â ffeiliau NOOBS. Cliciwch ar y blwch.

![Cliciwch ar NOOBS](images/click-noobs.png)

+ Yr opsiwn symlaf yw lawrlwytho archif zip y ffeiliau. Gwnewch yn siŵr eich bod yn talu sylw i ble rydych chi'n achub yr archif, fel y gallwch ddod o hyd iddo eto'n gyflym.

![Lawrlwythwch zip](images/download-zip.png)

#### Fformat y cerdyn SD

Bydd unrhyw beth sy'n cael ei storio ar y cerdyn SD yn cael ei orysgrifennu wrth fformatio. Felly, os oes gan y cerdyn SD yr ydych am osod Raspbian arno ar hyn o bryd unrhyw ffeiliau arno, ee o fersiwn hŷn o Raspbian, efallai y byddwch am adfer y ffeiliau hyn yn gyntaf i beidio â'u colli'n barhaol.

+ Ewch i wefan y Gymdeithas SD a lawrlwythwch [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) gyfer Windows neu Mac.

+ Dilynwch y cyfarwyddiadau i osod y meddalwedd.

+ Rhowch eich cerdyn SD i mewn i slot y cerdyn SD cyfrifiadur neu laptop a gwnewch nodyn o'r llythyr gyrru a ddyrennir iddo ee `F: /`.

+ Yn SD Formatter, dewiswch y llythyr gyrru ar gyfer eich cerdyn SD, a ffurf y cerdyn.

#### Detholwch NOOBS o'r archif zip

Nesaf, bydd angen i chi dynnu'r ffeiliau o'r archif zip NOOBS a'ch lawrlwythwyd o wefan y Mws Coch.

+ Dod o hyd i'r archif wedi'i lawrlwytho - yn ddiofyn, dylai fod yn eich ffolder `Downloads`.

+ Dwbl-gliciwch arno i dynnu'r ffeiliau, a chadw'r ffenestr Explorer / Finder sy'n deillio ohono ar agor.

#### Copïwch y ffeiliau

+ Nawr agorwch ffenestr Explorer / Finder arall ac ewch i'r cerdyn SD. Y peth gorau yw gosod y ddwy ffenestr ochr yn ochr.

+ Dewiswch yr holl ffeiliau yn y ffolder `NOOBS` a'u llusgo i mewn i'r ffenestr cerdyn SD i'w copïo i'r cerdyn.

![copi ffenestri](images/copy3.png)

![copi macos](images/macos_copy.png)

+ Unwaith y bydd y ffeiliau wedi'u copïo i gyd, gallwch chi dynnu'r cerdyn SD allan.