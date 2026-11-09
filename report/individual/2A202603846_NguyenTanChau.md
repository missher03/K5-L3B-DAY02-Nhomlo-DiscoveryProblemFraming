# Báo cáo cá nhân — 2A202603846_NguyenTanChau

## 1. Thông tin học viên

- Họ tên: Nguyễn Tấn Châu
- MSSV: 2A202603846
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: Nhomlo
- Link repo nhóm: https://github.com/missher03/K5-L3B-DAY02-Nhomlo-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi tới sáng thứ Hai, tôi muốn có số liệu sprint và tình hình team ở một chỗ, để gửi báo cáo tuần cho EM và CEO trước 10h | PM, EM, CEO | 85 phút và 95 phút/lần trong 2 sáng thứ Hai liên tiếp; ghi nhận bằng cách tự bấm giờ từ lúc bắt đầu thu thập dữ liệu đến khi gửi báo cáo |
| 2 | Lặp lại | Khi cập nhật slide cho buổi họp tháng, tôi muốn có sẵn velocity các sprint, để không phải copy tay từ Jira | PM | Khoảng 20–30 phút/lần, 1 lần/tháng; PM phải mở Jira, xem velocity của từng sprint và sao chép số liệu sang slide. Có thể kiểm chứng bằng cách bấm giờ trong lần cập nhật slide tiếp theo |
| 3 | Tốn thời gian | Khi nhận một PRD 10–15 trang cần review, tôi muốn nắm nhanh các quyết định chính, để comment đúng chỗ trước hạn | PM reviewer, design lead | Khoảng 40–50 phút/PRD, trung bình 2 PRD/tuần; tương đương 80–100 phút/tuần cho việc đọc, tổng hợp và ghi chú review. Có thể đối chiếu với lịch review và thời gian xử lý từng tài liệu |
| 4 | Tốn thời gian | Khi vừa xong một cuộc họp liên team, tôi muốn có danh sách việc cần làm và người phụ trách, để không ai bỏ sót | PM, team | Khoảng 15–30 phút/buổi họp để viết lại meeting notes, tổng hợp action items và người phụ trách; giả định có 2–3 buổi họp liên team/tuần. Có thể kiểm chứng bằng lịch họp và timestamp trên tài liệu ghi chú |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi có quá nhiều task cùng hạn, tôi muốn biết nên làm việc nào trước, để không trễ việc quan trọng | PM, team | Tuần gần nhất có 2 task bị trễ do ưu tiên công việc chưa hợp lý. Có thể đối chiếu deadline, trạng thái task trên Jira và lịch sử cập nhật để xác định nguyên nhân |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi cần biết vì sao team từng chọn phương án A, tôi muốn tìm lại được quyết định cũ, để không tranh luận lại từ đầu | Cả team | Mất khoảng 10–15 phút/lần tìm kiếm quyết định cũ trên Slack, xảy ra 3–4 lần/tuần; tương đương 30–60 phút/tuần. Có thể kiểm chứng bằng timestamp của các thread tìm kiếm và trao đổi liên quan |
| 7 | Pain từ người khác | Khi designer nhận spec từ tôi, họ muốn hiểu đúng yêu cầu ngay lần đầu, để không phải hỏi lại | Designer, PM | Designer phải hỏi lại PM trung bình 2–3 lần/spec để làm rõ yêu cầu; có thể kiểm tra bằng số lượng câu hỏi clarification trong các thread Slack của từng spec |
| 8 | Pain từ người khác | Khi CEO chuẩn bị họp leadership sáng thứ Hai, CEO muốn có báo cáo trước giờ họp, để nắm tình hình | CEO, PM | Báo cáo tuần được gửi trễ trong 3/8 tuần gần nhất (37,5%); đối chiếu timestamp gửi báo cáo với deadline 10h sáng thứ Hai |
| 9 | Tốn thời gian | Khi cuối tháng, tôi muốn có KPI từ nhiều dashboard trong một bảng, để báo cáo tháng | PM, manager | Khoảng 90–120 phút/lần, 1 lần/tháng; PM phải truy cập nhiều dashboard, tổng hợp KPI và chuẩn hóa dữ liệu vào một bảng báo cáo. Có thể kiểm chứng bằng cách bấm giờ trong lần lập báo cáo tháng tiếp theo |
| 10 | Lặp lại | Khi tới giờ standup, tôi muốn có sẵn update hôm qua, để không phải nhớ lại | PM | Khoảng 5–10 phút/ngày, tương đương 25–50 phút/tuần nếu làm việc 5 ngày; PM phải nhớ lại hoạt động hôm trước và tự viết status update. Có thể kiểm chứng bằng thời gian chuẩn bị standup update mỗi ngày |

