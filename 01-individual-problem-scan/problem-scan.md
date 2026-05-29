# Phase 1 — Individual Scan: tìm 5+ problems (25')

## Bảng scan

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI tốt hơn | Đọc các bài báo nghiên cứu (arXiv, conference papers) dài 10-15 trang để tìm cấu trúc mô hình, tập dữ liệu, phương pháp luận. | Bản thân sinh viên, thành viên nhóm đồ án | Mất 2-3 tiếng/bài báo, đọc 5-10 bài/tuần để viết tổng quan tài liệu. Dễ bị sa đà vào các phần chứng minh toán học rườm rà. |
| 2 | Lặp lại / Pain từ người khác | Chuẩn bị báo cáo tiến độ hàng tuần chạy thử nghiệm mô hình (training logs, accuracy, loss) và kế hoạch tuần tới cho thầy hướng dẫn và nhóm. | Thành viên nhóm đồ án, Thầy hướng dẫn | Tốn 45-60 phút tối Chủ Nhật để lục lại các log training, tổng hợp kết quả và gõ báo cáo. Báo cáo đôi khi sơ sài làm thầy khó theo sát. |
| 3 | Lặp lại / Tốn thời gian | Sắp xếp lịch làm việc hàng ngày kết hợp giữa task Jira (tại Vin), task code đồ án tốt nghiệp (Github) và lịch đi tập gym cá nhân. | Bản thân sinh viên | Tốn 15-20 phút mỗi sáng để lên to-do list. Hay bị lố giờ code làm trễ lịch tập gym, hoặc bị burnout cuối ngày do phân bổ tải không đều. |
| 4 | Lặp lại / AI tốt hơn | Ghi chép và quản lý nhật ký chạy thử nghiệm mô hình Deep Learning (training logs) với các bộ hyperparameter khác nhau. | Sinh viên nghiên cứu CS | Chạy 10-20 thí nghiệm/tuần. Ghi log bằng Excel thủ công dễ nhầm lẫn, dẫn đến quên mất mô hình tốt nhất chạy bằng config nào. |
| 5 | Tốn thời gian / Pain từ người khác | Tìm lại các quyết định kỹ thuật hoặc giải pháp sửa lỗi code (bug) đã thảo luận trong lịch sử chat Discord/Slack của nhóm đồ án. | Cả nhóm đồ án | Mất 15-20 phút gõ tìm kiếm nhưng ra nhiều tin nhắn rác hoặc không đúng bối cảnh, phải hỏi đi hỏi lại. |
| 6 | Tốn thời gian | Viết phần mô tả thuật toán và phương pháp luận (Methodology) cho báo cáo đồ án tốt nghiệp bằng tiếng Anh/Việt chuẩn học thuật. | Sinh viên viết đồ án | Mất 3-4 tiếng cho mỗi tiểu mục. Thường bị bí từ (blank page) hoặc diễn đạt không rõ ràng logic toán học. |
| 7 | Lặp lại / Tốn thời gian | Viết script Python tiền xử lý dữ liệu (parsing, cleaning, format conversion) mỗi khi đổi tập dữ liệu thử nghiệm hoặc đổi mô hình. | Sinh viên làm đồ án | Tốn 1-2 tiếng viết lại code xử lý thủ công cho mỗi tập dữ liệu mới, dễ gặp lỗi mismatch dimensions. |
| 8 | Pain từ người khác | Theo dõi và nhắc nhở các deadline bài tập trên lớp chồng chéo với công việc ở Vin và tiến độ đồ án tốt nghiệp. | Bản thân sinh viên | Sát giờ mới nhớ ra deadline phụ của các môn học chung, gây áp lực thời gian lớn hoặc bị sót bài nộp. |
| 9 | Lặp lại / AI tốt hơn | Viết docstring và comment giải thích chi tiết cho các hàm thuật toán phức tạp trong code đồ án để bạn cùng nhóm kế thừa. | Thành viên nhóm đồ án | Lười viết dẫn đến sau 1-2 tuần đọc lại code của chính mình không hiểu, hoặc bạn cùng nhóm phải nhắn tin hỏi cách dùng. |
| 10 | Lặp lại | Lọc và phân loại các bài báo nghiên cứu mới xuất hiện hàng ngày trên arXiv để tìm bài thực sự liên quan đến chủ đề đồ án. | Sinh viên nghiên cứu CS | Phải lướt arXiv/đọc email hàng ngày, đọc lướt abstract của 20+ bài nhưng chỉ chọn được 1 bài hữu ích, tốn 30 phút/ngày. |

