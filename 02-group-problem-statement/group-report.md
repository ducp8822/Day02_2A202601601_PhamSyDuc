# Group Report — Day 02

## 1. Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|---:|---|---|---|
| 1 | Vũ Văn Phong | 2A202601647 | Workflow analysis / AI-fit / synthesis |
| 2 | Nguyễn Đức Sơn | 2A202601485 | Citizen Agent candidate / user scope challenge |
| 3 | Nguyễn Thế Anh | 2A202601791 | Document processing candidate / validation notes |
| 4 | Nguyễn Quang Vinh | 2A202601517 | Problem owner / RegWatch domain synthesis |
| 5 | Hà Duy Anh | 2A202601511 | Repetitive workflow candidate / feasibility |
| 6 | Phạm Thế Dũng | 2A202601985 | Learning-resource candidate / survey notes |
| 7 | Hoàng Lê Minh | 2A202601653 | Deadline-learning candidate / documentation |
| 8 | Nguyễn Huy Nghĩa | 2A202601943 | HR workflow candidate / metric thinking |
| 9 | Phạm Sỹ Đức | 2A202601601 | IELTS candidate / user need framing |
| 10 | Đoàn Nhật Nam | 2A202601123 | AI guardrail / hallucination challenge |
| 11 | Phạm Văn Lưu | 2A202601857 | Risk & safety challenge |
| 12 | Trần Quốc Hùng | 2A202601683 | Legal document review candidate / final review |

---

## 2. Candidate Problems — 12 thành viên

Mỗi thành viên đưa một candidate chính. Một số thành viên có brainstorm thêm alternatives, nhưng group convergence chỉ lấy một candidate chính/người để tránh bảng bị loãng.

