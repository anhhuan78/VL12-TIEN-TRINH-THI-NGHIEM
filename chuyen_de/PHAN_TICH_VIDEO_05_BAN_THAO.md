# PAH | TỪ VIDEO 05 ĐẾN PHƯƠNG PHÁP BIÊN SOẠN VÀ GIẢNG DẠY

**Trạng thái:** Hồ sơ phương pháp v1, dùng để phát triển chuyên đề và câu hỏi PAH. Chưa phải giáo án/chuyên đề đã duyệt.  
**Nguồn chính:** `05 - Triển khai tiến trình và biên soạn câu hỏi tiến trình.mp4` (~58 phút 21 giây).  
**Nguồn bổ trợ:** Báo cáo NotebookLM người dùng cung cấp.  
**Đối chiếu trực tiếp:** slide video ở khoảng 10:00, 16:40, 23:20, 30:00, 36:40, 50:00, 56:40. Nhận xét kiểm định dưới đây là của PAH, không gán cho tác giả.

## I. Những gì thực sự học từ tác giả

**Một thí nghiệm không chỉ là một câu hỏi tính toán.** Thầy Nam dùng tình huống nấu ăn, đặt giả thuyết về nhiệt độ sôi của nước muối, lập kế hoạch thay dần lượng muối, đo nhiệt độ, lập bảng, thảo luận sai số và cuối cùng xây sáu nhận định a–f khai thác **các đoạn khác nhau của tiến trình**.

| Mảnh tiến trình từ video | Dạng câu hỏi được rút ra | Ý nghĩa sư phạm |
|---|---|---|
| Nêu phương án, nhiều bước đo | Đúng/sai về thao tác, số lượt lặp | Đọc chính xác phương án, không đoán |
| Phát biểu giả thuyết và mục tiêu | Đánh giá mức độ bằng chứng | Không đồng nhất dữ liệu hữu hạn với chứng minh phổ quát |
| Đun nối tiếp trong một nồi | Tìm yếu tố nhiễu: nước bay hơi | Phát hiện đại lượng tưởng cố định nhưng thực ra thay đổi |
| Bảng nhiệt độ–lượng muối | Tính nồng độ, mức tăng trung bình | Biến dữ liệu thô thành đại lượng có ý nghĩa |
| Thảo luận điều kiện, sai số | Chọn cải tiến, giới hạn kết luận | Hiểu độ tin cậy của phép đo |

**Quy tắc PAH rút ra (không phải lời trích của tác giả):** Với một thí nghiệm, xác định *hiện tượng → câu hỏi nghiên cứu → biến độc lập/biến phụ thuộc/biến cần giữ → dữ liệu → phép suy luận → giới hạn và sai số*. Lấy từng mắt xích này để biên soạn câu hỏi; không viết bốn nhận định chỉ xoay quanh một công thức.

## II. Dữ liệu nguồn và cách diễn giải đúng

Tại áp suất được tác giả giả định là 1 atm, mẫu ban đầu dùng 200 g nước, tăng **tổng lượng muối có trong nồi** từ 0 đến 50 g, theo từng lần thêm 10 g:

| Tổng muối (g) | Nồng độ danh nghĩa, tính với 200 g nước (%) | Nhiệt độ sôi trong bảng video (°C) |
|---:|---:|---:|
| 0 | 0 | 100,0 |
| 10 | 4,8 | 101,0 |
| 20 | 9,1 | 102,0 |
| 30 | 13,0 | 103,0 |
| 40 | 16,7 | 104,5 |
| 50 | 20,0 | 106,5 |

Nếu coi lượng nước luôn bằng 200 g, nồng độ tính toán là:

\[
C_{\rm danh\ nghia}=\frac{m_{\rm muoi}}{m_{\rm muoi}+200}\,100\%.
\]

Nhưng nếu quá trình đun làm bay hơi tích lũy \(e\) g nước và giả sử muối không thất thoát, thì:

\[
C_{\rm thuc}=\frac{m_{\rm muoi}}{m_{\rm muoi}+200-e}\,100\%, \quad 0\le e<200.
\]

Do đó khi \(e>0\) và có muối, \(C_{\rm thuc}>C_{\rm danh\ nghia}\). Đây là kết quả đại số từ mô hình hiệu chỉnh do PAH nêu rõ giả thiết, **không phải phép đo lượng nước thực đã mất trong video**.

