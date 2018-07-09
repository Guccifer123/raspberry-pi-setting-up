## Stel uw SD-kaart in

Als je een SD-kaart hebt waarop nog geen Raspbian-besturingssysteem staat of als je je Raspberry Pi wilt resetten, kun je Raspbian gemakkelijk zelf installeren. Hiervoor hebt u een computer nodig met een SD-kaartpoort - de meeste laptop- en desktopcomputers hebben er één.

### Het Raspbian-besturingssysteem via NOOBS

Het gebruik van de NOOBS-software is de gemakkelijkste manier om Raspbian op uw SD-kaart te installeren.

#### NOOBS downloaden

+ Bezoek de [Raspberry Pi downloads pagina](https://www.raspberrypi.org/downloads).

![Downloadpagina](images/downloads-page.png)

+ U zou een box moeten zien die linken naar de NOOBS-bestanden. Klik op het vakje.

![Klik op NOOBS](images/click-noobs.png)

+ De eenvoudigste optie is om het zip-archief van de bestanden te downloaden. Let goed op waar u het archief opslaat, zodat u het snel terug kunt vinden.

![Zip downloaden](images/download-zip.png)

#### Formatteer de SD-kaart

Alles dat op de SD-kaart is opgeslagen, wordt tijdens het formatteren overschreven. Dus als de SD-kaart waarop je Raspbian wilt installeren momenteel bestanden bevat, bijvoorbeeld van een oudere versie van Raspbian, wil je misschien eerst deze bestanden back-uppen om ze niet permanent kwijt te raken.

+ Bezoek de website van de SD Association en download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) voor Windows of Mac.

+ Volg de instructies om de software te installeren.

+ Plaats uw SD-kaart in de computer of de SD-kaartsleuf van uw laptop en noteer de stationsletter die eraan is toegewezen, bijvoorbeeld `F: /`.

+ Selecteer in SD Formatter de stationsaanduiding voor uw SD-kaart en het formaat van de kaart.

#### Extract NOOBS uit het zip-archief

Vervolgens moet je de bestanden uit het NOOBS zip-archief halen dat je hebt gedownload van de Raspberry Pi-website.

+ Zoek het gedownloade archief - dit moet standaard in de map `Downloads`.

+ Dubbelklik erop om de bestanden te extraheren en houd het resulterende Verkenner / Zoeker-venster open.

#### Kopieer de bestanden

+ Open nu een ander Explorer / Finder-venster en navigeer naar de SD-kaart. Het is het beste om de twee vensters naast elkaar te plaatsen.

+ Selecteer alle bestanden in de map `NOOBS` en sleep ze naar het SD-kaartvenster om ze naar de kaart te kopiëren.

![Windows kopie](images/copy3.png)

![macos kopie](images/macos_copy.png)

+ Nadat de bestanden allemaal zijn gekopieerd, kunt u de SD-kaart uitwerpen.