| # | Người đưa ra | Candidate problem | Actor | Bottleneck | Cảm nhận nhanh |
|---:|---|---|---|---|---|
| 1 | Vũ Văn Phong | QA và chuẩn hóa phụ đề do AI tạo cho video short-form tiếng Việt có nội dung chuyên ngành. | Technical Video Editor / Asset Producer | Phải nghe và đối chiếu subtitle với audio/video gốc cue-by-cue để sửa từ nghe sai, terminology, số liệu, ngày tháng, tỷ lệ, timestamp. | Workflow rõ, AI có thể hỗ trợ nhưng human review vẫn cần thiết. |
| 2 | Nguyễn Đức Sơn | AI Agent/Chatbot giúp người dân và ban quản lý/chính quyền tra cứu thông báo, thủ tục hành chính, quy định, FAQ. | Người dân, ban quản lý, cán bộ hỗ trợ | Thông tin phân tán, người dân hỏi lại nhiều câu giống nhau, tìm thủ tục hoặc thông báo mất thời gian. | Dễ hiểu, dễ demo, nhưng scope rộng. |
| 3 | Nguyễn Thế Anh | Phân loại hồ sơ scan theo danh mục thông tin và chuyển tài liệu quét thành dữ liệu/văn bản số. | Nhân viên xử lý hồ sơ | Tài liệu scan khó tìm kiếm, cần phân loại và nhập/chuyển nội dung thủ công. | Có thể kết hợp OCR + workflow. |
| 4 | Nguyễn Quang Vinh | Agent tổng hợp luật, phát hiện thay đổi và thông báo cập nhật; hỗ trợ các phòng ban ngân hàng xử lý văn bản pháp luật/quy định mới. | Compliance Department và các phòng ban liên quan trong ngân hàng | Phải theo dõi, đọc, so sánh, xác định phòng ban ảnh hưởng, đánh giá rủi ro, truyền đạt và theo dõi thực thi. | Candidate phát triển thành RegWatch. |
| 5 | Hà Duy Anh | Đăng/cập nhật thông tin sản phẩm hoặc căn hộ lên nhiều trang mỗi khi có tin mới hoặc thay đổi. | Sale / Marketing bất động sản | Copy-paste 5-6 lần/ngày giữa nhiều kênh, dễ lệch giá, diện tích hoặc thông tin. | Workflow lặp lại, nhiều phần rule được. |
| 6 | Phạm Thế Dũng | Tạo nơi tổng hợp tài nguyên học tập, giúp tiết kiệm thời gian và theo dõi tiến độ. | Học viên | Tài liệu và progress nằm rải rác nhiều nguồn. | Hữu ích nhưng dễ thành dashboard chung. |
| 7 | Hoàng Lê Minh | AI tổng hợp deadline, thông báo và sự kiện quan trọng trong khóa học, đồng thời hỗ trợ học tập. | Học viên | Thông báo/deadline nằm rải rác và dễ bị bỏ sót. | Pain thật, scope cần thu hẹp. |
| 8 | Nguyễn Huy Nghĩa | AI Workflow hỗ trợ Talent Acquisition đọc CV, trích xuất kỹ năng và viết tóm tắt gửi Hiring Manager. | Talent Acquisition / HR | Phải đọc và tóm tắt số lượng lớn CV thủ công. | Workflow rõ, có risk về bias/privacy. |
| 9 | Phạm Sỹ Đức | Hỗ trợ tự luyện IELTS Speaking khi không có partner hoặc feedback tức thì. | Học viên IELTS | Mất thời gian tự review ngữ pháp, từ vựng, fluency và đôi khi tự đánh giá sai. | AI fit khá tốt nhưng metric cần rõ. |
| 10 | Đoàn Nhật Nam | Tổng hợp thông tin từ nhiều JD và đề xuất kỹ năng/project phù hợp để cải thiện CV. | Người xin việc | Phải đọc hàng trăm JD và xác định skill gap; AI không được hallucinate kỹ năng/dự án chưa từng làm. | Guardrail rất quan trọng. |
| 11 | Phạm Văn Lưu | Nhận diện và cảnh báo sớm dấu hiệu ngủ gật của tài xế đường dài bằng Computer Vision AI. | Tài xế xe tải, xe khách, container, đặc biệt ca đêm | Microsleep 2-3 giây có thể xảy ra ngoài ý thức và gây tai nạn nghiêm trọng. | Impact rất cao, nhưng validation khó. |
| 12 | Trần Quốc Hùng | Rà soát hợp đồng theo mẫu cũ so với Luật/Nghị định mới. | Legal Executive / HR | Cross-check thủ công hợp đồng 15-20 trang với quy định mới, mất 30-45 phút/hợp đồng và dễ bỏ sót lỗi nhỏ. | Gần với legal/compliance, scope hẹp hơn RegWatch. |

---

## 3. Group Convergence

### 3.1 Cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Search / Knowledge / Information Access | Nguyễn Đức Sơn, Phạm Thế Dũng, Hoàng Lê Minh | Thông tin nằm phân tán, user mất thời gian tìm, hỏi lại hoặc tổng hợp. | Nhiều bài có thể bắt đầu bằng search/FAQ/dashboard, cần thu hẹp để tránh generic chatbot. |
| B — Document Processing / Knowledge Extraction | Nguyễn Thế Anh, Nguyễn Huy Nghĩa, Đoàn Nhật Nam | Đọc nhiều tài liệu bán cấu trúc và trích thông tin quan trọng. | AI có ích nhưng phải có schema, privacy và anti-hallucination. |
| C — Compliance / Content QA / High-risk Review | Nguyễn Quang Vinh, Trần Quốc Hùng, Vũ Văn Phong | Output sai hoặc bỏ sót có hậu quả cao nên cần traceability + human review. | Đây là cluster có boundary và success metric rõ nhất. |
| D — Repetitive Workflow Automation | Hà Duy Anh | Lặp thao tác giữa nhiều kênh, dữ liệu dễ lệch nếu copy thủ công. | Rule/workflow có thể giải phần lớn. |
| E — Real-time / Personal AI | Phạm Sỹ Đức, Phạm Văn Lưu | AI phản hồi theo thời gian thực hoặc gần thời gian thực cho người dùng cá nhân. | Driver drowsiness có impact cao nhưng safety validation nặng. |

### 3.2 Shortlist

