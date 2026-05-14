---
artifact: 2 — Phân tích case theo 4 câu hỏi
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Vận dụng Lens 1 (Customer Expectations + Four Fits)
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: 1-research.md + prompts/02-four-fits-analysis.md
nop-cuoi: Không — file trung gian
case: Adobe Inc. (ADBE)
---

# 2 — Phân tích case Adobe: Phần A (4 câu hỏi chiến lược) + Phần B (5 chiều phân tích)

Mục tiêu: trả lời 4 câu hỏi chiến lược (Phần A) và bổ sung 5 chiều phân tích định lượng (Phần B) cho case Adobe. Mọi nhận định lấy từ số liệu đã kiểm chứng ở `1-research.md` làm bằng chứng.

## Quy trình 15 phút

```text
3 phút  — Đọc lại 1-research.md
7 phút  — Phần A: trả lời 4 câu hỏi chiến lược
4 phút  — Phần B: điền 5 chiều phân tích định lượng
1 phút  — Rà lại: mỗi câu có bằng chứng chưa?
```

---

# Phần A — 4 câu hỏi chiến lược

---

## Câu hỏi 1 — Trước AI, sản phẩm hoạt động dựa trên giả định gì?

### Trả lời

Trước khi làn sóng AI image generation nổi lên (trước giữa 2022), Adobe hoạt động dựa trên các giả định sau:

- **Người dùng**: hai nhóm chính — (1) professional creative: graphic designer, photographer, video editor, motion designer, agency; (2) prosumer/SMB: marketer, content creator, small business chưa đủ ngân sách thuê agency. Cả hai nhóm đều phụ thuộc vào Adobe vì không có lựa chọn nào tốt hơn ở cùng mức chất lượng.

- **Vấn đề người dùng cần giải**: tạo và chỉnh sửa hình ảnh, video, vector, layout ở mức chất lượng chuyên nghiệp — đòi hỏi phần mềm phức tạp, nhiều tính năng, nhiều năm học. Không có công cụ nào thay thế được.

- **Giá trị sản phẩm cung cấp**: bộ công cụ chuyên nghiệp hoàn chỉnh (Photoshop, Illustrator, Premiere, InDesign...) với độ chính xác pixel-level mà không công cụ nào khác đạt được. Tích hợp chặt với nhau trong một hệ sinh thái duy nhất (Creative Cloud). Là tiêu chuẩn ngành — file .psd, .ai, .indd là định dạng mà toàn bộ ngành design dùng.

- **Mô hình kinh doanh**: subscription — Creative Cloud All Apps ~$55/tháng (individual), sau khi chuyển đổi từ mô hình bán license vĩnh viễn (trước 2013). Khóa người dùng vào hệ sinh thái bằng định dạng file độc quyền và muscle memory tích lũy qua nhiều năm học.

- **Vì sao mô hình này hoạt động được nhiều năm**:
  - **Lý do 1 — Switching cost cao nhân tạo**: học Photoshop mất hàng trăm giờ, file format độc quyền (.psd, .ai) không mở được bằng công cụ khác, toàn bộ team/agency dùng cùng format → ai ra đi phải kéo theo cả workflow.
  - **Lý do 2 — Không có đối thủ ngang tầm**: GIMP free nhưng quá phức tạp và thiếu tính năng; Canva đơn giản nhưng không đủ sâu cho professional. Adobe chiếm cả hai đầu thị trường — đủ mạnh cho pro, đủ phổ biến cho prosumer.
  - **Lý do 3 — Scarcity of expertise là moat**: "biết dùng Photoshop" là kỹ năng kiếm tiền được — Adobe là công cụ, chuyên môn con người là hào phòng thủ. Miễn là kỹ năng có giá trị, Adobe có giá trị.

**Bằng chứng**:

- **[S-07]**: Doanh thu FY2023 đạt kỷ lục $19.41 tỷ (+10% YoY) — mô hình hoạt động tốt ngay cả khi AI pressure đã bắt đầu, cho thấy inertia của user base hiện tại còn lớn.
- **[S-06]**: Creative revenue tăng +23% FY2021 — đây là tốc độ tăng trưởng của một công ty đang ở trạng thái bình thường trước khi bị AI shock. Biên lợi nhuận cao, churn thấp, switching cost phát huy tác dụng.
- **[S-09]**: Giá CC Standard $54.99/tháng — cao hơn Midjourney 5.5x — được thị trường chấp nhận nhiều năm vì không có lựa chọn thay thế thực sự cho professional workflow.

