# Giới thiệu về Dữ liệu
Dự án này sử dụng dữ liệu từ nhiều nguồn khác nhau để phục vụ cho bài toán phân loại mưa. Dữ liệu bao gồm các tập tin CSV lớn chứa các thông tin về quan trắc mưa, khí tượng, và dữ liệu vệ tinh. Các tệp dữ liệu đã được chia thành nhiều thư mục để thuận tiện cho việc tổ chức và xử lý.

# Cấu trúc Dữ liệu
Dưới đây là cấu trúc thư mục của dữ liệu trong dự án:

INT3401-2-Midterm/
│
├── data/
│   ├── data_raw/            
│   │   ├── merged_04.csv    
│   │   ├── merged_10.csv    
│   ├── final_data/          
│   │   ├── filled_data_april.csv 
│   │   ├── filled_data_october.csv 
│   ├── train_all/           
│   │   ├── train_all.csv  
│   │   ├── test_all.csv   
│   ├── train_split/       
│   │   ├── 04/
│   │   │   ├── test_april.csv 
│   │   │   ├── train_april.csv 
│   │   ├── 10/
│   │   │   ├── test_october.csv 
│   │   │   ├── train_october.csv 

# Các nguồn dữ liệu chính
## Dữ liệu thô (raw data):
merged_04.csv, merged_10.csv: Các tệp dữ liệu được thu thập và gộp từ nhiều nguồn cho tháng 4 và tháng 10, đã được extract từ ảnh qua bảng bao gồm các thông tin về mưa, khí tượng, và các chỉ số khác.

## Dữ liệu đã xử lý (final data):

filled_data_april.csv, filled_data_october.csv: Dữ liệu đã được xử lý để lấp đầy các giá trị bị thiếu ít và loại bỏ các giá trị thiếu nhiều hoặc không hợp lệ

## Dữ liệu huấn luyện:

train_all.csv: Dữ liệu huấn luyện tổng thể cho bài toán phân loại mưa/không mưa.

train_split/04 và train_split/10: Dữ liệu huấn luyện chia theo tháng (tháng 4 và tháng 10), bao gồm các tệp dữ liệu huấn luyện và kiểm tra riêng biệt cho mỗi tháng.
