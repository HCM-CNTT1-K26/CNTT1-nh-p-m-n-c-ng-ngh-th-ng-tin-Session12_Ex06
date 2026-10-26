# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session12_Ex06
**Phần 1: Phân tích bảng Excel**

* **Bảng Xấu:** Trộn ô (Merge Cell) lung tung, gom nhiều thông tin vào một cột, chèn dòng/cột trống làm hỏng cấu trúc dữ liệu phẳng.
* **Bảng Đúng:** Mỗi cột là 1 Field, mỗi dòng là 1 Record, không dùng Merge Cell trong vùng dữ liệu, dễ dàng lọc và tra cứu.

**Phần 2: Học liệu Smart-Home**

* **Word (SRS):** Cấu trúc bằng Heading 1, 2, 3 (1. Giới thiệu, 2. Yêu cầu chức năng, 3. Yêu cầu phi chức năng).
* **Excel:** Công thức tính hoa hồng: `=VLOOKUP(A2, 'BangHoaHong'!$A$2:$B$50, 2, FALSE)`.
* **PowerPoint (10 Slide):** Dùng tối đa 10 slide, chừa khoảng trắng (White Space) để làm nổi bật thông điệp chính cho từng slide gọi vốn.

**Phần 3: Khắc phục lỗi VLOOKUP**

* **Nguyên nhân:** Khi kéo công thức, vùng dữ liệu bị trôi theo dòng.
* **Cách sửa:** Thêm dấu `$` để cố định vùng tra cứu (ví dụ: `$A$2:$B$50`) giúp công thức luôn quét đúng bảng nguồn.
