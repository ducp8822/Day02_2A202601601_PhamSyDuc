
## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Tôi scan 10 problems từ trải nghiệm thật: học IELTS (Writing + Speaking), tập Gym, làm bài nhóm/thuyết trình, ghi chú buổi học. | Có nhiều candidate với actor và workflow khác nhau để đưa vào pool nhóm. |
| Pitch Problem Card | Tôi pitch bài IELTS Speaking không feedback vì bottleneck rất cụ thể (tự nghe lại + tự bắt lỗi mất 20-25'/bài, tổng 4h/tuần) và AI có thể giải trực tiếp. | Candidate của tôi được đưa vào pool 12 bài toán của nhóm. Sau convergence nhóm chọn RegWatch, tôi chấp nhận kết quả vote và tiếp tục đóng góp cho bài được chọn. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về scope của Citizen Agent: nếu mở rộng từ chung cư đến phường/xã thì dễ thành chatbot FAQ generic, cần thu hẹp actor và use case. | Câu hỏi giúp nhóm thấy rõ risk scope quá rộng của Citizen Agent khi so sánh với RegWatch. |
| Gom trùng / cluster | Tôi tham gia gom 12 candidates theo các pattern: Search/Knowledge, Document Processing, Compliance/High-risk Review, Repetitive Workflow và Real-time/Personal AI. | Nhóm nhìn ra điểm giống nhau giữa các candidate trước khi shortlist, thay vì vote ngay theo cảm giác. |
| Chọn candidate problem | Tôi vote Citizen Agent vì thấy pain người dân hỏi đáp dễ hiểu và dễ demo hơn. Tuy nhiên RegWatch thắng 6-4-2. | Tôi chấp nhận kết quả và chuyển sang đóng góp cho RegWatch. |
| Validation / research | Tôi cùng nhóm kiểm tra các claim trong concept RegWatch, tìm nguồn SBV/NHNN, VBPL và so sánh với các RegTech pattern hiện có. | Nhóm bỏ hoặc hạ mức nhiều claim quá mạnh, thu hẹp RegWatch vào scoped pilot cho Compliance ngân hàng. |
| Workflow nhóm | Tôi góp ý vào current workflow và future workflow, đặc biệt phần xác định human boundary ở các bước quyết định. | Workflow được phân tách rõ hơn giữa Rule, retrieval, AI reasoning và human approval. |
| Problem Statement | Tôi góp phần làm rõ actor và user need khi chuyển từ Problem Statement v0 sang v1, đảm bảo problem được framing từ góc người dùng chứ không phải từ solution. | V1 cụ thể hơn về actor (Compliance Department) và tách rõ pain thật (manual semantic cross-check) khỏi solution (Agent tổng hợp luật). |
| Rule / Workflow / Agent | Tôi tham gia thảo luận so sánh 3 mức. Từ góc nhìn user need, tôi thấy Workflow cố định có thể đủ cho nhiều case, nhưng đồng ý rằng bounded Agent có giá trị khi cần follow reference nhiều tầng. | Nhóm chọn Bounded Agent / Agentic Workflow with HITL thay vì gọi chung chung là "AI Agent". |
| Decision | Tôi ủng hộ GO dưới dạng scoped pilot, vì chưa có production evidence từ Compliance team thật. | Decision có điều kiện rõ: annotated test set, Compliance reviewer, traceability và fallback về rule/manual workflow nếu pilot không đạt. |

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI để mở rộng scan theo các lăng kính lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác. | Giúp tôi nghĩ ra thêm problems từ bối cảnh IELTS và làm bài nhóm mà ban đầu chưa nghĩ tới. | Một số gợi ý quá rộng không focus vào ý chính, trả lời lan man chung chung nhưng không rõ được vấn đề. | Tôi chỉ giữ problems có actor rõ, workflow vẽ được và dấu hiệu thật từ trải nghiệm cá nhân. |
| Problem Card | Dùng AI để kiểm tra Problem Card IELTS Speaking có thiếu field nào không (actor, metric, boundary, non-AI alternative). | Giúp metric bớt mơ hồ: tách rõ thời gian tự review (20-25'/bài) khỏi tổng thời gian luyện. | AI dễ đề xuất metric kiểu "cải thiện band score" dù đó không đo được trong ngắn hạn. | Tôi chuyển sang metric có cách đo rõ hơn: thời gian review/bài, có/không có feedback ngay. |
| Group convergence | Dùng AI sau khi nhóm đã có candidate pool để nhìn pattern giữa 12 problems. | Giúp diễn đạt cluster và trade-off rõ hơn. | AI có xu hướng đánh giá cao candidate nghe "AI" hơn. | Tôi quay về tiêu chí actor, workflow, evidence, impact, scope và khả năng pilot. |
| Workflow | Dùng AI để hỗ trợ chuyển workflow từ dạng text thành sơ đồ rõ ràng hơn. | Giúp tách các bước có input/output rõ ràng. | AI dễ gộp nhiều bước thành một ô "AI xử lý". | Tôi tách bước nào Rule đủ, bước nào cần AI, bước nào phải có người review. |
| Research | Dùng AI/search hỗ trợ tìm các solution hiện có cho regulatory intelligence. | Giúp tìm pattern từ Thomson Reuters, LexisNexis, CUBE, Regology, AscentAI. | Một số câu trả lời lặp lại claim marketing hoặc biến product claim thành fact. | Tôi chỉ giữ claim có nguồn, còn metric được ghi rõ là pilot target chứ không phải kết quả đã đạt. |
| Problem Statement | Dùng AI như reviewer để hỏi field nào trong v0 còn mơ hồ. | Giúp nhận ra "Agent tổng hợp luật" chưa phải Problem Statement vì chưa nói rõ actor và workflow. | AI dễ viết problem quá rộng. | Tôi cùng nhóm giữ scope ở Compliance ngân hàng và regulatory change liên quan NHNN. |
| Rule / Workflow / Agent | Dùng AI để stress-test ba mức. | Giúp làm rõ rằng fixed Workflow đủ cho happy path nhưng reference traversal có thể phát sinh branching. | AI thường thiên về Agent chỉ vì bài có nhiều tools. | Nhóm chỉ chọn Agent ở nơi cần dynamic orchestration, còn lại dùng Rule/Workflow. |
| Decision | Dùng AI để kiểm tra pilot metric và failure mode. | Giúp bổ sung false negative, false positive, citation traceability vào risk analysis. | AI có xu hướng biến target pilot thành lời hứa về performance. | Tôi giữ các con số dưới dạng target và chọn GO scoped pilot, không production rollout. |


## 3. Reflection câu hỏi mở

### Tôi học được gì khi nghe các problem của các thành viên khác?

Điều rõ nhất tôi học được là một problem có workflow rõ, actor rõ và metric đo được sẽ luôn mạnh hơn một problem chỉ nghe "hay" hoặc "dùng AI nhiều".

Ban đầu tôi nghĩ Citizen Agent dễ hiểu và dễ demo hơn nên mạnh hơn. Nhưng khi so sánh với RegWatch, tôi thấy RegWatch có workflow nhiều bước hơn, bottleneck cụ thể hơn (semantic cross-check), và human boundary rõ hơn. Citizen Agent tuy pain thật nhưng scope quá rộng nếu không thu hẹp.

Driver Drowsiness có impact về an toàn rất lớn, nhưng cần camera stream, dataset video và safety validation vượt phạm vi lab.

### Nhóm có lúc nào bị solution-first không?

Có. Ngay tên ban đầu đã là "Agent tổng hợp luật", nên nhóm có xu hướng mặc định solution phải là Agent.

Sau khi tách workflow, nhóm mới xác định phần nào thật sự cần Agent (reference traversal nhiều tầng) và phần nào Rule hoặc Workflow cố định đã đủ.

### Tôi có thay đổi ý kiến sau khi bị challenge không?

Có. Ban đầu tôi vote Citizen Agent vì thấy user-facing chatbot dễ hiểu hơn. Nhưng sau khi nhóm so sánh data, scope, validation và workflow, tôi thấy RegWatch có problem quality tốt hơn: actor rõ, workflow rõ, data public có thể bắt đầu, risk cao nhưng kiểm soát được trong pilot.

Tôi chấp nhận kết quả vote và chuyển sang đóng góp cho RegWatch thay vì cố bảo vệ ý kiến ban đầu.

### Tôi đóng góp gì thật sự vào artifact cuối?

Đóng góp chính của tôi là phần **user need framing**.

Tôi tập trung vào việc đảm bảo problem được framing từ góc người dùng (Compliance Department) chứ không phải từ góc solution (Agent tổng hợp luật). Khi viết Problem Statement, tôi nhấn mạnh phải bắt đầu từ pain thật (manual semantic cross-check) thay vì từ sản phẩm muốn build.

### Điều khó nhất khi viết Problem Statement là gì?

Khó nhất là tách **problem** khỏi **solution**.

"Agent tổng hợp luật" nghe giống một product idea hơn là problem. Khi viết lại, nhóm phải bỏ từ Agent ra khỏi phần lõi và quay về actor: Compliance Department phải xử lý regulatory change bằng cách tìm, cross-check và map ảnh hưởng giữa nhiều văn bản và nhiều phòng ban.

### Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

Nếu làm lại, tôi sẽ challenge sớm hơn ở phần **validation với người thật trong domain**.

Desk research đủ để xác nhận regulatory intelligence là pain có thật, nhưng không thay thế được việc hiểu một Compliance team tại ngân hàng Việt Nam đang thực sự làm gì. Nếu có dữ liệu này sớm, baseline, workflow và pilot metric của nhóm sẽ chắc hơn.



## 4. Tôi tự giải thích mạch bài toán của nhóm

### Problem

Khi NHNN hoặc cơ quan có thẩm quyền ban hành hoặc cập nhật một quy định, Compliance Department không chỉ cần "đọc văn bản mới".

Họ còn phải xác định:

- văn bản nào liên quan;
- quy định nào bị sửa đổi, thay thế hoặc dẫn chiếu;
- obligation nào thay đổi;
- policy/process nội bộ nào bị ảnh hưởng;
- phòng ban nào phải hành động;
- mức độ rủi ro;
- ai phải duyệt và ai phải thực thi.

Pain chính là **manual semantic cross-check và impact mapping**, không phải thiếu một chatbot hỏi đáp luật.

### Workflow

Current workflow có thể tóm tắt:

```text
Theo dõi nguồn pháp lý
→ phát hiện văn bản mới
→ đọc thủ công
→ tìm văn bản liên quan
→ cross-check thay đổi
→ đánh giá impact/risk
→ viết báo cáo
→ xin phê duyệt
→ phân công phòng ban
→ cập nhật policy/process
```

Bottleneck lớn nhất nằm giữa bước tìm văn bản liên quan và đánh giá impact, vì Compliance phải nối nhiều thông tin phân tán và giữ được traceability.

Future workflow của RegWatch:

```text
Source monitoring
→ parse + metadata
→ hybrid retrieval
→ legal relationship graph
→ impact/conflict analysis
→ risk prioritization
→ Compliance review
→ C-level/BoD approval
→ action plan
→ departmental implementation
```

### Metric

Pilot cần đo ít nhất:

- relevant provision recall;
- alert relevance/precision;
- tỷ lệ material claim có traceable source;
- human initial-review effort;
- critical miss trong controlled test set.

Các target như ≥90% recall, ≥80% alert relevance và giảm ≥50% initial review effort chỉ là **điều kiện đánh giá pilot**, chưa phải kết quả hệ thống đã đạt.

### Boundary

AI có thể:

- monitor;
- retrieve;
- follow references;
- compare;
- flag conflict;
- đánh giá impact sơ bộ;
- rank risk;
- draft report/action.

AI không được:

- đưa ra legal conclusion cuối cùng;
- tự phê duyệt risk response;
- tự sửa policy;
- tự thay đổi core banking/rule production;
- tự phát hành thông báo chính thức.

Compliance, C-level/BoD và các department owner vẫn giữ quyền quyết định tương ứng.

### Vì sao Rule không đủ?

Rule hữu ích cho số hiệu văn bản, ngày hiệu lực, metadata, exact references, keyword watch, owner mapping đã biết.

Nhưng Rule khó xử lý trường hợp semantic impact không dùng đúng cùng keyword hoặc obligation bị ảnh hưởng gián tiếp qua nhiều văn bản.

### Vì sao Workflow cố định chưa hoàn toàn đủ?

Một Workflow cố định giải được happy path:

```text
ingest → retrieve → compare → draft → review
```

Nhưng có trường hợp:

```text
Văn bản A sửa Điều X của B
→ B dẫn chiếu C
→ C lại bị thay thế một phần bởi D
```

Lúc đó bước tiếp theo phụ thuộc vào thứ vừa tìm được. Hệ thống có thể phải follow thêm reference, query graph, chuyển sang semantic search, hoặc hỏi reviewer khi confidence thấp.

### Vì sao không chọn fully autonomous Agent?

Vì đây là legal/compliance. False negative có thể làm bỏ sót obligation; hallucination có thể tạo ra claim pháp lý không tồn tại. Autonomy phải bị giới hạn.

### Vì sao chọn Bounded Agent / Agentic Workflow?

Đây là mức cân bằng: phần deterministic vẫn deterministic, phần dynamic mới dùng Agent, human vẫn nằm trong loop. Giữ được auditability, source traceability, approval và rollback.

### Vì sao GO nhưng chỉ scoped pilot?

Nhóm có actor tương đối rõ, workflow có thể mô tả, nguồn public, architecture hypothesis có thể prototype, success metric có thể đo, và fallback manual/rule-based.

Nhưng chưa có đủ production evidence từ Compliance team thực tế. Vì vậy: **GO — scoped pilot**, không phải production rollout.

---

## 5. Rubric self-assessment cá nhân

| Phần | Tự đánh giá | Evidence |
|---|---|---|
| Scan problem + top 3 Problem Cards | Tốt | Có 10 problems cá nhân, top 3 và 3 full Problem Cards; IELTS Speaking là card tôi pitch. |
| Pitch + challenge | Tốt | Tôi pitch IELTS Speaking và challenge scope của Citizen Agent. |
| Tham gia group convergence | Tốt | Tôi tham gia cluster, scoring và vote trong pool 12 candidates; vote cuối là RegWatch 6, Citizen Agent 4, Driver Drowsiness CV 2. |
| Reflection cá nhân | Tốt | Có mô tả vai trò, điểm AI hữu ích/sai/hời hợt, điều tôi thay đổi sau challenge và limitation. |
| Kiểm tra hiểu bài cá nhân | Tốt | Tôi giải thích được problem → workflow → metric → boundary → Rule/Workflow/Agent → decision của RegWatch. |