---

# Phase 2 — Top 3 Problem Cards + draft workflow (35')

## Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | **Tổng hợp báo cáo tiến độ đồ án tốt nghiệp** | Quy trình lặp lại hàng tuần rõ ràng. Bottleneck nằm ở việc gom thông tin từ các training logs và commits Git để viết narrative. Impact lớn cho nhóm. | Làm sao tự động gom dữ liệu từ nhiều server chạy AI khác nhau một cách thống nhất. |
| 2 | **Đọc bài báo nghiên cứu để tìm phương pháp luận** | Pain cực lớn đối với SV năm cuối làm nghiên cứu. Quy trình đọc báo có cấu trúc. Tiết kiệm thời gian rõ rệt. | AI có thể đọc hiểu sai hình vẽ hoặc các công thức toán phức tạp trong file PDF gốc. |
| 3 | **Lên kế hoạch ngày tối ưu lịch tập gym và học tập** | Thể hiện trải nghiệm cá nhân thực tế, có tính lặp lại hàng ngày. Có sự kết hợp giữa công việc tại Vin, đồ án và sinh hoạt cá nhân. | Khó định lượng được độ "thành công" của một ngày lên lịch ngoài việc hoàn thành task và đi tập đúng giờ. |

### Phân tích Top 3 ứng viên theo 4 trường thông tin (Yêu cầu riêng để pitch):

| Rank | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|
| **1** | **Tổng hợp báo cáo tiến độ đồ án tốt nghiệp** | Sinh viên làm đồ án, Giảng viên hướng dẫn | Tổng hợp số liệu từ logs/commits và viết giải thích (narrative) tại sao mô hình tốt/tệ. | Rất tiềm năng cho mức **Workflow**. Quy trình và nguồn dữ liệu rõ ràng, giải quyết pain lặp lại mỗi tối Chủ Nhật. |
| **2** | **Đọc bài báo nghiên cứu để tìm phương pháp luận** | Sinh viên ngành CS làm đồ án nghiên cứu | Đọc hiểu và phân tích phần Methodology có nhiều công thức toán học và cấu trúc mô hình phức tạp. | Phù hợp mức **Workflow**, giúp đọc nhanh. Nhưng rủi ro AI hiểu sai công thức toán và hình ảnh sơ đồ mạng. |
| **3** | **Lên kế hoạch ngày tối ưu lịch tập gym và học tập** | Bản thân sinh viên | Ước lượng thời gian chạy code và dự phòng (buffer time) dẫn đến việc vỡ lịch đi tập gym. | Có thể chỉ cần mức **Rule** hoặc **Workflow** đơn giản. Tính cá nhân hóa cao nhưng tác động nhóm thấp. |

---

## Problem Card 1

