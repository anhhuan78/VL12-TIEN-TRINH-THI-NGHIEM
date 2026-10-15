# PM01 — NHÁNH NGHIÊN CỨU CÒN THIẾU: KIỂM CHỨNG SỰ PHỤ THUỘC

> **Bản nhận diện lỗ hổng và định hướng biên soạn 15/10/2026 — CHỜ GIÁO VIÊN DUYỆT.**
> Không thay thế [PM01 đo chính xác / khử ẩn](PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md), mà bổ sung **một mục tiêu nghiên cứu khác**. Cùng một công thức không đồng nghĩa cùng một câu hỏi nghiên cứu.
> Nhận xét về *video 06 của thầy Nam* hiện là **quan sát của giáo viên** qua video; chưa có transcript/slide được đối chiếu ở tài liệu này.

## 1. Chứng cứ định hướng từ đề thật

**Đề chính thức TN THPT 2026, mã 0211, Phần II, Câu 4**: giả thuyết “nhiệt dung riêng của nước phụ thuộc vào khối lượng của nước”; thí nghiệm thay đổi khối lượng, ước lượng $c$ rồi xét kết luận giả thuyết. Nguồn tham khảo [bản đề & giải theo mã 0211](https://vatly.math.vn/2026/09/e-thi-tot-nghiep-thpt-2026-mon-vat-ly.html), [trình bày mã 0201 cùng họ câu](https://trolydithi.vn/de-thi-loi-giai/vat-ly/0201).

**Đề chính thức TN THPT 2026 lần 2, mã 0233, Phần II, Câu 3**: giả thuyết nhiệt độ cân bằng của hỗn hợp nước không phụ thuộc vào khối lượng; thay đổi khối lượng với các nhiệt độ ban đầu được kiểm soát, rồi phân tích kết quả. [Nguồn sao chép văn bản đề](https://www.scribd.com/document/1075768245/De-thi-tot-nghiep-THPT-2026-Lan-2-Vat-li-Ma-de-0233).

Các câu trên có trọng tâm **kiểm tra quan hệ phụ thuộc** chứ không yêu cầu học sinh trước tiên tối ưu hóa phương án để tìm chính xác một hệ số. Những mệnh đề thực tế vẫn có thể hỏi về thất thoát, năng lượng cấp và giới hạn của kết luận.

## 2. Hai mục đích nghiên cứu — hai trục song song, KHÔNG phải hai độ khó

| | Nhánh K — KHẢO SÁT QUAN HỆ (bổ sung) | Nhánh Đ — ĐO & CẢI TIẾN PHÉP ĐO (PM01 đang mạnh) |
|---|---|---|
| Câu hỏi | $Y$ có phụ thuộc $X$ không; nếu có, như thế nào? | Làm sao xác định chính xác $Y$ khi có thành phần phụ? |
| Biến | Biến khảo sát, đại lượng kết quả, yếu tố kiểm soát | Đại lượng mục tiêu, biến phải thay đổi để tách ẩn, yếu tố nhiễu |
| Kết quả | Mối quan hệ / phản ví dụ / giới hạn bằng chứng | Giá trị ước lượng hoặc quy trình đo đáng tin cậy hơn |
| Các câu Đ/S | Phát biểu về chiều, tính tỉ lệ, biến khống chế, giả thuyết, tính phổ quát | Phát biểu về phân bổ năng lượng, khử ẩn, sai số, tính đầy đủ dữ kiện |
| Rủi ro | Nhầm đại lượng *thực* với đại lượng *đo suy ra*, suy luận tỉ lệ từ công thức khi chưa cố định các biến còn lại | Loại nhầm thành phần nhiệt phụ hoặc mặc định các lần đo độc lập |

**Mỗi nhánh có thể có mức 1–4 riêng**, từ nhận biết đến đánh giá giả thuyết, không gọi nhánh Đ là mức cao hơn đương nhiên.

### Một câu hỏi nghiên cứu có thể *dẫn đến* nhánh kia

**Giả thuyết K:** “$c$ phụ thuộc khối lượng mẫu”.

Một nhóm dùng cùng nhiệt lượng kế (nhiệt dung $C>0$), xem mọi điện năng $E$ đều thuộc mẫu, rồi tính $\hat c=E/(m\Delta T)$. Nếu không có thất thoát ra ngoài và chất không chuyển thể:
\[
E=(mc+C)\Delta T\quad\Rightarrow\quad
\hat c=c+\frac C m.
\]
Vì vậy *giá trị suy ra chưa hiệu chỉnh* $\hat c$ giảm khi tăng $m$ ngay cả khi $c$ **thực** của cùng một chất không đổi theo khối lượng. Quan sát này **không chứng minh** $c$ thực giảm khi tăng $m$.

**Phản biện từ K dẫn đến Đ:** cần định lượng $C$ hoặc thiết kế hai phép đo khối lượng khác nhau để tách $c$ và $C$. Như vậy **cải tiến phép đo giải quyết điểm yếu phát hiện trong khảo sát**, chứ không thay thế luôn câu hỏi khảo sát.

Cẩn trọng: Đây là **tình huống mới do PAH rút ra**, không gán là số liệu hoặc kết quả của đề chính thức 2026. Đề chính thức cho một kết luận khác về số liệu của chính đề.

## 3. Cách đặt giả thuyết đúng

### K1. Nghiên cứu $c$ có phụ thuộc vào khối lượng $m$?

Khóa: *cùng chất, cùng trạng thái, cùng khoảng nhiệt độ xét, không chuyển thể*. Chọn nhiều $m$, đo năng lượng, độ tăng nhiệt, tách ảnh hưởng bình và mất nhiệt, rồi **so sánh giá trị $c$ đã hiệu chỉnh**.

Không kết luận từ $c=Q/(m\Delta T)$ rằng $c\propto 1/m$ vì $Q$ và $\Delta T$ thường cũng thay đổi khi $m$ thay đổi.

### K2. Nghiên cứu $c$ có giảm khi nhiệt độ $T$ tăng?

**Không được bác giả thuyết này chỉ bằng công thức $Q=mc\Delta T$.** Nhiệt dung riêng của nhiều chất có thể thay đổi theo nhiệt độ; công thức với $c$ hằng số là xấp xỉ trên một khoảng nhiệt độ.

Đo cùng khối lượng trong nhiều khoảng nhiệt độ khác nhau, so sánh **nhiệt dung riêng trung bình theo từng khoảng** sau khi hiệu chỉnh nhiệt dung dụng cụ và hao phí:
\[
\bar c_{[T_a,T_b]}
=\frac{Q_{\text{vào mẫu}}}{m(T_b-T_a)}.
\]
Nếu $c$ thực sự thay đổi theo $T$, đúng hơn có
\[
Q_{\text{vào mẫu}}=m\int_{T_a}^{T_b}c(T)\,\mathrm dT.
\]
**Đây là công thức chuyên môn dành cho người biên soạn, không mặc nhiên đưa tích phân vào bài học/đề THPT.** So sánh các khoảng có cùng độ rộng đủ để hỏi định tính. Nếu thấy $\bar c$ giảm qua các khoảng đã đo, kết luận tối đa là xu hướng của các giá trị trung bình **trong phạm vi khảo sát và điều kiện sai số**, không chứng minh $c(T)$ giảm tại mọi nhiệt độ.

### K3. Nghiên cứu $T_{\mathrm{cb}}$ có phụ thuộc khối lượng không?

Trong mô hình cùng một chất, không hao phí và bình không thu nhiệt đáng kể:
\[
T_{\mathrm{cb}}=\frac{m_1T_1+m_2T_2}{m_1+m_2}.
\]
Giữ $T_1,T_2$ cố định: $T_{\mathrm{cb}}$ phụ thuộc **tỉ lệ khối lượng** $m_2/m_1$, nhưng khi nhân đồng thời $m_1,m_2$ với cùng hệ số thì $T_{\mathrm{cb}}$ **không đổi**. Đề có thể khai thác hai ý kiến tưởng đối lập: “phụ thuộc vào khối lượng” và “không đổi khi tăng cả hai khối lượng”, thực ra có thể cùng đúng trong mô hình này. Nếu bình có nhiệt dung đáng kể, cần bổ sung cân bằng năng lượng đúng theo nhiệt độ ban đầu của bình.

## 4. Hai câu Đúng/Sai PAH mới, không số liệu (bản kiểm thử lập luận)

### Câu K01 — Sự phụ thuộc biểu kiến khi đo $c$ theo $m$

Một nhóm muốn kiểm tra giả thuyết “nhiệt dung riêng của cùng một chất lỏng giảm khi khối lượng mẫu tăng”. Họ làm nóng các mẫu trong **cùng một nhiệt lượng kế có nhiệt dung $C>0$**, từ cùng nhiệt độ ban đầu qua cùng độ tăng nhiệt $\Delta T>0$, đo điện năng nguồn cấp cho mỗi lần. Coi điện năng truyền hoàn toàn cho **chất lỏng và bình**, không truyền ra môi trường; chất không chuyển thể; $C$ và nhiệt dung riêng thực $c$ của chất **không đổi**. Nhóm lại tính “nhiệt dung riêng” bằng cách lấy điện năng cấp chia cho $m\Delta T$, coi như nhiệt lượng kế không hấp thụ năng lượng.

a) Nếu tăng khối lượng mẫu thì điện năng cần cung cấp để đạt cùng $\Delta T$ cũng tăng. **Đúng**.

b) Trong các điều kiện đã cho, điện năng cấp tỉ lệ thuận với khối lượng mẫu. **Sai** ($E=(mc+C)\Delta T$ có số hạng tự do $C\Delta T>0$).

