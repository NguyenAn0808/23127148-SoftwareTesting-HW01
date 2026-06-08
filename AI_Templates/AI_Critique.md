# AI Critique

- **Student ID:** 23127148
- **Assignment:** HW01 – QA/QC Jobs · 20 Defects · Test a Physical Product
- **Course:** Software Testing
- **Date:** 08/06/2026

AI hữu ích trong HW01 vì có thể nhanh chóng tạo first drafts cho job-market analysis, software defect summaries, QA/QC mindmap content và physical-product test ideas. Tuy nhiên, điểm yếu chính là AI thường đưa ra câu trả lời trông có vẻ đầy đủ nhưng vẫn thiếu các ràng buộc quan trọng. Ở Requirement 1, AI có thể mô tả tác động của AI lên QA/QC jobs, nhưng nội dung vẫn phải được kiểm tra lại với từng job posting thật để tránh phóng đại việc AI thay thế con người hoặc tự thêm yêu cầu không có trong tin tuyển dụng. Ở Requirement 2, AI đưa ra các vulnerability examples hữu ích, nhưng một số phần giải thích còn quá chung, thiếu technical conditions, affected scope chính xác hoặc evidence như CVE details và real-world impact. Với QA/QC mindmap, AI đã nhầm lẫn giữa test types và test design techniques, cho thấy AI có thể diễn đạt tự tin dù phân loại sai ISTQB concepts.

Hạn chế rõ nhất xuất hiện ở Requirement 3. AI đề xuất các normal kettle test cases, nhưng bỏ sót các edge cases thực tế như nhấc ấm khỏi đế khi đang đun, đặt ấm hơi lệch trên đế cấp điện và bật đun lại khi nước vẫn còn nóng. AI thất bại ở đây vì suy luận theo generic happy-path product checklist thay vì quan sát cách người dùng thật có thể thao tác với một household device thật.

Nguyên tắc tôi rút ra là AI nên được xem như một junior assistant: hữu ích cho tốc độ và cấu trúc, nhưng không chịu trách nhiệm cho tính đúng đắn cuối cùng. Sinh viên phải verify facts, bổ sung real evidence, sửa course-concept mistakes và đưa ra final quality decision.
