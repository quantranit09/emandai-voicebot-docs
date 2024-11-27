# Điều hướng nghiệp vụ (Task Oriented)

**'Điều hướng nghiệp vụ (Task Oriented)'** là tính năng cho phép người dùng thiết lập một số cài đặt nâng cao cho phản hồi của Bot.

Tính năng này giúp Bot có các phản hồi thông minh hơn khi phát hiện một số từ khóa cụ thể. Bằng cách thiết lập các từ khóa cụ thể cho các nội dung phản hồi từ khách hàng, giúp Bot nhận diện và đưa ra phản hồi phù hợp. Phản hồi có thể được hình thành từ kho nền tảng tri thức hiện có hoặc phản hồi bằng các đoạn văn bản cụ thể. Bạn càng thêm nhiều từ khóa vào Bot của mình, Bot càng trở nên thông minh hơn.

**Cách thức thiết lập 'Điều hướng nghiệp vụ (Task Oriented)'**

Nhấp vào nút **‘+ Thêm’** ở trên cùng bên trái màn hình, hệ thống hiển thị popup để tiến hành thêm nghiệp vụ.

<figure><img src="../.gitbook/assets/image (532).png" alt=""><figcaption><p>Hình 1: Thiết lập nghiệp vụ</p></figcaption></figure>

**Nhập tên & chọn nghiệp vụ cần tạo**

<figure><img src="../.gitbook/assets/image (533).png" alt=""><figcaption><p>Hình 2 - Nhập tên nghiệp vụ</p></figcaption></figure>

Đầu tiên, đặt tên nghiệp vụ. Tiêu đề mặc định thể hiện trong trường văn bản sẽ được tạo tự động, bạn có thể thay đổi hoặc giữ nguyên. Nhưng khuyến cáo bạn nên đặt tiêu đề của nhóm điều kiện để thuận tiện trong việc tìm kiếm và thao tác sau này khi phát sinh nhu cầu cập nhật hay sửa chữa

Sau khi đặt tên nghiệp vụ, bạn cần thiết lập thêm một số tiêu chí như:

* Chọn Từ khóa
* Nhập từ khóa (trên lượt nói của khách hàng)
* Thiết lập phản hồi của Bot
* Thu thập thông tin thực thể (tùy chọn)
  * Lựa chọn tham số parameter của thực thể cần thu thập thông tin
  * Phản hồi của Bot khi đã thu thập được đầy đủ các thông tin theo các tham số đã thiết lập
  * Xuất thông tin thu thập vào Google Sheet

**Thiết lập từ khóa (trên lượt nói của khách hàng)**

<figure><img src="../.gitbook/assets/image (539).png" alt=""><figcaption><p>Hình 3: Nhập từ khóa</p></figcaption></figure>

Từ khóa: từ khóa là các từ/cụm từ cố định được người dùng nhập vào để Bot nhận diện và phân loại các phản hồi từ khách hàng, từ đó Bot có thể phân tích và đưa ra phản hồi thích hợp và chính xác nhất

* Tại vùng nhập văn bản: gõ từ/cụm từ sau đó nhấn ‘enter' để hệ thống ghi nhận.
* Nếu cần xóa các từ đã nhập, bạn chỉ cần nhấn vào dấu 'x’ ngay bên phải của từ/cụm từ cần xóa như _hình 4_

<figure><img src="../.gitbook/assets/image (541).png" alt=""><figcaption><p>Hình 4: Nhập từ khóa</p></figcaption></figure>

Sau khi đã nhập các từ/cụm từ, hệ thống sẽ kiểm tra liệu phản hồi của khách hàng có chứa những từ/cụm từ này, nếu lượt tương tác của khách hàng có chứa những từ này thì Bot sẽ có những phản hồi dựa trên các điều kiện được thiết lập sau đây tại mục _**Thiết lập phản hồi của Bot**_

**Thiết lập phản hồi của Bot**

<figure><img src="../.gitbook/assets/image (534).png" alt=""><figcaption><p>Hình 5: Phản hồi của Bot</p></figcaption></figure>

Trong phần này, bạn sẽ tìm hiểu cách thiết lập các cách thức phản hồi của Bot nếu phát hiện trên trong phản hồi của khách hàng có chứa các từ khóa đã thiết lập:

