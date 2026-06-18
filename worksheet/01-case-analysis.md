---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** Stack Overflow  
**Người làm:** Đỗ Việt Anh — 2A202601008  
**Bàn / nhóm bàn:** _______________  
**Ngày:** 2026-06-18

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [ ] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [ ] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [ ] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [ ] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** Stack Overflow (Q&A cho lập trình viên)
- **AI / platform / sản phẩm mới tạo áp lực:** ChatGPT (ra mắt 11/2022) và các trợ lý code (GitHub Copilot, Gemini, Claude) — đều huấn luyện một phần trên chính dữ liệu Stack Overflow
- **Vì sao tôi chọn case này?**  
  > Đây là ví dụ rõ nhất về **hiệu ứng mạng bị đảo chiều**: moat của Stack Overflow là kho Q&A cộng đồng, nhưng AI học từ chính kho đó rồi trả lời trực tiếp, khiến số câu hỏi mới sụp đổ. Bằng chứng công khai dày (Data Explorer, Similarweb, thông báo sa thải), dễ chứng minh "thay đổi vĩnh viễn".

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | **Moat trước AI**: Stack Overflow "gamify" việc lập trình viên giúp nhau trả lời, tạo kho Q&A cộng đồng khổng lồ đầu thập niên 2010 → network effect (càng nhiều câu hỏi/đáp, càng hữu ích, càng kéo thêm user). | Xác định giá trị lõi & moat *trước* AI — gốc của mọi tổn thương sau này. | The Pragmatic Engineer — "Stack Overflow is almost dead" (blog.pragmaticengineer.com) |
| E2 | **AI shock**: ChatGPT ra mắt 11/2022; "ngay khi ChatGPT xuất hiện, số câu hỏi mới giảm rất nhanh". | Mốc đổi luật chơi rõ ràng, gắn trực tiếp với điểm gãy của đường cong câu hỏi. | The Pragmatic Engineer; dữ liệu từ Marc Gravell & Stack Overflow Data Explorer (SEDE) |
| E3 | **Câu hỏi mới sụp đổ**: 87.000 (3/2023) → 58.800 (3/2024) = **-32,5% YoY**; tới 12/2024 **-40% YoY**, về mức thấp như năm 2009; tổng giảm ~**76%** kể từ khi ChatGPT ra mắt. | Bằng chứng định lượng mạnh nhất cho thấy "động cơ nội dung" của SO đang tắt. | ericholscher.com (1/2025); Slashdot/ByteIota tổng hợp từ SEDE |
| E4 | **Traffic giảm sớm và sâu**: tới 4/2023 (5 tháng sau ChatGPT) traffic đã -14% YoY; ước tính Similarweb cho thấy traffic mất ~**75%** so với đỉnh. | Cho thấy không chỉ người hỏi rời đi mà cả người đọc — đúng kiểu phân khúc bị tái cấu trúc. | Similarweb (qua ppc.land, devclass 5/2025) |
| E5 | **Phản ứng tổ chức**: 10/2023 Stack Overflow sa thải **28% nhân sự** (~100 người), pivot mạnh sang sản phẩm AI doanh nghiệp (OverflowAI); 2025 tìm cách "rebrand". | Tác động tới chính công ty, và cho thấy họ thừa nhận mô hình cũ không còn đủ. | devclass (5/2025); Slashdot (1/2025) — *nguồn cấp 2, nên kiểm chéo thông báo gốc của SO nếu có thời gian* |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > network effect của kho Q&A cộng đồng: câu trả lời cũ được tái sử dụng hàng triệu lần qua Google, giữ SO ở entry point khi lập trình viên "bị kẹt". (E1)
2. **AI shock làm thay đổi...**  
   > entry point: thay vì search → click SO, lập trình viên hỏi thẳng ChatGPT/Copilot ngay trong IDE và nhận câu trả lời "may đo", tức thì. (E2)
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > số câu hỏi *mới* giảm ~76% về mức 2009 — vòng lặp đóng góp nội dung đang tắt, không chỉ là traffic giảm tạm thời. (E3, E4)

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> JTBD của user là **"giúp tôi gỡ kẹt một lỗi/câu hỏi lập trình cụ thể, nhanh và đáng tin"**. Trước AI, Stack Overflow thắng nhờ giả định: cách nhanh nhất để có câu trả lời đáng tin là *tìm trong kho câu hỏi mà người khác đã hỏi và được cộng đồng vote*. Moat = network effect + SEO (gần như mọi truy vấn lỗi đều dẫn về SO) + uy tín chấm điểm cộng đồng. Họ bán "đúng câu trả lời đã được kiểm chứng", không phải "trò chuyện".  
> Giả định ngầm: user *chấp nhận* chi phí tự diễn giải — tự viết lại câu hỏi, đọc nhiều câu trả lời, lọc cái hợp ngữ cảnh của mình.

