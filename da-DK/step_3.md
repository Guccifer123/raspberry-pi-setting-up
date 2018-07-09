## Opsæt dit SD-kort

Hvis du har et SD-kort, der ikke har Raspbian-operativsystemet på det endnu, eller hvis du vil nulstille din Raspberry Pi, kan du nemt installere Raspbian selv. For at gøre det har du brug for en computer, der har en SD-kortport - de fleste bærbare og stationære computere har en.

### Raspbian operativsystemet via NOOBS

Brug af NOOBS-softwaren er den nemmeste måde at installere Raspbian på dit SD-kort.

#### Download NOOBS

+ Besøg [Raspberry Pi downloads side](https://www.raspberrypi.org/downloads).

![Downloads side](images/downloads-page.png)

+ Du skal se en boks, der linker til NOOBS-filerne. Klik på boksen.

![Klik på NOOBS](images/click-noobs.png)

+ Den nemmeste mulighed er at downloade zip-arkivet for filerne. Sørg for at være opmærksom på, hvor du gemmer arkivet, så du hurtigt kan finde det igen.

![Download zip](images/download-zip.png)

#### Formater SD-kortet

Alt, der er gemt på SD-kortet, overskrives under formatering. Så hvis SD-kortet, som du vil installere Raspbian for øjeblikket, har nogen filer på det, f.eks. Fra en ældre version af Raspbian, kan du ønske at bakke disse filer op først for ikke at miste dem permanent.

+ Besøg SD Association's hjemmeside og download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) til Windows eller Mac.

+ Følg vejledningen for at installere softwaren.

+ Indsæt dit SD-kort i computerens eller laptopens SD-kortspor og noter det drevbogstav, der er tildelt det, f.eks. `F: /`.

+ Vælg SD-kort i SD Format, og format kortet.

#### Uddrag NOOBS fra zip arkivet

Derefter skal du udpakke filerne fra NOOBS zip-arkivet, du downloadede fra Raspberry Pi-webstedet.

+ Find det downloadede arkiv - det skal som standard være i din `Downloads` mappe.

+ Dobbeltklik på det for at udpakke filerne, og hold det resulterende Explorer / Finder-vindue åbent.

#### Kopier filerne

+ Nu åbner du et andet Explorer / Finder-vindue og navigerer til SD-kortet. Det er bedst at placere de to vinduer side om side.

+ Vælg alle filerne i mappen `NOOBS` og træk dem i SD-kortvinduet for at kopiere dem til kortet.

![Windows kopi](images/copy3.png)

![macos kopi](images/macos_copy.png)

+ Når filerne er blevet kopieret over, kan du skubbe SD-kortet ud.