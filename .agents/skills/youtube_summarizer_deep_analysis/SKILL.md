---
name: youtube_summarizer_deep_analysis
description: Triggers when the user wants a critical deep analysis of a YouTube video link (Phân tích sâu).
---

# YouTube Video Summarizer - Deep Analysis Mode

Khi người dùng yêu cầu phân tích sâu một video, hãy thực hiện:

1. Thu thập nội dung/transcript của video.
2. Tránh việc chỉ tóm tắt đơn thuần. Hãy tiến hành phân tích đa chiều:
   - **Ý tưởng chính (Core Idea)**
   - **Vì sao tác giả đưa ra quan điểm này (Rationale)**
   - **Những giả định ngầm (Assumptions)**
   - **Điểm mạnh (Strengths)**
   - **Điểm yếu (Weaknesses)**
   - **Điều còn thiếu/chưa nói hết (Gaps)**
   - **Phương án áp dụng vào thực tế**
   - Chỉ ra các thông tin chưa chính xác hoặc đã lỗi thời (nếu có).
3. Lưu kết quả ra file `.md` trong thư mục có tên theo định dạng ngày hiện tại `dd-MM-yyyy` (ví dụ: `23-07-2026/phan_tich_sau_<ten_video>.md`).
4. Trả lời người dùng kèm link của file đó.
