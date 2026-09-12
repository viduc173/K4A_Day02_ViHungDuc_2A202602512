# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1 | Nguyễn Mạnh Cường | 2A202602823 | workflow |
| 2 | Lê Thị Hoài Thương | 2A202602898 | facilitator |
| 3 | Nguyễn Văn Sơn | 2A202602744 | writer |
| 4 | Phan Văn Nghị | 2A202602632 | research |
| 5 | Vi Hùng Đức | 2A202602512 | validation |
| 6 | Đỗ Mạnh Đoan | 2A202602839 | reviewer |

**Candidate problem nhóm chọn (1 câu):**

Chuẩn hoá và tự động hoá việc chuyển 200 phiếu khảo sát giấy/PDF từ BA thành file Excel và docx có cấu trúc, giảm thời gian nhập/copy thủ công và lỗi trước khi bàn giao cho Giám đốc và PM.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Mạnh Cường | Báo cáo tiến độ tuần gửi GVHD: sinh viên mất khoảng 68 phút/tuần tổng hợp log thí nghiệm, commit và note họp thành báo cáo. | Sinh viên năm 4 làm đồ án tốt nghiệp, báo cáo trực tiếp cho 1 GVHD. | Bước 5 — viết phần diễn giải khó khăn, bước tiếp theo và câu hỏi cho GVHD; khoảng 18 phút, khó chuyển dữ liệu thô thành nhận định. | Workflow rõ 7 bước, baseline 68 phút/tuần được bấm giờ 3 tuần; cần làm rõ cách đo chất lượng báo cáo ngoài thời gian. |
| 2 | Nguyễn Mạnh Cường | Đọc và tóm tắt paper cho Related Work: khoảng 40 phút/paper với 15–20 paper, tương đương khoảng 10–13 giờ/kỳ. | Sinh viên làm đồ án, tự chịu trách nhiệm chương Related Work. | Bước 5 — viết 2–4 câu tóm tắt nêu paper khác gì hoặc bổ sung gì cho đồ án; khoảng 10–12 phút/paper, dễ viết chung chung. | Tốn nhiều thời gian, có thể thử AI hỗ trợ tóm tắt và đối chiếu với cách không dùng AI; chất lượng hiểu đúng paper khó đo, có rủi ro AI bịa hoặc tóm tắt sai. |
| 3 | Nguyễn Mạnh Cường | Tổng hợp kết quả thí nghiệm từ log/notebook: khoảng 50 phút/lần để gom kết quả thành bảng so sánh và viết nhận xét, lặp 1–2 lần/tuần. | Sinh viên chạy thí nghiệm, cần báo cáo kết quả cho GVHD và đưa vào chương Evaluation. | Bước 3 — chuẩn hoá tên cột, đơn vị và thứ tự metric giữa các lần chạy; khoảng 20 phút/lần và dễ sai. | Workflow tuyến tính, có số đo và dễ so sánh trước/sau; định dạng log chưa đồng nhất. Rule/script có thể xử lý điểm nghẽn chuẩn hoá, AI được đề xuất hỗ trợ viết nhận xét. |
| 4 | Lê Thị Hoài Thương | Đọc và tổng hợp 200 phiếu khảo sát từ 100 công an và 100 UBND xã để làm Excel gửi Giám đốc và docx gửi PM; file cá nhân ước tính 66,6 giờ/đợt, cần xác minh lại. | BA phụ trách khảo sát và tổng hợp dữ liệu tại 3 tỉnh/thành. | Đọc và tổng hợp thủ công các phiếu chưa có mẫu chuẩn hoá; nguồn tính 10 phút/xã × 200 × 2. | Ảnh hưởng trực tiếp hai đầu ra Excel/docx, điểm nghẽn rõ; cần bấm giờ lại và làm rõ hệ số ×2, đồng thời thử chuẩn hoá form trước. |
| 5 | Lê Thị Hoài Thương | Copy/viết dữ liệu khảo sát sang từng hàng Excel/docx: khoảng 2.000 hàng, ước tính 33,3 phút/đợt cho thao tác nhập/copy. | BA tổng hợp khảo sát trước khi gửi Giám đốc/PM. | Copy/viết từng hàng và chuyển dữ liệu sang tài liệu đích bằng tay, dễ sai trường và lỗi nhập liệu. | Thao tác cơ học, lặp lại, dễ tự động hoá; cần xác nhận số hàng và định dạng đích, so sánh với công thức Excel, mail merge và template cố định. |
| 6 | Lê Thị Hoài Thương | Hệ thống lại tài liệu bị lặp hoặc thiếu ý do nội dung giống nhau nhưng dùng từ khoá khác nhau; nguồn ước tính 80 lỗi × 10 phút sửa, khoảng 13,3 giờ/đợt. | Team BA, PM và Giám đốc khi chuẩn hoá tài liệu dùng chung trước khi duyệt/gửi khách hàng. | Tìm ý trùng và thiếu bằng từ khoá thủ công, khó nhận ra các cách diễn đạt cùng nghĩa. | Ảnh hưởng chất lượng tài liệu và quá trình duyệt; AI có thể hỗ trợ đối chiếu ngữ nghĩa, nhưng cách đo lỗi và tiêu chí đủ ý còn cần xác nhận. |
| 7 | Nguyễn Văn Sơn | Đối soát bằng chứng năng lực với JD và tạo CV phù hợp từng vị trí: sinh viên vừa khó chọn trải nghiệm liên quan, vừa mất công viết lại và định dạng CV. | Sinh viên năm cuối hoặc mới tốt nghiệp ứng tuyển Intern/Fresher/Junior. | Bước 2 — chọn dự án chứng minh yêu cầu JD; bước 3–4 — sửa câu chữ và bố cục thủ công, khoảng 20–30 phút. | Xếp hạng 1, xử lý cả chọn bằng chứng và tạo bản CV; cần kiểm tính xác thực, bố cục và khả năng chỉnh sửa. Baseline trong nguồn chưa thống nhất: có số đo 45–55 phút/JD nhưng card vẫn ghi giả thuyết 35–50 phút. |
| 8 | Nguyễn Văn Sơn | Đọc và lập ma trận so sánh từ 20–30 bài báo PDF cho chương Tổng quan nghiên cứu; nguồn nêu mất 15–20 giờ nhưng ghi chú rời rạc, khó đối chiếu các công trình. | Sinh viên năm cuối làm khoá luận, đồ án chuyên ngành hoặc nghiên cứu khoa học. | Bước 3–4 — ghi chú thiếu tiêu chí thống nhất, phải đọc lại và trích thủ công phương pháp, dữ liệu, kết quả và hạn chế từ nhiều PDF. | Xếp hạng 2, tốn nhiều thời gian và có đầu ra ma trận cụ thể; cần kiểm từng thông tin với PDF gốc, đặc biệt số liệu thực nghiệm. |
| 9 | Nguyễn Văn Sơn | Soạn bản tóm tắt tiến độ trước họp GVHD và trích danh sách việc sau họp; báo cáo thiếu trọng tâm, dễ quên hoặc ghi sót yêu cầu chỉnh sửa. | Sinh viên làm khoá luận cá nhân/nhóm 2–3 người và GVHD. | Bước 3 — nghe lại ghi âm, mất khoảng 30–40 phút để chuyển nhận xét phân tán thành việc rõ ràng, có trách nhiệm và hạn chót. | Xếp hạng 3, lặp hằng tuần; cần kiểm nhận diện thuật ngữ tiếng Việt pha thuật ngữ kỹ thuật. Tổng thời gian trong workflow nguồn chưa khớp các bước nên cần đo lại baseline. |
| 10 | Phan Văn Nghị | Chỉnh CV theo từng JD khi ứng tuyển AI Engineer: khoảng 45 phút/vị trí, tương đương 225 phút cho 5 vị trí/tuần. | Thực tập sinh AI đang ứng tuyển 5–6 vị trí mỗi tuần. | Bước 3 — viết lại bullet dự án, khoảng 20 phút để nhớ chi tiết dự án và diễn đạt phù hợp yêu cầu JD. | Workflow 5 bước, baseline bấm giờ 3 lần là 42, 47 và 45 phút; mới có dữ liệu từ một người. Cần kiểm bullet đúng kinh nghiệm thật và chọn metric đo được trong lab. |
| 11 | Phan Văn Nghị | Lọc tin tuyển dụng AI trên 5–6 nguồn: khoảng 60 phút/tuần để tìm 4–5 tin phù hợp, nhiều tin đã xem từ tuần trước. | Thực tập sinh AI tìm việc AI Engineer ở Hà Nội và 3 người cùng đợt thực tập. | Bước 3 — mở và đọc lướt từng JD để loại tin không phù hợp, khoảng 25 phút; khoảng 1/3 tin bị lặp từ tuần trước. | Tiêu chí địa điểm, cấp bậc và từ khoá có thể viết thành Rule, chưa cần AI; cần kiểm khả năng lấy dữ liệu từ LinkedIn và nhóm Facebook do đăng nhập/chặn bot. |
| 12 | Phan Văn Nghị | Ghi tay config và metric của 8–12 lần train/eval mỗi tuần; nguồn nêu khoảng 50 phút/tuần và đã 2 lần không tái hiện được kết quả vì ghi thiếu. | Thực tập sinh AI làm dự án NLP/RAG cá nhân trên máy riêng và Colab. | Bước 4 — ghi config thủ công, khoảng 3 phút/lần nhưng dễ thiếu seed hoặc learning rate; cuối tuần phải dò lại khoảng 20 phút. | Ưu tiên sửa quy trình bằng file config và công cụ tự log, không cần AI; cần kiểm khả năng đổi thói quen. Tổng thời gian tuần cần đối soát vì phép tính ở bảng scan chưa khớp số lần chạy. |
| 13 | Vi Hùng Đức | Phải mở lại 5 tài liệu đã đọc để tìm phương pháp, điều kiện đánh giá và hạn chế vì ghi chú thiếu cấu trúc, không lưu trang nguồn. | Sinh viên năm 4 ngành Khoa học máy tính viết phần nghiên cứu liên quan của đồ án. | Bước 3 — tìm lại trường thông tin còn thiếu; minh hoạ 35 phút trong tổng 100 phút/5 tài liệu, chưa đo thật. | Phạm vi hẹp, đầu ra là bảng có nguồn; cần phân biệt công tìm lại với công đọc hiểu và so với mẫu ghi chú thủ công. Chưa có tài liệu thật hoặc baseline thực tế. |
| 14 | Vi Hùng Đức | Không theo dõi được đã sửa đủ góp ý giảng viên chưa vì từng ý chưa gắn với việc cần làm, vị trí thay đổi và tiêu chí hoàn thành. | Sinh viên sửa đồ án; GVHD xác nhận những ý còn mơ hồ. | Bước 2 — đọc và diễn giải comment có nhiều ý, dễ bỏ sót hoặc hiểu khác ý giảng viên; minh hoạ 15 phút trong tổng 40 phút/10 góp ý, chưa đo thật. | Đầu vào/đầu ra rõ, thử được trên một đợt góp ý; cần nguồn góp ý thật, đối chiếu hai chiều và giữ trạng thái chờ làm rõ cho ý chưa xác nhận. |
| 15 | Vi Hùng Đức | Không truy được mỗi số liệu đánh giá thuộc phiên bản mã, dữ liệu và cấu hình nào do đầu ra các lần chạy lưu rời rạc, chưa gắn với bản ghi tương ứng. | Sinh viên chạy đánh giá và viết phần kết quả đồ án Khoa học máy tính. | Bước 2 — truy lại phiên bản và cấu hình sau khi chạy; minh hoạ 20 phút trong tổng 45 phút công xử lý/5 lần chạy, chưa gồm thời gian chương trình chạy. | Ưu tiên Rule để kiểm trường bắt buộc và tổng hợp theo mã lần chạy; cần kiểm nguồn còn lưu, tính tương thích khi so sánh và đo cả công ghi nhận ban đầu. Chưa có baseline thực tế. |
| 16 | Đỗ Mạnh Đoan | Đọc, tách yêu cầu và đối chiếu JD với CV/project để quyết định job nên ứng tuyển; ước tính 140–205 phút/tuần cho 20–25 JD AI, vẫn có nguy cơ bỏ sót job phù hợp. | Sinh viên vừa tốt nghiệp tìm vị trí AI Engineer Intern/Fresher. | Bước 3–6 — đọc, hiểu, tra thuật ngữ và đối chiếu yêu cầu với bằng chứng trong hồ sơ; ước tính 7–9 phút/JD, chưa bấm giờ thực tế. | Xếp hạng 1, lặp hằng tuần và đo được thời gian cùng tỷ lệ bỏ sót; cần định nghĩa tiêu chí phù hợp, kiểm baseline và so với checklist/Sheet. Pilot giới hạn 20 JD do người dùng cung cấp, mọi đối chiếu phải có dẫn chứng và người dùng quyết định ứng tuyển. |
| 17 | Đỗ Mạnh Đoan | Cá nhân hoá CV theo từng JD mà không thêm thông tin sai: ước tính 25–30 phút/hồ sơ, khoảng 125–150 phút/tuần cho 5 hồ sơ. | Ứng viên AI Intern/Fresher có CV gốc và nhiều project học tập/thực tế. | Bước 2–4 — mở nguồn, chọn bằng chứng dự án phù hợp rồi viết lại summary/bullet ngắn gọn; ước tính 18–22 phút/hồ sơ. | Xếp hạng 2, workflow rõ và đo được thời gian/lỗi thông tin; baseline còn là ước tính, cần thử mục tiêu ≤15 phút có giữ chất lượng không. Mỗi đề xuất phải truy về CV gốc hoặc kho bằng chứng, ứng viên kiểm trước khi xuất CV. |
| 18 | Đỗ Mạnh Đoan | Theo dõi trạng thái hồ sơ ứng tuyển và thời điểm follow-up từ email, website và ghi chú; kiểm tra khoảng 3 lần/tuần nhưng vẫn có nguy cơ quên cập nhật hoặc follow-up trễ. | Sinh viên vừa tốt nghiệp đang đồng thời theo dõi nhiều hồ sơ ứng tuyển. | Bước 3–5 — kiểm tra nhiều nguồn, cập nhật Sheet và tính ngày follow-up; ước tính 30–45 phút/tuần, cần đo thực tế. | Xếp hạng 3, đầu vào/đầu ra rõ; pilot dùng Sheet chuẩn và Rule nhắc lịch, chưa cần AI. Cần xác nhận tần suất quên thực tế và độ ổn định của email nếu muốn tự động cập nhật; ứng viên vẫn duyệt và gửi follow-up. |

