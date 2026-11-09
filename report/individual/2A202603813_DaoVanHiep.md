# Báo cáo cá nhân — 2A202603813_DaoVanHiep

## 1. Thông tin học viên

- **Họ tên:** Đào Văn Hiệp
- **MSSV:** 2A202603813
- **Email trường / liên hệ:** daohiep302@gmail.com
- **Tên nhóm:** NhomBB (Lớp K5 · L3B)
- **Link repo nhóm:** https://github.com/missher03/K5-L3B-DAY02-Nhomlo-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Các vấn đề dưới đây xuất phát từ trải nghiệm cá nhân khi thiết lập công cụ và thực hiện bài lab, được ghi lại theo những sự việc tôi đã cung cấp. Dấu hiệu gồm ngày xảy ra, thông báo lỗi và việc đã phải hỏi hướng dẫn; chưa có số đo thời gian xử lý nên không tự bổ sung số phút.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi chạy bài lab Python trên Windows nhưng hệ thống báo không tìm thấy Python, tôi muốn xác định nguyên nhân và cách chạy đúng môi trường, để tiếp tục thực hiện bài lab. | Bản thân tôi khi thực hành Python trên Windows | Ngày **06/11/2026**, tôi chạy lệnh `python3` trong terminal có hiển thị `(venv)` nhưng nhận thông báo **“Python was not found…”** và đã gửi nguyên văn lỗi để hỏi cách khắc phục. |
| 2 | Tốn thời gian | Khi cài tiện ích Codex trong VS Code nhưng giao diện không khởi động, tôi muốn xác định cách khắc phục phù hợp, để sử dụng công cụ hỗ trợ lập trình. | Bản thân tôi khi thiết lập công cụ học tập và lập trình | Ngày **07/11/2026**, tôi gặp lỗi **“The extension could not start its user interface”**. Sau khi được hướng dẫn, tôi tiếp tục báo **“vẫn lỗi”** và gửi ảnh màn hình. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu một bài lab có yêu cầu và hướng dẫn trên GitHub, tôi muốn hiểu thứ tự thực hiện và những nội dung cần hoàn thành, để làm bài đúng yêu cầu. | Bản thân tôi khi học các bài lab AI | Tôi đã yêu cầu hướng dẫn repo **Day01 ngày 06/11/2026** và repo **Discovery & Problem Framing Day02 ngày 09/11/2026**. Với Day02, tôi còn phải hỏi riêng cách làm phần cá nhân và yêu cầu của CP1. |
| 4 | Tốn thời gian | Khi cần đưa bài thực hành lên GitHub, tôi muốn hiểu các bước tạo repository và đẩy bài lên, để lưu trữ và chia sẻ bài làm đúng nơi. | Bản thân tôi khi sử dụng GitHub cho bài học | Ngày **06/11/2026**, tôi đã hỏi cách **tạo repository VinUni-Codelab-Day01 trên tài khoản của mình và push Codelab lên đó**. Đây là một thao tác tôi cần được hướng dẫn để thực hiện. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi bài thực hành yêu cầu gọi mô hình qua API, tôi muốn xác định nơi lấy API key và cách thiết lập, để có thể thực hiện phần gọi mô hình trong bài. | Bản thân tôi khi làm bài thực hành sử dụng API | Ngày **06/11/2026**, tôi hỏi cách lấy API miễn phí từ **OpenRouter**. Ngày **09/11/2026**, khi tìm hiểu Codelab Day02, tôi tiếp tục hỏi cách lấy **API key**. |

**Dùng AI trong CP1:** Tôi cung cấp 5 tình huống cùng ngày xảy ra và dấu hiệu cụ thể; Codex hỗ trợ trình bày thành bảng Job Story. Nội dung này thay thế danh sách tình huống và số liệu giả định trước đó.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3 đề xuất

