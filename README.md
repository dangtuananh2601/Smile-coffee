# ☕ Smile Coffee

Smile Coffee là website bán cà phê, trà sữa, nước ép, bánh ngọt và các sản phẩm đồ uống trực tuyến.  
Hệ thống hỗ trợ khách hàng xem thực đơn, tìm kiếm sản phẩm, đặt hàng, thanh toán, theo dõi đơn hàng và đánh giá sản phẩm.

Dự án được xây dựng với Spring Boot, Thymeleaf, PHP REST API và SQL Server.


## 🛠️ Công nghệ sử dụng

### Frontend

- Java Spring Boot
- Thymeleaf
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Backend

- PHP
- REST API
- PHPMailer
- SQL Server
- PDO SQL Server

### Công cụ phát triển

- Visual Studio Code
- SQL Server Management Studio
- Git và GitHub
- XAMPP/PHP Server
- Maven

---

# 📸 Giao diện và chức năng

## 1. Giao diện trang chủ

Trang chủ là giao diện đầu tiên mà khách hàng nhìn thấy khi truy cập website.

### Chức năng chính

- Hiển thị banner giới thiệu thương hiệu Smile Coffee.
- Hiển thị các sản phẩm nổi bật.
- Hiển thị món ăn và đồ uống được đề xuất.
- Hiển thị chương trình khuyến mãi đang áp dụng.
- Cho phép khách hàng nhận voucher giảm giá.
- Truy cập nhanh đến trang thực đơn.
- Truy cập trang giới thiệu cửa hàng.
- Truy cập giỏ hàng.
- Truy cập trạng thái đơn hàng.
- Truy cập thông tin tài khoản.
- Hỗ trợ thay đổi ngôn ngữ giữa tiếng Việt và tiếng Anh.
- Hiển thị chatbot hỗ trợ khách hàng.

---

## 2. Giao diện thực đơn sản phẩm

Trang thực đơn hiển thị danh sách các sản phẩm hiện đang được bán tại Smile Coffee.

### Chức năng chính

- Hiển thị toàn bộ sản phẩm.
- Hiển thị tên sản phẩm.
- Hiển thị hình ảnh sản phẩm.
- Hiển thị giá bán.
- Hiển thị danh mục của sản phẩm.
- Hiển thị điểm đánh giá trung bình.
- Hiển thị số lượng sản phẩm đã bán.
- Lọc sản phẩm theo danh mục.
- Tìm kiếm sản phẩm theo tên món.
- Điều chỉnh số lượng sản phẩm.
- Thêm sản phẩm vào giỏ hàng.
- Truy cập trang chi tiết sản phẩm.

### Một số danh mục sản phẩm

- Cà phê.
- Trà sữa.
- Nước ép.
- Sinh tố.
- Bánh ngọt.
- Topping.

---

## 3. Giao diện chi tiết sản phẩm

Trang chi tiết cung cấp đầy đủ thông tin về món ăn hoặc đồ uống mà khách hàng lựa chọn.

### Chức năng chính

- Hiển thị hình ảnh sản phẩm.
- Hiển thị tên sản phẩm.
- Hiển thị giá bán.
- Hiển thị mô tả sản phẩm.
- Hiển thị thành phần của sản phẩm.
- Hiển thị danh mục sản phẩm.
- Hiển thị số lượng đã bán.
- Hiển thị điểm đánh giá trung bình.
- Hiển thị trạng thái còn bán hoặc tạm ngừng bán.
- Điều chỉnh số lượng sản phẩm muốn mua.
- Thêm sản phẩm vào giỏ hàng.
- Xem các đánh giá của khách hàng đã mua sản phẩm.
- Quay lại trang thực đơn.

---

## 4. Giao diện đăng nhập

Trang đăng nhập cho phép người dùng truy cập vào tài khoản của mình.

### Chức năng chính

- Đăng nhập bằng tên tài khoản và mật khẩu.
- Phân quyền tài khoản khách hàng.
- Phân quyền tài khoản quản trị viên.
- Phân quyền tài khoản nhân viên giao hàng.
- Hiển thị thông báo khi thông tin đăng nhập không đúng.
- Chuyển đến trang đăng ký tài khoản.
- Chuyển đến chức năng quên mật khẩu.
- Duy trì thông tin đăng nhập bằng session.
- Điều hướng người dùng đến giao diện phù hợp với vai trò.

