# Báo cáo cá nhân — 2A202603468-DuongVanCong


## 1\. Thông tin học viên

*   Họ tên: Dương Văn Công
*   MSSV: 2A202603468
*   Email trường (không bắt buộc, repo có thể để public):
*   Tên nhóm: Nhóm 7
*   Link repo nhóm: https://github.com/dcongdev/K5-L3A-Day02-Nhom07-DiscoveryProblemFraming

---

## 2\. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
| --- | --- | --- | --- | --- |
| 1 | Tốn thời gian | Khi bắt đầu ngày làm việc và có nhiều email, tin nhắn chưa đọc, tôi muốn xác định những thông tin và yêu cầu cần xử lý, để không bỏ sót việc quan trọng. | Cả team | Email, chat(Zalo, Slack, Teams) nội bộ gửi tin nhắn rất nhiều mỗi sáng. |
| 2 | Tốn thời gian | Khi chốt tiền phòng cuối tháng, tôi muốn đối chiếu chỉ số điện nước và các khoản phí của từng phòng, để tính đúng số tiền cần thu. | Chủ trọ | Quản lý >20 phòng; thời gian tính; lần sai hoặc thiếu khoản phí. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi cần tìm lại một quyết định đã thống nhất, tôi muốn biết nội dung cuối cùng và lý do chọn, để không làm theo thông tin cũ hoặc hỏi lại đồng nghiệp. | Nhân viên | Số lần tìm mỗi tuần; thời gian tìm; lần dùng nhầm thông tin. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp báo cáo từ dữ liệu nằm trên Google Drive, GitHub, Discord và LMS, tôi muốn tìm đúng thông tin cần dùng và xác định phiên bản mới nhất, để hoàn thành báo cáo mà không bỏ sót hoặc dùng nhầm dữ liệu. | Người tổng hợp báo cáo | Dữ liệu, báo cáo được lưu ở nhiều nơi khác nhau như: Google Drive, Github, Discord, LMS |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn một chủ đề đã học, tôi muốn tìm đúng ghi chú và tài liệu liên quan, để dành thời gian hiểu bài thay vì tìm kiếm. | Sinh viên | Số nơi lưu tài liệu; thời gian tìm; tần suất gặp. |

**Sử dụng gợi ý từ AI:** Tôi sử dụng AI để rà soát cách diễn đạt Job Story và cấu trúc card. Tôi chọn problem tiền phòng làm card muốn pitch nhất vì actor và quy trình cụ thể, có phương án bảng tính để so sánh.

---

## 3\. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| --- | --- | --- | --- |
| 1 | Chốt tiền phòng cuối tháng | Actor rõ; quản lý trên 20 phòng theo CP1; dễ đo thời gian và sai sót. | Bước nghẽn là ghi chỉ số, tính phí hay kiểm tra? |
| 2 | Tìm lại quyết định đã thống nhất | Nhu cầu cụ thể, có thể kiểm tra kết quả bằng nguồn trao đổi gốc. | Quyết định cuối và lý do có được ghi lại đầy đủ không? |
| 3 | Tổng hợp báo cáo từ nhiều nền tảng | Có thể quan sát thời gian tìm và đối chiếu dữ liệu. | Loại báo cáo và tần suất sử dụng. |

