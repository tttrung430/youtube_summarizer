---
name: youtube_summarizer_markdown
description: Triggers when the user wants a full structured Markdown document from a YouTube video link (Chuyển thành tài liệu Markdown).
---

# YouTube Video Summarizer - Markdown Document Generator

Khi người dùng muốn chuyển đổi transcript thành tài liệu Markdown hoàn chỉnh, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tạo tài liệu Markdown có cấu trúc phân tầng (`# Tiêu đề`, `## Mục 1`, `### Ví dụ`).
3. Làm giàu tài liệu bằng cách tích hợp thêm (nếu phù hợp):
   - Bảng biểu (Tables)
   - Checklist
   - Hộp lưu ý/cảnh báo
   - Code blocks (nếu có đoạn mã)
4. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/tai_lieu_markdown_<ten_video>.md`).
5. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
6. Trả lời người dùng kèm link của file đó.
