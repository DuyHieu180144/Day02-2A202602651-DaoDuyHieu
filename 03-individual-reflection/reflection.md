# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đào Duy 
- Mã học viên: 2A202602651
- Nhóm: X Zone C
- Candidate problem nhóm chọn: Chuẩn hóa commit message và tối ưu quy trình merge code nhiều lập trình viên khi push lên các nhánh feature và production trong dự án phát triển phần mềm.

---
## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tìm 5 vấn đề thực tế của sinh viên mới tốt nghiệp (CV, format báo cáo, lọc job Fresher...) | Đóng góp 3 candidate problems vào pool của nhóm |
| Pitch Problem Card | Pitch 3 bài toán: Tối ưu CV theo JD, Format báo cáo/đồ án, Lọc tin tuyển dụng Fresher | Giúp nhóm hình dung nỗi đau thực tế của sinh viên, lọt 2 bài vào shortlist 12 candidates |
| Challenge bài của bạn khác | Challenge bài FAQ Fanpage (#1) về hiệu quả thực sự của Chatbot Rule hiện tại | Giúp nhóm nhận ra rủi ro AI trả lời sai giá/sản phẩm, hạ điểm bài FAQ |
| Gom trùng / cluster | Gom các bài toán xử lý CV và tài liệu (#6, #8, #10) vào Cluster B | Phân loại rõ nhóm bài toán xử lý tài liệu bán cấu trúc có tính cá nhân hóa cao |
| Chọn candidate problem | Đánh giá và chấm điểm Scorecard (Vote cho bài Commit/Merge code #3 đạt 35/35) | Thống nhất 100% nhóm chọn bài toán Git/Merge code |
| Validation / research | Phân tích các công cụ chuẩn hóa Git/PR hiện có (GitHub Copilot for PRs, Commitizen) | Chỉ ra khoảng trống về chi phí, rủi ro bảo mật mã nguồn và nguy cơ vendor lock-in |
| Workflow nhóm | Góp ý xác định ranh giới (boundary) ở bước AI draft PR/Commit và Dev review | Đảm bảo AI không tự động push/merge code mà bắt buộc phải qua con người duyệt |
| Problem Statement | Tham gia viết và làm nét phần Impact cùng thành phần Actor/Bottleneck | Làm rõ metric giảm thời gian xử lý PR từ 30 phút xuống dưới 15 phút |
| Rule / Workflow / Agent | So sánh ranh giới giữa Rule (Commitlint), AI (Draft commit/PR) và Con người | Xác định Rule gác cổng, AI hỗ trợ sinh text, Human quyết định merge |
| Decision | Phân tích phương án tự xây dựng workflow/agent nội bộ thay vì dùng SaaS đóng kín | Giúp nhóm chốt quyết định "Go" với phương án tự phát triển để bảo mật dữ liệu |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đóng góp phần research đối thủ (GitHub Copilot for PRs) để chỉ ra nguy cơ rò rỉ mã nguồn và phụ thuộc nhà cung cấp (vendor lock-in), từ đó làm rõ lý do nhóm cần tự xây dựng workflow/agent nội bộ.
```

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các lăng kính quan sát vấn đề của sinh viên mới tốt nghiệp | Mở rộng nhiều góc nhìn và bối cảnh khác nhau | Đưa ra các vấn đề chung chung, thiếu số liệu chứng minh | Tự bổ sung số liệu thời gian thực tế (20–30 phút/lần nộp CV) |
| Problem Card | Draft current và future workflow cho 3 bài toán cá nhân | Gợi ý chuỗi các bước thao tác logic và mạch lạc | Lạc quan quá mức về thời gian AI xử lý ở future workflow | Sửa lại thời gian human review thực tế mất 4–5 phút thay vì 1 phút |
| Workflow | Vẽ sơ đồ các bước trong quy trình Git tích hợp | Liệt kê đầy đủ các câu lệnh Git cơ bản | Bỏ qua bước interactive rebase dọn commit rác | Tự chèn bước rebase thủ công — điểm nghẽn chính của workflow cũ |
| Research | Tìm các công cụ chuẩn hóa Git và hỗ trợ PR hiện có | Tìm nhanh tên các công cụ phổ biến như Commitizen, Copilot | Bịa link trích dẫn và mô tả sai một số tính năng nâng cao | Tự verify lại link official (conventionalcommits.org, github.com) và lọc thông tin chuẩn |
| Problem Statement | Tinh chỉnh văn phong câu chữ cho Problem Statement | Sửa câu từ mượt mà, đúng định dạng chuyên nghiệp | Làm trôi mất các con số metric và số liệu cụ thể | Tự chèn lại các mốc thời gian 15–20 phút và target giảm 50% thời gian |
| Rule / Workflow / Agent | So sánh ưu/nhược điểm giữa Rule, Workflow và Agent | Phân tích logic, chỉ ra điểm mạnh của từng cấp độ | Thiên vị việc dùng AI Agent cho tất cả các bước | Siết chặt lại boundary: Rule gác cổng ở local, AI chỉ đóng vai trò draft text |
| Decision | Không dùng | Không dùng | Không dùng | Tự phân tích dựa trên năng lực thực tế của lab và mục tiêu bảo mật của nhóm |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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
Khi nghe top 3 bài toán của các thành viên khác, đặc biệt là bài toán chuẩn hóa commit và merge code của bạn Đăng, tôi nhận ra các bài toán cá nhân của mình (tối ưu CV, lọc job) còn mang tính cá nhân hóa cao và thiếu tính nhất quán để đo lường. Bài toán Git chạm đúng nỗi đau chung của cả 6 lập trình viên trong nhóm khi ai cũng từng trực tiếp chịu tổn thất từ việc xung đột mã nguồn sát giờ nộp bài. Ban đầu, nhóm cũng rơi vào cái bẫy "solution-first" khi hào hứng muốn dựng ngay một AI Agent tự động sửa conflict code. Tuy nhiên, sau khi thảo luận, chúng tôi nhận ra điều khó nhất khi viết Problem Statement không phải là đo metric mà chính là vạch rõ ranh giới (boundary) giữa Rule, AI và Con người. AI không được phép tự ý thay đổi logic code nghiệp vụ khi xảy ra conflict; ranh giới an toàn bắt buộc AI chỉ giải thích nguyên nhân, còn lập trình viên phải tự tay sửa và quyết định merge. Dấu tay rõ nhất của tôi trong artifact cuối nằm ở phần Research đối thủ và đánh giá nguy cơ rò rỉ mã nguồn (IP protection). Tôi đã chỉ ra rằng các công cụ SaaS như GitHub Copilot for PRs tiềm ẩn rủi ro lộ tài sản trí tuệ và gây vendor lock-in, giúp nhóm củng cố lý do phải tự xây dựng workflow nội bộ hỗ trợ Local LLMs. Bài học lớn nhất tôi rút ra là một vấn đề tốt phải có workflow rành mạch và ranh giới can thiệp minh bạch trước khi nghĩ đến việc đưa AI vào. Nếu làm lại, tôi sẽ challenge nhóm mạnh mẽ hơn ngay từ Phase 3 để loại bỏ sớm các ý tưởng trùng lặp hoặc thiếu bằng chứng thực tế.


```

---


## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [X] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [X] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [X] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [X] [15đ] Nhóm có workflow trước/sau
- [X] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [X] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [X] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [X] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [X] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