> Mục 3.1 mở rộng thành 18 candidates cho 6 thành viên, mỗi người 3 đề xuất. Thứ tự trong từng nhóm theo bảng top 3 của file cá nhân; các nhận xét trên chưa phải ý kiến đồng thuận của nhóm. Số liệu được chuyển từ nguồn cá nhân, chưa được nhóm validation.

### 3.2. Gom trùng / cluster (gom 18 ý thành 4 cụm)

Các mã # tham chiếu mục 3.1. Mỗi candidate chỉ thuộc một cụm chính; cùng cụm chỉ thể hiện chủ đề gần nhau, chưa phải bài toán triển khai chung.

| Cluster | Candidates included | Pattern chung và mức độ trùng | Hướng shortlist |
|---|---|---|---|
| **A — Tìm việc và chuẩn bị hồ sơ** | **#7, #10, #11, #16, #17, #18** | #7, #10, #17 trùng nhiều ở chọn bằng chứng và chỉnh CV; #16 giao với #7 nhưng tập trung quyết định có ứng tuyển; #11 là lọc tin, #18 là theo dõi sau nộp. | Chọn một điểm nghẽn riêng; #11 và #18 có thể ưu tiên Rule/quy trình. |
| **B — Tổng hợp tài liệu nghiên cứu** | **#2, #8, #13** | #8 và #13 cùng cần trích thông tin có cấu trúc; #2 tập trung viết nhận định Related Work sau khi hiểu paper. | Có thể thử ma trận có trang/mục nguồn; cần kiểm độ đúng của thông tin trích xuất. |
| **C — Ghi nhận và truy vết thí nghiệm** | **#3, #12, #15** | #12 và #15 cùng thiếu liên kết giữa config và kết quả; #3 thiên về chuẩn hoá, ghép bảng ở bước sau. | Ưu tiên mẫu log, config và Rule/script; AI viết nhận xét chỉ là bước phụ. |
| **D — Tổng hợp báo cáo và việc cần xử lý** | **#1, #4, #5, #6, #9, #14** | Gồm hai nhánh khác domain: GVHD (#1, #9, #14) và BA (#4, #5, #6). #4 → #5 là hai bước nối tiếp, không phải cùng một problem. | Không gộp hai domain; giữ actor, input và output cụ thể khi shortlist. |

