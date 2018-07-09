## Configurați cardul SD

Dacă aveți încă o cartelă SD care nu are încă sistemul de operare Raspbian sau dacă doriți să resetați Raspberry Pi, puteți instala cu ușurință Raspbian. Pentru a face acest lucru, aveți nevoie de un computer care are un port de card SD - majoritatea laptopurilor și computerelor desktop au unul.

### Sistemul de operare Raspbian prin intermediul NOOBS

Utilizarea software-ului NOOBS este cel mai simplu mod de a instala Raspbian pe cardul SD.

#### Descărcați NOOBS

+ Vizitați pagina de descărcare [Raspberry Pi pagina](https://www.raspberrypi.org/downloads).

![Pagina de descărcări](images/downloads-page.png)

+ Ar trebui să vedeți o casetă care să conecteze fișierele NOOBS. Dați clic pe casetă.

![Faceți clic pe NOOBS](images/click-noobs.png)

+ Cea mai simplă opțiune este să descărcați arhiva zip a fișierelor. Asigurați-vă că acordați atenție locului în care salvați arhiva, astfel încât să o puteți găsi din nou rapid.

![Descărcați zip](images/download-zip.png)

#### Formatați cardul SD

Orice stocat pe cardul SD va fi suprascris în timpul formatării. Deci, dacă cardul SD pe care doriți să instalați Raspbian are în prezent fișiere de pe el, de exemplu dintr-o versiune mai veche a Raspbian, ați putea dori să întoarceți aceste fișiere mai întâi pentru a nu le pierde definitiv.

+ Accesați site-ul web al asociației SD și descărcați [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pentru Windows sau Mac.

+ Urmați instrucțiunile pentru a instala software-ul.

+ Introduceți cardul SD în slotul pentru cardul SD al computerului sau al laptopului și notați litera de unitate alocată acestuia, de exemplu `F: /`.

+ În formatatorul SD, selectați litera unității pentru cardul SD și formatați cardul.

#### Extrageți NOOBS din arhiva zip

Apoi, va trebui să extrageți fișierele din arhiva zip NOOBS pe care ați descărcat-o de pe site-ul Raspberry Pi.

+ Găsiți arhiva descărcată - în mod implicit, ar trebui să fie în dosarul `Descărcări`.

+ Faceți dublu clic pe acesta pentru a extrage fișierele și păstrați fereastra Explorer / Finder rezultată.

#### Copiați fișierele

+ Deschideți acum o altă fereastră Explorer / Finder și navigați pe cardul SD. Cel mai bine este să poziționați cele două ferestre una lângă alta.

+ Selectați toate fișierele din dosarul `NOOBS` și glisați-le în fereastra cartelei SD pentru a le copia pe carte.

![Windows copie](images/copy3.png)

![copie macos](images/macos_copy.png)

+ Odată ce fișierele au fost copiate, puteți scoate cardul SD.