---
name: youtube_summarizer_knowledge
description: Triggers when the user wants to extract structured knowledge from a lecture YouTube video link (Trích xuất kiến thức).
---

# YouTube Video Summarizer - Knowledge Extraction

Khi người dùng yêu cầu trích xuất toàn bộ kiến thức từ video bài giảng, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tổ chức lại toàn bộ nội dung thành một tài liệu học tập theo cấu trúc:
   - **Khái niệm**
   - **Định nghĩa**
   - **Ví dụ**
   - **Công thức (nếu có)**
   - **Best Practices**
   - **Những lỗi thường gặp**
   *Lưu ý: Không kể lại nội dung video, hãy hệ thống hóa lại cấu trúc.*
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/kien_thuc_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
