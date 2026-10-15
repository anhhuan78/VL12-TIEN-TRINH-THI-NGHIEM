# VIDEO 06 — KIỂM ĐỊNH BÁO CÁO NOTEBOOKLM VÀ BỔ SUNG TRỤC K–M–Đ

> Ngày 15/10/2026 · **BẢN NGHIÊN CỨU / CHƯA DUYỆT**.
>
> **Nguồn:** báo cáo NotebookLM do giáo viên cung cấp trong hội thoại ngày 15/10/2026 về Video 06 (thầy Nam) và đề chính thức 2026, mã 0211, II.4; đề 2026 lần 2, mã 0233, II.3.
> **Mức độ xác minh:** chưa có toàn bộ video/slide/timestamp gốc trong lần làm việc này. Các câu “Video 06 có ...” bên dưới **theo báo cáo NotebookLM**, không thay thế việc kiểm tra video thực. Những phân loại, bổ sung và câu hỏi mới là **PAH suy ra**.

## 1. Phát hiện từ báo cáo

Theo NotebookLM, Video 06 mô tả **gia nhiệt liên tục, theo dõi đồ thị $T(t)$**, rồi tìm nhiệt độ chuyển thể và ước lượng $c_{\rm rắn},c_{\rm lỏng},\lambda,L$. Đến thảo luận mới nêu giới hạn: truyền nhiệt ra môi trường trong quá trình lâu có thể làm ước lượng sai; cần cải tiến trong nghiên cứu tiếp theo.

Hai câu Bộ được báo cáo sử dụng đặt **giả thuyết về sự phụ thuộc**:
- **2026 — 0211 — II.4:** $c$ của nước có phụ thuộc $m$?
- **2026, lần 2 — 0233 — II.3:** nhiệt độ cân bằng chỉ phụ thuộc vào hai nhiệt độ ban đầu hay còn phụ thuộc khối lượng?

Báo cáo cũng ghi tác giả Video 06 có một giả thuyết về khả năng xác định các hằng số bằng $T(t)$ và trình bày kết luận phù hợp mô hình lý tưởng. **Chưa nên gọi đó là “chứng minh đúng” ở mọi điều kiện**; cũng không thể suy từ hai câu minh họa rằng mọi đề Bộ đều “ưu tiên giả thuyết sai”.

## 2. Phản biện phân loại NotebookLM: hai nhánh là chưa đủ

**Sửa điểm trọng yếu:** Quan sát $T(t)$ là thao tác đo **biến thiên theo thời gian**, nhưng **mục tiêu của nghiên cứu mới quyết định phân loại**, không phải sự có mặt của đồ thị.

| Nhánh | Câu hỏi trung tâm | Sản phẩm |
|---|---|---|
| **K — Khảo sát quan hệ** | $Y$ có phụ thuộc $X$ không? Dạng phụ thuộc ra sao? Giả thuyết bị dữ liệu phản bác không? | Quy luật, phạm vi kết luận và giới hạn chứng cứ |
| **M — Đo đại lượng** | Làm sao tìm giá trị $c,\lambda,L,T_{\rm nc},T_{\rm sôi}$ bằng số đo? | Giá trị ước lượng từ mô hình hợp lệ |
| **Đ — Cải tiến phép đo** | Vì sao ước lượng còn bị ảnh hưởng và phải làm gì để đáng tin cậy hơn? | Thiết kế kiểm soát nhiễu, hiệu chỉnh hoặc loại đại lượng phụ |

**Đối chiếu Video 06 THEO BÁO CÁO**:
- Quan sát dạng $T(t)$ có tính **K** nếu thật sự hỏi quy luật $T$ theo $t$ hay cách phụ thuộc.
- Dùng độ dốc và đoạn nhiệt độ không đổi để **xác định** $c,\lambda,L$ là **M (mục tiêu chính được nêu)**; không nên mặc định tất cả là K.
- Nhận diện hao phí và đề xuất kiểm soát/hiệu chỉnh là bước mở sang **Đ**, nhưng báo cáo không chứng minh Video 06 đã triển khai đủ thí nghiệm hai lần đo.

**K, M, Đ không phải mức độ khó**. Mỗi nhánh đều có mức tư duy 1–4. Một tiến trình có thể chứa đồng thời K, M, Đ; gắn **mục tiêu chính** cho tình huống, và **nhiệm vụ riêng** cho từng nhận định.

## 3. Vật lý bắt buộc phải giữ khi tạo đề từ đồ thị T–t

Một mẫu chất cùng pha, khối lượng $m$ cố định, không có chuyển thể, công suất nhiệt hữu ích $P_{\rm ích}$ không đổi, $c$ có thể coi không đổi:
\[
P_{\rm ích}=\frac{Q}{\Delta t} \Longrightarrow \Delta T=\frac{P_{\rm ích}}{mc}\Delta t.
\]
Nếu có nhiệt dung dụng cụ $C$ cùng tăng nhiệt nhưng không hao môi trường:
\[
P=\left(mc+C\right)\frac{\Delta T}{\Delta t}.
\]
Nếu có trao đổi với môi trường, nguồn điện cấp $P$ **không đồng nghĩa** mẫu nhận $P$:
\[
P=(mc+C)\frac{\mathrm dT}{\mathrm dt}+P_{\rm hao}(T,\ldots).
\]