| Rank | Problem từ CP1 | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #3 — Hiểu yêu cầu và thứ tự làm bài lab trên GitHub | Đã phải hỏi hướng dẫn ở 2 bài lab, sau đó hỏi riêng phần cá nhân và CP1 của Day02; có thể đối chiếu đầu ra với yêu cầu trong repo. | Mất bao lâu để đọc hiểu; bước khó nhất là tìm tài liệu, hiểu nội dung hay xác định phần cần nộp? |
| 2 | #1 — Không chạy được Python trên Windows | Có lệnh, thông báo lỗi và bối cảnh terminal cụ thể; đầu ra thành công có thể kiểm tra trực tiếp. | Nguyên nhân thực tế và cách khắc phục cuối cùng chưa được cung cấp; chưa biết thời gian xử lý. |
| 3 | #2 — Giao diện tiện ích Codex không khởi động | Có thông báo lỗi và phản hồi “vẫn lỗi” sau hướng dẫn, thể hiện vấn đề chưa được giải quyết ở thời điểm đó. | Chưa có log, phiên bản hay kết quả khắc phục cuối cùng để xác định nguyên nhân. |

Hai vấn đề còn lại vẫn được giữ ở CP1. #4 có phạm vi thao tác tương đối cụ thể, phù hợp kiểm tra bằng hướng dẫn từng bước; #5 cần làm rõ đang vướng ở việc tìm nơi cấp key hay cấu hình sử dụng. Đây là lý do ưu tiên phân tích, không phải kết luận hai vấn đề đó đã được giải quyết.

### Quy ước về bằng chứng và thời gian

CP1 xác nhận sự việc và ngày xảy ra, chưa xác nhận số phút hay toàn bộ thao tác. Các luồng dưới đây tái dựng sơ bộ từ mô tả, cần học viên kiểm tra. **Số phút là ước lượng minh họa để lập kế hoạch đo, không phải baseline thực tế.** Target là đề xuất thử nghiệm, chưa phải kết quả đạt được.

### Problem Card #1 — Hiểu yêu cầu và thứ tự làm bài lab trên GitHub

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một bài lab có yêu cầu và hướng dẫn trên GitHub, tôi muốn hiểu thứ tự thực hiện và những nội dung cần hoàn thành, để làm bài đúng yêu cầu. |
| Actor | Tôi — học viên đang thực hiện Codelab Day01 và Day02. |
| Bối cảnh / bằng chứng | Đã hỏi hướng dẫn Day01 ngày 06/11/2026 và Day02 ngày 09/11/2026; với Day02 còn hỏi riêng phần cá nhân và CP1. |
| Quy trình nháp | Mở repo → đọc yêu cầu → đối chiếu các tài liệu và xác định phần phải làm → hỏi lại chỗ chưa rõ → lập danh sách đầu việc. |
| Bottleneck giả định | Bước đối chiếu tài liệu để phân biệt yêu cầu cá nhân, yêu cầu nhóm và đầu ra từng checkpoint. Cần tự đo để xác nhận. |
| Impact | Chưa tự xác định được ngay phần cần làm; phải hỏi hướng dẫn tổng thể và hỏi lại phần cụ thể. Chưa có bằng chứng về điểm bị trừ hoặc trễ hạn. |
| Success metric đề xuất | Baseline: chưa đo; ghi thời gian từ lúc mở repo tới khi có danh sách đầu việc trong lần làm bài tiếp theo. Target thử: trong 15 phút lập được checklist bao phủ toàn bộ yêu cầu bắt buộc; kiểm từng mục với tài liệu gốc. Nếu baseline vốn dưới 15 phút, đặt lại target theo dữ liệu. |
| Phương án không dùng AI | Đọc theo thứ tự được repo hướng dẫn; ghi bảng checkpoint – việc cần làm – file đầu ra – điều kiện hoàn thành – nguồn yêu cầu. |
| Giả thuyết về AI | Nếu vẫn khó đối chiếu văn bản, thử AI hỗ trợ trích yêu cầu kèm đường dẫn mục nguồn trong một quy trình định sẵn; tôi tự kiểm lại. |
| Cảm nhận nhanh | Ưu tiên No AI bằng checklist; chỉ cân nhắc Workflow có AI sau khi kiểm tra cách đơn giản hơn. |
| Boundary | Không biến gợi ý thành yêu cầu bắt buộc; không tự viết reflection, bịa trải nghiệm hay hoạt động nhóm; tài liệu gốc là căn cứ đối chiếu. |

```text
HIỆN TẠI — luồng tái dựng; ước lượng minh họa 40 phút/lần
[Mở repo: 2 phút] → [Đọc yêu cầu: 8 phút]
→ [Đối chiếu tài liệu và đầu ra: 15 phút] ← NGHẼN GIẢ ĐỊNH
→ [Hỏi lại điểm chưa rõ: 10 phút] → [Lập đầu việc: 5 phút]
Thời gian chờ câu trả lời chưa được ghi nhận, không tính trong tổng minh họa.
```

