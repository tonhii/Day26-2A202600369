---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

Mục tiêu: dựng outline đầy đủ cho slide deck Analysis Report ngay trong file markdown — viết hết nội dung 5 mục ở đây trước, sau đó copy sang slide (pptx / Keynote / Google Slides). Không build slide trước khi outline xong.

Lý do làm bước này: dựng thẳng slide từ log dễ bị thiếu mục hoặc bị "đẹp ngoài rỗng trong". Outline markdown ép nhóm trả lời từng câu hỏi trước khi nghĩ về thiết kế slide. Khi giảng viên / nhóm khác hỏi "vì sao bạn xếp Sản phẩm A là Promising?" — câu trả lời đã có sẵn trong outline.

Quy tắc: mỗi nhận định trong outline phải nối được về bằng chứng cụ thể (ảnh / log / số liệu công khai). Nếu một sub-mục để trống → quay lại `1-research-notes.md` đào thêm trước khi sang slide.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để có context
8 phút  — Điền outline 5 mục (S1 → S5)
4 phút  — Riêng cho S5: mở rộng 8 sub-mục (S5.1 → S5.8)
1 phút  — Đối chiếu bảng kiểm trước khi build slide
```

> Sau 15 phút outline + đối chiếu, mới mở pptx / Google Slides / Keynote và copy nội dung sang. Slide deck export thành `analysis-report.pdf` ở cùng folder này.

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: 2A202600369 (Hồ Thị Tố Nhi) + 2A202600432 (Trần Thị Kim Ngân)
- **Ngành chọn**: D — Nghiên cứu
- **Nhiệm vụ chung đã test**: Tìm kiếm bằng chứng khoa học đánh giá tác động của việc thiếu ngủ đến kết quả học tập của sinh viên đại học.
- **Sản phẩm A** (tên + URL): Elicit (https://elicit.com)
- **Sản phẩm B** (tên + URL): NotebookLM (https://notebooklm.google.com)
- **Câu prompt chính xác đã dùng**: "Does sleep deprivation negatively affect academic performance in university students?"

---

## S1 — Product Moment (slide 1-2)

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, điểm gặp đầu (entry point).

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| Tên + URL | Elicit (https://elicit.com) | NotebookLM (https://notebooklm.google.com) |
| Entry point (trang đầu nhìn thấy gì) | Giao diện thanh tìm kiếm có gợi ý, kèm các luồng Research agent/Report. | Giao diện sổ tay trống yêu cầu "Add sources" (Tải nguồn lên). |
| Ý định người dùng (vào để làm gì) | Tìm hiểu tổng quan rộng từ kho báo học thuật. | Đọc sâu và tổng hợp tài liệu cá nhân đã chọn lọc. |
| Surface chính (chat / form / canvas / IDE / khác) | Search / Table (bảng trích xuất). | Chat / Notebook. |
| Có cần đăng nhập / paywall ngay không | Có, bắt buộc đăng nhập. Paywall (hết credit) cho tính năng sâu. | Cần đăng nhập Google. Hoàn toàn miễn phí. |

### S1.2 — Bằng chứng (ảnh tham chiếu)

- `screenshots/product-A-1-entry.png` — Giao diện tìm kiếm trực quan có sẵn "Suggested prompts" nhưng yêu cầu đăng nhập trước khi sử dụng.
- `screenshots/product-B-1-entry.jpg` — Giao diện sổ tay trống, yêu cầu người dùng phải chủ động tải lên các nguồn tài liệu (PDF) trước khi có thể hỏi đáp.

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Elicit tạo first impression (ấn tượng đầu) tốt hơn cho nhu cầu tìm kiếm nhanh (zero-setup) nhờ kho 200 triệu bài báo có sẵn. Trong khi đó, NotebookLM tạo rào cản lớn hơn ở lần gặp đầu do yêu cầu chuẩn bị tài liệu (tải PDF lên), nhưng điều này phù hợp với ý định đọc sâu cá nhân hóa của tool.

---

## S2 — Workflow Evidence (slide 3-4)

Mục đích: hiển thị luồng người dùng + 3 friction areas (Lens 3).

### S2.1 — Luồng người dùng (trước / trong / sau khi dùng AI)

```text
TRƯỚC khi gặp AI:
- Sinh viên/nhà nghiên cứu cần tìm tài liệu và tổng hợp số liệu về tác động của mất ngủ lên học tập.