```text
Problem 1 câu:
Mỗi tối Chủ Nhật, thành viên nhóm đồ án tốt nghiệp mất 45-60 phút để tổng hợp thủ công kết quả chạy mô hình AI và lịch sử code trong tuần nhằm viết báo cáo tiến độ gửi thầy hướng dẫn.

Actor:
Sinh viên làm đồ án tốt nghiệp.

Thời điểm / bối cảnh:
Tối Chủ Nhật hàng tuần trước buổi họp tiến độ đầu tuần.

Current workflow 3-7 bước:
1. Lục lại các log chạy mô hình trên Weights & Biases hoặc terminal server (15 phút).
2. Đọc lại lịch sử Git commits trong tuần để xem đã thay đổi cấu trúc code nào (10 phút).
3. Đọc lại danh sách task của tuần trước trên Trello/Notion để đối chiếu (10 phút).
4. Phân tích các số liệu (Loss, Accuracy, Epochs) và viết giải thích (narrative) về lý do mô hình chạy tốt/tệ (15 phút).
5. Định dạng báo cáo theo mẫu Markdown/Slide của nhóm (5 phút).
6. Gửi báo cáo vào kênh Discord nhóm và gửi email cho thầy hướng dẫn (5 phút).

Bottleneck:
Bước 4 — Tổng hợp số liệu và viết giải thích (narrative) vì phải phân tích nguyên nhân mô hình hội tụ chậm hoặc bị overfitting (mất 15-20 phút và dễ bị blank page).

Impact:
Tốn 60 phút/tuần/sinh viên. Nhóm 3 người tốn 180 phút/tuần. Nếu báo cáo viết sơ sài, thầy hướng dẫn không nắm rõ vấn đề để định hướng tiếp, dẫn đến buổi họp tiến độ kéo dài lê thê.

Success metric:
Giảm thời gian chuẩn bị báo cáo từ 60 phút xuống dưới 20 phút. Thầy hướng dẫn đọc hiểu ngay tình trạng mô hình mà không cần hỏi lại các thông số cơ bản.

Non-AI alternative:
Dùng template sẵn và tích hợp tự động các API của Git/W&B vào một dashboard chung. Tuy nhiên, dashboard chỉ hiển thị số liệu thô (raw charts), không tự viết được phần giải thích lý do tăng/giảm hiệu năng mô hình (narrative).

AI hypothesis:
AI đọc file log tóm tắt (chỉ số chạy tốt nhất) và Git commits, kết hợp to-do list tuần trước để tự động phác thảo (draft) báo cáo tiến độ (bao gồm những gì đã làm, kết quả đạt được, và rủi ro/khó khăn gặp phải). Sinh viên review và chỉnh sửa trước khi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

---

## Problem Card 2

```text
Problem 1 câu:
Sinh viên mất 2-3 tiếng để đọc toàn bộ một bài báo khoa học PDF dài 10-15 trang trên arXiv chỉ để lọc ra kiến trúc mô hình (architecture) và các hyperparameters cần thiết cho đồ án tốt nghiệp.

Actor:
Sinh viên ngành CS làm đồ án nghiên cứu.

Thời điểm / bối cảnh:
Khi cần tìm thuật toán mới hoặc viết phần tổng quan nghiên cứu (Literature Review) cho đồ án tốt nghiệp.

Current workflow 3-7 bước:
1. Tải file PDF bài báo từ arXiv (5 phút).
2. Đọc Abstract và Introduction để xác định bài báo có thực sự liên quan không (15 phút).
3. Đọc lướt qua phần Methodology/Architecture để tìm sơ đồ khối và công thức cốt lõi (45 phút).
4. Đọc phần Experiments và Results để xem tập dữ liệu sử dụng và độ chính xác (30 phút).
5. Ghi chú lại các ý chính (mô hình, hyperparameters, dataset, kết quả) vào file Excel so sánh (25 phút).

Bottleneck:
Bước 3 & Bước 4 — Đọc hiểu chi tiết lý thuyết toán và cấu trúc mạng phức tạp (mất 60-75 phút, dễ nản và tốn năng lượng).

Impact:
Tốn 2-3 tiếng cho một bài báo. Mỗi tuần đọc 5 bài tốn 10-15 tiếng. Trì hoãn việc đọc báo vì tài liệu quá học thuật và dài.

Success metric:
Giảm thời gian lọc thông tin cốt lõi của một bài báo từ 120 phút xuống dưới 30 phút mà vẫn nắm vững kiến trúc và thông số thí nghiệm của bài báo đó.

