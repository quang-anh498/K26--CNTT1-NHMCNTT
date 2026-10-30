**Tên:** Đặng Quang Anh 
**Lớp:** CNTT1
**Môn:** NMCNTT
**Session:** 15
# Vấn đề 
Bạn nhân viên đã vô tình gửi link với quyền Editor cho một ứng viên bên ngoài.
# Yêu cầu 

- Bản thiết kế phân quyền: Bảng phân loại đối tượng tương ứng với các mức quyền truy cập an toàn nhất.
- Kịch bản xử lý sự cố: Quy trình 3 bước xử lý khi phát hiện dữ liệu bị chia sẻ sai quyền.

# Bài làm
Lập bảng 

| Nhòm đối đối tượng  |  Mức quyền truy cập an toàn | Giải thích và phạm vi quyền hạn |
| :---: | :---: | :---| 
| Trưởng phòng Nhân sự | Chủ sở hữu và  Editor | Có quyền giám sát cấp phép truy cập cho mọi người trong nhóm.
| Các Trưởng bộ phận | Commenter | Chỉ được xem danh sách và đưa ra các đánh giá, không được quyền chỉnh sửa.
| Nhân viên  nhân sự | viewer | Tra cứu thông tin để phục vụ công việc liên lạc |
| Ứng viên tuyển dụng | No access | Chặn quyền truy cập| 
 
 Kịch bản xử lý sự cố: 
 Bước 1:  Thay đổi quyền truy cập 
 Bước 2: Kiểm tra đánh giá sự cố ( kiếm tra xem ai đã truy cập ) 
 Bước 3: Khắc phục (Khôi phục lại quyền ) 
