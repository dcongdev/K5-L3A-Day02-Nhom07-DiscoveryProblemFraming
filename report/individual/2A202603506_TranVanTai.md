# Báo cáo cá nhân — 2A202603506_TranVanTai

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Văn Tài
- MSSV: 2A202603506
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom07
- Link repo nhóm: https://github.com/dcongdev/K5-L3A-Day02-Nhom07-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Các vấn đề dưới đây được ghi từ trải nghiệm của tôi. Hiện chưa có bằng chứng cụ thể về pain lặp lại của người khác, nên tôi không gán lăng kính **Pain từ người khác** cho các dòng này.


| # | Lăng kính                                                              | Job Story: Khi…, tôi muốn…, để…                                                                                                                                                                          | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                                                                                                                                                    |
| -: | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 | Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin              | Khi bắt đầu một buổi thực hành, tôi muốn nhanh chóng nắm được yêu cầu và việc cần làm từ các file hướng dẫn, để bắt tay vào bài mà không mất nhiều thời gian dò tài liệu. | Tôi, học viên L3    | Mỗi buổi sáng từ thứ Hai đến thứ Sáu; tôi mất khoảng 15–30 phút để đọc các file Markdown.                                                                                                                            |
| 2 | Tốn thời gian                                                          | Khi có nhiều task và deadline, tôi muốn xác định việc nào cần ưu tiên trước, để hoàn thành bài đúng hạn.                                                                                 | Tôi, học viên L3    | Hôm qua tôi chạm mốc deadline nộp Codelab 02.                                                                                                                                                                                      |
| 3 | Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin              | Khi ôn lại kiến thức của các buổi trước, tôi muốn hệ thống lại những nội dung cần nhớ, để nắm vững và vận dụng được kiến thức.                                                    | Tôi, học viên L3    | Hôm qua tôi dành khoảng 2 giờ đọc lại slide Day 1 và Day 2.                                                                                                                                                                    |
| 4 | Lặp lại · Tốn thời gian                                             | Khi kết thúc mỗi ngày học, tôi muốn kiểm tra những bài tập đã nộp và nhiệm vụ đã hoàn thành, để phát hiện việc còn thiếu và không bỏ sót đầu việc.                           | Tôi, học viên L3    | Mỗi ngày tôi dành khoảng 10 phút để kiểm tra.                                                                                                                                                                                  |
| 5 | Lặp lại · Tốn thời gian                                             | Khi kết thúc mỗi ngày học, tôi muốn xem lịch trình của ngày hôm sau, để chủ động phân bổ thời gian và chuẩn bị trước.                                                                  | Tôi, học viên L3    | Mỗi ngày tôi dành khoảng 10–15 phút để kiểm tra lịch trình.                                                                                                                                                                 |
| 6 | Lặp lại · Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin | Khi có cập nhật trong ngày, tôi muốn nắm được tin nhắn và thay đổi lịch trình quan trọng, để không bỏ lỡ thông tin cần xử lý.                                                         | Tôi, học viên L3    | Tôi kiểm tra 3 kênh: Discord, Outlook và Zalo nhiều lần trong ngày. Mỗi lượt kiểm tra cả 3 kênh mất khoảng 10 phút; do số lượt mỗi ngày không cố định, tổng thời gian dao động khoảng 30–60 phút/ngày. |

**Nếu có dùng AI để gợi ý thêm:** Các problem trong bảng xuất phát từ phần tự scan; tôi dùng AI để rà soát và chỉnh cách diễn đạt Job Story, không thêm problem mới từ gợi ý của AI.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3


