Phần1 :

1\. Sai lầm của Nam là sử dụng lệnh (Get-ChildItem -Filter "\*404\*"). Lệnh này chỉ liệt kệ các file có trong thư mục là viết tắt của (ls và dir) chỉ tìn các file có chứa "\*404\*" nên dẫn đến kết quả rỗng.

2\. **Get-childitem** sử dụng để tìm các tệp file có chứa tên theo mình muốn gọi.

3\. **Select-string** dùng để liệt kê các dòng thông tin có chứa những chữ như "error" để sắp xếp tất cả chúng lại giúp ta không phải ngồi mò từng dòng 1.



Phần 2 : 

select-string "ERROR" access.log -filter





&#x20;

