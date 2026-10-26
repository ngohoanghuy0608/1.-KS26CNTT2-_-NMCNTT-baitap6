# Phần 1. Phân tích bảng Excel

Bảng Excel xấu

Bảng Excel đúng

Gộp ô (Merge Cells)

Không gộp ô dữ liệu

Nhiều thông tin trong một ô

Mỗi ô chứa một giá trị

Thiếu tên cột

Có tiêu đề rõ ràng

Một dòng chứa nhiều nhà đất

Mỗi dòng là một bản ghi nhà đất

Dữ liệu lẫn lộn, khó lọc

Mỗi cột là một trường dữ liệu

Khó tra cứu bằng VLOOKUP

Có mã định danh để tra cứu

Quy tắc vàng: Một dòng là một bản ghi (Record), một cột là một trường (Field), không Merge Cell trong vùng dữ liệu.

# Phần 2. Triển khai học liệu Smart-Home

## A. Nội dung báo cáo Word — SRS

Bạn tạo file Word, nhập nội dung bên dưới và áp dụng Heading 1, Heading 2, Heading 3 cho các tiêu đề tương ứng.

# TÀI LIỆU ĐẶC TẢ YÊU CẦU PHẦN MỀM (SRS)

## DỰ ÁN SMART-HOME

**Phiên bản:** 1.0  
**Mục đích:** Xây dựng nền tảng quản lý và cho thuê nhà đất trực tuyến.

# 1. Tổng quan dự án

## 1.1. Mục đích

Smart-Home giúp người dùng tìm kiếm, đăng tin và quản lý thông tin nhà đất. Hệ thống hỗ trợ tính giá thuê, chiết khấu và hoa hồng môi giới.

## 1.2. Đối tượng sử dụng

-   **Khách thuê:** Tìm kiếm và xem thông tin nhà đất.
    
-   **Chủ nhà:** Đăng tin và quản lý bất động sản.
    
-   **Môi giới:** Tư vấn, kết nối khách hàng và nhận hoa hồng.
    
-   **Quản trị viên:** Quản lý tài khoản, tin đăng và dữ liệu hệ thống.
    

# 2. Yêu cầu chức năng

## 2.1. Quản lý tài khoản

-   Người dùng có thể đăng ký, đăng nhập và đăng xuất.
    
-   Người dùng có thể cập nhật thông tin cá nhân.
    
-   Quản trị viên có quyền khóa tài khoản vi phạm.
    

## 2.2. Quản lý nhà đất

-   Chủ nhà có thể thêm, sửa và xóa tin đăng.
    
-   Hệ thống lưu mã bất động sản, địa chỉ, diện tích và giá thuê.
    
-   Người dùng có thể tìm kiếm theo khu vực, giá và diện tích.
    

## 2.3. Quản lý giá thuê và hoa hồng

-   Hệ thống tính giá thuê sau chiết khấu.
    
-   Hệ thống tra cứu tỷ lệ hoa hồng theo loại giao dịch.
    
-   Hệ thống hiển thị số tiền hoa hồng dự kiến.
    

# 3. Yêu cầu phi chức năng

## 3.1. Bảo mật

-   Mật khẩu phải được lưu dưới dạng băm an toàn.
    
-   Chỉ người có quyền mới được sửa hoặc xóa dữ liệu.
    
-   Dữ liệu cá nhân phải được bảo vệ và không được chia sẻ trái phép.
    

## 3.2. Hiệu năng

-   Kết quả tìm kiếm cần được trả về nhanh trong điều kiện tải thông thường.
    
-   Hệ thống cần hỗ trợ nhiều người dùng truy cập đồng thời.
    

## 3.3. Độ tin cậy

-   Dữ liệu phải được sao lưu định kỳ.
    
-   Hệ thống cần có phương án khôi phục khi xảy ra sự cố.
    

# 4. Quy trình hoạt động

## 4.1. Quy trình tìm nhà

1.  Khách hàng nhập tiêu chí tìm kiếm.
    
2.  Hệ thống lọc danh sách bất động sản.
    
3.  Khách hàng xem chi tiết và liên hệ chủ nhà hoặc môi giới.
    

## 4.2. Quy trình đăng tin

1.  Chủ nhà nhập thông tin bất động sản.
    
2.  Hệ thống kiểm tra dữ liệu bắt buộc.
    
3.  Tin đăng được lưu và chuyển sang trạng thái phù hợp.
    

# 5. Thiết kế dữ liệu

## 5.1. Thông tin bất động sản

Mỗi bất động sản có mã duy nhất, địa chỉ, loại hình, giá thuê, diện tích và trạng thái.

## 5.2. Thông tin giao dịch

Mỗi giao dịch có mã giao dịch, mã bất động sản, giá thuê, tỷ lệ chiết khấu và tỷ lệ hoa hồng.

# 6. Kiểm thử và nghiệm thu

## 6.1. Kiểm thử chức năng

-   Kiểm tra đăng nhập với thông tin hợp lệ và không hợp lệ.
    
-   Kiểm tra tìm kiếm bất động sản theo giá.
    
-   Kiểm tra tính giá thuê sau chiết khấu.
    
-   Kiểm tra tra cứu tỷ lệ hoa hồng bằng Excel.
    

## 6.2. Tiêu chí nghiệm thu

Hệ thống được chấp nhận khi các chức năng chính hoạt động đúng, dữ liệu được lưu chính xác và quyền truy cập được kiểm soát.

# 7. Kết luận

Smart-Home hướng tới việc đơn giản hóa quy trình tìm kiếm, quản lý và cho thuê nhà đất. Dự án cần tiếp tục được phát triển, kiểm thử và hoàn thiện bảo mật trước khi triển khai thực tế.
