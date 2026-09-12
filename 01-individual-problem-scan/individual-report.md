# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- **Họ và tên:** Nguyễn Thị Vàng
- **Mã học viên:** 2A202602897
- **Vai trò / bối cảnh:** Sinh viên lớp K4B - VinUni AI kiêm Machine Learning Intern / Nghiên cứu viên trẻ, thường xuyên huấn luyện mô hình Deep Learning, đi lại học tập bằng phương tiện công cộng và thực hiện nghiên cứu khoa học.
- **Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):**
  - Huấn luyện, theo dõi metric và debug lỗi mô hình Deep Learning trên cluster GPU/cloud (MLflow, Weights & Biases).
  - Tìm kiếm, đọc abstract và tổng hợp tài liệu học thuật (Literature Review) cho đồ án và đề tài nghiên cứu.
  - Di chuyển hằng ngày giữa nơi ở, trường học và phòng lab bằng xe buýt và metro đô thị.
  - Tham gia họp nhóm dự án kỹ thuật (2 buổi/tuần) và viết báo cáo tiến độ milestone.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| **1** | AI có thể tốt hơn | **Theo dõi và xử lý cảnh báo từ nhiều công cụ AI/MLOps** | Kỹ sư AI/Machine Learning Engineer, nghiên cứu viên AI | Cảnh báo từ nhiều nền tảng (MLflow, Weights & Biases, Slack, Grafana...) bị phân tán, nhận 30-50 alert/ngày; mất 45-60 phút/ngày lọc lỗi; phản hồi chậm 1-3 tiếng khi sập run training. |
