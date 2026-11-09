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
| Pitch Problem Card               | Trình bày vấn đề theo dõi cập nhật quan trọng trên các kênh mình dùng; mô tả việc kiểm tra lặp lại và thời gian tự thuật khoảng 30–60 phút/ngày. | Candidate #3 của mình được đưa vào cluster A cùng vấn đề theo dõi thông báo của Hà và được chọn làm problem nhóm. Khi rà soát, nhóm nhận ra card cần thống nhất số kênh: nội dung liệt kê ba kênh nhưng bản pitch ban đầu ghi “4 app”. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Mình chưa lưu lại câu hỏi cụ thể đã hỏi bạn khác trong buổi phản biện. | Không ghi nhận nguyên văn nên không gán một câu hỏi cụ thể cho mình; đây là phần cần bổ sung từ ghi chú/bạn cùng nhóm nếu còn lưu. |
| Nhận phản biện                | Câu hỏi tôi nhận được: Vì sao chọn Outlook thay vì chỉ ghi “Email”, để bao quát email cá nhân, trường học và cơ quan? | Tôi đổi cách gọi ở Problem Card 6 từ “Email” thành “Outlook”, theo nội dung đã ghi trong reflection. |
| Gom cluster / cây OST           | Tham gia đưa candidate theo dõi cập nhật của mình vào cluster A — “Thông báo quan trọng bị phân tán”. | Nhóm nối vấn đề của mình với candidate của Hà về thông báo lớp/deadline; cây OST và phần mô tả tập trung vào việc giảm công tìm, đọc và xác định cập nhật cần xử lý. |
| Chọn candidate problem          | Problem #3 của mình được shortlist với tổng điểm đề xuất 27; nhóm chọn vấn đề này làm bài toán chung. | Nhóm ưu tiên vấn đề xảy ra hằng ngày, có thể đo thời gian kiểm tra và số cập nhật cần xử lý bị bỏ sót; đồng thời giới hạn phạm vi vào trải nghiệm của mình thay vì khái quát mọi học viên. |
| Kiểm chứng / research          | Cùng nhóm rà soát giả định, nguồn tính năng của Zalo, Discord, Outlook và các khoảng trống bằng chứng. | Research cho thấy từng nền tảng có tính năng tổ chức/lọc riêng; nhóm chưa phỏng vấn người ngoài, chưa thu log hoặc thử trên tài khoản của mình. Vì vậy chưa thể kết luận các tính năng giảm thời gian hay giải quyết được vấn đề. |
| Quy trình nhóm                 | Cung cấp quy trình hiện tại: mở ba kênh, xem tin mới, đọc tìm cập nhật, xác định thông tin và việc cần làm; thời gian từng bước là tự thuật. | Nhóm xác định bước đọc tìm cập nhật là bottleneck khoảng 4/10 phút mỗi lượt theo card. Quy trình tương lai thêm kiểm tra nguồn và rà soát cuối ngày; thời gian dự kiến vẫn cần đo, chưa phải kết quả. |
| Problem Statement                | Cung cấp bối cảnh, actor, thời gian tự thuật và phạm vi cập nhật lịch học/thay đổi lịch/deadline cho bản Problem Statement. | Bản statement giữ actor là mình, tách phút/lượt khỏi phút/ngày, ghi baseline chưa đo và target giảm 50% là đề xuất. Boundary yêu cầu đối chiếu tin gốc và không tự gửi, xóa tin hoặc đổi lịch. |
| Mức can thiệp AI               | Tham gia xem xét No AI, Rule, Workflow và Agent theo độ rõ của quy trình, dữ liệu và rủi ro. | Nhóm đề xuất No AI làm đối chứng và thử Rule bằng tính năng sẵn có nếu cần; chưa có bằng chứng để chọn Workflow/Agent. Người dùng tiếp tục đọc ngữ cảnh, xác nhận và hành động. |
| Quyết định                    | Cung cấp các giới hạn còn thiếu: chưa đo baseline, chưa xác minh quyền dữ liệu và chưa thử phương án. | Kết luận đề xuất là Not Yet; cần ghi thời gian 5 ngày học, xác nhận phạm vi/quyền và ngưỡng tin khẩn, rồi so sánh No AI với Rule trước khi quyết định triển khai. |

