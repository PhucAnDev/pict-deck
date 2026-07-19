## **1. Business Vision and Objective (Tầm nhìn & Mục tiêu kinh doanh)**
### **1.1. Tuyên bố tầm nhìn (Vision Statement)**
Xây dựng Mentor Booking trở thành nền tảng "Self-service" trung tâm kết nối nguồn lực tri thức, thu hẹp khoảng cách giữa Nhà trường và Doanh nghiệp. Hệ sinh thái này hỗ trợ Sinh viên chủ động định hướng sự nghiệp, giúp Mentor tối ưu hóa quỹ thời gian chia sẻ kinh nghiệm, và tạo điều kiện cho Doanh nghiệp tiếp cận sớm nguồn nhân lực chất lượng cao thông qua một quy trình đặt lịch tự động, minh bạch và hiệu quả.
### **1.2. Hệ mục tiêu KPI (Key Performance Indicators)**
Đánh giá hiệu quả của phiên bản MVP trong 6 tháng đầu triển khai qua các chỉ số cốt lõi sau:

**Tỷ lệ đặt lịch thành công (Booking Success Rate):** Mục tiêu đạt trên **85%**. Chỉ số này được đo lường bằng tổng số lịch được Mentor bấm chấp nhận chia cho tổng số yêu cầu đặt lịch từ Sinh viên nhân với 100.


**Thời gian phản hồi trung bình (Avg. Response Time):** Mục tiêu đạt dưới **12 giờ**. Chỉ số này đo lường khoảng thời gian trung bình tính từ lúc Sinh viên nhấn nút gửi yêu cầu đến khi hệ thống ghi nhận phản hồi (Chấp nhận hoặc Từ chối) từ Mentor hoặc Doanh nghiệp.


**Tỷ lệ tạo biên bản tư vấn (Meeting Minutes Rate):** Mục tiêu đạt trên **90%**. Chỉ số này được tính bằng tổng số cuộc họp có Biên bản tư vấn được cập nhật chia cho tổng số cuộc họp thực tế đã diễn ra thành công.


**Lượng người dùng tích cực (Active Users):** Mục tiêu đạt tối thiểu **1,000 Sinh viên**, **150 Mentor** và **30 Doanh nghiệp** hoạt động tích cực. Chỉ số này đo lường số lượng tài khoản có phát sinh ít nhất 1 hành động như Đặt lịch, Duyệt lịch, Cập nhật lịch trống hoặc Quản lý nhân sự trên hệ thống trong vòng một tháng.

## **2. Problem Statement (Tuyên bố vấn đề)**
### **2.1. Hiện trạng (As-is) & Nỗi đau (Pain points)**
Quy trình kết nối giữa sinh viên, chuyên gia và doanh nghiệp hiện tại đang vận hành hoàn toàn thủ công thông qua câu lạc bộ, khoa/trường hoặc các buổi kết nối rời rạc bằng Google Forms, Excel, và Zalo. Cách làm này dẫn đến các nút thắt lớn:

**Đối với Sinh viên:** Họ bị rơi vào trạng thái mù mờ thông tin, không biết rõ hồ sơ năng lực thực tế của Mentor và các cơ hội kết nối từ Doanh nghiệp. Việc xếp lịch thủ công qua trung gian mất quá nhiều thời gian khiến họ bỏ lỡ các mốc quan trọng như chuẩn bị phỏng vấn, làm đồ án tốt nghiệp hoặc định hướng nghề nghiệp khẩn cấp.


**Đối với Mentor:** Họ bị phiền toái vì phải nhắn tin trao đổi qua lại nhiều lần chỉ để chốt một khung giờ rảnh với sinh viên. Nhiều trường hợp sinh viên không chuẩn bị kỹ câu hỏi trước, thậm chí hủy lịch sát giờ (ghosting) mà không thông báo trước, gây lãng phí quỹ thời gian quý báu của chuyên gia.


**Đối với Doanh nghiệp:** Khó quản lý và theo dõi hiệu quả làm việc của đội ngũ Mentor thuộc công ty mình khi tham gia các hoạt động cộng đồng hoặc hướng nghiệp. Doanh nghiệp thiếu dữ liệu tập trung để đánh giá chất lượng sinh viên tiềm năng nhằm phục vụ cho mục tiêu tuyển dụng sớm.


**Đối với Admin:** Bộ phận điều phối trường học hoặc ban tổ chức bị quá tải vận hành trầm trọng khi số lượng sinh viên đăng ký tăng lên. Admin không có công cụ để theo dõi sát sao tiến độ và chất lượng các buổi tư vấn, dữ liệu lưu trữ rải rác làm mất đi tính hệ thống.

