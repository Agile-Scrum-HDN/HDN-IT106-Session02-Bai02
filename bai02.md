# KẾ HOẠCH VẬN HÀNH AGILE - DỰ ÁN GREENMART (6 TUẦN ĐẦU)

**Thông tin chung:**
*   **Dự án:** Nâng cấp Hệ thống quản lý bán hàng đa kênh cho chuỗi 30 siêu thị GreenMart.
*   **Thời lượng áp dụng kế hoạch:** 6 tuần đầu tiên.
*   **Đội dự án (Scrum Team):** Long, Hoa, An, Bình, Chi, Dung (6 thành viên).
*   **Mô hình vận hành:** Scrum.

---

## 1. Lý do chọn Agile thay vì Waterfall

*   **Hạn chế của mô hình Waterfall (Thác nước):** Trong quá khứ, dự án áp dụng Waterfall bắt buộc chốt cứng mọi yêu cầu từ đầu. Khi thị trường bán lẻ biến động hoặc GreenMart phát sinh nhu cầu mới, việc thay đổi gặp vô vàn rào cản. Khách hàng chỉ được xem hệ thống ở giai đoạn cuối dự án, dẫn đến rủi ro "làm xong nhưng không đúng thứ khách cần", gây lãng phí thời gian và chi phí làm lại (re-work).
*   **Tinh thần Agile khắc phục khó khăn:** Agile chia nhỏ dự án thành các chu kỳ ngắn (phát triển lặp - iterative) và chuyển giao sản phẩm liên tục (incremental). Khách hàng được xem và trải nghiệm hệ thống sớm, từ đó đưa ra phản hồi kịp thời để đội điều chỉnh hướng đi. Sự thay đổi không bị xem là "phá vỡ hợp đồng" mà là cơ hội để gia tăng lợi thế cạnh tranh cho khách hàng.
*   **Kết luận:** GreenMart đang trong giai đoạn chuyển đổi số (mở rộng sang bán hàng online đa kênh) - một lĩnh vực có yêu cầu thay đổi liên tục. Do đó, áp dụng Agile là lựa chọn tối ưu và bắt buộc để đảm bảo sản phẩm bám sát nhu cầu thực tế của thị trường và của chuỗi 30 siêu thị.

---

## 2. Nguyên tắc làm việc theo 4 giá trị cốt lõi của Agile

Dưới đây là sự điều chỉnh các thói quen cũ của đội TechViet để phù hợp với 4 giá trị của Tuyên ngôn Agile:

| Thói quen cũ (Cần loại bỏ) | Giá trị Agile bị đi ngược | Đề xuất cách làm mới (Agile) |
| :--- | :--- | :--- |
| **1.** Cả đội chỉ trao đổi qua bình luận trên phần mềm, gần như không họp. | **Cá nhân và sự tương tác** quan trọng hơn quy trình và công cụ. | Tổ chức họp Daily Scrum (15 phút mỗi ngày). Ưu tiên trao đổi trực tiếp hoặc gọi video để giải quyết ngay các điểm nghẽn thay vì chờ đợi qua bình luận. |
| **2.** Viết tài liệu đặc tả rất chi tiết trước, chỉ trình diễn 1 lần ở cuối dự án. | **Sản phẩm chạy tốt** quan trọng hơn tài liệu đầy đủ. | Tập trung tạo ra một phần mềm chạy được (Increment) vào cuối mỗi Sprint. Tài liệu chỉ viết đủ dùng, lấy sản phẩm thực tế làm thước đo tiến độ. |
| **3.** Hợp đồng tính phí và bắt chờ 2 tuần phê duyệt mỗi khi đổi yêu cầu. | **Cộng tác với khách hàng** quan trọng hơn đàm phán hợp đồng. | Product Owner làm việc liên tục với đại diện GreenMart. Chấp nhận thay đổi ưu tiên vào Product Backlog để lên kế hoạch làm ở Sprint tiếp theo mà không cần giấy tờ rườm rà. |
| **4.** Khi thực tế khác với kế hoạch, đội vẫn làm đúng theo kế hoạch ban đầu. | **Phản hồi với sự thay đổi** quan trọng hơn bám sát kế hoạch. | Liên tục đánh giá lại tình hình (Inspect & Adapt) qua các buổi Sprint Review và Retrospective. Kế hoạch của Sprint sau sẽ linh hoạt thay đổi dựa trên tình hình thực tế hiện tại. |

