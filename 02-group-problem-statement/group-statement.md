# Phase 3 — Group Convergence: từ 9-12 candidates về 1 (30')

## Bước 3.1 — Trình bày top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Vũ Anh | Tổng hợp báo cáo tiến độ đồ án tốt nghiệp | Sinh viên làm đồ án, Giảng viên hướng dẫn | Tổng hợp số liệu từ logs/commits và viết giải thích (narrative) tại sao mô hình tốt/tệ. | Rất tiềm năng cho mức **Workflow**. Quy trình và nguồn dữ liệu rõ ràng, giải quyết pain lặp lại mỗi tối Chủ Nhật. |
| 2 | Vũ Anh | Đọc bài báo nghiên cứu để tìm phương pháp luận | Sinh viên ngành CS làm đồ án nghiên cứu | Đọc hiểu và phân tích phần Methodology có nhiều công thức toán học và cấu trúc mô hình phức tạp. | Phù hợp mức **Workflow**, giúp đọc nhanh. Nhưng rủi ro AI hiểu sai công thức toán và hình ảnh sơ đồ mạng. |
| 3 | Vũ Anh | Lên kế hoạch ngày tối ưu lịch tập gym và học tập | Bản thân sinh viên | Ước lượng thời gian chạy code và dự phòng (buffer time) dẫn đến việc vỡ lịch đi tập gym. | Có thể chỉ cần mức **Rule** hoặc **Workflow** đơn giản. Tính cá nhân hóa cao nhưng tác động nhóm thấp. |
| 4 | Phạm Sơn | Đọc tài liệu API (như cổng sandbox VNPAY/PayPal) hoặc tài liệu công nghệ mới (Next.js) bằng tiếng Anh để tích hợp vào bài tập lớn | Thành viên đảm nhận tích hợp hệ thống | Khâu đọc hiểu tài liệu tiếng Anh và cấu hình tham số kỹ thuật mất nhiều thời gian vì tài liệu dài, thiếu ví dụ thực tế hoặc lỗi thời. | Rất tiềm năng cho mức **Workflow**. Quy trình rõ ràng và pain lặp lại khi tích hợp API, nhưng rủi ro AI hiểu sai phiên bản tài liệu. |
| 5 | Phạm Sơn | Cài các môi trường thủ công (SQL Server,..) mỗi khi chuyển từ máy này sang máy khác | Lập trình viên hệ thống | Khâu xử lý lỗi cấu hình môi trường và dependency (SQL Server, port, quyền truy cập, connection string...) bị lặp lại do mỗi máy có cấu hình khác nhau. | Phù hợp mức **Workflow**, giúp giảm thời gian xử lý lỗi cấu hình. Tuy nhiên, khác biệt môi trường giữa các máy gây khó tự động hóa hoàn toàn. |
| 6 | Phạm Sơn | Gia hạn và cấu hình lại chứng chỉ bảo mật (SSL) thủ công cho các tên miền | Thành viên phụ trách hạ tầng web | Phải theo dõi ngày hết hạn chứng chỉ và thực hiện các dòng lệnh cấu hình máy chủ web thủ công. | Phù hợp mức **Agent/Rule**, tác động rõ ràng nếu quên gia hạn. Tuy nhiên, tần suất lặp lại không quá cao. |
| 7 | Minh Đức | Phân bổ thời gian giữa đồ án tốt nghiệp và chương trình AI thực chiến | Sinh viên năm cuối làm AI thực chiến | Khó quản lý thời gian, deadline dễ chồng chéo dẫn đến quá tải task. | Pain xảy ra hằng ngày, workflow rõ, nhưng thiên về tính cá nhân và ý chí hơn là vấn đề công nghệ thuần túy. |
| 8 | Minh Đức | Hổng kiến thức AI khi xuất phát từ ngành vi mạch, điện tử | Sinh viên chuyển ngành sang AI | Mất nhiều thời gian để hiểu các tài liệu học tập nâng cao và các bài lab thực chiến do thiếu nền tảng toán/CS. | Pain thật, sát cá nhân, phù hợp hướng **AI Tutor** hỗ trợ học tập nhưng scope hơi rộng cho một bài lab cụ thể. |
| 9 | Minh Đức | Theo dõi thông báo chương trình từ nhiều kênh khác nhau | Học viên chương trình AI thực chiến | Thông báo bị phân tán trên nhiều nền tảng (Discord, Zalo, Email, LMS), dễ bị bỏ sót deadline. | Workflow rõ, có tính lặp lại. Nhưng có thể giải quyết tốt bằng **Rule/Script** gom tin (Web scraping) đơn giản, chưa cần dùng nhiều AI. |
| 10 | Hưng | Di chuyển xa mỗi ngày khi tham gia chương trình AI thực chiến | Học viên ở xa trung tâm | Mất gần 3 tiếng/ngày cho việc di chuyển bằng xe buýt hoặc xe máy, gây mệt mỏi và giảm thời gian học tập. | Pain thật, impact lớn nhưng là vấn đề vật lý, thiên về thay đổi quy trình cá nhân (process fix) hơn là áp dụng AI. |
| 11 | Hưng | Thiếu nền tảng AI khi chuyển từ DevSecOps/Security sang AI | Sinh viên chuyển ngành sang AI | Mất nhiều thời gian để hiểu khái niệm toán học, học máy căn bản và theo kịp tốc độ của lớp thực chiến. | Pain rõ ràng, có khả năng giải bằng AI tutor/learning path generator nhưng khó đo lường độ chính xác và thành công ngắn hạn. |
| 12 | Hưng | Thiếu kinh phí để gọi API phục vụ học và làm project | Sinh viên / Fresher học AI | Chi phí gọi các LLM API chất lượng cao (GPT-4, Claude 3 Opus...) quá lớn, hạn chế việc thực hành thử nghiệm. | Có nhu cầu thật, phù hợp hướng **AI Router/Cost Optimization** nhưng thiên về bài toán tối ưu chi phí hạ tầng. |

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | 1, 2, 4 | Đọc hiểu, tổng hợp tài liệu (PDF, Commits, API Docs) và xuất ra văn bản. | Rất tiềm năng giải bằng **AI Workflow** do input/output rõ ràng. |
| B | 8, 11 | Hỗ trợ học tập, bù đắp kiến thức cho người chuyển ngành. | Mang tính sư phạm và cá nhân hóa cao, scope hơi rộng. |
| C | 5, 6 | Thiết lập môi trường và cấu hình hạ tầng. | Giải quyết triệt để hơn bằng Non-AI tools (Docker, Ansible). |
| D | 3, 7, 9, 10 | Phân bổ thời gian, nhắc việc, di chuyển. | Thiên về kỷ luật cá nhân hoặc các tool quản lý thông thường. |

