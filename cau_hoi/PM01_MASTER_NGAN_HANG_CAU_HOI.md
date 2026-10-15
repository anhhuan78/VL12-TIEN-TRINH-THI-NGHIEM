# PAH · MASTER NGÂN HÀNG CÂU HỎI THỰC NGHIỆM — PM01

> **Ngày tổng hợp: 15/10/2026 — CHỜ GIÁO VIÊN DUYỆT.** Đây là bộ câu do PAH biên soạn hoặc phát triển từ phương pháp nguồn, **không phải câu chính thức của Bộ, Cambridge, AP hay IOP**. Một số đáp án đã được kiểm toán đại số nhưng chưa có dữ liệu làm bài thực tế để đánh giá độ khó.
>
> **Tổng:** **28 câu Đúng/Sai khác nhau về tình huống hoặc dữ liệu**, gồm câu có số và không số; bản TeX trùng một câu không được đếm thêm. File này chứa **nội dung đầy đủ, đáp án và phần giải thích từ file gốc** để giáo viên lấy nhanh; **không dùng nguyên bản này phát cho học sinh**, vì đáp án có thể hiện ngay trên dòng câu hỏi.

## Quy ước phân loại

- **K — Khảo sát:** câu hỏi nghiên cứu nhằm kiểm tra *mối quan hệ, sự phụ thuộc hoặc giả thuyết*.
- **M — Đo:** câu hỏi nhằm *xác định đại lượng chưa biết* qua quan sát, thiết kế và xử lý đo.
- **Đ — Cải tiến:** câu hỏi nhằm *khử yếu tố gây nhiễu, đánh giá phương án đo hoặc kiểm tra mức đáng tin của kết luận*. Chữ **Đ** không có nghĩa Đúng/Sai.
- **4 mức độc lập với K–M–Đ:** (1) Nhận diện; (2) Mô hình hóa; (3) Thiết kế/kiểm định điều kiện phép đo; (4) Đánh giá chứng cứ và phản biện.
- **Mã cố định** `PM01-K-3-02`: PM01 / nhánh K / mức 3 / thứ tự trong nhóm. Không đánh lại số khi bổ sung câu, chỉ nối số cuối.
- **Mỗi câu 1 nhánh chính** theo mục tiêu chủ đạo (dù một ý riêng lẻ có thể thuộc nhánh khác). Mức là mức cao nhất cần huy động trong câu. Một vài mức là đề xuất phân loại của MASTER, được ghi chú.
- **Trạng thái mặc định:** `NHÁP – CHỜ DUYỆT`. Đề và lời giải dưới đây giữ đúng trạng thái tại file nguồn.

## I. MA TRẬN TRA CỨU NHANH

