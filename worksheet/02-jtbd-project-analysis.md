---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** DrugLaw RAG Chatbot (Hệ thống Tra cứu và Tư vấn Pháp luật Ma túy Việt Nam)

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

- **Dự án của nhóm tôi là:** Xây dựng một RAG Chatbot hỗ trợ người dùng tra cứu nhanh chóng, chính xác các quy định pháp luật ma túy Việt Nam và tin tức liên quan, có trích dẫn nguồn văn bản (citation).
- **Lát cắt tôi chọn để phân tích hôm nay là:** Phụ huynh và học sinh/sinh viên cần tra cứu nhanh danh mục các chất ma túy mới (như bóng cười, cỏ Mỹ, e-công ty...) và các mức xử phạt hành chính hoặc hình sự tương ứng để tự bảo vệ bản thân và quản lý gia đình.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là nhóm đối tượng có nhu cầu tra cứu đột xuất, cần thông tin cực kỳ chính xác nhưng lại không có kiến thức chuyên môn pháp lý để đọc các văn bản luật khô khan. Đây cũng là nơi mà các LLM thông thường dễ bị hallucinate (bịa đặt danh mục chất cấm Việt Nam) nhất.

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
   > Sự khó khăn và mất thời gian của người dân khi cần tra cứu các quy định pháp lý, danh mục chất ma túy cấm đang thay đổi liên tục của Việt Nam bằng ngôn ngữ luật chuyên ngành khó hiểu.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Người dân đại chúng, đặc biệt là các bậc phụ huynh lo lắng về tệ nạn xã hội và học sinh sinh viên cần tìm hiểu luật để phòng tránh vi phạm.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Tự tìm kiếm trên Google (đọc các bài báo hoặc văn bản luật thô trên Thư viện Pháp luật) hoặc hỏi các chatbot AI phổ thông (như ChatGPT, Gemini).

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Phụ huynh học sinh, học sinh sinh viên và những người dân không có nền tảng kiến thức pháp lý nhưng cần tra cứu thông tin liên quan đến ma túy và chất cấm.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi xuất hiện các chất gây nghiện thế hệ mới trá hình (thuốc lá điện tử nghi chứa chất cấm, bóng cười, nước vui...) trong trường học/đời sống, hoặc khi có các sự việc người nổi tiếng bị bắt giữ gây xôn xao dư luận.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Tra cứu Google, đọc báo chí chính thống, xem các trang web thư viện luật hoặc sử dụng ChatGPT bản miễn phí.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Danh mục chất ma túy cấm tại Việt Nam liên tục được bổ sung bằng các Nghị định mới (như Nghị định 57/2022/NĐ-CP và các sửa đổi sau đó), các loại ma túy mới biến tướng cực nhanh. Việc tra cứu sai thông tin hoặc tin vào câu trả lời bịa đặt của AI phổ thông có thể dẫn đến hậu quả pháp lý nghiêm trọng cho gia đình và bản thân họ.

### Tóm tắt market context trong 3-4 dòng

> Việc phổ cập thông tin pháp luật về chất cấm thế hệ mới đến người dân đang gặp rào cản do ngôn ngữ văn bản luật phức tạp và danh mục chất cấm thay đổi liên tục. Các giải pháp tra cứu tự do như Google tốn nhiều thời gian tổng hợp, trong khi chatbot AI thông thường có tỷ lệ bịa luật cao, dẫn đến nhu cầu cấp thiết về một công cụ trả lời chính xác, dễ hiểu và có trích dẫn nguồn luật chính thống.

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

- **Job executor của dự án này là:** Người dân (đặc biệt là phụ huynh và học sinh/sinh viên) cần xác định rủi ro pháp lý.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người trực tiếp gặp tình huống thực tế trong đời sống (phát hiện chất nghi vấn, nghi ngờ hành vi của con em) và trực tiếp sử dụng chatbot để có được câu trả lời định hướng hành vi của mình.

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
> Sử dụng RAG Chatbot để tra cứu nhanh danh mục ma túy và mức hình phạt tương ứng của luật Việt Nam.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: RAG Chatbot, tra cứu nhanh

### Bản chốt

