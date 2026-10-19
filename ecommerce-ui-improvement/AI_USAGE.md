# AI Usage Log

## 1. Công cụ AI
- **Tên công cụ:** Gemini và ChatGPT

## 2. Mục đích sử dụng
- Khảo sát & phân tích UX/UI 5 khu vực website TMĐT.
- Đề xuất khung mã nguồn HTML5/CSS3 cho thẻ sản phẩm.
- Gợi ý phương án tối ưu cụm nút thao tác mua hàng.

## 3. Prompt đã sử dụng
1. *Prompt 1:* "Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng... Hãy giúp tôi lập bảng phân tích các khu vực..."
2. *Prompt 2:* "Tôi đang thực hiện bài tập phát triển giao diện... Tôi muốn cải tiến khu vực thẻ sản phẩm..."
3. *Prompt 3:* "Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện..."

## 4. Kết quả AI đề xuất
- Bảng phân tích ưu/nhược điểm 5 khu vực giao diện.
- Mã nguồn `index.html` và `style.css` dựng khung thẻ sản phẩm dạng lưới responsive.
- Đề xuất bổ sung nút "Mua ngay" cạnh "Thêm vào giỏ".

## 5. Kiểm tra và điều chỉnh
- **Loại bỏ:** Nhận xét AI cho rằng tìm kiếm bị chậm do không đúng thực tế web Cocoon.
- **Bổ sung:** Cấu hình Flexbox cho `.card-actions` để đặt nút Icon giỏ hàng và nút "Mua ngay" nằm song song chuẩn thẩm mỹ.

## 6. Phần tôi hiểu và có thể giải thích
- **HTML:** Cấu trúc thẻ `<article>`, `<div class="card-price">`, `<div class="card-actions">`.
- **CSS:** Sử dụng `display: grid` làm lưới sản phẩm, `display: flex` cho cụm nút bấm, thuộc tính `min-height` giữ độ đồng nhất và Media Queries `@media (max-width: 768px)` cho giao diện điện thoại.