# Tổng quan về Redis

Redis tên đầy đủ là Remote Dictionary Server

Là một kho lưu trữ cấu trúc dữ liệu trong bộ nhớ

Thường được dùng như:

+ Cơ sở dữ liệu key-value
+ Bộ nhớ đệm
+ Message broker
  Là một cơ sở

Là một cơ sở dữ liệu phi quan hệ

Redis lưu trữ dữ liệu trên bộ nhớ chính thay vì lưu trữ trên đĩa cứng hay SSD

## Một số cấu trúc dữ liệu của Redis

+ String
+ Lists: danh sách các string
+ Hashes
+ Bitmaps
+ Geospatial Indexes

## Uu điểm

+ Tốc độ
+ Đa dụng
+ Mã nguồn mở
+ Cấu trúc dữ liệu đa dạng
+ Data Persistence

## Hạn chế 

+ Chi phí
+ Dung lượng
+ Giao diện

## Ung dụng

+ Caching : Sử dụng Redis hiện thực hóa bộ nhớ đệm
+ Giảm độ trễ truy cập dữ liệu với đĩa hoặc SSD
+ Tăng thông lượng và giảm tải cho cơ sở dữ liệu và ứng dụng

## Ung dụng của Redis trong Caching

+ Bộ nhớ đệm trong các trang web
+ Bộ nhớ kết quả truy vấn cơ sở dữ liệu
+ Bộ nhớ đệm cho các đối tượng thường dùng như ảnh, tệp, siêu dữ liệu
+ Các ứng dụng khác: Lưu trữ phiên làm việc, bảng xếp hạng, ứng dụng nhắn tin, sử dụng vị trí, hàng đợi
+ Được ứng dụng bởi: Twitter, StackOverflow,....
