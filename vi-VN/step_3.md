## Thiết lập thẻ SD của bạn

Nếu bạn có một thẻ SD mà không có hệ điều hành Raspbian trên nó, hoặc nếu bạn muốn thiết lập lại Raspberry Pi của bạn, bạn có thể tự mình dễ dàng cài đặt Raspbian. Để làm như vậy, bạn cần một máy tính có một cổng thẻ SD - hầu hết các máy tính xách tay và máy tính để bàn có một cổng như vậy.

### Hệ điều hành Raspbian thông qua NOOBS

Sử dụng phần mềm NOOBS là cách dễ nhất để cài đặt Raspbian trên thẻ SD của bạn.

#### Tải xuống NOOBS

+ Truy cập trang tải xuống [Raspberry Pi](https://www.raspberrypi.org/downloads).

![Trang tải xuống](images/downloads-page.png)

+ Bạn sẽ thấy một khung có liên kết đến các file NOOBS. Nhấp vào khung.

![Nhấp vào NOOBS](images/click-noobs.png)

+ Tùy chọn đơn giản nhất là tải xuống file nén zip của các tệp tin. Đảm bảo chú ý đến nơi bạn lưu tệp lưu trữ để bạn có thể tìm lại nhanh chóng.

![Tải xuống mã zip](images/download-zip.png)

#### Định dạng thẻ SD

Mọi thứ được lưu trữ trên thẻ SD sẽ bị ghi đè trong khi định dạng. Vì vậy, nếu thẻ SD mà bạn muốn cài đặt Raspbian hiện có bất kỳ tệp nào trên đó, ví dụ từ phiên bản cũ của Raspbian, bạn có thể muốn sao lưu các tệp này trước để không bị mất vĩnh viễn.

+ Truy cập trang web của Hiệp hội SD và tải xuống [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) cho Windows hoặc Mac.

+ Làm theo hướng dẫn để cài đặt phần mềm.

+ Lắp thẻ SD của bạn vào khe cắm thẻ SD của máy tính hoặc máy tính xách tay và ghi chú ký tự ổ đĩa được cấp cho nó, ví dụ: `F: /`.

+ Trong SD Formatter, chọn ký tự ổ đĩa cho thẻ SD của bạn và định dạng thẻ.

#### Trích xuất NOOBS từ kho lưu trữ zip

Tiếp theo, bạn sẽ cần giải nén các tệp từ kho lưu trữ zip NOOBS mà bạn đã tải xuống từ trang web Raspberry Pi.

+ Tìm kho lưu trữ đã tải xuống - theo mặc định, nó sẽ nằm trong thư mục `Tải xuống` của bạn.

+ Bấm đúp vào nó để giải nén các tập tin, và giữ cửa sổ Explorer / Finder kết quả mở ra.

#### Sao chép tệp

+ Bây giờ mở một cửa sổ Explorer / Finder khác và điều hướng đến thẻ SD. Tốt nhất nên đặt hai cửa sổ cạnh nhau.

+ Chọn tất cả các tệp trong thư mục `NOOBS` và kéo chúng vào cửa sổ thẻ SD để sao chép chúng vào thẻ.

![windows copy](images/copy3.png)

![macos copy](images/macos_copy.png)

+ Khi các tệp đã được sao chép xong, bạn có thể đẩy thẻ SD ra.