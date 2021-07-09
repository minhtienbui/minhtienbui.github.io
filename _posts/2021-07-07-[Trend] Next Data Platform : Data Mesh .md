***"Banking has to work when and where you need it. The best advice and the best service in financial services happens in real time and is based on customer behavior, using principles of Big Data, mobility, and gamification.” by Brett King
Tạm hiểu là ngân hàng cần phải cung cấp khác hàng 24/7 real time bất kỳ khi nào khách hàng cần. Dịch vụ tài chính tốt nhất là các sản phẩm/dịch vụ diễn ra theo thời gian thực và dựa trên hành vi của khách hàng, sử dụng nền tảng phân tích của Big Data -Dữ liệu lớn, tính di động và việc nhập vai cá nhân hoá tới từng đối tượng khác hàng.”***
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012132-deefbd80-e093-11eb-8ce9-06b6a4e1aaf1.png)
<br/>

Về xu hướng công nghệ data platform hiện nay, đã trải qua khá nhiều
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012157-eadb7f80-e093-11eb-8b43-04171c91b5b1.png)
<br/>
## Data Warehouse - Kho dữ liệu
<br/>
Xu hướng 20–30 năm trước đây khi dữ liệu được thu thập và tập trung hoá vào phân vùng và sử dụng các mô hình dữ liệu khá độ sộ : Star-Schema hoặc Snow Flake để tổ chức và phân tích
Data warehouse là kho dữ liệu tập trung được thu thập, làm sạch, biến đổi và chuẩn hoá (ETL) từ các hệ thống nguồn riêng biệt được thiết kế, tổ chức tích hợp dữ liệu dưới dạng 3NF normalization model để phục vụ việc lưu trữ dữ liệu lịch sử lâu dài. Dữ liệu Data warehouse sẽ sử dụng cho các ứng dụng downstream, ứng dụng online và là đầu vào các Data mart được tạo theo yêu cầu phục vụ báo cáo, phân tích của từng phòng ban…
Data mart là phiên bản thu gọn của kho dữ liệu và được thiết kế tổ chức mô hình dữ liệu đa chiều Multiple Dimension Model để phục vụ việc báo cáo phân tích cho một bộ phận, đơn vị hoặc nhóm người dùng cụ thể trong tổ chức.
<br/>
## Data Lake - Hồ dữ liệu
<br/>
Bước tiếp theo với sự gia tăng của nguồn dữ liệu Big data đặc biệt dữ liệu phi cấu trúc kể đến như Văn bản , mail, video, âm thanh , …
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012171-f3cc5100-e093-11eb-851c-e2b4667126ae.png)
<br/>

Thuật ngữ data lake được đặt tên bởi Pentaho CTO JamesDixon. Ông mô tả data mart (một tập hợp con của kho dữ liệu) giống như một bình nước Lavie, “đã được làm sạch, đóng gói và có cấu trúc để dễ tiêu thụ”.
<br/>
Trong khi Data lake — hồ dữ liệu giống một vùng nước ở trạng thái tự nhiên hơn. Nguồn dữ liệu từ dòng, luồng (stream) (hệ thống nguồn) đi vào data lake. Người dùng có quyền truy cập vào data lake để kiểm tra, lấy mẫu hoặc mining hơn từ bên trong.
<br/>
Một vài đặc tính quan trọng Data Lake
<br/>
***Collect everything*** : Tất cả dữ liệu từ hệ thống nguồn đều được load lên Data Lake. Không loại bỏ dữ liệu nào cả.
***Dive in anywhere*** : Data Lake cho phép người dùng trên các đơn vị kinh doanh khác nhau tinh chỉnh, khám phá và làm giàu thêm dữ liệu liên quan các mảng nghiệp vụ đặc thù của từng đơn vị.
***Flexible access*** : Data Lake cho phép đa luồng truy cập dữ liệu theo các pattern sẵn có trên hạ tầng dùng chung: Batch (theo lô), tương tác, online, search, in-memory and hỗ trợ các engine xử lý khác…
<br/>
## Data Mesh
<br/>
***Data Mesh là thế hệ tiếp theo của Data Lake. Mang tính tổ chức theo kiểu Microservice và hướng domain nghiệp vụ. Các domain nghiệp vụ này mang tính độc lập với nhau và đủ nhỏ để các đơn vị phòng ban có thể self service đảm bảo thời gian Time-to-market nhanh nhất có thể trong bối cảnh cạnh tranh ngày càng khắc nhiệt như ngày nay.***
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012204-05adf400-e094-11eb-86ea-a96a4eb44766.png)
<br/>
Hiện tại “DATA MESH” đang là xu hương khá mới và hot khi doanh nghiệp quan tâm xây dựng Data Plaform. Bài viết xin tập trung sâu hơn vào keyword Data Messh và một số khái niệm liên quan.
Trong thời đại mô hình kinh doanh tự phục vụ Self service , gần như mọi công ty đều coi mình là định hướng bởi dữ liệu, nhưng không phải công ty nào cũng xử lý kiến trúc dữ liệu của họ với mức độ dân chủ hóa và khả năng mở rộng tuỳ theo yêu cầu và hành vi của khách hàng.
<br/>
**Data Driven** : Phương thức kinh doanh dựa trên cơ sở thông tin dữ liệu đã thu thập và phân tích được. Tất cả các quyết định kinh doanh đều dựa trên dữ liệu đã phân tích, dự báo và dự đoán.
<br/>
**Domain Driven** : Hướng nghiệp vụ là cách tiếp cận trong việc thiết kế và phát triển phần mềm với đặc thù logic nghiệp vụ phức tạp như việc triển khai Data Platform, Corebanking cho banking — các dự án này
Yêu cầu về quy trình nghiệp vụ, logic và quy tắc khá phức tạp (Loan, Deposit, Card, Treasury, …. )
Cần mô hình hoá các nghiệp vụ (Logical ) chuyển vào trong code, thiết kế mức vật lý sản phẩm phần mềm (Physical)
Cần có phối hợp, cộng tác giữa nhóm kỹ thuật và nhóm nghiệp vụ (Domain Expert — đầu mối về mảng nghiệp vụ cụ thể)
<br/>
**Data Mesh là gì**
<br/>
***Giống như cách mà các ứng dụng phần mềm hiện nay chuyển từ kiến trúc nguyên khối ( Monolithic ) sang kiến trúc Microservices. Hiểu đơn giản Data mesh là phiên bản nền tảng dữ liệu (data platform) xây dựng theo kiến trúc microservices hướng domain nghiệp vụ, được phân tán , đủ nhỏ cho service/product/usecase để có thể chạy, vận hành độc lập không thụ thuộc lẫn nhau. Mục đích chính là dân chủ hoá quyền sở hữu, tiện lợi cho các phòng ban khối có thể dễ dàng tự khai thác quản trị và bổ sung dự liệu bất cứ khi nào họ cần.***
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012230-11011f80-e094-11eb-9d79-c2763275f279.png)
<br/>

Quyền sở hữu đối với 2 loại dữ liệu thô raw data và dữ liệu đã chuyển đổi (Transformed) theo 2 cách tập trung(Central) hoặc phi tập trung (Decentralized). Điều này tạo ra bốn góc phần tư với các giải pháp khác nhau.
<br/>
![image](https://user-images.githubusercontent.com/52438010/125012248-15c5d380-e094-11eb-9232-f03c460c9a47.png)

