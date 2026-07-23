---
name: youtube_summarizer_learning_plan
description: Triggers when the user wants to generate a learning plan and roadmap from a YouTube video link (Tạo kế hoạch học).
---

# YouTube Video Summarizer - Learning Plan & Roadmap

Khi người dùng muốn xây dựng kế hoạch học tập từ một video, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Xây dựng chương trình học tự chọn:
   - **Tóm tắt nội dung video**
   - **Kiến thức cần biết trước (Prerequisites)**
   - **Đánh giá độ khó (Difficulty Level)**
   - **Lộ trình học tập (Roadmap)**
   - **Gợi ý bài tập thực hành**
   - **Đề xuất dự án thực tế để luyện tập**
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/ke_hoach_hoc_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
