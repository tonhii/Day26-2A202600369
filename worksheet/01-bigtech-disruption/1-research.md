---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu: tìm 1 case bị big tech AI ảnh hưởng + số liệu thật

Mục tiêu: bạn tự chọn 1 sản phẩm hoặc 1 công ty bị ảnh hưởng nặng sau khi big tech AI (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...) ra mắt tính năng tương tự. Tự tìm số liệu cụ thể về case đó từ nguồn công khai. Mỗi số liệu phải có nguồn (URL + tên báo/tổ chức + ngày tháng). Lab 1 là phần cá nhân — mỗi học viên tự chọn case riêng và tự làm phần research trong repo cá nhân.

Lý do làm bước này: phân tích chỉ có sức nặng khi đứng trên số liệu thật. Bạn cần tự tìm ít nhất 8-10 số liệu cụ thể để có nền tảng phản biện cho 4 câu hỏi ở phase 2.

Quy tắc: **không có số liệu = không có nhận định**. Học viên tự tìm số liệu cho case mình chọn. Mỗi nhận định phải có nguồn (URL + ngày).

## Bước 0 — Chọn case (5 phút đầu)

Trước khi tìm số liệu, bạn quyết định case nào:

1. Sản phẩm/công ty bạn chọn là gì?
2. Big tech AI nào ra tính năng tương tự gây ảnh hưởng? (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...)
3. Vì sao bạn chọn case này? (Có số liệu công khai? Có mốc thời gian rõ? Có liên hệ với ngành bạn quan tâm?)

Ghi câu trả lời ngắn vào ô dưới đây trước khi bắt đầu tìm số liệu.

- **Tên case**: Adobe Inc. (NASDAQ: ADBE)
- **Big tech AI tạo áp lực**: Midjourney (ra beta 7/2022), DALL·E / ChatGPT image gen (OpenAI), Stable Diffusion (Stability AI)
- **Lý do chọn**: Công ty niêm yết → có đầy đủ báo cáo tài chính, SEC filings, dữ liệu cổ phiếu công khai. Mốc thời gian rõ ràng. Là case kinh điển về "incumbent bị AI-native disrupt trong ngành Design/Creative" — doanh thu vẫn tăng nhưng cổ phiếu lao dốc, phản ánh mâu thuẫn giữa hiện tại và kỳ vọng dài hạn của thị trường.

## Quy trình 15 phút

```text
5 phút  — Chọn case + xác định 4 nhóm số liệu cần tìm cho case của mình
8 phút  — Tự tìm số liệu trên các nguồn chính (báo chí công nghệ, báo cáo tài chính, blog chính thức...)
2 phút  — Rà lại bảng số liệu, đánh dấu số chưa kiểm chứng
```

---

## Phần A — Các nhóm số liệu cần tìm

### Nhóm 1 — Quy mô trước & sau (cổ phiếu, doanh thu, người dùng)

- **Cổ phiếu đỉnh**: $699.54 / cổ phiếu (22/11/2021) — all-time high
- **Cổ phiếu hiện tại**: ~$254 / cổ phiếu (5/2026) → giảm **~63.7%** từ đỉnh
- **Cổ phiếu giảm liên tiếp**: -25% năm 2024, -21% năm 2025, -29% từ đầu 2026 (tính đến tháng 4/2026)
- **Doanh thu FY2023**: $19.41 tỷ (+10% YoY) — kỷ lục, nhưng tốc độ tăng trưởng đang giảm dần
- **Doanh thu Creative Cloud**: tăng trưởng giảm từ **+23% (FY2021) → +10% (FY2022) → +10% (FY2023) → +10% (FY2024)** — giảm mạnh ngay năm Midjourney ra mắt, sau đó tăng trưởng bị kẹt ở mức 10% suốt 3 năm liên tiếp (nguồn: SEC 8-K filings)
- **Vốn hóa hiện tại**: ~$99.5 tỷ (5/2026) vs đỉnh ~$320 tỷ (2021)

Nguồn đã dùng:
- MacroTrends: https://www.macrotrends.net/stocks/charts/ADBE/adobe/stock-price-history
- TradingView: https://www.tradingview.com/symbols/NASDAQ-ADBE/
- SEC Form 8-K FY2023: https://www.sec.gov/Archives/edgar/data/0000796343/000079634323000252/adbeex991q423.htm

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

