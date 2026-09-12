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
| Scan | Quăng list cviec vô nhờ nó mớm mấy cái pain point tiềm năng. | Gợi ý dc vụ hay hỏi vặt trên forum vs note rải rác, mình nhặt lại 2 ý này. | Mấy cái gợi ý như sửa format copy từ PDF hay tự update lịch nghe dể ăn nhưng chưa có pain thật. | Tự lọc lại, giử mấy cái có số liệu đo đạc dc, bỏ mấy cái ảo ma đi. |
| Problem Card | Kêu AI đóng vai người phản biện để soi mấy cái actor, workflow vs bottleneck. | Giúp mình nhìn ra giới hạn của con người trong cái Card PDF. | Nó k tự lường dc dụ bản quyền, hay lỗi OCR công thức toán nhìn lướt khó thấy. | Mình đắp thêm câu hỏi challenge vụ công thức, chi phí gọi API vs bắt buộc lưu link PDF gốc. |
| Workflow | Nhờ nó draft cái workflow hiện tại/tương lai, chia ranh giới người/AI rõ ràng. | Biểu diễn nhanh dc cái flow: gom nguồn -> bóc tách -> review -> ra checklist. | Cứ hở tí là nó đòi tự động hoá, đòi xài Agent chọc API tè le hệ thống. | Mình chốt giữ lại bước người tự gom input vs human review; k giả định là có API Vlearn hay Discord đâu. |
| Research | Bắt nó search mấy hướng giải pháp coi có pattern gì giống k. | Ra dc mấy cái hay như source citation, notebook, extraction đỡ mắc công tự vọc từ zero. | AI đưa link nhiều khi ảo, với k chắc sp đó nó work vs Vlearn hay Discord kín của nhóm. | Chỉ lấy mấy link check dc thật, tự tay tách cái research evidence ra khỏi mấy cái tự assumption. |
| Problem Statement | Nhờ nó viết draft thử cái PS cho chuẩn format (actor, impact, metric...). | Khui ra dc mấy chỗ còn lấn cấn như thiếu source-of-truth vs fallback. | Bệnh cũ của AI là hay viết PS siêu rông (quản lý học tập), vs cứ mặc định cái baseline là đúng r. | Kéo team lại thu hẹp vô 1 lab, ghi rõ source cho từng món và note con số 15-25p là cái cần phải đi đo lại. |
| Rule / Workflow / Agent | Kêu nó so sánh 3 cái level auto này ốp vô cái workflow của nhóm xem sao. | Clear dc là Rule dư sức làm template, còn AI chỉ nhét vô chỗ hiểu ngôn ngữ tự nhiên thôi. | Nghe mùi nó muốn xúi xài Agent cho nó ngầu, dù bài mình chưa cần lập kế hoạch động gì. | Chốt cứng là xài Workflow, phần nào chuẩn hoá dc thì ốp Rule, vs bắt buộc user phải approve nháp. |
| Decision | Kêu nó rà lại coi đủ đk Go/No-Go chưa và list rủi ro lỡ AI ngáo. | List dc khá rõ ai owner review, input lấy đâu vs metric là gì. | Khi các nguồn (ví dụ Vlearn vs Discord) mà mâu thuẩn nhau thì AI nó ngu lun k biết nghe ai. | Chốt Go có đk: bắt nhập tay pilot, người review cuối, dùng doc gốc làm chân lý vs có đg lùi về text thủ công. |

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
Ban đầu lúc scan mình chỉ chăm chăm vô mấy cái pain point cá nhân kiểu kiếm info trên FB/Discord dạo vs chế PDF sang note, tại bthg làm suốt. Nhưng lúc nghe top 3 problems của mng thì mình mới vỡ lẽ ra là nhìu cái pain khác nhau cuối cùng cũng chung 1 gốc: info nằm rải rác tứ lung tung bắt người học phải đi nhặt rồi mới action dc. Mình từng pitch bài PDF -> Note vì flow nó trong sáng dễ đo time, cơ mà lúc bị challenge vụ AI đọc sai công thức thì mình thấy nó cần validate khoai quá. Thế là chốt luôn chọn bài gom deadline lab của team, vì tự tụi mình là actor lun, data pilot có sẵn lại dể bấm giờ coi bottleneck nằm đâu. Cái phần đóng góp mà mình thấy bự nhất là níu kéo team ko cho làm cái agent bự chà bá đòi tự cào data Vlearn vs Discord. Lúc viết Problem Statement mới thấy chua, đo timer thôi k đủ đâu, output ra cái gì cũng phải kèm cái link source cho ngta double check. Mình rút ra là AI nó chỉ thật sự ngon khúc cấu trúc lại ngôn ngữ tự nhiên, mấy cái template fix cứng hay nhắc lịch cứ táng Rule vô cho nhẹ server. Cái bước human review hông phải gắn vô cho đẹp đội hình, mà nó là cái phanh an toàn lỡ AI nó cắn thiếu file hay đọc lộn deadline. Nấu mà cho làm lại á, mình sẽ dí team mạnh hơn từ đầu cái vụ source-of-truth: lỡ thầy update trên Discord mà Vlearn chưa có thì nghe ai? Với lại cũng phải bắt đi đo timer nhìu người nhìu lab chứ k xài chay cái base 15-25p nữa.

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