---

## 5. Giao diện đăng ký

Trang đăng ký cho phép khách hàng tạo tài khoản mới để sử dụng các chức năng mua hàng.

### Chức năng chính

- Nhập tên đăng nhập.
- Nhập mật khẩu.
- Nhập họ và tên.
- Nhập email.
- Nhập số điện thoại.
- Nhập địa chỉ giao hàng.
- Kiểm tra thông tin bắt buộc.
- Kiểm tra tên đăng nhập đã tồn tại.
- Kiểm tra email hoặc số điện thoại đã được sử dụng.
- Tạo tài khoản khách hàng mới.
- Chuyển đến trang đăng nhập sau khi đăng ký thành công.

---

## 6. Giao diện quên mật khẩu

Chức năng quên mật khẩu hỗ trợ người dùng lấy lại quyền truy cập tài khoản qua email.

### Chức năng chính

- Nhập địa chỉ email đã đăng ký.
- Gửi mã OTP qua Gmail SMTP.
- Xác nhận mã OTP.
- Kiểm tra thời hạn sử dụng của mã.
- Thiết lập mật khẩu mới.
- Hiển thị thông báo khi mã OTP không chính xác.
- Quay lại trang đăng nhập sau khi đổi mật khẩu thành công.

---

## 7. Giao diện giỏ hàng

Trang giỏ hàng lưu trữ các sản phẩm mà khách hàng đã lựa chọn trước khi đặt hàng.

### Chức năng chính

- Hiển thị danh sách sản phẩm trong giỏ hàng.
- Hiển thị hình ảnh và tên sản phẩm.
- Hiển thị đơn giá của từng sản phẩm.
- Hiển thị số lượng sản phẩm.
- Tính thành tiền của từng sản phẩm.
- Tăng số lượng sản phẩm.
- Giảm số lượng sản phẩm.
- Cập nhật số lượng sản phẩm.
- Xóa sản phẩm khỏi giỏ hàng.
- Tính tổng giá trị giỏ hàng.
- Tiếp tục xem thực đơn.
- Chuyển đến trang xác nhận đơn hàng.
- Yêu cầu đăng nhập trước khi sử dụng giỏ hàng.

---

## 8. Giao diện xác nhận và thanh toán đơn hàng

Trang thanh toán cho phép khách hàng kiểm tra thông tin và lựa chọn phương thức thanh toán trước khi đặt hàng.

### Chức năng chính

- Hiển thị họ tên khách hàng.
- Hiển thị số điện thoại.
- Hiển thị địa chỉ giao hàng.
- Hiển thị danh sách món đã đặt.
- Hiển thị số lượng và giá của từng món.
- Tính tổng tiền sản phẩm.
- Tính phí giao hàng.
- Hiển thị voucher khách hàng đã nhận.
- Áp dụng voucher giảm giá.
- Tính số tiền được giảm.
- Tính tổng số tiền cần thanh toán.
- Thanh toán bằng tiền mặt khi nhận hàng.
- Thanh toán bằng ví hoặc mã QR.
- Kiểm tra số dư ví của khách hàng.
- Tạo đơn hàng mới.
- Xóa giỏ hàng sau khi đặt hàng thành công.

---

## 9. Giao diện thanh toán QR

Trang thanh toán QR được hiển thị khi khách hàng lựa chọn thanh toán trực tuyến.

### Chức năng chính

- Tạo mã QR thanh toán.
- Hiển thị số tiền cần thanh toán.
- Hiển thị nội dung chuyển khoản.
- Hỗ trợ thanh toán qua tài khoản ngân hàng.
- Xác nhận trạng thái thanh toán.
- Điều hướng đến trang đặt hàng thành công.
- Cập nhật trạng thái đã thanh toán cho đơn hàng.

---

## 10. Giao diện đặt hàng thành công

Trang này thông báo đơn hàng đã được hệ thống tiếp nhận thành công.

### Chức năng chính