- **Midjourney open beta**: 12/07/2022 — công cụ text-to-image thay thế trực tiếp Photoshop/Illustrator cho nhiều use case sáng tạo
- **DALL·E 2 public**: 2022 (OpenAI) — tích hợp sâu vào ChatGPT từ 2023
- **Stable Diffusion**: ra mắt tháng 8/2022 — open source, miễn phí hoàn toàn
- **ChatGPT ra mắt**: 11/2022 — 100 triệu user trong 2 tháng, kéo theo làn sóng AI image gen vào mainstream
- **Tính năng trùng lặp**: text-to-image, image editing, background removal, style transfer — tất cả là core workflow của Photoshop/Illustrator

Nguồn đã dùng:
- Britannica (Midjourney history): https://www.britannica.com/technology/Midjourney
- Wikipedia Midjourney: https://en.wikipedia.org/wiki/Midjourney

### Nhóm 3 — Phản ứng của Adobe sau khi big tech AI ra mắt

- **Adobe Firefly beta**: ra mắt 21/03/2023 — **8 tháng** sau khi Midjourney mở beta (7/2022)
- **Firefly GA (thương mại hóa)**: 13/09/2023 — tích hợp vào Photoshop, Illustrator, Express
- **Firefly Video Model**: ra mắt beta tháng 10/2024
- **Model AI dùng**: tự phát triển, train trên Adobe Stock + public domain — không dùng OpenAI/Google
- **Kết quả adoption**: 13 tỷ ảnh được tạo bằng Firefly tính đến tháng 10/2024
- **Vấn đề cốt lõi**: Firefly có adoption cao nhưng **không chuyển thành doanh thu** — không có đợt sa thải lớn, không có tái cơ cấu công bố rộng

Nguồn đã dùng:
- Adobe blog (Firefly launch): https://blog.adobe.com/en/publish/2023/03/21/bringing-gen-ai-to-creative-cloud-adobe-firefly
- Adobe press release (Firefly GA): https://news.adobe.com/news/news-details/2023/adobe-unleashes-new-era-of-creativity-for-all-with-the-commercial-release-of-generative-ai
- Adobe MAX 2024: https://news.adobe.com/news/2024/10/101424-adobe-launches-firefly-video-model
- TechCrunch: https://techcrunch.com/2023/03/21/adobe-firefly-generative-ai/

### Nhóm 4 — Đối thủ AI thay thế

| Sản phẩm | Use case thay thế Adobe | Giá/tháng | Ra mắt |
|---|---|---|---|
| Midjourney | Image generation, concept art, editorial | $10–$120 | 7/2022 |
| DALL·E 3 (ChatGPT Plus) | Image gen tích hợp trong chat workflow | $20 (bundled) | 10/2023 |
| Stable Diffusion | Image gen, fine-tuning | Miễn phí (open source) | 8/2022 |
| Canva Magic Studio | Design + AI cho SMB/non-designer | $15 | 2023 |
| Adobe Creative Cloud Standard (gốc) | Full professional suite | $54.99 (Standard) / $69.99 (Pro) | — |

Chênh lệch giá: Adobe CC (~$55/tháng) đắt hơn Midjourney **5.5 lần**, đắt hơn ChatGPT Plus **2.75 lần**.

Nguồn đã dùng:
- Midjourney pricing: https://www.aicontentcreate.com/tools/midjourney/pricing/
- Adobe Firefly pricing comparison: https://gptprompts.ai/ai-pricing/adobe-firefly-pricing
- toolradar.com: https://toolradar.com/tools/adobe-firefly/pricing

---

## Phần B — Bảng tổng hợp số liệu

