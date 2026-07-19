# Spec: Pitch Deck HTML Chuẩn EXE (Mentor Booking)

**Status:** approved

## Goal
Xây dựng một Pitch Deck dưới dạng trang HTML đơn trang (Single-Page Presentation) theo chuẩn chương trình khởi nghiệp EXE cho dự án **Mentor Booking**, trực quan hóa toàn bộ thông tin chiến lược, quy tắc nghiệp vụ và KPI từ `PRD.md` thành 8 phân hệ trình bày chuyên nghiệp, sẵn sàng sử dụng trực tiếp trong buổi thuyết trình pitching trước nhà đầu tư và đối tác.

## Requirements
- **WHEN** người dùng mở trang HTML trên trình duyệt Desktop hoặc Mobile **THEN** trang web phải hiển thị giao diện cao cấp (Premium & Modern Aesthetics), hỗ trợ 2 chế độ: **Chế độ Trình chiếu (Slide/Pitching Mode)** (dùng phím mũi tên Trái/Phải hoặc nút bấm để qua lại giữa các slide) và **Chế độ Cuộn trang (Scroll Mode)** (để xem tổng thể như Landing page).
- **WHEN** thuyết trình theo tiêu chuẩn EXE **THEN** nội dung Pitch Deck phải bao gồm đầy đủ 8 phần chính theo cấu trúc logic:
  1. **PROBLEM (Vấn đề & Nỗi đau 3P):** Trình bày rõ nỗi đau thực tế của Sinh viên (mù mờ thông tin, đặt lịch thủ công, lỡ cơ hội), Mentor (phiền toái chốt lịch qua lại, sinh viên thiếu chuẩn bị/ghosting), và Doanh nghiệp/Admin (khó quản lý đội ngũ mentor, thiếu dữ liệu tuyển dụng sớm, quá tải điều phối).
  2. **SOLUTION (Giải pháp khép kín):** Nền tảng tự động hóa "Self-service" kết nối 3 bên với quy trình 4 bước: Khớp nối nhu cầu -> Đặt lịch chống trùng slot tự động -> Tích hợp Video Call/Calendar -> Đánh giá & Lưu biên bản tư vấn.
  3. **MARKET (Thị trường tiềm năng):** Thể hiện quy mô thị trường EdTech/HRTech Việt Nam (~3.5 tỷ USD) và mô hình TAM - SAM - SOM (TAM: ~2 triệu sinh viên toàn quốc; SAM: ~500k sinh viên khối ngành trọng điểm; SOM cho MVP 6 tháng: 10,000 sinh viên tại các trường đối tác, 150+ Mentor, 30+ Doanh nghiệp).
  4. **PRODUCT (Sản phẩm & Năng lực cốt lõi):** Giới thiệu trực quan 4 phân hệ cốt lõi từ `PRD.md`: (a) Hồ sơ & Lịch trống (timeslot 45-60p), (b) Quy tắc Khóa/Mở lịch (Pending Lock lập tức & Auto-unlock sau 24h nếu chưa duyệt), (c) Đồng bộ Calendar & Nhắc lịch đa kênh (trước 24h & 2h), (d) Hậu tư vấn & Chế tài (Meeting Minutes, Action Items, 3-Strike Rule cho No-show >15p).
  5. **BUSINESS MODEL (Mô hình kinh doanh B2B2C):** Freemium cho Sinh viên (tạo hiệu ứng mạng lưới) kết hợp B2B Subscription/Partnership cho Doanh nghiệp & Trường học (công cụ quản lý Mentor công ty, truy xuất dữ liệu Talent Pipeline cho tuyển dụng sớm & tài trợ Employer Branding/CSR).
  6. **TRACTION & ROADMAP (Dấu ấn & Lộ trình):** Hiển thị các KPI mục tiêu MVP 6 tháng theo PRD: Tỷ lệ đặt lịch thành công (>85%), Thời gian phản hồi (<12h), Tỷ lệ tạo biên bản tư vấn (>90%), và 1,000+ Active Students / 150+ Active Mentors / 30+ Active Companies; kèm lộ trình phát triển 8 tuần Go-live.
  7. **TEAM (Đội ngũ nhân sự & Hệ sinh thái):** Giới thiệu vai trò và sự gắn kết của 3 đối tượng trọng tâm (Sinh viên - Mentor - Doanh nghiệp/Nhà trường) cùng đội ngũ thực hiện dự án.
  8. **ASK (Kêu gọi đồng hành / Đầu tư):** Nêu thông điệp kêu gọi hợp tác chiến lược từ 30 Doanh nghiệp tiên phong (Sponsor & Mentor Network) và ngân sách/tài nguyên hỗ trợ triển khai MVP trong 8 tuần.
- **WHEN** người dùng tương tác với các phần tử UI **THEN** trang HTML phải có hiệu ứng mượt mà (hover cards, tab switching, counter animations cho KPI, mô phỏng interactive booking slot) để tạo ấn tượng WOW.
- **WHEN** tải trang **THEN** file HTML là tự chứa (nhúng sẵn CDN Tailwind CSS hoặc Vanilla CSS nhúng gọn, Google Fonts Inter/Outfit, FontAwesome/Lucide icons) đảm bảo mở nhanh, không phụ thuộc build tool phức tạp.

## Out of scope
- Không xây dựng backend hay kết nối database thực tế (đây là tài liệu trình diễn mô phỏng phục vụ thuyết trình pitching).
- Không sử dụng các framework nặng (như Next.js hay React build) để đảm bảo tính di động tối đa: người dùng có thể copy file `index.html` mở trên bất kỳ máy tính nào tại phòng pitching mà không cần cài Node.js hay chạy server.

## Acceptance criteria
- [ ] File HTML đơn trang (`index.html` trong thư mục workspace) được tạo ra với bố cục chuyên nghiệp, hỗ trợ responsive hoàn hảo trên Desktop và Mobile.
- [ ] Tích hợp bộ chuyển đổi (Toggle Button) giữa Chế độ Trình chiếu (Pitching Mode với phím mũi tên trái/phải và thanh tiến trình) và Chế độ Cuộn (Scroll Mode).
- [ ] Đầy đủ 8 phần chuẩn EXE: Problem, Solution, Market, Product, Business Model, Traction, Team, Ask.
- [ ] Số liệu KPI và quy tắc nghiệp vụ khớp 100% với `PRD.md` (Success rate >85%, Response <12h, Meeting Minutes >90%, 1,000 SV/150 Mentor/30 DN, quy tắc Pending Lock, Auto-unlock 24h, 3-Strike Rule).
- [ ] Giao diện trực quan, phối màu hiện đại (Dark slate/Navy `#0f172a`, Indigo/Blue `#4f46e5`, Gold accent `#f59e0b`), typography rõ ràng, sẵn sàng thuyết trình ngay lập tức.