---

## Câu hỏi 2 — Kỳ vọng của người dùng đã thay đổi như thế nào?

### Trả lời

Trong 7 Customer Expectation Shifts, case Adobe bị tấn công mạnh nhất bởi 3 shift:

- **Shift số 1 — "Do the work for me" (tool → teammate)**: Trước đây người dùng mở Photoshop, tự học từng công cụ, tự kéo từng thanh adjustment. Sau khi Midjourney/DALL·E ra mắt, người dùng gõ một câu prompt và có kết quả trong vài giây. Công cụ không còn là công cụ nữa — nó *làm thay* phần sáng tạo. Adobe mất 8 tháng mới ra Firefly, nhưng Firefly đến quá muộn — thói quen đã hình thành ở nơi khác.

- **Shift số 3 — "Busy work done for me"**: background removal, object selection, color correction, image upscaling — tất cả đều là "busy work" mà Adobe charge $55/tháng. ChatGPT, Canva, và hàng chục startup đã tự động hóa đúng những task này, miễn phí hoặc rẻ hơn nhiều.

- **Shift số 4 — "Pay for output, not seat"**: Mô hình Adobe là trả $55/tháng bất kể dùng nhiều hay ít. Midjourney tính theo GPU hour, ChatGPT Plus $20 cho cả gói, Stable Diffusion miễn phí. Người dùng phổ thông bắt đầu đặt câu hỏi: tại sao trả $55 khi mình chỉ cần 10 ảnh/tháng?

So sánh kỳ vọng cũ và mới:

| Trước khi big tech AI ra tính năng tương tự (kỳ vọng cũ) | Sau khi big tech AI ra tính năng tương tự (kỳ vọng mới) |
|---|---|
| Học cách dùng công cụ phức tạp để làm được việc | Mô tả bằng ngôn ngữ tự nhiên, AI làm thay |
| Trả phí định kỳ để có quyền truy cập công cụ | Trả theo output, hoặc miễn phí với quota giới hạn |
| Chấp nhận learning curve cao vì không có lựa chọn | Kỳ vọng kết quả ngay lập tức, không cần học |
| File format của Adobe là tiêu chuẩn không thể tránh | Output là ảnh/video thô — không cần file format độc quyền |
| "Biết Photoshop" là kỹ năng có giá trị | AI thay thế được phần kỹ năng đó, nhanh hơn, rẻ hơn |

**Bằng chứng**:

- **[S-08]**: 13 tỷ ảnh được tạo bằng Firefly trong 18 tháng — cho thấy người dùng đã chuyển sang kỳ vọng "AI làm thay" ngay cả trong hệ sinh thái Adobe, nhưng adoption này không tạo thêm doanh thu (S-06 tăng trưởng vẫn flat 10%).
- **[S-03] + [S-09]**: Midjourney mở beta 7/2022 với giá $10/tháng — bằng 1/5 giá Adobe CC — và có thể làm được phần lớn use case image generation mà người dùng phổ thông cần. Shift "pay for output not seat" hiện rõ.

---

## Câu hỏi 3 — Giả định nào đã không còn đúng? (Four Fits)

### Trả lời

Bốn Fit của Adobe trước AI:

- **Product Market Fit**: Photoshop/Illustrator giải đúng vấn đề "cần tạo visual chuyên nghiệp" cho cả professional lẫn prosumer — không có lựa chọn thay thế ngang tầm.
- **Product Channel Fit**: kênh phân phối là trực tiếp qua Adobe.com + education licensing + enterprise deal — hợp với sản phẩm phức tạp cần demo và training.
- **Channel Model Fit**: subscription $55/tháng khớp với kênh direct-to-consumer và enterprise — người dùng commit dài hạn vì switching cost cao.
- **Model Market Fit**: thị trường creative professional chấp nhận trả premium vì Adobe là tiêu chuẩn ngành — không có lựa chọn.

Sau khi AI ra mắt, các Fit vỡ theo trình tự:

