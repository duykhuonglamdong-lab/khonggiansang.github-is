# KPS - Website tĩnh miễn phí

Đây là bộ mã nguồn website tĩnh (HTML/CSS) cho **KPS – Cửa hàng đèn chiếu sáng**. Có thể triển khai miễn phí trên GitHub Pages, Netlify hoặc Vercel.

## Cấu trúc
- `index.html` – Trang chủ
- `san-pham.html` – Danh sách sản phẩm mẫu
- `lien-he.html` – Thông tin & form liên hệ (mailto)
- `assets/style.css` – Giao diện

## Triển khai miễn phí

### Cách 1: GitHub Pages
1. Tạo tài khoản tại github.com.
2. Tạo repo mới tên `kps-website` (Public).
3. Tải toàn bộ file lên repo (Upload files).
4. Vào **Settings → Pages → Build and Deployment**:
   - Source: **Deploy from a branch**.
   - Branch: `main` (hoặc `master`) / folder root.
5. Chờ GitHub xuất bản, truy cập: `https://<tên-tài-khoản>.github.io/kps-website/`.

### Cách 2: Netlify
1. Vào app.netlify.com, đăng nhập bằng GitHub.
2. **New Site from Git**, chọn repo vừa tạo.
3. Build command để trống, publish directory: `/`.
4. Nhấn Deploy → sẽ có tên miền miễn phí `*.netlify.app`.

### Cách 3: Vercel
1. Vào vercel.com, đăng nhập bằng GitHub.
2. **Add New… → Project**, chọn repo.
3. Framework: *Other* (static), Output dir: `/`.
4. Deploy → có tên miền `*.vercel.app`.

## Tuỳ chỉnh nhanh
- Thay hotline, email, địa chỉ trong các file `.html`.
- Đổi tên thương hiệu ở phần `<a class="logo">KPS</a>`.
- Thay ảnh sản phẩm: thay nội dung khối `.placeholder` bằng thẻ `<img src="..." alt="">`.

## Mẹo SEO miễn phí
- Sử dụng tiêu đề trang (title) rõ ràng, mô tả (description) chứa từ khoá.
- Tạo trang Google Business Profile để hiển thị Maps.
- Thêm `alt` mô tả cho ảnh.

Chúc bạn triển khai suôn sẻ!