Sau challenge, nhóm shortlist đúng 3 candidate để chấm sâu hơn.

| Candidate | Người đưa ra | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|---|
| Citizen Agent | Nguyễn Đức Sơn | Actor rộng nhưng dễ hiểu; pain tìm thông tin/thủ tục lặp lại; có thể pilot bằng FAQ + document retrieval. | Scope "chung cư → khu dân cư → phường → xã" quá rộng; dễ thành chatbot FAQ generic. |
| RegWatch | Nguyễn Quang Vinh | Actor rõ là Compliance ngân hàng; workflow có nhiều bước; impact cao; có nguồn pháp lý công khai; có human boundary rõ. | Cần tránh claim quá mức về legal accuracy; phải kiểm citation/traceability. |
| Driver Drowsiness CV | Phạm Văn Lưu | Impact an toàn tính mạng rất rõ; actor và failure mode cụ thể; có tín hiệu real-time. | Cần camera stream, dataset video, threshold calibration, safety-critical validation; khó pilot sâu trong lab. |

### 3.3 Scoring

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| RegWatch | 5 | 5 | 4 | 5 | 4 | 5 | 4 | 32 |
| Citizen Agent | 5 | 4 | 4 | 4 | 5 | 4 | 4 | 30 |
| Driver Drowsiness CV | 5 | 5 | 5 | 5 | 3 | 4 | 3 | 30 |

Điểm của Driver Drowsiness cao ở impact, nhưng bị trừ ở khả năng làm pilot vì cần dữ liệu video thực tế, thiết bị camera và kiểm định safety. Citizen Agent khả thi hơn, nhưng nếu không thu hẹp sẽ giống một FAQ chatbot. RegWatch không thắng vì "dùng AI nhiều" mà vì problem quality tốt: actor rõ, workflow rõ, risk cao, data public có thể bắt đầu, và có thể so sánh No AI / Rule / Workflow / Agent rất rõ.

### 3.4 Vote

| Thành viên | Vote | Lý do ngắn |
|---|---|---|
| Vũ Văn Phong | RegWatch | Workflow + AI-fit rõ, có human boundary. |
| Nguyễn Đức Sơn | Citizen Agent | Gần với pain người dân hỏi đáp lặp lại. |
| Nguyễn Thế Anh | RegWatch | Gần nhóm document processing và legal extraction. |
| Nguyễn Quang Vinh | RegWatch | Problem owner, hiểu context compliance. |
| Hà Duy Anh | RegWatch | Workflow nhiều bước và có thể pilot. |
| Phạm Thế Dũng | Citizen Agent | Dễ demo và gần bài toán tìm thông tin học tập/cộng đồng. |
| Hoàng Lê Minh | Citizen Agent | Pain thông báo/deadline phân tán tương tự. |
| Nguyễn Huy Nghĩa | RegWatch | Có document review + impact mapping. |
| Phạm Sỹ Đức | Citizen Agent | User-facing chatbot dễ hiểu hơn. |
| Đoàn Nhật Nam | Driver Drowsiness CV | Safety impact cao, cần guardrail nghiêm. |
| Phạm Văn Lưu | Driver Drowsiness CV | Problem owner của candidate safety. |
| Trần Quốc Hùng | RegWatch | Gần legal review và cập nhật hợp đồng/quy định. |

**Kết quả vote:** RegWatch 6, Citizen Agent 4, Driver Drowsiness CV 2. Total = 12.

### 3.5 Selected candidate

Nhóm chọn **RegWatch — Hệ thống giám sát thay đổi pháp lý và hỗ trợ Compliance trong lĩnh vực Ngân hàng - Tài chính**.

**Vì sao chọn RegWatch:**