Mức tăng trung bình từ **hai đầu bảng danh nghĩa** là \((106,5-100)/20 = 0,325\ ^\circ\mathrm C\) trên **1 điểm phần trăm nồng độ**, không có nghĩa mọi mức tăng 1 điểm phần trăm đều cho đúng 0,325 °C. Đường khớp bậc hai tác giả trình bày là mô tả thực nghiệm trong khoảng dữ liệu; không phải định luật nhiệt độ sôi có thể áp dụng cho mọi nồng độ/áp suất.

## III. Kiểm định sáu nhận định gốc: giữ lịch sử nguồn, nhưng không bê nguyên đáp án

| Ý gốc | Kết luận tác giả trên slide ~56:40 | Đánh giá PAH trước khi tái sử dụng |
|---|---|---|
| a — lặp thao tác thêm 5 lần | Sai | Rõ khi đếm theo quy trình (sau lần thêm 10 g đầu chỉ thêm 4 lần). Có thể dùng như câu đọc hiểu mức cơ bản. |
| b — dữ liệu đủ **chứng minh** giả thuyết đúng | Sai | Tốt để dạy giới hạn chứng cứ; cần làm rõ đang hỏi toàn miền nồng độ hay chỉ sáu điểm đo. |
| c — thời gian đun càng dài thì sai lệch nồng độ càng lớn | Đúng | **Cần bổ sung điều kiện**: tốc độ bay hơi khác nhau; mối quan hệ chắc hơn là 'càng mất nhiều nước (muối giữ nguyên), nồng độ thực càng lớn so với giá trị tính từ 200 g'. Không nên dùng thời gian như tác nhân duy nhất nếu không kiểm soát các điều kiện khác. |
| d — tăng trung bình 0,325 °C/1% | Đúng | Chỉ đúng với độ dốc trung bình **trên 1 điểm phần trăm của nồng độ danh nghĩa** trong đoạn 0–20%; không suy ra gia tăng tuyến tính từng khoảng. |
| e — bỏ phép đo nước tinh khiết vẫn đủ **chứng minh** trong phạm vi khảo sát | Đúng | **Chưa chặt để chấm**: áp suất 1 atm cho giá trị sôi nước tinh khiết xấp xỉ 100 °C nhưng không phải 'định nghĩa' thay thế mọi phép đo nền; bỏ phép đối chứng làm yếu cơ sở so sánh và kiểm tra sai số hệ thống. Từ sáu điểm cũng không thể khẳng định mọi nồng độ trung gian một cách tuyệt đối. Nên viết lại phạm vi kết luận. |
| f — bù nước bay hơi để cải tiến | Đúng | Hướng khắc phục hợp lý **nếu đo được lượng mất và khôi phục đúng lượng nước trước lần đo**, đồng thời kiểm soát các điều kiện khác. 'Thêm một ít nước' tùy ý không bảo đảm đúng nồng độ hay độ chính xác. |

**Quy tắc lưu nguồn:** hai cột khác nhau: `(1) đáp án tác giả` và `(2) trạng thái kiểm định PAH`. Không âm thầm sửa phát biểu gốc hay ghi rằng tác giả giải sai nếu chưa đủ căn cứ.

## IV. Chuyên đề phương pháp PAH phát triển từ video

### Tên phương pháp

**PM-V05 — Từ dữ liệu thực nghiệm đến kết luận có điều kiện**

### Nguyên lý cốt lõi

Một kết quả đo phải gắn với **đại lượng thật sự được kiểm soát**, **mô hình đo**, **phạm vi khảo sát** và **độ tin cậy của dữ liệu**. Không suy ra quy luật tổng quát chỉ vì bảng số liệu có xu hướng rõ.

### Bốn động tác tư duy cần dạy

1. **Nhận diện biến:** thứ ta chủ động thay là lượng muối; thứ quan sát là nhiệt độ sôi; áp suất và lượng nước cần được kiểm soát (lượng nước không nhất thiết giữ được nguyên qua nhiều lần đun).
2. **Biến dữ liệu thành đại lượng:** phân biệt `tổng muối đã thêm`, `nồng độ danh nghĩa`, `nồng độ thực nếu có bay hơi`; lập công thức trước khi nhận định.
3. **Diễn giải bằng chứng:** nói 'trong các lần đo ghi nhận, nhiệt độ sôi tăng khi nồng độ danh nghĩa tăng', không tự động nói 'mọi dung dịch muối ở mọi điều kiện đều tuân theo'.
4. **Cải tiến phép đo:** nhận ra vì sao nồi dùng lại qua sáu lần không giữ được mọi biến; đề xuất đo khối lượng sau mỗi lần đun/bù lượng nước mất có kiểm soát hoặc dùng các mẫu độc lập chuẩn bị cùng lượng nước.

