# BÁO CÁO BÀI TẬP: NHẬN DIỆN VÀ SỬA KẾ HOẠCH SPRINT REVIEW

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1 - Rà kế hoạch

Dưới đây là bảng phân tích chi tiết các điểm chưa phù hợp trong kế hoạch Sprint Review hiện tại, đối chiếu với các quy tắc Scrum chuẩn và phương án sửa đổi để biến buổi họp thành không gian trao đổi hai chiều:

- Kế hoạch hiện tại đang mắc bẫy coi Sprint Review là buổi báo cáo tiến độ thay vì kiểm tra và thích ứng sản phẩm.
- Product Owner không được phép nói thay cho Developers hoặc giấu giếm dữ liệu chưa hoàn thành.
- Việc demo cần bám sát hành trình người dùng thực tế trên môi trường thử nghiệm.

| Mã | Phù hợp / Chưa phù hợp | Quy tắc làm căn cứ | Cách sửa ngắn gọn |
| --- | --- | --- | --- |
| K-01 | Phù hợp | QT1 | Giữ nguyên: Product Owner nhắc lại Sprint Goal để mọi người cùng bám sát mục tiêu. |
| K-02 | Chưa phù hợp | QT1 | Sửa: Bỏ phần Product Owner tự báo cáo tiến độ và giải thích lý do bận. Thay bằng thời gian để Scrum Team cùng Stakeholders thảo luận thẳng vào kết quả thực tế. |
| K-03 | Chưa phù hợp | QT2 | Sửa: Chỉ chiếu và demo PBI-41 (Tra cứu trên web) là Increment đã Done. User Journey demo: Nhân viên cửa hàng mở trình duyệt, nhập mã đơn hàng 'DH12345' trên website thử nghiệm để kiểm tra trạng thái và nhận kết quả tức thì. PBI-42 và PBI-44 được tách riêng để thông báo rõ tình trạng chưa Done. |
| K-04 | Chưa phù hợp | QT3 & QT4 | Sửa: Thay thế việc Chủ cửa hàng nghiệm thu toàn bộ bằng không gian trao đổi hai chiều. Đặt câu hỏi mở: 'Anh/chị đánh giá như thế nào về tốc độ phản hồi của tính năng tra cứu đơn hàng trên web?'. Mọi Feedback ghi nhận vào Product Backlog, không hứa hẹn làm ngay. |

## Phần 2 - Trạng thái PBI

Việc minh bạch hóa trạng thái của từng Product Backlog Item (PBI) là cốt lõi để xây dựng lòng tin với Stakeholders trong Scrum. Dưới đây là bảng phân tích trạng thái và các câu thông báo chuẩn xác trong buổi Sprint Review:

- PBI-41 đạt điều kiện Done nhờ vượt qua toàn bộ 60 ca kiểm thử trên môi trường thử nghiệm mà không có lỗi nghiêm trọng.
- PBI-42 và PBI-44 chưa Done cần được thông báo số liệu cụ thể để Stakeholders nắm bắt thực trạng kỹ thuật.

| PBI | Done / Chưa Done | Câu thông báo trong Sprint Review |
| --- | --- | --- |
| PBI-41 | Done | PBI-41 đã hoàn thành việc tra cứu trạng thái đơn trên website, đã chạy thử nghiệm ổn định, vượt 60/60 ca kiểm thử chính và không còn lỗi nghiêm trọng. Mời anh chị trải nghiệm trực tiếp. |
| PBI-42 | Chưa Done | PBI-42 chưa được xem là Done vì tính năng tra cứu trạng thái đơn từ mạng xã hội vẫn còn 8 ca kiểm thử lỗi dịch vụ đơn hàng chưa đạt, đội ngũ đang tiếp tục khắc phục ở Sprint sau. |
| PBI-44 | Chưa Done | PBI-44 chưa được xem là Done vì tính năng nhận diện khiếu nại nghiêm trọng còn 6 ca bị phân loại sai và sót 1 lỗi mức nghiêm trọng cao, nhóm cần thêm thời gian tối ưu mô hình AI. |

## Phần 3 - Xử lý tình huống

Dựa trên các quy tắc nghiệp vụ Agile/Scrum và bẫy dữ liệu của bài toán, đây là phản hồi chi tiết dành cho Product Owner nhằm đảm bảo tính minh bạch và quy trình vận hành đúng đắn:

- Tuyệt đối không giấu giếm dữ liệu hoặc làm sai lệch số liệu kiểm thử để đánh bóng thành tích.
- Không tự ý hứa hẹn thực hiện mọi Feedback ngay lập tức mà phải đưa vào Product Backlog để Product Owner sắp xếp độ ưu tiên.
- Bổ sung mời Trưởng nhóm CSKH tham dự buổi Sprint Review vì góc nhìn của họ rất quan trọng đối với luồng chuyển tiếp hội thoại khi AI gặp khó khăn.

| STT | Nội dung trao đổi với Product Owner | Cơ sở giải thích kỹ thuật |
| --- | --- | --- |
| 1 | Chúng ta không thể giấu 6 ca phân loại sai của PBI-44 để làm đẹp báo cáo. Nếu giữ nguyên K-02 và K-03 theo hướng che giấu, Sprint Review sẽ biến thành buổi diễn kịch thay vì cơ hội thích ứng thực tế. | Đảm bảo tính minh bạch (Transparency) trong Scrum, giúp Stakeholders thấy đúng thực trạng hệ thống AI. |
| 2 | Anh/chị không được tự ý hứa làm ngay mọi Feedback của Chủ cửa hàng trong Sprint tới. Phản hồi này sẽ được ghi nhận và xem xét đưa vào Product Backlog để tinh chỉnh trong các lập kế hoạch sau. | Tuân thủ QT4: Tránh làm quá tải Developers và phá vỡ Sprint Goal đã cam kết. |
| 3 | Buổi họp này bắt buộc phải mời thêm Trưởng nhóm CSKH dù họ chưa có trong danh sách ban đầu. Trưởng nhóm CSKH có góc nhìn thiết thực muốn chuyển hội thoại cho nhân viên sớm khi AI không chắc chắn, rất cần thiết cho việc định hướng tính năng. | Tận dụng đúng góc nhìn liên quan từ các bên liên quan cốt lõi để sản phẩm sát với nhu cầu vận hành thực tế. |

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