1. Actor rất rõ: Compliance Department tại ngân hàng.
2. Workflow hiện tại có thể mô tả theo từng bước.
3. Pain xảy ra khi NHNN hoặc cơ quan có thẩm quyền ban hành/cập nhật văn bản.
4. Bỏ sót obligation hoặc cập nhật muộn có thể tạo compliance risk.
5. Có nguồn dữ liệu tương đối khả dụng: SBV/NHNN, VBPL, văn bản công khai.
6. Có thể tạo pilot nhỏ trên một nhóm văn bản hạn chế.
7. AI intervention point rõ: retrieval, impact analysis, conflict detection, risk prioritization.
8. Human-in-the-loop có thể giảm risk.
9. Bài đủ phức tạp để so sánh manual, Rule, Workflow, Agent.
10. Có thể đánh giá bằng time-to-detect, recall/precision, traceability và human review effort.

**Vì sao không chọn Citizen Agent:** pain thật và dễ demo, nhưng scope từ chung cư tới phường/xã và thủ tục hành chính quá rộng. Dữ liệu có nhiều authority khác nhau; success metric khó đồng nhất. Nếu không thu hẹp, bài dễ trở thành FAQ chatbot generic.

**Vì sao không chọn Driver Drowsiness CV:** impact an toàn rất cao, nhưng cần camera stream, dataset video, real-time inference, threshold calibration và đánh giá trong nhiều điều kiện ánh sáng/góc camera/rung xe. False negative có safety consequence, nên pilot thực tế vượt phạm vi lab.

**Disagreement:** Một số thành viên nghiêng về Driver Drowsiness vì tác động tới an toàn tính mạng; một số khác nghiêng về Citizen Agent vì dễ hiểu và dễ demo. Sau khi so sánh data, scope, validation, risk, workflow và pilot, nhóm thống nhất chọn RegWatch với tỷ lệ 6/12.

---

## 4. Selected Problem — RegWatch

### 4.1 Original candidate

Idea ban đầu của Nguyễn Quang Vinh là: "Agent tổng hợp luật, phát hiện thay đổi và thông báo cập nhật cho người dùng khi có thay đổi."

Sau khi deep-dive, nhóm refine thành **RegWatch**: hệ thống giám sát thay đổi pháp lý và hỗ trợ Compliance trong lĩnh vực Ngân hàng - Tài chính. Đây không chỉ là chatbot hỏi đáp luật, cũng không chỉ là phát hiện conflict. Core workflow gồm:

```text
Monitoring
→ Change detection
→ Semantic retrieval
→ Conflict / impact assessment
→ Risk prioritization
→ Action planning
→ Notification
→ Human approval
```

### 4.2 Actor và context

**Primary actor:** Compliance Department tại ngân hàng thương mại.

**Downstream stakeholders:** Risk, Legal, Product, IT, Operations và CEO/BoD/C-level.

**Context:** Khi NHNN hoặc cơ quan có thẩm quyền ban hành/cập nhật quy định, Compliance phải phát hiện văn bản mới, đọc, xác định thay đổi, so sánh với quy định hiện hành/nội bộ, xác định phòng ban chịu ảnh hưởng, đánh giá risk, báo cáo, xin approval và truyền đạt/action.

---

## 5. Quick Validation

| Nguồn | Tín hiệu xác nhận | Tín hiệu phản bác / giới hạn | Nhóm sửa problem thế nào |
|---|---|---|---|
| Internal discussion | Nhóm thấy regulatory change có workflow nhiều bước và nhiều handoff; không thể chỉ search keyword. | Nhóm không có Compliance expert thật trong buổi lab. | Ghi rõ đây là scoped pilot và cần expert annotation. |
| SBV/NHNN public site | Trang SBV có mục văn bản quy phạm pháp luật và hiển thị các Thông tư gần đây. | Public site giúp monitoring, nhưng không map tự động sang policy nội bộ của từng ngân hàng. | RegWatch dùng public source làm input, không claim tự có dữ liệu nội bộ. |
| VBPL / CSDL quốc gia về pháp luật | Có cơ sở dữ liệu văn bản pháp luật phục vụ tra cứu văn bản trung ương/địa phương. | Search database không tự thay compliance impact assessment. | RegWatch không cạnh tranh với VBPL; nó dùng nguồn pháp lý như corpus đầu vào. |
| Existing RegTech products | Nhiều sản phẩm quốc tế đã có regulatory intelligence, alerts, obligations register hoặc change management. | Chưa thấy bằng chứng công khai về một workflow đúng scope Việt Nam + ngân hàng + HITL nội bộ. | Wording: "trong phạm vi desk research", không nói tuyệt đối là chưa có giải pháp. |

