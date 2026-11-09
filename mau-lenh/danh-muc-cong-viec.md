# Rà soát danh mục công việc và sản phẩm

**Dùng khi:** xây dựng hoặc đối chiếu danh mục sản phẩm, vị trí việc làm và thời gian thực hiện.

```text
Rà soát [tên danh mục, phiên bản] của [đơn vị] so với [chức năng nhiệm vụ, báo cáo, danh mục tham chiếu và minh chứng được phép]. Kỳ xem xét: [thời gian].

1. Lập bảng từng dòng: mã/dòng nguồn | nhiệm vụ | sản phẩm | căn cứ hoặc minh chứng | đơn vị/cá nhân | tần suất | thời gian hiện có.
2. Phát hiện dòng trùng, công việc thiếu hoặc chưa thuộc phạm vi, tên sản phẩm chưa rõ và các chỗ thiếu minh chứng. Không xem văn bản đi là bằng chứng duy nhất của toàn bộ công việc.
3. Đánh giá độ khó theo tiêu chí nêu rõ: phạm vi, độ phức tạp, số bên phối hợp, dữ liệu và yêu cầu thẩm định. Ghi nhận đây là đánh giá đề xuất, không tự gán thang điểm chính thức.
4. Với thời gian xử lý đề xuất, nêu giả định về hồ sơ đầy đủ, khối lượng và bước xử lý; phân biệt thời gian làm việc thực tế với thời gian chờ phối hợp/phê duyệt. Nếu luật hoặc quy chế quy định hạn, đối chiếu riêng và không đề xuất trái hạn.
5. Đề xuất khoảng thời gian theo độ khó, giải thích cách ước tính và yêu cầu kiểm chứng bằng dữ liệu thực tế; nếu không có cơ sở thì ghi [cần khảo sát], không tự khẳng định định mức.
6. Lập bảng thay đổi: dòng gốc, đề xuất, lý do, nguồn, tác động và phương án; giữ nguyên dữ liệu chưa cần sửa. Khi tách danh mục công tác Đảng và chính quyền, trình bày tiêu chí phân loại, dòng giao thoa và đối chiếu số dòng trước/sau để tránh bỏ sót.
7. Nếu công cụ có thể tạo tệp, bảo toàn cấu trúc, công thức, kiểu dữ liệu và định dạng theo yêu cầu; tô vàng thay đổi và thêm bảng giải trình. Kiểm tra số dòng, công thức, ô gộp và nội dung sau khi xuất; không tuyên bố đã kiểm tra nếu chưa thực hiện.

Dữ liệu: [liệt kê]. Giả định: [điền]. Hình thức: [Excel/bảng].
Không tạo minh chứng, kết quả công việc hay định mức đã được phê duyệt.
```

**Kiểm tra:** xác nhận với người thực hiện; đối chiếu minh chứng, quy định thời hạn và tính đầy đủ của các dòng trong tệp.

## Tách bảng rà soát và bảng nhập chính thức

```text
Đối chiếu [bảng đề xuất] với [biểu gốc] theo mã dòng và kỳ dữ liệu. Tạo hai đầu ra: (A) bảng rà soát giữ toàn bộ đề xuất; (B) bảng nhập giữ đúng cột, thứ tự và kiểu dữ liệu của biểu gốc, chỉ chứa thay đổi đã xác nhận.

Trong bảng A, với mỗi mã đề xuất, ghi dòng gốc liên quan, hướng xử lý (chuẩn hóa/làm rõ/bổ sung có điều kiện/không nhập), minh chứng giao việc, đầu ra độc lập, căn cứ về sản lượng hoặc thời gian và trạng thái xác nhận. Nếu cùng một bộ hồ sơ có bảng, dự thảo, báo cáo hoặc nhiều lượt cập nhật, chỉ tính riêng khi có căn cứ về phần việc hoặc sản phẩm độc lập và không tính lại giờ đã ghi.
Không đưa số lượng, số giờ, độ khó hoặc tên người thực hiện chưa xác nhận vào bảng B. Giữ ô chưa biết ở trạng thái chưa xác nhận trong bảng A; không thay bằng 0. Nếu chưa có phê duyệt, xuất bảng A và biểu trống hoặc danh sách dòng đủ điều kiện để người phụ trách xác nhận.
Cuối cùng, kiểm đếm theo từng hướng xử lý, đối chiếu mã giữa hai bảng và ghi rõ dòng nào chưa nhập, lý do và bằng chứng còn thiếu.
```
