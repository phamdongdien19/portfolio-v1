# Case Study 1: Dự án CCI – Chuyển đổi số trong Nghiên cứu Công chúng

**Dự án:** CCI (Consumer Confidence Index) & Public Research
**Vai trò:** IT Support & Data Operations Specialist
**Thời gian:** 2021 – Hiện tại

---

## 🚀 Tóm tắt (The STAR Method)

### S – Situation (Bối cảnh)
Tại IFM Research, dự án CCI yêu cầu thu thập và xử lý dữ liệu từ hàng ngàn mẫu khảo sát mỗi tháng. Quy trình cũ phụ thuộc nhiều vào thao tác thủ công: từ việc gửi link khảo sát, theo dõi tiến độ đến kiểm soát chất lượng (QC). Điều này dẫn đến nguy cơ sai sót cao, chi phí vận hành (CPI) lớn và tốc độ báo cáo chậm.

### T – Task (Nhiệm vụ)
Nhiệm vụ của tôi là tối ưu hóa toàn bộ luồng dữ liệu của dự án CCI. Mục tiêu cụ thể là:
1. Giảm thời gian chết giữa các khâu từ 48 giờ xuống dưới 4 giờ.
2. Tự động hóa quy trình gửi tin nhắn/email mời khảo sát.
3. Xây dựng hệ thống cảnh báo sớm cho các mẫu dữ liệu không đạt chuẩn.

### A – Action (Hành động)
Tôi đã chủ động triển khai các giải pháp công nghệ:
- **Tự động hóa luồng (Workflow Automation):** Sử dụng các công cụ (như Alchemer API + Custom Scripts) để tự động hóa việc phân phối mẫu dựa trên nhân khẩu học.
- **Robot QC:** Xây dựng script kiểm tra logic dữ liệu ngay trong quá trình field, phát hiện ngay lập tức các hành vi khảo sát bất thường (như trả lời quá nhanh - speeders, hoặc trả lời trùng lặp).
- **Dashboard trực quan:** Kết nối dữ liệu thời gian thực vào bảng điều khiển để Manager có thể theo dõi biến động CPI hàng giờ.

### R – Result (Kết quả)
- **Hiệu quả chi phí:** Giảm **20% chi phí thu thập mẫu (CPI)** nhờ chiến lược phân bổ nguồn mẫu thông minh.
- **Tiêu chuẩn chất lượng:** Nâng tỷ lệ dữ liệu sạch (Clean Data) từ 85% lên **98%** ngay trong lần xử lý đầu tiên.
- **Quy mô:** Hệ thống này sau đó đã được áp dụng thành công cho hơn **400 dự án** khác nhau tại IFM, giúp đội ngũ vận hành xử lý khối lượng công việc gấp 3 lần mà không cần thêm nhân sự.

---

## 🛠 Công cụ đã sử dụng
- **Data Collection:** Alchemer, SurveyMonkey.
- **Programming:** Javascript (Node.js), Lua (cho Logic Alchemer).
- **Automation:** Custom API Integrations, Robot QC Scripts.
- **AI Integration:** ChatGPT API để phân loại các câu hỏi mở (Open-ended questions).

> [!NOTE]
> **Giá trị then chốt:** "Tôi không chỉ thu thập dữ liệu; tôi xây dựng một nhà máy sản xuất insight tự động, nơi sai sót con người bị triệt tiêu ngay từ khâu đầu vào."