### Problem Card #2 — Không chạy được Python trên Windows

| Trường | Nội dung |
|---|---|
| Job Story | Khi chạy bài lab Python trên Windows nhưng hệ thống báo không tìm thấy Python, tôi muốn xác định nguyên nhân và cách chạy đúng môi trường, để tiếp tục thực hiện bài lab. |
| Actor | Tôi — học viên thực hành Python trên Windows. |
| Bối cảnh / bằng chứng | Ngày 06/11/2026, chạy `python3` trong terminal hiển thị `(venv)` nhưng nhận “Python was not found…”; đã gửi nguyên văn lỗi để hỏi cách khắc phục. |
| Quy trình nháp | Mở terminal → chạy lệnh → đọc lỗi → kiểm tra lệnh và môi trường đang dùng → thử cách khắc phục rồi chạy lại. Chưa biết thực tế đã thử những bước kiểm tra nào. |
| Bottleneck giả định | Xác định đúng môi trường và lệnh thực thi trước khi chọn cách sửa; không kết luận nguyên nhân chỉ từ nhãn `(venv)`. |
| Impact | Không tiếp tục được bước chạy Python tại thời điểm báo lỗi; chưa có thời gian gián đoạn thực tế. |
| Success metric đề xuất | Baseline: chưa đo. Target thử: chẩn đoán và chạy được lệnh kiểm tra cùng bài lab trong 15 phút với trường hợp tương tự; ghi thời gian từng bước và đường dẫn interpreter được dùng. Không coi hết thông báo lỗi là đủ nếu bài lab vẫn chưa chạy. |
| Phương án không dùng AI | Checklist kiểm tra bám theo hướng dẫn môi trường của bài lab; ghi lại lệnh, kết quả và thay đổi đã thử. |
| Giả thuyết về AI | Chỉ hỗ trợ đọc log và đề xuất bước kiểm tra khi checklist chưa đủ; mỗi giả thuyết phải có kết quả kiểm tra trước khi thay đổi cấu hình. |
| Cảm nhận nhanh | Bắt đầu bằng No AI; có thể cân nhắc Rule cho kiểm tra lặp lại sau khi hiểu nguyên nhân. Chưa có căn cứ cần Agent. |
| Boundary | Không xóa môi trường, cài lại hàng loạt hay đổi cấu hình hệ thống chỉ từ phỏng đoán; người dùng xem và chọn từng thay đổi. |

```text
HIỆN TẠI — luồng tái dựng; ước lượng minh họa 30 phút/lần
[Mở terminal: 2 phút] → [Chạy lệnh và đọc lỗi: 3 phút]
→ [Xác định lệnh và môi trường: 15 phút] ← NGHẼN GIẢ ĐỊNH
→ [Thử khắc phục: 7 phút] → [Chạy lại và xác nhận: 3 phút]
```

### Problem Card #3 — Giao diện tiện ích Codex trong VS Code không khởi động

| Trường | Nội dung |
|---|---|
| Job Story | Khi cài tiện ích Codex trong VS Code nhưng giao diện không khởi động, tôi muốn xác định cách khắc phục phù hợp, để sử dụng công cụ hỗ trợ lập trình. |
| Actor | Tôi — người thiết lập công cụ học tập và lập trình. |
| Bối cảnh / bằng chứng | Ngày 07/11/2026 gặp “The extension could not start its user interface”; sau hướng dẫn vẫn báo “vẫn lỗi” và gửi ảnh màn hình. |
| Quy trình nháp | Mở tiện ích → đọc thông báo → hỏi hướng dẫn → thử hướng dẫn → báo vẫn lỗi và bổ sung ảnh. Đây là thứ tự sơ bộ từ thông tin đã cung cấp. |
| Bottleneck giả định | Chọn bước xử lý tiếp theo khi thông báo chung và hướng dẫn đầu tiên chưa giúp khắc phục; cần thêm dữ liệu chẩn đoán. |
| Impact | Chưa mở được giao diện tiện ích ở thời điểm phản hồi; phải tiếp tục trao đổi để tìm cách xử lý. Chưa xác nhận công cụ đã hoạt động trở lại. |
| Success metric đề xuất | Baseline: chưa đo. Target thử: trong 10 phút thu thập đủ phiên bản, lỗi và log liên quan để chọn bước kiểm tra có căn cứ; kết quả cuối được đánh giá riêng bằng việc giao diện mở và nhận một yêu cầu thử. Không đồng nhất thu thập log với sửa xong lỗi. |
| Phương án không dùng AI | Mẫu báo lỗi thống nhất: phiên bản công cụ, thông báo nguyên văn, thao tác tái hiện, cách đã thử, kết quả và log đã ẩn thông tin riêng tư. |
| Giả thuyết về AI | Hỗ trợ đọc dữ liệu lỗi đã thu thập; không lặp lại cùng cách sửa nếu không có thông tin mới. |
| Cảm nhận nhanh | Ưu tiên No AI bằng mẫu chẩn đoán; chưa đủ dữ liệu để quyết định cần AI. |
| Boundary | Không công khai token hoặc dữ liệu nhạy cảm trong ảnh/log; không tự suy ra nguyên nhân hay tuyên bố đã sửa xong. |

