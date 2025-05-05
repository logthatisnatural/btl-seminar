# Dự Báo Thị Trường Chứng Khoán bằng AI và Machine Learning

## Giới thiệu
Kho lưu trữ này triển khai các phương pháp Trí tuệ Nhân tạo (AI) và Học máy (ML) để dự báo thị trường chứng khoán, dựa trên báo cáo *Đánh giá và Nâng cao Các Phương pháp Trí tuệ Nhân tạo trong Dự báo Thị trường Chứng Khoán* của Hồ Tú Minh, Đỗ Quang Dũng và Phạm Long Nhật (5/5/2025). Dự án phân tích hai nghiên cứu: dự báo cổ phiếu Apple (AAPL) qua phân tích kỹ thuật và cảm xúc Twitter, cùng dự báo chỉ số VNINDEX bằng chỉ báo dẫn dắt và PCA.

Kho bao gồm:
- Mã nguồn cho **Phân tích Kỹ thuật** (Linear Regression, LSTM) với dữ liệu giá AAPL (2010–2021).
- Mã nguồn cho **Phân tích Cơ bản** (Logistic Regression, SVM, ANN) dựa trên cảm xúc Twitter.
- Tài liệu báo cáo chi tiết.

## Cài đặt
1. Sao chép kho:
   ```bash
   git clone https://github.com/your-username/stock-market-prediction.git
   cd stock-market-prediction
   ```
2. Cài đặt thư viện:
   ```bash
   pip install -r requirements.txt
   ```
3. Đảm bảo dữ liệu nằm trong thư mục `data/`.

## Sử dụng
- **Phân tích Kỹ thuật**: Chạy `src/technical_analysis/linear_regression.py` hoặc `lstm_model.py`.
- **Phân tích Cơ bản**: Chạy `src/fundamental_analysis/sentiment_analysis.py`.
- Xem `report.pdf` để biết thêm chi tiết.

## Kết quả
- **AAPL**: Hồi quy Tuyến tính và LSTM đạt độ chính xác cao; phân tích cảm xúc Twitter có F1-score 62%–75.7%.
- **VNINDEX**: MAPE < 1.6% cho dự báo ngắn hạn.

## Hạn chế
- Dữ liệu Twitter hạn chế trong việc phản ánh tâm lý thị trường.
- Dự báo ngắn hạn hiệu quả hơn dài hạn.
- Cần kiểm tra thực tế (backtesting).

## Hướng phát triển
- Kết hợp phân tích kỹ thuật và cơ bản.
- Áp dụng học sâu và NLP tiên tiến.
- Tăng cường đánh giá thực tế.

## Tài liệu tham khảo
1. *Xây dựng Mô hình Dự báo Không điều kiện cho Chỉ số Thị trường Chứng khoán*. [Link](https://indjst.org/download-article.php?Article_Unique_Id=INDJST157&Full_Text_Pdf_Download=True)
2. *Hiệu quả của AI trong Dự báo Thị trường Chứng khoán*. arXiv:2107.01031, 2021. [Link](https://arxiv.org/abs/2107.01031)

## Đóng góp
- Hồ Tú Minh (22022674)
- Đỗ Quang Dũng (22022561)
- Phạm Long Nhật (22022520)

## Giấy phép
Dự án sử dụng Giấy phép MIT.