## Bước 3.3 — Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| **Tổng hợp báo cáo tiến độ đồ án** | Tác động lớn cho cả nhóm, quy trình lặp lại ổn định hàng tuần. | Cách thu thập logs tự động trên nhiều môi trường khác nhau. |
| **Đọc tài liệu API để tích hợp** | Giải quyết pain-point thực tế khi làm bài tập lớn cần tích hợp cổng thanh toán. | Mỗi bên cung cấp API có định dạng docs rất khác nhau. |
| **Đọc bài báo nghiên cứu khoa học** | Giúp sinh viên nắm bắt nhanh phương pháp luận từ các paper học thuật. | AI có thể hiểu sai công thức toán và sơ đồ mạng trong PDF. |

## Bước 3.4 — Score để đồng thuận

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Tổng hợp báo cáo tiến độ đồ án** | 5 | 5 | 5 | 4 | 5 | 5 | 5 | **34** |
| **Đọc tài liệu API để tích hợp** | 4 | 4 | 4 | 4 | 4 | 4 | 4 | **28** |
| **Đọc bài báo nghiên cứu khoa học** | 5 | 4 | 4 | 3 | 4 | 4 | 5 | **29** |

Candidate nhóm chọn:

```text
Tổng hợp báo cáo tiến độ đồ án tốt nghiệp
```