**Scope refinement:** Ban đầu là "Agent tổng hợp luật". Sau validation, nhóm thu hẹp thành "bounded agentic workflow hỗ trợ Compliance ngân hàng xử lý regulatory change, có traceability và human approval".

**Limitation:** Baseline thời gian trong bài là estimate cho pilot, chưa phải observed production data. Nhóm cần Compliance reviewer annotate test set trước khi kết luận.

---

## 6. Research Existing Solutions

Chi tiết nguồn nằm trong `02-group-problem-statement/research-notes.md`. Bảng dưới đây chỉ tóm tắt gap chính.

| Nguồn / tool / pattern | Giải quyết tốt phần nào | Gap so với RegWatch hypothesis |
|---|---|---|
| SBV/NHNN public portal | Công bố văn bản quy phạm pháp luật, dự thảo và thông tin ngành ngân hàng. | Không tự map impact tới quy định nội bộ và phòng ban ngân hàng. |
| VBPL / CSDL quốc gia về pháp luật | Tra cứu văn bản pháp luật trung ương/địa phương, dữ liệu pháp luật công khai. | Không phải workflow riêng cho Compliance ngân hàng với action plan/HITL. |
| Thư Viện Pháp Luật | Tra cứu, đọc, cập nhật văn bản pháp luật phổ biến. | Mạnh về search/content, không chứng minh end-to-end impact mapping nội bộ. |
| Thomson Reuters Regulatory Intelligence | Regulatory monitoring, horizon scanning, regulatory materials ở nhiều nguồn. | Global/commercial solution; chưa đủ evidence cho local Vietnamese banking internal workflow. |
| LexisNexis Regulatory Compliance | Obligations register, alerts, guidance cho compliance. | Pattern hữu ích, nhưng cần adaptation theo nguồn Việt Nam và policy/process nội bộ. |
| CUBE / Regology / AscentAI | RegTech pattern: monitor change, map obligations/risks/controls, AI hỗ trợ regulatory change. | Là benchmark pattern, không phải bằng chứng RegWatch đã được validate trong nhóm. |

**Research takeaway:** Không cần train foundation model mới. Pilot nên dùng legal corpus + retrieval + graph relationship + bounded agentic orchestration + human review.

---

## 7. Current Workflow

![Sơ đồ workflow](../assets/regwatch_01.svg)

| Step | Actor | Input | Output | Avg effort pilot estimate | Handoff | Risk |
|---:|---|---|---|---:|---|---|
| 1 | Compliance | SBV/VBPL/news/email | Candidate legal updates | 15' | Source → Compliance | Bỏ sót nguồn hoặc văn bản mới |
| 2 | Compliance | New document | Initial relevance decision | 20' | Compliance internal | Keyword search miss semantic relevance |
| 3 | Compliance | New document | Notes on changed clauses | 45' | Compliance | Đọc thiếu effective date/amendment |
| 4 | Compliance + Legal | New document + current rules | Related regulations/policies | 60' | Compliance ↔ Legal | Không tìm đủ văn bản dẫn chiếu |
| 5 | Compliance | Related documents | Impact/conflict notes | 90' | Compliance → Risk/Business | Bottleneck semantic cross-check |
| 6 | Compliance / Risk | Impact notes | Risk classification | 30' | Compliance ↔ Risk | Inconsistent risk label |
| 7 | Compliance | Risk notes | Risk report/action proposal | 45' | Compliance → C-level | Traceability yếu |
| 8 | C-level / BoD | Risk report | Approved direction | 30' | C-level → departments | Decision thiếu source context |
| 9 | Product/IT/Risk/Ops | Action proposal | Department tasks | 45' | Cross-functional | Owner/action bị rơi |
| 10 | Departments | Approved tasks | Updated policy/process/training | 60' | Departments → Compliance | Thực thi chậm, thiếu archive |

