---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để biết khung giờ chính xác)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — file trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu: trong 20 phút thử nghiệm, 2 thành viên cùng test 2 sản phẩm AI với 1 nhiệm vụ chung. File này ghi lại **quan sát thật** (không phải đánh giá tổng kết) — sẽ làm nền cho bảng so sánh ở bước 2.

Lý do làm bước này: slide deck Lab 2 chỉ có sức nặng khi mỗi nhận định dựa trên quan sát cụ thể có ảnh chụp + tên model + thời gian + câu prompt cụ thể. Nếu chỉ "thấy A tốt hơn B" mà không có log → không phòng thủ được khi giảng viên cold-call.

Quy tắc: **không có ảnh chụp / log = không có quan sát**. Mỗi quan sát phải có ảnh tham chiếu hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + câu prompt + tài khoản dùng)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + ghi log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + ghi log
2 phút   — First impressions: ghi 3 quan sát nổi nhất cho mỗi sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên thống nhất các thông số chung. Câu prompt phải **giống y nhau** cho cả 2 sản phẩm — nếu khác sẽ không so sánh được.

- **Nhiệm vụ chung** (1 câu mô tả): Tìm kiếm bằng chứng khoa học đánh giá tác động của việc thiếu ngủ đến kết quả học tập của sinh viên đại học.
- **Câu prompt chính xác** (paste y nguyên ở đây — sẽ dán giống vào cả 2 sản phẩm): "Does sleep deprivation negatively affect academic performance in university students?"
- **Loại tài khoản dùng**:
  - Sản phẩm A: Elicit - Tài khoản Free (giới hạn credit)
  - Sản phẩm B: NotebookLM - Tài khoản Google miễn phí
- **Trình duyệt + thời gian test** (để dễ tham chiếu ảnh sau này): Chrome, Tháng 5/2026

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Elicit
**URL**: https://elicit.com
**Model dưới mui xe** (nếu hiển thị): Các model LLM tinh chỉnh riêng cho trích xuất dữ liệu khoa học

### B.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Giao diện tìm kiếm dạng thanh dài. Có nút chọn nguồn "Source: Research papers". Góc trái có các luồng làm việc như Research agent, Report. Góc phải có thông tin tài khoản và nút Upgrade.
- Có hint / sample prompt sẵn không? Có sẵn mục "Suggested prompts" ở ngay dưới ô tìm kiếm (ví dụ: "How does sleep deprivation affect immune response?").
- Cần đăng nhập / paywall trước khi dùng không? Có, bắt buộc đăng nhập để thấy màn hình này (Góc phải trên cùng hiện tên tài khoản và nút Upgrade báo hiệu đây là bản Free).
- Ảnh đã chụp: `screenshots/product-A-1-entry.png`

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~5-10 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Có progress bar / skeleton loading báo hiệu đang tổng hợp từ các bài báo.
- Output dài bao nhiêu (số câu / dòng / từ)? Tóm tắt (Summary) khoảng 4-5 câu ở trên, bên dưới là bảng (Table) liệt kê chi tiết 4-8 bài báo top đầu.
- Output có dẫn nguồn không? Có, trích dẫn chuẩn xác bằng các bài báo học thuật thực tế (có link DOI, số lượt trích dẫn).
- Có hiển thị disclaimer / cảnh báo không (vd: "có thể sai", "kiểm tra lại")? Cảnh báo định dạng học thuật yêu cầu người dùng đọc kỹ bài báo gốc.
- Ảnh đã chụp: `screenshots/product-A-2-input-1.png`, `screenshots/product-A-2-input-2.png` + `screenshots/product-A-3-output.png`

### B.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có thể tải thêm bài báo (Show more papers).
- Có nút copy / export ra format khác không? Có, export ra file CSV, RIS (cho Zotero/Mendeley).
- Có gợi ý câu hỏi tiếp theo không? Không nổi bật, UI tập trung vào việc lọc (filter) hoặc thêm cột (add columns).
- Có lưu lịch sử để truy lại không? Có, lưu trong Library/Notebook của user.
- Có thumb up / thumb down để feedback không? Có.

### B.4 — Quan sát nổi (3 quan sát)