**Kết quả gom:** 18 candidates → 4 cụm (A: 6, B: 3, C: 3, D: 6). Mỗi candidate xuất hiện đúng một lần; các cụm chỉ là cơ sở để chọn shortlist, không thay thế validation và điểm số ở mục 3.3–3.4.

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#1 — Tự động tổng hợp báo cáo tiến độ tuần gửi GVHD** | Actor và workflow 7 bước khá rõ; đã có baseline 68 phút/tuần được bấm giờ trong 3 tuần; đầu ra, thời gian và chất lượng báo cáo có thể so sánh trước/sau. | Chưa có tiêu chí đo chất lượng báo cáo; cần tách phần Rule tổng hợp dữ liệu và phần AI diễn giải để tránh dùng AI cho bước có thể tự động hoá. |
| **#3 — Chuẩn hoá và tổng hợp kết quả thí nghiệm** | Có đầu ra cụ thể là bảng metric và nhận xét; bottleneck chuẩn hoá tên cột, đơn vị và thứ tự metric có thể đo; phù hợp để so sánh Rule/script, Workflow và AI hỗ trợ viết nhận xét. | Format log/notebook hiện chưa đồng nhất; cần kiểm tra lại tần suất, thời gian 50 phút/lần và độ chính xác của bảng sau khi chuẩn hoá. |
| **#10 — Chỉnh CV theo từng JD** | Actor, input và output rõ; baseline đã bấm giờ 3 lần (42, 47 và 45 phút/vị trí); có thể đo thời gian xử lý, mức phù hợp với JD và lỗi thông tin. | Dữ liệu mới từ một người; cần có bộ CV/JD mẫu và tiêu chí đánh giá khách quan, đồng thời bảo đảm AI không tự thêm kinh nghiệm không có trong CV gốc. |
| **#4 — Tổng hợp 200 phiếu khảo sát thành Excel và docx** | Actor và hai đầu ra bàn giao khá rõ; pain point là đọc, chuẩn hoá và tổng hợp dữ liệu thủ công; có tiềm năng đo thời gian, số lỗi và mức giảm thao tác khi dùng form/template hoặc workflow tự động. | Ước tính 66,6 giờ/đợt và cách tính 10 phút/xã × 200 × 2 chưa được xác minh; cần kiểm tra lại số phiếu, mẫu dữ liệu, yêu cầu định dạng và bảo mật thông tin khảo sát. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#4 — Tổng hợp 200 phiếu khảo sát thành Excel và docx** | 5 | 5 | 3 | 5 | 5 | 5 | 4 | **32** |
| **#1 — Tự động tổng hợp báo cáo tiến độ tuần gửi GVHD** | 5 | 5 | 4 | 4 | 4 | 4 | 4 | **30** |
| **#3 — Chuẩn hoá và tổng hợp kết quả thí nghiệm** | 5 | 4 | 3 | 4 | 5 | 5 | 4 | **30** |
| **#10 — Chỉnh CV theo từng JD** | 5 | 5 | 3 | 4 | 4 | 4 | 3 | **28** |

