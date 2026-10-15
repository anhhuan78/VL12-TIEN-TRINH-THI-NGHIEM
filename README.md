# VL12 — TIẾN TRÌNH THÍ NGHIỆM

> **Từ vấn đề thực tế → mô hình vật lí → điều kiện áp dụng → kiểm chứng → kết luận.**

Kho này lưu **nguyên tắc biên soạn, kiểm định và dạy học các câu hỏi về tư duy thực nghiệm Vật lí 12**. Mục tiêu không phải sưu tầm thật nhiều câu theo mẫu, mà là giúp học sinh xử lí được **một tình huống chưa từng gặp** bằng kiến thức và lập luận có căn cứ.

## Phạm vi

- Vật lí nhiệt
- Khí lí tưởng
- Từ trường
- Vật lí hạt nhân

Yêu cầu cần đạt (YCCD) của chương trình là **giới hạn bắt buộc** đối với kiến thức và năng lực yêu cầu học sinh sử dụng. Bối cảnh có thể mới; điều kiện để giải không được âm thầm vượt khỏi chương trình.

## Bắt đầu từ đâu?

1. [01 — Nguyên tắc mô hình hóa và dạy học](01_NGUYEN_TAC_MO_HINH_HOA.md): triết lí sư phạm, vai trò toán học, cách đi từ vấn đề đến mô hình.
2. [02 — Quy tắc biên soạn và kiểm định câu thực nghiệm](02_QUY_TAC_KIEM_DINH_THI_NGHIEM.md): kiểm soát giả thiết, nguồn, dữ kiện, phản ví dụ, đáp án và tạo biến thể.
3. [03 — Chiến lược chuyên đề luyện thi](03_CHIEN_LUOC_CHUYEN_DE_LUYEN_THI.md): kho câu phong phú song song với hệ phương pháp; dạy phương pháp qua chuỗi bài luyện, không tách thành bài lí thuyết dài.

Bắt đầu bằng ba tài liệu ngắn xác định triết lí, luật kiểm định và cách triển khai chuyên đề. **Chưa tạo thêm hệ mã câu, bảng chỉ mục hay cấu trúc dữ liệu tự động** cho tới khi đã có sản phẩm thực tế cần chúng.

## Một vòng làm việc chuẩn

**Nguồn có thể kiểm chứng → Đối chiếu YCCD → Xác định hệ và mô hình → Kiểm tra điều kiện → Tạo câu/bài học → Tìm phản ví dụ → Giáo viên duyệt.**

Một thí nghiệm đã kiểm định có thể tạo ra **hai sản phẩm**: (1) bài dạy giúp học sinh tự xây dựng, kiểm chứng mô hình; (2) họ câu hỏi luyện thi khai thác các thao tác tư duy khác nhau. Không chỉ thay số để nhân số lượng câu.

## Vai trò và trách nhiệm

- **Giáo viên:** sở hữu nội dung và phê duyệt cuối cùng; phân biệt rõ điều đã chốt và ý tưởng đang thử.
- **NotebookLM:** đọc, tìm vị trí và trích xuất nguồn; không mặc định kết quả trích xuất là đúng.
- **ChatGPT/AI:** đề xuất mô hình, câu hỏi, lời giải, thử phản ví dụ, phát hiện điều kiện thiếu và hỗ trợ LaTeX; không tự chứng nhận câu đạt.
- **GitHub:** lưu quyết định đã duyệt và lịch sử thay đổi; không sao chép nguyên mọi cuộc thảo luận.

## Quy tắc nguồn

YCCD và văn bản chính thức quyết định phạm vi; đề thi chính thức cung cấp bằng chứng về cách đánh giá; đề sưu tầm, khóa học và đề quốc tế cung cấp tình huống để nghiên cứu. **Một đáp án có sẵn không thay thế cho kiểm định vật lí.** Luôn lưu nguồn gốc, năm/đợt, trang và câu (nếu có). Không đưa toàn bộ tài liệu có bản quyền lên repo nếu không có quyền phân phối; ưu tiên dẫn tới bản gốc.

## Trạng thái khởi tạo — 12/10/2026

