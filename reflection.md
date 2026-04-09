# Individual reflection — Tạ Vĩnh Phúc (2A202600424)

## 1. Role
Team leader, UX/UI Designer, Front-end Developer, Prompt Engineer và DEMO Presenter.

## 2. Đóng góp cụ thể
- **Thiết kế UI/UX:** Sử dụng kỹ năng prompt trên nền tảng Stitch để thiết kế và lên ý tưởng cho giao diện người dùng.
- **Prompt Engineering:** Trực tiếp đóng góp và xây dựng system prompt để định hình hành vi và câu trả lời cho tính năng AI của dự án.
- **Nghiên cứu giải pháp:** Đóng góp solution, tìm hiểu và đề xuất sử dụng và tích hợp model Wit.ai để xử lý bài toán Speech-to-Text để tối ưu giữa chất lượng output và chi phí.
- **Phát triển Front-end:** Trực tiếp dev + vibe code phần Front-end cho ứng dụng (codebase tại `front-end/src`).
- **Tích hợp hệ thống:** Integrate Front-end với API Back-end do các thành viên khác trong nhóm phụ trách, xử lý trơn tru các luồng call API.
- **Pitching / Demo:** Chịu trách nhiệm trực tiếp chuẩn bị kịch bản và thuyết trình phần demo sản phẩm.

## 3. SPEC mạnh/yếu
- **Mạnh nhất:** Giao diện trực quan, thân thiện do được prompt kỹ càng qua Stitch. Giải pháp dùng model Wit.ai hoạt động khá hiệu quả cho tác vụ nhận dạng giọng nói trong yêu cầu của dự án.
- **Yếu nhất:** Cần thêm thời gian để tối ưu mượt mà hơn quá trình giao tiếp bất đồng bộ giữa Front-end, Back-end và tốc độ phản hồi của AI.

## 4. Đóng góp khác
- Hỗ trợ debug các vấn đề tích hợp (CORS, format dữ liệu API) để đảm bảo flow từ lúc người dùng nói (Speech-to-text) tới lúc hiển thị kết quả hoạt động thông suốt.
- Prompt chỉnh CSS/giao diện kỹ càng để bản demo trở nên hoàn thiện và bóng bẩy hơn.

## 5. Điều học được
- Học được quy trình tích hợp một dịch vụ AI (Wit.ai) vào trong một ứng dụng web thực tế.
- Tích lũy kinh nghiệm làm việc team: cách thống nhất chuẩn giao tiếp API với người làm Back-end và debug hiệu quả khi ghép nối; quản lý và phân chia công việc hợp lý trong team.
- Khám phá cách tận dụng các công cụ AI generation (như Stitch) để tăng tốc xây dựng UI/UX.

## 6. Nếu làm lại
- Sẽ thống nhất API contract (cấu trúc dữ liệu trả về) với team Back-end sớm và chi tiết hơn nữa để tiết kiệm thời gian integrate.
- Có thể test thêm các model Speech-to-Text khác (như Whisper, Google Speech) song song với Wit.ai để so sánh ưu điểm/tốc độ.

## 7. AI giúp gì / AI sai gì
- **Giúp:** Nền tảng Stitch (AI) giúp generate các component UI cực nhanh, làm khung vững chắc để đắp logic. Dùng AI (Gemini Pro) hỗ trợ brainstorm và tối ưu system prompt tiết kiệm nhiều công sức. Dùng Google AI Studio để chuyển đổi UI thành interactable code. Dùng Antigravity để dev và vibe code.
- **Sai/mislead:** Code AI tạo ra đôi khi chưa bao hàm được các state management phức tạp khi gọi API, phải tự can thiệp thủ công nhiều ở thư mục `front-end/src` để web app có luồng dữ liệu trơn tru chứ không chỉ là giao diện tĩnh. Đôi khi AI chưa gen ra được các screen UI theo đúng yêu cầu về bố cục, màu sắc,... nên phải cần prompt thật kỹ và chỉnh sửa thủ công.