```text
HIỆN TẠI — luồng tái dựng; ước lượng minh họa 35 phút/lần
[Mở tiện ích, ghi lỗi: 3 phút] → [Mô tả và hỏi: 5 phút]
→ [Thử hướng dẫn: 10 phút]
→ [Xác định thông tin còn thiếu sau khi vẫn lỗi: 12 phút] ← NGHẼN GIẢ ĐỊNH
→ [Gửi bổ sung ảnh/log: 5 phút]
Kết quả khắc phục cuối cùng và thời gian chờ trả lời chưa được ghi nhận.
```

### Card dự kiến muốn pitch nhất

- **Card #1 — Hiểu yêu cầu và thứ tự làm bài lab trên GitHub.** Đây là đề xuất để chuẩn bị pitch, chưa phải lựa chọn đã được nhóm thông qua.
- **Lý do:** Có dấu hiệu ở 2 bài lab và có tài liệu nguồn để kiểm tra chất lượng checklist; có thể thử thay đổi cách đọc và ghi đầu việc trước khi chọn công nghệ.
- **Câu hỏi chuẩn bị:** “Tôi bị nghẽn ở việc tìm yêu cầu, hiểu yêu cầu hay chuyển yêu cầu thành đầu việc? Nếu một checklist đã đủ, có cần AI không?”

### Phản biện của AI cho bản nháp CP2