Non-AI alternative:
Đọc các bài viết tóm tắt (blog posts/medium) của người khác viết về bài báo đó. Tuy nhiên, các bài báo ngách hoặc mới xuất bản sẽ không có bài tóm tắt sẵn.

AI hypothesis:
AI đọc file PDF bài báo, tự động trích xuất các thông tin cốt lõi (Kiến trúc mô hình, Dataset sử dụng, Hyperparameters, Kết quả Baseline) và điền vào bảng so sánh cho sinh viên. Sinh viên chỉ cần đọc lại bảng tóm tắt và mở PDF gốc để đối chiếu khi cần kiểm chứng sâu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

---

## Problem Card 3

```text
Problem 1 câu:
Sinh viên mất 20 phút mỗi sáng để sắp xếp các task công việc ở Vin, task đồ án tốt nghiệp và lịch tập gym cá nhân thành một thời biểu khả thi, dễ dẫn đến việc lỡ lịch tập gym khi code bị trễ tiến độ.

Actor:
Sinh viên năm cuối năng động.

Thời điểm / bối cảnh:
Đầu giờ sáng mỗi ngày.

Current workflow 3-7 bước:
1. Mở Jira của Vin để xem các task được giao trong ngày (5 phút).
2. Mở Github/Trello đồ án tốt nghiệp xem các task code cần chạy (5 phút).
3. Xem lịch học trên trường và xác định khung giờ trống để đi tập gym (5 phút).
4. Viết thời gian biểu chi tiết ra sổ hoặc Google Calendar (10 phút).
5. Cố gắng bám sát lịch trình nhưng thường bị trễ task code dẫn đến bỏ tập gym (Phát sinh trong ngày).

Bottleneck:
Bước 4 — Ước lượng thời gian cho mỗi task code (thường ước lượng sai dẫn đến lấn chiếm thời gian đi tập gym và nghỉ ngơi).

Impact:
Tốn thời gian lên lịch hàng ngày. Nếu bỏ tập gym thường xuyên sẽ ảnh hưởng đến sức khỏe thể chất và tinh thần; nếu đi tập đúng lịch thì lo lắng vì task code chưa xong.

Success metric:
Lên lịch ngày mất dưới 5 phút. Tỷ lệ đi tập gym đúng giờ tăng lên trên 90% mà không bị trễ task công việc/đồ án.

Non-AI alternative:
Sử dụng các khung thời gian cố định (Time-blocking) cố định hàng ngày (ví dụ luôn đi tập lúc 18h-20h). Tuy nhiên, lịch học và deadline công việc ở Vin thường thay đổi động theo tuần nên lịch cố định dễ bị vỡ.

AI hypothesis:
AI dựa vào to-do list thô và lịch học cố định, tự động tối ưu hóa và phân bổ các block thời gian (time-blocking) phù hợp, đưa ra các cảnh báo "Buffer Time" (thời gian dự phòng) cho các task code phức tạp để đảm bảo sinh viên vẫn kịp đi tập gym.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

---

## Draft workflow cho mỗi top problem

### Top Problem 1: Báo cáo tiến độ đồ án tốt nghiệp
```text
CURRENT STATE — 60 phút

┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ 1 Gom logs   │───>│ 2 Xem Git    │───>│ 3 Đối chiếu  │
│ W&B          │    │ commits      │    │ tasks Notion │
│ ⏱ 15'        │    │ ⏱ 10'        │    │ ⏱ 10'        │
└──────────────┘    └──────────────┘    └──────────────┘
                                                │
                                                ▼
┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ 4 Viết       │───>│ 5 Format     │───>│ 6 Gửi        │
│ narrative    │🔴  │ Markdown     │    │ báo cáo      │
│ ⏱ 15'        │    │ ⏱ 5'         │    │ ⏱ 5'         │
└──────────────┘    └──────────────┘    └──────────────┘

🔴 = Bottleneck

FUTURE STATE — 18 phút

┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ 1 Script gom │───>│ 2 AI viết    │───>│ 3 SV review  │
│ data         │    │ draft        │    │ & sửa chữa   │🟢
│ ⏱ 2'         │    │ ⏱ 3'         │    │ ⏱ 10'        │
└──────────────┘    └──────────────┘    └──────────────┘
                                                │
                                                ▼
                                        ┌──────────────┐
                                        │ 4 Gửi báo    │
                                        │ cáo tự động  │
                                        │ ⏱ 3'         │
                                        └──────────────┘

🟢 = Human boundary
Fallback: Nếu AI draft sai kết quả logs, sinh viên bỏ draft và tự viết dựa trên file logs thô.

```

### Top Problem 2: Đọc bài báo nghiên cứu tìm phương pháp luận
```text
CURRENT STATE — 120 phút
[1. Tải PDF: 5'] 
→ [2. Đọc Abstract/Intro: 15'] 
→ [3. Đọc hiểu Methodology & Toán học: 45'] <-- Bottleneck
→ [4. Đọc Experiments & Results: 30'] 
→ [5. Ghi chú vào Excel so sánh: 25']

FUTURE STATE — 25 phút
[1. Tải PDF lên công cụ AI: 2'] 
→ [2. AI tự động trích xuất cấu trúc & tham số: 3'] -- Workflow Step
→ [3. Sinh viên đọc tóm tắt & đối chiếu PDF: 15'] <-- Human Boundary
→ [4. Điền tự động vào bảng Excel: 5'] -- Rule/API

Fallback: Nếu AI trích xuất sai tham số, sinh viên tự tra cứu lại phần Experiments trong PDF gốc.
```

### Top Problem 3: Lên kế hoạch ngày
```text
CURRENT STATE — 30 phút
[1. Kiểm tra Jira: 5'] 
→ [2. Kiểm tra Github/Trello: 5'] 
→ [3. Kiểm tra lịch học: 5'] 
→ [4. Ước lượng thời gian & xếp lịch: 15'] <-- Bottleneck
→ [5. Phát sinh trễ giờ code -> bỏ tập gym]

FUTURE STATE — 8 phút
[1. Auto-sync lịch học & task thô: 2'] -- Rule
→ [2. AI tự động phân chia Time-Block + Buffer: 2'] -- Workflow Step
→ [3. Sinh viên review và chốt lịch ngày: 4'] <-- Human Boundary
→ [4. Nhắc nhở thông minh dựa trên tiến độ thực tế]

Fallback: Nếu lịch bị vỡ giữa ngày, AI hỗ trợ xếp lại lịch nhanh (Reschedule) cho các buổi tối.
```

---

## Chọn card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
PROBLEM CARD #1: Tổng hợp báo cáo tiến độ đồ án tốt nghiệp.
```

Vì sao:

```text
1. Vấn đề này rất thực tế và lặp lại hàng tuần đối với sinh viên CS làm đồ án (đặc biệt là đồ án nghiên cứu chạy mô hình).
2. Quy trình làm việc rất rõ ràng (W&B log, Git history, Notion task) và có các nguồn dữ liệu có cấu trúc cụ thể để AI xử lý.
3. Rất phù hợp để so sánh giữa:
   - Rule: Chỉ gom số liệu thô tạo dashboard.
   - Workflow: AI draft báo cáo tiến độ dựa trên số liệu thô và commits, người chỉnh sửa.
   - Agent: Tự động chạy code thí nghiệm, thu thập log, phát hiện lỗi rồi tự viết báo cáo và gửi.
4. Phù hợp với thời lượng lab, dễ dàng vẽ workflow và validate nhanh với các bạn cùng lớp.
```

Câu hỏi tôi muốn nhóm challenge:

```text
1. Làm thế nào để đo lường định lượng chất lượng báo cáo do AI viết (narrative) so với báo cáo do người tự viết?
2. Nếu AI bỏ sót một lỗi chạy mô hình quan trọng trong tuần (nhưng ghi nhận các chỉ số accuracy vẫn tăng), làm thế nào để đảm bảo người review phát hiện ra điều đó?
```
