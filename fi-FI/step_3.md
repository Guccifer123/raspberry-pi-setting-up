## Aseta SD-kortti

Jos sinulla on SD-kortti, jolla ei vielä ole Raspbian-käyttöjärjestelmää tai jos haluat nollata Raspberry Pi -sovelluksen, voit helposti asentaa Raspbian itse. Tätä varten tarvitset tietokoneen, jolla on SD-korttiportti - useimmilla kannettaviin tietokoneisiin ja pöytätietokoneisiin on yksi.

### Raspbian-käyttöjärjestelmä NOOBS: n kautta

NOOBS-ohjelmiston käyttö on helpoin tapa asentaa Raspbian SD-kortille.

#### Lataa NOOBS

+ Käy [Raspberry Pi -lataussivulla](https://www.raspberrypi.org/downloads).

![Lataussivu](images/downloads-page.png)

+ Näet NOOBS-tiedostoihin yhdistetyn laatikon. Napsauta laatikkoa.

![Napsauta NOOBS](images/click-noobs.png)

+ Yksinkertaisin vaihtoehto on ladata tiedostojen zip-arkisto. Muista kiinnittää huomiota siihen, missä tallennat arkiston, jotta voit löytää sen nopeasti uudelleen.

![Lataa zip](images/download-zip.png)

#### Muotoile SD-kortti

Kaikki, jotka on tallennettu SD-kortille, korvataan muotoilun aikana. Joten jos SD-kortti, johon haluat asentaa Raspbianin, on tällä hetkellä tiedostoja, esim. Vanhasta Raspbian-versiosta, voit halutessasi varmuuskopioida nämä tiedostot ensin, jotta et menetä niitä pysyvästi.

+ Käy SD Associationin verkkosivuilla ja lataa [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) Windowsille tai Macille.

+ Asenna ohjelmisto noudattamalla ohjeita.

+ Aseta SD-kortti tietokoneeseen tai kannettavan tietokoneen SD-korttipaikkaan ja kirjoita sille osoitetun aseman kirjain, esim. `F: /`.

+ Valitse SD Formatter -ohjelmassa SD-kortille aseman kirjain ja muodosta kortti.

#### Poista NOOBS zip-arkistosta

Seuraavaksi sinun on purettava tiedostot NPSPS-arkistosta, jonka olet ladannut Raspberry Pi -sivustosta.

+ Löydä ladattu arkisto - oletuksena sinun pitäisi olla `Lataukset` -kansiossa.

+ Kaksoisnapsauta sitä tiedostojen purkamiseksi ja säilytä Resurssienhallinta / Etsijä-ikkuna auki.

#### Kopioi tiedostot

+ Avaa nyt uusi Explorer / Finder-ikkuna ja siirry SD-kortille. On parasta sijoittaa kaksi ikkunaa vierekkäin.

+ Valitse kaikki `NOOBS` -kansiossa olevat tiedostot ja vedä ne SD-kortin ikkunaan, jotta voit kopioida ne korttiin.

![ikkunat kopioida](images/copy3.png)

![macos kopio](images/macos_copy.png)

+ Kun kaikki tiedostot on kopioitu, voit poistaa SD-kortin.