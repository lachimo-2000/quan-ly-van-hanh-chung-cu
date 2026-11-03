# Quản lý vận hành nhà chung cư — Bản tự học tối giản

Website tự học với thiết kế **mobile-first, đọc liên tục, ít thao tác**. Mục tiêu là hiểu nội dung từ tổng quan đến chi tiết.

## Website

https://lachimo-2000.github.io/quan-ly-van-hanh-chung-cu/

## Cách học

1. **Tổng quan:** xem lộ trình 5 chủ đề và bức tranh ngành.
2. **Đọc nội dung:** chạm vào một chủ đề và cuộn qua toàn bộ các mục; dùng mục lục để nhảy đến phần muốn đọc.
3. **Ví dụ:** mỗi mục có diễn giải, ví dụ công việc và chỉ dẫn trang PDF tương ứng.
4. **Tự ôn (không bắt buộc):** mỗi chủ đề có 2 câu gợi nhớ; tổng cộng **10 câu**, không chấm điểm, không có thi riêng hay gamification.
5. **Thuật ngữ:** trang tra cứu các khái niệm phổ biến, có tìm kiếm tiếng Việt.

Giao diện ưu tiên màn hình **320–430px**, chữ đọc thoải mái, không cần mở từng bài học thành các trang con. Trình duyệt lưu chủ đề và vị trí đọc gần nhất trên cùng thiết bị.

## Cấu trúc kỹ thuật

Website chính nằm trong `index.html` và chạy độc lập. Để triển khai, vào **Settings → Pages → Source: GitHub Actions**. Workflow `.github/workflows/deploy.yml` chạy khi cập nhật nhánh `main`.

Không cần Node, backend, API key hoặc cơ sở dữ liệu.

## Giới hạn và quyền nội dung

Nội dung là bản diễn giải tự học từ 5 PDF về pháp luật, bàn giao, vận hành, hợp đồng và tài chính; không phải chứng nhận nghiệp vụ. Các tình huống tổng hợp chỉ để minh họa. Kiểm tra hiệu lực văn bản pháp luật trước khi dùng trong công việc. Việc công khai học liệu chuyển thể cần có quyền sử dụng phù hợp; repository không chứa các PDF nguyên bản.
