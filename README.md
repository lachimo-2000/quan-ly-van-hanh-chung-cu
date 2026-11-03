# Tự học quản lý vận hành nhà chung cư — Mobile Reading Hub (V3)

Trang web: https://lachimo-2000.github.io/quan-ly-van-hanh-chung-cu/

## Mục đích

Bản học tập ưu tiên **đọc - hiểu - tra cứu từ tổng quan đến chi tiết**, thay vì kiểm tra liên tục. Được thiết kế cho điện thoại và người học mới.

- **5 chủ đề**, 38 mục đọc cốt lõi được diễn giải, **25 cụm kiến thức đọc sâu**.
- Sơ đồ quy trình, so sánh, vai trò và các thẻ trực quan theo từng chủ đề.
- Nguồn PDF và **số trang cụ thể cạnh mỗi mục**.
- Thư viện 5 PDF gốc, hỗ trợ mở theo số trang khi người học đã chọn file trên thiết bị.
- Lộ trình cuộn liên tục và mục lục nhảy nhanh tùy chọn; không phải mở nhiều lớp bài học.
- Không có hệ thống quiz/test bắt buộc.

## Sử dụng trên điện thoại

1. Mở website, chọn chủ đề.
2. Cuộn từ tổng quan đến chi tiết. Có thể mở *Mục lục* để nhảy tới mục muốn xem.
3. Khi muốn xem slide gốc, nhấn nút **Mở PDF trang ...**; lần đầu website chuyển tới Thư viện để bạn chọn đúng PDF.
4. Tại Thư viện, chọn file PDF từ thiết bị. Website thử lưu file trong **IndexedDB** của trình duyệt để mở lại ở những lần sau, nhưng việc lưu có thể thất bại nếu thiết bị thiếu dung lượng hoặc giới hạn bộ nhớ.
5. Sau đó quay lại chủ đề và nhấn mở trang tương ứng. Một số ứng dụng xem PDF trên điện thoại có thể bỏ qua tham số trang, khi đó dùng số trang hiển thị để đi tới trang thủ công.

**Quan trọng:** PDF tải vào Thư viện được lưu **riêng trên thiết bị của người học**, không gửi lên GitHub hay máy chủ. PDF gốc **chưa được xuất bản công khai** do chưa xác nhận quyền phân phối nội dung từ tác giả/cơ sở đào tạo. Vì vậy người mới truy cập cần có sẵn 5 file PDF để liên kết hoạt động.

## Nội dung gốc và giới hạn

Bộ tài liệu gồm:
1. Pháp luật (60 trang)
2. Tiếp nhận hồ sơ chung cư (47 trang, chọn bản có tên `(1)`)
3. Quản lý dự án (33 trang)
4. Hợp đồng QLVH (54 trang)
5. Quản lý tài chính (30 trang)

Tổng cộng **224 trang**. Phần học trên website là bản tóm lược và diễn giải; các mục đọc sâu tăng độ phủ nhưng vẫn **không đồng nghĩa đã chuyển thể từng chi tiết của 224 trang**. Muốn tìm đầy đủ quy định, biểu mẫu và hình ảnh slide, sử dụng nút mở PDF gốc. Cần kiểm tra hiệu lực pháp luật trước khi áp dụng vào công việc thực tế.

## Kỹ thuật / triển khai GitHub Pages

- `index.html`: điểm vào, dữ liệu bài học.
- `assets/v3.css`: giao diện mobile-first.
- `assets/atlas.js`: 25 cụm đọc sâu có sơ đồ và tham chiếu trang.
- `assets/v3.js`: nội dung trang, điều hướng, thư viện PDF cá nhân dùng IndexedDB.
- `.github/workflows/deploy.yml`: deploy tất cả file cần thiết khi push lên `main`.

Tại GitHub **Settings → Pages**, chọn **GitHub Actions**. Không cần backend, tài khoản học viên, API key hoặc Node.js để vận hành.

Source ZIP cập nhật từ repository: https://github.com/lachimo-2000/quan-ly-van-hanh-chung-cu/archive/refs/heads/main.zip
