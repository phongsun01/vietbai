# Kiểm tra nhất quán

**Mục đích:** Bảo đảm bài không tự mâu thuẫn khi nhiều module cùng áp dụng. Chạy sau cùng, khi đã có bản hoàn chỉnh.

---

## Thứ tự ưu tiên khi hai module nói khác nhau

```
1. Yêu cầu rõ ràng của người dùng (giọng, độ dài, kênh)
2. Module có ghi "ngoại lệ" hoặc "chỉ cho" đúng tình huống đó
   (vd: rhythm.md §1.1, emphasis.md ngoại lệ debunk, facebook.md)
3. Quy tắc chung trong review/ (punctuation, capitalization, natural, anti-ai)
4. Hướng dẫn kỹ thuật viết trong editorial/
```

Nguyên tắc: quy tắc chung là mặc định, ngoại lệ có điều kiện thì thắng trong đúng điều kiện đó. `publishing/` chỉ quyết định cách trình bày theo kênh, không đổi nội dung.

Ví dụ: `natural.md` cho đoạn 1-6 câu. `rhythm.md` §1.1 cho phép đoạn 8-12 câu khi có chuỗi bằng chứng liền mạch. Khi bài thuộc tình huống đó thì theo `rhythm.md`.

Nếu vẫn không phân định được, chọn cách an toàn hơn (theo `review/`) và nói rõ cho người dùng.

---

## 4 tiêu chí kiểm tra

### 1. Mâu thuẫn quy tắc

Module A bảo làm X, module B bảo không làm X. Với mỗi quy tắc đã áp dụng, hỏi: có module nào đang dùng nói ngược lại không? Xử lý theo thứ tự ưu tiên ở trên.

### 2. Ưu tiên không rõ

Hai module cùng bàn một việc mà không biết nghe ai. Xử lý như trên, ghi chú lựa chọn nếu có ảnh hưởng đến bài.

### 3. Khoảng trống

Yêu cầu không khớp module nào. Dùng bộ mặc định cho bài kể chuyện (`story-core` + `hook-close` + `rhythm`), hoặc `technical` nếu là tài liệu kỹ thuật. Có thể đề xuất bổ sung module mới (xem `development/upgrade.md`).

### 4. Tham chiếu hỏng

Mọi tên file `.md` được nhắc trong module đang dùng phải tồn tại trong skill. Nếu không, sửa tham chiếu hoặc báo lỗi.

---

## Checklist

- [ ] Không vi phạm `punctuation.md`?
- [ ] Không vi phạm `natural.md`?
- [ ] Ngoại lệ đã dùng có đúng điều kiện của nó?
- [ ] Giọng văn nhất quán từ đầu đến cuối (không nhảy giữa thân mật và trang trọng)?
- [ ] Thuật ngữ nhất quán (một khái niệm, một cách gọi)?
- [ ] Số liệu, tên riêng, ngày tháng khớp nhau giữa các đoạn?