- Hiển thị thông báo đặt hàng thành công.
- Hiển thị mã đơn hàng.
- Hiển thị tổng số tiền của đơn hàng.
- Hiển thị phương thức thanh toán.
- Chuyển đến trang theo dõi đơn hàng.
- Quay lại trang chủ.
- Tiếp tục mua sắm.

---

## 11. Giao diện trạng thái và lịch sử đơn hàng

Trang trạng thái đơn hàng giúp khách hàng theo dõi toàn bộ quá trình xử lý và giao hàng.

### Chức năng chính

- Hiển thị danh sách đơn hàng đã đặt.
- Hiển thị mã đơn hàng.
- Hiển thị ngày đặt hàng.
- Hiển thị danh sách món trong đơn.
- Hiển thị tổng giá trị đơn hàng.
- Hiển thị phương thức thanh toán.
- Hiển thị trạng thái thanh toán.
- Hiển thị trạng thái giao hàng.
- Hiển thị thông tin nhân viên giao hàng.
- Theo dõi các trạng thái:
  - Chờ xử lý.
  - Đang giao hàng.
  - Đã giao hàng.
  - Đã hủy.
- Cho phép khách hàng đánh giá sản phẩm sau khi nhận hàng.
- Cho phép chọn số sao từ 1 đến 5.
- Cho phép nhập nội dung nhận xét.
- Hiển thị đánh giá đã gửi trước đó.

---

## 12. Giao diện tài khoản cá nhân

Trang tài khoản cho phép khách hàng xem và cập nhật thông tin cá nhân.

### Chức năng chính

- Hiển thị mã khách hàng.
- Hiển thị tên đăng nhập.
- Hiển thị họ và tên.
- Hiển thị ảnh đại diện.
- Hiển thị email.
- Hiển thị số điện thoại.
- Hiển thị giới tính.
- Hiển thị ngày sinh.
- Hiển thị ngày đăng ký tài khoản.
- Hiển thị địa chỉ giao hàng.
- Hiển thị số dư ví.
- Cập nhật thông tin cá nhân.
- Thay đổi ảnh đại diện.
- Chuyển đến trang đổi mật khẩu.
- Chuyển đến trang trạng thái đơn hàng.
- Quay lại trang chủ.

---

## 13. Giao diện đổi mật khẩu

Chức năng đổi mật khẩu giúp người dùng bảo vệ tài khoản của mình.

### Chức năng chính

- Nhập mật khẩu hiện tại.
- Nhập mật khẩu mới.
- Xác nhận lại mật khẩu mới.
- Kiểm tra mật khẩu hiện tại.
- Kiểm tra hai mật khẩu mới có trùng khớp.
- Cập nhật mật khẩu trong cơ sở dữ liệu.
- Hiển thị thông báo đổi mật khẩu thành công hoặc thất bại.

---

## 14. Giao diện giới thiệu

Trang giới thiệu cung cấp thông tin về thương hiệu Smile Coffee.

### Nội dung chính

- Giới thiệu quá trình hình thành Smile Coffee.
- Giới thiệu nguồn gốc ý tưởng.
- Trình bày động lực thành lập.
- Giải thích ý nghĩa tên gọi Smile Coffee.
- Trình bày cam kết về chất lượng sản phẩm.
- Giới thiệu không gian và phong cách phục vụ.
- Tạo sự tin tưởng cho khách hàng khi sử dụng dịch vụ.

---

## 15. Giao diện chatbot

Chatbot hỗ trợ khách hàng tìm kiếm thông tin nhanh chóng trong quá trình sử dụng website.

### Chức năng chính

- Gửi câu hỏi cho chatbot.
- Hỏi thông tin về thực đơn.
- Hỏi về sản phẩm.
- Hỏi về chương trình khuyến mãi.
- Hỏi về món mới.
- Nhận phản hồi tự động.
- Hiển thị cuộc hội thoại giữa khách hàng và chatbot.
- Hỗ trợ khách hàng ngay trên website.

---

# 🔐 Giao diện quản trị viên

## 16. Dashboard quản trị

Dashboard giúp quản trị viên theo dõi tổng quan hoạt động kinh doanh của cửa hàng.

### Chức năng chính