| Nhánh | Mức 1 | Mức 2 | Mức 3 | Mức 4 | Tổng |
|---|---|---|---|---|---:|
| **K** | [PM01-K-1-01](#pm01-k-1-01) | [PM01-K-2-01](#pm01-k-2-01)<br>[PM01-K-2-02](#pm01-k-2-02) | [PM01-K-3-01](#pm01-k-3-01) | [PM01-K-4-01](#pm01-k-4-01)<br>[PM01-K-4-02](#pm01-k-4-02)<br>[PM01-K-4-03](#pm01-k-4-03)<br>[PM01-K-4-04](#pm01-k-4-04)<br>[PM01-K-4-05](#pm01-k-4-05) | **9** |
| **M** | [PM01-M-1-01](#pm01-m-1-01)<br>[PM01-M-1-02](#pm01-m-1-02) | [PM01-M-2-01](#pm01-m-2-01)<br>[PM01-M-2-02](#pm01-m-2-02) | [PM01-M-3-01](#pm01-m-3-01)<br>[PM01-M-3-02](#pm01-m-3-02)<br>[PM01-M-3-03](#pm01-m-3-03)<br>[PM01-M-3-04](#pm01-m-3-04)<br>[PM01-M-3-05](#pm01-m-3-05) | [PM01-M-4-01](#pm01-m-4-01)<br>[PM01-M-4-02](#pm01-m-4-02) | **11** |
| **Đ** | [PM01-Đ-1-01](#pm01-đ-1-01) | [PM01-Đ-2-01](#pm01-đ-2-01) | [PM01-Đ-3-01](#pm01-đ-3-01)<br>[PM01-Đ-3-02](#pm01-đ-3-02)<br>[PM01-Đ-3-03](#pm01-đ-3-03)<br>[PM01-Đ-3-04](#pm01-đ-3-04) | [PM01-Đ-4-01](#pm01-đ-4-01)<br>[PM01-Đ-4-02](#pm01-đ-4-02) | **8** |
| **Tổng** | **4** | **5** | **10** | **9** | **28** |

### Bảng chọn nhanh (Ctrl+F theo từ khóa)

| Mã câu | Nhóm / Mức | Chủ đề | Dữ liệu số | Đáp án (nháp) | File nguồn |
|---|---|---|:---:|:---:|---|
| [PM01-K-1-01](#pm01-k-1-01) | K/1 | Cùng nhiệt lượng, thay đổi khối lượng | Không | **S–Đ–Đ–S** | [K1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-1-01](#pm01-m-1-01) | M/1 | Chọn số đo cần thiết để xác định c | Không | **S–Đ–Đ–S** | [M1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-1-02](#pm01-m-1-02) | M/1 | Nguồn điện cấp nhiệt có phải chất nhận hết? | Không | **Đ–S–Đ–Đ** | [Tiến trình / Câu 1](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-Đ-1-01](#pm01-đ-1-01) | Đ/1 | Đo nền để loại ảnh hưởng nhiệt môi trường | Không | **S–S–Đ–Đ** | [Đ1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-K-2-01](#pm01-k-2-01) | K/2 | Hai chất có nhiệt dung riêng khác nhau | Không | **S–Đ–S–Đ** | [K2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-K-2-02](#pm01-k-2-02) | K/2 | Gấp đôi khối lượng, ΔT có giảm một nửa? | Không | **Đ–S–Đ–S** | [Tiến trình / Câu 2](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-M-2-01](#pm01-m-2-01) | M/2 | Đồ thị đun nóng qua chuyển thể | Không | **Đ–S–S–Đ** | [M2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-2-02](#pm01-m-2-02) | M/2 | Chất lỏng sôi dưới nhiệt độ phòng nhận nhiệt từ đâu? | Không | **S–Đ–Đ–S** | [Tiến trình / Câu 3](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-Đ-2-01](#pm01-đ-2-01) | Đ/2 | Hai khối lượng cùng ΔT: khử nhiệt bình | Không | **S–Đ–Đ–S** | [Đ2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-K-3-01](#pm01-k-3-01) | K/3 | Thiết kế kiểm chứng ΔT phụ thuộc m | Không | **Đ–S–S–Đ** | [K3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-3-01](#pm01-m-3-01) | M/3 | Nhiều phép đo cùng m có đủ tách c,C? | Không | **S–Đ–S–Đ** | [M3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-3-02](#pm01-m-3-02) | M/3 | Hai khối lượng và bảng số liệu để tách c,C | Có | **S–Đ–Đ–Đ** | [Khung tạo sinh / C01](../cau_hoi/PM01_KHUNG_TAO_SINH_V1.md) |
| [PM01-M-3-03](#pm01-m-3-03) | M/3 | Hóa hơi hai thời gian: tính L và công suất hao | Có | **Đ–Đ–S–S** | [Khung tạo sinh / C02](../cau_hoi/PM01_KHUNG_TAO_SINH_V1.md) |
| [PM01-M-3-04](#pm01-m-3-04) | M/3 | Bài thực hành A: tìm c,C bằng hai lần đun | Có | **S–Đ–Đ–S** | [Hai phép đo / Bài A](../chuyen_de/PM01_HAI_PHEP_DO_VLN_BAN_THAO.md) |
| [PM01-M-3-05](#pm01-m-3-05) | M/3 | Bài chuyển giao B: chất lỏng nhận nhiệt môi trường | Có | **S–Đ–Đ–S** | [Hai phép đo / Bài B](../chuyen_de/PM01_HAI_PHEP_DO_VLN_BAN_THAO.md) |
| [PM01-Đ-3-01](#pm01-đ-3-01) | Đ/3 | Cùng ΔT không bảo đảm cùng nhiệt thất thoát | Không | **S–Đ–S–Đ** | [Đ3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-Đ-3-02](#pm01-đ-3-02) | Đ/3 | Hai thời gian khác nhau: khử công suất hao thế nào? | Không | **Đ–Đ–S–S** | [Tiến trình / Câu 4](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-Đ-3-03](#pm01-đ-3-03) | Đ/3 | Hai bố trí: bố trí nào tách được c và C? | Không | **Đ–S–Đ–S** | [Tiến trình / Câu 5](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-Đ-3-04](#pm01-đ-3-04) | Đ/3 | Cùng thời gian nhưng nhiệt thất thoát có bằng nhau? | Không | **S–Đ–Đ–S** | [Tiến trình / Câu 7](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-K-4-01](#pm01-k-4-01) | K/4 | Sự phụ thuộc giả tạo của c đo theo m | Không | **S–Đ–S–Đ** | [K4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-K-4-02](#pm01-k-4-02) | K/4 | Nhiệt dung riêng biểu kiến phụ thuộc khối lượng | Không | **Đ–S–Đ–S** | [Nhánh K / K01](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md) |
| [PM01-K-4-03](#pm01-k-4-03) | K/4 | Khảo sát nhiệt dung riêng theo nhiệt độ | Không | **Đ–S–Đ–S** | [Nhánh K / K02](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md) |
| [PM01-K-4-04](#pm01-k-4-04) | K/4 | Nhiệt độ tăng không đều dù công suất điện không đổi | Không | **Đ–S–Đ–S** | [Video 06 / câu K](../nguon/VIDEO06_K_M_D_DOI_CHIEU_V1.md) |
| [PM01-K-4-05](#pm01-k-4-05) | K/4 | Nồng độ muối và nhiệt độ sôi: giới hạn suy luận | Có | **Đ–S–Đ–S** | [Video 05 / câu PAH](../chuyen_de/PHAN_TICH_VIDEO_05_BAN_THAO.md) |
| [PM01-M-4-01](#pm01-m-4-01) | M/4 | Hai tốc độ hóa hơi: điều kiện xác định L,H | Không | **Đ–S–Đ–S** | [M4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-M-4-02](#pm01-m-4-02) | M/4 | Bình cứng: không đổi khác với đã biết | Không | **Đ–S–S–Đ** | [Tiến trình / Câu 8](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |
| [PM01-Đ-4-01](#pm01-đ-4-01) | Đ/4 | Thí nghiệm thứ ba kiểm định phương án đo | Không | **Đ–S–S–Đ** | [Đ4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md) |
| [PM01-Đ-4-02](#pm01-đ-4-02) | Đ/4 | Dữ liệu trái dự đoán: phản biện mô hình | Không | **Đ–S–S–Đ** | [Tiến trình / Câu 6](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md) |

## II. NỘI DUNG ĐẦY ĐỦ — XẾP THEO MỨC × NHÁNH

**Chú ý:** Bản toàn văn là trích từ file PAH trong repo ở thời điểm tổng hợp, không phải file nguồn gốc bất biến. Khi sửa câu gốc, phải đồng bộ lại MASTER và kiểm tra lại đáp án.

## MỨC 1 — Nhận diện hiện tượng, hệ và đại lượng

**Nhánh K: Khảo sát mối quan hệ / kiểm định giả thuyết**

### PM01-K-1-01

**Tên:** Cùng nhiệt lượng, thay đổi khối lượng  
**Phân loại:** K / mức 1 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** khối lượng; độ tăng nhiệt; biến độc lập  
**Nguồn nguyên bản PAH:** [K1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một nhóm muốn khảo sát độ tăng nhiệt độ của nước phụ thuộc vào khối lượng như thế nào. Nhóm sử dụng hai phần nước cùng trạng thái, có nhiệt độ ban đầu bằng nhau; mỗi phần được cung cấp **cùng một nhiệt lượng thực sự truyền cho nước**. Khối lượng mẫu B lớn hơn mẫu A. Trong khoảng thí nghiệm, nhiệt dung riêng $c$ của nước không đổi, không có chuyển thể.

a) Mẫu B có độ tăng nhiệt độ lớn hơn mẫu A do khối lượng lớn hơn. **S**.

b) Khối lượng nước là đại lượng được chủ động thay đổi trong thí nghiệm. **Đ**.

c) Độ tăng nhiệt độ của nước là đại lượng nhóm cần đo để đánh giá sự phụ thuộc. **Đ**.

d) Từ thí nghiệm này có thể kết luận nhiệt dung riêng của nước tỉ lệ nghịch với khối lượng mẫu. **S**.

**Đáp án:** **S–Đ–Đ–S**.

**Giải thích:** $\Delta T=Q/(mc)$. Với cùng $Q$ hữu ích và $c$, mẫu lớn hơn tăng nhiệt ít hơn. $c$ được giả định là đặc trưng không đổi của chất; không suy $c\propto1/m$ từ công thức.

**Hình cần vẽ:** hai cốc nước A và B, cùng nhiệt độ ban đầu, cùng mũi tên nhiệt lượng $Q$, khác mức khối lượng.

---

**Nhánh M: Đo đại lượng vật lí**

### PM01-M-1-01

**Tên:** Chọn số đo cần thiết để xác định c  
**Phân loại:** M / mức 1 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nhiệt dung riêng; công suất; thời gian  
**Nguồn nguyên bản PAH:** [M1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một nhóm dùng dây điện trở có công suất điện $P$ không đổi để đun một khối lượng $m$ chất lỏng. Nhiệt lượng kế được coi không thu nhiệt, nhiệt truyền ra môi trường không đáng kể; chất không chuyển thể và $c$ không đổi trong khoảng khảo sát. Nhóm đo nhiệt độ trước và sau khi đun trong thời gian $t$.

a) Để xác định $c$ theo mô hình, có thể bỏ phép đo khối lượng $m$. **S**.

b) Cần xác định độ tăng nhiệt $\Delta T$ từ hai số chỉ nhiệt kế. **Đ**.

c) Trong điều kiện đã giả định, có thể dùng $Pt=mc\Delta T$. **Đ**.

d) Đo đúng thời gian $t$ là đủ xác định $c$ ngay cả khi chưa biết công suất, khối lượng và $\Delta T$. **S**.

**Đáp án:** **S–Đ–Đ–S**.

**Giải thích:** $c=Pt/(m\Delta T)$; mỗi đại lượng đo có một vai trò, không được bỏ bớt tùy ý.

**Hình cần vẽ:** nhiệt lượng kế, dây đốt, đồng hồ, cân, nhiệt kế, nguồn điện có wattmeter.

---

### PM01-M-1-02

**Tên:** Nguồn điện cấp nhiệt có phải chất nhận hết?  
**Phân loại:** M / mức 1 · **Đáp án thử:** `Đ–S–Đ–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nóng chảy; bảo toàn năng lượng; nhiệt mất  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 1](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Một phòng thực hành muốn xác định nhiệt nóng chảy riêng của một chất rắn tinh thể. Chất được duy trì ở nhiệt độ nóng chảy, **cao hơn nhiệt độ phòng**, trong suốt hai giai đoạn. Người làm thí nghiệm dùng cùng một nồi đun, mỗi giai đoạn cấp điện trong thời gian $t$, nhưng công suất lần sau $P_2$ lớn hơn $P_1$. Phần nhiệt truyền ra môi trường trong hai giai đoạn được coi là **bằng nhau và khác không**; còn đủ chất rắn chưa nóng chảy hết ở cả hai giai đoạn. Gọi $m_1,m_2$ là khối lượng nóng chảy tương ứng.

a) Điện năng dây đốt cung cấp ở giai đoạn $i$ là $P_it$.

b) Nhiệt lượng chất rắn dùng để nóng chảy ở giai đoạn $i$ bằng toàn bộ $P_it$.

c) Nếu những điều kiện trên được bảo đảm, khối lượng nóng chảy ở giai đoạn 2 lớn hơn giai đoạn 1.

d) Việc giữ thời gian bằng nhau không cản trở xác định nhiệt nóng chảy riêng từ hai kết quả đo khác nhau.

**Giáo viên:** **Đ–S–Đ–Đ**. Mô hình $P_it=m_i\lambda+Q_{\rm mất}$, $Q_{\rm mất}>0$ chung cả hai; lấy hiệu suy ra $(P_2-P_1)t=(m_2-m_1)\lambda$. Chốt: *nguồn cấp bao nhiêu không đồng nghĩa đối tượng nghiên cứu nhận trọn bấy nhiêu*.

---

**Nhánh Đ: Cải tiến / đánh giá độ tin cậy của phép đo**

### PM01-Đ-1-01

**Tên:** Đo nền để loại ảnh hưởng nhiệt môi trường  
**Phân loại:** Đ / mức 1 · **Đáp án thử:** `S–S–Đ–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nóng chảy; đo nền; năng lượng phụ  
**Nguồn nguyên bản PAH:** [Đ1 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một nhóm muốn đo nhiệt nóng chảy riêng của nước đá ở nhiệt độ nóng chảy trong phòng ấm. Nước đá đặt trong phễu có dây điện trở, nước tan chảy được hứng và cân. Nhóm đo **giai đoạn A không cấp điện** và **giai đoạn B có cấp điện**; hai giai đoạn dài bằng nhau. Nhóm nêu **giả thiết bổ sung**: phần nhiệt do môi trường truyền vào nước đá trong hai giai đoạn bằng nhau, hệ không tích lũy năng lượng đáng kể ngoài chuyển thể.

a) Chỉ vì hai giai đoạn cùng thời gian, nhiệt từ môi trường chắc chắn bằng nhau trong mọi bố trí. **S**.

b) Nếu bỏ giả thiết nhiệt môi trường truyền vào hai giai đoạn bằng nhau, việc lấy chênh lệch khối lượng tan vẫn luôn loại trừ chính xác tác động của môi trường. **S**.

c) Trong giai đoạn A, nước đá vẫn có thể tan do nhận nhiệt từ môi trường. **Đ**.

d) Với giả thiết đã cho, chênh lệch khối lượng nước đá tan là do phần nhiệt tăng thêm từ dây điện trở ở giai đoạn B. **Đ**.

**Đáp án:** **S–S–Đ–Đ**.

**Giải thích:** dưới các điều kiện mô hình, $\lambda(m_B-m_A)=Pt$ nếu chỉ gia tăng phần cấp điện ở B. Cùng thời gian là một lựa chọn thiết kế, **chưa tự đủ** để chứng minh nhiệt môi trường bằng nhau.

**Hình cần vẽ:** hai trạng thái phễu nước đá, dây đốt OFF/ON, cân dưới phễu.

---

## MỨC 2 — Mô hình hóa, giải thích kết quả

**Nhánh K: Khảo sát mối quan hệ / kiểm định giả thuyết**

### PM01-K-2-01

**Tên:** Hai chất có nhiệt dung riêng khác nhau  
**Phân loại:** K / mức 2 · **Đáp án thử:** `S–Đ–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** c; nhiệt lượng hữu ích; biến kiểm soát  
**Nguồn nguyên bản PAH:** [K2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Nhóm khảo sát ảnh hưởng của bản chất vật liệu đến độ tăng nhiệt độ. Hai khối rắn A, B có cùng khối lượng và nhiệt độ ban đầu, được cung cấp cùng nhiệt lượng hữu ích, không chuyển thể; nhiệt dung riêng của A nhỏ hơn B và đều xem như không đổi trong khoảng đo.

a) Hai vật có cùng khối lượng và nhận cùng nhiệt lượng thì nhất thiết có cùng độ tăng nhiệt độ. **S**.

b) Với các điều kiện đã cho, vật A tăng nhiệt độ nhiều hơn vật B. **Đ**.

c) Kết quả A tăng nhiệt nhiều hơn cho phép suy ra nhiệt dung riêng của A lớn hơn B. **S**.

d) Khi khảo sát ảnh hưởng của bản chất chất, việc giữ cùng khối lượng và nhiệt lượng cấp giúp hạn chế sự lẫn lộn do hai yếu tố này. **Đ**.

**Đáp án:** **S–Đ–S–Đ**.

**Giải thích:** $\Delta T=Q/(mc)$, nên $c_A<c_B\Rightarrow\Delta T_A>\Delta T_B$; cần phân biệt thứ tự các đại lượng với quan hệ tỉ lệ. Thí nghiệm khảo sát quan hệ, không phải hiệu chuẩn nhiệt lượng kế.

**Hình cần vẽ:** hai khối A/B, mũi tên $Q$ như nhau, nhiệt kế ban đầu bằng nhau.

---

### PM01-K-2-02

**Tên:** Gấp đôi khối lượng, ΔT có giảm một nửa?  
**Phân loại:** K / mức 2 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** giả thuyết; khối lượng; nhiệt dung bình  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 2](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Một nhóm học sinh muốn đo nhiệt dung riêng của một chất lỏng trong **cùng nhiệt lượng kế**. Một bạn dự đoán: “Giữ nguyên điện năng đun, khi khối lượng chất lỏng gấp đôi thì độ tăng nhiệt độ giảm còn đúng một nửa.” Nhóm đun hai khối lượng $m$ và $2m$, cùng điện năng, cùng nhiệt độ ban đầu và đo hai độ tăng nhiệt độ. Chất không chuyển thể; nhiệt dung hiệu dụng $C$ của bình **dương, không đổi**; bỏ qua trao đổi nhiệt với bên ngoài và các ảnh hưởng khác.

a) Điện năng cấp cho mỗi lần đo bằng tổng nhiệt lượng chất lỏng và nhiệt lượng kế hấp thụ.

b) Vì khối lượng lần sau gấp đôi nên độ tăng nhiệt độ lần sau bằng đúng một nửa lần đầu.

c) Độ tăng nhiệt độ lần sau nhỏ hơn lần đầu nhưng **lớn hơn một nửa** lần đầu.

d) Nếu giữ khối lượng không đổi mà chỉ thay công suất và thời gian, hai lần đo vẫn luôn cho phép tìm riêng cả nhiệt dung riêng của chất và nhiệt dung của bình.

**Giáo viên:** **Đ–S–Đ–S**. Tự lập $E=(mc+C)\Delta T_1=(2mc+C)\Delta T_2$; với $m,c,C>0$: $\frac12<\Delta T_2/\Delta T_1<1$. Nếu giữ $m$ không đổi thì chỉ tìm được tổ hợp $mc+C$. Chốt: *không được suy luận quan hệ tỉ lệ nghịch khi còn một thành phần năng lượng phụ*.

---

**Nhánh M: Đo đại lượng vật lí**

### PM01-M-2-01

**Tên:** Đồ thị đun nóng qua chuyển thể  
**Phân loại:** M / mức 2 · **Đáp án thử:** `Đ–S–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** đồ thị T–t; nóng chảy; độ dốc  
**Nguồn nguyên bản PAH:** [M2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một mẫu chất rắn tinh khiết được cấp nhiệt với công suất **hữu ích không đổi** trong một thiết bị không trao đổi nhiệt với môi trường. Đồ thị nhiệt độ theo thời gian gồm đoạn A–B tăng nhiệt độ khi còn rắn; đoạn B–C nằm ngang trong lúc mẫu nóng chảy hoàn toàn; đoạn C–D tăng nhiệt độ khi mẫu đã lỏng. Khối lượng mẫu không đổi, không có biến đổi hóa học.

a) Đoạn B–C biểu diễn quá trình mẫu vẫn nhận năng lượng nhưng nhiệt độ không tăng. **Đ**.

b) Vì nhiệt độ không đổi trên B–C, mẫu hoàn toàn không nhận năng lượng từ nguồn. **S**.

c) Độ dốc của A–B và C–D chắc chắn bằng nhau vì cùng nguồn điện. **S**.

d) Nếu biết công suất hữu ích và khối lượng đã nóng chảy, có thể dùng thời lượng B–C để ước lượng nhiệt nóng chảy riêng. **Đ**.

**Đáp án:** **Đ–S–S–Đ**.

**Giải thích:** trên B–C năng lượng dùng cho chuyển thể, $\lambda=P_{\rm ích}(t_C-t_B)/m$ khi nóng chảy hoàn toàn. Sườn gia nhiệt trong hai pha có thể khác nhau do nhiệt dung riêng khác nhau.

**Hình cần vẽ bắt buộc:** đường gấp khúc A–B–C–D theo trục $t,T$, B–C nằm ngang, rõ nhãn đoạn.

---

### PM01-M-2-02

**Tên:** Chất lỏng sôi dưới nhiệt độ phòng nhận nhiệt từ đâu?  
**Phân loại:** M / mức 2 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hóa hơi; nguồn nhiệt môi trường  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 3](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Một chất lỏng tinh khiết có nhiệt độ sôi **thấp hơn nhiệt độ phòng** được khảo sát bằng nguồn điện điều chỉnh công suất. Khi chất đã sôi ổn định, người nghiên cứu cấp điện hai giai đoạn **cùng thời gian $t$**, với $P_2>P_1\ge0$, đo khối lượng hóa hơi $m_1,m_2$. Coi **nhiệt lượng dương từ môi trường truyền vào chất lỏng ở mỗi giai đoạn như nhau**, nhiệt hóa hơi riêng không đổi, bỏ qua các ảnh hưởng khác.

a) Nguồn điện là nguồn năng lượng duy nhất làm chất lỏng hóa hơi.

b) Hiệu nhiệt lượng dùng để hóa hơi ở hai giai đoạn bằng $(P_2-P_1)t$.