### Problem Card #1

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi chốt tiền phòng cuối tháng, tôi muốn đối chiếu chỉ số điện nước và các khoản phí của từng phòng, để tính đúng số tiền cần thu. |
| Actor | Chủ trọ trực tiếp quản lý và tính phí cho trên 20 phòng. |
| Thời điểm / bối cảnh | Cuối mỗi tháng, khi tổng hợp tiền thuê, điện nước và phí dịch vụ. |
| Quy trình hiện tại (3–7 bước) | Ghi chỉ số → tìm chỉ số tháng trước → tính lượng tiêu thụ → tính tiền và cộng phí → kiểm tra → thông báo số tiền. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 4 — tính tiền và cộng phí từng phòng, 17 phút/kỳ. |
| Impact (nếu không giải thì sao) | Tốn thời gian mỗi kỳ; có nguy cơ tính thiếu hoặc sai phí và phải thông báo lại. |
| Success metric (baseline → target) | Tổng thời gian chốt phí: khoảng 30 phút/phòng/kỳ, đo từ lúc tổng hợp chỉ số đến khi kiểm tra xong toàn bộ hóa đơn. |
| Phương án không dùng AI | Bảng tính có công thức cố định, lưu chỉ số theo tháng và checklist kiểm tra trước khi thông báo. |
| Giả thuyết về AI (nếu có) | Nếu nhập chỉ số từ giấy/ảnh là bước nghẽn, thử nhận dạng số để hỗ trợ nhập liệu, chủ trọ đối chiếu lại. |
| Cảm nhận nhanh | Rule — vì cách tính theo công thức cố định. |

Quy trình nháp hiện tại:

```
[Ghi chỉ số: 2 phút] → [Tìm chỉ số tháng trước: cần 2 phút]
→ [Tính lượng tiêu thụ: 7 phút]
→ [Tính tiền và cộng phí: 10 phút] ← BOTTLENECK
→ [Kiểm tra: 5 phút] → [Thông báo: cần 4 phút]
Tổng: 30 phút/phòng/kỳ, trên 20 phòng.
```

### Problem Card #2

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi cần tìm lại một quyết định đã thống nhất, tôi muốn biết nội dung cuối cùng và lý do chọn, để không làm theo thông tin cũ hoặc hỏi lại đồng nghiệp. |
| Actor | Nhân viên tham gia dự án và cần tra cứu quyết định của nhóm; |
| Thời điểm / bối cảnh | Khi tiếp tục công việc hoặc cần xác nhận hướng đã chốt sau nhiều cuộc trao đổi; |
| Quy trình hiện tại (3–7 bước) | Xác định quyết định cần tìm → xác định kênh/thời gian → tìm từ khóa → đọc trao đổi → đối chiếu kết luận cuối → hỏi người liên quan nếu chưa rõ. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 5 — phân biệt phương án thảo luận với quyết định cuối, 20 phút/lần. |
| Impact (nếu không giải thì sao) | Có thể chậm bắt đầu việc, hỏi lại đồng nghiệp hoặc làm theo thông tin cũ. |
| Success metric (baseline → target) | Thời gian tìm và xác nhận quyết định: 37 phút/lần. Ghi thời gian các lần tra cứu; chỉ tính thành công khi có nguồn xác nhận kết luận cuối. |
| Phương án không dùng AI | Nhật ký quyết định chung có ngày chốt, nội dung, lý do, người xác nhận và link nguồn; dùng tìm kiếm từ khóa. |
| Giả thuyết về AI (nếu có) | Hỗ trợ tìm và tổng hợp hội thoại nếu tìm kiếm thường chưa đủ. Phải dẫn nguồn; thiếu bằng chứng phải báo chưa xác định, không tự suy diễn quyết định. |
| Cảm nhận nhanh | Chưa biết — thử nhật ký quyết định và tìm kiếm sẵn có trước khi cân nhắc Workflow. |

Quy trình nháp hiện tại:

```
[Xác định quyết định cần tìm: 5 phút]
→ [Xác định kênh/thời gian: 5 phút] → [Tìm từ khóa: cần 5 phút]
→ [Đọc trao đổi: 7 phút]
→ [Đối chiếu kết luận cuối: 20 phút] ← BOTTLENECK
→ [Hỏi người liên quan nếu chưa rõ: khoảng 15 phút]
Tổng: 37 phút/lần;
```

