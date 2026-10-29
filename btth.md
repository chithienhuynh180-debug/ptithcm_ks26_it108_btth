**Bài 1: Quản lý lưu trữ và đường dẫn tệp trong Windows** 
Phần 1:
- Sai lầm vị trí lưu trữ: lưu trong Windows\system32 vì chỗ này thuộc ổ đĩa C nên khi lưu sẽ bị mất dữ liệu khi cài lại Windows và nó sẽ không an toàn.
- Cách đặt tên file: Nam đặt tên file có khoảng trắng đây nên đặt lại là Bai-tap-1.py và Session-01.
- Tốc độ mạng đc đo bằng Mbps còn tốc độ tải của file là MB/s thì 12,5MB/s là tốc độ file chạy rất tốt và nhanh.
- Ổ cứng SSD 256GB nhưng thực tế hiển thị nhỏ hơn vì:
- 1GB = 1 000 000 000 bytes vậy 256GB = 256 000 000 000 bytes 
- Windows hiển thị theo hệ nhị phân: 1GB = 1073741824 bytes 
- Nên 256 000 000 000 bytes = 238,4185791 GB


Phần 2:
D:\IT108-nhap-mon-cntt\Bai-tap-cua-Nam\session-01-bai-tap-1.py.

﻿**Bài 2 : Phân tích hiệu năng hệ thống và quản lý đường dẫn tệp** 
3.
- Đường dẫn tuyệt đối bị lỗi khi đổi máy vì: mỗi máy có những cách ghi đường dẫn khác nhau nên khi dùng đường dẫn tuyệt đối chũng sẽ bị gãy và hiện lỗi
 
- Input (đầu vào)
- click chuột vào ứng dụng hoặc ngón tay bấm vào biểu tượng shoppee trên điện thoại


- Process (quá trình xử lí)
- Hệ điều hành sẽ tạo ra một vùng để chứa RAM cho shoppee
- Dữ liệu từ Shoppee sẽ tải lên RAM
- CPU sẽ lấy dữ liệu từ RAM để xử lí


- Out (đầu ra)
- Biểu tượng logo Shopee và màn hình chờ của shopee hiện ra
- Cung cấp mạng để tải dữ liệu các sản phẩm.


- Đường dẫn tương đối
- ../assets/logo_shopee.png
- ../assets/icon_user.png
- ../assets/image_product1.jpg


- 3 cách để giảm lag dựa Task Manager
- Tắt bớt những Tab không cần thiết
- Tắt nguồn để giải phóng bớt RAM
- End task cho một số ứng dụng ỡ Task Manager

**﻿Bài 3 : Thiết kế hệ thống IoT thông minh và quản lý cấu hình** 
Mô hình DIKW cho hệ thống trang trại
- Data (dữ liệu)
- Thu thập thông tin về môi trường
- Lượng mưa
- Chỉ số độ ẩm
- Ánh sáng


- Information (thông tin)
- Cung cấp thông tin cho chủ vườn
- Hiển thị nhiệt độ và độ ẩm qua từng giờ


- Knowledge (Hiểu biết)
- Thiết lập các hệ thống bơm nước tự động
- Cần lắp đặt thêm mái phía trên dạng kéo tránh bị nắng kiến chết khô hoặc mưa làm ngập úng


- Wisdom (trí tuê)
- Tối ưu hóa việc tưới nước thông qua dự báo thời tiết
- Lắp hệ thống báo động cảm biến xung quanh khi các chỉ số về nhiệt độ và độ ẩm  có vấn đề

**﻿Bài 4 : Tối ưu tài nguyên máy tính và xây dựng hệ thống lưu trữ khoa học**
  Phần 1: 
- Máy bị lag vì: mở 20 tab chorme nên khiến bị RAM đầy và gây ra hiện tượng lag, đầy bộ nhớ nên những dữ liệu của những tab không cần thiết sẽ bị đẩy xuống ổ cứng để nhường cho những tab cần RAM. Khiến ổ cứng chậm hơn RAM thì dữ liệu không thể chuyển đến CPU để CPU xử lí gây ra hiện tượng chậm chuột, lag,...
- RAM: là bộ nhớ tạm thời, dữ liệu sẽ bị mất khi tắt nguồn hoặc cài lại Windows, RAM càng nhiều thì có thể để càng nhiều tab và tốc độ xử lí cực kì nhanh.
- Storage: là chỗ để lưu trữ dữ liệu lâu dài, không bị mất dữ liệu khi tắt nguồn và chậm hơn RAM.

