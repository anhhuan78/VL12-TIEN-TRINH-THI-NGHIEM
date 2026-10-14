---
title: "PAH | CHUYÊN ĐỀ PHƯƠNG PHÁP 01"
subtitle: "Hai phép đo — một đại lượng gây nhiễu — điều kiện xác định"
author: "Bản nghiên cứu & biên soạn thử | Vật lí 12"
date: "14/10/2026"
geometry: margin=2.2cm
fontsize: 11pt
lang: vi-VN
---

> **Trạng thái:** Chuyên đề PHỎNG THEO NGUỒN, do PAH biên soạn thử; chưa phải bản giáo viên duyệt để sử dụng chấm điểm. Câu gốc chỉ được mô tả và liên kết, không sao chép nguyên cả bộ đề. Các bài phía dưới là **câu hỏi mới**.

# 1. Từ hai câu nguồn thật, tìm ra trục tư duy

**Nguồn A — DE 01.pdf, trang 3, phần II, câu 1:** [Mở bản PDF gốc trên Google Drive](https://drive.google.com/file/d/1GHKuGYy8MZlTZ-bB26fQ0xz4pRX4HkX1/view). Tác giả tổ chức hai lần đun những lượng chất khác nhau trong cùng nhiệt lượng kế. Nhiệt lượng kế cũng nhận năng lượng, phần đó tỉ lệ với độ tăng nhiệt độ. Học sinh phải phân tích biểu thức tổng quát và đánh giá hiệu quả phương án đo.

**Nguồn B — Đề về đích số 2, trang 3, phần II, câu 1:** [Mở bản PDF gốc trên Google Drive](https://drive.google.com/file/d/17OQbyOM309R-VGrOQfyXsTSMNjUmk5My/view). Tác giả bố trí hai giai đoạn đun chất lỏng đang sôi, cùng thời gian nhưng khác công suất. Nhiệt độ sôi thấp hơn nhiệt độ môi trường nên có nhiệt từ môi trường truyền vào. Học sinh đánh giá khả năng loại ảnh hưởng môi trường khi xác định nhiệt hóa hơi riêng.

**Nhận xét PAH, không phải phát biểu trích nguyên văn của tác giả:** Hai câu gốc cùng khai thác một vấn đề nghiên cứu: **làm sao xác định đại lượng cần đo khi dữ liệu còn chịu ảnh hưởng của đại lượng phụ chưa biết?** Song hai đại lượng phụ có cơ chế khác nhau, do đó phải xử lý khác nhau.

# 2. Trục gốc: đừng trừ phương trình trước khi nhận diện đại lượng phụ

Một phép đo không chỉ cho “số liệu để thế công thức”. Nó phản ánh một **cân bằng vật lý**. Hãy đi từ điều kiện thí nghiệm đến phương trình:

1. **Chọn hệ:** Năng lượng đang đi vào và tích lũy ở đâu?
2. **Viết phương trình cho từng phép đo:** Không bỏ qua phần năng lượng của bình/môi trường khi đề chưa cho phép.
3. **Chỉ ra ẩn cần tìm và đại lượng phụ:** Đại lượng phụ xuất hiện dưới dạng **cùng một nhiệt dung** hay **cùng một công suất trao đổi nhiệt**?
4. **Biến đổi để làm lộ phần chung:** Khi cần, chia hai vế cho độ tăng nhiệt độ hoặc cho thời gian trước khi trừ.
5. **Kiểm tra thông tin độc lập:** Phép trừ có thực sự còn đại lượng cần tìm hay chỉ còn đẳng thức $0=0$?
6. **Kiểm chứng kết luận:** Thế nghiệm vào các phương trình ban đầu; kiểm tra đơn vị và giả thiết.

## 2.1. Nguồn A — nhiệt dung của bình

Trong mô hình không chuyển thể, bỏ qua trao đổi nhiệt với môi trường, cùng một bình có nhiệt dung hiệu dụng $C$ không đổi:

$$
P_i\tau_i=(m_ic+C)\Delta T_i,\qquad i=1,2.
$$

Sau khi chia cho $\Delta T_i>0$:

$$
\frac{P_i\tau_i}{\Delta T_i}=m_i c+C.
$$

Suy ra, nếu $m_1\ne m_2$:

$$
\boxed{c=\frac{P_2\tau_2/\Delta T_2-P_1\tau_1/\Delta T_1}{m_2-m_1}},\qquad
C=\frac{P_1\tau_1}{\Delta T_1}-m_1c.
$$

**Phản ví dụ quan trọng:** Nếu $m_1=m_2=m$, dù thay đổi $P_i$ và $\tau_i$ bao nhiêu lần (với các giả thiết vẫn giữ nguyên), ta chỉ xác định được $mc+C$, không thể tách riêng $c,C$ khi chưa có thông tin bổ sung.

## 2.2. Nguồn B — trao đổi nhiệt với môi trường

Ở nhiệt độ sôi không đổi, giả sử trong hai giai đoạn có cùng thời gian $t$ và nhiệt lượng môi trường truyền vào là cùng $Q_{\mathrm{mt}}$:

$$
m_iL=P_it+Q_{\mathrm{mt}}.
$$

Trừ hai phương trình:

$$
\boxed{L=\frac{(P_2-P_1)t}{m_2-m_1}},\qquad m_2\ne m_1.
$$

Nếu **thời gian không bằng nhau** mà giả sử **công suất trao đổi nhiệt với môi trường $P_{\mathrm{mt}}$ không đổi**, mô hình đúng là

$$
m_iL=(P_i+P_{\mathrm{mt}})t_i
\quad\Rightarrow\quad
\boxed{L=\frac{P_2-P_1}{m_2/t_2-m_1/t_1}}
$$

khi mẫu số khác 0. Không được áp dụng công thức thời gian bằng nhau cho trường hợp này.

**Lưu ý nguồn:** Câu gốc B có cách diễn đạt một nhận định về *nhiệt dung riêng* trong khi thí nghiệm nghiên cứu *nhiệt hóa hơi riêng*; đây là điểm cần giữ trong hồ sơ kiểm định, không tự sửa rồi gọi là văn bản gốc.

# 3. Bài thực hành A — câu mới do PAH tạo sinh (Đúng/Sai)

Một câu lạc bộ khoa học muốn xác định nhiệt dung riêng $c$ của nước bằng dây điện trở. Trong lần thử đầu, các thành viên dự đoán: “Giữ nguyên điện năng cung cấp, nếu dùng gấp đôi khối lượng nước thì độ tăng nhiệt độ chắc chắn giảm còn một nửa”. Một thành viên khác cho rằng dự đoán này đã bỏ quên nhiệt lượng kế.

Nhóm sử dụng **cùng một nhiệt lượng kế**, dây điện trở có công suất truyền nhiệt cho hệ $P=60\,\mathrm{W}$, mỗi lần đun $\tau=120\,\mathrm{s}$. Hai lần đều bắt đầu từ nhiệt độ như nhau, không có sự chuyển thể. Bỏ qua trao đổi nhiệt với môi trường; coi $c$ và nhiệt dung hiệu dụng $C$ của bình không đổi. Số liệu ghi nhận:

| Lần đo | Khối lượng nước $m$ | Độ tăng nhiệt độ $\Delta T$ |
|:--:|--:|--:|
| 1 | $0{,}20\,\mathrm{kg}$ | $7{,}2\,\mathrm{K}$ |
| 2 | $0{,}40\,\mathrm{kg}$ | $4{,}0\,\mathrm{K}$ |

Xác định Đúng hoặc Sai cho các nhận định:

a) Kết quả đo phù hợp với dự đoán độ tăng nhiệt độ lần 2 bằng đúng một nửa lần 1.

b) Với lần đo 1, có thể viết $P\tau/\Delta T_1=m_1c+C$.

