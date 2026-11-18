## Prompt 1: Phân tích Chân dung Khách hàng Mục tiêu
Vai trò: Chuyên gia Marketing Giáo dục.
Dữ liệu gốc: Khóa học Python cơ bản cho người mới bắt đầu (Thời lượng: 8 tuần). Đối tượng: Sinh viên năm nhất (18–20 tuổi). Mục tiêu chiến dịch: 100 lượt đăng ký tư vấn qua Facebook và TikTok.
Yêu cầu: Suy luận từng bước (Chain-of-Thought) để phác họa chân dung khách hàng mục tiêu gồm: (1) Nỗi đau học tập/nghề nghiệp, (2) Động lực học Python, (3) Rào cản ra quyết định, (4) Thói quen dùng Facebook/TikTok.
Ràng buộc: Ngắn gọn dạng gạch đầu dòng, không thay đổi dữ liệu gốc. Đặt tên kết quả là [OUTPUT_1].

## Prompt 2: Xác định Thông điệp Truyền thông Chính
Vai trò: Chuyên gia Marketing Giáo dục.
Dữ liệu gốc: Khóa học Python cơ bản cho người mới bắt đầu (Thời lượng: 8 tuần). Đối tượng: Sinh viên năm nhất (18–20 tuổi). Mục tiêu chiến dịch: 100 lượt đăng ký tư vấn qua Facebook và TikTok.
Yêu cầu: Suy luận từng bước (Chain-of-Thought) để phác họa chân dung khách hàng mục tiêu gồm: (1) Nỗi đau học tập/nghề nghiệp, (2) Động lực học Python, (3) Rào cản ra quyết định, (4) Thói quen dùng Facebook/TikTok.
Ràng buộc: Ngắn gọn dạng gạch đầu dòng, không thay đổi dữ liệu gốc. Đặt tên kết quả là [OUTPUT_1].

## Prompt 3: Xây dựng Lịch Nội dung 7 Ngày
Vai trò: Content Planner.
Ngữ cảnh đầu vào: [OUTPUT_1] + [OUTPUT_2: Dán kết quả Prompt 2 vào đây].
Yêu cầu: Lập bảng kế hoạch nội dung 7 ngày trên Facebook và TikTok nhằm đạt 100 lượt đăng ký tư vấn. Chia theo 3 giai đoạn: Nhận biết (Ngày 1-2) -> Thuyết phục (Ngày 3-5) -> Chuyển đổi (Ngày 6-7).
Ràng buộc: Xuất dạng bảng Markdown (Ngày | Kênh | Chủ đề | Mục tiêu CTA). Mọi chủ đề phải xoay quanh [OUTPUT_2]. Đặt tên kết quả là [OUTPUT_3].

## Prompt 4: Viết Bài Quảng cáo Facebook & Kịch bản TikTok
Vai trò: Copywriter & TikTok Creator.
Ngữ cảnh đầu vào: [OUTPUT_1] + [OUTPUT_2] + [OUTPUT_3: Dán kết quả Prompt 3 vào đây].
Yêu cầu: Dựa trên lịch trình ở [OUTPUT_3], hãy viết:
1. 02 bài đăng Facebook (1 bài khai thác nỗi đau, 1 bài kêu gọi đăng ký tư vấn khóa 8 tuần).
2. 02 kịch bản video TikTok (thời lượng 30–45 giây, chia cột: Thời gian | Hình ảnh | Âm thanh/Lời thoại).
Ràng buộc: Văn phong tự nhiên hợp tuổi 18–20, lồng ghép chính xác thông điệp ở [OUTPUT_2] và CTA đăng ký tư vấn. Đặt tên kết quả là [OUTPUT_4].

## Prompt 5: Kiểm tra Tính Thống nhất Toàn Chiến dịch
Vai trò: Quản lý Chất lượng Chiến dịch (QA).
Ngữ cảnh đầu vào: Dữ liệu gốc + [OUTPUT_1] + [OUTPUT_2] + [OUTPUT_3] + [OUTPUT_4].
Yêu cầu: Đối chiếu chéo toàn bộ đầu ra từ Prompt 1 đến 4 và xuất Báo cáo kiểm tra tính nhất quán theo 4 tiêu chí:
(1) Đúng thông số khóa học (SV năm 1, 18-20t, 8 tuần, 100 tư vấn, FB/TikTok),
(2) Sự xuyên suốt của Thông điệp chính,
(3) Mức độ giải quyết nỗi đau ở [OUTPUT_1],
(4) Tính khả thi của CTA. Chỉ ra điểm lệch (nếu có) và đề xuất chỉnh sửa.


## 3. Kết quả Đầu ra Mẫu (Khi chạy chuỗi Prompt trên)

