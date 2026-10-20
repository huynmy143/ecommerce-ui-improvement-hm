# E-commerce UI Improvement

## 1. Giới thiệu

Dự án thực hiện cải tiến giao diện trang chủ (Homepage) của website thương mại điện tử Ananas ([https://ananas.vn/](https://ananas.vn/)) bằng HTML5 và CSS3.

Giao diện được thiết kế lại nhằm cải thiện khả năng điều hướng, giúp người dùng truy cập nhanh đến các danh mục sản phẩm phổ biến, đồng thời sắp xếp nội dung quảng bá và mua sắm theo thứ tự ưu tiên rõ ràng hơn.

## 2. Website tham khảo

- **Tên website:** Ananas
- **URL:** https://ananas.vn/
- **Khu vực đã khảo sát:** Trang chủ (Homepage).
- **Khu vực cải tiến:** Trang chủ, tập trung vào Hero Banner và khu vực truy cập nhanh danh mục sản phẩm.

## 3. Chức năng

- Hiển thị các khu vực chính gồm Header, Hero Banner, danh mục nhanh, sản phẩm nổi bật, khu vực quảng bá thương hiệu và Footer.
- Hiển thị danh mục sản phẩm như Giày Nam, Giày Nữ, Sản phẩm mới và Sale Off.
- Hiển thị danh sách sản phẩm mẫu với hình ảnh, tên, thông tin phân loại và giá bán bằng VNĐ.
- Cung cấp các liên kết điều hướng và nút thao tác trên giao diện.
- Hỗ trợ bố cục responsive cho màn hình máy tính, máy tính bảng và điện thoại.

**Lưu ý:** Đây là bản dựng giao diện phía người dùng. Các chức năng như tìm kiếm thực tế, quản lý giỏ hàng và thanh toán chưa được triển khai.

## 4. Công nghệ

- **HTML5:** Xây dựng cấu trúc và nội dung trang web.
- **CSS3:** Thiết kế giao diện, định dạng nội dung, tạo hiệu ứng và điều chỉnh bố cục responsive.
- **Flexbox và CSS Grid:** Hỗ trợ sắp xếp các thành phần giao diện.
- **Media Queries:** Điều chỉnh bố cục theo kích thước màn hình.
- **Google Fonts – Be Vietnam Pro:** Hỗ trợ hiển thị nội dung tiếng Việt.

## 5. Cách chạy

1. Tải hoặc sao chép mã nguồn dự án về máy tính.
2. Đảm bảo file `index.html` và file `style.css` nằm trong cùng một thư mục.
3. Mở file `index.html` bằng trình duyệt Microsoft Edge, Google Chrome hoặc trình duyệt tương thích.
4. Để kiểm tra giao diện trên điện thoại, mở Developer Tools và sử dụng chế độ mô phỏng thiết bị (Device Toolbar).
5. Đảm bảo thiết bị có kết nối Internet nếu giao diện sử dụng font chữ và hình ảnh từ nguồn trực tuyến.

## 6. Cải tiến đã thực hiện

### Vấn đề ban đầu

Qua khảo sát website Ananas, trang chủ có nhiều banner, nội dung quảng bá và chương trình khuyến mãi. Điều này có thể khiến người dùng mất thêm thời gian để tìm đến danh mục sản phẩm mong muốn.

### Những thay đổi đã thực hiện

- **Cải tiến Hero Banner:** Phân chia bố cục bất đối xứng, đặt nội dung bên trái và hình ảnh sản phẩm bên phải nhằm làm nổi bật thông điệp chính.
- **Tăng khả năng nhận diện:** Sử dụng màu cam làm màu nhấn, kết hợp nền trung tính và hình ảnh sneaker.
- **Cải thiện kiểu chữ:** Sử dụng font Be Vietnam Pro, điều chỉnh kích thước, độ đậm và khoảng cách chữ.
- **Bổ sung khu vực truy cập nhanh:** Tổ chức bốn danh mục Giày Nam, Giày Nữ, Sản phẩm mới và Sale Off ngay sau Hero Banner.
- **Tổ chức sản phẩm đồng nhất:** Sử dụng các thẻ sản phẩm có cấu trúc thống nhất, hiển thị hình ảnh, tên, thông tin phân loại và giá.
- **Điều chỉnh giao diện responsive:** Sử dụng CSS Grid và Media Queries để thay đổi bố cục theo kích thước màn hình.

### Kết quả

Giao diện được tổ chức theo thứ tự rõ ràng hơn, nhấn mạnh thông điệp thương hiệu và tạo lối truy cập nhanh đến các danh mục phổ biến. Tuy nhiên, đây vẫn là bản dựng giao diện minh họa; hiệu quả cải thiện trải nghiệm người dùng chưa được đo lường bằng dữ liệu thực tế.

## 7. Hỗ trợ từ AI

ChatGPT được sử dụng để hỗ trợ đề xuất bố cục, xây dựng mã nguồn HTML5 và CSS3, giải thích các thành phần giao diện.

Sau khi nhận kết quả, người thực hiện đã kiểm tra giao diện trên trình duyệt và sử dụng Developer Tools để mô phỏng màn hình điện thoại. Các điều chỉnh bổ sung tập trung vào bố cục Hero Banner, font Be Vietnam Pro, màu sắc, kích thước chữ và cách trình bày thanh điều hướng.

Người thực hiện chịu trách nhiệm kiểm tra, điều chỉnh mã nguồn và đánh giá mức độ phù hợp của các thay đổi với mục tiêu cải tiến ban đầu.

Chi tiết về việc sử dụng AI được trình bày trong file `AI_USAGE.md`.