c) Từ hai lần đo này, nhiệt dung hiệu dụng của bình là $C=200\,\mathrm{J/K}$.

d) Nếu giữ nguyên khối lượng nước trong mọi lần đo và chỉ thay đổi công suất, thời gian đun thì vẫn xác định riêng được $c$ và $C$ từ hai phương trình tương ứng.

**Đáp án:** a) Sai; b) Đúng; c) Đúng; d) Sai.

**Lời giải ngắn (dành cho giáo viên):** $P\tau=7200\,\mathrm{J}$; lập hệ

$$
\begin{cases}
7200=(0{,}20c+C)\cdot7{,}2,\\
7200=(0{,}40c+C)\cdot4{,}0.
\end{cases}
$$

Suy ra $0{,}20c+C=1000\,\mathrm{J/K}$; $0{,}40c+C=1800\,\mathrm{J/K}$, nên $c=4000\,\mathrm{J/(kg\cdot K)}$ và $C=200\,\mathrm{J/K}$. Độ tăng nhiệt độ lần 2 là $4{,}0\,\mathrm K$, không phải $3{,}6\,\mathrm K$.

**Tác dụng của bốn ý:** (a) đối chiếu giả thuyết và dữ liệu; (b) lập mô hình; (c) xử lý định lượng; (d) đánh giá thiết kế phép đo. Đây là cách PAH ứng dụng kỹ thuật phân bố câu hỏi qua các bước tiến trình đã phân tích từ video 05, **không phải sao chép câu của video**.

# 4. Bài chuyển giao B — cùng trục tư duy, khác hiện tượng

Một kỹ thuật viên kiểm tra phương pháp xác định nhiệt hóa hơi riêng $L$ của một chất lỏng có nhiệt độ sôi thấp hơn nhiệt độ phòng. Khi chất đang sôi, kỹ thuật viên dùng nguồn điện cấp nhiệt trong hai giai đoạn **cùng $120\,\mathrm{s}$** và ghi khối lượng hóa hơi. Thiết bị được giữ ở điều kiện sao cho nhiệt lượng môi trường truyền vào trong hai lần là bằng nhau.