---

## 3. Khung thời gian làm việc (Scrum Framework)

*   **Độ dài Sprint cố định:** Chọn Sprint dài **2 tuần**. Tổng cộng dự án sẽ chạy 3 Sprints trong 6 tuần đầu tiên.
*   **Lý do chọn 2 tuần và sự liên kết với 3 trụ cột Scrum:**
    *   *Minh bạch (Transparency):* 2 tuần là khoảng thời gian đủ ngắn để mọi thành viên thấy rõ tiến độ công việc, không ai bị "chìm" quá lâu trong một tác vụ mà không ai biết.
    *   *Thanh tra (Inspection):* Độ dài này cho phép kiểm tra tiến độ mỗi ngày (Daily Scrum) và kiểm tra chất lượng sản phẩm cùng khách hàng GreenMart (Sprint Review) 2 tuần một lần, tránh rủi ro đi sai hướng quá xa.
    *   *Thích nghi (Adaptation):* Cứ sau 2 tuần, dựa trên phản hồi của GreenMart, đội có cơ hội điều chỉnh Product Backlog và cải tiến cách làm việc (Sprint Retrospective) cho chặng tiếp theo.
*   **Vì sao chọn Scrum:** Scrum cung cấp một nhịp độ cố định (timebox), phân rõ vai trò và có các sự kiện định kỳ giúp đội ngũ kiểm soát tốt sự bất định của mảng bán hàng đa kênh mà Waterfall không làm được.

---

## 4. Phân vai Scrum Team

Để đảm bảo hiệu quả, 6 thành viên được phân vai và ủy quyền như sau:

| Vai trò Scrum | Người đảm nhận | Được quyền quyết định | Không được quyền quyết định |
| :--- | :--- | :--- | :--- |
| **Product Owner (PO)** | **Long** | Quyết định TÍNH NĂNG GÌ cần làm (What), sắp xếp thứ tự ưu tiên trong Product Backlog, và nghiệm thu sản phẩm. | Không được quyết định CÁCH THỨC kỹ thuật (How) và không ép thời gian hoàn thành (Estimate) cho Devs. |
| **Scrum Master (SM)** | **Hoa** | Quyết định CÁCH ÁP DỤNG QUY TRÌNH Scrum, bảo vệ đội khỏi yếu tố gây nhiễu, tháo gỡ rào cản. | Không được quyết định ưu tiên nghiệp vụ (của PO) và không can thiệp vào cách viết code (của Devs). |
| **Developers (Dev Team)** | **An, Bình, Chi** (Lập trình), **Dung** (Tester) | Quyết định CÁCH LÀM (How) để biến yêu cầu thành sản phẩm, quyết định số lượng công việc nhận vào Sprint dựa trên năng lực. | Không được tự ý thay đổi yêu cầu nghiệp vụ của tính năng nếu chưa thông qua Product Owner. |

---

## 5. Artifacts (Tạo tác) & Lịch sự kiện

### 5.1. Product Backlog (Danh sách ưu tiên từ cao xuống thấp)
1.  *(Cao)* Khách hàng có thể tìm kiếm sản phẩm theo tên hoặc danh mục.
2.  *(Cao)* Khách hàng có thể xem chi tiết sản phẩm và thêm vào giỏ hàng.
3.  *(Trung bình)* Khách hàng có thể thanh toán trực tuyến qua cổng thanh toán VNPay/Thẻ tín dụng.
4.  *(Trung bình)* Hệ thống gửi email xác nhận đặt hàng thành công.
5.  *(Thấp)* Khách hàng có thể theo dõi trạng thái đơn hàng (Đang chuẩn bị, Đang giao).
6.  *(Thấp)* Khách hàng được tích lũy điểm thẻ thành viên GreenMart khi mua online.

### 5.2. Sprint Backlog & Mục tiêu Sprint 1
*   **Mục tiêu Sprint 1 (Sprint Goal):** *"Xây dựng luồng mua sắm cơ bản: Khách hàng có thể tìm thấy sản phẩm, xem chi tiết và cho vào giỏ hàng thành công."*
*   **Hạng mục chọn vào Sprint Backlog:** Hạng mục số (1) và (2) từ Product Backlog.