c) Giá trị “nhiệt dung riêng” nhóm tính ra có thể giảm khi khối lượng mẫu tăng, dù nhiệt dung riêng thực của chất không đổi. **Đúng** ($\hat c=c+C/m$).

d) Xu hướng $\hat c$ giảm khi tăng $m$ đủ để khẳng định nhiệt dung riêng thực của chất giảm theo khối lượng. **Sai**.

**Giáo viên:** Đ–S–Đ–S. Mức 3–4 của nhánh K; câu c,d chủ yếu kiểm tra khác nhau giữa giá trị quan sát *suy ra từ phép tính* và đặc trưng vật lý.

### Câu K02 — Nghiên cứu sự phụ thuộc theo nhiệt độ (không số liệu)

Một nhóm đưa ra giả thuyết: “Trong khoảng nhiệt độ đang khảo sát, nhiệt dung riêng của một chất lỏng giảm khi nhiệt độ tăng”. Họ dùng cùng khối lượng chất lỏng, đun nóng lần lượt qua một số khoảng nhiệt độ bằng nhau. Ở mỗi khoảng, nhóm đo điện năng cấp và đã xác định để loại phần năng lượng làm nóng dụng cụ cũng như phần truyền ra môi trường. Họ nhận thấy **nhiệt lượng truyền cho riêng chất lỏng ở những khoảng nhiệt độ cao hơn nhỏ hơn** so với các khoảng trước. Coi không chuyển thể và các phép đo đủ chính xác để phân biệt sự chênh lệch.