- Đã hình thành bộ nguyên tắc nền tảng từ thảo luận chuyên môn.
- **Chưa** tuyên bố đã có ngân hàng câu được thẩm định, phân tích dự báo đề thi đáng tin cậy, hoặc giáo án thử nghiệm với học sinh.
- **Hướng triển khai đã chốt ngày 14/10/2026:** mở rộng nguồn câu hỏi đa dạng theo hai trục YCCD và thao tác tư duy; tổ chức chuỗi luyện **giải mẫu → có hướng dẫn → độc lập → tình huống mới**; phương pháp được rút ra sau từng nhóm bài.
- **Checkpoint hiện tại:** dùng NotebookLM để kiểm kê câu thực nghiệm từ 2–3 đề sưu tầm mỗi lượt; chỉ sau khi đối chiếu nguồn và kiểm định vật lí mới dùng câu để chấm điểm.


## Tài liệu làm việc hiện có — từ nguồn thật đến sản phẩm PAH

**Nguồn PDF gốc** (không chỉnh sửa, không sao chép lên Git): [thư mục DE MINH HOA trên Google Drive](https://drive.google.com/drive/folders/1lGy7VHKZiwJi3hZaWB9Vqn-nkQvH9BlN). NotebookLM dùng những PDF này cùng video bài giảng để tìm hiểu cách ra đề; kết quả NotebookLM chỉ là gợi ý, phải đối chiếu nguồn.

**Tài liệu PAH trên Git (đang CHỜ DUYỆT):**

- [Phân tích phương pháp từ video 05](chuyen_de/PHAN_TICH_VIDEO_05_BAN_THAO.md)
- [Chuyên đề PM01 — Hai phép đo, loại trừ đại lượng phụ](chuyen_de/PM01_HAI_PHEP_DO_VLN_BAN_THAO.md)
- [PM01 — Nguồn nước ngoài đối chiếu 4 mức tư duy](nguon/PM01_QUOC_TE_4_MUC_V1.md)
- [PM01 — Đối chiếu bốn câu nguồn và trục tư duy hai ẩn](nguon/PM01_DOI_CHIEU_4_CAU_NGUON_V1.md)
- [Video 06 — Audit và phân biệt K (khảo sát), M (đo), Đ (cải tiến)](nguon/VIDEO06_K_M_D_DOI_CHIEU_V1.md)
- [PM01 — Nhánh khảo sát sự phụ thuộc (bổ sung từ đề chính thức 2026)](chuyen_de/PM01_NHANH_KHAO_SAT_SU_PHU_THUOC_V1.md)
- [PM01 — Tiến trình 4 mức, 6 câu Đúng/Sai không có số liệu](chuyen_de/PM01_TIEN_TRINH_TU_DUY_KHONG_SO_V1.md)
- [PM01 — LaTeX BODY 6 câu tình huống thực nghiệm](cau_hoi/PM01_06_CAU_DUNG_SAI_KHONG_SO_BODY.tex)
- [PM01 — Khung tạo sinh và câu thử đã kiểm tra đại số](cau_hoi/PM01_KHUNG_TAO_SINH_V1.md)
- [Hai bài tập PM01 — LaTeX BODY \`ex_test\`](cau_hoi/PM01_BAI_TAP_EX_TEST_BODY.tex)

**Khi muốn sinh đề mới:** chọn phương pháp hoặc nhóm câu nguồn cần khai thác; yêu cầu AI đọc **(1) đề gốc Drive, (2) hồ sơ phương pháp trên Git, (3) quy tắc kiểm định ở mục 02**, sau đó:
1. Trích vị trí và cơ chế câu gốc, phân biệt **câu gốc** và **câu phỏng theo**.
2. Tạo biến thể thay đổi ngữ cảnh, giả thuyết, điều kiện hoặc dữ kiện **nhưng không tự thay đổi mô hình đã kiểm định**.
3. Tự giải theo phương trình gốc, kiểm tra đơn vị, nghiệm, trường hợp suy biến và từng nhận định Đúng/Sai.
4. Xuất bản học sinh, đáp án giáo viên, LaTeX; đánh dấu **CHỜ DUYỆT**.
5. Sau khi giáo viên duyệt, commit câu hỏi và phiên bản chuyên đề vào Git. Không tự gắn nhãn đã duyệt.

**Nguyên tắc lưu trữ:** Drive = nguồn PDF/video gốc; Git = tri thức phân tích, khung câu, Markdown, TeX, mã nguồn và lịch sử chỉnh sửa; PDF in ấn được biên dịch từ nguồn phiên bản tương ứng. Không bắt đầu lại từ prompt trắng và không mặc định rằng chỉ có 2 câu đã tạo đã được duyệt.
