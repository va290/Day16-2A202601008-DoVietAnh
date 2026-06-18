---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** ISA — Trợ lý AI hỗ trợ Sinh viên Quốc tế & Hòa nhập (AI20K-C2-HE-14)  
**Người làm:** Đỗ Việt Anh — 2A202601008 (Trưởng nhóm)  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [ ] **1 nhóm người dùng chính**
- [ ] **1 hoàn cảnh / tình huống rõ**
- [ ] **1 job cốt lõi**
- [ ] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** ISA — web app chatbot RAG trả lời câu hỏi của SV quốc tế dựa trên tài liệu chính thức, luôn kèm trích dẫn, đa ngôn ngữ, có guardrail + escalation cho luồng pháp lý/visa.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp **SV quốc tế năm nhất (<3 tháng tại VN, chưa thạo tiếng Việt)** tự **làm đúng thủ tục cư trú/tạm trú đúng hạn** khi phải tra cứu **ngoài giờ hành chính**.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là hoàn cảnh đau nhất và rủi ro cao nhất (làm sai visa hậu quả lớn), đúng persona hẹp trong brief, và là nơi giá trị "trả lời chính thức có trích dẫn + biết khi nào chuyển người thật" của ISA khác biệt rõ nhất so với ChatGPT thuần.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > SV quốc tế năm nhất khó tìm **đúng** thông tin chính thức về thủ tục/sinh hoạt/học vụ **đúng lúc**, vì thông tin rải rác bằng tiếng Việt và hỗ trợ chỉ có trong giờ hành chính → dễ làm sai thủ tục, trễ hạn, hòa nhập chậm.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > SV quốc tế **năm nhất, < 3 tháng tại VN**, chưa thạo tiếng Việt, đang làm thủ tục cư trú lần đầu, hay tra cứu ngoài giờ hành chính.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Google dịch + tự lục nhiều trang web/PDF tiếng Việt của trường & cơ quan; hỏi bạn bè / nhóm Facebook SV quốc tế; hỏi ChatGPT (tiện nhưng dễ bịa, không nguồn); chờ đến giờ hành chính để hỏi Phòng CTSV/HTQT.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > SV quốc tế năm nhất mới sang Việt Nam, chưa thạo tiếng Việt, lần đầu tự xử lý thủ tục cư trú/học vụ.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi cần tra cứu/làm thủ tục **ngoài giờ hành chính** (tối, cuối tuần, sát deadline), thông tin lại rải rác bằng tiếng Việt và rủi ro làm sai cao (đặc biệt visa).

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Google dịch + tự lục web/PDF; nhóm Facebook/bạn bè SV; ChatGPT/Claude thuần; Phòng CTSV trong giờ hành chính.

4. **Vì sao đây là thời điểm đáng giải?**  
   > LLM + RAG nay đủ rẻ và đủ tốt để bám tài liệu chính thức, trích dẫn nguồn và trả lời đa ngôn ngữ 24/7 — điều mà chatbot FAQ cứng trước đây không làm được, còn ChatGPT thuần thì dễ bịa.

### Tóm tắt market context trong 3-4 dòng

> SV quốc tế năm nhất phải tự làm đúng các thủ tục rủi ro cao trong khi vừa kẹt rào cản ngôn ngữ, vừa chỉ được hỗ trợ trong giờ hành chính, vừa đối mặt thông tin rải rác. Các giải pháp hiện tại hoặc nhanh-nhưng-dễ-sai (ChatGPT, Google dịch), hoặc đúng-nhưng-chậm-và-giới-hạn-giờ (Phòng CTSV). Đây là lúc RAG có trích dẫn + escalation có thể vừa nhanh vừa đáng tin.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** SV quốc tế năm nhất (người trực tiếp tra cứu và tự làm thủ tục).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Chính họ là người gõ câu hỏi, đọc câu trả lời và đi nộp hồ sơ. Phòng CTSV/HTQT chỉ là **stakeholder/buyer giả định** định hướng sản phẩm, không phải người trực tiếp làm job; trường là tổ chức quá rộng. Người "đau" và hành động là SV.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [ ] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [ ] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [ ] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng chatbot AI để tra thủ tục cư trú ngoài giờ. _(còn lẫn solution)_

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: "chatbot AI", "tra" (thao tác trên tool)

### Bản chốt

**Core JTBD cuối cùng:**  
> Hoàn tất đúng một thủ tục cư trú/học vụ đúng hạn ngay khi cần, dù chưa thạo tiếng Việt và phải tự xoay ngoài giờ hỗ trợ.  
> _(verb: hoàn tất đúng · object: một thủ tục cư trú/học vụ · contextual clarifier: đúng hạn, khi chưa thạo tiếng Việt & ngoài giờ hỗ trợ — không có tên sản phẩm/AI; job vẫn tồn tại nếu bỏ ISA đi)_

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Vừa sang VN, phải đăng ký tạm trú trong vài ngày nhưng hướng dẫn toàn tiếng Việt | hiểu chính xác cần nộp giấy gì, ở đâu, hạn nào | làm đúng ngay lần đầu, không bị phạt/trễ hạn | Job xuất hiện lúc rủi ro cao, cần thông tin chính thức & rõ ràng |
| JS2 | Gặp vướng mắc vào tối/cuối tuần khi Phòng CTSV đã đóng cửa | có câu trả lời đáng tin ngay lập tức | không phải chờ tới giờ hành chính và lỡ deadline | Giá trị "24/7" — thay thế kênh chỉ-giờ-hành-chính |
| JS3 | Không chắc thông tin tìm trên Google/ChatGPT có đúng & còn hiệu lực không | thấy nguồn chính thức kèm câu trả lời | yên tâm hành động mà không sợ làm sai thủ tục rủi ro cao | Giá trị "trích dẫn nguồn" — khác biệt với ChatGPT thuần |