Vì sao chọn:

```text
1. Cả 4 thành viên trong nhóm đều đang học năm cuối và cùng chịu chung nỗi đau chuẩn bị báo cáo tiến độ vào tối Chủ Nhật.
2. Quy trình làm việc rất rõ ràng (W&B log, Git history, Notion task) và có các nguồn dữ liệu có cấu trúc cụ thể để AI xử lý.
3. Rất dễ vẽ workflow trước/sau và đánh giá hiệu năng tiết kiệm thời gian cụ thể.
```

Vì sao không chọn các candidate còn lại:

```text
- Đọc tài liệu API: Cấu trúc tài liệu của các bên khác nhau quá nhiều, khó tạo ra một workflow chung thống nhất trong thời gian ngắn.
- Đọc bài báo nghiên cứu: Rủi ro AI hiểu sai công thức toán học và bảng biểu số liệu trong PDF là rất lớn, dễ dẫn đến sai lệch học thuật nghiêm trọng.
```

Nếu có disagreement, nhóm xử lý thế nào:

```text
Lúc đầu Sơn muốn chọn bài toán cài đặt môi trường của mình vì hay gặp lỗi cấu hình. Tuy nhiên, sau khi cả nhóm phản biện rằng bài toán này có thể giải quyết triệt để 100% bằng giải pháp Non-AI (như viết Dockerfile hoặc Script cài đặt Docker tự động) an toàn và ít rủi ro hơn AI, Sơn đã hoàn toàn đồng thuận chuyển sang chọn đề tài báo cáo tiến độ.
```

---

# Phase 4 — Quick Validation + Research giải pháp (30')

## Bước 4.1 — Quick validation

Chọn ít nhất một cách.

### Option A — Quick interviews

Hỏi 2-3 người:
- Lần gần nhất bạn gặp vấn đề này là khi nào?
- Bạn đang xử lý bằng workflow nào?
- Bước nào mất thời gian hoặc khó chịu nhất?
- Bạn mất khoảng bao lâu?
- Nếu tốt hơn, bạn muốn điều gì thay đổi?

### Option B — Micro survey / Discord poll

Hỏi 5-10 người:
- Bạn có gặp vấn đề này không?
- Tần suất?
- Bước nào đau nhất?
- Hiện bạn workaround thế nào?
- Mức độ đáng giải quyết: 1-5?

Kết quả:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 bạn ở nhóm khác | 2/3 bạn mất hơn 50 phút mỗi tuần để làm báo cáo, cảm thấy mệt mỏi nhất ở phần viết giải trình (narrative). | 1 bạn cho biết nhóm của họ dùng bảng Kanban trên Github Projects và thầy tự vào xem trực tiếp nên không cần viết báo cáo dạng văn bản. | Nhóm nhận thấy pain nằm ở bước giải trình (narrative) tại sao mô hình tốt/tệ. Do đó nhóm thu hẹp phạm vi: tập trung vào AI hỗ trợ viết draft narrative từ logs và commits thô. |
| Survey / poll | 8 người trên Discord lớp | 7/8 người xác nhận việc viết báo cáo tiến độ tuần là bắt buộc và thường tốn trung bình 45-70 phút tối Chủ Nhật. | 1 người cho biết họ chỉ cần chụp ảnh màn hình dashboard là xong. | Giữ nguyên đề tài báo cáo, bổ sung ranh giới an toàn: AI chỉ viết nháp, người review và gửi. |
| Log / review / ticket | N/A | N/A | N/A | N/A |