Phần 2:
D:\IT108-HCMKS26-CNTT2\Bai-tap-cua-Nhan\Session-03-Bai-code-cua-toi.py

﻿**Bài 5 : Phân tích tốc độ truyền dữ liệu và quản lý đường dẫn tệp an toàn** 
Phần 1:
- Absolute Path (đường dẫn tuyệt đối): điểm xuất phát C:\ hoặc D:\, khi chép thư mục sang máy khác sẽ bị báo lỗi (File Not Found)
- Relative Path (đường dẫn tương đối): điểm xuát phát là dấu . hoặc .. , sẽ không bị lỗi khi chép thư mục sang máy khác và chạy mượt trên mọi máy
- 1 Bytes = 8 bits  =>  80 bits = 10 Bytes => 10 MB/s
- Theo hệ thập phân: 1GB = 1000MB => 2GB = 2000MB
- 1s -> 10MB => 2000MB -> 200s  
- Theo hệ nhị phân: 1GB = 1024MB => 2GB=2048MB
- 1s -> 10MB => 2048MB -> 204,8s

Phần 2:
- ./db.csv , ../data/db.csv
  
**Bài 6 : Thiết kế hệ thống ứng dụng theo mô hình DIKW và quản lý tệp cấu hình** 
1. Mô hình DIKW (MoMo-Lite) 
- Data: Các bản ghi giao dịch như là ngày giờ, số tiền chuyển và nhận,.... 
- Information: Báo cáo các chi tiêu theo tháng như ăn uống, giải trí. 
 
- Knowledge: Hệ thống sẽ so sánh các chi tiêu và đưa ra các cảnh báo về mức chi tiêu quá mức trong giời gian qua.
- Wisdom: Gợi ý kế hoạch tiết kiệm chi tiêu cá nhân dựa trên thói quen chi tiêu sao cho hợp lí và tránh bị chi tiệu quá mức
 
2. Các module trong mô hình IPO 
- Input: Luồng thanh toán (QR, chuyển khoản) và cài đặt hạn mức từ người dùng. 
- Process: Phân loại giao dịch và phân tích thói quen chi tiêu trong tháng 
- Output: hiển thị các mục đã chi tiêu cảnh báo và gợi ý cách chi tiêu và tiết kiệm.

**Bài 1 : Tối ưu hóa quy trình khởi tạo hạ tầng Smart-Farm qua PowerShell** 
Phần 1: Phân tích
- 2 Lỗi:
- Thứ nhất: tên folder có khoảng trắng
- Thứ hai: khi có cd thì tên folder phải để trong “ “

Phần 2: Hoàn thiện
mkdir "Smart Farm Project\src\sensors\temperature"

﻿**Bài 2 : Chẩn đoán lỗi thực thi và xác định vị trí làm việc trong Terminal** 
- HĐH: Windows PowerShell
- Lệnh tạo thư mục: mkdir drink_module
- Di chuyển vào thư mục vừa tạo: cd drink_module
- Tạo 2 file trống: New-Item -Itemtype File “coffee.txt”, “tea.txt”

﻿**Bài 3 : Kiến trúc sư hạ tầng server chuyên nghiệp** 
- mkdir smart-farm/data/logs, smart-farm/code
- New-Item -ItemType File -Path "config.json", "sensors.py", ".env"  
- Copy-Item  "smart-farm\code"  "backup\code_v1" -Recurse
- Yêu cầu đầu ra
Input (đầu vào):
- Tạo các thư mục: code, data/logs, và backup.
- Tạo các file cùng lúc với cấu hình: config.json, sensors.py, .env

Process (xử  lí)
- mkdir smart-farm/data/logs, smart-farm/code, backup
- New-Item -ItemType File -Path "smart-farm/data/logs/config.json", "smart-farm\code\ sensors.py", "smart-farm/data/logs/.env"  -Force
- Copy-Item -Path "smart-farm\code"  "backup\code_v1" -Recurse


Output (Đầu ra):
- Tạo ra đc cây thư mục
  
**Bài 4 : Xử lý lỗi đường dẫn khi triển khai dự án**
- Phần 1: Bảng so sánh Absolute Path và Relative Path
  
|Tiêu chí | Absolute Path (Đường dẫn tuyệt đối) | Relative Path (Đường dẫn tương đối) |
|:---:|:---:|:---:|
|Độ dài | Dài, ghi đầy đủ đường dẫn | Ngắn gọn hơn | 
|Tính di động |Thấp, phụ thuộc vào ổ đĩa và tên máy | Cao hơn, dễ chia sẻ project cho người khác | 
	

