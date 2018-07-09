## Configurez votre carte SD

Si vous avez une carte SD sur laquelle le système d'exploitation Raspbian n'est pas encore installé, ou si vous voulez réinitialiser votre Raspberry Pi, vous pouvez facilement installer Raspbian vous-même. Pour ce faire, vous avez besoin d'un ordinateur doté d'un port de carte SD - la plupart des ordinateurs portables et de bureau en ont un.

### Le système d'exploitation Raspbian via NOOBS

L'utilisation du logiciel NOOBS est le moyen le plus simple d'installer Raspbian sur votre carte SD.

#### Télécharger NOOBS

+ Visitez la page des téléchargements [Raspberry Pi](https://www.raspberrypi.org/downloads).

![Page de téléchargements](images/downloads-page.png)

+ Vous devriez voir une boîte de lien vers les fichiers NOOBS. Cliquez sur la case

![Cliquez sur NOOBS](images/click-noobs.png)

+ L'option la plus simple consiste à télécharger l'archive zip des fichiers. Assurez-vous de faire attention à l'endroit où vous sauvegardez l'archive, afin de pouvoir la retrouver rapidement.

![Télécharger le zip](images/download-zip.png)

#### Formater la carte SD

Tout ce qui est stocké sur la carte SD sera écrasé pendant le formatage. Donc, si la carte SD sur laquelle vous voulez installer Raspbian contient actuellement des fichiers, par exemple d'une ancienne version de Raspbian, vous pouvez d'abord sauvegarder ces fichiers pour ne pas les perdre définitivement.

+ Visitez le site Web de l'association SD et téléchargez [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pour Windows ou Mac.

+ Suivez les instructions pour installer le logiciel.

+ Insérez votre carte SD dans l'emplacement pour carte SD de l'ordinateur ou de l'ordinateur portable et notez la lettre de lecteur qui lui est attribuée, par ex. `F: /`.

+ Dans SD Formatter, sélectionnez la lettre de lecteur de votre carte SD et le format de la carte.

#### Extrait NOOBS de l'archive zip

Ensuite, vous devrez extraire les fichiers de l'archive zip NOOBS que vous avez téléchargée sur le site Web de Raspberry Pi.

+ Trouver l'archive téléchargée - par défaut, il devrait être dans votre `téléchargements` dossier.

+ Double-cliquez dessus pour extraire les fichiers et gardez la fenêtre Explorateur / Finder qui s'ouvre.

#### Copiez les fichiers

+ Maintenant, ouvrez une autre fenêtre Explorer / Finder et naviguez jusqu'à la carte SD. Il est préférable de positionner les deux fenêtres côte à côte.

+ Sélectionnez tous les fichiers dans le dossier `NOOBS` et faites-les glisser dans la fenêtre de la carte SD pour les copier sur la carte.

![Windows copie](images/copy3.png)

![macos copie](images/macos_copy.png)

+ Une fois les fichiers copiés, vous pouvez éjecter la carte SD.