### Bảng số liệu case Adobe Inc. (ADBE)

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Giá cổ phiếu đỉnh (all-time high) | $699.54 / cổ phiếu | 22/11/2021 | https://www.macrotrends.net/stocks/charts/ADBE/adobe/stock-price-history | Có |
| S-02 | Giá cổ phiếu hiện tại | ~$254 / cổ phiếu | 5/2026 | https://www.macrotrends.net/stocks/charts/ADBE/adobe/stock-price-history | Có |
| S-02b | Mức giảm tổng từ đỉnh | -63.7% | 2021 → 2026 | Tính từ S-01 và S-02 | Tính toán |
| S-03 | Midjourney open beta — mốc AI image gen vào mainstream | Open beta public | 12/07/2022 | https://www.britannica.com/technology/Midjourney | Có |
| S-04 | Adobe Firefly beta — phản ứng chính thức | Ra mắt Firefly beta | 21/03/2023 | https://news.adobe.com/news/news-details/2023/adobe-unveils-firefly-a-family-of-new-creative-generative-ai | Có |
| S-05 | Khoảng cách phản ứng (Midjourney → Firefly beta) | 8 tháng | 7/2022 → 3/2023 | Tính từ S-03 và S-04 | Tính toán |
| S-06 | Tốc độ tăng trưởng Creative revenue (YoY) giảm mạnh rồi bị kẹt | +23% → +10% → +10% → +10% | FY2021 → FY2022 → FY2023 → FY2024 | SEC 8-K FY2021: https://www.sec.gov/Archives/edgar/data/0000796343/000079634321000247/adbeex991q421.htm — SEC 8-K FY2022: https://www.sec.gov/Archives/edgar/data/0000796343/000079634322000225/adbeex991q422.htm — SEC 8-K FY2024: https://www.sec.gov/Archives/edgar/data/796343/000079634324000250/adbeex991q424.htm | Có — nguồn SEC cấp 1, kiểm chứng chéo 4 năm |
| S-07 | Doanh thu toàn công ty FY2023 | $19.41 tỷ (+10% YoY) | FY2023 | https://www.sec.gov/Archives/edgar/data/0000796343/000079634323000252/adbeex991q423.htm | Có — nguồn SEC |
| S-08 | Firefly — tổng số ảnh được tạo (18 tháng sau launch) | 13 tỷ ảnh | 10/2024 | https://news.adobe.com/news/2024/10/101424-adobe-launches-firefly-video-model | Có |
| S-09 | So sánh giá: Adobe CC vs đối thủ AI | CC Standard $54.99/th — CC Pro $69.99/th vs Midjourney $10/th vs ChatGPT+ $20/th | 5/2026 | Adobe chính thức: https://www.adobe.com/creativecloud/plans.html — Midjourney: https://www.midjourney.com | Có — giá CC lấy trực tiếp từ adobe.com |
| S-10 | Cổ phiếu theo calendar year: lao dốc 2022, bật lại 2023, giảm lại 2024–2026 | 2022: **-40.65%** — 2023: +77.28% — 2024: **-25.46%** — YTD 2026: **-27.44%** | 2022–2026 | financecharts.com: https://www.financecharts.com/stocks/ADBE/performance/total-return | Có — kiểm chứng chéo với MacroTrends (52-week low $224.13 ngày 10/4/2026) |

---

## Phần C — Kiểm chứng nguồn

### Checklist kiểm chứng

- [x] Mỗi số liệu có URL nguồn cụ thể.
- [x] URL mở được, không 404 (đã kiểm tra tại thời điểm research).
- [x] Nội dung URL khớp với số liệu ghi (cùng đơn vị, cùng năm).
- [x] Với số liệu quan trọng (quy mô, doanh thu, ngày tháng), kiểm chứng chéo 2 nguồn độc lập. ✅ **S-06, S-09, S-10 đã kiểm chứng xong.**
- [x] Số chưa chắc đã đánh dấu `[CHƯA KIỂM CHỨNG]`.

### Việc cần làm trước khi sang Phần 2

| Dòng | Việc cần làm | Nguồn gốc cần mở |
|---|---|---|
| ~~S-06~~ | ✅ Đã kiểm chứng từ SEC 8-K filings — số đã cập nhật vào bảng | — |
| ~~S-09~~ | ✅ Đã kiểm chứng từ adobe.com — CC Standard $54.99, CC Pro $69.99 | — |
| ~~S-10~~ | ✅ Đã kiểm chứng từ financecharts.com — số theo calendar year đã cập nhật | — |