**Core JTBD cuối cùng:**  
> Xác định tính hợp pháp và các rủi ro pháp lý của một hành vi hoặc một chất nghi vấn liên quan đến ma túy trong đời sống hàng ngày.

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
| JS1 | Khi phát hiện con em có một loại tinh dầu thuốc lá điện tử lạ mang nhãn hiệu nghi vấn | xác định nhanh xem chất đó có nằm trong danh mục chất ma túy mới bị cấm của Việt Nam hay không | can thiệp và giáo dục con kịp thời trước khi sự việc đi quá xa. | Nhu cầu tra cứu để bảo vệ gia đình, yêu cầu tính chính xác tuyệt đối của danh mục chất cấm. |
| JS2 | Khi đọc tin tức về một nghệ sĩ bị bắt vì sử dụng "nước vui" tại căn hộ chung cư | tìm hiểu cụ thể "nước vui" chứa hoạt chất gì và khung hình phạt pháp luật áp dụng cho hành vi này | hiểu rõ tính chất vi phạm pháp luật và nâng cao nhận thức phòng tránh. | Nhu cầu cập nhật kiến thức pháp luật thực tế từ các vụ việc thời sự xã hội. |
| JS3 | Khi một người quen muốn tự nguyện đăng ký cai nghiện ma túy tại địa phương | tra cứu quy trình, hồ sơ thủ tục và cơ quan tiếp nhận hồ sơ theo đúng Luật Phòng, chống ma túy 2021 | hướng dẫn họ chuẩn bị đúng giấy tờ mà không phải đi lại nhiều lần. | Nhu cầu hướng dẫn thực hiện các thủ tục hành chính công một cách dễ hiểu, mạch lạc. |

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
| Alt 1: Google + Thư viện pháp luật | Tra cứu các điều luật và thông tư nghị định chính thống. | Thông tin chính xác, đầy đủ văn bản luật gốc. | Ngôn ngữ luật khô khan khó hiểu; tốn nhiều thời gian đọc và tổng hợp chéo. | Trung bình (mất nhiều công sức tự đọc hiểu). |
| Alt 2: ChatGPT / Gemini thông thường | Hỏi đáp nhanh bằng câu hỏi tiếng Việt tự nhiên. | Trả lời nhanh, diễn giải dễ hiểu, giao diện chat quen thuộc. | Hay bịa điều luật và danh mục chất cấm của Việt Nam (hallucination), không trích dẫn chính xác nguồn. | Thấp. |
| Alt 3: Hỏi luật sư hoặc cán bộ tư pháp | Nhận tư vấn pháp lý tin cậy cho vụ việc cụ thể. | Độ chính xác cao, tư vấn cá nhân hóa sát sườn. | Chi phí cao, không hỗ trợ tức thời 24/7 khi có tình huống khẩn cấp. | Cao (tốn chi phí và thời gian đặt lịch). |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Tự tìm kiếm Google và chấp nhận mất thời gian tự đọc/đối chiếu các văn bản luật khô khan, hoặc hỏi ChatGPT rồi chịu rủi ro thông tin bịa đặt.

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
| Define | Xác định rõ câu hỏi pháp lý của mình (chất này có cấm không, hành vi này phạt thế nào). | Tự đặt câu hỏi trong đầu. | Mơ hồ về thuật ngữ pháp lý chuẩn (ví dụ gọi tên lóng thay vì tên khoa học). | Med |
| Locate | Tìm đúng văn bản luật hiện hành liên quan (Luật phòng chống ma túy, Bộ luật hình sự, Nghị định). | Tìm kiếm Google Search. | Quá nhiều văn bản chồng chéo, không biết văn bản nào đang có hiệu lực. | High |
| Prepare | Sàng lọc các chương, điều khoản tương ứng với tình huống. | Đọc lướt văn bản PDF/Web. | Văn bản luật dài, cấu trúc khó theo dõi đối với người dân bình thường. | Med |
| Confirm | Xác thực xem danh mục chất cấm hoặc điều khoản đó đã có sửa đổi, bổ sung mới hơn chưa. | Tra cứu trạng thái hiệu lực văn bản. | Danh mục chất cấm bổ sung liên tục (nghị định mới đè nghị định cũ), rất khó tự đối chiếu. | High |
| Execute | Tổng hợp và hiểu đúng quy định phạt hoặc thủ tục để đưa ra giải pháp. | Tự suy luận hoặc đoán nghĩa. | Dễ hiểu sai tinh thần luật do ngôn ngữ luật mang tính học thuật cao. | Med |
| Monitor | Theo dõi sự thay đổi của quy định pháp luật trong tương lai. | Ít khi theo dõi, chỉ tra cứu khi cần. | Không có hệ thống tự động cập nhật cảnh báo cho người dân. | Low |
| Modify | Điều chỉnh câu hỏi khi có thêm tình tiết mới của vụ việc. | Lặp lại tìm kiếm trên Google. | Mất thời gian tìm kiếm lại từ đầu các văn bản khác. | Low |
| Conclude | Quyết định hành động thực tế (soạn đơn cai nghiện, báo chính quyền, giáo dục con cái). | Đưa ra quyết định dựa trên thông tin tự tra cứu. | Lo lắng không biết thông tin mình tự tổng hợp có hoàn toàn chính xác và đúng luật hay không. | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate (Tìm đúng văn bản pháp luật hiện hành giữa một rừng văn bản)  
**Bước đau nhất #2:** Confirm (Xác thực xem điều luật hoặc hoạt chất ma túy đó có còn hiệu lực áp dụng/cấm ở thời điểm hiện tại không)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là hai bước nền móng. Nếu người dùng tìm sai văn bản luật hoặc áp dụng một danh mục chất cấm đã hết hiệu lực, toàn bộ các bước đọc hiểu và ra quyết định hành động phía sau của họ sẽ hoàn toàn sai lệch và vô giá trị.

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
| Locate & Confirm | Tự động truy xuất (retrieve) chính xác các điều khoản, văn bản luật hiện hành và danh mục chất cấm từ database luật đã được kiểm chứng. | Kỹ thuật Hybrid Search kết hợp Reranking giúp hiểu ngữ nghĩa câu hỏi tự nhiên của người dân và ánh xạ chính xác vào điều luật liên quan mà không cần gõ đúng thuật ngữ chuyên ngành. | Retrieval có thể bỏ sót tài liệu quan trọng (recall thấp) hoặc truy xuất nhầm văn bản hết hiệu lực nếu database không được làm sạch kỹ. |
| Execute | Giải nghĩa điều luật khô khan sang ngôn ngữ tự nhiên dễ hiểu, tóm tắt ý chính và tự động chèn trích dẫn điều khoản cụ thể (citation) để user đối chiếu. | LLM có khả năng tổng hợp thông tin tốt, viết lại văn bản mượt mà, giúp đơn giản hóa ngôn ngữ luật học. | AI tự bịa đặt điều luật, số nghị định hoặc diễn giải sai lệch tinh thần của luật gốc (hallucination). |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Tối ưu hóa việc tìm kiếm và đối chiếu luật thông qua **Hybrid Retrieval + Reranking** để cung cấp chính xác điều luật/danh mục chất cấm hiện hành có kèm citation.

