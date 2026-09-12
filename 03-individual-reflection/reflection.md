# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Thân Tiến Đạt
- Mã học viên: 2A202603023
- Nhóm: ABC gì cũng được - Vũ Gia Khải, Thân Tiến Đạt, Giang Thế Vũ, Nguyễn Hoàng Lê Nguyên
- Candidate problem nhóm chọn: Dev/freelancer mất nhiều thời gian đọc lại chat/email và hỏi lại khách hàng để làm rõ yêu cầu trước khi code, đặc biệt khó phân biệt đâu là chỉnh sửa nhỏ và đâu là thay đổi lớn.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 problems từ bối cảnh sinh viên năm 4, gồm làm đồ án, đọc paper, chuẩn bị thực tập, CV/JD, làm việc nhóm và học tiếng Anh. | Nhóm có thêm 3 candidate từ phần của tôi: đọc paper/tài liệu tiếng Anh, kiểm tra CV với JD, và thành viên nhóm quên/hiểu sai task. |
| Pitch Problem Card | Tôi chuẩn bị pitch card "Đọc paper/tài liệu tiếng Anh phục vụ đồ án", với workflow tìm paper -> lọc -> đọc/dịch -> ghi chú -> quyết định có dùng không. | Candidate này được đưa vào nhóm đọc-hiểu tài liệu và giúp nhóm có thêm lựa chọn có workflow, bottleneck và metric rõ. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về việc problem có đo được không, có workflow thật không, và AI có cần thiết hay chỉ cần template/rule. | Nhóm loại bớt các bài quá rộng hoặc khó đo, đặc biệt là những bài chưa rõ bottleneck hoặc phụ thuộc input không kiểm soát được. |
| Gom trùng / cluster | Tôi cùng nhóm gom 12 candidates thành các cụm: đọc-hiểu tài liệu, task/tiến độ nhóm, yêu cầu/feedback, CV vs JD. | Nhóm nhìn được pattern chung thay vì chọn từng ý rời rạc, từ đó shortlist còn 3 bài dễ so sánh hơn. |
| Chọn candidate problem | Tôi tham gia so sánh #4 làm rõ yêu cầu khách hàng, #10 tổng hợp tiến độ và #2 đọc method paper theo các tiêu chí actor, workflow, evidence, impact, làm trong lab, R/W/A và domain. | Nhóm thống nhất chọn #4 vì workflow chat/email dễ vẽ, có thể validate nhanh và so sánh được Rule / Workflow / Agent. |
| Validation / research | Tôi phụ trách research/tổng hợp giải pháp đã có, gồm Linear issue/form templates, Linear Triage và Shortwave AI email summaries. | Nhóm có cơ sở để kết luận không nên build Agent tự chốt yêu cầu, mà nên dùng Rule/form làm baseline và Workflow có AI hỗ trợ tóm tắt thread. |
| Workflow nhóm | Tôi góp ý để workflow nhóm có current workflow và future workflow, trong đó AI chỉ tóm tắt/gợi ý, còn dev vẫn review và chốt scope. | Workflow thể hiện được bottleneck, thời gian trước/sau, boundary và fallback nếu AI sai. |
| Problem Statement | Tôi hỗ trợ làm rõ phần metric, boundary và AI intervention point trong Problem Statement v0/v1. | Problem Statement không chỉ nói "làm rõ yêu cầu nhanh hơn", mà có baseline 75-105 phút, target 35-45 phút và giới hạn AI không tự chốt scope. |
| Rule / Workflow / Agent | Tôi tham gia lập luận rằng Rule/template có ích nhưng chưa đủ cho thread chat/email dài, còn Agent thì quá rủi ro. | Nhóm chọn Workflow: form/template -> AI tóm tắt/gợi ý -> dev review -> dev chốt scope. |
| Decision | Tôi đồng ý với quyết định Not Yet vì nhóm chưa có quote/log validation thật từ dev/freelancer ngoài nhóm. | Decision cuối nhất quán với evidence hiện tại: bài toán rõ hướng nhưng cần validate thêm trước khi Go. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần research giải pháp đã có và lập luận chọn Workflow thay vì Agent. Tôi cũng góp phần làm rõ boundary: AI chỉ được tóm tắt thread, gợi ý câu hỏi còn thiếu và phân loại sơ bộ, còn dev phải kiểm tra và chốt scope cuối.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI để gợi ý thêm 8-10 scan problems phù hợp với sinh viên năm 4. | AI giúp mở rộng góc nhìn sang đồ án, CV/JD, phỏng vấn, học tiếng Anh và làm việc nhóm. | Một số ý còn rộng hoặc nghe hợp lý nhưng chưa chắc là pain thật của tôi. | Tôi chỉ giữ các problem gắn với trải nghiệm thật và thêm số đo như 2-3 tiếng/paper, 10-15 phút/JD, 2-3 lần nhắc task/tuần. |
| Problem Card | Dùng AI để phản biện card đọc paper và kiểm tra các field có rõ chưa. | AI nhắc tôi cần có human boundary và metric chất lượng tóm tắt. | AI có xu hướng làm problem nghe quá "AI-first" nếu không kiểm soát. | Tôi giữ lại phần người học phải đọc lại đoạn quan trọng và đo output bằng 5 ý chính từ mỗi paper. |
| Workflow | Dùng AI để hỗ trợ viết workflow trước/sau rõ bước hơn. | AI giúp tách các bước như tìm paper, đọc, dịch, ghi chú, review, fallback. | Có lúc AI gộp quá nhiều bước hoặc làm thời gian chưa khớp tổng. | Tôi chỉnh lại workflow để có bottleneck, human boundary và fallback rõ hơn. |
| Research | Dùng AI để gợi ý hướng research tool/pattern tương tự, sau đó kiểm link. | AI giúp nghĩ ra các pattern như template/form, triage và email thread summary. | AI có thể đưa nguồn hoặc claim chưa chắc, đặc biệt là số liệu tiết kiệm thời gian. | Tôi chỉ giữ các link kiểm được và không dùng số liệu nếu chưa verify. |
| Problem Statement | Dùng AI để kiểm xem field actor, workflow, bottleneck, metric, boundary còn mơ hồ không. | AI giúp chỉ ra baseline và validation thật còn yếu. | AI có thể viết lại quá trơn, khiến bài giống đã có evidence dù thực tế chưa có quote/log. | Tôi ghi rõ baseline còn là giả định cần validate và không tick phần validation thật. |
| Rule / Workflow / Agent | Dùng AI để so sánh Rule, Workflow và Agent cho cùng một bài toán. | AI giúp hệ thống hóa rủi ro của Agent và vai trò của Rule/template. | AI dễ đề xuất Agent quá sớm nếu chỉ nhìn bài toán là chat/email dài. | Tôi chọn Workflow vì hợp với boundary hiện tại: AI hỗ trợ, dev chốt cuối. |
| Decision | Dùng AI để kiểm tra decision Go / Not Yet / No-Go có nhất quán với evidence không. | AI giúp thấy nếu thiếu validation thật thì chưa nên Go. | AI có thể muốn chốt Go vì workflow đã rõ, nhưng bỏ qua điểm thiếu bằng chứng. | Tôi giữ decision là Not Yet cho đến khi có interview, quote hoặc thread thật để validate. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn khác, tôi nhận ra một problem tốt không nhất thiết là problem nghe liên quan AI nhất, mà là problem có actor, workflow, bottleneck và metric rõ. Ban đầu tôi muốn pitch bài đọc paper/tài liệu tiếng Anh vì nó rất gần với bối cảnh sinh viên năm 4 và có số đo 2-3 tiếng/paper. Sau khi nhóm gom cluster và so sánh các candidate, tôi thấy bài làm rõ yêu cầu khách hàng qua chat/email phù hợp hơn cho phần nhóm vì workflow dễ validate và dễ so sánh Rule / Workflow / Agent. Tôi cũng học được rằng nếu chỉ nói "dev mất thời gian làm rõ yêu cầu" thì vẫn còn mơ hồ, cần chỉ ra cụ thể bước nghẽn là đọc lại thread, phân loại scope nhỏ/lớn và viết câu hỏi làm rõ. Nhóm có lúc dễ nghĩ tới AI tóm tắt hoặc Agent tự xử lý yêu cầu, nhưng khi phân tích boundary thì thấy không thể để AI tự chốt scope, deadline hoặc chi phí với khách. Phần tôi đóng góp rõ nhất là research các giải pháp đã có và kéo bài về hướng Workflow: dùng form/template làm baseline, AI hỗ trợ tóm tắt và gợi ý, dev review và chốt cuối. Điều khó nhất khi viết Problem Statement là metric, vì nhóm có thể ước lượng thời gian 75-105 phút nhưng chưa có quote hoặc log thật để xác nhận. Vì vậy tôi đồng ý với decision Not Yet thay vì Go ngay, vì bài có hướng tốt nhưng validation chưa đủ chắc. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở Phase 4 bằng cách yêu cầu có ít nhất 2 quote thật từ dev/freelancer trước khi chốt baseline thời gian. Tôi cũng sẽ chuẩn bị sẵn một thread chat/email đã ẩn thông tin riêng tư để nhóm đo số vòng hỏi-đáp và kiểm tra workflow thực tế hơn.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

