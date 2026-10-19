---
name: viet-chuyen-nghiep
description: Viết, biên tập và rà soát văn bản tiếng Việt chuyên nghiệp. Dùng khi người dùng nhờ viết bài (blog, bài đăng Facebook, bình luận, phản bác bài viral, tài liệu kỹ thuật), sửa hoặc "làm cho tự nhiên hơn" một bản nháp tiếng Việt, kiểm tra dấu câu, viết hoa, dấu vết văn AI, hoặc viết theo phong cách một bài mẫu.
---

# Viết chuyên nghiệp 3.2

Skill này là một bộ module độc lập. Bạn đọc file này, chọn đúng module cho yêu cầu, viết, tự rà soát bằng checklist, rồi giao bài. Không có tầng quản lý trung gian: mỗi module là một bộ quy tắc, đọc module nào cần module đó.

## Việc nhỏ thì làm thẳng

Caption vài dòng, sửa một đoạn, trả lời nhanh: đọc `review/punctuation.md` và `review/natural.md`, viết, trả kết quả. Không cần lập quy trình.

## Quy trình cho bài hoàn chỉnh

1. **Hiểu yêu cầu.** Xác định: người dùng đã có gì (bản nháp, dữ liệu thô, ý tưởng, chỉ có chủ đề), mục đích (truyền cảm hứng, giải thích, hướng dẫn, phản bác), độc giả, kênh đăng, bài có số liệu hoặc claim quan trọng không. Nếu thiếu thông tin quyết định đến bài (độc giả, kênh, trải nghiệm thật của người viết), hỏi ngắn gọn trước khi viết.
2. **Chọn module** theo bảng bên dưới.
3. **Viết.** Bài dài hơn khoảng 1.000 từ thì lập dàn ý trước (insight, chuỗi logic, hook, kết), rồi viết từng phần.
4. **Rà soát** theo mục "Rà soát" bên dưới. Sửa rồi mới giao.
5. **Giao bài** kèm vài dòng nói rõ: đã dùng giả định nào, chỗ nào còn `[cần điền: ...]`, claim nào chưa kiểm chứng được.

## Bảng chọn module

| Yêu cầu | Đọc |
|---------|-----|
| Bài cảm xúc, blog, kể chuyện | `editorial/story-core.md`, `hook-close.md`, `rhythm.md` (bộ mặc định). Thêm `metaphor.md`, `reframe.md`, `emphasis.md` khi cần |
| Phản bác, debunk, bình luận lên bài khác | bộ mặc định + `editorial/debunk.md` + `emphasis.md`; **bắt buộc** `review/fact-check.md` |
| Tài liệu kỹ thuật, giáo trình | `editorial/technical.md` (thay cho story-core và rhythm, không dùng chung) |
| Thiếu thông tin về chủ đề | `research/research.md` trước khi viết |
| Có dữ liệu thô cần rút insight | `research/analysis.md` trước khi viết |
| Đăng Facebook (mọi loại: cá nhân, Page, Group) | `publishing/facebook.md` sau khi viết xong |
| Người dùng đưa bản nháp để sửa | bỏ qua bước viết, đi thẳng vào "Rà soát". Giữ giọng và ý của họ |
| "Viết theo style bài này", phân tích bài mẫu | `development/style-audit.md` |
| Cải tiến skill từ bài mẫu | `development/upgrade.md`, `development/research-framework.md` |
| Tìm kỹ thuật phù hợp cho một dạng bài | `archive/pattern-catalog.md` |

Không có giới hạn cứng về số dòng đọc mỗi lượt, nhưng chỉ đọc module phục vụ yêu cầu, đừng đọc cả bộ.

## Rà soát

Chạy theo thứ tự:

1. `review/punctuation.md`, `capitalization.md`, `natural.md`, `anti-ai.md`: kiểm bằng checklist cuối mỗi file.
2. `review/fact-check.md`: khi bài có số liệu, trích dẫn, claim mạnh, nội dung pháp lý, y tế, tài chính, và luôn luôn với bài debunk. Đưa bảng kết quả kiểm chứng cho người dùng.
3. `review/consistency.md`: chạy cuối cùng trên bản hoàn chỉnh.

Có lỗi thì sửa rồi rà lại. Sau tối đa 2 vòng sửa mà vẫn còn lỗi không giải quyết được, giao bài và nói thẳng điều gì còn tồn tại.

## Quy tắc không thương lượng

- **Không bịa dữ kiện.** Số liệu, tên người, tên công ty, trích dẫn, anecdote, trải nghiệm cá nhân phải đến từ người dùng hoặc từ nguồn đã kiểm. Thiếu thì hỏi hoặc để `[cần điền: ...]`.
- **Không viết "mình đã đối chiếu / kiểm chứng" khi chưa làm.**
- **Giữ nguyên ý và giọng của người dùng** khi biên tập bài của họ. Chỉ đề xuất, không tự thay đổi quan điểm.
- Mọi ví dụ trong các module chỉ để minh họa nhịp và cấu trúc, không chép nguyên văn vào bài.

## Cấu trúc thư mục

```
research/     research.md, analysis.md
editorial/    story-core, hook-close, rhythm, metaphor, reframe, debunk, emphasis, technical
review/       punctuation, capitalization, natural, anti-ai, fact-check, consistency
publishing/   facebook.md
archive/      pattern-catalog.md
development/  upgrade, style-audit, research-framework, research-results
```

**Phiên bản:** 3.2 (2026-10-19). Lịch sử thay đổi: `development/upgrade.md`.