| Rank | Problem                                                        | Vì sao chọn                                                                                                                                              | Điều còn chưa chắc                                                                                                                  |
| ---: | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
|    1 | Theo dõi cập nhật trong ngày từ Zalo, Discord và Outlook | Thời gian ghi nhận cao nhất trong các vấn đề đã scan: khoảng 30–60 phút mỗi ngày; tôi phải kiểm tra nhiều kênh nhiều lần trong ngày. | Cần xác định tiêu chí nhận diện cập nhật quan trọng ở từng kênh và cách kiểm tra việc bỏ lỡ thông tin cần xử lý. |
|    2 | Đọc hướng dẫn để nắm yêu cầu và việc cần làm     | Xảy ra mỗi buổi thực hành và hiện mất khoảng 15–30 phút đọc các file Markdown.                                                               | Cần xác định khâu chiếm nhiều thời gian nhất: tìm file, đọc hướng dẫn hay tổng hợp đầu việc.                         |
|    3 | Kiểm tra bài tập đã nộp và nhiệm vụ đã hoàn thành | Là việc lặp lại hằng ngày, khoảng 10 phút mỗi lần; quy trình có thể mô tả và đo được.                                                  | Cần xác định cách rút ngắn thời gian kiểm tra mà vẫn đảm bảo không bỏ sót bài tập hoặc nhiệm vụ.                   |

### Problem Card #1


