# Giới thiệu
Họ và tên: Sơn Ngọc Tân

Lớp: DA22TTB

MSSV: 110122154

Giáo viên hướng dẫn: Nguyễn Nhứt Lam
# Tên đề tài 
-	Xây dựng website giới thiệu cá nhân ( Portfolio ) sử dụng React.js
# Mô tả 
Xây dựng website giới thiệu thông tin cá nhân (Portfolio) sử dụng React.js, bao gồm thông tin cá nhân, quá trình đào tạo, kỹ năng chuyên môn....
# Phương pháp thực hiện 
Bước 1 : Xác định cấu trúc , chức năng , giao diện . Thiết kế giao diện và chọn màu sắc , phông chữ và bố cục. cài đặt môi trường phát triển và tạo cấu trúc dự án .Xây dựng các component cơ bản . 
Bước 2 : Xậy dựng nội dung và chức năng cơ bản . xây dựng phần giới thiệu và kỹ năng, thêm nội dung vào thông tin cá nhân . Xây dựng phần quá trình và đào tạo dự án . 
Bước 3: thiết lế hiệu ứng cho website . Thêm CSS và chỉnh sửa giao diện.
 Bước 4 : tối ưu hoá và hoàn thành .
 Kiểm tra hiệu suất website và tối ưu hình ảnh , mã nguồn để tăng tốc độ tải trang. Tạo chức năng liên hệ và kiểm trả cuối cùng. Kiểm tra trên các trình duyệt và thiết bị khác nhau
 # kết quả đạt được 
 + Tạo giao diện hiện đại, tối ưu hiệu suất và khả năng tương tác động.
+ Đảm bảo website tối ưu với SEO cơ bản và tương thích với các thiết bị di động.
+ có đầy đủ thông tin cá nhân gồm phần giới thiệu , mục tiêu, kế hoạch , hoạt động và thành tích
  # Mục tiêu
  Đề tài “Xây dựng website giới thiệu cá nhân (Portfolio) sử dụng React.js” tạo ra một nền tảng trực tiếp hiện đại và tối ưu, giúp cá nhân thể hiện bản thân một cách chuyên nghiệp. Sản phẩm tập trung vào việc tạo giao diện người dùng hiện đại , tối ưu hóa hiệu suất và đảm báo khả năng tương tác động. Website cần được tối ưu hóa cho SEO cơ bản và đảm bảo tương thích với các thiết bị di động.
  # ý nghĩa
  Xây dựng website cá nhân rất quan trọng trong lĩnh vực công nghệ thông tin, giúp tăng cường khả năng giới thiệu cá nhân , cạnh tranh, tương tác , quản lý thông tin, tương thích, bảo mật, và mở rộng
  # lợi ích
   + Hiệu suất cao
 React.js sử dụng Virtual DOM để giảm thiểu số lần cập nhật DOM thực tế, giúp cải thiện hiệu suất của ứng dụng khi có sự thay đổi dữ liệu. Điều này rất quan trọng đối với các trang web cần sự mượt mà và phản hồi nhanh chóng.

	+ Tái sử dụng thành phần 
React cho phép phát triển dựa trên thành phần, điều này giúp các nhà phát triển có thể tái sử dụng code hiệu quả, làm giảm thời gian phát triển và tăng khả năng bảo trì của ứng dụng.
Cộng đồng lớn và hỗ trợ mạnh mẽ và có một cộng đồng lớn các nhà phát triển, cung cấp một lượng lớn tài nguyên học tập, thư viện bổ sung, và các công cụ phát triển.

React.js hỗ trợ render phía máy chủ (Server-Side Rendering - SSR), giúp cải thiện khả năng SEO và tăng khả năng hiển thị trên các công cụ tìm kiếm.
# hiện trạng và xây dựng hệ thống
-	Sau khi em thực hiện khảo sát qua website giới thiệu cá nhân em đã nắm bắt được các thông tin :
-	Thông tin giới thiệu bản thân không thể thiếu trong mỗi Portfolio. Những nội dung nhất định phải có trong phần giới thiệu gồm: 
•	Tên tuổi.
•	Hình ảnh chân dung.
•	Chuyên môn, bằng cấp và lĩnh vực hoạt động.
•	Kinh nghiệm làm việc.
•	Mục tiêu nghề nghiệp dài hạn và ngắn hạn.
•	Tóm tắt quá trình làm việc ở đơn vị cũ.
•	Các giải thưởng từng đạt được.
•	Địa chỉ liên lạc gồm số điện thoại, email cá nhân, địa chỉ nơi ở.
# cơ sở lý thuyết
Cơ sở lý thuyết
+	Responsive Web Design
Lý thuyết về thiết kế web đáp ứng, sử dụng các kỹ thuật như CSS Media Queries và Flexbox/Grid để đảm bảo website hiển thị tốt trên các thiết bị có kích thước màn hình khác nhau.
+	Kiến trúc component của React.js
Lý thuyết về component là nền tảng của React.js, cho phép xây dựng giao diện người dùng từ các component nhỏ, độc lập và tái sử dụng. Việc sử dụng component giúp tăng tính tổ chức, dễ bảo trì và phát triển ứng dụng.
+	Virtual DOM
React.js sử dụng Virtual DOM để tối ưu hóa hiệu suất render. Thay vì cập nhật trực tiếp vào DOM thật, React.js sẽ so sánh Virtual DOM với DOM thật và chỉ cập nhật những thay đổi cần thiết, giúp giảm thiểu thao tác trên DOM và tăng tốc độ render.
+	JSX
JSX là một cú pháp mở rộng của JavaScript cho phép viết HTML trong JavaScript. Nó giúp đơn giản hóa việc tạo và quản lý cấu trúc HTML trong component React.
+	Quản lý state và props
State và props là hai khái niệm quan trọng trong React.js, giúp quản lý dữ liệu và luồng thông tin giữa các component.
+	React Router
Thư viện giúp quản lý định tuyến trong ứng dụng React, cho phép tạo các trang và điều hướng giữa chúng.
# cài đặt
node.js
React.js
# liên hệ
<div>SĐT : 0866996041</div>
Mail : 110122154@st.tvu.edu.vn


