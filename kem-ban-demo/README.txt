KÈMBẠN — DEMO UX/UI WEB GIA SƯ 1–1 OFFLINE

BẮT ĐẦU
1. Giải nén ZIP.
2. Mở file index.html bằng Chrome/Edge. Không cần cài thư viện hoặc server.
3. Click các menu: Khám phá, Tìm gia sư, Bảng tin, Lớp học, Tin nhắn.
4. Chuyển vai trò ở góc phải để xem Khách, Phụ huynh, Gia sư, Quản trị.
5. Luồng demo: Khám phá > Tìm gia sư > Hồ sơ > Kết nối > Tin nhắn > Xem gói > Thanh toán demo > Lớp học > Xác nhận buổi > Ví/Đánh giá/Gia hạn.

TẬP TIN
- index.html: giao diện và liên kết mã nguồn.
- styles.css: thiết kế và responsive.
- app.js: route, dữ liệu giả lập và tương tác.
- mockup.png: ảnh định hướng mỹ thuật (concept, không phải ảnh chụp prototype).
- so_do_giao_dien.drawio: file mở trong app.diagrams.net, có 3 trang diagram.

PHẠM VI MÔ PHỎNG
- Không có backend, login thật, lưu trữ dữ liệu, tài khoản ngân hàng, QR thật, realtime socket hoặc OCR thật.
- Giá, hồ sơ, rating, lịch học, giao dịch là dữ liệu minh họa.
- Nút "Giả lập thanh toán thành công" KHÔNG thu tiền.
- Bộ lọc tin nhắn chỉ là regex đơn giản, KHÔNG được xem là biện pháp bảo mật.
- Dữ liệu trong phiên được reset khi refresh trang (riêng vai trò lưu localStorage).
- Chưa có cơ chế đồng thuận 2 bên, kiểm tra lịch trùng, trạng thái duyệt admin hay settlement thực tế.
- Cách tính phí 300.000đ trong demo: khấu trừ từ giá trị gói đầu; phương thức dòng tiền sản xuất phải được xác minh pháp lý và kỹ thuật.

THAM KHẢO UX
- Preply: tìm gia sư theo môn, mức phí, lịch rảnh (dịch vụ online)
- Superprof: hồ sơ gia sư, địa điểm và mô hình gia sư trực tiếp
- Điểm khác biệt KèmBạn: riêng offline 1-1, match và chat, gói buổi, xác nhận từng buổi, hủy/dời 12h, đánh giá, gia hạn lớp.
