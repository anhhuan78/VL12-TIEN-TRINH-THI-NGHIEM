# PM01 — Khung tạo sinh câu hỏi từ bốn nguồn (v1)

> **Trạng thái:** Khung biên soạn có kiểm định toán học, nhưng **chưa được giáo viên duyệt**. Nguồn: [bản đối chiếu bốn đề](../nguon/PM01_DOI_CHIEU_4_CAU_NGUON_V1.md). Bài mới ghi **PAH phỏng theo**, không gán là câu nguyên bản.

## I. Trục bắt buộc không được phá

1. Một tình huống có **mục tiêu đo** $X$ và **đại lượng phụ** $Y$.
2. Đề mô tả nguồn năng lượng, hệ và điều kiện rõ ràng; **nếu có môi trường trao đổi nhiệt, chỉ ra chiều truyền**.
3. Mỗi giai đoạn cho phương trình năng lượng hợp lệ rồi đưa về $R_i=a_iX+b_iY$.
4. Tính $D=a_1b_2-a_2b_1$. Nếu $D=0$ thì câu yêu cầu tính riêng hai ẩn bị loại, trừ khi chủ đích là câu **phản biện không đủ dữ kiện**.
5. Kiểm tra đơn vị, dấu, giá trị vật lý ($c,\lambda,L>0$; $C\ge0$; $P_{\rm hao}\ge0$ nếu gọi là công suất mất ra môi trường).
6. Dữ kiện bảng phải được **sinh từ tham số thật** rồi thế ngược vào mọi phương trình; không chọn số ngẫu nhiên độc lập.
7. Thử mỗi nhận định bằng trường hợp đặc biệt và đối chiếu đúng điều kiện đề.

## II. Bốn mẫu phương trình (không dùng lẫn)

| Mẫu | Phương trình đúng khi… | Đại lượng phụ | Điều kiện để tìm $X,Y$ |
|---|---|---|---|
| PM01-A | $P_it_i=(m_ic+C)\Delta T_i$; không chuyển thể, bình $C$ không đổi, không thất thoát | $C$ | $\Delta T_i\ne0$, $m_1\ne m_2$ |
| PM01-B | $P_it=m_i\lambda+Q_{\rm mất}$; chuyển thể rắn-lỏng ở nhiệt độ không đổi và khoản mất bằng nhau | $Q_{\rm mất}$ | $m_1\ne m_2$ |
| PM01-C | $P_i=(m_i/t_i)L+P_{\rm hao}$; đun sôi ở nhiệt độ trên môi trường, công suất hao ổn định | $P_{\rm hao}$ | $t_i>0$, $m_1/t_1\ne m_2/t_2$ |
| PM01-D | $P_it=m_iL-Q_{\rm vào}$; sôi dưới nhiệt độ phòng, môi trường truyền vào bằng nhau | $Q_{\rm vào}$ | $m_1\ne m_2$ |

**Được đổi:** hiện tượng phù hợp trong cùng mẫu, tên dụng cụ, giả thuyết, ngữ cảnh, thông số được sinh kiểm soát, vai trò nhận định a–d; so sánh phương án khác nhau ở cùng một mô hình.

**Không được tự đổi:** bỏ thành phần năng lượng phụ, đổi chiều nhiệt không sửa dấu, cho hai thời gian khác nhau nhưng vẫn khẳng định hai khoản $Q_{\rm môi trường}$ bằng nhau nếu chỉ biết công suất trao đổi ổn định, dùng mẫu A khi có chuyển thể, coi $P_1\ne P_2$ là điều kiện toán học đủ cho mọi tình huống phi tuyến.

## III. Khung 4 nhận định trong một câu

Một câu Đúng/Sai có ngữ cảnh đủ thật (vấn đề hoặc giả thuyết, thiết bị và phép đo, bảng kết quả/kết luận) chọn **bốn nhiệm vụ khác nhau**:
- Nhận diện bản chất năng lượng đầu vào/đầu ra.
- Đánh giá giả thuyết qua kết quả hoặc tính đủ thông tin của thiết kế.
- Lập hoặc thẩm định biểu thức tìm $X$.
- Kiểm tra đại lượng phụ, điều kiện giới hạn hoặc cải tiến thí nghiệm.

Phối vị trí và dấu Đúng/Sai, không gài sai bằng câu văn mơ hồ. Không bắt buộc cả bốn loại trong mọi đề; phải có ít nhất 2 thao tác tư duy khác nhau.

## IV. Hai câu sinh mới — kiểm tra tham số

### PAH-PM01-C01 — Thí nghiệm làm nóng chất lỏng (Đ/S)

Một nhóm học sinh dùng cùng một nhiệt lượng kế có dây đốt để kiểm tra giả thuyết: “Khi tăng khối lượng chất lỏng gấp đôi và giữ nguyên điện năng cấp, độ tăng nhiệt độ sẽ giảm đúng một nửa.” Mỗi lần dây đốt cấp **$84\,\mathrm W$ trong $100\,\mathrm s$**. Hai lần bắt đầu cùng nhiệt độ, không chuyển thể; bỏ qua trao đổi nhiệt với ngoài; nhiệt dung riêng $c$ và nhiệt dung $C$ của bình không đổi.