### Tự kiểm nhanh

- [ ] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [ ] 3 story không trùng hệt nhau
- [ ] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Google dịch + tự lục web/PDF trường | Tự tìm & dịch hướng dẫn thủ tục | Miễn phí, sẵn có | Rải rác, dễ dịch sai, không biết bản nào mới/chính thức | Thấp |
| Nhóm Facebook / bạn bè SV | Hỏi kinh nghiệm người đi trước | Đa ngôn ngữ, kinh nghiệm thật, gần gũi | Thông tin cũ/sai, không chính thống, không trích nguồn | Thấp |
| ChatGPT / Claude thuần | Hỏi đáp tức thì, đa ngôn ngữ | Nhanh, hội thoại tự nhiên, "may đo" câu trả lời | Dễ bịa, không bám tài liệu chính thức, không trích nguồn | Thấp |
| Phòng CTSV/HTQT (giờ hành chính) | Hỏi người thật, chính thống | Đáng tin, có thể xử lý ca khó | Chỉ giờ hành chính, rào cản ngôn ngữ, phải chờ/xếp hàng | Thấp–Trung |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> ChatGPT/Claude + Google dịch cho tốc độ, rồi hỏi nhóm SV để "kiểm chứng" — tức là chấp nhận rủi ro sai để đổi lấy phản hồi tức thì. Đây chính là alternative ISA phải thắng.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Hiểu mình cần làm thủ tục gì, hạn khi nào | Email/loáng thoáng từ bạn, trường | Không rõ mình phải làm gì & deadline | Med |
| Locate | Tìm đúng hướng dẫn & nguồn chính thức | Google, web/PDF trường, hỏi nhóm | Rải rác, tiếng Việt, không biết nguồn nào đúng & mới nhất | **High** |
| Prepare | Chuẩn bị đúng giấy tờ/điều kiện | Tự suy từ thông tin lượm được | Thiếu sót, hiểu sai do dịch máy | High |
| Confirm | Xác nhận mình hiểu đúng trước khi làm | Hỏi bạn / ChatGPT | Không ai đảm bảo đúng & còn hiệu lực; sợ sai | **High** |
| Execute | Nộp hồ sơ / đi làm thủ tục | Đến cơ quan / nộp online | Phần lớn ngoài phạm vi app; nhưng chuẩn bị sai sẽ fail ở đây | Med |
| Monitor | Theo dõi tiến độ & hạn | Tự nhớ | Quên hạn, không có checklist nhắc | Med |
| Modify | Xử lý khi bị thiếu/sai hồ sơ | Làm lại, hỏi lại | Mất thời gian, lặp vòng, stress | Med |
| Conclude | Biết chắc đã hoàn tất | Tự đoán | Không chắc đã đủ/đúng | Low–Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate — tìm đúng nguồn chính thức, cập nhật, bằng ngôn ngữ hiểu được  
**Bước đau nhất #2:** Confirm — xác nhận hiểu đúng & đáng tin trước khi hành động (rủi ro cao)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là 2 bước user tốn công và sợ sai nhất, và là gốc của mọi lỗi xuống dưới (Prepare/Execute sai vì Locate/Confirm sai).  
> Quan trọng hơn: đây đúng là chỗ ChatGPT thuần **fail** (bịa, không nguồn) — nên nếu ISA thắng ở Locate + Confirm thì mới có lý do tồn tại thay vì để user dùng ChatGPT.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Locate | RAG truy xuất & tóm tắt đúng đoạn tài liệu chính thức theo câu hỏi, đa ngôn ngữ, 24/7 | Đây là retrieval + dịch + tóm tắt — đúng thế mạnh LLM; pain cao | Retrieve sai đoạn / tài liệu KB cũ → trả lời lệch |
| Confirm | Trả lời kèm **trích dẫn nguồn chính thức** + guardrail: luồng pháp lý/visa thiếu nguồn → banner "tham khảo" + **escalation** sang người thật | Tăng độ tin, giảm hậu quả sai; AI giỏi tóm tắt-có-dẫn-nguồn; biết khi nào dừng | Hallucination ở luồng rủi ro cao → phải bắt buộc escalate khi thiếu nguồn |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước **Confirm**: câu trả lời bám tài liệu chính thức **có trích dẫn** + guardrail/escalation. Đây mới là giá trị lõi của ISA — không phải "trả lời nhanh" (ChatGPT đã làm được) mà là "trả lời **đúng, có nguồn, và biết khi nào chuyển người thật**".

