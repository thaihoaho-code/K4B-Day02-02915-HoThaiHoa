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
| --- | --- | --- |
| Scan cá nhân | Mình list ra 9 vấn đề từ cviec hằng tuần của mình, kiểu check email, lấy note từ PDF, debug vs đi lùng info trên FB/Discord. | Cung cấp cho nhóm mấy candidate có đủ actor, có tgian cụ thể với nhìu góc nhìn để dễ so sánh. |
| Pitch Problem Card | Mình pitch Card #2 note vs công thức từ PDF sang Markdown/LaTeX, baseline là mất 1.5 lần tgian đọc. | Team chốt là bài này input/output ổn đẻ làm prototype, nhưng mà không chọn vì Card lab deadline sát với pain của cả nhóm hơn. |
| Challenge bài của bạn khác | Mình hỏi vụ AI tóm tắt slide có công thức, lỡ nó tóm tắt sai công thức toán mà người dùng không biết, không nhận ra thì nguy hiểm. | Team phải thêm cái bước "human review" và kèm link ảnh gốc làm boundary bắt buộc. |
| Gom trùng / cluster | Gom các candidate của mng lại thành các nhóm. | Nhóm nhìn ra 1 cái pattern chung là info đang bị phân tán quá, cần gom lại thành action. |
| Chọn candidate problem | Cùng các bạn ngồi cân nhắc các shortlist rồi chốt bài gom deadline, gom requirement lab từ Vlearn, Github, Discord... | Team chốt dc cái scope rõ ràng, trải nghiệm thực tế ai cũng có thể bị. |
| Validation / research | Mình phản biện lại mấy cái kết quả phỏng vấn vs tự research về Notion, Gemini, Structured Outputs, với mấy cái nhắc nhở rule-based. | Giúp team bóc tách dc đâu là bằng chứng thật đâu là assumption. |
| Workflow nhóm | Làm facilitator nên mình ráng clear lại cái current workflow, tìm chỗ bottleneck lúc gom requirement, rồi vẽ future workflow có người review. | Thu gọn được workflow từ 6 bước manual xuống còn 4 bước|
| Problem Statement | Góp ý vô phần actor cho rõ là học viên AI20K, source-of-truth lấy ở đâu, field nào cần lấy ra. | Cái PS v0/v1 nó có đủ metric, boundary vs fallback |
| Rule / Workflow / Agent | bàn luận dùng Rule cho mấy cái template, còn AI Workflow thì để xài cho phần extraction. Chưa cần Agent. | Nhóm đi đúng hướng Workflow vì flow cơ bản là tuyến tính. |
| Decision | Cùng team chốt làm pilot nhỏ thôi, AI chỉ tạo ra checklist nháp rùi người học phải tự check lại. | Ra quyết định Go nhưng có điều kiện, giảm thiểu vụ hallucination và fallback về cái `todo.md`. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Mình chỉ ra được điểm khó nhất của workflow: lỡ thông tin trên Vlearn, README và Discord đá nhau thì sao? Team phải chọn rule xác định rõ đâu là source of truth ưu tiên cao nhất thay vì thả cho AI tự đoán hoặc fallback hoặc báo lỗi khi gặp trường hợp này.
```
---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| --- | --- | --- | --- | --- |
| Scan | Đẩy nguyên list 9 việc hằng tuần vô, nhờ gợi ý thêm pain point mình có thể bỏ sót. | Gợi ý thêm được vài chỗ mình quên, kiểu mấy câu hay bị hỏi lại trên forum, note rải rác chưa gom. | Vài gợi ý như "sửa format copy từ PDF" hay "tự update lịch" nghe hợp lý nhưng thực ra chưa có pain thật, chỉ là việc lặt vặt. | Lọc lại theo tiêu chí đo dc thời gian/tần suất, cái nào không đủ pain thì bỏ. |
| Problem Card | Nhờ AI đóng vai reviewer, soi lại actor, workflow trong Card #2. | Chỉ ra vài giới hạn mình đọc PDF lướt qua không để ý | Không tự lường dc vụ bản quyền, với lỗi OCR đọc sai ký hiệu toán mà nhìn lướt khó thấy. | Thêm câu hỏi challenge riêng cho công thức, tính thêm chi phí gọi API |
| Workflow | Nhờ AI vẽ nháp workflow hiện tại vs tương lai, chia rõ đoạn nào người làm đoạn nào AI làm. | Ra dc cái flow nhanh bằng mermaid, dễ hình dung để chỉnh tiếp. | Cứ vài bước là chèn tự động hoá, đòi gắn Agent gọi API dù nhóm chưa cần tới mức đó. | Cắt bớt, giữ lại bước người tự gom input vs human review, không giả định có sẵn API cho Vlearn hay Discord. |
| Research | Bắt AI tìm coi có nhóm nào làm hướng tương tự chưa, có pattern gì lặp lại không. | Chỉ ra được vài hướng như Notion, Gemini Structured Outputs. | không chắc mấy tool đó work được với Vlearn/Discord riêng của nhóm mình. | Chỉ giữ link tự tay bấm vào kiểm tra được thật. |
| Problem Statement | Nhờ AI viết thử draft PS theo đúng format actor/impact/metric. | Lòi ra được mấy chỗ nhóm còn thiếu, kiểu chưa nói rõ source-of-truth hay fallback là gì. | viết PS rộng quá (kiểu quản lý học tập chung chung), với mặc định luôn cái baseline là đúng. | Kéo về đúng 1 lab, ghi rõ nguồn cho từng field, note con số 15-25p là ước lượng, cần đi đo lại thật. |
| Rule / Workflow / Agent | Kêu AI so sánh 3 mức Rule/Workflow/Agent rồi áp dụng vô workflow của nhóm. | Giúp thấy rõ Rule đủ sức làm mấy cái template, AI chỉ cần cho đoạn hiểu ngôn ngữ tự nhiên. | Có xu hướng đẩy về Agent cho có vẻ xịn, dù bài nhóm chưa cần tới mức. | Chốt dùng Workflow, chỗ nào chuẩn hoá dc thì gắn Rule, còn lại bắt buộc user tự duyệt bản nháp. |
| Decision | Nhờ AI rà lại xem đủ điều kiện Go/No-Go chưa, liệt kê hộ rủi ro nếu AI trả sai. | List khá rõ ai là người review, input lấy từ đâu, metric nào cần theo dõi. | Tới đoạn nguồn tin đá nhau, kiểu Vlearn với Discord nói khác nhau, thì AI chịu, không biết nghe bên nào. | Chốt Go có điều kiện: pilot nhập tay trước, có người review cuối, vẫn giữ đường lùi về làm thủ công. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):

* Tôi học được gì khi nghe top 3 problems của các bạn khác?
* Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
* Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
* Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
* Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
* Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Lúc mới scan mình chỉ nhìn theo hướng cá nhân, kiểu tìm kiếm thông tin trên FB/Discord với trich PDF sang note, vì đó là việc mình làm hằng tuần nên thấy dễ nhất. Nghe top 3 problems của mọi người xong mới nhận ra mấy cái pain khác nhau cuối cùng đều quy về 1 chỗ: info nằm rải rác nhiều nguồn, phải tự đi gom lại mới làm dc gì tiếp. Mình pitch bài PDF -> Note vì input/output rõ, dễ đo tgian đọc, nhưng lúc bị challenge vụ AI đọc sai công thức toán mà k ai kiểm lại thì mình thấy phần validate nó nặng hơn mình tưởng, nên đồng ý đổi hướng qua bài gom deadline lab của team. Cái mình thấy rõ dấu tay nhất là lúc phản biện việc gắn Agent tự cào data từ Vlearn vs Discord, vì tụi mình chưa có API, cũng chưa chắc cào được gì cho đúng. Viết Problem Statement mới thấy khó ở chỗ chỉ đo tgian thôi chưa đủ, mỗi con số, mỗi field đưa ra phải kèm theo biết lấy từ nguồn nào để người khác check lại dc. Rút ra dc là AI làm tốt nhất ở đoạn xử lý ngôn ngữ tự nhiên, còn mấy cái template cố định hay nhắc lịch thì nên để Rule làm. Bước human review mình nghĩ nó là chỗ chặn lại nếu AI đọc thiếu file hay hiểu sai deadline. Nếu làm lại, mình sẽ đặt thêm câu hỏi: lỡ thầy update trên Discord mà Vlearn chưa cập nhật thì lấy cái nào làm chuẩn. Với lại cũng nên bắt đo tgian ở nhìu người, nhìu lab khác nhau, chứ không nên chỉ dựa vào 1 con số baseline ước lượng từ 1 người 15-25p.
```
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

