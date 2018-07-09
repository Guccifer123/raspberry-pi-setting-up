## SD 카드 설정

아직 Raspbian 운영 체제가없는 SD 카드가 있거나 Raspberry Pi를 재설정하려는 경우 Raspbian을 쉽게 설치할 수 있습니다. 이렇게하려면 SD 카드 포트가있는 컴퓨터가 필요합니다. 대부분의 랩톱 및 데스크톱 컴퓨터에는 SD 카드 포트가 있습니다.

### NOOBS를 통한 Raspbian 운영 체제

NOOBS 소프트웨어를 사용하면 SD 카드에 Raspbian을 설치하는 가장 쉬운 방법입니다.

#### NOOBS 다운로드

+ [라즈베리 파이 다운로드 페이지](https://www.raspberrypi.org/downloads)방문하십시오.

![다운로드 페이지](images/downloads-page.png)

+ NOOBS 파일에 연결된 상자가 나타납니다. 상자를 클릭하십시오.

![NOOBS를 클릭하십시오.](images/click-noobs.png)

+ 가장 간단한 옵션은 파일의 zip 아카이브를 다운로드하는 것입니다. 아카이브를 어디에서 저장했는지주의 깊게 다시 확인하십시오.

![zip 다운로드](images/download-zip.png)

#### SD 카드 포맷

SD 카드에 저장된 내용은 서식을 지정하는 동안 덮어 씁니다. 따라서 현재 Raspbian을 설치하려는 SD 카드에 이전 버전의 Raspbian과 같은 파일이있는 경우 영구적으로 손실되지 않도록 파일을 백업 할 수 있습니다.

+ SD 협회 웹 사이트를 방문하여 Windows 또는 Mac 용 [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) 을 다운로드하십시오.

+ 지침에 따라 소프트웨어를 설치하십시오.

+ SD 카드를 컴퓨터 또는 노트북의 SD 카드 슬롯에 넣고 할당 된 드라이브 문자를 적어 둡니다 (예 : `F : /`.

+ SD Formatter에서 SD 카드의 드라이브 문자와 카드의 형식을 선택하십시오.

#### zip 아카이브에서 NOOBS 추출

다음으로, Raspberry Pi 웹 사이트에서 다운로드 한 NOOBS zip 아카이브에서 파일을 추출해야합니다.

+ 다운로드 한 보관 파일을 찾으십시오. 기본적으로 다운로드 파일은 귀하의 `Downloads` 폴더에 있어야합니다.

+ 파일을 두 번 클릭하고 결과 탐색기 / Finder 윈도우를 열어 두십시오.

#### 파일 복사

+ 이제 다른 탐색기 / Finder 창을 열고 SD 카드로 이동하십시오. 두 개의 창을 나란히 놓는 것이 가장 좋습니다.

+ `NOOBS` 폴더에있는 모든 파일을 선택하고 SD 카드 창으로 끌어 카드에 복사하십시오.

![창문 복사](images/copy3.png)

![macos 사본](images/macos_copy.png)

+ 파일이 모두 복사되면 SD 카드를 꺼낼 수 있습니다.