| Điểm yếu AI chỉ ra trong lần viết này | Điều chỉnh trong bản nháp / việc còn cần làm |
|---|---|
| Ngày và thông báo lỗi chưa cho biết baseline thời gian. | Không ghi số phút như dữ liệu đã đo; tách rõ ước lượng minh họa và kế hoạch đo. |
| Gặp lỗi không chứng minh đã biết nguyên nhân. | Giữ nguyên nhân ở trạng thái chưa xác nhận; thêm bước kiểm tra kết quả. |
| Các bước tái dựng chưa chắc đúng với những gì học viên đã làm. | Ghi rõ luồng nháp, cần học viên kiểm tra từng bước và bottleneck. |
| Có thể nhảy từ khó khăn sang chatbot hoặc Agent quá sớm. | Đưa checklist và mẫu báo lỗi làm phương án đầu tiên; chỉ cân nhắc AI khi có bằng chứng phương án đơn giản chưa đủ. |
| Sửa nhanh nhưng bài lab vẫn không chạy thì chưa đạt. | Bổ sung điều kiện đầu ra kiểm chứng được, không chỉ đo thời gian. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Card #1: "Hiểu yêu cầu và thứ tự làm bài lab trên GitHub" (xuất phát từ việc ngày 06/11 và 09/11 phải hỏi lại hướng dẫn tổng thể và CP1). | Đóng góp vào nhóm candidate về đọc hiểu và đối chiếu tài liệu hướng dẫn trong bảng pitch chung. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Hỏi Quốc ở Card mất trộm xe máy: *"Trước cửa hàng quần áo ban ngày có rất nhiều người qua lại, nếu chỉ dùng vùng cảnh báo + thời gian đứng trên camera sẵn có thì làm sao tránh báo nhầm liên tục khiến chủ quán tắt luôn thông báo?"* (2) Hỏi Châu ở Card báo cáo tuần: *"Con số 90 phút đã tách riêng thời gian lấy số liệu ở Jira/Sheets và thời gian ngồi viết nhận định (narrative) chưa?"* | Giúp Quốc làm rõ điểm nghẽn báo nhầm ban ngày và tách rõ actor chủ quán với khách mua hàng; giúp Châu làm rõ bottleneck thực sự nằm ở 25 phút viết narrative chứ không phải bước lấy số. |
| Nhận phản biện | Câu hỏi tôi nhận được: Quốc và Châu hỏi: *"Việc bạn chưa rõ thứ tự làm bài lab là do tài liệu trong repo thiếu, hay do bạn chưa đọc theo bảng 'Thứ tự đọc' đã có sẵn trong README? Nếu chỉ lập một checklist đọc tuần tự có giải quyết xong không, và bạn đã bấm giờ thực tế chưa?"* | Tôi đã sửa gì: Tôi thừa nhận mình chưa có số đo phút thực tế (chỉ mới ghi nhận sự việc phải hỏi lại ngày 06/11 và 09/11) và nhận ra chỉ cần đọc đúng bảng thứ tự trong README kèm lập checklist thủ công (No AI) là giải quyết được phần lớn, nên đồng thuận rút bài của mình để ưu tiên bài có baseline đo đếm rõ hơn. |
| Gom cluster / cây OST | Cùng nhóm gom 9 cards của 3 thành viên thành các cụm vấn đề (Tổng hợp & viết báo cáo; Đọc hiểu & đối chiếu tài liệu/lời dặn; Giám sát & cảnh báo sự cố) và rà soát gạch bỏ các nhánh mang tên công cụ khỏi cây OST. | Giữ cho tầng Opportunity của cây OST chỉ chứa nỗi đau/nhu cầu của người dùng, không bị lẫn tên giải pháp như "chatbot hướng dẫn lab" hay "dashboard tự động". |
| Chọn candidate problem | Chấm điểm 7 tiêu chí cho shortlist 3 bài (Báo cáo tuần của PM, Cảnh báo mất xe máy trước cửa hàng, Hiểu yêu cầu bài lab) và thảo luận chốt bài. | Nhóm thống nhất chọn bài "Báo cáo tuần của PM" vì có baseline bấm giờ thực tế (85 và 95 phút), quy trình 7 bước rõ ràng và dễ kiểm chứng trong phạm vi buổi lab. |
| Kiểm chứng / research | Tham gia đối chiếu các giả định trong Assumption Map (đặc biệt là giả định người đọc có thực sự đọc phần narrative hay chỉ xem bảng số) và kiểm tra lại đường dẫn tài liệu Slack AI, Atlassian Rovo. | Phát hiện một số tính năng tóm tắt nâng cao của Slack AI bị giới hạn theo gói cước để nhóm điều chỉnh lại quy trình tương lai sát thực tế hơn. |
| Quy trình nhóm | Rà soát việc tách biệt từng bước trong sơ đồ quy trình trước/sau, đảm bảo không gộp chung bước "viết narrative" với bước "PM review và sửa". | Giữ đúng vị trí bottleneck ở bước viết narrative (25 phút) và làm rõ bước con người kiểm tra trước khi gửi. |
| Problem Statement | Đối chiếu 6 trường của Problem Statement v0 và v1 với tiêu chí trong Rubric, kiểm tra phần baseline, target và cách đo. | Bổ sung tiêu chí đo chất lượng (tỉ lệ phải viết lại bản nháp dưới 50% và số câu hỏi lại từ CEO/EM không tăng) vào bản v1 thay vì chỉ đo thời gian. |
| Mức can thiệp AI | Thảo luận phân biệt giữa No AI (template + checklist), Rule (script lấy số liệu) và Workflow (AI soạn nháp phần chữ trong luồng cố định). | Nhóm chốt chọn mức Workflow kết hợp Rule lấy số liệu, đồng thời giữ khuyến nghị No AI cho các team mà lãnh đạo chỉ xem bảng số. |
| Quyết định | Cùng nhóm rà soát 4 rủi ro (Value, Usability, Feasibility, Viability) và đặt ngưỡng dừng cụ thể cho kế hoạch chạy thử 2 tuần. | Thống nhất quyết định "Go, phạm vi nhỏ" kèm ngưỡng dừng định lượng: nếu 2 tuần liên tiếp phải viết lại trên 70% bản nháp hoặc sai số liệu lọt qua bước duyệt thì quay về template cũ. |

---

## 5. Dùng AI