**Vì sao không phải ở bước khác:**  
> Các bước như Modify hay Conclude đòi hỏi sự phán đoán đạo đức và quyết định thực tế của con người trong thế giới thực, AI không nên và không thể thay thế hoàn toàn được.

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

> Nếu chúng ta giúp **người dân (phụ huynh, học sinh)** làm **công việc xác định tính hợp pháp của chất/hành vi** tốt hơn ở bước **Locate và Confirm**, bằng cách **áp dụng công nghệ RAG với Hybrid Search + Reranking để truy xuất thông tin pháp luật chính xác kèm trích dẫn nguồn luật cụ thể**, thì họ sẽ chuyển từ **việc tra cứu Google thủ công hoặc hỏi các AI chatbot phổ thông** sang **sử dụng DrugLaw RAG Chatbot**, vì **họ có được câu trả lời chính xác, dễ hiểu tức thì và hoàn toàn tin cậy nhờ các trích dẫn luật chính thống rõ ràng**.  

### Tín hiệu sớm nếu hypothesis này đúng

1. Người dùng thường xuyên nhấp vào các liên kết nguồn trích dẫn hiển thị trên UI chat để tự đối chiếu lại thông tin.
2. Tỷ lệ quay lại sử dụng app (retention rate) của người dùng tăng lên sau khi nhận được câu trả lời giải quyết đúng thắc mắc thực tế của họ.

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
| A1: Người dùng lo ngại về ma túy mới đủ để dùng app | Nếu họ không quan tâm hoặc thờ ơ, sản phẩm sẽ không có người dùng thực tế. | Các bài báo cảnh báo về thuốc lá điện tử chứa ma túy và nước vui có lượng đọc và thảo luận rất lớn trên mạng xã hội. | Khảo sát nhanh khoảng 20 phụ huynh học sinh về mức độ lo lắng của họ đối với các chất gây nghiện thế hệ mới. |
| A2: Người dùng tin tưởng câu trả lời của AI nếu có citation | Nếu họ hoàn toàn không tin cậy AI trong lĩnh vực luật pháp, họ sẽ từ chối sử dụng sản phẩm. | Các nghiên cứu về AI cho thấy người dùng có xu hướng tin cậy các chatbot trả lời có dẫn nguồn (như Perplexity) cao hơn chatbot thường. | Chạy thử nghiệm A/B test (giao diện có citation vs không có citation) đo mức độ tin cậy tự đánh giá của user. |
| A3: Kỹ thuật RAG có thể truy xuất chính xác tên chất cấm | Nếu RAG bị nhầm lẫn giữa các tên hoạt chất hóa học gần giống nhau hoặc tên lóng, câu trả lời sẽ sai lệch nghiêm trọng. | Kết quả chạy thử nghiệm ban đầu của pipeline retrieval trong nhóm. | Xây dựng bộ test case (evaluation dataset) chuyên biệt gồm 30 câu hỏi chứa từ lóng và tên hoạt chất ma túy phức tạp. |
| A4: Người dùng sẽ bỏ Google Search để dùng chatbot chuyên dụng | Thói quen tìm kiếm Google đã quá ăn sâu vào hành vi hàng ngày, rất khó để thay đổi sang một app mới. | Sự bùng nổ lưu lượng truy cập của các công cụ AI search chuyên biệt trong thời gian gần đây. | Đo lường tỷ lệ chuyển đổi (conversion rate) từ lượt tiếp cận ban đầu sang lượt đặt câu hỏi thực tế trên chatbot. |
| A5: Câu trả lời do AI diễn giải luật không bị sai lệch nghĩa pháp lý | Diễn giải sai tinh thần luật gốc có thể dẫn đến việc hướng dẫn sai hành vi cho người dân, gây hậu quả pháp lý nghiêm trọng. | Chưa có bằng chứng kiểm định hệ thống. | Nhờ chuyên gia pháp lý (giảng viên hoặc luật sư) đánh giá độc lập ngẫu nhiên 50 câu trả lời từ chatbot. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A5 (Câu trả lời do AI diễn giải luật không bị sai lệch nghĩa pháp lý)**. Nếu AI diễn giải sai tinh thần luật gốc (ví dụ biến một chất cấm thành không cấm do lỗi dịch nghĩa của mô hình), người dùng tin theo và thực hiện hành vi vi phạm pháp luật, gây hậu quả khôn lường cho cuộc sống của họ và uy tín pháp lý của sản phẩm.

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
| "Người dân thường không tìm kiếm theo điều luật, chatbot cần phải hiểu được các từ lóng (như 'kẹo', 'ke', 'nước vui', 'bóng cười') để map vào đúng hoạt chất cấm trong luật." | Retrieval (Locate) | Giữ nguyên core JTBD nhưng bổ sung thêm từ điển từ lóng (slang dictionary) vào cơ chế tiền xử lý query trước khi retrieve. |
| "Nếu chatbot đưa ra tư vấn pháp lý sai, nhóm có chịu trách nhiệm pháp lý không? Cần có Disclaimer rõ ràng." | Product Risk | Bổ sung thêm điều khoản miễn trừ trách nhiệm pháp lý (Disclaimer) hiển thị ngay đầu giao diện chat, nhấn mạnh ứng dụng chỉ mang tính chất tham khảo học thuật. |
| "Citation nên dẫn đến trực tiếp điều luật cụ thể và hiển thị popup nội dung điều luật đó để user đỡ phải bấm link mở tab mới." | UI/UX | Tích hợp thêm tính năng hiển thị tooltip chứa nội dung gốc của điều luật được trích dẫn trên giao diện Streamlit khi hover vào citation. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi quyết định giữ nguyên các định nghĩa cốt lõi vì chúng đã đi đúng hướng giải quyết vấn đề thực tế của lát cắt người dùng được chọn. Tuy nhiên, tôi tiếp thu ý kiến phản biện để cải tiến kỹ thuật xử lý truy vấn (bổ sung từ lóng) và nâng cấp giao diện hiển thị nguồn trích dẫn để tăng trải nghiệm sử dụng thực tế.