### Problem Card #3

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi tổng hợp báo cáo từ dữ liệu nằm trên Google Drive, GitHub, Discord và LMS, tôi muốn tìm đúng thông tin cần dùng và xác định phiên bản mới nhất, để hoàn thành báo cáo mà không bỏ sót hoặc dùng nhầm dữ liệu. |
| Actor | Người trực tiếp tổng hợp báo cáo. |
| Thời điểm / bối cảnh | Trước hạn nộp, khi dữ liệu liên quan nằm ở nhiều nền tảng; loại báo cáo và tần suất. |
| Quy trình hiện tại (3–7 bước) | Đọc yêu cầu → mở các nguồn → tìm dữ liệu từng mục → xác định phiên bản mới nhất → tổng hợp → đối chiếu và hoàn thiện. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 3 — tìm dữ liệu từng mục trên nhiều nền tảng, 10 phút/báo cáo. |
| Impact (nếu không giải thì sao) | Có thể tốn thời gian tra cứu, thiếu nội dung hoặc dùng bản cũ và phải sửa báo cáo. |
| Success metric (baseline → target) | Tổng thời gian chuẩn bị: 32 phút/báo cáo, đo từ lúc đọc yêu cầu đến khi đối chiếu xong. Theo dõi số mục thiếu/sai và số lần dùng nhầm phiên bản. |
| Phương án không dùng AI | Mẫu báo cáo thống nhất, danh mục link nguồn theo từng mục, quy ước phiên bản và người cập nhật. |
| Giả thuyết về AI (nếu có) | Nếu đọc và tổng hợp văn bản vẫn là bước nghẽn sau khi tổ chức lại nguồn, thử AI trích xuất có dẫn nguồn. Không tự sửa dữ liệu gốc hoặc tự nộp; người tổng hợp kiểm tra. |
| Cảm nhận nhanh | Chưa biết — ưu tiên kiểm tra No AI/Rule; chỉ cân nhắc Workflow nếu cần đọc hiểu và cách đơn giản hơn chưa đủ. |

Quy trình nháp hiện tại:

```
[Đọc yêu cầu: 5 phút] → [Mở các nguồn: cần 7 phút]
→ [Tìm dữ liệu từng mục: 10 phút/nền tảng] ← BOTTLENECK
→ [Xác định phiên bản mới nhất: 5 phút]
→ [Tổng hợp: 10 phút] → [Đối chiếu và hoàn thiện: cần 10 phút]
Tổng: 32 phút/báo cáo.
```

### Card muốn pitch nhất