### **2.2. Trạng thái mong muốn (To-be) & Khoảng cách (Gap)**

**Trạng thái To-be:** Nền tảng tự động hóa khâu kết nối ba bên. Sinh viên chủ động tra cứu và đặt lịch theo nhu cầu kỹ năng; Mentor tự quản lý quỹ thời gian rảnh; Doanh nghiệp có không gian quản lý đội ngũ chuyên gia của mình và theo dõi các tài năng trẻ tiềm năng; hệ thống tự xử lý link phòng họp, đồng bộ lịch và nhắc nhở tự động.


**Khoảng cách cần giải quyết (Gap):** Xây dựng luồng nghiệp vụ khép kín từ Tìm kiếm -> Khớp nối nhu cầu -> Đặt lịch -> Họp trực tuyến -> Đánh giá hậu tư vấn, loại bỏ hoàn toàn sự can thiệp thủ công của Admin trong suốt quá trình chốt lịch.

## **3. Stakeholder Register (Sổ đăng ký bên liên quan)**
Cấu trúc quản lý và phân bổ nỗ lực giao tiếp cho các nhóm đối tượng tham gia dự án:

**Nhóm Sponsor / C-level (Ban giám hiệu / Giám đốc dự án):** Mức độ tác động chiến lược rất cao. Họ cung cấp ngân sách, định hướng phát triển, kỳ vọng hệ thống giảm chi phí nhân sự vận hành và nâng cao chỉ số việc làm của sinh viên sau khi tốt nghiệp. Tần suất giao tiếp là hàng tháng thông qua kênh báo cáo Dashboard trực quan và họp Review Demo trực tiếp.


**Nhóm Sinh viên (Người đặt lịch):** Mức độ tác động rất cao vì họ là người dùng cuối trực tiếp tạo ra tương tác. Kỳ vọng luồng đặt lịch tối giản, tìm được đúng Mentor phù hợp với mục tiêu sự nghiệp. Tần suất giao tiếp diễn ra liên tục qua thông báo In-app, Email và khảo sát tự động.


**Nhóm Mentor (Người nhận lịch):** Mức độ tác động cao vì họ là nguồn cung tri thức cốt lõi. Kỳ vọng giao diện quản lý lịch trực quan, công cụ lọc các yêu cầu đặt lịch nghiêm túc từ sinh viên để không gây lãng phí thời gian. Tần suất giao tiếp khi có tính năng mới hoặc có yêu cầu đặt lịch mới qua Email và thông báo In-app.


**Nhóm Doanh nghiệp (Đối tác chiến lược):** Mức độ tác động cao. Họ cung cấp mạng lưới Mentor chuyên gia và tài trợ các chương trình hướng nghiệp. Kỳ vọng có công cụ quản lý danh sách Mentor của công ty, xem báo cáo tổng hợp về chất lượng tương tác với sinh viên để làm thương hiệu nhà tuyển dụng. Tần suất giao tiếp định kỳ hàng tháng qua email báo cáo và họp điều phối quý.


**Nhóm Admin / Hệ thống (Người quản trị):** Mức độ tác động trung bình. Vai trò giám sát hệ thống, phân quyền và trích xuất báo cáo dữ liệu tổng hợp. Kỳ vọng giao diện quản trị (CMS) mạnh mẽ. Tần suất giao tiếp diễn ra hàng ngày thông qua các buổi họp nội bộ với đội ngũ phát triển.

## **4. Business Scope and Capabilities (Phạm vi & Năng lực phục vụ)**
### **4.1. Phân định phạm vi hệ thống**

**Nằm trong phạm vi (In-Scope của MVP):** Phát triển nền tảng Web-responsive chạy tốt trên cả PC và Mobile browser. Bao gồm các phân hệ: Quản lý tài khoản riêng biệt (Sinh viên/Mentor/Doanh nghiệp/Admin); Cấu hình lịch trống của Mentor; Đặt và duyệt lịch tư vấn; Đồng bộ lịch Google/Outlook; Tích hợp API tạo link phòng họp tự động Google Meet/Zoom; Hệ thống thông báo nhắc lịch đa kênh; Quản lý lưu trữ Biên bản tư vấn sau buổi gặp.


**Nằm ngoài phạm vi (Out-of-Scope của MVP):** Không phát triển ứng dụng di động cài đặt (Native App); Không tích hợp cổng thanh toán trực tuyến trong giai đoạn hỗ trợ sinh viên; Không tự xây dựng hệ thống Video Call riêng; Không phát triển thuật toán AI tự động gợi ý Mentor nâng cao.

### **4.2. Năng lực & Tính năng cốt lõi (Core Capabilities)**

**Phân hệ Quản lý hồ sơ & Lịch trống:**


