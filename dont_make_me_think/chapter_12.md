# CHƯƠNG 12. Khả năng truy cập và bạn
**NGAY KHI BẠN NGHĨ MÌNH ĐÃ XONG, MỘT CON MÈO TRÔI QUA VỚI MIẾNG BÁNH MÌ NƯỚNG BƠ BUỘC TRÊN LƯNG**

Mọi người đôi khi hỏi tôi: "Còn khả năng truy cập (accessibility) thì sao? Đó chẳng phải là một phần của tính khả dụng sao?"
Và họ đúng, tất nhiên rồi. Trừ khi bạn quyết định rằng người khuyết tật không nằm trong đối tượng khán giả của mình, bạn thực sự không thể nói trang web của mình khả dụng trừ khi nó có thể truy cập được.

### Những gì nhà thiết kế và lập trình viên nghe được
Khi họ cố gắng tìm hiểu về những gì họ nên làm, các sách hoặc bài báo họ cầm lên inevitably liệt kê cùng một tập hợp các lý do tại sao họ cần làm cho trang web của mình có thể truy cập được. Nhưng có hai lập luận đặc biệt khiến các nhà phát triển 22 tuổi hoài nghi:
*   *___% dân số bị khuyết tật.* (Họ nghĩ đây là sự phóng đại).
*   *Làm cho mọi thứ dễ truy cập hơn sẽ mang lại lợi ích cho tất cả mọi người.* (Lập luận về "Tang" - bột cam dành cho phi hành gia).

Điều tồi tệ nhất về sự hoài nghi này là nó che khuất thực tế rằng thực sự chỉ có **MỘT** lý do quan trọng:
**Đó là điều đúng đắn cần làm.** Và không chỉ đúng đắn; nó vô cùng đúng đắn, bởi vì một lập luận cho khả năng truy cập không được đưa ra đủ thường xuyên là nó cải thiện cuộc sống của một số người **tốt đẹp hơn biết bao nhiêu**. Người mù có quyền truy cập vào máy tính bây giờ có thể tự mình đọc hầu hết mọi tờ báo hoặc tạp chí. Hãy tưởng tượng điều đó. Chúng ta có bao nhiêu cơ hội để cải thiện đáng kể cuộc sống của mọi người chỉ bằng cách làm tốt hơn công việc của mình một chút?

### Nỗi sợ của nhà thiết kế và lập trình viên
Khi họ tìm hiểu thêm về khả năng truy cập, hai nỗi sợ hãi có xu hướng xuất hiện:
*   **Nhiều việc hơn.**
*   **Thiết kế bị thỏa hiệp.** (Họ sợ những "con mèo bơ" - những nơi mà thiết kế tốt cho người khuyết tật và thiết kế tốt cho những người khác sẽ đối đầu trực tiếp).

### 4 điều bạn có thể làm ngay bây giờ
**#1. Sửa các vấn đề khả dụng khiến mọi người bối rối**
Cách tốt nhất để cải thiện khả năng truy cập là kiểm tra nó thường xuyên và liên tục làm mượt những phần khiến *mọi người* bối rối. Nếu một thứ khiến hầu hết mọi người bối rối, nó gần như chắc chắn sẽ khiến người dùng có vấn đề về truy cập bối rối.

**#2. Đọc một bài báo**
Bài báo: *"Guidelines for Accessible and Usable Web Sites: Observing Users Who Work with Screen Readers"* của Mary Theofanos và Janice (Ginny) Redish.
*Insight:* Người dùng màn hình đọc **quét bằng tai của họ**. Họ không nghe từng từ. Họ nghe vài từ đầu tiên của một liên kết hoặc dòng văn bản. Nếu nó không có vẻ liên quan, họ nhanh chóng chuyển sang liên kết tiếp theo.

**#3. Đọc một cuốn sách**
*   *A Web for Everyone* của Sarah Horton và Whitney Quesenbery.
*   *Web Accessibility* của Jim Thatcher và cộng sự.

**#4. Hái những quả thấp (Low-hanging fruit)**
*   Thêm alt text thích hợp cho mọi hình ảnh.
*   Sử dụng các thẻ heading (`<h1>`, `<h2>`, `<h3>`) chính xác.
*   Làm cho các biểu mẫu (forms) của bạn hoạt động với trình đọc màn hình (sử dụng thẻ `<label>`).
*   Đặt liên kết "Bỏ qua đến Nội dung Chính" (Skip to Main Content) ở đầu mỗi trang.
*   Làm cho tất cả nội dung có thể truy cập bằng bàn phím.
*   Tạo độ tương phản đáng kể giữa văn bản và nền.
*   Sử dụng một mẫu (template) có thể truy cập.