---

## 5. Dùng AI


| Checkpoint                          | Tôi dùng AI để làm gì?                                                                                                         | AI hữu ích ở đâu?                                                                                                                                                                            | AI sai hoặc hời hợt ở đâu?                                                                                                                                                                                | Tôi sửa gì bằng nhận định của mình?                                                                                                                                                                                                                                                                       |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CP1 Scan                            | Sau khi tự scan, nhờ AI rà soát cách diễn đạt Job Story và tính nhất quán của thông tin.                               | Giúp làm rõ Problem #6 sử dụng đúng 3 kênh Discord, Outlook và Zalo; hỗ trợ chỉnh câu mô tả deadline ở Problem #2 theo sự việc đã xảy ra.                                    | Ban đầu phần nhận xét tập trung vào việc thiếu tần suất đo lặp lại, khiến câu ghi chú dài và không phù hợp với cách trình bày tôi muốn.                                             | Tôi xác nhận thông tin thực tế và sửa dấu hiệu của Problem #2 thành: “Hôm qua tôi chạm mốc deadline nộp Codelab 02.”                                                                                                                                                                            |
| CP2 Problem Card                    | Nhờ AI phản biện Card #1 và rà soát tính nhất quán giữa số kênh, thời lượng mỗi lượt, tổng thời gian và metric. | Phản biện giúp tôi nhận ra cần làm rõ tiêu chí “cập nhật quan trọng”, giữ người dùng kiểm tra trước khi xử lý, và kiểm tra lại mục tiêu thời gian so với baseline. | AI đề xuất phân bổ thời gian từng bước và đánh giá các phản biện quá đồng thuận; các con số này cần được tôi đối chiếu với quy trình thực tế thay vì xem là kết quả đo. | Tôi tự đối chiếu quy trình và chốt mô tả gồm 3 kênh, khoảng 10 phút mỗi lượt; chọn “Đồng ý một phần” với góp ý về tiêu chí cập nhật; sau khi xem lại baseline 30–60 phút/ngày, tôi đặt mục tiêu giảm ít nhất 50% so với mức trung bình ghi nhận trong một tuần. |
| CP4 Research                        | Nhờ AI hỗ trợ hệ thống hóa giả định cần kiểm chứng và rà soát các cách tổ chức/lọc thông báo sẵn có trên Zalo, Discord, Outlook. | Giúp nhận diện rằng mỗi nền tảng đã có tính năng ghim, cấu hình thông báo hoặc lọc thư; từ đó mở ra phương án thử cách đơn giản trước khi nghĩ đến AI. | Tài liệu tính năng chỉ xác nhận công cụ có khả năng đó, không chứng minh tiết kiệm thời gian cho tôi hay tích hợp được cả ba kênh. AI cũng không thể thay dữ liệu phỏng vấn, log thời gian hoặc kiểm tra trên tài khoản thực tế. | Tôi giữ số 30–60 phút/ngày là tự thuật, không xem là baseline đã đo; ghi rõ chưa phỏng vấn người ngoài nhóm và chưa thử tính năng. Tôi thu hẹp kết luận vào trường hợp của mình và xác định cần so sánh No AI/Rule bằng cách bấm giờ. |
| CP5 Quy trình                      | Nhờ AI phản biện sơ đồ trước/sau và kiểm tra xem thời gian, bước rà soát, rủi ro bỏ sót có được tính đủ không. | Góp ý giúp tách quy trình hiện tại thành các bước, nêu rõ bước đọc tìm cập nhật là bottleneck theo tự thuật, đồng thời tính thêm bước rà soát cuối ngày vào phương án đề xuất. | Mốc thời gian quy trình tương lai (5 phút/lượt và 5 phút rà soát/ngày) là ước lượng để thử, chưa phải kết quả đo. Nếu chỉ tính thời gian lọc mà bỏ phần kiểm tra lại thì lợi ích sẽ bị phóng đại; rà soát cuối ngày cũng có thể trễ với tin khẩn. | Tôi ghi rõ số liệu hiện tại lấy từ card, phương án sau chưa thử nghiệm; đưa chi phí rà soát vào phép tính và nêu rằng mô hình mới chưa đạt mục tiêu giảm 50%. Tôi bổ sung việc giữ nguồn gốc, kiểm tra tin khẩn và phương án quay lại mở đầy đủ các kênh. |
| CP5–6 Problem Statement            | Nhờ AI rà soát bản Problem Statement v0 về actor, phạm vi vấn đề, baseline/target và boundary. | Phản biện làm rõ sự khác nhau giữa phút/lượt và phút/ngày, yêu cầu đo baseline trong 5 ngày học, tính cả thời gian rà soát/sửa sai và giới hạn thông tin cần xử lý ở lịch học, thay đổi lịch, deadline. | Một số đề xuất metric/ngưỡng chỉ là gợi ý, không phải số liệu đã xác nhận; nhận định “không bỏ sót” thiếu phạm vi và độ trễ chấp nhận được. AI không có bằng chứng để khái quát pain của tôi thành pain của mọi học viên. | Tôi để rõ baseline còn là tự thuật, mục tiêu giảm 50% là mục tiêu đề xuất chưa chứng minh, cần ghi cả cập nhật bị bỏ sót và độ trễ. Tôi giữ actor là bản thân, yêu cầu đối chiếu đầu ra với nguồn và không cho tự gửi tin, xóa nội dung hay đổi lịch. |
| CP6 Mức can thiệp / quyết định | Nhờ AI giúp so sánh No AI, Rule, Workflow và Agent, đồng thời rà soát các rủi ro và điều kiện cần trước khi chọn mức. | Khung so sánh giúp thấy phần tổ chức/lọc theo điều kiện cố định có thể thử bằng tính năng sẵn có; chưa có bằng chứng rằng cần AI đọc hiểu hoặc Agent tự quyết định bước tiếp theo. | Đề xuất mức cao hơn có thể hấp dẫn nhưng chưa giải quyết các thiếu hụt về quyền truy cập, dữ liệu kiểm thử, hiệu quả thực tế và kiểm soát bỏ sót. Đánh giá rủi ro/Not Yet vẫn là phân tích đề xuất, chưa được pilot hay nhóm xác nhận đầy đủ. | Tôi không xem AI/Agent là lựa chọn mặc định; ghi mức đề xuất là Rule để so sánh với No AI, và nếu No AI đủ thì dừng ở đó. Tôi giữ quyết định Not Yet, nêu rõ cần đo 5 ngày, xác minh quyền và ngưỡng tin khẩn, và để người dùng kiểm tra nguồn, tự hành động, có thể quay về cách kiểm tra đầy đủ. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?** Mình học thêm được các ý tưởng từ các bạn, cách viết Problem Statement theo quy trình và cách xác định pain point, bottleneck. Mình cũng nhận ra cần mô tả một tình huống cụ thể, người bị ảnh hưởng và dấu hiệu có thể kiểm tra, thay vì chỉ nêu một chủ đề rộng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?** Có lúc mình nghĩ ngay đến việc dùng AI/Agent để gom thông báo từ nhiều kênh, vì thấy việc mở Zalo, Discord và Outlook nhiều lần khá mất thời gian. Khi làm tiếp phần research và quy trình, nhóm nhận ra mình chưa có bằng chứng rằng cần kết nối tự động hay để AI tự quyết định. Các nền tảng đã có tính năng ghim, cài thông báo và lọc thư; tuy vậy nhóm cũng chưa thử chúng trên tài khoản của mình nên chưa biết có hiệu quả không. Vì vậy, nhóm quay lại mô tả các bước đang làm, giữ No AI làm phương án so sánh và chỉ đề xuất thử Rule nếu cách tổ chức đơn giản chưa đủ. Đây là hướng đề xuất, chưa phải kết quả thử nghiệm.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.** Mình có đổi ý sau khi bị phản biện. Ở Problem Card 6, lúc đầu mình chọn “Email”, nhưng sau khi các bạn góp ý, mình đổi thành Outlook vì Outlook bao gồm các email cá nhân, trường học hoặc cơ quan. Việc đổi cách gọi giúp mình xác định rõ hơn nền tảng đang nói tới.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?** Phần này chưa có kết quả phỏng vấn hoặc survey: nhóm chưa hỏi người ngoài nhóm và chưa thu thập log bấm giờ, nên mình chưa thể nói người dùng khác có cùng vấn đề hay không. Điều mình nhận ra từ research là cả ba nền tảng đều có cách tổ chức hoặc lọc nội dung riêng. Điều đó khiến mình thận trọng hơn với ý tưởng cần một Agent gom tất cả thông báo. Tuy nhiên, research chỉ xác nhận tính năng có tồn tại; mình chưa thử trên tài khoản thực tế và chưa biết chúng có giúp giảm thời gian hoặc tránh bỏ sót thông báo hay không. Vì vậy, đây là điều chỉnh trong nhận định chứ chưa phải kết quả kiểm chứng hiệu quả.

