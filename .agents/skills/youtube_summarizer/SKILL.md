---
name: youtube_video_summarizer
description: Triggers when the user provides a YouTube video link and requests a summary or analysis.
---

# YouTube Video Summarizer Skill

Khi người dùng cung cấp một đường dẫn video YouTube (chứa `youtube.com` hoặc `youtu.be`) để tóm tắt hoặc phân tích, hãy thực hiện theo các bước sau:

## Quy trình thực hiện

1. **Thu thập thông tin:**
   - Sử dụng công cụ tìm kiếm web hoặc duyệt web để tìm kiếm tiêu đề video, nội dung chi tiết, transcript (phần dịch tả văn bản) hoặc các bản tóm tắt có sẵn của video đó từ mã ID video.
   
2. **Phân tích và Tổng hợp:**
   - Đóng vai trò là một chuyên gia phân tích nội dung chuyên sâu.
   - Trích xuất các ý chính, cấu trúc lập luận và thông điệp mà tác giả muốn truyền tải.

3. **Cấu trúc bản tóm tắt:**
   - **Chủ đề chính:** Trình bày ngắn gọn chủ đề cốt lõi của video.
   - **5–10 ý quan trọng nhất:** Liệt kê rõ ràng, đánh số thứ tự kèm diễn giải ngắn gọn, súc tích.
   - **Kết luận của video:** Tóm tắt thông điệp cuối cùng hoặc cái kết của video.
   - **Những điều người xem nên ghi nhớ:** Các bài học thực tế, hành động cụ thể hoặc lưu ý quan trọng rút ra từ video.

4. **Yêu cầu về ngôn ngữ và trình bày:**
   - Sử dụng **tiếng Việt**, súc tích, mạch lạc, dễ đọc.
   - Sử dụng định dạng Markdown rõ ràng, in đậm các từ khóa quan trọng và sử dụng các biểu tượng biểu cảm (emoji) phù hợp để tăng tính trực quan.

5. **Lưu trữ kết quả:**
   - Tạo một tệp Markdown trong thư mục workspace với tên tệp chuẩn hóa từ tiêu đề video (ví dụ: `tom_tat_the_math_of_winning.md`).
   - **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
     ```markdown
     ## 🔗 Nguồn
     - Link video: <link_video_youtube_da_nhap>
     ```
   - Trả lời người dùng kèm liên kết dẫn đến tệp đã tạo.
