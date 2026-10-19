# Nâng cấp skill

**Mục đích:** Phân tích bài đã viết hoặc bài mẫu bên ngoài, rút pattern mới và đề xuất bổ sung vào đúng module.

**Nguyên tắc:** chỉ phân tích và đề xuất. Chỉ sửa file skill sau khi người dùng duyệt đề xuất.

---

## Khi nào dùng

- Người dùng đưa bài mẫu: "phân tích bài này để cải tiến skill", "viết theo style bài này".
- Sau một bài phức tạp đã được người dùng duyệt, nếu thấy kỹ thuật lặp lại mà skill chưa ghi.
- Cần rà soát kích thước và độ trùng lặp của các module.

---

## Quy trình

1. **Phân tích bài.** Dùng `development/style-audit.md` (đánh giá sơ bộ, cấu trúc, nội dung cốt lõi, style DNA). Với bài bên ngoài, đếm số câu mỗi đoạn và ghi lý do nếu có đoạn siêu dài. Với bài của chính skill, chạy thêm phần self-check dấu hiệu AI. Xuất báo cáo cho người dùng.
2. **So sánh với skill hiện có.** Với mỗi kỹ thuật hoặc lỗi phát hiện, tìm trong `editorial/`, `review/` và `archive/pattern-catalog.md` xem đã có chưa.
3. **Đề xuất.** Với điều mới, nêu rõ file đích (`editorial/rhythm.md`, `review/natural.md`, v.v.) và viết sẵn nội dung theo định dạng bên dưới. Trình người dùng duyệt.
4. **Thực hiện.** Sau khi duyệt, sửa file đích, thêm một dòng vào changelog, cập nhật bảng định tuyến trong `SKILL.md` nếu thêm hoặc bỏ module, và kiểm tra các tham chiếu `.md` còn trỏ đúng.

---

## Định dạng bổ sung

### Kỹ thuật mới (vào `editorial/`)

Đủ 5 thành phần:

```
## Kỹ thuật N: [Tên] ([Tên tiếng Anh nếu cần])

**Mô tả:** [1-2 câu]

**Công thức:**
[Cấu trúc từng bước]

**Ví dụ:**
[Ví dụ cụ thể từ bài thật]

**Cấm:**
[Anti-pattern, điều cần tránh]
```

### Quy tắc mới (vào `review/`)

```
### [Tên quy tắc]

| Sai | Đúng |
|-----|------|
| `[ví dụ sai]` | `[ví dụ đúng]` |
```

Ví dụ trong module phải tuân thủ chính các quy tắc của skill (không em-dash, không trộn tiếng Anh).

### Giới hạn kích thước

- Mỗi module không quá **300 dòng**. Sắp vượt thì tách file.
- Không giới hạn tổng số dòng đọc mỗi lượt, nhưng chỉ đọc module cần cho yêu cầu.
- File dưới 30 dòng mà nội dung trùng với file khác thì cân nhắc gộp.

---

## Changelog

| Ngày | File | Thay đổi |
|------|------|----------|
| 2026-02-26 | các module cũ | Thêm 6 kỹ thuật nâng cao, quy tắc Oxford comma (bài AI và Gen Z) |
| 2026-03-08 | các module cũ | Thêm Structured Debunking, Strategic Caps, Vernacular Translation (bài phản bác Anthropic) |
| 2026-03-08 | toàn bộ | Refactor v3.0, kiến trúc "tòa soạn" |
| 2026-03-09 | `editorial/`, `review/` | Thêm Self-Proof, Concept System, Delayed Reveal, đoạn siêu dài, ngoại lệ CAPS cho debunk, trích dẫn tiếng Anh, ngoại lệ bio (3 bài của tác giả) |
| 2026-03-09 | `SKILL.md` | v3.1: 4 mô hình luồng, quy tắc GATE |
| 2026-10-19 | toàn bộ | **v3.2:** bỏ mô hình TBT/lead/staff, SKILL.md thành điểm vào duy nhất; bỏ giới hạn 200 dòng/lượt; Facebook chỉ còn một định dạng (cá nhân), bỏ Page/Group; sửa tham chiếu cũ (`meta/`, `quality/`, `style/`, V1/V3, Q1-Q4); sửa ví dụ vi phạm luật của skill; cấm bịa dữ kiện, fact-check bắt buộc với debunk; thêm quy tắc số, ngày, văn bản pháp luật; đồng bộ lại số liệu README |
