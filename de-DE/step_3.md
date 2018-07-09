## Richten Sie Ihre SD-Karte ein

Wenn Sie eine SD-Karte haben, auf der noch kein Raspbian-Betriebssystem installiert ist, oder wenn Sie Ihren Raspberry Pi zurücksetzen möchten, können Sie Raspbian einfach selbst installieren. Dazu benötigen Sie einen Computer mit einem SD-Kartenanschluss - die meisten Laptops und Desktop-Computer verfügen über einen.

### Das Raspbian-Betriebssystem über NOOBS

Die Verwendung der NOOBS-Software ist der einfachste Weg, um Raspbian auf Ihrer SD-Karte zu installieren.

#### Laden Sie NOOBS herunter

+ Besuchen Sie die [Raspberry Pi Downloads Seite](https://www.raspberrypi.org/downloads).

![Downloads Seite](images/downloads-page.png)

+ Sie sollten eine Box sehen, die mit den NOOBS-Dateien verknüpft ist. Klicke auf das Kästchen.

![Klicke auf NOOBS](images/click-noobs.png)

+ Am einfachsten ist es, das Zip-Archiv der Dateien herunterzuladen. Achte darauf, wo du das Archiv speicherst, damit du es schnell wieder finden kannst.

![Zip herunterladen](images/download-zip.png)

#### Formatieren Sie die SD-Karte

Alles, was auf der SD-Karte gespeichert ist, wird während der Formatierung überschrieben. Wenn die SD-Karte, auf der Sie Raspbian installieren möchten, z. B. aus einer älteren Version von Raspbian besteht, möchten Sie diese Dateien möglicherweise zuerst sichern, um sie nicht dauerhaft zu verlieren.

+ Besuchen Sie die Website der SD Association und laden Sie [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) für Windows oder Mac herunter.

+ Folgen Sie den Anweisungen, um die Software zu installieren.

+ Legen Sie Ihre SD-Karte in den SD-Kartenschacht des Computers oder Laptops ein und notieren Sie sich den Laufwerksbuchstaben, zB: `F: /`.

+ Wählen Sie in SD Formatter den Laufwerksbuchstaben für Ihre SD-Karte und das Format der Karte.

#### Extrahiere NOOBS aus dem Zip-Archiv

Als nächstes müssen Sie die Dateien aus dem NOOBS-ZIP-Archiv extrahieren, das Sie von der Raspberry Pi-Website heruntergeladen haben.

+ Suchen Sie das heruntergeladene Archiv - standardmäßig sollte es sich in Ihrem Ordner `Downloads`.

+ Doppelklicken Sie darauf, um die Dateien zu extrahieren, und halten Sie das resultierende Explorer / Finder-Fenster geöffnet.

#### Kopiere die Dateien

+ Öffnen Sie nun ein anderes Explorer / Finder-Fenster und navigieren Sie zur SD-Karte. Am besten positionieren Sie die beiden Fenster nebeneinander.

+ Wählen Sie alle Dateien im Ordner `NOOBS` und ziehen Sie sie in das SD-Kartenfenster, um sie auf die Karte zu kopieren.

![Windows kopieren](images/copy3.png)

![macos kopieren](images/macos_copy.png)

+ Sobald die Dateien vollständig kopiert wurden, können Sie die SD-Karte auswerfen.