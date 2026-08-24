# Real-time Emotion Recognition with YOLOv12

Giới thiệu:

Một hệ thống Computer Vision nhận diện cảm xúc khuôn mặt theo thời gian thực sử dụng kiến trúc YOLOv12, thiết kế để cân bằng giữa tốc độ suy luận và độ chính xác. Phù hợp triển khai trên thiết bị Edge hoặc server giám sát.

Điểm nổi bật kỹ thuật:

- Áp dụng YOLOv12 để phát hiện khuôn mặt nhanh và ổn định, sau đó đưa ra nhãn cảm xúc bằng mô-đun phân loại nhẹ.
- Tối ưu hoá inference bằng ONNX/TensorRT (hỗ trợ FP16) để giảm độ trễ trên GPU/Edge.
- Pipeline xử lý video real-time với OpenCV, hỗ trợ batching và tăng tốc bằng CUDA.

Công nghệ:

Python, PyTorch, YOLOv12, OpenCV, ONNX, TensorRT, CUDA, NumPy

Link:

Code & tài liệu: https://github.com/khanhbes/Emotion-Recognition-YOLOv12
