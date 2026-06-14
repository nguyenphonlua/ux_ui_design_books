
# CHƯƠNG 10. Di động: Nó không chỉ còn là một thành phố ở Alabama nữa
**CHÀO MỪNG ĐẾN VỚI THẾ KỶ 21. BẠN CÓ THỂ SẼ TRẢI QUA MỘT CHÚT CẢM GIÁC CHÓNG MẶT**

*"SỨC MẠNH VŨ TRỤ KHỔNG LỒ! [nói khẽ] Không gian sống bé tí teo!"*
— **ROBIN WILLIAMS TRONG VAI THẦN ĐÈN TRONG ALADDIN**

Sự ra đời của smartphone (điển hình là iPhone năm 2007) đã thay đổi hoàn toàn cục diện. Lần đầu tiên, chúng ta có một máy tính mạnh mẽ, kết nối Internet, nằm gọn trong túi quần. 

### Tất cả là sự đánh đổi (Tradeoffs)
Thiết kế, về bản chất, là làm việc với các ràng buộc và sự đánh đổi. Hầu hết các vấn đề khả dụng nghiêm trọng đều là kết quả của một quyết định đánh đổi kém. 

Ví dụ, tôi không đọc tin tức của CBS News trên iPhone của mình. Họ chia nhỏ bài viết thành các phần quá nhỏ, mỗi phần mất rất nhiều thời gian để tải, và tôi phải cuộn qua cùng một bức ảnh lặp đi lặp lại. Đây rõ ràng là kết quả của một sự thỏa hiệp (có thể để tối ưu hóa lượt xem trang quảng cáo), nhưng nó đã không đặt đủ trọng lượng vào việc tạo ra trải nghiệm tốt cho người dùng.

### Sự chuyên chế của không gian sống tí hon
Màn hình di động rất nhỏ. Trước đây, bạn có thể tạo một trang web di động chỉ là tập con của trang web đầy đủ (Mobile First). Nhưng thực tế là người dùng di động không chỉ "di chuyển" (on the move); họ ngồi trên ghế sofa ở nhà và muốn làm *mọi thứ*. 

Vì không gian hạn chế, các trang web di động thường trở nên sâu hơn (nhiều cấp độ hơn). Người dùng sẽ phải chạm (tap) nhiều hơn. Điều đó không sao, miễn là mỗi lần chạm đều là một lựa chọn không cần động não và họ tin rằng mình đang đi đúng hướng. 
**Nguyên tắc:** QUẢN LÝ THÁCH THỨC VỀ KHÔNG GIAN KHÔNG ĐƯỢC TRẢ GIÁ BẰNG TÍNH KHẢ DỤNG.

### Nuôi tắc kè hoa (Responsive Design)
Tạo ra một phiên bản trang web có thể co giãn (responsive) để vừa vặn với mọi kích thước màn hình là một công việc khổng lồ và rất khó làm tốt. Nhưng hiện nay, đó là yêu cầu bắt buộc.
Nếu chưa có nguồn lực để làm responsive, ít nhất hãy:
*   **Cho phép phóng to (Allow zooming):** Đừng ngăn người dùng phóng to văn bản nhỏ.
*   **Đừng bỏ tôi đứng trước cửa:** Nếu tôi nhấp vào một liên kết trong email, hãy đưa tôi đến đúng bài viết đó, đừng bắt tôi bắt đầu từ Trang chủ di động.
*   **Luôn cung cấp liên kết đến trang web "đầy đủ":** Cho phép người dùng chuyển đổi giữa phiên bản Di động và Desktop.

### Đừng che giấu các Affordances (Dấu hiệu nhận biết chức năng)
Affordances là những manh mối thị giác cho chúng ta biết cách sử dụng một vật thể (ví dụ: viền nổi của một nút bấm gợi ý rằng nó có thể nhấn được). Trên thiết bị di động, nhiều affordances đang bị che giấu:
*   **Không có con trỏ = Không có hover = Không có manh mối:** Màn hình cảm ứng không phát hiện được ngón tay "lơ lửng" phía trên, nên các hiệu ứng hover (như tooltip, menu thả xuống khi rê chuột) hoàn toàn biến mất.
*   **Flat design (Thiết kế phẳng) - Bạn hay Thù?** Xu hướng thiết kế phẳng loại bỏ các chi tiết 3D, làm giao diện sạch sẽ hơn nhưng cũng xóa đi các manh mối thị giác quan trọng. Nếu dùng Flat design, bạn phải bù đắp bằng các chiều kích khác (vị trí, khoảng trắng, màu sắc tương phản) để người dùng biết đâu là nút, đâu là văn bản.

### Tốc độ
Máy tính không bao giờ được quá chậm. Trên di động, tốc độ tải chậm chạp = sự bực bội. Hãy cẩn thận để các giải pháp responsive không tải về những đoạn code và hình ảnh khổng lồ không cần thiết cho màn hình nhỏ.

### Các thuộc tính khả dụng của Ứng dụng di động
Khi nói đến ứng dụng di động, ngoài các yếu tố cơ bản, còn có 3 thuộc tính quan trọng:
1.  **Thú vị (Delightful):** Ứng dụng phải làm được những điều tưởng chừng không thể, mang lại cảm giác "ma thuật". Nhưng đừng mải mê làm nó thú vị mà quên mất làm nó dễ sử dụng.
2.  **Dễ học (Learnable):** Nhiều ứng dụng sáng tạo với các cử chỉ vuốt chạm phức tạp nhưng lại thiếu hướng dẫn. Nếu người dùng không thể nhớ cách sử dụng vào lần sau, họ sẽ xóa ứng dụng.
3.  **Dễ nhớ (Memorable):** Nếu người dùng phải mất 5 phút để nhớ lại cách bắt đầu một bản vẽ mới mỗi khi mở ứng dụng, họ sẽ sớm bỏ cuộc. Cuộc sống trên di động rất rẻ (99 xu), và sự kiên nhẫn của họ còn rẻ hơn.

### Kiểm tra tính khả dụng trên thiết bị di động
Về cơ bản, quy trình kiểm tra trên di động giống hệt trên máy tính để bàn: Giao tác vụ, quan sát, yêu cầu nghĩ to thành tiếng. 
Thách thức lớn nhất là **hậu cần (logistics)**: Làm thế nào để người quan sát nhìn thấy những gì người dùng đang làm trên màn hình nhỏ, cũng như thấy các cử chỉ ngón tay của họ?
Steve Krug gợi ý một giải pháp tự chế (gọi là "Brundlefly camera"): Gắn một webcam siêu nhẹ lên một chiếc kẹp sách, kẹp vào điện thoại. Nó cho phép người dùng cầm điện thoại tự nhiên, trong khi camera ghi lại chính xác màn hình và ngón tay của họ, truyền về máy tính qua cáp USB.