TRONG khi dùng Sản phẩm A (Elicit):
1. Gõ prompt vào thanh tìm kiếm.
2. AI quét qua kho 200M bài báo và trả về danh sách kèm tóm tắt.
3. Người dùng thêm các cột (vd: Sample size) để trích xuất dữ liệu, AI trừ credit dần.

TRONG khi dùng Sản phẩm B (NotebookLM):
1. Tự tìm và tải 3-5 bài báo PDF về máy.
2. Upload file PDF vào sổ tay NotebookLM.
3. Gõ prompt hỏi đáp, AI trả lời dạng text streaming kèm nguồn trích dẫn [1].

SAU khi dùng AI:
- Đọc tổng hợp, chép trích dẫn vào báo cáo, xuất bảng dữ liệu CSV (Elicit), hoặc lưu Note / nghe Audio Overview (NotebookLM) khi di chuyển.
```

### S2.2 — 3 Friction Areas (Lens 3)

| Friction | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| **Physical load** (số click, tab, copy-paste) | Rất nhẹ nhàng (chỉ cần gõ tìm). | Cực kỳ nặng lúc đầu (phải tự tìm và tải file PDF thủ công). |
| **Cognitive burden** (cần học prompt eng. / nhớ ngữ cảnh giữa lượt chat) | Yêu cầu tư duy học thuật cao để phân tích bảng số liệu. | Giảm tải rất tốt với hành văn tự nhiên và các bong bóng gợi ý câu hỏi liên quan. |
| **User workarounds** (nhóm phải tự làm gì để bù yếu điểm) | Hạn chế "thử sai" thêm cột do sợ tốn credit. | Phải tự làm khâu tìm kiếm bài báo bên ngoài (Google Scholar) rồi đưa vào tool. |

### S2.3 — Bằng chứng

- `screenshots/product-A-2-input-1.png`, `screenshots/product-A-2-input-2.png` + `screenshots/product-A-3-output.png`
- `screenshots/product-B-2-input.jpg` + `screenshots/product-B-3-output.jpg`

### S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn? Tại sao? (3-4 câu)

Elicit giảm physical load ban đầu cực tốt nhờ kho dữ liệu 200 triệu bài báo tích hợp sẵn, người dùng không cần setup. Tuy nhiên, NotebookLM lại giải quyết cognitive burden (tải nhận thức) trong quá trình đọc hiểu xuất sắc hơn nhờ khả năng diễn giải mạch lạc, đưa ra các câu hỏi gợi ý thông minh và tính năng Audio Overview, giúp bù đắp hoàn toàn cho điểm yếu về việc phải tải file PDF thủ công ban đầu.

---

## S3 — Output & Trust (slide 5-6)

Mục đích: đánh giá chất lượng output + 6 tín hiệu đáng tin.

### S3.1 — Chất lượng output

Cho mỗi sản phẩm, trả lời 3 câu:

- **Sản phẩm A (Elicit)**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, tổng hợp dựa trên 4-8 bài báo top đầu.
  - Output có **bịa thông tin** không (hallucination)? Rất thấp vì dựa trên bài báo thật, nhưng đôi khi summary bị nén quá mức khiến mất ngữ cảnh.
  - Output có **đầy đủ** hay nửa vời? Đầy đủ dưới dạng bảng (Data Extraction Table) nhưng người dùng phải tự đọc hiểu số liệu.
- **Sản phẩm B (NotebookLM)**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, trả lời chính xác dựa trên nội dung PDF đã nạp.
  - Output có **bịa thông tin** không? Không, grounded 100% trên nguồn cấp nên loại trừ hoàn toàn hallucination ngoài luồng.
  - Output có **đầy đủ** hay nửa vời? Đầy đủ và chi tiết dưới góc độ tài liệu người dùng đã cung cấp, hành văn tự nhiên.

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| 1. Dẫn nguồn (citation mở được, đúng nội dung) | Có (DOI, link trích dẫn uy tín) | Có (highlight đúng dòng trong PDF tải lên) |
| 2. Disclaimer khi không chắc | Có (cảnh báo đọc bài gốc) | Có ("có thể hiển thị thông tin không chính xác") |
| 3. Fallback / dừng lại khi out-of-scope | Có (nếu không tìm ra trong kho báo) | Có (chỉ trả lời dựa trên nội dung PDF) |
| 4. Consistency (chạy 2 lần cùng prompt) | Một phần (bài báo giống nhưng summary có thể khác) | Có (rất nhất quán vì dựa trên nguồn cố định) |
| 5. User control (sửa, dừng, regenerate, undo) | Có (thêm/xóa cột, filter) | Có (tùy chỉnh chọn nguồn PDF cụ thể) |
| 6. Explanation (giải thích "vì sao AI nói thế") | Một phần (dựa vào câu văn trong bài báo) | Có (click nguồn [1] để đọc bối cảnh gốc) |

### S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn? Vì sao? (3-4 câu)

NotebookLM tạo trust (niềm tin) mạnh mẽ hơn một cách tuyệt đối nhờ cơ chế source-grounding 100% trên dữ liệu cá nhân, đánh tan nỗi lo hallucination. Elicit dù đáng tin ở mức tổng quan học thuật rộng nhờ trích dẫn chuẩn DOI, nhưng cơ chế quét tự động vẫn đòi hỏi người dùng phải tự cẩn trọng đối chiếu bản gốc để không bỏ sót bối cảnh quan trọng của nghiên cứu.

---

## S4 — Business Signal (slide 7)

Mục đích: định vị 2 sản phẩm trên Cost-Capability-Speed + pricing pattern.

### S4.1 — Định vị tam giác (cho mỗi sản phẩm)

- **Sản phẩm A**: mạnh-đắt — model dưới mui xe: Các LLM tinh chỉnh riêng cho trích xuất học thuật — lý do định vị 1 câu: Khả năng trích xuất dữ liệu qua bảng (Data Extraction Table) cực mạnh, giải quyết pain-point học thuật nhưng credit tiêu hao nhanh.
- **Sản phẩm B**: rẻ-nhanh — model dưới mui xe: Gemini 1.5 Pro — lý do định vị 1 câu: Hoàn toàn miễn phí, tốc độ tổng hợp thông tin và tạo Audio Overview cực nhanh sau khi đã tải nguồn.

### S4.2 — Pricing pattern

| Yếu tố | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| Mô hình giá | Freemium (Dùng credit) | Free |
| Giá entry (free tier giới hạn gì) | Miễn phí với tín dụng hạn chế, trừ khá nhanh khi thêm cột. | Hoàn toàn miễn phí. |
| Giá trả phí (gói chính + giá) | Elicit Plus ($10/tháng, 12,000 credits). | Không có trả phí (nằm trong hệ sinh thái Google). |
| Paywall xuất hiện ở đâu (khi hết quota / tính năng nâng cao / etc.) | Khi yêu cầu trích xuất thông tin chi tiết (Add columns) hoặc hết credit. | Không có paywall trực tiếp. |

### S4.3 — Nhận định: chiến lược kinh doanh của 2 sản phẩm khác nhau thế nào? (2-3 câu)

Elicit nhắm thẳng vào niche học thuật, sử dụng tính năng trích xuất bảng dữ liệu mạnh mẽ để ép người dùng chuyên nghiệp (nhà nghiên cứu, sinh viên) phải nâng cấp (Mạnh-Đắt). Ngược lại, NotebookLM đóng vai trò giữ chân người dùng trong hệ sinh thái Google, cung cấp miễn phí hoàn toàn nhằm hút người dùng đại chúng, tạo thói quen sử dụng AI để đọc sâu thay thế note-taking truyền thống (Rẻ-Nhanh).

---

## S5 — Product Judgment (slide 8-12 — phần đậm nhất)

Mục đích: ra verdict + vận dụng 4 Lens + Spark/Loop/System + Niche/Feature Map + liên hệ Lab 1.

S5 mở rộng thành 8 sub-mục — bắt buộc xong **S5.1, S5.6, S5.7, S5.8**. Nhóm khá phải hoàn thành cả 8 sub-mục. Nhóm Đạt có thể ghi "không có nguồn công khai" cho 1-2 số liệu ở S5.2-S5.5 nhưng phải ghi rõ.

### S5.1 — Verdict (BẮT BUỘC)

Cho mỗi sản phẩm, chọn 1 trong 4: **Strong** / **Promising** / **Weak** / **At Risk**, kèm lý do 1 câu.

- **Sản phẩm A**: Promising — Lý do: Giải quyết trúng pain-point học thuật bằng tính năng Data Extraction Table, nhưng rào cản credit làm hẹp tệp người dùng lười trả phí.
- **Sản phẩm B**: Strong — Lý do: Đột phá với Audio Overview và tính grounding tuyệt đối trên nguồn tài liệu cá nhân, đánh tan nỗi lo hallucination cho công việc đọc sâu.

### S5.2 — User base + tăng trưởng

Số liệu công khai (MAU, DAU, paid users, growth rate) cho cả 2 sản phẩm + nguồn (URL + ngày).

- **Sản phẩm A**: Không có nguồn công khai chính xác số lượng user (ước tính hàng trăm nghìn sinh viên/nhà nghiên cứu).
- **Sản phẩm B**: Không có nguồn công khai tách biệt (được tính gộp trong hệ sinh thái Google/Gemini).

> Nếu không tìm được số liệu công khai, ghi: "Không có nguồn công khai sau khi tra ở [tên 2-3 nguồn]". Không bịa.

### S5.3 — Doanh thu / pricing power

ARR / MRR công khai + pricing strategy (freemium / premium / enterprise).

- **Sản phẩm A**: Không có nguồn công khai ARR/MRR + chiến lược pricing: Freemium chuyển đổi lên Elicit Plus ($10/tháng) và Enterprise.
- **Sản phẩm B**: Không áp dụng doanh thu trực tiếp + chiến lược pricing: Hoàn toàn miễn phí, làm mồi nhử giữ chân người dùng trong hệ sinh thái Google.

### S5.4 — Moat phân tích (5 loại)

Đánh giá 5 loại moat (data / network / switching cost / brand / distribution) cho từng sản phẩm. Mỗi moat đánh dấu: **mạnh** / **trung bình** / **yếu / dễ bị copy**.

| Moat | Sản phẩm A (Elicit) | Sản phẩm B (NotebookLM) |
|---|---|---|
| Data (proprietary data flywheel) | Yếu (Dùng data open access) | Trung bình (Dữ liệu do người dùng tự tải lên) |
| Network effects | Yếu | Yếu |
| Switching cost (chi phí đổi sang sản phẩm khác) | Trung bình (Quen giao diện/workflow) | Cao (Đã lưu nhiều sổ tay cá nhân) |
| Brand | Mạnh (Trong giới học thuật) | Rất mạnh (Được bảo chứng bởi Google) |
| Distribution (kênh tiếp cận user) | Yếu (Word of mouth) | Rất mạnh (Có sẵn người dùng Google) |

### S5.5 — Data flywheel + feedback loop

Hành động người dùng nào feed lại model? Loop có compounding (mỗi lần dùng → cải thiện model → giá trị cao hơn → người dùng dùng tiếp) không?

- **Sản phẩm A**: Thumbs up/down cho kết quả giúp cải thiện thuật toán semantic search. Compounding nhẹ nhưng không mạnh.
- **Sản phẩm B**: Chưa có compounding rõ rệt từ feedback trực tiếp của người dùng do chính sách bảo mật dữ liệu upload của Google.

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

- **Sản phẩm A**:
  - Niche cụ thể (đối tượng người dùng + use case): Nhà nghiên cứu, sinh viên đại học cần quét tài liệu khoa học diện rộng.
  - AI Feature Map (User Value × User Alignment × Business Value):
    - User Value: Cao — Giảm hàng chục giờ đọc paper thủ công.
    - User Alignment: Trung — Bị giới hạn bởi paywall/credit barrier.
    - Business Value: Cao — Nhu cầu thường xuyên, dễ upsell cho trường học.
- **Sản phẩm B**:
  - Niche cụ thể: Sinh viên, tác giả, nhà phân tích cần đọc sâu và tổng hợp tài liệu cá nhân.
  - AI Feature Map:
    - User Value: Cao — Audio Overview mang tính đột phá.
    - User Alignment: Cao — Miễn phí, hành văn tự nhiên, cực kỳ dễ dùng.
    - Business Value: Trung — Chủ yếu giữ chân người dùng trong hệ sinh thái Google.

### S5.7 — Spark → Loop → System (BẮT BUỘC)

Mỗi sản phẩm đang ở giai đoạn nào trong 3 giai đoạn?

- **Sản phẩm A**: Loop — Lý do: Đã hình thành thói quen sử dụng thường xuyên cho nhóm cốt lõi và có luồng doanh thu từ Plus. Dự báo 12 tháng tới: Sẽ tích hợp thêm công cụ hỗ trợ viết bài học thuật.
- **Sản phẩm B**: Spark — Lý do: Audio Overview đang tạo viral mạnh mẽ, người dùng mới bắt đầu làm quen với note-taking bằng AI. Dự báo 12 tháng tới: Sẽ chuyển sang Loop nhờ tích hợp sâu vào Google Drive.

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

Đối chiếu 2 sản phẩm với case bigtech-disruption mỗi thành viên đã làm ở Lab 1:

- Sản phẩm A có rủi ro disruption tương tự case nào của nhóm? Có thể bị disrupt bởi các đối thủ lớn như Perplexity hoặc Google Scholar nếu họ tung ra tính năng trích xuất bảng (Data Extraction).
- Sản phẩm B có rủi ro disruption tương tự case nào của nhóm? Rất khó bị disrupt nhờ distribution khổng lồ của Google, ngược lại nó đang đi disrupt các công cụ note-taking truyền thống.
- Bài học rút từ Lab 1 áp dụng được cho 2 sản phẩm này thế nào? Ứng dụng AI cần gắn chặt với workflow (NotebookLM) hoặc tạo ra pain-killer đặc thù (Elicit) mới giữ chân được người dùng. Không có Distribution mạnh thì bắt buộc phải có Moat về Data.

---

## Bảng kiểm trước khi build slide

- [x] S1 → S4 đã điền đầy đủ.
- [x] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành (4 sub-mục bắt buộc).
- [x] S5.2 → S5.5 đã hoàn thành (hoặc đã ghi rõ "không có nguồn công khai" cho ô trống).
- [x] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [x] Verdict ở S5.1 nhất quán với phân tích moat ở S5.4 và giai đoạn ở S5.7.
- [x] 2 thành viên cùng đồng ý với toàn bộ outline.

---

## Sau khi xong outline

1. Mở pptx / Keynote / Google Slides / Figma.
2. Tạo 12-15 slide bám theo cấu trúc S1 → S5 ở trên (mỗi mục 1-3 slide).
3. **Mỗi slide có ít nhất 1 ảnh tham chiếu** (từ `screenshots/`).
4. Export PDF → lưu thành `analysis-report.pdf` trong cùng folder này.
5. Nếu dùng Google Slides công khai, lưu link vào `analysis-report-link.md` (tuỳ chọn).
6. 2 thành viên cùng copy `analysis-report.pdf` + `group-members.md` về repo cá nhân của mình.

> Tham khảo `prompts/08-analysis-report.md` nếu cần AI hỗ trợ build slide từ outline này.