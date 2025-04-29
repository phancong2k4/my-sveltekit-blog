---
title: "Hệ thống phân tán"
date: "2025-04-29"
author: "Phan Văn Công"
---
**Sinh viên: Phan Văn Công**

![Hệ thống phân tán](https://i.ytimg.com/vi/s9d9TWsTzNw/maxresdefault.jpg)
# Hệ thống phân tán là gì?

Hệ thống phân tán (Distributed System) là tập hợp nhiều máy tính độc lập, phối hợp với nhau để thực hiện một mục tiêu chung. Người dùng tương tác với hệ thống như thể nó là một hệ thống duy nhất, mặc dù thực tế nó được phân phối trên nhiều máy khác nhau.

# Các ứng dụng của hệ thống phân tán

- Dịch vụ lưu trữ đám mây: Google Drive, Dropbox, iCloud.
- Mạng xã hội: Facebook, Twitter, Instagram.
- Thương mại điện tử: Amazon, Shopee.
- Ngân hàng trực tuyến: Internet Banking, Mobile Banking.
- Các hệ thống video streaming: Netflix, YouTube.

# Các khái niệm chính của hệ thống phân tán

- **Scalability (Khả năng mở rộng):** Khả năng của hệ thống để xử lý sự gia tăng tải công việc.
- **Fault Tolerance (Chịu lỗi):** Hệ thống vẫn hoạt động ngay cả khi một số thành phần gặp sự cố.
- **Availability (Khả dụng):** Đảm bảo rằng hệ thống luôn sẵn sàng phục vụ người dùng.
- **Transparency (Tính trong suốt):** Người dùng không nhận thấy sự phức tạp bên dưới của hệ thống phân tán.
- **Concurrency (Tính đồng thời):** Nhiều người dùng hoặc tiến trình có thể truy cập tài nguyên cùng lúc.
- **Parallelism (Song song):** Thực hiện nhiều công việc cùng lúc để tăng hiệu suất.
- **Openness (Tính mở):** Khả năng tích hợp và giao tiếp dễ dàng giữa các hệ thống khác nhau.
- **Vertical Scaling (Mở rộng theo chiều dọc):** Nâng cấp phần cứng của máy chủ (thêm CPU, RAM).
- **Horizontal Scaling (Mở rộng theo chiều ngang):** Thêm nhiều máy chủ mới vào hệ thống.
- **Load Balancer (Cân bằng tải):** Phân phối đều lưu lượng truy cập đến các máy chủ khác nhau.
- **Replication (Sao chép dữ liệu):** Lưu trữ nhiều bản sao dữ liệu để đảm bảo an toàn và tăng tốc độ truy cập.

# Ví dụ thực tế: Hệ thống Netflix

Netflix sử dụng hệ thống phân tán toàn cầu:

- **Scalability:** Khi lượng người xem tăng vào giờ cao điểm, Netflix mở rộng hệ thống để đáp ứng.
- **Fault Tolerance:** Nếu một server ở Mỹ bị lỗi, hệ thống tự động chuyển người dùng sang server khác.
- **Availability:** Người dùng có thể xem phim 24/7.
- **Transparency:** Người xem không biết phim đang được lấy từ server nào.
- **Concurrency & Parallelism:** Hàng triệu người có thể xem phim cùng lúc.
- **Openness:** Netflix sử dụng nhiều công nghệ mã nguồn mở.
- **Horizontal Scaling:** Netflix thêm nhiều máy chủ mới khi cần thiết.
- **Load Balancer:** Phân phối người dùng vào các server gần nhất để giảm độ trễ.
- **Replication:** Phim được sao lưu ở nhiều khu vực khác nhau.

# Kiến trúc của hệ thống phân tán

Có nhiều mô hình kiến trúc phổ biến:

- **Client-Server:** Các client gửi yêu cầu đến server xử lý.
- **Peer-to-Peer (P2P):** Các nút mạng vừa đóng vai trò client vừa là server.
- **Multi-Tier:** Phân chia thành nhiều lớp (giao diện, logic nghiệp vụ, cơ sở dữ liệu).
- **Microservices:** Chia hệ thống thành các dịch vụ nhỏ độc lập.
- **Serverless Architecture:** Ứng dụng vận hành mà không cần quản lý server.

# Ví dụ về kiến trúc: Microservices của Amazon

Amazon chia hệ thống thành hàng ngàn dịch vụ nhỏ (microservices) như: quản lý giỏ hàng, thanh toán, tìm kiếm sản phẩm,... Mỗi dịch vụ có thể phát triển, triển khai và mở rộng độc lập.

---
