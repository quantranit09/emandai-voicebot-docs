# Tích hợp Zalo

**Bước 1: Tạo tài khoản OA**

Bạn cần có tài khoản OA để sử dụng các chức năng trên hệ thống OA API.

Nếu chưa có tài khoản OA, bạn có thể tạo mới tài khoản[ tại đây](https://oa.zalo.me/home).

<figure><img src="../../.gitbook/assets/image (229).png" alt=""><figcaption><p>Sau khi click “<a href="https://oa.zalo.me/home">tại đây</a>” sẽ được chuyển vào liên kết như trên hình</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (550).png" alt=""><figcaption><p>Bấm để tạo Official Account  mới</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (231).png" alt=""><figcaption><p>Chọn loại hình tài khoản tương ứng với mục đích sử dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (232).png" alt=""><figcaption><p>Nhấn chọn để chọn loại tài khoản tương ứng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (234).png" alt=""><figcaption><p>Nhấn Đăng ký tài khoản</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (235).png" alt=""><figcaption><p>Hệ thống hiển thị màn hình Khai báo thông tin</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (240).png" alt=""><figcaption><p>Điền các thông tin cơ bản cần thiết</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (241).png" alt=""><figcaption><p>Nhấn chọn đồng ý Điều khoản sử dụng -> nhấn <strong>Tạo tài khoản QA</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (244).png" alt=""><figcaption><p>Nhấn <strong>Xác nhận</strong> để đăng ký tài khoản</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (245).png" alt=""><figcaption><p>Thông báo thành công hay thất bại sẽ được trả về, việc tiếp theo là <strong>Bắt đầu xác thực</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (239).png" alt=""><figcaption><p>Ở đây sẽ có 3 loại xác thực, tải lên loại giấy tờ cần thiết </p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (554).png" alt=""><figcaption><p>Sau khi đăng tải các giấy tờ cần thiết, OA sẽ ở trạng thái “Đang chờ duyệt”</p></figcaption></figure>

Lưu ý\*: OA sau khi khởi tạo sẽ cần được hệ thống Zalo kích hoạt trước khi có thể sử dụng. Thời gian kích hoạt dự kiến trong vòng 1 – 7 ngày làm việc.

Điều kiện để tích hợp được AI Chatbot với Zalo OA:

* Tài khoản Zalo OA cần đăng ký Zalo Cloud Account (xem hướng dẫn [tại đây](https://oa.zalo.me/home/documents/guides/huong-dan-tao-ZCA_75))
* Tài khoản Zalo OA cần được nâng cấp lên gói Nâng cao trở lên (xem hướng dẫn [tại đây](https://oa.zalo.me/home/documents/guides/Quan-ly-goi-zalo-oa_5417812380640953602))

**Bước 2: Tạo ứng dụng để liên kết với OA**

Để sử dụng các chức năng thuộc hệ thống OA API, OA sẽ thực hiện thông qua một ứng dụng tương ứng được ủy quyền đại diện cho OA. Một OA có thể ủy quyền cho nhiều ứng dụng tùy theo mục đích và loại dịch vụ cần sử dụng.

Truy cập [tại đây](https://developers.zalo.me/) và đăng nhập bằng tài khoản Zalo của bạn để tạo ứng dụng.

<figure><img src="../../.gitbook/assets/image (555).png" alt=""><figcaption><p>Sau khi được chuyển ở liên kết trên, bấm “Thêm ứng dụng mới”</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (252).png" alt=""><figcaption><p>Sau khi bấm ‘Thêm ứng dụng mới” sẽ được chuyển vào liên kết như trên hình, điền thông tin thích hợp rồi bấm “Tạo ID ứng dụng”</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (556).png" alt=""><figcaption><p>Nhập <strong>Điện thoại liên hệ</strong> và <strong>Email liên hệ</strong> -> nhấn <strong>Lưu thay đổi</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (557).png" alt=""><figcaption><p>Nhấn vào toggle để kích hoạt ứng dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (558).png" alt=""><figcaption><p>Nhấn Đồng ý để kích hoạt ứng dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (560).png" alt=""><figcaption><p>Ứng dụng đã được kích hoạt thành công</p></figcaption></figure>

* **Lấy Zalo App ID**

<figure><img src="../../.gitbook/assets/image (561).png" alt=""><figcaption><p>Nhấn để sao chép ID ứng dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (563).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, dán đoạn text vừa sao chép vào trường <strong>Zalo App ID</strong></p></figcaption></figure>

* **Lấy App Secret Key**

<figure><img src="../../.gitbook/assets/image (565).png" alt=""><figcaption><p>Nhấn vào biểu tượng eye để hiển thị khóa bí mật của ứng dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (566).png" alt=""><figcaption><p>Nhấn để sao chép khóa bí mật của ứng dụng</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (568).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, dán đoạn text vừa sao chép vào trường <strong>App Secret Key</strong></p></figcaption></figure>

* **Lấy OA ID**

Truy cập Zalo OA [tại đây](https://oa.zalo.me/home)

<figure><img src="../../.gitbook/assets/image (181).png" alt=""><figcaption><p>Nhấn vào <strong>Danh sách OA của tôi</strong> để hiển thị danh sách OA</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (569).png" alt=""><figcaption><p>Sao chép <strong>OA ID</strong> cần tích hợp Chatbot</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (570).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, dán đoạn text sao chép vào trường OA ID</p></figcaption></figure>

* **Lấy Access Token**

<figure><img src="../../.gitbook/assets/image (571).png" alt=""><figcaption><p>Nhấn vào <strong>Quản lý Ứng dụng</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (594).png" alt=""><figcaption><p>Tại mục <strong>Công cụ</strong> -> Nhấn chọn <strong>API Explorer</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (595).png" alt=""><figcaption><p>Nhấn và chọn đúng ứng dụng cần tích hợp</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (596).png" alt=""><figcaption><p>Chọn loại <strong>Access Token</strong> là <strong>OA Access Token</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (597).png" alt=""><figcaption><p>Nhấn <strong>Lấy Access Token</strong> -> chọn đúng tài khoản OA của bạn</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (222).png" alt=""><figcaption><p>Tick vào <strong>Đồng ý cho phép ứng dụng quản lý Offcial Account</strong> -> nhấn <strong>Cho phép</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (573).png" alt=""><figcaption><p>Nhấn để sao chép <strong>Access Token</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (574).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, dán đoạn text vừa sao chép vào <strong>OA Access Token</strong> </p></figcaption></figure>

* **Lấy OA Refresh Token**

<figure><img src="../../.gitbook/assets/image (576).png" alt=""><figcaption><p>Nhấn để sao chép <strong>Refresh Token</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (577).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, dán đoạn text vừa sao chép vào <strong>OA Refresh Token</strong></p></figcaption></figure>

*   **Lấy Domain Authentication**

    Theo thay đổi từ chính sách thông tin khách hàng của Zalo OA ([xem tại đây](https://developers.zalo.me/docs/api/developer-notification/-quan-trong-gioi-han-du-lieu-theo-dia-chi-ip-post-7594))\
    Từ ngày **15/03/2024** domain của sever Vagent sẽ thay đổi thành: [https://agw.vagent.ai/](https://agw.vagent.ai/)\
    \*Lưu ý: _Khách hàng đã tích hợp Zalo OA trước ngày 15/03/2024 cần tiến hành tích hợp lại với domain trên để dịch vụ không bị gián đoạn dịch vụ._

<figure><img src="../../.gitbook/assets/image (578).png" alt=""><figcaption><p>Nhấn vào profile -> chọn ứng dụng phù hợp</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (579).png" alt=""><figcaption><p>Nhấn vào <strong>Xác thực Domain</strong> trên menu side-bar</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (580).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, nhấn sao chép <strong>Callback URL</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (581).png" alt=""><figcaption><p>Dán đoạn URL vừa sao chép vào Domain, xóa các đoạn text phía sau, chỉ giữ lại domain như hình -> nhấn <strong>Xác thực</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (582).png" alt=""><figcaption><p>Hệ thống hiện thị pop-up <strong>Chưa được xác thực</strong> -> nhấn vào <strong>Xác thực ngay</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (583).png" alt=""><figcaption><p>Hệ thống hiển thị pop-up <strong>Xác thực quyền sở hữu</strong> -> tại mục Tải tệp HTML lên trang web của bạn -> nhấn vào tải tệp xuống</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (584).png" alt=""><figcaption><p>Tại pop-up <strong>Tích hợp Zalo</strong>, nhấn chọn Thư mục -> chọn tệp vừa tải xuống</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (585).png" alt=""><figcaption><p>Tệp vừa tải xuống đã được chọn</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (587).png" alt=""><figcaption><p>Quay lại màn hình <a href="https://developers.zalo.me/">https://developers.zalo.me/</a>, hệ thống hiển thị pop-up Xác thực thành công -> nhấn <strong>OK</strong></p></figcaption></figure>

* **Cập nhật Webhook**

<figure><img src="../../.gitbook/assets/image (588).png" alt=""><figcaption><p>Nhấn để sao chép Callback URL</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (590).png" alt=""><figcaption><p>Nhấn vào <strong>Thay đổi</strong> để cập nhật Webhook URL</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (591).png" alt=""><figcaption><p>Dán đoạn URL vừa sao chép vào trường Webhook URL -> nhấn <strong>Cập nhật</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (696).png" alt=""><figcaption><p>Giao diện hiển thị sau khi cập nhật Webhook URL -> kích hoạt những mục cần hiển thị</p></figcaption></figure>

Khi muốn hiển thị các tin nhắn dạng hình ảnh, audio, file đính kèm, sticker từ đoạn hội thoại với người dùng tại **Livechat** thì khi tích hợp với Zalo cần kích hoạt các quyền Webhook sau:

* Để **Hiển thị liên kết** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn liên kết**
* Để **Hiển thị tin nhắn** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn text**
* Để **Hiển thị sticker** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn sticker**
* Để **Hiển thị gif** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn gif**
* Để **Hiển thị tin nhắn âm thanh** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn voice**
* Để **Hiển thị tệp tin đính kèm** -> Kích hoạt **Sự kiện người dùng gửi tin nhắn đính kèm file**

<figure><img src="../../.gitbook/assets/image (697).png" alt=""><figcaption><p>Có thể tìm kiếm các lệnh trong Webhook</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (698).png" alt=""><figcaption><p>Trạng thái sau khi kích hoạt các danh mục cần thiết</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (593).png" alt=""><figcaption><p>Kích hoạt Tích hợp Zalo</p></figcaption></figure>

Hoàn thành các bước trên thì đã đầy đủ yêu cầu để **Tích hợp Zalo** -> nhấn **Lưu** để hoàn tất tích hợp