| Giai đoạn | Công suất $P$ | Khối lượng hóa hơi $m$ |
|:--:|--:|--:|
| 1 | $90\,\mathrm W$ | $6{,}0\,\mathrm g$ |
| 2 | $150\,\mathrm W$ | $9{,}0\,\mathrm g$ |

Coi $L$ không đổi; bỏ qua những ảnh hưởng khác.

Xác định Đúng hoặc Sai:

a) Nhiệt lượng chất lỏng nhận được ở giai đoạn 1 chỉ là $P_1t$.

b) Dữ liệu cho phép tính $L=2{,}4\times10^6\,\mathrm{J/kg}$.

c) Trong mỗi giai đoạn, môi trường đã truyền cho chất lỏng $3600\,\mathrm J$.

d) Nếu thay bằng hai khoảng thời gian khác nhau nhưng công suất trao đổi nhiệt với môi trường vẫn không đổi thì nhiệt lượng do môi trường truyền vào hai giai đoạn vẫn luôn bằng nhau.

**Đáp án:** a) Sai; b) Đúng; c) Đúng; d) Sai.

**Lời giải ngắn (dành cho giáo viên):**

$$
L=\frac{(150-90)\cdot120}{(9-6)\times10^{-3}}=2{,}4\times10^6\,\mathrm{J/kg};
$$

$$
Q_{\mathrm{mt}}=m_1L-P_1t=0{,}006\cdot2{,}4\times10^6-90\cdot120=3600\,\mathrm J.
$$

Nếu $P_{\mathrm{mt}}$ không đổi thì $Q_{\mathrm{mt},i}=P_{\mathrm{mt}}t_i$; thời gian khác nhau kéo theo nhiệt lượng trao đổi khác nhau, trừ trường hợp công suất trao đổi bằng 0.

# 5. Phần chốt để dạy học sinh

**Thông điệp:** Không được mặc định “cứ có hai lần đo là tìm được hai ẩn”, và cũng không được mặc định “cứ có cùng đại lượng phụ là trừ được ngay”. Phải biết **đại lượng phụ phụ thuộc vào yếu tố nào**.

| Câu hỏi dẫn dắt trong giờ học | Dấu hiệu học sinh đã hiểu |
|---|---|
| Hệ đang nhận năng lượng từ đâu? | Viết được phương trình năng lượng **đủ thành phần** |
| Bình nhận thêm nhiệt theo gì? | Nói được $Q_{\mathrm{bình}}=C\Delta T$ |
| Môi trường trao đổi nhiệt theo gì? | Với công suất môi trường không đổi: $Q_{\mathrm{mt}}=P_{\mathrm{mt}}t$ |
| Khi nào phép đo giúp tách hai ẩn? | Xác định được đại lượng phải thay đổi; kiểm tra hệ không suy biến |
| Thí nghiệm chứng minh được điều gì? | Nêu được kết luận **trong các giả thiết và phạm vi đo** |

**Bài tập chuyển giao nhanh, không cần số liệu:** Một nhóm đun cùng một khối lượng nước ba lần với các cặp công suất–thời gian khác nhau. Chúng có thể xác định riêng $c$ và $C$ hay không? Vì sao? **Trả lời:** Không, nếu $C$ đều chưa biết và mô hình không đổi; mọi lần chỉ cung cấp một tổ hợp $mc+C$.

# 6. Khung tạo sinh từ câu đã có (dùng lại, không sinh tùy ý)

**Dữ liệu phải khóa:** nguồn câu và vị trí, phương trình vật lý, điều kiện, giá trị thực được chọn, giả thuyết cần kiểm tra, kiểu nhận định, đáp án kiểm định.

**Các phép biến đổi hợp lệ đã minh họa:** thay khối lượng nhưng giữ bình; thay thời gian/công suất nhưng giữ khối lượng để kiểm tra tính xác định; thay hiện tượng từ tăng nhiệt độ sang hóa hơi **đồng thời thay mô hình phụ tương ứng**.

**Không tự động hợp lệ:** giả thiết $Q_{\mathrm{mt}}$ bằng nhau khi thời gian khác nhau; tự bỏ nhiệt dung của bình; nội suy từ kết quả đo sang định luật phổ quát; dùng số liệu đúng công thức nhưng mâu thuẫn với điều kiện vật lý.

**Kiểm định tối thiểu mỗi câu mới:** (1) kiểm tra số liệu bằng phương trình gốc; (2) đáp án mọi nhận định xác định; (3) có ngữ cảnh thực nghiệm hữu ích; (4) truy được về mô hình/câu gốc; (5) phân biệt rõ **câu nguồn** với **câu phỏng theo PAH**.

---

**Nguồn đối chiếu:** DE 01.pdf, tr. 3, II.1; Đề về đích số 2, tr. 3, II.1. **Khung đặt nhận định theo tiến trình** tham khảo phân tích video 05, cần tiếp tục kiểm định khi chuyển sang những ví dụ khác. **Chuyên đề và câu số liệu đều do PAH tổng hợp/biên soạn**, không phải bản nguyên văn của các tác giả nguồn.