- Hiển thị tổng số sản phẩm.
- Hiển thị tổng số khách hàng.
- Hiển thị tổng số đơn hàng.
- Hiển thị tổng doanh thu.
- Truy cập nhanh đến quản lý sản phẩm.
- Truy cập quản lý danh mục.
- Truy cập quản lý khuyến mãi.
- Truy cập quản lý đánh giá.
- Truy cập quản lý đơn hàng.
- Truy cập quản lý khách hàng.
- Đăng xuất khỏi tài khoản quản trị.

---

## 17. Giao diện quản lý sản phẩm
Trang này cho phép quản trị viên quản lý toàn bộ món ăn và đồ uống của cửa hàng.

### Chức năng chính

- Hiển thị danh sách sản phẩm.
- Hiển thị tên và danh mục sản phẩm.
- Hiển thị giá bán.
- Hiển thị trạng thái đang bán hoặc đang ẩn.
- Hiển thị sản phẩm nổi bật.
- Thêm sản phẩm mới.
- Chỉnh sửa sản phẩm.
- Xóa sản phẩm.
- Tải ảnh sản phẩm lên hệ thống.
- Nhập mô tả sản phẩm.
- Nhập thành phần sản phẩm.
- Gán sản phẩm vào danh mục.
- Bật hoặc tắt trạng thái bán.
- Đánh dấu sản phẩm nổi bật.

---

## 18. Giao diện quản lý danh mục

Trang quản lý danh mục hỗ trợ tổ chức các sản phẩm trên thực đơn.

### Chức năng chính

- Hiển thị danh sách danh mục.
- Hiển thị mã danh mục.
- Hiển thị tên danh mục.
- Hiển thị số lượng sản phẩm trong từng danh mục.
- Thêm danh mục mới.
- Chỉnh sửa tên danh mục.
- Xóa danh mục.
- Đồng bộ danh mục với trang thực đơn của khách hàng.

---

## 19. Giao diện quản lý khuyến mãi

Trang này cho phép quản trị viên tạo và theo dõi các chương trình giảm giá.

### Chức năng chính

- Hiển thị danh sách chương trình khuyến mãi.
- Thêm chương trình khuyến mãi mới.
- Chỉnh sửa chương trình khuyến mãi.
- Xóa chương trình khuyến mãi.
- Thiết lập tên chương trình.
- Thiết lập phần trăm giảm giá.
- Thiết lập ngày bắt đầu.
- Thiết lập ngày kết thúc.
- Theo dõi số lượng khách hàng đã nhận voucher.
- Theo dõi số lượng voucher đã được sử dụng.
- Hiển thị voucher còn hiệu lực tại bước thanh toán.

---

## 20. Giao diện quản lý đánh giá

Trang quản lý đánh giá giúp quản trị viên theo dõi phản hồi của khách hàng.

### Chức năng chính

- Hiển thị tên khách hàng đánh giá.
- Hiển thị sản phẩm được đánh giá.
- Hiển thị số sao.
- Hiển thị nội dung bình luận.
- Hiển thị thời gian đánh giá.
- Xóa đánh giá không phù hợp.
- Tính lại điểm đánh giá trung bình của sản phẩm sau khi xóa.

---

## 21. Giao diện quản lý đơn hàng
Trang quản lý đơn hàng cho phép quản trị viên kiểm soát quá trình xử lý và giao hàng.

### Chức năng chính

- Hiển thị danh sách đơn hàng.
- Hiển thị mã đơn hàng.
- Hiển thị thông tin khách hàng.
- Hiển thị số điện thoại và địa chỉ giao hàng.
- Hiển thị danh sách sản phẩm.
- Hiển thị tổng số tiền.
- Hiển thị trạng thái thanh toán.
- Hiển thị trạng thái giao hàng.
- Cập nhật trạng thái đơn hàng.
- Chuyển đơn sang trạng thái chờ xử lý.
- Chuyển đơn sang trạng thái đang giao hàng.
- Chuyển đơn sang trạng thái đã giao hàng.
- Hủy đơn hàng.
- Phân công đơn hàng cho nhân viên giao hàng.
- Xác nhận đơn hàng đã thanh toán.

---

## 22. Giao diện quản lý khách hàng

Trang này giúp quản trị viên theo dõi tài khoản khách hàng trong hệ thống.

