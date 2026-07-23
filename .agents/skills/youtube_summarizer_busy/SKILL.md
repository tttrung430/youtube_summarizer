---
name: youtube_summarizer_busy
description: Triggers when the user wants a quick 2-minute summary of a YouTube video link (Tóm tắt dành cho người bận).
---

# YouTube Video Summarizer - Busy Mode (2-Minute Summary)

Khi người dùng yêu cầu tóm tắt siêu nhanh/cho người bận, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tạo bản tóm tắt súc tích tối đa 400 từ, có thể đọc trong vòng 2 phút:
   - **Video nói về gì**
   - **Các ý quan trọng**
   - **Điều mới đáng học**
   - **Kết luận**
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/tom_tat_nhanh_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