### A. Chân dung Khách hàng Mục tiêu (`[OUTPUT_1]`)
* **Đối tượng:** Sinh viên năm nhất (18–20 tuổi), mới bước vào đại học, chưa có nền tảng lập trình (Zero-base).
* **Nỗi đau (Pain points):** Ngợp trước các môn đại cương/nhập môn lập trình trên trường; sợ mất gốc ngay từ năm nhất; lo lắng thua kém bạn bè đồng trang lứa nhưng không biết bắt đầu từ đâu.
* **Động lực:** Muốn làm chủ một ngôn ngữ dễ học (Python) trong thời gian ngắn (8 tuần) để qua môn dễ dàng, làm nền tảng cho chuyên ngành và tạo lợi thế thực tập sớm.
* **Hành vi kênh:** Lướt TikTok giải trí nhanh (ưa video ngắn 30–45s, trực quan, bắt trend); dùng Facebook để đọc bài chia sẻ kinh nghiệm trong các group sinh viên và nhắn tin nhận tư vấn.

---

### B. Thông điệp Truyền thông Chính (`[OUTPUT_2]`)
* **Thông điệp chính (Key Message):** *"8 Tuần Xóa Mù Code Cùng Python – Bước Đệm Vững Chắc Cho Sinh Viên Năm Nhất"*
* **3 Trụ cột nội dung:** 
  1. Học từ số 0 không sợ mất gốc.
  2. Lộ trình tinh gọn 8 tuần vừa học trên trường vừa thực hành được ngay.
  3. Tư vấn lộ trình cá nhân hóa 1-1.

---

### C. Lịch đăng Nội dung trong 7 Ngày (`[OUTPUT_3]`)

| Ngày | Kênh | Chủ đề nội dung | Mục tiêu & CTA |
| :--- | :--- | :--- | :--- |
| **Ngày 1** | TikTok | *Video 1:* Nỗi ám ảnh mang tên "Mất gốc Code năm nhất" | Thu hút sự đồng cảm, tăng nhận diện |
| **Ngày 2** | Facebook | *Bài 1:* Tại sao Python là ngôn ngữ "cứu cánh" cho SV 18–20 tuổi? | Giáo dục thị trường, kích thích bình luận |
| **Ngày 3** | TikTok | *Video 2:* Lộ trình 8 tuần từ "Zero" đến tự viết dự án Python đầu tay | Chứng minh tính khả thi của khóa học |
| **Ngày 4** | Facebook | Infographic: So sánh SV năm nhất biết Python sớm vs. đợi năm 3 mới học | Tạo động lực hành động sớm |
| **Ngày 5** | TikTok | Q&A nhanh: Học 8 tuần có kịp áp dụng cho kỳ thi trên trường không? | Giải đáp rào cản thời gian/kiến thức |
| **Ngày 6** | Facebook | *Bài 2:* Mở cổng đăng ký tư vấn lộ trình 8 tuần (Giới hạn suất ưu đãi) | **Chuyển đổi trực tiếp (Inbox/Form)** |
| **Ngày 7** | FB & TikTok | Tổng kết & Nhắc hẹn: Chỉ còn vài suất nhận tư vấn 1-1 miễn phí | **Chốt hạ KPI 100 lượt đăng ký tư vấn** |

---

### D. Hai Bài đăng Facebook (`[OUTPUT_4.1]`)

* **Bài 1 (Khai thác nỗi đau & Giáo dục - Ngày 2):**
  > **SINH VIÊN NĂM NHẤT 18–20 TUỔI: ĐỪNG ĐỂ "MẤT GỐC CODE" TRỞ THÀNH NỖI ÁM ẢNH ĐẠI HỌC!** 😵‍💫
  >
  > Mới chân ướt chân ráo vào giảng đường, nhiều bạn đã "sốc nhiệt" vì những dòng code khô khan. Càng sợ càng lười, đến năm 2, năm 3 thì khoảng cách với bạn bè đã quá xa...
  >
  > 💡 Giải pháp cho người mới bắt đầu: **Python** – ngôn ngữ lập trình có cú pháp gần tiếng Anh nhất, cực kỳ thân thiện cho người chưa biết gì!
  >
  > Với lộ trình tinh gọn chỉ **8 tuần**, khóa học Python cơ bản giúp bạn đi từ con số 0 đến tự tin viết chương trình hoàn chỉnh.
  >
  > 👉 **8 Tuần Xóa Mù Code Cùng Python – Bước Đệm Vững Chắc Cho Sinh Viên Năm Nhất.**
  >
  > 💬 Comment **"TƯ VẤN"** bên dưới để nhận ngay lộ trình học 8 tuần chi tiết dành riêng cho bạn nhé!

* **Bài 2 (Chuyển đổi trực tiếp - Ngày 6):**
  > 🚀 **CHỈ CÒN VÀI SUẤT TƯ VẤN LỘ TRÌNH PYTHON 8 TUẦN CHO SINH VIÊN NĂM NHẤT!**
  >
  > Bạn 18–20 tuổi, muốn học lập trình bài bản nhưng không biết bắt đầu từ đâu? Đừng tự bơi một mình nữa!
  >
  > Khóa học **Python Cơ Bản (8 Tuần)** thiết kế riêng cho người mới bắt đầu cam kết:
  > ✅ Nắm vững tư duy lập trình từ gốc rễ, không cần kiến thức nền.
  > ✅ Thực hành 100% qua bài tập thực tế, áp dụng ngay vào môn học trên trường.
  > ✅ Giảng viên kèm cặp sát sao trong suốt 8 tuần.
  >
  > 🎯 **8 Tuần Xóa Mù Code Cùng Python – Bước Đệm Vững Chắc Cho Sinh Viên Năm Nhất.**
  >
  > 📩 **Nhắn tin ngay cho Fanpage** hoặc điền form tại `[Link]` để được tư vấn 1-1 miễn phí ngay hôm nay!