**Bottleneck:** Manual semantic cross-check giữa văn bản mới, văn bản hiện hành, chính sách nội bộ và nhiều phòng ban chịu ảnh hưởng. Đây không phải bước keyword search đơn giản.

---

## 8. Future Workflow

![Sơ đồ workflow](../assets/regwatch_02.svg)

### Implementation hypothesis

| Layer | Candidate approach | Vì sao |
|---|---|---|
| Data ingestion | Crawler/Playwright hoặc connector chính thức nếu có | Theo dõi văn bản mới từ nguồn công khai. |
| Parsing/chunking | Parser + metadata extractor | Lấy số hiệu, cơ quan ban hành, ngày hiệu lực, văn bản bị sửa/thay thế. |
| Retrieval | Vector search + keyword/BM25 | Tìm semantic similarity và exact references. |
| Relationship modeling | Knowledge graph | Biểu diễn `references`, `amends`, `repeals`, `supersedes`, `related-to`. |
| Orchestration | LangGraph-style bounded orchestrator | Cho phép branch khi cần deeper search hoặc reviewer feedback. |
| Human control | Compliance dashboard | Reviewer xem source, approve/reject, yêu cầu rerun. |
| Outputs | Risk report, action plan, alerts, draft policy/training notice | Output luôn có citation và trạng thái approval. |

Qdrant, Neo4j hoặc LangGraph chỉ là **implementation hypothesis**, không phải công nghệ bắt buộc.

---

## 9. Before / After Metrics

| Metric | Current baseline estimate | Pilot target | Measurement |
|---|---:|---:|---|
| Time-to-detect relevant document | 1-2 ngày làm việc | Trong ngày phát hiện / next business day | So sánh timestamp văn bản mới và lúc hệ thống tạo alert. |
| Initial review effort / document | 6-8 giờ cho một văn bản có nhiều dẫn chiếu | Giảm ≥50% effort initial triage | Reviewer time log. |
| Relevant provision recall | Chưa đo | ≥90% trên annotated pilot set | Expert annotation theo điều/khoản liên quan. |
| Alert relevance / precision | Chưa đo | ≥80% alerts được reviewer đánh giá relevant | Reviewer label alert. |
| Traceability | Nhiều note thủ công, khó audit | 100% material claim có source citation | Kiểm report output. |
| Critical miss | Không có metric ổn định | 0 critical miss trong controlled test set | Expert adjudication. |

Các số target là **pilot target**, không phải kết quả đã đạt.

---

## 10. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Compliance Department tại ngân hàng thương mại phải theo dõi và xử lý văn bản pháp lý/quy định mới có thể ảnh hưởng đến hoạt động ngân hàng. |
| **Workflow** | Theo dõi văn bản mới → đọc thủ công → tìm quy định liên quan → đánh giá tác động/rủi ro → viết báo cáo → xin duyệt → phân công phòng ban. |
| **Bottleneck** | Compliance phải tự cross-check semantic giữa nhiều văn bản và nhiều quy định nội bộ, dễ bỏ sót nghĩa vụ hoặc tác động gián tiếp. |
| **Impact** | Xử lý chậm, handoff rời rạc, khó trace source, tăng compliance risk nếu obligation bị bỏ sót. |
| **Success Metric** | Giảm ≥50% initial review effort, giữ 100% material claim có citation, đạt ≥90% relevant provision recall trên pilot annotated set. |
| **Boundary** | AI không tự kết luận pháp lý cuối cùng, không tự phê duyệt action plan, không tự thay đổi policy/process. |

---

## 11. AI Fit Analysis