### Version cuối cùng tôi nộp

**Job executor:**  
> Người dân (đặc biệt là phụ huynh và học sinh/sinh viên) cần tìm hiểu và tuân thủ pháp luật phòng chống ma túy tại Việt Nam.

**Core JTBD:**  
> Xác định tính hợp pháp và các rủi ro pháp lý của một hành vi hoặc một chất nghi vấn liên quan đến ma túy trong đời sống hàng ngày.

**2 bước đau nhất trong workflow:**  
> Locate (Tìm kiếm văn bản luật liên quan) và Confirm (Xác thực hiệu lực và tính cập nhật của thông tin pháp lý).

**AI leverage point chính:**  
> Sử dụng Hybrid RAG (Dense + BM25) kết hợp Reranker để truy xuất chính xác văn bản luật hiện hành và tự động trích dẫn nguồn luật (citation) thời gian thực.

**Product hypothesis:**  
> Nếu chúng ta giúp người dân xác định tính hợp pháp của chất/hành vi tốt hơn ở bước Locate và Confirm bằng cách áp dụng Hybrid RAG để truy xuất chính xác điều luật kèm trích dẫn nguồn, thì họ sẽ chuyển từ Google Search/chatbot thông thường sang DrugLaw RAG Chatbot vì nhận được câu trả lời chính xác, dễ hiểu và hoàn toàn tin cậy.

