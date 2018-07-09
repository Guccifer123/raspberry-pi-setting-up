## Configura la tua scheda SD

Se hai una scheda SD che non ha ancora il sistema operativo Raspbian su di esso, o se vuoi ripristinare il tuo Raspberry Pi, puoi facilmente installare Raspbian da solo. Per fare ciò, è necessario un computer dotato di una porta per scheda SD - la maggior parte dei computer portatili e desktop ne ha uno.

### Il sistema operativo Raspbian tramite NOOBS

L'uso del software NOOBS è il modo più semplice per installare Raspbian sulla tua scheda SD.

#### Scarica NOOBS

+ Visita la pagina dei download di [Raspberry Pi](https://www.raspberrypi.org/downloads).

![Pagina di download](images/downloads-page.png)

+ Dovresti vedere una casella che collega i file NOOBS. Clicca sulla scatola.

![Clicca su NOOBS](images/click-noobs.png)

+ L'opzione più semplice è scaricare l'archivio zip dei file. Assicurati di prestare attenzione a dove salvi l'archivio, in modo da poterlo ritrovare rapidamente.

![Scarica zip](images/download-zip.png)

#### Formattare la scheda SD

Tutto ciò che è memorizzato sulla scheda SD verrà sovrascritto durante la formattazione. Quindi, se la scheda SD su cui si desidera installare Raspbian ha attualmente dei file, ad esempio da una versione precedente di Raspbian, si potrebbe desiderare di eseguire il backup di questi file per non perderli definitivamente.

+ Visitare il sito Web di SD Association e scaricare [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) per Windows o Mac.

+ Seguire le istruzioni per installare il software.

+ Inserisci la scheda SD nello slot per scheda SD del computer o del laptop e prendi nota della lettera di unità assegnata ad esso, ad es. `F: /`.

+ In SD Formatter, selezionare la lettera dell'unità per la scheda SD e formattare la scheda.

#### Estrarre NOOBS dall'archivio zip

Successivamente, sarà necessario estrarre i file dall'archivio zip NOOBS scaricato dal sito Web Raspberry Pi.

+ Trova l'archivio scaricato: per impostazione predefinita, dovrebbe trovarsi nella cartella `Download`.

+ Fare doppio clic su di esso per estrarre i file e mantenere aperta la finestra Explorer / Finder risultante.

#### Copia i file

+ Ora apri un'altra finestra Explorer / Finder e vai alla scheda SD. È meglio posizionare le due finestre una accanto all'altra.

+ Seleziona tutti i file nella cartella `NOOBS` e trascinali nella finestra della scheda SD per copiarli sulla scheda.

![Windows copia](images/copy3.png)

![copia macos](images/macos_copy.png)

+ Una volta copiati tutti i file, è possibile espellere la scheda SD.