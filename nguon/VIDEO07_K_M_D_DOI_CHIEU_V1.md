# VIDEO 07 — ĐỐI CHIẾU K–M–Đ VÀ KIỂM ĐỊNH GIẢ THIẾT HAI PHÉP ĐO

> **Ngày ghi nhận:** 15/10/2026. **Trạng thái:** bản nghiên cứu PAH — CHỜ GIÁO VIÊN DUYỆT; không phải bản chép lời thầy Nam.
>
> **Nguồn trực tiếp:** [Video 07 — Tìm hiểu quá trình trao đổi nhiệt và xác định nhiệt dung riêng.mp4](https://drive.google.com/file/d/17SvrdD3sHk1_sM1rcjKzMserTy1WAix1/view) trong [thư mục 07](https://drive.google.com/drive/folders/1KXn77mHYBwd3PQqSAC8tqUpjxqcHMmo8), ~46 phút 11 giây.
>
> **Nguồn thứ cấp:** Báo cáo NotebookLM do giáo viên cung cấp ngày 15/10/2026, đối chiếu Video 07 với đề chính thức 2025–2026.
>
> **Phạm vi trực kiểm:** đã đọc các khung hình và slide ở nhiều thời điểm đại diện; **chưa phiên âm toàn bộ lời giảng**, không khẳng định bất cứ ý kiến riêng nào là lời nguyên văn thầy Nam nếu không hiện rõ trên slide.

## 1. Mục tiêu nghiên cứu: K–M–Đ cùng nằm trong Video 07

| Mốc slide gần đúng | Nội dung slide trực kiểm | Nhãn theo PAH |
|---|---|---|
| ~03:00 | **Đề xuất vấn đề**: làm thí nghiệm để **xác định nhiệt dung riêng** từ theo dõi thay đổi nhiệt độ dưới tác dụng cấp nhiệt liên tục | **M** — đo đại lượng |
| ~10:00 | Báo cáo cho rằng tiến trình nhiệt độ–thời gian với công suất ổn định có thể **xác định $c$** | **M**, với giả thiết lý tưởng |
| ~12:00–14:00 | Thảo luận về nhiệt hấp thụ bởi thiết bị và mất ra môi trường; đề xuất dùng **nhiệt lượng kế cách nhiệt** | **M→Đ** — xác định hạn chế để nâng độ tin cậy |
| ~16:00–23:00 | **Câu hỏi từ đề chính thức 2026**: giả thuyết $c$ của nước phụ thuộc khối lượng mẫu, khảo sát dữ liệu và bác bỏ nhận định không phù hợp | **K** — kiểm định quan hệ; là một ví dụ được đưa vào bài |
| ~24:00 | Bắt đầu tiến trình nâng cao: tách hai nguyên nhân sai lệch — môi trường và bộ phận bên trong bình hấp thụ nhiệt | **Đ** — mục tiêu phương án mới |
| ~26:00 | Giả thuyết dùng hai khối lượng, các lần cấp nhiệt để có cùng **độ tăng nhiệt độ**, giảm ảnh hưởng phần nhiệt bình hấp thụ | **Đ** |
| ~28:00–34:00 | Mô hình năng lượng, hai lần đun và khử đại lượng phụ $Q_{\mathrm{hp}}$ qua hai phương trình | **Đ** |
| ~36:00 | Báo cáo về tác dụng giảm ảnh hưởng hấp thụ nhiệt của **các bộ phận bình**, không có nghĩa loại bỏ hoàn toàn trao đổi nhiệt môi trường | **Đ** |
| ~38:00–44:00 | Đề mẫu nhiều ý **a–h**, có sơ đồ nhiệt lượng kế, khóa các giả thiết và kiểm tra biểu thức | Chủ yếu **Đ**, gồm kỹ năng M |

**Chỉnh phân loại NotebookLM:**
- NotebookLM gọi “tiến trình cơ bản đo $c$” là **K** vì video có ví dụ câu Bộ về sự phụ thuộc $c$ theo $m$. Điều này **chỉ chính xác đối với tình huống đề Bộ nằm trong phần minh họa**; riêng mục tiêu gốc của tiến trình xác định $c$ là **M**.
- Không đúng khi nói video bỏ hoàn toàn K: thầy trực tiếp phân tích đề 2026. Nhưng **chưa thấy phần K được hệ thống hóa thành họ câu hỏi độc lập** cùng mức độ như Đ.
- Không suy từ hai đề giả thuyết sai rằng Bộ *luôn ưu tiên* đặt giả thuyết sai. Một giả thuyết khoa học hợp lệ phải có thể kiểm chứng; chứng cứ có thể ủng hộ có giới hạn, phản bác hoặc chưa đủ kết luận.

## 2. Giả thiết quan trọng nhất trong tiến trình nâng cao

**Slide khoảng ~28:00–34:00**, với công suất cấp điện **giống nhau $P$** ở cả hai lần, khối lượng khác nhau $m_1\ne m_2$, cùng độ tăng nhiệt $\Delta T>0$:
\[
Pt_1=cm_1\Delta T+Q_{\mathrm{hp}},\qquad
Pt_2=cm_2\Delta T+Q_{\mathrm{hp}}.
\]
Suy ra:
\[
c=\frac{P(t_2-t_1)}{\Delta T(m_2-m_1)},\qquad
Q_{\mathrm{hp}}=\frac{P(t_1m_2-t_2m_1)}{m_2-m_1}.
\]

**Vì sao khử được $Q_{\mathrm{hp}}$?** Nếu cùng nhiệt lượng kế có nhiệt dung $C$ không đổi, cùng nhiệt độ ban đầu và cùng độ tăng nhiệt, thì nhiệt lượng **bộ phận bình** hấp thụ là
\[
Q_{\mathrm{bình}}=C\Delta T,
\]
bằng nhau. Đây là cơ chế khoa học, **không chỉ là phép trừ hai phương trình**.

**Phải tách ra ngoài mô hình:** nhiệt lượng trao đổi với môi trường
\[
Pt_i=(m_ic+C)\Delta T+Q_{\mathrm{mt},i}.
\]
Cùng $\Delta T$ **không tự bảo đảm** $Q_{\mathrm{mt},1}=Q_{\mathrm{mt},2}$ vì thời gian đun và diễn biến nhiệt độ có thể khác nhau. Dùng bình cách nhiệt **giảm** trao đổi nhiệt môi trường, không làm nó đương nhiên bằng 0.

**Căn cứ nguồn trực tiếp:** trong câu hỏi mẫu ở slide ~38:00, đề **ghi rõ** (i) nhiệt lượng các phần bên trong nhiệt lượng kế hấp thụ **coi là bằng nhau** và (ii) nhiệt lượng truyền ra bên ngoài **không đáng kể**, đồng thời bỏ qua bay hơi/ngưng tụ. Với các giả thiết được nêu rõ, biểu thức khử là phù hợp. Không thể đem điều kiện này gán cho mọi thí nghiệm thực tế.

**Lưu ý công suất:** slide giả thuyết ~26:00 diễn đạt các lần cấp nhiệt có thể dùng **công suất khác nhau**, còn slide phương trình và đề mẫu cuối cùng dùng **cùng công suất $P$**. Nếu thật sự $P_1\ne P_2$, cần viết
\[
c=\frac{P_2t_2-P_1t_1}{\Delta T(m_2-m_1)}
\]
khi vẫn bảo đảm cùng $Q_{\mathrm{bình}}$ và bỏ qua/kiểm soát thất thoát môi trường. **Không dùng công thức $P(t_2-t_1)$ nếu hai công suất khác nhau.**

## 3. Ma trận kỹ thuật tạo câu riêng từ chính Video 07

| Mục đích | Câu hỏi nghiên cứu KHÁC nhau | Dữ kiện cần khóa | Sai lầm để kiểm tra |
|---|---|---|---|
| **K — khảo sát** | $c$ thực có phụ thuộc khối lượng mẫu hay không? | Cùng chất, cùng trạng thái, cùng khoảng nhiệt độ; có kiểm soát bình & môi trường | Nhầm $c_{\rm đo}$ chưa hiệu chỉnh với $c$ thực |
| **K — khảo sát** | Nếu cấp cùng năng lượng hữu ích, $\Delta T$ phụ thuộc vào $m$ như thế nào? | Cùng chất, $c$ gần như không đổi; nhiệt dung dụng cụ không đáng kể hoặc đưa vào mô hình | Suy luôn tỉ lệ nghịch từ công thức mà không nhìn $C$ |
| **M — đo** | Chỉ đo $P,t,m,\Delta T$ có đủ xác định $c$ không? | Điều kiện phân phối nhiệt của hệ | Đồng nhất $Pt$ với nhiệt chất nhận |
| **M — đo** | Nếu đo nhiều điểm $\Delta T$ theo thời gian, giá trị ước lượng $c$ đáng tin khi nào? | Công suất hữu ích và nhiệt dung hiệu dụng, trạng thái vật | Nhầm đồ thị tăng nhiệt đều với việc đã loại sai lệch |
| **Đ — cải tiến** | Vì sao hai lần có cùng $\Delta T$ khử được phần nhiệt của bình? | Cùng bình, cùng nhiệt độ ban đầu, $C$ không đổi | Cho rằng cùng thời gian mới đủ hoặc cùng $\Delta T$ là đủ cho mọi hao phí |
| **Đ — đánh giá** | Khi thời gian đun khác nhau, còn phần nhiệt trao đổi với môi trường không? | Mô hình thất thoát hoặc điều kiện cách nhiệt | Nhầm giảm thất thoát với khử chính xác thất thoát |

Các ô này là **gợi ý PAH, không có nghĩa video đã đặt đúng những câu trên**.

## 4. Bài học sư phạm chuyển giao

**Cùng một thiết bị có thể có K, M và Đ nhưng ba loại có ba mục đích:**
1. **K:** Kiểm tra *mối quan hệ* giữa đại lượng quan sát/đại lượng vật lý.
2. **M:** *Ước lượng* một đại lượng từ số đo và mô hình.
3. **Đ:** *Đánh giá và nâng cấp* phương án để phép ước lượng đáng tin hơn.

Không coi các nhánh là thang từ thấp đến cao. Có thể xây 4 mức tư duy độc lập cho mỗi nhánh.

**Một ý kiểm tra khó quan trọng của Đ:** Nếu cùng $\Delta T$ nhưng $t_1\ne t_2$, “nhiệt lượng truyền ra môi trường chắc chắn bằng nhau” là **SAI**, trừ khi có giả thiết bổ sung kiểm soát tổn thất đó. Đây là **câu PAH phát triển**, không phải nhận định nguyên văn nguồn.

**Không copy nội dung video vào ngân hàng đề**; chỉ lưu trục phương pháp, nguồn gốc, điều kiện và nhận định mới có kiểm định.

## 5. Liên kết hồ sơ

- [Hệ 4 mức PM01 và sáu câu mở rộng](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)
- [Nhánh K — khảo sát sự phụ thuộc](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md)
- [Video 06 — audit K–M–Đ](VIDEO06_K_M_D_DOI_CHIEU_V1.md)

**Bước trước khi biên soạn câu hoàn chỉnh:** chọn mục đích nghiên cứu; đối chiếu slide/công thức; dựng bối cảnh và hình có vai trò trong lập luận; kiểm tra điều kiện mô hình; giáo viên duyệt rồi mới chuyển LaTeX chính thức.
