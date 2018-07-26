## De SD-kaart instellen

Als je een SD-kaart hebt waarop nog geen Raspbian-besturingssysteem staat of als je je Raspberry Pi wilt resetten, kun je Raspbian gemakkelijk zelf installeren. Hiervoor heb je een computer nodig met een SD-kaartsleuf - de meeste laptop- en desktopcomputers hebben er een.

### Het Raspbian-besturingssysteem via NOOBS

Het gebruik van de NOOBS-software is de gemakkelijkste manier om Raspbian op de SD-kaart te installeren.

#### NOOBS downloaden

+ Bezoek de [Raspberry Pi downloads pagina](https://www.raspberrypi.org/downloads).

![Downloadpagina](images/downloads-page.png)

+ Je zou een vak moeten zien met een link naar de NOOBS-bestanden. Klik op het vakje.

![Klik op NOOBS](images/click-noobs.png)

+ De eenvoudigste optie is om het zip-archief van de bestanden te downloaden. Onthou waar je het archiefbestand opslaat zodat je het snel weer kunt vinden.

![Zip downloaden](images/download-zip.png)

#### Formatteer de SD-kaart

Alles wat op de SD-kaart is opgeslagen, wordt tijdens het formatteren overschreven. Dus als de SD-kaart waarop je Raspbian wilt installeren nu nog bestanden bevat, bijvoorbeeld van een oudere versie van Raspbian, wil je misschien eerst deze bestanden back-uppen om ze niet voor altijd kwijt te raken.

+ Voor Windows of Mac ga je naar de website van de SD Association en download je [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html).

+ Volg de instructies op om de software te installeren.

+ Plaats de SD-kaart in de computer of de SD-kaartsleuf van de laptop en onthou de stationsletter die eraan is toegewezen, bijvoorbeeld `F: /`.

+ Selecteer in SD Formatter de stationsaanduiding voor de SD-kaart en formatteer het kaartje.

#### Haal NOOBS uit het zip-archief

Dan moeten de bestanden uit het NOOBS zip-archief, dat je hebt gedownload van de Raspberry Pi-website, worden uitgepakt.

+ Zoek het gedownloade archiefbestand - meestal staat dat in de map `Downloads`.

+ Dubbelklik erop om de bestanden uit te pakken en houd het Verkenner/Finder-venster open.

#### Kopieer de bestanden

+ Open nu een ander Explorer/Finder-venster en navigeer naar de SD-kaart. Het is het beste om de twee vensters naast elkaar te plaatsen.

+ Selecteer alle bestanden in de map `NOOBS` en sleep ze naar het SD-kaartvenster om ze naar de kaart te kopiëren.

![Windows kopie](images/copy3.png)

![macos kopie](images/macos_copy.png)

+ Nadat de bestanden allemaal zijn gekopieerd, kun je de SD-kaart uitwerpen.