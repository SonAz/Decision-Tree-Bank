# 📊 Decision Tree Classifier on Bank Marketing Dataset

## 📁 Giới thiệu

File notebook `Decision_Tree_Bank.ipynb` là một dự án phân tích và xây dựng mô hình học máy sử dụng **Decision Tree Classifier** trên tập dữ liệu tiếp thị ngân hàng (Bank Marketing Dataset). Dữ liệu được lấy từ một chiến dịch tiếp thị qua điện thoại của một ngân hàng Bồ Đào Nha nhằm quảng bá sản phẩm tiền gửi có kỳ hạn (term deposit).

## 🎯 Mục đích

- Tiền xử lý dữ liệu: xử lý dữ liệu thiếu, mã hóa biến phân loại (categorical encoding), và chuẩn hóa dữ liệu.
- Khám phá dữ liệu: sử dụng biểu đồ và thống kê mô tả để hiểu rõ hơn về phân bố và mối quan hệ giữa các thuộc tính.
- Xây dựng mô hình Decision Tree để phân loại khách hàng có khả năng đăng ký tiền gửi có kỳ hạn hay không.
- Đánh giá mô hình qua các chỉ số như Accuracy, Precision, Recall, F1-Score và biểu đồ Confusion Matrix.

## 🧠 Nội dung chính

- Nạp dữ liệu và xử lý dữ liệu đầu vào
- Phân tích dữ liệu bằng trực quan hóa (biểu đồ histogram, countplot,…)
- Mã hóa dữ liệu phân loại bằng Label Encoding và One-Hot Encoding
- Tách tập huấn luyện và kiểm tra (train/test split)
- Huấn luyện mô hình cây quyết định (Decision Tree)
- Hiển thị và đánh giá mô hình

## ✅ Kết luận

- Mô hình cây quyết định là một phương pháp dễ hiểu và trực quan, phù hợp để phân tích các yếu tố ảnh hưởng đến quyết định của khách hàng.
- Sau khi huấn luyện, mô hình đạt độ chính xác hợp lý và cho phép nhận biết các thuộc tính quan trọng nhất như "contact", "duration", "month", v.v.
- Mô hình có thể được cải thiện bằng cách sử dụng kỹ thuật pruning, điều chỉnh hyperparameter, hoặc thử nghiệm các mô hình khác như Random Forest hoặc Gradient Boosting.

## 📂 Yêu cầu

- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

## 🚀 Cách sử dụng

1. Clone repository hoặc tải về notebook.
2. Mở bằng Jupyter Notebook hoặc Google Colab.
3. Chạy từng cell từ trên xuống dưới để xem kết quả.

## 📌 Tác giả

Notebook này được thực hiện với mục tiêu học tập và minh họa kỹ thuật cây quyết định trong phân tích dữ liệu thực tế.

---