*   Card số: #1
*   Vì sao: Bài toán chốt tiền phòng có actor cụ thể là chủ trọ quản lý trên 20 phòng, diễn ra lặp lại hằng tháng và có quy trình dễ mô tả. Có thể đo thời gian tính, đối chiếu phí và số hóa đơn phải sửa để đánh giá mức độ cần giải quyết. Bài toán cũng có phương án đơn giản như bảng tính với công thức cố định để so sánh trước khi cân nhắc AI.
*   Câu hỏi muốn nhóm phản biện: Bước nghẽn thực sự nằm ở thu thập chỉ số, tính tiền hay kiểm tra các khoản phí; nếu dùng bảng tính có công thức sẵn và checklist thì đã đủ giải quyết chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| --- | --- | --- |
| Ở problem #1, AI chỉ ra diễn  tả "tin nhắn rất nhiều" còn chung chung. Cần cụ thể hơn về thời gian đọc mỗi sáng, số kênh phải kiểm tra. | Có | Bổ sung miêu tả số đo thực tế. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
| --- | --- | --- |
| Pitch Problem Card | Chuẩn bị ba card cá nhân: chốt tiền phòng, tìm quyết định cũ và tổng hợp báo cáo đa nguồn; chọn card tiền phòng để đề cử. Tổng hợp card của bốn thành viên vào bảng pitch với sự hỗ trợ của AI. | Mục 2.1 báo cáo nhóm có 12 candidate để so sánh. |
| Phản biện bài của bạn khác | Tổng hợp câu hỏi rà soát các candidate, tập trung vào phạm vi thời gian 30–60 phút/ngày của bài Tài. | Câu hỏi rà soát: thời gian này gồm đọc/lọc tin hay cả trả lời và xử lý việc? |
| Nhận phản biện | Nhận góp ý từ AI về đơn vị thời gian trong card tiền phòng và việc phân biệt bottleneck với tổng quy trình. | Nhận ra ảnh hưởng của đơn vị phút/phòng, phút/kỳ và tổng số phòng đến cách đánh giá pain. |
| Gom cluster / cây OST | Phụ trách chính CP3 theo TEAM.md; tổng hợp bảng cluster với AI hỗ trợ, gom các candidate theo pain thay vì tên công cụ. | Mục 2.2 có sáu cluster theo các nhóm pain. |
| Chọn candidate problem | Cập nhật lựa chọn nhóm đã chốt là problem của Tài; tổng hợp shortlist, lý do chọn và lý do chưa ưu tiên bài B1, tiền phòng. | Báo cáo chung tập trung một problem; bảng điểm có AI hỗ trợ soạn. |
| Kiểm chứng / research | Được phân công hỗ trợ Tài ở CP4 kiểm chứng; tổng hợp vào báo cáo assumption map, dữ liệu tự thuật hiện có và giới hạn bằng chứng. | Mục 3 phân biệt trải nghiệm thành viên với kiểm chứng ngoài nhóm; ghi rõ chưa phỏng vấn/survey. Tài là người phụ trách chính CP4 theo phân công. |
| Quy trình nhóm | Phụ trách ghép phần CP5 vào báo cáo chung; Hùng phụ trách chính, Tài hỗ trợ mô tả quy trình theo TEAM.md. | Mục 4 thể hiện quy trình hiện tại/tương lai, before/after, bước kiểm tra và fallback; thời gian tương lai là kỳ vọng. |
| Problem Statement | Được phân công hỗ trợ Hùng ở v0; tổng hợp v0/v1 có AI hỗ trợ, đối chiếu các trường với cấu trúc báo cáo. | Mục 5 và 7 phân biệt baseline tự thuật, target mục tiêu và boundary; v1 làm rõ mức can thiệp và người kiểm tra. |
| Mức can thiệp AI | Tổng hợp phần CP6 theo phân công Hà phụ trách chính, Hùng hỗ trợ; sử dụng AI hỗ trợ trình bày các phương án. | Mục 6 so sánh No AI/Rule/Workflow/Agent, ưu tiên kiểm tra mức đơn giản và chưa mặc định cần AI. |
| Quyết định | Được phân công hỗ trợ Hà ở phần quyết định và tổng hợp kết luận chung. | Báo cáo và TEAM.md ghi Not Yet; căn cứ là thiếu baseline đã đo và kết quả thử, chưa thể kết luận hiệu quả. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| --- | --- | --- | --- | --- |
| CP1 Scan — cá nhân | Rà soát Job Story và dấu hiệu thật của các problem. | Chỉ ra chỗ mô tả nhu cầu còn lẫn giải pháp và bằng chứng chưa cụ thể. | Có lúc nhận xét như thể tôi chưa có cột dấu hiệu thật dù bảng đã có. | Tôi chỉ rõ cột đã có và bổ sung bối cảnh theo trải nghiệm của mình. |
| CP2 Problem Card — cá nhân | Hỗ trợ trình bày ba card, quy trình nháp và review thời gian. | Giúp điền đúng các trường và cân nhắc phương án không AI. | Không biết thời gian thực tế của từng thao tác. | Tôi chọn card #1 và bổ sung số phút cho các thao tác. |
| CP3 Hội tụ — phụ trách chính | Hỗ trợ tổng hợp 12 candidate, gom cluster và trình bày bảng so sánh trong vai trò điều phối, ghi chép. | Chuẩn hóa trình bày từ các file cá nhân. | Điểm và lập luận phản ánh đánh giá từ card, không phải dữ liệu khảo sát. | Tôi cập nhật problem của Tài theo lựa chọn đã chốt và tổng hợp lý do chọn/loại. |
| CP4 Kiểm chứng — hỗ trợ Tài | Tra cứu cách lập assumption map và chuẩn bị câu hỏi phản biện về bằng chứng của problem. | Giúp phân biệt giả định, trải nghiệm cá nhân và dữ liệu kiểm chứng. | Dễ diễn giải trải nghiệm một thành viên thành nhu cầu chung của cả lớp. | Tôi giới hạn nhận định ở trường hợp của Tài và giữ rõ trạng thái chưa khảo sát người ngoài nhóm. |
| CP4 Research — góp ý khi tổng hợp | Tra cứu bổ sung tính năng lọc và tổ chức thông báo để đọc hiểu, góp ý phần research do Tài phụ trách chính và Hùng hỗ trợ. | Giúp đặt câu hỏi liệu tính năng sẵn có đã đủ trước khi cân nhắc AI. | Mô tả tính năng chưa phản ánh hiệu quả trong bối cảnh cụ thể. | Tôi phân biệt khả năng của công cụ với kết quả tiết kiệm thời gian khi tổng hợp báo cáo. |
| CP5 Quy trình — rà soát khi tổng hợp | Nhờ AI gợi ý câu hỏi kiểm tra sự nhất quán của quy trình và bảng before/after; Hùng phụ trách chính, Tài hỗ trợ. | Nhắc đến thời gian rà soát, thao tác thủ công và phương án quay về khi lọc sai. | Có thể đánh giá lợi ích quá cao nếu chỉ tính thời gian đọc tin mà bỏ qua bước kiểm tra. | Tôi đưa thời gian kiểm tra và sửa sai vào phạm vi so sánh, phân biệt thời gian tự thuật với kỳ vọng. |
| CP5 Problem Statement v0 — hỗ trợ Hùng | Dùng AI gợi ý câu hỏi phản biện về actor, bottleneck, baseline, target và boundary. | Giúp rà soát mối liên hệ giữa metric với quy trình. | Đủ các trường chưa có nghĩa là metric đã được đo hoặc giả định đã đúng. | Tôi tập trung góp ý cách phân biệt baseline tự thuật, mục tiêu giảm 50% và cách đo. |
| CP6 Mức can thiệp, v1, eval — góp ý khi tổng hợp | Tra cứu sự khác nhau giữa No AI, Rule, Workflow và Agent để đối chiếu phần Hà phụ trách chính, Hùng hỗ trợ. | Giúp đặt câu hỏi vì sao mức đơn giản hơn chưa đủ và tiêu chí đánh giá có rõ không. | Dễ đề xuất AI dù chưa có bằng chứng Rule hoặc cách tổ chức thủ công không đáp ứng được. | Tôi giữ lập luận so sánh No AI với Rule trước, đồng thời đối chiếu v1 với v0 khi ghép bài. |
| CP6 Quyết định — hỗ trợ Hà | Dùng AI gợi ý câu hỏi phản biện về bốn rủi ro, tính nhất quán của quyết định và ngưỡng dừng. | Giúp đối chiếu mức bằng chứng với kết luận Go/Not Yet/No-Go. | Có thể coi mục tiêu thiết kế là lợi ích đã đạt nếu bỏ qua trạng thái thử nghiệm. | Tôi giữ kết luận Not Yet phù hợp với việc chưa khảo sát, chưa đo hiệu quả và không ghi giảm 50% thành kết quả thực tế. |

