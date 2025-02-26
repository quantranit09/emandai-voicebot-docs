# Thống kê nâng cao

Thống kê nâng cao giúp doanh nghiệp đo lường được các tiêu chí nâng cao tùy theo mục tiêu doanh nghiệp. Ví dụ: số lần báo giá thành công, số lần chốt lịch hẹn thành công,... Hoặc thống kê số lượng ý định thường xuất hiện/ít xuất hiện giúp doanh nghiệp tối ưu luồng hội thoại VA cải thiện trải nghiệm khách hàng

## Tạo mới tiêu chí

Người dùng sử dụng tính năng "Thiết lập thống kê nâng cao" để tạo mới tiêu chí.&#x20;

* Bước 1: Chọn Cài đặt nâng cao -> chọn Thiết lập thống kê nâng cao
* Bước 2: Chọn Tạo mới tiêu chí&#x20;

![](<../.gitbook/assets/image (13).png>)

* Bước 3: Tại giao diện hiển thị, nhập vào tên tiêu chí&#x20;

![](<../.gitbook/assets/image (32).png>)

* Bước 4: Chọn loại phản hồi đánh giá tiêu chí. Có 2 loại
  * Response
  * Parameter

![](<../.gitbook/assets/image (3).png>)

* Bước 5: Thiết lập điều kiện đánh giá tiêu chí
  1. **or (đáp ứng một trong ý định được lựa chọn)**
  2. **and (đáp ứng tất cả các ý định được lựa chọn)**

#### OR

{% hint style="info" %}
Ví dụ: Theo cài đặt Tạo mới tiêu chí dưới đây, nếu phản hồi khách hàng là ý định hỏi tính năng hoặc hỏi hướng dẫn sử dụng thì đều được tính là "Tìm hiểu tính năng".
{% endhint %}

* Chọn điều kiện "OR"
* Chọn "choose\_intent" và chọn ý định cần đáp ứng trong danh sách hiển thị

![](<../.gitbook/assets/image (16).png>)

#### AND

Ví dụ: Doanh nghiệp cần xuất báo cáo về "Số lần báo giá thành công" của VA. Kịch bản cụ thể như sau:&#x20;

![](<../.gitbook/assets/image (29).png>)

Theo kịch bản trên, VA báo giá thành công khi khách hàng đi qua tất cả các bước theo thứ tự sau: Hỏi báo giá -> VA thu thập thông tin (Tên, số điện thoại, email) -> VA xác nhận lại thông tin -> Khách hàng xác nhận đúng -> VA cảm ơn & kết thúc hội thoại&#x20;

Người dùng thiết lập tiêu chí theo điều kiện "AND" như sau:&#x20;

* Chọn điều kiện AND&#x20;
* Chọn "choose\_intent" và chọn ý định cần đáp ứng trong danh sách hiển thị
* Kích hoạt SORT để thiết lập điều kiện đáp ứng tất cả các ý định theo tuần tự từ trên xuống&#x20;

![](<../.gitbook/assets/image (33).png>)

## Xem báo cáo tiêu chí

* Bước 1: Truy cập vào nền tảng Hybridchat để xuất báo cáo tham số ([https://livechat.vnlp.ai/](https://livechat.vnlp.ai/))
* Bước 2: Chọn Thống kê nâng cao để xem báo cáo tiêu chí

![](<../.gitbook/assets/image (9).png>)

