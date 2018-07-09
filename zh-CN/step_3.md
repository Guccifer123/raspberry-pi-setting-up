## 设置SD卡

如果您的SD卡上还没有Raspbian操作系统，或者您想要重置Raspberry Pi，您可以自己轻松安装Raspbian。 为此，您需要一台具有SD卡端口的计算机 - 大多数笔记本电脑和台式计算机都有一个。

### Rasopbian操作系统通过NOOBS

使用NOOBS软件是在SD卡上安装Raspbian的最简单方法。

#### 下载NOOBS

+ 访问 [Raspberry Pi下载页面](https://www.raspberrypi.org/downloads)。

![下载页面](images/downloads-page.png)

+ 您应该看到一个链接到NOOBS文件的框。 单击该框。

![点击NOOBS](images/click-noobs.png)

+ 最简单的选择是下载文件的zip存档。 请务必注意保存存档的位置，以便您可以快速找到它。

![下载zip](images/download-zip.png)

#### 格式化SD卡

存储在SD卡上的任何内容都将在格式化过程中被覆盖。 因此，如果您要安装Raspbian的SD卡上当前有任何文件，例如来自较旧版本的Raspbian，您可能希望先备份这些文件，以免永久丢失它们。

+ 访问SD Association的网站，下载适用于Windows或Mac的 [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html)。

+ 按照说明安装软件。

+ 将SD卡插入计算机或笔记本电脑的SD卡插槽，并记下分配给它的驱动器号，例如 `F：/`。

+ 在SD Formatter中，选择SD卡的驱动器号以及卡的格式。

#### 从zip存档中提取NOOBS

接下来，您需要从Raspberry Pi网站下载的NOOBS zip存档中提取文件。

+ 查找下载的存档 - 默认情况下，它应位于您的 `下载` 文件夹中。

+ 双击它以提取文件，并保持生成的Explorer / Finder窗口打开。

#### 复制文件

+ 现在打开另一个Explorer / Finder窗口并导航到SD卡。 最好将两个窗口并排放置。

+ 选择 `NOOBS` 文件夹中的所有文件，然后将它们拖到SD卡窗口中，将它们复制到卡上。

![Windows副本](images/copy3.png)

![macos副本](images/macos_copy.png)

+ 文件全部复制完毕后，即可弹出SD卡。