# Building Operations Learning Hub

Website tự học quản lý vận hành nhà chung cư — ưu tiên điện thoại, có thể chạy bằng file HTML tĩnh.

## Xem website

Mở [website GitHub Pages](https://lachimo-2000.github.io/quan-ly-van-hanh-chung-cu/) khi đã bật Pages.

## Triển khai

1. Trong repository vào **Settings → Pages → Build and deployment → Source: GitHub Actions**.
2. Mở tab **Actions**, chọn workflow **Deploy Building Operations Learning Hub**, bấm **Run workflow** nếu chưa tự chạy.
3. Khi workflow thành công, truy cập đường dẫn website ở trên.

Mã nguồn hiện đang ở dạng standalone `index.html`; không cần Node.js, npm, backend, API key hoặc dịch vụ hosting trả phí. Workflow chỉ deploy file này. Bản ZIP dự phòng có cấu trúc tách CSS/JS và dữ liệu bài học, hữu ích cho các lần phát triển tiếp theo.

## Học liệu

Lộ trình gồm 7 module, 41 bài học, phần kiểm tra, tình huống và thuật ngữ. Nội dung được chuyển thể phục vụ mục đích tự học từ 5 tài liệu khóa quản lý vận hành nhà chung cư. **Đây không phải khóa đào tạo cấp giấy chứng nhận.** Nội dung pháp lý cần đối chiếu quy định hiện hành trước khi áp dụng thực tế.

## Tiến độ học

Dữ liệu lưu trong trình duyệt trên thiết bị của học viên, không đồng bộ tự động giữa điện thoại và máy tính.

## Quyền sử dụng nội dung

Bản quyền học liệu gốc thuộc về tác giả/chủ sở hữu tương ứng. Nếu công khai website hoặc chia sẻ nội dung chuyển thể, cần có quyền sử dụng và phân phối phù hợp. Không đưa 5 file PDF gốc vào repository.