## Bước 4.2 — Research giải pháp đã có

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Weights & Biases Reports | https://docs.wandb.ai/guides/reports | Cho phép gom các biểu đồ huấn luyện và xuất thành báo cáo dạng web. | Biểu đồ trực quan, số liệu chính xác 100%. | Chỉ hiển thị số liệu thô và biểu đồ, không tự động viết văn bản nhận xét hoặc liên kết với các thay đổi trong code Git. | W&B là nguồn input số liệu huấn luyện lý tưởng nhất cho workflow của nhóm. |
| Github Actions (Auto release notes) | https://github.com/marketplace/actions/release-drafter | Tự động tổng hợp danh sách commits và PRs thành báo cáo dạng văn bản. | Rất nhanh, tự động hoàn toàn bằng các rule lọc tag. | Chỉ hiển thị danh sách tên commits/PRs khô khan, không phân tích được ý nghĩa khoa học của các thay đổi đó. | Dùng làm nguồn input về lịch sử code Git. |
| Gemini in Google Docs / Workspace | https://workspace.google.com/solutions/ai/ | Hỗ trợ soạn thảo và tóm tắt văn bản ngay trong tài liệu Docs. | Viết văn học thuật trôi chảy, sửa lỗi ngữ pháp tốt. | Phải copy-paste thủ công dữ liệu từ logs và Git vào Docs thì AI mới viết được, tốn thao tác thủ công. | AI rất mạnh ở bước "Viết nháp ngôn ngữ" (narrative draft) nếu được cấp đủ ngữ cảnh đầu vào (context). |

---

# Phase 5 — Workflow + Problem Statement (45')

## Bước 5.1 — Current workflow bản nhóm

Dán workflow hoặc link file:

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
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Sinh viên | Log Weights & Biases | Số liệu Accuracy, Loss thô | 15 phút / hàng tuần | Phải mở trình duyệt và tìm lại đúng run trong tuần. |
| 2 | Sinh viên | Local Git repository | Commit history trong tuần | 10 phút / hàng tuần | Gõ git log và tự đọc xem mình đã thay đổi file nào. |
| 3 | Sinh viên | Bảng Notion task | Danh sách task đã/chưa làm | 10 phút / hàng tuần | Đối chiếu so với kế hoạch đã đặt ra từ đầu tuần. |
| 4 | Sinh viên | Dữ liệu gom ở bước 1, 2, 3 | Phân tích giải trình narrative | 15 phút / hàng tuần | Tốn nhiều nơ-ron suy nghĩ lý do mô hình chạy tệ hoặc bị bug. |
| 5 | Sinh viên | Phần text thô | Tài liệu Markdown đúng chuẩn | 5 phút / hàng tuần | Định dạng đề mục, in đậm, chèn liên kết. |
| 6 | Sinh viên | File Markdown hoàn chỉnh | Tin nhắn Discord gửi nhóm / Email gửi thầy | 5 phút / hàng tuần | Copy paste và gửi đi. |

Bottleneck chính:

```text
Bước 4 — Viết narrative giải thích vì sao mô hình chạy tốt/tệ và tuần sau định làm gì dựa trên logs và commits. Đây là bước đòi hỏi sáng tạo ngôn từ và kết nối thông tin phức tạp, dễ gây trì hoãn (blank page).
```

## Bước 5.2 — Future workflow bản nhóm

Dán workflow hoặc link file:

