# Báo cáo cá nhân — 2A202603468-DuongVanCong

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.  
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).  
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

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

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

---

## 3\. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| --- | --- | --- | --- |
| 1 | Chốt tiền phòng cuối tháng | Actor rõ; quản lý trên 20 phòng theo CP1; dễ đo thời gian và sai sót. | Bước nghẽn là ghi chỉ số, tính phí hay kiểm tra? |
| 2 | Tìm lại quyết định đã thống nhất | Nhu cầu cụ thể, có thể kiểm tra kết quả bằng nguồn trao đổi gốc. | Quyết định cuối và lý do có được ghi lại đầy đủ không? |
| 3 | Tổng hợp báo cáo từ nhiều nền tảng | Có thể quan sát thời gian tìm và đối chiếu dữ liệu. | Cần xác định loại báo cáo và tần suất thực tế. |

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
| Cảm nhận nhanh | Rule — nhận định ban đầu vì cách tính theo công thức cố định; cần kiểm tra bottleneck. |

Quy trình nháp hiện tại:

```
[Ghi chỉ số: cần 2 phút] → [Tìm chỉ số tháng trước: cần 2 phút]
→ [Tính lượng tiêu thụ: cần 7 phút]
→ [Tính tiền và cộng phí: cần 10 phút] ← BOTTLENECK
→ [Kiểm tra: cần 5 phút] → [Thông báo: cần 4 phút]
Tổng: cần 30 phút/phòng/kỳ, trên 20 phòng.
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
[Xác định quyết định cần tìm: cần 5 phút]
→ [Xác định kênh/thời gian: cần 5 phút] → [Tìm từ khóa: cần 5 phút]
→ [Đọc trao đổi: cần 7 phút]
→ [Đối chiếu kết luận cuối: cần 20 phút] ← BOTTLENECK
→ [Hỏi người liên quan nếu chưa rõ: cần khoảng 15 phút]
Tổng: cần 37 phút/lần;
```

### Problem Card #3

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi tổng hợp báo cáo từ dữ liệu nằm trên Google Drive, GitHub, Discord và LMS, tôi muốn tìm đúng thông tin cần dùng và xác định phiên bản mới nhất, để hoàn thành báo cáo mà không bỏ sót hoặc dùng nhầm dữ liệu. |
| Actor | Người trực tiếp tổng hợp báo cáo; cần xác định loại báo cáo và trách nhiệm thực tế. |
| Thời điểm / bối cảnh | Trước hạn nộp, khi dữ liệu liên quan nằm ở nhiều nền tảng; loại báo cáo và tần suất. |
| Quy trình hiện tại (3–7 bước) | Đọc yêu cầu → mở các nguồn → tìm dữ liệu từng mục → xác định phiên bản mới nhất → tổng hợp → đối chiếu và hoàn thiện. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 3 — tìm dữ liệu từng mục trên nhiều nền tảng, 10 phút/báo cáo. Cần kiểm tra bước xác định phiên bản có phải nguyên nhân chính không. |
| Impact (nếu không giải thì sao) | Có thể tốn thời gian tra cứu, thiếu nội dung hoặc dùng bản cũ và phải sửa báo cáo. |
| Success metric (baseline → target) | Tổng thời gian chuẩn bị: 32 phút/báo cáo, đo từ lúc đọc yêu cầu đến khi đối chiếu xong. Theo dõi số mục thiếu/sai và số lần dùng nhầm phiên bản. |
| Phương án không dùng AI | Mẫu báo cáo thống nhất, danh mục link nguồn theo từng mục, quy ước phiên bản và người cập nhật. |
| Giả thuyết về AI (nếu có) | Nếu đọc và tổng hợp văn bản vẫn là bước nghẽn sau khi tổ chức lại nguồn, thử AI trích xuất có dẫn nguồn. Không tự sửa dữ liệu gốc hoặc tự nộp; người tổng hợp kiểm tra. |
| Cảm nhận nhanh | Chưa biết — ưu tiên kiểm tra No AI/Rule; chỉ cân nhắc Workflow nếu cần đọc hiểu và cách đơn giản hơn chưa đủ. |

Quy trình nháp hiện tại:

```
[Đọc yêu cầu: cần 5 phút] → [Mở các nguồn: cần 7 phút]
→ [Tìm dữ liệu từng mục: cần 10 phút/nền tảng] ← BOTTLENECK
→ [Xác định phiên bản mới nhất: cần 5 phút]
→ [Tổng hợp: cần 10 phút] → [Đối chiếu và hoàn thiện: cần 10 phút]
Tổng: cần 32 phút/báo cáo; cần xác nhận loại báo cáo.
```

### Card muốn pitch nhất

*   Card số:
*   Vì sao:
*   Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| --- | --- | --- |
| Ở problem #1, AI chỉ ra diễn  tả "tin nhắn rất nhiều" còn chung chung. Cần cụ thể hơn về thời gian đọc mỗi sáng, số kênh phải kiểm tra. | Có | Bổ sung miêu tả số đo thực tế. |

---

## 4\. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
| --- | --- | --- |
| Pitch Problem Card |   |   |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: |   |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST |   |   |
| Chọn candidate problem |   |   |
| Kiểm chứng / research |   |   |
| Quy trình nhóm |   |   |
| Problem Statement |   |   |
| Mức can thiệp AI |   |   |
| Quyết định |   |   |

---

## 5\. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| --- | --- | --- | --- | --- |
| CP1 Scan | Review problem | Phân tích những chi tiết còn thiếu trong Job story, Dấu hiệu thật. | Vô tình bỏ qua phần tôi đã làm và nhắc lại rằng tôi chưa làm. | Tôi đã lọc và bổ sung chi tiết thiếu. |
| CP2 Problem Card |   |   |   |   |
| CP4 Research |   |   |   |   |
| CP5 Quy trình |   |   |   |   |
| CP5–6 Problem Statement |   |   |   |   |
| CP6 Mức can thiệp / quyết định |   |   |   |   |

---

## 6\. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7\. Tài liệu tham khảo