Sinh viên tạo hồ sơ cá nhân bao gồm: Trường, Ngành học, Năm học, Định hướng nghề nghiệp, CV và các kỹ năng cần cải thiện.


Mentor thiết lập hồ sơ chuyên gia, gắn nhãn Doanh nghiệp quản lý, cấu hình các khung giờ sẵn sàng (Availability timeslots - mặc định 45-60 phút/slot).


Doanh nghiệp có chuyên trang hồ sơ công ty, hiển thị danh sách tất cả Mentor thuộc biên chế quản lý của doanh nghiệp mình và quản lý trạng thái hoạt động của họ.


**Phân hệ Đặt lịch & Phê duyệt:** Sinh viên lọc tìm kiếm Mentor theo Doanh nghiệp hoặc chuyên môn, chọn slot trống và điền mục tiêu buổi gặp (Câu hỏi cụ thể, tài liệu đính kèm). Mentor nhận yêu cầu và bấm Chấp nhận hoặc Từ chối kèm lý do.


**Phân hệ Thông báo & Tích hợp:** Hệ thống tự động sinh link phòng họp trực tuyến ngay khi lịch được phê duyệt, tự đồng bộ vào Calendar cá nhân của các bên và kích hoạt luồng gửi Email/Push Notification nhắc lịch trước **24 giờ** và **2 giờ**.


**Phân hệ Hậu tư vấn (Post-session):** Sinh viên điền Biên bản tư vấn (Meeting Minutes) và các hành động cần làm (Action items). Mentor đánh giá mức độ chuẩn bị của Sinh viên; Sinh viên chấm sao đánh giá chất lượng hỗ trợ của Mentor. Doanh nghiệp có thể xem tổng hợp báo cáo đánh giá này của đội ngũ chuyên gia thuộc công ty mình.

## **5. Business Rules (Quy tắc nghiệp vụ)**
### **5.1. Quy tắc Khóa/Mở lịch trống (Availability Rules)**

**Quy tắc Tạm khóa (Pending Lock):** Ngay khi một Sinh viên nhấn nút gửi yêu cầu đặt lịch vào một slot của Mentor, slot đó lập tức chuyển sang trạng thái "Tạm khóa" đối với tất cả các Sinh viên khác nhằm chống trùng lịch hoàn toàn.

**Quy tắc Tự động mở (Auto-unlock):** Nếu Mentor không thực hiện phản hồi trong vòng **24 giờ** kể từ thời điểm yêu cầu được gửi đi, hệ thống tự động hủy yêu cầu, giải phóng slot thời gian trở lại trạng thái trống và gửi thông báo gợi ý Sinh viên chọn Mentor khác.

### **5.2. Quy tắc Hủy/Đổi lịch (Cancellation & Reschedule)**

**Thời hạn bắt buộc (Deadline):** Việc thực hiện hủy lịch hoặc dời lịch tư vấn bắt buộc phải thực hiện trên hệ thống trước thời điểm diễn ra buổi hẹn tối thiểu **12 giờ**. Dưới 12 giờ, tính năng tự hủy/đổi trên giao diện sẽ bị khóa, người dùng buộc phải liên hệ Admin trường/hệ thống để xử lý khẩn cấp.
### **5.3. Quy tắc xử lý Vắng mặt & Chế tài (No-show & 3-Strike Rule)**
**Định nghĩa Vắng mặt (No-show):** Tham gia vào phòng họp muộn quá **15 phút** so với giờ bắt đầu mà không có thông báo trước cho bên còn lại qua hệ thống.

**Chế tài cho Sinh viên (3-Strike Rule):** Vi phạm lần 1 hệ thống gửi email cảnh báo. Vi phạm lần 2 Sinh viên bị giới hạn chỉ được đặt tối đa 1 buổi/tuần trong vòng 30 ngày tiếp theo. Vi phạm lần 3 trong vòng một học kỳ, tài khoản Sinh viên sẽ bị tự động khóa quyền đặt lịch trong **14 ngày**, mọi lịch đang chờ duyệt bị hệ thống xóa bỏ.
### **5.4. Quy tắc Phân quyền & Bảo mật Biên bản tư vấn (Data Access Rules)**
**Sinh viên (Chủ sở hữu lịch):** Có quyền Xem và Chỉnh sửa Biên bản tư vấn và danh sách hành động (Action items) của mình.

**Mentor (Người tư vấn):** Có quyền Xem và Thêm nhận xét vào Biên bản tư vấn của đúng buổi hẹn mình phụ trách. Không xem được dữ liệu của các Mentor khác.

