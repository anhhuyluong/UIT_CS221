# 📘 Phân tích cảm xúc các đánh giá sản phẩm trên sàn Amazon

## 🧠 Giới thiệu

Đồ án này thuộc môn **Xử lý ngôn ngữ tự nhiên - CS221**, nhằm mục tiêu xây dựng hệ thống phân tích cảm xúc (sentiment analysis) trên các đánh giá sản phẩm bằng tiếng Anh trên sàn thương mại điện tử Amazon. Dữ liệu bao gồm hàng nghìn phản hồi người dùng, và mô hình được huấn luyện để phân loại các đánh giá thành các nhãn cảm xúc như **tích cực**, **tiêu cực** hoặc **trung tính**.

## 📂 Cấu trúc thư mục

| Tên file                             | Mô tả                                                                 |
|-------------------------------------|----------------------------------------------------------------------|
| `Amazon_Final_Preprocessing.ipynb`  | Thực hiện tiền xử lý dữ liệu văn bản: làm sạch, loại bỏ stopword, chuẩn hóa. |
| `Amazon_Final_EDA_and_Statistics.ipynb` | Phân tích khám phá dữ liệu (EDA), thống kê số lượng nhãn và chiều dài văn bản. |
| `Amazon_Final_LR_TFIDF.ipynb`       | Huấn luyện mô hình Logistic Regression với TF-IDF.                  |
| `Amazon_Final_NB_TFIDF.ipynb`       | Huấn luyện mô hình Multinomial Naive Bayes với TF-IDF.             |
| `Amazon_Final_SVM_TFIDF.ipynb`      | Huấn luyện mô hình SVM (LinearSVC) với TF-IDF.                      |


