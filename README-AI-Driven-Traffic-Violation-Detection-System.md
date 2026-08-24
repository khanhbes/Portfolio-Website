# AI-Driven Traffic Violation Detection System

Giới thiệu:

Hệ thống giám sát giao thông tự động phát hiện hành vi vi phạm như vượt đèn đỏ và không đội mũ bảo hiểm, kết hợp mô hình phát hiện đối tượng và tracking để xác định hành vi theo ngữ cảnh. Hệ thống đồng bộ sự kiện lên ứng dụng di động để cảnh báo và quản lý.

Điểm nổi bật kỹ thuật:

- Hiệu chuẩn vùng (ví dụ: 5-second calibration) giúp xác định vùng tĩnh như vạch dừng để giảm false positive.
- Kết hợp YOLO cho detect và thuật toán Multiple-Object Tracking (MOT) để theo dõi cá thể qua nhiều khung hình.
- Pipeline song song: inference trên backend, lưu sự kiện vào DB, và gửi push notification thời gian thực qua Firebase Cloud Messaging đến app Flutter.
- Thiết kế đóng gói bằng Docker để dễ triển khai.

Công nghệ:

Python, YOLO, Multi-Object Tracking, OpenCV, Flask/FastAPI, Flutter, Firebase (FCM), Docker

Link:

Code & tài liệu: https://github.com/khanhbes/Violation-Detect