c) Nếu ở một giai đoạn ngừng cấp điện, chất lỏng vẫn có thể tiếp tục hóa hơi nhờ nhiệt lượng môi trường truyền vào, trong các điều kiện đang xét.

d) Khối lượng hóa hơi luôn tỉ lệ thuận với công suất điện cấp, tức $m_2/m_1=P_2/P_1$ với $P_1>0$.

**Giáo viên:** **S–Đ–Đ–S**. $m_iL=P_it+Q_{\rm vào}$, $Q_{\rm vào}>0$ chung. Điện năng không phải nguồn duy nhất; $m_i=(P_it+Q_{\rm vào})/L$ nên không tỉ lệ thuận trực tiếp với $P_i$. Chốt: *trước khi khử ẩn, xác định chiều trao đổi năng lượng*.

---

**Nhánh Đ: Cải tiến / đánh giá độ tin cậy của phép đo**

### PM01-Đ-2-01

**Tên:** Hai khối lượng cùng ΔT: khử nhiệt bình  
**Phân loại:** Đ / mức 2 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hiệu chỉnh; nhiệt dung bình; phép trừ  
**Nguồn nguyên bản PAH:** [Đ2 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Nhóm dùng cùng một nhiệt lượng kế có nhiệt dung chưa biết $C$ để đo $c$ của chất lỏng. Hai lần đun có khối lượng $m_1\ne m_2$, công suất điện như nhau $P$, thời gian tương ứng $t_1,t_2$. **Nhiệt độ ban đầu và độ tăng nhiệt $\Delta T>0$ bằng nhau trong hai lần**, các bộ phận của bình cùng tăng nhiệt, $C$ không đổi, không chuyển thể và bỏ qua truyền nhiệt ra môi trường.

a) Chỉ cần giữ cùng $\Delta T$, không cần cùng bình hoặc cùng nhiệt dung bình vẫn chắc chắn khử được nhiệt lượng của bình. **S**.

