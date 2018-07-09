## Nastavte SD kartu

Ak máte SD kartu, ktorá na ňom zatiaľ nemá operačný systém Raspbian, alebo ak chcete obnoviť svoj Raspberry Pi, môžete ju jednoducho nainštalovať sami. K tomu potrebujete počítač, ktorý má port karty SD - väčšina notebookov a stolných počítačov má jeden.

### Operačný systém Raspbian prostredníctvom NOOBS

Používanie softvéru NOOBS je najjednoduchší spôsob nainštalovania Raspbian na vašu kartu SD.

#### Stiahnite si NOOBS

+ Navštívte stránku sťahovania [Raspberry Pi na strane](https://www.raspberrypi.org/downloads).

![Stránka na prevzatie](images/downloads-page.png)

+ Mali by ste vidieť odkaz na súbory NOOBS. Kliknite na pole.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najjednoduchšou možnosťou je prevziať zip archív súborov. Dbajte na to, kam ukladáte archív, aby ste ho mohli znova nájsť rýchlo.

![Stiahnuť zip](images/download-zip.png)

#### Formátujte SD kartu

Všetko, čo je uložené na karte SD, sa počas formátovania prepíše. Ak teda SD karta, na ktorú chcete nainštalovať Raspbian, má v súčasnosti nejaké súbory, napr. Zo staršej verzie Raspbian, môžete tieto súbory najprv podporiť, aby ste ich natrvalo nestratili.

+ Navštívte webovú stránku združenia SD a stiahnite si [SD formátovač 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pre systém Windows alebo Mac.

+ Pri inštalácii softvéru postupujte podľa pokynov.

+ Vložte kartu SD do zásuvky na kartu SD alebo počítača a poznačte si písmeno jednotky, ktoré je jej pridelené, napr. `F: /`.

+ V SD formátovači vyberte písmeno jednotky pre kartu SD a formát kartu.

#### Extrahujte NOOBS zo zip archívu

Ďalej budete musieť extrahovať súbory z archívu zip NOOBS, ktorý ste stiahli z webovej stránky Raspberry Pi.

+ Nájdite stiahnutý archív - predvolene by mal byť v priečinku `sťahovania`.

+ Dvakrát kliknite na ňu, aby ste extrahovali súbory a otvorili okno výsledného Explorer / Findera.

#### Skopírujte súbory

+ Teraz otvorte ďalšie okno Explorer / Finder a prejdite na kartu SD. Najlepšie je umiestniť dve okná vedľa seba.

+ Vyberte všetky súbory v priečinku `NOOBS` a presuňte ich do okna SD karty a skopírujte ich na kartu.

![windows copy](images/copy3.png)

![kópia macos](images/macos_copy.png)

+ Keď sú všetky súbory skopírované, môžete kartu SD vysunúť.