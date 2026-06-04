# APPENDIX A: PROMPT LOG
**Student Name:** [Your Name]  
**Student ID (MSSV):** [Your Student ID]  
**Exercise ID:** HW01-AI  

*Guideline:* Record all prompts you sent to any AI tool (e.g., ChatGPT, Claude, Gemini, Copilot, Cursor, etc.) during this assignment. Every prompt must include a timestamp and the tool's name.

---

## 1. Prompt Log for Requirement 1 (QA/QC Job Market 2026+)

### Prompt 1.1: Suggesting job search keywords for AI-integrated QA/QC roles
* **Timestamp:** 10:15 02/06/2026
* **AI Tool Name:** Claude Sonnet 4.6
* **Prompt Content:**
  ```text
  I need to find 10 recent QA/QC job postings in Vietnam for my homework, and at least 3 of them must explicitly require AI/LLM/Automation-AI skills. Can you recommend popular job search keywords and specific job titles I should look for on ITviec, Glints, or VietnamWorks to easily find these AI-related testing roles?
  ```
* **Purpose:** Researching job search keywords and strategies to find AI-related testing positions in the Vietnamese market.

---

## 2. Prompt Log for Requirement 2 (20 Software Defects 2022–2026)

### Prompt 2.1: Research 20 software defects with AI-error verification
* **Timestamp:** 14:30 02/06/2026
* **AI Tool Name:** Claude Sonnet 4.6
* **Prompt Content:**
  ```text
  Để thoả mãn hoàn toàn yêu cầu của đề bài, với mỗi defect (trong tổng số 20 defects), bạn cần trình bày một block thông tin chuẩn chỉnh bao gồm 7 mục sau đây:
  1. Tên Defect & Năm xảy ra:
  Phải nằm trong giai đoạn 2022-2026.
  Lưu ý tổng thể: Đảm bảo trong 20 defect này có ít nhất 5 lỗi liên quan trực tiếp đến AI/LLM (ảo giác, prompt injection, thiên kiến).
  2. Source Link:
  Đường dẫn URL trích nguồn bài báo hoặc tài liệu kỹ thuật gốc.
  3. Description (Mô tả):
  Trình bày ngắn gọn nguyên nhân gây ra lỗi và điều gì đã xảy ra về mặt kỹ thuật.
  4. Severity (Mức độ nghiêm trọng):
  Xác định mức độ (Ví dụ: Low, Medium, High, Critical).
  Điểm cộng nâng cấp: Nên kèm theo một mệnh đề giải thích ngắn gọn tại sao lại xếp mức độ đó (ví dụ: Critical vì làm hệ thống sập toàn cầu, High vì rò rỉ dữ liệu nhạy cảm...).
  5. Consequences (Hậu quả):
  Thiệt hại thực tế do lỗi gây ra (ví dụ: thiệt hại tài chính, lộ dữ liệu, thời gian hệ thống ngừng hoạt động, kiện tụng).
  6. Solution (Giải pháp):
  Cách lỗi này được khắc phục.
  Điểm cộng nâng cấp cho dân Kỹ thuật Phần mềm: Đừng chỉ ghi cách sửa code đơn thuần. Hãy bổ sung thêm giải pháp từ góc độ kiểm thử (Ví dụ: "Đã bổ sung thêm test case cho Boundary Value", "Tích hợp thêm Penetration Testing vào quy trình CI/CD").
  7. AI Bias / Hallucination Instance (Trường hợp AI bị thiên kiến/ảo giác):
  Yêu cầu này bắt buộc phải có cho toàn bộ 20 defect. Mục này cần phân tách rõ:
  - AI Tool Used: Tên công cụ (ChatGPT, Claude, Gemini...).
  - Prompt Given: Câu lệnh chính xác bạn đã dùng để hỏi AI.
  - AI Explanation Error: Chỉ ra chi tiết điểm AI đã bịa đặt thông tin, nói sai kỹ thuật hoặc thể hiện thiên kiến.
  - Evidence (Đặc biệt quan trọng): Phải chèn ảnh chụp màn hình thu nhỏ (Screenshot) hoặc link Share Conversation để chứng minh AI thực sự tạo ra lỗi đó, tránh bị đánh giá là tự bịa ra để đối phó.
  ```
* **Purpose:** Generating technical details and verifying AI errors for the 20 software defects.

---

## 3. Prompt Log for Requirement 3 (Test Cases for Physical Product)

### Prompt 3.1: Generate 15 test cases for a stand fan
* **Timestamp:** 22:43 03/06/2026
* **AI Tool Name:** Claude Sonnet 4.6
* **Prompt Content:**
  ```text
  I am conducting a software/hardware testing assignment on a physical household device: the Senko B1612 Stand Fan. Please design a suite of 15 standard test cases for this device. Format the test cases as a markdown table with the following columns:

  Test ID (from TC-01 to TC-15)
  Objective
  Input
  Steps
  Expected Result
  Actual Result (Leave this blank or put "[Pending Execution]")
  Verdict (Leave this blank or put "[Pending]") Please focus on basic operations and standard user interactions such as power plugging, operation of the speed control knob (positions 0, 1, 2, and 3), oscillation control, fan neck angle adjustment, and normal fan blade rotation.
  ```
* **Purpose:** Generating baseline test cases for the physical device.

---

## 4. Prompt Log for QA/QC Role Mindmap

### Prompt 4.1: Create mindmap of QA/QC roles
* **Timestamp:** 11:33 04/06/2026
* **AI Tool Name:** Claude Sonnet 4.6
* **Prompt Content:**
  ```text
  Create a mindmap of QA/QC roles and their responsibilities in the software testing process based on ISTQB standards in Markdown format and PNG.
  ```
* **Purpose:** Generating the initial mindmap outline to identify mistakes.
