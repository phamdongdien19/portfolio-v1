# Case Study 2: Robot QC & AI – Cuộc cách mạng kiểm soát chất lượng

**Dự án:** Hệ thống kiểm soát chất lượng tự động chuyên dụng cho Nghiên cứu thị trường
**Vai trò:** Founder & Lead Developer (Internal Tool)
**Thời gian:** 2022 – Hiện tại

---

## 🚀 Tóm tắt (The STAR Method)

### S – Situation (Bối cảnh)
Trong nghiên cứu định lượng (Quantitative Research), chất lượng mẫu là yếu tố sống còn. Tuy nhiên, việc kiểm tra thủ công (Manual QC) hàng ngàn bảng hỏi mỗi ngày cực kỳ tốn thời gian và dễ bỏ sót các lỗi tinh vi như: "straight-lining" (trả lời cùng một đáp án cho tất cả câu hỏi) hoặc logic mâu thuẫn giữa câu hỏi đầu và cuối.

### T – Task (Nhiệm vụ)
Thiết kế và xây dựng một "Robot QC" có khả năng:
1. Tự động quét 100% dữ liệu khảo sát trong thời gian thực.
2. Phát hiện các mẫu gian lận hoặc kém chất lượng dựa trên thuật toán và hành vi.
3. Giảm gánh nặng cho đội ngũ QC thủ công để họ tập trung vào các lỗi phức tạp hơn.

### A – Action (Hành động)
- **Xây dựng thuật toán phát hiện (Detection Algorithms):** Tôi đã thiết kế các tiêu chuẩn kiểm tra như:
  - **Time-check:** Loại bỏ các bản ghi hoàn thành quá nhanh so với trung bình.
  - **Pattern-check:** Phát hiện các mẫu trả lời lặp lại (ví dụ 1,2,1,2,1,2...).
  - **Logic-cross-check:** Đối chiếu các câu hỏi bổ trợ để phát hiện mâu thuẫn.
- **Hệ thống cảnh báo tự động:** Kết nối Robot QC với Zalo/Viber Bot để thông báo ngay lập tức cho giám sát viên khi có dấu hiệu field bị "tấn công" bởi spam.
- **Tích hợp AI:** Sử dụng Natural Language Processing (NLP) để quét các câu trả lời văn bản, loại bỏ các câu vô nghĩa như "abc", "good", "không có".

### R – Result (Kết quả)
- **Tốc độ:** Thời gian làm sạch dữ liệu (Data Cleaning) giảm từ **3 ngày xuống còn 30 phút** sau khi kết thúc field.
- **Độ chính xác:** Loại bỏ được **15-20%** lượng mẫu lỗi mà trước đây QC thủ công thường bỏ sót.
- **Uy tín:** Giúp IFM Research đạt điểm tin cậy tuyệt đối trong các đợt Auditing từ các khách hàng khó tính nhất (Maturity/Global Clients).

---

## 🛠 Công cụ đã sử dụng
- **Backend:** Node.js, Firebase Functions.
- **AI/ML:** OpenAI GPT-4 API cho Sentiment Analysis & Open-end Coding.
- **Communication:** Zalo/Telegram Bot API.

> [!IMPORTANT]
> **Giá trị then chốt:** "Chất lượng dữ liệu không phải là một công đoạn sau cùng; nó phải là một phần của mã nguồn (Code) ngay từ khi bắt đầu."
