# TTA_Pedigree-clinical

**Hệ Thống Vẽ Cây Phả Hệ & Phân Tích Quy Luật Di Truyền Lâm Sàng (NSGC Standard v2.6)**  
- **Đơn vị:** Đơn nguyên Di truyền và Sinh học phân tử — Bệnh viện Nhi Hà Nội  
- **Phụ trách chuyên môn & Phát triển:** ThS. Trần Tuấn Anh (`Anh-Genetics`)  
- **Liên kết truy cập trực tuyến (GitHub Pages):** `https://anh-genetics.github.io/TTA_Pedigree-clinical/`

---

## Tính năng nổi bật
1. **Chuẩn danh pháp quốc tế NSGC (National Society of Genetic Counselors):**
   - Đầy đủ ký hiệu Nam, Nữ, Chưa rõ giới tính, Mắc bệnh, Người lành mang gen (Carrier chấm giữa / nửa kín), Đã mất, Proband (`P`), Thai kỳ, Thai lưu (`SB`), Sảy thai (`SAB`), Đình chỉ thai (`TOP`), Hôn nhân cận huyết (`=`), Ly hôn (`//`), Sinh đôi cùng trứng (`MZ`) & khác trứng (`DZ`).
   - Thuật toán tự động dàn trang phả hệ đa nhánh (Multi-Lineage Auto-Layout) tách biệt rõ nhánh Nội – Ngoại và cầu nối hôn nhân vuông góc.
2. **Thư viện 21 Mẫu Phả Hệ Lâm Sàng phổ biến tại Việt Nam:**
   - Beta-Thalassemia, Alpha-Thalassemia (Hb Bart's), HbE/Beta-Thal, SMA (`SMN1`), Bệnh Wilson (`ATP7B`), Tăng sản thượng thận bẩm sinh (`CYP21A2`), Thiếu hụt Citrin (`SLC25A13`), PKU (`PAH`), Điếc bẩm sinh (`GJB2`), Hemophilia A (`F8`), Duchenne (`DMD`), Thiếu men G6PD, Còi xương liên kết X (`PHEX`), Fragile X (`FMR1`), Hội chứng Marfan (`FBN1`), Achondroplasia (`FGFR3`), Tạo xương bất toàn (`COL1A1`), Ung thư vú-buồng trứng (`BRCA1`), Chuyển đoạn Robertson `rob(14;21)`.
3. **Phân tích tự động Quy luật di truyền Mendel (AD, AR, XLR, XLD)** & Khuyến cáo xét nghiệm phân tử bổ sung.
4. **Kiến trúc Bảo mật Enterprise (User/Email + Password):**
   - Tách biệt hoàn toàn Frontend tĩnh trên GitHub Pages và Backend JSON API trên Google Apps Script kết nối cơ sở dữ liệu Google Sheets (`Pedigrees` & `Allowed_Users`) và xuất ảnh vector `.SVG` / `.PNG 300 DPI` vào Google Drive.
