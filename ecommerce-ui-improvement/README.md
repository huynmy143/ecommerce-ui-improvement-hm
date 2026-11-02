# E-commerce UI Improvement
# README – BÀI TẬP CÁ NHÂN BUỔI 2
**Môn học:** Phát triển ứng dụng Thương mại điện tử

## 1. Giới thiệu bài tập
Bài tập Buổi 2 tiếp tục phát triển website từ Buổi 1, tập trung vào việc hoàn thiện giao diện bằng HTML5 và CSS3. Nội dung thực hành bao gồm sử dụng các bộ chọn CSS, Box Model, Flexbox và CSS Grid để bố trí, căn chỉnh và cải thiện trải nghiệm hiển thị trên website.

## 2. Website tham khảo và khu vực cải tiến
- **Website tham khảo:** Ananas – https://ananas.vn/
- **Website thực hiện:** Ananas – giao diện minh họa phục vụ mục đích học tập.
- **Khu vực cải tiến:** Header, Hero, danh mục sản phẩm, danh sách sản phẩm nổi bật, Brand Story, Newsletter và Footer.
- **Định hướng:** Hoàn thiện bố cục, khoảng cách, màu sắc, hiệu ứng tương tác và khả năng hiển thị trên các kích thước màn hình khác nhau.

## 3. Những kỹ thuật HTML5/CSS3 đã thực hành

**HTML5:**
- Sử dụng các thẻ ngữ nghĩa như `header`, `nav`, `main`, `section`, `article`, `footer`.
- Sử dụng danh sách `ul`, `li`, liên kết `a` và hình ảnh `img`.
- Sử dụng các thuộc tính `class`, `id`, `alt` và cấu trúc phân cấp nội dung.

**CSS3:**
- Sử dụng CSS Selector: Element, Class, ID, Pseudo-class.
- Áp dụng Box Model: `margin`, `padding`, `border`.
- Sử dụng Flexbox: `display: flex`, `justify-content`, `align-items`, `gap`.
- Sử dụng CSS Grid: `display: grid`, `grid-template-columns`, `gap`.
- Tạo hiệu ứng tương tác với `:hover`, `:focus-visible`, `transition`, `transform`.
- Sử dụng Media Queries để điều chỉnh giao diện theo kích thước màn hình.

## 4. Hướng dẫn chạy website
1. Tải hoặc sao chép thư mục dự án về máy tính.
2. Mở thư mục dự án bằng Visual Studio Code.
3. Kiểm tra các tệp HTML, CSS và thư mục hình ảnh.
4. Mở tệp `index.html` bằng trình duyệt hoặc sử dụng tiện ích Live Server trong Visual Studio Code.
5. Thay đổi kích thước cửa sổ trình duyệt để kiểm tra khả năng hiển thị responsive.

## 5. Những thay đổi đã thực hiện
- Điều chỉnh bố cục và khoảng cách giữa các thành phần giao diện.
- Hoàn thiện cách sắp xếp các danh mục và thẻ sản phẩm.
- Tối ưu bố cục Footer bằng CSS Grid và Flexbox.
- Điều chỉnh kích thước chữ, màu sắc, đường viền và khoảng cách.
- Bổ sung hiệu ứng hover cho các nút và liên kết.
- Điều chỉnh giao diện trên tablet và điện thoại bằng Media Queries.

## 6. Công cụ AI đã sử dụng và cách kiểm tra kết quả
**Công cụ AI:** ChatGPT.

**Mục đích sử dụng:**
- Hỗ trợ giải thích các thuộc tính HTML5 và CSS3.
- Gợi ý cách cải thiện bố cục và xử lý các lỗi hiển thị.
- Hướng dẫn điều chỉnh CSS và giải thích chức năng của từng thuộc tính.

**Cách kiểm tra kết quả:**
- Tự chỉnh sửa và lưu mã nguồn trong Visual Studio Code.
- Mở website trên Microsoft Edge để kiểm tra giao diện thực tế.
- Sử dụng Developer Tools và chế độ Responsive để kiểm tra hiển thị ở nhiều kích thước màn hình.
- Đối chiếu kết quả trước và sau khi chỉnh sửa để xác định tính phù hợp của các thay đổi.

AI được sử dụng như công cụ hỗ trợ học tập và tham khảo; mã nguồn được kiểm tra, điều chỉnh và chạy thử trực tiếp trên trình duyệt.
# README – BÀI TẬP CÁ NHÂN BUỔI 1
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