**Nếu có dùng AI để gợi ý thêm:** Sau khi tự scan 8 ý đầu tiên, tôi dùng AI gợi ý và giữ lại ý #9 và #10 vì sát với thực tế công việc định kỳ. Ý *"trợ lý AI quản lý toàn bộ dự án"* bị loại vì quá rộng, mơ hồ và không có quy trình thật kiểm chứng được.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Báo cáo tuần (#1) | Quy trình rõ, tốn thời gian, có baseline đo thật | Narrative "đủ tốt" đo thế nào? |
| 2 | Review PRD (#3) | Pain thật, nhiều người gặp | Chất lượng review khó đo |
| 3 | Tìm quyết định cũ (#6) | Nhiều người đau, impact rộng | Quyền truy cập dữ liệu khó, phạm vi dễ quá rộng |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tới sáng thứ Hai, tôi muốn có số liệu sprint và tình hình team ở một chỗ, để gửi báo cáo tuần cho EM và CEO trước 10h |
| Actor | Junior PM phụ trách báo cáo tuần cho EM và CEO |
| Thời điểm / bối cảnh | Sáng thứ Hai, trước buổi họp leadership lúc 10h |
| Quy trình hiện tại (3–7 bước) | 1. Export dữ liệu sprint từ Jira · 2. Lấy số từ Google Sheets · 3. Đọc lại Slack cả tuần · 4. Tổng hợp vào Google Docs · 5. Viết narrative (điểm nổi bật, rủi ro, việc tiếp theo) · 6. Tự review và format · 7. Gửi email |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, viết narrative: khoảng 25 phút, hay bị "trang trắng" |
| Impact (nếu không giải thì sao) | 90 phút/tuần cho 1 PM; công ty có 3 PM nên khoảng 270 phút/tuần; 3/8 tuần gần nhất gửi trễ |
| Success metric (baseline → target) | Tổng thời gian từ 90 phút xuống dưới 30 phút, số câu hỏi lại từ CEO/EM không tăng |
| Phương án không dùng AI | Template cố định + dashboard Jira + checklist: giảm thời gian format, chưa giảm thời gian viết narrative |
| Giả thuyết về AI (nếu có) | AI soạn nháp narrative từ dữ liệu đã gom; PM review và sửa trước khi gửi |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:
```text
[1 Export Jira: 10'] → [2 Lấy số Sheets: 10'] → [3 Đọc Slack: 15']
→ [4 Tổng hợp Docs: 15'] → [5 Viết narrative: 25'] ← BOTTLENECK
→ [6 Review + format: 10'] → [7 Gửi: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một PRD 10–15 trang cần review, tôi muốn nắm nhanh các quyết định chính, để comment đúng chỗ trước hạn |
| Actor | PM reviewer / Design Lead |
| Thời điểm / bối cảnh | Trước các buổi review tài liệu kỹ thuật |
| Quy trình hiện tại (3–7 bước) | 1. Mở tài liệu · 2. Đọc lướt toàn văn 10-15 trang · 3. Đọc kỹ phần scope · 4. Ghi chú câu hỏi · 5. Viết comment |
| Bottleneck (bước nào, mất bao nhiêu phút) | Đọc lướt toàn văn để lấy ngữ cảnh (mất 25 phút) |
| Impact (nếu không giải thì sao) | Mất thời gian đọc rà soát, dễ bỏ sót edge cases |
| Success metric (baseline → target) | Giảm thời gian review từ 45 phút xuống dưới 20 phút |
| Phương án không dùng AI | Mục lục chuẩn + Executive summary do tác giả viết |
| Giả thuyết về AI (nếu có) | AI tóm tắt 3 ý chính và cảnh báo điểm mù trong PRD |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:
```text
[Mở doc: 2'] → [Đọc lướt toàn văn: 25'] ← BOTTLENECK
→ [Đọc scope: 10'] → [Viết comment: 8']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần biết vì sao team từng chọn phương án A, tôi muốn tìm lại được quyết định cũ, để không tranh luận lại từ đầu |
| Actor | Thành viên team sản phẩm / Engineering |
| Thời điểm / bối cảnh | Khi bắt đầu tính năng mới hoặc gặp lại lỗi cũ |
| Quy trình hiện tại (3–7 bước) | 1. Nhớ lại thời điểm thảo luận · 2. Search keyword trên Slack · 3. Lọc qua nhiều channel · 4. Đọc lại thread dài · 5. Tổng hợp kết luận |
| Bottleneck (bước nào, mất bao nhiêu phút) | Đọc lại thread dài và lọc thông tin (mất 12 phút) |
| Impact (nếu không giải thì sao) | Tranh luận lại vấn đề đã chốt, mất thời gian họp |
| Success metric (baseline → target) | Thời gian tìm kiếm giảm từ 15 phút xuống dưới 2 phút |
| Phương án không dùng AI | Quy định ghim kết luận (Decision Log) vào Confluence/Notion |
| Giả thuyết về AI (nếu có) | AI semantic search tìm đúng đoạn quyết định trong kho message cũ |
| Cảm nhận nhanh | Workflow hoặc Agent |

Quy trình nháp hiện tại:
```text
[Nhớ thời điểm: 2'] → [Search keyword: 3'] 
→ [Đọc lại thread dài: 12'] ← BOTTLENECK → [Tổng hợp: 3']
```

### Card muốn pitch nhất

- Card số: Card #1 (Báo cáo tuần)
- Vì sao: Baseline đo được rõ ràng (bấm giờ thực tế), có dữ liệu mẫu và quy trình hiện tại cụ thể, dễ so sánh các mức can thiệp.
- Câu hỏi muốn nhóm phản biện: *"Baseline 90 phút có quá chủ quan không, và liệu leadership có thực sự đọc phần narrative hay chỉ nhìn vào số liệu?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 90 phút chỉ dựa trên trí nhớ cá nhân | Đồng ý | Bấm giờ thật 2 tuần liên tiếp: ghi nhận 85 và 95 phút |
| Chưa chắc CEO đọc phần narrative mà chỉ xem số | Đồng ý một phần | Đưa vào danh sách giả định cần kiểm chứng (Assumption Map) ở CP4 |
| Gợi ý làm Agent tự động gửi báo cáo đi | Không đồng ý | Giữ nguyên boundary cứng: "PM phải review trước khi gửi" |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Top 3 Problem Cards cá nhân, trọng tâm là Card #1: "Báo cáo tuần của PM" (với baseline bấm giờ thực tế 85 và 95 phút trong 2 tuần, bottleneck 25 phút ở bước viết narrative). | Card #1 được đưa vào shortlist và được cả nhóm thống nhất chọn làm candidate problem chính thức để đi sâu từ CP3 đến CP6. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Hỏi Quốc ở Card mất trộm xe máy: *"Camera sẵn có đã phát hiện người và có còi hú, nhưng nếu đặt trước cửa hàng quần áo đông người qua lại ban ngày thì Rule đứng quá N giây sẽ báo nhầm liên tục; hơn nữa một cửa hàng bao lâu mới mất xe một lần để đo metric?"* (2) Hỏi Hiệp ở Card đọc hiểu repo bài lab: *"Bạn đã bấm giờ thực tế từng bước chưa, và nếu chỉ làm một bảng checklist đối chiếu theo README thì đã giải quyết được vấn đề mà không cần tới AI chưa?"* | Giúp nhóm nhận thấy bài mất xe máy của Quốc có độ khó cao khi kiểm chứng tần suất thực tế trong buổi lab, còn bài đọc hiểu repo của Hiệp có thể giải quyết triệt để bằng No AI (checklist), từ đó hội tụ về bài toán có tần suất hàng tuần rõ ràng hơn. |
| Nhận phản biện | Câu hỏi tôi nhận được: Quốc và Hiệp hỏi: *"Baseline 90 phút có quá chủ quan từ một người không? Nếu chỉ dùng dashboard Jira + template cố định thì đã giảm được bao nhiêu thời gian rồi, và liệu CEO/EM có thực sự đọc phần chữ narrative hay chỉ nhìn vào các con số?"* | Tôi đã sửa gì: Tôi bổ sung rõ phương án No AI cho các team chỉ xem số, đồng thời đưa giả định *"Leadership thực sự đọc phần narrative chứ không chỉ xem số"* vào Assumption Map ở CP4 để kiểm chứng bằng phỏng vấn thực tế. |
| Gom cluster / cây OST | Cùng Hiệp và Quốc gom 9 Problem Cards của cả nhóm thành các cụm pattern chung và xây dựng cây Opportunity Solution Tree rút gọn từ 1 Outcome đo lường được. | Xác lập Outcome gốc rõ ràng và tách biệt hoàn toàn tầng Opportunity khỏi các giải pháp đội lốt. |
| Chọn candidate problem | Thiết lập bảng chấm điểm 7 tiêu chí cho shortlist 3 bài toán đại diện của 3 thành viên và cùng nhóm thảo luận lý do chọn/loại từng bài. | Chốt chọn "Báo cáo tuần của PM" và ghi rõ lý do loại các bài khác. |
| Kiểm chứng / research | Lập Assumption Map, thực hiện hỏi nhanh theo đúng 3 luật của The Mom Test và trực tiếp mở kiểm tra từng link công cụ (Atlassian Rovo, Aneto, n8n workflow, Slack AI). | Phát hiện cộng đồng báo cáo Rovo tính toán số liệu chưa ổn định và gói Slack Pro bị giới hạn tính năng recap từ 6/2025, giúp nhóm đổi hoàn toàn kết luận từ "tự xây công cụ AI" sang "dùng Rule lấy số + AI sẵn có soạn nháp + PM duyệt". |
| Quy trình nhóm | Vẽ chi tiết sơ đồ quy trình Hiện tại và quy trình Tương lai kèm bảng so sánh Before/After. | Tách rõ từng bước: Bước 1 dùng Rule lấy số liệu, Bước 2–3 dùng AI tóm tắt và soạn nháp narrative, Bước 4–5 do Con người (PM) kiểm duyệt và gửi, kèm phương án quay về template cũ nếu nháp lỗi. |
| Problem Statement | Soạn thảo Problem Statement v0 ở CP5, dùng AI phản biện tìm lỗ hổng và nâng cấp lên bản Problem Statement v1 ở CP6. | Thu hẹp Actor ở bản v1, bổ sung 2 metric chất lượng và viết 4 tiêu chí đánh giá cụ thể. |
| Mức can thiệp AI | Đặt bài toán lên ma trận Độ mơ hồ × Độ phức tạp, lập bảng so sánh 4 mức No AI / Rule / Workflow / Agent, điền AI Canvas rút gọn và trả lời 2 câu hỏi Google PAIR. | Chứng minh rõ vì sao chọn mức Workflow thay vì Agent, và vì sao lỗi "bỏ sót rủi ro/blocker" nguy hiểm hơn "báo nhầm" để ưu tiên kiểm soát trong bộ tiêu chí eval. |
| Quyết định | Đánh giá mức độ 4 rủi ro lớn (Value, Usability, Feasibility, Viability) theo khung Marty Cagan và thiết kế kế hoạch Pilot 2 tuần. | Thống nhất với nhóm quyết định cuối cùng |

---


## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm problem theo vai trò PM | Gợi ý nhanh ý #9 và #10 về báo cáo tháng | Đưa ra ý quá rộng *"trợ lý quản lý dự án toàn năng"* | Loại bỏ ý không có quy trình thật |
| CP2 Problem Card | Đóng vai PM hoài nghi phản biện card | Chỉ ra điểm yếu về baseline chủ quan | Gợi ý dùng Agent tự động hóa toàn phần | Giữ vững boundary PM duyệt thủ công |
| CP4 Research | Tìm các dòng camera chống trộm phổ thông, tính năng AI phát hiện người và giải pháp khóa báo động hiện có trên thị trường | Gợi ý nhanh các dòng camera Imou/Ezviz có sẵn Human Detection, vùng cảnh báo | Đưa một số link sản phẩm đã ngừng kinh doanh khẳng định tính năng "AI phát hiện người" của camera giá rẻ đủ sức chống trộm trước cửa hàng | Tự mở kiểm tra từng link sống ghi rõ khoảng trống: camera có sẵn chỉ phát hiện "có người đứng trong vùng" chứ chưa phân biệt được "khách dắt xe của mình" với "kẻ gian cúi bẻ khóa" vào ban ngày |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe Quốc trình bày các bài toán về mất trộm xe máy trước cửa hàng quần áo, nỗi lo triệu chứng sau xuất viện và nghe Hiệp chia sẻ về việc bị kẹt khi thiết lập môi trường Python/Codex cũng như đọc hiểu cấu trúc bài lab, tôi học được cách nhìn nhận sự đa dạng của "dấu hiệu thật" trong đời sống và học tập. Tôi nhận ra một vấn đề rất đau về mặt cảm xúc và tiền bạc (như mất chiếc xe 20 triệu đồng của bạn Quốc) lại có đặc thù hoàn toàn khác với một vấn đề lặp đi lặp lại hàng tuần trong công việc (như báo cáo tuần của PM). Việc đặt các bài toán cạnh nhau giúp tôi hiểu rằng khi chọn bài toán để đưa vào quy trình sản phẩm, tần suất xuất hiện đều đặn và khả năng thiết lập thực nghiệm đo lường nhanh đóng vai trò quyết định.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, bản thân tôi và nhóm đã vấp phải tư duy "solution-first" ở hai thời điểm. Lần thứ nhất là khi mới bắt đầu gom cụm và vẽ cây OST ở CP3, chúng tôi đã định viết các nhánh như "Xây dựng dashboard tự động nối Jira với Sheets" hay "Dùng chatbot tổng hợp Slack". Khi rà lại nguyên tắc của Teresa Torres rằng tầng Opportunity chỉ được chứa nỗi đau của người dùng, cả nhóm đã gạch bỏ ngay các dòng đó và viết lại thành nỗi đau số liệu nằm rải rác và áp lực ngồi viết nhận định từ trang trắng. Lần thứ hai là trước khi làm CP4, tôi vẫn mang tâm lý muốn "tự xây một công cụ hoặc agent viết báo cáo tuần", cho đến khi kết quả research công cụ sẵn có buộc cả nhóm phải nhìn lại bài toán một cách thực tế hơn.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý rất rõ ở hai điểm sau khi nhận phản biện từ Quốc, Hiệp và từ AI đóng vai PM hoài nghi. Ban đầu trong Problem Statement v0 và Card #1, tôi mặc định rằng mọi PM làm báo cáo tuần đều cần AI hỗ trợ viết narrative và chỉ đặt Success Metric duy nhất là giảm thời gian từ 90 phút xuống dưới 30 phút. Khi Quốc phản biện rằng *"Liệu sếp có thực sự đọc phần chữ narrative không hay chỉ nhìn bảng số, và nếu chỉ cần số thì một template kèm dashboard đã đủ chưa?"*, kết hợp với việc AI chỉ ra lỗ hổng *"báo cáo làm nhanh hơn nhưng chất lượng tệ hơn thì sao"*, tôi đã hoàn toàn đồng tình. Tôi đã thu hẹp lại Actor ở bản v1 (chỉ dành cho team mà leadership thực sự đọc narrative, còn team chỉ xem số thì dùng No AI/Rule) và bổ sung thêm metric tỉ lệ phải viết lại bản nháp dưới 50%.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả kiểm chứng và research ở CP4 làm tôi bất ngờ ở hai điểm lớn. Thứ nhất, khi phỏng vấn theo The Mom Test và khảo sát nhanh, dù đa số xác nhận bước viết nhận định (narrative) ngốn nhiều thời gian nhất, vẫn có 1/3 người được hỏi và 2/6 người trong khảo sát cho biết ở team của họ, dashboard số liệu và template cố định đã là đủ vì CEO chỉ lướt xem số. Nếu không hỏi hành vi thực tế mà chỉ hỏi câu dẫn dắt kiểu *"Bạn có muốn công cụ AI viết báo cáo không?"*, chắc chắn họ đã gật đầu khen hay và làm nhóm đi lệch hướng. Thứ hai, khi tự mở từng link research Atlassian Rovo và n8n, tôi thấy thị trường đã có sẵn công cụ giải quyết tới 80% quy trình nhưng Rovo lại bị phản ánh là tính toán số liệu chưa ổn định — điều này củng cố quyết định phải dùng Rule để lấy số chứ không giao phần số liệu cho AI.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất khi viết Problem Statement là giữ được sự cân bằng giữa tính cụ thể và tính mở: phải viết sao cho Bottleneck, Impact và Success Metric cực kỳ rõ ràng, có con số baseline và target đo đếm được, nhưng lại tuyệt đối không được lồng ghép giải pháp công nghệ vào trong bản mô tả vấn đề ở v0. Ngoài ra, việc chuyển hóa các giới hạn an toàn (Boundary) thành các tiêu chí đánh giá (eval) cụ thể ở bản v1 — chẳng hạn như định nghĩa thế nào là một bản nháp "đạt" về mặt số liệu, không bỏ sót blocker và không bịa nhận định — đòi hỏi phải hiểu rất sâu quy trình thật của người dùng chứ không thể viết chung chung.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được làm lại, tôi sẽ thực hiện kiểm chứng giả định số #3 (*"Leadership thực sự đọc phần narrative chứ không chỉ xem số"*) trực tiếp với người nhận báo cáo (EM hoặc CEO) và kiểm tra chính sách bảo mật dữ liệu nội bộ (giả định #5) ngay từ trước khi thiết kế luồng tương lai, thay vì để hai giả định quan trọng này sang giai đoạn chuẩn bị chạy pilot mới hỏi. Tôi cũng sẽ phản biện nhóm mạnh hơn ở việc thiết lập bộ dữ liệu mẫu (eval dataset) gồm ít nhất 5–10 báo cáo tuần cũ trong quá khứ để chấm thử chất lượng bản nháp ngay trong buổi lab, giúp quyết định Go có thêm bằng chứng thực nghiệm vững chắc hơn.

**6.7. Hiểu bài:**
Bài toán của nhóm bắt nguồn từ việc Junior PM (ở các team mà lãnh đạo đọc phần nhận định) phải tốn trung bình 90 phút mỗi sáng thứ Hai để làm báo cáo tuần, dẫn đến việc gửi trễ trong 3/8 tuần gần nhất và làm lãnh đạo thiếu thông tin trước giờ họp. Quy trình hiện tại gồm 7 bước thủ công liên tiếp (export Jira, lấy số từ Google Sheets, đọc lại Slack cả tuần, gom vào Google Docs, viết nhận định narrative, tự review định dạng và gửi email), trong đó bước nghẽn chính (bottleneck) là mất khoảng 25 phút ngồi viết phần narrative từ dữ liệu thô để nêu bật kết quả, rủi ro và việc cần làm tiếp theo. Để đo lường hiệu quả giải quyết, nhóm đặt Success Metric gồm 3 phần: giảm tổng thời gian từ 90 phút xuống dưới 30 phút, tỉ lệ PM phải viết lại bản nháp dưới 50%, và số câu hỏi làm rõ từ CEO/EM không tăng so với 4 tuần trước pilot. Nhóm vạch rõ Boundary: AI không được tự ý gửi báo cáo, không được tự sửa hay tính toán số liệu, và không được bịa ra nhận định không có căn cứ trong dữ liệu đầu vào. Khi phân tích mức can thiệp, nhóm không chọn Agent vì quy trình đã có các bước cố định và cần kiểm soát chặt quyền truy cập, mà chọn mức Workflow kết hợp Rule: dùng Rule/script tự động gom số liệu chuẩn xác vào template, dùng AI (Rovo hoặc prompt chuẩn) soạn nháp phần narrative, và bắt buộc có con người (PM) kiểm tra đối chiếu từng con số cùng các blocker trước khi gửi (kèm phương án quay về viết tay trên template cũ nếu nháp lỗi). Cuối cùng, vì cả 4 rủi ro (Value, Usability, Feasibility, Viability) đều ở mức Thấp hoặc Trung bình và có sẵn công cụ để thử ngay, nhóm ra quyết định "Go, phạm vi nhỏ" qua đợt chạy pilot 2 tuần với ngưỡng dừng định lượng: nếu 2 tuần liên tiếp PM phải viết lại trên 70% bản nháp, hoặc để lọt số liệu sai mà không phát hiện, hoặc công ty không cho phép đưa dữ liệu nội bộ vào công cụ AI thì sẽ dừng ngay và chuyển sang phương án No AI/Rule (dùng template và dashboard cố định).

---

## 7. Tài liệu tham khảo
- Atlassian. What is Rovo? (Rovo Search, Rovo Chat & AI Agents).
- Aneto Software. AI Executive Status Reports for Jira (AI-generated executive reports from Jira issues using JQL filters and templates).
- n8n. Generate daily Jira summaries & weekly reports with Azure OpenAI and Gmail (Jira integration, AI summarization & automated weekly reporting workflow).
- Slack. Guide to AI features in Slack (Conversation Summaries, Huddle Notes, AI Search & feature availability by subscription plan).