Phần 2: Lựa chọn giải pháp tối ưu và Giải thích 
- chọn Relative Path (../data/logs.csv) vì đường dẫn này ngắn gọn, dễ quản lý và thuận tiện khi chia sẻ project cho người khác.
- Ý nghĩa ký hiệu ..: lùi ra 1 cấp thư mục so với thư mục hiện tại rồi vào /data/logs.csv.
  

**Bài 5 : Thiết kế quy trình tự động quản lý tệp bằng Terminal**
-Yêu cầu đầu ra
sơ đồ:
1. Input (file thô)
2. Process: coi là file hay thư mục nếu là thư mục thì bỏ qua còn nếu là file thì sẽ phân loại theo đuôi
3. Output: đuôi .png/ .jpg/ -> (mv media/), đuôi .py -> (mv scripts/), đuôi .tmp -> (rm)
   
- Danh sách câu lệnh kịch bản cho Robot:
- mkdir -p media scripts
- mv .png .jpg ./media/
- mv .py ./scripts/
- rm .tmp

**Bài 6 : Thiết lập môi trường làm việc cho hệ thống Smart-Farm trên SoC**
- mkdir smart-farm/bin, smart-farm/config, smart-farm/data
- (New-Item -Itemtype File config\.env).Attributes = "Hidden"
- mkdir Public
- New-Item -Itemtype File Public\template.ps1
- Copy-Item .\Public\template.ps1 .\smart-farm\bin\pump_control.ps1 
- Get-ChildItem smart-farm -Recurse -Force

- Input:
- Tạo cây thư mục: mkdir smart-farm/bin, smart-farm/config, smart-farm/data
- Tạo file ẩn: (New-Item -Itemtype File config\.env).Attributes = "Hidden"

Process:
- Tạo cây thư mục: mkdir smart-farm/bin, smart-farm/config, smart-farm/data
- Tạo file ẩn: (New-Item -Itemtype File config\.env).Attributes = "Hidden"
- Tạo thư mục: mkdir Public
- Tạo file: New-Item -Itemtype File Public\template.ps1
- Sao chép từ file của Pubic sang thư mục bin và đổi tên: Copy-Item .\Public\template.ps1 .\smart-farm\bin\pump_control.ps1 
- Liệt kê toàn bộ file và folder trong smart-farm: Get-ChildItem smart-farm -Recurse -Force

- Output:
- Tạo ra smart-farm/ bin/pump_control.ps1, và tạo ra config/.env và hiện file .env

**Bài 1 : Xử lý Log máy chủ dung lượng lớn**
- Phần 1: Phân tích
- Không nên mở file 800MB bằng Notepad vì: ứng dụng sẽ cố nạp toàn bộ tệp vào RAM, khiến máy tính bị giật lag hoặc hiển thị thông báo “Not responding”
- Trong CMD không dùng lệnh cat để xem toàn bộ nội dụng của file mà dùng lệnh type filename.txt hoặc dùng more filename.txt (xem từng trang màn hình)
- Lệnh cat trong PowerShell là alias của Get-Content nên sẽ dùng để xem nội dung trong file.


- Phần 2: Hoàn thiện
- Xem toàn bộ nội dung tệp: Get-Content server_log_800MB.log
- Xem 10 dòng cuối cùng để kiểm tra lỗi: Get-Content sever_log_800MB.log -Tail 10

**﻿Bài 2 : Xử lý sự cố Website từ Access Log** 
Phần 1: Phân tích
- Get-ChildItem dùng để liệt kê ra các file và các tệp
- Câu lệnh Get-ChildItem -Recurse -Filter “404” là dùng để kiếm các tệp và file bên trong có chứa “404” 
- select-string: dùng để kiếm văn bản, chuỗi chữ.


Phần 2: Hoàn thiện
- select-string “ERROR” access.log

**Bài 3 : Thống kê sự cố TIMEOUT trên máy chủ** 
Phần 1:Phân tích
- Get-Content filename.txt | select-string “...” | Measure-Object -Line
- Xem ndung của file   ->  Tìm các dòng có chữ “...” -> Đếm số dòng xuất hiện 

Phần 2: Triển khai
- (Get-Content log.txt | select-string “TIMEOUT” | Where-Object { $_ -notmatch "NOT TIMEOUT" }).Count

**﻿Bài 4 : Xây dựng quy trình lưu nhật ký hệ thống** 
Phần 1: So sánh
-  Ghi đè: Tạo mới tệp nếu chưa có, hoặc xóa toàn bộ nội dung cũ để ghi dữ liệu mới vào (tương đương Out-File).
-  Ghi nối tiếp: Tạo mới tệp nếu chưa có, hoặc ghi thêm dữ liệu mới vào cuối tệp hiện tại (tương đương Out-File -Append).