| Lần đo | $m$ | $\Delta T$ |
|---|---|---|
| 1 | $0{,}30\,\mathrm{kg}$ | $7{,}0\,\mathrm K$ |
| 2 | $0{,}60\,\mathrm{kg}$ | $4{,}0\,\mathrm K$ |

a) Dữ liệu xác nhận giả thuyết “giảm còn đúng một nửa”. **Sai**.

b) Năng lượng điện cấp mỗi lần bằng tổng nhiệt lượng chất lỏng và nhiệt lượng kế hấp thụ. **Đúng**.

c) Hai lần đo cho nhiệt dung riêng $c=3000\,\mathrm{J/(kg\cdot K)}$ và nhiệt dung của bình $C=300\,\mathrm{J/K}$. **Đúng**.

d) Nếu giữ nguyên khối lượng mà chỉ đổi thời gian và công suất, dù đo nhiều lần cũng không thể tìm riêng $c,C$ nếu không biết thêm đại lượng khác. **Đúng**.

**Kiểm định:**
\[
84\cdot100=(0{,}30\cdot3000+300)\cdot 7=8400\ \mathrm J;
\]
\[
84\cdot100=(0{,}60\cdot3000+300)\cdot 4=8400\ \mathrm J.
\]
$m_2=2m_1$, nhưng $\Delta T_2=4\,\mathrm K\ne \Delta T_1/2=3{,}5\,\mathrm K$; $m_1\ne m_2$ nên tách được hai ẩn. **Trạng thái: Đã kiểm tra đại số, CHỜ GIÁO VIÊN DUYỆT.**

### PAH-PM01-C02 — Hóa hơi, thời gian khác nhau (Đ/S)

Một nhóm học sinh đặt thiết bị đo khối lượng dưới bình đun để xác định nhiệt hóa hơi riêng của một chất lỏng có nhiệt độ sôi lớn hơn nhiệt độ phòng. Công suất nhiệt mất ra môi trường được xem không đổi trong toàn bộ phép đo. Thực hiện hai giai đoạn:

| Giai đoạn | Công suất cấp | Thời gian | Khối lượng hóa hơi |
|---|---:|---:|---:|
| 1 | $150\,\mathrm W$ | $100\,\mathrm s$ | $6{,}0\,\mathrm g$ |
| 2 | $220\,\mathrm W$ | $160\,\mathrm s$ | $15{,}2\,\mathrm g$ |

a) Công suất hữu ích dùng để hóa hơi ở giai đoạn đầu là $120\,\mathrm W$. **Đúng**.

b) Nhiệt hóa hơi riêng của chất lỏng bằng $2{,}0\times10^6\,\mathrm{J/kg}$. **Đúng**.

c) Mỗi giai đoạn, nhiệt lượng thất thoát ra môi trường bằng nhau vì công suất thất thoát không đổi. **Sai**.

d) Nếu ở một phương án khác tốc độ hóa hơi hai giai đoạn bằng nhau thì hai phép đo vẫn luôn đủ để xác định duy nhất cả $L$ và $P_{\rm hao}$. **Sai**.

**Kiểm định:**
\[
(150-30)\cdot100=0.006\cdot 2\,000\,000=12000\ \mathrm J,
\]
\[
(220-30)\cdot160=0.0152\cdot 2\,000\,000=30400\ \mathrm J.
\]
$P_{\rm hao}=30\,\mathrm W$, $L=2\times10^6\,\mathrm{J/kg}$, $m_1/t_1\ne m_2/t_2$.

> **Trạng thái câu:** C02 có kiểm tra số liệu và suy biến toán học; vẫn CHỜ GIÁO VIÊN DUYỆT trước khi in. C01 đã sửa số liệu để thỏa mãn đầy đủ phương trình. Cả C01 và C02 đều CHỜ GIÁO VIÊN DUYỆT; việc kiểm toán chứng minh tính cần thiết của bước thế nghiệm.

## V. Mẫu lệnh ra đề bằng AI từ kho Git

“Đọc hồ sơ PM01 và bốn câu nguồn được liên kết trên Drive. Dùng khung PM01 phiên bản đang có để tạo **[số lượng]** câu **[MCQ/Đúng-Sai/Trả lời ngắn]** về **[mẫu A/B/C/D]**. Mỗi câu có một mục tiêu tư duy khác nhau, mô hình và điều kiện rõ, số liệu sinh từ tham số hợp lý; tự thế ngược xác minh mọi phương trình, rà đơn vị và tình huống suy biến. Xuất câu học sinh, đáp án giáo viên và LaTeX BODY; phân biệt biến thể PAH với câu gốc. Nếu phát hiện lỗi, loại câu trước khi xuất; tất cả giữ trạng thái CHỜ DUYỆT.”
