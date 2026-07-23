---
name: youtube_summarizer_second_brain
description: Triggers when the user wants to create an Obsidian-style Second Brain note from a YouTube video link (Tạo Second Brain).
---

# YouTube Video Summarizer - Obsidian Second Brain Note

Khi người dùng muốn tạo ghi chú theo phong cách Obsidian/Second Brain, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tạo tệp ghi chú có các trường dữ liệu tiêu chuẩn:
   - **Title** (Tiêu đề)
   - **Summary** (Tóm tắt nhanh)
   - **Concepts** (Các khái niệm cốt lõi)
   - **Examples** (Ví dụ minh họa)
   - **Key Insights** (Những phát hiện/bài học đắt giá)
   - **Action Items** (Hành động có thể thực hiện)
   - **Related Topics** (Các chủ đề liên quan để liên kết ghi chú)
   - **Tags** (Nhãn dạng `#tag-name`)
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/second_brain_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
