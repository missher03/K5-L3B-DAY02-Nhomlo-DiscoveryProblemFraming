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
| 1 | Lặp lại, tốn thời gian | Khi làm nhóm trưởng thu gom bài báo cáo Markdown từ branch riêng của các thành viên vào cuối buổi lab, tôi muốn biết ngay file của bạn nào còn thiếu mục bắt buộc hoặc lệch cấu trúc trước khi merge vào `main`, để cả nhóm không bị trừ điểm oan. | Tôi (nhóm trưởng) và 3 thành viên cùng nhóm | Trong 2 buổi lab liên tiếp (Day 01 và Day 02), tôi mất trung bình 25–30 phút/buổi mở từng branch để đọc rà thủ công 3–4 file `.md`; từng suýt merge 1 file bị thiếu nửa dưới nội dung và 1 file ảnh sai định dạng `.jpg` thay vì `.png`. |
| 2 | Tốn thời gian | Khi dùng máy tính cá nhân đăng nhập song song 2 tài khoản GitHub để push bài tập lên repo chung, tôi muốn biết ngay phiên xác thực hiện tại đang nhận tài khoản nào và thiếu quyền gì, để không bị chặn bởi lỗi 403 lúc sát giờ nộp bài. | Bản thân tôi khi làm bài lab trên VS Code | Tối ngày 09/11/2026, tôi mất 20 phút xử lý lỗi `Permission denied to chau2h / Lmeo2h (error 403)` trong Terminal, phải mở Windows Credential Manager xóa đi tạo lại Personal Access Token 3 lần mới push được branch cá nhân. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu một bài lab mới có 6–7 file hướng dẫn dài (`README`, `RULES`, `CHECKPOINTS`, `RUBRIC`, `WORKSHEET`, `SUBMISSION`), tôi muốn nắm được ngay danh sách các điều kiện bị trừ điểm nặng và thứ tự đầu việc theo từng mốc giờ, để không bỏ sót yêu cầu khi đang làm gấp. | Tôi và các học viên trong lớp K5-L3B | Đầu buổi lab ngày 09/11/2026, tôi mất 35 phút mở qua lại 6 file `.md` trong repo (tổng cộng hơn 2.500 dòng chữ) để ghi chú lại các lỗi bị trừ 5 điểm hoặc 0 điểm; trong nhóm có 2/3 thành viên phải hỏi lại thứ tự làm CP1–CP2. |
| 4 | Pain từ người khác, lặp lại | Khi các thành viên trong nhóm làm bài trên máy cá nhân rồi báo "chạy lệnh cài thư viện bị lỗi không tìm thấy file", tôi muốn nhìn thấy ngay đường dẫn thư mục hiện tại và trạng thái môi trường ảo của họ, để chỉ đúng lệnh cần sửa thay vì đoán mò qua tin nhắn. | Tôi và 2 bạn cùng nhóm khi cài đặt môi trường Python | Trong buổi lab vừa qua, nhóm có 3 lần bị kẹt ở bước `pip install -r requirements.txt` và lệnh chạy Python (tốn 15–20 phút/lần chụp màn hình hỏi qua lại trên Discord/Zalo) chỉ vì Terminal đang đứng ở thư mục cha bên ngoài repo. |
| 5 | Cần đọc, tổng hợp nhiều thông tin, tốn thời gian | Khi tìm mua đồ công nghệ hoặc bàn phím cơ cũ trên các hội nhóm Facebook và sàn thương mại điện tử, tôi muốn đối chiếu nhanh lịch sử giá bán thật và các lỗi vặt hay gặp của mẫu đó từ người dùng trước, để không mua hớ hoặc mua nhầm hàng lỗi. | Tôi (người mua đồ công nghệ cũ) | Tháng trước khi tìm mua bàn phím cơ cũ, tôi mất gần 3 tiếng trong 2 buổi tối lướt đọc hơn 40 bài đăng và bình luận trên 3 group Facebook khác nhau; có 2 lần nhắn hỏi xong mới phát hiện người bán đăng giá cao hơn mặt bằng 200.000đ. |
| 6 | Lặp lại | Khi viết báo cáo tiến độ cá nhân (Daily Standup) mỗi buổi sáng trong chương trình học, tôi muốn gom nhanh những việc mình đã làm xong hôm qua, kế hoạch hôm nay và điểm đang vướng từ lịch sử commit/ghi chú, để gửi đúng giờ trước 9h sáng. | Tôi và các học viên cùng khóa | Thực hiện đều đặn 5–6 ngày/tuần; mỗi sáng mất khoảng 10–12 phút mở lại Git log và ghi chú rời rạc để nhớ lại hôm qua đã sửa những file nào; trong 2 tuần qua có 2 lần tôi gửi muộn sau 9h15 vì mải tìm lại tên task. |
| 7 | Tốn thời gian | Khi làm dự án web/app theo nhóm ở trường và cần tích hợp API từ phần Backend của bạn khác viết, tôi muốn biết ngay các trường dữ liệu JSON trả về đã thay đổi ở đâu so với tài liệu ban đầu, để sửa giao diện luôn mà không phải chạy thử từng màn hình rồi chờ hỏi lại. | Tôi (làm Frontend) và bạn làm Backend trong nhóm đồ án | Trong đợt làm đồ án gần nhất (nhóm 4 người), trung bình mỗi tuần có 3–4 lần giao diện bị lỗi trắng trang do Backend đổi tên trường dữ liệu mà quên báo; mỗi lần dò `console.log` và nhắn hỏi lại mất 20–25 phút. |