```text
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

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 4 | Gom các bước lấy dữ liệu thủ công vào 1 script tự động. |
| Tổng thời gian | 60 phút | 18 phút | Tiết kiệm hơn 70% tổng thời gian thực hiện. |
| Số bước thủ công | 6 | 1 | Chỉ còn bước Review & Edit là sinh viên phải trực tiếp làm. |
| Bottleneck chính | Viết narrative (căng thẳng trí óc) | Review & Edit (đọc và sửa đổi bản nháp) | Chuyển dịch điểm nghẽn sang khâu kiểm soát chất lượng. |
| Risk mới | Báo cáo bị trễ deadline | AI bịa đặt số liệu (hallucination) | Rủi ro về tính chính xác thông tin được kiểm soát qua Human Boundary. |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối ngành Khoa học máy tính đang thực hiện đồ án tốt nghiệp về AI. |
| **Workflow** | Hàng tuần phải gom logs huấn luyện từ Weights & Biases, lịch sử commit Git và task Notion để viết báo cáo tiến độ bằng Markdown gửi giảng viên hướng dẫn. |
| **Bottleneck** | Khâu phân tích logs thô và viết lời giải thích giải trình (narrative) vì sao mô hình tăng/giảm hiệu năng mất tới 15 phút và dễ gây cảm giác nhàm chán, mệt mỏi. |
| **Impact** | Mỗi tuần tốn 60 phút/thành viên (180 phút/nhóm). Báo cáo dễ bị nộp trễ hoặc viết quá sơ sài, làm giảng viên không nắm sát được tiến độ để góp ý đúng hướng. |
| **Success Metric** | Giảm tổng thời gian làm báo cáo từ 60 phút xuống dưới 20 phút. 100% báo cáo nộp đúng hạn trước buổi họp đầu tuần. Số câu hỏi chất vấn lại từ giảng viên về thông số cơ bản giảm về 0. |
| **Boundary** | AI không được tự ý gửi báo cáo đi mà không có sự phê duyệt của sinh viên. AI không được tự bịa ra các số liệu accuracy/loss ngoài dữ liệu logs thực tế. |

---

# Phase 6 — Rule / Workflow / Agent + Decision (25')

## Bước 6.0 — Ma trận độ phù hợp với AI để suy nghĩ nhanh

Bài toán của nhóm nằm ở ô nào?

```text
Độ phức tạp cao - Độ mơ hồ cao
```

Vì sao?

```text
- Quy trình gồm nhiều bước thu thập dữ liệu từ các nguồn khác nhau (W&B, Git, Notion) tạo nên độ phức tạp cao.
- Output cần viết giải thích bằng ngôn ngữ tự nhiên (narrative) thay đổi linh hoạt theo tuần, không có đáp án đúng duy nhất tạo nên độ mơ hồ cao.
```

## Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Viết script Python tự động lấy API Git/W&B và đổ vào một template Markdown cố định. | Đủ nếu chỉ cần báo cáo số liệu dạng bảng khô khan. | Không viết được phần giải thích ý nghĩa bằng ngôn ngữ tự nhiên (narrative) cho thầy hướng dẫn đọc. | Không chọn làm giải pháp chính (nhưng dùng làm bước gom data đầu vào). |
| **Workflow** | Dùng script gom data -> Gọi LLM API kèm Prompt Template để viết draft -> Sinh viên review/edit -> Nhấn nút gửi đi. | Hợp vì quy trình có các bước tuyến tính cố định. AI chỉ xử lý khâu thế mạnh là ngôn ngữ để viết nháp. | Bản nháp có thể thiếu chiều sâu hoặc bịa số liệu nếu prompt không được giới hạn chặt chẽ. | **Chọn** |
| **Agent** | AI Agent tự động giám sát server chạy AI, tự quyết định thời điểm xuất báo cáo, tự tìm lỗi code trong repo, tự viết báo cáo và gửi trực tiếp cho thầy. | Cần khi hệ thống cực kỳ phức tạp và cần đưa ra quyết định độc lập. | Rủi ro bảo mật hệ thống cao, AI tự gửi báo cáo lỗi hoặc số liệu sai học thuật trực tiếp cho giảng viên. | Không chọn |

Mức chọn:

```text
Workflow
```

Vì sao chọn:

```text
Data collection có thể dùng rule/script để đảm bảo độ chính xác của số liệu thô. Khâu viết narrative cần AI hỗ trợ xử lý ngôn ngữ. Việc sinh viên review ở bước 3 đảm bảo tính an toàn cao (Human-in-the-loop) mà không cần cấu trúc Agent tự lập kế hoạch động phức tạp.
```

Vì sao không chọn mức đơn giản hơn:

```text
Mức Rule đơn giản không giải quyết được khâu viết narrative bằng ngôn ngữ tự nhiên. Nếu chỉ hiển thị số liệu dạng bảng thô, giảng viên sẽ mất rất nhiều thời gian đọc hiểu và không nắm bắt được bối cảnh của nghiên cứu.
```

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối ngành Khoa học máy tính đang làm đồ án tốt nghiệp về AI. |
| **Workflow** | Chạy script tự động gom logs (W&B) + commits (Git) -> LLM viết draft báo cáo tiến độ -> Sinh viên review & sửa đổi trên file Markdown -> Nhấn nút tự động gửi đi qua Discord/Email. |
| **Bottleneck** | Khâu viết giải thích (narrative) diễn giải lý do tăng/giảm hiệu năng mô hình từ số liệu thô. |
| **Impact** | Tốn 60 phút/tuần/sinh viên; báo cáo dễ sơ sài hoặc trễ hạn làm buổi họp tiến độ với giảng viên kéo dài không hiệu quả. |
| **Success Metric** | Thời gian làm báo cáo giảm từ 60 phút xuống dưới 20 phút. 100% báo cáo nộp trước 8h00 sáng thứ Hai. |
| **Boundary** | AI chỉ được hoạt động trong môi trường sandbox đọc logs/commits được cung cấp, không được tự động tương tác gửi báo cáo khi chưa có sự xác nhận của sinh viên. |
| **AI intervention point** | Điểm can thiệp của AI: Ngay sau khi script hoàn thành việc thu thập và cấu trúc hóa dữ liệu thô (W&B logs + Git commits). |
| **Mức chọn** | **Workflow** (Phối hợp Script tự động hóa dữ liệu + LLM sinh văn bản nháp + Người chỉnh sửa). |
| **Rủi ro & người thật kiểm tra** | **Rủi ro:** AI bịa số liệu huấn luyện hoặc diễn giải sai nguyên nhân lỗi. **Cách kiểm tra:** Sinh viên bắt buộc phải đối chiếu các chỉ số accuracy/loss trong bản nháp Markdown với biểu đồ thực tế trên trang dashboard W&B trước khi gửi. |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | **Yes** | Đã định nghĩa rõ ràng các bước và thời gian trước/sau. |
| Baseline và success metric đã đo được chưa? | **Yes** | Baseline: 60 phút, Target: < 20 phút. Đo bằng thời gian thực hiện. |
| Có data/input đủ dùng chưa? | **Yes** | API của Weights & Biases và GitHub có sẵn và dễ trích xuất. |
| Nếu AI sai, hậu quả có chấp nhận được không? | **Yes** | Được, vì sinh viên là người kiểm soát cuối cùng (Human Boundary). |
| Có người review/owner vận hành không? | **Yes** | Sinh viên là chủ thể chịu trách nhiệm gửi báo cáo cho thầy. |
| Có cách non-AI đơn giản hơn không? | **No** | Bản template tĩnh không tự động tạo ra diễn giải linh hoạt hàng tuần được. |

Decision:

```text
Go với scope nhỏ (Pilot)
```

Lý do:

```text
Bài toán có quy trình cụ thể, dữ liệu đầu vào có sẵn và rủi ro được kiểm soát tốt bởi con người. Việc triển khai thử nghiệm (pilot) giúp đánh giá chính xác khả năng viết narrative của AI trước khi tự động hóa hoàn toàn.
```

Nếu Go, pilot nhỏ nhất là:

```text
1. Sử dụng log Weights & Biases và Git commits thực tế của 2 tuần gần nhất.
2. Viết một script Python call API W&B trích xuất file json chứa các thông số huấn luyện cốt lõi của tuần.
3. Chạy câu lệnh `git log --since="1 week ago" --oneline` để lấy list commit.
4. Paste thủ công dữ liệu json và commits trên vào ChatGPT/Gemini kèm Prompt Template để xem chất lượng bản nháp báo cáo Markdown.
5. Đo lường thời gian thực tế sinh viên phải chỉnh sửa bản nháp đó.
```

Nếu Not Yet, cần validate gì trước:

```text
N/A
```

Nếu No-Go, nên làm gì thay AI:

```text
N/A
```