| Dimension | Đánh giá | Lý do |
|---|---|---|
| Ambiguity | High | Văn bản pháp lý có dẫn chiếu, sửa đổi, thay thế, ngoại lệ và ngữ nghĩa phụ thuộc context. |
| Complexity | High | Nhiều nguồn, nhiều văn bản liên quan, nhiều phòng ban downstream, nhiều vòng approval. |
| Need tool use | Medium-high | Cần search, retrieval, graph traversal, comparison, report drafting và dashboard review. |
| Dynamic branching | Medium-high | Có case cần follow references sâu hơn, rerun khi reviewer thêm context, route theo risk/confidence. |
| Failure cost | High | False negative có thể làm miss obligation; hallucination có thể gây quyết định sai. |

**Kết luận:** Fixed Workflow đủ cho happy path, nhưng RegWatch có dynamic branching trong legal reference traversal và impact analysis. Vì vậy nhóm chọn **Bounded Agent / Agentic Workflow with Human-in-the-loop**, không phải fully autonomous agent.

---

## 12. No AI / Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Giới hạn | Chọn? |
|---|---|---|---|---|
| No AI / Process fix | Compliance checklist, legal change register, email distribution, owner matrix, manual review. | Đủ để chuẩn hóa handoff cơ bản. | Không giải quyết semantic scale và nhiều dẫn chiếu. | Không chọn làm toàn bộ; dùng làm fallback. |
| Rule | Keyword watch, metadata filter, regex số hiệu văn bản, exact reference extraction, fixed owner mapping. | Tốt với explicit relation và nguồn ổn định. | Yếu với semantic impact, nghĩa vụ gián tiếp, policy nội bộ. | Dùng trong pipeline. |
| Workflow | Ingest → retrieve → compare → draft report → human review. | Giải được happy path và dễ audit. | Khi văn bản dẫn chiếu nhiều tầng, workflow cứng có thể thiếu deeper search. | Chưa đủ một mình. |
| Agent | Bounded agent chọn retrieval path, gọi semantic search/graph, phân tích impact/conflict, branch theo risk/confidence, rerun sau feedback. | Hợp khi cần dynamic orchestration nhưng vẫn có guardrail. | Nếu autonomous quá mức sẽ rủi ro legal/compliance. | Chọn dạng bounded + HITL. |

**Tại sao không chọn Workflow đơn thuần:** Một fixed workflow đủ cho case đơn giản. Nhưng regulatory analysis có thể có chuỗi như: văn bản A sửa Điều X của B; B dẫn chiếu C; C bị thay thế một phần bởi D. Hệ thống cần follow reference, query graph, retrieve semantic context và quyết định có cần deeper comparison không.

**Tại sao không full autonomous Agent:** Legal/compliance là high-risk. Agent không được approve, publish, sửa policy hoặc thay đổi rule production. Human approval bắt buộc ở nhiều mức.

---

## 13. Selected AI Level

**Selected level:** Bounded Agent / Agentic Workflow with Human-in-the-loop.

Autonomy được giới hạn:

- Agent được monitor, retrieve, compare, draft, rank risk và đề xuất action.
- Agent phải trích nguồn cho mọi material claim.
- Agent phải chuyển sang Compliance reviewer khi confidence thấp, conflict cao hoặc thiếu source.
- Agent không được đưa ra kết luận pháp lý cuối cùng.

---

## 14. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Compliance Department tại ngân hàng thương mại; downstream stakeholders gồm Risk, Legal, Product, IT, Operations và BoD/C-level. |
| **Workflow** | Theo dõi văn bản mới → xác định thay đổi → retrieve quy định liên quan → đánh giá impact/conflict → phân cấp risk → expert review → approval → action planning → departmental update. |
| **Bottleneck** | Manual semantic cross-check giữa nhiều văn bản pháp lý, quy định nội bộ và mapping ảnh hưởng tới nhiều phòng ban. |
| **Impact** | Thời gian xử lý dài, bỏ sót nghĩa vụ, handoff không nhất quán, khó audit traceability, tăng compliance risk. |
| **Success Metric** | Pilot target: ≥90% relevant provision recall, ≥80% alert relevance, 100% material claim có traceable source, giảm ≥50% initial review effort, 0 critical miss trong controlled test set. |
| **Boundary** | Human approval mandatory cho compliance analysis, risk response/action plan và implementation update. |
| **AI intervention** | Semantic retrieval, graph traversal, impact/conflict analysis, risk prioritization, draft report/action generation. |
| **Level** | Bounded Agent / Agentic Workflow with HITL. |

