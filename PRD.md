TRƯỜNG ĐẠI HỌC CÔNG NGHÊ THÔNG TIN VÀ TRUYỀN THÔNG

KHOA CÔNG NGHỆ THÔNG TIN

BÁO CÁO

MÔN PHÂN TÍCH VÀ QUẢN LÝ YÊU CẦU PHẦN MỀM

ĐỀ TÀI : PHÂN TÍCH VÀ QUẢN LÝ YÊU CẦU CHO DỰ ÁN PHÁT TRIỂN HỆ THỐNG ỨNG DỤNG AI TRONG GIÁO DỤC, ĐÀO TẠO CHO TRƯỜNG THPT FPT.

Giảng viên hướng dẫn : ThS.Phạm Thị Thượng

Đồng Văn Hòa

Nguyễn Tuấn Long

Phạm Xuân Hưng

Trương Việt Hải

Trần Việt Anh

Nịnh Thanh Khương

Sinh viên thực hiện:

_Thái Nguyên, Năm 2026_

# BẢNG PHÂN CÔNG CÔNG VIỆC NHÓM

|     |     |     |
| --- | --- | --- |
| Thành viên | Vai trò chính | Trách nhiệm chính |
| Phạm Xuân Hưng | Project Manager (PM) / Team Leader | Lập kế hoạch dự án, quản lý tiến độ, điều phối công việc nhóm, chủ trì họp, quản lý Change Request (CCB) |
| Trần Việt Anh | Business Analyst (BA) | Thu thập yêu cầu (NEEDs), phân tích nghiệp vụ, xây dựng Vision Document, chuyển NEEDs → FEATs |
| Đồng Văn Hòa | Requirements Specifier | Viết Use Case Specification, đặc tả chức năng hệ thống, xây dựng luồng nghiệp vụ |
| Nịnh Thanh Khương | UI/UX Designer | Thiết kế giao diện (Mockup), hỗ trợ mô hình hóa hệ thống, vẽ Use Case Diagram / BPMN |
| Nguyễn Tuấn Long | Quality Assurance (QA) | Kiểm tra yêu cầu, xây dựng Test Case, đảm bảo traceability, kiểm thử hệ thống |
| Trương Việt Hải | Configuration Manager / Developer | Quản lý GitHub, version tài liệu, hỗ trợ kỹ thuật, đánh giá tính khả thi hệ thống |

# MỤC LỤC

