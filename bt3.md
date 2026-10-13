Phần1:

&#x20;1. get-content logs\\server.log -encoding utf8

&#x20;2. Tại vì notepad cũng giống như Ram khi bị quá tải dữ liệu thì máy sẽ tự động đẩy qua bộ nhớ ổ C khiến cho máy bị giật lag còn noptepad thì lại nạp thẳng vào ram để xử lí hiện thị khiến máy bị đơ và giật lag có nguy cơ làm treo máy.

&#x20;2.2. Còn khi đọc bằng terminal thì mượt mà do terminal là CLI ,CLI thì lại tốn ít dụng lượng khi sử lí 1000 ảnh sẽ vẫn mượt mà giúp máy giảm bớt dữ liệu phải gánh.

&#x20;3. get-content -filter .\*log



Phần2 : 

&#x20;4. select-string "ERROR" access.log -filter

&#x20;5. 

|Câu hỏi |Lệnh PowerShell|
|-|-|
|dervops-lab\\logs\\server.log|get-content logs\\server.log|
|Bên trong file có chứa lỗi "404"|select-string "404 server.log |



&#x20;

get-content logs\\server.log | select-string "404"

&#x20;6. Get-ChildItem -Path "devops-lab" -Filter "\*.log" -Recurse

&#x20;   Select-String -Pattern "INFO" -NotMatch



Phần3 : 

&#x20;7. get-conent logs\\server.log | select-string "404" > reports\\daily\_report.txt

&#x20;8. get-conent logs\\server.log | select-string "404" >> orts\\daily\_report.txt

&#x20;giải thích 

Hậu quả: Toàn bộ báo cáo cũ ở Câu 7 sẽ bị xóa sạch và thay thế hoàn toàn bằng duy nhất dòng lỗi 404 mới. 



Phần4 :

&#x20;9. Write-Output "Dang loc log..."

"=== LOG REPORT ===" > "reports\\daily\_report.txt"

&#x20;10. Write-Output "Dang loc log..."

Get-ChildItem -Path "devops-lab" -Filter "\*.log" -Recurse | Get-Content | Select-String "404" > "reports\\daily\_report.txt"



Phần5: 

&#x20;11.scripts\\auto\_report.ps1

&#x20;Get-Content "reports\\daily\_report.txt"

&#x20;12.Get-ChildItem -Path "C:\\" -Filter "\*.log" -Recurse

Get-ChildItem -Path "devops-lab\\temp\\" -Filter "\*.log" -Recurse | Get-Content | Select-String "404" > "reports\\daily\_report.txt"