b) Trong mô hình trên, nhiệt lượng bình hấp thụ ở hai lần bằng nhau. **Đ**.

c) Phép trừ hai phương trình dẫn đến $c=P(t_2-t_1)/[\Delta T(m_2-m_1)]$. **Đ**.

d) Nếu $m_1=m_2$ thì công thức trên vẫn xác định được $c$ hữu hạn mà không cần phép đo bổ sung. **S**.

**Đáp án:** **S–Đ–Đ–S**.

**Giải thích:** $Pt_i=(m_ic+C)\Delta T$. Phần bình $C\Delta T$ bằng nhau; khi trừ hai lần nó triệt tiêu. Cần $m_1\ne m_2$ và các điều kiện làm giả thiết “cùng $C\Delta T$” đúng.

**Hình cần vẽ bắt buộc:** hai bình cùng cấu tạo, mức nước khác nhau, nhiệt kế có cùng $\Delta T$, thời gian khác nhau $t_1,t_2$.

---

## MỨC 3 — Thiết kế phép đo và kiểm tra điều kiện

**Nhánh K: Khảo sát mối quan hệ / kiểm định giả thuyết**

### PM01-K-3-01

**Tên:** Thiết kế kiểm chứng ΔT phụ thuộc m  
**Phân loại:** K / mức 3 · **Đáp án thử:** `Đ–S–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** giả thuyết; biến khảo sát; kiểm soát thời gian  
**Nguồn nguyên bản PAH:** [K3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Hai nhóm muốn kiểm tra giả thuyết “độ tăng nhiệt độ của cùng chất lỏng phụ thuộc vào khối lượng khi năng lượng truyền cho chất không đổi”. Nhóm I thay đổi **đồng thời** khối lượng và thời gian đun, giữ công suất điện cố định. Nhóm II thay đổi **chỉ khối lượng**, giữ nhiệt lượng **hữu ích truyền cho chất** bằng nhau giữa các lần; cả hai nhóm đều dùng cùng chất, cùng trạng thái ban đầu, không chuyển thể. Nhóm II đo $\Delta T$ sau mỗi lần.

a) Nhóm II đã chủ động thay đổi đúng biến cần khảo sát. **Đ**.

b) Ở nhóm I, mọi thay đổi nhiệt độ đo được đều có thể quy cho riêng sự thay đổi khối lượng. **S**.

c) Vì công suất điện của nhóm I không đổi, điện năng nguồn cấp chắc chắn bằng nhau dù thời gian đun khác nhau. **S**.

d) Để đánh giá giả thuyết, nhóm II có thể so sánh $\Delta T$ ở các giá trị khối lượng khác nhau. **Đ**.

**Đáp án:** **Đ–S–S–Đ**.

**Giải thích:** Nhóm I thay đồng thời $m$ và $t$, nên $E=Pt$ cũng biến đổi — phép kiểm tra chưa cô lập được ảnh hưởng $m$. Nhóm II giữ $Q_{\rm hữu ích}$ cố định nên phù hợp hơn cho câu hỏi nghiên cứu.

**Hình cần vẽ:** sơ đồ hai phương án I (thay đổi $m,t$) và II (chỉ thay $m$), điểm khóa biến.

---

**Nhánh M: Đo đại lượng vật lí**

### PM01-M-3-01

**Tên:** Nhiều phép đo cùng m có đủ tách c,C?  
**Phân loại:** M / mức 3 · **Đáp án thử:** `S–Đ–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hai ẩn; phép đo độc lập; tính xác định  
**Nguồn nguyên bản PAH:** [M3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một nhóm đun cùng một khối lượng $m$ nước trong cùng nhiệt lượng kế có nhiệt dung **chưa biết $C$**. Công suất $P$ được xác định, nhiệt lượng ra môi trường không đáng kể, nước không chuyển thể, $c$ và $C$ không đổi. Nhóm đo nhiều cặp thời gian đun $t$ và độ tăng nhiệt $\Delta T$ với cùng khối lượng nước.

a) Chỉ tăng số lần đo $t,\Delta T$ ở cùng $m$ luôn đủ để xác định riêng cả $c$ và $C$. **S**.

b) Từ độ dốc đường $\Delta T$ theo $t$, nhóm xác định được tổ hợp $mc+C$. **Đ**.

c) Vì nhiệt lượng kế không trao đổi nhiệt với môi trường, nó không thể hấp thụ phần nào điện năng cấp vào. **S**.

d) Nếu $C$ được xác định bằng phép hiệu chuẩn độc lập, nhóm có thể tìm riêng $c$. **Đ**.

**Đáp án:** **S–Đ–S–Đ**.

**Giải thích:** $Pt=(mc+C)\Delta T$. Các phép đo lặp cùng cấu trúc chỉ cho một tổ hợp hai ẩn. **Không hao nhiệt ra ngoài** khác **bình không hấp thụ nhiệt**.

**Hình cần vẽ:** cùng bình và cùng $m$, các điểm đo trên đồ thị $\Delta T(t)$ thẳng qua gốc lý tưởng.

---

### PM01-M-3-02

**Tên:** Hai khối lượng và bảng số liệu để tách c,C  
**Phân loại:** M / mức 3 · **Đáp án thử:** `S–Đ–Đ–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nhiệt dung riêng; bảng số liệu; nhiệt dung bình  
**Nguồn nguyên bản PAH:** [Khung tạo sinh / C01](../cau_hoi/PM01_KHUNG_TAO_SINH_V1.md)  
**Lưu ý:** Biến thể định lượng của mô hình khối lượng–ΔT; câu chữ và dữ liệu khác.

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

---

### PM01-M-3-03

**Tên:** Hóa hơi hai thời gian: tính L và công suất hao  
**Phân loại:** M / mức 3 · **Đáp án thử:** `Đ–Đ–S–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hóa hơi; bảng số liệu; hai ẩn  
**Nguồn nguyên bản PAH:** [Khung tạo sinh / C02](../cau_hoi/PM01_KHUNG_TAO_SINH_V1.md)

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

---

### PM01-M-3-04

**Tên:** Bài thực hành A: tìm c,C bằng hai lần đun  
**Phân loại:** M / mức 3 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nhiệt dung bình; hai khối lượng; giả thuyết  
**Nguồn nguyên bản PAH:** [Hai phép đo / Bài A](../chuyen_de/PM01_HAI_PHEP_DO_VLN_BAN_THAO.md)

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

---

### PM01-M-3-05

**Tên:** Bài chuyển giao B: chất lỏng nhận nhiệt môi trường  
**Phân loại:** M / mức 3 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hóa hơi; nguồn nhiệt môi trường; hai giai đoạn  
**Nguồn nguyên bản PAH:** [Hai phép đo / Bài B](../chuyen_de/PM01_HAI_PHEP_DO_VLN_BAN_THAO.md)

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

---

**Nhánh Đ: Cải tiến / đánh giá độ tin cậy của phép đo**

### PM01-Đ-3-01