**6.5. Điều khó nhất khi viết Problem Statement là gì?** Điều khó nhất với mình là chọn vấn đề quan trọng, làm rõ pain point và giới hạn phạm vi. Việc đo thời gian cũng khó: số 30–60 phút/ngày hiện mới là tự thuật, chưa có log; cần tách thời gian mở kênh, đọc tìm cập nhật, ghi việc và xử lý công việc phát sinh. Vì vậy mình phải ghi rõ baseline chưa được đo và mục tiêu giảm 50% chưa được chứng minh, thay vì trình bày chúng như kết quả.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?** Nếu làm lại, mình sẽ ghi thời gian và số lượt kiểm tra trong vài ngày sớm hơn, đồng thời tách việc đọc/lọc thông báo khỏi trả lời hoặc làm nhiệm vụ. Khi thảo luận, mình sẽ hỏi rõ nhóm đã thử tính năng sẵn có chưa, chi phí rà soát sau khi lọc là bao nhiêu và thông báo khẩn có thể bị trễ thế nào. Mình cũng sẽ nhắc nhóm phân biệt điều đã đo với điều mới là giả định. Hiện chưa có phỏng vấn người ngoài nhóm, log đo hoặc pilot, nên mình không nên kết luận cách đề xuất đã tiết kiệm thời gian hay phù hợp với mọi học viên.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình. Nhóm tập trung vào trường hợp của mình: mất thời gian theo dõi cập nhật lịch học, thay đổi lịch và deadline trên Zalo, Discord và Outlook; chưa khẳng định đây là vấn đề chung của mọi học viên. Hiện tại mình mở ba kênh, xem tin mới, đọc để tìm cập nhật cần xử lý rồi xác định việc cần làm; bước đọc tìm thông tin là bottleneck theo tự thuật, khoảng 4 phút trong một lượt khoảng 10 phút. Baseline 30–60 phút/ngày cần được đo trong 5 ngày học, sau đó so sánh thời gian trung bình, tính cả rà soát và sửa sai; mục tiêu đề xuất là giảm ít nhất 50% và theo dõi cả cập nhật bị bỏ sót, nhưng chưa được kiểm chứng. Người dùng phải đối chiếu thông tin với tin gốc và tự xác nhận lịch/deadline; không tự gửi tin, xóa nội dung hay đổi lịch. Nhóm đề xuất bắt đầu với No AI và Rule theo tính năng sẵn có; nếu No AI đủ thì không cần nâng mức, và hiện chưa chọn Workflow hay Agent. Quyết định là Not Yet vì còn thiếu log thời gian, phản hồi người dùng ngoài nhóm, xác nhận quyền dữ liệu và thử nghiệm hiệu quả cũng như độ trễ với tin khẩn.

---

## 7. Tài liệu tham khảo
