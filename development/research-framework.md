# Nghiên Cứu Phong Cách Viết — Framework Thực Thi

**Mục đích:** Quy trình chuẩn hóa để thu thập, phân tích, và tích hợp phong cách viết từ báo chí vào skill.

---

## Hướng Dẫn Sử Dụng

```
Mỗi phiên làm việc:
1. Đọc file này để nắm quy trình
2. Đọc `research-results.md` để biết đã làm đến đâu
3. Chọn 3-5 bài tiếp theo chưa phân tích (xem nguồn gợi ý cuối file)
4. Đọc bài → Điền bảng phân tích → Ghi kết quả vào research-results.md
5. Sau mỗi batch: cập nhật bảng tổng hợp pattern ở cuối file
```

---

## Bước 1: Chọn Bài

Từ danh sách nguồn, chọn bài đạt **3/4 tiêu chí**:

- ✅ Có lập luận (không phải tin thuần túy)
- ✅ Tương tác cao (nhiều comment/share)
- ✅ Đại diện thể loại (phóng sự, bình luận, phân tích...)
- ✅ Viết tốt (cấu trúc rõ, kết ấn tượng)

---

## Bước 2: Phân Tích (Template)

Copy template sau cho MỖI bài:

```markdown
### [Tên bài] — [Nguồn]

**URL:** [link]
**Thể loại:** [phóng sự / bình luận / phân tích / tiểu luận / giải thích / tin tức]
**Lĩnh vực:** [tổng hợp / pháp luật / kinh tế / giáo dục / KHCN / sức khỏe / xã hội / văn hóa]

#### Staged Assessment
- L1 Phong cách đặc biệt: [Có/Không]
- L2 Kỹ thuật nghệ thuật: [Có/Một phần/Không]
- L3 Tầng nghĩa ẩn: [Có/Không]
- L4 Mức độ phức tạp: [Cao/Trung bình/Thấp]

#### Cấu trúc
- **Hook:** [Loại hook + trích dẫn câu đầu]
- **Chuyển tiếp:** [Từ nối đặc trưng]
- **Nhịp đoạn:** [Mô tả pattern biến thiên]
- **Kết bài:** [Loại closing + trích dẫn]

#### Kỹ thuật phát hiện
| Kỹ thuật | Evidence (trích dẫn) | Đã có trong skill? |
|----------|---------------------|-------------------|
| [tên] | "[trích]" | Có/Không |

#### Style DNA
- Đặc điểm 1: [tên] — "[evidence]"
- Đặc điểm 2: [tên] — "[evidence]"

#### Kết luận
- Pattern mới cần bổ sung: [có/không] → [mô tả]
- Bài mẫu đáng lưu: [có/không]
```

---

## Bước 3: Tổng Hợp Pattern (Cuối Mỗi Batch)

Sau khi phân tích xong 3-5 bài, cập nhật bảng tổng hợp:

```markdown
## Bảng Tổng Hợp Pattern

| # | Pattern | Phát hiện từ | Thể loại | Đã có trong skill? | Đề xuất |
|---|---------|-------------|----------|-------------------|---------|
| 1 | [tên] | [bài nào] | [thể loại] | [Có/Không] | [thêm vào file nào] |
```

---

## Bước 4: Tích Hợp Vào Skill (Sau Khi Đủ Data)

Khi đã phân tích đủ ~20 bài trở lên:

```
1. Đọc bảng tổng hợp pattern
2. Lọc pattern mới (chưa có trong skill)
3. Phân loại: thuộc nhóm nào? (`editorial/`, `review/`, `research/`)
4. Viết theo định dạng module (mục đích + quy tắc + checklist)
5. Cập nhật bảng định tuyến trong `SKILL.md` nếu thêm module mới
6. Ghi changelog vào `upgrade.md`
```

---

## Nguồn gợi ý (không theo dõi trạng thái ở đây)

Trạng thái phân tích ghi trong `research-results.md`, không ghi trong danh sách này.

- **Tổng hợp, pháp luật, kinh tế:** VnExpress Ý kiến, Tuổi Trẻ (phóng sự, Cuối tuần), Báo Pháp Luật, CafeF, VnEconomy
- **Giáo dục, khoa học công nghệ, sức khỏe, xã hội:** Dân Trí, Tia Sáng, Sức Khỏe & Đời Sống, Lao Động, Người Lao Động, VietnamNet, Giáo dục & Thời đại
- **Văn hóa, quốc tế, nội dung hiện đại:** Nhân Dân Cuối Tuần, Thế Giới & Việt Nam, BBC Vietnamese, Vietcetera, Spiderum
- **Quốc tế:** The Atlantic, The Economist, HBR, Wired, Paul Graham, Morgan Housel