### Lộ trình dạy ngắn, dùng chính tình huống này

- **Khởi động:** Vì sao bảng cho '200 g nước' nhưng ở lần đo cuối có thể không còn 200 g?
- **Mô hình:** Học sinh tự viết hai công thức nồng độ danh nghĩa/thực, chứng minh hướng sai lệch.
- **Lập luận:** Học sinh phân biệt độ dốc trung bình với mối quan hệ gia tăng đều từng 1%; so sánh 'ủng hộ' với 'chứng minh'.
- **Chuyển giao:** Đưa tình huống thí nghiệm bay hơi khác hoặc phép đo nhiệt dung riêng có nhiệt lượng kế; học sinh tự nhận diện yếu tố phụ.

## V. Một câu bốn nhận định PAH viết mới (không phải nguyên văn từ nguồn)

**Tình huống:** Một nhóm khảo sát ảnh hưởng của nồng độ muối đến nhiệt độ sôi. Ban đầu nhóm dùng 200 g nước trong cùng một nồi, sau đó lần lượt thêm muối và ghi nhiệt độ sôi sau mỗi lần. Tổng muối lần lượt là 0, 10, 20, 30, 40, 50 g; nhiệt độ đo tương ứng là 100,0; 101,0; 102,0; 103,0; 104,5; 106,5 °C. Nhóm tính nồng độ dựa trên khối lượng nước ban đầu là 200 g, nhưng chưa cân lại nước sau mỗi lần đun. Coi muối không bay hơi theo hơi nước.

Xét các nhận định:

**a)** Nếu bỏ qua nước bay hơi, nồng độ ở lần có tổng 30 g muối xấp xỉ 13,0%.  
**b)** Nếu nước đã bay hơi trong quá trình đun thì nồng độ thực tế của dung dịch luôn nhỏ hơn nồng độ được nhóm tính từ 200 g nước ban đầu.  
**c)** Theo số liệu danh nghĩa, mức tăng nhiệt độ sôi trung bình trong khoảng nồng độ từ 0% đến 20% là 0,325 °C trên mỗi **điểm phần trăm nồng độ**.  
**d)** Sáu lần đo đủ để khẳng định với mọi nồng độ và mọi áp suất, cứ tăng thêm một điểm phần trăm nồng độ thì nhiệt độ sôi tăng đúng 0,325 °C.

**Đáp án thử nghiệm:** a Đúng; b Sai; c Đúng; d Sai.

**Lý do:** a \(30/(200+30)\simeq13,0\%\). b nước bay hơi làm mẫu số giảm, nồng độ tăng (nếu không thất thoát muối). c \(6,5/20=0,325\). d sai vì vượt phạm vi quan sát và nhầm trung bình với gia tăng đều. Câu đã được kiểm tra số học/mô hình cơ bản, **chưa qua thử nghiệm học sinh**.

## VI. Quy tắc sinh thêm câu từ hồ sơ này

- **Có thể đổi:** bối cảnh nguồn câu hỏi, loại biến nhiễu, cấu trúc bảng dữ liệu, thao tác tính trung bình, yêu cầu đánh giá phạm vi kết luận.
- **Phải khóa:** phương trình tính đại lượng, định nghĩa nồng độ, trạng thái biến độc lập/phụ thuộc, dữ liệu và giả thiết; tất cả số liệu sinh phải được tính ngược/kiểm lại.
- **Không được làm:** bịa rằng là 'đo thực tế' nếu số liệu tự sinh; gọi phép khớp thực nghiệm là định luật phổ quát; ra nhận định cần dữ kiện bay hơi nhưng không nêu gì về lượng bay hơi/điều kiện.
- **Nhất thiết phân biệt:** `CÂU GỐC` / `BIẾN THỂ PHỎNG THEO` / `CÂU PAH MỚI`.

## VII. Trạng thái hoàn thành

**Đã làm:** xem các khung hình video nguồn, đối chiếu nhận định a–f, kiểm tra các phép tính và sai lệch do bay hơi, chắt lọc một phương pháp tư duy, lập một chuỗi dạy ngắn và một câu hỏi 4 nhận định làm mẫu.

**Chưa làm:** xác minh toàn bộ lời giảng; kiểm tra thực địa và sai số dụng cụ; biến phương pháp thành chuyên đề đã duyệt; chấm thử trên học sinh.

**Phần giáo viên cần quyết định:** phương pháp này có phù hợp trình độ lớp và định hướng đề cương không; dùng câu bốn nhận định PAH này hay thay bằng một câu nguồn khác.