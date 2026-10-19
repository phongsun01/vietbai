# Viết kỹ thuật và học thuật

**Mục đích:** Tạo tài liệu kỹ thuật, giáo trình, whitepaper với cấu trúc chặt chẽ và giọng văn uy tín. Dùng thay cho `story-core` + `rhythm`, không dùng chung với chúng.

---

## Nguyên Tắc

**Technical Academic = Clarity × Structure × Authority**

- **Clarity:** Mỗi câu, mỗi đoạn có mục đích rõ ràng
- **Structure:** Logic chặt chẽ, dễ scan và tra cứu
- **Authority:** Khách quan, chuyên môn, đáng tin cậy

---

## 1. Đoạn văn

### Topic Sentence

Câu đầu tiên = ý chính. Các câu sau: phát triển, minh chứng.

```
✅ "Hệ thống giải quyết vấn đề này bằng nhật ký công việc, tức bằng chứng
    mà tác tử tạo ra trong quá trình thực hiện nhiệm vụ."
❌ "Tác tử chụp ảnh. Nó ghi video. Log lưu chi tiết. Đây là nhật ký công việc."
```

### Độ dài biến thiên

Đoạn 2-6 câu, xen kẽ ngắn dài. Tránh pattern lặp (3-3-3-3).

```
[Đoạn 2 câu — Mở đề]
[Đoạn 5 câu — Giải thích chi tiết]
[Đoạn 3 câu — Ví dụ]
[Đoạn 1 câu — Chuyển tiếp]
[Đoạn 4 câu — Kết luận mở rộng]
```

---

## 2. Dòng chảy logic

### Kết nối giữa các đoạn

Mỗi đoạn kết nối tự nhiên qua:
- **Từ nối:** Tuy nhiên, Do đó, Hơn nữa, Ngược lại (đa dạng, không lặp một từ nối quá 3 lần/bài, xem `anti-ai.md`)
- **Tham chiếu:** "Điều này...", "Vấn đề trên...", "Cơ chế này..."
- **Logic progression:** Problem → Solution, General → Specific, Theory → Practice

---

## 3. Hạn chế Bullet Points

**Văn xuôi > Bullet points** trong thân văn giải thích.

```
❌ Knowledge có đặc điểm:
  - Tự động học
  - Lưu trữ dài hạn

✅ Knowledge tương đương kinh nghiệm làm việc thực tế. Đây là loại tri thức
   được tích lũy dần qua tương tác, giống cách nhân viên mới "học lỏm."
```

**Bullet CHỈ dùng cho:** Specs kỹ thuật, checklist, commands, so sánh.

---

## 4. Heading

- **H1 sách:** `# 3.1 Tên bài` — viết hoa chữ đầu
- **H2+:** Chỉ viết hoa chữ đầu
- **Format:** Noun phrase, không phải câu hỏi

```
✅ Phương pháp thiết kế Workflow
❌ Làm thế nào để thiết kế Workflow?
```

---

## 5. Giọng văn

Khách quan, chuyên môn nhưng không khô khan, rõ ràng nhưng không đơn giản hóa quá mức.

→ Quy tắc chống dấu vết AI và chống trộn tiếng Anh: xem `review/anti-ai.md` và `review/natural.md`

---

## Workflow

1. **Lập dàn ý logic:** General → Specific, Theory → Practice
2. **Viết câu chủ đề:** Mỗi section có câu chủ đề
3. **Phát triển đoạn văn:** 1-3 câu supporting per topic sentence
4. **Rà soát và gọt lại:** Kiểm tra flow, từ nối, độ dài biến thiên

---

## Checklist

- [ ] Mỗi đoạn có topic sentence rõ ràng?
- [ ] Đoạn văn độ dài biến thiên (không đều nhau)?
- [ ] Các đoạn kết nối qua từ nối/tham chiếu?
- [ ] Heading là noun phrase?
- [ ] Bullet points chỉ cho specs, steps, comparisons?
- [ ] Giọng văn chuyên môn, khách quan?
- [ ] Không bịa đặt tên người/công ty/thời gian cụ thể?
