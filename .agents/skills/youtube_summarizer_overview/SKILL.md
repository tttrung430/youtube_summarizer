---
name: youtube_summarizer_overview
description: Triggers when the user wants a general overview summary of a YouTube video link (Tóm tắt tổng quan).
---

# YouTube Video Summarizer - General Overview

Khi người dùng yêu cầu tóm tắt tổng quan một video YouTube bằng cách cung cấp link hoặc kích hoạt skill này, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tạo bản tóm tắt theo cấu trúc sau:
   - **Chủ đề chính**
   - **5–10 ý quan trọng nhất**
   - **Kết luận của video**
   - **Những điều người xem nên ghi nhớ**
3. Viết bằng tiếng Việt, súc tích, dễ đọc.
4. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/tom_tat_tong_quan_<ten_video>.md`).
5. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
6. Trả lời người dùng kèm link của file đó.