1. **Fit vỡ đầu tiên — Product Market Fit (PMF)**: AI tools làm được 80% use case của non-professional với chất lượng "đủ dùng" ở giá thấp hơn 5x. Adobe vẫn tốt hơn cho professional — nhưng phân khúc "prosumer muốn kết quả nhanh, không muốn học" đã có lựa chọn thay thế thực sự. PMF vỡ không hoàn toàn nhưng co lại đáng kể.
   - **Bằng chứng [S-06]**: Creative revenue growth giảm từ +23% (FY2021) xuống +10% (FY2022) — giảm hơn nửa ngay năm Midjourney ra mắt, sau đó kẹt ở 10% suốt 3 năm. Nếu PMF còn nguyên, tốc độ tăng trưởng không thể "đóng băng" như vậy.

2. **Fit vỡ thứ hai — Model Market Fit (MMF)**: Thị trường không còn chấp nhận mô hình "trả $55/tháng dù dùng ít hay nhiều" khi có lựa chọn trả ít hơn (hoặc miễn phí) cho output tương đương. Adobe buộc phải tung CC Standard $54.99 và CC Pro $69.99 để segment hóa — nhưng vẫn đắt hơn đối thủ nhiều lần.
   - **Bằng chứng [S-09] + [S-10]**: Giá CC Standard $54.99 vs Midjourney $10 (5.5x). Cổ phiếu giảm -40.65% năm 2022 — thị trường đặt cược Model Market Fit đã vỡ ngay từ sớm.

3. **Fit vỡ thứ ba — Channel Model Fit (CMF)**: Kênh enterprise và education vẫn còn — nhưng kênh individual direct bị đe dọa. Adobe phải giữ giá cao để phục vụ enterprise, trong khi người dùng individual có lý do để rời đi. Hai segment cần hai pricing model khác nhau, nhưng Adobe chỉ có một channel.
   - **Bằng chứng [S-08]**: Firefly có 13 tỷ lượt gen ảnh nhưng không tạo thêm ARR — người dùng dùng tính năng AI miễn phí bundled trong subscription hiện tại, không upgrade hay mua thêm. CMF của Firefly không được thiết kế để monetize usage.

4. **Fit vỡ thứ tư — Product Channel Fit (PCF)**: Kênh phân phối của Adobe (direct, enterprise sales, education) không phù hợp để cạnh tranh với model "sign up online trong 30 giây, dùng ngay" của Midjourney/ChatGPT.
   - **Bằng chứng [S-05]**: Mất 8 tháng từ Midjourney open beta đến Firefly beta — trong khi Midjourney là startup nhỏ ra mắt và viral qua Discord trong vài tuần. Tốc độ phân phối hoàn toàn khác nhau.

**Tốc độ Fit Collapse**:

- Từ khi Midjourney open beta (7/2022) đến khi cổ phiếu mất 40% (cuối 2022): **5 tháng**.
- Adobe chưa mất 50% doanh thu — nhưng đã mất ~70% market cap tính từ đỉnh (2021 → 2026).
- Kết luận: Adobe đang trong trạng thái **Fit Collapse chậm** — doanh thu vẫn tăng nhờ inertia của enterprise/professional user base, nhưng thị trường đã định giá lại tương lai. Đây là dạng collapse nguy hiểm nhất vì khó nhận ra từ bên trong.

**Bằng chứng tổng hợp**:

- **[S-01] + [S-02b]**: Cổ phiếu từ $699 (11/2021) xuống ~$254 (5/2026) = -63.7% — thị trường đã định giá lại toàn bộ tương lai của Adobe.
- **[S-06]**: Tăng trưởng Creative revenue kẹt ở 10%/năm suốt FY2022–FY2024 bất chấp Firefly adoption — bằng chứng PMF đang co lại.
- **[S-10]**: Cổ phiếu -40.65% năm 2022 (ngay năm Midjourney/SD ra mắt) — thị trường phản ứng tức thì với PMF collapse.

---

## Câu hỏi 4 — Sản phẩm có thể cứu vãn? Hay đã quá muộn?

### Trả lời

So sánh Adobe với Canva — đối thủ phản ứng tốt hơn trong cùng ngành:

| Yếu tố | Adobe | Canva |
|---|---|---|
| Đối tác AI | Tự build Firefly (train trên Adobe Stock) | Dùng DALL·E + Imagen (Google) — tích hợp API |
| Thời gian ra sản phẩm AI | 8 tháng (7/2022 → 3/2023) | Đầu 2023 — tốc độ tương đương nhưng distribution nhanh hơn |
| Giá sản phẩm AI | Bundled vào CC Standard $54.99/th | Magic Studio bundled vào Canva Pro $15/th |
| Tích hợp với sản phẩm cũ | Sâu (Photoshop, Illustrator) nhưng complex UX | Seamless — cùng giao diện kéo thả |
| Mô hình kinh doanh | Subscription premium → khó hạ giá | Freemium + upgrade nhẹ → dễ convert |
| Kết quả | Creative growth flat 10% | Revenue $3.5 tỷ (2025), MAU top 3 AI tools toàn cầu |

