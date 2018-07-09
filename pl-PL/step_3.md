## Skonfiguruj kartę SD

Jeśli masz kartę SD, na której nie ma jeszcze systemu operacyjnego Raspbian, lub jeśli chcesz zresetować Raspberry Pi, możesz łatwo zainstalować Raspboga samemu. Aby to zrobić, potrzebujesz komputera z portem kart SD - większość komputerów przenośnych i stacjonarnych ma taki.

### System operacyjny Raspbian za pośrednictwem NOOBS

Korzystanie z oprogramowania NOOBS to najprostszy sposób na zainstalowanie Raspbian na karcie SD.

#### Pobierz NOOBS

+ Odwiedź stronę [pobierania Raspberry Pi na stronie](https://www.raspberrypi.org/downloads).

![Strona pobierania](images/downloads-page.png)

+ Powinieneś zobaczyć pole z linkami do plików NOOBS. Kliknij pole.

![Kliknij na NOOBS](images/click-noobs.png)

+ Najprostszą opcją jest pobranie archiwum zip z plików. Zwróć uwagę na to, gdzie zapiszesz archiwum, aby móc je szybko znaleźć.

![Pobierz zip](images/download-zip.png)

#### Sformatuj kartę SD

Wszystko, co jest zapisane na karcie SD, zostanie nadpisane podczas formatowania. Jeśli więc karta SD, na której chcesz zainstalować Raspbian, ma obecnie jakieś pliki, na przykład ze starszej wersji Raspbina, możesz najpierw zarchiwizować te pliki, aby nie utracić ich na stałe.

+ Odwiedź stronę SD Association i pobierz [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) dla Windows lub Mac.

+ Postępuj zgodnie z instrukcjami, aby zainstalować oprogramowanie.

+ Włóż kartę SD do gniazda karty SD komputera lub laptopa i zanotuj przypisaną do niej literę dysku, np. `F: /`.

+ W SD Formatter wybierz literę dysku dla karty SD i sformatuj kartę.

#### Wyodrębnij NOOBS z archiwum zip

Następnie musisz wyodrębnić pliki z archiwum zip NOOBS pobranego ze strony Raspberry Pi.

+ Znajdź pobrane archiwum - domyślnie powinien znajdować się w folderze `pobrań`.

+ Kliknij go dwukrotnie, aby wyodrębnić pliki, i pozostaw otwarte okno Eksploratora / Findera.

#### Skopiuj pliki

+ Teraz otwórz kolejne okno Eksploratora / Findera i przejdź do karty SD. Najlepiej ustawić dwa okna obok siebie.

+ Wybierz wszystkie pliki w folderze `NOOBS` i przeciągnij je do okna karty SD, aby skopiować je na kartę.

![kopia okien](images/copy3.png)

![kopia makra](images/macos_copy.png)

+ Po skopiowaniu wszystkich plików możesz wysunąć kartę SD.