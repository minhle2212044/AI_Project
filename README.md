# Một số project AI nhỏ

Repo này tổng hợp một số dự án nhỏ về **Trí tuệ nhân tạo (AI)** và **Xử lý ngôn ngữ tự nhiên (NLP)** đã thực hiện trong quá trình học tập và nghiên cứu.

## 📂 Danh sách dự án

### Dự đoán trầm cảm sinh viên
- Mục tiêu: Dự đoán nguy cơ trầm cảm của sinh viên dựa trên dữ liệu khảo sát.  
- Thuật toán: Logistic Regression, Random Forest, SVM  
[Xem chi tiết](./Student-Depression-Prediction)

---

### Dự án Natural Language Processing

#### 1. Phân loại email spam
- **Mục tiêu:** Phân loại email thành **spam** hoặc **không spam**.  
- **Thuật toán:** Naive Bayes (MultinomialNB, GaussianNB)
- **Kết quả:** Độ chính xác ~90%  
👉 [Xem chi tiết](./NLP/Spam-Email-Classification)

#### 2. Dự đoán từ tiếp theo
- **Mục tiêu:** Xây dựng mô hình ngôn ngữ dựa trên N-gram để dự đoán từ tiếp theo.  
- **Phương pháp:** Unigram, Bigram, Trigram, Laplace smoothing  
- **Đánh giá:** So sánh bằng Perplexity  
👉 [Xem chi tiết](./NLP/Next-Word-Prediction)

#### 3. Phân tích cảm xúc (Sentiment Analysis)
- **Mục tiêu:** Phân loại cảm xúc trong đánh giá sản phẩm Amazon (tích cực / tiêu cực hoặc theo thang điểm 1–5).  
- **Dữ liệu:** [Amazon Product Review — Digital Music 5](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Digital_Music_5.json.gz)  
- **Bước xử lý:**  
  - Tiền xử lý văn bản (xóa ký tự đặc biệt, chuẩn hóa chữ thường, loại bỏ stop words)  
  - Vector hóa văn bản bằng TF-IDF  
  - Huấn luyện mô hình: Logistic Regression, Multinomial Naive Bayes  
  - Đánh giá: Accuracy, Precision, Recall, F1-score, Confusion Matrix  
- **Công nghệ:** Python, Pandas, scikit-learn, Matplotlib, Seaborn  
👉 [Xem chi tiết](./NLP/Sentiment-Analysis)
---

## 🛠 Công nghệ sử dụng
- Python 3.1+
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK
- Jupyter Notebook