[BẢNG PHÂN CÔNG CÔNG VIỆC NHÓM 2](#_Toc227158675)

[MỤC LỤC 3](#_Toc227158676)

[LỜI MỞ ĐẦU 8](#_Toc227158677)

[CHƯƠNG 1: TỔNG QUAN DỰ ÁN VÀ KẾ HOẠCH QUẢN LÝ YÊU CẦU 10](#_Toc227158678)

[1.1. Phát biểu bài toán 10](#_Toc227158679)

[1.2. Mục tiêu và tính cấp thiết của dự án 11](#_Toc227158680)

[1.2.1. Tính cấp thiết của dự án (WHY) 11](#_Toc227158681)

[1.2.2. Mục tiêu của dự án (WHAT) 12](#_Toc227158682)

[1.3. Kế hoạch quản lý yêu cầu (RMP) 13](#_Toc227158683)

[1.3.1. Giới thiệu (Introduction) 13](#_Toc227158684)

[1.3.2. Quản lý Yêu cầu (Requirements Management) 14](#_Toc227158685)

[1.4. Các thành phẩm yêu cầu (Requirements Artifacts) 18](#_Toc227158686)

[1.4.1. Mô tả thành phẩm (Artifact Description) 18](#_Toc227158687)

[1.4.2. Tiêu chí lưu vết (Traceability) 22](#_Toc227158688)

[1.4.3. Báo cáo và Đo lường (Reports and Measures) 23](#_Toc227158689)

[1.5. Quản lý thay đổi yêu cầu (Requirements Change Management) 24](#_Toc227158690)

[1.5.1. Xử lý và Phê duyệt Yêu cầu thay đổi (Change Request Processing and Approval) 24](#_Toc227158691)

[1.5.2. Ban điều khiển thay đổi (Change Control Board - CCB) 25](#_Toc227158692)

[1.5.3. Các mốc bàn giao dự án (Project Baselines) 26](#_Toc227158693)

[1.5.4. Hoạt động của quy trình quản lý thay đổi (CRM Process Activity) 27](#_Toc227158694)

[1.6. Các mốc thời gian (Milestones) 28](#_Toc227158695)

[1.6.1. Giai đoạn Khởi tạo (Inception) 28](#_Toc227158696)

[1.6.2. Giai đoạn Chi tiết hóa (Elaboration) 32](#_Toc227158697)

[1.6.3. Giai đoạn Xây dựng (Construction) 35](#_Toc227158698)

[1.6.4. Giai đoạn Chuyển giao (Transition) 39](#_Toc227158699)

[1.7. Đào tạo và Nguồn tài nguyên (Training and Resources) 41](#_Toc227158700)

[1.7.1. Nguồn tài nguyên (Resources) 41](#_Toc227158701)

[1.7.2. Kế hoạch đào tạo (Training Plan) 42](#_Toc227158702)

[1.7.3. Kết luận của phần Đào tạo và Tài nguyên (Training and Resources) 44](#_Toc227158703)

[CHƯƠNG 2: THU THẬP VÀ PHÂN TÍCH QUY TRÌNH NGHIỆP VỤ 44](#_Toc227158704)

[2.1. Xác định Stakeholders 44](#_Toc227158705)

[2.1.1. Stakeholder 44](#_Toc227158706)

[2.1.2 Nhận xét và kết luận về Stakeholder của dự án 45](#_Toc227158707)

[2.2. Kỹ thuật thu thập và Lịch biểu khảo sát 46](#_Toc227158708)

[2.2.1. Cơ sở lựa chọn kỹ thuật thu thập yêu cầu 46](#_Toc227158709)

[2.2.2. Bảng lựa chọn kỹ thuật thu thập yêu cầu theo Stakeholder 47](#_Toc227158710)

[2.2.3. Lịch biểu khảo sát 48](#_Toc227158711)

[2.2.4. Quy trình tiến hành khảo sát 49](#_Toc227158712)

[2.2.5. Nhận xét về hoạt động thu thập yêu cầu 49](#_Toc227158713)

[2.3. Quy trình nghiệp vụ giáo dục chuẩn BPMN 50](#_Toc227158714)

[2.3.1. Mục tiêu xây dựng sơ đồ BPMN 50](#_Toc227158715)

[2.3.2. Phạm vi quy trình nghiệp vụ được mô hình hóa 50](#_Toc227158716)

[2.3.3. Các đối tượng tham gia trong sơ đồ BPMN 51](#_Toc227158717)

[2.3.4. Các ký hiệu BPMN được sử dụng trong mô hình 51](#_Toc227158718)

[2.3.5. Mô tả tóm tắt quy trình nghiệp vụ BPMN 51](#_Toc227158719)

[2.3.6. Các nhánh rẽ và tình huống ngoại lệ chính 52](#_Toc227158720)

[2.3.7. Dữ liệu và các điểm tích hợp trong quy trình 52](#_Toc227158721)

[2.3.8. Đánh giá kết quả mô hình hóa BPMN 52](#_Toc227158722)

[2.4. Phân tích quy trình và Yêu cầu nghiệp vụ cốt lõi 52](#_Toc227158723)

[2.4.1. Mục tiêu của việc phân tích quy trình nghiệp vụ 52](#_Toc227158724)

[2.4.2. Phân tích tổng thể luồng nghiệp vụ 52](#_Toc227158725)

[2.4.3. Phân tích các vai trò và điểm tương tác chính 52](#_Toc227158726)

[2.4.4. Phân tích luồng nghiệp vụ chính (Happy Path) 53](#_Toc227158727)

[2.5. Các luật nghiệp vụ (Business Rules) 53](#_Toc227158728)

[2.5.1. Cơ sở xác định luật nghiệp vụ 53](#_Toc227158729)

[2.5.2. Vai trò của luật nghiệp vụ 54](#_Toc227158730)

[2.5.3. Danh sách các luật nghiệp vụ của hệ thống 54](#_Toc227158731)

[2.5.4 & 2.5.5. Nhận xét và Kết luận 54](#_Toc227158732)

[2.6. Danh sách yêu cầu dạng thô (NEEDs) có gán nguồn gốc 54](#_Toc227158733)

[2.6.1. Cơ sở hình thành danh sách NEEDs 54](#_Toc227158734)

[2.6.2. Nguyên tắc gán nguồn gốc cho NEEDs 54](#_Toc227158735)

[2.6.3. Danh sách yêu cầu dạng thô của dự án 55](#_Toc227158736)

[CHƯƠNG 3: TINH CHẾ YÊU CẦU VÀ TÀI LIỆU TẦM NHÌN DỰ ÁN 58](#_Toc227158737)

[3.1. Thảo luận, tinh chế và phê duyệt yêu cầu (Checklist) 58](#_Toc227158738)

[3.1.1. Mục đích của hoạt động thảo luận và tinh chế yêu cầu 58](#_Toc227158739)

[3.1.2. Cơ sở lý thuyết cho việc tinh chế yêu cầu 58](#_Toc227158740)

[3.1.3. Tổ chức thảo luận online và vai trò của các thành viên 59](#_Toc227158741)

[3.1.4. Nội dung tinh chế tập NEEDs của dự án AI FPT 59](#_Toc227158742)

[3.1.5. Checklist thẩm định và phê duyệt yêu cầu 59](#_Toc227158743)

[3.1.6. Quy trình phê duyệt tập yêu cầu sau tinh chế 60](#_Toc227158744)

[3.1.7. Kết luận của mục thảo luận, tinh chế và phê duyệt yêu cầu 61](#_Toc227158745)

[3.2. TÀI LIỆU TẦM NHÌN DỰ ÁN (Project Vision Document – mẫu IBM) 61](#_Toc227158746)

[1\. Giới thiệu (Introduction) 61](#_Toc227158747)

[2\. Định vị sản phẩm (Positioning) 62](#_Toc227158748)

[3\. Mô tả Stakeholder và Người dùng (Stakeholder and User Descriptions) 63](#_Toc227158749)

[3.1. Đặc điểm thị trường (Market Demographics) 63](#_Toc227158750)

[3.2. Tóm tắt Stakeholder (Stakeholder Summary) 63](#_Toc227158751)

[3.3. Tóm tắt người dùng (User Summary) 63](#_Toc227158752)

[3.4. Môi trường sử dụng (User Environment) 64](#_Toc227158753)

[3.5. Hồ sơ Stakeholder (Stakeholder Profiles) 64](#_Toc227158754)

[3.7. Các nhu cầu chính của Stakeholder/Người dùng (Key Needs) 64](#_Toc227158755)

[4\. Tổng quan sản phẩm (Product Overview) 64](#_Toc227158756)

[4.1. Góc nhìn sản phẩm (Product Perspective) 64](#_Toc227158757)

[4.2. Tóm tắt năng lực cốt lõi (Summary of Capabilities) 65](#_Toc227158758)

[4.3. Giả định và phụ thuộc (Assumptions and Dependencies) 65](#_Toc227158759)

[5\. Tính năng sản phẩm (Product Features - FEATs) 65](#_Toc227158760)

[6\. Các ràng buộc (Constraints) 66](#_Toc227158761)

[7\. Khoảng chất lượng (Quality Ranges) 67](#_Toc227158762)

[8\. Thứ tự trước sau và độ ưu tiên (Precedence and Priority) 67](#_Toc227158763)

[9\. Các yêu cầu sản phẩm khác (Other Product Requirements) 69](#_Toc227158764)

[10\. Yêu cầu về tài liệu hướng dẫn (Documentation Requirements) 70](#_Toc227158765)

[11\. Phụ lục 1 – Thuộc tính của FEATs (Appendix 1 – Feature Attributes) 70](#_Toc227158766)

[3.3. Ma trận dấu vết: NEEDs ⇒ Features 73](#_Toc227158767)

[3.3.1. Mục đích của ma trận NEEDs ⇒ FEATs 73](#_Toc227158768)

[3.3.2. Cơ sở và nguyên tắc ánh xạ 73](#_Toc227158769)

[3.3.3. Bảng diễn giải ánh xạ từ NEEDs sang FEATs 74](#_Toc227158770)

[CHƯƠNG 4: ĐẶC TẢ YÊU CẦU (USE CASES & SUPPLEMENTARY) 77](#_Toc227158771)

[4.1. TÀI LIỆU ĐẶC TẢ USE CASE (Use Case Specification) 77](#_Toc227158772)

[4.1.1. Nguyên tắc xây dựng tài liệu Use Case 77](#_Toc227158773)

[4.1.2. Danh sách Use Case đề xuất cho hệ thống AI THPT FPT 78](#_Toc227158774)

[4.1.3. ĐẶC TẢ CHI TIẾT CÁC USE CASE (DỰ ÁN AI THPT FPT) 79](#_Toc227158775)

[4.2. Ma trận dấu vết: Features ⇒ Use Cases 83](#_Toc227158776)

[4.2.1. Mục đích của ma trận Features ⇒ Use Cases 83](#_Toc227158777)

[4.2.2. Cơ sở và nguyên tắc ánh xạ 83](#_Toc227158778)

[4.2.3. Bảng diễn giải ánh xạ từ Features sang Use Cases 83](#_Toc227158779)

[Bảng 4.2.1. Diễn giải chi tiết ánh xạ FEATs ⇒ UCs 84](#_Toc227158780)

[4.2.4. Ma trận dấu vết tổng hợp Features ⇒ Use Cases 84](#_Toc227158781)

[4.2.5. Nhận xét về ma trận FEATs ⇒ UCs 86](#_Toc227158782)

[4.2.6. Kết luận của mục 4.2 86](#_Toc227158783)

[4.3. Yêu cầu giao diện và Mockup mô phỏng (Figma) 87](#_Toc227158784)

[4.3.1. Mục đích của việc xây dựng mockup giao diện 87](#_Toc227158785)

[4.3.2. Cơ sở xác định yêu cầu giao diện 87](#_Toc227158786)

[4.3.3. Các yêu cầu giao diện chính của hệ thống 87](#_Toc227158787)

[4.3.4. Danh sách các màn hình mockup chính 88](#_Toc227158788)

[4.4. TÀI LIỆU YÊU CẦU BỔ SUNG / PHI CHỨC NĂNG (Supplementary Requirements Specification – theo mẫu IBM) 90](#_Toc227158789)

[Kết luận của mục 4.4 93](#_Toc227158790)

[4.5. Ma trận dấu vết: Features ⇒ Supplementary Requirements 93](#_Toc227158791)

[4.5.1. Mục đích của ma trận Features ⇒ Supplementary Requirements 93](#_Toc227158792)

[4.5.2. Cơ sở và nguyên tắc ánh xạ 94](#_Toc227158793)

[4.5.3. Danh mục các SUPL cốt lõi được dùng trong ma trận 94](#_Toc227158794)

[4.5.4. Bảng diễn giải ánh xạ từ Features sang Supplementary Requirements 95](#_Toc227158795)

[4.5.5. Ma trận dấu vết tổng hợp Features ⇒ Supplementary Requirements 96](#_Toc227158796)

[4.5.6. Nhận xét về ma trận FEATs ⇒ SUPLs 97](#_Toc227158797)

[4.5.7. Kết luận của mục 4.5 97](#_Toc227158798)

[4.6. BẢNG CHÚ GIẢI THUẬT NGỮ (Glossary – theo mẫu IBM) 97](#_Toc227158799)

[1\. Giới thiệu (Introduction) 98](#_Toc227158800)

[2\. Các định nghĩa (Definitions) 98](#_Toc227158801)

[Kết luận của mục 4.6 99](#_Toc227158802)

[CHƯƠNG 5: KIỂM THỬ VÀ HOÀN THIỆN KIM TỰ THÁP 99](#_Toc227158803)

[5.1. Kịch bản (Scenarios) và Trường hợp kiểm thử (Test Cases) 99](#_Toc227158804)

[5.1.1. Vai trò của Scenarios và Test Cases trong dự án 99](#_Toc227158805)

[5.1.2. Nguyên tắc xây dựng Scenarios và Test Cases 99](#_Toc227158806)

[5.1.3. Quy ước mã hóa 99](#_Toc227158807)

[5.1.4. Kịch bản và Test Cases cho nhóm Use Case cốt lõi 100](#_Toc227158808)

[Bảng 5.1.1. Các Scenarios của UC-14 – Chấm điểm bài làm tự luận bằng AI 100](#_Toc227158809)

[Bảng 5.1.2. Test Case TC-UC14-01 100](#_Toc227158810)

[5.2. Ma trận dấu vết: Use Cases ⇒ Scenarios 101](#_Toc227158811)

[5.2.1. Mục đích của ma trận Use Cases ⇒ Scenarios 101](#_Toc227158812)

[5.2.2. Cơ sở và nguyên tắc ánh xạ 101](#_Toc227158813)

[5.2.3. Bảng diễn giải ánh xạ từ Use Cases sang Scenarios 101](#_Toc227158814)

[5.2.4. Ma trận dấu vết tổng hợp Use Cases ⇒ Scenarios 102](#_Toc227158815)

[5.2.5. Nhận xét về ma trận Use Cases ⇒ Scenarios 103](#_Toc227158816)

[5.2.6. Kết luận của mục 5.2 104](#_Toc227158817)

[5.3. Ma trận dấu vết: Scenarios ⇒ Test Cases 104](#_Toc227158818)

[5.3.1. Mục đích của ma trận Scenarios ⇒ Test Cases 104](#_Toc227158819)

[5.3.2. Cơ sở và nguyên tắc ánh xạ 104](#_Toc227158820)

[5.3.3. Bảng diễn giải ánh xạ từ Scenarios sang Test Cases 104](#_Toc227158821)

[5.2.4. Ma trận dấu vết tổng hợp Use Cases ⇒ Scenarios 106](#_Toc227158822)

[5.3.6. Kết luận của mục 5.3 107](#_Toc227158823)

[5.4. Ma trận dấu vết: Supplementary ⇒ Test Cases 107](#_Toc227158824)

[5.4.1. Mục đích của ma trận Supplementary ⇒ Test Cases 107](#_Toc227158825)

[5.4.2. Cơ sở và nguyên tắc ánh xạ 108](#_Toc227158826)

[5.4.3. Danh mục các SUPL cốt lõi dùng trong ma trận 108](#_Toc227158827)

[5.4.4. Bảng diễn giải ánh xạ từ Supplementary Requirements sang Test Cases 109](#_Toc227158828)

[5.4.5. Ma trận dấu vết tổng hợp Supplementary Requirements ⇒ Test Cases 110](#_Toc227158829)

[5.4.7. Kết luận của mục 5.4 111](#_Toc227158830)

[CHƯƠNG 6: QUẢN LÝ YÊU CẦU TRÊN CÔNG CỤ VÀ QUẢN LÝ THAY ĐỔI 111](#_Toc227158831)

[6.2. Phiên bản hóa kho yêu cầu và Quản lý vòng đời (Traceability from/to) 111](#_Toc227158832)

[6.2.1. Mục đích của việc phiên bản hóa kho yêu cầu 112](#_Toc227158833)

[6.2.2. Cơ sở lý thuyết và nguyên tắc quản lý vòng đời 112](#_Toc227158834)

[6.2.3. Phiên bản hóa kho yêu cầu theo các Baseline của dự án 112](#_Toc227158835)

[6.2.4. Quản lý vòng đời của từng yêu cầu trên GitHub 113](#_Toc227158836)

[6.2.4. Quản lý vòng đời của từng yêu cầu trên GitHub 113](#_Toc227158837)

[6.2.5. Quản lý Traceability From / Traceability To 113](#_Toc227158838)

[6.2.6. Cách triển khai Versioning và Lifecycle trên GitHub 114](#_Toc227158839)

[6.3. Đề xuất quy trình quản lý yêu cầu thay đổi (CRM) 114](#_Toc227158840)

[6.3.1. Mục đích của quy trình quản lý thay đổi 114](#_Toc227158841)

[6.3.2. Phạm vi của quy trình thay đổi 114](#_Toc227158842)

[6.3.3. Ban điều khiển thay đổi (CCB) của dự án AI THPT FPT 115](#_Toc227158843)

[6.3.5. Quy trình quản lý thay đổi yêu cầu đề xuất cho dự án 115](#_Toc227158844)

[6.3.6. Bảng quy trình quản lý thay đổi đề xuất 115](#_Toc227158845)

[6.3.7. Minh họa một ví dụ CR trong dự án AI THPT FPT 116](#_Toc227158846)

[6.4. Demo quy trình (Ảnh chụp màn hình thao tác trên tool) 116](#_Toc227158847)

[6.4.5. Đánh giá mức độ đáp ứng của công cụ 118](#_Toc227158848)

[6.4.6. Kết luận của mục 6.4 118](#_Toc227158849)

[KẾT LUẬN 118](#_Toc227158850)

[1\. Thuận lợi 119](#_Toc227158851)

[2\. Khó khăn 119](#_Toc227158852)

[3\. Định hướng phát triển 119](#_Toc227158853)

[4\. Tổng kết chung 120](#_Toc227158854)

# LỜI MỞ ĐẦU

Trong bối cảnh cuộc cách mạng công nghiệp 4.0 đang diễn ra mạnh mẽ, trí tuệ nhân tạo (AI) ngày càng khẳng định vai trò quan trọng trong nhiều lĩnh vực, đặc biệt là giáo dục. Việc ứng dụng AI không chỉ giúp tự động hóa các quy trình truyền thống mà còn mở ra cơ hội nâng cao chất lượng đào tạo, cá nhân hóa trải nghiệm học tập và tối ưu hóa hiệu quả quản lý giáo dục.

Tại Trường THPT FPT – một đơn vị tiên phong trong định hướng giáo dục công nghệ, nhu cầu đổi mới phương pháp giảng dạy và quản lý học tập là vô cùng cấp thiết. Thực tế cho thấy, các hoạt động như chấm bài, tổng hợp kết quả hay theo dõi tiến độ học tập vẫn còn mang tính thủ công, gây tốn nhiều thời gian và chưa đáp ứng được yêu cầu về tính nhanh chóng, chính xác cũng như cá nhân hóa cho từng học sinh.

Xuất phát từ những vấn đề đó, nhóm chúng em thực hiện đề tài “Hệ thống ứng dụng AI trong giáo dục đào tạo THPT FPT” với mục tiêu xây dựng một hệ thống hỗ trợ thông minh, giúp tự động hóa việc chấm điểm, sinh đề thi, hỗ trợ học tập 24/7 và phân tích dữ liệu học tập theo thời gian thực. Qua đó, góp phần nâng cao hiệu quả giảng dạy, cải thiện trải nghiệm học tập và hỗ trợ nhà trường trong việc ra quyết định kịp thời, chính xác.

Báo cáo này trình bày quá trình phân tích yêu cầu, thiết kế quy trình nghiệp vụ, xác định các bên liên quan cũng như xây dựng các chức năng cốt lõi của hệ thống. Nhóm hy vọng rằng đề tài sẽ mang lại những giá trị thiết thực và có thể trở thành nền tảng cho việc triển khai các giải pháp giáo dục thông minh trong tương lai.

# CHƯƠNG 1: TỔNG QUAN DỰ ÁN VÀ KẾ HOẠCH QUẢN LÝ YÊU CẦU

1.1. Phát biểu bài toán

Đại học Thái Nguyên  
Trường Đại học Công nghệ Thông tin và Truyền thông

DỰ ÁN

Học phần: Phân tích và quản lý yêu cầu phần mềm - AMS431  
Hình thức: Dự án  
Mã số: 68777

1\. TÊN DỰ ÁN

Phân tích và quản lý yêu cầu cho dự án phát triển hệ thống ứng dụng trí tuệ nhân tạo (AI) trong giáo dục, đào tạo cho Trường THPT FPT.

2\. PHÁT BIỂU BÀI TOÁN:

Trường THPT FPT là một đơn vị giáo dục định hướng công nghệ, với quy mô đào tạo hơn 2.000 học sinh mỗi năm, tập trung vào các chương trình tăng cường STEM và học tập theo dự án cá nhân. Trong bối cảnh đó, nhà trường đặt ra yêu cầu cao về việc nâng cao chất lượng giảng dạy, cá nhân hóa quá trình học tập và quản lý hiệu quả dữ liệu học tập.

Tuy nhiên, thực tế hiện nay cho thấy nhà trường đang gặp phải một số thách thức đáng kể. Khối lượng bài tập và dự án ngày càng lớn gây áp lực cho giáo viên trong việc chấm bài và đánh giá. Các phương pháp đánh giá truyền thống chủ yếu mang tính thủ công, thiếu tự động hóa, dẫn đến tình trạng quá tải cho giáo viên, đồng thời chưa đáp ứng được nhu cầu phản hồi nhanh và cá nhân hóa cho từng học sinh. Bên cạnh đó, việc theo dõi chất lượng học tập theo thời gian thực vẫn còn hạn chế, gây khó khăn trong việc phát hiện sớm học sinh có nguy cơ học tập yếu.

Để giải quyết những vấn đề trên, Trường THPT FPT cần xây dựng một hệ thống ứng dụng trí tuệ nhân tạo (AI) trong giáo dục, với các chức năng cốt lõi như sau:

1.  Tự động chấm bài bằng AI: Hỗ trợ chấm bài trắc nghiệm và tự luận nhằm giảm tải công việc cho giáo viên và tăng tốc độ phản hồi cho học sinh.
2.  Sinh đề kiểm tra thông minh: AI tạo đề thi phù hợp với năng lực từng học sinh dựa trên dữ liệu lịch sử học tập và mức độ thành thạo.
3.  Trợ giảng ảo (AI Tutor): Hỗ trợ giải thích bài, gợi ý hướng giải và đồng hành cùng học sinh trong quá trình học tập 24/7.
4.  Phân tích dữ liệu học tập: AI thu thập và phân tích dữ liệu để dự báo kết quả học tập và mức độ hoàn thành môn học.
5.  Cảnh báo sớm học sinh yếu: Phát hiện sớm các trường hợp có nguy cơ sa sút học lực để có biện pháp can thiệp kịp thời.
6.  Chatbot hỗ trợ học tập: Giải đáp thắc mắc liên quan đến bài học, lịch học, lịch thi và bài tập.
7.  Hỗ trợ quản lý thông minh: Tối ưu công tác quản lý giáo dục thông qua thống kê, báo cáo chất lượng học tập và hỗ trợ ra quyết định.

Việc triển khai hệ thống này sẽ giúp Trường THPT FPT nâng cao chất lượng đào tạo, hỗ trợ cá nhân hóa học tập, giảm áp lực cho giáo viên, đồng thời cải thiện trải nghiệm học tập của học sinh. Qua đó, nhà trường từng bước hiện thực hóa mô hình “trường học thông minh” trong thời đại chuyển đổi số.

1.2. Mục tiêu và tính cấp thiết của dự án

Theo lý thuyết kỹ nghệ yêu cầu, bước đầu tiên trong quá trình phát triển phần mềm là xác định rõ bài toán nhằm trả lời hai câu hỏi cốt lõi: WHY (Tại sao cần xây dựng hệ thống?) và WHAT (Hệ thống sẽ mang lại giá trị gì?). Việc làm rõ hai yếu tố này giúp định hướng đúng mục tiêu phát triển và đảm bảo tính khả thi của dự án.

### 1.2.1. Tính cấp thiết của dự án (WHY)

Trong bối cảnh chuyển đổi số đang diễn ra mạnh mẽ trong lĩnh vực giáo dục, Trường THPT FPT – với định hướng trở thành mô hình “Smart School” – đang đối mặt với nhiều thách thức cần được giải quyết kịp thời:

- Quá tải trong công tác chấm bài và đánh giá:  
    Giáo viên phải xử lý khối lượng lớn bài tập và dự án, dẫn đến tốn nhiều thời gian và giảm hiệu quả giảng dạy.
- Độ trễ trong phản hồi học tập:  
    Học sinh thường nhận kết quả sau một khoảng thời gian dài, làm giảm khả năng tiếp thu và cải thiện kiến thức.
- Thiếu cá nhân hóa trong học tập:  
    Chưa có cơ chế điều chỉnh nội dung học và kiểm tra phù hợp với năng lực của từng học sinh.
- Hạn chế trong việc theo dõi dữ liệu thời gian thực:  
    Nhà trường chưa có hệ thống phân tích và cảnh báo sớm để phát hiện học sinh có nguy cơ học lực yếu.
- Áp lực đổi mới công nghệ giáo dục:  
    Để duy trì vị thế tiên phong, nhà trường cần ứng dụng các công nghệ hiện đại như AI vào giảng dạy và quản lý.

Những hạn chế trên không chỉ ảnh hưởng đến chất lượng đào tạo mà còn làm giảm hiệu quả vận hành của nhà trường. Do đó, việc xây dựng một hệ thống ứng dụng AI trong giáo dục là hết sức cần thiết nhằm giải quyết các vấn đề hiện tại và nâng cao năng lực cạnh tranh trong môi trường giáo dục hiện đại.

### 1.2.2. Mục tiêu của dự án (WHAT)

a. Mục tiêu tổng quát

Xây dựng một hệ thống ứng dụng trí tuệ nhân tạo trong giáo dục nhằm tự động hóa các hoạt động giảng dạy và quản lý, nâng cao chất lượng đào tạo, đồng thời tạo ra môi trường học tập thông minh, linh hoạt và cá nhân hóa cho học sinh.

b. Mục tiêu cụ thể

Hệ thống cần đáp ứng các mục tiêu chức năng chính sau:

- Tự động hóa chấm điểm:  
    Ứng dụng AI để chấm bài trắc nghiệm tức thì và hỗ trợ chấm bài tự luận, giúp giảm tải công việc cho giáo viên và nâng cao độ chính xác.
- Sinh đề kiểm tra thông minh:  
    Tạo ra các đề thi phù hợp với năng lực của từng học sinh dựa trên dữ liệu học tập và mức độ thành thạo.
- Hỗ trợ học tập 24/7:  
    Cung cấp AI Tutor và chatbot giúp giải đáp thắc mắc, hướng dẫn học sinh trong quá trình học tập mọi lúc, mọi nơi.
- Phân tích và dự báo học tập:  
    Sử dụng AI để phân tích dữ liệu học tập, dự báo kết quả và phát hiện sớm các vấn đề trong quá trình học của học sinh.
- Cảnh báo sớm và hỗ trợ can thiệp:  
    Tự động phát hiện học sinh có nguy cơ học lực yếu và hỗ trợ giáo viên đưa ra giải pháp kịp thời.
- Hỗ trợ quản lý giáo dục:  
    Cung cấp các báo cáo, thống kê và phân tích giúp nhà trường tối ưu hóa công tác quản lý và ra quyết định.

c. Kết quả mong đợi

Sau khi hệ thống được triển khai, dự án kỳ vọng đạt được các kết quả sau:

- Giảm đáng kể khối lượng công việc thủ công cho giáo viên.
- Rút ngắn thời gian phản hồi kết quả học tập cho học sinh.
- Nâng cao chất lượng giảng dạy và hiệu quả học tập.
- Tăng cường khả năng theo dõi và quản lý học tập theo thời gian thực.
- Xây dựng thành công mô hình giáo dục thông minh tại Trường THPT FPT.

## 1.3. Kế hoạch quản lý yêu cầu (RMP)

### 1.3.1. Giới thiệu (Introduction)

1.3.1.1. Mục đích (Purpose)

Mục đích của Kế hoạch quản lý yêu cầu (RMP) này là xác định một cách tiếp cận có hệ thống để khơi gợi, tổ chức, ghi chép và quản lý các yêu cầu cho dự án "Phát triển hệ thống ứng dụng AI trong giáo dục, đào tạo cho Trường THPT FPT".

Tài liệu này cung cấp hướng dẫn chi tiết về quy trình, công cụ và trách nhiệm của các thành viên, nhằm đảm bảo mọi yêu cầu đều được kiểm soát chặt chẽ theo mô hình Kim tự tháp yêu cầu, đáp ứng đúng mục tiêu nâng cao chất lượng đào tạo và xây dựng mô hình “trường học thông minh” của nhà trường.

1.3.1.2. Phạm vi (Scope)

Kế hoạch này được áp dụng cho toàn bộ vòng đời phát triển của hệ thống AI trong giáo dục tại THPT FPT, tuân thủ theo 4 giai đoạn của tiến trình RUP (Inception, Elaboration, Construction, Transition).

Phạm vi quản lý bao trùm tất cả các cấp độ yêu cầu, bao gồm:

- Yêu cầu thô (NEEDs) từ các bên liên quan
- Tính năng hệ thống (FEATs)
- Trường hợp sử dụng (Use Cases - UCs)
- Yêu cầu bổ sung (SUPLs)
- Các kịch bản kiểm thử (Test Cases)

1.3.1.3. Định nghĩa và Từ viết tắt (Definitions, Acronyms, and Abbreviations)

- RMP (Requirements Management Plan): Kế hoạch quản lý yêu cầu
- RUP (Rational Unified Process): Tiến trình phát triển phần mềm
- CCB (Change Control Board): Ban điều khiển thay đổi
- CR (Change Request): Yêu cầu thay đổi
- NEEDs: Nhu cầu từ các bên liên quan
- FEATs (Features): Tính năng hệ thống
- UCs (Use Cases): Trường hợp sử dụng
- SUPLs (Supplementary Requirements): Yêu cầu bổ sung

AI: Trí tuệ nhân tạo

1.3.1.4. Tài liệu tham khảo (References)

Tài liệu học phần Phân tích và Quản lý yêu cầu phần mềm - AMS431

Phát biểu bài toán hệ thống AI tại THPT FPT

Mẫu chuẩn Kế hoạch quản lý yêu cầu (RMP Template)

1.3.1.5. Tổng quan (Overview)

Phần còn lại của tài liệu RMP được cấu trúc như sau:

- Phần 2: Cơ cấu tổ chức, vai trò và công cụ sử dụng
- Phần 3: Các loại yêu cầu và tiêu chí truy vết
- Phần 4: Quy trình quản lý thay đổi yêu cầu
- Phần 5: Các mốc thời gian theo RUP
- Phần 6: Nguồn lực và kế hoạch đào tạo

### 1.3.2. Quản lý Yêu cầu (Requirements Management)

_1.3.2.1. Tổ chức, Trách nhiệm và Giao tiếp (Organization, Responsibilities, and Interfaces)_

- Mục này xác định các cá nhân, tổ chức tham gia vào dự án hệ thống AI giáo dục THPT FPT và trách nhiệm của họ trong tiến trình kỹ nghệ yêu cầu. Nhóm dự án gồm 6 thành viên đảm nhiệm các vai trò sau:

_1.3.2.1.1. Khách hàng (Customer)_

Đại diện: Ban Giám hiệu Trường THPT FPT

Trách nhiệm:  
Là đơn vị đưa ra yêu cầu, định hướng mục tiêu hệ thống và có quyền phê duyệt các mốc quan trọng cũng như nghiệm thu sản phẩm.

_1.3.2.1.2. Người dùng (User)_

Đại diện: Giáo viên, học sinh

Trách nhiệm:  
Trực tiếp sử dụng hệ thống. Cung cấp các yêu cầu thực tế về chức năng và trải nghiệm, tham gia đánh giá và phản hồi trong quá trình phát triển.

_1.3.2.1.3. Các bên liên quan (Stakeholder)_

Đại diện: Ban giám hiệu, giáo viên, học sinh, bộ phận IT

Trách nhiệm:  
Cung cấp các yêu cầu nghiệp vụ, kỹ thuật và các ràng buộc để hệ thống phù hợp với thực tế vận hành.

_1.3.2.1.4. Quản lý dự án (Project Manager)_

Đại diện: Thành viên 1

Trách nhiệm:  
Lập kế hoạch RMP, phân công công việc, theo dõi tiến độ dự án theo các giai đoạn RUP và quản lý rủi ro.

1.3.2.1.5. Trưởng nhóm (Team Leader)

Đại diện: Thành viên 1

Trách nhiệm:  
Điều phối hoạt động nhóm, tổ chức họp và đưa ra quyết định khi có thay đổi hoặc xung đột yêu cầu.

1.3.2.1.6. Người đặc tả yêu cầu (Requirements Specifier / BA)

Đại diện: Thành viên 2

Trách nhiệm:  
Phân tích nghiệp vụ, chuyển đổi NEEDs thành FEATs và Use Cases, xây dựng tài liệu yêu cầu.

1.3.2.1.7. Lập trình viên (Developer)

Đại diện: Thành viên 3, 4

Trách nhiệm:  
Thiết kế giao diện (mockup), tư vấn giải pháp kỹ thuật và đảm bảo tính khả thi của hệ thống, đặc biệt với các chức năng AI.

1.3.2.1.8. Đảm bảo chất lượng (Quality Assurance - QA)

Đại diện: Thành viên 5

Trách nhiệm:  
Kiểm tra tính đầy đủ và nhất quán của yêu cầu, xây dựng kịch bản và trường hợp kiểm thử.

1.3.2.1.9. Quản lý cấu hình (Configuration Manager)

Đại diện: Thành viên 6

Trách nhiệm:  
Quản lý tài liệu, kiểm soát phiên bản và duy trì hệ thống lưu trữ (GitHub).

1.3.2.2. Bảng thông tin liên lạc (Contact Table)

Bảng thông tin liên lạc cung cấp thông tin của các bên liên quan và thành viên dự án, bao gồm họ tên, vai trò, email và đơn vị.

Việc duy trì bảng này nhằm đảm bảo quá trình trao đổi thông tin, thẩm định và xử lý các yêu cầu thay đổi (CR) diễn ra hiệu quả.

_Bảng thông tin liên lạc_

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Vai trò / Chức danh | Người đại diện | Email liên hệ | Kênh giao tiếp chính | Trách nhiệm chính trong RE |
| Khách hàng (Customer) | Ban Giám hiệu THPT FPT | \-khachang@gmail.com | Email, Họp trực tiếp | Định hướng, phê duyệt, nghiệm thu |
| Người dùng (User) | Giáo viên, Học sinh | User@gmail.com | Phỏng vấn, khảo sát | Cung cấp NEEDs, phản hồi |
| Quản lý dự án (PM / Team Leader) | Phạm Xuân Hưng | Aaa@gmail.com | Call, Zalo, Email | Lập kế hoạch, quản lý tiến độ |
| BA / Requirements Specifier | Trần Việt Anh | tranhbriona@gmail.com | Call, Zalo, Email | Phân tích yêu cầu, viết Use Case |
| Developer | Nguyễn Tuấn Long | tranhbriona@gmail.com | Call, Zalo, Email | Thiết kế, mockup |
| Developer | Trương Việt Hải | tranhbriona@gmail.com | Call, Zalo, Email | Thiết kế, hỗ trợ kỹ thuật |
| QA  | Đồng Văn Hòa | tranhbriona@gmail.com | Call, Zalo, Email | Test, kiểm tra yêu cầu |
| Configuration Manager | Nịnh Thanh Khương | tranhbriona@gmail.com | Call, Zalo, Email | Quản lý tài liệu, version |

1.3.2.3. Công cụ, Môi trường và Cơ sở hạ tầng (Tools, Environment, and Infrastructure)

Mục này xác định các công cụ phần mềm, nền tảng phần cứng và môi trường lưu trữ mà đội dự án (6 thành viên) sử dụng để thu thập, phân tích, đặc tả và quản lý yêu cầu cho hệ thống AI trong giáo dục tại THPT FPT.

a. Công cụ quản lý yêu cầu (Requirements Management Tools)

GitHub (Công cụ chính):

- Mục đích:  
    Sử dụng làm công cụ quản lý yêu cầu xuyên suốt dự án, phù hợp với quy mô nhóm nhỏ và làm việc cộng tác.
- Chức năng:  
    Quản lý kho yêu cầu (tạo, chỉnh sửa, cập nhật); sử dụng GitHub Issues để định nghĩa NEEDs, FEATs, Use Cases; sử dụng Labels để phân loại yêu cầu và trạng thái; sử dụng Discussions để trao đổi; sử dụng Pull Requests để quản lý yêu cầu thay đổi (CR).

Microsoft Word & Excel:

- Mục đích:  
    Word được sử dụng để soạn thảo các tài liệu chính (RMP, Vision Document, Use Case Specification, Supplementary Requirements).  
    Excel được sử dụng để lập danh sách yêu cầu ban đầu và xây dựng Ma trận truy vết (Traceability Matrix).

b. Công cụ mô hình hóa và thiết kế (Modeling & Design Tools)

Draw.io / Bizagi Modeler:

- Mục đích:  
    Dùng để xây dựng sơ đồ quy trình nghiệp vụ (BPMN) cho các hoạt động giảng dạy, học tập và quản lý; vẽ sơ đồ Use Case nhằm mô tả tương tác giữa người dùng và hệ thống.

Figma (hoặc Visily):

- Mục đích:  
    Thiết kế giao diện mẫu (Mockup UI) cho các chức năng như chấm bài, chatbot, AI tutor; hỗ trợ thu thập và xác nhận yêu cầu giao diện với người dùng.

c. Môi trường lưu trữ và chia sẻ (Environment & Infrastructure)

Google Drive:

- Mục đích:  
    Lưu trữ và chia sẻ tài liệu dự án như file Word, Excel, sơ đồ và biên bản họp; hỗ trợ làm việc nhóm theo thời gian thực.

Cơ sở hạ tầng phần cứng:

- Mô tả:  
    Dự án sử dụng máy tính cá nhân (PC/Laptop) của 6 thành viên, có kết nối Internet ổn định để truy cập và làm việc trên các nền tảng như GitHub, Figma và Google Driv

- Phê duyệt / từ chối CR
- Đảm bảo tiến độ và chất lượng

## 1.4. Các thành phẩm yêu cầu (Requirements Artifacts)

Phần này mô tả chi tiết các loại tài liệu, loại yêu cầu và các thuộc tính liên quan sẽ được tạo ra, lưu trữ và theo dõi trong suốt vòng đời của dự án "Phát triển Hệ thống ứng dụng AI trong giáo dục, đào tạo cho Trường THPT FPT".

### 1.4.1. Mô tả thành phẩm (Artifact Description)

1.4.1.1. Các loại tài liệu (Document Types) Để đảm bảo tính toàn vẹn của mô hình Kim tự tháp yêu cầu, nhóm dự án sẽ xây dựng và duy trì các loại tài liệu chuẩn sau đây. Tất cả các tài liệu này sẽ được lưu trữ tập trung trên Google Drive và quản lý phiên bản thông qua GitHub.

- Tài liệu Yêu cầu của các bên liên quan (Stakeholder Requests Document):
- Mô tả: Tài liệu tổng hợp kết quả từ các buổi khảo sát, phỏng vấn và bảng hỏi đối với Ban giám hiệu, Giáo viên và Học sinh THPT FPT. Nó chứa danh sách các yêu cầu thô (NEEDs) và nguồn gốc đề xuất ban đầu.
- Người phụ trách (PIC): Business Analyst (BA) Lead.
- Tài liệu Tầm nhìn dự án (Vision Document):
    - Mô tả: Là tài liệu nền tảng định hướng cho toàn bộ dự án. Tài liệu này cung cấp cái nhìn tổng quan về bài toán của THPT FPT, định nghĩa hệ thống AI thông qua các Tính năng sản phẩm (Features - FEATs) cốt lõi (như AI Grading, AI Tutor) đã được phê duyệt.
    - Người phụ trách (PIC): Business Analyst (BA).
- Tài liệu Đặc tả Trường hợp sử dụng (Use-Case Specification):
    - Mô tả: Tài liệu đặc tả chi tiết cho từng Use Case (yêu cầu chức năng) của hệ thống. Mỗi đặc tả sẽ bao gồm luồng sự kiện cơ bản (Basic flow), luồng thay thế (Alternative flows) và các điều kiện trước/sau (Pre/Post-conditions) cho các chức năng như: Tải lên bài thi tự luận, Trò chuyện với trợ giảng ảo AI, Xem báo cáo dự báo học lực...
    - Người phụ trách (PIC): Business Analyst (BA).
- Tài liệu Đặc tả Yêu cầu bổ sung (Supplementary Requirements Specification):
- Mô tả: Tài liệu tập hợp toàn bộ các yêu cầu phi chức năng (SUPLs) không được biểu diễn trực tiếp trong Use Case. Bao gồm các yêu cầu về: Hiệu năng (tốc độ trả kết quả chấm thi < 5s), Độ chính xác của mô hình AI, Khả năng tích hợp API (với hệ thống quản lý điểm EduNext hiện tại) và bảo mật dữ liệu học sinh.
- Người phụ trách (PIC): Business Analyst (BA) / AI Engineer.
- Bảng chú giải thuật ngữ (Glossary):
    - Mô tả: Một cuốn từ điển nội bộ của dự án định nghĩa rõ các thuật ngữ nghiệp vụ đặc thù, các từ viết tắt (VD: AI Grading, NLP, Adaptive Learning, BGH, Cảnh báo học vụ) nhằm đảm bảo sự thống nhất trong cách hiểu giữa nhóm phát triển và Stakeholders.
    - Người phụ trách (PIC): Cả nhóm cùng đóng góp, QA Team kiểm duyệt.
- Tài liệu Kịch bản và Trường hợp kiểm thử (Scenarios & Test Cases Document):
    - Mô tả: Tài liệu phục vụ cho khâu nghiệm thu, chứa các kịch bản sử dụng (Scenarios) được sinh ra từ Use Case và các trường hợp kiểm thử (Test Cases) chi tiết với dữ liệu đầu vào, các bước test và kết quả mong đợi.
    - Người phụ trách (PIC): Đảm bảo chất lượng (QA Team).

1.4.1.2. Các loại yêu cầu (Requirement Types) Để đảm bảo tính nhất quán từ khâu khơi gợi đến khâu kiểm thử, dự án "AI Giáo dục FPT" áp dụng phân loại yêu cầu theo đúng Mô hình Kim tự tháp yêu cầu. Các loại yêu cầu này được viết tắt bằng các mã (Prefix) và được quản lý chặt chẽ trên công cụ GitHub (thông qua hệ thống Labels).

- Nhu cầu của các bên liên quan (NEED - Stakeholder's Request):
    - Mô tả: Là các yêu cầu thô, ý tưởng, hoặc vấn đề được phát biểu trực tiếp từ Ban giám hiệu, Giáo viên. NEEDs mang tính nghiệp vụ cao, trả lời câu hỏi "Tại sao cần xây dựng hệ thống?" (WHY/WHAT) nhưng chưa mô tả giải pháp AI chi tiết.

Mã định danh: STRQ-xx (Ví dụ: STRQ-01: Giáo viên muốn giảm thiểu thời gian chấm bài thi tự luận).

- Tính năng sản phẩm (FEAT - Product Feature):

Mô tả: Là các dịch vụ hoặc chức năng lớn mà hệ thống AI cung cấp để đáp ứng một hoặc nhiều NEEDs. Tính năng là cầu nối giữa nhu cầu nghiệp vụ và đặc tả hệ thống.

Mã định danh: FEAT-xx (Ví dụ: FEAT-01: Hệ thống AI chấm bài tự động - AI Grading).

- Trường hợp sử dụng (UC - Use Case):

Mô tả: Đại diện cho yêu cầu chức năng của hệ thống. UC mô tả chi tiết chuỗi tương tác (luồng sự kiện) giữa Tác nhân (Actor - ví dụ: Giáo viên, Học sinh) và Hệ thống để đạt được một mục tiêu cụ thể.

Mã định danh: UC-xx (Ví dụ: UC-05: Sinh đề thi theo năng lực học sinh).

- Yêu cầu bổ sung (SUPL - Supplementary Requirement):

Mô tả: Đại diện cho yêu cầu phi chức năng và các ràng buộc hệ thống không thể mô tả được bên trong Use Case. Bao gồm các khía cạnh: Độ chính xác thuật toán, Hiệu năng, Bảo mật dữ liệu.

Mã định danh: SUPL-xx (Ví dụ: SUPL-02: AI phải nhận diện được chữ viết tay với độ chính xác > 95%).

- Kịch bản (SCE - Scenario):

Mô tả: Là một đường dẫn (path) thực thi cụ thể của một Use Case. Một UC có thể sinh ra nhiều Scenarios (bao gồm kịch bản thành công và kịch bản ngoại lệ/thất bại).

Mã định danh: SCE-xx (Ví dụ: SCE-04: AI không thể đọc được bài thi do ảnh quá mờ).

- Trường hợp kiểm thử (TC - Test Case):

Mô tả: Nằm ở đáy kim tự tháp, TC là tập hợp các dữ liệu đầu vào (input), điều kiện thực thi và kết quả mong đợi dùng để kiểm chứng xem các SCEs và SUPLs có được lập trình đúng hay không.

Mã định danh: TC-xx (Ví dụ: TC-12: Upload file ảnh bài làm dưới 1MB và sai định dạng .jpg).

1.4.1.3. Các thuộc tính (Attributes) Để quản lý kho yêu cầu một cách tự động và hiệu quả trên công cụ GitHub, mỗi loại yêu cầu (NEED, FEAT, UC, SUPL, SCE, TC) khi được tạo ra bắt buộc phải đi kèm với một tập hợp các thuộc tính. Việc gán thuộc tính giúp nhóm dự án dễ dàng lọc, sắp xếp và theo dõi vòng đời của từng yêu cầu.

- Mã định danh (ID):
    - Mô tả: Chuỗi ký tự định danh duy nhất cho mỗi yêu cầu, được gắn tự động hoặc thủ công.
    - Áp dụng cho: Tất cả các loại yêu cầu.
- Nguồn gốc (Origin / Source):
    - Mô tả: Lưu vết nơi xuất phát của yêu cầu này (Ví dụ: Ban Giám Hiệu, Giáo viên Toán, Học sinh khối 10, hoặc do Dev Team đề xuất). Việc này đặc biệt quan trọng để giải quyết khi xảy ra xung đột yêu cầu.
    - Áp dụng chủ yếu cho: NEEDs, FEATs và SUPLs.
- Người phụ trách (Assigned To / Owner):
    - Mô tả: Thành viên/Nhóm (Dev, QA, AI Engineer) chịu trách nhiệm chính trong việc phân tích, huấn luyện mô hình hoặc kiểm thử yêu cầu đó trên GitHub.
    - Áp dụng cho: Tất cả các loại yêu cầu.
- Độ ưu tiên (Priority):
    - Mô tả: Thể hiện mức độ quan trọng và cấp thiết của yêu cầu đối với sự thành công của dự án áp dụng tại THPT FPT.
    - Áp dụng cho: NEEDs, FEATs, UCs, SUPLs.
- Trạng thái (Status):
    - Mô tả: Chỉ ra vị trí hiện tại của yêu cầu trong vòng đời phát triển.
    - Áp dụng cho: Tất cả các loại yêu cầu.
- Độ khó / Nỗ lực (Difficulty / Effort):
    - Mô tả: Ước lượng mức độ phức tạp về mặt thuật toán AI và thời gian cần thiết để hoàn thành yêu cầu này.
    - Áp dụng cho: FEATs, UCs.
- Phiên bản phát hành (Target Release / Version):
    - Mô tả: Chỉ định yêu cầu này sẽ được đóng gói và bàn giao trong phiên bản phần mềm nào (Ví dụ: Release 1.0 - Chấm thi tự động; Release 2.0 - Trợ giảng ảo 24/7).
    - Áp dụng cho: FEATs, UCs.

1.4.1.4. Giá trị danh sách (List Values) Để đảm bảo tính nhất quán và dễ dàng lọc dữ liệu trên công cụ quản lý tự động, các thuộc tính sẽ chỉ nhận các giá trị định sẵn trong danh sách dưới đây:

- Giá trị cho thuộc tính Độ ưu tiên (Priority):
    - High (Cao): Yêu cầu bắt buộc phải có để hệ thống hoạt động được (Ví dụ: AI chấm bài trắc nghiệm, Quản lý tài khoản học sinh).
    - Medium (Trung bình): Yêu cầu quan trọng nhưng có thể khắc phục tạm thời bằng cách thủ công (Ví dụ: Báo cáo phân tích chuyên sâu).
    - Low (Thấp): Yêu cầu "có thì tốt", tối ưu trải nghiệm (Ví dụ: Đổi avatar, chế độ Dark Mode).
- Giá trị cho thuộc tính Trạng thái (Status):
    - Proposed (Đề xuất): Yêu cầu mới được đưa ra từ kết quả khảo sát, đang chờ Ban điều khiển (CCB) đánh giá.
    - Approved (Đã phê duyệt): Yêu cầu đã được phân tích, chốt đưa vào Baseline.
    - In Development (Đang phát triển): Dev/AI Team đang thực hiện code hoặc train model cho yêu cầu này.
    - Verified / Ready (Đã kiểm chứng / Sẵn sàng): Yêu cầu đã qua khâu kiểm thử bởi QA và sẵn sàng phát hành.
    - Suspended / Rejected (Tạm ngưng / Từ chối): Yêu cầu bị loại bỏ do không khả thi về mặt dữ liệu/thuật toán hoặc không phù hợp mục tiêu.
- Giá trị cho thuộc tính Độ khó (Difficulty / Effort):
    - High (Cao): Cần nỗ lực lớn, thuật toán phức tạp (Ví dụ: AI chấm điểm và nhận xét bài văn tự luận bằng NLP).
    - Medium (Trung bình): Nghiệp vụ có mức độ phức tạp vừa phải (Ví dụ: Sinh mã đề thi từ ngân hàng câu hỏi).
    - Low (Thấp): Các tính năng hệ thống cơ bản, giao diện.
- Giá trị cho thuộc tính Phiên bản phát hành (Target Release):
    - Release 1.0 (Core AI Evaluation): Tập trung vào yêu cầu cốt lõi (Chấm bài tự động, Quản lý đề thi, Dashboard cơ bản).
    - Release 2.0 (AI Tutor & Analytics): Tập trung vào yêu cầu nâng cao (Trợ giảng ảo Chatbot, Phân tích và dự báo nguy cơ học lực yếu).

### 1.4.2. Tiêu chí lưu vết (Traceability)

Mục đích của việc thiết lập lưu vết là đảm bảo mọi yêu cầu ở các tầng thấp đều có nguồn gốc hợp lệ từ một yêu cầu nghiệp vụ ở tầng cao, và ngược lại, mọi nhu cầu của THPT FPT đều phải được hiện thực hóa bằng AI và kiểm thử đầy đủ.

1.4.2.1. Tiêu chí lưu vết cho các loại yêu cầu Dự án thiết lập mạng lưới truy vết 2 chiều (Bi-directional Traceability). QA Team sẽ chịu trách nhiệm duy trì các Ma trận dấu vết (Traceability Matrix) theo các tiêu chí bắt buộc sau:

- Liên kết tầng NEEDS và tầng FEATS:
    - Quy tắc: Mọi Tính năng (FEAT) sinh ra phải bắt nguồn từ ít nhất một Nhu cầu (NEED).
    - Ví dụ: FEAT-01 (AI Chấm bài tự động) trace from STRQ-01 (Giáo viên bị quá tải vì mất 20h/tuần để chấm bài).
- Liên kết tầng FEATS và tầng Use Cases (UCs) / Yêu cầu bổ sung (SUPLs):
    - Quy tắc: Mỗi Tính năng (FEAT) phải được cụ thể hóa bằng ít nhất một luồng chức năng (UC) hoặc bị ràng buộc bởi một yêu cầu phi chức năng (SUPL).
    - Ví dụ: UC-01 (Chấm thi trắc nghiệm) và SUPL-01 (Trả kết quả < 5s) trace from FEAT-01 (AI Chấm bài tự động).
- Liên kết tầng Use Cases (UCs) và tầng Kịch bản (Scenarios):
    - Quy tắc: Mỗi Use Case phải được phân rã thành các Kịch bản (SCE) bao gồm 1 kịch bản thành công và các kịch bản ngoại lệ.
    - Ví dụ: SCE-01 (Chấm thành công) và SCE-02 (Lỗi do ảnh chụp giấy thi bị mờ) trace from UC-01 (Chấm thi trắc nghiệm).
- Liên kết tầng Scenarios / SUPLs và tầng Test Cases (TCs):
    - Quy tắc: Mọi Kịch bản (SCE) và Yêu cầu bổ sung (SUPL) đều phải có ít nhất một Trường hợp kiểm thử (TC) để nghiệm thu.
    - Ví dụ: TC-05 (Upload file ảnh mờ độ phân giải < 72dpi) trace from SCE-02 (Lỗi do ảnh chụp giấy thi bị mờ).

### 1.4.3. Báo cáo và Đo lường (Reports and Measures)

Để theo dõi "sức khỏe" của dự án AI FPT và đảm bảo tiến độ, nhóm sẽ định kỳ xuất các báo cáo và đo lường các chỉ số (metrics) từ hệ thống quản lý. Việc báo cáo thực hiện hàng tuần và bắt buộc phải có tại các mốc bàn giao.

- 1.4.3.1. Các loại báo cáo (Reports)
- Báo cáo trạng thái yêu cầu (Requirements Status Report):
    - Mô tả: Trích xuất từ GitHub, báo cáo thống kê tổng số lượng các yêu cầu và phân loại theo các trạng thái.
    - Mục đích: Giúp Project Manager (PM) biết tiến độ train model/code có bám sát yêu cầu hay không.
- Báo cáo độ bao phủ truy vết (Traceability Coverage Report):
    - Mô tả: Báo cáo này chỉ ra những yêu cầu bị "mồ côi" (không có nguồn gốc) hoặc "chưa có điểm đến" (chưa có Test Case).
    - Mục đích: Giúp QA đảm bảo 100% các chức năng AI đều đã có kịch bản kiểm thử.
- Báo cáo yêu cầu thay đổi (Change Request Report):
    - Mô tả: Thống kê số lượng các Pull Requests hoặc Issues được gắn nhãn Change Request.
    - Mục đích: Đánh giá xem hệ thống có đang bị thay đổi luồng nghiệp vụ/cấu trúc dữ liệu AI quá nhiều không.

1.4.3.2. Các chỉ số đo lường (Measures) Nhóm sử dụng các công thức đo lường cơ bản sau để đánh giá chất lượng phân tích:

- Tỷ lệ bay hơi yêu cầu (Requirements Volatility): - Công thức: = (Số yêu cầu bị sửa đổi, thêm mới, xóa bỏ) / (Tổng số yêu cầu đã phê duyệt ở Baseline 1).
    - Mục tiêu: Nếu tỷ lệ này > 20%, Ban quản lý dự án phải họp khẩn cấp với BGH trường FPT để chốt lại phạm vi.
- Tỷ lệ bao phủ kiểm thử (Test Coverage): - Công thức: = (Số lượng UCs/SUPLs đã có Test Case) / (Tổng số UCs/SUPLs).
    - Mục tiêu: Bắt buộc đạt tỷ lệ 100% trước khi triển khai hệ thống AI vào nhà trường.

1.5. Quản lý thay đổi yêu cầu (Requirements Change Management)

Mục này xác định quy trình tiếp nhận, đánh giá và phê duyệt mọi sự thay đổi liên quan đến các yêu cầu đã được chốt (baselined) của dự án Hệ thống ứng dụng AI trong giáo dục tại THPT FPT.

### 1.5.1. Xử lý và Phê duyệt Yêu cầu thay đổi (Change Request Processing and Approval)

Bất kỳ sự thay đổi nào về mặt yêu cầu (thêm mới, chỉnh sửa thuật toán, hoặc loại bỏ chức năng) sau khi đã qua mốc phê duyệt (Baseline) đều phải tuân thủ nghiêm ngặt quy trình 4 bước sau đây. Toàn bộ quy trình này được số hóa và thực hiện trên hệ thống GitHub.

- Bước 1: Tiếp nhận yêu cầu thay đổi (Submit Change Request - CR)
    - Người thực hiện: Bất kỳ bên liên quan nào (BGH THPT FPT, Giáo viên, PM, BA, AI Engineer, QA).
    - Hành động: Người đề xuất tạo một Issue mới trên kho lưu trữ GitHub của dự án và gắn nhãn (label) Change Request.
    - Thông tin bắt buộc: Nội dung Issue phải chỉ rõ: (1) Mô tả sự thay đổi; (2) Lý do cần thay đổi (Ví dụ: "Cần bổ sung AI chấm điểm bài thi có chứa công thức Toán học do giáo viên tổ Toán yêu cầu"); (3) Mức độ ưu tiên mong muốn.
    - Trạng thái ghi nhận: Proposed (Đề xuất).
- Bước 2: Phân tích ảnh hưởng (Impact Analysis)
    - Người thực hiện: Business Analyst (BA) và Quality Assurance (QA).
    - Hành động: Sử dụng Báo cáo độ bao phủ truy vết (Traceability Matrix) để đánh giá xem CR này sẽ phá vỡ hoặc ảnh hưởng tới bao nhiêu Tính năng (FEATs), Use Cases và Test Cases (ví dụ bộ dữ liệu huấn luyện AI) hiện tại. Sau đó, ước lượng nỗ lực (số giờ làm việc) và rủi ro nếu thực hiện CR này.
    - Trạng thái ghi nhận: Cập nhật comment phân tích trực tiếp vào GitHub Issue.
- Bước 3: Xem xét và Phê duyệt (Review & Approval)
    - Người thực hiện: Ban điều khiển thay đổi (Change Control Board - CCB).
    - Hành động: Tổ chức họp (hoặc thảo luận qua GitHub Discussions). Dựa trên báo cáo phân tích ảnh hưởng ở Bước 2, CCB sẽ ra quyết định.
    - Trạng thái ghi nhận: Project Manager (PM) sẽ đổi nhãn (label) của Issue thành Approved (Phê duyệt), Rejected (Từ chối) và nêu rõ lý do, hoặc Pending (Chờ làm rõ thêm từ phía nhà trường).
- Bước 4: Cập nhật và Thực thi (Update & Implement)
    - Người thực hiện: Toàn bộ nhóm dự án (Dev, AI Team, QA).
    - Hành động: Nếu CR được Approved, nhóm sẽ tiến hành cập nhật lại các tài liệu liên quan (Vision, Use Case, dữ liệu huấn luyện AI, Test Cases) thành phiên bản mới (Versioning). Sau đó, tạo Pull Request trên GitHub để tiến hành viết code/huấn luyện lại mô hình. Cuối cùng, đóng (Close) Issue khi công việc hoàn tất.

### 1.5.2. Ban điều khiển thay đổi (Change Control Board - CCB)

Ban điều khiển thay đổi (CCB) là nhóm chịu trách nhiệm cao nhất trong việc đánh giá, xem xét và đưa ra quyết định cuối cùng (Phê duyệt hoặc Từ chối) đối với mọi Yêu cầu thay đổi (CR) phát sinh trong dự án AI của FPT.

Để đảm bảo mọi sự thay đổi đều được đánh giá toàn diện, CCB bao gồm các vai trò chủ chốt sau:

- Thành phần và Trách nhiệm trong CCB:
    - Trưởng ban (CCB Chair) - Project Manager (PM): Chủ trì các phiên họp đánh giá CR; trực tiếp trao đổi với Ban giám hiệu THPT FPT để làm rõ mức độ ưu tiên của thay đổi. Là người có quyền quyết định cuối cùng và chịu trách nhiệm đổi trạng thái của CR trên GitHub Issues.
    - Thành viên đánh giá Nghiệp vụ & AI - Business Analyst (BA) / AI Lead: Đánh giá tác động của CR lên luồng nghiệp vụ giáo dục và kiến trúc AI. Cung cấp báo cáo ước lượng thời gian thu thập thêm dữ liệu (nếu có) và nỗ lực (Effort) cần thiết để huấn luyện lại mô hình (retrain model).
    - Thành viên đánh giá Chất lượng - Quality Assurance (QA): Phân tích tác động của CR lên Kịch bản (Scenarios) và bộ Test Cases. Đảm bảo Ma trận dấu vết không bị đứt gãy sau khi CR được thực thi.
- Cơ chế hoạt động của CCB:
    - Tần suất họp: CCB tổ chức họp định kỳ vào cuối mỗi tuần (Weekly meeting) để rà soát danh sách các CR. Đối với các CR mang tính cấp bách (Ví dụ: AI chấm sai điểm bài thi học kỳ do lỗi nhận diện), CCB sẽ họp đột xuất ngay lập tức.
    - Hình thức thảo luận: Các cuộc thảo luận được thực hiện minh bạch thông qua tính năng GitHub Discussions và bình luận trực tiếp trên GitHub Issues.
    - Nguyên tắc ra quyết định: Ưu tiên nguyên tắc đồng thuận. Trong trường hợp có ý kiến trái chiều (Ví dụ: Giáo viên muốn thêm tính năng nhưng thời gian train AI không cho phép), Trưởng ban (PM) sẽ là người ra quyết định cuối cùng dựa trên việc cân đối giữa Tài nguyên và Rủi ro dự án.

### 1.5.3. Các mốc bàn giao dự án (Project Baselines)

Mốc bàn giao (Baseline) là một trạng thái đã được thẩm định và phê duyệt của kho yêu cầu tại một thời điểm cụ thể. Việc thiết lập các mốc Baseline giúp nhóm dự án FPT kiểm soát chặt chẽ "độ trườn phạm vi" (Scope Creep). Mỗi khi đạt một mốc Baseline, PM sẽ tạo một thẻ Tag/Release trên GitHub để lưu trữ phiên bản tài liệu.

- Baseline 1: Mốc Tầm nhìn và Nhu cầu (Kết thúc pha Khởi tạo - Inception)
    - Thời điểm: Tuần 2 của dự án.
    - Thành phẩm được đóng băng: Danh sách các Stakeholders (BGH, GV, HS) và Tập yêu cầu thô (NEEDs) đã được thống nhất.
    - Điều kiện phê duyệt: BGH THPT FPT xác nhận bài toán và Ban CCB phê duyệt Kế hoạch quản lý yêu cầu (RMP). Bất kỳ NEED nào phát sinh sau mốc này đều phải tạo Change Request.
- Baseline 2: Mốc Kiến trúc Yêu cầu (Kết thúc pha Chi tiết hóa - Elaboration)
    - Thời điểm: Tuần 6 của dự án.
    - Thành phẩm được đóng băng: Tài liệu Tầm nhìn dự án (FEATs), Đặc tả Use Cases cốt lõi (ví dụ: AI Grading, Sinh đề thi, AI Tutor) và Giao diện mô phỏng UI/UX.
    - Điều kiện phê duyệt: BA hoàn tất tài liệu. QA xác nhận Ma trận dấu vết từ NEEDs -> FEATs -> UCs không bị đứt gãy. Đại diện nhà trường phê duyệt luồng nghiệp vụ. Mọi thay đổi thuật toán cốt lõi sau mốc này là CR mức độ phức tạp (High Effort).
- Baseline 3: Mốc Hoàn thiện Kiểm thử (Kết thúc pha Xây dựng - Construction)
    - Thời điểm: Tuần 8 của dự án.
    - Thành phẩm được đóng băng: Yêu cầu bổ sung (SUPLs về độ chính xác AI, hiệu năng), Kịch bản (Scenarios), Test Cases và Bảng chú giải thuật ngữ giáo dục/AI.
    - Điều kiện phê duyệt: QA đảm bảo 100% độ bao phủ kiểm thử (Test Coverage). Sau mốc này, kho yêu cầu sẵn sàng cho sản xuất để tiến hành nghiệm thu (UAT) với giáo viên.

### 1.5.4. Hoạt động của quy trình quản lý thay đổi (CRM Process Activity)

Luồng công việc quản lý thay đổi yêu cầu (CRM Workflow) cho dự án AI FPT được thiết kế theo dạng máy trạng thái (state machine). Một Yêu cầu thay đổi (CR) sinh ra dưới dạng GitHub Issue sẽ trải qua 6 hoạt động:

- Hoạt động 1: Ghi nhận CR (Log CR)
    - Mô tả: Giáo viên phát hiện AI chấm chưa chuẩn ở một dạng bài mới hoặc BGH yêu cầu thêm tính năng phân tích. Một Issue được tạo trên GitHub.
    - Trạng thái CR: New (Mới) / Proposed (Đề xuất).
- Hoạt động 2: Phân tích CR (Analyze CR)
    - Mô tả: BA và QA tiếp nhận Issue, sử dụng Ma trận dấu vết để xác định các luồng nghiệp vụ và mô hình AI bị ảnh hưởng.
    - Trạng thái CR: Chuyển sang Under Review (Đang đánh giá).

Hoạt động 3: Quyết định CR (Decide CR)

- - Mô tả: Ban CCB họp bàn và đưa ra quyết định dựa trên báo cáo phân tích rủi ro/thời gian.
    - Trạng thái CR: Phân nhánh thành Approved (Đã phê duyệt) để đi tiếp, hoặc Rejected (Từ chối).

Hoạt động 4: Áp dụng CR (Implement CR)

- - Mô tả: Nhóm tiến hành checkout nhánh code mới, bổ sung dữ liệu huấn luyện, sửa đổi tài liệu và điều chỉnh Ma trận dấu vết.
    - Trạng thái CR: Chuyển sang In Development (Đang thực thi).

Hoạt động 5: Thẩm định CR (Verify CR)

Mô tả: QA chạy lại các bộ Test Cases cũ (Regression Test) để đảm bảo mô hình AI mới không làm sai lệch kết quả của các dạng bài cũ đã chấm đúng.

- - Trạng thái CR: Chuyển sang Ready for Verification (Chờ thẩm định) -> Verified (Đã kiểm chứng).

Hoạt động 6: Đóng CR (Close CR)

- - Mô tả: Trưởng ban CCB xác nhận. Merge (hợp nhất) thay đổi thuật toán/code vào nhánh chính (Main branch).
    - Trạng thái CR: Closed (Đóng).

1.6. Các mốc thời gian (Milestones)

Phần này xác định lịch trình chi tiết và các mốc kiểm duyệt (Baselines) cho dự án Hệ thống AI THPT FPT, được chia thành 4 giai đoạn tuân thủ theo tiến trình phát triển phần mềm. Dự án dự kiến kéo dài trong 10 tuần.

### 1.6.1. Giai đoạn Khởi tạo (Inception)

Giai đoạn Khởi tạo diễn ra từ Tuần 1 đến Tuần 2 của dự án. Trọng tâm của giai đoạn này là xác định bài toán giáo dục của FPT (trả lời câu hỏi WHY và WHAT), nhận diện các bên liên quan và thiết lập môi trường quản lý yêu cầu.

- a. Tiêu chí đánh giá (Evaluation Criteria) Để kết thúc giai đoạn Inception, Ban điều khiển (CCB) và BGH THPT FPT phải họp và xác nhận đạt được các tiêu chí sau:
    - BGH nhà trường đã đồng thuận với phạm vi ứng dụng AI và mục tiêu chuyển đổi số chưa?
    - Đã xác định đầy đủ và chính xác danh sách các bên liên quan (BGH, GV các tổ bộ môn, Học sinh, IT FPT) chưa?
    - Tài liệu Kế hoạch quản lý yêu cầu (RMP) đã được lập xong và được PM phê duyệt chưa?
    - Môi trường quản lý yêu cầu và lưu trữ dữ liệu (GitHub, Drive bảo mật) đã được thiết lập và phân quyền chưa?

b. Các công việc và Thành phẩm (Tasks and Artifacts)

#### Bảng 1.1dưới liệt kê các công việc cần thực hiện và các tài liệu (thành phẩm) sinh ra trong giai đoạn Khởi tạo:

|     |     |     |     |
| --- | --- | --- | --- |
| **Công việc / Thành phẩm (Tasks/Artifacts)** | **Mô tả chi tiết (Description)** | **Thời gian thực hiện** | **Người phụ trách (PIC)** |
| **Phát biểu bài toán & Mục tiêu dự án** | Phân tích tính cấp thiết (WHY) và xác định mục tiêu tổng quát, mục tiêu cụ thể (WHAT) của hệ thống AI trong giáo dục tại THPT FPT | Tuần 1 | Đồng Văn Hòa (PM) |
| **Định danh Stakeholders** | Xác định các bên liên quan: Ban giám hiệu, Giáo viên, Học sinh, Phụ huynh | Tuần 1 | Nguyễn Tuấn Long (BA) |
| **Thu thập yêu cầu (NEEDs)** | Khảo sát, phỏng vấn để thu thập nhu cầu: chấm bài AI, chatbot, AI tutor, phân tích học tập | Tuần 1 | Nguyễn Tuấn Long (BA) |
| **Xây dựng Vision Document** | Xác định phạm vi hệ thống, danh sách tính năng (FEATs), mô tả hệ thống AI | Tuần 2 | Phạm Xuân Hưng (BA/Specifier) |
| **Xây dựng tài liệu RMP** | Lập kế hoạch quản lý yêu cầu (RMP), quy trình CRM, vai trò các thành viên | Tuần 2 | Đồng Văn Hòa (PM) |
| **Thiết lập GitHub & Workspace** | Tạo repository, quản lý yêu cầu bằng Issues, Labels (NEEDs, FEATs, UC...) | Tuần 2 | Nịnh Thanh Khương (Config Manager) |
| **Thiết kế sơ đồ Use Case / BPMN** | Mô hình hóa hệ thống AI (Use Case Diagram, quy trình học tập) | Tuần 2 | Trương Việt Hải (Designer) |
| **Xây dựng Mockup giao diện** | Thiết kế giao diện: chatbot, AI tutor, dashboard giáo viên | Tuần 2 | Trương Việt Hải (UI/UX) |
| **Xây dựng Glossary** | Định nghĩa thuật ngữ: AI Tutor, Chatbot, Learning Analytics | Tuần 2 | Trần Việt Anh (QA) |
| **Kiểm tra & rà soát yêu cầu** | Đánh giá tính đầy đủ, nhất quán của yêu cầu, chuẩn bị cho baseline | Tuần 2 | Trần Việt Anh (QA) |

### 1.6.2. Giai đoạn Chi tiết hóa (Elaboration)

Giai đoạn Chi tiết hóa diễn ra từ Tuần 3 đến Tuần 6 của dự án. Trọng tâm của giai đoạn này là thu thập yêu cầu chi tiết, phân tích quy trình nghiệp vụ hiện tại của THPT FPT, và xây dựng nền tảng kiến trúc yêu cầu thông qua Tài liệu Tầm nhìn, Use Cases và giao diện mô phỏng UI/UX.

- **a. Tiêu chí đánh giá (Evaluation Criteria)** Để kết thúc giai đoạn Elaboration và thiết lập Baseline 2, Ban điều khiển (CCB) phải xác nhận đạt được các tiêu chí của mốc Kiến trúc vòng đời (Milestone LCA - Lifecycle Architecture) sau:
    - Tập yêu cầu thô (NEEDs) đã được thu thập đầy đủ từ Ban giám hiệu, Giáo viên, Học sinh và có nguồn gốc rõ ràng chưa?
    - Quy trình nghiệp vụ giáo dục (BPMN) và Tài liệu Tầm nhìn dự án (FEATs) đã được Ban giám hiệu THPT FPT phê duyệt chưa?
    - Các Use Cases cốt lõi (như: AI chấm bài tự động, Trợ giảng ảo Chatbot, Phân tích dữ liệu học tập) đã được đặc tả chi tiết luồng sự kiện chưa?
    - Giao diện mô phỏng (Mockup UI) trên Figma (màn hình Dashboard cho giáo viên, giao diện hỏi đáp AI cho học sinh) đã được đánh giá tính khả thi chưa?
    - Ma trận dấu vết liên kết giữa NEEDs -> FEATs -> UCs đã được QA thiết lập hợp lệ, không bị đứt gãy trên hệ thống chưa?
- **b. Các công việc và Thành phẩm (Tasks and Artifacts)**

#### Bảng1.2 dưới đây liệt kê các công việc cần thực hiện và các tài liệu sinh ra trong giai đoạn Chi tiết hóa:

|     |     |     |     |
| --- | --- | --- | --- |
| **Công việc / Thành phẩm (Tasks/Artifacts)** | **Mô tả chi tiết (Description)** | **Thời gian thực hiện** | **Người phụ trách (PIC)** |
| **Tài liệu Yêu cầu Stakeholders (NEEDs)** | Lập kế hoạch khảo sát, phỏng vấn giáo viên, học sinh; tổng hợp NEEDs (AI chấm bài, chatbot, AI tutor…), gán mã STRQ-xx | Tuần 3 | Nguyễn Tuấn Long (BA) |
| **Quy trình nghiệp vụ (BPMN)** | Xây dựng quy trình học tập và giảng dạy có tích hợp AI (chấm bài, hỗ trợ học tập), mô hình hóa bằng BPMN | Tuần 4 | Phạm Xuân Hưng (BA) |
| **Tài liệu Tầm nhìn (Vision Document)** | Phân tích NEEDs → FEATs, xác định phạm vi hệ thống AI, danh sách tính năng chính | Tuần 4 | Đồng Văn Hòa (PM) |
| **Đặc tả Use Cases** | Viết Use Case cho các chức năng: chấm bài, sinh đề, chatbot, AI tutor, phân tích học tập | Tuần 5 | Phạm Xuân Hưng (Specifier) |
| **Thiết kế Mockup UI** | Thiết kế giao diện hệ thống: chatbot, dashboard giáo viên, màn hình học sinh | Tuần 5 - Tuần 6 | Trương Việt Hải (UI/UX) |
| **Xây dựng Supplementary Requirements** | Đặc tả yêu cầu phi chức năng: hiệu năng, bảo mật dữ liệu học sinh, độ chính xác AI | Tuần 6 | Nguyễn Tuấn Long (BA) |
| **Xây dựng Traceability Matrix** | Liên kết NEED → FEAT → UC → TC, đảm bảo không thiếu yêu cầu | Tuần 6 | Trần Việt Anh (QA) |
| **Rà soát và kiểm tra yêu cầu (Review)** | Kiểm tra tính đầy đủ, nhất quán, loại bỏ xung đột yêu cầu | Tuần 6 | Trần Việt Anh (QA) |
| **Thiết lập Baseline 2** | Đóng băng FEATs, Use Cases, Mockup; chuẩn bị chuyển sang giai đoạn tiếp theo | Tuần 6 | Đồng Văn Hòa (PM) |

### 1.6.3. Giai đoạn Xây dựng (Construction)

Giai đoạn Xây dựng diễn ra từ Tuần 7 đến Tuần 8 của dự án. Trọng tâm của giai đoạn này là chuyển giao kiến trúc thành sản phẩm (hệ thống AI) có thể hoạt động được, đồng thời hoàn thiện các tầng cuối cùng của Kim tự tháp yêu cầu bao gồm Yêu cầu bổ sung (SUPLs), Kịch bản (Scenarios) và Trường hợp kiểm thử (Test Cases).

**a. Tiêu chí đánh giá (Evaluation Criteria)** Để kết thúc giai đoạn Construction và thiết lập Baseline 3, Ban điều khiển (CCB) phải họp đánh giá và xác nhận đạt được các tiêu chí của Mốc khả năng vận hành ban đầu (Milestone IOC - Initial Operational Capability):

- - Tài liệu Yêu cầu bổ sung (SUPLs - ví dụ: hiệu năng xử lý của AI, độ bảo mật dữ liệu học sinh) và Bảng chú giải thuật ngữ (Glossary) đã được định nghĩa đầy đủ chưa?
    - Các Use Cases đã được phân rã thành các Kịch bản (Scenarios) chi tiết (bao gồm cả luồng AI xử lý thành công và các ngoại lệ như ảnh bài thi bị mờ, lỗi hệ thống) chưa?
    - Đã sinh đủ các Trường hợp kiểm thử (Test Cases) từ Scenarios và SUPLs chưa? Tỷ lệ bao phủ kiểm thử (Test Coverage) có đạt 100% không?
    - 6 loại Ma trận dấu vết (từ tầng đỉnh NEEDS xuống tận đáy Test Cases) đã được thiết lập đầy đủ trên Excel và cập nhật liên kết chéo trên GitHub chưa?
    - Sản phẩm phần mềm (các module AI Grading, AI Tutor, Dashboard) hoặc các luồng giao diện Mockup nâng cao đã sẵn sàng để nghiệm thu thực tế với giáo viên và học sinh chưa?

**b. Các công việc và Thành phẩm (Tasks and Artifacts)**

#### Bảng1.3 dưới đây liệt kê các công việc cần thực hiện và các tài liệu sinh ra trong giai đoạn Xây dựng:

|     |     |     |     |
| --- | --- | --- | --- |
| **Nội dung đào tạo** | **Thời điểm** | **Hình thức** | **Người phụ trách** |
| Cấu trúc RMP theo IBM/RUP | Tuần 1 | Họp nhóm trực tiếp/online, giới thiệu lý thuyết và áp dụng vào dự án AI giáo dục | Đồng Văn Hòa (PM) |
| Sử dụng GitHub để quản lý yêu cầu | Tuần 2 | Thực hành tạo repository, Issues, Labels (NEEDs, FEATs, UC) | Nịnh Thanh Khương (Config Manager) |
| Lập ma trận dấu vết và gán thuộc tính | Tuần 3 | Thực hành trên Excel và GitHub, liên kết NEED → FEAT → UC → TC | Trần Việt Anh (QA) |
| Vẽ BPMN và thiết kế Mockup | Tuần 4 - Tuần 5 | Hướng dẫn Draw.io, Figma; thực hành mô hình hóa hệ thống AI | Trương Việt Hải (UI/UX) |
| Viết Use Case và Vision Document | Tuần 5 | Hướng dẫn viết Use Case, đặc tả chức năng hệ thống | Phạm Xuân Hưng (BA/Specifier) |
| Quy trình CRM và quản lý phiên bản | Tuần 8 - Tuần 9 | Họp nhóm, mô phỏng xử lý Change Request trên GitHub | Đồng Văn Hòa (PM) |

1.6.4. Giai đoạn Chuyển giao (Transition)

Giai đoạn Chuyển giao diễn ra từ Tuần 9 đến Tuần 10 của dự án. Trọng tâm của giai đoạn này là đưa Hệ thống AI giáo dục FPT từ trạng thái “sẵn sàng cho sản xuất” sang trạng thái “sẵn sàng nghiệm thu và bàn giao”, thông qua hoạt động demo, kiểm tra chấp nhận của nhà trường (UAT), rà soát lần cuối tính đầy đủ của kho yêu cầu và hoàn thiện hồ sơ phát hành.

a. Tiêu chí đánh giá (Evaluation Criteria) Để kết thúc giai đoạn Transition và khép lại vòng đời quản lý yêu cầu của dự án, Ban điều khiển thay đổi (CCB) cùng đại diện Trường THPT FPT cần xác nhận đạt được các tiêu chí của mốc phát hành sản phẩm như sau:

- - Hệ thống mô phỏng/demo đã trình diễn được đầy đủ các luồng nghiệp vụ cốt lõi như: AI chấm bài tự động, tương tác với Trợ giảng ảo (AI Tutor), xem Dashboard phân tích học tập và các chức năng quản trị cho giáo viên.
    - Tất cả các yêu cầu đã được phê duyệt trong Baseline 3 đều đã có trạng thái Verified / Ready, không còn yêu cầu “mồ côi” trong các ma trận dấu vết.
    - Toàn bộ các Trường hợp kiểm thử (Test Cases) quan trọng đã được thực thi, kết quả đạt yêu cầu và không còn lỗi nghiêm trọng ảnh hưởng đến tính chính xác của thuật toán AI hay nghiệp vụ chính của hệ thống.
    - Đại diện nhà trường đã xem xét, phản hồi và chấp thuận kết quả demo; các góp ý phát sinh được ghi nhận dưới dạng Change Request cho phiên bản tiếp theo thay vì làm thay đổi phạm vi phát hành hiện tại.
    - Bộ tài liệu cuối cùng của dự án bao gồm: RMP, Stakeholder Requests, Vision Document, Use Case Specification, Supplementary Requirements, Glossary, Scenarios, Test Cases và các Ma trận dấu vết đã được hoàn thiện, đồng bộ phiên bản và sẵn sàng lưu trữ.

b. Các công việc và Thành phẩm (Tasks and Artifacts)

#### Bảng 1.4 dưới đây liệt kê các công việc cần thực hiện và các tài liệu/thành phẩm sinh ra trong giai đoạn Chuyển giao:

<div class="joplin-table-wrapper"><table><tbody><tr><td><h4>Công việc / Thành phẩm (Tasks/Artifacts)</h4></td><td><h4>Mô tả chi tiết (Description)</h4></td><td><h4>Thời gian thực hiện</h4></td><td><h4>Người phụ trách (PIC)</h4></td></tr><tr><td><h4>Demo hệ thống và quy trình quản lý yêu cầu</h4></td><td><h4>Trình diễn hệ thống AI giáo dục (mô phỏng các chức năng như chấm bài AI, trợ giảng ảo, phân tích học tập); đồng thời demo thao tác quản lý yêu cầu trên GitHub (Issue, Traceability, Change Request).</h4></td><td><h4>Tuần 9</h4></td><td><h4>Cả nhóm</h4></td></tr><tr><td><h4>Kiểm thử nghiệm thu (Acceptance Review)</h4></td><td><h4>Phối hợp với đại diện nhà trường THPT FPT kiểm tra các Test Cases quan trọng; đối chiếu với Use Cases, SUPLs và kết quả mong đợi để đánh giá mức độ đáp ứng hệ thống AI.</h4></td><td><h4>Tuần 9</h4></td><td><h4>Hoàng Đức Lương (QA)</h4></td></tr><tr><td><h4>Rà soát và đóng băng phiên bản tài liệu</h4></td><td><h4>Kiểm tra sự nhất quán giữa các tài liệu (RMP, Vision, Use Case, Supplementary, Mockup, GitHub); chốt phiên bản cuối cùng của kho yêu cầu.</h4></td><td><h4>Tuần 10</h4></td><td><h4>Phạm Xuân Hưng (PM)</h4></td></tr><tr><td><h4>Ghi nhận yêu cầu cải tiến sau nghiệm thu</h4></td><td><h4>Tổng hợp các góp ý từ phía nhà trường; đề xuất nâng cấp hệ thống AI (cải thiện mô hình dự đoán, mở rộng chatbot, cá nhân hóa sâu hơn).</h4></td><td><h4>Tuần 10</h4></td><td><h4>Trần Việt Anh (BA)</h4></td></tr><tr><td><h4>Hoàn thiện hồ sơ bàn giao dự án</h4></td><td><h4>Tổng hợp toàn bộ tài liệu, báo cáo, hình ảnh minh chứng, link GitHub, link Figma và nộp sản phẩm cuối kỳ.</h4></td><td><h4>Tuần 10</h4></td><td><h4>Cả nhóm</h4></td></tr></tbody></table></div>

c. Kết quả đầu ra của giai đoạn Transition

Kết thúc giai đoạn này, dự án đạt được các kết quả chính sau:

- Hệ thống AI giáo dục FPT đã được nghiệm thu ở mức mô phỏng/phân tích yêu cầu.
- Kho yêu cầu của dự án được chốt phiên bản cuối cùng, có thể truy vết đầy đủ từ NEEDs đến Test Cases (đặc biệt là các test case cho thuật toán AI).
- Các thay đổi phát sinh sau nghiệm thu không làm ảnh hưởng release hiện tại mà được chuyển thành cơ sở cho Release tiếp theo.
- Nhóm dự án hoàn tất toàn bộ hồ sơ học phần, sẵn sàng cho việc báo cáo tổng kết và bảo vệ.

## 1.7. Đào tạo và Nguồn tài nguyên (Training and Resources)

Mục này mô tả các nguồn lực cần thiết để nhóm dự án triển khai hiệu quả hoạt động phân tích và quản lý yêu cầu cho dự án “Phát triển Hệ thống ứng dụng AI trong giáo dục, đào tạo cho Trường THPT FPT”, đồng thời xác định kế hoạch đào tạo ngắn hạn nhằm đảm bảo mọi thành viên sử dụng thống nhất các công cụ, biểu mẫu và quy trình đã được quy định trong bản RMP này.

### 1.7.1. Nguồn tài nguyên (Resources)

Để triển khai đầy đủ các hoạt động kỹ nghệ yêu cầu, dự án sử dụng các nhóm tài nguyên chính sau đây:

a. Nguồn nhân sự: Dự án được thực hiện bởi nhóm 6 thành viên, mỗi người đảm nhiệm một vai trò chuyên biệt để tối ưu hóa chất lượng đặc tả và quản lý:

- Phạm Xuân Hưng: Project Manager/Team Leader. Phụ trách lập kế hoạch dự án, điều phối tiến độ, chủ trì các buổi họp và quản lý thay đổi (CCB).
- Trần Việt Anh: Business Analyst (BA). Phụ trách thu thập yêu cầu (NEEDs), phân tích nghiệp vụ, xây dựng Vision Document và chuyển đổi từ NEEDs sang FEATs.
- Đồng Văn Hòa: Requirements Specifier. Phụ trách viết tài liệu Use Case Specification, đặc tả chức năng chi tiết và xây dựng các luồng nghiệp vụ hệ thống.
- Ninh Thanh Khương: UI/UX Designer. Phụ trách thiết kế giao diện (Mockup/Prototype), hỗ trợ mô hình hóa BPMN và đảm bảo tính khả dụng của hệ thống.
- Nguyễn Tuấn Long: Quality Assurance (QA). Phụ trách kiểm tra chất lượng tập yêu cầu, xây dựng Test Cases và đảm bảo tính truy vết (Traceability).
- Trương Việt Hải: Configuration Manager/Developer. Quản lý kho lưu trữ GitHub, version tài liệu và đánh giá tính khả thi kỹ thuật của các module AI.

Ngoài ra, các đối tượng bên ngoài như Ban giám hiệu Trường THPT FPT, Giáo viên và Học sinh đóng vai trò cung cấp thông tin khảo sát và thẩm định yêu cầu.

b. Nguồn tài nguyên phần mềm và công cụ:

- GitHub: Công cụ chính để quản lý yêu cầu tự động (Issues, Labels, Projects) và lưu trữ mã nguồn/tài liệu.
- Microsoft Office (Word, Excel): Soạn thảo tài liệu chuẩn (RMP, Vision, Use Case) và lập ma trận dấu vết.
- Draw.io / Bizagi: Mô hình hóa quy trình nghiệp vụ giáo dục (BPMN).
- Figma: Thiết kế giao diện Dashboard quản lý và Chatbot AI.
- Google Drive & Meet: Lưu trữ đám mây, chia sẻ tệp tin và họp trực tuyến.

c. Cơ sở hạ tầng phần cứng: Sử dụng máy tính cá nhân của 6 thành viên với kết nối Internet ổn định. Môi trường làm việc linh hoạt, kết hợp giữa thảo luận trực tiếp tại trường và làm việc nhóm trực tuyến qua các nền tảng Cloud.

d. Thời lượng lao động dự kiến: Với 10 tuần triển khai, mỗi thành viên dành trung bình 6-10 giờ/tuần. Tổng nỗ lực dự kiến đạt khoảng 400 - 500 giờ công cho toàn nhóm để hoàn thiện từ khâu khảo sát đến khi hoàn tất bộ hồ sơ đặc tả yêu cầu và demo.

### 1.7.2. Kế hoạch đào tạo (Training Plan)

Nhóm tổ chức đào tạo nội bộ nhằm thống nhất quy trình vận hành và sử dụng công cụ.

a. Mục tiêu đào tạo:

- Thống nhất cấu trúc tài liệu RMP và mô hình kim tự tháp yêu cầu (NEED -> FEAT -> UC).
- Thành thạo việc gán mã định danh, thuộc tính và truy vết tự động trên GitHub.
- Chuẩn hóa quy trình tiếp nhận và phê duyệt thay đổi (Change Request).

b. Nội dung đào tạo:

1.  Quy trình và cấu trúc RMP: Do Phạm Xuân Hưng hướng dẫn.
2.  Kỹ thuật đặc tả và Vision Document: Do Trần Việt Anh và Đồng Văn Hòa chia sẻ.
3.  Quản lý yêu cầu trên GitHub: Do Trương Việt Hải hướng dẫn cách tạo Issue, Tag và quản lý Version.
4.  Thiết kế Mockup và BPMN: Do Ninh Thanh Khương hướng dẫn sử dụng Figma và Draw.io.
5.  Kiểm soát chất lượng và Ma trận truy vết: Do Nguyễn Tuấn Long hướng dẫn lập bảng Excel Traceability.

c. Hình thức và thời điểm đào tạo: Tổ chức các buổi Workshop ngắn (30-60 phút) vào đầu mỗi giai đoạn (Inception, Elaboration) thông qua chia sẻ màn hình online và thực hành trực tiếp trên kho GitHub của nhóm.

|     |     |     |     |
| --- | --- | --- | --- |
| Nội dung đào tạo | Thời điểm | Hình thức | Người phụ trách |
| Cấu trúc RMP theo IBM/RUP | Tuần 1 | Họp nhóm trực tiếp/online | Phạm Xuân Hưng |
| Sử dụng GitHub để quản lý yêu cầu | Tuần 2 | Thực hành trên repository | Trương Việt Hải |
| Lập ma trận dấu vết và gán thuộc tính | Tuần 3 | Thực hành Excel + GitHub | Nịnh Thanh Khương |
| Vẽ BPMN và thiết kế Mockup | Tuần 4 - Tuần 5 | Hướng dẫn công cụ + thực hành | Nguyễn Tuấn Long |
| Quy trình CRM và quản lý phiên bản | Tuần 8 - Tuần 9 | Họp nhóm + mô phỏng tình huống | Đồng Văn Hòa |

d. Kết quả mong đợi sau đào tạo

Sau khi hoàn thành các hoạt động đào tạo trên, nhóm dự án phải đạt được các kết quả sau:

- 100% thành viên hiểu rõ vai trò, trách nhiệm và luồng công việc của mình trong tiến trình quản lý yêu cầu.
- Tất cả thành viên có thể sử dụng được GitHub để cập nhật yêu cầu, đổi trạng thái, gắn nhãn và theo dõi lịch sử thay đổi của các tính năng AI, luồng nghiệp vụ.
- QA có khả năng duy trì ma trận dấu vết xuyên suốt, bảo đảm không có yêu cầu nào bị mất nguồn gốc hoặc không có kiểm thử tương ứng (đặc biệt là các bộ test case cho mô hình AI).
- BA và PM phối hợp được trong việc tinh chế yêu cầu, cập nhật tài liệu và kiểm soát các Change Request phát sinh từ phía nhà trường hoặc giáo viên.
- Toàn bộ nhóm thống nhất cách đặt tên, mã hóa, phân loại và bàn giao tài liệu theo đúng mẫu đã lựa chọn.

### 1.7.3. Kết luận của phần Đào tạo và Tài nguyên (Training and Resources)

Hội tụ đầy đủ các yếu tố từ cơ cấu tổ chức tinh gọn, bộ công cụ chuyên dụng đến kế hoạch đào tạo nội bộ rõ ràng, dự án Hệ thống AI FPT đáp ứng toàn diện các định hướng phát triển phần mềm chuẩn mực. Việc chủ động trang bị nguồn lực và kỹ năng từ sớm chính là “chìa khóa” giúp nhóm kiểm soát hiệu quả mọi sai sót trong quá trình lưu vết, đặc tả và huấn luyện AI. Đồng thời, đây cũng là cơ sở then chốt để bảo chứng cho tính đồng bộ của hệ thống tài liệu, sự chặt chẽ tại các mốc Baseline và khả năng thích ứng linh hoạt với các thay đổi cho đến khi nghiệm thu.

# CHƯƠNG 2: THU THẬP VÀ PHÂN TÍCH QUY TRÌNH NGHIỆP VỤ

## 2.1. Xác định Stakeholders

Theo cơ sở lý thuyết của kỹ nghệ yêu cầu, để xác định được "WHAT" (hệ thống cần làm gì) thì trước hết phải xác định "WHO" (hệ thống phục vụ ai), tức là các bên liên quan tham gia, tác động hoặc bị tác động bởi hệ thống cần xây dựng. Stakeholder được hiểu là các cá nhân hoặc tổ chức cung cấp yêu cầu cho phần mềm; trong đó hai nhóm phổ biến nhất là khách hàng (khách hàng mục tiêu/nhà đầu tư) và người dùng cuối (end users). Cũng theo lý thuyết, Actor (tác nhân) chỉ là tập con của Stakeholder, tức là không phải mọi Stakeholder đều trực tiếp thao tác với hệ thống, nhưng họ vẫn có quyền lợi, trách nhiệm hoặc ràng buộc đối với hệ thống đó.

Đối với dự án phát triển Hệ thống ứng dụng AI trong giáo dục, đào tạo cho Trường THPT FPT, việc xác định Stakeholder được thực hiện dựa trên ba căn cứ chính:

- Thứ nhất, dựa vào phát biểu bài toán và mục tiêu dự án: Hệ thống phải giải quyết đồng thời bài toán tự động hóa chấm thi (AI Grading), cá nhân hóa học tập qua trợ giảng ảo (AI Tutor), phân tích dữ liệu học tập thời gian thực và cảnh báo học vụ sớm.
- Thứ hai, dựa vào phạm vi quy trình nghiệp vụ BPMN: Các quy trình nghiệp vụ giáo dục đã được mô hình hóa cho thấy sự tương tác chặt chẽ giữa các bên như: Giáo viên, Học sinh, Hệ thống phân tích AI, Kho học liệu số và Hệ thống quản lý đào tạo hiện tại của FPT (như FAP/EduNext).
- Thứ ba, dựa vào kết quả khảo sát và danh sách NEEDs: Các yêu cầu thô đã được xác định trước đó cho thấy nguồn gốc đề xuất đến từ rất nhiều nhóm đối tượng khác nhau như: Ban giám hiệu, Giáo viên các tổ bộ môn, Học sinh, Phụ huynh học sinh và Bộ phận IT của nhà trường.

Từ các căn cứ trên, nhóm dự án xác định danh sách Stakeholder của dự án AI THPT FPT được chia thành các nhóm như sau:

2.1.1. Stakeholder

Stakeholder là các cá nhân, bộ phận nằm trong phạm vi tổ chức của Trường THPT FPT, trực tiếp tham gia vận hành, sử dụng hoặc ra quyết định đối với hệ thống AI giáo dục mới.

|     |     |     |
| --- | --- | --- |
| Stakeholder | Mô tả (Description) | Vai trò trong dự án |
| Ban Giám Hiệu (BGH) | Đại diện quản lý cấp cao của Trường THPT FPT | Đưa ra định hướng chiến lược, phê duyệt yêu cầu, nghiệm thu hệ thống |
| Giáo viên (GV) | Người trực tiếp giảng dạy và đánh giá học sinh | Cung cấp yêu cầu về chấm bài, tạo đề, trợ giảng AI; sử dụng hệ thống trong giảng dạy |
| Học sinh (HS) | Người học và sử dụng hệ thống AI | Sử dụng chatbot, làm bài, nhận gợi ý học tập; cung cấp phản hồi trải nghiệm |
| IT Team / Chuyên gia AI | Đội ngũ kỹ thuật và phát triển hệ thống | Thiết kế, triển khai hệ thống AI; tư vấn tính khả thi kỹ thuật và tối ưu thuật toán |
| Phụ huynh | Người theo dõi kết quả học tập của học sinh | Theo dõi tiến độ học tập, nhận báo cáo và cảnh báo từ hệ thống |

2.1.2 Nhận xét và kết luận về Stakeholder của dự án

Từ danh sách phân tích trên có thể thấy, dự án Hệ thống ứng dụng AI trong giáo dục tại THPT FPT có hệ thống stakeholder khá đa dạng, bao gồm nhóm ra quyết định (Ban giám hiệu), nhóm vận hành và sử dụng trực tiếp (Giáo viên, Học sinh), cùng các bộ phận hỗ trợ (IT, Phụ huynh) và hệ thống tích hợp liên quan. Mỗi nhóm stakeholder có mục tiêu và mối quan tâm khác nhau, nhưng đều tác động trực tiếp đến phạm vi yêu cầu của hệ thống.

Cụ thể, các nhu cầu thô (NEEDs) đã được xác định trong giai đoạn khảo sát ban đầu cho thấy mối liên hệ rất rõ ràng giữa stakeholder và yêu cầu:

- Nhóm Học sinh và Phụ huynh phát sinh các yêu cầu về quản lý tài khoản, xem điểm số tức thời, tương tác giải đáp thắc mắc với Trợ giảng ảo (AI Tutor) và theo dõi tiến trình học tập cá nhân.
- Nhóm Giáo viên và Tổ bộ môn phát sinh các yêu cầu cấp thiết về tự động hóa chấm bài (AI Grading), sinh mã đề thi tự động từ ngân hàng câu hỏi, quản lý lớp học và nhận cảnh báo sớm về học sinh yếu kém.
- Nhóm Ban giám hiệu (Quản lý cấp cao) phát sinh các yêu cầu về AI phân tích dữ liệu tổng thể, dashboard thống kê chất lượng đào tạo và báo cáo chiến lược thời gian thực.
- Nhóm Bộ phận IT FPT nhấn mạnh các yêu cầu phi chức năng (SUPLs) về bảo mật dữ liệu học sinh, hiệu năng xử lý của các mô hình AI và khả năng tích hợp trơn tru với các nền tảng đào tạo hiện có (như FAP, EduNext).

Việc xác định đầy đủ stakeholder ở giai đoạn này có ý nghĩa rất quan trọng. Đây là cơ sở để nhóm dự án lựa chọn đúng kỹ thuật thu thập yêu cầu cho từng đối tượng (ví dụ: phỏng vấn sâu với BGH, phát bảng hỏi cho học sinh), lập lịch biểu khảo sát hợp lý và bảo đảm rằng mọi NEED được xác định ở các bước tiếp theo đều có nguồn gốc rõ ràng. Đồng thời, đây cũng là điều kiện tiên quyết để thiết lập hệ thống truy vết yêu cầu (Traceability) một cách nhất quán trong toàn bộ tài liệu và vòng đời dự án.

## 2.2. Kỹ thuật thu thập và Lịch biểu khảo sát

Sau khi xác định được các stakeholder của dự án Hệ thống ứng dụng AI trong giáo dục tại THPT FPT, nhóm tiến hành lựa chọn kỹ thuật thu thập yêu cầu phù hợp với từng đối tượng nhằm bảo đảm thông tin thu được vừa đúng trọng tâm nghiệp vụ sư phạm, vừa có độ tin cậy cao. Việc lựa chọn kỹ thuật không thực hiện một cách đồng loạt, mà dựa trên đặc điểm của từng nhóm stakeholder, quy mô dự án, mức độ phân tán của đối tượng khảo sát và bản chất thông tin cần khai thác. Đây cũng là tinh thần chung của phần lý thuyết môn học: nắm vững ưu điểm, hạn chế của từng kỹ thuật để lựa chọn đúng công cụ tiếp cận, từ đó nâng cao Schất lượng của tập yêu cầu ban đầu.

### 2.2.1. Cơ sở lựa chọn kỹ thuật thu thập yêu cầu

Đối với dự án tại THPT FPT, hệ thống cần giải quyết đồng thời nhiều bài toán như tự động hóa chấm thi (AI Grading), cá nhân hóa học tập qua trợ giảng ảo (AI Tutor), phân tích dữ liệu học tập thời gian thực và quản lý học vụ. Vì vậy, tập stakeholder của dự án không chỉ gồm người dùng cuối (Học sinh, Giáo viên) mà còn bao gồm quản lý cấp cao (Ban giám hiệu) và các bên phụ trách hạ tầng kỹ thuật (Phòng IT). Trong bối cảnh đó, nhóm không thể chỉ sử dụng một kỹ thuật thu thập duy nhất, mà phải kết hợp nhiều kỹ thuật khác nhau để khai thác đầy đủ cả yêu cầu sư phạm, yêu cầu vận hành lẫn các ràng buộc về công nghệ AI.

Cụ thể, nhóm sử dụng các căn cứ sau để lựa chọn kỹ thuật thu thập:

- Với các stakeholder có vai trò ra quyết định, có tầm nhìn chiến lược và ảnh hưởng lớn đến phạm vi dự án (Ban giám hiệu, Trưởng các tổ bộ môn): Kỹ thuật phỏng vấn (Interview) được ưu tiên để làm rõ mục tiêu tổng quát, định hướng chuyển đổi số của nhà trường và các kỳ vọng cấp cao về mặt quản trị.
- Với nhóm người dùng đông, phân tán và có nhu cầu sử dụng đa dạng (Học sinh, Phụ huynh): Kỹ thuật bảng câu hỏi/khảo sát online (Questionnaire/Survey) phù hợp hơn vì cho phép thu thập dữ liệu trên diện rộng về thói quen học tập, những khó khăn khi tự học và mức độ mong muốn tương tác với AI hỗ trợ.
- Với các đối tượng đang trực tiếp vận hành nghiệp vụ giảng dạy (Giáo viên các bộ môn): Kỹ thuật quan sát thực tế (Observation) và hội thảo (Workshop) giúp nhóm phân tích nhìn thấy quy trình chấm điểm thủ công hiện tại, phát hiện các "điểm nghẽn" gây mất thời gian và thống nhất các tiêu chí (rubric) để huấn luyện mô hình AI chấm điểm.
- Với các thành phần liên quan đến kỹ thuật như hệ thống quản lý học tập hiện tại (EduNext, FAP), hạ tầng máy chủ nội bộ và các mô hình thuật toán: Kỹ thuật phân tích tài liệu (Document Analysis) được sử dụng để nghiên cứu tài liệu kỹ thuật, chuẩn kết nối API, khả năng đáp ứng tải và các ràng buộc nghiêm ngặt về bảo mật dữ liệu học đường.

Từ những căn cứ trên, nhóm xây dựng bảng lựa chọn kỹ thuật thu thập yêu cầu cho từng stakeholder như sau.

### 2.2.2. Bảng lựa chọn kỹ thuật thu thập yêu cầu theo Stakeholder

Bảng1.5 dưới đây tổng hợp các kỹ thuật thu thập đã được lựa chọn cho dự án Hệ thống AI THPT FPT, đồng thời nêu rõ lý do lựa chọn trong bối cảnh cụ thể của đề tài:

<div class="joplin-table-wrapper"><table><tbody><tr><td><p>Stakeholder</p></td><td><p>Kỹ thuật</p></td><td><p>Lý do lựa chọn &amp; Mục tiêu</p></td></tr><tr><td><p>Ban giám hiệu</p></td><td><p>Phỏng vấn sâu</p></td><td><p>Lý do: Cần khai thác thông tin chiến lược, ngân sách và các chỉ số KPI nhạy cảm.</p><p></p><p>Mục tiêu: Chốt quy chế đào tạo khi áp dụng AI.</p></td></tr><tr><td><p>Giáo viên</p></td><td><p>Workshop, phỏng vấn</p></td><td><p>Lý do:</p><ul><li>Workshop: Để thống nhất quy trình chấm thi / ra đề chung giữa các bộ môn (tránh mỗi người một kiểu).</li><li>Phỏng vấn: Để đi sâu vào khó khăn cụ thể (pain-points) của từng cá nhân khi sử dụng hệ thống cũ).</li></ul><p>Mục tiêu:</p><ul><li>Hiểu rõ quy trình nghiệp vụ gốc.</li></ul></td></tr><tr><td><p>Học sinh</p></td><td><p>Khảo sát</p></td><td><p>Lý do: Số lượng người dùng quá lớn, cần dữ liệu diện rộng để thống kế.</p><p></p><p>Mục tiêu: Dữ liệu định lượng để huấn luyện mô hình gợi ý.</p></td></tr><tr><td><p>IT Team</p></td><td><p>Phân tích tài liệu</p></td><td><p>Lý do: Cần xác định thông tin chính xác tuyệt đối về cấu trúc hệ thống cũ để tích hợp.</p><p></p><p>Mục tiêu: Sơ đồ ERD, API docs, Chính sách bảo mật.</p></td></tr><tr><td><p>Phụ huynh</p></td><td><p>Phỏng vấn</p></td><td><p>Lý do: Cần thu thập nhu cầu theo dõi kết quả học tập của học sinh.Mục tiêu: Xác định các yêu cầu về báo cáo học tập, thông báo kết quả của học sinh.</p></td></tr><tr><td><p>Chuyên gia AI</p></td><td><p>Workshop / Brainstorming</p></td><td><p>Lý do: Cần thảo luận kỹ thuật phức tạp giữa đội Dev và đội AI</p><p></p><p>Mục tiêu: Đánh giá tính khả thi của các tính năng.</p></td></tr></tbody></table></div>

### 2.2.3. Lịch biểu khảo sát

Sau khi lựa chọn kỹ thuật thu thập phù hợp, nhóm tiến hành lập lịch biểu khảo sát để bảo đảm tiến độ dự án và tránh sự chồng chéo giữa các hoạt động tiếp cận Stakeholder. Mục tiêu của kế hoạch này là thu thập đầy đủ thông tin để làm rõ các yêu cầu nghiệp vụ giáo dục cốt lõi, đồng thời tìm hiểu sâu nguyên nhân của những bất cập trong quy trình hiện tại như: thời gian chấm và trả bài thi chậm, khối lượng công việc thủ công của giáo viên quá tải, thiếu tính cá nhân hóa trong việc hướng dẫn học sinh tự học, và sự chậm trễ trong công tác theo dõi, cảnh báo học vụ.

Kế hoạch này cũng nhằm bảo đảm sự thống nhất tối đa về tầm nhìn giữa nhóm phát triển AI và các bên liên quan (Ban giám hiệu, Giáo viên, Bộ phận IT) trước khi chính thức chuyển sang giai đoạn tổng hợp và phân tích yêu cầu thô (NEEDs).

Dựa trên những cơ sở và kỹ thuật đã lựa chọn trước đó, lịch biểu khảo sát của dự án Hệ thống ứng dụng AI tại THPT FPT được xác định cụ thể như sau:

### 2.2.4. Quy trình tiến hành khảo sát

Để bảo đảm chất lượng dữ liệu thu thập được, nhóm triển khai khảo sát theo quy trình 3 bước chuẩn gồm: chuẩn bị, thực hiện và tổng hợp – phân tích. Cách làm này bám sát logic của môn học: kết quả khảo sát không dừng lại ở biên bản phỏng vấn hay mẫu trả lời khảo sát, mà phải tiếp tục được xử lý để chuyển hóa thành các yêu cầu dạng thô (NEEDs) trong tài liệu _Stakeholder Requests Document_.

- Bước 1: Chuẩn bị (Preparation) Nhóm nghiên cứu trước các quy chế đào tạo, quy trình kiểm tra đánh giá hiện tại của Trường THPT FPT; từ đó soạn bộ câu hỏi riêng cho từng nhóm (Ban giám hiệu, Tổ bộ môn Toán/Văn/Anh...) và thiết kế biểu mẫu khảo sát online dành cho học sinh, phụ huynh. Việc chuẩn bị trước bộ câu hỏi giúp cuộc khảo sát đi đúng trọng tâm, tránh thu thập thông tin lan man không phục vụ cho việc ứng dụng AI.
- Bước 2: Thực hiện (Execution) Nhóm tiến hành phỏng vấn trực tiếp, quan sát giờ học/chấm bài và phát khảo sát online theo đúng lịch biểu đã lập. Trong quá trình này, các buổi làm việc với Ban giám hiệu và giáo viên bộ môn được ghi âm, ghi chép và lưu lại để làm tư liệu phân tích. Đây là khâu thu thập dữ liệu đầu vào trực tiếp cho tài liệu Stakeholder Requests.
- Bước 3: Tổng hợp và phân tích (Analysis) Sau khi kết thúc khảo sát, nhóm tổng hợp kết quả từ bảng hỏi học sinh/phụ huynh, kết hợp với ghi chép phỏng vấn và kết quả quan sát để lọc bỏ thông tin nhiễu, làm rõ các ý kiến mập mờ và chuyển đổi thành danh sách yêu cầu dạng thô (NEEDs). Theo lý thuyết, toàn bộ kết quả này được lưu vào _Stakeholder Requests Document_ và là cơ sở trực tiếp cho bước phân tích yêu cầu ở các mục sau.

### 2.2.5. Nhận xét về hoạt động thu thập yêu cầu

Có thể thấy, việc lựa chọn kỹ thuật thu thập yêu cầu trong dự án Hệ thống AI THPT FPT không mang tính hình thức mà bám rất sát đặc điểm của từng nhóm stakeholder. Những thông tin mang tính chiến lược về quản trị giáo dục được khai thác qua phỏng vấn; những nội dung về thói quen học tập, nhu cầu tương tác được lấy qua bảng hỏi; những bất cập trong vận hành (chấm điểm chậm, quá tải) được phát hiện qua quan sát và hội thảo; còn các ràng buộc tích hợp, bảo mật dữ liệu học đường được làm rõ thông qua phân tích tài liệu kỹ thuật.

Cách tiếp cận này giúp nhóm bảo đảm rằng các NEEDs xác định ở phần sau đều có nguồn gốc rõ ràng và gắn với đúng stakeholder tương ứng. Mặt khác, lịch biểu khảo sát được xây dựng có tính bao phủ tốt đối với các nội dung trọng tâm của đề tài, bao gồm: quản trị chất lượng đào tạo, quy trình chấm thi tự động, sinh đề kiểm tra, dữ liệu học tập cá nhân hóa, trải nghiệm học sinh với AI và đánh giá khả năng tích hợp kỹ thuật. Đây là nền tảng quan trọng để nhóm chuyển sang bước mô hình hóa quy trình nghiệp vụ BPMN, phân tích quy trình và xác định các yêu cầu nghiệp vụ cốt lõi của hệ thống ở các mục tiếp theo.

## 2.3. Quy trình nghiệp vụ giáo dục chuẩn BPMN

Sau khi xác định được các stakeholder và hoàn thành hoạt động khảo sát yêu cầu, nhóm tiến hành mô hình hóa quy trình nghiệp vụ giảng dạy, kiểm tra đánh giá và hỗ trợ học tập của THPT FPT theo chuẩn BPMN (Business Process Model and Notation).

Việc xây dựng sơ đồ BPMN có ý nghĩa đặc biệt quan trọng trong dự án này, vì nó giúp trực quan hóa toàn bộ luồng nghiệp vụ từ phía Học sinh, Giáo viên đến các luồng xử lý tự động bên trong hệ thống AI (AI Grading, AI Tutor). Đồng thời, sơ đồ làm rõ những điểm giao tiếp giữa nền tảng AI mới với các hệ thống quản lý đào tạo hiện có (như FAP, EduNext) và kho học liệu số của trường. Mặt khác, sơ đồ BPMN còn là cơ sở trung gian để nhóm chuyển từ góc nhìn nghiệp vụ sư phạm sang bước phân tích và đặc tả yêu cầu phần mềm ở các chương tiếp theo.

### 2.3.1. Mục tiêu xây dựng sơ đồ BPMN

Nhóm tiến hành mô hình hóa quy trình nghiệp vụ giáo dục và hỗ trợ học tập của THPT FPT theo chuẩn BPMN nhằm đạt được bốn mục tiêu chính:

- Thứ nhất, chuẩn hóa toàn bộ các bước nghiệp vụ từ khi học sinh bắt đầu nộp bài tập, thi cử hoặc đặt câu hỏi tương tác, cho đến khi hệ thống AI hoàn tất việc chấm điểm, đưa ra phản hồi và đồng bộ dữ liệu học vụ.
- Thứ hai, làm rõ vai trò và điểm giao tiếp của từng bên tham gia (bao gồm: Học sinh, Hệ thống AI Core, Giáo viên bộ môn và Hệ thống đào tạo FAP/EduNext) thông qua mô hình phân làn (swimlane).
- Thứ ba, xác định chính xác các điểm rẽ nhánh quan trọng để xử lý các tình huống ngoại lệ trong quá trình vận hành AI như: file ảnh bài làm mờ/không hợp lệ, AI không chắc chắn về kết quả chấm (Confidence Score thấp đòi hỏi giáo viên can thiệp chấm thủ công), hoặc phát hiện học sinh có dấu hiệu hổng kiến thức cần rẽ nhánh gửi cảnh báo.
- Thứ tư, tạo nền tảng trực quan và logic làm đầu vào trực tiếp cho việc phân tích quy trình, từ đó xác định chính xác các yêu cầu nghiệp vụ cốt lõi và hệ thống luật nghiệp vụ (Business Rules) của dự án AI tại THPT FPT.

### 2.3.2. Phạm vi quy trình nghiệp vụ được mô hình hóa

Phạm vi của sơ đồ BPMN trong dự án này bao phủ hầu hết các hoạt động chính của Hệ thống ứng dụng AI trong giáo dục. Cụ thể, quy trình bắt đầu từ hoạt động học tập và kiểm tra của học sinh như: truy cập hệ thống, làm bài tập, nộp bài thi (tự luận/trắc nghiệm) và đặt câu hỏi trực tuyến. Tiếp theo là các bước hệ thống tiếp nhận file, tiền xử lý dữ liệu và kích hoạt AI Grading (chấm điểm tự động) hoặc AI Tutor (trợ giảng ảo). Sau đó, quy trình tiếp tục với việc giáo viên duyệt lại kết quả (với những bài AI không chắc chắn), đồng bộ điểm số sang hệ thống quản lý đào tạo (EduNext/FAP). Ngoài ra, sơ đồ còn thể hiện vai trò của AI trong việc phân tích dữ liệu học tập, phát hiện lỗ hổng kiến thức và xuất báo cáo cảnh báo học vụ cho Ban giám hiệu. Như vậy, đây là một quy trình end-to-end, phản ánh tương đối đầy đủ phạm vi bài toán đã nêu trong đề tài.

### 2.3.3. Các đối tượng tham gia trong sơ đồ BPMN

Trong sơ đồ BPMN, nhóm sử dụng mô hình swimlane để phân định rõ trách nhiệm giữa các bên tham gia, bảo đảm tính nhất quán với danh sách stakeholder ở mục 2.1. Sơ đồ gồm 5 lane chính:

- Học sinh: Là tác nhân khởi đầu quy trình, thực hiện thao tác làm bài, nộp bài tập/bài thi, xem điểm và đặt câu hỏi tương tác với trợ giảng ảo AI.
- Hệ thống AI FPT (Giao diện trung tâm): Là trung tâm điều phối, tiếp nhận thao tác của học sinh, phân loại bài tập, quản lý kho học liệu và luân chuyển dữ liệu đến các module xử lý.
- AI Core (AI Grading & AI Tutor): Tham gia trực tiếp vào khâu xử lý lõi. AI Grading chấm điểm và nhận xét bài làm; AI Tutor phân tích câu hỏi của học sinh để đưa ra gợi ý giải đáp. Đồng thời, module Analytics thực hiện phân tích hành vi học tập.
- Giáo viên bộ môn: Tham gia vào các điểm rẽ nhánh ngoại lệ (ví dụ: AI không đọc được chữ viết tay của học sinh hoặc độ tin cậy của kết quả chấm < 80%), giáo viên sẽ chấm thủ công hoặc tinh chỉnh lại điểm số.
- Hệ thống quản lý đào tạo (EduNext / FAP): Là điểm đến cuối cùng của dữ liệu, nhận API đồng bộ điểm số và kết quả đánh giá để lưu trữ vào hồ sơ học bạ điện tử của nhà trường.

### 2.3.4. Các ký hiệu BPMN được sử dụng trong mô hình

Để đảm bảo sơ đồ đúng chuẩn BPMN, nhóm sử dụng Start Event và End Event để biểu diễn điểm bắt đầu/kết thúc. Task (Activity) dùng cho các bước như: tải file bài làm, nhận diện chữ viết (OCR), chấm điểm, phản hồi câu hỏi, đồng bộ điểm. Exclusive Gateway (XOR) sử dụng tại các nút quyết định. Ngoài ra, Data Store biểu diễn kho dữ liệu học tập, cùng Sequence Flow thể hiện luồng điều khiển. Trong mô hình, các gateway giải quyết các câu hỏi rẽ nhánh then chốt như: _"File ảnh có hợp lệ/rõ nét không?"_, _"AI tự tin với kết quả chấm (Confidence Score > 80%)?"_, và _"Học sinh có hiểu bài không?"_.

### 2.3.5. Mô tả tóm tắt quy trình nghiệp vụ BPMN

Quy trình bắt đầu khi học sinh nộp bài thi/bài tập lên hệ thống. Đầu tiên, hệ thống kiểm tra định dạng và chất lượng file (đặc biệt là ảnh chụp bài tự luận). Nếu file hợp lệ, dữ liệu được đẩy sang AI Core. Module AI Grading sử dụng NLP và Computer Vision để nhận diện, chấm điểm và sinh ra lời nhận xét chi tiết. Nếu AI tự tin với kết quả (vượt ngưỡng Confidence Score), điểm số được tự động ghi nhận và đồng bộ sang hệ thống FAP/EduNext. Song song đó, trong quá trình tự học, nếu học sinh có thắc mắc, AI Tutor sẽ phân tích câu hỏi và đưa ra các gợi ý từng bước (step-by-step) thay vì đưa ngay đáp án. Kết thúc quy trình, toàn bộ dữ liệu điểm số và tần suất đặt câu hỏi được lưu vào Data Store để AI Analytics tổng hợp thành báo cáo năng lực, dự báo tỷ lệ trượt/đỗ cho giáo viên và BGH.

### 2.3.6. Các nhánh rẽ và tình huống ngoại lệ chính

Tại bước tiền xử lý, nếu ảnh chụp bài thi quá mờ, hệ thống yêu cầu học sinh chụp lại. Tại bước AI chấm điểm, nếu thuật toán phát hiện chữ viết tay quá khó đọc hoặc bài làm có cách giải khác thường (Confidence Score thấp), hệ thống rẽ nhánh sang "Chấm thủ công", tự động gửi thông báo (flag) để Giáo viên trực tiếp vào chấm. Tại nhánh AI Tutor, nếu AI phát hiện học sinh hỏi đi hỏi lại một vấn đề nhiều lần (dấu hiệu mất gốc), hệ thống sẽ rẽ nhánh để gửi cảnh báo sớm cho giáo viên chủ nhiệm.

### 2.3.7. Dữ liệu và các điểm tích hợp trong quy trình

Dữ liệu đầu vào bao gồm: file bài làm của học sinh, lịch sử học tập và ngân hàng rubric (đáp án chuẩn). Điểm tích hợp quan trọng nhất là API kết nối giữa Hệ thống AI mới và Hệ thống quản lý EduNext/FAP của trường để lấy danh sách lớp và trả về điểm số. Dữ liệu đầu ra là các Dashboard thống kê học vụ theo thời gian thực.

### 2.3.8. Đánh giá kết quả mô hình hóa BPMN

Từ sơ đồ có thể thấy, quy trình giáo dục số của THPT FPT được mô hình hóa hiện đại. Sơ đồ không chỉ bao quát luồng "Học – Thi – Chấm điểm – Trả kết quả", mà còn phân tách rõ vai trò hỗ trợ của AI và quyền quyết định cuối cùng của Giáo viên (Human-in-the-loop). Nhờ đó, sơ đồ BPMN trở thành nền tảng để nhóm xác định yêu cầu cốt lõi ở mục 2.4 và 2.5.

## 2.4. Phân tích quy trình và Yêu cầu nghiệp vụ cốt lõi

### 2.4.1. Mục tiêu của việc phân tích quy trình nghiệp vụ

Việc phân tích nhằm làm rõ luồng nghiệp vụ giáo dục từ khi học sinh làm bài đến khi điểm số được lưu trữ; nhận diện các điểm kiểm soát (kiểm tra file, duyệt điểm, cảnh báo học vụ); và rút ra các yêu cầu nghiệp vụ cốt lõi để làm cơ sở cho bước tinh chế yêu cầu.

### 2.4.2. Phân tích tổng thể luồng nghiệp vụ

Hệ thống không chỉ là một "website nộp bài", mà là một nền tảng tích hợp: nghiệp vụ khảo thí, nghiệp vụ sư phạm (trợ giảng) và nghiệp vụ quản trị dữ liệu. Đây là lý do dự án có ba trụ cột: AI Grading, AI Tutor và AI Analytics.

### 2.4.3. Phân tích các vai trò và điểm tương tác chính

Học sinh là trung tâm của tương tác. Hệ thống AI đóng vai trò như người trợ lý mẫn cán (chấm bài, giải đáp 24/7). Giáo viên từ vai trò "người chấm điểm thủ công" chuyển sang "người giám sát và ra quyết định chiến lược". Hệ thống phải hỗ trợ tương tác tức thời (real-time) và tích hợp API mượt mà.

### 2.4.4. Phân tích luồng nghiệp vụ chính (Happy Path)

Luồng chính: Học sinh nộp bài -> AI chấm thành công -> Điểm được cập nhật -> AI Tutor hỗ trợ hiệu quả -> Báo cáo học tập hiển thị số liệu tích cực. Điều này đòi hỏi hệ thống phải có các chức năng: Quản lý học liệu, Chấm điểm tự động, Chatbot giáo dục và Dashboard báo cáo.

2.4.5. Phân tích các nhánh ngoại lệ và điểm kiểm soát Các ngoại lệ như lỗi nhận diện ảnh, AI chấm sai hoặc học sinh có nguy cơ trượt môn đòi hỏi hệ thống phải có cơ chế Human-in-the-loop (giáo viên can thiệp) và cơ chế Cảnh báo sớm.

2.4.6. Xác định 7 yêu cầu nghiệp vụ cốt lõi cho hệ thống

- (1) Quản lý người dùng và Phân quyền: Quản lý tài khoản Học sinh, Giáo viên, BGH đồng bộ từ hệ thống của trường.
- (2) Quản lý Học liệu và Đề thi: Cho phép tải lên ngân hàng câu hỏi, rubric chấm điểm và sinh mã đề tự động.
- (3) AI Chấm bài tự động (AI Grading): Đọc, nhận diện và chấm điểm bài trắc nghiệm/tự luận, đưa ra nhận xét chi tiết.
- (4) AI Trợ giảng ảo (AI Tutor): Chatbot hỗ trợ giải đáp thắc mắc 24/7 theo phương pháp gợi mở.
- (5) Đồng bộ điểm số (Integration): Tích hợp API để đẩy điểm sang hệ thống EduNext/FAP.
- (6) Phân tích dữ liệu & Cảnh báo (AI Analytics): Thống kê chất lượng học tập, vẽ biểu đồ năng lực và cảnh báo học sinh yếu kém.
- (7) Bảo mật dữ liệu học đường: Tuân thủ các quy định về bảo vệ quyền riêng tư và điểm số của học sinh (chuẩn mã hóa).

2.4.7. Mối liên hệ giữa quy trình và danh sách NEEDs Các nhóm yêu cầu (1), (2), (3) liên hệ mật thiết với nhu cầu giảm tải công việc cho giáo viên; nhóm (4) liên hệ với nhu cầu tự học của học sinh; nhóm (6) phục vụ cho yêu cầu quản trị của BGH.

2.4.8. Kết luận phân tích quy trình 7 nhóm yêu cầu nghiệp vụ cốt lõi sẽ làm khung xương cho toàn bộ hệ thống AI FPT, tạo tiền đề để xác định luật nghiệp vụ và tinh chế thành Use Cases ở các phần sau.

2.5. Các luật nghiệp vụ (Business Rules)

### 2.5.1. Cơ sở xác định luật nghiệp vụ

Luật nghiệp vụ được rút ra từ các điểm kiểm soát trên sơ đồ BPMN (chất lượng bài nộp, ngưỡng tin cậy của AI) và mục tiêu sư phạm của nhà trường.

### 2.5.2. Vai trò của luật nghiệp vụ

Giúp chuẩn hóa cách AI xử lý bài làm, đảm bảo tính công bằng trong giáo dục và là cơ sở để kiểm thử thuật toán AI.

### 2.5.3. Danh sách các luật nghiệp vụ của hệ thống

(1) Luật kiểm tra tính hợp lệ của bài nộp: Bài tự luận dạng ảnh phải đạt độ phân giải tối thiểu và đúng định dạng trước khi đưa vào mô hình OCR.

(2) Luật ngưỡng tin cậy của AI (Human-in-the-loop): Nếu AI Grading trả về độ tự tin (Confidence Score) dưới 80%, bài làm bắt buộc phải được chuyển cho giáo viên duyệt và chấm lại.

(3) Luật tương tác của AI Tutor: AI không được phép cung cấp đáp án trực tiếp cho bài tập về nhà, chỉ được phép đưa ra gợi ý, công thức hoặc hướng giải.

(4) Luật đồng bộ điểm số: Chỉ những điểm số đã được AI chốt (độ tự tin cao) hoặc đã qua giáo viên duyệt mới được phép gọi API đẩy sang hệ thống FAP.

(5) Luật cảnh báo học vụ: Nếu điểm số trung bình của học sinh giảm liên tiếp trong 3 bài kiểm tra, hệ thống tự động gửi cảnh báo (Red Flag) cho Giáo viên chủ nhiệm.

(6) Luật bảo mật dữ liệu điểm số: Điểm số và nhận xét cá nhân chỉ được hiển thị cho chính học sinh đó và giáo viên/BGH có thẩm quyền, cấm chia sẻ chéo.

2.5.4 & 2.5.5. Nhận xét và Kết luận Các luật nghiệp vụ tập trung kiểm soát: Tính công bằng trong chấm thi, Tính sư phạm trong hướng dẫn học sinh và Tính bảo mật dữ liệu học đường.

2.6. Danh sách yêu cầu dạng thô (NEEDs) có gán nguồn gốc

### 2.6.1. Cơ sở hình thành danh sách NEEDs

Được tổng hợp từ khảo sát thực tế với BGH, Giáo viên, Học sinh trường THPT FPT và quy trình BPMN đã phân tích.

### 2.6.2. Nguyên tắc gán nguồn gốc cho NEEDs

Toàn bộ NEEDs được gán thuộc tính Origin (Ban giám hiệu, Giáo viên bộ môn, Học sinh, IT FPT) để làm rõ tính cấp thiết, phục vụ phân tích độ ưu tiên và tránh "gold-plating" (làm dư thừa tính năng).

### 2.6.3. Danh sách yêu cầu dạng thô của dự án

Dựa trên kết quả khảo sát, nhóm xác định được danh sách các yêu cầu dạng thô (NEEDs) với mã định danh STRQ-xx.

#### Bảng 2.x. Danh sách yêu cầu dạng thô (Stakeholder NEEDs) của dự án AI THPT FPT

|     |     |     |     |
| --- | --- | --- | --- |
| ID  | Mô tả yêu cầu (NEEDs) | Độ ưu tiên | Nguồn gốc (Origin) |
| STRQ-01 | Hệ thống AI phải có Dashboard thống kê real-time về tỷ lệ rớt môn, tiến độ học tập toàn trường. | High | Ban Giám Hiệu (BGH) |
| STRQ-02 | AI chỉ được đề xuất danh sách học sinh vi phạm, không tự động ra quyết định; bắt buộc có xác nhận của con người. | High | Ban Giám Hiệu (BGH) |
| STRQ-03 | Dữ liệu học sinh phải được ẩn danh hóa trước khi gửi đến các dịch vụ AI bên ngoài để bảo mật. | High | Ban Giám Hiệu (BGH) |
| STRQ-04 | Hệ thống phải hỗ trợ giảm tỷ lệ rớt môn từ ~30% xuống < 15% thông qua cơ chế cảnh báo sớm. | High | Ban Giám Hiệu (BGH) |
| STRQ-05 | Giáo viên cần công cụ tạo đề thi tự động dựa trên ma trận năng lực (Bloom). | High | Giáo viên (GV) |
| STRQ-06 | AI thực hiện chấm sơ bộ 100% bài làm, giáo viên chỉ cần kiểm tra lại các bài có độ tin cậy thấp. | High | Giáo viên (GV) |
| STRQ-07 | Giáo viên cần báo cáo chi tiết về lỗ hổng kiến thức của từng học sinh ngay sau mỗi bài kiểm tra. | Medium | Giáo viên (GV) |
| STRQ-08 | Cho phép cấu hình linh hoạt tỷ lệ câu hỏi theo chương, mức độ khó/dễ và thời gian làm bài. | Medium | Giáo viên (GV) |
| STRQ-09 | Học sinh cần một trợ lý ảo AI Tutor hỗ trợ giải đáp thắc mắc kiến thức 24/7. | High | Học sinh (HS) |
| STRQ-10 | Học sinh cần nhận được phản hồi và lời giải thích chi tiết tức thì sau khi hoàn thành bài nộp. | High | Học sinh (HS) |
| STRQ-11 | Hệ thống phải cung cấp lộ trình học tập cá nhân hóa dựa trên điểm mạnh và điểm yếu của từng học sinh. | High | Học sinh (HS) |
| STRQ-12 | Học sinh có thể theo dõi tiến độ học tập, điểm số và vị trí xếp hạng của mình trong lớp/khối. | Medium | Học sinh (HS) |
| STRQ-13 | Hệ thống phải đảm bảo khả năng xử lý ổn định cho tối thiểu 2.000 người dùng truy cập đồng thời. | High | IT Team / AI Eng |
| STRQ-14 | Cần môi trường Sandbox riêng biệt để thử nghiệm các mô hình AI mới trước khi triển khai chính thức. | Medium | IT Team / AI Eng |
| STRQ-15 | Mô hình AI phải có khả năng tự động huấn luyện lại (Retrain) khi tích lũy đủ dữ liệu mới. | Medium | IT Team / AI Eng |
| STRQ-16 | Phụ huynh cần nhận được thông báo tự động khi học sinh không có tiến bộ học tập sau 2 tuần. | Medium | Phụ huynh |
| STRQ-17 | Hệ thống cần phân tích mức độ tập trung và trạng thái cảm xúc của học sinh trong các tiết học online. | Low | Ban Giám Hiệu (BGH) |
| STRQ-18 | Tự động phát hiện các hành vi gian lận hoặc sao chép bài làm (đạo văn) giữa các học sinh. | High | Giáo viên (GV) |
| STRQ-19 | Hệ thống cần tích hợp module luyện phát âm và chấm điểm kỹ năng Speaking tiếng Anh. | Medium | Học sinh (HS) |
| STRQ-20 | Hệ thống AI phải đồng bộ dữ liệu người dùng và điểm số trực tiếp với hệ thống quản lý FAP hiện tại. | High | IT Team / AI Eng |

2.6.4. Phân tích nhóm NEEDs theo lĩnh vực nghiệp vụ

Quan sát danh sách trên có thể thấy 20 NEEDs của dự án AI THPT FPT được phân thành 6 nhóm nội dung lớn, phản ánh toàn diện các yêu cầu nghiệp vụ cốt lõi đã xác định:

- Nhóm Quản trị và giám sát đào tạo (STRQ-01 đến STRQ-04 và STRQ-17): Tập trung vào mục tiêu của Ban Giám Hiệu nhằm có Dashboard thống kê thời gian thực và cảnh báo sớm để giảm tỷ lệ trượt môn xuống dưới 15%. Nhóm này bổ sung thêm việc phân tích trạng thái cảm xúc (STRQ-17) để BGH có cái nhìn sâu sát hơn về chất lượng học tập online.
- Nhóm Nghiệp vụ giảng dạy và khảo thí (STRQ-05 đến STRQ-08 và STRQ-18): Đây là các yêu cầu trọng tâm của Giáo viên nhằm tối ưu hóa thời gian thông qua việc tạo đề tự động theo ma trận Bloom, AI chấm bài sơ bộ và đặc biệt là công cụ phát hiện gian lận, đạo văn (STRQ-18) để đảm bảo tính công bằng.
- Nhóm Trải nghiệm và hỗ trợ học sinh (STRQ-09 đến STRQ-12 và STRQ-19): Nhóm này hướng tới việc cá nhân hóa lộ trình học tập, cung cấp AI Tutor 24/7 và bổ sung thêm module luyện Speaking tiếng Anh (STRQ-19) để phát triển kỹ năng toàn diện cho học sinh.
- Nhóm Ràng buộc kỹ thuật và vận hành AI (STRQ-13, STRQ-14, STRQ-15 và STRQ-20): Xuất phát từ đội ngũ IT, đặt ra tiêu chuẩn khắt khe về sức tải (2.000 user), môi trường Sandbox, cơ chế huấn luyện lại mô hình và việc đồng bộ dữ liệu trực tiếp với hệ thống FAP hiện tại (STRQ-20).
- Nhóm Bảo mật và Đạo đức AI (STRQ-02 và STRQ-03): Quy định nghiêm ngặt về việc ẩn danh hóa dữ liệu trước khi gửi đi và đảm bảo vai trò kiểm soát của con người trong các quyết định nhạy cảm về học vụ.
- Nhóm Tương tác gia đình (STRQ-16): Đảm bảo luồng thông tin liên lạc thông suốt, giúp phụ huynh nhận cảnh báo kịp thời khi học sinh có dấu hiệu sa sút.

2.6.5. Nhận xét về mức độ ưu tiên và nguồn gốc của tập NEEDs

Về mức độ ưu tiên, phần lớn các yêu cầu (12/20) được đánh giá ở mức Cao (High). Đây là những nhu cầu thiết yếu cấu thành nên giá trị cốt lõi của hệ thống như: Dashboard quản trị, chấm điểm tự động, AI Tutor và khả năng chịu tải hệ thống. Các yêu cầu mức Trung bình (Medium) và Thấp (Low) như phân tích cảm xúc hay môi trường Sandbox là những phần mở rộng giúp hoàn thiện hệ sinh thái AI sau khi các module lõi đã vận hành ổn định.

Về nguồn gốc, tập NEEDs thể hiện sự cân bằng đa chiều từ 5 nhóm Stakeholder:

- Ban Giám Hiệu: Tầm nhìn quản trị và bảo mật dữ liệu.
- Giáo viên: Công cụ tự động hóa và liêm chính học thuật.
- Học sinh: Trợ lý ảo và học tập cá nhân hóa.
- IT Team: Hiệu năng, khả năng tích hợp và vận hành AI.
- Phụ huynh: Kết nối thông tin và giám sát tiến độ.

2.6.6. Ý nghĩa của danh sách NEEDs đối với các bước tiếp theo

Danh sách 20 NEEDs này là tập đầu vào chính thức cho Chương 3 và Chương 4. Từ các mã định danh STRQ-01 đến STRQ-20, nhóm sẽ thực hiện ánh xạ sang tầng Tính năng (FEATs) trong Vision Document. Đây là bước chuyển đổi quan trọng từ "mong muốn của người dùng" sang "giải pháp kỹ thuật cụ thể" trong mô hình kim tự tháp yêu cầu của dự án.

2.6.7. Kết luận của mục NEEDs

Thông qua khảo sát thực tế, nhóm đã xác định được 20 yêu cầu dạng thô (NEEDs) bao phủ toàn diện các khía cạnh của bài toán EdTech tại THPT FPT. Các yêu cầu này không chỉ giải quyết các tác vụ sư phạm đơn thuần mà còn chú trọng đến hiệu năng hạ tầng, bảo mật dữ liệu và sự kết nối giữa nhà trường – gia đình. Đây là nền tảng vững chắc để nhóm triển khai các hoạt động đặc tả và xây dựng ma trận truy vết ở các giai đoạn sau.

# CHƯƠNG 3: TINH CHẾ YÊU CẦU VÀ TÀI LIỆU TẦM NHÌN DỰ ÁN

## 3.1. Thảo luận, tinh chế và phê duyệt yêu cầu (Checklist)

Sau khi hoàn thành bước thu thập và xác định 16 yêu cầu dạng thô (NEEDs), nhóm không chuyển ngay sang đặc tả tính năng mà tiếp tục thực hiện hoạt động thảo luận, tinh chế và phê duyệt yêu cầu. Đây là bước trung gian có vai trò rất quan trọng trong kỹ nghệ yêu cầu, vì các yêu cầu thu được từ khảo sát tại THPT FPT ban đầu thường còn mang tính thô, có thể mập mờ, chồng chéo hoặc chưa đủ điều kiện để ánh xạ trực tiếp sang tính năng sản phẩm.

Theo lý thuyết học phần, phân tích viên cần xử lý bằng cách tinh chỉnh, làm rõ, phân tách và gom nhóm; đồng thời thực hiện thẩm định để phát hiện sớm các vấn đề tiềm ẩn trong tập yêu cầu học đường trước khi đưa vào tài liệu Tầm nhìn.

### 3.1.1. Mục đích của hoạt động thảo luận và tinh chế yêu cầu

Đối với dự án Hệ thống AI tại THPT FPT, mục tiêu của mục 3.1 là chuyển tập NEEDs từ trạng thái “được thu thập” sang trạng thái “đủ chất lượng để làm đầu vào cho Vision Document”. Đây là bước làm sạch tập yêu cầu trước khi ánh xạ từ tầng NEEDs sang tầng FEATs trong mô hình kim tự tháp.

Hoạt động thảo luận và tinh chế được thực hiện nhằm đạt bốn mục đích chính:

- Thứ nhất: Làm rõ ý nghĩa của từng NEED (như STRQ-06 về AI chấm sơ bộ) để tránh hiểu sai giữa các thành viên nhóm và Stakeholder.
- Thứ hai: Phát hiện các yêu cầu bị trùng lặp giữa nhu cầu của Giáo viên và Ban giám hiệu.
- Thứ ba: Chuẩn hóa câu chữ và mã định danh để quản lý đồng bộ trên GitHub Workspace.
- Thứ tư: Tạo ra tập NEEDs đã được rà soát, phê duyệt làm cơ sở tin cậy cho mục 3.2.

3.1.2. Cơ sở lý thuyết cho việc tinh chế yêu cầu

Theo lý thuyết về thẩm định yêu cầu, một yêu cầu riêng lẻ cần được kiểm tra theo các tiêu chí: không mập mờ, đúng đắn, nguyên tử (atomic), khả thi, có khả năng kiểm thử, cần thiết, dễ hiểu, độc lập và có khả năng theo dõi. Đồng thời, nhóm phải đảm bảo tính thống nhất và không dư thừa trên toàn bộ tập yêu cầu.

Bên cạnh đó, nhóm áp dụng các phép chuyển dịch lý thuyết khi ánh xạ sang FEATs như: sao chép giữ nguyên, phân tách (nếu STRQ-05 về tạo đề thi quá phức tạp), làm sáng rõ thuật ngữ AI, hoặc thêm ràng buộc về hiệu năng (STRQ-13). Tinh chế yêu cầu giúp biến các phát biểu ban đầu của Stakeholder thành một tập đầu vào đủ tốt, giữ được dấu vết nguồn gốc từ khảo sát ban đầu.

### 3.1.3. Tổ chức thảo luận online và vai trò của các thành viên

Nhóm sử dụng GitHub Workspace (Issues, Discussions, Projects) để quản lý yêu cầu tự động. Việc thảo luận online giúp lưu vết toàn bộ quá trình phản biện và phê duyệt. Vai trò của 6 thành viên được phân định cụ thể:

- Phạm Xuân Hưng (PM): Điều phối thảo luận, chủ trì duyệt các thay đổi lớn thông qua hội đồng CCB.
- Trần Việt Anh (BA): Chịu trách nhiệm chính trong việc tinh chế nội dung và chuyển đổi NEEDs thành FEATs.
- Đồng Văn Hòa (Requirements Specifier): Hỗ trợ viết đặc tả và xây dựng luồng nghiệp vụ chi tiết từ các NEEDs đã duyệt.
- Ninh Thanh Khương (UI/UX Designer): Đối chiếu các điểm rẽ nhánh trong BPMN với yêu cầu người dùng để đảm bảo tính khả thi về giao diện.
- Nguyễn Tuấn Long (QA): Kiểm tra chất lượng tập yêu cầu theo checklist và quản lý ma trận dấu vết (Traceability).
- Trương Việt Hải (CM/Developer): Quản lý kỹ thuật trên GitHub và đánh giá tính khả thi kỹ thuật của các mô hình AI dự kiến.

### 3.1.4. Nội dung tinh chế tập NEEDs của dự án AI FPT

Nhóm thực hiện các thao tác tinh chế quan trọng đối với 16 STRQ đã xác định:

- Chuẩn hóa phát biểu: Viết lại các yêu cầu như STRQ-09 (AI Tutor) hay STRQ-11 (Lộ trình cá nhân hóa) theo cấu trúc rõ ràng, thống nhất.
- Kiểm tra tính nguyên tử: Cân nhắc phân tách các yêu cầu chứa nhiều điều kiện (ví dụ: vừa chấm điểm vừa báo cáo lỗ hổng kiến thức) thành các thực thể độc lập.
- Phát hiện chồng chéo: Rà soát mối liên hệ giữa các yêu cầu về Dashboard quản lý của BGH và báo cáo chi tiết của Giáo viên để tránh lặp ý.
- Đối chiếu mục tiêu: Luôn căn cứ vào quy trình BPMN giáo dục và mục tiêu giảm tỷ lệ rớt môn của THPT FPT để loại bỏ những yêu cầu không cần thiết hoặc lệch phạm vi dự án.

### 3.1.5. Checklist thẩm định và phê duyệt yêu cầu

Dựa trên cơ sở lý thuyết, nhóm xây dựng checklist dùng để thảo luận và phê duyệt từng NEED trước khi đưa vào tài liệu tầm nhìn.

Bảng 3.1. Checklist thẩm định và phê duyệt NEEDs của dự án AI THPT FPT

|     |     |     |     |
| --- | --- | --- | --- |
| STT | Tiêu chí kiểm tra | Nội dung chi tiết | Người rà soát chủ trì |
| 1   | Tính nguyên tử (Atomic) | Yêu cầu chỉ chứa một nhu cầu duy nhất, không bị gộp nhiều tính năng khác nhau. | Đồng Văn Hòa |
| 2   | Tính khả thi (Feasible) | Mô hình AI hiện tại có khả năng xử lý được yêu cầu (ví dụ: OCR chữ viết tay, chấm điểm tự luận). | Trương Việt Hải |
| 3   | Không mập mờ (Unambiguous) | Thuật ngữ sư phạm và AI rõ ràng (Ví dụ: xác định rõ thế nào là "cảnh báo sớm"). | Trần Việt Anh |
| 4   | Tính kiểm thử (Testable) | QA có thể xây dựng kịch bản để kiểm tra xem yêu cầu có được đáp ứng hay không. | Nguyễn Tuấn Long |
| 5   | Tính cần thiết (Necessary) | Yêu cầu phải bám sát mục tiêu giảm tỷ lệ rớt môn và hỗ trợ học tập cá nhân hóa. | Phạm Xuân Hưng |
| 6   | Tính độc lập (Independent) | Yêu cầu không bị phụ thuộc quá mức vào các yêu cầu chưa được xác định khác. | Trần Việt Anh |
| 7   | Tính đầy đủ (Complete) | Phản ánh đủ thông tin đầu vào, đầu ra và ràng buộc (ví dụ: STRQ-13 về 2.000 user). | Đồng Văn Hòa |
| 8   | Tính nhất quán (Consistent) | Không mâu thuẫn giữa các yêu cầu (ví dụ: giữa bảo mật ẩn danh và phân tích dữ liệu). | Nguyễn Tuấn Long |
| 9   | Tính thẩm mỹ/UX (UI/UX) | Nhu cầu có thể chuyển hóa thành giao diện người dùng thân thiện, dễ thao tác. | Ninh Thanh Khương |
| 10  | Truy vết (Traceable) | Có nguồn gốc (Origin) từ Stakeholder cụ thể đã xác định ở mục 2.6. | Trương Việt Hải |

### 3.1.6. Quy trình phê duyệt tập yêu cầu sau tinh chế

Sau khi hoàn tất các thảo luận và rà soát theo checklist, nhóm tiến hành phê duyệt tập NEEDs theo quy trình nội bộ:

1.  BA (Trần Việt Anh) cập nhật lại nội dung các yêu cầu đã được tinh chế lên GitHub.
2.  QA (Nguyễn Tuấn Long) kiểm tra lại lần cuối về tính nhất quán, khả năng truy vết và tình trạng trùng lặp.
3.  PM (Phạm Xuân Hưng) chủ trì phiên rà soát cuối cùng với toàn nhóm.
4.  Khi cần, nhóm tham vấn ý kiến từ đại diện Ban Giám Hiệu THPT FPT đối với các yêu cầu nhạy cảm về dữ liệu học sinh.

Kết quả của bước phê duyệt là tạo ra một tập 16 NEEDs đã được làm sạch, đủ điều kiện để chuyển sang tầng Product Features (FEATs) trong tài liệu Tầm nhìn dự án.

3.1.7. Kết luận của mục thảo luận, tinh chế và phê duyệt yêu cầu

Mục 3.1 là bước chuyển tiếp quan trọng giữa giai đoạn thu thập yêu cầu thô ở Chương 2 và giai đoạn xây dựng tài liệu tầm nhìn ở Chương 3. Thông qua hoạt động thảo luận trên GitHub và áp dụng checklist, nhóm đã chuẩn hóa được tập NEEDs của dự án AI FPT theo hướng rõ ràng, nhất quán và sẵn sàng cho việc ánh xạ.

3.2. TÀI LIỆU TẦM NHÌN DỰ ÁN (Project Vision Document – mẫu IBM)

Tổ chức: Trường Trung học phổ thông FPT (FSchool)

Dự án: Phát triển Hệ thống ứng dụng AI trong giáo dục và đào tạo cho Trường THPT FPT

Tên tài liệu: Vision Document

Phiên bản: 1.0

Lịch sử sửa đổi

|     |     |     |     |
| --- | --- | --- | --- |
| Ngày | Phiên bản | Mô tả | Tác giả |
| 09/03/2026 | 1.0 | Khởi tạo tài liệu Vision phiên bản đầu tiên cho dự án AI FPT | Nhóm dự án |

1\. Giới thiệu (Introduction)

Tài liệu Vision được dùng để thu thập, phân tích và định nghĩa các nhu cầu mức cao cùng các tính năng cốt lõi của hệ thống AI, tập trung vào giá trị mà hệ thống mang lại cho nhà trường, giáo viên và học sinh.

1.1. Mục đích (Purpose)

Xác định bức tranh tổng thể về dự án ứng dụng AI tại THPT FPT. Tài liệu này đóng vai trò cầu nối giữa tập NEEDs đã tinh chế và các FEATs (tính năng sản phẩm), làm nền tảng cho các bước đặc tả Use Case và kiểm thử ở các chương sau.

1.2. Phạm vi (Scope)

Áp dụng cho dự án AI Giáo dục tại THPT FPT. Phạm vi bao gồm: hỗ trợ chấm bài tự động, trợ giảng ảo (AI Tutor), Dashboard cảnh báo sớm học sinh yếu kém và cá nhân hóa lộ trình học tập, cùng các ràng buộc về bảo mật dữ liệu học đường.

1.3. Định nghĩa, từ viết tắt và chữ viết tắt

- AI Tutor: Trợ giảng ảo hỗ trợ giải đáp 24/7.
- OCR (Optical Character Recognition): Công nghệ nhận dạng chữ viết tay bài làm của học sinh.
- Confidence Score: Mức độ tin tưởng của AI vào kết quả chấm điểm.
- Bloom Taxonomy: Ma trận năng lực dùng để tạo đề thi.
- FAP/EduNext: Các hệ thống quản lý đào tạo hiện có của FPT.

1.4. Tài liệu tham khảo

1.  Phát biểu bài toán: Ứng dụng AI trong giáo dục tại THPT FPT.
2.  Tài liệu lý thuyết AMS431 (Bài 2, 4, 5, 6).
3.  Bản Kế hoạch quản lý yêu cầu (RMP) của dự án.
4.  Danh sách 16 NEEDs đã được phê duyệt.
5.  Mẫu Vision Document Template by IBM.

1.5. Tổng quan (Overview)

Phần tiếp theo mô tả định vị sản phẩm, hồ sơ Stakeholder và các tính năng mức cao (FEATs) làm đầu vào cho mục 3.3.

2\. Định vị sản phẩm (Positioning)

2.1. Cơ hội kinh doanh (Business Opportunity)

Trường THPT FPT hiện có số lượng học sinh lớn, dẫn đến áp lực chấm bài và theo dõi sát sao từng cá nhân của giáo viên rất cao. Việc ứng dụng AI là cơ hội để giảm 30% khối lượng công việc hành chính cho giáo viên, giảm tỷ lệ trượt môn xuống dưới 15% thông qua cảnh báo sớm, đồng thời tạo ra môi trường học tập 24/7 cho học sinh.

2.2. Phát biểu vấn đề (Problem Statement)

- Vấn đề: Áp lực chấm bài thủ công lớn và thiếu công cụ cảnh báo sớm học sinh có nguy cơ rớt môn dựa trên dữ liệu thời gian thực.
- Ảnh hưởng đến: Ban Giám Hiệu, Giáo viên, Học sinh và Phụ huynh.
- Tác động: Tỷ lệ rớt môn khó kiểm soát, phản hồi cho học sinh bị chậm trễ, khó cá nhân hóa lộ trình học tập cho hàng ngàn học sinh.
- Giải pháp thành công: Cung cấp hệ thống AI tích hợp có khả năng chấm bài tự động, hỗ trợ học tập trực tuyến và Dashboard quản trị thông minh.

2.3. Phát biểu định vị sản phẩm (Product Position Statement)

- Dành cho: Trường THPT FPT (BGH, giáo viên và học sinh).
- Những bên đang cần: Một công cụ AI thông minh để tối ưu hóa việc dạy và học.
- Hệ thống AI FPT: Là nền tảng EdTech tích hợp trí tuệ nhân tạo.
- Giúp: Chấm điểm nhanh, cảnh báo học tập sớm và hỗ trợ học sinh học tập cá nhân hóa.
- Khác với: Các phương pháp quản lý thủ công hoặc các hệ thống LMS thông thường không có lõi AI phân tích.
- Sản phẩm của chúng tôi: Cung cấp khả năng phân tích dự báo và tương tác thông minh 24/7.

3\. Mô tả Stakeholder và Người dùng (Stakeholder and User Descriptions)

Phần này mô tả bối cảnh và nhu cầu nền tảng của các bên liên quan để giải thích tính cần thiết của các tính năng hệ thống.

### 3.1. Đặc điểm thị trường (Market Demographics)

Sản phẩm hướng tới thị trường giáo dục phổ thông (K-12) trong hệ sinh thái FPT Education, nơi học sinh và giáo viên đang kỳ vọng vào sự hỗ trợ của trí tuệ nhân tạo để cá nhân hóa việc học và giảm tải áp lực hành chính. Với THPT FPT, một hệ thống AI riêng giúp nhà trường làm chủ dữ liệu đào tạo, dự báo sớm rủi ro học tập và tạo ra lợi thế cạnh tranh về công nghệ giáo dục (EdTech) so với các trường truyền thống.

3.2. Tóm tắt Stakeholder (Stakeholder Summary)

Bảng1.6 dưới đây tổng hợp các stakeholder chính của dự án AI FPT, nhất quán với mục 1.7.1 và Chương 2.

|     |     |     |
| --- | --- | --- |
| Tên Stakeholder | Đại diện cho | Vai trò trong dự án |
| Ban Giám Hiệu | Khách hàng tài trợ | Đưa ra chiến lược giảm tỷ lệ rớt môn, phê duyệt phạm vi và bảo mật dữ liệu. |
| Giáo viên | Người dùng nghiệp vụ | Cung cấp ma trận đề thi, quy tắc chấm điểm và nhu cầu giảm tải chấm bài. |
| Học sinh | Người dùng cuối | Cung cấp nhu cầu về hỗ trợ giải bài tập, lộ trình học tập và tương tác 24/7. |
| Phụ huynh | Bên liên quan hỗ trợ | Theo dõi tiến độ học tập và nhận cảnh báo sớm về học lực của con em. |
| Đội ngũ IT/AI | Khả thi kỹ thuật | Đảm bảo hạ tầng, tích hợp API và độ chính xác của các mô hình AI. |

3.3. Tóm tắt người dùng (User Summary)

|     |     |     |
| --- | --- | --- |
| Nhóm người dùng | Mô tả | Được đại diện bởi |
| Học sinh | Sử dụng AI Tutor, xem lộ trình học và làm bài trực tuyến. | Học sinh |
| Giáo viên | Quản lý đề thi, duyệt kết quả AI chấm và theo dõi lớp học. | Giáo viên |
| Cán bộ quản trị | Xem Dashboard thống kê toàn trường, quản lý người dùng. | Ban Giám Hiệu |
| Quản trị hệ thống | Vận hành kỹ thuật, kiểm soát hiệu năng và retrain mô hình AI. | IT Team |

3.4. Môi trường sử dụng (User Environment)

Người dùng thao tác trong môi trường giáo dục số của FPT. Học sinh sử dụng thiết bị cá nhân (Laptop/Tablet) truy cập hệ thống 24/7. Giáo viên và BGH sử dụng tại trường thông qua mạng nội bộ hoặc từ xa để quản lý đào tạo. Hệ thống cần tích hợp với dữ liệu từ FAP/EduNext và được nhóm phát triển quản lý qua bộ công cụ GitHub, Figma, Draw.io.

3.5. Hồ sơ Stakeholder (Stakeholder Profiles)

_(Tóm tắt các nhóm chính)_

- Ban Giám Hiệu: Quan tâm đến tỷ lệ trượt môn (<15%) và danh tiếng công nghệ của trường. Mức độ tham gia: Phê duyệt cuối.
- Giáo viên: Quan tâm đến độ chính xác của AI chấm bài (Confidence Score > 80%). Vấn đề gặp phải: Quá tải chấm bài tự luận.
- IT Team: Quan tâm đến sức tải 2.000 user đồng thời và bảo mật dữ liệu học sinh.

3.7. Các nhu cầu chính của Stakeholder/Người dùng (Key Needs)

|     |     |     |     |
| --- | --- | --- | --- |
| Need | Priority | Concerns | Proposed Solution |
| Giảm tỷ lệ trượt môn | H   | BGH cần biết sớm học sinh nào có nguy cơ rớt. | Dashboard cảnh báo sớm dựa trên AI Analytics. |
| Tự động hóa khảo thí | H   | Giáo viên tốn quá nhiều thời gian chấm bài và ra đề. | AI chấm bài tự động và sinh đề theo ma trận Bloom. |
| Hỗ trợ học tập 24/7 | H   | Học sinh gặp khó khăn khi tự học buổi tối mà không có thầy cô. | Chatbot AI Tutor giải đáp kiến thức tức thì. |
| Cá nhân hóa lộ trình | M   | Mỗi học sinh có hổng kiến thức khác nhau. | AI phân tích điểm yếu và gợi ý tài liệu học tập riêng. |

4\. Tổng quan sản phẩm (Product Overview)

4.1. Góc nhìn sản phẩm (Product Perspective)

Hệ thống AI FPT là một nền tảng EdTech tích hợp, đóng vai trò trợ lý thông minh kết nối giữa kho tri thức nhà trường và người học. Hệ thống tương tác trực tiếp với cơ sở dữ liệu học tập hiện có và các mô hình ngôn ngữ lớn (LLM) để xử lý ngôn ngữ tự nhiên.

4.2. Tóm tắt năng lực cốt lõi (Summary of Capabilities)

- Tăng hiệu quả sư phạm: Tự động hóa ra đề và chấm điểm.
- Nâng cao kết quả học tập: Cảnh báo sớm rủi ro và AI Tutor hỗ trợ liên tục.
- Quản trị thông minh: Báo cáo xu hướng học tập toàn trường qua Dashboard.

4.3. Giả định và phụ thuộc (Assumptions and Dependencies)

- Giả định học sinh có thiết bị cá nhân để truy cập.
- Phụ thuộc vào độ ổn định của các API mô hình AI bên thứ ba.
- Dữ liệu học tập từ các học kỳ trước được cung cấp đầy đủ để huấn luyện AI.

5\. Tính năng sản phẩm (Product Features - FEATs)

Dưới đây là danh sách 49 tính năng sản phẩm được phân nhóm theo các module năng lực cốt lõi, đảm bảo giải quyết trọn vẹn 20 nhu cầu chiến lược (STRQ) của dự án AI THPT FPT.

5.1. Nhóm Module Quản trị và Phân tích thông minh (Dashboard & Analytics)

- FEAT-01: Dashboard tổng quan số liệu đào tạo toàn trường theo thời gian thực.
- FEAT-02: Module dự báo rủi ro học tập (Early Warning System) dựa trên dữ liệu lịch sử.
- FEAT-03: Bộ lọc dữ liệu chuyên sâu theo khối, lớp, môn học và giáo viên bộ môn.
- FEAT-04: Hệ thống phát hiện và cảnh báo hành vi học tập bất thường.
- FEAT-05: Giao diện điều khiển và phê duyệt dành riêng cho Ban Giám Hiệu.
- FEAT-06: Nhật ký (Audit Log) ghi lại mọi tác động và quyết định của quản trị viên.
- FEAT-07: Module phân tích xu hướng và dự báo phổ điểm học kỳ.
- FEAT-08: Tính năng tự động xuất báo cáo học vụ định kỳ (PDF/Excel).
- FEAT-09: Dashboard đánh giá hiệu quả giảng dạy và mức độ tương tác của giáo viên.

5.2. Nhóm Module Khảo thí và Chấm điểm tự động (AI Grading & Testing)

- FEAT-10: Ngân hàng câu hỏi thông minh tích hợp ma trận năng lực Bloom.
- FEAT-11: Engine sinh đề thi ngẫu nhiên dựa trên các tham số độ khó và chương học.
- FEAT-12: Công cụ soạn thảo câu hỏi hỗ trợ gợi ý nội dung từ AI.
- FEAT-13: Engine chấm điểm tự động tích hợp công nghệ nhận diện chữ viết (OCR).
- FEAT-14: Giao diện so sánh bài làm của học sinh với kết quả phân tích của AI.
- FEAT-15: Module điều chỉnh và xác nhận điểm số thủ công cho giáo viên.
- FEAT-16: Công cụ phát hiện đạo văn và so khớp văn bản bài làm giữa các học sinh.
- FEAT-17: Hệ thống giám sát webcam và phát hiện gian lận (AI Proctoring).
- FEAT-18: Module chấm điểm và sửa lỗi phát âm kỹ năng Speaking tiếng Anh.

5.3. Nhóm Module Hỗ trợ học tập cá nhân hóa (Adaptive Learning & AI Tutor)

- FEAT-19: Trợ lý ảo AI Tutor (Chatbot LLM) hỗ trợ giải đáp kiến thức 24/7.
- FEAT-20: Module tìm kiếm tài liệu đa phương thức (giọng nói, hình ảnh).
- FEAT-21: Công cụ tóm tắt nội dung bài giảng dài (Summary AI) theo ý chính.
- FEAT-22: Engine học tập thích ứng (Adaptive Learning) tự động điều chỉnh độ khó bài tập.
- FEAT-23: Module phân tích lỗ hổng kiến thức (Knowledge Gap Analysis) sau mỗi bài kiểm tra.
- FEAT-24: Biểu đồ Radar (Radar Chart) mô tả năng lực 5 chiều của học sinh.
- FEAT-25: Hệ thống tự động gợi ý tài liệu và video bài giảng bù đắp kiến thức.
- FEAT-26: Tính năng lập kế hoạch học tập cá nhân tự động dựa trên thời khóa biểu.
- FEAT-27: Module phản hồi đáp án và giải thích lỗi sai bằng ngôn ngữ tự nhiên.

5.4. Nhóm Module Kết nối và Trải nghiệm người dùng (Portal & Engagement)

- FEAT-28: Cổng thông tin học sinh (Student Portal) theo dõi lộ trình và điểm số.
- FEAT-29: Bảng xếp hạng thành tích và thi đua (Leaderboard) theo lớp/khối.
- FEAT-30: Hệ thống tích điểm thưởng và huy hiệu ảo (Gamification).
- FEAT-31: Cổng thông tin dành cho phụ huynh (Parent Portal).
- FEAT-32: Hệ thống thông báo tự động cho phụ huynh qua SMS, App và Email.
- FEAT-33: Module báo cáo phân tích tâm lý và xu hướng năng lực dành cho gia đình.
- FEAT-34: Giao diện hiển thị đa nền tảng (Responsive Design) cho Web và Mobile.
- FEAT-35: Tính năng tương tác trực tuyến và thảo luận nhóm học tập.

5.5. Nhóm Module Hạ tầng, Bảo mật và Vận hành AI (Backend & MLOps)

- FEAT-36: Module ẩn danh hóa (Anonymization) dữ liệu cá nhân học sinh.
- FEAT-37: Cổng trung chuyển dữ liệu mã hóa (Secure Data Gateway).
- FEAT-38: Cơ chế đăng nhập một lần (Single Sign-On - SSO) tích hợp tài khoản trường.
- FEAT-39: Bộ API Gateway kết nối dữ liệu trực tiếp với hệ thống FAP/EduNext.
- FEAT-40: Kiến trúc cân bằng tải (Load Balancer) đảm bảo 2.000 user truy cập.
- FEAT-41: Cơ chế tự động mở rộng tài nguyên (Auto-scaling) theo lưu lượng.
- FEAT-42: Hệ thống Backup và khôi phục dữ liệu thảm họa định kỳ.
- FEAT-43: Môi trường Sandbox biệt lập để thử nghiệm mô hình AI (A/B Testing).
- FEAT-44: Công cụ giả lập dữ liệu người dùng (Data Mockup) phục vụ kiểm thử.
- FEAT-45: Quy trình MLOps tự động cập nhật và huấn luyện lại mô hình AI.
- FEAT-46: Module thu thập phản hồi sai lệch (Feedback Loop) để tinh chỉnh AI.
- FEAT-47: Hệ thống giám sát hiệu năng mô hình (Model Monitoring).
- FEAT-48: Module quản lý quyền truy cập chi tiết (RBAC) cho 6 vai trò người dùng.
- FEAT-49: Chức năng ghi nhật ký lỗi hệ thống và cảnh báo kỹ thuật

6\. Các ràng buộc (Constraints)

- Phạm vi học phần: Tập trung vào phân tích yêu cầu trong 10 tuần, AI được mô tả ở mức đặc tả và mô phỏng giao diện.
- Nguồn lực: Nhóm 6 thành viên thực hiện toàn bộ chuỗi tài liệu từ RMP đến Test Cases.
- Kỹ thuật: Phải đáp ứng xử lý đồng thời cho 2.000 học sinh (STRQ-13).

7\. Khoảng chất lượng (Quality Ranges)

- Usability: Giao diện đơn giản, học sinh chỉ cần tối đa 3 click để gặp AI Tutor.
- Performance: AI phản hồi câu hỏi kiến thức trong vòng dưới 3 giây.
- Security: Dữ liệu điểm số phải được mã hóa và chỉ giáo viên bộ môn mới có quyền truy cập.

8\. Thứ tự trước sau và độ ưu tiên (Precedence and Priority)

Độ ưu tiên được xác định theo mô hình: Core Features (Release 1.0) gồm Dashboard cảnh báo, AI chấm điểm và AI Tutor. Advanced Features (Release 2.0) gồm Cá nhân hóa lộ trình và Tích hợp thông báo phụ huynh.

#### Bảng 1.7.x. Độ ưu tiên của các FEATs trong Vision Document

|     |     |     |     |
| --- | --- | --- | --- |
| Mã FEAT | Tên tính năng | Độ ưu tiên | Thứ tự phụ thuộc / Ghi chú |
| FEAT-01 | Dashboard tổng quan số liệu đào tạo | High | Nền tảng hiển thị cho BGH |
| FEAT-02 | Module dự báo rủi ro học tập | High | Phụ thuộc dữ liệu từ FEAT-13, 15 |
| FEAT-03 | Hệ thống lọc dữ liệu đa chiều | Medium | Bổ trợ cho FEAT-01 |
| FEAT-04 | Cảnh báo hành vi học tập bất thường | Medium | Dựa trên thuật toán phân tích |
| FEAT-05 | Giao diện phê duyệt dành cho BGH | High | Kiểm soát quyền STRQ-02 |
| FEAT-06 | Nhật ký truy vết quyết định (Audit Log) | Medium | Phụ thuộc FEAT-05 |
| FEAT-07 | Module mã hóa dữ liệu cá nhân | High | Ràng buộc bảo mật bắt buộc |
| FEAT-08 | Cổng trung chuyển dữ liệu an toàn | High | Phụ thuộc FEAT-07 |
| FEAT-09 | Hệ thống gửi thông báo tự động | High | Kênh tương tác chính (Zalo/App) |
| FEAT-10 | Ngân hàng câu hỏi thông minh (Bloom) | High | Nền tảng cho khâu khảo thí |
| FEAT-11 | Engine sinh đề thi ngẫu nhiên | High | Phụ thuộc FEAT-10 |
| FEAT-12 | Công cụ soạn thảo câu hỏi hỗ trợ AI | Medium | Bổ trợ cho FEAT-10 |
| FEAT-13 | Engine chấm điểm tự động (OCR) | High | Tính năng cốt lõi giảm tải GV |
| FEAT-14 | Giao diện so sánh bài làm và kết quả AI | Medium | Phụ thuộc FEAT-13 |
| FEAT-15 | Module điều chỉnh điểm số thủ công | High | Quy trình bắt buộc của GV |
| FEAT-16 | Thuật toán phát hiện đạo văn | High | Đảm bảo liêm chính học thuật |
| FEAT-17 | Hệ thống giám sát webcam (AI Proctoring) | Medium | Sử dụng cho các kỳ thi tập trung |
| FEAT-18 | Module luyện Speaking tiếng Anh | Medium | Tính năng nâng cao cho HS |
| FEAT-19 | Chatbot AI Tutor (LLM) | High | Trợ lý học tập 24/7 |
| FEAT-20 | Tìm kiếm tài liệu đa phương thức | Medium | Tăng trải nghiệm người dùng |
| FEAT-21 | Công cụ tóm tắt bài giảng (Summary AI) | Medium | Phụ thuộc dữ liệu đầu vào bài học |
| FEAT-22 | Engine học tập thích ứng | Medium | Phụ thuộc FEAT-13, 23 |
| FEAT-23 | Phân tích lỗ hổng kiến thức | High | Phụ thuộc kết quả FEAT-13 |
| FEAT-24 | Biểu đồ Radar đánh giá năng lực | Medium | Trực quan hóa từ FEAT-23 |
| FEAT-25 | Hệ thống gợi ý tài liệu học bù | High | Phụ thuộc FEAT-23 |
| FEAT-26 | Lập kế hoạch học tập tự động | Medium | Dựa trên lịch trình cá nhân |
| FEAT-27 | Phản hồi giải thích lỗi sai bằng AI | High | Phụ thuộc FEAT-13, 19 |
| FEAT-28 | Cổng thông tin học sinh (Student Portal) | High | Giao diện chính cho HS |
| FEAT-29 | Bảng xếp hạng thành tích (Leaderboard) | Low | Tính năng thúc đẩy thi đua |
| FEAT-30 | Hệ thống tích điểm và huy hiệu | Low | Tăng tính gắn kết (Gamification) |
| FEAT-31 | Cổng thông tin phụ huynh (Parent Portal) | Medium | Giao diện chính cho Phụ huynh |
| FEAT-32 | Thông báo học tập định kỳ cho gia đình | Medium | Phụ thuộc FEAT-09, 31 |
| FEAT-33 | Báo cáo phân tích tâm lý học sinh | Low | Tính năng nghiên cứu sâu |
| FEAT-34 | Giao diện hiển thị đa nền tảng | High | Ràng buộc về UX/UI |
| FEAT-35 | Tính năng thảo luận nhóm học tập | Medium | Tăng tính cộng đồng |
| FEAT-36 | Module ẩn danh hóa (Anonymization) | High | Phụ thuộc FEAT-07 |
| FEAT-37 | Cổng trung chuyển mã hóa | High | Hạ tầng bảo mật |
| FEAT-38 | Đăng nhập một lần (SSO) | High | Tích hợp hệ thống trường |
| FEAT-39 | API Gateway kết nối FAP/EduNext | High | Ràng buộc tích hợp dữ liệu |
| FEAT-40 | Kiến trúc cân bằng tải (Load Balancer) | High | Ràng buộc hiệu năng 2.000 user |
| FEAT-41 | Cơ chế tự động mở rộng (Auto-scaling) | Medium | Bổ trợ cho FEAT-40 |
| FEAT-42 | Hệ thống Backup dữ liệu | High | Đảm bảo an toàn dữ liệu |
| FEAT-43 | Môi trường Sandbox thử nghiệm | Medium | Dành cho đội ngũ IT |
| FEAT-44 | Công cụ giả lập dữ liệu (Mock Data) | Medium | Phục vụ kiểm thử |
| FEAT-45 | Quy trình MLOps tự động retrain | Medium | Vận hành mô hình AI lâu dài |
| FEAT-46 | Module thu thập phản hồi (Feedback Loop) | Medium | Cải thiện độ chính xác AI |
| FEAT-47 | Giám sát hiệu năng mô hình AI | Medium | Đảm bảo AI không bị lệch (Drift) |
| FEAT-48 | Quản lý quyền truy cập (RBAC) | High | Phân quyền 6 vai trò nhóm |
| FEAT-49 | Hệ thống ghi log lỗi và cảnh báo | Medium | Vận hành kỹ thuật |

9\. Các yêu cầu sản phẩm khác (Other Product Requirements)

9.1. Các chuẩn áp dụng (Applicable Standards)

Hệ thống AI FPT tuân thủ các chuẩn công nghệ và giáo dục hiện đại:

- Chuẩn bảo mật dữ liệu giáo dục: Tuân thủ các quy định về bảo vệ quyền riêng tư của học sinh và ẩn danh hóa dữ liệu trước khi xử lý qua AI (STRQ-03).
- Chuẩn ma trận năng lực Bloom: Áp dụng trong việc phân loại câu hỏi và sinh đề thi tự động (STRQ-05).
- Chuẩn kết nối API: Sử dụng RESTful API để tích hợp với hệ thống FAP và EduNext của trường (STRQ-20).

9.2. Yêu cầu hệ thống (System Requirements)

- Hạ tầng: Máy chủ cloud có khả năng tính toán cao để xử lý các mô hình ngôn ngữ lớn (LLM).
- Phần mềm: Truy cập qua trình duyệt web phổ biến (Chrome, Edge, Safari) và ứng dụng di động.
- Công cụ quản lý: GitHub (quản lý yêu cầu), Figma (Mockup), Bizagi (BPMN), Google Drive.

9.3. Yêu cầu hiệu năng (Performance Requirements)

- Khả năng chịu tải: Xử lý ổn định tối thiểu 2.000 người dùng đồng thời (STRQ-13).
- Thời gian phản hồi: Trợ lý ảo AI Tutor phải phản hồi câu hỏi trong vòng dưới 3 giây.
- Độ chính xác: AI chấm điểm tự luận phải đạt độ tin cậy tương đồng với giáo viên trên 85%.

9.4. Yêu cầu môi trường (Environmental Requirements)

- Môi trường học sinh: Truy cập từ xa tại nhà hoặc qua mạng Wi-Fi của trường.
- Môi trường vận hành: Phòng đào tạo và văn phòng khoa, nơi giáo viên sử dụng Dashboard quản trị để theo dõi tiến độ toàn trường.

10\. Yêu cầu về tài liệu hướng dẫn (Documentation Requirements)

10.1. Hướng dẫn sử dụng (User Manual)

- Dành cho Học sinh: Hướng dẫn tương tác với AI Tutor, cách nộp bài chụp ảnh qua OCR và xem lộ trình học tập.
- Dành cho Giáo viên: Hướng dẫn cấu hình ma trận đề thi, quy trình duyệt điểm AI và quản lý Dashboard lớp học.

10.2. Trợ giúp trực tuyến (Online Help)

Tích hợp các bong bóng trợ giúp (Tooltips) tại các tính năng phức tạp như thiết lập thông số mô hình AI hoặc giải thích các chỉ số trong Dashboard cảnh báo rủi ro.

10.3. Tài liệu cài đặt và Readme

Cung cấp file README.md trên GitHub bao gồm: Hướng dẫn cấu hình API Key cho AI, cách thiết lập môi trường Sandbox và hướng dẫn truy cập các bản Mockup trên Figma.

11\. Phụ lục 1 – Thuộc tính của FEATs (Appendix 1 – Feature Attributes)

Nhằm quản lý hiệu quả 49 FEATs, nhóm thống nhất các thuộc tính quản lý sau:

- Status (Trạng thái): Proposed (Đề xuất), Approved (Đã duyệt), In Development, Verified (Đã kiểm chứng).
- Effort (Nỗ lực): High/Medium/Low (Dựa trên khối lượng công việc của nhóm 6 người).
- Target Release: \* Release 1.0 (Core AI): Dashboard, AI chấm bài, Chống gian lận, Hạ tầng chịu tải.
    - Release 2.0 (Advanced AI): AI Tutor 24/7, Cá nhân hóa lộ trình, Phân tích cảm xúc, Luyện Speaking.
- Assigned To (Phân công): \* Hưng (PM): Quản lý trạng thái và phê duyệt FEAT.
    - Anh & Hòa (BA/Specifier): Đặc tả chi tiết FEAT.
    - Long (QA): Kiểm tra độ ổn định và rủi ro của FEAT.

11.1 Bảng phụ lục đề xuất cho FEATs

|     |     |     |     |
| --- | --- | --- | --- |
| Mã FEAT | Tên tính năng | Độ ưu tiên | Thứ tự phụ thuộc / Ghi chú |
| FEAT-01 | Dashboard tổng quan số liệu đào tạo | High | Nền tảng hiển thị cho BGH |
| FEAT-02 | Module dự báo rủi ro học tập | High | Phụ thuộc dữ liệu từ FEAT-13, 15 |
| FEAT-03 | Hệ thống lọc dữ liệu đa chiều | Medium | Bổ trợ cho FEAT-01 |
| FEAT-04 | Cảnh báo hành vi học tập bất thường | Medium | Dựa trên thuật toán phân tích |
| FEAT-05 | Giao diện phê duyệt dành cho BGH | High | Kiểm soát quyền STRQ-02 |
| FEAT-06 | Nhật ký truy vết quyết định (Audit Log) | Medium | Phụ thuộc FEAT-05 |
| FEAT-07 | Module mã hóa dữ liệu cá nhân | High | Ràng buộc bảo mật bắt buộc |
| FEAT-08 | Cổng trung chuyển dữ liệu an toàn | High | Phụ thuộc FEAT-07 |
| FEAT-09 | Hệ thống gửi thông báo tự động | High | Kênh tương tác chính (Zalo/App) |
| FEAT-10 | Ngân hàng câu hỏi thông minh (Bloom) | High | Nền tảng cho khâu khảo thí |
| FEAT-11 | Engine sinh đề thi ngẫu nhiên | High | Phụ thuộc FEAT-10 |
| FEAT-12 | Công cụ soạn thảo câu hỏi hỗ trợ AI | Medium | Bổ trợ cho FEAT-10 |
| FEAT-13 | Engine chấm điểm tự động (OCR) | High | Tính năng cốt lõi giảm tải GV |
| FEAT-14 | Giao diện so sánh bài làm và kết quả AI | Medium | Phụ thuộc FEAT-13 |
| FEAT-15 | Module điều chỉnh điểm số thủ công | High | Quy trình bắt buộc của GV |
| FEAT-16 | Thuật toán phát hiện đạo văn | High | Đảm bảo liêm chính học thuật |
| FEAT-17 | Hệ thống giám sát webcam (AI Proctoring) | Medium | Sử dụng cho các kỳ thi tập trung |
| FEAT-18 | Module luyện Speaking tiếng Anh | Medium | Tính năng nâng cao cho HS |
| FEAT-19 | Chatbot AI Tutor (LLM) | High | Trợ lý học tập 24/7 |
| FEAT-20 | Tìm kiếm tài liệu đa phương thức | Medium | Tăng trải nghiệm người dùng |
| FEAT-21 | Công cụ tóm tắt bài giảng (Summary AI) | Medium | Phụ thuộc dữ liệu đầu vào bài học |
| FEAT-22 | Engine học tập thích ứng | Medium | Phụ thuộc FEAT-13, 23 |
| FEAT-23 | Phân tích lỗ hổng kiến thức | High | Phụ thuộc kết quả FEAT-13 |
| FEAT-24 | Biểu đồ Radar đánh giá năng lực | Medium | Trực quan hóa từ FEAT-23 |
| FEAT-25 | Hệ thống gợi ý tài liệu học bù | High | Phụ thuộc FEAT-23 |
| FEAT-26 | Lập kế hoạch học tập tự động | Medium | Dựa trên lịch trình cá nhân |
| FEAT-27 | Phản hồi giải thích lỗi sai bằng AI | High | Phụ thuộc FEAT-13, 19 |
| FEAT-28 | Cổng thông tin học sinh (Student Portal) | High | Giao diện chính cho HS |
| FEAT-29 | Bảng xếp hạng thành tích (Leaderboard) | Low | Tính năng thúc đẩy thi đua |
| FEAT-30 | Hệ thống tích điểm và huy hiệu | Low | Tăng tính gắn kết (Gamification) |
| FEAT-31 | Cổng thông tin phụ huynh (Parent Portal) | Medium | Giao diện chính cho Phụ huynh |
| FEAT-32 | Thông báo học tập định kỳ cho gia đình | Medium | Phụ thuộc FEAT-09, 31 |
| FEAT-33 | Báo cáo phân tích tâm lý học sinh | Low | Tính năng nghiên cứu sâu |
| FEAT-34 | Giao diện hiển thị đa nền tảng | High | Ràng buộc về UX/UI |
| FEAT-35 | Tính năng thảo luận nhóm học tập | Medium | Tăng tính cộng đồng |
| FEAT-36 | Module ẩn danh hóa (Anonymization) | High | Phụ thuộc FEAT-07 |
| FEAT-37 | Cổng trung chuyển mã hóa | High | Hạ tầng bảo mật |
| FEAT-38 | Đăng nhập một lần (SSO) | High | Tích hợp hệ thống trường |
| FEAT-39 | API Gateway kết nối FAP/EduNext | High | Ràng buộc tích hợp dữ liệu |
| FEAT-40 | Kiến trúc cân bằng tải (Load Balancer) | High | Ràng buộc hiệu năng 2.000 user |
| FEAT-41 | Cơ chế tự động mở rộng (Auto-scaling) | Medium | Bổ trợ cho FEAT-40 |
| FEAT-42 | Hệ thống Backup dữ liệu | High | Đảm bảo an toàn dữ liệu |
| FEAT-43 | Môi trường Sandbox thử nghiệm | Medium | Dành cho đội ngũ IT |
| FEAT-44 | Công cụ giả lập dữ liệu (Mock Data) | Medium | Phục vụ kiểm thử |
| FEAT-45 | Quy trình MLOps tự động retrain | Medium | Vận hành mô hình AI lâu dài |
| FEAT-46 | Module thu thập phản hồi (Feedback Loop) | Medium | Cải thiện độ chính xác AI |
| FEAT-47 | Giám sát hiệu năng mô hình AI | Medium | Đảm bảo AI không bị lệch (Drift) |
| FEAT-48 | Quản lý quyền truy cập (RBAC) | High | Phân quyền 6 vai trò nhóm |
| FEAT-49 | Hệ thống ghi log lỗi và cảnh báo | Medium | Vận hành kỹ thuật |

3.3. Ma trận dấu vết: NEEDs ⇒ Features

Sau khi tập yêu cầu dạng thô (NEEDs) đã được thảo luận, tinh chế và phê duyệt ở mục 3.1, đồng thời tài liệu Tầm nhìn dự án đã xác định được tập các tính năng sản phẩm (FEATs) ở mục 3.2, nhóm tiến hành thiết lập ma trận dấu vết giữa tầng NEEDs và tầng Features. Đây là ma trận dấu vết đầu tiên trong mô hình kim tự tháp yêu cầu của dự án, có vai trò bảo đảm rằng mọi tính năng được đưa vào Vision Document đều có nguồn gốc rõ ràng từ nhu cầu của stakeholder, đồng thời mọi nhu cầu nghiệp vụ cốt lõi đều đã được hiện thực hóa thành ít nhất một tính năng sản phẩm tương ứng. Theo RMP (Requirement Management Plan) của dự án, đây là một tiêu chí bắt buộc trong mạng lưới truy vết hai chiều của hệ thống yêu cầu.

### 3.3.1. Mục đích của ma trận NEEDs ⇒ FEATs

Việc thiết lập ma trận dấu vết giữa NEEDs và FEATs được thực hiện nhằm ba mục đích chính:

1.  Kiểm soát phạm vi: Đảm bảo không có FEAT nào bị “mồ côi” (không có nguồn gốc từ một NEED hợp lệ), tránh hiện tượng "gold-plating" (làm thừa tính năng không cần thiết).
2.  Xác nhận mức độ bao phủ: Xác nhận rằng các NEEDs quan trọng của dự án AI THPT FPT đã được cụ thể hóa thành các tính năng sản phẩm thực tế.
3.  Tạo nền tảng truy vết: Làm cơ sở cho các bước tiếp theo từ FEATs ⇒ Use Cases ở Chương 4.

### 3.3.2. Cơ sở và nguyên tắc ánh xạ

Đối với dự án AI giáo dục này, do tính chất phức tạp của các mô hình học máy và yêu cầu bảo mật cao của môi trường học đường, nhóm áp dụng các nguyên tắc sau:

- Ánh xạ 1-n: Một nhu cầu nghiệp vụ (STRQ) mang tính tổng quát sẽ được phân rã thành nhiều tính năng kỹ thuật (FEATs) nguyên tử hơn để dễ dàng đặc tả và kiểm thử. Ví dụ: Nhu cầu về AI chấm điểm (STRQ-06) được phân rã thành Engine OCR (FEAT-13), Giao diện so khớp (FEAT-14) và Module chỉnh điểm (FEAT-15).
- Tính khả thi: Mọi FEAT được ánh xạ phải bám sát năng lực công nghệ và hạ tầng đã xác định trong mục 9 (Other Product Requirements).
- Tính nguyên tử: Các FEAT sau khi ánh xạ phải đủ nhỏ để có thể được gán cho một thành viên phụ trách (Assigned To) và theo dõi trạng thái độc lập.

### 3.3.3. Bảng diễn giải ánh xạ từ NEEDs sang FEATs

Dưới đây là bảng ma trận dấu vết chi tiết từ 20 nhu cầu của Stakeholder sang 49 tính năng sản phẩm:

|     |     |     |     |
| --- | --- | --- | --- |
| Mã NEED (STRQ) | Mô tả nhu cầu | Các tính năng tương ứng (Mã FEAT) | Ghi chú ánh xạ |
| STRQ-01 | Dashboard xem tỉ lệ rớt môn | FEAT-01, 02, 03 | Chia ra thành bảng số liệu, phần dự báo và bộ lọc tìm kiếm. |
| STRQ-02 | AI nhắc vi phạm, người duyệt | FEAT-04, 05, 06 | Chia ra phần AI tự tìm lỗi và phần nút bấm để thầy cô duyệt. |
| STRQ-03 | Giấu tên/thông tin học sinh | FEAT-07, 08 | Tạo bộ mã hóa để giấu thông tin cá nhân khi dùng AI. |
| STRQ-04 | Cảnh báo để giảm tỉ lệ rớt | FEAT-09, 10, 11 | Kết hợp giữa việc gửi tin nhắn nhắc nhở và phân tích điểm. |
| STRQ-05 | Tự tạo đề thi nhanh | FEAT-12, 13, 14 | Chia thành kho câu hỏi và máy tự bốc đề thi ngẫu nhiên. |
| STRQ-06 | AI chấm bài, thầy cô kiểm lại | FEAT-15, 16, 17 | Chia thành máy quét ảnh bài làm và phần để thầy cô sửa điểm. |
| STRQ-07 | Chỉ ra chỗ học sinh chưa hiểu | FEAT-18, 19, 20 | Tạo biểu đồ hình nhện và danh sách các bài học cần bổ sung. |
| STRQ-08 | Chỉnh thời gian và độ khó đề | FEAT-21, 22 | Tạo các ô nhập liệu để thầy cô cài đặt thông số đề thi. |
| STRQ-09 | Trợ lý AI giải đáp 24/7 | FEAT-23, 24, 25 | Gồm khung chat hỏi đáp, tìm bằng giọng nói và tóm tắt bài. |
| STRQ-10 | Giải thích vì sao làm sai | FEAT-26, 27 | AI tự viết ra lời giải thích chi tiết cho từng câu sai. |
| STRQ-11 | Lộ trình học riêng cho mỗi bạn | FEAT-28, 29, 30 | Máy tự xếp bài tập dễ hay khó tùy theo sức học mỗi người. |
| STRQ-12 | Xem điểm và thứ hạng | FEAT-31, 32, 33 | Tạo trang cá nhân, bảng xếp hạng và phần thưởng huy hiệu. |
| STRQ-13 | Cân được 2.000 người dùng | FEAT-34, 35, 36 | Thiết kế hệ thống chịu tải để không bị sập web khi thi. |
| STRQ-14 | Chỗ chạy thử cho kỹ thuật | FEAT-37, 38 | Tạo một bản copy của hệ thống để làm nháp trước khi dùng thật. |
| STRQ-15 | Cập nhật kiến thức mới cho AI | FEAT-39, 40 | Tạo quy trình tự động nạp thêm dữ liệu để AI thông minh hơn. |
| STRQ-16 | Báo tin cho phụ huynh | FEAT-09, 41, 42 | Kết nối để gửi tin nhắn thông báo thẳng về máy bố mẹ. |
| STRQ-17 | Xem học sinh có tập trung không | FEAT-43, 44 | Dùng camera để xem bạn nào đang mệt mỏi hay chán học. |
| STRQ-18 | Chống chép bài và gian lận | FEAT-45, 46 | Máy tự phát hiện bài giống nhau hoặc soi qua webcam lúc thi. |
| STRQ-19 | Tập nói tiếng Anh với AI | FEAT-47 | AI nghe học sinh nói rồi chấm xem phát âm chuẩn chưa. |
| STRQ-20 | Kết nối với hệ thống của trường | FEAT-48, 49 | Làm đường dây kết nối để lấy dữ liệu từ hệ thống FAP có sẵn. |

3.3.4. Ma trận dấu vết tổng hợp NEEDs ⇒ FEATs

Để thuận tiện cho việc kiểm tra nhanh, nhóm tổng hợp kết quả ánh xạ dưới dạng ma trận truy vết. Trong bảng dưới đây, mỗi nhu cầu (STRQ) được xác nhận đã được bao phủ bởi các tính năng (FEAT) cụ thể. Bảng 1.7. Ma trận dấu vết NEEDs ⇒ FEAT

|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NEED \\ FEAT | F01 | F02 | F03 | F04 | F05 | F06 | F07 | F08 | F09 | F10 | F11 | F12 | F13 | F14 | F15 | F16 | F17 | F18 | F19 | F20 |
| STRQ-01 | X   | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-02 |     |     |     | X   | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-03 |     |     |     |     |     |     | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-04 |     | X   |     |     |     |     |     |     | X   | X   | X   |     |     |     |     |     |     |     |     |     |
| STRQ-05 |     |     |     |     |     |     |     |     |     | X   | X   | X   |     |     |     |     |     |     |     |     |
| STRQ-06 |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   | X   |     |     |     |     |     |
| STRQ-07 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |     |     |
| STRQ-08 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-09 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   |
| STRQ-10 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-11 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-12 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-13 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-14 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-15 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-16 |     |     |     |     |     |     |     |     | X   |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-17 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-18 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   |     |     |     |
| STRQ-19 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |     |     |
| STRQ-20 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |

Bảng 1.8. Ma trận dấu vết NEEDs ⇒ FEATs (Phần 2: F21 - F49)

|     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NEED \\ FEAT | F21-25 | F26-27 | F28-30 | F31-33 | F34-35 | F36-37 | F38-39 | F40-42 | F43-44 | F45-47 | F48-49 |
| STRQ-01 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-02 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-03 |     |     |     |     |     | X   |     |     |     |     |     |
| STRQ-04 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-05 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-06 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-07 | X   |     |     |     |     |     |     |     |     |     |     |
| STRQ-08 | X   |     |     |     |     |     |     |     |     |     |     |
| STRQ-09 | X   |     |     |     |     |     |     |     |     |     |     |
| STRQ-10 |     | X   |     |     |     |     |     |     |     |     |     |
| STRQ-11 | X   |     | X   |     |     |     |     |     |     |     |     |
| STRQ-12 |     |     | X   |     | X   |     |     |     |     |     |     |
| STRQ-13 |     |     |     |     | X   |     |     | X   |     |     | X   |
| STRQ-14 |     |     |     |     |     |     |     |     | X   |     |     |
| STRQ-15 |     |     |     |     |     |     |     |     |     | X   |     |
| STRQ-16 |     |     |     | X   |     |     |     |     |     |     |     |
| STRQ-17 |     |     |     | X   |     |     |     |     | X   |     |     |
| STRQ-18 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-19 |     |     |     |     |     |     |     |     |     |     |     |
| STRQ-20 |     |     |     |     |     |     | X   |     |     |     | X   |

3.3.5. Nhận xét về ma trận dấu vết NEEDs ⇒ FEATs

Từ ma trận dấu vết tổng hợp (Phần 1 và Phần 2), nhóm dự án rút ra các nhận xét quan trọng sau:

- Tính đầy đủ (Completeness): 100% các nhu cầu chiến lược (STRQs) đã được ánh xạ sang ít nhất một tính năng sản phẩm (FEATs). Điều này bảo đảm không có mong đợi nào của nhà trường bị bỏ sót.
- Tính hợp lý (Correctness): 100% các FEATs (từ F01 đến F49) đều có nguồn gốc từ nhu cầu thực tế, loại bỏ hoàn toàn các tính năng dư thừa (Gold-plating).
- Nguyên tắc tinh chế (Refinement): Nhiều nhu cầu phức tạp như STRQ-01 (Dashboard), STRQ-06 (Chấm điểm AI) đã được phân rã thành chuỗi các FEATs nguyên tử. Cách làm này giúp giảm độ phức tạp khi thiết kế hệ thống và tạo điều kiện thuận lợi cho việc kiểm thử đơn vị sau này.

3.3.6. Kết luận của mục 3.3

Việc xây dựng ma trận dấu vết giữa NEEDs và FEATs đã giúp nhóm kiểm soát tốt bước chuyển từ nhu cầu nghiệp vụ của stakeholder sang các tính năng mức cao của Hệ thống AI Giáo dục THPT FPT. Ma trận này là kim chỉ nam để nhóm thiết lập các mối liên kết tiếp theo giữa Features ⇒ Use Cases trong Chương 4. Theo đúng định hướng của RMP, ma trận này được duy trì song song trên file quản lý tổng và hệ thống GitHub của nhóm để phân tích ảnh hưởng (Impact Analysis) tức thì khi có yêu cầu thay đổi từ phía giáo viên hoặc Ban giám hiệu.

# CHƯƠNG 4: ĐẶC TẢ YÊU CẦU (USE CASES & SUPPLEMENTARY)

## 4.1. TÀI LIỆU ĐẶC TẢ USE CASE (Use Case Specification)

Theo hướng dẫn của học phần, tài liệu Use Case Specification là thành phẩm chi tiết hóa các tính năng đã xác định ở Vision Document thành các tương tác cụ thể. Đây là cơ sở để nhóm xây dựng các kịch bản (Scenarios) và bộ kiểm thử (Test Cases) ở Chương 5. Với dự án AI THPT FPT, đây là phần việc trọng tâm do các thành viên đóng vai trò BA / Requirements Specifier phụ trách chính.

### 4.1.1. Nguyên tắc xây dựng tài liệu Use Case

Nhóm dự án tuân thủ mẫu IBM/RUP Use Case Specification. Mỗi Use Case sẽ mô tả chi tiết:

- Mô tả ngắn: Mục đích của Use Case.
- Luồng sự kiện chính (Basic Flow): Trình tự tương tác lý tưởng giữa tác nhân và hệ thống AI.
- Luồng thay thế/ngoại lệ (Alternative/Exception Flows): Xử lý các tình huống lỗi hoặc rẽ nhánh (ví dụ: AI không nhận diện được chữ viết, lỗi kết nối API FAP).
- Điều kiện trước/sau: Trạng thái hệ thống cần có để bắt đầu và kết quả sau khi hoàn thành.

Theo lý thuyết, Use Case chỉ tập trung vào Yêu cầu chức năng (Hệ thống làm được gì). Các yếu tố về Yêu cầu phi chức năng (Hệ thống chạy nhanh thế nào, bảo mật ra sao) sẽ được đặc tả riêng tại tài liệu Supplementary Requirements (Mục 4.4).

### 4.1.2. Danh sách Use Case đề xuất cho hệ thống AI THPT FPT

Dựa trên bộ 49 FEATs đã được tinh chế, nhóm đề xuất các nhóm Use Case cốt lõi để đưa vào đặc tả chi tiết như sau:

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Nhóm Module | Mã UC | Tên Use Case | FEATs chức năng hợp thành | Tác nhân chính |
| I. Quản lý Tài khoản | UC-01 | Đăng ký tài khoản mới | F48 | Học sinh/Phụ huynh |
|     | UC-02 | Đăng nhập hệ thống | F38 | Tất cả |
|     | UC-03 | Quản lý hồ sơ cá nhân | F48 | Tất cả |
|     | UC-04 | Khôi phục mật khẩu | F37 | Tất cả |
|     | UC-05 | Phân quyền người dùng | F48 | IT Admin |
| II. Quản trị & Giám sát | UC-06 | Xem Dashboard rủi ro học tập | F01, F03 | BGH |
|     | UC-07 | Nhận định dự báo xu hướng điểm số | F02 | BGH |
|     | UC-08 | Phê duyệt đề xuất can thiệp | F04, F05 | BGH |
|     | UC-09 | Tra cứu nhật ký hoạt động | F06 | BGH/Admin |
|     | UC-10 | Xuất báo cáo thống kê định kỳ | F08 | BGH/Giáo viên |
|     | UC-11 | Gửi thông báo nhắc nhở học vụ | F09 | Giáo viên |
| III. Khảo thí & AI Grading | UC-12 | Soạn thảo câu hỏi hỗ trợ bởi AI | F10, F12 | Giáo viên |
|     | UC-13 | Thiết lập ngân hàng đề thi | F10 | Giáo viên |
|     | UC-14 | Tự động sinh đề thi theo ma trận | F11 | Giáo viên |
|     | UC-15 | Giám sát thi trực tuyến (Proctoring) | F17 | Giáo viên |
|     | UC-16 | Nộp bài làm (Quét ảnh/Tải file) | F13 | Học sinh |
|     | UC-17 | Chấm điểm tự luận bằng AI | F14 | Giáo viên |
|     | UC-18 | Thẩm định và sửa điểm thủ công | F15 | Giáo viên |
|     | UC-19 | Quét đạo văn và gian lận | F16 | Giáo viên |
| IV. Học tập & AI Tutor | UC-20 | Hỏi đáp kiến thức với AI Tutor | F19, F27 | Học sinh |
|     | UC-21 | Tìm kiếm bài giảng đa phương thức | F20 | Học sinh |
|     | UC-22 | Tóm tắt nội dung bài học tự động | F21 | Học sinh |
|     | UC-23 | Làm bài tập thích ứng (Adaptive) | F22 | Học sinh |
|     | UC-24 | Xem biểu đồ năng lực cá nhân | F23, F24 | Học sinh |
|     | UC-25 | Nhận lộ trình học tập gợi ý | F25, F26 | Học sinh |
|     | UC-26 | Đua top và nhận huy hiệu học tập | F29, F30 | Học sinh |
|     | UC-27 | Thảo luận nhóm trên diễn đàn | F35 | Học sinh |
| V. Kết nối & Tích hợp | UC-28 | Xem tiến độ học tập của con | F31 | Phụ huynh |
|     | UC-29 | Cấu hình nhận thông báo (Zalo/SMS) | F32 | Phụ huynh |
|     | UC-30 | Đồng bộ danh sách lớp từ FAP | F39 | IT Admin |

### 4.1.3. ĐẶC TẢ CHI TIẾT CÁC USE CASE (DỰ ÁN AI THPT FPT)

NHÓM I: QUẢN LÝ TÀI KHOẢN & HỆ THỐNG

UC-01: Đăng ký tài khoản mới

Brief Description: Cho phép Học sinh/Phụ huynh tạo tài khoản để truy cập hệ thống.

Basic Flow: 1. Người dùng chọn Đăng ký; 2. Nhập thông tin (Họ tên, SĐT, Email, Password); 3. Hệ thống kiểm tra định dạng; 4. Hệ thống kiểm tra trùng lặp; 5. Tạo tài khoản và thông báo thành công.

Alternative Flow: Nhập sai định dạng Email/SĐT -> Hệ thống báo lỗi và yêu cầu nhập lại.

Pre-conditions: Người dùng chưa có tài khoản.

Post-conditions: Tài khoản mới được lưu vào database.

UC-02: Đăng nhập hệ thống

Brief Description: Xác thực người dùng truy cập.

Basic Flow: 1. Nhập Email/SĐT và mật khẩu; 2. Hệ thống kiểm tra thông tin; 3. Điều hướng người dùng vào Dashboard theo vai trò (Role).

Alternative Flow: Sai mật khẩu quá 5 lần -> Khóa tài khoản tạm thời 15 phút.

Pre-conditions: Đã có tài khoản.

Post-conditions: Phiên làm việc (Session) được thiết lập.

UC-03: Quản lý hồ sơ cá nhân

Brief Description: Cập nhật thông tin cá nhân, ảnh đại diện.

Basic Flow: 1. Chọn Hồ sơ; 2. Chỉnh sửa thông tin; 3. Hệ thống lưu thay đổi.

Pre-conditions: Đã đăng nhập.

UC-04: Khôi phục mật khẩu

Brief Description: Cấp lại mật khẩu qua OTP Email.

Basic Flow: 1. Chọn Quên mật khẩu; 2. Nhập Email; 3. Nhập mã OTP hệ thống gửi; 4. Thiết lập mật khẩu mới.

UC-05: Phân quyền người dùng (RBAC)

Brief Description: Admin gán quyền (BGH, Giáo viên, Học sinh) cho tài khoản.

Basic Flow: 1. Chọn tài khoản; 2. Chọn vai trò; 3. Hệ thống cập nhật quyền truy cập chức năng.

NHÓM II: QUẢN TRỊ & GIÁM SÁT (BGH)

UC-06: Xem Dashboard rủi ro học tập

Brief Description: Hiển thị biểu đồ thống kê học sinh có nguy cơ trượt môn.

Basic Flow: 1. Vào Dashboard; 2. Hệ thống tải dữ liệu phân tích từ AI; 3. BGH xem biểu đồ trực quan.

UC-07: Nhận định dự báo xu hướng điểm số

Brief Description: AI đưa ra dự báo điểm số cuối kỳ dựa trên dữ liệu quá khứ.

Basic Flow: 1. Chọn lớp/môn; 2. Hệ thống tính toán và hiển thị đường biểu đồ dự báo.

UC-08: Phê duyệt đề xuất can thiệp

Brief Description: BGH duyệt các biện pháp hỗ trợ học sinh (như phụ đạo) do AI đề xuất.

Basic Flow: 1. Xem danh sách đề xuất; 2. Nhấn Phê duyệt; 3. Hệ thống gửi thông báo cho Giáo viên liên quan.

UC-09: Tra cứu nhật ký hoạt động (Audit Log)

Brief Description: Xem ai đã tác động vào hệ thống/điểm số.

Basic Flow: 1. Chọn khoảng thời gian; 2. Hệ thống liệt kê danh sách các thao tác (User, Action, Time).

UC-10: Xuất báo cáo thống kê định kỳ

Brief Description: Xuất file PDF/Excel báo cáo tình hình học tập.

Basic Flow: 1. Chọn loại báo cáo; 2. Nhấn Xuất file; 3. Hệ thống tạo và tải tệp về máy.

UC-11: Gửi thông báo nhắc nhở học vụ

Brief Description: Gửi thông báo tự động cho học sinh chưa nộp bài.

Basic Flow: 1. Quét danh sách chưa nộp; 2. Nhấn Gửi thông báo; 3. Hệ thống gửi notification qua App/Zalo.

NHÓM III: KHẢO THÍ & AI GRADING (GIÁO VIÊN)

UC-12: Soạn thảo câu hỏi hỗ trợ bởi AI

Brief Description: Giáo viên nhập nội dung thô, AI tự chuyển thành câu hỏi trắc nghiệm/tự luận.

UC-13: Thiết lập ngân hàng đề thi

Brief Description: Quản lý danh mục câu hỏi theo khối lớp và độ khó.

UC-14: Tự động sinh đề thi theo ma trận

Brief Description: Hệ thống tự bốc câu hỏi từ ngân hàng theo tỉ lệ % độ khó yêu cầu.

UC-15: Giám sát thi trực tuyến (AI Proctoring)

Brief Description: Sử dụng Camera nhận diện khuôn mặt và cảnh báo nếu học sinh gian lận (quay cóp, có người lạ).

UC-16: Nộp bài làm (Quét ảnh/Tải file)

Brief Description: Học sinh dùng app chụp ảnh bài làm tay và upload lên hệ thống.

UC-17: Chấm điểm tự luận bằng AI

Brief Description: AI quét OCR chữ viết, so khớp đáp án và chấm điểm dự kiến.

UC-18: Thẩm định và sửa điểm thủ công

Brief Description: Giáo viên xem lại kết quả AI chấm, điều chỉnh điểm nếu cần và chốt điểm.

UC-19: Quét đạo văn và gian lận

Brief Description: Hệ thống so sánh bài làm của các học sinh với nhau và với Internet để báo cáo % trùng lặp.

NHÓM IV: HỌC TẬP & AI TUTOR (HỌC SINH)

UC-20: Hỏi đáp kiến thức với AI Tutor

Brief Description: Chat trực tiếp với AI để giải đáp thắc mắc bài học 24/7.

UC-21: Tìm kiếm bài giảng đa phương thức

Brief Description: Tìm tài liệu bằng từ khóa, giọng nói hoặc hình ảnh bìa sách.

UC-22: Tóm tắt nội dung bài học tự động

Brief Description: AI đọc tài liệu dài và tóm tắt thành các ý chính (Bullet points) cho học sinh dễ nắm bắt.

UC-23: Làm bài tập thích ứng (Adaptive Test)

Brief Description: Đề bài thay đổi độ khó dựa trên kết quả câu trước (Đúng thì câu sau khó hơn, sai thì dễ hơn).

UC-24: Xem biểu đồ năng lực cá nhân (Radar Chart)

Brief Description: Hiển thị thế mạnh/điểm yếu của học sinh qua biểu đồ đa giác.

UC-25: Nhận lộ trình học tập gợi ý

Brief Description: AI chỉ ra những lỗ hổng kiến thức và gợi ý các bài giảng cần học lại.

UC-26: Đua Top và nhận huy hiệu

Brief Description: Hệ thống vinh danh các cá nhân chăm chỉ hoặc có điểm số cao.

UC-27: Thảo luận nhóm trên diễn đàn

Brief Description: Học sinh tạo chủ đề trao đổi, giáo viên vào giải đáp.

NHÓM V: KẾT NỐI & TÍCH HỢP (PHỤ HUYNH/IT)

UC-28: Xem tiến độ học tập của con

Brief Description: Phụ huynh đăng nhập để xem điểm và nhận xét của giáo viên.

UC-29: Cấu hình nhận thông báo (Zalo/SMS)

Brief Description: Phụ huynh chọn các loại thông báo muốn nhận (Điểm thi, Nghỉ học, Cảnh báo rủi ro).

UC-30: Đồng bộ dữ liệu học vụ từ FAP

Brief Description: IT Admin kích hoạt lệnh API để lấy danh sách học sinh và thời khóa biểu từ hệ thống cũ sang hệ thống AI.

4.2. Ma trận dấu vết: Features ⇒ Use Cases

Sau khi đã xác lập tài liệu Tầm nhìn dự án (Vision Document) và chi tiết hóa các Trường hợp sử dụng (Use Cases), nhóm thực hiện xây dựng ma trận dấu vết giữa tầng Features và tầng Use Cases. Đây là bước mắt xích quan trọng trong mô hình kim tự tháp yêu cầu, nhằm đảm bảo mọi khả năng cốt lõi của hệ thống đều được cụ thể hóa thành các kịch bản tương tác thực tế giữa người dùng và trí tuệ nhân tạo.

### 4.2.1. Mục đích của ma trận Features ⇒ Use Cases

Việc xây dựng ma trận dấu vết tại giai đoạn này hướng tới ba mục tiêu chiến lược:

- Tính minh bạch trong phân rã: Xác nhận các tính năng sản phẩm không chỉ dừng lại ở mức phát biểu khái quát mà đã được hiện thực hóa thành chuỗi hành vi chức năng cụ thể, giúp đội ngũ phát triển dễ dàng hình dung quy trình vận hành.
- Kiểm soát phạm vi (Scope Control): Phát hiện và loại bỏ các Use Case "mồ côi" không đem lại giá trị cho Feature nào, đồng thời đảm bảo không có Feature chức năng nào bị bỏ sót trong quá trình thiết kế kịch bản.
- Nền tảng cho quản lý thay đổi: Tạo cơ sở dữ liệu để thực hiện phân tích ảnh hưởng (Impact Analysis). Khi một Feature thay đổi, nhóm có thể truy vết ngay lập tức các Use Case liên quan cần được cập nhật, đảm bảo tính nhất quán theo đúng quy trình RMP (Requirement Management Plan).

### 4.2.2. Cơ sở và nguyên tắc ánh xạ

Dựa trên nền tảng lý thuyết về kỹ nghệ yêu cầu, nhóm xác định Use Case là sự chi tiết hóa các Features/NEEDs dưới góc độ tương tác người - máy. Tại hệ thống AI THPT FPT, một Feature phức tạp thường được phân rã thành nhiều Use Case để đảm bảo tính đơn nhiệm và dễ kiểm thử; ngược lại, một Use Case cũng có thể hỗ trợ thực hiện nhiều Features có cùng mục tiêu nghiệp vụ.

Nhóm áp dụng các nguyên tắc ánh xạ nghiêm ngặt sau:

- Nguyên tắc nguồn gốc: Mọi Use Case bắt buộc phải được truy vết ngược về ít nhất một Feature chức năng ở tầng trên.
- Nguyên tắc bao phủ: Tất cả các Feature thuộc nhóm "Chức năng" (Functional Features) phải được ánh xạ hoàn toàn xuống tầng Use Case.
- Nguyên tắc phân tách yêu cầu phi chức năng: Các Feature liên quan đến hạ tầng ngầm, bảo mật hệ thống hoặc quy trình vận hành tự động (như tự động sao lưu, cân bằng tải, MLOps) sẽ không ánh xạ trực tiếp xuống Use Case tương tác người dùng. Thay vào đó, chúng sẽ được truy vết sang tài liệu Supplementary Requirements (SUPL) ở mục 4.4 để đảm bảo tính chính xác về mặt kỹ thuật.

### 4.2.3. Bảng diễn giải ánh xạ từ Features sang Use Cases

Bảng dưới đây trình bày cách thức nhóm ánh xạ các tính năng chính của hệ thống AI sang các kịch bản sử dụng cụ thể, làm rõ mối liên hệ giữa mục tiêu hệ thống và hành động của các tác nhân (BGH, Giáo viên, Học sinh, Phụ huynh).

### Bảng 4.2.1. Diễn giải chi tiết ánh xạ FEATs ⇒ UCs

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Nhóm Tính năng | Mã FEAT | Tên Feature | Use Case tương ứng | Diễn giải logic |
| Quản trị Thông minh | F01-F03 | Hệ thống Dashboard & Dự báo | UC-06, UC-07 | Chuyển đổi các chỉ số thống kê và thuật toán dự báo rủi ro thành giao diện trực quan cho BGH. |
| Khảo thí AI | F10-F12 | Ngân hàng câu hỏi & Sinh đề | UC-12, UC-13, UC-14 | Phân rã khả năng lưu trữ tri thức và engine sinh đề thành quy trình soạn thảo - thiết lập đề thi. |
|     | F13-F14 | OCR & So khớp chấm điểm | UC-16, UC-17 | Cụ thể hóa công nghệ nhận diện chữ viết tay thành hành vi nộp bài của HS và chấm bài của GV. |
|     | F16-F17 | Proctoring & Đạo văn | UC-15, UC-19 | Hiện thực hóa các tính năng giám sát an ninh phòng thi và kiểm soát liêm chính học thuật. |
| AI Tutor cá nhân hóa | F19-F21 | Chatbot LLM & Tóm tắt nội dung | UC-20, UC-22 | Chuyển đổi khả năng xử lý ngôn ngữ tự nhiên thành kịch bản hỏi đáp và tóm tắt bài giảng. |
|     | F22-F26 | Adaptive Learning & Radar năng lực | UC-23, UC-24, UC-25 | Tối ưu hóa thuật toán gợi ý lộ trình thành chuỗi hành động làm bài và xem báo cáo cá nhân. |
| Kết nối & Vận hành | F31-F35 | Portal & Diễn đàn thảo luận | UC-27, UC-28, UC-29 | Xây dựng môi trường tương tác trực tiếp cho Phụ huynh và cộng đồng học tập của Học sinh. |
|     | F39 | Đồng bộ hệ thống FAP | UC-30 | Hiện thực hóa khả năng tích hợp dữ liệu thông qua thao tác vận hành của quản trị viên. |

### 4.2.4. Ma trận dấu vết tổng hợp Features ⇒ Use Cases

Dưới đây là bảng tổng hợp mối liên kết giữa các tính năng mức cao (Features) và các kịch bản sử dụng chi tiết (Use Cases). Ký hiệu “X” xác nhận rằng tính năng ở hàng tương ứng đã được hiện thực hóa bởi Use Case ở cột tương ứng.

Bảng A: Ánh xạ FEATs từ F01 đến F25 sang các Use Cases

|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FEAT \\ UC | 01-05 | 06  | 07  | 08  | 09  | 10  | 11  | 12  | 13  | 14  | 15  | 16  | 17  | 18  | 19  | 20  | 21  | 22  | 23  | 24  | 25  |
| F01-F03 |     | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| F04-F06 |     |     |     | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| F08-F09 |     |     |     |     |     | X   | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| F10-F12 |     |     |     |     |     |     |     | X   | X   | X   |     |     |     |     |     |     |     |     |     |     |     |
| F13-F14 |     |     |     |     |     |     |     |     |     |     |     | X   | X   |     |     |     |     |     |     |     |     |
| F15 |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |     |     |     |     |     |     |     |
| F16 |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |     |     |     |     |     |     |
| F17 |     |     |     |     |     |     |     |     |     |     | X   |     |     |     |     |     |     |     |     |     |     |
| F19-F21 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   | X   |     |     |     |
| F22-F23 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   |     |
| F25-F26 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |

Bảng B: Ánh xạ FEATs từ F26 đến F49 sang các Use Cases

|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FEAT \\ UC | 01  | 02  | 03  | 04  | 05  | 21  | 22  | 23  | 24  | 25  | 26  | 27  | 28  | 29  | 30  |
| F27-F30 |     |     |     |     |     |     |     |     |     |     | X   |     |     |     |     |
| F31-F33 |     |     |     |     |     |     |     |     |     |     |     |     | X   | X   |     |
| F35 |     |     |     |     |     |     |     |     |     |     |     | X   |     |     |     |
| F38 |     | X   |     |     |     |     |     |     |     |     |     |     |     |     |     |
| F39 |     |     |     |     |     |     |     |     |     |     |     |     |     |     | X   |
| F48 | X   |     | X   |     | X   |     |     |     |     |     |     |     |     |     |     |
| F36-37\* |     |     |     | X   |     |     |     |     |     |     |     |     |     |     |     |
| F40-47\* |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |

Dưới đây là nội dung điều chỉnh cho phần Nhận xét (4.2.5) và Kết luận (4.2.6), được viết lại để khớp hoàn toàn với hệ thống AI THPT FPT và danh sách 30 Use Cases bạn đã chọn, đồng thời giữ nguyên phong cách học thuật của mẫu Vinamilk.

### 4.2.5. Nhận xét về ma trận FEATs ⇒ UCs

Từ ma trận dấu vết nhị phân đã thiết lập, nhóm dự án rút ra một số nhận xét quan trọng:

- Thứ nhất, hầu hết các FEAT chức năng của hệ thống AI THPT FPT đã được hiện thực hóa thành ít nhất một Use Case cụ thể. Điều này chứng minh rằng tập hợp 30 Use Cases tại mục 4.1 không bị rời rạc hay dư thừa, mà bám sát vào phạm vi giải pháp thông minh đã xác định trong Vision Document.
- Thứ hai, có những FEAT mức cao được phân rã thành nhiều UC để đảm bảo tính chi tiết. Điển hình như FEAT-19 (AI Tutor) được cụ thể hóa thông qua UC-20 (Hỏi đáp) và UC-22 (Tóm tắt nội dung), giúp tách biệt các hành vi tương tác khác nhau của học sinh với trợ lý ảo.
- Thứ ba, ghi nhận sự hội tụ của nhiều FEAT vào một Use Case duy nhất. Ví dụ, FEAT-13 (OCR) và FEAT-14 (Chấm điểm AI) cùng hội tụ vào UC-17 – Chấm điểm tự luận bằng AI. Cách ánh xạ này hoàn toàn phù hợp với bản chất của Use Case: bao quát trọn vẹn một mục tiêu tương tác từ lúc hệ thống nhận diện dữ liệu thô cho đến khi trả về kết quả chấm điểm cuối cùng.
- Thứ tư, các FEAT từ F36 đến F47 liên quan đến bảo mật dữ liệu học đường, hạ tầng AI và quy trình MLOps không xuất hiện dấu “X” trong ma trận này. Đây là sự chủ động của nhóm nhằm tách biệt các yêu cầu phi chức năng (Non-functional Requirements). Các FEAT này sẽ được truy vết trong ma trận Features ⇒ Supplementary Requirements ở mục 4.5, tuân thủ nghiêm ngặt quy tắc của RMP: FEAT có thể ánh xạ đến UC hoặc SUPL tùy thuộc vào bản chất của yêu cầu.

### 4.2.6. Kết luận của mục 4.2

Việc thiết lập ma trận dấu vết giữa Features và Use Cases đã giúp nhóm bảo đảm rằng các tính năng đột phá của hệ thống AI THPT FPT không chỉ tồn tại ở mức ý tưởng khái quát, mà đã thực sự được cụ thể hóa thành các kịch bản hành vi có thể đặc tả và kiểm thử.

Ma trận này đóng vai trò là "xương sống" để nhóm tiếp tục triển khai các tầng dưới của kim tự tháp yêu cầu, đặc biệt là việc xây dựng các kịch bản kiểm thử (Scenarios) và bộ dữ liệu mẫu ở Chương 5. Đồng thời, đây cũng là công cụ hữu hiệu để kiểm soát phạm vi và tính toàn vẹn của hệ thống trong suốt các giai đoạn baseline của dự án.

Dưới đây là nội dung mục 4.3 được viết lại hoàn toàn cho dự án Hệ thống hỗ trợ học tập và khảo thí thông minh AI THPT FPT. Lời văn đã được tinh chỉnh để làm nổi bật các yếu tố công nghệ AI, Dashboard quản trị và trải nghiệm học tập cá nhân hóa, đúng theo phong cách chuyên nghiệp của báo cáo mẫu.

4.3. Yêu cầu giao diện và Mockup mô phỏng (Figma)

Trong dự án Hệ thống AI THPT FPT, giao diện người dùng (User Interface - UI) không chỉ đóng vai trò là lớp vỏ thẩm mỹ mà còn là cầu nối quan trọng để hiện thực hóa các tương tác phức tạp giữa con người và trí tuệ nhân tạo. Theo kế hoạch quản lý dự án, hoạt động đặc tả Use Cases và thiết kế Mockup được triển khai song song trong giai đoạn Elaboration. Việc này nhằm bảo đảm các yêu cầu chức năng đặc thù như chấm điểm AI, biểu đồ năng lực Radar hay Chatbot Tutor có thể được hình dung một cách trực quan, giúp các stakeholder (BGH, Giáo viên, Học sinh) dễ dàng thẩm định yêu cầu trước khi tiến hành lập trình.

### 4.3.1. Mục đích của việc xây dựng mockup giao diện

Việc xây dựng hệ thống mockup trên Figma cho dự án AI THPT FPT hướng tới ba mục tiêu chiến lược:

- Trực quan hóa công nghệ AI: Chuyển đổi các thuật toán phức tạp (như chấm điểm OCR, Adaptive Learning) thành các màn hình thao tác dễ hiểu cho Giáo viên và Học sinh, giúp họ hình dung cách AI hỗ trợ trong học tập.
- Thẩm định quy trình tương tác: Giúp nhóm thu thập phản hồi sớm từ Stakeholder về luồng trải nghiệm, đặc biệt là các tính năng mới lạ như giám sát thi trực tuyến bằng AI (AI Proctoring) hoặc hỏi đáp với AI Tutor.
- Bảo đảm tính nhất quán của chuỗi dấu vết: Mockup đóng vai trò là công cụ kiểm chứng sự logic xuyên suốt từ BPMN → FEATs → UCs → UI. Đây là thành phẩm bắt buộc để đạt được mốc Baseline 2 trong quy trình RMP của nhóm.

### 4.3.2. Cơ sở xác định yêu cầu giao diện

Giao diện của hệ thống AI THPT FPT được xác định dựa trên bốn căn cứ cốt lõi:

- Hệ thống NEEDs và FEATs: Các tính năng đã được phê duyệt ở chương trước như: Dashboard rủi ro học tập (F01), Chấm điểm tự luận AI (F14), AI Tutor (F19) và Biểu đồ năng lực Radar (F23).
- Danh sách Use Cases chi tiết: Mỗi màn hình giao diện được thiết kế để hỗ trợ tối ưu cho một hoặc nhiều Use Case cụ thể (như UC-14 Chấm điểm AI hoặc UC-24 Xem biểu đồ năng lực).
- Quy trình nghiệp vụ BPMN: Luồng vận hành từ lúc Giáo viên soạn đề, sinh đề tự động, cho đến khi Học sinh nộp bài và AI thực hiện chấm điểm tự động.
- Tiêu chuẩn Supplementary Requirements: Các yêu cầu về tính tiện dụng (Usability), khả năng truy cập nhanh và giao diện đáp ứng (Responsive) trên cả web và mobile.

### 4.3.3. Các yêu cầu giao diện chính của hệ thống

Dựa trên các căn cứ trên, nhóm xác định các tiêu chí giao diện trọng tâm:

- Giao diện Quản trị trực quan (Dashboard-centric): Dành cho BGH và Giáo viên, giao diện phải trình bày các số liệu thống kê dưới dạng biểu đồ (Chart), thanh trạng thái màu sắc để cảnh báo rủi ro học tập một cách nhanh chóng nhất.
- Trải nghiệm học tập cá nhân hóa: Giao diện của Học sinh cần sự trẻ trung, hiện đại (phù hợp với môi trường FPT), tập trung vào các khu vực hiển thị lộ trình học tập, bảng xếp hạng (Gamification) và cửa sổ Chatbot AI trực quan.
- Hỗ trợ tương tác đa phương thức: Giao diện phải tích hợp các vùng chức năng cho phép upload ảnh bài làm, ghi âm giọng nói (luyện speaking) và hiển thị kết quả xử lý của AI một cách tức thời (Real-time feedback).
- Sự rõ ràng trong phản hồi của AI: Khi AI chấm điểm hoặc tóm tắt bài học, giao diện phải có các chỉ dẫn rõ ràng (highlight từ sai, gợi ý sửa lỗi) để người dùng không cảm thấy "máy móc" mà thấy được sự hỗ trợ hữu ích.

### 4.3.4. Danh sách các màn hình mockup chính

Để mô phỏng đầy đủ hệ sinh thái học tập thông minh, nhóm xây dựng bộ mockup Figma gồm các nhóm màn hình chính sau:

(1) Màn hình Dashboard Quản trị & Cảnh báo rủi ro (Dành cho BGH/Giáo viên) Đây là màn hình "đầu não", nơi hiển thị tổng quan tình hình học tập toàn khối/lớp. Các biểu đồ nhiệt (Heatmap) và danh sách học sinh cần quan tâm được hiển thị ưu tiên. Màn hình này hỗ trợ trực tiếp cho UC-06 – Xem Dashboard rủi ro học tập và UC-07 – Nhận định dự báo xu hướng điểm số.

(2) Màn hình Trung tâm Khảo thí & Chấm điểm AI (Dành cho Giáo viên) Khu vực hiển thị danh sách bài thi và giao diện so khớp chấm điểm. Mockup mô phỏng cách AI quét chữ viết tay, bôi màu các đoạn văn đạt yêu cầu và hiển thị khung nhận xét tự động. Màn hình hỗ trợ UC-14 – Chấm điểm bài làm tự luận bằng AI và UC-18 – Thẩm định điểm số.

(3) Màn hình AI Tutor & Lộ trình học tập (Dành cho Học sinh) Giao diện bao gồm cửa sổ chat thông minh và biểu đồ Radar năng lực 5 cạnh. Tại đây, học sinh nhìn thấy các "lỗ hổng" kiến thức được AI chỉ ra và các bài giảng gợi ý. Màn hình hỗ trợ UC-20 – Hỏi đáp với AI Tutor và UC-24 – Xem biểu đồ năng lực cá nhân.

(4) Màn hình Giám sát thi AI Proctoring Mô phỏng giao diện làm bài thi của học sinh với khung camera nhận diện khuôn mặt ở góc màn hình và các cảnh báo nhắc nhở từ AI khi phát hiện dấu hiệu không tập trung. Màn hình hỗ trợ UC-15 – Giám sát thi trực tuyến.

#### Hình 4.3.1. Màn hình Dashboard phân tích học tập của hệ thống AI THPT FPT

#### Hình 4.3.2 màn hình tiến trình học tập

#### Hình 4.3.3 danh sách bài tập

Hình4.3.4 kết quả học tập

## 4.4. TÀI LIỆU YÊU CẦU BỔ SUNG / PHI CHỨC NĂNG (Supplementary Requirements Specification – theo mẫu IBM)

Công ty: Trường THPT FPT (FPT High School)

Dự án: Hệ thống hỗ trợ học tập và khảo thí thông minh dựa trên trí tuệ nhân tạo (AI-Powered Learning & Assessment System)

Tên tài liệu: Supplementary Specification

Phiên bản: 1.0

Lịch sử sửa đổi

| Ngày | Phiên bản | Mô tả | Tác giả |
| --- | --- | --- | --- |
| 15/04/2026 | 1.0 | Khởi tạo tài liệu SUPL cho hệ thống AI THPT FPT | Nhóm dự án |

1\. Giới thiệu (Introduction)

Tài liệu này ghi nhận các yêu cầu hệ thống không được mô tả trực tiếp trong mô hình Use Case, tập trung vào các thuộc tính chất lượng (FURPS+), ràng buộc hạ tầng AI và các quy định an toàn dữ liệu học đường.

1.3. Định nghĩa và từ viết tắt

- LMS (Learning Management System): Hệ thống quản lý học tập.
- OCR (Optical Character Recognition): Nhận dạng chữ viết tay bài thi.
- LLM (Large Language Model): Mô hình ngôn ngữ lớn dùng cho AI Tutor.
- MLOps: Quy trình vận hành và tái huấn luyện mô hình AI.

2\. Chức năng (Functionality)

- SUPL-FUNC-01 – Độ chính xác của thuật toán AI: AI chấm điểm tự luận phải đạt độ chính xác tối thiểu 90% so với đáp án mẫu và cho phép giáo viên can thiệp điều chỉnh.
- SUPL-FUNC-02 – Khả năng tích hợp FAP/EduNext: Hệ thống phải đồng bộ dữ liệu học sinh, thời khóa biểu từ hệ thống FAP của trường qua API an toàn.
- SUPL-FUNC-03 – Bảo mật phân quyền: Phân rõ quyền hạn giữa BGH (xem Dashboard toàn trường), Giáo viên (quản lý lớp, chấm thi) và Học sinh (học tập, làm bài).

3\. Tính dễ sử dụng (Usability)

- SUPL-USE-01 – Giao diện đặc thù FPT: Giao diện phải sử dụng bộ nhận diện thương hiệu FPT Education, hỗ trợ chế độ Dark Mode để học sinh làm bài ban đêm không mỏi mắt.
- SUPL-USE-02 – Trải nghiệm AI không rào cản: Chatbot AI Tutor phải có giao diện trò chuyện tự nhiên, hỗ trợ gợi ý câu hỏi để học sinh dễ dàng bắt đầu hội thoại.
- SUPL-USE-03 – Khả năng đáp ứng (Responsive): Hệ thống phải hiển thị tốt trên máy tính bảng và laptop – hai thiết bị học tập chính của học sinh FPT.

4\. Độ tin cậy (Reliability)

- SUPL-REL-01 – Tính sẵn sàng trong kỳ thi: Trong các kỳ thi tập trung, hệ thống phải đảm bảo độ ổn định 99.9%, tránh tình trạng nghẽn mạng khi hàng ngàn học sinh cùng nộp bài.
- SUPL-REL-02 – Chống gian lận AI Proctoring: Hệ thống giám sát phải nhận diện chính xác các hành vi bất thường (rời màn hình, có người lạ) và ghi lại minh chứng phục vụ phúc khảo.
- SUPL-REL-03 – Bảo mật dữ liệu học bạ: Dữ liệu điểm số phải được sao lưu định kỳ 2 giờ/lần để tránh mất mát do sự cố kỹ thuật.

5\. Hiệu năng (Performance)

- SUPL-PERF-01 – Thời gian phản hồi AI: AI Tutor phải trả lời câu hỏi của học sinh trong vòng dưới 3 giây. Kết quả chấm điểm OCR phải trả về trong dưới 10 giây sau khi nộp bài.
- SUPL-PERF-02 – Khả năng chịu tải: Hệ thống phải đáp ứng đồng thời ít nhất 2,000 người dùng truy cập làm bài thi mà không làm tăng độ trễ xử lý quá 20%.

6\. Khả năng hỗ trợ và bảo trì (Supportability)

- SUPL-SUPP-01 – Cập nhật tri thức AI: Hệ thống phải cho phép giáo viên cập nhật thêm tài liệu giảng dạy vào "kho tri thức" của AI mà không cần can thiệp vào code.
- SUPL-SUPP-02 – ML Monitoring: Tích hợp công cụ giám sát hiệu năng mô hình AI để phát hiện thời điểm AI bắt đầu trả lời sai kiến thức mới (Model Drift).

7\. Các ràng buộc thiết kế (Design Constraints)

- SUPL-DES-01 – Nền tảng hạ tầng: Hệ thống ưu tiên triển khai trên hạ tầng Google Cloud hoặc Azure để tận dụng các dịch vụ AI sẵn có.
- SUPL-DES-02 – Quy chuẩn dữ liệu: Dữ liệu học sinh phải được lưu trữ tại máy chủ Việt Nam theo luật an ninh mạng.

8\. Yêu cầu về tài liệu hướng dẫn

- SUPL-DOC-01: Phải có video hướng dẫn học sinh cách chụp ảnh bài làm tay sao cho AI chấm điểm chính xác nhất.
- SUPL-DOC-02: Tài liệu hướng dẫn Giáo viên cách "Fine-tuning" (tinh chỉnh) câu trả lời của AI Tutor.

9\. Thành phần mua ngoài (Purchased Components)

- SUPL-PC-01: Sử dụng API của OpenAI (GPT-4o) hoặc Google Gemini cho module LLM.
- SUPL-PC-02: Sử dụng thư viện nhận dạng ảnh chuyên dụng cho module OCR bài thi.

10\. Các giao diện (Interfaces)

- SUPL-UI-01: Giao diện học sinh tích hợp ngay trên trình duyệt Chrome/Edge của laptop học tập.
- SUPL-SW-01: Giao diện API RESTful để kết nối với cơ sở dữ liệu điểm số của hệ thống FAP hiện hành.

11\. Yêu cầu cấp phép (Licensing)

- SUPL-LIC-01: Hệ thống sử dụng bản quyền giáo dục của Microsoft 365 để xác thực người dùng (Single Sign-On qua tài khoản @fpt.edu.vn).

12\. Thông báo pháp lý (Legal)

- SUPL-LEGAL-01: Tuân thủ Luật Giáo dục và các quy định về bảo mật thông tin trẻ em/học sinh của Bộ GD&ĐT Việt Nam.

13\. Các chuẩn áp dụng (Standards)

- SUPL-STD-01: Tuân thủ tiêu chuẩn SCORM/xAPI trong việc lưu trữ và truyền tải học liệu trực tuyến.

Kết luận của mục 4.4

Tài liệu Supplementary Specification này đóng vai trò là "bản cam kết về chất lượng" cho hệ thống AI THPT FPT. Bằng việc tách biệt các yêu cầu phi chức năng khỏi Use Case, nhóm đã xác định được các cột trụ kỹ thuật quan trọng như độ chính xác của AI và tính an toàn của dữ liệu thi. Đây chính là cơ sở để nhóm xây dựng các kịch bản kiểm thử (Test Cases) ở chương tiếp theo, đảm bảo hệ thống không chỉ chạy đúng tính năng mà còn chạy ổn định và an toàn trong môi trường giáo dục.

Để hoàn thiện mục 4.5 cho hệ thống AI THPT FPT, mình sẽ xây dựng danh mục các yêu cầu bổ sung cốt lõi và ma trận dấu vết tương ứng, đảm bảo tính logic giữa các tính năng AI và các ràng buộc kỹ thuật.

## 4.5. Ma trận dấu vết: Features ⇒ Supplementary Requirements

Sau khi đã xác lập các tính năng mức cao tại Vision Document (Chương 3) và đặc tả chi tiết các yêu cầu phi chức năng tại mục 4.4, nhóm tiến hành xây dựng ma trận dấu vết giữa Features và Supplementary Requirements (SUPLs). Đây là bước quan trọng để khẳng định rằng các tính năng của hệ thống AI không chỉ tồn tại dưới dạng chức năng thuần túy mà còn được ràng buộc bởi các tiêu chuẩn về độ chính xác của AI, tính bảo mật dữ liệu học đường và hiệu năng vận hành thực tế.

### 4.5.1. Mục đích của ma trận Features ⇒ Supplementary Requirements

Việc thiết lập ma trận FEATs ⇒ SUPLs hướng tới ba mục tiêu:

- Đảm bảo tính thực thi của AI: Xác nhận các tính năng AI (như chấm điểm, gợi ý lộ trình) đã được gắn kèm các ràng buộc về độ chính xác và thời gian phản hồi.
- Kiểm soát rủi ro hệ thống: Đảm bảo các chức năng nhạy cảm như quản lý điểm số hay thi trực tuyến đều được bảo vệ bởi các yêu cầu về độ tin cậy và bảo mật chức năng.
- Hoàn thiện chuỗi dấu vết: Tạo tiền đề để xây dựng các kịch bản kiểm thử phi chức năng (Non-functional Test Cases) ở Chương 5, đảm bảo hệ thống đạt chuẩn "Production-ready" cho môi trường giáo dục.

### 4.5.2. Cơ sở và nguyên tắc ánh xạ

- Nhóm áp dụng nguyên tắc phân loại FURPS+ của IBM để ánh xạ các FEATs xuống SUPLs:
- Quan hệ đa - đa: Một tính năng AI (FEAT) có thể chịu sự ràng buộc của nhiều yêu cầu chất lượng (SUPLs) cùng lúc và ngược lại.
- Ưu tiên các SUPL đặc thù: Tập trung ánh xạ các yêu cầu về độ chính xác thuật toán, hiệu năng xử lý và tính sẵn sàng của hệ thống vào các tính năng cốt lõi.
- Loại biên các SUPL toàn cục: Các yêu cầu về pháp lý, bản quyền hoặc chuẩn tài liệu (nhóm SUPL-LEGAL, SUPL-STD) được hiểu là áp dụng cho toàn bộ dự án nên sẽ không liệt kê chi tiết trong ma trận 1-1 để tránh gây nhiễu dữ liệu.

### 4.5.3. Danh mục các SUPL cốt lõi được dùng trong ma trận

Nhóm lựa chọn 15 yêu cầu bổ sung quan trọng nhất, có tác động trực tiếp đến sự thành công của các tính năng AI trong hệ thống:

#### Bảng 4.5.1. Danh mục SUPL cốt lõi dùng trong ma trận FEATs ⇒ SUPLs

|     |     |     |
| --- | --- | --- |
| Mã rút gọn | Mã SUPL đầy đủ | Nội dung yêu cầu bổ sung |
| S01 | SUPL-FUNC-01 | Độ chính xác và nhất quán của thuật toán chấm điểm AI |
| S02 | SUPL-FUNC-02 | Khả năng tích hợp API với hệ thống FAP/EduNext |
| S03 | SUPL-FUNC-03 | Phân quyền truy cập dựa trên vai trò (RBAC) |
| S04 | SUPL-USE-01 | Giao diện tương thích đa thiết bị (Web/Tablet/Mobile) |
| S05 | SUPL-USE-02 | Khả năng phản hồi tự nhiên của Chatbot AI Tutor |
| S06 | SUPL-REL-01 | Tính sẵn sàng của hệ thống trong các kỳ thi tập trung |
| S07 | SUPL-REL-02 | Khả năng phát hiện gian lận và chịu lỗi của AI Proctoring |
| S08 | SUPL-REL-03 | Tự động sao lưu dữ liệu học bạ và kết quả thi |
| S09 | SUPL-PERF-01 | Thời gian phản hồi của AI (Tutor/OCR) dưới 3 giây |
| S10 | SUPL-PERF-02 | Khả năng phục vụ đồng thời 2,000 học sinh nộp bài |
| S11 | SUPL-SUPP-01 | Tính dễ bảo trì và cập nhật kho tri thức cho AI |
| S12 | SUPL-SUPP-02 | Hệ thống giám sát độ lệch mô hình AI (Model Drift) |
| S13 | SUPL-DES-01 | Ràng buộc triển khai trên hạ tầng Cloud (Azure/GCP) |
| S14 | SUPL-PC-01 | Tích hợp thư viện AI bên thứ ba (OpenAI/Gemini API) |
| S15 | SUPL-UI-01 | Tuân thủ bộ nhận diện thương hiệu FPT Education |

### 4.5.4. Bảng diễn giải ánh xạ từ Features sang Supplementary Requirements

#### Bảng 4.5.2. Diễn giải ánh xạ FEATs ⇒ SUPLs

|     |     |     |     |
| --- | --- | --- | --- |
| FEAT ID | Nội dung Feature | SUPL được ánh xạ | Giải thích ngắn |
| F01 | Dashboard phân tích rủi ro học tập (BGH) | S01, S03, S04, S13, S15 | Cần thuật toán dự báo chính xác, phân quyền bảo mật dữ liệu học sinh, giao diện biểu đồ trực quan và tuân thủ nhận diện thương hiệu FPT. |
| F14 | Chấm điểm bài làm tự luận bằng AI | S01, S08, S09, S10, S12, S14 | Yêu cầu độ chính xác cao (OCR), sao lưu kết quả thi ngay lập tức, phản hồi nhanh dưới 3 giây và giám sát sai lệch mô hình (Model Drift). |
| F17 | Giám sát thi trực tuyến (AI Proctoring) | S06, S07, S09, S10, S13 | Cần tính sẵn sàng cực cao trong kỳ thi, khả năng phát hiện gian lận thời gian thực và hạ tầng Cloud đủ mạnh để xử lý luồng Video/Ảnh. |
| F19 | Hỏi đáp kiến thức với AI Tutor | S01, S05, S09, S11, S14 | Tập trung vào tính chính xác của kiến thức, ngôn ngữ phản hồi tự nhiên, tốc độ chat real-time và khả năng cập nhật kho tri thức. |
| F25 | Gợi ý lộ trình học tập cá nhân hóa | S01, S04, S09, S13 | AI cần tính toán chính xác lỗ hổng kiến thức, hiển thị tốt trên thiết bị di động của học sinh và xử lý dữ liệu lớn trên Cloud. |
| F31 | Portal dành cho Phụ huynh | S03, S04, S08, S15 | Liên quan đến phân quyền xem điểm của con, giao diện dễ dùng cho phụ huynh, bảo mật dữ liệu cá nhân và đồng bộ thương hiệu trường. |
| F39 | Đồng bộ dữ liệu từ hệ thống FAP | S02, S03, S06, S13 | Cần khả năng tích hợp API ổn định, bảo mật đường truyền dữ liệu và tính sẵn sàng của kết nối mạng giữa các server. |

4.5.5. Ma trận dấu vết tổng hợp Features ⇒ Supplementary Requirements

Bảng dưới đây thể hiện mối liên kết giữa các tính năng (Features) và các yêu cầu bổ sung (SUPLs). Ký hiệu “X” xác nhận rằng tính năng ở hàng tương ứng bị ràng buộc hoặc phải tuân thủ yêu cầu chất lượng ở cột tương ứng.

|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FEAT \\ SUPL | S01 | S02 | S03 | S04 | S05 | S06 | S07 | S08 | S09 | S10 | S11 | S12 | S13 | S14 | S15 |
| FEAT-01 (Dashboard) | X   |     | X   | X   |     |     |     |     |     |     |     |     | X   |     | X   |
| FEAT-10 (Ngân hàng đề) |     |     | X   |     |     | X   |     |     |     |     | X   |     |     |     |     |
| FEAT-13 (OCR bài thi) | X   |     |     |     |     |     |     | X   | X   | X   |     | X   |     | X   |     |
| FEAT-14 (Chấm điểm AI) | X   |     |     |     |     |     |     | X   | X   | X   |     | X   |     | X   |     |
| FEAT-17 (AI Proctoring) |     |     |     |     |     | X   | X   |     |     | X   |     |     | X   |     |     |
| FEAT-19 (AI Tutor) | X   |     |     |     | X   |     |     |     | X   |     |     | X   |     | X   |     |
| FEAT-21 (Tóm tắt nội dung) | X   |     |     |     |     |     |     |     | X   |     |     |     |     | X   |     |
| FEAT-24 (Radar năng lực) | X   |     |     | X   |     |     |     |     | X   |     |     |     |     |     |     |
| FEAT-25 (Lộ trình học) | X   |     |     | X   |     |     |     |     | X   |     |     |     |     |     |     |
| FEAT-31 (Portal PH) |     |     | X   | X   |     |     |     | X   |     |     |     |     |     |     | X   |
| FEAT-39 (Đồng bộ FAP) |     | X   |     |     |     |     |     |     |     |     |     |     | X   |     |     |

### 4.5.6. Nhận xét về ma trận FEATs ⇒ SUPLs

Từ hai bảng ma trận trên, nhóm dự án rút ra một số nhận xét quan trọng:

- Thứ nhất, các FEAT chức năng cốt lõi của hệ thống AI THPT FPT như Quản lý ngân hàng đề, Tổ chức thi trực tuyến và Cổng học tập học sinh đều đã được gắn chặt với các SUPL về độ tin cậy (S06), bảo mật (S03) và hiệu năng (S10). Điều này chứng minh việc đặc tả phi chức năng không hề rời rạc mà bám sát tính chất nhạy cảm của dữ liệu học đường.
- Thứ bả, các FEAT đột phá liên quan đến AI (Tutor, Adaptive Learning) được truy vết chủ yếu sang các SUPL về độ chính xác thuật toán (S01), thời gian phản hồi (S09) và khả năng cập nhật tri thức (S11). Đây là những ràng buộc then chốt để đảm bảo AI là một trợ thủ đắc lực chứ không phải rào cản cho học sinh.
- Thứ ba, ghi nhận tính "bao phủ" của hạ tầng Cloud (S13) và tích hợp API (S02). Đây là các yêu cầu nền tảng ảnh hưởng đến hầu hết các tính năng phân tích dữ liệu lớn và đồng bộ hóa với hệ thống FAP của nhà trường.

### 4.5.7. Kết luận của mục 4.5

Việc thiết lập ma trận dấu vết FEATs ⇒ SUPLs đã giúp nhóm hoàn thiện mảnh ghép còn lại của tầng hệ thống trong kim tự tháp yêu cầu. Ma trận này khẳng định rằng mọi tính năng trong Vision Document đều đã được "bao bọc" bởi các tiêu chuẩn chất lượng và ràng buộc vận hành cụ thể. Đây chính là cơ sở dữ liệu đầu vào để nhóm tiếp tục xây dựng ma trận Supplementary Requirements ⇒ Test Cases ở Chương 5 nhằm kiểm chứng toàn diện hệ thống.

4.6. BẢNG CHÚ GIẢI THUẬT NGỮ (Glossary – theo mẫu IBM)

Dự án: Hệ thống hỗ trợ học tập và khảo thí thông minh AI THPT FPT

Tên tài liệu: Glossary

Phiên bản: 1.0

### 1\. Giới thiệu (Introduction)

Tài liệu Glossary định nghĩa các thuật ngữ đặc thù của miền giáo dục thông minh và các khái niệm kỹ nghệ yêu cầu theo chuẩn RUP/IBM. Mục tiêu là giúp các thành viên nhóm, BGH trường FPT và giảng viên có một cách hiểu thống nhất duy nhất.

### 2\. Các định nghĩa (Definitions)

_(Lưu ý: Mình giữ lại các thuật ngữ học thuật của RUP và thay thế hoàn toàn các thuật ngữ nghiệp vụ Vinamilk sang AI FPT)_

- 2.1. Actor (Tác nhân): Thực thể bên ngoài tương tác với hệ thống. Trong dự án gồm: Học sinh, Giáo viên, Cán bộ BGH, Hệ thống FAP và API OpenAI/Gemini.
- 2.2. AI Tutor (Trợ lý học tập): Thành phần trí tuệ nhân tạo hỗ trợ giải đáp thắc mắc, tóm tắt bài giảng và gợi ý lộ trình học tập cá nhân hóa cho học sinh.
- 2.3. AI Proctoring (Giám sát thi thông minh): Công nghệ sử dụng camera và AI để nhận diện khuôn mặt, phát hiện các hành vi gian lận (rời khỏi màn hình, có người lạ) trong quá trình thi trực tuyến.
- 2.4. Adaptive Learning (Học tập thích ứng): Khả năng hệ thống tự điều chỉnh độ khó của bài tập và tài liệu học tập dựa trên biểu đồ năng lực Radar của từng học sinh.
- 2.5. Baseline (Đường cơ sở): Tập hợp các yêu cầu (NEEDs, FEATs, UCs...) đã được phê duyệt và đóng băng để làm mốc phát triển.
- 2.6. Dashboard rủi ro học tập: Màn hình quản trị dành cho giáo viên/BGH, sử dụng AI để cảnh báo sớm những học sinh có nguy cơ sút giảm điểm số hoặc hổng kiến thức.
- 2.7. EduNext/FAP: Các hệ thống quản lý đào tạo hiện hành của FPT Education mà hệ thống AI THPT FPT cần tích hợp dữ liệu.
- 2.8. Feature – FEAT: Tính năng mức cao của sản phẩm, ví dụ: Chấm điểm tự luận bằng AI, Ngân hàng đề thông minh.
- 2.9. LLM (Large Language Model): Mô hình ngôn ngữ lớn (như GPT-4, Gemini) được sử dụng để làm "bộ não" cho AI Tutor.
- 2.10. MLOps (Machine Learning Operations): Quy trình quản lý vòng đời của mô hình AI, bao gồm huấn luyện lại mô hình khi dữ liệu giáo dục thay đổi.
- 2.11. OCR (Optical Character Recognition): Công nghệ nhận dạng chữ viết tay, dùng để chuyển đổi bài làm trên giấy của học sinh thành dữ liệu số để AI chấm điểm.
- 2.12. Radar Competency Chart (Biểu đồ năng lực Radar): Biểu đồ 5-6 cạnh hiển thị mức độ nắm vững các kỹ năng/kiến thức của học sinh (Ví dụ: Nghe, Nói, Đọc, Viết).
- 2.13. Supplementary Requirement – SUPL: Yêu cầu phi chức năng (bảo mật, hiệu năng, độ chính xác AI) được đặc tả theo chuẩn FURPS+.
- 2.14. Traceability (Khả năng truy vết): Khả năng lần theo mối liên kết giữa các tầng yêu cầu (Ví dụ: Từ một kịch bản thi hỏng truy ngược lại lỗi ở tầng tính năng).
- 2.15. Use Case – UC: Mô tả một chuỗi tương tác giữa Actor và hệ thống để đạt mục tiêu (Ví dụ: UC-14 Chấm điểm AI).

### Kết luận của mục 4.6

Tài liệu Glossary này đã chuẩn hóa thành công ngôn ngữ chung cho dự án, từ các khái niệm quản lý yêu cầu chuyên sâu đến các thuật ngữ công nghệ AI hiện đại. Việc duy trì một Glossary duy nhất đảm bảo rằng không có sự hiểu lầm về mặt kỹ thuật hay nghiệp vụ giữa nhóm phát triển và nhà trường, tạo nền tảng vững chắc cho việc đặc tả Scenarios ở chương kế tiếp.

Chào cậu, chúng mình cùng bước sang Chương 5 để "chốt hạ" tầng đáy của kim tự tháp yêu cầu nhé. Tớ sẽ chuyển đổi toàn bộ logic từ việc đặt hàng sữa Vinamilk sang quy trình Nộp bài và Chấm điểm AI – những "trái tim" của hệ thống AI THPT FPT.

# CHƯƠNG 5: KIỂM THỬ VÀ HOÀN THIỆN KIM TỰ THÁP

5.1. Kịch bản (Scenarios) và Trường hợp kiểm thử (Test Cases)

### 5.1.1. Vai trò của Scenarios và Test Cases trong dự án

Sau khi đã hoàn thiện đặc tả Use Cases và SUPLs ở Chương 4, nhóm tiếp tục triển khai tầng cuối cùng của kim tự tháp: Scenarios và Test Cases. Trong hệ thống AI THPT FPT, mỗi Use Case (như Chấm điểm AI hay Giám sát thi) chứa đựng rất nhiều tình huống thực tế (ví dụ: học sinh nộp ảnh mờ, AI không nhận diện được chữ viết, hoặc mất kết nối khi đang thi). Việc chia nhỏ Use Case thành các Scenario giúp nhóm kiểm soát mọi rủi ro có thể xảy ra. Từ đó, các Test Case được sinh ra với đầy đủ các thành phần: _ID, mô tả, điều kiện trước, các bước thực hiện và kết quả mong đợi_ để đảm bảo phần mềm vận hành hoàn hảo trước khi bàn giao cho nhà trường.

### 5.1.2. Nguyên tắc xây dựng Scenarios và Test Cases

Trong dự án này, nhóm áp dụng các nguyên tắc sau:

- Thứ nhất: Mỗi Use Case trọng điểm (đặc biệt là các UC liên quan đến AI) phải có ít nhất một Happy Path (kịch bản thành công) và các Exception Paths (kịch bản ngoại lệ như lỗi OCR, lỗi logic đáp án).
- Thứ hai: Đảm bảo tính truy vết tuyệt đối (UCs → Scenarios → Test Cases). Điều này giúp nhóm khẳng định không có bất kỳ yêu cầu chức năng nào bị bỏ sót trong quá trình kiểm thử.
- Thứ ba: Ưu tiên đặc tả các kịch bản liên quan đến luồng chấm điểm và thi trực tuyến. Đây là vùng nghiệp vụ nhạy cảm nhất, ảnh hưởng trực tiếp đến quyền lợi điểm số của học sinh FPT.

### 5.1.3. Quy ước mã hóa

Nhóm sử dụng quy ước mã hóa đồng bộ với các chương trước:

- Scenario ID: SCE-UCxx-yy (Ví dụ: SCE-UC14-01 là kịch bản thành công của UC-14 Chấm điểm AI).
- Test Case ID: TC-UCxx-yy (Ví dụ: TC-UC14-01 dùng để kiểm thử kịch bản tương ứng).

### 5.1.4. Kịch bản và Test Cases cho nhóm Use Case cốt lõi

A. Use Case UC-14 – Chấm điểm bài làm tự luận bằng AI Đây là Use Case phức tạp nhất, đóng vai trò cầu nối giữa bài làm của học sinh và hệ thống điểm số. Hệ thống phải nhận diện ảnh chụp (OCR), so khớp với đáp án mẫu bằng AI và trả về kết quả thẩm định.

1\. Danh sách Scenarios của UC-14

Dưới đây là bảng phân tích các kịch bản có thể xảy ra khi AI thực hiện chấm bài:

### Bảng 5.1.1. Các Scenarios của UC-14 – Chấm điểm bài làm tự luận bằng AI

|     |     |     |     |
| --- | --- | --- | --- |
| Mã kịch bản | Tên kịch bản | Mô tả đường đi | Kết quả mong đợi |
| SCE-UC14-01 | Chấm điểm thành công (Happy Path) | Học sinh nộp ảnh rõ nét, AI nhận diện được 100% chữ viết và khớp đáp án. | Hệ thống hiển thị điểm dự kiến và các đoạn văn được highlight. |
| SCE-UC14-02 | Lỗi nhận diện OCR | Ảnh chụp bị mờ hoặc chữ viết quá khó đọc khiến AI không thể số hóa dữ liệu. | Hệ thống thông báo "Ảnh không đạt chất lượng" và yêu cầu học sinh chụp lại. |
| SCE-UC14-03 | AI không tự tin về kết quả (Low Confidence) | AI nhận diện được chữ nhưng độ khớp đáp án thấp hơn ngưỡng an toàn. | Hệ thống tự động chuyển trạng thái bài làm sang "Chờ giáo viên thẩm định". |
| SCE-UC14-04 | Sai lệch định dạng tệp | Học sinh nộp file không phải định dạng ảnh (ví dụ: .zip, .exe). | Hệ thống từ chối tệp và hiển thị cảnh báo định dạng hỗ trợ (.jpg, .png, .pdf). |

2\. Đặc tả Test Case mẫu cho kịch bản thành công

Để cụ thể hóa, nhóm trình bày Test Case dành cho kịch bản SCE-UC14-01:

### Bảng 5.1.2. Test Case TC-UC14-01

- Test Case ID: TC-UC14-01
- Tên kiểm thử: Kiểm tra luồng chấm điểm tự luận AI thành công.
- Điều kiện trước: 1. Học sinh đã đăng nhập. 2. Đã có đáp án mẫu được cấu hình trong ngân hàng đề.
- Các bước thực hiện:
    - Truy cập vào module "Nộp bài".
    - Tải lên ảnh chụp bài làm tự luận (rõ nét, đúng định dạng).
    - Nhấn nút "Nộp bài và Chấm điểm".
- Kết quả mong đợi: 1. Hệ thống hiển thị thông báo "Đang xử lý bằng AI...". 2. Trong vòng 10 giây, hiển thị bảng điểm chi tiết kèm nhận xét tự động. 3. Trạng thái bài làm cập nhật thành "Đã chấm điểm".
- Điều kiện sau: Dữ liệu điểm được lưu tạm vào cơ sở dữ liệu chờ giáo viên phê duyệt chính thức.

## 5.2. Ma trận dấu vết: Use Cases ⇒ Scenarios

Sau khi hoàn thiện mục 5.1, nhóm tiếp tục thiết lập ma trận dấu vết giữa tầng Use Cases (UCs) và tầng Scenarios (SCEs). Bước này giúp khẳng định rằng các kịch bản thực thi không chỉ bao gồm luồng thành công (Happy Path) mà còn bao trùm cả các tình huống ngoại lệ (Exceptions) đã được dự báo trong đặc tả hệ thống AI.

### 5.2.1. Mục đích của ma trận Use Cases ⇒ Scenarios

Việc xây dựng ma trận UCs ⇒ SCEs hướng tới ba mục tiêu cốt lõi:

- Kiểm soát độ bao phủ: Đảm bảo mỗi đặc tả Use Case (ví dụ: Chấm điểm AI) đều được cụ thể hóa thành các đường đi thực tế, tránh việc yêu cầu chỉ nằm trên giấy mà không có kịch bản chạy thử.
- Xác định nguồn gốc kịch bản: Bảo đảm mọi Scenario đều có nguồn gốc từ một Use Case được phê duyệt, giúp hệ thống không phát sinh các kịch bản nằm ngoài phạm vi (Out of Scope).
- Tiền đề cho kiểm thử: Tạo danh mục kịch bản chuẩn để từ đó sinh ra các Test Cases ở mục 5.3, đảm bảo kiểm tra được toàn bộ "sức khỏe" của các thuật toán AI và logic nghiệp vụ học đường.

### 5.2.2. Cơ sở và nguyên tắc ánh xạ

Nhóm áp dụng các nguyên tắc nghiêm ngặt của chuẩn RUP khi xây dựng ma trận:

- Quan hệ 1-N: Một Use Case nguồn sẽ sinh ra ít nhất một Scenario thành công và có thể có nhiều Scenario ngoại lệ.
- Tính kế thừa: Các Scenario được chiết xuất trực tiếp từ _Basic Flow_ (Luồng cơ bản) và _Alternative/Exception Flows_ (Luồng thay thế/ngoại lệ) trong tài liệu đặc tả Use Case.
- Quy ước mã hóa nhất quán:
    - UC-xx: Mã định danh Use Case.
    - SCE-UCxx-yy: Mã kịch bản cụ thể (Ví dụ: SCE-UC14-02 là kịch bản ngoại lệ số 02 của UC-14).

### 5.2.3. Bảng diễn giải ánh xạ từ Use Cases sang Scenarios

Dưới đây là bảng diễn giải chi tiết cho các Use Case trọng điểm của hệ thống AI THPT FPT:

Bảng 5.2.1. Diễn giải ánh xạ Use Cases ⇒ Scenarios

|     |     |     |     |
| --- | --- | --- | --- |
| UC ID | Tên Use Case | Scenario ID | Diễn giải kịch bản thực thi |
| UC-01 | Đăng nhập hệ thống (SSO) | SCE-UC01-01 | Đăng nhập thành công qua tài khoản @fpt.edu.vn. |
|     |     | SCE-UC01-02 | Đăng nhập thất bại do sai mật khẩu hoặc tài khoản bị khóa. |
| UC-14 | Chấm điểm bài làm AI | SCE-UC14-01 | AI nhận diện OCR rõ nét và trả kết quả chấm điểm thành công. |
|     |     | SCE-UC14-02 | Ảnh chụp bài làm bị mờ, hệ thống yêu cầu học sinh chụp lại. |
|     |     | SCE-UC14-03 | AI phát hiện bài làm có dấu hiệu sao chép, đánh dấu "Nghi vấn". |
| UC-17 | Giám sát thi trực tuyến | SCE-UC17-01 | Học sinh hoàn thành bài thi dưới sự giám sát bình thường của AI. |
|     |     | SCE-UC17-02 | AI phát hiện có người lạ trong khung hình và phát cảnh báo. |
|     |     | SCE-UC17-03 | Mất kết nối mạng trong lúc thi, AI lưu trạng thái chờ kết nối lại. |
| UC-19 | Hỏi đáp với AI Tutor | SCE-UC19-01 | Học sinh hỏi kiến thức trong kho tri thức, AI trả lời chính xác. |
|     |     | SCE-UC19-02 | Học sinh hỏi kiến thức ngoài phạm vi, AI từ chối và hướng dẫn lại. |
| UC-25 | Gợi ý lộ trình học | SCE-UC25-01 | AI tổng hợp kết quả thi và đề xuất lộ trình ôn tập cá nhân hóa. |
|     |     | SCE-UC25-02 | Dữ liệu học tập quá ít (mới nhập học), AI yêu cầu làm bài test đầu vào. |
| UC-39 | Đồng bộ dữ liệu FAP | SCE-UC39-01 | Hệ thống FAP trả về danh sách lớp học thành công. |
|     |     | SCE-UC39-02 | API FAP bị lỗi kết nối, hệ thống ghi log và thử lại sau (Retry). |

### 5.2.4. Ma trận dấu vết tổng hợp Use Cases ⇒ Scenarios

Do số lượng scenario khá lớn, để thuận tiện trình bày và theo dõi, nhóm chia ma trận thành các bảng nhỏ dựa trên các nhóm chức năng cốt lõi. Cách trình bày này giúp đảm bảo tính dễ đọc trong báo cáo Word nhưng vẫn duy trì được tính liên kết chặt chẽ của kim tự tháp yêu cầu.

A. Nhóm Use Case Quản lý người dùng và Tích hợp hệ thống

Nhóm này tập trung vào các hoạt động nền tảng như đăng nhập và đồng bộ dữ liệu với FAP.

Bảng 5.2.2A. Ma trận dấu vết UCs ⇒ SCEs

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| UC \\ SCE | SCE-UC01-01 | SCE-UC01-02 | SCE-UC39-01 | SCE-UC39-02 |
| UC-01 (Đăng nhập) | X   | X   |     |     |
| UC-39 (Đồng bộ FAP) |     |     | X   | X   |

B. Nhóm Use Case Khảo thí và Giám sát AI (Trọng tâm)

Đây là nhóm Use Case chứa nhiều kịch bản ngoại lệ nhất do tính chất phức tạp của các thuật toán nhận diện.

Bảng 5.2.2B. Ma trận dấu vết UCs ⇒ SCEs (Nhóm Khảo thí & AI)

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
| UC \\ SCE | SCE-UC14-01 | SCE-UC14-02 | SCE-UC14-03 | SCE-UC17-01 | SCE-UC17-02 | SCE-UC17-03 |
| UC-14 (Chấm bài) | X   | X   | X   |     |     |     |
| UC-17 (Giám sát thi) |     |     |     | X   | X   | X   |

C. Nhóm Use Case Hỗ trợ học tập và Cá nhân hóa

Tập trung vào các kịch bản tương tác giữa học sinh và AI Tutor.

Bảng 5.2.2C. Ma trận dấu vết UCs ⇒ SCEs (Nhóm Học tập)

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| UC \\ SCE | SCE-UC19-01 | SCE-UC19-02 | SCE-UC25-01 | SCE-UC25-02 |
| UC-19 (AI Tutor) | X   | X   |     |     |
| UC-25 (Gợi ý lộ trình) |     |     | X   | X   |

5.2.5. Nhận xét về ma trận Use Cases ⇒ Scenarios

Từ các bảng ma trận phân đoạn trên, nhóm dự án rút ra một số nhận xét quan trọng:

- Thứ nhất: 100% Use Case của hệ thống AI THPT FPT hiện đều đã được phân rã thành ít nhất một Scenario, trung bình mỗi UC có từ 2 đến 4 kịch bản. Điều này chứng tỏ tập Use Case không chỉ dừng lại ở mức mô tả lý thuyết mà đã sẵn sàng cho việc thực thi kiểm thử thực tế.
- Thứ hai: Các UC trọng tâm về AI như UC-14 (Chấm điểm) và UC-17 (Giám sát thi) có số lượng Scenario nhiều nhất. Điều này hoàn toàn hợp lý vì đây là các tính năng có nhiều rủi ro ngoại lệ nhất như: ảnh chụp bài làm bị mờ, học sinh gian lận, mất kết nối camera hoặc lỗi logic nhận diện. Việc tập trung nhiều kịch bản vào đây giúp hệ thống trở nên tin cậy hơn.
- Thứ ba: Các Use Case quản trị như Dashboard (UC-01) hay Gợi ý lộ trình (UC-25) cũng được phân rã đầy đủ luồng thành công và ngoại lệ (như thiếu dữ liệu đầu vào). Nhờ đó, mọi chức năng dù là nền tảng hay nâng cao đều được bao bọc bởi mạng lưới truy vết chặt chẽ.

### 5.2.6. Kết luận của mục 5.2

Việc xây dựng ma trận dấu vết giữa Use Cases và Scenarios đã giúp nhóm hoàn thiện thêm một tầng quan trọng của kim tự tháp yêu cầu. Ma trận này chứng minh rằng toàn bộ các hành vi của hệ thống AI THPT FPT đã được triển khai xuống các kịch bản thực thi cụ thể. Đây là cơ sở trực tiếp để nhóm tiếp tục thiết lập ma trận Scenarios ⇒ Test Cases ở mục 5.3, đảm bảo tập yêu cầu chức năng được kiểm soát tốt ở chiều sâu kiểm thử.

## 5.3. Ma trận dấu vết: Scenarios ⇒ Test Cases

Sau khi đã phân rã Use Cases thành Scenarios ở mục 5.2, mục 5.3 này sẽ đóng vai trò là "lớp bảo vệ cuối cùng" để chứng minh rằng mỗi kịch bản thực thi đều có ít nhất một trường hợp kiểm thử (Test Case) tương ứng. Đây là bước kết nối trực tiếp giữa đặc tả yêu cầu và thực tế kiểm chứng phần mềm.

### 5.3.1. Mục đích của ma trận Scenarios ⇒ Test Cases

Ma trận được thiết lập nhằm ba mục đích:

- Xác nhận độ bao phủ (Test Coverage): Đảm bảo không có Scenario nào (đặc biệt là các lỗi ngoại lệ của AI) bị bỏ quên mà không được kiểm thử.
- Đảm bảo tính chính xác: Mỗi Test Case phải bám sát vào một kịch bản cụ thể, tránh việc viết các bài test dư thừa, không liên quan đến yêu cầu của nhà trường.
- Sẵn sàng cho Baseline 3: QA dựa vào ma trận này để xác nhận toàn bộ hệ thống đã đủ điều kiện bàn giao và vận hành thực tế tại trường THPT FPT.

### 5.3.2. Cơ sở và nguyên tắc ánh xạ

Nhóm áp dụng nguyên tắc truy vết 1-1 hoặc 1-N:

- Mỗi Scenario phải tương ứng với ít nhất một Test Case.
- Quy ước mã hóa nhất quán: SCE-UCxx-yy truy vết xuống TC-UCxx-yy.
- Các Scenario về AI (chấm bài, giám sát) có thể sinh ra nhiều Test Case để kiểm tra với các loại dữ liệu đầu vào khác nhau (ví dụ: các loại nét chữ khác nhau khi chấm bài).

### 5.3.3. Bảng diễn giải ánh xạ từ Scenarios sang Test Cases

Dưới đây là bảng giải thích cách nhóm chuyển đổi từ kịch bản thực tế sang bài kiểm thử cụ thể:

Bảng 5.3.1. Diễn giải ánh xạ Scenarios ⇒ Test Cases

|     |     |     |     |
| --- | --- | --- | --- |
| Scenario ID | Nội dung kịch bản | Test Case ID | Mục tiêu kiểm thử |
| SCE-UC01-01 | Đăng nhập SSO thành công | TC-UC01-01 | Kiểm tra khả năng kết nối và xác thực với tài khoản FPT Education. |
| SCE-UC01-02 | Đăng nhập sai mật khẩu | TC-UC01-02 | Kiểm tra hiển thị thông báo lỗi và cơ chế khóa tài khoản sau 5 lần sai. |
| SCE-UC10-01 | Tạo đề thi từ ngân hàng | TC-UC10-01 | Kiểm tra logic trộn đề và đảm bảo không trùng lặp câu hỏi. |
| SCE-UC10-02 | Upload câu hỏi sai định dạng | TC-UC10-02 | Kiểm tra thông báo lỗi khi tải file Excel không đúng template. |
| SCE-UC14-01 | AI chấm bài tự luận thành công | TC-UC14-01 | Kiểm tra độ chính xác của điểm số so với đáp án mẫu đã cấu hình. |
| SCE-UC14-02 | Ảnh bài làm bị mờ/mất góc | TC-UC14-02 | Kiểm tra AI phát hiện chất lượng ảnh thấp và yêu cầu chụp lại. |
| SCE-UC14-03 | Bài làm có chữ viết tay quá yếu | TC-UC14-03 | Kiểm tra tính năng tự động chuyển bài sang giáo viên chấm thủ công. |
| SCE-UC14-04 | AI phát hiện bài làm đạo văn | TC-UC14-04 | Kiểm tra tỷ lệ tương đồng giữa các bài thi của học sinh. |
| SCE-UC17-01 | Giám sát thi bình thường | TC-UC17-01 | Kiểm tra độ ổn định của luồng streaming camera suốt 90 phút thi. |
| SCE-UC17-02 | AI phát hiện có người lạ | TC-UC17-02 | Kiểm tra độ nhạy của thuật toán nhận diện khuôn mặt người lạ. |
| SCE-UC17-03 | Học sinh dùng điện thoại | TC-UC17-03 | Kiểm tra AI nhận diện vật thể lạ (điện thoại, tài liệu) trong khung hình. |
| SCE-UC17-04 | Mất kết nối internet khi thi | TC-UC17-04 | Kiểm tra tính năng tự động lưu bài làm và ghi log thời điểm mất kết nối. |
| SCE-UC19-01 | AI Tutor trả lời kiến thức cũ | TC-UC19-01 | Kiểm tra phản hồi dựa trên kho tri thức sẵn có trong hệ thống. |
| SCE-UC19-02 | AI Tutor hỏi về kiến thức mới | TC-UC19-02 | Kiểm tra khả năng truy xuất Internet/RAG để cập nhật kiến thức mới. |
| SCE-UC19-03 | Học sinh hỏi câu hỏi nhạy cảm | TC-UC19-03 | Kiểm tra bộ lọc ngôn từ và các ràng buộc đạo đức của Chatbot AI. |
| SCE-UC21-01 | Tóm tắt bài giảng video | TC-UC21-01 | Kiểm tra khả năng trích xuất âm thanh thành văn bản và tóm tắt ý chính. |
| SCE-UC25-01 | Đề xuất lộ trình theo Radar | TC-UC25-01 | Kiểm tra thuật toán gợi ý bài tập tập trung vào "điểm khuyết" trên Radar. |
| SCE-UC25-02 | Học sinh chưa có dữ liệu điểm | TC-UC25-02 | Kiểm tra hiển thị lộ trình mặc định (Standard) khi AI chưa đủ dữ liệu. |
| SCE-UC31-01 | Phụ huynh xem bảng điểm | TC-UC31-01 | Kiểm tra tính bảo mật, đảm bảo PH chỉ xem được dữ liệu của con mình. |
| SCE-UC31-02 | Nhận thông báo cảnh báo AI | TC-UC31-02 | Kiểm tra tính năng Push Notification khi học sinh có dấu hiệu sút giảm. |
| SCE-UC39-01 | Đồng bộ điểm sang FAP | TC-UC39-01 | Kiểm tra tính toàn vẹn dữ liệu khi đẩy điểm từ hệ thống AI sang FAP. |
| SCE-UC39-02 | API FAP không phản hồi | TC-UC39-02 | Kiểm tra cơ chế xếp hàng (Queue) để gửi lại dữ liệu sau khi kết nối lại. |
| SCE-SUPL-01 | Kiểm thử hiệu năng (2k users) | TC-SUPL-01 | Kiểm tra thời gian phản hồi khi 2000 học sinh cùng nộp bài một lúc. |
| SCE-SUPL-02 | Kiểm thử bảo mật SQLi | TC-SUPL-02 | Kiểm tra các lỗ hổng bảo mật phổ biến tại các ô nhập liệu tìm kiếm. |

### 5.2.4. Ma trận dấu vết tổng hợp Use Cases ⇒ Scenarios

Để đảm bảo tính thẩm mỹ và dễ theo dõi trên khổ giấy A4 đứng, nhóm chia ma trận dấu vết thành các bảng phân đoạn theo từng cụm chức năng.

Bảng 5.2.2A. Ma trận dấu vết UCs ⇒ SCEs (Nhóm UC-01 đến UC-10)

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
| SCE \\ TC | TC-UC01-01 | TC-UC01-02 | TC-UC10-01 | TC-UC10-02 | TC-UC10-03 | TC-UC10-04 |
| SCE-UC01-01 | X   |     |     |     |     |     |
| SCE-UC01-02 |     | X   |     |     |     |     |
| SCE-UC10-01 |     |     | X   |     |     |     |
| SCE-UC10-02 |     |     |     | X   |     |     |
| SCE-UC10-03 |     |     |     |     | X   |     |
| SCE-UC10-04 |     |     |     |     |     | X   |

Bảng 5.2.2B. Ma trận dấu vết UCs ⇒ SCEs (Nhóm UC-14 đến UC-17: Chấm điểm & Giám sát AI)

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
| SCE \\ TC | TC-UC14-01 | TC-UC14-02 | TC-UC14-03 | TC-UC14-04 | TC-UC14-05 | TC-UC14-06 |
| SCE-UC14-01 | X   |     |     |     |     |     |
| SCE-UC14-02 |     | X   |     |     |     |     |
| SCE-UC14-03 |     |     | X   |     |     |     |
| SCE-UC14-04 |     |     |     | X   |     |     |
| SCE-UC14-05 |     |     |     |     | X   |     |
| SCE-UC14-06 |     |     |     |     |     | X   |

C. Nhóm Scenarios về Giám sát thi (AI Proctoring) và AI Tutor

Nhóm kiểm tra khả năng tương tác thời gian thực và phát hiện hành vi.

Bảng 5.3.2C. Ma trận dấu vết SCEs ⇒ TCs (Nhóm Giám sát & Trợ lý AI)

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
| SCE \\ TC | TC-UC17-01 | TC-UC17-02 | TC-UC17-03 | TC-UC19-01 | TC-UC19-02 | TC-UC19-03 |
| SCE-UC17-01 | X   |     |     |     |     |     |
| SCE-UC17-02 |     | X   |     |     |     |     |
| SCE-UC17-03 |     |     | X   |     |     |     |
| SCE-UC19-01 |     |     |     | X   |     |     |
| SCE-UC19-02 |     |     |     |     | X   |     |
| SCE-UC19-03 |     |     |     |     |     | X   |

### 5.3.6. Kết luận của mục 5.3

Việc xây dựng ma trận dấu vết giữa Scenarios và Test Cases đã hoàn thiện thêm một bước quan trọng ở đáy của kim tự tháp yêu cầu. Ma trận này giúp chứng minh rằng các kịch bản thực thi của hệ thống AI THPT FPT không chỉ tồn tại trên giấy, mà đã được chuyển hóa thành các trường hợp kiểm thử có thể dùng để xác minh yêu cầu một cách cụ thể. Đồng thời, ma trận cũng giúp nhóm nhìn thấy rõ những khoảng trống kiểm thử còn lại để bổ sung trước khi chốt Baseline 3 và đánh giá độ bao phủ kiểm thử của toàn bộ kho yêu cầu, đặc biệt là các kịch bản ngoại lệ của mô hình AI.

## 5.4. Ma trận dấu vết: Supplementary ⇒ Test Cases

Sau khi đã xây dựng tài liệu Supplementary Requirements ở mục 4.4 và hoàn thiện tập Test Cases ở mục 5.1, nhóm tiếp tục thiết lập ma trận dấu vết giữa tầng Supplementary Requirements (SUPLs) và tầng Test Cases (TCs). Nếu ma trận ở mục 5.3 chứng minh rằng các Scenarios đã được kiểm thử đầy đủ, thì mục 5.4 có nhiệm vụ chứng minh chiều còn lại của đáy kim tự tháp yêu cầu: các yêu cầu bổ sung / phi chức năng cũng đã được kiểm chứng bằng các test case tương ứng.

### 5.4.1. Mục đích của ma trận Supplementary ⇒ Test Cases

Ma trận được xây dựng nhằm ba mục đích chính:

- Hiện thực hóa yêu cầu phi chức năng: Đảm bảo các ràng buộc về độ chính xác AI, bảo mật và hiệu năng được chuyển hóa thành hoạt động kiểm thử cụ thể thay vì chỉ là những mô tả định tính.
- Phát hiện lỗ hổng kiểm thử: Tránh tình trạng hệ thống chỉ tập trung kiểm thử chức năng (Functional Testing) mà bỏ sót các yêu cầu về tải trọng (Load Testing) hay tính sẵn sàng của hạ tầng Cloud.
- Hoàn thiện đáy kim tự tháp: Tạo ra một mạng lưới truy vết khép kín, nơi cả hành vi (Scenarios) và tính chất (SUPLs) đều được hội tụ tại tầng kiểm thử cuối cùng.

### 5.4.2. Cơ sở và nguyên tắc ánh xạ

Nhóm áp dụng các nguyên tắc sau:

- Một SUPL (ví dụ: Bảo mật) có thể ánh xạ tới nhiều Test Case khác nhau vì nó tác động lên toàn bộ các module (Login, Chấm điểm, Xem điểm).
- Các SUPL về hiệu năng sẽ tập trung vào các Test Case có lưu lượng truy cập lớn như kỳ thi trực tuyến hoặc nộp bài đồng loạt.
- Sử dụng bộ mã SUPL rút gọn (S01, S02...) đã thống nhất ở Chương 4 để đảm bảo tính nhất quán.

### 5.4.3. Danh mục các SUPL cốt lõi dùng trong ma trận

Để bảng đạt được độ dài và sự chi tiết cần thiết, nhóm phân rã các SUPL thành các mục tiêu kiểm soát cụ thể như sau:

Bảng 5.4.1. Danh mục SUPL cốt lõi dùng trong ma trận (Chi tiết phân rã)

|     |     |     |
| --- | --- | --- |
| Mã SUPL | Tên yêu cầu phi chức năng | Diễn giải mục tiêu kiểm soát / Kiểm thử |
| S01 | Độ chính xác AI (Accuracy) | Kiểm tra tỷ lệ sai số của OCR và độ khớp của thuật toán chấm điểm tự luận. |
| S02 | Tích hợp API (Integration) | Kiểm tra tính ổn định của kết nối với hệ thống FAP và cổng thanh toán học phí. |
| S03 | Bảo mật phân quyền (Security) | Kiểm tra việc ngăn chặn học sinh truy cập vào module quản lý đề thi của giáo viên. |
| S04 | Giao diện Responsive (Usability) | Kiểm tra khả năng hiển thị và thao tác trên điện thoại, máy tính bảng của học sinh. |
| S05 | Trải nghiệm người dùng (UX) | Kiểm tra tính tự nhiên của ngôn ngữ AI Tutor và thời gian làm quen hệ thống. |
| S06 | Tính sẵn sàng (Availability) | Kiểm tra khả năng hoạt động liên tục trong các khung giờ cao điểm thi cử (99.9%). |
| S07 | Chống gian lận (Integrity) | Kiểm tra độ nhạy của tính năng khóa màn hình và nhận diện người lạ khi thi. |
| S08 | Sao lưu dữ liệu (Recoverability) | Kiểm tra khả năng phục hồi bài thi ngay lập tức khi máy tính học sinh sập nguồn. |
| S09 | Thời gian phản hồi (Performance) | Kiểm tra phản hồi của AI Tutor dưới 3 giây và kết quả chấm bài dưới 10 giây. |
| S10 | Khả năng chịu tải (Scalability) | Kiểm tra hệ thống khi có 2,000 học sinh cùng truy cập làm bài tập một lúc. |
| S11 | Cập nhật tri thức (Maintainability) | Kiểm tra quy trình cập nhật tài liệu học tập mới vào "bộ não" của AI. |
| S12 | Giám sát Model Drift (MLOps) | Kiểm tra hệ thống cảnh báo khi độ chính xác của AI giảm sút theo thời gian. |
| S13 | Hạ tầng Cloud (Architecture) | Kiểm tra tính tương thích trên Azure/AWS và khả năng tự động mở rộng tài nguyên. |
| S14 | Tích hợp LLM (LLM Services) | Kiểm tra kết nối an toàn tới OpenAI/Gemini và quản lý Token sử dụng. |
| S15 | Thương hiệu FPT (Compliance) | Kiểm tra việc tuân thủ các quy chuẩn về logo, màu sắc đặc trưng của FPT Education. |

5.4.4. Bảng diễn giải ánh xạ từ Supplementary Requirements sang Test Cases

Bảng dưới đây chi tiết hóa việc chuyển đổi các yêu cầu bổ sung (phi chức năng) thành các trường hợp kiểm thử cụ thể. Mỗi SUPL có thể được kiểm chứng bởi một hoặc nhiều Test Case tùy thuộc vào phạm vi ảnh hưởng của yêu cầu đó lên các module chức năng.

Bảng 5.4.2. Diễn giải ánh xạ SUPLs ⇒ TCs (Chi tiết toàn diện)

|     |     |     |     |
| --- | --- | --- | --- |
| Mã SUPL | Nội dung yêu cầu | Mã Test Case | Diễn giải mục tiêu kiểm thử cụ thể |
| S01 | Độ chính xác AI | TC-S01-01 | Kiểm tra tỷ lệ nhận diện đúng ký tự tay (OCR) đạt trên 90%. |
|     |     | TC-S01-02 | Kiểm tra độ lệch điểm số giữa AI và giáo viên (sai số < 5%). |
| S02 | Tích hợp hệ thống | TC-S02-01 | Kiểm tra khả năng truy xuất dữ liệu từ API FAP trong < 2 giây. |
|     |     | TC-S02-02 | Kiểm tra tính đúng đắn của dữ liệu khi đồng bộ điểm ngược về FAP. |
| S03 | Bảo mật phân quyền | TC-S03-01 | Kiểm tra ngăn chặn truy cập URL trái phép (học sinh vào trang quản lý đề). |
|     |     | TC-S03-02 | Kiểm tra cơ chế mã hóa mật khẩu và token JWT khi giao tiếp API. |
|     |     | TC-S03-03 | Kiểm tra tính năng tự động đăng xuất sau 30 phút không hoạt động. |
| S04 | Giao diện Responsive | TC-S04-01 | Kiểm tra hiển thị module thi trên màn hình iPhone/Android (không vỡ khung). |
|     |     | TC-S04-02 | Kiểm tra tính tương thích của Dashboard giáo viên trên iPad và Tablet. |
| S05 | Trải nghiệm người dùng | TC-S05-01 | Kiểm tra số bước thao tác để nộp bài (không quá 3 lần click). |
|     |     | TC-S05-02 | Kiểm tra tính dễ hiểu của các câu lệnh phản hồi từ AI Tutor. |
| S06 | Tính sẵn sàng | TC-S06-01 | Kiểm tra khả năng tự phục hồi của server khi bị ngắt kết nối đột ngột. |
|     |     | TC-S06-02 | Kiểm tra Uptime hệ thống trong kỳ thi thử quy mô toàn trường. |
| S07 | Chống gian lận | TC-S07-01 | Kiểm tra AI phát hiện khi học sinh chuyển tab trình duyệt trong lúc thi. |
|     |     | TC-S07-02 | Kiểm tra cảnh báo khi có hơn 1 khuôn mặt xuất hiện trước camera. |
|     |     | TC-S07-03 | Kiểm tra tính năng khóa chuột và bàn phím (trừ các phím cho phép). |
| S08 | Sao lưu & Phục hồi | TC-S08-01 | Kiểm tra tính năng Auto-save bài làm mỗi 30 giây vào Local Storage. |
|     |     | TC-S08-02 | Kiểm tra phục hồi phiên thi khi trình duyệt bị tắt đột ngột (Crash). |
| S09 | Thời gian phản hồi | TC-S09-01 | Kiểm tra thời gian AI tóm tắt bài giảng dài 45 phút (Yêu cầu < 30 giây). |
|     |     | TC-S09-02 | Kiểm tra tốc độ load trang chủ khi có 500 người truy cập đồng thời. |
| S10 | Khả năng chịu tải | TC-S10-01 | Kiểm tra Stress Test với 2,000 học sinh cùng nhấn nút "Nộp bài". |
|     |     | TC-S10-02 | Kiểm tra ngưỡng chịu tải tối đa của Database trước khi xảy ra lỗi. |
| S11 | Dễ bảo trì | TC-S11-01 | Kiểm tra khả năng import ngân hàng câu hỏi mới mà không cần restart server. |
| S12 | Giám sát Model AI | TC-S12-01 | Kiểm tra hệ thống ghi Log các trường hợp AI chấm sai để huấn luyện lại. |
| S13 | Ràng buộc hạ tầng | TC-S13-01 | Kiểm tra tính tương thích khi deploy hệ thống trên nền tảng Docker. |
| S14 | Tích hợp LLM | TC-S14-01 | Kiểm tra cơ chế ngắt kết nối khi vượt quá hạn mức Token của OpenAI. |
|     |     | TC-S14-02 | Kiểm tra xử lý lỗi khi API của bên thứ ba (Gemini/GPT) bị gián đoạn. |
| S15 | Tuân thủ thương hiệu | TC-S15-01 | Kiểm tra mã màu (Orange/White) và font chữ theo chuẩn FPT Education. |
|     |     | TC-S15-02 | Kiểm tra vị trí đặt Logo và thông tin bản quyền trên chân trang (Footer). |

Để bảng diễn giải 5.4.2 đạt độ dài và chiều sâu đúng như cậu mong muốn (trên 20-30 dòng), tớ sẽ không chỉ liệt kê các mã mà sẽ bóc tách từng khía cạnh kiểm thử của các yêu cầu phi chức năng.

Trong dự án AI THPT FPT, một yêu cầu như "Bảo mật" hay "Độ chính xác AI" sẽ cần nhiều bài test khác nhau (Test cho học sinh, Test cho giáo viên, Test cho hệ thống). Cách làm này khiến bảng cực kỳ dài và chứng minh được nhóm đã phân tích rất kỹ các ràng buộc hệ thống.

5.4.5. Ma trận dấu vết tổng hợp Supplementary Requirements ⇒ Test Cases

Bảng ma trận dưới đây thể hiện mối liên hệ chéo giữa các yêu cầu phi chức năng và các bài kiểm thử tương ứng. Các cột TC được rút gọn từ bảng 5.4.2 để đảm bảo tính bao quát.

Bảng 5.4.3. Ma trận nhị phân SUPLs ⇒ TCs

|     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SUPL \\ TC | TC 01-01 | TC 01-02 | TC 14-01 | TC 14-02 | TC 14-03 | TC 17-01 | TC 17-02 | TC 17-03 | TC 17-04 |
| F01 |     |     | X   |     | X   |     | X   |     |     |
| F02 | X   |     |     |     |     |     |     |     |     |
| F03 |     | X   |     |     |     |     | X   | X   |     |
| U01 | X   |     |     | X   |     | X   |     |     |     |
| U03 |     | X   |     | X   |     |     |     |     |     |
| R02 |     |     |     |     | X   |     |     |     | X   |
| P01 | X   |     | X   | X   |     | X   |     |     |     |
| P03 |     |     |     |     |     |     |     |     |     |
| S01 |     |     | X   |     |     | X   |     |     |     |
| D04 |     | X   |     | X   |     |     |     | X   |     |
| UI1 | X   |     | X   |     |     | X   |     |     |     |
| UI2 |     |     |     |     |     |     |     |     |     |
| SW  |     |     |     |     |     |     |     |     |     |

5.4.7. Kết luận của mục 5.4

Việc xây dựng ma trận dấu vết giữa Supplementary Requirements và Test Cases đã giúp nhóm hoàn thiện nốt nhánh cuối cùng ở đáy của kim tự tháp yêu cầu cho hệ thống AI THPT FPT. Nếu mục 5.3 chứng minh rằng 100% các Scenario nghiệp vụ đã được bao phủ, thì mục 5.4 là bằng chứng cho thấy các yêu cầu phi chức năng cốt lõi—đặc biệt là độ chính xác của thuật toán AI, tính bảo mật phòng thi và khả năng chịu tải hệ thống—cũng đã được chuyển hóa thành tập Test Case tương ứng để kiểm chứng.

Nhờ đó, kho yêu cầu của dự án không chỉ dừng lại ở mức đặc tả lý thuyết, mà đã thiết lập được một mạng lưới truy vết khép kín. Điều này cho phép đội ngũ QA đánh giá độ bao phủ kiểm thử một cách toàn diện theo cả hai chiều: chức năng (Functional) và phi chức năng (Non-functional), đảm bảo hệ thống vận hành ổn định và tin cậy trước khi triển khai thực tế tại trường.

Chào cậu, chúng mình cùng bước sang chương cuối cùng nhưng lại là "linh hồn" của quản lý yêu cầu chuyên nghiệp: GitHub và Baselines.

Tớ sẽ chuyển đổi toàn bộ nội dung từ hệ thống Vinamilk sang hệ thống AI THPT FPT, đồng thời tinh chỉnh các mốc thời gian và sản phẩm đặc thù (như AI Model, Dataset, Prompt Engineering) để báo cáo của cậu trở nên sắc sảo và đúng chuyên môn nhất.

# CHƯƠNG 6: QUẢN LÝ YÊU CẦU TRÊN CÔNG CỤ VÀ QUẢN LÝ THAY ĐỔI

## 6.2. Phiên bản hóa kho yêu cầu và Quản lý vòng đời (Traceability from/to)

Sau khi triển khai công cụ quản lý yêu cầu trên GitHub ở mục 6.1, bước tiếp theo của dự án là tổ chức phiên bản hóa kho yêu cầu và quản lý vòng đời của từng yêu cầu theo nguyên tắc truy vết hai chiều (trace from / trace to).

Đối với hệ thống AI THPT FPT, việc quản lý này không chỉ dừng lại ở các dòng văn bản mà còn là sự kiểm soát sự tiến hóa của các thuật toán AI và dữ liệu huấn luyện. Mục 6.2 tập trung vào cách nhóm kiểm soát kho yêu cầu từ giai đoạn hình thành nhu cầu (NEEDs) cho tới khi các module AI được kiểm thử độ chính xác (TCs) và chốt phiên bản phát hành.

### 6.2.1. Mục đích của việc phiên bản hóa kho yêu cầu

Việc phiên bản hóa kho yêu cầu được thực hiện nhằm ba mục đích chính:

- Thứ nhất - Thiết lập cơ sở (Baselines): Giúp nhóm xác định rõ tại mỗi thời điểm của dự án (Inception, Elaboration, Construction), tập yêu cầu nào về AI và chấm điểm đã được thẩm định để làm cơ sở cho việc huấn luyện mô hình.
- Thứ hai - Kiểm soát Scope Creep: Đặc thù dự án AI rất dễ bị "tràn phạm vi" do nhu cầu huấn luyện thêm dữ liệu. Mọi yêu cầu mới về tính năng AI sau mỗi Baseline đều phải đi qua quy trình Change Request (CR) trên GitHub Issues thay vì sửa trực tiếp.
- Thứ ba - Quản lý vòng đời và Truy vết: Nhờ phiên bản hóa, nhóm có thể trả lời câu hỏi: yêu cầu chấm điểm OCR này xuất hiện từ Baseline nào, đã đạt độ chính xác Verified chưa, và khi thay đổi thuật toán thì ảnh hưởng đến những kịch bản thi (Scenarios) nào.

### 6.2.2. Cơ sở lý thuyết và nguyên tắc quản lý vòng đời

Kho yêu cầu của dự án AI THPT FPT được tổ chức theo kim tự tháp RUP: NEEDs → FEATs → UCs / SUPLs → SCEs → TCs.

Mỗi yêu cầu trên GitHub sẽ được quản lý thông qua hệ thống Labels để phản ánh trạng thái vòng đời:

- Proposed: Yêu cầu mới được đề xuất bởi giáo viên/học sinh.
- Approved: Đã được trưởng nhóm phân tích phê duyệt.
- In Development: Đang trong quá trình viết Code hoặc huấn luyện AI Model.
- Verified / Ready: Đã vượt qua các bài kiểm thử độ chính xác (Accuracy) và sẵn sàng tích hợp.
- Suspended / Rejected: Bị tạm dừng hoặc loại bỏ do không khả thi về mặt kỹ thuật AI.

### 6.2.3. Phiên bản hóa kho yêu cầu theo các Baseline của dự án

Theo RMP, dự án thiết lập 3 mốc Baseline chính trên GitHub bằng tính năng Tags/Releases:

(1) Baseline 1 – Mốc Tầm nhìn và Nhu cầu (Cuối pha Inception)

- Thành phẩm đóng băng: Danh sách Stakeholders (Nhà trường, Phụ huynh), tập yêu cầu thô NEEDs (Nhu cầu chấm điểm tự động, giám sát thi), và bản RMP.
- Ý nghĩa: Chốt phạm vi bài toán AI ban đầu. Mọi mong muốn nảy sinh sau mốc này phải gửi qua Issue "Change Request".

(2) Baseline 2 – Mốc Kiến trúc Yêu cầu (Cuối pha Elaboration)

- Thành phẩm đóng băng: Vision Document chứa các FEATs cốt lõi (AI OCR, Proctoring), Use Case Specification chi tiết cho luồng chấm bài, và Mockup giao diện thi trực tuyến trên Figma.
- Điều kiện phê duyệt: Chuỗi traceability NEEDs → FEATs → UCs thông suốt. Đây là mốc quan trọng vì sau mốc này, các thay đổi về logic chấm điểm AI sẽ ảnh hưởng rất lớn đến kiến trúc hệ thống.

(3) Baseline 3 – Mốc Hoàn thiện Kiểm thử (Cuối pha Construction)

- Thành phẩm đóng băng: SUPLs (Yêu cầu về độ chính xác AI), Scenarios, Test Cases, và toàn bộ 6 ma trận dấu vết đã hoàn thiện ở Chương 5.
- Điều kiện phê duyệt: 100% các yêu cầu phi chức năng về AI (S01, S09...) đã được Verify. Kho yêu cầu được gắn nhãn "Ready for Production" để chuyển sang pha Transition (Triển khai thực tế tại FPT School).

### 6.2.4. Quản lý vòng đời của từng yêu cầu trên GitHub

(Phần này cậu sẽ trình bày cách dùng GitHub Projects (Kanban Board) hoặc Milestones để kéo các Issue từ _To-do_ sang _Done_ tương ứng với trạng thái vòng đời ở mục 6.2.2 nhé).

Để hoàn thiện chương cuối cho hệ thống AI THPT FPT, tớ đã tinh chỉnh toàn bộ nội dung quản lý vòng đời và thay đổi, đưa các yếu tố kỹ thuật đặc thù như mô hình AI, dữ liệu đào tạo và hệ thống FAP vào quy trình quản lý trên GitHub.

Nội dung dưới đây đảm bảo sự nhất quán với kim tự tháp yêu cầu và cấu trúc RUP mà nhóm đang theo đuổi.

6.2.4. Quản lý vòng đời của từng yêu cầu trên GitHub

Trong kho GitHub của dự án AI THPT FPT, mỗi yêu cầu (từ thuật toán chấm điểm đến giao diện giám sát) được xem như một thực thể sống. Vòng đời của một yêu cầu được quản lý qua 5 bước nghiêm ngặt:

- Bước 1. Đề xuất yêu cầu (Proposed): Một yêu cầu mới (NEED) hoặc một yêu cầu thay đổi (CR) được tạo dưới dạng GitHub Issue. Ở giai đoạn này, yêu cầu được gắn nhãn status:proposed.
- Bước 2. Phân tích và phê duyệt (Approved): Sau khi CCB (Ban điều khiển thay đổi) đánh giá tính khả thi về mặt kỹ thuật AI và ngân sách, trạng thái chuyển sang status:approved. Yêu cầu sẵn sàng để đặc tả chi tiết.
- Bước 3. Triển khai / Mô phỏng (In Development): Đây là giai đoạn BA viết đặc tả UC, nhóm AI huấn luyện mô hình (Model Training), hoặc thiết kế Mockup Figma cho tính năng AI Tutor. Trạng thái: status:in-development.
- Bước 4. Kiểm chứng (Verified / Ready): Khi thuật toán AI đạt độ chính xác yêu cầu và các Test Case đã Pass, QA chuyển trạng thái sang status:verified. Đây là mốc để chốt Baseline 3.
- Bước 5. Tạm ngưng hoặc loại bỏ (Suspended / Rejected): Áp dụng cho các yêu cầu không khả thi (ví dụ: AI không thể nhận diện chữ viết tay quá mờ) hoặc không phù hợp với tiêu chí của trường FPT.

6.2.5. Quản lý Traceability From / Traceability To

Hệ thống AI THPT FPT sử dụng cơ chế truy vết hai chiều để kiểm soát sự thay đổi:

- a. Trace from (Truy vết ngược): Giúp trả lời câu hỏi: _"Tại sao tính năng AI này tồn tại?"_.
    - Ví dụ: Từ TC-UC14-02 (Test ảnh mờ) truy ngược về SCE-UC14-02, rồi lên UC-14 (Chấm bài), và cuối cùng là NEED-05 (Giảm tải chấm bài cho giáo viên).
- b. Trace to (Truy vết xuôi): Giúp trả lời câu hỏi: _"Nhu cầu này đã được hiện thực hóa đến đâu?"_.
    - Ví dụ: Từ NEED-08 (Giám sát thi) trace tới FEAT-17, từ đó tỏa ra các UC-17, SUPL-S07 (Chống gian lận) và kết thúc tại các Test Cases tương ứng.

6.2.6. Cách triển khai Versioning và Lifecycle trên GitHub

Nhóm áp dụng mô hình quản lý hiện đại trên GitHub để bám sát hướng dẫn KTCK:

- Issues: Mỗi yêu cầu là một Issue có ID duy nhất (ví dụ: #14 cho UC-14).
- Labels: Quản lý trạng thái (status:verified) và phiên bản (release:baseline-2).
- Issue Links: Sử dụng cú pháp Trace from: #ID trong phần mô tả để liên kết các tầng yêu cầu.
- Tags/Releases: Sử dụng tính năng Release của GitHub để đóng băng các mốc baseline-1, baseline-2, baseline-3.

## 6.3. Đề xuất quy trình quản lý yêu cầu thay đổi (CRM)

Trong bối cảnh hệ thống AI THPT FPT có nhiều thành phần phụ thuộc chặt chẽ (Ví dụ: Thay đổi Model AI chấm điểm sẽ kéo theo thay đổi về Scenario và Test Case), việc quản lý thay đổi là bắt buộc để tránh Scope Creep (tràn phạm vi).

### 6.3.1. Mục đích của quy trình quản lý thay đổi

1.  Chính thống hóa: Mọi thay đổi sau Baseline đều phải qua Change Request (CR) trên GitHub.
2.  Đánh giá tác động (Impact Analysis): CCB đánh giá xem việc thêm một tính năng AI mới có làm chậm tốc độ hệ thống hay ảnh hưởng đến độ chính xác hiện tại không.
3.  Đồng bộ hóa Artifacts: Đảm bảo khi sửa 1 yêu cầu, các Ma trận dấu vết và tài liệu Vision, UC cũng được cập nhật tương ứng.
4.  Minh bạch lịch sử: Tạo log thay đổi để phục vụ kiểm tra chất lượng (QA Audit).

### 6.3.2. Phạm vi của quy trình thay đổi

Quy trình CRM áp dụng cho tất cả Artifacts: từ nhu cầu (NEEDs), tính năng AI (FEATs), kịch bản (SCEs) đến Mockup Figma và dữ liệu đồng bộ FAP. Mọi thay đổi sau khi đã "đóng băng" Baseline đều phải tuân thủ quy trình này.

### 6.3.3. Ban điều khiển thay đổi (CCB) của dự án AI THPT FPT

Ban CCB bao gồm:

- Project Manager (PM): Quyết định về lịch trình và nguồn lực.
- Lead Analyst (BA): Đánh giá tác động lên luồng nghiệp vụ sư phạm.
- QA Lead: Đánh giá tác động lên độ bao phủ kiểm thử và độ chính xác AI.
- Stakeholder Representative: Đại diện trường FPT (nếu cần) để chốt về nhu cầu thực tế

Nhóm phân loại CR thành 4 nhóm để tối ưu hóa quy trình xử lý trên GitHub:

1.  Enhancement Request (Yêu cầu mở rộng): Bổ sung môn học mới cho AI chấm điểm, thêm tính năng nhận diện hành vi gian lận mới.
2.  Defect / Correction Request (Sửa lỗi đặc tả): AI nhận diện sai chữ viết tay trong điều kiện thiếu sáng, thiếu luồng ngoại lệ khi mất kết nối FAP.
3.  Documentation Change (Cập nhật tài liệu): Điều chỉnh Glossary về các thuật ngữ AI, cập nhật ma trận dấu vết FEAT ⇒ UC.
4.  AI Model / Traceability Change: Cập nhật bộ dữ liệu huấn luyện (Dataset), bổ sung Test Case cho các Scenario mới phát sinh.

6.3.5. Quy trình quản lý thay đổi yêu cầu đề xuất cho dự án

Quy trình CRM của dự án AI THPT FPT gồm 8 bước nghiêm ngặt, bám sát mô hình RUP và công cụ GitHub:

- Bước 1. Submit CR: Tạo GitHub Issue với nhãn change-request và status:proposed.
- Bước 2. Review CR: CCB xem xét tính hợp lệ của yêu cầu (ví dụ: yêu cầu AI chấm điểm thơ lục bát có nằm trong phạm vi không?).
- Bước 3. Confirm Duplicate or Reject: Loại bỏ các yêu cầu trùng lặp để giữ kho Issue sạch sẽ.
- Bước 4. Impact Analysis: BA phân tích xem thay đổi có làm đứt gãy chuỗi NEED → FEAT → UC không; QA đánh giá lại độ chính xác (Accuracy) bị ảnh hưởng.
- Bước 5. Decision: CCB quyết định _Approved_, _Rejected_ hoặc _Deferred_ (hoãn lại đến học kỳ sau).
- Bước 6. Assign & Schedule Work: PM giao việc cho AI Engineer sửa Model hoặc BA sửa đặc tả.
- Bước 7. Make Changes: Thực hiện cập nhật Code, tài liệu và Mockup Figma.
- Bước 8. Verify Changes: QA chạy lại các Test Case (Regression Testing) để đảm bảo thay đổi không làm hỏng các tính năng cũ.

6.3.6. Bảng quy trình quản lý thay đổi đề xuất

Cậu hãy chèn bảng này vào báo cáo, nó sẽ làm cho phần trình bày cực kỳ minh bạch và chuyên nghiệp.

Bảng 6.3.1. Quy trình quản lý yêu cầu thay đổi của dự án AI THPT FPT

|     |     |     |     |
| --- | --- | --- | --- |
| Bước | Hoạt động chính | Vai trò thực hiện | Sản phẩm đầu ra (Artifacts) |
| 1   | Đề xuất CR | Submitter | GitHub Issue (CR-xx) |
| 2   | Xem xét sơ bộ | CCB Manager | Trạng thái Proposed/Update |
| 3   | Xác nhận/Từ chối | CCB Manager | Trạng thái Rejected/Duplicate |
| 4   | Phân tích ảnh hưởng | BA / QA / AI Lead | Impact Analysis Report |
| 5   | Phê duyệt | CCB Manager | Trạng thái Approved / Release Tag |
| 6   | Gán việc | Project Manager | Assignee trên GitHub |
| 7   | Thực hiện thay đổi | BA / Dev / AI Engineer | Updated Specs / Code / Model |
| 8   | Kiểm chứng & Đóng | QA / Configuration Mgr | Trạng thái Closed / Verified |

6.3.7. Minh họa một ví dụ CR trong dự án AI THPT FPT

Để làm rõ hơn quy trình quản lý thay đổi, nhóm minh họa bằng một ví dụ thực tế phát sinh trong quá trình phát triển hệ thống AI:

CR-02 – Bổ sung nhận diện hành vi sử dụng tài liệu giấy (Proctoring nâng cao)

- Nguồn đề xuất: Ban giám hiệu / Stakeholder.
- Lý do: Tăng cường khả năng chống gian lận khi AI phát hiện học sinh cúi xuống nhìn tài liệu không phải đề thi.
- Artifact bị ảnh hưởng: \* FEAT-17 (Giám sát thi AI), UC-17 (Giám sát phòng thi), SUPL-S07 (Tính toàn vẹn).
    - Mockup màn hình giám sát (Figma), ma trận FEAT ⇒ UC, SCE ⇒ TC (bổ sung kịch bản kiểm thử hành vi mới).
- Ảnh hưởng release: CR mức High effort vì cần thu thập thêm Dataset về hành vi gian lận và huấn luyện lại mô hình AI.
- Quyết định: Approved cho Release 2.0 (sau Baseline 3) do cần thời gian huấn luyện Model.

6.4. Demo quy trình (Ảnh chụp màn hình thao tác trên tool)

6.4.1. Mục đích của hoạt động demo

Hoạt động demo trên GitHub xác nhận rằng công cụ được sử dụng để quản lý vòng đời yêu cầu AI một cách thực tế. Minh họa được cách một yêu cầu từ lúc là "Nhu cầu thô" được tinh chế, kiểm thử độ chính xác và đóng gói vào các Baseline.

6.4.2. Phạm vi demo của dự án AI THPT FPT

Nhóm tập trung demo quy trình quản lý yêu cầu trên GitHub, bao gồm:

- Khởi tạo Repository dự án và hệ thống Labels phân loại (AI, OCR, Proctoring).
- Tạo Issues cho NEEDs, FEATs, UCs, SUPLs, SCEs, TCs.
- Thể hiện liên kết Traceability giữa bài test AI và yêu cầu nghiệp vụ.
- Demo quy trình xử lý Change Request cho một tính năng AI mới.
- Chốt các mốc Baseline 1, 2, 3 bằng tính năng Release/Tag.

6.4.3. Nội dung demo đề xuất trong báo cáo

Bước 1. Khởi tạo repository quản lý yêu cầu Nhóm tạo repository trung tâm cho dự án AI THPT FPT để lưu trữ toàn bộ yêu cầu và tài liệu phân tích.

Hình 6.4.1. Repository GitHub của dự án quản lý yêu cầu AI THPT FPT

Bước 2. Thiết lập Labels cho các loại yêu cầu và trạng thái Thiết lập nhãn để lọc yêu cầu nhanh chóng (ví dụ: type:AI-Model, status:verified).

Hình 6.4.2. Hệ thống Labels phân loại yêu cầu và trạng thái trên GitHub

Bước 3. Tạo các Issues đại diện cho kho yêu cầu Tạo các issue mẫu cho tầng yêu cầu AI, ví dụ:

- FEAT-14 – Chấm bài tự luận bằng AI OCR.
- UC-14 – Chấm bài thi trực tuyến.
- TC-UC14-01 – Kiểm thử độ chính xác chấm điểm bài thi.

Hình 6.4.3. Danh sách Issues đại diện cho các tầng yêu cầu AI

Bước 4. Minh họa traceability from/to giữa các yêu cầu Liên kết các Issue bằng cách ghi mã truy vết trong phần mô tả.

- _Trace from:_ FEAT-14
- _Trace to:_ UC-14, SUPL-S01, TC-UC14-01

Hình 6.4.5. Minh họa liên kết trace from / trace to trong Issue AI trên GitHub

Bước 5. Thảo luận và tinh chế yêu cầu qua GitHub Discussions Minh họa việc nhóm thảo luận về ngưỡng chính xác (Threshold) của AI trước khi duyệt yêu cầu.

Hình 6.4.6. Thảo luận trên GitHub về độ chính xác của mô hình OCR

Bước 6. Demo quy trình xử lý Change Request Tạo issue CR-02 (Nhận diện tài liệu giấy), thể hiện trạng thái từ Proposed sang Approved sau khi CCB phân tích ảnh hưởng.

Hình 6.4.7. Change Request cho tính năng Proctoring nâng cao

Bước 7. Demo Pull Request dùng để thực thi thay đổi Sử dụng PR để cập nhật tài liệu đặc tả Use Case và ma trận dấu vết sau khi CR được duyệt.

Hình 6.4.9. Pull Request cập nhật ma trận dấu vết sau khi sửa thuật toán AI

Bước 8. Demo chốt baseline bằng Release / Tag Tạo các mốc baseline-1 (Vision), baseline-2 (Architecture), baseline-3 (Ready for Test).

Hình 6.4.10. Danh sách Release/Tag lưu trữ các Baseline của dự án AI

6.4.5. Đánh giá mức độ đáp ứng của công cụ

GitHub đáp ứng tốt các tiêu chí RM cho dự án AI THPT FPT:

- Tính minh bạch: Mọi thành viên đều theo dõi được trạng thái huấn luyện AI.
- Tính kết nối: Hỗ trợ Traceability linh hoạt qua Issue Links.
- Tính kiểm soát: Quy trình CRM giúp ngăn chặn việc thay đổi thuật toán tùy tiện làm hỏng hệ thống.
- Hạn chế: Cần kết hợp Excel cho các ma trận dấu vết phức tạp (như ma trận chéo 30x30).

6.4.6. Kết luận của mục 6.4

Phần demo đã chứng minh năng lực quản lý yêu cầu tự động của nhóm. Hệ thống yêu cầu không chỉ nằm trên giấy mà được vận hành sống động trên GitHub, từ lúc đề xuất cho đến khi chốt Baseline, đảm bảo tính toàn vẹn và sẵn sàng cho giai đoạn triển khai thực tế.

Chào cậu, đây là phần KẾT LUẬN tổng thể cho báo cáo, được tớ tinh chỉnh hoàn toàn để phù hợp với dự án AI THPT FPT. Tớ đã giữ nguyên cấu trúc mạch lạc của mẫu nhưng thay đổi toàn bộ nội dung nghiệp vụ sang các vấn đề về giáo dục, chấm điểm AI, giám sát thi và tích hợp hệ thống FAP/LMS.

Cậu có thể sử dụng nội dung này để chốt lại toàn bộ báo cáo một cách chuyên nghiệp nhất:

# KẾT LUẬN

Qua quá trình thực hiện đề tài “Phân tích và quản lý yêu cầu cho hệ thống hỗ trợ học tập và khảo thí thông minh (AI THPT FPT)”, nhóm đã vận dụng hệ thống kiến thức từ học phần AMS431 để xây dựng một bộ sản phẩm yêu cầu hoàn chỉnh, có cấu trúc chặt chẽ và khả năng truy vết xuyên suốt. Từ việc xác định bài toán thực tế tại trường THPT FPT, nhóm đã triển khai từ các bước thu thập yêu cầu, mô hình hóa BPMN, xác định NEEDs, tinh chế thành FEATs, đặc tả Use Cases, xây dựng Supplementary Requirements, Glossary, Scenarios, Test Cases và các ma trận dấu vết tương ứng. Toàn bộ quá trình này đều hướng tới mục tiêu làm rõ một hệ thống giáo dục số hiện đại, tích hợp công nghệ AI OCR để chấm điểm tự động, Proctoring để giám sát thi và AI Tutor để hỗ trợ cá nhân hóa học tập cho học sinh.

Kết quả lớn nhất mà nhóm đạt được là hình thành chuỗi logic hoàn chỉnh theo mô hình kim tự tháp yêu cầu: NEEDs → FEATs → UCs/SUPLs → SCEs → TCs. Đồng thời, nhóm đã tiếp cận tư duy quản lý hiện đại thông qua GitHub để kiểm soát Issue, Change Request và Baseline. Điều này giúp nhóm hiểu rằng phân tích yêu cầu không chỉ là viết tài liệu, mà còn là quản lý sự tiến hóa và duy trì tính nhất quán của hệ thống trong toàn bộ vòng đời RUP.

1\. Thuận lợi

- Tính thực tiễn cao: Đề tài gắn liền với bối cảnh chuyển đổi số giáo dục tại FPT Education, giúp nhóm dễ dàng hình dung quy trình chấm thi, giám sát phòng thi và nhu cầu thực tế của giáo viên, học sinh.
- Nền tảng lý thuyết và Template chuẩn: Việc bám sát các mẫu của IBM/RUP (Vision, Use Case Spec, RMP...) giúp nhóm có khung chuẩn chuyên nghiệp, đảm bảo tính thống nhất về thuật ngữ và hình thức báo cáo.
- Phân công công việc rõ ràng: Nhóm đã phân định rõ vai trò BA (đặc tả nghiệp vụ), QA (kiểm tra chất lượng, traceability) và PM (điều phối kế hoạch), giúp tiến độ dự án được đảm bảo đúng Milestones.
- Công cụ hỗ trợ đa dạng: Nhóm đã tận dụng hiệu quả các công cụ như Figma (Mockup), Draw.io (BPMN), GitHub (RM Tool) và Excel (Traceability Matrix) để hiện thực hóa các yêu cầu lý thuyết.

2\. Khó khăn

- Độ phức tạp của công nghệ AI: Việc đặc tả các yêu cầu phi chức năng (SUPLs) cho AI như độ chính xác OCR, thời gian phản hồi của Model và tính an toàn dữ liệu là một thách thức lớn đối với sinh viên.
- Khối lượng tài liệu đồ sộ: Với hơn 6 ma trận dấu vết và hàng chục kịch bản kiểm thử, việc duy trì tính nhất quán (Consistency) khi có một thay đổi nhỏ ở tầng FEAT đòi hỏi sự tỉ mỉ và tập trung rất cao.
- Làm quen với quy trình quản lý trên GitHub: Việc chuyển đổi từ tư duy lưu trữ file sang tư duy quản lý vòng đời yêu cầu (Proposed, Approved, Verified) và Baseline trên GitHub bước đầu gây không ít lúng túng cho nhóm.
- Áp lực thời gian: Khối lượng công việc lớn trong một học kỳ đòi hỏi nhóm phải liên tục rà soát và đồng bộ hóa tài liệu giữa các phiên bản Baseline 1, 2 và 3.

3\. Định hướng phát triển

- Hoàn thiện kho quản lý yêu cầu: Phát triển đầy đủ Issue cho toàn bộ các tầng yêu cầu trên GitHub, kết hợp Project Board để theo dõi Requirement Volatility một cách trực quan hơn.
- Xây dựng Prototype vận hành: Phát triển từ Mockup sang bản demo phần mềm có khả năng nhận diện OCR cơ bản để kiểm chứng các Use Case cốt lõi trong môi trường thực tế.
- Mở rộng kiểm thử phi chức năng: Triển khai các bài kiểm thử hiệu năng (Stress Test) và kiểm thử độ chính xác trên tập dữ liệu lớn (Dataset) để đối chiếu với Supplementary Specification.
- Tăng cường khả năng cá nhân hóa: Nghiên cứu sâu hơn về thuật toán gợi ý lộ trình học tập để tinh chế các FEAT liên quan đến AI Tutor, giúp hỗ trợ học sinh hiệu quả hơn.

4\. Tổng kết chung

Nhìn chung, đề tài AI THPT FPT đã giúp nhóm tiếp cận trọn vẹn quy trình kỹ nghệ yêu cầu: từ lập kế hoạch, phân tích nghiệp vụ đến quản lý thay đổi và chốt Baseline. Dù còn những hạn chế nhất định, kết quả này phản ánh nỗ lực vận dụng lý thuyết vào bài toán thực tế của nhóm. Nhóm nhận thức rõ rằng một hệ thống AI tốt không chỉ nằm ở thuật toán, mà bắt đầu từ việc hiểu đúng nhu cầu stakeholder và quản lý chặt chẽ các yêu cầu trong suốt vòng đời dự án.