**Bằng chứng đỡ nhận định này:** E1, E2

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** #2 May đo cho tôi + #5 Phản hồi ngay + #7 Thấu hiểu ngữ cảnh  
**Competitive dynamic quan trọng nhất:** build-copy cycles tăng tốc + switching costs giảm (AI học từ chính dữ liệu SO rồi trả lời thay)

**Trả lời của tôi:**  
> Kỳ vọng đổi từ "tôi tự tìm câu trả lời chung trong kho" sang **"trả lời thẳng vào đúng đoạn code của tôi, ngay lập tức, không phải tự lọc"**. ChatGPT/Copilot dán code lỗi vào là có lời giải "may đo" trong vài giây, ngay trong IDE — đúng 3 shift #2/#5/#7.  
> Về luật chơi: moat dữ liệu của SO bị **đảo chiều** — chính kho Q&A công khai trở thành dữ liệu huấn luyện cho đối thủ, nên build-copy gần như tức thì; đồng thời switching cost của user ≈ 0 vì không cần tài khoản, không cần học cách hỏi đúng chuẩn SO.

**Bằng chứng đỡ nhận định này:** E2, E3

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> Giả định chết: *"khi kẹt code, lập trình viên sẽ tìm tới một trang Q&A công khai do người khác viết"*. Entry point đã dời hẳn vào **hội thoại với AI ngay trong công cụ làm việc (IDE/chatbot)** và rất khó quay lại — đây là **chuẩn mới trong đầu user**, không phải biến động tạm thời.  
> Quan trọng hơn: vòng phản hồi cộng đồng (hỏi → đáp → tích lũy nội dung mới) bị phá. Câu hỏi mới -76% nghĩa là chính nguồn dữ liệu tươi mà cả SO lẫn các model phụ thuộc đang cạn — đây là tổn thương cấu trúc, không cứu bằng marketing được. Switching cost cũ (uy tín, SEO, thói quen) không giữ được vì AI cho câu trả lời "may đo" nhanh hơn hẳn.

**Bằng chứng đỡ nhận định này:** E3, E4

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh

**Trả lời của tôi:**  
> Dạng "Q&A công khai cho con người" thì khó hồi sinh — quá muộn vì entry point đã mất. Nhưng công ty *có thể* sống nếu đổi moat: (1) trở thành **nguồn dữ liệu/ground-truth được cấp phép cho các hãng AI** (đã có thương vụ license dữ liệu); (2) làm **knowledge base nội bộ + Q&A có kiểm chứng cho doanh nghiệp** (OverflowAI) nơi độ tin cậy và quyền riêng tư quan trọng hơn tốc độ; (3) thành **lớp xác minh/curation** đứng trên câu trả lời AI.  
> So với đối thủ phản ứng tốt hơn (GitHub nhúng Copilot thẳng vào IDE — đúng nơi user làm việc), SO chậm vì vẫn ở mô hình "web destination" mà user phải rời công cụ để ghé thăm.

