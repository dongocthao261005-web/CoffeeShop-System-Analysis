# Coffee Shop Management 

## Project Overview
Đồ án Phân tích và Thiết kế hệ thống thông tin cho mô hình Quán Cà Phê, nhằm số hóa và tối ưu hóa các quy trình: Gọi món, Thanh toán, Quản lý thành viên, Kiểm soát kho và Điều hành nhân sự.
- **Team Size:** 5 members.
- **My Role:** System Analyst (Phụ trách chính phân hệ Kiểm soát hàng hóa và Mô hình hóa Use Case nghiệp vụ).

## Full Documentation
Vui lòng xem chi tiết toàn bộ quy trình, đặc tả Use Case và các sơ đồ phân tích tại tài liệu PDF dưới đây:
**[Xem Báo Cáo Phân Tích Hệ Thống]([THPTTKHT_QLCAFE.pdf](https://github.com/user-attachments/files/29939763/THPTTKHT_QLCAFE.pdf))**

## Highlighted Analysis & Modeling

### 1. Business Use Case Diagram
Mô hình hóa các tương tác giữa các tác nhân bên ngoài (Khách hàng, Chủ quán, Nhà cung cấp) với các quy trình kinh doanh cốt lõi của quán.
> ![Business Use Case](<img width="765" height="668" alt="Use Case" src="https://github.com/user-attachments/assets/de72022a-fc05-48c4-9a88-c36f4c16aac0" />)

### 2. Inventory Management Process (Kiểm soát hàng hóa)
Phân tích chi tiết quy trình kiểm kê, đề xuất và phê duyệt nhập kho nguyên vật liệu từ nhà cung cấp.
- **Activity Diagram:** Đặc tả luồng công việc nghiệp vụ nhập kho.
> ![Activity Diagram](<img width="1463" height="964" alt="Activity Diagram" src="https://github.com/user-attachments/assets/df61a507-db67-4e2e-93c5-db3c5cacd5f5" />)
- **Sequence Diagram:** Mô phỏng sự trao đổi thông điệp giữa Nhân viên kho, Quản lý và Nhà cung cấp.
> ![Sequence Diagram](<img width="1106" height="767" alt="Sequence Diagram" src="https://github.com/user-attachments/assets/22dc198e-dd39-42aa-9c73-d20a861a4d03" />)

### 3. UI/UX Prototyping
Thiết kế nguyên mẫu giao diện cho chức năng Kiểm soát hàng hóa (Thống kê tồn kho và Phiếu nhập kho).
> ![UI Inventory](<img width="1277" height="719" alt="Giao diện thống kê nguyên liệu" src="https://github.com/user-attachments/assets/ddaa8b1c-cca0-44ba-ae22-642451867f7c" /> <img width="1276" height="720" alt="Giao diện phiếu nhập kho" src="https://github.com/user-attachments/assets/db0f174b-4ced-4539-8d92-152db1af01e3" /> <img width="1278" height="719" alt="Giao diện sau khi nhập kho" src="https://github.com/user-attachments/assets/3edabdb7-7e78-4072-8e18-f05f5a955dac" />)
