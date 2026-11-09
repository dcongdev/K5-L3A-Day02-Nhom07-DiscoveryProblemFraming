# Báo cáo cá nhân — 2A202603719_NguyenThiThuHa

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Thị Thu Hà
- MSSV:2A202603719
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:nhóm 7
- Link repo nhóm: https://github.com/dcongdev/K5-L3A-Day02-Nhom07-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại | Khi bắt đầu mỗi ngày học, tôi muốn vào nhiều chỗ (nhóm Zalo/google classroom, email, LMS) để kiểm tra thông báo về lớp học, deadline |Tôi, các bạn cùng lớp |Mỗi ngày mất tầm 5-10 phút kiểm tra |
| 2 |Tốn thời gian |Khi đăng ký tín chỉ đầu mỗi kỳ học, tôi muốn sắp xếp thời khóa biểu để không bị trùng lịch và còn chỗ, để đủ tín chỉ mà không mất nhiều thời gian xếp đi xếp lại  |tôi, các bạn sinh viên | Mất 30-40 phút để xếp trong một lần,có 2 lần tôi phải xếp lại vì lớp đầy,kỳ trước  đăng ký trượt một lớp đại cương|
| 3 |Tốn thời gian |Khi làm báo cáo thí nghiệm Vật lý, tôi muốn xử lý số liệu, vẽ đồ thị và tính sai số nhanh để dành thời gian cho phần phân tích kết quả |Sinh viên các ngành liên quan đến vật lý |Mất khoảng 30-40 phút tính sai số , vẽ đồ thị cho một bài |
| 4 |Cần đọc,tổng hơp nhiều thông tin |Khi đọc paper tiếng Anh cho đồ án, tôi muốn ghi chú ý chính của từng bài ở một chỗ để lúc viết phần tổng quan tìm lại nhanh, trích dẫn đúng |Sinh viên năm cuối làm đồ án, sinh viên làm nghiên cứu khoa học |Trung bình 1 bài paper phải đọc lại 4-5 lần vì không nhớ ý chính là gì |
| 5 |Pain từ người khác |Khi làm bài tập lớn theo nhóm, tôi muốn biết ai đang làm phần nào và tiến độ đến đâu, để không phải nhắc từng người và không dồn việc sát deadline |Nhóm trưởng, các thành viên nhóm |Kỳ trước có 3 bài nhóm, mỗi bài mất tầm 5 phút nhắc việc/ ngày, 1 lần phải làm thay phần người khác do sát hạn nộp bài vẫn chưa xong |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đăng ký tín chỉ (#2)|Quy trình rõ, có bằng chứng |Phụ thuộc hệ thống của trường, khó can thiệp |
| 2 |Thông báo rải rác nhiều kênh (#1) |Sinh viên nào cũng gặp, lặp lại mỗi ngày |Mỗi ngày mất khoảng 5-10 phút, chưa chắc đủ nghiêm trọng để cần giải pháp |
| 3 | Theo dõi tiến độ bài nhóm (#5)|Có pain từ nhiều người, có hậu quả thật (làm thay) |có thể làm vấn đề con người, không phải công  |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đăng ký tín chỉ đầu mỗi kỳ học, tôi muốn sắp xếp thời khóa biểu để không bị trùng lịch và còn chỗ, để đủ tín chỉ mà không mất nhiều thời gian xếp đi xếp lại |
| Actor |Sinh viên tự đăng ký tín chỉ |
| Thời điểm / bối cảnh |Đầu mỗi kỳ, khi trường mở cổng đăng ký; nhiều sinh viên vào cùng lúc, lớp đầy nhanh |
| Quy trình hiện tại (3–7 bước) |1. Xem chương trình đào tạo, chọn môn cần học -> 2. Xem danh sách lớp mở -> 3. Xếp thời khóa biểu thử -> 4. Canh giờ mở cổng, đăng ký -> 5.Lớp đầy hoặc trùng thì xếp lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5 lớp đầy -> phải xếp lịch ~20 phút, đã từng xếp lại 2 lần nguyên nhân do bước 3 không chuẩn bị phương án dự phòng|
| Impact (nếu không giải thì sao) |Mất 1-2 tiếng mỗi kỳ; kỳ trước đăng ký trượt 1 môn đại cương phải học bù kỳ sau, ảnh hưởng tiến độ ra trường |
| Success metric (baseline → target) |Thời gin xếp lịch: 30-40 phút/ lần, xếp lại 2 lần -> dưới 5 phút, có phương án dự phòng, không trượt lớp nào |
| Phương án không dùng AI |Lập sẵn 2-3 phương án thời khóa biểu dự phòng trước ngày mở cổng |
| Giả thuyết về AI (nếu có) |Công cụ tự đề xuất các tổ hợp lớp không trùng lịch khi có danh sách lớp  |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
[1] Xem CTĐT, chọn môn        ~5 phút
      ↓
[2] Xem danh sách lớp mở      ~10 phút
      ↓
[3] Xếp TKB thử               ~30–40 phút   ⚠ BOTTLENECK
      ↓
[4] Canh giờ mở cổng, đăng ký ~10 phút
      ↓
[5] Lớp đầy/trùng → quay lại [3]   (đã xảy ra 2 lần)  ⚠ BOTTLENECK
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu mỗi ngày học, tôi muốn xem hết thông báo lớp và deadline ở một chỗ, để không bỏ sót bài nộp hay thay đổi lịch học |
| Actor | Sinh viên học nhiều môn cùng lúc, mỗi môn dùng kênh thông báo khác nhau (bản thân mình, các bạn cùng lớp) |
| Thời điểm / bối cảnh | Hằng ngày trong kỳ học; giảng viên đăng thông báo ở Zalo, Google Classroom, email hoặc LMS tùy môn |
| Quy trình hiện tại (3–7 bước) | 1. Mở nhóm Zalo các lớp → 2. Mở Google Classroom → 3. Kiểm tra email → 4. Vào LMS → 5. Tự ghi deadline vào lịch/ghi chú |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1: lướt Zalo, tin thông báo bị trôi giữa tin nhắn nói chuyện, khó tìm (~5 phút/ngày) |
| Impact (nếu không giải thì sao) | Mất 5–10 phút/ngày (~1 tiếng/tuần); nguy cơ bỏ sót deadline hoặc đổi phòng; kỳ này đã nhiều lần suýt lỡ |
| Success metric (baseline → target) | Thời gian kiểm tra: 5–10 phút/ngày qua 4 kênh → dưới 3 phút/ngày; số deadline bị bỏ sót: nhiều lần/kỳ → 0 |
| Phương án không dùng AI | Tự lập 1 Google Calendar/Notion ghi tất cả deadline; đề nghị lớp trưởng ghim thông báo quan trọng trên Zalo |
| Giả thuyết về AI (nếu có) | Tự đọc tin từ các kênh, lọc ra tin thông báo/deadline và gom về một danh sách |
| Cảm nhận nhanh | Workflow (cần đọc hiểu tin nhắn tự do để lọc thông báo, nhưng các bước định sẵn) |

Quy trình nháp hiện tại:

```text
[1] Lướt nhóm Zalo các lớp     ~3–5 phút   ⚠ BOTTLENECK (tin thông báo lẫn tin chat)
      ↓
[2] Mở Google Classroom        ~1–2 phút
      ↓
[3] Kiểm tra email trường      ~1 phút
      ↓
[4] Vào LMS                    ~1 phút
      ↓
[5] Ghi deadline vào lịch      ~1 phút (hay quên bước này)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài tập lớn theo nhóm, tôi muốn biết ai đang làm phần nào và tiến độ đến đâu, để không phải nhắc từng người và không dồn việc sát deadline |
| Actor | Nhóm trưởng bài tập lớn (bản thân mình) và các thành viên nhóm 4 người |
| Thời điểm / bối cảnh | Suốt thời gian làm bài nhóm (khoảng 2 tuần/bài), căng nhất 3–5 ngày trước hạn nộp |
| Quy trình hiện tại (3–7 bước) | 1. Họp/chat chia việc → 2. Mỗi người tự làm → 3. Nhóm trưởng nhắn hỏi tiến độ từng người → 4. Ghép bài → 5. Ai chưa xong thì làm thay/thức khuya sửa |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: hỏi tiến độ từng người, ~5 phút/ngày, không biết ai chậm cho đến sát hạn |
| Impact (nếu không giải thì sao) | Kỳ trước 3 bài nhóm; 1 lần phải làm thay phần người khác sát hạn; chất lượng bài giảm, căng thẳng trong nhóm |
| Success metric (baseline → target) | Thời gian nhắc việc: ~5 phút/ngày → dưới 5 phút/tuần; số lần làm thay sát hạn: 1/kỳ → 0 |
| Phương án không dùng AI | Bảng phân công trên Google Sheets/Trello có cột người làm, hạn con, trạng thái; chốt hạn nội bộ trước hạn thật 2 ngày |
| Giả thuyết về AI (nếu có) | Chưa rõ AI giúp gì; vấn đề chủ yếu là trách nhiệm cá nhân |
| Cảm nhận nhanh | No AI / Rule (bảng phân công + nhắc hạn tự động là đủ) |

Quy trình nháp hiện tại:

```text
[1] Chat chia việc             ~15 phút (1 lần)
      ↓
[2] Mỗi người tự làm           12 ngày
      ↓
[3] Nhóm trưởng hỏi tiến độ    ~5 phút/ngày   ⚠ BOTTLENECK (không thấy ai chậm)
      ↓
[4] Ghép bài                   ~30 phút
      ↓
[5] Ai chưa xong → làm thay    ~1 giờ (đã xảy ra 1 lần)
```

### Card muốn pitch nhất

- Card số: #1
- Vì sao:Vì có bằng chứng (xếp lại 2 lần, đăng ký trượt 1 lớp)
- Câu hỏi muốn nhóm phản biện:“Vấn đề nằm ở hệ thống của trường hay ở cách SV chuẩn bị? Nếu do hệ thống thì mình có can thiệp được không?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Bottleneck thật là lớp đầy khi đăng ký, không phải bước xếp lịch | Đồng ý một phần | Sửa bottleneck: bước 5 "lớp đầy → xếp lại dưới áp lực thời gian" là nghẽn chính; xếp lịch trước là nguyên nhân phụ vì không có phương án dự phòng |
| Metric chưa có cách đo, baseline chỉ từ 1 người | Đồng ý | Thêm cách đo: bấm giờ lần xếp lịch kỳ tới; hỏi thêm 3–5 bạn cùng khóa để có baseline |
| Tần suất thấp, phương án không AI có thể đã đủ | Chưa đồng ý hẳn | Giữ card nhưng ghi rõ ở "Điều còn chưa chắc": cần kiểm chứng xem lập phương án dự phòng trước có giải được không |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card: #2 Đăng ký tín chỉ, #7 Thông báo rải rác nhiều kênh, #8 Theo dõi tiến độ bài nhóm | Card #7 được gom vào cluster A cùng card của Tài (candidate được chọn); card #7 được dùng làm nguồn đối chiếu ở CP4 (5–10 phút/ngày so với 30–60 phút/ngày của Tài) |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: hỏi Công (#1) "Tiền phòng tính theo công thức cố định, sao không dùng Excel?"; hỏi Tài (#3) "Card ghi 4 app nhưng chỉ liệt kê 3 kênh; 30–60 phút/ngày là đo hay ước lượng?"; hỏi Hùng (#4) "Giảm thời gian chép từ có làm nhớ từ kém đi không?" | Câu hỏi cho Tài giúp nhóm ghi rõ 30–60 phút là số tự thuật và thêm bước bấm giờ 5 ngày để lấy baseline (CP4–CP5); câu hỏi cho Công và Hùng trở thành lý do loại #1 và #4 khi chấm shortlist |
| Nhận phản biện | Câu hỏi tôi nhận được: bảng pitch nhóm (mục 2.1) chưa ghi nhận câu hỏi phản biện nào cho 3 card của tôi; phản biện chính tôi nhận được là từ AI cho card #1 (xem mục 3) | Tôi đã sửa gì: sửa bottleneck card #1 thành bước 5 "lớp đầy → xếp lại dưới áp lực thời gian"; thêm cách đo baseline (bấm giờ kỳ tới, hỏi 3–5 bạn cùng khóa); ghi rõ điều còn chưa chắc về phương án dự phòng |
| Gom cluster / cây OST | Hỗ trợ CP3 (Công phụ trách chính, theo TEAM.md): xếp 3 card của mình vào các cluster | Card #7 vào cluster A (thông báo phân tán) cùng card của Tài; card #8 vào cluster D (theo dõi phần việc còn thiếu); card #2 thành cluster E riêng vì chưa có bài tương tự |
| Chọn candidate problem | Tham gia chấm shortlist và chọn candidate cùng nhóm | Nhóm chọn #3 của Tài (theo dõi cập nhật quan trọng trong ngày). Các điểm tôi phản biện (Excel cho #1, hiệu quả học từ cho #4, baseline tự thuật cho #3) nằm trong lý do chọn/loại ở mục 2.4 |
| Kiểm chứng / research | Không phụ trách chính (Tài phụ trách CP4). Card thông báo của tôi được dùng làm một nguồn tự thuật để đối chiếu | Thời gian của tôi (5–10 phút/ngày) thấp hơn nhiều so với Tài (30–60 phút/ngày), là tín hiệu để nhóm không khái quát pain cho mọi học viên và giới hạn phạm vi ở trường hợp của Tài |
| Quy trình nhóm | Không phụ trách chính (Hùng phụ trách CP5) | Quy trình trước/sau là đầu vào cho phần CP6 tôi phụ trách: bottleneck bước 3 (đọc tìm cập nhật ~4/10 phút/lượt) và mô hình before/after giảm khoảng 33–42% |
| Problem Statement | v0 do Hùng phụ trách (CP5); tôi phụ trách chính Problem Statement v1 (CP6, theo TEAM.md) | v1 bổ sung so sánh No AI với Rule, ghi riêng thời gian thiết lập/bảo trì, ngưỡng độ trễ 30 phút cho tin khẩn; boundary làm rõ Rule không hiểu ngữ cảnh thay người dùng; thêm 5 tiêu chí đánh giá |
| Mức can thiệp AI | Phụ trách chính CP6 (theo TEAM.md): ma trận độ mơ hồ × độ phức tạp, so sánh 4 mức No AI / Rule / Workflow / Agent | Đề xuất Rule kết hợp No AI, giữ No AI làm đối chứng; chưa chọn Workflow vì chưa chứng minh phần đọc hiểu còn nghẽn và chưa xác minh quyền dữ liệu; không chọn Agent vì các bước đã mô tả trước được |
| Quyết định | Phụ trách chính phần 4 rủi ro và kết luận; Công, Tài, Hùng hỗ trợ | Kết luận Not Yet: Value rủi ro Cao (chưa khảo sát ngoài nhóm, baseline chưa đo, mô hình mới giảm 33–42% chưa đạt 50%). Đề ra pilot nhỏ nhất và các ngưỡng dừng |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | [cần bạn điền, nếu không dùng ghi "Không dùng"] | | | |
| CP2 Problem Card | Nhờ AI phản biện Problem Card #1 (đăng ký tín chỉ) | Chỉ ra bottleneck thật là lớp đầy khi đăng ký, không phải bước xếp lịch; chỉ ra metric chưa có cách đo và baseline chỉ từ 1 người | Cho rằng tần suất thấp nên phương án không AI có thể đã đủ, chưa tính hậu quả trượt lớp làm chậm tiến độ ra trường | Sửa bottleneck thành bước 5 (lớp đầy → xếp lại dưới áp lực thời gian); thêm cách đo (bấm giờ kỳ tới, hỏi 3–5 bạn cùng khóa); giữ card nhưng ghi rõ cần kiểm chứng phương án dự phòng ở "Điều còn chưa chắc" |
| CP4 Research | [cần bạn điền] | | | |
| CP5 Quy trình | [cần bạn điền] | | | |
| CP5–6 Problem Statement | [cần bạn điền] | | | |
| CP6 Mức can thiệp / quyết định | [cần bạn điền] | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- [docs/01-worksheet.md](../../docs/01-worksheet.md): template và prompt mẫu cho từng mục
- [RULES.md](../../RULES.md), [CHECKPOINTS.md](../../CHECKPOINTS.md), [RUBRIC.md](../../RUBRIC.md)
- [report/team/group_report.md](../team/group_report.md): báo cáo nhóm 07 (CP3–CP6)
- Báo cáo cá nhân Trần Văn Tài, Card #1 (candidate được chọn)
