# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Vũ Gia Khải | 2A202602786 | Facilitator / điều phối thảo luận |
| 2   | Thân Tiến Đạt | 2A202603023 | Research / tổng hợp giải pháp đã có |
| 3   | Giang Thế Vũ | 2A202602478 | Domain owner / mô tả workflow thực tế |
| 4   | Nguyễn Hoàng Lê Nguyên | 2A202602472 | Writer / metric & Problem Statement |

**Candidate problem nhóm chọn (1 câu):**
Dev/freelancer mất nhiều thời gian đọc lại chat/email và hỏi lại khách hàng để làm rõ yêu cầu trước khi code, đặc biệt khó phân biệt đâu là chỉnh sửa nhỏ và đâu là thay đổi lớn (candidate #4).


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Vũ Gia Khải | Gom nguồn + lọc paper theo chủ đề (arXiv/ICPR/ICCV/NeurIPS) | Sinh viên | Gom 3-4 tiếng/tuần; đọc lướt + ra quyết định 15-30'/đợt | Workflow rõ, số đo lớn; nhưng chỉ 1/4 thành viên đọc paper nhiều nên khó validate chung |
| 2 | Vũ Gia Khải | Đọc paper 10-15 trang để hiểu method | Sinh viên | Đọc method + đối chiếu 60-90'/paper | Pain thật, impact lớn nhất; điểm yếu là metric "hiểu" khó đo chắc |
| 3 | Vũ Gia Khải | Hỏi AI về method, AI bịa ref | Sinh viên | Tra cứu bù kiến thức nền 30-60'/lần | Pain AI rõ, so được Rule/Workflow/Agent; cần log tỉ lệ AI bịa ref 1 tuần |
| 4 | Giang Thế Vũ | Làm rõ yêu cầu khách hàng qua chat/email | Dev làm nhiều dự án | Hỏi-đáp làm rõ tốn thời gian; chưa rõ thay đổi lớn hay chỉnh nhỏ | Người đưa ra có pain lặp lại ở nhiều dự án; workflow chat/email vẽ được, cần validate thêm với 2-3 dev khác |
| 5 | Giang Thế Vũ | Theo dõi tiến độ + ưu tiên nhiều dự án cùng lúc | Người làm nhiều dự án | Khó kiểm soát; vừa trả lời khách vừa sắp xếp; chưa đo giờ/deadline | Bài rộng, số đo còn mờ; cần bóc rõ mất bao nhiêu giờ và trễ deadline nào |
| 6 | Giang Thế Vũ | Xử lý lỗi + feedback sau bàn giao sản phẩm | Dev + khách hàng | Debug + sửa nhiều vòng; chưa rõ lỗi do yêu cầu hay kỹ thuật | Pain thật nhưng nguyên nhân lẫn lộn, khó khoanh bottleneck 1 bước |
| 7 | Thân Tiến Đạt | Đọc paper/tài liệu tiếng Anh rút ý chính cho đồ án | Sinh viên làm đồ án | Đọc/dịch/ghi chú mất 2-3 tiếng | Gần với 3 ý đọc-hiểu #1-#3, gom chung khi cluster |
| 8 | Thân Tiến Đạt | Không biết CV thiếu gì so với JD thực tập | Sinh viên năm cuối | So CV-JD 10-15'/JD; tiêu chí mỗi công ty khác nhau | Metric rõ, workflow vẽ được; nhưng chỉ 1/4 thành viên sát bối cảnh thực tập |
| 9 | Thân Tiến Đạt | Thành viên quên/hiểu sai task được giao | Cả nhóm (nhóm trưởng nhắc 2-3 lần/tuần) | Trễ task/làm sai; chưa rõ do công cụ hay cách phân công | Tình huống nhóm nào cũng có thể gặp; cần xác định rõ do tool hay do cách giao việc |
| 10 | Nguyễn Hoàng Lê Nguyên | Tổng hợp tiến độ từ Slack + Notion gửi supervisor | Thành viên phụ trách báo cáo | 35-45'/lần, 2 lần/tuần; owner có theo form chung không | Workflow lặp lại rõ, số đo có sẵn; rủi ro là owner không theo form chung |
| 11 | Nguyễn Hoàng Lê Nguyên | Biến ghi chú họp thành checklist công việc | Project team | AI có phân biệt được ý tưởng vs task thật không | Đầu vào sẵn, dễ đo số action item; điểm khó là phân biệt ý tưởng vs task |
| 12 | Nguyễn Hoàng Lê Nguyên | Tóm tắt feedback user thử thành nhóm insight | Người tổng hợp feedback | 70'/lần; số đợt feedback chưa nhiều | 70'/lần là số tốt, output kiểm được; nhưng số đợt feedback ít nên evidence yếu |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Đọc-hiểu tài liệu | #1 lọc paper, #2 đọc method, #3 hỏi AI về method, #7 đọc tài liệu TA | Biến tài liệu dài/rời rạc thành hiểu biết dùng được; bottleneck ở bước đọc-hiểu | Cụm đông nhất (4 ý) nhưng chỉ 2/4 thành viên sát bối cảnh paper |
| B. Task + tiến độ nhóm | #5 đa dự án, #9 quên/hiểu sai task, #10 tổng hợp tiến độ, #11 notes thành checklist | Thông tin nhóm phân tán nhiều nơi, việc dễ rơi, phải gom lại mới kiểm soát được | Pain phổ biến khi làm nhiều việc cùng lúc; ứng viên shortlist tốt nếu khoanh được 1 workflow cụ thể |
| C. Yêu cầu + feedback | #4 làm rõ yêu cầu KH, #6 lỗi sau bàn giao, #12 feedback user | Khoảng cách giữa người làm và người nhận: yêu cầu mơ hồ, feedback nhiều vòng | Chứa candidate nhóm chọn (#4); workflow chat/email vẽ và validate được |
| D. CV vs JD | #8 thiếu gì so với JD | So khớp hiện trạng với chuẩn để biết còn thiếu gì | Chỉ 1 ý từ 1/4 thành viên; cân nhắc loại ở shortlist |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #4 Làm rõ yêu cầu KH qua chat/email | Pain lặp lại ở nhiều dự án (người đưa ra); workflow hỏi-đáp vẽ được 4-6 bước; cùng cụm C nên dễ validate chéo với #6, #12 | Chưa phân biệt thay đổi lớn hay chỉnh nhỏ; cần log giờ làm rõ 1-2 tuần |
| #10 Tổng hợp tiến độ Slack + Notion gửi supervisor | Workflow lặp lại 2 lần/tuần rõ ràng; số đo 35-45'/lần có sẵn; bottleneck và owner rõ | Phụ thuộc owner có cập nhật theo form chung không — nhóm không kiểm soát được input |
| #2 Đọc paper 10-15 trang để hiểu method | Impact giờ lớn nhất (~600-1440'/tuần); bottleneck 1 bước đọc method; so được Rule/Workflow/Agent | Metric "hiểu" khó đo chắc; chỉ 1/4 thành viên sát bối cảnh nên khó validate chung |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #4 Làm rõ yêu cầu KH | 4 | 4 | 3 | 3 | 5 | 5 | 4 | 28 |
| #10 Tổng hợp tiến độ | 4 | 5 | 3 | 4 | 4 | 4 | 3 | 27 |
| #2 Đọc method paper | 4 | 5 | 4 | 5 | 3 | 4 | 2 | 27 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#4 — Làm rõ yêu cầu khách hàng qua chat/email trước khi làm sản phẩm.
```

**Vì sao chọn (4-5 câu):**

```text
Workflow hỏi-đáp qua chat/email vẽ được thành 4-6 bước cụ thể. Pain lặp lại ở nhiều dự án của người đưa ra, không phải ý tưởng một lần, nhưng nhóm vẫn cần validation thật để làm chắc evidence. Bài thu hẹp được về 1 bottleneck: bước đọc lại yêu cầu và phân biệt thay đổi lớn với chỉnh sửa nhỏ. Có thể validate nhanh bằng cách hỏi 2-3 dev/freelancer ngoài nhóm. So được Rule (template câu hỏi làm rõ) với Workflow (AI tóm tắt thread + gợi ý câu hỏi thiếu).
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#10 Tổng hợp tiến độ: số đo sẵn và workflow rõ, nhưng input phụ thuộc owner có cập nhật theo form chung không — nhóm không kiểm soát được nên metric dễ vỡ.
#2 Đọc method paper: impact giờ lớn nhất nhưng metric "hiểu" khó đo chắc, và chỉ 1/4 thành viên sát bối cảnh nên khó validate chung trong thời gian lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Không có disagreement lớn. 1 ý kiến từng muốn giữ #2 vì impact giờ cao nhất, nhưng đồng ý lùi vì metric "hiểu" khó đo; nhóm chốt #4 vì validate và vẽ workflow nhanh nhất trong lab.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa có quote thật trong file. Cần hỏi 2-3 dev/freelancer từng làm dự án khách hàng: lần gần nhất phải làm rõ yêu cầu là khi nào, hỏi-đáp mấy vòng, mất bao lâu, muốn thay đổi điều gì. | Chưa đủ dữ liệu để kết luận. Evidence hiện tại mới đến từ trải nghiệm của thành viên đưa ra candidate. | Có thể có người phản bác rằng họ đã dùng template/brief rõ nên không thấy đau. | Tạm giữ problem ở dạng candidate; sau interview cần sửa lại actor, bottleneck và baseline thời gian nếu dữ liệu khác giả định ban đầu. |
| Survey / poll | Chưa có poll thật trong file. Nếu làm, nên hỏi 5-10 người trong lớp/Discord: có gặp không, tần suất, bước đau nhất, workaround, mức đáng giải quyết 1-5. | Chưa đủ dữ liệu survey. | Chưa có tín hiệu phản bác từ survey. | Chỉ dùng survey để bổ sung độ rộng của pain, không thay thế interview vì workflow cần hiểu sâu. |
| Log / ticket / review (nếu có) | Chưa có log/ticket đính kèm. | Chưa có bằng chứng từ lịch sử chat/email thật. | Không có. | Nếu có thể, lấy 1 thread chat/email cũ đã ẩn thông tin riêng tư để đo số vòng hỏi-đáp và thời gian làm rõ. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Hiện tại nhóm mới có evidence nội bộ, chưa có quote hoặc log thật từ người ngoài nhóm. Pain giả định nằm ở đoạn dev phải đọc lại nhiều tin nhắn/email, tự đoán ý khách hàng và hỏi lại nhiều vòng trước khi dám chốt scope để code.
```

Bằng chứng đính kèm cần bổ sung nếu có: `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Linear issue/form templates | https://linear.app/docs/issue-templates | Bước chốt yêu cầu thành đầu việc có đủ field (tương đương bước "chốt yêu cầu đã làm rõ") | Template + form bắt buộc field, tạo được từ Slack/email | Chỉ xử lý đầu vào có cấu trúc, không giúp đọc hiểu thread chat/email dài | Rule (template câu hỏi làm rõ) đủ cho 70-80% case lặp lại — làm baseline trước khi nghĩ tới AI |
| Linear Triage | https://linear.app/docs/triage | Đưa issue mới từ integration hoặc người ngoài team vào hàng đợi triage để team review trước khi vào workflow chính | Tách inbox mới khỏi backlog; có người chịu trách nhiệm review, cập nhật và ưu tiên issue | Cần cả team theo quy trình; team 1-2 dev có thể thấy nặng | Pattern "gom vào hàng đợi + người chốt": boundary người review là bắt buộc, không để AI tự chốt |
| Shortwave AI email summaries | https://www.shortwave.com/blog/ai-email-summaries/ | Bước đọc lại thread email dài: tóm tắt các ý chính trong một email thread | Phù hợp với việc bắt nhanh nội dung thread dài hoặc cuộc trao đổi bị kéo dài | Chủ yếu cho email, không tự gom đủ chat đa kênh; output vẫn phải kiểm lại trước khi hành động | AI tóm tắt thread dùng được cho bước "ôn lại yêu cầu", nhưng dev vẫn verify trước khi code |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không build agent tự chốt yêu cầu với khách. Hướng hợp lý: Rule (template câu hỏi làm rõ + form) làm baseline, Workflow dùng AI tóm tắt thread dài và gợi ý câu hỏi còn thiếu, dev chốt cuối trước khi code.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Khách gửi yêu cầu qua chat/email: 5' - khách hàng]
→ [2 Dev đọc lại thread và gom ý chính: 20']
→ [3 Dev tự phân loại chỉnh sửa nhỏ / thay đổi lớn: 20']  <-- bottleneck
→ [4 Dev hỏi lại khách để làm rõ: 15-30']
→ [5 Khách phản hồi / bổ sung context: 30' đến vài giờ chờ]
→ [6 Dev chốt scope và estimate lại: 20']
→ [7 Dev bắt đầu code hoặc sửa task: sau khi scope rõ]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Khách hàng | Ý tưởng, yêu cầu sửa, ảnh chụp màn hình hoặc mô tả qua chat/email | Tin nhắn/email yêu cầu ban đầu | 5-10 phút/lần yêu cầu | Input thường thiếu context, tiêu chí hoàn thành hoặc mức ưu tiên |
| 2 | Dev/freelancer | Thread chat/email, file thiết kế, sản phẩm hiện tại | Ghi chú thô các ý khách muốn sửa | 15-25 phút/lần | Dev phải đọc lại nhiều đoạn rời rạc |
| 3 | Dev/freelancer | Ghi chú thô và hiểu biết về hệ thống | Phân loại tạm: chỉnh sửa nhỏ hay thay đổi lớn | 15-25 phút/lần | Bottleneck: dễ đánh giá sai scope nếu yêu cầu mơ hồ |
| 4 | Dev/freelancer -> khách hàng | Các điểm chưa rõ | Câu hỏi làm rõ gửi lại khách | 10-20 phút/lần | Handoff qua chat/email; có thể hỏi thiếu câu quan trọng |
| 5 | Khách hàng | Câu hỏi làm rõ từ dev | Câu trả lời bổ sung | 30 phút đến vài giờ chờ | Thời gian chờ làm chậm việc code |
| 6 | Dev/freelancer | Phản hồi bổ sung của khách | Scope cuối, estimate, danh sách việc cần làm | 15-25 phút/lần | Nếu scope thay đổi lớn, cần báo lại effort/deadline |
| 7 | Dev/freelancer | Scope đã chốt | Task/code bắt đầu được thực hiện | Sau khi scope rõ | Nếu bước trước sai, dễ phải sửa nhiều vòng sau khi bàn giao |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck chính nằm ở bước 2-4: dev phải đọc lại thread rời rạc, tự hiểu yêu cầu và tự phân biệt chỉnh sửa nhỏ với thay đổi lớn trước khi code. Nếu phân loại sai, dev có thể estimate thiếu, code sai hướng hoặc phải hỏi lại khách nhiều vòng. Đây là bottleneck phù hợp để cải thiện bằng template/rule và AI hỗ trợ tóm tắt, nhưng quyết định scope cuối vẫn phải do dev xác nhận.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Khách gửi yêu cầu qua form/template: 5' - rule]
→ [2 AI tóm tắt thread chat/email và trích yêu cầu chính: 3']
→ [3 AI gợi ý câu hỏi còn thiếu + phân loại sơ bộ nhỏ/lớn: 3']
→ [4 Dev review, sửa phân loại, chọn câu hỏi gửi khách: 10']  <-- human boundary
→ [5 Khách trả lời câu hỏi còn thiếu]
→ [6 Dev chốt scope, estimate và tạo task: 15']

Fallback: nếu AI tóm tắt sai, bỏ sót context hoặc phân loại sai scope, dev bỏ output AI và quay về checklist câu hỏi làm rõ thủ công.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian xử lý chủ động của dev | 75-105 phút/lần yêu cầu, chưa tính thời gian chờ khách | 35-45 phút/lần yêu cầu, chưa tính thời gian chờ khách | Bấm giờ 3-5 yêu cầu thật trước/sau pilot |
| Số bước | 7 | 6 | Đếm số bước trong workflow |
| Số bước thủ công | 6/7 | 3/6 | Đếm bước dev phải tự đọc, tự phân loại, tự viết câu hỏi |
| Bottleneck chính | Đọc thread + phân loại scope + viết câu hỏi làm rõ | Dev review output AI và chốt scope | So thời gian ở bước bottleneck trước/sau |
| Risk mới | Không có hallucination AI nhưng dễ hiểu sai do chat rời rạc | AI tóm tắt sai, bỏ sót yêu cầu, phân loại nhầm nhỏ/lớn | Dev kiểm tra output AI trước khi gửi khách hoặc code |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Dev/freelancer làm nhiều dự án nhỏ hoặc nhận yêu cầu sửa sản phẩm từ khách hàng qua chat/email. Actor chính là người phải đọc yêu cầu, hỏi lại khách và chốt scope trước khi code. |
| **Workflow** | Khách gửi yêu cầu qua chat/email -> dev đọc lại thread -> dev phân loại chỉnh sửa nhỏ hay thay đổi lớn -> dev hỏi lại khách -> khách phản hồi -> dev chốt scope/estimate -> dev bắt đầu code. Workflow hiện tại phụ thuộc nhiều vào việc dev tự đọc hiểu và tự nhớ context trong các đoạn chat rời rạc. |
| **Bottleneck** | Bottleneck nằm ở bước đọc lại thread, phân loại scope và viết câu hỏi làm rõ. Bước này mất khoảng 45-70 phút xử lý chủ động cho mỗi yêu cầu phức tạp và dễ sai nếu khách mô tả thiếu context. |
| **Impact** | Nếu hiểu sai scope, dev có thể estimate thiếu, code sai hướng hoặc phải sửa lại sau bàn giao. Việc hỏi-đáp nhiều vòng cũng làm chậm thời điểm bắt đầu code và làm khách hàng cảm thấy tiến độ không rõ. |
| **Success Metric** | Giảm thời gian xử lý chủ động của dev trước khi chốt scope từ khoảng 75-105 phút/lần yêu cầu xuống còn 35-45 phút/lần yêu cầu. Đồng thời mỗi yêu cầu sau khi làm rõ phải có đủ 4 field: yêu cầu chính, tiêu chí hoàn thành, phân loại nhỏ/lớn, câu hỏi còn thiếu hoặc xác nhận không còn thiếu. |
| **Boundary** | Không để AI tự chốt scope, tự báo deadline/chi phí với khách hoặc tự quyết định yêu cầu là nhỏ/lớn mà không có dev review. AI chỉ được tóm tắt thread, gợi ý câu hỏi thiếu và phân loại sơ bộ để dev kiểm tra. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Evidence validation và baseline thời gian còn yếu vì chưa có quote/log thật từ dev ngoài nhóm.
- Tôi sửa gì: Giữ Problem Statement ở mức v0, ghi rõ baseline là giả định cần validate; bổ sung boundary không để AI tự chốt scope hoặc tự phản hồi khách.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: cùng một yêu cầu khách hàng có thể được hiểu theo nhiều mức scope khác nhau, đặc biệt khi thiếu tiêu chí hoàn thành hoặc context kỹ thuật.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: workflow cần đọc chat/email, đối chiếu sản phẩm hiện tại, hỏi lại khách, chốt scope và chuyển thành task/code.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ cao + độ phức tạp cao.
```

**Vì sao (2-3 câu):**

```text
Bài toán có nhiều bước phụ thuộc nhau và input từ khách thường không đủ cấu trúc. Tuy nhiên AI chưa nên tự chạy như Agent vì quyết định scope, deadline và chi phí có rủi ro cao; hướng hợp lý hơn là Workflow có AI hỗ trợ tóm tắt và dev review.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Template/form làm rõ yêu cầu: mục tiêu, màn hình liên quan, tiêu chí hoàn thành, deadline, mức ưu tiên, ảnh/video nếu có | Đủ khi khách chịu điền form và yêu cầu tương đối đơn giản/lặp lại | Khách có thể không điền đủ; không xử lý tốt thread chat/email dài đã có sẵn | Có dùng làm baseline và bước input |
| **Workflow** | Form/template -> AI tóm tắt thread -> AI gợi ý câu hỏi thiếu/phân loại sơ bộ -> dev review -> dev chốt scope | Đủ khi dev vẫn là người quyết định cuối, AI chỉ hỗ trợ đọc hiểu và chuẩn hóa thông tin | AI có thể tóm tắt sai, bỏ sót context, phân loại nhầm nhỏ/lớn | Chọn cho bài toán nhóm |
| **Agent** | Agent tự đọc nhiều kênh, tự hỏi khách, tự tạo issue, tự estimate và cập nhật backlog | Chỉ phù hợp khi có quyền truy cập hệ thống, dữ liệu đủ sạch, rule vận hành rõ và có kiểm soát chặt | Rủi ro cao: hỏi sai khách, chốt sai scope, lộ thông tin, tạo task sai | Chưa chọn |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

Trả lời:

```text
1. Rule có thể giải được một phần lớn case đơn giản nếu khách chịu điền form/template, nhưng không đủ cho các thread chat/email dài đã có sẵn.
2. Workflow chính khá tuyến tính: nhận yêu cầu -> gom context -> hỏi lại -> chốt scope -> code, nhưng có thể lặp lại ở bước hỏi-đáp nếu khách trả lời chưa đủ.
3. Chưa cần Agent vì AI không nên tự hỏi khách, tự estimate hoặc tự chốt scope khi chưa có dữ liệu và quyền kiểm soát rõ.
4. Nếu AI sai, dev/freelancer là người phát hiện đầu tiên bằng cách đối chiếu output với thread gốc; thời gian sửa kỳ vọng 5-10 phút nếu chỉ sai tóm tắt/phân loại nhỏ.
5. Có thể hạ mức: nếu AI không ổn thì dùng Rule/template làm rõ yêu cầu; nếu Rule không đủ cho thread dài thì dùng Workflow có AI hỗ trợ nhưng vẫn có dev review.
```

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì bài toán cần nhiều bước hơn một template cố định: đọc thread, tóm tắt, phát hiện thông tin thiếu và phân loại sơ bộ scope. AI có ích ở phần xử lý ngôn ngữ và tổng hợp context, nhưng dev vẫn phải review trước khi gửi câu hỏi hoặc chốt scope. Agent là quá sớm vì chưa có validation thật, chưa có dữ liệu sạch và rủi ro tự phản hồi khách/chốt scope sai khá cao.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule đơn giản hơn có thể giải quyết một phần bằng form/template, nhưng không đủ khi yêu cầu đã nằm trong thread chat/email dài và rời rạc. Nếu chỉ dùng Rule, dev vẫn phải đọc lại toàn bộ thread và tự phát hiện thông tin thiếu. Vì vậy nhóm dùng Rule làm baseline input, còn Workflow để AI hỗ trợ bước tóm tắt và gợi ý câu hỏi.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Dev/freelancer nhận yêu cầu sửa hoặc bổ sung tính năng từ khách hàng qua chat/email. |
| **Workflow** | Khách gửi yêu cầu -> dev đọc thread -> dev phân loại scope -> dev hỏi lại -> khách phản hồi -> dev chốt scope/estimate -> dev code. |
| **Bottleneck** | Dev mất nhiều thời gian đọc thread rời rạc, phân biệt chỉnh sửa nhỏ với thay đổi lớn và viết câu hỏi làm rõ trước khi code. |
| **Impact** | Chậm bắt đầu code, dễ estimate thiếu, dễ code sai hướng và phải sửa lại sau bàn giao. |
| **Success Metric** | Giảm thời gian xử lý chủ động trước khi chốt scope từ 75-105 phút/lần xuống 35-45 phút/lần; mỗi yêu cầu có đủ yêu cầu chính, tiêu chí hoàn thành, phân loại nhỏ/lớn và câu hỏi còn thiếu. |
| **Boundary** (làm / không làm) | Làm: tóm tắt thread, chuẩn hóa thông tin, gợi ý câu hỏi thiếu, phân loại sơ bộ scope. Không làm: tự chốt scope, tự báo deadline/chi phí, tự gửi phản hồi cho khách, tự tạo cam kết thay dev. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau khi có thread chat/email hoặc form yêu cầu ban đầu, trước khi dev viết câu hỏi làm rõ và chốt scope. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow: Rule/form giúp chuẩn hóa input, AI hỗ trợ tóm tắt và gợi ý, dev review và chốt cuối. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI bỏ sót yêu cầu hoặc phân loại sai scope. Dev/freelancer kiểm tra bằng cách đối chiếu output AI với thread gốc trước khi gửi khách hoặc bắt đầu code. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là dev/freelancer nhận yêu cầu qua chat/email; workflow trước/sau đã mô tả được các bước chính. |
| Baseline + metric đo được chưa? | Not Yet | Có baseline ước lượng 75-105 phút/lần nhưng chưa có log/interview thật để xác nhận. |
| Data/input đủ dùng chưa? | Not Yet | Cần ít nhất 1-2 thread chat/email đã ẩn thông tin riêng tư hoặc interview thật để thử workflow. |
| AI sai, hậu quả chấp nhận được không? | Yes, nếu có dev review | Hậu quả chấp nhận được khi AI chỉ draft/tóm tắt và dev bắt buộc kiểm tra trước khi gửi khách hoặc code. |
| Có người review/owner không? | Yes | Dev/freelancer là owner review output AI và chốt scope cuối. |
| Có cách non-AI đơn giản hơn không? | Yes | Template/form làm rõ yêu cầu là phương án Rule nên làm trước hoặc làm cùng workflow. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm chưa nên Go ngay vì phần validation thật còn thiếu: chưa có quote từ dev/freelancer ngoài nhóm và chưa có log chat/email để kiểm tra baseline thời gian. Tuy nhiên bài toán có actor, workflow, bottleneck, metric và boundary tương đối rõ. Hướng tiếp theo là validate nhỏ bằng 2-3 interview hoặc 1-2 thread thật, rồi mới quyết định Go với workflow có AI hỗ trợ.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Nếu sau validation chuyển sang Go, pilot nhỏ nhất là lấy 1-2 thread chat/email đã ẩn thông tin riêng tư, cho AI tóm tắt yêu cầu + gợi ý câu hỏi thiếu + phân loại nhỏ/lớn, sau đó dev review. Đo 3 số: thời gian dev đọc hiểu trước/sau, số câu hỏi làm rõ còn thiếu, số lỗi phân loại scope.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Cần validate với 2-3 dev/freelancer từng làm dự án khách hàng và ghi quote thật. Cần đo ít nhất 1-2 case: một yêu cầu cũ mất bao lâu để làm rõ, hỏi-đáp mấy vòng, phần nào khiến dev dễ hiểu sai nhất.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu validation cho thấy pain không đủ lớn hoặc Rule đã đủ, nhóm nên làm template/form làm rõ yêu cầu thay vì dùng AI.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng dùng AI nếu AI bỏ sót yêu cầu quan trọng, phân loại sai scope trong 2 case liên tiếp, hoặc dev phải sửa lại phần lớn output. Khi đó quay về template câu hỏi làm rõ + checklist scope thủ công.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
