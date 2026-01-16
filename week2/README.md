## 1. Giới thiệu

Dự án sử dụng **Python** và thư viện **Pandas** để xử lý, phân tích và biến đổi dữ liệu xét tuyển đại học từ file `dulieuxettuyendaihoc.csv`.
Mục tiêu chính là làm sạch dữ liệu, tạo các biến mới, chuẩn hóa điểm số và xác định **kết quả xét tuyển đại học**.

---

## 2. Công nghệ sử dụng

* **Ngôn ngữ:** Python 3
* **Thư viện:** Pandas
* **Dữ liệu:** File CSV (đầu vào và đầu ra)

---

## 3. Cách hoạt động

Chương trình thực hiện các bước sau:

1. Đọc dữ liệu từ file CSV
2. Phân loại dữ liệu:

   * Biến định tính
   * Biến định lượng
3. Xử lý dữ liệu thiếu:

   * Biến định tính: điền giá trị `0`
   * Biến định lượng: điền giá trị **trung bình**
4. Tính điểm trung bình môn:

   * `TBM1`, `TBM2`, `TBM3`
5. Xếp loại học lực:

   * Y (Yếu), TB (Trung bình), K (Khá), G (Giỏi), XS (Xuất sắc)
6. Chuẩn hóa điểm trung bình môn về **thang điểm 0–4**
7. Xét tuyển đại học theo **khối thi**
8. Lưu dữ liệu đã xử lý ra file CSV mới

---

## 4. Kết quả

* Dữ liệu được làm sạch và xử lý đầy đủ
* Tạo thêm các cột mới:

  * `TBM1`, `TBM2`, `TBM3`
  * `XL1`, `XL2`, `XL3`
  * `US_TBM1`, `US_TBM2`, `US_TBM3`
  * `KQXT` (Kết quả xét tuyển)
* File kết quả đầu ra:

  * `processed_dulieuxettuyendaihoc.csv`

---

## 5. Giao diện web (mở rộng – tùy chọn)

Dự án có thể mở rộng bằng giao diện web để trực quan hóa kết quả:

* **Backend:** Flask (Python)
* **Frontend:** HTML / CSS

**Chức năng chính:**

* Upload file CSV
* Hiển thị bảng dữ liệu sau xử lý
* Tải về file CSV đã xử lý

---

## 6. Ghi chú

Dự án phục vụ mục đích **học tập và thực hành phân tích dữ liệu** với Python & Pandas.

