# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Trung Kiên
- Mã học viên: 2A202602748
- Nhóm: Recall
- Candidate problem nhóm chọn: Lưu quá nhiều nội dung (bài viết, video, tài liệu, link) để đọc sau nhưng khó xác định ưu tiên và thường quên quay lại đọc.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự rà soát quy trình quản lý thông tin hằng tuần, đưa ra 10 vấn đề thuộc 4 lăng kính với số đo cụ thể | Hoàn thành 10 problems, đóng góp các problem card về quản lý tri thức và lọc thông tin vào danh sách nhóm |
| Pitch Problem Card | Pitch chi tiết vấn đề Bookmark/Save link tràn lan nhưng không bao giờ đọc lại (mất 45 phút/tuần mò tìm link) | Nhóm nhận diện rõ pain point "Save & Forget" phổ biến ở sinh viên/người đi làm và tiềm năng của việc dùng AI tóm tắt |
| Challenge bài của bạn khác | Phản biện các bài toán tự động tổng hợp quá rộng, đặt câu hỏi về rủi ro AI tóm tắt sai ý chính hoặc không khớp nhu cầu | Giúp nhóm nhìn ra giới hạn của AI ở các bài toán thiếu boundary và cần cơ chế lọc đúng nhu cầu thật |
| Gom trùng / cluster | Đóng góp ý kiến phân loại 12 candidate problems thành 4 cụm bài toán (Lặp lại, Tốn thời gian, Phân tích dữ liệu, Quản lý tri thức) | Nhóm nhanh chóng thu hẹp phạm vi và nhận diện được pattern "Information Overload" xuất hiện ở nhiều thành viên |
| Chọn candidate problem | Đánh giá và chấm điểm (Score) dựa trên tiêu chí actor rõ, pain point phổ biến và tính khả thi khi làm trong lab | Nhóm đồng thuận 100% chọn bài toán "Save & Forget / Khó ưu tiên nội dung đọc sau" với số điểm cao nhất |
| Validation / research | Thực hiện phỏng vấn (interview) 3 bạn sinh viên/intern và khảo sát thói quen bookmark/lưu link thực tế | Thu thập được quote bằng chứng thật (lưu 20-30 link/tuần nhưng chỉ đọc lại < 10%) và xác nhận pain point có thật |
| Workflow nhóm | Trực tiếp bóc tách 5 bước của workflow HIỆN TẠI (Lưu -> Quên -> Mất thời gian lục tìm) và 4 bước workflow TƯƠNG LAI | Nhóm xác định đúng điểm nghẽn (Bước phân loại & đánh giá mức độ ưu tiên) và đo lường metric giảm thời gian lọc bài từ 45' xuống 10' |
| Problem Statement | Đề xuất bổ sung boundary cụ thể (chỉ xử lý bài viết dạng text/link báo chí < 3000 từ, không xử lý video/file tài liệu bảo mật) | Giúp Problem Statement v1 đạt điểm tối đa về tính cụ thể, không bị mơ hồ hay bao la |
| Rule / Workflow / Agent | Nghiên cứu so sánh 4 cấp độ (No AI / Rule / Workflow / Agent) dựa trên rủi ro kỹ thuật | Giúp nhóm chốt cấp độ Workflow (gọi API LLM tóm tắt + gán Tag ưu tiên) thay vì đòi làm Agent tự động nhắc nhở phức tạp |
| Decision | Phân tích bài toán rủi ro hallucination khi tóm tắt và giới hạn dung lượng đầu vào | Nhóm tự tin đưa ra quyết định GO với kế hoạch làm thử nghiệm (lab test) bài toán |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text

