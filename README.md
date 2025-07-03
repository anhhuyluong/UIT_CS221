# 📘 Phân tích cảm xúc các đánh giá sản phẩm trên sàn Amazon

## 🧠 Giới thiệu

* **Tên môn học**: Xử lý ngôn ngữ tự nhiên - Natural Language Processing
* **Mã môn học**: CS221 - **Lớp**: CS221.P21
* **Năm học**: Học kì 2 - Năm học: 2024 - 2025
* **Giảng viên**: TS. Nguyễn Trọng Chỉnh
* **Mục tiêu đồ án**: Xây dựng hệ thống phân tích cảm xúc (sentiment analysis) trên các đánh giá sản phẩm bằng tiếng Anh trên sàn thương mại điện tử Amazon. Dữ liệu bao gồm hàng nghìn phản hồi người dùng, và mô hình được huấn luyện để phân loại các đánh giá thành các nhãn cảm xúc như **tích cực**, **tiêu cực** hoặc **trung tính**.

## 📂 Cấu trúc thư mục

| Tên file                             | Mô tả                                                                 |
|-------------------------------------|----------------------------------------------------------------------|
| `Amazon_Final_Preprocessing.ipynb`  | Thực hiện tiền xử lý dữ liệu văn bản: làm sạch, loại bỏ stopword, chuẩn hóa. |
| `Amazon_Final_EDA_and_Statistics.ipynb` | Phân tích khám phá dữ liệu (EDA), thống kê số lượng nhãn và chiều dài văn bản. |
| `Amazon_Final_LR_TFIDF.ipynb`       | Huấn luyện mô hình Logistic Regression với TF-IDF.                  |
| `Amazon_Final_NB_TFIDF.ipynb`       | Huấn luyện mô hình Multinomial Naive Bayes với TF-IDF.             |
| `Amazon_Final_SVM_TFIDF.ipynb`      | Huấn luyện mô hình SVM (LinearSVC) với TF-IDF.                      |

## Quá trình chạy các file
1. Chạy file EDA_and_Statistics để có được hai file train và test dưới định dạng csv
2. Sau khi có được hai file csv, chạy file Final_Processing để tạo ra hai file csv đã được làm sạch (Sử dụng thư viện TextBlob nên thời gian thực thi khoảng 3 tiếng)
3. Chạy các file mô hình theo thứ tự tùy ý

## Thành viên nhóm: 
| STT    | MSSV          | Họ và Tên              |Vai trò    | Email                   |
| ------ |:-------------:| ----------------------:|----------:|-------------------------:
| 1      |22520550|Lương Anh Huy|Trưởng nhóm| 22520550@gm.uit.edu.vn|
| 2      |22520967|Hồng Khải Nguyên|Thành viên| 22520967@gm.uit.edu.vn|

## 🛠️ Công nghệ và thư viện
Python 3.x
NLTK
TextBlob
Scikit-learn
Pandas
Matplotlib
Seaborn
Logistic Regression
Multinomial Naive Bayes
Support Vector Machine (SVC)

## 📊 Kết quả So sánh Mô hình
* Các độ đo hiển thị là **Weighted Avg** trong classification report
  
| Mô hình                     | Accuracy | Precision | Recall | F1-score |
|----------------------------|----------|-----------|--------|----------|
| Multinomial Naive Bayes + TF - IDF| 0.70 | 0.71 | 0.70 | 0.70 |
| Logistic Regression + TF - IDF | 0.74 | 0.71 | 0.74 | 0.72 |
| SVM + TF - IDF | 0.74 | 0.71 | 0.74 | 0.71 |

## 📄 Giấy phép
Đồ án học thuật – Không sử dụng vào mục đích thương mại.
© 2025 - Trường Đại học Công nghệ thông tin.