**Big Squeeze trên Adobe (3 lực nén)**:

- **Lực 1 — Doanh nghiệp lớn sao chép**: Microsoft tích hợp AI design vào Designer và Copilot; Google tích hợp Imagen vào Workspace. Cả hai đều nhắm vào use case mà Adobe đang phục vụ — và đều có distribution lớn hơn Adobe nhiều lần.
- **Lực 2 — Startup xây nhanh hơn**: Canva ($3.5B revenue, 2025), Figma (AI features ra liên tục sau khi Adobe thất bại mua lại), Midjourney ($500M ARR ước tính 2025 với dưới 100 nhân viên). Tất cả đều nhẹ hơn, nhanh hơn, và rẻ hơn.
- **Lực 3 — Platform AI gom người dùng**: ChatGPT với GPT-Image đã trở thành điểm đến mặc định cho image generation với 100M+ user. Người dùng không cần mở Photoshop — họ hỏi ChatGPT. Adobe mất top-of-mind cho phân khúc casual và SMB.

**Đánh giá: Adobe vẫn có thể cứu vãn — nhưng chỉ nếu chấp nhận thu hẹp thị trường mục tiêu về đúng phân khúc còn defensible.**

- **Lý do 1 — Enterprise moat vẫn còn nguyên**: IP safety (Firefly train trên licensed data), workflow integration sâu, và enterprise trust là những thứ Midjourney không có. Doanh nghiệp lớn không thể dùng Midjourney vì rủi ro copyright — họ cần Adobe.
- **Lý do 2 — Professional workflow không thể thay thế ngay**: Photoshop cho retouching phức tạp, Premiere cho video edit chuyên nghiệp, InDesign cho layout — không AI nào làm được những việc này ở mức chuyên nghiệp thực sự. Phân khúc này còn defensible trong ít nhất 3–5 năm.
- **Lý do 3 — Nhưng pricing model hiện tại không bền**: $55–70/tháng không còn justify được cho người dùng phổ thông. Adobe cần tách pricing rõ ràng: premium cho professional/enterprise, lighter plan cho casual.

**Điều Adobe đáng lẽ phải làm khác trong 6 tháng đầu (7/2022 – 1/2023)**:

- Ra ngay một **"Adobe Express AI" tier giá $10/tháng** để giữ casual user — thay vì để họ chạy sang Midjourney và hình thành thói quen ở đó.
- **Partnership với OpenAI hoặc Stability AI** để có AI features nhanh hơn, thay vì mất 14 tháng tự build Firefly đến GA (3/2023 → 9/2023).
- **Mua Figma sớm hơn** (thực ra đã thử nhưng bị EU chặn — nếu deal thành công, Adobe có thêm 4M+ designer trong hệ sinh thái và một cộng đồng design workflow hiện đại hơn).

**Bằng chứng**:

- **[S-05]**: 8 tháng phản ứng — trong khi Canva ra AI features cùng giai đoạn và có distribution tốt hơn nhiều nhờ mô hình freemium.
- **[S-10]**: Cổ phiếu bật lại +77.28% năm 2023 khi Firefly GA ra mắt — thị trường tin Adobe có thể phục hồi. Nhưng sau đó -25.46% năm 2024 khi thấy Firefly không monetize được — niềm tin mất lại. Cơ hội có nhưng Adobe đã không chuyển đổi được.

---

# Phần B — 5 chiều phân tích định lượng

---

## B1 — User base (số lượng người dùng)

| Chỉ số | Trước AI shock (FY2021) | Sau AI shock (FY2024) | Nguồn |
|---|---|---|---|
| Creative Cloud subscribers (paid) | ~26M (ước tính từ ARR/ARPU) | ~32–33M (ước tính) | electroiq.com / Adobe investor data |
| Creative Cloud ARR | ~$11B | $13.85B | SEC 8-K FY2024 |
| Digital Media ARR tổng | ~$14B | $17.33B | SEC 8-K FY2024 |
| Số ảnh tạo bằng Firefly | — | 13 tỷ (10/2024) | Adobe MAX 2024 press release |