| **2** | Tốn thời gian | **Lập lộ trình di chuyển tối ưu khi kết hợp nhiều phương tiện công cộng** | Người đi làm và sinh viên sử dụng xe buýt, metro | Khó đồng bộ thời gian giữa các tuyến và điểm trung chuyển; lỡ chuyến 2-3 lần/tuần; mất thêm 20-30 phút chờ đợi trung chuyển mỗi ngày khi lịch trình xe buýt bị trễ do tắc đường. |
| **3** | Tốn thời gian | **Tìm và tổng hợp tài liệu liên quan (Literature Review) cho đề tài nghiên cứu** | Nghiên cứu viên, học viên cao học, sinh viên làm khóa luận | Phải đọc lướt abstract và loại bỏ 40-50 paper không liên quan thủ công; mất 4-6 tiếng/tuần trước khi tìm được 3-5 tài liệu thực sự phù hợp. |
| **4** | Lặp lại | Tổng hợp biên bản họp (Meeting Notes) và trích xuất Action Items sau mỗi buổi họp nhóm đồ án | Trưởng nhóm, 4 thành viên trong nhóm | Mất 35-45 phút/buổi họp (bấm giờ 3 buổi: 38', 42', 35'); 2 lần/tuần; từng có 2 lần giao sót task do ghi chép tay vội. |
| **5** | Tốn thời gian | Đọc hiểu và phân tích log lỗi (stack trace) dài hàng trăm dòng khi debug mô hình Deep Learning (CUDA OOM, shape mismatch) | Sinh viên thực hành lab | Mất 40-60 phút mỗi lần gặp lỗi lạ; phải copy thủ công từng đoạn trace lên Google/StackOverflow tìm cách khắc phục. |
| **6** | Pain từ người khác | Thành viên nhóm nộp phần code/nội dung không đúng chuẩn quy ước (formatting/style guide) khiến người phụ trách tổng hợp phải sửa thủ công | Người phụ trách tích hợp (Merge lead) | 3/4 đợt nộp milestone phải tốn thêm 30-45 phút chỉ để căn chỉnh lại thụt dòng, citation và format bảng biểu trước giờ nộp. |
| **7** | Lặp lại | Soạn bộ câu hỏi trắc nghiệm/flashcard ôn tập từ slide bài giảng dài 80-120 trang trước kỳ thi Quiz tuần | Sinh viên ôn tập | Mất 2.5 - 3 tiếng/môn học vào mỗi cuối tuần; 80% câu hỏi tự tạo chỉ kiểm tra mức độ ghi nhớ bề mặt, thiếu tính liên kết. |
| **8** | AI có thể tốt hơn | Phân loại, gắn nhãn (tag) và tóm tắt nhanh tài liệu tham khảo (PDF, link bài báo) được lưu trữ trong kho tài liệu nhóm | Cả nhóm đồ án | Kho lưu trữ có hơn 60 bài viết nhưng 70% không ai đọc lại vì thiếu nhãn phân loại; mất 10-15 phút mỗi lần tìm lại nguồn đã lưu. |
| **9** | Lặp lại | Soạn thảo email báo cáo tiến độ tuần và xin ý kiến giảng viên hướng dẫn theo đúng cấu trúc chuẩn | Trưởng nhóm đồ án | Mất 20-25 phút mỗi chiều thứ Sáu để rà soát câu chữ, kiểm tra link tài liệu đính kèm; lặp lại đều đặn mỗi tuần. |
| **10** | Tốn thời gian | Chuyển đổi công thức toán học và bảng biểu từ tài liệu PDF sang mã LaTeX để chèn vào báo cáo đồ án | Thành viên viết báo cáo | Mất 15-20 phút cho mỗi trang có nhiều công thức phức tạp; trung bình gặp lỗi biên dịch (syntax error) 3-4 lần mỗi tài liệu. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Gợi ý các điểm nghẽn (bottlenecks) phổ biến trong quy trình làm việc của một kỹ sư/nghiên cứu viên AI, người sử dụng phương tiện công cộng và làm nghiên cứu học thuật."
- Ý dùng được: Vấn đề phân tán cảnh báo MLOps gây trễ xử lý lỗi sập training, điểm nghẽn trung chuyển buýt - metro thiếu dữ liệu real-time, sàng lọc abstract thủ công trong literature review.
- Ý bỏ vì không phải pain thật: "AI tự động viết toàn bộ bài báo nghiên cứu" (loại vì vi phạm liêm chính học thuật và không giải quyết đúng điểm nghẽn quy trình).

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (10 dòng)
- [x] Dùng ít nhất 3/4 lăng kính (AI có thể tốt hơn, Tốn thời gian, Lặp lại, Pain từ người khác)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| **1** | **Theo dõi và xử lý cảnh báo từ nhiều công cụ AI/MLOps** *(Candidate #7 của Vàng trong buổi pitch)* | - Actor cụ thể (Kỹ sư AI/MLE).<br>- Workflow rõ từ alert phát sinh $\rightarrow$ phân loại $\rightarrow$ xử lý.<br>- Impact đo được bằng thời gian cứu vãn run training sập và chi phí GPU. | Nguồn dữ liệu log MLOps thật từ enterprise khó tiếp cận đầy đủ trong môi trường lab học tập. |
| **2** | **Lập lộ trình di chuyển tối ưu khi kết hợp nhiều phương tiện công cộng** *(Candidate #8 của Vàng trong buổi pitch)* | - Actor đông đảo (Sinh viên, người đi làm đi buýt/metro).<br>- Workflow di chuyển rõ ràng qua các điểm trung chuyển.<br>- Impact đo được bằng thời gian chờ và số chuyến lỡ. | Độ trễ dữ liệu GPS thời gian thực từ các tuyến xe buýt công cộng có thể không ổn định. |
| **3** | **Tìm và tổng hợp tài liệu liên quan (Literature Review) cho đề tài nghiên cứu** *(Candidate #9 của Vàng trong buổi pitch)* | - Pain point rất lớn của người làm nghiên cứu (mất 4-6h/tuần).<br>- Dữ liệu arXiv/Semantic Scholar chuẩn hóa, API mở sẵn có.<br>- AI xử lý ngôn ngữ và phân tích ngữ nghĩa abstract cực mạnh. | Khả năng tổng hợp chính xác các công thức toán và đánh giá chiều sâu giới hạn của paper. |

---

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Theo dõi và xử lý cảnh báo từ nhiều công cụ AI/MLOps (Candidate #7)

```text
Problem 1 câu:
Kỹ sư AI/MLE mất 45-60 phút mỗi ngày để kiểm tra và phân loại cảnh báo phân tán từ nhiều công cụ MLOps (MLflow, Weights & Biases, Slack, Grafana), khiến việc phát hiện lỗi training sập (CUDA OOM, NaN loss) bị chậm trễ từ 1-3 tiếng, gây lãng phí tài nguyên GPU đắt đỏ.

Actor:
Kỹ sư AI (Machine Learning Engineer), nghiên cứu viên vận hành huấn luyện mô hình Deep Learning.

Thời điểm / bối cảnh:
Trong suốt quá trình huấn luyện mô hình học sâu chạy dài ngày trên cluster GPU hoặc cloud server.

Current workflow 3-7 bước:
1. Cảnh báo phát sinh từ nhiều công cụ riêng lẻ gửi về email, kênh Slack bot, Grafana dashboard (liên tục).
2. Kỹ sư mở từng nền tảng (W&B, MLflow, Grafana) để tìm kiếm run ID tương ứng và mở log chi tiết (15 phút).
3. Đọc dò log để phân biệt lỗi nghiêm trọng (loss NaN, CUDA OOM, server disconnect) với warning thông thường (20 phút).
4. Xác định mức ưu tiên và tìm người phụ trách run đó để thông báo qua chat (10 phút).
5. Kỹ sư SSH vào server để kill process hoặc chỉnh sửa hyperparameter và restart job (5 phút).

Bottleneck:
Bước 3 — Phải đọc log thủ công và đối chiếu giữa nhiều công cụ rời rạc để xác định lỗi ưu tiên, tốn nhiều thời gian phân tích và dễ bỏ sót khi có bão thông báo (alert fatigue).

Impact:
Lãng phí 45-60 phút/ngày cho kỹ sư. Mỗi run training sập bị treo thêm 2-3 tiếng gây lãng phí hàng triệu đồng chi phí thuê GPU và làm chậm tiến độ phát triển mô hình.

Success metric:
- Giảm thời gian phát hiện và thông báo lỗi nghiêm trọng từ 120 phút xuống dưới 5 phút.
- Gom 100% cảnh báo về một dashboard tập trung, tự động lọc bỏ >= 80% cảnh báo rác/warning vô hại.

Non-AI alternative:
Cấu hình webhook lọc theo từ khóa cứng hoặc HTTP status code. Nhược điểm: Không hiểu được ngữ nghĩa log phức tạp (như validation loss không giảm, gradient exploding).

AI hypothesis:
AI Agent làm listener thu thập log đa nguồn, dùng LLM phân tích ngữ cảnh stack trace để xếp hạng mức độ khẩn cấp (Critical vs Info), gợi ý nguyên nhân cốt lõi và tag trực tiếp kỹ sư phụ trách kèm nút bấm xử lý nhanh.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 50 phút

[1 Nhận alert phân tán qua Slack/Email/Grafana: liên tục] 
→ [2 Mở từng công cụ tìm log chi tiết: 15'] 
→ [3 Đọc log phân biệt lỗi thật vs warning rác: 20']  <-- bottleneck
→ [4 Tìm và tag kỹ sư phụ trách thủ công: 10'] 
→ [5 SSH vào server kill/restart job: 5']

FUTURE STATE — 5 phút

[1 Rule/Listener gom alert đa nguồn về 1 gateway: tức thì] 
→ [2 AI Agent phân tích stack trace & đánh giá mức độ khẩn cấp: 30s] 
→ [3 Bắn thông báo Digest tóm tắt nguyên nhân & gợi ý tag kỹ sư: 30s] 
→ [4 Kỹ sư review thông báo & xác nhận hành động: 1']  <-- human boundary
→ [5 Hệ thống tự động kích hoạt script restart/kill process: tức thì]

Fallback: Nếu AI không chắc chắn về mức độ nghiêm trọng (độ tin cậy < 70%), alert được gắn cờ "Cần review" và chuyển tiếp nguyên văn vào kênh Slack chung.
```

---

#### Problem Card #2 — Lập lộ trình di chuyển tối ưu khi kết hợp nhiều phương tiện công cộng (Candidate #8)

```text
Problem 1 câu:
Người đi làm và sinh viên sử dụng phương tiện công cộng mất 15-20 phút mỗi chuyến để tra cứu qua lại giữa nhiều ứng dụng nhằm kết hợp xe buýt và metro, nhưng vẫn thường xuyên bị lỡ chuyến do thời gian thực tế không đồng bộ khi có tắc đường.

Actor:
Sinh viên đại học và nhân viên văn phòng thường xuyên di chuyển bằng xe buýt kết hợp tuyến metro đô thị.

Thời điểm / bối cảnh:
Giờ cao điểm sáng (7h00-8h30) và chiều tối (17h00-18h30) trên các trục đường huyết mạch có trạm metro và trạm buýt trung chuyển.

Current workflow 3-7 bước:
1. Mở app BusMap để xem vị trí và thời gian ước tính của tuyến buýt sắp tới (4 phút).
2. Mở Google Maps để tra cứu lộ trình đi bộ hoặc kết nối với ga metro gần nhất (5 phút).
3. Tự tính nhẩm thời gian trừ hao trung chuyển giữa buýt và metro để không bị lỡ chuyến tàu (5 phút).
4. Quyết định lộ trình và bắt đầu di chuyển ra trạm (2 phút).
5. Khi xe buýt bị kẹt xe giữa đường, phải đứng tại chỗ mở lại cả 2 app để tìm tuyến khác thay thế (2 phút).

Bottleneck:
Bước 2 & 3 — Không có nền tảng nào đồng bộ thời gian thực giữa xe buýt (bị biến động do tắc đường) và metro (chạy theo giờ cố định), người dùng phải tự tính nhẩm và phán đoán rủi ro.

Impact:
Bị lỡ chuyến trung chuyển 2-3 lần/tuần, tăng thời gian chết chờ đợi tại điểm trung chuyển thêm 20-30 phút mỗi ngày, dẫn đến nguy cơ muộn học/muộn làm.

Success metric:
- Giảm thời gian lên kế hoạch lộ trình kết hợp từ 18 phút xuống dưới 2 phút.
- Giảm tỷ lệ lỡ chuyến trung chuyển do trễ giờ xuống dưới 5%.

Non-AI alternative:
Sử dụng bảng giờ chạy cố định dán tại trạm xe buýt và ga metro. Nhược điểm: Hoàn toàn bất lực trước tình trạng tắc đường giờ cao điểm tại Việt Nam.

AI hypothesis:
Hệ thống Workflow AI thu thập dữ liệu GPS thời gian thực của xe buýt và lịch chạy metro, dự báo độ trễ theo thời gian thực dựa trên mô hình giao thông giờ cao điểm, và tự động đề xuất phương án kết hợp tối ưu từng phút.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 18 phút

[1 Mở BusMap xem xe buýt: 4'] 
→ [2 Mở Google Maps xem ga metro: 5']  <-- bottleneck
→ [3 Tự tính nhẩm thời gian trung chuyển buýt - tàu: 5']  <-- bottleneck
→ [4 Quyết định tuyến đường: 2'] 
→ [5 Tra cứu lại khi buýt tắc đường: 2']

FUTURE STATE — 2 phút

[1 Người dùng nhập điểm đi và điểm đến: 30s] 
→ [2 AI Workflow fetch real-time GPS buýt + lịch metro & dự báo độ trễ: 30s] 
→ [3 Hiển thị 2 phương án di chuyển tối ưu kèm điểm trung chuyển chuẩn xác: 30s] 
→ [4 Người dùng chọn phương án và bật chế độ theo dõi hành trình: 30s]  <-- human boundary

Fallback: Nếu dữ liệu GPS xe buýt bị gián đoạn, hệ thống tự động cảnh báo và chuyển sang chế độ tính toán dựa trên thời gian di chuyển trung bình theo lịch trình cố định.
```

---

#### Problem Card #3 — Tìm và tổng hợp tài liệu liên quan (Literature Review) cho đề tài nghiên cứu (Candidate #9)

```text
Problem 1 câu:
Nghiên cứu viên và sinh viên làm khóa luận mất 4-6 tiếng mỗi tuần để đọc lướt hàng chục abstract trên Google Scholar/arXiv và loại bỏ thủ công các paper không liên quan trước khi tìm được 3-5 tài liệu thực sự phù hợp với đề tài.

Actor:
Nghiên cứu viên trẻ, học viên cao học, sinh viên làm khóa luận tốt nghiệp chuyên ngành AI/Khoa học máy tính.

Thời điểm / bối cảnh:
Giai đoạn khởi động đề cương nghiên cứu hoặc chuẩn bị phần tổng quan tài liệu (Related Works) cho bài báo khoa học.

Current workflow 3-7 bước:
1. Gõ từ khóa tìm kiếm trên Google Scholar, arXiv, Semantic Scholar (10 phút).
2. Tải về hoặc mở danh sách 30-50 bài báo tiềm năng (15 phút).
3. Đọc lướt từng Abstract và Conclusion để phân loại bài có liên quan (45 phút).
4. Đọc sâu phần Methodology và Experiment để kiểm tra xem họ giải quyết bài toán gì, baseline nào (30 phút).
5. Ghi chép tóm tắt các phát hiện vào file Notion hoặc Excel (15 phút).
6. Viết bản tổng hợp so sánh các phương pháp (5 phút).

Bottleneck:
Bước 3 & 4 — Việc đọc lướt hàng chục abstract thủ công tiêu tốn rất nhiều năng lượng chú ý và rất dễ bỏ sót các paper đột phá nếu tác giả dùng từ khóa đồng nghĩa khác.

Impact:
Mất 120 phút/đợt tìm x 2-3 đợt/tuần = 4-6 tiếng/tuần; sinh viên dễ nản lòng và chỉ trích dẫn các paper quen thuộc bề mặt, làm giảm chất lượng học thuật của khóa luận.

Success metric:
- Giảm thời gian sàng lọc và lập bảng ma trận tài liệu từ 120 phút xuống dưới 20 phút.
- Tỷ lệ paper được AI gợi ý đáp ứng đúng tiêu chí nghiên cứu đạt >= 85%.

Non-AI alternative:
Sử dụng bộ lọc từ khóa Boolean (AND, OR, NOT) và sắp xếp theo số trích dẫn (citation count). Nhược điểm: Bỏ sót các công trình mới xuất bản trong 6-12 tháng gần nhất (ít citation).

AI hypothesis:
AI Semantic Search đọc hiểu câu hỏi nghiên cứu/hypothesis của sinh viên, quét kho arXiv/Semantic Scholar, trích xuất cấu trúc ma trận so sánh (Problem, Method, Dataset, Metrics, Limitations) và xếp hạng độ liên quan ngữ nghĩa.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 120 phút

[1 Tìm từ khóa Scholar/arXiv: 10'] 
→ [2 Tải danh sách 30-50 paper: 15'] 
→ [3 Đọc lướt Abstract/Conclusion loại bài lệch: 45']  <-- bottleneck
→ [4 Mở từng bài xem Method/Baseline: 30']  <-- bottleneck
→ [5 Ghi chép ma trận vào Notion: 15'] 
→ [6 Viết tóm tắt tổng quan: 5']

FUTURE STATE — 20 phút

[1 Nhập đề tài nghiên cứu & tiêu chí sàng lọc: 2'] 
→ [2 AI Semantic Search quét API arXiv/Semantic Scholar: 1'] 
→ [3 AI tự động trích xuất bảng ma trận so sánh 10 paper phù hợp nhất: 2'] 
→ [4 Sinh viên đọc ma trận so sánh có link đối chiếu PDF gốc: 10']  <-- human boundary
→ [5 Sinh viên chọn các paper ưng ý và xuất báo cáo Literature Review: 5']

Fallback: Nếu bảng tóm tắt có điểm chưa rõ hoặc nghi ngờ ảo giác, người dùng click trực tiếp vào link DOI/arXiv để đọc văn bản gốc của tác giả.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Theo dõi và xử lý cảnh báo từ nhiều công cụ AI/MLOps (Candidate #7)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là bài toán có quy trình kỹ thuật rất rõ ràng trong môi trường phát triển AI thực tế, nơi các kỹ sư MLE đang lãng phí 45-60 phút mỗi ngày chỉ để lọc các cảnh báo phân tán. Tình trạng sập run training không được phát hiện kịp thời gây lãng phí 2-3 tiếng GPU đắt đỏ cho mỗi sự cố. AI Agent với khả năng đọc hiểu ngữ nghĩa stack trace và gọi API tích hợp đa nguồn sẽ là giải pháp đắc lực giải quyết triệt để điểm nghẽn này.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. "Nếu nhóm chúng ta không có sẵn dữ liệu log MLOps thật từ các hệ thống server doanh nghiệp lớn trong buổi lab, liệu chúng ta có thể kiểm chứng và chạy thử nghiệm (dogfood) bài toán này một cách khả thi không?"
2. "Liệu một bộ lọc rule tĩnh (webhook lọc theo status code hoặc error level) có đủ giải quyết 70-80% cảnh báo thông thường mà không cần đầu tư xây dựng AI Agent tốn kém không?"
```

**AI phản biện Card (nếu có):**
- **Điểm yếu AI chỉ ra:** Nguy cơ bão thông báo (alert fatigue) khiến chi phí token API của LLM tăng vọt nếu phân tích mọi log; rào cản truy cập dữ liệu log nội bộ doanh nghiệp.
- **Tôi sửa gì:** Đưa vào cơ chế lọc phân tầng: Rule tĩnh lọc bỏ các warning vô hại trước (bước 1), chỉ kích hoạt AI Agent phân tích sâu đối với các ngoại lệ chưa rõ nguyên nhân hoặc lỗi sập hệ thống (bước 2); đồng thời giới hạn phạm vi thử nghiệm trên log lab học máy nội bộ.

---

### Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field (10 problems scan, top 3 cards chuẩn)
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge (Khớp với Candidate #7 trong thảo luận nhóm)
