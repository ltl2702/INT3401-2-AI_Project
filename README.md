# Phân Loại mưa và không mưa theo giờ bằng Machine Learning

**Môn học:** Trí tuệ nhân tạo – INT3401E_2    
**Nhóm Thực Hiện:**
- Lê Hoàng Lan – 22028013
- Lương Thị Linh – 22028202
- Vũ Tú Quỳnh – 22028253
- Nguyễn Thị Thu Trang – 22028254

---

##  Mô Tả Đề Tài

Project này trình bày quá trình thực hiện bài tập giữa kỳ môn Trí tuệ nhân tạo – INT3401E_2, với mục tiêu áp dụng các phương pháp học máy vào bài toán **phân loại mưa và không mưa theo giờ** tại một vài tỉnh ở Việt Nam.

---

##  Dữ Liệu Sử Dụng

Bộ dữ liệu tổng hợp từ nhiều nguồn đáng tin cậy, bao gồm:

-  **Ảnh vệ tinh Himawari-8**: Cung cấp thông tin hình ảnh liên quan đến mây, nhiệt độ bề mặt, độ sáng,...
-  **Dữ liệu khí tượng ERA5**: Bao gồm các thông số khí tượng như áp suất, độ ẩm, nhiệt độ không khí,...
-  **Dữ liệu mưa/không mưa thực tế**: Được thu thập từ các trạm đo tự động AWS, đóng vai trò là nhãn (label) để huấn luyện mô hình.

---

##  Mục Tiêu

- Xây dựng mô hình học máy có khả năng **phân loại chính xác** từng giờ có mưa hay không mưa tại khu vực nghiên cứu.
- Đánh giá hiệu năng mô hình qua các chỉ số như độ chính xác, recall, precision, F1-score.

---

##  Công Cụ & Kỹ Thuật

- **Ngôn ngữ lập trình**: Python
- **Thư viện chính**:
  - `scikit-learn`: Xây dựng và đánh giá mô hình
  - `pandas`, `numpy`: Xử lý dữ liệu
  - `matplotlib`, `seaborn`: Trực quan hóa dữ liệu
- **Phương pháp học máy**: 
  - CatBoost
  - Random Forest
  - XGBoost
  - PNN, SCG
- **Tiền xử lý ảnh và dữ liệu thời gian**: Chuẩn hóa, xử lý thiếu dữ liệu, cân bằng dữ liệu, mã hóa nhãn

---

##  Kết Quả Mong Đợi

- Độ chính xác cao trong việc phân loại mưa/không mưa theo giờ
- Bản đồ mưa và không mưa so sánh với ground truth
- Kiến thức thực tiễn về xử lý dữ liệu thời tiết và ảnh vệ tinh

---