- Ghi đè:
- Rất cao: Chỉ cần chạy chạy nhầm vào tệp đang lưu trữ là toàn bộ dữ liệu trước đó sẽ bị xóa sạch.
- Phù hợp khi muốn tạo mới báo cáo độc lập
- Mặc định sử dụng UTF-16 LE. Dễ gây lỗi hiển thị ký tự  khi xem bằng các công cụ chỉ hỗ trợ UTF-8/ANSI.


- Ghi nối tiếp:
- Rất thấp: Bảo toàn nguyên vẹn dữ liệu cũ, chỉ chèn thêm dòng mới vào cuối tệp
- Phù hợp cho việc theo dõi liên tục 24/7 để dồn lỗi phát sinh theo thời gian thực mà không làm mất lịch sử trước đó.
- Mặc định là UTF-16 LE. Nếu nối tiếp vào một file sẵn có khác bảng mã, có thể dẫn tới xung đột encoding giữa các phần nội dung.
  
Phần 2: Lựa chọn
- Chọn cách ghi nối tiếp:
- Get-Content server.log | Select-String "ERROR" | Out-File daily_report.txt -Append -Encoding utf8
- Lập luận lý do:
- Giúp giữ toàn bộ dòng log lỗi đã thu thập từ trước đó, tránh việc xóa mất kết quả của lần quét trước.


