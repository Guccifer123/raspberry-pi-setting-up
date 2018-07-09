## Postavite SD karticu

Ako imate SD karticu koja još nema Raspbian operativni sustav ili ako želite resetirati Raspberry Pi, možete sami instalirati Raspbian. Da biste to učinili, potreban vam je računalo s priključkom za SD karticu - većina prijenosnih računala i stolnih računala imaju jedan.

### Operacijski sustav Raspbian preko NOOBS-a

Korištenje softvera NOOBS najlakši je način za instalaciju programa Raspbian na SD karticu.

#### Preuzmite NOOBS

+ Posjetite stranicu [Download malina Pi](https://www.raspberrypi.org/downloads).

![Stranica za preuzimanje](images/downloads-page.png)

+ Trebali biste vidjeti okvir povezan s NOOBS datotekama. Kliknite na okvir.

![Kliknite NOOBS](images/click-noobs.png)

+ Najjednostavnija je mogućnost preuzimanje zip arhive datoteka. Obavezno obratite pažnju na mjesto gdje spremite arhivu, tako da je možete brzo pronaći.

![Preuzmite zip](images/download-zip.png)

#### Formatiranje SD kartice

Sve što je pohranjeno na SD kartici će biti prebrisano tijekom formatiranja. Dakle, ako SD kartica na koju želite instalirati Raspbian trenutačno ima bilo kakve datoteke na njemu, npr. Iz starijih verzija Raspbian, možda biste željeli vratiti ove datoteke prije nego što ih ne biste trajno izgubili.

+ Posjetite web stranicu Udruge SD i preuzmite [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ili Mac.

+ Slijedite upute za instalaciju softvera.

+ Umetnite SD karticu u utor SD kartice na računalu ili laptopa i zabilježite dodijeljeno slovo pogona, npr. `F: /`.

+ U programu SD Formatter odaberite slovo pogona za SD karticu i formatirajte karticu.

#### Izvadite NOOBS iz zip arhive

Zatim ćete morati izdvojiti datoteke iz arhive zip-a NOOBS koje ste preuzeli s web stranice Raspberry Pi.

+ Pronađite preuzetu arhivu - po defaultu, to bi trebao biti u vašem `Downloads` mapu.

+ Dvaput kliknite na njega da biste izdvojili datoteke i zadržali otvoreni prozor Explorer / Finder.

#### Kopirajte datoteke

+ Sada otvorite još jedan prozor Explorer / Finder i idite na SD karticu. Najbolje je postaviti dva prozora jedan do drugoga.

+ Odaberite sve datoteke u mapi `NOOBS` i povucite ih u prozor SD kartice da biste ih kopirali na karticu.

![kopiranje sustava Windows](images/copy3.png)

![mako kopirati](images/macos_copy.png)

+ Kad sve datoteke budu kopirane, možete izbrisati SD karticu.