# Độ tin cậy của câu trả lời

**Độ tin cậy của câu trả lời**

<figure><img src="../../../.gitbook/assets/image (724).png" alt=""><figcaption><p>Nhấn để bật/tắt Tính năng Độ tin cậy của câu trả lời</p></figcaption></figure>

Độ tin cậy của câu trả lời: là thiết lập nhằm kiểm soát câu trả lời, nếu độ tin cậy của câu trả lời thấp hơn mức thiết lập -> phản hồi theo các điều kiện thiết lập ở bên dưới

<figure><img src="../../../.gitbook/assets/image (725).png" alt=""><figcaption><p>Thiết lập phản hồi dự phònh</p></figcaption></figure>

Tính năng này cho phép Bot phản hồi theo lệnh điều khiển Prompt (Câu lệnh) hoặc phản hồi theo văn bản định sẵn (Nguyên văn):

* **Câu lệnh** (Lệnh điều khiển Prompt): Bạn sẽ nhập lệnh điều khiển cách Bot phản hồi tại đây, mặc định sẽ có sẵn một lệnh điều khiển, bạn có thể tùy chỉnh lệnh điều khiển này, hoặc bỏ qua, thiết lập như mặc địn&#x68;_._ Đồng thời Bot sẽ sử dụng các nội dung trong nền tảng tri thức như nguồn dữ liệu tham chiếu, để phân tích và hình thành các câu trả lời phù hợp, tương ứng với nội dung câu hỏi
* **Nguyên văn:** nhập đoạn văn bản cụ thể mà bạn mong muốn Bot sẽ phản hồi

Nếu người dùng thiết lập độ tin cậy của câu trả lời là trên 10%, thì bot sẽ trả lời các câu hỏi có độ tin cậy trên 10%.&#x20;

* **Đối với các câu trả lời có độ tin cậy dưới 10%:** bot sẽ thay thế các câu trả lời đó bằng thông tin Nguyên văn hoặc Câu lệnh mà người dùng đã thiết lập.&#x20;
* **Đối với trường hợp tắt tính năng:** bot sẽ mặc định trả lời theo dữ liệu do bot tạo ra mà không quan tâm đến độ tin cậy.

Trong trường hợp đã thay đổi Câu lệnh hoặc Nguyên văn nhưng muốn khôi phục Câu lệnh hoặc Nguyên văn của hệ thống, nhấn **Khôi phục phản hồi mặc định**:&#x20;

<figure><img src="../../../.gitbook/assets/image (726).png" alt=""><figcaption><p>Nhấn Khôi phục phản hồi mặc định</p></figcaption></figure>
