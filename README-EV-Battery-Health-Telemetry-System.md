# EV Battery Health & Telemetry System (VinFast Feliz Neo 2025)

Giới thiệu:

Giải pháp theo dõi telemetry và phân tích sức khỏe pin dành cho xe máy điện VinFast Feliz Neo 2025. Gồm module phần cứng đọc dữ liệu từ BMS, kênh truyền dữ liệu đến backend và giao diện di động để trực quan hóa và cảnh báo.

Điểm nổi bật kỹ thuật:

- Giao tiếp phần cứng tùy chỉnh (CAN/Serial) để thu thập các thông số SOH, SOC, điện áp và dòng sạc.
- Phân tích sức khỏe pin và dự đoán chu kỳ sạc bằng phương pháp thống kê/heuristic; cảnh báo khi phát hiện bất thường.
- Ứng dụng Flutter với biểu đồ thời gian thực, lịch sử telemetry và thông báo tức thì khi xảy ra bất thường.
- Hỗ trợ đồng bộ dữ liệu cloud hoặc lưu cục bộ khi ngoại tuyến.

Công nghệ:

Flutter, Dart, Embedded firmware (C/C++), MQTT/HTTP, Firebase/SQLite, Python cho phân tích dữ liệu

Link:

Code & tài liệu: https://github.com/khanhbes/Vinfast-Batery