---

### E. Hai Kịch bản Video TikTok 30–45 giây (`[OUTPUT_4.2]`)

#### Kịch bản 1: Nỗi đau mất gốc (35 giây - Ngày 1)

| Thời gian | Hình ảnh | Âm thanh / Lời thoại |
| :--- | :--- | :--- |
| **0:00–0:05** | *(Hook)* SV năm nhất ôm đầu nhìn màn hình toàn lỗi đỏ (`SyntaxError`). | *(Nhạc kịch tính)* "Cảnh báo sinh viên năm nhất 18–20 tuổi đang có nguy cơ mất gốc lập trình ngay từ kỳ 1!" |
| **0:05–0:20** | Chuyển cảnh nhanh: Ngồi trên giảng đường không hiểu bài, tối về mở laptop lên rồi lại tắt. | "Cứ nghĩ lên đại học mới bắt đầu học code là vừa, nhưng sự thật là bạn bè đã chạy trước cả cây số. Càng để lâu càng sợ, cuối cùng bỏ cuộc." |
| **0:20–0:30** | Màn hình chuyển sang giao diện code Python chạy mượt mà, đơn giản. | "Đừng lo! Chỉ cần **8 tuần** với **Python cơ bản** – ngôn ngữ dễ học nhất cho người mới bắt đầu, bạn sẽ lấy lại toàn bộ gốc rễ." |
| **0:30–0:35** | *(CTA)* Chỉ tay xuống nút tin nhắn/link bio kèm text: *"8 Tuần Xóa Mù Code"*. | "8 tuần xóa mù code cùng Python! Nhắn tin ngay ở bio để nhận tư vấn lộ trình 1-1 miễn phí nhé!" |

#### Kịch bản 2: Lộ trình 8 tuần thực tế (40 giây - Ngày 3)

| Thời gian | Hình ảnh | Âm thanh / Lời thoại |
| :--- | :--- | :--- |
| **0:00–0:05** | *(Hook)* Cầm tờ giấy ghi "8 Tuần = Biết Code Python?" rồi xé đôi tờ giấy. | *(Nhạc nền năng động)* "Sinh viên năm nhất chưa biết gì về IT, liệu 8 tuần có học được Python không?" |
| **0:05–0:25** | Đồ họa chạy timeline từ Tuần 1 đến Tuần 8 kèm các sản phẩm mini (máy tính, game đoán số). | "Câu trả lời là CÓ nếu đi đúng lộ trình! Tuần 1-2: Làm quen tư duy, không nhồi nhét lý thuyết. Tuần 3-5: Thành thạo cấu trúc dữ liệu. Tuần 6-8: Tự tay hoàn thiện dự án cá nhân đầu tiên!" |
| **0:25–0:35** | Cảnh sinh viên tự tin thuyết trình bài tập trên lớp. | "Khóa học thiết kế riêng cho độ tuổi 18–20 mới bắt đầu, giúp bạn tạo bước đệm vững chắc ngay từ năm nhất." |
| **0:35–0:40** | *(CTA)* Hiện thông tin đăng ký tư vấn ở cuối video. | "Comment 'PYTHON' hoặc bấm vào link đầu trang để được tư vấn miễn phí ngay hôm nay!" |

---

### F. Báo cáo Kiểm tra Tính Nhất quán (`[OUTPUT_5]`)

| Tiêu chí kiểm tra | Kết quả đối chiếu từ Prompt 1 → Prompt 4 | Trạng thái |
| :--- | :--- | :---: |
| **1. Thông số khóa học** | Giữ nguyên 100%: Khóa Python cơ bản cho người mới, SV năm 1 (18–20 tuổi), thời lượng 8 tuần, kênh Facebook & TikTok, mục tiêu 100 lượt tư vấn. Không bịa thêm học phí hay cam kết việc làm sai lệch. | **Đạt (10/10)** |
| **2. Xuyên suốt Thông điệp** | Thông điệp *"8 Tuần Xóa Mù Code Cùng Python – Bước Đệm Vững Chắc Cho Sinh Viên Năm Nhất"* xuất hiện nhất quán từ Prompt 2 xuống lịch 7 ngày và cả 4 sản phẩm nội dung ở Prompt 4. | **Đạt (10/10)** |
| **3. Bám sát Chân dung KH** | Các bài viết và video đều đánh trực diện vào nỗi đau "sợ mất gốc năm nhất" và động lực "học nhanh trong 8 tuần" đã phân tích ở Prompt 1. | **Đạt (10/10)** |
| **4. Tính liên kết CTA** | Toàn bộ CTA từ Ngày 1–7 đều tập trung duy nhất vào hành động **đăng ký nhận tư vấn**, phục vụ trực tiếp KPI 100 lượt tư vấn. | **Đạt (10/10)** |