| Trường                                        | Nội dung                                                                                                                                                                                                                                                                  |
| ----------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                       | Khi có cập nhật trong ngày, tôi muốn nắm được tin nhắn và thay đổi lịch trình quan trọng trên các kênh mình theo dõi, để không bỏ lỡ thông tin cần xử lý.                                                                                   |
| Actor                                           | Tôi, học viên L3 sử dụng Zalo, Discord và Outlook để nhận thông tin.                                                                                                                                                                                             |
| Thời điểm / bối cảnh                       | Nhiều lần trong ngày, khi kiểm tra Zalo, Discord và Outlook.                                                                                                                                                                                                          |
| Quy trình hiện tại (3–7 bước)             | 1. Mở lần lượt Zalo, Discord và Outlook (1 phút). 2. Xem thông báo/tin nhắn mới ở từng kênh (3 phút). 3. Mở nội dung liên quan để tìm cập nhật cần xử lý (4 phút). 4. Xác định thông tin quan trọng và ghi nhớ việc cần làm (2 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, mở và đọc nội dung liên quan để tìm cập nhật cần xử lý, khoảng 4 phút/lượt. Tổng một lượt kiểm tra 3 kênh khoảng 10 phút; số lượt mỗi ngày không cố định nên tổng thời gian ghi nhận khoảng 30–60 phút/ngày.          |
| Impact (nếu không giải thì sao)             | Có nguy cơ bỏ lỡ tin nhắn hoặc thay đổi lịch trình quan trọng;                                                                                                                                                                                                  |
| Success metric (baseline → target)             | Baseline: 30–60 phút/ngày. Ghi thời gian kiểm tra trong 1 tuần để xác định mức trung bình; mục tiêu là giảm ít nhất 50% so với baseline trung bình mà không bỏ lỡ cập nhật cần xử lý.                                                        |
| Phương án không dùng AI                    | Xác định kênh chính cho từng loại thông tin, tắt thông báo không cần thiết và gom các lần kiểm tra những kênh còn lại vào khung giờ cố định.                                                                                                    |
| Giả thuyết về AI (nếu có)                  | AI có thể hỗ trợ rà soát tin mới trên 3 kênh và gợi ý tin nhắn hoặc thay đổi lịch trình cần chú ý; tôi kiểm tra lại trước khi xử lý. Khả năng truy cập dữ liệu và tiêu chí xác định tin quan trọng cần được kiểm chứng.      |
| Cảm nhận nhanh                                | Chưa biết; cần kiểm chứng tiêu chí xác định cập nhật cần xử lý và khả năng truy cập dữ liệu trước khi chọn mức can thiệp.                                                                                                                        |

Quy trình hiện tại:

```text
MỞ ZALO, DISCORD, OUTLOOK (1 phút)
→ XEM TIN MỚI Ở TỪNG KÊNH (3 phút)
→ TÌM CẬP NHẬT CẦN XỬ LÝ (4 phút)
→ XÁC ĐỊNH THÔNG TIN QUAN TRỌNG VÀ VIỆC CẦN LÀM (2 phút)
Tổng khoảng 10 phút/lượt; số lượt kiểm tra mỗi ngày không cố định nên tổng thời gian ghi nhận dao động khoảng 30–60 phút/ngày.
```

### Problem Card #2 — Đọc hướng dẫn để nắm yêu cầu


| Trường                                        | Nội dung                                                                                                                                                                                                                                                          |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story                                       | Khi bắt đầu một buổi thực hành, tôi muốn nhanh chóng nắm được yêu cầu và việc cần làm từ các file hướng dẫn, để bắt tay vào bài mà không mất nhiều thời gian dò tài liệu.                                                    |
| Actor                                           | Tôi, học viên L3 đang làm bài thực hành.                                                                                                                                                                                                                   |
| Thời điểm / bối cảnh                       | Khi bắt đầu mỗi buổi thực hành.                                                                                                                                                                                                                             |
| Quy trình hiện tại (3–7 bước)             | 1. Tìm/mở các file Markdown liên quan (2–4 phút). 2. Đọc hướng dẫn để tìm yêu cầu của buổi (8–15 phút). 3. Xác định các đầu việc cần làm (3–6 phút). 4. Ghi nhớ hoặc ghi lại yêu cầu để bắt đầu thực hành (2–5 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, đọc và dò các file Markdown để tìm yêu cầu của buổi, khoảng 8–15 phút. Tổng thời gian hiện ghi nhận khoảng 15–30 phút/buổi.                                                                                                       |
| Impact (nếu không giải thì sao)             | Mất thời gian trước khi bắt tay vào thực hành và có nguy cơ bỏ sót yêu cầu.                                                                                                                                                                         |
| Success metric (baseline → target)             | Baseline hiện ghi nhận 15–30 phút/buổi. Mục tiêu: giảm ít nhất 50% thời gian trung bình so với baseline đo được, đồng thời vẫn nắm đủ các yêu cầu và đầu việc.                                                                      |
| Phương án không dùng AI                    | Sắp xếp file hướng dẫn theo checkpoint, dùng mục lục và checklist yêu cầu/đầu việc cho mỗi buổi.                                                                                                                                                   |
| Giả thuyết về AI (nếu có)                  | AI có thể hỗ trợ tóm tắt yêu cầu và liệt kê đầu việc từ các file Markdown; tôi cần đối chiếu kết quả với hướng dẫn gốc để tránh thiếu hoặc sai yêu cầu.                                                                         |
| Cảm nhận nhanh                                | Rule hoặc Workflow đơn giản có thể đủ; cần thử mục lục/checklist trước khi cân nhắc AI.                                                                                                                                                            |

Quy trình hiện tại:

```text
TÌM/MỞ FILE HƯỚNG DẪN (2–4 phút)
→ ĐỌC VÀ DÒ YÊU CẦU CỦA BUỔI (8–15 phút)
→ XÁC ĐỊNH CÁC ĐẦU VIỆC (3–6 phút)
→ GHI NHỚ/GHI LẠI ĐỂ BẮT ĐẦU THỰC HÀNH (2–5 phút)
Tổng thời gian ghi nhận: 15–30 phút/buổi.
```

### Problem Card #3 — Kiểm tra bài tập và nhiệm vụ đã hoàn thành


| Trường                                        | Nội dung                                                                                                                                                                                                                                                             |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                       | Khi kết thúc mỗi ngày học, tôi muốn kiểm tra những bài tập đã nộp và nhiệm vụ đã hoàn thành, để phát hiện việc còn thiếu và không bỏ sót đầu việc.                                                                                 |
| Actor                                           | Tôi, học viên L3.                                                                                                                                                                                                                                                  |
| Thời điểm / bối cảnh                       | Cuối mỗi ngày học.                                                                                                                                                                                                                                                |
| Quy trình hiện tại (3–7 bước)             | 1. Xem lại danh sách bài tập và nhiệm vụ cần làm (2 phút). 2. Kiểm tra trạng thái nộp bài và hoàn thành nhiệm vụ (2 phút). 3. Đối chiếu với yêu cầu và deadline (4 phút). 4. Ghi lại việc còn thiếu hoặc cần làm tiếp (2 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đối chiếu yêu cầu và deadline với trạng thái hoàn thành để tìm việc còn thiếu, khoảng 4 phút. Tổng thời gian hiện ghi nhận khoảng 10 phút/ngày.                                                                                   |
| Impact (nếu không giải thì sao)             | Có nguy cơ bỏ sót bài tập hoặc nhiệm vụ.                                                                                                                                                                                                                     |
| Success metric (baseline → target)             | Baseline hiện ghi nhận khoảng 10 phút/ngày. Mục tiêu thử nghiệm: giảm thời gian xuống không quá 5 phút/ngày mà không bỏ sót bài tập hoặc nhiệm vụ; cần theo dõi thời gian và số việc bị bỏ sót để đánh giá.                    |
| Phương án không dùng AI                    | Dùng checklist hằng ngày có tên bài/nhiệm vụ, deadline, trạng thái và liên kết nộp bài.                                                                                                                                                                |
| Giả thuyết về AI (nếu có)                  | Chưa rõ có cần AI; trước tiên có thể thử checklist hoặc Rule nhắc việc dựa trên deadline và trạng thái.                                                                                                                                             |
| Cảm nhận nhanh                                | No AI hoặc Rule có thể đủ; chưa có bằng chứng cho thấy cần Workflow hay Agent.                                                                                                                                                                             |

Quy trình hiện tại:

```text
XEM DANH SÁCH BÀI TẬP VÀ NHIỆM VỤ (2 phút)
→ KIỂM TRA TRẠNG THÁI NỘP BÀI/HOÀN THÀNH (2 phút)
→ ĐỐI CHIẾU YÊU CẦU VÀ DEADLINE (4 phút)
→ GHI LẠI VIỆC CÒN THIẾU HOẶC CẦN LÀM TIẾP (2 phút)
Tổng thời gian ghi nhận: khoảng 10 phút/ngày.
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Đây là vấn đề tôi ghi nhận tốn thời gian nhiều nhất (30–60 phút/ngày) và xảy ra nhiều lần trong ngày.
- Câu hỏi muốn nhóm phản biện: Làm thế nào xác định cập nhật nào thật sự cần xử lý, và liệu gom thời gian kiểm tra thông báo có giảm thời gian mà không làm tôi bỏ lỡ việc quan trọng không?

### AI đã phản biện card thế nào


| Điểm yếu AI chỉ ra                                                                                                                                                               | Đồng ý?           | Đã sửa gì                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tiêu chí “cập nhật quan trọng” và “cần xử lý” chưa được định nghĩa rõ; các loại tin cần chú ý và tình huống cần hành động cần được phân biệt. | Đồng ý một phần | Giữ thay đổi lịch trình là một loại thông tin cần chú ý; bổ sung việc xác định tiêu chí cho các tin nhắn khác và giữ bước người dùng kiểm tra, không để AI tự quyết định. |
| Mục tiêu giảm ít nhất 50% và mục tiêu cố định dưới 20 phút/ngày chưa nhất quán với baseline 30–60 phút/ngày.                                                   | Đồng ý            | Dùng baseline trung bình của một tuần làm mốc, rồi đặt target giảm ít nhất 50% so với mốc đó.                                                                                                 |
| Giả thuyết AI cần quyền truy cập dữ liệu từ cả ba kênh và khả năng nhận diện chính xác cập nhật; AI tự thông báo có thể gây bỏ sót hoặc báo nhầm.      | Đồng ý            | Giới hạn AI ở việc rà soát và gợi ý; người dùng kiểm tra trước khi xử lý. Bổ sung quyền truy cập dữ liệu và tiêu chí nhận diện cập nhật vào các điểm cần kiểm chứng.       |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)


| Hoạt động                     | Tôi đã làm gì?           | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------------- | ----------------------------- | ---------------------------------------- |
| Pitch Problem Card               |                               |                                          |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                          |
| Nhận phản biện                | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                      |
| Gom cluster / cây OST           |                               |                                          |
| Chọn candidate problem          |                               |                                          |
| Kiểm chứng / research          |                               |                                          |
| Quy trình nhóm                 |                               |                                          |
| Problem Statement                |                               |                                          |
| Mức can thiệp AI               |                               |                                          |
| Quyết định                    |                               |                                          |

---

## 5. Dùng AI


| Checkpoint                          | Tôi dùng AI để làm gì?                                                                                                         | AI hữu ích ở đâu?                                                                                                                                                                            | AI sai hoặc hời hợt ở đâu?                                                                                                                                                                                | Tôi sửa gì bằng nhận định của mình?                                                                                                                                                                                                                                                                       |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CP1 Scan                            | Sau khi tự scan, nhờ AI rà soát cách diễn đạt Job Story và tính nhất quán của thông tin.                               | Giúp làm rõ Problem #6 sử dụng đúng 3 kênh Discord, Outlook và Zalo; hỗ trợ chỉnh câu mô tả deadline ở Problem #2 theo sự việc đã xảy ra.                                    | Ban đầu phần nhận xét tập trung vào việc thiếu tần suất đo lặp lại, khiến câu ghi chú dài và không phù hợp với cách trình bày tôi muốn.                                             | Tôi xác nhận thông tin thực tế và sửa dấu hiệu của Problem #2 thành: “Hôm qua tôi chạm mốc deadline nộp Codelab 02.”                                                                                                                                                                            |
| CP2 Problem Card                    | Nhờ AI phản biện Card #1 và rà soát tính nhất quán giữa số kênh, thời lượng mỗi lượt, tổng thời gian và metric. | Phản biện giúp tôi nhận ra cần làm rõ tiêu chí “cập nhật quan trọng”, giữ người dùng kiểm tra trước khi xử lý, và kiểm tra lại mục tiêu thời gian so với baseline. | AI đề xuất phân bổ thời gian từng bước và đánh giá các phản biện quá đồng thuận; các con số này cần được tôi đối chiếu với quy trình thực tế thay vì xem là kết quả đo. | Tôi tự đối chiếu quy trình và chốt mô tả gồm 3 kênh, khoảng 10 phút mỗi lượt; chọn “Đồng ý một phần” với góp ý về tiêu chí cập nhật; sau khi xem lại baseline 30–60 phút/ngày, tôi đặt mục tiêu giảm ít nhất 50% so với mức trung bình ghi nhận trong một tuần. |
| CP4 Research                        |                                                                                                                                      |                                                                                                                                                                                                   |                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                    |
| CP5 Quy trình                      |                                                                                                                                      |                                                                                                                                                                                                   |                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                    |
| CP5–6 Problem Statement            |                                                                                                                                      |                                                                                                                                                                                                   |                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                    |
| CP6 Mức can thiệp / quyết định |                                                                                                                                      |                                                                                                                                                                                                   |                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                    |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?** Mình học thêm được các idea mới từ các bạn, cách viết problem state đúng quy trình, cách xác định painpoint, bottleneck.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.** Mình có đổi ý sau khi bị phản biện, ở phần Problem Card 6 thì lúc đầu mình chọn là Email, nhưng sau khi các bạn có bảo là dùng outlook sẽ tốt hơn vì outlook bao gồm được cả email cá nhân và cả các email trường học hay cơ quan.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?** Điều khó nhất đó là tìm ra các vấn đề quan trọng nhất, có paint point đau nhất và phải làm rõ nó nữa. Các bước đo lường thời gian cụ thể cũng là vấn đề khó.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình. Nhóm chọn problem về việc học viên mất thời gian theo dõi các thông báo quan trọng trên các kênh Discord, Outlook và Zalo. Về quy trình hiện tại là mở ba kênh, xem tin mới, tìm thông tin quan trọng như lịch trình mới hay lịch trình thay đổi, các thông báo quan trọng, điểm nghẽn là thông tin phân tán. Metric đo bằng thời gian kiểm tra điện thoại mỗi ngày trong một tuần và đếm số thông báo quan trọng bị bỏ sót, mục tiêu là giảm bớt đc 50% thời gian xem điện thoại. Boundary là AI chỉ tóm tắt và gợi ý, không tự thay đổi thông tin hay quyết định thay người dùng. Chọn AI là mức Agent. Nhóm quyết định Not Yet cho vì còn những thông tin cần đc kiểm chứng như quyền truy cập dữ liệu, tiêu chí nhận diện thông báo, kênh nhận thông báo và xác nhận chung cho cả 3 kênh.

---

## 7. Tài liệu tham khảo