**Tên:** Cùng ΔT không bảo đảm cùng nhiệt thất thoát  
**Phân loại:** Đ / mức 3 · **Đáp án thử:** `S–Đ–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** thất thoát; chênh lệch nhiệt độ; điều kiện  
**Nguồn nguyên bản PAH:** [Đ3 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Hai lần đun cùng chất trong cùng nhiệt lượng kế có nhiệt dung $C$ không đổi. Mỗi lần nhiệt độ chất và bình đều tăng cùng một lượng $\Delta T$, nhưng **nhiệt độ ban đầu ở lần hai cao hơn lần một**. Hai lần kéo dài cùng thời gian; nhiệt độ phòng không đổi và thấp hơn nhiệt độ mẫu suốt thí nghiệm. Cho biết tại **mọi thời điểm tương ứng**, nhiệt độ mẫu trong lần hai cao hơn lần một. Mô hình thất thoát ra môi trường có công suất tăng theo chênh lệch nhiệt độ vật–phòng, cùng một quy luật trong hai lần.

a) Vì thời gian đun và $\Delta T$ đều bằng nhau nên nhiệt lượng mất ra môi trường cũng nhất thiết bằng nhau. **S**.

b) Nhiệt lượng bình hấp thụ trong hai lần bằng nhau nếu $C$ không đổi. **Đ**.

c) Có thể trừ hai phương trình năng lượng và tự động triệt tiêu đồng thời cả nhiệt bình hấp thụ lẫn toàn bộ nhiệt thất thoát môi trường mà không cần điều kiện bổ sung. **S**.

d) Với mô hình đã cho, nhiệt lượng mất ra môi trường trong lần hai lớn hơn lần một. **Đ**.

**Đáp án:** **S–Đ–S–Đ**.

**Giải thích:** $Q_{\rm bình}=C\Delta T$ bằng nhau, nhưng nếu $T_2(\tau)>T_1(\tau)$ trong cùng thời lượng thì $P_{{\rm mt},2}(\tau)>P_{{\rm mt},1}(\tau)$; tổng hao phí lần 2 lớn hơn. Chỉ **bình** được khử bởi cùng $\Delta T$.

**Hình cần vẽ bắt buộc:** hai đường $T_1(t),T_2(t)$ cùng độ tăng nhưng khác nhiệt độ ban đầu; đường 2 luôn cao hơn.

---

### PM01-Đ-3-02

**Tên:** Hai thời gian khác nhau: khử công suất hao thế nào?  
**Phân loại:** Đ / mức 3 · **Đáp án thử:** `Đ–Đ–S–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hóa hơi; chuẩn hóa thời gian; khử ẩn  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 4](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Một thiết bị đang đo nhiệt hóa hơi riêng của chất lỏng có nhiệt độ sôi **cao hơn nhiệt độ phòng**. Kỹ thuật viên thực hiện hai giai đoạn ở hai công suất và hai khoảng thời gian có thể khác nhau. Từ công suất, thời gian và sự giảm khối lượng, kỹ thuật viên xác định $P_i,t_i,m_i$ ($t_i>0$). Giả sử **công suất nhiệt mất ra môi trường là một hằng số dương như nhau trong hai giai đoạn** và nhiệt hóa hơi riêng không đổi.

a) Nhiệt lượng mất ra ngoài ở mỗi giai đoạn tỉ lệ với thời gian giai đoạn ấy.

b) Có thể chia phương trình năng lượng của từng giai đoạn cho thời gian rồi lấy hiệu để loại công suất mất nhiệt.

c) Nếu hai thời gian khác nhau, chỉ cần lấy hiệu hai điện năng $P_2t_2-P_1t_1$ là luôn bằng hiệu nhiệt lượng dùng hóa hơi $(m_2-m_1)L$.

d) Nếu hai phép đo có cùng tốc độ hóa hơi $m_1/t_1=m_2/t_2$, dữ liệu vẫn luôn xác định duy nhất được cả nhiệt hóa hơi riêng và công suất mất nhiệt.

**Giáo viên:** **Đ–Đ–S–S**. $P_it_i=m_iL+P_{\rm hao}t_i$; chia $t_i$ mới hiện $P_i=(m_i/t_i)L+P_{\rm hao}$. Nếu $m_1/t_1=m_2/t_2$, không tách được hai ẩn từ hai phương trình. Chốt: *phải chuẩn hóa theo đại lượng mà phần gây nhiễu phụ thuộc*.

---

### PM01-Đ-3-03

**Tên:** Hai bố trí: bố trí nào tách được c và C?  
**Phân loại:** Đ / mức 3 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** thiết kế; dữ liệu độc lập  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 5](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Hai nhóm cùng xác định nhiệt dung riêng của một chất lỏng bằng bộ nhiệt lượng kế như nhau. Nhiệt dung hiệu dụng của bình $C$ chưa biết. Nhóm A **giữ nguyên khối lượng chất lỏng**, thay đổi công suất và thời gian rồi đo độ tăng nhiệt độ. Nhóm B **đổi khối lượng chất lỏng** giữa hai lần đo và cũng ghi đủ điện năng cùng độ tăng nhiệt độ. Trong mọi phép đo, các độ tăng nhiệt độ đều dương; chất không chuyển thể; $c,C$ không đổi và không có thất thoát nhiệt ra môi trường.

a) Dữ liệu nhóm A có thể xác định tổ hợp $mc+C$.

b) Nếu hai lần đo của nhóm A có độ tăng nhiệt độ khác nhau, điều đó đủ để suy ra riêng $c$ và $C$.

c) Với hai khối lượng khác nhau, nhóm B có thể xác định riêng $c$ và $C$ trong mô hình đã nêu.

d) Thêm một lần đo thứ ba với đúng khối lượng ban đầu luôn giúp nhóm A xác định riêng $c$ và $C$.

**Giáo viên:** **Đ–S–Đ–S**. Nhóm A chỉ có $E_i/\Delta T_i=mc+C$; nhóm B có $E_i/\Delta T_i=m_ic+C$ với hai $m_i$ khác nhau. Chốt: *hai lần đo không đồng nghĩa hai thông tin độc lập*.

---

### PM01-Đ-3-04

**Tên:** Cùng thời gian nhưng nhiệt thất thoát có bằng nhau?  
**Phân loại:** Đ / mức 3 · **Đáp án thử:** `S–Đ–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** IOP; hao nhiệt; kiểm soát giả thiết  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 7](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)  
**Lưu ý:** Câu mới PAH dựa trên kĩ thuật nguồn nước ngoài; không phải câu AP/IOP nguyên văn.

Một nhóm học sinh đo nhiệt dung riêng của một chất lỏng bằng **cùng nhiệt lượng kế và dây đốt**. Nhóm thực hiện hai lần đun với cùng khối lượng chất lỏng, cùng nhiệt độ ban đầu, cùng thời gian cấp điện, nhưng công suất lần thứ hai lớn hơn. Nhiệt độ chất lỏng đều cao hơn nhiệt độ phòng; trong suốt mỗi lần đun, nhiệt độ ở lần thứ hai luôn cao hơn lần thứ nhất tại những thời điểm tương ứng (trừ thời điểm ban đầu).

Nhóm giả định nhiệt dung riêng của chất và nhiệt dung của bình không đổi, không có chuyển thể. Trong điều kiện bố trí này, **công suất truyền nhiệt ra môi trường tăng theo độ chênh lệch nhiệt độ giữa nhiệt lượng kế và phòng**, với quy luật truyền nhiệt như nhau cho hai lần đo.

a) Vì hai lần đun kéo dài cùng thời gian nên nhiệt lượng truyền ra môi trường ở hai lần chắc chắn bằng nhau.

b) Trong mô hình trao đổi nhiệt đã cho, tổng nhiệt lượng truyền ra môi trường trong lần thứ hai lớn hơn lần thứ nhất.

c) Phương trình năng lượng của từng lần đo phải kể đến cả nhiệt lượng làm nóng chất lỏng, làm nóng bình và truyền ra môi trường.

d) Nếu đo và hiệu chỉnh chính xác được nhiệt lượng hao phí của cả hai lần, việc giữ nguyên khối lượng chất lỏng vẫn đủ để xác định riêng cả $c$ và $C$ chỉ bằng hai phép đo nhiệt độ.

**Đáp án PAH:** **S–Đ–Đ–S**.

**Giải thích dành cho giáo viên:** đặt $E_i=P_it_i$, $Q_{{\rm hao},i}>0$:
\[
E_i=(mc+C)\Delta T_i+Q_{{\rm hao},i}.
\]
Theo mô hình tốc độ hao phí tăng theo $T-T_{\rm phòng}$, thời gian bằng nhau nhưng nhiệt độ lần 2 **cao hơn tại mỗi thời điểm** nên $Q_{{\rm hao},2}>Q_{{\rm hao},1}$. Nếu loại được $Q_{{\rm hao},i}$, cả hai phép đo vẫn chỉ cho cùng tổ hợp $mc+C$ vì $m$ không đổi; không thể tách riêng $c,C$.

**Trục PAH mới:** *Đại lượng phụ là hệ quả của lịch sử nhiệt độ, không phải chỉ của thời gian.* Không bắt học sinh tính tích phân truyền nhiệt: yêu cầu hiểu chiều biến thiên và điều kiện so sánh.

---

## MỨC 4 — Đánh giá chứng cứ và phản biện kết luận

**Nhánh K: Khảo sát mối quan hệ / kiểm định giả thuyết**

### PM01-K-4-01

**Tên:** Sự phụ thuộc giả tạo của c đo theo m  
**Phân loại:** K / mức 4 · **Đáp án thử:** `S–Đ–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** sai lệch hệ thống; nhiệt dung bình  
**Nguồn nguyên bản PAH:** [K4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một nhóm cho rằng “nhiệt dung riêng của một chất lỏng giảm khi khối lượng mẫu tăng”. Nhóm dùng **cùng một bình có nhiệt dung $C>0$**, làm nóng các mẫu khác khối lượng và đo điện năng $E$ cùng độ tăng nhiệt $\Delta T$. Toàn bộ điện năng chỉ dùng để làm nóng mẫu và bình; không chuyển thể, không mất nhiệt ra môi trường. Trong phạm vi khảo sát, $c$ thực của chất và $C$ đều không đổi. Tuy nhiên, nhóm tính $c_{\rm đo}=E/(m\Delta T)$, **bỏ qua nhiệt lượng bình hấp thụ**, rồi nhận thấy $c_{\rm đo}$ giảm theo $m$.

a) Xu hướng số đo trên là bằng chứng đủ để khẳng định $c$ thực của chất giảm khi khối lượng tăng. **S**.

