---
name: youtube_summarizer_engineer
description: Triggers when the user wants a technical summary for engineers from a YouTube video link (Tóm tắt dành cho kỹ sư).
---

# YouTube Video Summarizer - Engineering Mode

Khi người dùng yêu cầu tóm tắt một video kỹ thuật dành cho kỹ sư, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Phân tích và biên soạn tài liệu theo cấu trúc:
   - **Giải thích các khái niệm kỹ thuật.**
   - **Tóm tắt quy trình (Workflow/Process).**
   - **Liệt kê công nghệ được nhắc tới.**
   - **So sánh ưu/nhược điểm.**
   - **Đưa ra Best Practices.**
   - **Tạo bảng so sánh các giải pháp.**
   - **Đề xuất tài liệu nên học tiếp.**
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/ky_su_<ten_video>.md`).
4. Trả lời người dùng kèm link của file đó.
