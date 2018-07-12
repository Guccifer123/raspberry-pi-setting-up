## 준비물

### 어떤 라즈베리 파이인지?

[라즈베리 파이 모델](https://www.raspberrypi.org/products/)에는 몇 가지 종류가 있으며, 많은 이들이 라즈베리 파이 3 B+를 선택합니다.

![라스베리 파이 3](images/raspberry-pi.png)

라즈베리 파이 3 B+는 최신식이며, 빠르고, 사용하기 쉽습니다.

Raspberry Pi Zero와 Zero W는 작아서 전력 소모가 적기 때문에 로봇과 같은 휴대용 프로젝트에 유용합니다. 보통은 라즈베리 파이 3으로 프로젝트를 시작하고, 작은 크기의 라즈베리 파이를 사용해야하는 프로토타입을 만들 때 Pi Zero로 바꾸는 것이 낫습니다.

라즈베리 파이를 사고 싶다면 [rpf.io/products로 가십시오](https://rpf.io/products).

### 전원 공급 장치

콘센트에 연결하려면 Raspberry Pi에 있는 마이크로 USB 포트를 사용하세요. (대다수의 휴대폰과 같은 포트입니다.)

최소 2.5A를 제공하는 전원 공급 장치가 필요합니다. [정식 라즈베리 파이 전원 공급 장치](https://www.raspberrypi.org/products/raspberry-pi-universal-power-supply/)를 사용하는 것이 좋습니다.

![전원 공급 장치](images/powersupply.png)

### 마이크로 SD 카드

라즈베리 파이는 모든 파일과 라즈비안 운영 체제를 저장하기 위해 SD 카드가 필요합니다.

![SD 카드](images/pi-sd.png)

8 GB 이상의 마이크로 SD 카드가 필요합니다.

많은 곳에서 라즈비안 운영 체제를 설치한 라즈베리 파이 전용 SD 카드를 판매하고 있습니다.

### 키보드와 마우스

라즈베리 파이를 사용하려면, USB 키보드와 USB 마우스가 필요합니다.

라즈베리 파이를 설정한 후에는 Bluetooth 키보드와 마우스를 사용할 수 있지만, 라즈베리 파이를 설정하기 위해서는 USB 키보드와 마우스가 필요합니다.

### TV 또는 컴퓨터 화면

라즈비안 데스크탑 환경을 보려면, 라즈베리 파이를 연결하기 위한 화면 장비와 케이블이 필요합니다. 화면 장비로는 TV와 컴퓨터 모니터 모두 가능합니다. 화면 장비에 스피커가 내장되어 있다면, 라즈베리 파이로 음향을 재생할 수 있습니다.

#### HDMI

라즈베리 파이에는 최신 TV 및 컴퓨터 모니터의 HDMI 포트와 호환되는 HDMI 출력 포트가 있습니다. 다수의 컴퓨터 모니터에는 DVI 또는 VGA 포트가 있을 수도 있습니다.

![HDM 포트](images/hdmi-port.png)

#### DVI

화면 장비에 DVI 포트가 있다면, HDMI-DVI 케이블을 사용하여 라즈베리 파이를 연결할 수 있습니다.

![dvi 포트](images/dvi-port.png)

#### VGA

일부 화면 장비에는 VGA 포트만 있을 수도 있습니다.

![vga 포트](images/vga-port.png)

라즈베리 파이를 해당 화면 장비에 연결하려면, HDMI-VGA 연결 어댑터를 사용하세요.

![hga 어댑터 포트 vga](images/hdmi-vga-adapter.png)

### 옵션 사항

#### 케이스

라즈베리 파이를 케이스에 넣을 수도 있습니다. 꼭 필요하지는 않지만, 라즈베리 파이를 보호할 수 있습니다. [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-case/) 또는 [Pi Zero 또는 Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-case/)의 정식 케이스를 사용할 수도 있습니다.

#### 헤드폰 또는 스피커

대형 라즈베리 파이 모델 (Pi Zero / Zero W는 제외)에는 스마트 폰 또는 MP3 플레이어에 사용하는 표준 오디오 포트가 있습니다. 원한다면 Pi가 사운드를 재생할 수 있도록 헤드폰이나 스피커를 연결할 수 있습니다. Pi를 연결하는 화면에 내장 스피커가 있으면 Pi는이를 통해 소리를 재생할 수 있습니다.

#### 이더넷 케이블

대형 라즈베리 파이 모델 (Pi Zero / Zero W가 아님)에는 표준 이더넷 포트가있어 인터넷에 연결할 수 있습니다. Pi Zero를 인터넷에 연결하려면 USB 대 이더넷 어댑터가 필요합니다. Raspberry Pi 3와 Pi Zero W는 또한 웹에 무선으로 연결할 수 있습니다.