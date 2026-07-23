# Hướng Dẫn Sử Dụng Hệ Thống YouTube Video Summarizer Skills

Hệ thống của bạn đã được cấu hình với **10 Skills chuyên biệt** để phục vụ các nhu cầu tóm tắt và phân tích video YouTube khác nhau. Toàn bộ các bản tóm tắt sau khi hoàn thành sẽ được tự động xuất ra tệp Markdown (`.md`) và lưu trữ khoa học trong thư mục được đặt tên theo định dạng ngày hiện tại `dd-MM-yyyy`.

---

## 🛠️ Danh Sách 10 Skills & Cách Kích Hoạt

Dưới đây là bảng tra cứu nhanh cách kích hoạt từng Skill. Bạn chỉ cần nhập **Đường dẫn video YouTube** kèm theo các **Từ khóa kích hoạt** tương ứng:

| STT | Tên Skill | Mục đích sử dụng | Từ khóa kích hoạt gợi ý | File đầu ra mẫu |
| :--- | :--- | :--- | :--- | :--- |
| **1** | `youtube_summarizer_overview` | Tóm tắt tổng quan, súc tích | "tóm tắt tổng quan", "ý chính", "chủ đề chính" | `tom_tat_tong_quan_<tên_video>.md` |
| **2** | `youtube_summarizer_notes` | Chuyển thành ghi chú học tập phân cấp | "dạng ghi chú", "notes học tập", "take notes" | `ghi_chu_<tên_video>.md` |
| **3** | `youtube_summarizer_busy` | Tóm tắt siêu nhanh 2 phút (dưới 400 từ) | "cho người bận", "tóm tắt nhanh", "tóm tắt 2 phút" | `tom_tat_nhanh_<tên_video>.md` |
| **4** | `youtube_summarizer_knowledge` | Hệ thống hóa kiến thức từ bài giảng | "trích xuất kiến thức", "bài giảng", "khái niệm định nghĩa" | `kien_thuc_<tên_video>.md` |
| **5** | `youtube_summarizer_markdown` | Biên soạn tài liệu Markdown hoàn chỉnh | "tài liệu markdown", "định dạng md đầy đủ" | `tai_lieu_markdown_<tên_video>.md` |
| **6** | `youtube_summarizer_second_brain` | Ghi chú phong cách Obsidian/Second Brain | "second brain", "obsidian note", "liên kết kiến thức" | `second_brain_<tên_video>.md` |
| **7** | `youtube_summarizer_engineer` | Tóm tắt kỹ thuật & so sánh công nghệ | "cho kỹ sư", "kỹ thuật", "technical summary" | `ky_su_<tên_video>.md` |
| **8** | `youtube_summarizer_deep_analysis` | Phân tích phản biện & đánh giá đa chiều | "phân tích sâu", "phản biện", "deep analysis" | `phan_tich_sau_<tên_video>.md` |
| **9** | `youtube_summarizer_learning_plan` | Lập lộ trình học & đề xuất bài tập | "kế hoạch học", "lộ trình học", "roadmap" | `ke_hoach_hoc_<tên_video>.md` |
| **10** | `youtube_summarizer_technical_engineer` | Tài liệu học thuật chuyên sâu (Docker, K8s, GenAI...) | "technical knowledge engineer", "tài liệu đầy đủ" | `tai_lieu_ky_thuat_<tên_video>.md` |

---

## 🚀 Hướng Dẫn Sử Dụng Chi Tiết (Ví Dụ Thực Tế)

### Bước 1: Copy link video YouTube cần tóm tắt
Ví dụ: `https://youtu.be/abcxyz`

### Bước 2: Gõ câu lệnh kèm từ khóa kích hoạt
Chọn 1 trong các cách viết dưới đây tùy thuộc vào mục đích của bạn:

* **Ví dụ 1 (Tóm tắt nhanh cho người bận):**
  > *"tóm tắt nhanh cho người bận rộn video này https://youtu.be/abcxyz"*
  
* **Ví dụ 2 (Cần nghiên cứu sâu công nghệ):**
  > *"hãy đóng vai trò technical knowledge engineer và tạo tài liệu đầy đủ cho video https://youtu.be/abcxyz"*
  
* **Ví dụ 3 (Lập lộ trình học tập):**
  > *"lập kế hoạch học và lộ trình từ bài giảng này https://youtu.be/abcxyz"*

### Bước 3: Nhận kết quả và mở file
Sau khi chạy xong, tôi sẽ:
1. Hiển thị nội dung tóm tắt trực tiếp trên màn hình chat.
2. Tự động tạo thư mục ngày hôm nay (ví dụ: `23-07-2026/`) trong thư mục làm việc của bạn.
3. Gửi cho bạn đường link trực tiếp (ví dụ: `[tom_tat_nhanh_abc.md](file:///...)`) để bạn bấm mở xem hoặc chỉnh sửa lại.

---

## 📂 Cấu Trúc Thư Mục Lưu Trữ

Kết quả lưu trữ trong thư mục làm việc sẽ có cấu trúc như sau:

```text
Summarize Videos/
├── .agents/
│   └── skills/                  # Chứa cấu hình của 10 Skills
├── 23-07-2026/                  # Thư mục tự động tạo theo ngày
│   ├── tom_tat_nhanh_video_A.md
│   └── tai_lieu_ky_thuat_video_B.md
└── HUONG_DAN_SU_DUNG.md         # File hướng dẫn này
```

*Chúc bạn học tập và làm việc hiệu quả với trợ lý tóm tắt video!*
