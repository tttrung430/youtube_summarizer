---
name: youtube_summarizer_technical_engineer
description: Triggers when the user wants a comprehensive technical knowledge document from a YouTube video link (Technical Knowledge Engineer).
---

# YouTube Video Summarizer - Technical Knowledge Engineer

Mẫu prompt nâng cao dành cho các chủ đề kỹ thuật chuyên sâu (như Docker, Kubernetes, GenAI, Android, Go, Nexus Repository...).

Khi người dùng yêu cầu phân tích nâng cao, đóng vai trò là một **Technical Knowledge Engineer** và thực hiện:

1. Thu thập nội dung/transcript của video.
2. Biên soạn tài liệu chi tiết đầy đủ gồm các thành phần:
   - **Executive Summary:** Tóm tắt khái quát (200–300 từ).
   - **Tóm tắt từng phần của video** theo mốc thời gian/chủ đề.
   - **Giải thích các khái niệm quan trọng.**
   - **Bảng kê toàn bộ:** Thuật ngữ (Terminology), Công nghệ (Technology), Framework, API, Công cụ (Tools).
   - **Chi tiết từng khái niệm:** Định nghĩa, Khi nào sử dụng, Ví dụ thực tế, Best Practices.
   - **Trích xuất:** Checklist, Quy trình (Workflows), Sơ đồ luồng (Flows), Kiến trúc (Architecture), Mẹo hữu ích.
   - **Bảng so sánh** nếu có nhiều công nghệ đối lập.
   - **Lưu ý & Sai lầm thường gặp.**
   - **Đề xuất:** Tài liệu học tiếp, Video nên xem thêm, Dự án thực hành.
   - **Các phần bổ trợ cuối trang:**
     - **Key Takeaways**
     - **Flashcards (Q&A)**
     - **Interview Questions** (Câu hỏi phỏng vấn gợi ý)
     - **Mind Map** dạng văn bản
     - **Todo List** hành động tiếp theo
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/tai_lieu_ky_thuat_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