1. [Physical load nhẹ nhưng Cognitive mạnh]: Elicit tự động tìm bài báo trên kho 200 triệu bài của nó, người dùng không cần nạp dữ liệu. Nhưng bảng trích xuất yêu cầu tư duy học thuật để đọc hiểu.
2. [Data Extraction Table]: Tính năng thêm cột (vd: "Sample size", "Outcomes") cực kỳ ấn tượng, AI tự động quét ngang qua các bài báo để điền số liệu vào bảng. (Xem ảnh `product-A-4-source-1.png` và `product-A-4-source-2.png`).
3. [Credit limit]: Bản Free trừ credit khá nhanh với mỗi lần thêm cột hoặc tìm kiếm sâu, tạo cảm giác "ngại thử sai" (Friction về mental load do sợ tốn tiền).

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: NotebookLM
**URL**: https://notebooklm.google.com
**Model dưới mui xe** (nếu hiển thị): Gemini 1.5 Pro

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Giao diện dạng "Sổ tay" (Notebook). Màn hình trống yêu cầu "Add sources" (Tải nguồn lên).
- Có hint / sample prompt sẵn không? Không có hint ban đầu, phải chờ upload xong tài liệu mới có gợi ý.
- Cần đăng nhập / paywall trước khi dùng không? Cần tài khoản Google, hoàn toàn miễn phí.
- Ảnh đã chụp: `screenshots/product-B-1-entry.jpg`

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~3-5 giây (rất nhanh sau khi tài liệu đã được nạp xong).
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Chữ hiện ra theo dạng streaming.
- Output dài bao nhiêu (số câu / dòng / từ)? Khoảng 2-3 đoạn văn (100-200 từ), hành văn tự nhiên dễ đọc.
- Output có dẫn nguồn không? Có, dẫn nguồn dạng số [1], [2], bấm vào sẽ highlight đúng đoạn text trong file PDF gốc mình đã tải lên (Source-grounding).
- Có hiển thị disclaimer / cảnh báo không? Cảnh báo chuẩn của Google "NotebookLM có thể hiển thị thông tin không chính xác".
- Ảnh đã chụp: `screenshots/product-B-2-input.jpg` + `screenshots/product-B-3-output.jpg`

### C.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Không có nút regenerate trực tiếp, người dùng phải gõ lại prompt.
- Có nút copy / export ra format khác không? Có thể lưu câu trả lời thành 1 Note (ghi chú) đính kèm trong sổ tay.
- Có gợi ý câu hỏi tiếp theo không? Có, luôn có 3-4 bong bóng gợi ý câu hỏi bám sát ngữ cảnh ở dưới cùng.
- Có lưu lịch sử để truy lại không? Có, mọi thứ chat lưu trong luồng chung của Notebook.
- Có thumb up / thumb down để feedback không? Có.

### C.4 — Quan sát nổi (3 quan sát)

1. [Friction vật lý rất lớn lúc đầu]: NotebookLM KHÔNG tự lên mạng tìm bài báo khoa học. Nhóm phải TỰ TÌM 3-5 file PDF về chủ đề "mất ngủ ở sinh viên đại học", tải về máy rồi upload lên NotebookLM mới bắt đầu hỏi được.
2. [Độ tin cậy tuyệt đối dựa trên nguồn]: Vì nó chỉ trả lời dựa trên PDF mình tải lên, nên độ tin cậy rất cao, loại bỏ hoàn toàn hallucination ngoài luồng. Trích dẫn bấm vào là nhảy tới đúng trang PDF.
3. [Audio Overview]: Tính năng chuyển đổi các PDF nghiên cứu thành 1 buổi podcast thảo luận giữa 2 AI host cực kỳ ấn tượng, hữu ích cho việc "nghe" tóm tắt nghiên cứu khi đang di chuyển.

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
   - Elicit mang lại trải nghiệm "zero-setup" tốt hơn: vào là gõ tìm được ngay nhờ kho 200M bài báo tích hợp sẵn. NotebookLM yêu cầu thao tác chuẩn bị dữ liệu (tải PDF lên) rất mất thời gian ban đầu, tạo rào cản lớn cho người dùng mới lười tìm tài liệu.

2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
   - Phụ thuộc vào workflow: NotebookLM đáng tin tuyệt đối 100% *đối với dữ liệu mình cung cấp* (grounded on user's sources). Elicit đáng tin ở mức *tổng quan học thuật rộng* vì nó quét tài liệu mà mình chưa biết tới, nhưng đôi khi summary bị nén quá mức khiến mất ngữ cảnh sâu.

3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
   - Làm thế nào để đảm bảo Elicit lọc ra các bài báo chất lượng cao (top-tier journals) chứ không phải các bài báo trôi nổi thiếu uy tín?
   - Giới hạn tải lên của NotebookLM là bao nhiêu file PDF, và xử lý một cuốn sách giáo khoa dài hàng nghìn trang liệu nó có bị "quên" chi tiết không?

> Đây là first impressions — chưa phải nhận định. Khi sang `2-comparison-table.md` sẽ đối chiếu chéo với số liệu cụ thể.

---

## Bảng kiểm trước khi sang Bước 2

- [ ] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [ ] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
- [ ] Mỗi quan sát có ảnh / log tham chiếu.
- [ ] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
- [ ] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.