**Nếu có dùng AI để gợi ý thêm:** Sau khi tự liệt kê 8 vấn đề đầu tiên từ trải nghiệm làm bài lab, làm đồ án và học tập của chính mình, tôi dùng AI gợi ý thêm góc nhìn đời sống và giữ lại ý #9 (người thân hỏi tin nhắn lạ) và #10 (chia tiền phòng trọ cuối tháng) sau khi viết lại bằng đúng số liệu thật của mình. Tôi đã loại bỏ các gợi ý quá rộng và mang tính giải pháp sẵn của AI như *"xây dựng hệ thống AI tự động chấm điểm code toàn diện"* hay *"ứng dụng quản lý tài chính cá nhân thông minh"* vì không bám vào một quy trình thủ công cụ thể nào của tôi.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Rà soát file báo cáo Markdown trước khi merge vào `main` (#1) | Vấn đề xảy ra ngay trong các buổi lab của nhóm, quy trình 6 bước rõ ràng, có thời gian bấm giờ thật và hậu quả mất điểm được ghi rõ trong Rubric | Nếu chỉ dùng một bảng checklist thủ công kèm lệnh kiểm tra tên file bằng script (Rule) thì đã bắt được 90% lỗi chưa, có thực sự cần tới AI đọc nội dung không? |
| 2 | Đọc và tổng hợp quy tắc/tiêu chí chấm từ nhiều file hướng dẫn lab (#3) | Cả 3 thành viên trong nhóm đều gặp (Hiệp cũng đưa vấn đề này vào Top 1 của bạn ấy), tốn 35 phút đầu mỗi buổi lab | Việc đọc chậm là do tài liệu phân tán ở 6 file hay do học viên chưa quen đọc theo mục "Thứ tự đọc" trong `README`? |
| 3 | Tổng hợp và đối chiếu tiền ứng trước trong nhóm chat phòng trọ (#10) | Quy trình thủ công lặp lại hàng tháng, mất 40–45 phút kéo đọc lại tin nhắn và ảnh chụp màn hình, dễ cộng sót | Nếu cả phòng thống nhất đổi thói quen ghi ngay vào 1 file Google Sheets chung lúc vừa mua đồ (No AI) thì họ có duy trì được không? |

### Problem Card #1 — Rà soát báo cáo cá nhân/nhóm trước khi merge vào `main`

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm nhóm trưởng thu gom bài báo cáo Markdown từ branch riêng của các thành viên vào cuối buổi lab, tôi muốn biết ngay file của bạn nào còn thiếu mục bắt buộc hoặc lệch cấu trúc trước khi merge vào `main`, để cả nhóm không bị trừ điểm oan. |
| Actor | Học viên đóng vai trò Nhóm trưởng (hoặc người phụ trách merge nhánh `main`) trong các buổi lab làm việc nhóm trên GitHub. |
| Thời điểm / bối cảnh | 30–45 phút cuối cùng trước hạn nộp bài lab (deadline 23h59 hoặc 11h59 hôm sau), khi các thành viên vừa push bài từ branch cá nhân lên repo chung. |
| Quy trình hiện tại (3–7 bước) | 1. Nhắn giục các thành viên push branch cá nhân · 2. Chạy `git fetch` và mở xem từng branch · 3. Kiểm tra tên file và định dạng ảnh (`.md`, `.png`) · 4. Mở `RUBRIC.md` và `CHECKPOINTS.md` đối chiếu từng mục xem file của bạn mình có bị thiếu bảng/câu trả lời hay còn sót chữ mẫu `[TODO]` không · 5. Nhắn lại trên Zalo yêu cầu bạn sửa những chỗ thiếu · 6. Chạy lệnh `git checkout` lấy các file chuẩn sang `main` rồi push. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 — Đọc rà thủ công từng file báo cáo dài 200–300 dòng để đối chiếu với các tiêu chí trong `RUBRIC.md` và `CHECKPOINTS.md` (mất khoảng 15 phút/lần cho 3–4 file, rất dễ nhìn sót khi đang vội). |
| Impact (nếu không giải thì sao) | Mất 25–30 phút căng thẳng ở cuối mỗi buổi lab; nếu nhìn sót lỗi sai tên file sẽ bị trừ 5 điểm, thiếu mục hoặc nộp nhầm file bị cắt cụt nội dung có thể làm mất từ 6 đến 15 điểm của cá nhân/nhóm. |
| Success metric (baseline → target) | Thời gian rà soát toàn bộ các file trước khi merge giảm từ **25–30 phút xuống dưới 5 phút/buổi lab**; tỉ lệ phát hiện đúng các mục còn trống, dòng template chưa xóa hoặc sai quy cách đặt tên file đạt **100%** trước khi push lên `main`. |
| Phương án không dùng AI | Lập một bảng Checklist kiểm tra 10 mục cố định trước khi nộp (dựa sẵn vào `SUBMISSION.md`) + viết một script ngắn (Rule/Regex) tự động kiểm tra tên file, đuôi ảnh `.png`, đếm số dòng trong bảng Scan và đếm số từ ở mục Reflection (> 200 từ). |
| Giả thuyết về AI (nếu có) | Sau khi script đã kiểm tra xong phần khung (tên file, số từ, số dòng bảng), dùng AI đọc lướt nội dung để cảnh báo các lỗi ngữ nghĩa mà Rule khó bắt (ví dụ: cột Job Story vô tình chứa giải pháp, hoặc câu hỏi phỏng vấn vi phạm luật The Mom Test). |
| Cảm nhận nhanh | Rule kết hợp Workflow |

Quy trình nháp hiện tại:
```text
HIỆN TẠI — 28 phút/buổi lab

[1 Giục & chờ push branch: 3'] → [2 Fetch & mở các branch: 2'] → [3 Kiểm tên file & đuôi ảnh: 3']
→ [4 Đọc rà từng mục đối chiếu Rubric/Checklist: 15'] ← BOTTLENECK
→ [5 Nhắn bạn sửa chỗ thiếu: 3'] → [6 Checkout sang main & push: 2']
```

### Problem Card #2 — Đọc và tổng hợp yêu cầu từ nhiều file hướng dẫn bài lab

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một bài lab mới có 6–7 file hướng dẫn dài, tôi muốn nắm được ngay danh sách các điều kiện bị trừ điểm nặng và thứ tự đầu việc theo từng mốc giờ, để không bỏ sót yêu cầu khi đang làm gấp. |
| Actor | Học viên tham gia các buổi Codelab / Product Lab có tài liệu hướng dẫn chia thành nhiều file Markdown trên GitHub. |
| Thời điểm / bối cảnh | 30 phút đầu tiên khi vừa clone/fork repo bài lab mới về máy và chuẩn bị phân chia công việc cho nhóm. |
| Quy trình hiện tại (3–7 bước) | 1. Mở `README.md` xem giới thiệu chung · 2. Mở lần lượt `RULES.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `01-worksheet.md`, `SUBMISSION.md` · 3. Đọc lướt hơn 2.000 dòng để tìm xem phải nộp những file gì và chấm điểm ra sao · 4. Ghi chú lại các mục dễ bị trừ điểm · 5. Giải thích lại cho các bạn trong nhóm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Đọc đối chiếu chéo giữa `CHECKPOINTS.md`, `01-worksheet.md` và `RUBRIC.md` để biết mỗi mục trong file nộp bài cần đạt điều kiện gì mới được tối đa điểm (mất 20 phút). |
| Impact (nếu không giải thì sao) | Tốn 35 phút đầu giờ chỉ để định hình cách làm; học viên dễ làm sót các yêu cầu ẩn (như quên ghi phản biện của AI ở CP2 làm mất 1 điểm bắt buộc, hoặc viết thiếu 200 từ ở CP7). |
| Success metric (baseline → target) | Giảm thời gian đọc hiểu và lập danh sách đầu việc đầu buổi lab từ **35 phút xuống dưới 10 phút**; các thành viên trong nhóm không phải hỏi lại các câu về quy cách tên file và thứ tự làm bài. |
| Phương án không dùng AI | Tuân thủ đúng bảng "Thứ tự đọc" trong `README.md` và điền vào một tờ "Tóm tắt 1 trang" (One-page Cheat Sheet) gồm 3 cột: Mục phải điền — Điều kiện đạt điểm tối đa — Lỗi bị trừ điểm. |
| Giả thuyết về AI (nếu có) | Đưa các file `CHECKPOINTS.md` và `RUBRIC.md` vào AI để trích xuất bảng đối chiếu yêu cầu từng mục kèm trích dẫn chính xác tên file nguồn để học viên tự kiểm lại. |
| Cảm nhận nhanh | No AI (Checklist 1 trang) hoặc Workflow |

Quy trình nháp hiện tại:
```text
HIỆN TẠI — 35 phút/đầu buổi lab

[1 Mở README: 3'] → [2 Mở 5 file hướng dẫn còn lại: 2']
→ [3 Đọc đối chiếu chéo Worksheet & Rubric: 20'] ← BOTTLENECK
→ [4 Ghi chú các bẫy trừ điểm: 5'] → [5 Phổ biến lại cho nhóm: 5']
```

### Problem Card #3 — Tổng hợp khoản chi ứng trước và chia tiền phòng trọ cuối tháng

| Trường | Nội dung |
|---|---|
| Job Story | Khi cả phòng trọ 3 người cùng góp tiền đi chợ và thanh toán hóa đơn điện, nước, wifi hàng tháng, tôi muốn tổng hợp nhanh ai đã ứng trước khoản nào từ các tin nhắn chuyển khoản rải rác trong nhóm Zalo, để chia tiền cuối tháng chính xác mà không phải ngồi cộng tay lại từ đầu. |
| Actor | Người đại diện tính tiền cuối tháng trong phòng trọ sinh viên / người đi làm ở ghép (3–4 người). |
| Thời điểm / bối cảnh | Tối ngày cuối cùng của tháng, khi có đủ hóa đơn điện, nước, mạng và cần chốt số tiền mỗi người phải chuyển bù. |
| Quy trình hiện tại (3–7 bước) | 1. Mở nhóm chat Zalo của phòng · 2. Kéo ngược lịch sử tin nhắn và mục Ảnh/File của cả tháng · 3. Đọc từng tin nhắn báo mua đồ và mở từng ảnh bill chuyển khoản · 4. Gõ tay từng khoản (ngày, người chi, số tiền, chia cho ai) vào bảng tính · 5. Cộng tổng và nhắn số tiền chênh lệch cho từng người. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4 — Lọc tìm trong hàng trăm tin nhắn chat và mở từng ảnh chụp bill để gõ lại số tiền vào bảng tính (mất 30 phút). |
| Impact (nếu không giải thì sao) | Mất 40–45 phút mỗi cuối tháng; dễ bỏ sót các khoản mua lặt vặt chỉ nhắn bằng chữ hoặc cộng nhầm phải rà lại từ đầu. |
| Success metric (baseline → target) | Giảm thời gian chốt sổ cuối tháng từ **45 phút xuống dưới 10 phút/tháng**; số khoản chi bị bỏ sót giảm về **0**. |
| Phương án không dùng AI | Quy định cả phòng dùng chung một link Google Form gắn sẵn với Google Sheets hoặc app Splitwise: ai vừa trả tiền xong phải nhập ngay trong 30 giây thì mới được tính vào quỹ phòng. |
| Giả thuyết về AI (nếu có) | Cuối tháng xuất đoạn chat hoặc ảnh bill đưa vào công cụ đọc ảnh/văn bản để trích xuất thành bảng CSV cho người tính tiền kiểm lại trước khi chốt. |
| Cảm nhận nhanh | No AI (Đổi quy trình nhập liệu ngay lúc chi) |

Quy trình nháp hiện tại:
```text
HIỆN TẠI — 45 phút/tháng

[1 Mở nhóm Zalo: 2'] → [2 Kéo tìm lịch sử chat & ảnh cả tháng: 8']
→ [3 Đọc từng bill & gõ tay vào bảng tính: 30'] ← BOTTLENECK
→ [4 Kiểm tra lại & gửi bảng chốt tiền: 5']
```

### Card muốn pitch nhất

- Card số: **Card #1 (Rà soát báo cáo cá nhân/nhóm trước khi merge vào `main`)**
- Vì sao: Đây là nỗi đau sát sườn mà nhóm trưởng nào trong lớp cũng đang trải qua ngay trong buổi lab, có số phút thật (25–30 phút) và ranh giới cực kỳ rõ ràng giữa phần kiểm tra cấu trúc (dùng Rule/script) với phần kiểm tra nội dung (dùng AI hoặc người đọc).
- Câu hỏi muốn nhóm phản biện: *"Trong 25–30 phút rà bài trước khi merge, phần tốn thời gian nhất là kiểm tra các quy tắc cứng (tên file, số dòng, số từ) hay đọc hiểu nội dung bên trong? Nếu một script kiểm tra tự động kèm checklist thủ công đã giải quyết được 80% lỗi bị trừ điểm thì có cần dùng tới AI không?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Các lỗi như sai tên file `MSSV_HoTen.md`, sai đuôi ảnh `.png`, thiếu đủ 5 dòng bảng Scan hay viết dưới 200 từ ở mục 6 đều là điều kiện đếm được chính xác 100% bằng một script Python/Bash đơn giản hoặc checklist, hoàn toàn không cần gọi LLM. | Đồng ý | Sửa lại trường "Phương án không dùng AI" và "Cảm nhận nhanh": ưu tiên dùng Checklist + Rule/script cho toàn bộ các lỗi định dạng và số lượng; chỉ cân nhắc AI ở bước phụ trợ kiểm tra lỗi ngữ nghĩa (như câu hỏi phỏng vấn phạm luật Mom Test). |
|Nếu chỉ tính riêng việc merge bài trong một buổi lab thì chỉ diễn ra vài lần trong khóa học, thời gian viết công cụ tự động có thể lâu hơn thời gian tự kiểm bằng tay. | Đồng ý một phần | Làm rõ rằng phương án khả thi nhất ngay trong buổi lab là lập bảng Checklist chuẩn hóa (No AI) để dùng chung cho các thành viên tự kiểm trước khi push, giúp nhóm trưởng không phải gánh toàn bộ ở bước cuối. |
|Nếu dùng AI tự động điền hoặc viết lại những mục còn trống của thành viên khác trước khi merge sẽ vi phạm nghiêm trọng quy định "không viết hộ, không để AI viết thay" trong `RUBRIC.md`. | Đồng ý tuyệt đối | Khóa chặt Boundary: công cụ hoặc nhóm trưởng chỉ được phép chỉ ra ví trí bị lỗi để chính thành viên đó tự sửa trên branch cá nhân, tuyệt đối không tự ý sinh nội dung thay thế. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày 3 Problem Cards cá nhân, tập trung pitch Card #1 ("Rà soát báo cáo trước khi merge vào `main`") và Card #2 ("Đọc hiểu và tổng hợp quy tắc từ nhiều file hướng dẫn lab"). | Đóng góp vào nhóm bài toán về tối ưu quy trình kiểm tra tài liệu và đối chiếu quy tắc; giúp nhóm có thêm góc nhìn so sánh giữa bài toán học tập (tần suất theo buổi học) và bài toán đời sống thực tế. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Hỏi Quốc ở Card #1 ("Mất trộm xe máy trước cửa hàng/nhà dù có camera"): *"Trong bảng Card ban đầu bạn đang gộp cả chủ xe lẫn chủ cửa hàng vào chung một Actor, vậy thực tế ai mới là người sở hữu camera và đứng gần xe nhất để chạy ra ngăn kịp trong vài chục giây? Và nếu đặt target báo động 'dưới 1 phút' thì có quá chậm so với tốc độ bẻ khóa xe Wave không?"* (2) Hỏi Hiệp ở Card #1 ("Hiểu yêu cầu và thứ tự làm bài lab"): *"Bạn chưa có số phút bấm giờ thực tế cho từng bước, vậy nếu chỉ dùng bảng 'Thứ tự đọc' sẵn có trong README kèm một checklist giấy thì đã giải quyết xong mà không cần AI chưa?"* | Câu hỏi phản biện giúp Quốc và cả nhóm nhận ra phải tách bạch Actor chính là chủ/nhân viên cửa hàng (người giữ camera) khỏi người chịu thiệt, đồng thời thúc đẩy nhóm hạ target thời gian cảnh báo từ "dưới 1 phút" xuống ≤ 10 giây (đo bằng thử nghiệm giả lập). Với bài của Hiệp, cả hai chúng tôi đều thấy có chung pattern với Card #2 của tôi và giải quyết tốt bằng checklist (No AI). |
| Nhận phản biện | Câu hỏi tôi nhận được: Hiệp hỏi về Card #1 của tôi: *"Nếu các lỗi trừ điểm nặng như sai tên file, sai đuôi ảnh `.png`, thiếu dòng bảng hay thiếu 200 từ đều có sẵn trong `SUBMISSION.md` và kiểm tra được bằng mắt hoặc 1 script đếm chữ trong 2 phút, thì tại sao không yêu cầu từng thành viên tự tích vào checklist trước khi push mà lại nghĩ tới AI?"* | Tôi đã sửa gì: Tôi thừa nhận mình đã hơi nghiêng về giải pháp công nghệ sớm; nếu mỗi thành viên tự kiểm bằng checklist cố định trước khi push thì thời gian rà bài của nhóm trưởng đã giảm quá nửa mà không cần xây công cụ AI. Vì vậy, tôi đồng thuận rút bài của mình để cả nhóm tập trung vào bài toán "Mất trộm xe máy trước cửa hàng/nhà dù có camera" của Quốc. |
| Gom cluster / cây OST | Cùng Quốc và Hiệp gom 9 Problem Cards của 3 thành viên thành 3 cụm pattern (Cụm A: Kiểm tra & đối chiếu quy tắc bài lab; Cụm B: Cảnh báo sớm rủi ro an ninh/sức khỏe khi thiếu người giám sát trực tiếp; Cụm C: Tổng hợp thông tin & chi phí từ nhiều nguồn rời rạc) và dựng cây OST cho bài toán chống trộm xe máy. | Xác lập đúng 1 Outcome ở gốc (*"Giúp chủ cửa hàng/chủ nhà phát hiện và phản ứng kịp thời ngay lúc có người tác động trái phép vào xe máy đang đỗ trước cửa mà không bị làm phiền bởi cảnh báo giả"*) và gạch bỏ các giải pháp đội lốt khỏi tầng Opportunity (như *"Lắp camera AI nhận diện cử chỉ"*). |
| Chọn candidate problem | Thiết lập bảng chấm điểm 7 tiêu chí cho shortlist 3 bài toán đại diện của 3 thành viên (Cảnh báo mất trộm xe máy trước cửa hàng; Rà soát & đọc hiểu yêu cầu bài lab; Bệnh nhân lo lắng triệu chứng sau xuất viện). | Cả nhóm thống nhất chọn "Mất trộm xe máy trước cửa hàng/nhà dù có camera" vì có sự việc thật cụ thể (bạn của Quốc mất xe Wave 20 triệu ngày 25/6/2025 + 3 người quen từng mất xe), thiệt hại lớn, quy trình hiện tại rõ ràng và đặt ra bài toán phân định cực hay giữa No AI (khóa đĩa) / Rule (vùng cảnh báo) / Workflow. |
| Kiểm chứng / research | Xây dựng Assumption Map, tham gia hỏi nhanh chủ cửa hàng/người đang dùng camera an ninh theo đúng 3 luật của The Mom Test (hỏi về lần gần nhất camera báo nhầm và họ đã xử lý thế nào) và trực tiếp mở kiểm tra các link tài liệu về camera Imou, Ezviz (Thế Giới Di Động, FPT Shop, Song Phương). | Phát hiện 2 thực tế quan trọng làm nhóm đổi hướng: (1) Camera wifi giá rẻ hiện nay (Imou, Ezviz ~500k–1 triệu) đã có sẵn AI phát hiện con người (Human Detection), kẻ vùng cảnh báo và còi hú 110dB; (2) Nhưng nhiều chủ tiệm/chủ nhà phải tắt tính năng báo động ban ngày vì khách ra vào liên tục làm điện thoại kêu inh ỏi (tín hiệu phản bác đối với Rule đơn giản vào ban ngày). |
| Quy trình nhóm | Vẽ chi tiết sơ đồ quy trình Hiện tại (6 bước — chủ xe chỉ biết sau ~1 giờ khi mua đồ xong quay ra) và quy trình Tương lai (5 bước — phát hiện, gửi thông báo kèm ảnh/clip ngắn cho chủ quán xác nhận trước khi hú còi) kèm bảng so sánh Before/After. | Phân định rõ: ban đêm vắng người thì chỉ cần Rule trên camera sẵn có; còn ban ngày trước cửa hàng đông khách thì phải có Boundary không cho còi hú tự động bừa bãi mà chuyển qua bước Con người (nhân viên/chủ quán liếc màn hình hoặc điện thoại xác nhận trong vài giây), kèm phương án quay về khóa cơ/khóa đĩa có còi. |
| Problem Statement | Soạn thảo Problem Statement v0 ở CP5, dùng AI phản biện chỉ ra lỗ hổng và nâng cấp lên bản Problem Statement v1 cùng 4 tiêu chí đánh giá ở CP6. | Sửa 2 trường quan trọng từ v0 sang v1: (1) Tách rõ Actor chính là chủ/nhân viên cửa hàng có camera; (2) Đổi Success Metric từ "dưới 1 phút" thành ≤ 10 giây và giới hạn số lần báo nhầm < 3 lần/ngày. |
| Mức can thiệp AI | Đặt bài toán lên ma trận Độ mơ hồ × Độ phức tạp, lập bảng so sánh 4 mức No AI / Rule / Workflow / Agent, điền AI Canvas rút gọn và trả lời 2 câu hỏi Google PAIR. | Làm rõ vì sao không chọn Agent tự trị, vì sao Rule chỉ đủ cho ban đêm mà chưa đủ cho ban ngày đông khách, và xác định theo Google PAIR rằng người dùng muốn Augment chứ không muốn giao quyền hú còi hoàn toàn cho máy. |
| Quyết định | Đánh giá mức độ 4 rủi ro lớn (Value, Usability, Feasibility, Viability) theo khung Marty Cagan và thiết kế kế hoạch thử nghiệm thực tế kèm ngưỡng dừng định lượng. | Thống nhất quyết định "Not Yet đối với việc tự xây AI nhận diện hành vi mới / Go phạm vi nhỏ với công cụ có sẵn (Rule + quy trình bán thủ công)"|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sau khi tự viết 8 vấn đề từ trải nghiệm làm bài lab và học tập, tôi nhờ AI gợi ý thêm các vấn đề theo 4 lăng kính trong đời sống sinh viên. | Gợi ý nhanh ý tưởng về việc kiểm tra tin nhắn lừa đảo cho người thân ở quê (#9) và tổng hợp tiền phòng trọ cuối tháng (#10). | Đưa ra các câu mang tính giải pháp sẵn (*"Cần một trợ lý AI tự động chấm điểm bài tập"*, *"Ứng dụng AI quản lý chi tiêu"*) và tự điền những con số thời gian giả định không phải của tôi. | Tôi bỏ hoàn toàn các từ "AI", "trợ lý", "hệ thống" khỏi cột Job Story; viết lại toàn bộ 10 dòng bằng sự việc thật có ngày tháng và số phút thực tế của chính mình (như lỗi Git 403 tối 09/11/2026, 28 phút rà bài merge, 45 phút tính tiền phòng). |
| CP2 Problem Card | Đóng vai "PM hoài nghi" để phản biện 3 Problem Cards cá nhân của tôi (đặc biệt là Card #1 về rà soát file báo cáo trước khi merge). | Chỉ ra rất trúng rằng các lỗi sai tên file `MSSV_HoTen.md`, sai đuôi `.png` hay thiếu số từ đều có thể bắt chính xác bằng Checklist hoặc script đếm chữ (Rule) chứ chưa cần tới LLM. | Gợi ý làm một GitHub Action gọi LLM tự động sửa luôn nội dung file báo cáo của các thành viên nếu phát hiện thiếu chữ. | Tôi bác bỏ gợi ý để AI tự sửa bài vì vi phạm quy tắc trung thực của môn học; chỉnh lại Card #1 theo hướng ưu tiên Checklist + Rule và giữ cứng Boundary là chỉ báo vị trí thiếu để thành viên tự bổ sung. |
| CP4 Research | Tìm các dòng camera chống trộm phổ thông, tính năng AI phát hiện người và giải pháp khóa báo động hiện có trên thị trường cho bài toán nhóm ("Mất trộm xe máy trước cửa hàng"). | Gợi ý nhanh các dòng camera Imou/Ezviz có sẵn Human Detection, vùng cảnh báo (Activity Zone), còi hú 110dB và các bài viết kỹ thuật từ Thế Giới Di Động, FPT Shop, Song Phương. | Đưa một số link sản phẩm đã ngừng kinh doanh (lỗi 404); khẳng định tính năng "AI phát hiện người" của camera giá rẻ đã đủ sức chống trộm trước cửa hàng mà quên mất bối cảnh ban ngày khách ra vào liên tục sẽ gây báo nhầm. | Tự mở kiểm tra từng link sống (TGDĐ, FPT Shop, Song Phương); ghi rõ khoảng trống: camera có sẵn chỉ phát hiện "có người đi vào vùng" chứ chưa phân biệt được "khách dắt xe của mình" với "kẻ gian cúi bẻ khóa" vào ban ngày. |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe Quốc trình bày 3 bài toán từ trải nghiệm đời sống (vụ bạn thân mất chiếc xe Wave 20 triệu đồng trước cửa hàng quần áo ngày 25/6/2025, lần chính bạn ấy phải quay lại bệnh viện tốn 1.200.000đ và 4 giờ vì lo lắng triệu chứng sau xuất viện, và 2 ngày vất vả so giá khách sạn Đà Lạt) cùng 3 bài toán rất thật của Hiệp khi vật lộn với lỗi `python3`, lỗi giao diện Codex và đọc tài liệu repo bài lab, tôi nhận ra sự phong phú của các vấn đề quanh mình. Bản thân tôi ở CP1–CP2 chủ yếu quét các vấn đề xoay quanh quy trình làm việc nhóm trên GitHub, đồ án môn học và sinh hoạt phòng trọ. Khi đặt cạnh bài của Quốc, tôi học được cách nhìn vào những điểm nghẽn mà ở đó "công cụ đã có mặt tại hiện trường nhưng hoàn toàn vô dụng vào thời điểm quyết định" — giống như việc cửa hàng quần áo đã lắp sẵn camera nhưng chỉ dùng để xem lại sau khi chiếc xe 20 triệu đã bị lấy mất cách đó cả tiếng đồng hồ.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, nhóm tôi đã rơi vào bẫy "solution-first" ở cả giai đoạn cá nhân lẫn lúc mới hội tụ nhóm ở CP3. Ở phần cá nhân, tôi từng nghĩ ngay tới việc dùng AI kiểm tra file báo cáo trước khi merge, còn Quốc ban đầu định đề xuất "hệ thống AI đọc cử chỉ kẻ gian qua camera". Khi bước vào CP3 để vẽ cây Opportunity Solution Tree cho bài toán chống trộm xe máy, một số ý kiến trong nhóm lại tiếp tục ghi nhánh cơ hội là *"Tích hợp mô hình AI nhận diện hành vi bẻ khóa lên camera quán"*. Nhóm đã kịp thời phát hiện ra đây là giải pháp đội lốt cơ hội khi đối chiếu với quy tắc của Teresa Torres. Chúng tôi đã gạch bỏ ngay dòng đó khỏi tầng Opportunity và lùi lại hỏi nhau: tại sao có camera mà vẫn mất xe? Từ đó, nhóm viết lại thành các nỗi đau thật: chủ quán bận tiếp khách không thể nhìn màn hình liên tục, và cảnh báo chuyển động thông thường kêu nhầm quá nhiều vào ban ngày khiến người dùng tắt luôn thông báo.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý rất rõ ở hai thời điểm. Thứ nhất là đối với chính Card #1 cá nhân của tôi (rà soát file báo cáo trước khi merge vào `main`): sau khi Quốc, Hiệp và AI đóng vai PM hoài nghi phản biện rằng 80% các lỗi bị trừ điểm trong Rubric (sai tên file, sai đuôi ảnh `.png`, thiếu số dòng bảng, thiếu 200 từ) đều là quy tắc cứng có thể kiểm tra ngay bằng một bảng Checklist hoặc script đếm chữ đơn giản mà không cần gọi mô hình ngôn ngữ, tôi đã hoàn toàn đồng tình và rút ý định dùng AI cho bài đó. Thứ hai là ở bài nhóm về chống trộm xe máy: lúc đầu tôi nghĩ chỉ cần kẻ vùng cảnh báo (Activity Zone) trên camera và đặt Rule *"ai đứng trong vùng quá 10 giây thì hú còi"* là giải quyết xong. Nhưng khi Quốc phản biện bằng đúng bối cảnh vụ mất xe ngày 25/6/2025 là ban ngày trước cửa hàng quần áo đông khách, khách mua hàng đứng dắt xe hoặc chờ bạn trên vỉa hè cũng mất 15–30 giây, tôi mới nhận ra Rule đơn giản chỉ chạy tốt vào ban đêm, còn ban ngày sẽ gây báo động giả liên tục.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả kiểm chứng theo The Mom Test và research công cụ có sẵn ở CP4 làm tôi bất ngờ ở hai điểm lớn. Điểm bất ngờ đầu tiên đến từ phần research kỹ thuật: khi tự mở kiểm tra các trang thông số camera an ninh phổ thông tại Việt Nam (như dòng Imou, Ezviz giá chỉ vài trăm nghìn đồng trên Thế Giới Di Động và Song Phương), chúng tôi phát hiện các camera này đã tích hợp sẵn tính năng AI phát hiện dáng người (Human Detection), tùy chỉnh vùng báo động và còi hú 110dB chứ không hề thiếu công nghệ như nhóm tưởng. Điểm bất ngờ thứ hai đến từ việc hỏi người dùng thật: lý do họ vẫn bị mất trộm hoặc không biết lúc sự việc xảy ra không phải vì camera thiếu tính năng báo động, mà vì vào ban ngày camera báo nhầm mỗi khi có người đi bộ lướt qua vùng để xe nên chủ tiệm đã chủ động tắt luôn thông báo trên điện thoại. Phát hiện này làm nhóm thay đổi hẳn trọng tâm Problem Statement sang việc kiểm soát tỉ lệ báo nhầm (< 3 lần/ngày) và thiết kế luồng xác nhận nhanh.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất khi viết Problem Statement cho bài toán mất trộm xe máy là tách bạch đúng Actor và thiết kế một Success Metric có thể đo kiểm chứng được ngay mà không phải ngồi chờ một vụ trộm thật xảy ra. Ở bản v0, nhóm rất dễ mắc lỗi gộp chung "khách để xe và chủ cửa hàng" làm một Actor, trong khi khách đang thử quần áo bên trong thì không hề cầm điện thoại kết nối với camera của quán. Khi sửa sang bản v1, việc xác định lại Actor chính là chủ/nhân viên cửa hàng (người giữ thiết bị và ở gần cửa nhất) cùng việc chuyển đổi cách đo từ "giảm số vụ mất xe" sang "thời gian phát hiện ≤ 10 giây thông qua 10 lần thử nghiệm giả lập tác động vào ổ khóa xe (đạt ≥ 9/10 lần) và số cảnh báo nhầm < 3 lần/ngày" là bước chuyển tư duy khó nhưng đắt giá nhất của cả nhóm.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được làm lại từ đầu, tôi sẽ đề xuất nhóm thực hiện ngay bài test giả lập 10 lần trên một chiếc camera Imou/Ezviz thật tại cửa hàng hoặc trước nhà một thành viên trong nhóm để lấy con số baseline thực nghiệm về tỉ lệ báo nhầm ban ngày, thay vì chỉ dừng ở việc thu thập thông tin qua phỏng vấn. Ngoài ra, tôi sẽ phản biện nhóm mạnh hơn ở phương án No AI (vật lý): tại sao chủ cửa hàng không phát cho khách một chiếc khóa đĩa có còi báo động cảm biến rung (giá chỉ 150.000đ–200.000đ, chỉ kêu khi có lực tác động trực tiếp vào bánh xe chứ không bao giờ báo nhầm vì người đi bộ ngang qua)? Việc đặt giải pháp khóa cơ có còi lên bàn cân sòng phẳng với giải pháp camera sẽ giúp quyết định cuối cùng ở CP6 khách quan và chặt chẽ hơn nữa.

**6.7. Hiểu bài:**
Bài toán của nhóm bắt nguồn từ sự việc có thật (bạn của thành viên trong nhóm bị mất chiếc xe Wave trị giá khoảng 20 triệu đồng vào ban ngày 25/6/2025 trước một cửa hàng quần áo dù quán có lắp camera): khi xe máy để trước cửa hàng hoặc trước nhà không có bảo vệ trông coi, chủ quán và chủ xe muốn được báo ngay lúc có người tác động vào ổ khóa để kịp thời ngăn chặn, thay vì mua hàng xong quay ra mới biết mất xe (Problem). Quy trình hiện tại gồm 6 bước (khách khóa cổ để xe trước quán → vào mua đồ khoảng 1 giờ → kẻ trộm tiếp cận bẻ khóa trong khi camera chỉ ghi hình thụ động không ai nhìn → kẻ trộm chạy xe đi → khách quay ra mới phát hiện mất → nhờ quán trích xuất camera đi trình báo), trong đó bottleneck nằm ở bước thứ 3 khi camera chỉ ghi hình mà không có cơ chế cảnh báo tức thời khiến độ trễ phát hiện lên tới gần 1 giờ. Nhóm đặt Success Metric cụ thể: rút ngắn thời gian từ lúc có hành vi tác động vào ổ khóa đến lúc chủ/nhân viên quán nhận được cảnh báo từ ~1 giờ xuống ≤ 10 giây và giữ số lần báo nhầm dưới 3 lần/ngày qua log thông báo ứng dụng trong 1 tuần. Về Boundary, hệ thống chỉ được phép gửi thông báo kèm ảnh/clip ngắn cho chủ quán hoặc nháy đèn nhắc nhở, tuyệt đối không được tự động bật còi hú 110dB tối đa vào ban ngày khi chưa có xác nhận của con người, không tự động gửi hình ảnh người đi đường lên mạng hay cơ quan chức năng, và luôn có phương án quay về là dùng khóa đĩa có còi kết hợp màn hình quan sát trực tiếp tại quầy thu ngân. Khi xét các mức can thiệp, nhóm loại bỏ Agent tự trị vì rủi ro báo động giả cao và chọn kết hợp Rule + Workflow bán thủ công: ban đêm dùng Rule có sẵn trên camera, còn ban ngày dùng Workflow phát hiện người đứng sát đầu xe/cúi xuống ổ khóa để đẩy clip 3 giây lên màn hình/điện thoại cho nhân viên quầy thu ngân kiểm tra trước khi bấm còi hoặc bước ra nhắc. Cuối cùng, sau khi chấm 4 rủi ro, nhóm ra quyết định Go phạm vi nhỏ với công cụ có sẵn / Not Yet với việc tự xây mô hình AI mới, kèm ngưỡng dừng: nếu trong 1 tuần chạy thử mà số cảnh báo nhầm vượt quá 3 lần/ngày khiến nhân viên muốn tắt thông báo hoặc độ trễ thông báo quá 10 giây thì dừng và chuyển hẳn sang phương án No AI là trang bị khóa đĩa có còi báo động cho xe khách để trước quán.

---

## 7. Tài liệu tham khảo
- Thế Giới Di Động — Top camera chống trộm (camera AI chỉ cảnh báo khi phát hiện con người, có còi báo động): https://www.thegioididong.com/hoi-dap/top-camera-chong-trom-1563276
- Song Phương — Camera cửa hàng/shop (camera wifi Imou có phát hiện con người, tùy chỉnh khu vực báo động): https://songphuong.vn/cam-shop/
- Song Phương — Camera Imou (báo động chủ động bằng còi 110dB và đèn): https://songphuong.vn/product-tag/camera-imou-can-tho
- FPT Shop — Công nghệ nhận diện con người trên camera an ninh: https://fptshop.com.vn/tin-tuc/dien-may/cong-nghe-nhan-dien-con-nguoi-tren-camera-154105