---

## 6. Reflection (CP7)


**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua việc tổng hợp các card, tôi thấy những vấn đề có vẻ khác nhau vẫn có thể cùng một pattern. Bài theo dõi cập nhật của Tài và bài thông báo lớp của Hà đều liên quan đến thông tin phân tán. So với bài tiền phòng của tôi, bài được chọn có bối cảnh học tập chung hơn và xảy ra hằng ngày. 

**6.2. Nhóm có lúc nào bị "solution-first" không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong quá trình tổng hợp, tôi cần phân biệt việc chọn problem với việc chọn công cụ. Có thông tin ở nhiều kênh chưa đủ để kết luận phải xây một hệ thống AI gom tin. Báo cáo hiện so sánh cách tổ chức lại công việc, dùng Rule rồi mới cân nhắc Workflow.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Khi nhờ AI review quy trình tiền phòng, tôi nhận được góp ý rằng thời gian phải nói rõ là cho một phòng hay toàn bộ dãy. Tôi nhận ra chỉ ghi tổng phút chưa đủ, vì đơn vị khác nhau làm mức độ pain khác hẳn. Tôi đã điều chỉnh số phút trong card và nhận ra tầm quan trọng của việc ghi đúng đơn vị thời gian.

**6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?**

Nhóm chưa thực hiện phỏng vấn hoặc survey nên tôi không có kết quả người dùng để nhận xét. Trong phần tổng hợp research, điểm đáng chú ý là đã có cách tổ chức và lọc ngay trên từng nền tảng. Điều đó khiến bản phân tích phải xét No AI/Rule trước. 

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điểm khó tôi gặp là nối các mục thành một lập luận thống nhất, thay vì điền đủ ô riêng lẻ. Khoảng 30–60 phút/ngày là tự thuật, còn giảm 50% là mục tiêu; hai thứ không được trình bày như kết quả thử nghiệm. Khi cộng cả thời gian rà soát, phương án cải thiện chưa chắc đạt target. Boundary và cách đo vì vậy phải đi cùng metric, không chỉ nói chung là nhanh hơn.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi đã mất nhiều thời gian để làm rõ lab yêu cầu gì và cách chia việc giữa người phụ trách chính với người hỗ trợ. Nếu làm lại, tôi muốn chốt cách làm sớm hơn: mỗi người chuẩn bị một phần, chia sẻ nội dung và dành thời gian góp ý trước khi ghép. Tôi cũng sẽ ưu tiên kiểm tra đơn vị thời gian, nguồn số liệu và tình trạng kiểm chứng trước, thay vì cố điền đầy báo cáo khi chưa rõ dữ kiện.

