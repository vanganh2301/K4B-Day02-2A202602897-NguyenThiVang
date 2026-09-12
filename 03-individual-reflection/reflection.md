# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- **Họ và tên:** Nguyễn Thị Vàng
- **Mã học viên:** 2A202602897
- **Nhóm:** Nhóm 02 — EasyMessage
- **Candidate problem nhóm chọn:** Những người làm việc/học tập theo dự án thường xuyên bị lỡ các công việc hoặc thông tin quan trọng do bị trôi tin nhắn trong các nhóm chat có quá nhiều "tiếng ồn" (tin nhắn rác, thảo luận không liên quan).

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| **Scan cá nhân** | Quét 10 bài toán thực tế; hoàn thiện Top 3 Problem Cards chi tiết: #7 (Cảnh báo MLOps phân tán), #8 (Lộ trình kết hợp buýt - metro) và #9 (Tổng hợp tài liệu Literature Review). | Cung cấp cho nhóm 3 ứng viên chất lượng cao; đóng góp góc nhìn đa dạng từ kỹ thuật MLOps đến di chuyển và nghiên cứu học thuật. |
| **Pitch Problem Card** | Trình bày Problem Card #1 (Theo dõi và xử lý cảnh báo từ nhiều công cụ AI/MLOps — Candidate #7) trong 2 phút; nêu rõ số liệu baseline 45-60 phút/ngày và rủi ro lãng phí hàng triệu đồng khi sập job GPU. | Được nhóm thảo luận sôi nổi về domain kỹ thuật sâu; giúp nhóm cân nhắc giữa bài toán chuyên biệt (MLOps) và bài toán phổ quát (Group Chat). |
| **Challenge bài của bạn khác** | Đặt câu hỏi chất vấn bạn Thành Đạt ở Candidate #4: "Làm sao định nghĩa được thế nào là 'tin rác' một cách khách quan, và giải quyết bài toán quyền riêng tư ra sao khi AI đọc tin nhắn?" | Buộc nhóm phải định nghĩa lại ranh giới dữ liệu và không để AI đọc các kênh riêng tư. |
| **Gom trùng / cluster** | Cùng nhóm phân loại 18 candidate ideas thành 4 cụm logic A, B, C, D; trực tiếp đề xuất gộp các bài toán chat, email và cảnh báo vào Cụm A (Quản lý thông tin đa kênh). | Giúp nhóm nhìn ra mẫu hình chung (pattern) nhanh chóng, giảm từ 18 ý tưởng phân tán về 4 cụm rõ ràng. |
| **Chọn candidate problem** | Ban đầu bảo vệ ý tưởng #7 (Cảnh báo MLOps phân tán), nhưng sau khi lắng nghe nhóm phản biện về việc khó thu thập log thật trong lab, tôi đã đồng thuận hội tụ về #4. | Giúp nhóm đạt được sự đồng thuận 100% dựa trên tiêu chí domain quen thuộc và khả năng tự kiểm chứng (dogfood). |
| **Validation / research** | Trực tiếp tham gia khảo sát 6 học viên lớp K4B và phỏng vấn 1 bạn làm trưởng nhóm CLB; tìm kiếm và phân tích tài liệu tính năng của Slack AI và Discord. | Thu thập được bằng chứng thực tế (83.3% người dùng gặp pain point); nhận ra khoảng trống thị trường của các app như Zalo/Discord. |
| **Workflow nhóm** | Phối hợp cùng bạn Thắng rà soát Current State (7 bước) và Future State (6 bước); chỉ ra điểm nghẽn ở khâu đọc lướt thủ công và đề xuất bổ sung bước Human Review bắt buộc. | Đảm bảo quy trình tương lai có ranh giới kiểm soát chất lượng rõ ràng, không phụ thuộc mù quáng vào AI. |
| **Problem Statement** | Đảm nhận vai trò Writer chính: chắp bút soạn thảo Problem Statement v0; sau đó tiếp thu phản biện để nâng cấp lên bản v1 với Success Metric định lượng cụ thể. | Tạo ra bản Problem Statement v1 chặt chẽ, có số đo trước/sau rõ ràng ($\ge 85\%$ tag đúng, thời gian xử lý $\le 3$ phút). |
| **Rule / Workflow / Agent** | Phân tích 5 câu hỏi chốt cùng nhóm; lập luận vì sao Rule từ khóa cứng không xử lý được ngôn ngữ tự nhiên và đề xuất mô hình lai: khung Workflow bao quanh lõi Agent. | Nhóm thống nhất được phương án kỹ thuật hợp lý: chỉ dùng Agent ở bước phân tích context & gợi ý tag, các bước còn lại dùng Rule/Script. |
| **Decision** | Cùng nhóm chốt quyết định "Go"; đóng góp ý kiến thiết kế bài test pilot nhỏ nhất trên 50 tin nhắn thật và đưa ra tiêu chí rollback an toàn. | Bản kế hoạch hành động có tính khả thi cao, có lộ trình thử nghiệm rõ ràng và phương án rút lui nếu AI hoạt động dưới 60%. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người trực tiếp chắp bút biên soạn toàn bộ cấu trúc Problem Statement v1 và bản so sánh Rule/Workflow/Agent, trong đó dấu ấn rõ nhất là việc thiết lập ranh giới Boundary nghiêm ngặt: AI tuyệt đối không được tự động phát tán tin nhắn hay tạo task khi chưa có sự xác nhận của người dùng (Human-in-the-loop).
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan** | Gợi ý thêm các điểm nghẽn tiềm ẩn trong quy trình học tập và làm lab AI của sinh viên. | Mở rộng góc nhìn về các thao tác lặp lại trong môi trường kỹ thuật (log trace, format báo cáo). | Gợi ý nhiều ý tưởng viển vông kiểu "AI tự viết code đồ án thay người", không phải pain point quy trình thực tế. | Lọc bỏ hoàn toàn các ý tưởng vi phạm tính liêm chính học thuật; chỉ giữ lại các vấn đề về quản lý thời gian và tài liệu. |
| **Problem Card** | Tham khảo cách phân rã thời gian cho từng bước trong workflow đọc paper khoa học. | Cung cấp khung cấu trúc các bước đọc paper chuẩn (Abstract $\rightarrow$ Method $\rightarrow$ Experiment). | Ước lượng thời gian quá ngắn (cho rằng đọc hiểu paper chỉ mất 15 phút), không sát thực tế sinh viên. | Tự bấm giờ và điều chỉnh lại baseline lên 90-120 phút dựa trên trải nghiệm thật của bản thân và các bạn trong nhóm. |
| **Workflow** | Nhờ AI chuyển đổi mô tả quy trình dạng gạch đầu dòng thành sơ đồ Mermaid trực quan. | Sinh mã Mermaid nhanh, bố cục hình khối chuẩn và tiết kiệm thời gian vẽ tay. | AI tự động gộp bước suy luận của Agent với bước gửi tin nhắn thành một khối duy nhất, bỏ qua sự can thiệp của con người. | Tách đôi thành 2 bước riêng biệt: bước AI gợi ý và bước Human Review bắt buộc, đồng thời bổ sung nhánh Fallback khi AI đoán sai. |
| **Research** | Tìm kiếm các giải pháp và công cụ hiện có trên thị trường xử lý vấn đề quá tải thông báo chat. | Chỉ ra nhanh chóng hai sản phẩm đầu ngành là Slack AI và Microsoft Teams Copilot. | Bịa ra số liệu thống kê không có thật ("tiết kiệm 47.5% thời gian làm việc") mà không kèm liên kết nguồn kiểm chứng. | Loại bỏ các số liệu bịa đặt; tự truy cập tài liệu chính thức của Slack và Microsoft để trích dẫn tính năng và link đối soát thực. |
| **Problem Statement** | Đóng vai trò phản biện (Devil's Advocate) để tìm ra các điểm mơ hồ trong bản thảo v0. | Chỉ ra rất chính xác việc trường `Impact` còn mang tính cảm tính và `Boundary` chưa làm rõ quyền riêng tư dữ liệu chat. | AI đề xuất mở rộng bài toán sang xử lý tự động toàn bộ tin nhắn đa kênh (Scope Creep — phình to phạm vi). | Giữ vững định hướng thu hẹp phạm vi: chỉ tập trung vào một tác vụ then chốt là phân tích ngữ cảnh dự án để gợi ý tag đúng người phụ trách. |
| **Rule / Workflow / Agent** | Hệ thống hóa 5 câu hỏi chốt để kiểm tra mức độ phù hợp của từng cấp độ công nghệ. | Giúp cấu trúc bảng so sánh Rule vs Workflow vs Agent một cách rõ ràng và khoa học. | Có xu hướng "Agent hóa" mọi bước trong quy trình một cách không cần thiết, làm tăng chi phí và rủi ro ảo giác. | Kéo về thực tế: chỉ dùng Agent tại bước cần gọi công cụ fetch context ngoài; các bước gom tin, gửi thông báo giữ nguyên ở mức Rule và Workflow. |
| **Decision** | Gợi ý các kịch bản thử nghiệm nhỏ (pilot) và tiêu chí dừng cuộc chơi (rollback). | Cung cấp ý tưởng đo lường tỷ lệ gợi ý đúng và tần suất chỉnh sửa của con người. | Đề xuất pilot trên dữ liệu giả lập (synthetic data) thiếu tính ngẫu nhiên của ngôn ngữ đời thường. | Quyết định pilot trên dữ liệu thật của 1 nhóm đồ án đang hoạt động với 50 tin nhắn công việc phát sinh tự nhiên. |

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
Buổi lab thực hành hôm nay đã đem lại cho tôi một bước chuyển đổi tư duy rất lớn từ việc "nghĩ về công nghệ AI" sang "đào sâu vào bài toán thực tế". Khi lắng nghe phần trình bày top 3 của các bạn trong nhóm, tôi nhận ra mỗi người đều có những nỗi đau công việc rất chân thật, nhưng một đề tài tốt cho nhóm bắt buộc phải là bài toán mà cả nhóm cùng hiểu domain và có khả năng tự kiểm chứng (dogfood) ngay lập tức. Bản thân tôi ban đầu rất tâm đắc với bài toán cảnh báo MLOps của mình, nhưng sau khi bị nhóm chất vấn thẳng thắn về tính khả thi của việc lấy dữ liệu log thực tế trong phòng lab, tôi đã vui vẻ thay đổi ý kiến để hội tụ về bài toán trôi tin nhắn nhóm chat. Trong quá trình thảo luận, nhóm tôi cũng có thời điểm bị cuốn vào bẫy "solution-first", khao khát xây dựng một Agent toàn năng tự động đọc và trả lời thay người dùng cho đến khi các câu hỏi worksheet kéo chúng tôi về mặt đất. Với vai trò Writer, dấu tay rõ nhất của tôi trong bản nộp cuối là việc chắt lọc ngôn từ và thiết lập ranh giới kiểm soát rủi ro (Boundary) cực kỳ nghiêm ngặt: kiên quyết không cho phép AI tự động gửi tin nhắn hay tạo task mà bắt buộc phải có bước phê duyệt của con người. Đối với tôi, khâu khó khăn nhất chính là việc xác định Boundary và Success Metric — làm sao để đo lường được một khái niệm định tính như "tiếng ồn" thành con số tỷ lệ tag đúng 85% và thời gian phản hồi dưới 3 phút. AI đóng vai trò như một người phản biện sắc sảo chỉ ra những chỗ mơ hồ trong bản v0, nhưng chính nhận định thực tế của tôi và các đồng đội mới là yếu tố quyết định để tạo nên một bản thiết kế khả thi. Nếu được làm lại lab này, tôi sẽ thúc đẩy nhóm thực hiện phỏng vấn sâu thêm 1-2 giảng viên hoặc quản lý dự án doanh nghiệp để có cái nhìn toàn diện hơn về góc độ phân quyền thông tin. Nhìn chung, bài học lớn nhất mà tôi khắc ghi sau lab là: một giải pháp AI xuất sắc không nằm ở việc sử dụng mô hình phức tạp nhất, mà nằm ở việc thấu hiểu tường tận điểm nghẽn quy trình và dũng cảm đặt ra những ranh giới an toàn cho công nghệ.
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