| Phần | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc còn thiếu ở đâu? | Điều chỉnh / việc cần tự kiểm |
|---|---|---|---|---|
| CP1 | Nhờ gợi ý tình huống, sau đó cung cấp 5 trải nghiệm cụ thể để thay thế. | Trình bày dữ liệu cá nhân thành bảng Job Story. | Bản gợi ý trước đó chưa phản ánh trải nghiệm đã xác nhận; số liệu minh họa không thể làm bằng chứng. | Tôi cung cấp sự việc, ngày và thông báo lỗi; bản mới bỏ danh sách giả định. |
| CP2 | Nhờ Codex phát triển 3 card nháp từ CP1 và phản biện điểm yếu. | Tách actor, quy trình, bottleneck, metric và boundary; so sánh với cách không dùng AI. | Chưa biết toàn bộ thao tác thực tế, nguyên nhân lỗi hoặc số phút xử lý. | Bản nháp ghi rõ giả định; tôi cần kiểm lại quy trình và đo baseline trước khi dùng làm kết luận. |
| CP4 Research | | | | |
| CP5 Quy trình | Chuyển đổi mô tả quy trình sang Mermaid | Vẽ sơ đồ nhanh chóng | Gộp nhầm bước "viết narrative" và "review" thành một | Tách lại vì bottleneck nằm ở viết narrative |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe Quốc và Châu trình bày 3 Problem Cards của mỗi bạn, tôi nhận ra sự khác biệt rất lớn giữa một vấn đề chỉ mới có "sự việc xảy ra" và một vấn đề đã có "bằng chứng định lượng và quy trình cụ thể". Ở bài của tôi, dù các sự việc như lỗi lệnh `python3` ngày 06/11, lỗi giao diện Codex ngày 07/11 hay việc phải hỏi lại hướng dẫn lab là hoàn toàn có thật, tôi lại chưa từng bấm giờ xem mình mất chính xác bao nhiêu phút ở từng bước và chưa ghi lại đầy đủ các thao tác đã thử. Ngược lại, bài báo cáo tuần của Châu có số phút bấm giờ thực tế ở từng chặng (85 và 95 phút), còn bài mất xe máy và xuất viện của Quốc có mốc thiệt hại cụ thể (20 triệu đồng, 1.200.000đ và 4 giờ chờ đợi). Điều này giúp tôi hiểu vì sao việc ghi nhận baseline ngay khi gặp vấn đề lại quan trọng đến vậy.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có. Ngay từ lúc bắt đầu thảo luận gom nhóm và vẽ cây OST, cả nhóm nhiều lần vô thức nhắc đến giải pháp trước như "làm con bot tóm tắt repo bài lab", "dùng AI nhận diện dáng người bẻ khóa xe" hay "xây agent tự động gom Jira gửi báo cáo". Nhóm nhận ra lỗi này khi đối chiếu với quy tắc tầng Opportunity chỉ được phép chứa nỗi đau (pain) chứ không được chứa tên công cụ. Chúng tôi đã xử lý bằng cách gạch bỏ thẳng các cụm từ chứa công cụ khỏi cây OST và đặt lại câu hỏi: "Nếu cấm dùng từ AI hay công cụ, người trong cuộc đang khổ nhất ở đúng thao tác nào?".

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý hoàn toàn đối với chính Card #1 của mình ("Hiểu yêu cầu và thứ tự làm bài lab trên GitHub"). Ban đầu tôi định đề xuất dùng một luồng AI tự động trích xuất yêu cầu từ các file trong repo để tạo danh sách việc cần làm. Tuy nhiên, khi các bạn trong nhóm phản biện rằng bản thân file `README.md` đã có sẵn mục "Thứ tự đọc" rất rõ và hỏi tôi đã thử làm một bảng checklist thủ công chưa, tôi nhận ra nguyên nhân chính là do mình đọc nhảy cóc chứ không phải do tài liệu quá phức tạp đến mức bắt buộc phải dùng AI. Sau phản biện đó, tôi chuyển phương án ưu tiên của card này về No AI (đọc theo thứ tự + lập bảng checklist) và đồng ý chọn bài báo cáo tuần của PM làm bài chung của nhóm.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Điều làm tôi bất ngờ nhất ở bước kiểm chứng và research là thực tế có những nhóm làm việc mà lãnh đạo hầu như chỉ nhìn vào bảng số liệu chứ không đọc kỹ phần nhận định bằng chữ, đồng thời các công cụ có sẵn như Atlassian Rovo hay mẫu luồng n8n đã giải quyết được phần lớn các bước trong quy trình. Trước khi tìm hiểu, tôi cứ nghĩ giải quyết bài toán cho PM là phải tự thiết kế một công cụ mới hoàn toàn. Kết quả research cho thấy nếu để AI tính toán số liệu thì rất dễ sai sót, nên hướng thực tế nhất là dùng Rule để lấy số chính xác, chỉ dùng công cụ AI có sẵn để soạn nháp phần chữ và giữ nguyên bước con người kiểm duyệt.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là giữ cho Problem Statement mô tả đúng độ sắc nét của vấn đề và cách đo lường (Success Metric) nhưng tuyệt đối không được cài cắm giải pháp vào bên trong, đồng thời không được tự bịa ra các con số baseline khi chưa đo thật. Khi chuyển từ bản v0 sang v1, việc xác định ranh giới (Boundary) và tiêu chí đánh giá sao cho vừa ngăn được rủi ro AI bịa thông tin, vừa không biến người kiểm duyệt thành một điểm nghẽn mới tốn thời gian ngang với tự viết từ đầu đòi hỏi nhóm phải cân nhắc rất kỹ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại từ đầu, ngay từ khi gặp các lỗi cài đặt môi trường hay đọc tài liệu bài lab, tôi sẽ bấm giờ từng bước và lưu lại đầy đủ log thao tác để có dữ liệu baseline thật thay vì phải dùng số phút ước lượng minh họa. Đối với bài nhóm, tôi sẽ phản biện mạnh hơn ở giả định "CEO và EM thực sự đọc kỹ phần narrative mỗi tuần": nhóm cần yêu cầu người viết báo cáo kiểm chứng trực tiếp với sếp của họ trước khi đầu tư thời gian chuẩn hóa prompt, bởi nếu người nhận chỉ xem số trên dashboard thì giải pháp Rule + Template đã là quá đủ.

