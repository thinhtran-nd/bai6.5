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
<img width="1920" height="1080" alt="GD" src="https://github.com/user-attachments/assets/689a7ad1-4fd4-44f5-b633-0b78a42278ca" />

2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="1920" height="1080" alt="CN1" src="https://github.com/user-attachments/assets/706f3067-f278-4b82-8e3b-0f172de8980f" />

3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="1920" height="1080" alt="CN2" src="https://github.com/user-attachments/assets/bdb30cc7-44ed-4a4e-8804-a43534602004" />

4. Màn hình Báo cáo - Thống kê:
<img width="1920" height="1080" alt="KQ" src="https://github.com/user-attachments/assets/190caea9-993e-4452-b761-2d889b43ff19" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
