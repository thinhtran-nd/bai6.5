# bai6.5
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.5: HỆ THỐNG QUẢN LÝ ĐẶT PHÒNG & DỊCH VỤ KARAOKE (KARAOKE MANAGEMENT SYSTEM)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:
<img width="1176" height="797" alt="GD" src="https://github.com/user-attachments/assets/d971b28c-a9e9-4162-8ce4-efa66461bacb" />


2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="1171" height="785" alt="CN1" src="https://github.com/user-attachments/assets/e6475adb-5a99-4f39-94c3-419bce019c22" />


3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="1170" height="803" alt="CN2" src="https://github.com/user-attachments/assets/5b6456db-6c0c-4aac-8c4b-e6e7ee00b3ca" />


4. Màn hình Báo cáo - Thống kê:
<img width="1181" height="793" alt="KQ" src="https://github.com/user-attachments/assets/d19f6a19-f4d0-4db6-b9d0-79acf352b98b" />



## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