Dấu tay rõ nhất của tôi nằm ở phần Quick Validation (phỏng vấn 3 người dùng để xác nhận tỉ lệ lưu 20-30 link nhưng chỉ đọc lại <10%) và việc xác định ranh giới hệ thống (Boundary - chỉ nhận link bài viết text < 3000 từ) để giúp nhóm làm giải pháp Workflow thực tế.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý 10 ý tưởng problem theo 4 lăng kính | Mở rộng góc nhìn về các tác vụ tốn thời gian ở nhiều vị trí công việc | Gợi ý các ý tưởng chung chung như "tự động đọc và ghi nhớ toàn bộ internet" | Bổ sung các chỉ số đo lường cụ thể (số link lưu, số phút lục tìm) từ trải nghiệm thực tế |
| Problem Card | Chuyển đổi mô tả thô thành cấu trúc Problem Card chuẩn | Chuẩn hóa nhanh câu từ theo đúng template 9 mục | AI tự bịa ra metric thời gian không thực tế (đọc bài trong 1 giây) | Tự đo lại thời gian thực tế lọc và đọc tóm tắt (giảm từ 45 phút xuống 10 phút/tuần) |
| Workflow | Gợi ý các bước phân loại bài viết tự động | Phác thảo được khung các bước tóm tắt và gán tag chủ đề | Bỏ qua bước xác định mức độ ưu tiên theo nhu cầu thực tế của người dùng | Bổ sung thêm bước đánh giá Priority Score (Độ ưu tiên: Gấp / Cần cho dự án / Đọc giải trí) |
| Research | Tìm kiếm các rủi ro kỹ thuật khi tóm tắt nội dung web/link bằng LLM | Liệt kê nhanh các vấn đề về paywall, bài viết quá dài, định dạng trang web phức tạp | Đánh giá quá cao khả năng tự truy cập mọi URL của mô hình AI | Đề xuất giải pháp bóc tách text bài viết (web scraping/readability) trước khi đưa vào LLM tóm tắt |
| Problem Statement | Hỗ trợ diễn đạt câu lệnh Problem Statement sắc nét hơn | Giúp câu văn mạch lạc, đúng ngữ pháp và giàu tính thuyết phục | AI đưa ra metric quá lạc quan (tự động giúp đọc 100% bài viết) | Điều chỉnh metric thực tế: giúp người dùng chọn đúng 3-5 bài quan trọng nhất/tuần để đọc |
| Rule / Workflow / Agent | So sánh ưu nhược điểm của 4 phương pháp giải quyết | Cung cấp cái nhìn tổng quan về đặc tính kỹ thuật của từng cấp độ giải pháp | Khuyên nên làm Agent tự động lên lịch nhắc đọc bài hằng ngày | Nhấn mạnh với nhóm chỉ nên dừng ở cấp độ Workflow tóm tắt & xếp hạng ưu tiên để người dùng tự chủ |
| Decision | Tổng hợp các lý do Go / No-Go thành đoạn văn chốt | Dàn trang và format văn bản đẹp mắt, chuẩn Markdown | Lý do Go bị thiên về màu hồng, thiếu tính cảnh báo rủi ro về bản quyền bài viết | Bổ sung điều kiện Go có ràng buộc: Hệ thống chỉ lưu bản tóm tắt và link gốc, không lưu lại toàn bộ văn bản |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Trong quá trình thảo luận nhóm, tôi đã học được rất nhiều khi lắng nghe top 3 problems của các bạn khác, đặc biệt là sự tương đồng ở thói quen "Save & Forget" - lưu hàng loạt tài liệu nhưng không bao giờ quay lại đọc. Ban đầu, nhóm chúng tôi cũng từng rơi vào bẫy "solution-first" khi một số thành viên đề xuất xây dựng hẳn một Autonomous Agent tự động đọc bài, lên lịch thông báo nhắc nhở và tự động tóm tắt thành file âm thanh để nghe. Tuy nhiên, với vai trò là một Researcher, tôi đã đứng ra phản biện và chỉ ra rằng nếu chưa làm rõ nguyên nhân cốt lõi (Information Overload + Thiếu ưu tiên), việc bắn thông báo dồn dập chỉ làm người dùng thêm áp lực và gỡ ứng dụng. Bản thân tôi cũng đã thay đổi góc nhìn sau khi bị nhóm challenge về khả năng AI đọc được các link web có tường lửa (paywall) hoặc chứa quá nhiều quảng cáo; điều này thúc đẩy tôi tiến hành phỏng vấn sâu 3 người dùng thật để xác định xem họ lưu nguồn bài viết từ đâu. Đóng góp lớn nhất của tôi vào artifact cuối chính là phần Quick Validation (chỉ ra thực trạng lưu 20-30 link/tuần nhưng chỉ đọc <10%) và khoanh vùng Boundary: chỉ nhận link bài viết công khai dạng text dưới 3000 từ. Điều khó nhất khi viết Problem Statement chính là định nghĩa metric đo lường sự thành công của một thói quen đọc. Nếu được làm lại, tôi sẽ challenge nhóm mạnh mẽ hơn ngay từ đầu ở khâu thu thập minh chứng thật (evidence) của từng candidate problem để tiết kiệm thời gian hội tụ nhóm.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

