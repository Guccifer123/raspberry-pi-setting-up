## Nastavite kartico SD

Če imate kartico SD, ki še nima operacijskega sistema Raspbian, ali če želite ponastaviti vašo Raspberry Pi, lahko preprosto namestite Raspbian. Če želite to narediti, potrebujete računalnik, ki ima pomnilniško kartico SD - večina prenosnih in namiznih računalnikov ima eno.

### Operacijski sistem Raspbian prek NOOBS-a

Uporaba programske opreme NOOBS je najlažji način namestitve programa Raspbian na kartico SD.

#### Prenesi NOOBS

+ Obiščite spletno stran [Malpberry Pi downloads](https://www.raspberrypi.org/downloads).

![Stran za prenos](images/downloads-page.png)

+ Prikaže se okence, ki se povezuje z datotekami NOOBS. Kliknite na polje.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najpreprostejša možnost je prenesti zip arhiv datotek. Poskrbite, da boste pozorni na to, kje shranite arhiv, da ga boste hitro našli hitro.

![Prenesi zip](images/download-zip.png)

#### Oblikujte kartico SD

Vse, kar je shranjeno na kartici SD, bo med formatiranjem prepisano. Torej, če SD kartica, na kateri želite namestiti Raspbian, trenutno vsebuje vse datoteke na njej, npr. Iz starejše različice programa Raspbian, boste morda želeli najprej odpreti te datoteke, da jih ne izgubite trajno.

+ Obiščite spletno stran SD Association in prenesite [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ali Mac.

+ Sledite navodilom za namestitev programske opreme.

+ Vstavite kartico SD v režo za kartico računalnika ali prenosnega računalnika in zabeležite črko pogona, ki ji je dodeljena, npr. `F: /`.

+ V SD Formatter izberite črko pogona za kartico SD in formatirajte kartico.

#### Izvlecite NOOBS iz zip arhiva

Nato boste morali iz datoteke NOOBS zip arhivirati datoteke, ki ste jih prenesli s spletne strani Raspberry Pi.

+ Poiščite prenesen arhiv - privzeto mora biti v mapi `prenosov`.

+ Dvokliknite na njej, da izvlečete datoteke in ohranite odprto okno Raziskovalec / Finder.

#### Kopirajte datoteke

+ Zdaj odprite novo okno Explorer / Finder in se pomaknite do kartice SD. Najbolje je, da oba okna namestite drug ob drugem.

+ Izberite vse datoteke v mapi `NOOBS` in jih povlecite v okno SD kartice, da jih kopirate na kartico.

![okno kopiranje](images/copy3.png)

![macos copy](images/macos_copy.png)

+ Ko so datoteke kopirane, lahko SD kartico odstranite.