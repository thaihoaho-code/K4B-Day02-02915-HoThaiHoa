# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Hồ Thái Hòa
- Mã học viên: 2A202602915
- Nhóm: Nhóm AI20K — facilitator
- Candidate problem nhóm chọn: Gom deadline và yêu cầu lab từ nhiều nguồn khi học Vlearn và làm Lab trong khóa học AI20K.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 9 vấn đề trong các công việc hằng tuần, trong đó có kiểm tra email, ghi chú từ PDF, debug và tìm thông tin trên Facebook/Discord. | Giúp nhóm có các candidate có actor, số đo thời gian và nhiều góc nhìn để so sánh. |
| Pitch Problem Card | Tôi pitch Card #2 về trích xuất note và công thức từ PDF sang Markdown/LaTeX, với baseline ghi note mất khoảng 1,5 lần thời gian đọc. | Nhóm ghi nhận đây là bài có input/output rõ và dễ prototype, nhưng chưa chọn vì candidate deadline/lab sát domain chung hơn. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về độ chính xác của AI khi tóm tắt slides cùng công thức toán và nguy cơ công thức sai nhưng người dùng không nhận ra. | Nhóm đưa human review và link/ảnh nguồn gốc thành boundary bắt buộc khi dùng AI. |
| Gom trùng / cluster | Tôi cùng nhóm gom các candidate thành các cụm retrieval, research/debugging, productivity và knowledge capture. | Nhóm nhận ra nhiều ý khác nhau cùng có pattern thông tin phân tán phải được chuyển thành hành động. |
| Chọn candidate problem | Tôi tham gia so sánh các shortlist và đồng thuận chọn bài gom deadline, requirement lab từ Vlearn, README, worksheet, Discord và GitHub. | Nhóm chọn được scope cụ thể, gần với trải nghiệm của tất cả thành viên và có thể pilot bằng dữ liệu thật. |
| Validation / research | Tôi tham gia phản biện kết quả interview, self-observation và research về Notion, Gemini Notebook, Structured Outputs và reminder rule-based. | Nhóm phân biệt được bằng chứng trực tiếp với giả định; baseline 15-25 phút/lab được giữ là số cần đo lại trong pilot. |
| Workflow nhóm | Với vai trò facilitator, tôi góp phần làm rõ current workflow, bottleneck ở bước hợp nhất requirement và future workflow có human review. | Workflow được thu hẹp từ 6 bước thủ công xuống 4 bước, với mục tiêu gom requirement + tạo checklist nháp dưới 7 phút. |
| Problem Statement | Tôi góp ý làm rõ actor là học viên AI20K, source-of-truth, input được cung cấp và các field cần trích xuất. | Problem Statement v0/v1 có metric, boundary, fallback và không biến bài toán thành quản lý toàn bộ deadline học tập. |
| Rule / Workflow / Agent | Tôi tham gia đánh giá và ủng hộ dùng Rule cho template/chuẩn hóa, AI Workflow cho semantic extraction, chưa dùng Agent tự trị. | Nhóm chọn đúng mức Workflow vì quy trình tuyến tính nhưng input là ngôn ngữ tự nhiên và có thể mâu thuẫn. |
| Decision | Tôi cùng nhóm chốt pilot có phạm vi nhỏ, AI chỉ tạo checklist nháp và học viên phải đối chiếu trước khi sử dụng. | Quyết định Go có điều kiện, giảm rủi ro hallucination và vẫn có fallback về `todo.md` thủ công. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi đóng góp rõ nhất ở việc đưa ra Card PDF → Markdown/LaTeX và challenge rủi ro AI nhận diện sai công thức, từ đó giúp nhóm coi human review và source trace là bắt buộc. Với vai trò facilitator, tôi cũng góp phần giữ candidate cuối ở scope “gom requirement của một Lab AI20K”, thay vì mở rộng thành một agent quản lý mọi deadline.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các pain point tiềm ẩn từ danh sách công việc hằng tuần. | Gợi ra việc đặt câu hỏi trên diễn đàn và tổng hợp note rải rác, là hai ý tôi giữ lại để xem xét. | Một số gợi ý như sửa format khi copy PDF hoặc cập nhật lịch thủ công chưa có đủ pain evidence. | Tôi tự giữ các vấn đề có số đo và bỏ các ý chỉ nghe có vẻ tiện lợi nhưng chưa phải pain thật. |
| Problem Card | Phản biện cách mô tả actor, workflow, bottleneck và AI hypothesis cho các card. | Giúp tôi nhìn rõ human boundary của Card PDF. | AI không tự biết rủi ro bản quyền, OCR sai công thức hoặc lỗi LaTeX có thể khó phát hiện. | Tôi bổ sung câu hỏi challenge về công thức sai, chi phí API và yêu cầu giữ ảnh/link PDF để đối chiếu. |
| Workflow | Hỗ trợ diễn đạt current/future workflow và phân tách phần người, rule, AI. | Giúp nhóm biểu diễn nhanh việc gom nguồn → trích xuất → review → checklist. | Gợi ý tự động hóa dễ làm scope phình ra thành Agent truy cập mọi hệ thống. | Tôi giữ bước người gom input, bước human review và fallback thủ công; không giả định có API Vlearn/Discord. |
| Research | Hỗ trợ tìm hướng giải pháp và đối chiếu pattern đã có. | Các pattern source citation, notebook theo nguồn, structured extraction và reminder rule-based giúp nhóm tránh build từ đầu. | Kết quả AI không mặc nhiên là bằng chứng; sản phẩm có thể không hỗ trợ Vlearn hoặc Discord private. | Tôi chỉ giữ link có thể kiểm tra, ghi rõ khoảng trống và tách research evidence khỏi số liệu tự quan sát. |
| Problem Statement | Gợi ý cách viết actor, bottleneck, impact, metric và boundary. | Giúp nhóm phát hiện các field còn mơ hồ như source-of-truth và fallback. | AI có xu hướng viết problem rộng như “quản lý deadline học tập” và coi baseline là đã được xác nhận. | Tôi cùng nhóm thu hẹp vào một lab cụ thể, giữ source cho từng mục và ghi baseline 15-25 phút là cần đo lại. |
| Rule / Workflow / Agent | So sánh ba mức tự động hóa trên cùng một workflow. | Làm rõ Rule đủ cho template/reminder, còn AI cần ở bước hiểu ngôn ngữ tự nhiên. | AI có thể mặc định chọn Agent vì nghe mạnh hơn, dù bài toán chưa cần lập kế hoạch động. | Tôi ủng hộ quyết định Workflow, dùng Rule ở phần chuẩn hóa và bắt buộc người học approve checklist. |
| Decision | Kiểm tra các điều kiện Go/Not Yet/No-Go và rủi ro khi AI sai. | Giúp nhóm liệt kê rõ owner review, input pilot và metric đo được. | AI không thể thay nhóm quyết định source nào là đúng khi các nguồn mâu thuẫn. | Nhóm chọn Go có điều kiện: pilot manual input, human review, tài liệu gốc là source-of-truth và có fallback `todo.md`. |

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
Ban đầu tôi tập trung vào các pain point cá nhân như tìm thông tin trên Facebook/Discord và chuyển PDF thành note, vì đó là những việc tôi trực tiếp làm hằng ngày. Khi nghe top 3 của các bạn, tôi nhận ra nhiều vấn đề khác nhau đều quy về việc thông tin nằm rải rác rồi người học phải tự chuyển thành một hành động cụ thể. Tôi pitch bài PDF → Markdown/LaTeX vì workflow rõ và có metric tốt, nhưng sau khi challenge độ chính xác của công thức, tôi thấy nó cần validation kỹ hơn trước khi chọn. Tôi đồng ý chọn bài gom deadline và requirement lab vì actor là chính nhóm, dữ liệu pilot có sẵn và bottleneck có thể đo bằng timer. Đóng góp quan trọng của tôi là giữ cho bài toán không bị mở rộng thành một agent tự truy cập Vlearn, Discord và GitHub. Trong lúc viết Problem Statement, tôi học được rằng metric thời gian chưa đủ; mỗi output quan trọng còn phải giữ source để người dùng kiểm tra. Tôi cũng nhận ra AI hữu ích nhất ở bước đọc và cấu trúc ngôn ngữ tự nhiên, còn template, reminder và format cố định có thể dùng rule đơn giản. Human review không phải phần thừa của workflow mà là boundary để kiểm soát việc AI bỏ sót hoặc hiểu sai deadline, file và field. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về source-of-truth khi Vlearn, README và Discord có thông tin mâu thuẫn. Tôi cũng sẽ đo timer trên nhiều lab và nhiều người trước khi dùng baseline 15-25 phút/lab để kết luận impact.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] [15đ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