**Doanh nghiệp (Đơn vị quản lý Mentor):** Được quyền Xem báo cáo tổng hợp số lượng buổi và điểm đánh giá (Rating) trung bình của các Mentor thuộc công ty mình. Không được xem nội dung chi tiết biên bản tư vấn cá nhân của Sinh viên trừ khi có sự đồng ý chia sẻ của Sinh viên để bảo mật.

**Admin:** Có quyền Xem (Read-only) toàn bộ nội dung phục vụ kiểm soát chất lượng chuyên môn và kết nối học đường.
## **6. Constraints and Assumptions (Ràng buộc & Giả định)**
### **6.1. Ràng buộc (Constraints)**
**Ràng buộc Kỹ thuật & Nền tảng:** Hệ thống vận hành hoàn toàn trên nền tảng Web-responsive. Việc kết nối với API bên thứ ba (Google Calendar, Outlook, Google Meet, Zoom) bị giới hạn bởi các hạn mức (Rate-limit) theo chính sách của nhà cung cấp dịch vụ.

**Ràng buộc Bảo mật cuộc họp:** Mặc định tắt hoàn toàn tính năng tự động ghi âm/ghi hình để bảo vệ thông tin riêng tư của Sinh viên và Mentor. Các tài liệu đính kèm khi tải lên phải được lưu trữ dưới dạng đường dẫn mã hóa có thời hạn (Signed URL) và tự động hết hạn truy cập sau **7 ngày**.

**Ràng buộc Thời gian & Ngân sách:** Phiên bản MVP phải hoàn thành kiểm thử (UAT) và chính thức Go-live trong vòng **8 tuần** với nguồn ngân sách giới hạn từ phía nhà trường/tổ chức.
### **6.2. Giả định (Assumptions)**
Giả định rằng 100% Sinh viên sử dụng email sinh viên do nhà trường cấp hoặc Gmail cá nhân cố định; Mentor sử dụng email doanh nghiệp hoặc email công việc chính thức.

Giả định rằng Doanh nghiệp phối hợp đôn đốc các Mentor thuộc tổ chức của mình chủ động thiết lập, cập nhật khung giờ rảnh trên hệ thống ít nhất 1 lần mỗi tháng.

Giả định rằng người dùng bật quyền nhận thông báo Push Notification trên trình duyệt Web để không bị lỡ lịch hẹn.
## **7. Risks and Issues (Rủi ro & Vấn đề cần giải quyết)**
Các nguy cơ tiềm ẩn trong vận hành nghiệp vụ/kỹ thuật và giải pháp ứng phó cụ thể:

**Rủi ro 1: Mentor quên lịch hoặc vắng mặt đột xuất do lịch công tác khẩn cấp tại Doanh nghiệp.** Mức độ ảnh hưởng là Cao. Phương án xử lý là hệ thống thiết lập luồng gửi SMS/Zalo nhắc lịch trước 2 giờ yêu cầu Mentor xác nhận. Nếu Mentor vắng mặt sau 15 phút, hệ thống tự động hủy lịch và cấp cho Sinh viên một "Vé ưu tiên" (Priority Ticket) để đặt lại lịch khác và được đưa lên đầu hàng đợi phê duyệt.

**Rủi ro 2: Lỗi đồng bộ API gây trùng lịch cá nhân bên ngoài của Mentor.** Mức độ ảnh hưởng là Trung bình. Phương án xử lý là xây dựng cơ chế tự động thử lại (Auto-retry) khi gọi API lỗi. Hệ thống tự động gửi mail yêu cầu Mentor xác thực lại kết nối (Re-auth) nếu Token Calendar cá nhân hết hạn, đồng thời cung cấp tính năng khóa slot thủ công nhanh trên Web của Mentor.

**Rủi ro 3: Sinh viên chia sẻ link phòng họp hướng nghiệp ra bên ngoài cho người lạ vào phá hoại.** Mức độ ảnh hưởng là Cao. Phương án xử lý là cấu hình API phòng họp luôn bật tính năng "Phòng chờ" (Waiting Room), chỉ cho phép các tài khoản email sinh viên/chuyên gia có trong thư mời được tự động vào thẳng phòng. Mentor có toàn quyền loại bỏ tài khoản lạ ra khỏi cuộc họp ngay lập tức.

**Rủi ro 4: Doanh nghiệp không duy trì được số lượng Mentor hoạt động tích cực, dẫn đến khan hiếm lịch trống.** Mức độ ảnh hưởng là Trung bình. Phương án xử lý là thiết kế Admin Dashboard dành riêng cho Doanh nghiệp giúp họ thấy biểu đồ đóng góp của nhân sự công ty mình. Hệ thống tự động gửi báo cáo vinh danh hàng tháng cho Doanh nghiệp để làm truyền thông thương hiệu (Employer Branding), tạo động lực duy trì nguồn cung Mentor.

