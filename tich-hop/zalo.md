# Zalo

Để tích hợp VA với Zalo OA, người dùng cần tạo ứng dụng liên kết với Zalo OA account và lấy mã Page Access Token. Xem hướng dẫn dưới đây để biết chi tiết

### Tạo ứng dụng tại Zalo Developer

* Bước 1: Truy cập trang [https://developers.zalo.me/](https://developers.zalo.me/) -> Click vào avatar tài khoản, chọn **Thêm ứng dụng mới**&#x20;

![](<../.gitbook/assets/image (8).png>)

* Bước 2: Tại giao diện hiển thị điền thông tin ứng dụng, chọn "Tôi không phải là người máy" và chọn **Tạo ID ứng dụng** để hoàn tất

![](<../.gitbook/assets/image (5).png>)

* Bước 3: Sau khi tạo ứng dụng thành công, màn hình hiển thị mục Cài đặt -> chọn **Kích hoạt ứng dụng** để hoàn tất quá trình

![](<../.gitbook/assets/image (22).png>)

### Liên kết ứng dụng với Zalo OA

Tại giao diện cài đặt, tiến hành liên kết ứng dụng vừa tạo với trang Zalo OA&#x20;

* Bước 1: Chọn **Official Account**
* Bước 2: Tại mục **Liên kết với Official Account**, chọn tài khoản OA cần liên kết ứng dụng
* Bước 3: Chọn **Liên kết** để hoàn tất

![](<../.gitbook/assets/image (17).png>)

* Bước 4: Nộp xét duyệt ứng dụng

Chọn **Đăng ký sử dụng API** -> chọn **Official Account API** -> chọn các quyền cần xét duyệt -> Chọn **Nộp xét duyệt** để hoàn tất.

![](<../.gitbook/assets/image (30).png>)

### Lấy Access Token

* Bước 1: Trở về trang chủ -> Chọn **Công cụ** -> Chọn **API Explorer**

![](<../.gitbook/assets/image (21).png>)

* Bước 2: Chọn **Lấy User Access Token** -> Chọn Zalo OA cần lấy mã liên kết

![](<../.gitbook/assets/image (37).png>)

* Bước 3: Tại giao diện hiển thị, chọn **Đồng ý kết nối** và chọn **Cho phép** để hoàn tất

![](<../.gitbook/assets/image (10).png>)

* Bước 4: Sao chép mã Access Token được tạo

![](<../.gitbook/assets/image (34).png>)

### Tích hợp VA với Zalo OA

Chọn **Tích hợp** -> **Kích hoạt tích hợp Zalo ->** Dán mã Access Token vừa tạo vào ô Page Access Token.

![](<../.gitbook/assets/image (31).png>)

### Đăng ký Webhook VA cho ứng dụng Zalo OA

* Bước 1: Copy đường link Webhook của VA tại giao diện tích hợp Zalo&#x20;

![](<../.gitbook/assets/image (25).png>)

* Bước 2:&#x20;
  * Tại trang chủ Zalo developer, chọn avatar tài khoản -> chọn ứng dụng Zalo OA vừa tạo
  * Tại trang quản lý ứng dụng, chọn **Webhook ->** chọn **Thay đổi**
* Bước 3: Tại giao diện hiển thị, copy đường link webhook của VA vào ô **Webhook URL -**> Chọn **Cập nhật** để hoàn tất

![](<../.gitbook/assets/image (20).png>)

