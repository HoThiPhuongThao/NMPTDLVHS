LAB 4: Phân tích dữ liệu Titanic & Dự đoán khả năng sống sót
1. Mục tiêu của LAB
LAB 4 tập trung vào việc phân tích dữ liệu hành khách trong thảm họa Titanic nhằm xác định các yếu tố có ảnh hưởng đến khả năng sống sót. Thông qua quá trình tiền xử lý, khai thác dữ liệu và trực quan hóa, bài lab giúp người học hiểu rõ cách chuẩn bị dữ liệu và rút ra tri thức phục vụ cho việc xây dựng mô hình dự đoán.

2. Công nghệ và công cụ sử dụng
Bài lab được thực hiện với các công nghệ và thư viện sau:
Python 3
Google Colab / Jupyter Notebook
Pandas: xử lý và làm sạch dữ liệu
NumPy: hỗ trợ tính toán
Matplotlib: vẽ biểu đồ
Seaborn: trực quan hóa dữ liệu nâng cao
Bộ dữ liệu Titanic (CSV)
3. Quy trình hoạt động của chương trình
Bước 1: Nạp dữ liệu
Đọc dữ liệu hành khách Titanic từ file CSV.
Kiểm tra cấu trúc và các thuộc tính trong tập dữ liệu.
Bước 2: Tiền xử lý dữ liệu (Data Cleansing)
Phát hiện và xử lý dữ liệu bị thiếu.
Điền giá trị tuổi còn thiếu bằng phương pháp phù hợp.
Chuẩn hóa dữ liệu giới tính về dạng số.
Xử lý thông tin Cabin.
Loại bỏ các cột không cần thiết cho quá trình phân tích.
Bước 3: Xây dựng đặc trưng (Feature Engineering)
Tạo thêm các biến mới nhằm tăng khả năng phân tích:
AgeGroup: phân nhóm độ tuổi
familySize: tổng số người trong gia đình
Alone: xác định hành khách đi một mình
namePrefix: trích xuất danh xưng từ tên
typeCabin: loại cabin
4. Khai thác dữ liệu và phân tích khám phá (EDA)
Sử dụng biểu đồ để phân tích mối quan hệ giữa khả năng sống sót và các yếu tố:
Giới tính
Hạng vé
Độ tuổi
Số người đi cùng
Giá vé
Cảng lên tàu
Các biểu đồ giúp quan sát xu hướng và so sánh tỷ lệ sống sót giữa các nhóm hành khách.
5. Kết quả và nhận xét
Từ quá trình phân tích dữ liệu, có thể rút ra các kết luận chính:
Nữ giới có khả năng sống sót cao hơn nam giới.
Hành khách hạng nhất có tỷ lệ sống sót cao nhất.
Trẻ em được ưu tiên trong quá trình cứu hộ.
Hành khách đi theo nhóm nhỏ có cơ hội sống cao hơn người đi một mình.
Giá vé cao thường gắn liền với khả năng sống sót lớn hơn.
Những đặc trưng này đóng vai trò quan trọng trong việc xây dựng mô hình dự đoán.
6. Mở rộng: Giao diện web hiển thị kết quả (nếu yêu cầu)
Trong trường hợp cần xây dựng giao diện trực quan:
Có thể sử dụng Flask hoặc Streamlit
Người dùng nhập thông tin hành khách:
Tuổi
Giới tính
Hạng vé
Giá vé
Số người đi cùng
Hệ thống trả về xác suất sống sót,ví dụ:
Passenger survival probability: 72%
7. Kết luận
LAB 4 giúp người học nắm vững quy trình phân tích dữ liệu thực tế, bao gồm:
Làm sạch dữ liệu
Xây dựng đặc trưng
Phân tích và trực quan hóa dữ liệu
Chuẩn bị dữ liệu cho các bài toán Machine Learning