**6.7. Hiểu bài:**
Bài toán của nhóm xuất phát từ việc Junior PM mất trung bình 90 phút mỗi sáng thứ Hai để làm báo cáo tuần cho EM và CEO, dẫn đến việc gửi trễ trong 3/8 tuần gần nhất. Quy trình hiện tại gồm 7 bước thủ công (export Jira, lấy số từ Google Sheets, đọc lại các kênh Slack, gom vào Google Docs, viết phần nhận định narrative, tự kiểm tra định dạng rồi gửi email), trong đó bước nghẽn lớn nhất là mất 25 phút ngồi viết phần nhận định từ dữ liệu thô. Để giải quyết, nhóm đặt Success Metric là giảm tổng thời gian từ 90 phút xuống dưới 30 phút, đồng thời tỉ lệ PM phải viết lại bản nháp dưới 50% và số câu hỏi làm rõ từ CEO/EM không tăng so với 4 tuần trước đó. Ranh giới (Boundary) được thiết lập nghiêm ngặt: AI tuyệt đối không được tự ý gửi báo cáo, không được tự sửa đổi hay tính toán số liệu, và không được suy diễn thêm thông tin nằm ngoài dữ liệu đầu vào. Dựa trên tính chất quy trình có các bước cố định nhưng đầu ra ngôn ngữ có độ mở, nhóm chọn mức can thiệp là Workflow (kết hợp Rule/script ở bước lấy số liệu chuẩn xác, dùng AI soạn bản nháp phần nhận định và bắt buộc có con người là PM kiểm tra trước khi gửi). Cuối cùng, sau khi đánh giá 4 rủi ro đều ở mức Thấp và Trung bình, nhóm đưa ra quyết định "Go, phạm vi nhỏ" với kế hoạch chạy thử 2 tuần bằng công cụ sẵn có và đặt ngưỡng dừng rõ ràng: nếu sau 2 tuần PM vẫn phải viết lại trên 70% bản nháp hoặc phát sinh lỗi sai số liệu thì sẽ dừng để quay về phương án dùng template và dashboard cố định.

---

## 7. Tài liệu đối chiếu

- [Worksheet — yêu cầu CP1, CP2 và CP7](../../docs/01-worksheet.md).
- [Rules — quy định dùng AI và dữ liệu thực tế](../../RULES.md).
- [Rubric — tiêu chí chấm phần cá nhân](../../RUBRIC.md).
