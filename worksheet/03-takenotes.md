---
artifact: 03-takenotes — Quan sát cá nhân sau phần chia sẻ nhóm khác
bai-tap: 3 — Quan sát + rút ra bài học (cá nhân)
phase: Sau phần shareout của các nhóm
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác)
input: Phần thuyết trình của ít nhất 2 nhóm khác trên lớp
nop-cuoi: Có — file cuối Lab 3 (cá nhân)
---

# 03 — Take notes: quan sát + bài học cá nhân

Đây là phần cá nhân. Sau khi nhóm bạn trình bày Lab 2 và nghe ít nhất 2 nhóm khác chia sẻ Analysis Report của họ, bạn ghi lại quan sát + bài học của riêng mình vào file này.

Mục tiêu: rèn kỹ năng nghe, đối chiếu, và rút ra bài học từ phân tích của người khác — không chỉ từ phân tích của chính nhóm mình.

Quy tắc khi viết:

- Trích dẫn cụ thể tên sản phẩm + nhóm đã quan sát (không nói chung chung).
- Bằng chứng yếu / lập luận lỏng cần chỉ rõ chỗ nào trong slide deck của nhóm khác.
- Câu hỏi đặt cho nhóm khác phải gắn với bằng chứng cụ thể từ phần trình bày của họ.

---

## Thông tin

- **Mã học viên**: 2A202600369
- **Họ tên**: Hồ Thị Tố Nhi
- **Ngày**: 2026-05-14
- **Nhóm Lab 2 của tôi**: [Sản phẩm A vs Sản phẩm B trong ngành ___] (Đã làm ở Lab 2)

---

## Phần 1 — Nhóm đã quan sát (≥ 2 nhóm khác)

| # | Tên nhóm / mã 2 học viên | Ngành | 2 sản phẩm họ test |
|---|---|---|---|
| 1 | Quách Ngọc Quang (2A202600285) & Nguyễn Đông Hưng (2A202600392) | [B] Lập trình | Cursor vs GitHub Copilot |
| 2 | [Bạn tự điền thêm 1 nhóm khác trên lớp để đủ điều kiện] | [...] | [...] vs [...] |

---

## Phần 2 — Điều thấy hay từ nhóm khác

Góc nhìn / framework / case study mà nhóm khác đưa ra mà nhóm mình chưa nghĩ tới.

**Quan sát 1** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể họ đưa ra: Nhận định ở mục S3.3 "Với code generation, trust không đến từ citation mà đến từ khả năng execute và verify bằng unit test".
- Vì sao tôi thấy hay: Góc nhìn này cực kỳ thực tế và đúng với bản chất ngành lập trình. Nhóm không bị rập khuôn vào template (phải có citation mới là trust) mà linh hoạt định nghĩa lại Trust Signal dựa trên đặc thù của loại output (Code).

**Quan sát 2** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể họ đưa ra: Phân tách rõ ràng giữa Product Moat (trải nghiệm UX/Agent mượt mà của Cursor) và Distribution Moat (Hệ sinh thái GitHub của Copilot) ở mục S5.4.
- Vì sao tôi thấy hay: Giúp dự báo rủi ro disruption rất logic ở S5.8 (Cursor dễ bị copy tính năng, Copilot khó bị lật đổ vì ăn sâu vào quy trình công ty). Khái niệm Distribution Moat được nhóm vận dụng sắc bén.

---

## Phần 3 — Điểm yếu / chỗ chưa thuyết phục

Bằng chứng yếu, lập luận lỏng, framework dùng sai. Chỉ rõ chỗ nào trong slide deck của nhóm khác.

**Điểm yếu 1** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể: Ở S2.2, nhóm đánh giá Cognitive burden của GitHub Copilot là "Thấp" (tương đương Cursor) vì "giao tiếp tự nhiên".
- Bằng chứng gì còn thiếu: Nhóm bỏ qua việc Copilot Chat yêu cầu user tự copy/paste code vào đúng vị trí và tự duy trì context trong đầu (so với nút Apply của Cursor). Bằng chứng ở S2.1 của nhóm ghi rõ user phải "copy thủ công".
- Tôi sẽ đề xuất họ làm thêm gì: Đánh giá Cognitive burden của Copilot là "Trung bình/Cao" vì mental load cho việc map code từ chat vào editor thủ công là khá lớn.

