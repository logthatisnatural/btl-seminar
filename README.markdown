# Dự Báo Thị Trường Chứng Khoán bằng Machine Learning

## Giới thiệu
Repo này triển khai các phương pháp Học máy kết hợp với những học thuyết về thị trường chứng khoán để dự đoán giá đóng và chỉ số thị trường. Dự án phân tích hai nghiên cứu: dự báo cổ phiếu Apple (AAPL) qua phân tích kỹ thuật (các chỉ số tài chính) và phân tích cảm xúc (dữ liệu từ Twitter), cùng dự báo chỉ số VNINDEX bằng leading indicators và PCA

Repo bao gồm:
- Mã nguồn cho **Phân tích Kỹ thuật** (Linear Regression, LSTM) với dữ liệu giá AAPL (2010–2021)
- Mã nguồn cho **Phân tích Cơ bản** (Logistic Regression, SVM, ANN) dựa trên cảm xúc Twitter
- Tài liệu báo cáo chi tiết

## Kết quả
- **AAPL**: Hồi quy Tuyến tính và LSTM đạt độ chính xác cao; phân tích cảm xúc Twitter có F1-score 62%–75.7%
- **VNINDEX**: MAPE < 1.6% cho dự báo ngắn hạn

## Hạn chế
- Dữ liệu Twitter hạn chế trong việc phản ánh tâm lý thị trường
- Dự báo ngắn hạn hiệu quả hơn dài hạn
- Cần kiểm tra thực tế thêm (backtesting)

## Hướng phát triển
- Kết hợp phân tích kỹ thuật và cơ bản
- Áp dụng các kỹ thuật học sâu tiên tiến hơn 
- Kết hợp thêm các hình thức đánh giá thực tế 

## Tài liệu tham khảo
1. *Xây dựng Mô hình Dự báo Không điều kiện cho Chỉ số Thị trường Chứng khoán*. [Link](https://indjst.org/download-article.php?Article_Unique_Id=INDJST157&Full_Text_Pdf_Download=True)
2. *Hiệu quả của AI trong Dự báo Thị trường Chứng khoán*. arXiv:2107.01031, 2021. [Link](https://arxiv.org/abs/2107.01031)

## Đóng góp
- Hồ Tú Minh (22022674)
- Đỗ Quang Dũng (22022561)
- Phạm Long Nhật (22022520)
