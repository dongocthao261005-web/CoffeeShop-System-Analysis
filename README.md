# Coffee Shop Management 

## Project Overview
Đồ án Phân tích và Thiết kế hệ thống thông tin cho mô hình Quán Cà Phê, nhằm số hóa và tối ưu hóa các quy trình: Gọi món, Thanh toán, Quản lý thành viên, Kiểm soát kho và Điều hành nhân sự.
- **Team Size:** 5 members.
- **My Role:** System Analyst (Phụ trách chính phân hệ Kiểm soát hàng hóa và Mô hình hóa Use Case nghiệp vụ).

## Full Documentation
Vui lòng xem chi tiết toàn bộ quy trình, đặc tả Use Case và các sơ đồ phân tích tại tài liệu PDF dưới đây:
[THPTTKHT_QLCAFE.pdf](https://github.com/user-attachments/files/29939899/THPTTKHT_QLCAFE.pdf)


## Highlighted Analysis & Modeling

### 1. Business Use Case Diagram
Mô hình hóa các tương tác giữa các tác nhân bên ngoài (Khách hàng, Chủ quán, Nhà cung cấp) với các quy trình kinh doanh cốt lõi của quán.
<img width="765" height="668" alt="UseCase" src="https://github.com/user-attachments/assets/ea50659e-f3cc-4ffd-b4b8-38f6035ae818" />


### 2. Inventory Management Process (Kiểm soát hàng hóa)
Phân tích chi tiết quy trình kiểm kê, đề xuất và phê duyệt nhập kho nguyên vật liệu từ nhà cung cấp.
- **Activity Diagram:** Đặc tả luồng công việc nghiệp vụ nhập kho.
<img width="1463" height="964" alt="ActivityDiagram" src="https://github.com/user-attachments/assets/dd8da708-55c6-4120-a801-b82fd30743ba" />

- **Sequence Diagram:** Mô phỏng sự trao đổi thông điệp giữa Nhân viên kho, Quản lý và Nhà cung cấp.
<img width="1106" height="767" alt="SequenceDiagram" src="https://github.com/user-attachments/assets/5a263e2b-8e88-419b-9185-66cd90dff2be" />

- **Communication Diagram:** Thể hiện cấu trúc liên kết và luồng trao đổi thông tin giữa các đối tượng (Nhân viên kho, Quản lý, Nhà cung cấp) trong quy trình kiểm soát hàng hóa.
<img width="1078" height="613" alt="CommunicationDiagram" src="https://github.com/user-attachments/assets/7032a90d-4500-4aeb-8789-f22ca5d2ac6a" />


### 3. UI/UX Prototyping
Thiết kế nguyên mẫu giao diện cho chức năng Kiểm soát hàng hóa (Thống kê tồn kho và Phiếu nhập kho).
<img width="1277" height="719" alt="Giao diện thống kê nguyên liệu" src="https://github.com/user-attachments/assets/ddaa8b1c-cca0-44ba-ae22-642451867f7c" /> <img width="1276" height="720" alt="Giao diện phiếu nhập kho" src="https://github.com/user-attachments/assets/db0f174b-4ced-4539-8d92-152db1af01e3" /> <img width="1278" height="719" alt="Giao diện sau khi nhập kho" src="https://github.com/user-attachments/assets/3edabdb7-7e78-4072-8e18-f05f5a955dac" />
