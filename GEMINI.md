# Project Rules: Graduation Web Project (Đồ Án Tốt Nghiệp)

## 1. Mục tiêu cốt lõi
- Xây dựng hệ thống web đồ án tốt nghiệp chỉn chu, thực tế, hoàn chỉnh từ giao diện (Frontend) đến logic nghiệp vụ (Backend) và CSDL.
- **Tuyệt đối tránh "mùi AI" (AI-generated smell)** trong cả mã nguồn (source code), giao diện (UI/UX) và tài liệu/báo cáo.

---

## 2. Quy chuẩn Frontend & UI/UX (Tuân thủ Skill `scroll-craft`)
- **Tránh bẫy template AI:**
  - KHÔNG sử dụng màu gradient tím neon rập khuôn (*AI-purple*).
  - KHÔNG dùng font `Inter` làm lựa chọn mặc định không suy nghĩ. Ưu tiên các font chất lượng cao, có cá tính: *Geist, Archivo, Outfit, Satoshi, Cabinet Grotesk* hoặc theo nhận diện thương hiệu của đề tài.
  - KHÔNG lặp lại các khối card 3 cột giống hệt nhau một cách sáo rỗng, không dùng số đếm kiểu `01 / 06` hay các dashboard số liệu giả lập.
- **Tiêu chuẩn Taste Floor (`taste.md`):**
  - Spacing nhịp điệu trên hệ 4px cơ sở, khoảng cách trên tiêu đề luôn lớn hơn dưới tiêu đề.
  - Bảng màu có cấu trúc 6 vai trò: `canvas`, `surface`, `ink`, `ink-soft`, `accent`, `accent-ink` (chỉ dùng duy nhất 1 màu accent chủ đạo).
  - Sử dụng chiều sâu thị giác (Layering, Parallax nhẹ, Depth) thay vì các khối hộp phẳng vô hồn.

---

## 3. Quy chuẩn Mã nguồn (Source Code) - "Code người viết, không phải AI sinh bừa"
- **Clean Code & Tự giải thích:**
  - Tên biến, tên hàm, tên class phải đặt bằng tiếng Anh chuẩn ngành hoặc theo thuật ngữ nghiệp vụ của đề tài, rõ nghĩa.
  - KHÔNG viết comment thừa múa, ngây ngô kiểu AI (vd: `// Khởi tạo biến`, `// Trả về kết quả`).
  - Chỉ ghi chú ở những luồng logic phức tạp hoặc nghiệp vụ đặc thù bằng tiếng Việt/tiếng Anh tự nhiên.
- **Thiết kế kiến trúc thực tế (KISS & YAGNI):**
  - Tránh over-engineering: Không nhồi nhét design pattern phức tạp không cần thiết khiến sinh viên không thể giải thích khi phản biện.
  - Cấu trúc thư mục module hóa rõ ràng (MVC, Clean Architecture tinh gọn hoặc Modular Layered) phù hợp với chuẩn bài làm tốt nghiệp.
- **Khả năng làm chủ và bảo vệ đồ án:**
  - Mọi đoạn code được sinh ra phải đảm bảo sinh viên trong nhóm có thể đọc, hiểu bản chất 100% để trả lời tự tin trước hội đồng chấm thi.
