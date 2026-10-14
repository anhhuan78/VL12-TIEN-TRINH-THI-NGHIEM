# PM01 — Đối chiếu bốn câu nguồn (bản nghiên cứu 01)

> **Ngày:** 15/10/2026. **Trạng thái:** ĐANG KIỂM ĐỊNH, chưa phải đáp án gốc đã xác nhận.
> **Đầu vào:** báo cáo NotebookLM “PM01 — PHÂN TÍCH 4 CÂU HỎI NGUỒN” do giáo viên đưa ngày 15/10/2026.
> **Cảnh báo xuất xứ:** Các trích dẫn [1]–[4] trong báo cáo là chỉ dấu bên NotebookLM, không tự động xác nhận rằng các phép giải và giải thích là lời của tác giả. Phân biệt **đề ghi** và **PAH suy ra**.

## Danh mục nguồn và tình trạng đối chiếu

| Mã | PDF gốc và vị trí | Tình trạng |
|---|---|---|
| N01 | [DE 01.pdf](https://drive.google.com/file/d/1GHKuGYy8MZlTZ-bB26fQ0xz4pRX4HkX1/view), tr. 3, II.1 | Đã đối chiếu ảnh câu gốc; các phép suy luận dưới đây là kiểm định PAH |
| N06 | [DE 06 - Hoc sinh.pdf](https://drive.google.com/file/d/1hCInlzsOKiSfyuXgQLwJPNoO1cZp9iYM/view), tr. 3, II.1 | Mới có bản trích NotebookLM; **CẦN ĐỐI CHIẾU ẢNH PDF GỐC** |
| N08 | [DE 08 - Hoc sinh.pdf](https://drive.google.com/file/d/1bWkYyDa0kFQpe6OT2moSRO9UQLNjf4sm/view), tr. 3, II.1 | Mới có bản trích NotebookLM; **CẦN ĐỐI CHIẾU ẢNH PDF GỐC** |
| N02 | [Đề về đích số 2](https://drive.google.com/file/d/17OQbyOM309R-VGrOQfyXsTSMNjUmk5My/view), tr. 3, II.1 | Đã đối chiếu ảnh câu gốc; có lỗi biểu thức / diễn đạt trong nhận định nguồn |

## 1. N01 — Nhiệt dung của dụng cụ

**Đề gốc mô tả:** hai lần đun khối lượng khác nhau bằng cùng nhiệt lượng kế; phần bên trong nhiệt lượng kế hấp thụ nhiệt tỉ lệ với độ tăng nhiệt độ; nhiệt truyền ra ngoài không đáng kể.

**Mô hình PAH diễn giải** (cần bổ sung giả thiết không chuyển thể, $c,C$ ổn định và điện năng chuyển vào hệ):
\[
P_i t_i=(m_ic+C)\Delta T_i;\qquad
\frac{P_i t_i}{\Delta T_i}=m_i c+C.
\]
Với $\Delta T_i\ne0$ và $m_1\ne m_2$:
\[
c=\frac{P_2t_2/\Delta T_2-P_1t_1/\Delta T_1}{m_2-m_1}.
\]

**Phản biện nguồn:** ý a của câu gốc nói đến khả năng chuyển thể, trong khi công thức nhiệt dung riêng ở ý c chỉ có dạng nêu trên nếu *không* có nhiệt chuyển thể. Báo cáo NotebookLM tự thêm “bỏ qua chuyển thể” vào giả thiết; phải phân biệt với nguyên văn đề. Ý c dùng từ “chất lỏng” dù phần giới thiệu nói “một chất”. Không được âm thầm sửa đề gốc thành đề đã đầy đủ điều kiện.

**Kết luận phương pháp:** khử được $C$ bằng chia theo $\Delta T_i$ rồi trừ; nếu $m_1=m_2$, dữ liệu chỉ cho $mc+C$, dù thay $P,t$.

## 2. N06 — Nóng chảy, tổn thất ra môi trường

**Theo NotebookLM:** quá trình ở nhiệt độ nóng chảy cao hơn nhiệt độ môi trường, cùng thời gian $t$, hai công suất, nhiệt lượng ra môi trường ở hai giai đoạn bằng nhau.

**Mô hình PAH:**
\[
P_i t=m_i\lambda+Q_{\rm mất}.
\]
Nếu $Q_{\rm mất}$ thật sự bằng nhau:
\[
\lambda=\frac{(P_2-P_1)t}{m_2-m_1},\quad m_2\ne m_1.
\]

**Điểm khóa:** $t_1=t_2$ **không tự bảo đảm** hai khoản thất thoát bằng nhau; phải có giả thiết trao đổi nhiệt tương đương / công suất mất nhiệt ổn định. Mệnh đề “công suất hai giai đoạn bắt buộc khác không” phải xét thêm chiều nhiệt, lượng nóng chảy thực đo và các nguồn năng lượng khác; **chưa đóng dấu đáp án** trước khi đối chiếu toàn bộ đề.

## 3. N08 — Hóa hơi, tổn thất với công suất không đổi

**Theo NotebookLM:** chất lỏng sôi ở nhiệt độ cao hơn môi trường; $P_{\rm hao}$ không đổi, nhưng $t_1,t_2$ có thể khác nhau.

**Mô hình PAH:**
\[
P_it_i=m_iL+P_{\rm hao}t_i
\quad\Longleftrightarrow\quad
P_i=\frac{m_i}{t_i}L+P_{\rm hao}.
\]
\[
L=\frac{(P_2-P_1)t_1t_2}{m_2t_1-m_1t_2},\qquad
P_{\rm hao}=\frac{m_2P_1t_1-m_1P_2t_2}{m_2t_1-m_1t_2}.
\]

**Điểm khóa:** mẫu $m_2t_1-m_1t_2\ne0$. Điều kiện cốt lõi là **tốc độ hóa hơi hai giai đoạn khác nhau**, không phải “thời gian buộc phải khác nhau”. Nếu $t_1=t_2=t$ thì rút về mẫu N06/N02 với chiều nhiệt tương ứng.

## 4. N02 — Hóa hơi, môi trường TRUYỀN nhiệt VÀO

**Đề gốc:** nhiệt độ sôi thấp hơn nhiệt độ môi trường; thời gian bằng nhau; nguồn điện và môi trường đồng thời truyền năng lượng cho chất lỏng.

**Mô hình PAH:**
\[
m_iL=P_it+Q_{\rm vào},\qquad
L=\frac{(P_2-P_1)t}{m_2-m_1},\qquad
Q_{\rm vào}=\frac{(m_1P_2-m_2P_1)t}{m_2-m_1}.
\]

**Lỗi trong đề nguồn được nhìn thấy khi đối chiếu ảnh:**
- Ý c ghi $(m_2P_1+m_1P_2)t$ cho nhiệt lượng nhận từ môi trường: **sai thứ nguyên** (biểu thức mang đơn vị $\mathrm{kg\cdot J}$, không phải $\mathrm J$). Không được lấy làm công thức chuẩn.
- Ý d nói kết quả đo **nhiệt dung riêng** trong một thí nghiệm xác định **nhiệt hóa hơi riêng**: lỗi diễn đạt / đổi tên đại lượng. Khi dùng làm đề mới phải viết lại, không gán là nguyên văn tác giả.

## 5. Trục PAH rút ra, KHÔNG gán cho tác giả

Đặt dữ liệu sau biến đổi ở dạng hai phương trình:
\[
R_1=a_1X+b_1Y,\qquad R_2=a_2X+b_2Y.
\]
Trong đó $X$ là đại lượng mục tiêu ($c,\lambda,L$), $Y$ là đại lượng phụ ($C,Q_{\rm mất},P_{\rm hao},Q_{\rm vào}$).

**Đủ thông tin khi** $\boxed{D=a_1b_2-a_2b_1\ne0}$. Nếu $D=0$, hai phương trình không xác định duy nhất hai ẩn; còn phải kiểm tra chúng có nhất quán hay không.

| Nguồn | $R_i$ | $a_i$ | $b_i$ | $X$ | $Y$ |
|---|---|---|---|---|---|
| N01 | $P_it_i/\Delta T_i$ | $m_i$ | $1$ | $c$ | $C$ |
| N06 | $P_it$ | $m_i$ | $1$ | $\lambda$ | $Q_{\rm mất}$ |
| N08 | $P_i$ | $m_i/t_i$ | $1$ | $L$ | $P_{\rm hao}$ |
| N02 | $P_it$ | $m_i$ | $-1$ | $L$ | $Q_{\rm vào}$ |

**Chốt để dạy:** xác định hệ và chiều nhiệt → viết phương trình đầy đủ → nhận dạng ẩn phụ → chuẩn hóa để làm rõ ẩn chung → kiểm tra $D$ (hoặc điều kiện tương đương) → giải và thế kiểm tra.

## 6. Các nhóm lệnh hỏi đã được tìm thấy trong nguồn

1. Phân biệt năng lượng nguồn cấp và năng lượng vật nhận.
2. Kiểm tra điều kiện cần / không cần của thiết kế phép đo.
3. Xác minh biểu thức tìm đại lượng mục tiêu.
4. Xác minh biểu thức đại lượng phụ.
5. Đánh giá giả thuyết và giới hạn kết luận.

**Cảnh báo biên soạn:** ưu tiên dạy học sinh *lập mô hình vật lí* rồi mới biến đổi; không bắt học thuộc công thức định thức. Mô hình tuyến tính trên là **trục tổng quát PAH suy ra**, không phải công thức chính thức mà bốn PDF tự trình bày.

## 7. Chốt trạng thái

- **ĐÃ XÁC MINH TRỰC TIẾP:** ảnh nguồn N01, N02; sự tồn tại và vị trí PDF.
- **ĐÃ KIỂM TRA ĐẠI SỐ:** bốn mô hình điều kiện kể trên.
- **CẦN ĐỐI CHIẾU ẢNH NGUỒN:** N06, N08 (các câu chữ nguyên văn và ý d).
- **CHƯA CÓ:** bảng đáp án chính thức của tác giả cho bốn câu.
- **KHÔNG được tuyên bố:** “4/4 câu nguồn đã chuẩn hóa” hoặc “công thức do tác giả nêu” khi chỉ là PAH tự suy ra.
