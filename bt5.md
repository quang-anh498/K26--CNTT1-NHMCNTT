# Yêu cầu đầu ra 
## Phần 1: Phân tích hệ thống trang trại Smart Farm

1.  **Input :**
   -  Dữ liệu từ cảm biến nhiệt độ và độ ẩm đất.
    -   Lệnh thủ công từ người nông dân thông qua ứng dụng di động hoặc bảng điều khiển.
        
2.   **Process :**
  -   Bộ vi điều khiển SoC (System on Chip) tiếp nhận tín hiệu, xử lý thuật toán so sánh với ngưỡng nhiệt độ/độ ẩm thiết lập để đưa ra quyết định tưới.
        
3.   **Output :**
    
 - Kích hoạt rơ-le bật máy bơm nước hoặc van điện từ tự động.
  - Hiển thị trạng thái hệ thống lên màn hình LCD hoặc gửi thông báo cảnh báo về điện thoại.

## Phần 2 : Triển khai
🚀 Smart Farm - Hệ Thống Tưới Tự Động IoT 
```Giải pháp công nghệ thông minh ứng dụng Internet Vạn Vậtgiúp tối ưu hóa quy trình chăm sóc cây trồng tại trang trại Lan, phát hiện các rủi ro kịp thời để xử lí , tiết kiệm được sức người hơn, tiết kiệm nước và nâng cao năng suất nông nghiệp.```

 ⚙️ Hướng dẫn cài đặt
Hệ thống để khởi chạy phần mềm điều khiển trên vi điều khiển của trạm trung tâm, sử dụng lệnh cấu hình sau trong termina

 ✨ Tính năng chính

-  [x] Tự động đo đạc độ ẩm đất và nhiệt độ môi trường thời gian thực.
    
-  [x] Tích hợp chế độ tưới  từ xa qua giao diện web
    
-  [ ] Cảnh báo kịp thời để xử lí những vấn đề có thể ảnh hưởng đến quá trình nuôi trồng. 
- [x] Lưu trữ nhật ký hoạt động vào bộ nhớ hệ thống để tối ưu lịch trình tưới.

Phần 3. Kiểm thử & Xử lý sự cố 
Khi hệ thống vận hành liên tục, RAM có thể bị tràn do quá tải nhật ký cảm biến. Giải pháp an toàn đã được cập nhật vào mục **Lưu ý vận hành an toàn** trong file `README.md` ở trên: * **Phương án xử lý:** Tránh ngắt nguồn cứng có thể dẫn đến mất dữ liệu .
