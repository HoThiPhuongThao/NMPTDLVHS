1. Giới thiệu

Dự án sử dụng Python và Pandas để xử lý, phân tích và biến đổi dữ liệu xét tuyển đại học từ file dulieuxettuyendaihoc.csv.
Mục tiêu là làm sạch dữ liệu, tạo biến mới và xác định kết quả xét tuyển.

2. Công nghệ sử dụng

Ngôn ngữ: Python 3

Thư viện: Pandas

Dữ liệu: CSV (input / output)

3. Cách hoạt động

Chương trình thực hiện các bước chính:

Đọc dữ liệu từ file CSV

Phân loại dữ liệu định tính và định lượng

Xử lý dữ liệu thiếu

Biến định tính: điền 0

Biến định lượng: điền giá trị trung bình

Tính điểm trung bình môn (TBM1, TBM2, TBM3)

Xếp loại học lực (Y, TB, K, G, XS)

Chuẩn hóa điểm TBM về thang 0–4

Xét tuyển đại học theo khối thi

Lưu dữ liệu đã xử lý ra file mới

4. Kết quả

Dữ liệu được làm sạch hoàn toàn

Tạo thêm các cột:

TBM1, TBM2, TBM3

XL1, XL2, XL3

US_TBM1, US_TBM2, US_TBM3

KQXT (kết quả xét tuyển)

Xuất file:

processed_dulieuxettuyendaihoc.csv

5. Giao diện web

Có thể mở rộng hiển thị kết quả bằng:

Flask (Python)

HTML/CSS

Chức năng: upload file, xem bảng kết quả, tải file CSV đã xử lý