### Chức năng chính

- Hiển thị danh sách khách hàng.
- Hiển thị mã khách hàng.
- Hiển thị họ tên.
- Hiển thị tên đăng nhập.
- Hiển thị email.
- Hiển thị số điện thoại.
- Hiển thị địa chỉ.
- Hiển thị số dư ví.
- Tìm kiếm thông tin khách hàng.
- Truy cập chức năng cộng tiền vào ví khách hàng.

---

# 🚚 Giao diện nhân viên giao hàng

## 23. Giao diện đơn giao hàng
Giao diện dành cho nhân viên giao hàng xem những đơn đã được quản trị viên phân công.

### Chức năng chính

- Hiển thị danh sách đơn hàng được giao.
- Hiển thị mã đơn hàng.
- Hiển thị tên khách hàng.
- Hiển thị số điện thoại.
- Hiển thị địa chỉ giao hàng.
- Hiển thị ngày đặt hàng.
- Hiển thị tổng số tiền.
- Hiển thị phương thức thanh toán.
- Hiển thị trạng thái thanh toán.
- Hiển thị trạng thái giao hàng.
- Cập nhật đơn hàng đang giao.
- Xác nhận đơn hàng đã giao thành công.

---

# 🌐 Hỗ trợ đa ngôn ngữ

Website hỗ trợ hai ngôn ngữ:

- Tiếng Việt.
- Tiếng Anh.

Người dùng có thể thay đổi ngôn ngữ bằng biểu tượng lá cờ trên thanh điều hướng. Nội dung của các trang được thay đổi theo ngôn ngữ đã chọn.

---

# 🔄 Quy trình đặt hàng

1. Khách hàng đăng ký hoặc đăng nhập.
2. Truy cập trang thực đơn.
3. Tìm kiếm hoặc lọc sản phẩm theo danh mục.
4. Xem chi tiết sản phẩm.
5. Chọn số lượng và thêm sản phẩm vào giỏ hàng.
6. Kiểm tra và cập nhật giỏ hàng.
7. Chuyển đến trang thanh toán.
8. Kiểm tra thông tin giao hàng.
9. Chọn voucher giảm giá.
10. Chọn thanh toán COD hoặc ví/QR.
11. Xác nhận đặt hàng.
12. Theo dõi trạng thái đơn hàng.
13. Nhận hàng và đánh giá sản phẩm.

---

# 🗂️ Cấu trúc dự án

```text
smile-coffee-sqlserver-2025/
│
├── backend-php/
│   ├── api/
│   ├── config/
│   ├── uploads/
│   └── vendor/
│
├── frontend-spring/
│   ├── src/main/java/
│   │   └── com/smilecoffee/frontend/
│   │       ├── controller/
│   │       ├── dto/
│   │       ├── service/
│   │       └── config/
│   │
│   └── src/main/resources/
│       ├── static/
│       ├── templates/
│       └── application.properties
│
├── screenshots/
├── SQLQuery1.sql
└── README.md
```

---

# 👤 Vai trò người dùng

Hệ thống có ba vai trò chính:

### Khách hàng

- Đăng ký và đăng nhập.
- Xem sản phẩm.
- Quản lý giỏ hàng.
- Đặt hàng và thanh toán.
- Theo dõi đơn hàng.
- Quản lý tài khoản.
- Đánh giá sản phẩm.
- Sử dụng chatbot.

### Quản trị viên

- Quản lý sản phẩm.
- Quản lý danh mục.
- Quản lý khuyến mãi.
- Quản lý đánh giá.
- Quản lý đơn hàng.
- Quản lý khách hàng.
- Cộng tiền vào ví.
- Phân công nhân viên giao hàng.
- Theo dõi doanh thu.

### Nhân viên giao hàng

- Xem đơn được phân công.
- Xem thông tin người nhận.
- Theo dõi trạng thái thanh toán.
- Cập nhật tiến trình giao hàng.
- Xác nhận giao hàng thành công.

---

# Tác giả

**Đặng Tuấn Anh**

Dự án được phát triển nhằm phục vụ mục đích học tập, thực hành xây dựng website bán hàng và phát triển kỹ năng Full-stack Web Development.