**Vì sao không phải ở bước khác:**  
> Execute (nộp hồ sơ thực tế) nằm ngoài app; Define ít đau hơn và user thường đã biết đại khái phải làm gì. Locate quan trọng nhưng chỉ "tìm ra" thông tin là chưa đủ — với thủ tục rủi ro cao, user cần **tin** thông tin đó, nên Confirm (độ tin + escalation) mới là điểm quyết định họ rời ChatGPT.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **SV quốc tế năm nhất** làm đúng thủ tục cư trú/học vụ tốt hơn ở bước **Locate + Confirm**, bằng cách **trả lời RAG bám tài liệu chính thức kèm trích dẫn + guardrail/escalation, đa ngôn ngữ, 24/7**, thì họ sẽ chuyển từ **ChatGPT thuần + Google dịch + hỏi nhóm** sang **ISA**, vì đây là nơi duy nhất vừa **tức thì** vừa **đáng tin** (có nguồn chính thức và biết khi nào chuyển người thật).

### Tín hiệu sớm nếu hypothesis này đúng

1. Tỉ lệ câu trả lời kèm trích dẫn cao và user **bấm xem nguồn** thường xuyên (groundedness + tin tưởng).
2. Phần lớn câu hỏi rơi vào **ngoài giờ hành chính** và user **quay lại** lần sau (retention) — chứng tỏ ISA đang thay kênh cũ.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1 — Đúng job executor: SV năm nhất **tự** tra & làm thủ tục | Có thể họ nhờ buddy/người bản địa làm hộ → ISA chệch người dùng | Suy luận từ persona trong brief, chưa có data thật | Phỏng vấn nhanh 5 SV quốc tế: ai thực sự thao tác? |
| A2 — SV tra cứu **ngoài giờ hành chính** đủ thường xuyên | Nếu không, giá trị 24/7 giảm mạnh | Giả định trong user-research §5 | Đo **log thời điểm hỏi** |
| A3 — Trích dẫn nguồn đủ để khiến SV **rời ChatGPT/Google dịch** | Họ có thể vẫn ưu tiên tốc độ & thói quen ChatGPT | Suy luận, chưa kiểm | A/B có vs không trích dẫn; đo retention/feedback |
| A4 — Bộ tài liệu công khai phủ **≥80%** câu hỏi (AI thật sự tạo giá trị ở Locate) | KB thiếu → answer_rate thấp → phải escalate nhiều → mất giá trị | Giả định trong user-research §5 | Đo **answer_rate** qua bộ eval có version |
| A5 — User đủ tin AI ở thủ tục **rủi ro cao (visa)** để hành động | Với visa họ có thể vẫn chỉ tin người thật | Chưa có | Đo **escalation_precision** + interview |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A3 + A4**: nếu trích dẫn nguồn không đủ khiến SV rời ChatGPT, hoặc KB không phủ đủ câu hỏi, thì khác biệt cốt lõi của ISA sập — user sẽ ở lại với ChatGPT "đủ tốt và quen tay". Đây là giả định phải kiểm sớm nhất.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _(điền sau khi nghe bàn phản biện tại lớp)_

### Version cuối cùng tôi nộp

**Job executor:**  
> SV quốc tế năm nhất (<3 tháng tại VN, chưa thạo tiếng Việt) — người trực tiếp tra cứu và tự làm thủ tục.

**Core JTBD:**  
> Hoàn tất đúng một thủ tục cư trú/học vụ đúng hạn ngay khi cần, dù chưa thạo tiếng Việt và phải tự xoay ngoài giờ hỗ trợ.

**2 bước đau nhất trong workflow:**  
> Locate (tìm đúng nguồn chính thức & cập nhật) và Confirm (xác nhận hiểu đúng, đáng tin trước khi hành động).

**AI leverage point chính:**  
> Bước Confirm — trả lời bám tài liệu chính thức **có trích dẫn** + guardrail/escalation cho luồng pháp lý/visa; đây là điểm khác biệt so với ChatGPT thuần.

**Product hypothesis:**  
> Nếu giúp SV quốc tế năm nhất làm đúng thủ tục tốt hơn ở Locate + Confirm bằng RAG có trích dẫn + escalation đa ngôn ngữ 24/7, họ sẽ chuyển từ ChatGPT + Google dịch + hỏi nhóm sang ISA, vì đây là nơi duy nhất vừa tức thì vừa đáng tin.

**Assumption cần validate đầu tiên:**  
> Trích dẫn nguồn chính thức có đủ khiến SV rời ChatGPT không (A3) — và KB có phủ ≥80% câu hỏi không (A4). Kiểm bằng A/B trích dẫn + đo answer_rate qua bộ eval.

---

## Checklist trước khi nộp

- [ ] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [ ] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [ ] `Core JTBD` của tôi không nhét solution vào câu.
- [ ] Tôi đã viết đủ 3 `job stories`.
- [ ] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [ ] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [ ] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