**Bài 5 : Tối ưu quy trình xử lý Log hằng ngày** 
Phần 1:Thiết kế kiến trúc
- Xác định 4 khối cấu trúc của PowerShell Script:
1. Header block (Khối thông tin script): Dùng ghi chú (#) để lưu thông tin tên script, tác giả, mục đích và ngày khởi tạo.
2. Biến cấu hình: Khai báo các đường dẫn tệp nguồn (server.log) và tệp đích báo cáo (report.txt) bằng biến bắt đầu với ký tự $.
3. Thông báo tiến trình: Dùng lệnh Write-Host để xuất các bước thực thi và trạng thái ra màn hình để đảm bảo không ghi đè vào file kết quả
4. Logic xử lý: Đọc nội dung file log (Get-Content), đưa qua pipeline để lọc chuỗi lỗi 404 (Select-String), ghi dòng tiêu đề === HE THONG TU DONG LOC LOG === và nối tiếp các dòng lỗi tìm được vào file kết quả bằng toán tử >> hoặc Out-File -Append.

Phần 2: Sản phẩm
- # Dat ten file nguon va file dich 
- $duong_dan_log = "server.log" 
- $duong_dan_report = "report.txt" 
- # Thong bao tien trinh ra man hinh
- Write-Host "Dang khoi tao va loc log..." 
- # logic xu ly: 
- #  Ghi tieu de vao file report.txt
- "=== HE THONG TU DONG LOC LOG ===" > $duong_dan_report
- # Doc file log -> Loc chuoi 404 -> Ghi noi tiep (>>) vao file report.tx
- Get-Content $duong_dan_log | Select-String "404" >> $duong_dan_report
- # Thong bao xong 
- Write-Host "Da hoan thanh xuat bao cao!"

**Bài 6 : Rà soát Script bảo trì hệ thống** 
Phần 1: Phân tích (Auditing)
- Path: chỉ đến đường dẫn của ổ đĩa
- Recurse: cho phép đi vào bên sâu bên trong để lấy file
- Force: cho phép xóa các file bị ẩn (hidden) hoặc chỉ đọc (read-only) mà không hỏi xác nhận. 
- Hậu quả khi chạy đoạn script trên: Xóa sạch toàn bộ hệ điều hành Windows, dữ liệu phần mềm và tệp tin người dùng 

- Áp dụng 3 nguyên tắc "Vàng":
1. Hiểu rõ trước khi chạy: Không bao giờ copy-paste mã từ AI vào máy chủ khi chưa phân tích từng tham số.
2. Khoanh vùng phạm vi: phải giới hạn đường dẫn cụ thể, tuyệt đối không dùng đường dẫn gốc (/ hoặc C:\).
3. Mô phỏng an toàn: Không chạy thử trên môi trường test trước khi thực thi lệnh hủy diệt dữ liệu.



Phần 2: Triển khai (Safe Script)
- Set-Location .\logs
- select-string “WARNING” .\system.log | Out-File .\issues.txt
- Remove-Item  ..\*.tmp -Force


Phần 3: Kiểm thử (Verify)
PowerShell
- Get-Content .\issues.txt
- Get-ChildItem -Recurse *.tmp
- Test-Path issues.txt

**Bài 1 : Chuẩn hóa tài liệu Markdown cho dự án**
Phần  1: Phân tích
- Lỗi 1: sai thứ tự cấp tiêu đề
- Kết quả Render: Markdown vẫn hiển thị được H3 nhưng làm sai cấu trúc phân cấp tài liệu 


- Lỗi 2: thiếu dấu ! trước [Logo Dự án] (https://greentech.vn/logo.png)
- Kết quả Render:  không hiển thị hình ảnh ra màn hình. chỉ hiển thị một đường link văn bản có thể nhấp vào 

- Lỗi 3: dòng Rất quan trọng muốn in đậm để trong cặp dấu *...* 
- Kết quả Render: in ra chữ in nghiêng và nếu muốn in đậm phải bỏ trong hai cặp dấu **...**


  Phần 2: Hoàn thiện
  # Lợi ích của rau sạch                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  
  ## Danh sách các loại rau   
  ![Logo dự án](https://greentech.vn/logo.png)
  - **Rất quan trọng**
 
**﻿Bài 2 : Chuẩn hóa tài liệu cài đặt hệ thống** 
- Input (Văn bản thô):
- Thông tin tài liệu kỹ thuật hướng dẫn cài đặt và thiết lập cảm biến độ ẩm DHT22 cho trang trại hoa Lan.
- Các câu lệnh thực thi dòng lệnh trên Terminal (cập nhật hệ thống, cài đặt thư viện, raspi-config, crontab...).
- Dữ liệu sơ đồ kết nối chân cảm biến và lưu ý vị trí lắp đặt thực tế.
  
Output (Giao diện render chuyên nghiệp):
- Phân cấp tiêu đề : Sử dụng Heading theo Markdown (#, ##, ###) để phân chia từ chuẩn bị đến triển khai.
- Sử dụng bảng Markdown (Table) để so sánh (DHT11 cũ vs DHT22 mới).
- Danh sách công việc (Task List): check list ( -[ ] ) để chuẩn bị thiết bị kiểm tra.
- Xử lý bẫy ký tự (Escape): Sử dụng ký tự thoát \ trước các ký tự đặc biệt như \*, \# khi hiển thị dạng text thuần để tránh lỗi định dạng ngoài ý muốn.

  
# HƯỚNG DẪN CÀI ĐẶT CẢM BIẾN ĐỘ ẨM CHO TRANG TRẠI LAN.

## 1. Tổng quan
- Cảm biến độ ẩm giúp theo dõi độ ẩm không khí trong nhà lưới, đảm bảo môi trường tối ưu cho Lan phát triển

**Thiết bị cần chuẩn bị (task list):**
- ✅ Cảm biến độ ẩm (DHT22 / AM2302)
- ✅ Raspberry Pi / Jetson / soC
- ✅ Dây nối Dupont
- ✅ Tua vít, băng keo, ốc vít
- ✅ Thẻ nhớ đã cài hệ điều hành

**Bảng so sánh cảm biến cũ và mới**

| Tiêu chí | Cảm biến DHT11 (Cũ) | Cảm biến DHT22 (Mới) |
| :--- | :--- | :--- |
| Dải đo độ ẩm| 20% - 90% | 0% - 100% |
| Độ chính xác | Thấp (±5%) | Cao (±2%) |
| Giá thành | Rẻ hơn | Đắt hơn |
| Ứng dụng| Học tập cơ bản | Nhà kính, trang trại lan |

## 2. Các bước cài đặt:
**1. Cập nhật hệ thống:**
- Mở Terminal và cập nhật danh sách gói.
```bash
sudo apt update && sudo apt upgrade -y
```
 **2. Cài đặt thư viện cho cảm biến DHT22**
 - Cài đặt thư viện đọc dữ liệu từ cảm biến.
```bash
sudo apt install -y git python3-pip
sudo pip3 install Adafruit_DHT
 ```
**3. Kích hoạt giao tiếp 1-Wire (nếu dùng DHT22)** 
- Bật giao tiếp 1-Wire trên hệ thống.
```bash
sudo raspi-config                # Chọn: interface Options >
                                 # 1-Wire > Enable
``` 
**4. Kiểm tra module đã được nhận**
- Sau khi bật 1-Wire, kiểm tra thiết bị.
```bash
ls /sys/bus/w1/devices/          # Kết quả có dạng 28-xxxxxxx
```
**5. Chạy thử chương trình đọc cảm biến**
- Tải và chạy file Python mẫu.
```bash
git clone https://github.com/adafuit/Adafruit_Python_DHT.git
cd Adafruit_Python_DHT/examples
```
```bash
python3 AdafruitDHT.py 22 4      # 22: DHT22, 4: GPIO pin 
                                 # Nhận kết quả độ ẩm và nhiệt độ
```
**6. Tự động chạy khi khởi động (tùy chọn)**
- Thêm vào contab để đọc dữ liệu định kỳ.
```bash
crontab -e                       # Thêm dòng(ví dụ mỗi 5 phút)                            
                                 */5 * * * * python3 /home/pi/read_dht22.py
```
### 3. Sơ đổ kết nối
| DHT22 | Raspberry Pi (BCM) |
|:---|:---|
|🟥 VCC | 3.3V (Pin 1)|
|⬛ GND | GND (Pin 6)|
|🟨 Data| GPIO4 (Pin 7)|
|⬜ NC| (không kết nối)|

#### 4. Vị trí lắp đặt
- Lắp cảm biến ở nơi thoáng, tránh ánh nắng trực tiếp và  nước bắn vào.

##### 5. Kiểm tra kết quả.
```bash
Temp=28.4*    Humidity=67.1%
pi@farm:~ $
```
﻿**Bài 3 : Giảm chi phí vận hành Chatbot AI**                                                                                                                                                                               
Phần 1. Phân tích bài toán: Vì sao Markdown giúp AI xử lý nhanh hơn?
- Cơ chế Token: AI không đọc từng từ mà chia văn bản thành các mẫu ký tự nhỏ (Token).
- HTML Chứa hàng loạt <div>, <table>, <tr>, class, style khiến số lượng token tăng vọt lên ~2.350 tokens.
- Markdown tinh gọn: Chỉ dùng các ký hiệu tối giản (#, -, **) nên tốn rất ít token (~620 tokens, giảm ~74%).
- Tốc độ xử lý: Càng ít token đầu vào, AI tính toán càng ít. Thời gian phản hồi giảm từ 8.2 giây xuống còn 1.6 giây (nhanh hơn ~80%).
  
Phần 2. So sánh & Đánh giá
1. Bảng so sánh Markdown và HTML
|Ngôn ngữ | Markdown | HTML |
|:---:|:---:|:---:|
|Số lượng kí tự | Nhiều kí tự | Ít kí tự |
|Độ dễ đọc với người dùng | Làm rối mắt người dùng | Rõ ràng, trực quan, đọc là hiểu ngay |
|Số lượng Tokens | Tốn rất cao | Không tốn nhiều vì là văn bản thuần túy |
|Thời gian AI phản hồi | Chậm | Nhanh |

2. Giải pháp cho hệ thống "GreenTech"
- Lựa chọn: Dùng định dạng Markdown làm dữ liệu giao tiếp với AI.
- Lý do lựa chọn:
- Phản hồi nhanh cho nông dân: Giảm độ trễ từ 8.2s còn 1.6s, giúp người dùng nhận hướng dẫn xử lý sâu bệnh ngay lập tức kể  cả khi mạng yếu.
- Tiết kiệm tới 74% chi phí

**Bài 4 : THIẾT KẾ PROMPT TỐI ƯU CHO AI ASSISTANT**

**Thiết kế kiến trúc: Bản Prompt hoàn chỉnh viết bằng Markdown**

**Mô hình IPO trong trang trại thông minh**
![ảnh bài](https://rikkeiedu-storage.s3.ap-southeast-2.amazonaws.com/uploads/editor-images/1787648044474_7a916fcc-9287-48ea-a454-2b5fdfbf14de.webp)

# 1. Bốí cảnh
- Tôi là sinh viên năm nhất
- Chưa có nhiều kiến thức nền
- Đang học công nghệ thông tin

## 2. Nội dung
- Giải thích khái niệm mô hình IPO trong trang trại thông minh
- Cần lên kế hoạch về mô hình này như thế nào ?
- Thêm ví dụ gần gũi, dễ hiểu

### 3. Yêu cầu 
- Trình bày rõ ràng, ngắn gọn
- Có dấu gạch đầu dòng 
- Nội dung đọc dễ hiểu 
- Từ ngữ đơn giản

**Câu trả lời của AI**

**🟡 Khái niệm mô hình IPO trong Trang trại thông minh**

- Mô hình IPO (viết tắt của Input – Process – Output) là tư duy nền tảng trong lập trình và thiết kế hệ thống, mô tả luồng đi của dữ liệu từ lúc nhận vào đến lúc tạo ra kết quả:

- Input (Đầu vào): Dữ liệu thu thập từ môi trường thực tế thông qua các cảm biến (nhiệt độ, độ ẩm đất, ánh sáng, nồng độ pH...).

- Process (Xử lý): Bộ não trung tâm nhận dữ liệu từ Input, tính toán, so sánh với các ngưỡng cài sẵn để đưa ra quyết định logic.

- Output (Đầu ra): Hành động thực thi tác động ngược lại môi trường thông qua các thiết bị chấp hành (bật máy bơm, quạt thông gió, đèn LED, gửi thông báo về điện thoại).

**🔴 Ví dụ trực quan, gần gũi: Hệ thống tưới cây tự động**
- **vd: bạn đang làm một hệ thống tưới cây**

- Input: Cảm biến cắm vào đất đo được độ ẩm hiện tại là 25% (đất đang rất khô).

- Process: Vi điều khiển nhận giá trị 25%, kiểm tra logic đã cài trước:

- **Nếu độ ẩm nhỏ hơn 40%, kích hoạt bật máy bơm; ngược lại thì tắt.**

- Vì 25% < 40%, bộ xử lý ra lệnh: BẬT MÁY BƠM.

- Output: máy bơm phun nước tưới cây; đồng thời gửi tin nhắn thông báo về ứng dụng điện thoại: "Đất khô, đã tự động tưới nước."

**🔵 Kế hoạch từng bước xây dựng mô hình IPO (Dành cho sinh viên IT)**

**Bước 1: Xác định bài toán thực tế**

- Quyết định đối tượng giám sát (ví dụ: tưới rau, thông gió chuồng gà, hay điều hòa nhiệt độ nhà màng).

- Đặt ra tiêu chí đo đạc và ngưỡng mong muốn (ví dụ: giữ độ ẩm đất luôn từ 50% – 70%).

**Bước 2: Lập danh sách phần cứng theo từng khối**

- Khối Input: Chọn cảm biến tương ứng (cảm biến độ ẩm đất soil moisture, cảm biến nhiệt độ DHT11/DHT22, cảm biến quang trở LDR).

- Khối Process: Chọn board mạch điều khiển phù hợp cho người mới bắt đầu (Arduino Uno, ESP8266, hoặc ESP32 tích hợp sẵn Wi-Fi/Bluetooth).

- Khối Output: Module rơ-le (relay 5V), động cơ máy bơm mini 5V/12V, còi buzzer cảnh báo, hoặc màn hình LCD hiển thị trạng thái.

**Bước 3: Viết mã nguồn xử lý logic (Code Process)**

- Đọc tín hiệu số hoặc analog từ chân cảm biến vào biến lưu trữ.

- Viết hàm chuẩn hóa dữ liệu (mapping giá trị thô thành đơn vị phần trăm % hoặc °C).

- Sử dụng cấu trúc điều kiện logic để quyết định xuất xung điện kích hoạt chân Output.

**Nhận xét theo các yêu cầu (Task List)**

- ✅ Trình bày rõ ràng, ngắn gọn
- ❎ Có dấu gạch đầu dòng
- ✅ Nội dung đọc dễ hiểu
- ❎ Ngôn ngữ đơn giản

**Bài 5 : Xây dựng bộ tài liệu kỹ thuật cho dự án Smart Farm**

**PHẦN 1: PHÂN TÍCH HỆ THỐNG**

- Input: Cảm biến nhiệt độ, độ ẩm không khí/đất, ánh sáng, lệnh điều khiển và cài đặt từ app.

- Output: Kích hoạt bơm tưới, quạt thông gió, đèn bổ sung; thông báo cảnh báo.  

**- Sơ đồ luồng: Cảm biến -> Gateway -> Cloud/Server -> App di động -> Thiết bị điều khiển (bơm,quạt,dèn)** 
 
 PHẦN 2: NỘI DUNG TẬP TIN README.mdMarkdown# 🚀 SMART-FARM: Hệ Thống IoT Cho Trang Trại Lan

- **SMART-FARM giúp theo dõi môi trường tự động, tiết kiệm chi phí và cảnh báo kịp thời** 

![sơ đồ hệ thống và các bước sử dụng](https://rikkeiedu-storage.s3.ap-southeast-2.amazonaws.com/uploads/editor-images/1787648283613_687ec2e7-229c-4942-a347-080fae59560a.webp)


# 1. Cài đặt nhanh

1. Quét mã QR hoặc tải ứng dụng **Smart-Farm** trên **Google Play** / **App Store**.
2. Mở ứng dụng, nhập tài khoản và mật khẩu được cấp.
3. Quét mã vạch trên bộ Gateway để tự động đồng bộ cảm biến và bắt đầu theo dõi.


## 2. Tính năng 

- [x] Giám sát các chỉ số môi trường theo thời gian thực.
- [x] Phân loại và cảnh báo đa cấp độ (Tốt, Cảnh báo, Nguy hiểm).
- [x] Bật/tắt thủ công hoặc chạy chế độ tự động cho bơm, quạt, đèn.
- [x] Báo cáo lịch sử theo ngày, tuần, tháng cho chủ vườn.

### 3. Bảng thông số kỹ thuật

| Thông số | Cảm biến | Độ đo chuẩn | Ngưỡng cảnh báo |
| :--- | :--- | :--- | :--- |
| **Nhiệt độ** |  DHT22 | 22°C – 28°C | > 30°C |
| **Độ ẩm đất** | Điện dung v1.2 | 60% – 75% | < 60% |
| **Độ ẩm không khí** | DHT22 | 70% – 85% | < 60% |
| **Ánh sáng** | BH1750 | 1000 – 1500 Lux | > 2000 Lux |

#### 5. Chu kỳ Fetch – Decode – Execute
- **Fetch:** CPU trạm nạp lệnh từ RAM vào thanh ghi lệnh (IR) qua địa chỉ từ bộ đếm chương trình (PC).
- **Decode:** Khối điều khiển giải mã lệnh, nhận diện thao tác xuất mức logic HIGH ra chân GPIO kết nối rơ-le máy bơm.
- **Execute:** CPU xuất tín hiệu điện áp đóng rơ-le, cấp nguồn cho máy bơm hoạt động và cập nhật trạng thái hệ thống.

##### 6. Chuyển hóa dữ liệu theo mô hình DIKW
- **Data:** Cảm biến gửi giá trị thô: `35`°C và `50`% độ ẩm.
- **Information:** Xử lý ngữ cảnh: *Nhiệt độ hiện tại 35°C (vượt ngưỡng 30°C), độ ẩm 50% (dưới chuẩn 60%)*.
- **Knowledge:** Hoa lan gặp nhiệt độ cao kèm ẩm thấp sẽ mất nước nhanh, dễ cháy chóp lá nếu không hạ nhiệt kịp thời.
- **Wisdom:** Hệ thống tự động kích hoạt **phun sương 5 phút** kết hợp **quạt thông gió**, tránh tưới ngập gốc gây thối rễ do sốc nhiệt.


**PHẦN 3: KIỂM THỬ**
- Giả định: RAM trạm Gateway chạm mức 100% do tích tụ file log.   
- Hành vi xử lý: Thiết bị rơ-le chuyển về trạng thái ngắt để khóa van tưới chống ngập úng, lưu trạng thái hiện tại xuống bộ nhớ flash và tự khởi động lại dịch vụ an toàn.

**﻿Bài 6 : Sự cố tài liệu dự án trên GitHub** 
Phần 1: phân tích
- khi tải file .docx lên GitHub, trình duyệt không thể xem trước trực tiếp nội dung. Các thành viên khác trong nhóm buộc phải tải file về máy mới đọc được, gây bất tiện lớn trong quy trình làm việc nhóm.
- Ngược lại, Markdown (.md) được GitHub dựng giao diện tự động ngay trên trình duyệt với đầy đủ tiêu đề, danh sách, khối mã và bảng biểu chuẩn mực


- File Word (.docx) là tệp gồm nhiều cấu trúc. Git không thể đọc và phân tích từng dòng ký tự bên trong.
- Ngược lại, Markdown là tệp văn bản thuần theo từng dòng, giúp Git hiểu chính xác vị trí thay đổi


- Markdown lại an toàn và nhẹ hơn vì:
- Markdown chỉ lưu chuỗi ký tự thô kèm vài ký hiệu định dạng (#, **, -), dung lượng chỉ tính bằng vài chục đến vài trăm byte (nhẹ hơn hàng trăm lần). 
- Vì là chuỗi văn bản nếu mất 1 byte dữ liệu trong quá trình truyền tải, file chỉ mất duy nhất ký tự tại vị trí lỗi đó hoặc hiển thị một ký tự lạ vì vậy nội dung và cấu trúc tài liệu còn lại vẫn hoàn toàn nguyên vẹn

Phần 2:
[link stackedit](https://stackedit.io/app#)