b) Giá trị $c_{\rm đo}$ theo cách xử lý của nhóm bằng $c+C/m$. **Đ**.

c) Sự phù hợp của dữ liệu với một giả thuyết luôn loại trừ khả năng cách xử lý số liệu có sai lệch hệ thống. **S**.

d) Khi tăng khối lượng mẫu, $c_{\rm đo}$ có thể giảm dù $c$ thực vẫn không đổi. **Đ**.

**Đáp án:** **S–Đ–S–Đ**.

**Giải thích:** $E=(mc+C)\Delta T$ nên $c_{\rm đo}=c+C/m$. Đây là **phụ thuộc biểu kiến**, không phải chứng cứ của phụ thuộc vật lý thực.

**Hình cần vẽ:** nhiệt lượng kế có mẫu $m$, bình nhận $C\Delta T$, mẫu nhận $mc\Delta T$, 2 mũi tên năng lượng riêng biệt.

---

---

### PM01-K-4-02

**Tên:** Nhiệt dung riêng biểu kiến phụ thuộc khối lượng  
**Phân loại:** K / mức 4 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** khối lượng; nhiệt dung bình; sai lệch hệ thống  
**Nguồn nguyên bản PAH:** [Nhánh K / K01](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md)

Một nhóm muốn kiểm tra giả thuyết “nhiệt dung riêng của cùng một chất lỏng giảm khi khối lượng mẫu tăng”. Họ làm nóng các mẫu trong **cùng một nhiệt lượng kế có nhiệt dung $C>0$**, từ cùng nhiệt độ ban đầu qua cùng độ tăng nhiệt $\Delta T>0$, đo điện năng nguồn cấp cho mỗi lần. Coi điện năng truyền hoàn toàn cho **chất lỏng và bình**, không truyền ra môi trường; chất không chuyển thể; $C$ và nhiệt dung riêng thực $c$ của chất **không đổi**. Nhóm lại tính “nhiệt dung riêng” bằng cách lấy điện năng cấp chia cho $m\Delta T$, coi như nhiệt lượng kế không hấp thụ năng lượng.

a) Nếu tăng khối lượng mẫu thì điện năng cần cung cấp để đạt cùng $\Delta T$ cũng tăng. **Đúng**.

b) Trong các điều kiện đã cho, điện năng cấp tỉ lệ thuận với khối lượng mẫu. **Sai** ($E=(mc+C)\Delta T$ có số hạng tự do $C\Delta T>0$).

c) Giá trị “nhiệt dung riêng” nhóm tính ra có thể giảm khi khối lượng mẫu tăng, dù nhiệt dung riêng thực của chất không đổi. **Đúng** ($\hat c=c+C/m$).

d) Xu hướng $\hat c$ giảm khi tăng $m$ đủ để khẳng định nhiệt dung riêng thực của chất giảm theo khối lượng. **Sai**.

**Giáo viên:** Đ–S–Đ–S. Mức 3–4 của nhánh K; câu c,d chủ yếu kiểm tra khác nhau giữa giá trị quan sát *suy ra từ phép tính* và đặc trưng vật lý.

---

### PM01-K-4-03

**Tên:** Khảo sát nhiệt dung riêng theo nhiệt độ  
**Phân loại:** K / mức 4 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** sự phụ thuộc; biến khảo sát; ngoại suy  
**Nguồn nguyên bản PAH:** [Nhánh K / K02](../chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md)  
**Lưu ý:** MASTER xếp mức 4 theo ý kết luận vượt miền quan sát; cần giáo viên duyệt.

Một nhóm đưa ra giả thuyết: “Trong khoảng nhiệt độ đang khảo sát, nhiệt dung riêng của một chất lỏng giảm khi nhiệt độ tăng”. Họ dùng cùng khối lượng chất lỏng, đun nóng lần lượt qua một số khoảng nhiệt độ bằng nhau. Ở mỗi khoảng, nhóm đo điện năng cấp và đã xác định để loại phần năng lượng làm nóng dụng cụ cũng như phần truyền ra môi trường. Họ nhận thấy **nhiệt lượng truyền cho riêng chất lỏng ở những khoảng nhiệt độ cao hơn nhỏ hơn** so với các khoảng trước. Coi không chuyển thể và các phép đo đủ chính xác để phân biệt sự chênh lệch.

a) Để kiểm tra giả thuyết về $c$ phụ thuộc nhiệt độ, cần so sánh phép đo ở những khoảng nhiệt độ khác nhau. **Đúng**.

b) Từ $c=Q/(m\Delta T)$ có thể kết luận ngay rằng $c$ luôn tỉ lệ nghịch với độ tăng nhiệt độ trong mọi thí nghiệm. **Sai**.

c) Với cùng khối lượng và cùng độ rộng khoảng nhiệt độ, nhiệt lượng riêng mẫu nhận nhỏ hơn có nghĩa **nhiệt dung riêng trung bình** trên khoảng đó nhỏ hơn. **Đúng**.

d) Quan sát các giá trị trung bình giảm ở những khoảng đã thử chứng minh $c$ giảm tại **mọi nhiệt độ** và mọi trạng thái khác của chất. **Sai**.

**Giáo viên:** Đ–S–Đ–S. Bài mới phát triển từ giả thuyết của giáo viên, **không phải câu Bộ 2026**.

---

### PM01-K-4-04

**Tên:** Nhiệt độ tăng không đều dù công suất điện không đổi  
**Phân loại:** K / mức 4 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** đồ thị T–t; giả thuyết; truyền nhiệt  
**Nguồn nguyên bản PAH:** [Video 06 / câu K](../nguon/VIDEO06_K_M_D_DOI_CHIEU_V1.md)  
**Lưu ý:** MASTER xếp mức 4 theo thao tác phản biện; cần giáo viên duyệt.

**Mục tiêu câu:** xem giả thuyết $T$ tăng đều theo thời gian có được kết quả kiểm chứng hay không; **không bắt học sinh tìm $c$ hay thiết kế phương pháp hiệu chỉnh**.

Một nhóm nghiên cứu muốn kiểm tra giả thuyết: “Với một mẫu chất lỏng không chuyển thể, nếu dây đốt cung cấp công suất điện không đổi thì nhiệt độ chất lỏng tăng đều theo thời gian”. Họ đặt mẫu chất lỏng vào nhiệt lượng kế có dây đốt, giữ khối lượng và công suất không đổi, dùng nhiệt kế ghi nhiệt độ sau những khoảng thời gian bằng nhau. Kết quả cho thấy độ tăng nhiệt độ ở các khoảng thời gian sau nhỏ hơn ở các khoảng trước. Nhiệt độ phòng không đổi và thấp hơn nhiệt độ mẫu trong thời gian khảo sát.

**Các nhận định Đúng/Sai:**

a) So sánh độ tăng nhiệt độ ở những khoảng thời gian bằng nhau là một cách kiểm tra giả thuyết nhiệt độ tăng đều theo thời gian. **Đúng**.