**Điểm yếu 2** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể: Ở S4.2 (Cost-Capability-Speed), nhóm nhầm lẫn giữa Tốc độ sinh output của model và Tốc độ hoàn thành workflow (Speed).
- Bằng chứng gì còn thiếu: Ở S3.1 nhóm ghi tốc độ trả lời của 2 tool là tương đương (5-15 giây), nhưng ở S4.2 lại chấm Cursor "Rất nhanh - 2-3x".
- Tôi sẽ đề xuất họ làm thêm gì: Làm rõ chữ "Speed" trong định vị tam giác. Đây là "Workflow Speed" (nhờ UI/UX của Cursor) chứ không phải "Generation Speed" của LLM.

---

## Phần 4 — Câu hỏi đặt cho nhóm khác

Câu hỏi gắn với bằng chứng cụ thể, không hỏi chung chung.

- Cho nhóm Quang & Hưng: Ở S3.1, các bạn đánh giá cả 2 tool đều "Không bịa (hallucination)". Tuy nhiên với code, AI thường hay bịa các hàm thư viện không tồn tại khi gặp edge cases khó. Các bạn đã thử các edge cases cực đoan để ép AI hallucinate chưa, hay chỉ đang test "happy path"?
- Cho nhóm Quang & Hưng: Ở S5.6, các bạn chấm Business Value của Cursor "Cao". Nhưng nếu Copilot tích hợp UX "Apply" tương tự trong VS Code, liệu dev có dễ dàng bỏ Cursor quay về Copilot vì nó được công ty trả tiền không (Switching cost từ túi tiền cá nhân sang công ty)?

---

## Phần 5 — Điều tôi rút ra cho bản thân

Bài học cụ thể tôi sẽ áp dụng vào lần phân tích sản phẩm AI tiếp theo. Không viết câu chung chung như "tôi học được nhiều" — cụ thể về phương pháp, bằng chứng, hoặc framework.

**Bài học 1**:

- Tôi sẽ làm khác lần sau: Sẽ định nghĩa lại linh hoạt các "Trust Signals" (S3.2) sao cho phù hợp với loại hình nhiệm vụ (Task type) thay vì áp dụng rập khuôn.
- Lý do: Học từ bài của nhóm lập trình (trust = execution/unit test thay vì citation). Nếu test sản phẩm tạo ảnh, trust có thể là "vẽ đúng số lượng ngón tay"; nếu test tóm tắt văn bản, trust là "có citation".

**Bài học 2**:

- Tôi sẽ làm khác lần sau: Sẽ phân tách rạch ròi giữa "Sức mạnh của Model" và "Sức mạnh của UI/UX (Workflow)" khi phân tích Friction.
- Lý do: Cả Cursor và Copilot đều dùng chung model mạnh (như Claude 3.5 Sonnet / GPT-4o) có tốc độ tương đương, nhưng Cursor ăn tiền ở luồng UX "Apply" code trực tiếp. Sự khác biệt sản phẩm nằm ở luồng Workflow chứ không phải Model nền.

---

## Checklist trước khi nộp

- [x] Phần 1 ghi rõ ≥ 2 nhóm đã quan sát (mã 2 học viên + ngành + sản phẩm). (Đã ghi 1 nhóm, bạn nhớ ghi thêm nhóm 2 nhé).
- [x] Phần 2 có ≥ 2 quan sát hay, gắn với nhóm cụ thể.
- [x] Phần 3 có ≥ 2 điểm yếu / câu hỏi chưa được trả lời.
- [x] Phần 4 có ≥ 2 câu hỏi cụ thể cho nhóm khác.
- [x] Phần 5 có ≥ 2 bài học rút ra, kèm lý do và cách áp dụng lần sau.