Hệ quả:
- $T(t)$ tăng đều chỉ khi các điều kiện về công suất hữu ích và nhiệt dung hiệu dụng hợp lệ.
- Độ dốc $T(t)$ giảm có thể là do $c$ thay đổi **hoặc** công suất hao nhiệt tăng; không tự kết luận một nguyên nhân.
- Nếu đường cong chứa đoạn chuyển thể, suy luận năng lượng dùng cho chuyển thể phải xét mức năng lượng hữu ích và khối lượng thực sự chuyển thể.
- Khi kiểm tra tính “$c$ không phụ thuộc $m$”, giữ cùng chất, cùng trạng thái và khoảng nhiệt độ phù hợp; *không tự suy* $c\propto1/m$ từ $Q=mc\Delta T$.
- Với giả thuyết “$c$ giảm khi $T$ tăng”, phải phân biệt $c$ trung bình trên mỗi khoảng và $c(T)$ tại một nhiệt độ, không dùng mô hình $c=\text{hằng số}$ để bác bỏ giả thuyết vốn đang được khảo sát.

## 4. Bài K THUẦN TÚY — tình huống PAH tự biên soạn, không số liệu

**Mục tiêu câu:** xem giả thuyết $T$ tăng đều theo thời gian có được kết quả kiểm chứng hay không; **không bắt học sinh tìm $c$ hay thiết kế phương pháp hiệu chỉnh**.

Một nhóm nghiên cứu muốn kiểm tra giả thuyết: “Với một mẫu chất lỏng không chuyển thể, nếu dây đốt cung cấp công suất điện không đổi thì nhiệt độ chất lỏng tăng đều theo thời gian”. Họ đặt mẫu chất lỏng vào nhiệt lượng kế có dây đốt, giữ khối lượng và công suất không đổi, dùng nhiệt kế ghi nhiệt độ sau những khoảng thời gian bằng nhau. Kết quả cho thấy độ tăng nhiệt độ ở các khoảng thời gian sau nhỏ hơn ở các khoảng trước. Nhiệt độ phòng không đổi và thấp hơn nhiệt độ mẫu trong thời gian khảo sát.

**Các nhận định Đúng/Sai:**

a) So sánh độ tăng nhiệt độ ở những khoảng thời gian bằng nhau là một cách kiểm tra giả thuyết nhiệt độ tăng đều theo thời gian. **Đúng**.

b) Vì công suất điện không đổi nên riêng mẫu chất lỏng nhất thiết nhận cùng một nhiệt lượng trong mọi khoảng thời gian bằng nhau. **Sai**; dụng cụ và môi trường có thể nhận nhiệt.

c) Nếu công suất truyền nhiệt hữu ích cho mẫu và bình là không đổi, nhiệt dung riêng của mẫu và nhiệt dung bình không đổi, không mất nhiệt ra môi trường, mô hình dự đoán nhiệt độ tăng đều theo thời gian. **Đúng**.

d) Kết quả độ tăng nhiệt độ mỗi khoảng giảm dần đã đủ để chứng minh nhiệt dung riêng của chất tăng khi nhiệt độ tăng. **Sai**; chưa loại được các giải thích khác, chẳng hạn truyền nhiệt ra ngoài tăng.

**Đáp án:** **Đ – S – Đ – S**, dựa trên điều kiện câu nêu. Câu chỉ hỏi **giả thuyết–dữ liệu–giới hạn kết luận** (K). Không có bước bắt buộc “hãy đo $c$ chính xác hơn”.

**Chú ý khi sửa đề:** “Công suất điện không đổi” khác “công suất hữu ích truyền cho mẫu không đổi”; phải phân biệt hai phát biểu, tránh gây tranh luận đáp án do bỏ sót điều kiện. Đây là bài mới PAH, **chưa qua duyệt**.

## 5. Chắt lọc kỹ thuật mới để soạn chuyên đề

- **K01: đặt giả thuyết có thể sai** để học sinh kiểm tra bằng quy trình và dữ liệu. Không phải cứ câu nào cũng ép kết luận “bác bỏ” — có thể kết luận **ủng hộ có điều kiện / không ủng hộ / chưa đủ dữ kiện**.
- **K02: kiểm tra tính độc lập**: $c$ thực có phụ thuộc $m$ không; nhưng $c$ ước lượng chưa hiệu chỉnh có thể phụ thuộc biểu kiến.
- **K03: đối chiếu lý tưởng và thực nghiệm**: khi $T(t)$ không thẳng như dự đoán, không được suy rằng định luật năng lượng sai.
- **M01: phép đo hằng số từ độ dốc / đoạn bằng nhiệt** với điều kiện đủ.
- **Đ01: sửa mô hình / quy trình khi phát hiện mất nhiệt** — là **mục tiêu riêng**, không bắt mọi câu K phải kết thúc bằng Đ.

## 6. Việc cần đối chiếu lần tới

- Mốc thời gian Video 06 về *đặt vấn đề*, *12 lệnh hỏi*, *diễn giải đồ thị* và *bước 5 thảo luận*: xác nhận từ video gốc.
- Câu chữ chính thức, hình và dữ liệu của 0211–II.4 và 0233–II.3; chú ý hai mã đề và thời điểm thi.
- Kiểm định tình huống mới, YCCD và tác dụng của hình vẽ trước khi duyệt câu hỏi dùng học sinh.

**Không ghi đè các chuyên đề K và Đ đã có.** Đây là hồ sơ bổ sung làm rõ ranh giới K–M–Đ; bộ câu K thuần túy tiếp tục phát triển trong [nhánh khảo sát sự phụ thuộc](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md). 