b) Vì công suất điện không đổi nên riêng mẫu chất lỏng nhất thiết nhận cùng một nhiệt lượng trong mọi khoảng thời gian bằng nhau. **Sai**; dụng cụ và môi trường có thể nhận nhiệt.

c) Nếu công suất truyền nhiệt hữu ích cho mẫu và bình là không đổi, nhiệt dung riêng của mẫu và nhiệt dung bình không đổi, không mất nhiệt ra môi trường, mô hình dự đoán nhiệt độ tăng đều theo thời gian. **Đúng**.

d) Kết quả độ tăng nhiệt độ mỗi khoảng giảm dần đã đủ để chứng minh nhiệt dung riêng của chất tăng khi nhiệt độ tăng. **Sai**; chưa loại được các giải thích khác, chẳng hạn truyền nhiệt ra ngoài tăng.

**Đáp án:** **Đ – S – Đ – S**, dựa trên điều kiện câu nêu. Câu chỉ hỏi **giả thuyết–dữ liệu–giới hạn kết luận** (K). Không có bước bắt buộc “hãy đo $c$ chính xác hơn”.

**Chú ý khi sửa đề:** “Công suất điện không đổi” khác “công suất hữu ích truyền cho mẫu không đổi”; phải phân biệt hai phát biểu, tránh gây tranh luận đáp án do bỏ sót điều kiện. Đây là bài mới PAH, **chưa qua duyệt**.

---

### PM01-K-4-05

**Tên:** Nồng độ muối và nhiệt độ sôi: giới hạn suy luận  
**Phân loại:** K / mức 4 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** nồng độ; nhiệt độ sôi; ngoại suy  
**Nguồn nguyên bản PAH:** [Video 05 / câu PAH](../chuyen_de/PHAN_TICH_VIDEO_05_BAN_THAO.md)  
**Lưu ý:** Có số liệu; cần đối chiếu phạm vi YCCD trước khi sử dụng.

**Tình huống:** Một nhóm khảo sát ảnh hưởng của nồng độ muối đến nhiệt độ sôi. Ban đầu nhóm dùng 200 g nước trong cùng một nồi, sau đó lần lượt thêm muối và ghi nhiệt độ sôi sau mỗi lần. Tổng muối lần lượt là 0, 10, 20, 30, 40, 50 g; nhiệt độ đo tương ứng là 100,0; 101,0; 102,0; 103,0; 104,5; 106,5 °C. Nhóm tính nồng độ dựa trên khối lượng nước ban đầu là 200 g, nhưng chưa cân lại nước sau mỗi lần đun. Coi muối không bay hơi theo hơi nước.

Xét các nhận định:

**a)** Nếu bỏ qua nước bay hơi, nồng độ ở lần có tổng 30 g muối xấp xỉ 13,0%.  
**b)** Nếu nước đã bay hơi trong quá trình đun thì nồng độ thực tế của dung dịch luôn nhỏ hơn nồng độ được nhóm tính từ 200 g nước ban đầu.  
**c)** Theo số liệu danh nghĩa, mức tăng nhiệt độ sôi trung bình trong khoảng nồng độ từ 0% đến 20% là 0,325 °C trên mỗi **điểm phần trăm nồng độ**.  
**d)** Sáu lần đo đủ để khẳng định với mọi nồng độ và mọi áp suất, cứ tăng thêm một điểm phần trăm nồng độ thì nhiệt độ sôi tăng đúng 0,325 °C.

**Đáp án thử nghiệm:** a Đúng; b Sai; c Đúng; d Sai.

**Lý do:** a \(30/(200+30)\simeq13,0\%\). b nước bay hơi làm mẫu số giảm, nồng độ tăng (nếu không thất thoát muối). c \(6,5/20=0,325\). d sai vì vượt phạm vi quan sát và nhầm trung bình với gia tăng đều. Câu đã được kiểm tra số học/mô hình cơ bản, **chưa qua thử nghiệm học sinh**.

---

**Nhánh M: Đo đại lượng vật lí**

### PM01-M-4-01

**Tên:** Hai tốc độ hóa hơi: điều kiện xác định L,H  
**Phân loại:** M / mức 4 · **Đáp án thử:** `Đ–S–Đ–S` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** hóa hơi; tốc độ; hao nhiệt; suy biến  
**Nguồn nguyên bản PAH:** [M4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Một chất lỏng đang sôi ở nhiệt độ lớn hơn nhiệt độ phòng. Trong hai giai đoạn đo, nhà nghiên cứu ghi lại công suất điện $P_i$, khối lượng hóa hơi $m_i$ và thời gian $t_i$ ($i=1,2$). Giả sử nhiệt hóa hơi riêng $L>0$ không đổi và **công suất nhiệt truyền ra môi trường $H$ không đổi giữa các giai đoạn**, toàn bộ phần công suất còn lại dùng để hóa hơi; dữ liệu đủ tin cậy. Đặt $r_i=m_i/t_i$ là tốc độ hóa hơi.

a) Mô hình từng giai đoạn có dạng $P_i=Lr_i+H$. **Đ**.

b) Nếu $r_1=r_2$ mà $P_1\ne P_2$, dữ liệu vẫn phù hợp đầy đủ với cùng một bộ giá trị $L,H$. **S**.

c) Nếu $r_1\ne r_2$, hai phương trình cho phép xác định duy nhất $L$ và $H$ về mặt đại số; sau đó cần kiểm tra các giá trị có ý nghĩa vật lý. **Đ**.

d) Nếu $r_1=r_2$ và $P_1=P_2$, số phép đo tăng lên bằng cách lặp lại đúng cấu hình ấy sẽ tự động tách được riêng $L$ và $H$. **S**.

**Đáp án:** **Đ–S–Đ–S**.

**Giải thích:** đây là hệ hai ẩn; hai hàng độc lập khi $r_1\ne r_2$. Trường hợp $r_1=r_2$, $P_1\ne P_2$ là mâu thuẫn với cả *bộ* giả thiết; $r_1=r_2$, $P_1=P_2$ thì chưa xác định riêng hai ẩn.

**Hình cần vẽ:** hai lượt hóa hơi có ghi $r_1,r_2,P_1,P_2$, mũi tên $H$ truyền ra môi trường; không cần số.

---

---

### PM01-M-4-02

**Tên:** Bình cứng: không đổi khác với đã biết  
**Phân loại:** M / mức 4 · **Đáp án thử:** `Đ–S–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** AP; khí lí tưởng; tính xác định  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 8](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)  
**Lưu ý:** Câu chuyển giao thuộc khí lí tưởng, không tự động đưa vào chuyên đề nhiệt.

Một phòng thí nghiệm khảo sát khí lí tưởng trong **bình kín có thành cứng**. Bình có bộ sưởi và hai cảm biến đo áp suất tuyệt đối $p$ và nhiệt độ tuyệt đối $T$. Khí không rò rỉ, số phân tử $N$ không đổi, nhưng **thể tích khí bên trong bình chưa được xác định**. Một nhóm thay đổi nhiệt độ, thu được nhiều cặp số đo $p,T$ và nhận thấy tỉ số $p/T$ gần như không đổi trong giới hạn sai số thiết bị.

Một học sinh kết luận: “Không cần xác định thể tích; càng đo nhiều cặp $p,T$ càng có thể tính chính xác số phân tử $N$, đồng thời chứng minh khí sẽ tuân theo định luật khí lí tưởng trong mọi điều kiện.”

a) Thành bình cứng khiến thể tích phần khí chứa trong bình không đổi trong quá trình đo (theo giả thiết).

b) Chỉ bằng nhiều số đo $p,T$, không có thông tin nào về giá trị thể tích $V$, vẫn xác định duy nhất được số phân tử $N$.

c) Việc $p/T$ gần như không đổi trong những điều kiện đã thử đủ để chứng minh khí lí tưởng đúng trong mọi trạng thái và điều kiện khác.

d) Nếu xác định thêm thể tích thực sự dành cho khí, có thể kết hợp $p,T,V$ với mô hình khí lí tưởng để tính $N$.

**Đáp án PAH:** **Đ–S–S–Đ**.

**Giải thích dành cho giáo viên:** từ $pV=Nk_{\rm B}T$ suy ra $p/T=Nk_{\rm B}/V$. Các phép đo trong cùng bình với $V$ chưa biết chỉ xác định $N/V$, không thể tự tách $N$ và $V$. Việc tỉ số đo gần như không đổi **phù hợp** với mô hình trong khoảng khảo sát nhưng không chứng minh mô hình đúng mọi điều kiện. Cần xác định thêm thể tích hiệu dụng của phần chứa khí (không được coi “bình cứng” là “biết thể tích”). 

**Trục PAH mới:** *Điều kiện cố định không thay thế dữ liệu còn thiếu; quan sát phù hợp mô hình không đồng nghĩa chứng minh phổ quát.*

---

**Nhánh Đ: Cải tiến / đánh giá độ tin cậy của phép đo**

### PM01-Đ-4-01

**Tên:** Thí nghiệm thứ ba kiểm định phương án đo  
**Phân loại:** Đ / mức 4 · **Đáp án thử:** `Đ–S–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** kiểm chứng; dữ liệu mâu thuẫn; sai số  
**Nguồn nguyên bản PAH:** [Đ4 (Pilot)](../cau_hoi/PM01_PILOT_12_CAU_KMD_V1.md)