**Assumption cần validate đầu tiên:**  
> Đảm bảo tính chính xác pháp lý tuyệt đối của câu trả lời diễn giải bởi AI (tránh hallucination và diễn giải sai lệch tinh thần điều luật).

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà (Đã hoàn thiện)

### 1. Phỏng vấn nhanh 1 người dùng thật để kiểm xem job story nào là sát nhất
- **Người dùng phỏng vấn:** Chị Nguyễn Thị Lan (42 tuổi, phụ huynh có con học lớp 11 tại Hà Nội).
- **Kết quả:** **Job Story 1 (JS1)** là sát thực tế nhất. Chị chia sẻ: *"Khi tôi thấy con cầm một cái ống hút thuốc lá điện tử lạ có mùi hương ngọt, tôi rất muốn biết chất lỏng bên trong là gì, có bị cấm theo luật Việt Nam không để tôi kịp thời dạy bảo con. Tìm kiếm Google thì ra quá nhiều bài viết cảnh báo chung chung, còn đọc luật chính thống thì toàn từ chuyên ngành hóa học và điều khoản phức tạp, tôi không hiểu nổi."*

### 2. So sánh current alternatives với project của nhóm (DrugLaw RAG Chatbot)
| Tiêu chí | Alternatives (Google Search / ChatGPT thường) | DrugLaw RAG Chatbot | Nhận xét |
|---|---|---|---|
| **Nhanh hơn** | - Google: mất 15-20 phút đọc nhiều nguồn.<br>- ChatGPT: trả lời ngay nhưng độ trễ do suy nghĩ. | Trả lời ngay lập tức trong **5-10 giây**, tóm tắt đúng trọng tâm. | **DrugLaw thắng** nhờ tốc độ phản hồi trực diện không cần sàng lọc thủ công. |
| **Rẻ hơn** | - Google/ChatGPT: Miễn phí.<br>- Hỏi luật sư: Chi phí cao (500k - vài triệu VNĐ). | **Miễn phí** hoàn toàn cho cộng đồng. | **Tương đương** AI phổ thông nhưng rẻ hơn việc đi tư vấn chuyên gia pháp lý. |
| **Tin hơn** | - Google: Tin cậy nhưng khó đối chiếu hiệu lực.<br>- ChatGPT: Hay bịa luật (hallucination), không có nguồn. | Đáng tin cậy cao nhờ **trích dẫn (citation) trực tiếp số hiệu điều luật/Nghị định** hiện hành. | **DrugLaw thắng tuyệt đối** chatbot phổ thông về tính chính xác pháp lý. |

### 3. Tự hỏi lại một câu khó: Nếu không dùng AI, project này còn tạo giá trị không?
- **Trả lời:** **Có, nhưng giá trị bị giảm đi rất nhiều.** 
  - Nếu không dùng AI (LLM), dự án vẫn có thể tạo ra giá trị bằng cách xây dựng một **Cổng thông tin tra cứu ma túy chuẩn hóa**, được phân loại và thiết kế giao diện trực quan cho người dân (thay vì các bảng biểu PDF thô của cơ quan nhà nước). 
  - Tuy nhiên, giá trị cốt lõi là **khả năng tương tác bằng ngôn ngữ tự nhiên** sẽ biến mất. Người dân sẽ phải tự mò mẫm qua các bộ lọc phức tạp thay vì chỉ cần mô tả tình huống đời thường của họ. AI ở đây không chỉ là "tính năng để làm cảnh", mà đóng vai trò là **cầu nối ngôn ngữ** giúp chuyển hóa thuật ngữ luật học phức tạp thành thông tin dễ hiểu và có thể hành động được cho người dân đại chúng.