**Cách hiểu điểm:** #4 đứng đầu vì có actor, input và hai output bàn giao rất cụ thể; quy trình có thể làm prototype trong lab bằng form/template, bảng dữ liệu và workflow kiểm tra. Điểm **3/5 ở Pain có evidence** vì số liệu 66,6 giờ/đợt và cách tính hiện chưa được xác minh; đây là việc phải kiểm tra ở Phase 4.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#4 — Chuẩn hoá và tổng hợp 200 phiếu khảo sát thành file Excel và docx có cấu trúc,
giảm thao tác nhập/copy thủ công và lỗi trước khi bàn giao cho Giám đốc/PM.
```

**Vì sao chọn (4-5 câu):**

```text
Actor, input và output của #4 tương đối rõ: BA nhận các phiếu khảo sát và phải tạo hai tài liệu bàn giao
cho Giám đốc và PM. Workflow có điểm nghẽn cụ thể ở việc đọc, chuẩn hoá, nhập/copy và kiểm tra dữ liệu;
đây là các bước có thể tách để đo thời gian và số lỗi trước/sau. Bài toán phù hợp để so sánh Rule/template,
Workflow tự động hoá và Agent, đồng thời vẫn có thể làm prototype trong phạm vi lab. Nhóm chưa coi baseline
66,6 giờ là số liệu đã xác nhận; pilot phải bấm giờ lại và kiểm tra số phiếu, số trường cùng định dạng đầu ra.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#1 có workflow và baseline khá tốt, nhưng phần viết diễn giải và đánh giá chất lượng báo cáo khó chuẩn hoá
trong thời gian lab. #3 phù hợp với Rule/script hơn là AI, trong khi format log và tần suất xử lý chưa ổn định.
#10 có baseline bấm giờ nhưng dữ liệu mới từ một người, chất lượng CV khó chấm khách quan và rủi ro AI thêm
thông tin sai khá cao.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Một số thành viên lo #4 đang dựa trên baseline ước tính và có thể chỉ cần chuẩn hoá form hoặc dùng công thức
Excel, chưa cần AI. Nhóm vẫn đưa #4 lên đầu vì đầu ra kép Excel/docx và quy trình nhập, kiểm tra, bàn giao
đủ rõ để thử trong lab; quyết định cuối chỉ được giữ sau khi xác minh lại số liệu và so sánh với phương án
non-AI.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa thực hiện | Chưa có quote nguyên văn; cần hỏi 2–3 BA/PM từng tổng hợp phiếu khảo sát về thời gian đọc, nhập và kiểm tra dữ liệu. | Chưa có dữ liệu để xác nhận hoặc phản bác. | Chưa dùng kết quả phỏng vấn để chốt problem; cần ghi chú gốc sau khi phỏng vấn. |
| Survey / poll | Chưa thực hiện | Chưa có mẫu khảo sát; dự kiến hỏi 5–10 người về số phiếu, số trường nhập, thời gian/đợt và lỗi thường gặp. | Chưa có dữ liệu phản bác. | Dùng kết quả để điều chỉnh baseline 66,6 giờ/đợt và xác định bước gây mất thời gian nhất. |
| Card cá nhân #4 / ước tính hiện có | 1 case, 200 phiếu | Có giả định: BA tổng hợp 200 phiếu từ 100 công an và 100 UBND xã để tạo Excel và docx; thời gian ước tính 66,6 giờ/đợt. Đây chưa phải quote hay log đã xác minh. | Cách tính 10 phút/xã × 200 × 2 chưa rõ; phần copy/nhập có thể là một bước riêng và có thể giải bằng template/Excel. | Tạm thu hẹp problem vào chuẩn hoá và chuyển dữ liệu có kiểm tra; phải bấm giờ lại và so sánh với form chuẩn, Power Query hoặc template. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain point hiện mới được xác định sơ bộ là công đọc, chuẩn hoá và chuyển dữ liệu từ nhiều phiếu khảo sát
sang hai đầu ra khác nhau, nhưng baseline 66,6 giờ chưa đủ bằng chứng để kết luận. Trước khi viết Problem
Statement v0, nhóm cần xác minh số phiếu, số trường, thời gian từng bước và tỷ lệ lỗi bằng log hoặc phỏng vấn.
```

Bằng chứng đính kèm (hiện chưa có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Microsoft Forms | https://support.microsoft.com/en-us/forms | Tạo form và thu thập câu trả lời theo trường dữ liệu cố định. | Chuẩn hoá input ngay từ đầu, giảm đọc và nhập lại thủ công. | Không tự xử lý các phiếu cũ; form thiết kế không phù hợp có thể làm mất thông tin cần thiết. | Ưu tiên sửa input bằng form/schema trước khi thêm AI. |
| Power Query for Excel | https://learn.microsoft.com/en-us/power-query/ | Nhập, làm sạch, đổi kiểu và gộp dữ liệu từ nhiều file/bảng. | Quy trình biến đổi có thể lặp lại, giảm copy/paste. | Cần cấu trúc cột ổn định; dữ liệu tự do hoặc scan/OCR vẫn cần người kiểm tra. | Dùng cho bước chuẩn hoá và tạo bảng Excel; đây là baseline non-AI bắt buộc phải so sánh. |
| Word mail merge | https://support.microsoft.com/en-us/office/mail-merge-ef0d6a09-e0a7-4e7c-a3b8-0c0d6f9e5d4a | Tạo nhiều tài liệu Word từ một nguồn dữ liệu có trường cố định. | Phù hợp đầu ra docx lặp lại, giảm nhập lại cùng thông tin. | Chỉ xử lý tốt template và trường dữ liệu đã chuẩn; không tự hiểu nội dung thiếu hoặc mâu thuẫn. | Tách bước tạo docx thành template/Rule, không cần Agent. |
| Power Automate | https://learn.microsoft.com/en-us/power-automate/getting-started | Nối form, file Excel và các bước xử lý theo trigger. | Tạo workflow có trigger, phân quyền và lịch sử chạy. | Connector, quyền truy cập và lỗi dữ liệu có thể làm workflow thất bại. | Chỉ dùng sau khi input, schema và bước kiểm tra đã ổn định; vẫn cần người duyệt trước khi gửi. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Giải pháp nên bắt đầu bằng form/schema chuẩn, Power Query hoặc script để làm sạch dữ liệu, rồi dùng
template/mail merge để tạo Excel và docx. Workflow có thể thêm AI ở bước phát hiện trường thiếu, gợi ý
chuẩn hoá câu trả lời hoặc đánh dấu bản ghi cần review, nhưng không nên để AI tự quyết định dữ liệu cuối
cùng hoặc tự gửi tài liệu. Nhóm cần so sánh bản non-AI trước; nếu Rule/template xử lý được 70–80% case,
không cần mở rộng thành Agent.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Nhận 200 phiếu: đầu đợt] → [2 Đọc & gạch ý: ~33h] → [3 Chuẩn hoá dữ liệu: lồng trong bước 2]  <-- bottleneck
→ [4 Nhập Excel: 33,3'] → [5 Soạn docx: lồng trong tổng] → [6 Rà lỗi trùng/thiếu: ~13,3h] → [7 Gửi Giám đốc/PM]

Tổng ước tính hiện tại: ~66,6 giờ/đợt (baseline cá nhân, chưa xác nhận — xem Phase 4.1)
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | BA | 200 phiếu khảo sát giấy/PDF từ 100 công an + 100 UBND xã | Bộ phiếu đã tập hợp theo đơn vị | 1 lần/đầu đợt | Chưa có mẫu chuẩn hoá chung giữa các đơn vị |
| 2 | BA | Từng phiếu | Dữ liệu đã đọc, gạch ý theo từng câu hỏi | ~10 phút/xã × 200 ≈ 33 giờ (ước tính, chưa bấm giờ) | Đọc thủ công, tốc độ phụ thuộc chữ viết/định dạng phiếu |
| 3 | BA | Dữ liệu đã đọc | Dữ liệu đã quy ước thống nhất (đơn vị, tên trường) | Lồng trong bước 2, chưa tách đo riêng | **Bottleneck nghi ngờ** — vừa đọc vừa tự quy ước vì chưa có schema chung |
| 4 | BA | Dữ liệu đã chuẩn hoá | ~2.000 dòng trong Excel | ~33,3 phút/đợt | Copy/nhập tay, dễ sai trường (theo candidate #5) |
| 5 | BA | Bảng Excel | Bản docx tổng hợp nháp | Lồng trong tổng 66,6 giờ, chưa tách riêng | Dễ trùng/thiếu ý vì dùng từ khoá khác nhau (theo candidate #6) |
| 6 | BA | Excel + docx nháp | Excel/docx đã rà lỗi | ~80 lỗi × 10 phút ≈ 13,3 giờ/đợt | Rà bằng mắt/từ khoá thủ công |
| 7 | BA | Excel + docx đã rà | Excel gửi Giám đốc, docx gửi PM | Cuối đợt | Bàn giao trực tiếp, chưa có bước review độc lập trước khi gửi |

**Bottleneck chính (2-3 câu):**

```text
Bước 2-3 (đọc và chuẩn hoá dữ liệu) chiếm phần lớn thời gian trong baseline ước tính 66,6 giờ/đợt, vì các
phiếu khảo sát từ 100 công an và 100 UBND xã chưa dùng chung một mẫu/schema. BA vừa đọc vừa tự quy ước cách
hiểu và cách ghi nhận, nên đây là bước khó tự động hoá nhất nếu không chuẩn hoá input ngay từ đầu.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Chuẩn hoá form khảo sát đầu vào: 1 lần/đợt - máy/Rule]
→ [2 Nhập qua Microsoft Forms/schema cố định - máy/Rule]
→ [3 Power Query làm sạch & gộp dữ liệu - máy/Rule]
→ [4 AI gắn cờ bản ghi nghi thiếu/trùng ý - AI hỗ trợ]
→ [5 BA review các bản ghi bị gắn cờ + duyệt số liệu cuối - boundary]
→ [6 Mail merge xuất docx + xuất Excel từ dữ liệu đã duyệt - máy/Rule]
→ [7 Gửi Giám đốc/PM]