**Tình huống.** Nhóm đo nhiệt hóa hơi riêng $L$ của chất lỏng đang sôi ở nhiệt độ cao hơn nhiệt độ phòng bằng **ba giai đoạn**. Trong từng giai đoạn, đo công suất cấp điện $P_i$ và tốc độ hóa hơi $r_i=m_i/t_i$. Nhóm giả định $L$ và công suất hao nhiệt môi trường $H$ **cùng không đổi** qua các giai đoạn, nên dự đoán $P_i=Lr_i+H$. Hai giai đoạn đầu có $r_1\ne r_2$ và cho một cặp $L,H$ phù hợp về mặt vật lý. Tuy nhiên, ở giai đoạn ba, cặp $(r_3,P_3)$ **không thỏa mãn** quan hệ dự đoán từ hai giai đoạn đầu, với mức lệch lớn hơn sai số đo đã đánh giá.

a) Hai giai đoạn đầu với tốc độ hóa hơi khác nhau cho phép xác định riêng $L$ và $H$ trong mô hình đã giả định. **Đ**.

b) Vì kết quả thứ ba không phù hợp, chắc chắn định luật bảo toàn năng lượng bị vi phạm. **S**.

c) Chỉ từ quan sát thứ ba có thể kết luận duy nhất rằng $L$ của chất đã thay đổi, còn giả thiết $H$ không đổi và tất cả phép đo khác đều chính xác. **S**.

d) Quan sát ở giai đoạn ba cho thấy không thể dùng cùng một bộ giá trị $L,H$ để giải thích cả ba kết quả với mô hình đã nêu trong giới hạn sai số đã đánh giá. **Đ**.

**Đáp án:** **Đ–S–S–Đ**.

**Giải thích:** Hai điểm với $r_1\ne r_2$ xác định một đường thẳng $P=Lr+H$. Điểm thứ ba lệch đường thẳng vượt sai số là bằng chứng chống lại **tập hợp mô hình và giả thiết**; không nhận diện duy nhất giả thiết nào sai. Có thể kiểm tra hao phí, mô hình công suất hữu ích, phép cân, điều kiện sôi, v.v.

**Hình cần vẽ bắt buộc:** đồ thị $P$ theo $r$, hai điểm đầu nằm trên đường mô hình, điểm thứ ba nằm lệch rõ, không đặt số liệu.

---

---

### PM01-Đ-4-02

**Tên:** Dữ liệu trái dự đoán: phản biện mô hình  
**Phân loại:** Đ / mức 4 · **Đáp án thử:** `Đ–S–S–Đ` · **Trạng thái:** CHỜ DUYỆT  
**Từ khóa:** kiểm chứng; dữ liệu mâu thuẫn; bảo toàn năng lượng  
**Nguồn nguyên bản PAH:** [Tiến trình / Câu 6](../chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)

Trong một nghiên cứu xác định nhiệt hóa hơi riêng, một chất lỏng được giữ ở nhiệt độ sôi lớn hơn nhiệt độ phòng. Nhà nghiên cứu giả định **nhiệt hóa hơi riêng không đổi và công suất thất thoát nhiệt ra môi trường là như nhau ở mọi giai đoạn**. Sau khi tiến hành hai giai đoạn với **công suất cấp điện ở giai đoạn 2 lớn hơn giai đoạn 1**, người nghiên cứu ghi nhận **khối lượng hóa hơi trên mỗi đơn vị thời gian lại bằng nhau** giữa hai giai đoạn.

Một thành viên kết luận rằng phép đo đã xác nhận mô hình ban đầu. Các thành viên khác đề xuất kiểm tra lại quy trình và giả thiết.

a) Theo mô hình đã giả định, công suất cấp lớn hơn phải tương ứng với tốc độ hóa hơi lớn hơn.

b) Kết quả vừa ghi nhận là bằng chứng đủ để xác nhận công suất thất thoát nhiệt không đổi giữa hai giai đoạn.

c) Kết quả trái dự đoán chứng minh rằng định luật bảo toàn năng lượng không còn đúng trong thí nghiệm.

d) Trước khi chấp nhận kết luận, cần xem lại dữ liệu đo và các giả thiết, chẳng hạn việc công suất thất thoát có thực sự không đổi hay không.

**Giáo viên:** **Đ–S–S–Đ**. Từ $P_i=L(m_i/t_i)+P_{\rm hao}$ và $L>0$; cùng tốc độ hóa hơi buộc $P_2=P_1$ trong mô hình. Nhưng đề ghi $P_2>P_1$: **dữ liệu và hệ giả thiết không đồng thời đúng**. Không được vội bác bỏ định luật bảo toàn năng lượng; phải kiểm tra phép đo, hiệu suất điện trở, tổn thất, thời điểm trạng thái sôi ổn định… Chốt: *kết luận khoa học phải tương thích với dữ liệu và các điều kiện; kết quả trái dự đoán là tín hiệu kiểm tra giả thiết*.

---

## III. TRÁNH ĐẾM TRÙNG VÀ ĐỐI CHIẾU NGUỒN

**Bản TeX đồng nội dung:**
- `cau_hoi/PM01_06_CAU_DUNG_SAI_KHONG_SO_BODY.tex` = Tiến trình câu 1–6.
- `cau_hoi/PM01_02_CAU_CHUYEN_GIAO_AP_IOP_BODY.tex` = Tiến trình câu 7–8.
- `cau_hoi/PM01_BAI_TAP_EX_TEST_BODY.tex` = Hai phép đo bài A và bài B.

**Không nhập nguyên văn vào ngân hàng PAH:** 4 câu PDF trong [đối chiếu bốn đề](../nguon/PM01_DOI_CHIEU_4_CAU_NGUON_V1.md) là **nguồn tham khảo có tác giả khác**; [các tài liệu quốc tế](../nguon/PM01_QUOC_TE_4_MUC_V1.md) là **nguồn phương pháp**, không phải 8 câu quốc tế để sao chép. Chỉ tính những câu **PAH tự biên soạn và có bốn ý Đ/S thực sự**.

**22 câu được nhắc tại [checkpoint cũ](../04_CP_VLN_PILOT_01.md)** (10 MCQ, 7 Đ/S, 5 trả lời ngắn) **chưa có đầy đủ toàn văn trong cây file của repo ở thời điểm tổng hợp** nên **không cộng 22 vào con số 28**, tránh đếm nhầm hoặc bịa lại câu. Khi tìm được file nguồn thì nhập riêng theo định dạng MCQ / TF / Short.

**Mô hình trùng không có nghĩa câu trùng:** ví dụ sự phụ thuộc biểu kiến của $c_{\rm đo}$ theo $m$ xuất hiện ở hai hoàn cảnh PAH khác nhau; câu không số và biến thể số cũng có thể cùng phương trình nền. Lúc soạn một đề cương, lọc bớt các câu khai thác cùng một bẫy.

## IV. LỆNH TRUY XUẤT NHANH VÀO ĐỀ CƯƠNG

> Đọc `cau_hoi/PM01_MASTER_NGAN_HANG_CAU_HOI.md`. Chọn **[số câu]** thuộc nhánh **[K/M/Đ]**, mức **[1–4]**, chủ đề **[ví dụ: nóng chảy, hóa hơi, nhiệt dung riêng, khí lí tưởng]**, dạng **[có số/không số]**. Xuất danh mục ID + đường dẫn nguồn + đáp án thử để tôi duyệt. Đọc lại file gốc, đối chiếu `02_QUY_TAC_KIEM_DINH_THI_NGHIEM.md` và YCCD trước khi đưa vào `ex_test`. Tránh chọn nhiều câu hỏi cùng một bẫy.

**Khi thêm câu:** (1) lưu đủ đề + 4 ý + lời giải trong file nguồn; (2) xác định nhánh và mức cao nhất; (3) cấp ID mới chỉ tăng hậu tố; (4) thêm vào ma trận, danh mục và nội dung MASTER; (5) chỉ đổi trạng thái sau khi giáo viên thực sự duyệt. **Git lưu tri thức và lịch sử; không sao chép PDF nước ngoài có bản quyền.**
