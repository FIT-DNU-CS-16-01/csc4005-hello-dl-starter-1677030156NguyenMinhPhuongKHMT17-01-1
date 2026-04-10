# Minh chứng bài thực hành - Hello Deep Learning Starter

## Thiết lập môi trường
- Đã clone repositiory bài lab về máy tính.
- Đã thiết lập môi trường Python ảo sử dụng venv với câu lệnh `python -m venv csc4005_env`.
- Cài đặt đầy đủ các thư viện phụ thuộc bằng câu lệnh `pip install -r requirements.txt`.

## Các bước kiểm tra đã chạy
- **Bước 1:** Đã chạy `python check_env.py` - Hệ thống kiểm tra phiên bản Python và các thư viện cốt lõi, sinh ra file log `outputs/logs/env_check.txt`.
- **Bước 2:** Đã chạy `python run_smoke_test.py` - Chạy thử nghiệm mô hình tối thiểu, loss hiển thị giảm dần qua các epochs. Sinh ra các kết quả ở mục `outputs/`.

## Vấn đề gặp phải và cách xử lý
- Quá trình chạy diễn ra trơn tru, không gặp lỗi cài đặt hay thiếu file cấu hình. Hệ thống tạo đủ `loss_curve.png`, `smoke_model.pt` và các log cơ bản để phục vụ bài lab.