### 5.3. Increment (Phần mềm tăng trưởng) mong đợi cuối Sprint 1
*   Một giao diện Web/App đã được triển khai lên môi trường kiểm thử (Staging), có kết nối cơ sở dữ liệu. Tại đây, GreenMart có thể thực tế gõ tên món hàng, ấn nút "Tìm kiếm", hiện ra danh sách, bấm vào 1 sản phẩm và ấn "Thêm vào giỏ hàng" thành công (số lượng giỏ hàng nhảy số).

### 5.4. Lịch 5 sự kiện Scrum trong 1 Sprint (Kéo dài 2 tuần/10 ngày làm việc)

| Sự kiện | Thời gian diễn ra | Mục đích |
| :--- | :--- | :--- |
| **1. Sprint (Bản thân Sprint)** | Kéo dài đúng 2 tuần. | Là "thùng chứa" tất cả các sự kiện khác, tạo nhịp đập cố định để phát triển sản phẩm. |
| **2. Sprint Planning** | Sáng Ngày 1 (tối đa 4 tiếng). | PO và Dev Team thống nhất Mục tiêu Sprint, chọn hạng mục làm việc và lên kế hoạch thực thi chi tiết. |
| **3. Daily Scrum** | Hàng ngày lúc 9h00 sáng (15 phút). | Dev Team đồng bộ tiến độ, lên kế hoạch cho 24h tới và nêu các khó khăn để SM hỗ trợ giải quyết. |
| **4. Sprint Review** | Chiều Ngày 10 (tối đa 2 tiếng). | Trình diễn Increment (sản phẩm hoàn thành) cho GreenMart, thu thập phản hồi để cập nhật Product Backlog. |
| **5. Sprint Retrospective**| Cuối chiều Ngày 10 (tối đa 1.5 tiếng).| Toàn đội (PO, SM, Devs) nhìn lại Sprint vừa qua, đánh giá con người, công cụ, quy trình để tìm ra 1-2 điểm cải tiến cho Sprint tới. |

---

## 6. Kịch bản Xử lý tình huống thay đổi

**Tình huống 1: Giữa Sprint, khách GreenMart muốn đổi thứ tự ưu tiên — làm tính năng đặt hàng online trước.**
*   **Cách xử lý:** Đội sẽ **không làm gián đoạn Sprint hiện tại**. Scrum Master và Product Owner sẽ bảo vệ (shield) Dev Team khỏi sự thay đổi này.
    *   PO (Long) sẽ ghi nhận yêu cầu tính năng đặt hàng online mới của GreenMart, phân tích và đưa nó vào vị trí ưu tiên cao nhất trong **Product Backlog**.
    *   Tại buổi Sprint Planning của Sprint tiếp theo (chỉ cách vài ngày), đội sẽ chính thức kéo tính năng mới này vào Sprint Backlog để phát triển. Việc này đảm bảo tính linh hoạt (Agile) đáp ứng nhu cầu khách hàng, nhưng vẫn duy trì sự ổn định, tập trung (Focus) cho Dev Team hoàn thành Mục tiêu Sprint hiện tại.

**Tình huống 2: Đến buổi Sprint Review, một tính năng vẫn chưa hoàn thành.**
*   **Cách xử lý:** Đội tuyệt đối tôn trọng sự Minh bạch (Transparency).
    *   Tại Sprint Review, đội sẽ **chỉ trình diễn (demo) những gì đã hoàn thành 100%** (đáp ứng Definition of Done). Không demo tính năng dở dang, lỗi, hoặc "giả lập" cho khách hàng xem.
    *   PO sẽ thông báo rõ tình trạng chưa xong với GreenMart. Hạng mục chưa hoàn thành đó sẽ được trả lại về Product Backlog. PO sẽ xem xét lại mức độ ưu tiên để quyết định có đưa nó vào Sprint tiếp theo hay không.
    *   Trong buổi Sprint Retrospective ngay sau đó, đội sẽ cùng nhau mổ xẻ lý do tại sao tính năng này không xong (Do chia việc quá to? Đánh giá sai nỗ lực? Hay có rào cản hệ thống?) để rút kinh nghiệm và ước lượng chính xác hơn trong chặng tiếp theo.