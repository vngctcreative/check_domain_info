# Check Info Domain

## Giới thiệu
Dự án "Check Info Domain" là một công cụ whois, kiểm tra và tra cứu thông tin tên miền. Người dùng có thể nhập tên miền và kiểm tra các thông tin liên quan đến tên miền đó. Giao diện người dùng được thiết kế thân thiện và dễ sử dụng.

## Các tính năng chính
- Tra cứu thông tin tên miền
- Hiển thị kết quả whois của tên miền
- Giao diện người dùng thân thiện

## Cấu trúc dự án
- **index.html**: Tệp HTML chính cho giao diện người dùng.
- **public/**
  - **assets/**
    - **css/**
      - `font-awesome.min.css`: Tệp CSS cho Font Awesome.
      - `theme.css`: Tệp CSS cho chủ đề.
      - `style.css`: Tệp CSS tùy chỉnh.
      - `ws.toast.css`: Tệp CSS cho thông báo.
    - **img/**: Thư mục chứa hình ảnh.
    - **js/**
      - `jquery-3.6.0.min.js`: Thư viện jQuery.
      - `index.js`: Tệp JS chính cho các chức năng của trang.
      - `ws.toast.js`: Thư viện JS cho thông báo.
      - `bootstrap.bundle.min.js`: Thư viện JS cho Bootstrap.

## Cài đặt
### Yêu cầu hệ thống
- Web server (Apache, Nginx, v.v.)
- PHP 7.3+ (nếu cần thiết cho backend)
- MySQL (nếu cần thiết cho backend)

### Hướng dẫn cài đặt
1. Clone repository:
    ```bash
    git clone https://github.com/vngctcreative/check_domain_info.git
    ```
2. Di chuyển vào thư mục dự án:
    ```bash
    cd Check-Info-Domain
    ```
3. Cấu hình web server của bạn để trỏ đến thư mục dự án.

4. Khởi động web server và truy cập vào trang chủ để bắt đầu sử dụng.

## Sử dụng
1. Mở trình duyệt web và truy cập vào URL của dự án.
2. Nhập tên miền vào ô tìm kiếm và nhấn "Kiểm Tra Domain".
3. Kết quả tra cứu sẽ được hiển thị ngay lập tức.

## Đóng góp
Nếu bạn muốn đóng góp cho dự án, vui lòng tạo Pull Request hoặc mở Issues trên GitHub để chúng tôi có thể thảo luận và xem xét.
