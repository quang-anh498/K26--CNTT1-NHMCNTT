

|Tiêu chí 	       	      |Absolute Path|Relative Path|
|-|-|-|
|Độ dài|Đường dẫn tuyệt đối :là đường dẫn đầy đủ luôn bắt đầu từ ổ đĩa gốc đi qua tất cả các thư mục cha cho tới đích.|Đường dẫn tương đối  : đường dẫn tính từ vị trí thư mục đang làm việc  không cần  ổ dĩa c|
|Tính di động|Kém :gây lỗi  ngay lập tức khi chạy trên máy của người khác hoặc khi đổi thư mục dự án, vì máy tính của họ không có cấu trúc thư mục .|Cao: Dự án có thể dễ dàng nén gửi cho người khác, chạy trên hệ điều hành khác hoặc đưa lên máy chủ (server) mà không cần sửa lại code .|

&#x09;	



Giải pháp tối ưu: sử dụng đường dẫn tương đối (../data/log/csv).

Ý nghĩa dấu ".." :đại diện cho thư mục cha.