---

## 15. Risk & Human Boundary

| Risk | Consequence | Mitigation | Owner |
|---|---|---|---|
| Hallucination | Báo cáo chứa claim pháp lý không có nguồn. | Citation-grounded generation + human review. | Compliance reviewer |
| False negative | Miss obligation hoặc văn bản liên quan. Đây là risk nguy hiểm nhất. | Hybrid retrieval + deterministic reference extraction + expert evaluation. | Compliance + Legal |
| False positive | Reviewer overload, mất niềm tin vào alert. | Confidence/risk threshold, feedback loop, precision tracking. | Compliance ops |
| Outdated document | Dùng văn bản hết hiệu lực hoặc effective date sai. | Version/effective-date metadata, source refresh log. | Data owner |
| Wrong legal relationship | Map sai `amends/repeals/references`, dẫn tới impact sai. | Graph trace + source citation + reviewer approval. | Legal reviewer |
| Data leakage | Lộ policy/process nội bộ khi dùng cloud/public LLM. | Private deployment, access control, VPC/on-prem tùy môi trường. | IT/Security |
| Automation bias | Người dùng tin AI suggestion như kết luận approved. | UI tách rõ AI suggestion vs approved conclusion. | Product owner |

### Human-in-the-loop

| Level | Người duyệt | Duyệt nội dung gì |
|---|---|---|
| Level 1 | Compliance expert | Impact, conflict, risk classification, source trace. |
| Level 2 | CEO / BoD / C-level | Risk response và Action Plan. |
| Level 3 | Product / IT / Risk / Operations | Revised policy/process, training notice, system/rule changes. |

---

## 16. Final Decision

**Decision:** **GO — scoped pilot**.

Không phải production rollout. Scope pilot:

- Chỉ văn bản pháp lý/quy định liên quan đến NHNN.
- Chọn một nhóm văn bản hạn chế, ví dụ một số Thông tư gần đây.
- Dùng một số văn bản nội bộ/sample policy giả lập.
- Có một Compliance reviewer annotate và review output.

**Lý do Go:** Problem rõ, actor rõ, nguồn public đủ để bắt đầu, failure có thể kiểm soát trong môi trường pilot, và có rollback manual/rule-based.

---

## 17. Pilot Design

**Pilot data:**

- Public: legal/regulatory docs, amendments, metadata từ SBV/VBPL.
- Internal/sample: policy/process metadata, sample compliance workflow.
- Annotated test set: relevant documents, legal references, changed obligations, affected units, expected risk labels.

**Evaluate:**

- Retrieval recall.
- Impact precision.
- Conflict alert precision.
- Traceability.
- Human review time.
- False negative.
- False positive.

### Exit / rollback criteria

**GO forward nếu:**

- ≥90% relevant provision recall trên annotated pilot.
- ≥80% alerts được reviewer đánh giá relevant.
- 100% material claim có traceable source.
- Giảm ≥50% initial review effort.
- Không có critical miss trong controlled test set.

**NOT YET nếu:**

- Reviewer vẫn phải đọc lại gần như toàn bộ corpus.
- False positives quá nhiều.
- Graph relations unreliable.
- Citation traceability chưa đạt.

**NO-GO / fallback:**

- Legal change register.
- Keyword/rule monitoring.
- Deterministic document linking.
- Manual Compliance review.

---

## 18. Final Self-check

- 12 members.
- 12 candidate rows.
- 5 clusters.
- 3 shortlist candidates.
- Score table consistent.
- Vote total = 12: RegWatch 6, Citizen Agent 4, Driver Drowsiness CV 2.
- Selected candidate always RegWatch.
- Selected AI level: Bounded Agent / Agentic Workflow with HITL.
- Final decision: GO — scoped pilot.
- Research links moved to `research-notes.md`.
- Mermaid diagrams included for current and future workflow before SVG conversion.
- No blank section, no pending placeholder.