a) Để kiểm tra giả thuyết về $c$ phụ thuộc nhiệt độ, cần so sánh phép đo ở những khoảng nhiệt độ khác nhau. **Đúng**.

b) Từ $c=Q/(m\Delta T)$ có thể kết luận ngay rằng $c$ luôn tỉ lệ nghịch với độ tăng nhiệt độ trong mọi thí nghiệm. **Sai**.

c) Với cùng khối lượng và cùng độ rộng khoảng nhiệt độ, nhiệt lượng riêng mẫu nhận nhỏ hơn có nghĩa **nhiệt dung riêng trung bình** trên khoảng đó nhỏ hơn. **Đúng**.

d) Quan sát các giá trị trung bình giảm ở những khoảng đã thử chứng minh $c$ giảm tại **mọi nhiệt độ** và mọi trạng thái khác của chất. **Sai**.

**Giáo viên:** Đ–S–Đ–S. Bài mới phát triển từ giả thuyết của giáo viên, **không phải câu Bộ 2026**.

## 5. Quy tắc tiếp theo cho hệ PAH và NotebookLM

Phân loại mọi **câu nguồn thực nghiệm** trước theo *mục đích nghiên cứu*:

- **K — Khảo sát quan hệ / kiểm định giả thuyết**: $Y$ có phụ thuộc $X$ không; tăng hay giảm; có tỉ lệ tuyến tính không; kết luận trong khoảng nào; thay biến/giữ biến ra sao?
- **Đ — Đo đại lượng / cải tiến phương pháp đo**: đo $Y$ thế nào; ẩn phụ nào; hai phép đo đủ độc lập không; giảm sai lệch ra sao?
- **Khác**: quan sát để giải thích cơ chế, chọn mô hình, dự đoán trạng thái… nếu không rơi vào hai nhóm trên, **không ép phân loại**.

**Một đề có thể chứa cả K và Đ:** có câu khảo sát phụ thuộc, có ý hỏi ảnh hưởng phép đo. Gắn nhãn **mục tiêu chính của cả câu** và **nhiệm vụ của từng ý**, tránh dùng một nhãn thay tất cả.

**Trình tự biên soạn mới khi phát triển PM01:** 
- Trước hết viết tình huống nghiên cứu K (giả thuyết -> các biến -> dự đoán -> dữ liệu/quan sát -> kết luận).
- Sau đó đặt câu hỏi có thể làm sai suy luận: yếu tố gây nhiễu / độ tin cậy / giới hạn.
- Nếu bài đòi hỏi, dẫn sang Đ: thay đổi phương án hoặc thiết kế phép đo mới để cải tiến.
- Tạo ít nhất một câu **chỉ tập trung K**, không buộc mọi câu kết thúc bằng cải tiến.
- Vẫn lưu đáp án/điều kiện/nguồn và đánh dấu chờ duyệt.

**Checkpoint:** trước đây PM01 phát triển mạnh nhánh Đ với 8 câu; không xoá hoặc sửa hàng loạt. Từ nay bổ sung nhánh K để bộ đề có đủ hai góc độ.
