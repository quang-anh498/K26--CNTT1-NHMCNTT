**Tên:** Đặng Quang Anh 
**Lớp:** CNTT1
**Môn:** NMCNTT
**Session:** 15
# Vấn đề 
Nhóm của bạn quản lý 500GB dữ liệu video giám sát campus. Ổ cứng Laptop của các bạn chỉ có 256GB. Nếu đồng bộ toàn bộ về máy, SSD sẽ bị tràn ngay lập tức và gây treo phần mềm đồng bộ.
# Yêu cầu 

-   Giải pháp kỹ thuật: Mô tả cách thiết lập tính năng Files On-Demand để chỉ tải file xuống khi cần mở thực tế.
    
-   Báo cáo dung lượng: Tính toán và chứng minh tính hiệu quả của giải pháp khi dung lượng Cloud lớn hơn dung lượng Local SSD nhiều lần.

# Bài làm 
## **Giải pháp kỹ thuật:**
- **Bước 1: Lựa chọn nền tảng Cloud hỗ trợ** Sử dụng các dịch vụ lưu trữ đám mây có hỗ trợ sẵn ( google drive , one drive...)
- **Bước 2: Cấu hình chế độ mặc định **
 Sau khi cài đặt ứng dụng đồng bộ trên laptop, tiến hành cấu hình thư mục dự án camera giám sát ở chế độ **Online-only** (trên OneDrive thường hiển thị biểu tượng đám mây màu xanh.)
 - **Bước 3: Cơ chế gọi và tải file khi cần mở thực tế**
 Khi nhân viên kỹ thuật cần xem lại một đoạn video giám sát cũ. Ứng dụng đồng bộ chặn thao tác mở tạm thời .
 - **Bước 4: Thiết lập tự động giải phóng dung lượng**
Cấu hình chính sách tự động xóa file khỏi cache local sau một khoảng thời gian không truy cập (ví dụ sau 7 ngày) hoặc cho phép người dùng click chuột phải chọn **Free up space.**
## **Báo cáo dung lượng: Tính toán và chứng minh tính hiệu quả**

**Số liệu bài toán:**

-   Dung lượng dữ liệu Video giám sát trên Cloud:  
`D_Cloud = 500 GB`
    
-   Dung lượng ổ cứng Local SSD của Laptop:  
`D_ssd = 256 GB`
    
-   Tỷ lệ dữ liệu trên Cloud lớn hơn Local SSD:
    
   `D_Cloud/ D_ssd = 500/256 = 1.95 (Lần)`
