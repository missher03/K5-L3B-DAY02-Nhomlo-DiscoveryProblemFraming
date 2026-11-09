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
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---


## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm problem theo vai trò PM | Gợi ý nhanh ý #9 và #10 về báo cáo tháng | Đưa ra ý quá rộng *"trợ lý quản lý dự án toàn năng"* | Loại bỏ ý không có quy trình thật |
| CP2 Problem Card | Đóng vai PM hoài nghi phản biện card | Chỉ ra điểm yếu về baseline chủ quan | Gợi ý dùng Agent tự động hóa toàn phần | Giữ vững boundary PM duyệt thủ công |
| CP4 Research | Tìm kiếm công cụ và case tương tự | Gợi ý nhanh Atlassian Rovo, Slack AI, n8n | Đưa 1 link Google Help đã lỗi; nói sai về gói Slack | Tự mở từng link kiểm chứng; check lại giá gói Pro |
| CP5 Quy trình | Chuyển đổi mô tả quy trình sang Mermaid | Vẽ sơ đồ nhanh chóng | Gộp nhầm bước "viết narrative" và "review" thành một | Tách lại vì bottleneck nằm ở viết narrative |
| CP5–6 Problem Statement | Phản biện 6 trường Problem Statement | Chỉ ra thiếu metric chất lượng (nháp tệ thì sao) | Đề xuất thêm các chỉ số phức tạp ngoài tầm lab | Lọc lại các metric đo được thực tế (tỉ lệ viết lại) |
| CP6 Mức can thiệp / quyết định | So sánh 4 mức can thiệp AI | Xây dựng bảng so sánh No AI / Rule / Workflow / Agent | Mặc định khuyên dùng Workflow cho mọi thứ | Giữ lập luận No AI cho team chỉ cần số |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:**

---

## 7. Tài liệu tham khảo
- Atlassian. What is Rovo? (Rovo Search, Rovo Chat & AI Agents).
- Aneto Software. AI Executive Status Reports for Jira (AI-generated executive reports from Jira issues using JQL filters and templates).
- n8n. Generate daily Jira summaries & weekly reports with Azure OpenAI and Gmail (Jira integration, AI summarization & automated weekly reporting workflow).
- Slack. Guide to AI features in Slack (Conversation Summaries, Huddle Notes, AI Search & feature availability by subscription plan).