**Tất cả số liệu đã được kiểm chứng. File sẵn sàng để chuyển sang `2-analysis.md`.**

### Quy tắc loại nguồn

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 — Nguồn gốc | Báo cáo tài chính, thông báo chính thức, hồ sơ pháp lý | 10-K filings, SEC filings, blog công ty |
| 2 — Báo lớn | Báo chí công nghệ/kinh doanh uy tín | CNBC, Bloomberg, TechCrunch, Reuters, FT |
| 3 — Báo cáo phân tích | Báo cáo tài chính độc lập | MacroTrends, Yahoo Finance, Google Finance |
| 4 — Tránh dùng | Bài đăng cá nhân, blog không nguồn, mạng xã hội | Reddit posts, Medium articles không có citation |

### Cảnh báo

AI có thể bịa cả nguồn — đặc biệt khi bạn hỏi AI số liệu thay vì tự tìm. Nếu dùng AI để gợi ý nơi tìm, vẫn phải tự mở URL và xác minh.

---

## Phần D — Phát hiện ban đầu

- **Nghịch lý doanh thu vs cổ phiếu**: Doanh thu Adobe vẫn tăng đều ~10% YoY (kỷ lục $19.41 tỷ FY2023) nhưng cổ phiếu mất ~63.7% từ đỉnh — thị trường không tin Adobe bảo vệ được moat dài hạn trước AI-native competitors.
- **Phản ứng chậm 8 tháng**: Adobe mất 8 tháng sau khi Midjourney mở beta mới ra Firefly beta (7/2022 → 3/2023) — trong khi Midjourney là startup nhỏ dưới 100 người đã thay đổi kỳ vọng của cả ngành.
- **Adoption cao nhưng không monetize được**: Firefly tạo 13 tỷ ảnh trong 18 tháng — nhưng tốc độ tăng trưởng Creative revenue bị kẹt ở đúng **+10% suốt FY2022–FY2024** (nguồn SEC 8-K). Tăng trưởng giảm từ +23% (FY2021) xuống +10% (FY2022) ngay năm Midjourney ra mắt, rồi không phục hồi dù Firefly deploy rộng — AI feature không chuyển thành doanh thu mới.
- **Chênh lệch giá cực lớn**: Adobe CC Standard **$54.99/tháng** (Pro $69.99) vs Midjourney $10/tháng (5.5x rẻ hơn) vs ChatGPT Plus $20/tháng (2.75x rẻ hơn) — nguồn: adobe.com + midjourney.com. Người dùng phổ thông và SMB có lựa chọn thay thế rẻ hơn nhiều cho các use case đơn giản.
- **Moat đang bị bào mòn từ dưới lên**: AI tools không thay thế Photoshop cho professional ngay — nhưng đang thay thế Photoshop cho 80% use case của non-professional, SMB, marketer, content creator — đúng phần user base dễ mất nhất.

---

## Phần E — Câu hỏi mở (cho phân tích Phần 2)

- **Câu hỏi 1**: Firefly có 13 tỷ lượt tạo ảnh nhưng doanh thu không tăng tương ứng — tại sao AI adoption không dẫn đến revenue growth? Adobe đang tặng miễn phí giá trị mà trước đây người dùng trả tiền để có?
- **Câu hỏi 2**: Khách hàng nào đang rời Adobe — hay đúng hơn là không gia nhập? Người dùng cá nhân/SMB/non-designer có đang bỏ qua Adobe để dùng thẳng Midjourney/ChatGPT không, và segment enterprise có thực sự an toàn không?
- **Câu hỏi 3**: Lợi thế thực sự của Adobe là gì sau khi AI xóa bỏ lợi thế "khó học, khó dùng"? Workflow integration, IP safety (Firefly trained on licensed data), hay enterprise trust — cái nào đủ mạnh để giữ pricing power?
- **Câu hỏi 4**: Adobe nên định vị lại thành "AI platform" (giống Canva đang làm) hay giữ "professional creative tools for experts" — hai hướng đi này có xung đột nhau không, và Adobe có đang bị kẹt ở giữa không?

Sau bước này, chuyển sang `2-analysis.md` để vận dụng Lens 1 (Customer Expectations + Four Fits) vào case Adobe.