**Lưu ý**: Adobe không công bố số subscriber trực tiếp — chỉ công bố ARR. Số subscriber là ước tính từ ARR ÷ ARPU trung bình.

**Nhận định**: Tệp enterprise và professional subscriber vẫn tăng trưởng đều (ARR +23% từ FY2021 đến FY2024). Tệp bị ảnh hưởng nặng nhất là **"potential new user"** — người dùng SMB/non-designer đáng lẽ sẽ subscribe Adobe nhưng giờ chọn Canva/Midjourney thay thế. Adobe không mất user hiện tại nhiều, nhưng mất tăng trưởng mới — đây là silent churn của growth ceiling.

---

## B2 — Tốc độ tăng trưởng

| Giai đoạn | Tốc độ tăng trưởng Creative revenue | Nguồn |
|---|---|---|
| FY2021 (trước AI shock) | +23% YoY | SEC 8-K FY2021 |
| FY2022 (năm Midjourney/SD ra mắt) | +10% YoY | SEC 8-K FY2022 |
| FY2023 (năm Firefly beta → GA) | +10% YoY | SEC 8-K FY2023 |
| FY2024 (Firefly đã deploy rộng) | +10% YoY | SEC 8-K FY2024 |
| Thời điểm tăng trưởng đảo chiều | Q3/Q4 2022 — ngay sau Midjourney open beta (7/2022) | Tính từ S-03 và S-06 |

**Nhận định**: Adobe chưa thật sự quay đầu giảm — doanh thu vẫn tăng. Nhưng "bị kẹt ở 10% suốt 3 năm" sau khi từng tăng 23% là tín hiệu nguy hiểm: tốc độ tăng trưởng bị nén xuống sàn và không phục hồi dù Firefly deploy rộng. Đây là **growth ceiling** — không phải decline, nhưng nguy hiểm hơn decline vì khó phát hiện và khó biện minh.

---

## B3 — Doanh thu / valuation

| Chỉ số | Trước AI shock (FY2021) | Sau AI shock (FY2024) | Nguồn |
|---|---|---|---|
| Tổng doanh thu | ~$15.78 tỷ | $21.51 tỷ | SEC 8-K FY2024 |
| Creative Cloud revenue | $9.55 tỷ | $12.68 tỷ | SEC 8-K FY2021 + FY2024 |
| Market cap (đỉnh) | ~$320 tỷ (11/2021) | ~$99.5 tỷ (5/2026) | MacroTrends |
| Giá cổ phiếu | $699.54 (11/2021) | ~$254 (5/2026) | MacroTrends |
| Operating cash flow | ~$6B | $8.06 tỷ | SEC 8-K FY2024 |

**Nguồn**: tất cả số liệu tài chính từ SEC filings — **nguồn cấp 1, đáng tin cậy cao**.

**Nhận định**: Adobe là case hiếm gặp — **doanh thu tăng nhưng valuation sụp**. Revenue FY2024 ($21.51B) cao hơn FY2021 ($15.78B) 36%, nhưng market cap mất 69%. Thị trường đang định giá "tương lai tệ hơn hiện tại" — cụ thể là lo ngại về khả năng tăng trưởng dài hạn khi AI native tools tiếp tục cải thiện.

---

## B4 — Moat strategy

| Loại moat | Mức mạnh | Bằng chứng cụ thể |
|---|---|---|
| Switching cost | **Mạnh** — nhưng đang yếu dần | File format .psd/.ai độc quyền, muscle memory, team workflow đều trên CC. Nhưng AI output là .jpg/.png — không cần Adobe format nữa cho nhiều use case. |
| Brand | **Mạnh** với professional | "Photoshop" là verb trong tiếng Anh. Nhưng Gen Z/non-designer không còn aspirational với Adobe brand như thế hệ trước. |
| Data moat | **Trung bình** | Adobe Stock + hàng tỷ ảnh người dùng tạo — train được Firefly. Nhưng OpenAI/Midjourney cũng có data lớn hơn hoặc ngang. |
| Distribution | **Mạnh với enterprise** | Education licensing, enterprise deal, partner network là kênh mà startup không copy được. |
| Network effect | **Yếu** | Creative Cloud không có network effect thực sự — tôi dùng Photoshop không làm Photoshop tốt hơn cho bạn. |

