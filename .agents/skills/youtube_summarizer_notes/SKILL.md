---
name: youtube_summarizer_notes
description: Triggers when the user wants study notes from a YouTube video link (Tóm tắt theo dạng ghi chú).
---

# YouTube Video Summarizer - Study Notes

Khi người dùng yêu cầu tóm tắt video dưới dạng ghi chú (Notes), hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Chuyển thành ghi chú học tập theo cấu trúc:
   - Chia thành các heading (`#`, `##`, `###`)
   - Sử dụng bullet point cho từng ý
   - Giữ nguyên các thuật ngữ quan trọng
   - Không bỏ sót ý chính
   - Có phần "Key Takeaways" ở cuối
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/ghi_chu_<ten_video>.md`).
4. **BẮT BUỘC:** Thêm phần nguồn ở cuối tệp dưới dạng:
   ```markdown
   ## 🔗 Nguồn
   - Link video: <link_video_youtube_da_nhap>
   ```
5. Trả lời người dùng kèm link của file đó.