Fallback: nếu AI gắn cờ sai hoặc bỏ sót, BA rà lại theo cách cũ (đối chiếu phiếu gốc) trước khi gửi.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | ~66,6 giờ/đợt (ước tính, chưa xác nhận) | Dưới 20 giờ/đợt | Bấm giờ toàn bộ quy trình cho 1 đợt pilot, so trước/sau |
| Số bước | 7 | 7 (4/7 bước là Rule/script) | Đếm bước trong workflow |
| Số bước thủ công | 7/7 | 2/7 (review bản ghi gắn cờ + duyệt cuối) | Đếm bước con người trực tiếp thao tác dữ liệu |
| Bottleneck chính | Đọc & chuẩn hoá thủ công | BA review bản ghi bị AI gắn cờ | Đo riêng thời gian bước này trước/sau |
| Risk mới | Sai sót do nhập tay | AI gắn cờ sai (bỏ sót/báo nhầm) | Đếm số bản ghi AI gắn cờ sai so với rà thủ công trên mẫu pilot |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | BA phụ trách khảo sát và tổng hợp dữ liệu tại 3 tỉnh/thành, chịu trách nhiệm bàn giao Excel cho Giám đốc và docx cho PM. |
| **Workflow** | Nhận 200 phiếu khảo sát từ 100 công an và 100 UBND xã → đọc và chuẩn hoá dữ liệu → nhập vào Excel → soạn docx → rà lỗi trùng/thiếu → gửi Giám đốc và PM. |
| **Bottleneck** | Đọc và chuẩn hoá dữ liệu từ các phiếu chưa có mẫu chung, chiếm phần lớn thời gian trong baseline ước tính 66,6 giờ/đợt. |
| **Impact** | Một BA mất khoảng 66,6 giờ mỗi đợt khảo sát (ước tính, cần xác nhận lại) để tổng hợp; việc lặp lại mỗi đợt khảo sát mới, ảnh hưởng tiến độ báo cáo cho Giám đốc/PM. |
| **Success Metric** | Giảm tổng thời gian tổng hợp một đợt 200 phiếu từ ~66,6 giờ xuống dưới 20 giờ, không tăng số lỗi trong Excel/docx so với cách làm thủ công. |
| **Boundary** | AI không tự quyết định dữ liệu cuối cùng hoặc tự gửi tài liệu; AI chỉ gắn cờ bản ghi nghi thiếu/trùng để BA review; phạm vi giới hạn ở khâu chuẩn hoá & tổng hợp, không mở rộng sang phân tích nội dung khảo sát. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Success Metric "giảm xuống dưới 20 giờ" chưa nói rõ cách đo từng bước; Impact mới dựa trên 1 baseline cá nhân chưa xác nhận.
- Tôi sửa gì: Bổ sung cách đo cụ thể (bấm giờ pilot 1 đợt thật) ở Before/after impact, và giữ nguyên ghi chú "chưa xác nhận" thay vì nói chắc như số liệu đã kiểm chứng.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: mỗi trường trong phiếu khảo sát có đáp án xác định, việc chuẩn hoá/nhập liệu là tác vụ có kết quả đúng/sai rõ ràng.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: phải phối hợp nhiều nguồn (phiếu công an, phiếu UBND xã), nhiều đầu ra (Excel, docx) và các bước phụ thuộc tuần tự nhau.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao + độ mơ hồ thấp → "Workflow điều phối nhiều bước rõ ràng, chưa chắc cần Agent".
```

**Vì sao (2-3 câu):**

```text
Các bước xử lý dữ liệu khảo sát đi theo một trình tự cố định (đọc → chuẩn hoá → nhập → xuất), không cần AI
tự quyết định bước tiếp theo hay tự gọi nhiều công cụ động. Bài toán phù hợp lắp ráp bằng Rule/script cho
các bước có schema rõ, chỉ thêm AI ở đúng bước phát hiện bất thường (trường thiếu, ý trùng).
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Form/schema chuẩn hoá đầu vào (Microsoft Forms) + Power Query làm sạch + mail merge xuất docx | Nếu ≥70-80% phiếu có thể nhập qua form chuẩn ngay từ đầu | Phiếu giấy cũ/đã thu thập trước đó không đi qua form nên vẫn cần nhập tay một phần | Chọn — dùng cho bước 1-3 và 6 (chuẩn hoá, làm sạch, xuất docx) |
| **Workflow** | Rule ở các bước chuẩn hoá/xuất + AI hỗ trợ gắn cờ bản ghi thiếu/trùng ý ở giữa quy trình, người review trước khi gửi | Khi các bước đã rõ và chỉ cần AI hỗ trợ đúng 1-2 bước ngôn ngữ/phát hiện bất thường | AI gắn cờ sai (bỏ sót hoặc báo nhầm) | **Chọn** — dùng cho toàn bộ pipeline, AI chỉ ở bước 4 |
| **Agent** | AI tự đọc phiếu gốc, tự quyết định cách chuẩn hoá, tự tạo và gửi tài liệu | Nếu định dạng phiếu quá đa dạng, cần AI tự lập kế hoạch xử lý theo từng loại phiếu | Rủi ro cao: có thể tự diễn giải sai câu trả lời khảo sát, tự gửi tài liệu chưa được duyệt | Không chọn ở giai đoạn này |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Có, với các phiếu chuẩn hoá được qua form/schema cố định (phần lớn phiếu công an và UBND xã dùng chung bộ câu hỏi); phần phiếu giấy cũ/chữ viết tay khó đọc vẫn cần người xử lý.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Đi thẳng một đường: đọc → chuẩn hoá → nhập → xuất → rà soát → gửi, không có bước cần AI tự quyết định rẽ nhánh động.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Không; toàn bộ trình tự cố định, chỉ cần một bước AI hỗ trợ phát hiện bất thường, không cần AI tự gọi nhiều công cụ hay tự lập kế hoạch.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? BA là người review các bản ghi bị AI gắn cờ trước khi xuất file, phát hiện ngay ở bước review (ước tính vài phút/bản ghi bị gắn cờ).
5. Có hạ được từ Agent → Workflow → Rule không? Có; nếu bước AI gắn cờ không hiệu quả, có thể hạ hoàn toàn về Rule (Power Query + rà thủ công theo checklist) mà vẫn hoàn thành được công việc.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Các bước xử lý dữ liệu khảo sát đã tách rõ và phần lớn xử lý được bằng Rule (form chuẩn hoá, Power Query,
mail merge). AI chỉ cần hỗ trợ đúng một bước ngôn ngữ/phát hiện bất thường (trường thiếu, ý trùng diễn đạt
khác nhau) mà Rule khó làm tốt. BA vẫn giữ vai trò review trước khi gửi nên rủi ro được kiểm soát, và có thể
hạ về Rule thuần nếu AI không hiệu quả.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Chỉ dùng Rule/template thuần tuý (không có bước AI) sẽ khó xử lý phần phát hiện ý trùng/thiếu diễn đạt khác
nhau giữa các phiếu (candidate #6), vì đây là việc cần hiểu ngữ nghĩa chứ không chỉ so khớp từ khoá — nên
Workflow (Rule + 1 bước AI hỗ trợ) phù hợp hơn Rule đơn thuần.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | BA phụ trách khảo sát và tổng hợp dữ liệu tại 3 tỉnh/thành, chịu trách nhiệm bàn giao Excel cho Giám đốc và docx cho PM. |
| **Workflow** | Nhận 200 phiếu (100 công an + 100 UBND xã) → nhập qua form/schema chuẩn → Power Query làm sạch & gộp → AI gắn cờ bản ghi nghi thiếu/trùng ý → BA review & duyệt → mail merge xuất Excel/docx → gửi Giám đốc/PM. |
| **Bottleneck** | Đọc và chuẩn hoá dữ liệu từ các phiếu chưa có mẫu chung — chiếm phần lớn baseline ước tính 66,6 giờ/đợt; sau khi có form chuẩn, bottleneck mới dự kiến chuyển sang bước BA review bản ghi bị gắn cờ. |
| **Impact** | Một BA mất khoảng 66,6 giờ mỗi đợt khảo sát (ước tính, cần xác nhận lại) cho việc tổng hợp; lặp lại mỗi đợt khảo sát mới, ảnh hưởng tiến độ báo cáo cho Giám đốc/PM. |
| **Success Metric** | Giảm tổng thời gian tổng hợp một đợt 200 phiếu từ ~66,6 giờ xuống dưới 20 giờ, không tăng số lỗi trong Excel/docx; đo bằng cách bấm giờ toàn bộ quy trình cho 1 đợt pilot (100-200 phiếu) trước và sau khi áp dụng form chuẩn + Power Query + AI gắn cờ. |
| **Boundary** (làm / không làm) | Làm: chuẩn hoá input, làm sạch dữ liệu, gắn cờ bản ghi nghi thiếu/trùng, xuất Excel/docx theo template. Không làm: AI không tự sửa dữ liệu, không tự quyết định bản ghi cuối, không tự gửi tài liệu, không phân tích nội dung khảo sát. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau bước dữ liệu đã được chuẩn hoá và làm sạch bằng Power Query, trước bước BA duyệt cuối để xuất docx — AI chỉ gắn cờ bản ghi nghi thiếu/trùng ý, không tự sửa dữ liệu. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — vì các bước cố định và phần lớn xử lý được bằng Rule, chỉ cần AI hỗ trợ đúng một bước ngôn ngữ mà Rule khó làm tốt. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI gắn cờ sai (bỏ sót bản ghi lỗi thật hoặc báo nhầm bản ghi đúng); BA kiểm tra bằng cách đối chiếu các bản ghi bị gắn cờ với phiếu gốc trước khi xuất file cuối. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor (BA) và workflow 7 bước đã mô tả cụ thể ở Phase 3.1 và 5.1. |
| Baseline + metric đo được chưa? | Not Yet | Baseline 66,6 giờ/đợt mới là ước tính cá nhân, chưa được bấm giờ/kiểm chứng trên pilot thật. |
| Data/input đủ dùng chưa? | Not Yet | Chưa có mẫu phiếu khảo sát thật hoặc dữ liệu mẫu để thử form chuẩn hoá và Power Query. |
| AI sai, hậu quả chấp nhận được không? | Yes | AI chỉ gắn cờ, không tự sửa/gửi, nên nếu sai chỉ tốn thêm thời gian review, không gây hậu quả nghiêm trọng. |
| Có người review/owner không? | Yes | BA là người duyệt cuối trước khi gửi Giám đốc/PM. |
| Có cách non-AI đơn giản hơn không? | Yes | Form chuẩn hoá + Power Query + mail merge có thể giải quyết phần lớn vấn đề mà chưa cần AI. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Baseline 66,6 giờ/đợt hiện chỉ là ước tính cá nhân chưa được kiểm chứng (xem Phase 4.1), và nhóm chưa có
mẫu phiếu khảo sát thật để thử nghiệm form chuẩn hoá và Power Query. Tuy nhiên actor, workflow đã rõ, rủi ro
nếu AI sai thấp (vì AI chỉ gắn cờ, không tự quyết định), và đã có hướng non-AI rõ ràng — nên bài toán khả thi
để tiếp tục ngay sau khi validate lại baseline và có dữ liệu mẫu, chưa đủ điều kiện Go ngay.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Dùng dữ liệu mẫu ẩn danh từ 1 đợt khảo sát nhỏ (khoảng 20-30 phiếu): nhập qua form chuẩn → Power Query làm
sạch → AI gắn cờ bản ghi nghi thiếu/trùng → BA review → xuất thử Excel/docx. Đo 3 số: (1) tổng thời gian xử
lý đợt nhỏ so với cách làm tay, (2) số bản ghi AI gắn cờ đúng/sai so với rà thủ công, (3) số lỗi còn sót
trong Excel/docx sau khi xuất.
```

**Nếu Not Yet — cần validate gì trước:**

```text
(1) Phỏng vấn nhanh 2-3 BA để xác nhận lại baseline thời gian và bước tốn nhất trong quy trình hiện tại.
(2) Xin mẫu phiếu khảo sát thật (ẩn danh) để thử form chuẩn hoá và Power Query. (3) Đo thử tỷ lệ ý trùng/
thiếu thật trên một đợt dữ liệu mẫu để biết bước rà lỗi có đáng đưa AI vào hay không.
```

**Nếu No-Go — làm gì thay AI:**

```text
Chỉ dùng form chuẩn hoá + Power Query + mail merge (toàn Rule), bỏ hẳn bước AI gắn cờ; BA tự rà theo
checklist thủ công trước khi gửi Giám đốc/PM.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu sau 2 đợt pilot, AI gắn cờ sai quá nhiều (ước tính trên 30% bản ghi bị gắn cờ sai hoặc bỏ sót lỗi thật)
hoặc BA vẫn phải rà lại toàn bộ như cách cũ, nhóm dừng bước AI và quay về quy trình Rule thuần (form +
Power Query + rà thủ công theo checklist).
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