* Văn bản: Bot sẽ trả lời bằng các đoạn văn bản cụ thể theo nội dung người dùng đã nhập
* Prompt: Bot sẽ sử dụng các nội dung trong nền tảng tri thức như nguồn dữ liệu tham chiếu, để phân tích và hình thành các câu trả lời phù hợp, tương ứng với nội dung câu hỏi

**Thu thập thông tin thực thể (Capture Entity)**

<figure><img src="../.gitbook/assets/Component 11 (1).png" alt=""><figcaption><p>Hình 6: Thu thập thông tin thực thể</p></figcaption></figure>

Thực thể là đối tượng/người/địa điểm/số lượng… được đề cập trong phản hồi của khách hàng trong suốt đoạn hội thoại.

Tính năng 'Thu thập thông tin thực thể' sẽ cho phép Bot nhận dạng, phát hiện và ghi nhận lại các thông tin thực thể có đề cập trong phản hồi, câu trả lời của khách hàng

Khi kích hoạt chức năng này trong nhóm điều kiện của chức năng _**'Điều hướng nghiệp vụ'**,_ có nghĩa là sau khi Bot nhận dạng được ý định trong phản hồi của khách hàng có chứa các từ khóa đã thiết lập, Bot sẽ phản hồi lại cài đặt của người dùng, đồng thời kích hoạt chức năng thu thập thông tin thực thể cho các đoạn phản hồi tiếp theo của khách hàng

Mặc định: tính năng 'Thu thập thông tin thực thể' sẽ không được kích hoạt. Nếu bạn kích vào biểu tượng chuyển đổi toggle 'Thu thập thông tin thực thể', hệ thống sẽ kích hoạt chức năng này, tức là Bot sẽ bắt đầu ghi nhận các thông tin thực thể được đề cập từ các phản hồi của khách hàng

<figure><img src="../.gitbook/assets/Component 3.png" alt=""><figcaption><p>Hình 7: Kích hoạt thu thập thông tin thực thể</p></figcaption></figure>

Thông tin thực thể sẽ được đại diện bởi các tham số parameter. Các thông tin thực thể bạn có lấy được từ phản hồi của khách hàng:

* Ngày tháng
* Số nhà
* Tên đường
* Phường
* Quận
* Thành phố
* Thời gian
* Tên khách hàng
* Số điện thoại khách hàng
* Email khách hàng

Lưu ý không bắt buộc phải cài đặt tất cả các tham số này. Bạn có thể tùy chọn cài đặt một hoặc một vài tham số, tùy theo nhu cầu của bạn.

Nhấn thêm/xóa tham số bằng cách nhấn vào biểu tượng **“+”**, hoặc **“-”** nằm ngay bên phải của tham số.

**Thiết lập phản hồi của Bot**

<figure><img src="../.gitbook/assets/image (538).png" alt=""><figcaption><p>Hình 8: Thiết lập phản hồi của Bot</p></figcaption></figure>

Mặc định: tính năng thiết lập phản hồi của Bot sẽ không được kích hoạt như _hình 8_. Nếu bạn nhấn chọn checkbox, hệ thống sẽ cho phép thực hiện chức năng này, tức là Bot sẽ phản hồi dựa trên điều kiện đã thiết lập nếu ghi nhận các thông tin thực thể.

Trong phần này, bạn sẽ tìm hiểu cách thiết lập các cách thức phản hồi của Bot sau khi Bot đã ghi nhận đầy đủ các thông tin tham số:

* Văn bản: Bot sẽ trả lời bằng các đoạn văn bản cụ thể theo nội dung người dùng đã nhập
* Prompt: Bot sẽ sử dụng các nội dung trong nền tảng tri thức như nguồn dữ liệu tham chiếu, để phân tích và hình thành các câu trả lời phù hợp, tương ứng với nội dung câu hỏi

**Xuất thông tin Google Sheet - Export to Google Sheet**

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption><p>Hình 9: Xuất dữ liệu ra file Google Sheet</p></figcaption></figure>

Sau khi kích hoạt tính năng, tất cả các thông tin lấy được sẽ được đính kèm trong file Google Sheet và gửi link vào email mà bạn đăng ký ở mục **Thông tin tài khoản**
