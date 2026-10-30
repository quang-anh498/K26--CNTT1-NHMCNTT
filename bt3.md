**Tên:** Đặng Quang Anh 
**Lớp:** CNTT1
**Môn:** NMCNTT
**Session:** 15
# Vấn đề 
Các thông báo kỹ thuật về cảm biến bị lẫn lộn giữa các tin nhắn tán gẫu và meme hài hước. Thành viên thường xuyên quên deadline vì tin nhắn bị đè nát.
# Yêu cầu 

-   Sơ đồ kiến trúc kênh: Danh sách các Channel cần có và quy định nội dung cho từng kênh.
    
-   Bản quy ước giao tiếp: 3 quy tắc vàng để tránh No-Hello Trap và spam @all.

# Bài làm 
Sơ đồ kiến trúc :
| Danh sách các Channel | Nội dung cho từng kênh | 
| :---: | :---|
| `#announcements` |Kênh thông báo chung: Chỉ dành cho các thông báo quan trọng từ Leader, mốc deadline cốt lõi, hoặc thay đổi phạm vi dự án. | 
| `#proj-smart-parking` | Kênh thảo luận kỹ thuật chính: Nơi trao đổi kiến trúc hệ thống, code, sơ đồ mạch cảm biến và giải pháp lập trình chung của dự án. |
| `#random-meme`| Kênh giải trí: Nơi chia sẻ meme, chuyện cười, link nhạc hoặc tán gẫu xả stress để giữ không khí thoải mái mà không làm loãng kênh công việc.
Bản quy ước giao tiếp :
Quy tắc 1: Triệt tiêu "No-Hello Trap"
Quy tắc 2: Tuyệt đối không lạm dụng `@all` hoặc `@channel`
Quy tắc 3: Bắt buộc sử dụng `Reply in Thread` cho mọi thảo luận chi tiết.