- **Moat chủ đạo trước AI**: Switching cost — vì đã đầu tư hàng trăm giờ học và toàn bộ file archive là .psd/.ai.
- **Big tech AI tấn công moat nào**: Tấn công trực tiếp **switching cost** — bằng cách làm cho output không cần file format độc quyền nữa. Khi kết quả là một prompt → ảnh .jpg, không còn file .psd nào để lock-in.
- **Moat vẫn còn hiệu quả**: Distribution enterprise + Brand với professional — vì enterprise cần IP safety (Firefly trained on licensed data) và audit trail mà Midjourney không cung cấp.

**Nhận định**: Cấu trúc moat của Adobe vẫn đứng vững với professional/enterprise — nhưng moat đã biến mất hoàn toàn với phân khúc SMB/non-designer. Đây là "moat bị bào mòn từ dưới lên" — không thấy ở doanh thu hiện tại nhưng thấy ở growth ceiling và thấy rõ ở market cap.

---

## B5 — Data flywheel + feedback loop

- **Hành động người dùng feed lại model**: Mỗi lần user dùng Firefly (generate, rate, edit), Adobe thu thập dữ liệu để cải thiện model. Ngoài ra, Adobe Stock với hàng trăm triệu ảnh licensed là nguồn training data đặc thù mà đối thủ không có.

- **Loop có compounding không**: **Một phần** — loop tồn tại nhưng không compounding mạnh vì:
  - Firefly data flywheel chậm hơn OpenAI/Midjourney do user base nhỏ hơn và tần suất generate thấp hơn.
  - 13 tỷ ảnh Firefly (10/2024) vs hàng tỷ prompt/ngày của ChatGPT — quy mô data không cạnh tranh được.
  - Loop không tạo ra network effect: một user dùng Firefly nhiều không kéo user mới vào Adobe.

- **Sản phẩm có thu thập feedback systematically không**: **Có** — generative credits system theo dõi usage, Adobe có telemetry tốt. Nhưng vấn đề là **biết mà không dùng được**: biết user dùng Firefly nhiều nhưng không monetize được thêm từ usage đó (vẫn flat $55/tháng).

- **Big tech AI có vô hiệu hóa flywheel không**: **Một phần** — OpenAI và Midjourney có flywheel lớn hơn và nhanh hơn, làm Firefly luôn chạy sau về model quality. Tuy nhiên, Adobe có một flywheel riêng biệt mà đối thủ không copy được: **IP-safe training data từ Adobe Stock** — đây là lý do duy nhất enterprise tin dùng Firefly thay vì Midjourney.

**Nhận định**: Nếu flywheel Firefly bị vô hiệu hóa bởi OpenAI (model tốt hơn + rẻ hơn), Adobe vẫn còn hai thứ để giữ chân user: (1) workflow integration sâu trong Photoshop/Premiere cho professional, và (2) IP safety cho enterprise. Cả hai đều không phải flywheel — chúng là switching cost và trust. Đủ để sống còn, không đủ để tăng trưởng nhanh.

---

## Tổng kiểm tra trước khi chuyển sang file FINAL

| Phần | Đã trả lời | Có ít nhất 2 bằng chứng |
|---|---|---|
| A — Câu 1 — Giả định cũ | ✅ | ✅ S-07, S-06, S-09 |
| A — Câu 2 — Kỳ vọng người dùng thay đổi | ✅ | ✅ S-08, S-03, S-09 |
| A — Câu 3 — Fit nào vỡ | ✅ | ✅ S-06, S-09, S-10, S-05, S-01/S-02b |
| A — Câu 4 — Sản phẩm có cứu được không | ✅ | ✅ S-05, S-10 |
| B1 — User base | ✅ | ✅ SEC 8-K FY2024, Adobe MAX 2024 |
| B2 — Tốc độ tăng trưởng | ✅ | ✅ SEC 8-K FY2021–FY2024 (4 năm) |
| B3 — Doanh thu / valuation | ✅ | ✅ SEC filings + MacroTrends |
| B4 — Moat strategy | ✅ | ✅ S-09 (switching cost), S-08 (IP safety) |
| B5 — Data flywheel | ✅ | ✅ S-08 (13B images), S-06 (flat revenue dù adoption cao) |

**Tất cả phần đã có ít nhất 2 bằng chứng. File sẵn sàng để chuyển sang `3-FINAL-case-analysis.md`.**