**Bằng chứng đỡ nhận định này:** E1, E5

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì AI học từ chính kho Q&A của SO rồi trả lời "may đo" ngay trong IDE, làm sụp đổ vòng đóng góp câu hỏi mới (-76%) và đảo chiều network effect.  
2. Điều thay đổi vĩnh viễn là entry point khi "kẹt code" đã dời từ trang web công cộng sang hội thoại AI tại chỗ — chuẩn mới trong đầu lập trình viên.  
3. Verdict của tôi là **Có nhưng phải đổi rất mạnh**: chỉ sống nếu chuyển từ "Q&A cho người" sang nguồn dữ liệu được cấp phép / lớp xác minh & KB doanh nghiệp.

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Bạn 1 | Stack Overflow (Q&A cho lập trình viên) | User/traffic sụt ~70% | AI trả lời & giải quyết vấn đề cho lập trình viên, thay thế được SO | Không cứu được; chỉ có thể tận dụng cơ sở dữ liệu riêng để làm hướng khác |
| Bạn 2 (Nguyễn Lê Văn) | Chegg (giải đáp bài tập) | Cổ phiếu **−48% trong 1 phiên (02/05/2023)**; người dùng **7,8M → 3,2M** (2024); sa thải gần nửa nhân sự (2024) | "Entry point" học tập chuyển từ Google Search sang AI prompt → sụp đổ lợi thế SEO + kho dữ liệu tĩnh; "pay to get solution" không còn hợp lý | Chỉ sống nếu chuyển từ "bán lời giải có sẵn" sang **"AI gia sư" cá nhân hóa**, dùng dữ liệu chuyên gia để thắng AI phổ thông về độ chính xác/tin cậy |
| Bạn 3 | Teleperformance (BPO/CSKH, thâm dụng lao động) | Klarna dùng AI làm **2/3 lượng phản hồi**, thời gian phản hồi **11 phút → 2 phút** → cổ phiếu Teleperformance **−29%** | CSKH chuyển sang AI để tối ưu chi phí nhân sự & thời gian phản hồi | Sự sụp đổ của FTE truyền thống; phải chuyển sang **hybrid (AI + Human)** |
| Bạn 4 | Upwork (nền tảng kết nối freelancer) | Nhu cầu viết/dịch **−21%…−33%**; cổ phiếu **−17% (5/2026)**; bùng nổ bot spam proposal | Kỳ vọng client chuyển từ "thuê rẻ" sang **"tự gõ prompt lấy ngay"** | Có nhưng phải đổi rất mạnh: tập trung **chuyên gia cao cấp & Super-Freelancer dùng AI** |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> Case Chegg. Vì số liệu tài chính và người dùng bị ảnh hưởng trực tiếp, nghiêm trọng nhất trên quy mô cực lớn: cổ phiếu bốc hơi ~48% chỉ trong 1 phiên ngay sau khi CEO thừa nhận tác động của ChatGPT, thuê bao trả phí sụt >50% (7,8M → 3,2M), và phải sa thải gần một nửa nhân sự năm 2024.

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> - **Switching cost sụp đổ nhanh**: user sẵn sàng bỏ giải pháp cũ (Stack Overflow, Chegg, Upwork) để tự dùng AI khi AI phản hồi tức thì và miễn phí.  
> - **Sụp đổ mô hình thâm dụng lao động / dữ liệu tĩnh**: trả phí để nhận kết quả tĩnh, hoặc thuê người làm việc lặp lại, không còn hiệu quả kinh tế so với AI.

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> Tránh xây sản phẩm giải quyết vấn đề quá đơn giản, dễ bị tự động hóa bằng công cụ AI phổ thông có sẵn. Phải tìm ra điểm chạm mà AI không tự làm một mình được — cần thẩm định, kiểm chứng, hoặc quy trình nghiệp vụ đặc thù.

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [x] Giữ nguyên
- [ ] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Phản biện trong bàn (case Chegg) củng cố thêm chứ không bác bỏ verdict của tôi: cùng một pattern — sản phẩm bán "câu trả lời/lời giải" bị AI cung cấp miễn phí và "may đo", buộc phải đổi định vị (Chegg → "suggest solution" giúp SV tránh phụ thuộc; SO → nguồn dữ liệu cấp phép / lớp xác minh). Bằng chứng định lượng của Stack Overflow vẫn vững nên tôi giữ nguyên verdict.

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> Moat của SO là network effect quanh kho Q&A công khai, nhưng AI được huấn luyện trên chính kho đó rồi trả lời "may đo", tức thì, ngay trong IDE — switching cost về 0, vòng đóng góp câu hỏi mới sụp đổ (-76%), traffic mất ~75%.

**Điều thay đổi vĩnh viễn là:**  
> Entry point khi lập trình viên "kẹt code" đã dời hẳn từ trang web công cộng sang hội thoại với AI tại chỗ. Đây là chuẩn kỳ vọng mới (#2 "may đo", #5 phản hồi ngay, #7 hiểu ngữ cảnh), không phải biến động ngắn hạn.

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Đừng dựng moat trên dữ liệu/nội dung công khai mà AI có thể học rồi phục vụ thẳng cho user. Phải bám **đúng nơi user đang làm việc** (in-workflow) và sở hữu thứ AI không tự sao chép được: dữ liệu độc quyền/được cấp phép, ngữ cảnh riêng tư, hoặc lớp xác minh đáng tin.

---

## Checklist trước khi nộp

- [ ] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [ ] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [ ] Tôi đã ghi lại phần share trong bàn.
- [ ] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

- Bổ sung thêm một case "đối thủ phản ứng tốt hơn" để so.
- Thêm một đoạn ngắn: **nếu tôi là PM của case này trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?**
- Kiểm lại xem case này yếu vì expectation shift, competitive dynamics, hay cả hai cùng lúc.
