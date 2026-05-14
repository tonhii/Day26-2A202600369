---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** — cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng. Sau bước này, nhóm có "khung xương" của slide deck.

Lý do làm bước này: nhảy thẳng từ log sang slide deck dễ bị bỏ sót mục. Bảng so sánh ép nhóm trả lời từng mục cho cả 2 sản phẩm song song — phát hiện ngay nếu mục nào còn thiếu bằng chứng.

Quy tắc: mỗi ô của bảng dài tối đa 2 câu. Nếu ô nào để trống → quay lại `1-research-notes.md` đào thêm trước khi sang Bước 3.

## Quy trình 5 phút

```text
3 phút  — Điền bảng so sánh 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô nào còn thiếu bằng chứng
1 phút  — Quyết định: cần test thêm hay đủ để sang slide?
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính (chat / form / canvas / IDE)</sup> | Giao diện thanh tìm kiếm tích hợp kho 200M bài báo học thuật. Ý định: Tìm hiểu tổng quan rộng. Surface chính: Search / Table. | Giao diện sổ tay cá nhân yêu cầu tải PDF. Ý định: Đọc sâu và tổng hợp tài liệu cá nhân. Surface chính: Chat / Notebook. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính (số click, tab, copy-paste, load mental)</sup> | Trước: Không setup. Trong: Cần credit để trích xuất dữ liệu thêm vào bảng. Sau: Export CSV/RIS. Nhẹ physical nhưng nặng mental load. | Trước: Tự tìm và tải 3-5 PDF (friction rất lớn). Trong: Chat với text streaming. Sau: Lưu Note / nghe Audio Overview. Nặng physical load lúc đầu. |
| **S3 — Output & Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control cho người dùng</sup> | Tóm tắt nhanh và tạo bảng trích xuất chi tiết. Dẫn nguồn chuẩn (có DOI), disclaimer yêu cầu kiểm tra bài gốc. | Đoạn văn tự nhiên, dẫn nguồn [1] nhảy đúng dòng text trong PDF. Grounded 100% trên nguồn cấp, độ tin cậy tuyệt đối. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + định vị Cost-Capability-Speed (rẻ-nhanh hay mạnh-đắt)</sup> | Bản Free giới hạn credit, trừ nhanh khi thêm cột. Định vị: Mạnh-đắt. | Hoàn toàn miễn phí, không giới hạn rõ ràng. Định vị: Rẻ-nhanh. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng: Strong / Promising / Weak / At Risk + lý do</sup> | Promising — Tính năng Data Extraction Table đột phá nhưng rào cản credit làm hẹp tệp người dùng lười trả phí. | Strong — Tính năng Audio Overview ấn tượng và khả năng loại bỏ hoàn toàn hallucination nhờ grounding tuyệt đối. |

---

## Phần B — Đối chiếu 3 friction areas (nén từ Lens 3)

Đây là cột trụ của mục S2 trong slide deck. Mỗi friction area trả lời 1 câu so sánh:

- **Physical load** (số click / tab / lần copy-paste): Elicit nhẹ nhàng (chỉ cần gõ tìm), trong khi NotebookLM cực kỳ nặng lúc đầu (phải tự tìm và tải file PDF thủ công).
- **Cognitive burden** (cần học prompt engineering / có hint sẵn / có nhớ ngữ cảnh giữa lượt chat):
  - Elicit yêu cầu tư duy học thuật cao để phân tích bảng số liệu, còn NotebookLM giảm tải rất tốt với hành văn tự nhiên và các bong bóng gợi ý câu hỏi liên quan.
- **User workarounds** (nhóm phải tự làm gì để bù yếu điểm — vd: prompt lại 3 lần, copy sang công cụ khác):
  - Với Elicit, người dùng hạn chế "thử sai" sợ tốn credit; với NotebookLM, người dùng tự làm khâu tìm kiếm bài báo bên ngoài (Google Scholar) rồi mới đưa vào tool.

---

## Phần C — Đối chiếu 6 trust signals (nén cho mục S3)

Đánh dấu mỗi sản phẩm có / không / một phần:

| Tín hiệu đáng tin | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung | Có (DOI, link trích dẫn uy tín) | Có (highlight đúng dòng trong PDF tải lên) |
| 2. Disclaimer khi không chắc ("không tìm được", "có thể sai") | Có (cảnh báo đọc bài gốc) | Có ("có thể hiển thị thông tin không chính xác") |
| 3. Fallback / dừng lại khi out-of-scope | Có (nếu không tìm ra trong kho báo) | Có (chỉ trả lời dựa trên nội dung PDF) |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | Một phần (bài báo giống nhưng summary có thể khác) | Có (rất nhất quán vì dựa trên nguồn cố định) |
| 5. User control — sửa lại, dừng, regenerate, undo | Có (thêm/xóa cột, filter) | Có (tùy chỉnh chọn nguồn PDF cụ thể) |
| 6. Explanation — giải thích "tại sao AI nói thế" (nếu có) | Một phần (dựa vào câu văn trong bài báo) | Có (click nguồn [1] để đọc bối cảnh gốc) |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed (cho mục S4)

Mỗi sản phẩm chọn **1** trong 3 góc tam giác (vẽ hình tay nếu cần — sẽ dán vào slide S4):

- **Sản phẩm A nghiêng về**: mạnh-đắt — lý do 1 câu: Khả năng trích xuất dữ liệu qua bảng (Data Extraction Table) cực mạnh, giải quyết pain-point học thuật nhưng credit tiêu hao nhanh.
- **Sản phẩm B nghiêng về**: rẻ-nhanh — lý do 1 câu: Hoàn toàn miễn phí và tốc độ tổng hợp thông tin, tạo Audio Overview cực nhanh sau khi có nguồn.

---

## Phần E — Verdict sơ bộ (cho mục S5.1)

Đặt verdict 1 dòng cho mỗi sản phẩm (sẽ tinh chỉnh lại ở Bước 3 sau khi vận dụng 4 Lens + Spark/Loop/System):

- **Sản phẩm A (Elicit) — verdict sơ bộ**: Promising
  - Lý do 1 câu: Giải quyết trúng pain-point của giới học thuật với tính năng tự động trích xuất bảng dữ liệu, tuy nhiên paywall hạn chế khả năng scale với sinh viên.
- **Sản phẩm B (NotebookLM) — verdict sơ bộ**: Strong
  - Lý do 1 câu: Đột phá với Audio Overview và tính grounding tuyệt đối trên nguồn tài liệu cá nhân, đánh tan nỗi lo hallucination cho công việc đọc sâu.

---

## Bảng kiểm trước khi sang Bước 3

- [x] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [x] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [x] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [x] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [x] Còn ô nào thiếu bằng chứng → đã đánh dấu để Phase 3 đào thêm.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ (với S5 mở rộng 8 sub-mục) trước khi build slide.