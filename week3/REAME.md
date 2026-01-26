1. Giới thiệu

Bài lab này nhằm mục đích thực hành các kỹ năng:
- Đọc và xử lý dữ liệu / xây dựng ứng dụng / lập trình server (tùy bài)
- Áp dụng các thư viện và công nghệ đã học
- Xuất kết quả phục vụ cho phân tích / hiển thị trên web

File chính:
- Notebook / Script: `HoTen_LabX.ipynb` (hoặc file .py, .js)
- Dữ liệu đầu vào: `...`
- Kết quả đầu ra: `...`

---

## 2. Công nghệ sử dụng

Trong bài lab này, các công nghệ và thư viện được sử dụng gồm:

- Ngôn ngữ:  
  - Python 3.x (hoặc JavaScript / NodeJS / …)

- Thư viện chính:
  - pandas – xử lý dữ liệu dạng bảng  
  - numpy – tính toán số học  
  - seaborn / matplotlib – trực quan hóa dữ liệu  
  - flask / express (nếu có web)

- Môi trường:
  - Jupyter Notebook  
  - VS Code  

---

## 3. Cách hoạt động của chương trình

Quy trình xử lý của chương trình gồm các bước chính:

### Bước 1 – Đọc dữ liệu đầu vào

- Đọc file dữ liệu từ định dạng CSV / JSON / Database
- Gán tên cột và kiểm tra dữ liệu ban đầu

### Bước 2 – Tiền xử lý dữ liệu

- Xử lý giá trị thiếu (missing values)  
- Xóa các bản ghi trùng lặp  
- Chuẩn hóa định dạng dữ liệu (ví dụ: tuổi, cân nặng, ngày tháng)

### Bước 3 – Biến đổi và phân tích dữ liệu

- Tách cột, gộp cột  
- Chuyển đổi dữ liệu từ dạng wide sang long (nếu có)  
- Tính toán các giá trị thống kê cần thiết  

### Bước 4 – Xuất kết quả

- Lưu dữ liệu đã xử lý ra file:
  - `result.csv` / `*_clean.csv`
- In kết quả ra màn hình hoặc vẽ biểu đồ

---

## 4. Kết quả đạt được

Sau khi chạy chương trình, thu được:

- File dữ liệu sạch:  
  - `ten_file_clean.csv`

- Dữ liệu đã được:
  - Chuẩn hóa định dạng  
  - Loại bỏ dữ liệu lỗi, thiếu, trùng  
  - Sẵn sàng cho các bước phân tích tiếp theo  

Ví dụ một số dòng kết quả:

| ID | Age | Value | Result |
|----|-----|-------|--------|
| 1  | 25  |  72   |  OK    |
| 2  | 30  |  85   |  OK    |

---

## 5. Giao diện web xuất kết quả (nếu có)

Nếu bài lab có phần hiển thị kết quả trên web:

- Công nghệ:
  - Flask / Express / React / HTML-CSS-JS

- Chức năng giao diện:
  - Hiển thị bảng dữ liệu kết quả  
  - Hiển thị biểu đồ  
  - Cho phép tải file kết quả  

Mô tả giao diện:
- Trang chính hiển thị danh sách kết quả xử lý  
- Người dùng có thể xem chi tiết từng bản ghi  

(Hình ảnh giao diện có thể chèn thêm vào đây nếu cần)