**6.7. Hiểu bài: Problem → Quy trình → Metric → Boundary → Mức can thiệp AI → Quyết định**

Bài nhóm tập trung vào việc Tài phải kiểm tra Zalo, Discord và Outlook để tìm cập nhật cần xử lý. Quy trình hiện tại gồm mở kênh, xem tin mới, đọc tìm thông tin liên quan và xác định việc cần làm, với bước đọc tìm cập nhật là bottleneck theo card. Baseline tự thuật là 30–60 phút/ngày; mục tiêu là giảm ít nhất 50% tổng thời gian kiểm tra. Người dùng phải xác nhận nguồn và lịch/deadline; giải pháp không được tự gửi tin, xóa nội dung hoặc thay đổi lịch chưa kiểm tra. Phương án hiện tại so sánh No AI với Rule trước, vì chưa có bằng chứng phải dùng AI đọc hiểu hoặc tự quyết bước tiếp theo. Báo cáo chọn Not Yet do chưa kiểm chứng người dùng và chưa đo được hiệu quả.

---

## 7\. Tài liệu tham khảo

- [Báo cáo nhóm](../team/group_report.md): problem chung, quy trình, v0/v1, phương án và quyết định.
- [TEAM.md](../../TEAM.md): thông tin thành viên và phân công.
- [Worksheet](../../docs/01-worksheet.md), [RULES.md](../../RULES.md) và [Rubric](../../RUBRIC.md): yêu cầu checkpoint, cách dùng AI và tiêu chí chấm.
- Nguồn công cụ tham khảo được tổng hợp ở mục 10 báo cáo nhóm.
