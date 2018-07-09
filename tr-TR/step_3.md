## SD kartınızı ayarlayın

Raspbian işletim sistemine sahip olmayan bir SD kartınız varsa veya Raspberry Pi'nizi sıfırlamak istiyorsanız, Raspbian'ı kolayca yükleyebilirsiniz. Bunu yapmak için bir SD kart bağlantı noktasına sahip bir bilgisayara gereksiniminiz vardır - çoğu dizüstü bilgisayar ve masaüstü bilgisayarlarda bir tane vardır.

### NOOBS üzerinden Raspbian işletim sistemi

NOOBS yazılımını kullanmak, SD kartınıza Raspbian'ı yüklemenin en kolay yoludur.

#### NOOBS indir

+ [Ahududu Pi indirme sayfasını ziyaret edin](https://www.raspberrypi.org/downloads).

![İndirmeler sayfası](images/downloads-page.png)

+ NOOBS dosyalarına bağlantı veren bir kutu görmelisiniz. Kutuyu tıklayın.

![NOOBS'a tıklayın](images/click-noobs.png)

+ En basit seçenek, dosyaların zip arşivini indirmektir. Arşivinizi nereye kaydettiğinize dikkat ettiğinizden emin olun, böylece hızlı bir şekilde tekrar bulabilirsiniz.

![Zip indir](images/download-zip.png)

#### SD kartı biçimlendir

SD kartta saklanan herhangi bir şey biçimlendirme sırasında üzerine yazılacaktır. Dolayısıyla, Raspbian'ı kurmak istediğiniz SD kartın üzerinde herhangi bir dosya varsa, örneğin Raspbian'ın eski bir sürümünde, bu dosyaları önce kalıcı olarak kaybetmemek için geri yüklemek isteyebilirsiniz.

+ SD Association'ın web sitesini ziyaret edin ve Windows veya Mac için [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html).

+ Yazılımı kurmak için talimatları izleyin.

+ SD kartınızı bilgisayara veya dizüstü bilgisayarın SD kart yuvasına takın ve buna tahsis edilen sürücü harfini not edin, örneğin `F: /`.

+ SD Formatter'de, SD kartınızın sürücü harfini seçin ve kartı formatlayın.

#### Zip arşivinden NOOBS ayıklayın

Ardından, Raspberry Pi web sitesinden indirdiğiniz NOOBS zip arşivindeki dosyaları ayıklamanız gerekecektir.

+ İndirilen arşivi bulun - varsayılan olarak `İndirme` klasörünüzde olmalıdır.

+ Dosyaları ayıklamak ve ortaya çıkan Explorer / Finder penceresini açık tutmak için çift tıklayın.

#### Dosyaları kopyala

+ Şimdi başka bir Explorer / Finder penceresi açın ve SD karta gidin. İki pencereyi yan yana konumlandırmak en iyisidir.

+ `NOOBS` klasöründeki tüm dosyaları seçin ve bunları karta kopyalamak için SD kart penceresine sürükleyin.

![windows kopyası](images/copy3.png)

![macos kopyası](images/macos_copy.png)

+ Dosyalar kopyalandıktan sonra SD kartını çıkarabilirsiniz.