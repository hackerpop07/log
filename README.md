# log
[Thực hành] Xem log của ứng dụng web
Mục tiêu
Luyện tập việc xem log của một ứng dụng PHP.

Mô tả
Tạo một ứng dụng PHP đơn giản. Xem các log được ghi nhận của ứng dụng.

Có 2 loại log cần theo dõi: Log truy cập và Log lỗi.

Hướng dẫn
Bước 1: Tìm vị trí lưu file log.

Tùy vào hệ điều hành đang dùng, file log có thể được lưu ở những vị trí khác nhau.

Chẳng hạn:

Windows: c:\program files (x86)\php\{PHP Version}
Linux: 
/var/log/apache2/error.log
/var/www/logs/httpd/
Bước 2: Mở file access_log để xem ghi nhận các truy cập

Bước 3: Mở file error_log để xem ghi nhận các lỗi

Có thể cố ý thêm các dòng code phát sinh lỗi trong mã nguồn của ứng dụng để quan sát error_log.

Bước 4: Tùy chỉnh nơi ghi log.

