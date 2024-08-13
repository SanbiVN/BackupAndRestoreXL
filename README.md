# BackupAndRestoreXL
 Add-in giúp tự động Lưu, Sao lưu và khôi phục dự án Excel

[Click vào đây để tải xuống](https://github.com/SanbiVN/BackupAndRestoreXL/releases/download/backup_and_restore_excel/BackupAndRestoreXL_v2.22.zip)

[![Lượt tải](https://img.shields.io/github/downloads/SanbiVN/BackupAndRestoreXL/total.svg)](https://github.com/SanbiVN/BackupAndRestoreXL/releases/download/backup_and_restore_excel/BackupAndRestoreXL_v2.22.zip) 


Hôm nay tôi chia sẻ với các bạn Add-in tự động Lưu, Sao lưu và khôi phục dự án Excel, giúp bảo vệ dữ án của bạn tránh khỏi những rủi ro như:
1. Quá trình lưu làm hỏng ứng dụng của bạn.
2. Bạn cần trở về phiên sao lưu cũ vì phiên mới bị sai sót.

Vì vậy việc sao lưu là cần thiết cho dự án của bạn.

Với Add-in này hoàn toàn tự động sao lưu sau mỗi lần bạn thực hiện lưu dự án.
Với việc cài đặt các thông số một cách dễ dàng với form hoặc hàm.
Với các chức năng sao lưu, khôi phục, xóa tệp sao lưu rất linh hoạt.

Add-in có một chức năng đơn giản nhưng sẽ khiến các bạn thích thú khi sử dụng, đó là thông báo Tên tệp, dung lượng và thời gian lưu sau khi bạn thao tác lưu. Giúp các bạn biết được ứng dụng đã được lưu một cách trực quan.

# Hướng dẫn sử dụng

Các lệnh thực thi để đóng mở và cài đặt thông số:
(Chỉ cần gõ =Backup_ các hàm liên quan sẽ được gợi ý)

Thực thi	|Gõ Hàm ô bất kỳ	|Chú thích
---------|----------------|-----------------
Mở form đầy đủ cài đặt	|=Backup_Settings()	|
Bật sao lưu tự động|	=Backup_On()	|
Tắt sao lưu tự động|	=Backup_Off()	|
Sao lưu bằng tay|	=Backup_BookActivated()	Hữu dụng khi đã tắt sao lưu tự động|
Hiện thư mục sao lưu|	=Backup_ShowDirectories()	|
Thay đổi thư mục sao lưu|	=Backup_ChooseDirectories()	|
Khôi phục cài đặt mặc định|	=Backup_Reset()	|

# Mục cài đặt của Add-in


![settings backup and restore excel](https://user-images.githubusercontent.com/58664571/210329538-739b6a8f-0833-48cb-a9d4-199f6d894b26.jpg)


# Danh sách sao lưu và khôi phục

![list add-in backup and restore](https://user-images.githubusercontent.com/58664571/209465576-38f9c089-db63-4232-b41f-58d29585aa06.png)


# Phím tắt

Ctrl+Alt+Shift+S để thực hiện sao lưu dự án hiện tại, khi chế độ tự động sao lưu đã tắt.\
Ctrl+Alt+Shift+D để mở thư mục chứa tệp đã sao lưu.

# Cài đặt

Vào tab Developer, vào Excel Add-in, sau đó nhấn Browse... để đến đường dẫn chứa Add-in.

![setup add-in backup and restore](https://user-images.githubusercontent.com/58664571/209465567-24c182a2-3724-491e-97aa-813aaee998e2.png)


Đây là phiên bản đầu tay nên sẽ có lỗi xảy ra trong quá trình sử dụng, các bạn tham khảo và đóng góp ý kiến bên dưới bài viết.
Chúc thành công!
