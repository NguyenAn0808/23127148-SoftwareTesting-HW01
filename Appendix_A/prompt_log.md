# Appendix A – Prompt Log

## Entry 1 – Requirement 1 AI Impact Analysis

- **Timestamp:** 14:03 06/06/2026
- **AI tool used:** GPT-5.5 (OpenAI)
- **Platform**: Cursor IDE
- **Files attached / used:**
  - `HW01.md`
  - `Report/requirement_1.md`

### Prompt

```text
You are a software testing instructor and QA/QC career analyst helping me complete Requirement 1 of my Software Testing HW01 report.

Context files:
- HW01.md contains the assignment requirements and AI audit rules.
- Report/requirement_1.md contains my completed Requirement 1 job-posting research.
- Requirement 1 asks for 10 QA/QC job postings, and each posting must include 1–2 sentences of AI Impact Analysis.
- I already collected the job links, dated screenshot evidence, job descriptions, required skills, salary information, and whether each job requires AI/LLM/automation-AI skills.
- The missing part is the “Phân tích tác động của AI” section for all 10 jobs.

Task:
Read HW01.md first to understand the grading requirements.
Then read Report/requirement_1.md and replace every “TODO” under “#### Phân tích tác động của AI” with a suitable AI Impact Analysis for that specific job.

Output requirements:
- Write in Vietnamese.
- Each AI Impact Analysis must be 1–2 sentences only.
- Match the tone and style of the existing Requirement 1 report.
- Keep the analysis specific to each job.
- Do not repeat the same generic wording across all jobs.
- Do not invent new job data, salary, companies, links, screenshots, dates, or requirements.
- Base the analysis only on the existing job description and required skills in Report/requirement_1.md.
- Preserve the current Markdown structure.
- Do not edit any section except the “TODO” lines under “#### Phân tích tác động của AI”.
- Do not create new files.

Analysis rules:
- For jobs marked “Yêu cầu kỹ năng AI/LLM/automation-AI: YES”, explain how AI directly changes the QA/QC role and what skills become more important, such as AI testing, LLM evaluation, automation, data-driven testing, prompt-based validation, or AI-assisted defect detection.
- For jobs marked “Yêu cầu kỹ năng AI/LLM/automation-AI: NO”, explain AI as a supporting tool rather than a required core skill.
- Do not claim AI fully replaces the QA/QC role unless the job description clearly supports that.
- Make the human responsibility clear, especially judgment, domain knowledge, defect triage, communication, compliance, quality audits, and final quality decisions.
- Mention practical QA/QC work when relevant, such as manual testing, automation testing, test case design, quality audits, defect detection, API testing, regression testing, risk-based testing, or process improvement.

Before editing:
Show me the proposed AI Impact Analysis text for Job 1 through Job 10.

After showing the proposed text:
Apply the edits directly to Report/requirement_1.md.

Done when:
- All 10 TODO placeholders under “Phân tích tác động của AI” are replaced.
- Each job has a 1–2 sentence AI Impact Analysis.
- No unrelated content is changed.

@Report/requirement_1.md @HW01.md
```

### AI output

```text
Proposed AI Impact Analysis text:

Job 1: AI không phải là kỹ năng cốt lõi trong vị trí này, nhưng có thể hỗ trợ QA Specialist tổng hợp dữ liệu kiểm toán, phát hiện xu hướng lỗi và chuẩn hóa báo cáo chất lượng trong sản xuất nội thất. Tuy vậy, trách nhiệm chính vẫn thuộc về con người vì việc đánh giá GMP, kiểm tra vật liệu/sản phẩm thực tế và quyết định cải tiến quy trình cần kinh nghiệm ngành, quan sát trực tiếp và phán đoán chuyên môn.

Job 2: Dù công ty hoạt động trong lĩnh vực Cognitive AI, vị trí Junior QA/QC Engineer này vẫn tập trung vào manual testing, API testing, test case design và defect tracking, nên AI chủ yếu đóng vai trò công cụ hỗ trợ tạo test cases, phân tích log hoặc gợi ý phạm vi regression. Người QA vẫn cần tự xác nhận hành vi web/mobile, đánh giá defect theo ngữ cảnh sản phẩm và phối hợp với developer để xử lý lỗi đúng mức ưu tiên.

Job 3: Với vai trò Junior QA Engineer kết hợp manual và automation, AI có thể hỗ trợ viết test scenarios từ business requirements, tạo dữ liệu kiểm thử và phân tích lỗi trong Jira hoặc automation scripts. Tuy nhiên, công việc vẫn cần QA tự hiểu nghiệp vụ, xác định coverage cho functional/regression/UAT và kiểm soát chất lượng script Katalon/TestComplete thay vì phụ thuộc hoàn toàn vào gợi ý tự động.

Job 4: AI có thể hỗ trợ Quality Control Engineer trong việc gợi ý corner cases, phân tích defect metrics như defect density/open defect count và hỗ trợ review yêu cầu về testability. Tuy nhiên, vị trí này không yêu cầu AI trực tiếp, nên năng lực quan trọng vẫn là thiết kế exploratory/automated tests, đánh giá risk, giao tiếp issue sớm và đưa ra corrective actions dựa trên hiểu biết domain của team.

Job 5: AI tác động trực tiếp đến vai trò này vì QC phải kiểm thử một AI-powered sales agent, bao gồm conversational accuracy, data consolidation, conflict logic, source attribution và yêu cầu EU AI Act compliance. Vì vậy kỹ năng quan trọng không chỉ là manual/automation testing mà còn là đánh giá đầu ra AI, thiết kế test data cho nhiều nguồn dữ liệu, kiểm tra audit log và đảm bảo human oversight trước khi chấp nhận chất lượng.

Job 6: Ở vị trí Quality Engineer của ZaloPay, AI được nêu như công cụ cải thiện hiệu quả công việc, đặc biệt trong việc gợi ý test cases, tối ưu automation scripts, phân tích kết quả test và nhận diện khu vực cần regression. Tuy nhiên, trong sản phẩm thanh toán số, QA vẫn phải chịu trách nhiệm cuối cùng về coverage, traceability, defect triage và xác nhận deliverables đáp ứng functional/design requirements.

Job 7: AI là một phần thiết yếu của vai trò Senior QA Engineer này vì công việc yêu cầu dùng GPT/Claude, AI self-healing frameworks, visual AI testing và Postbot để mở rộng test generation, failure analysis, API testing và visual regression. Tác động chính là QA chuyển từ chỉ viết và chạy test sang thiết kế chiến lược kiểm thử có AI hỗ trợ, đồng thời vẫn phải kiểm soát risk-based testing, quality metrics và quyết định chất lượng cuối cùng.

Job 8: Với vai trò Senior Automation Test Engineer/Test Lead, AI không thay thế nền tảng automation nhưng nâng kỳ vọng về năng suất thông qua Copilot, Cursor, Claude Code, prompting workflows và agentic workflows trong toàn bộ SDLC. Người QA lead vẫn cần năng lực phân rã yêu cầu, thiết kế test strategy, kiểm soát end-to-end automated coverage và đánh giá khi nào kết quả do AI hỗ trợ là đáng tin cậy.

Job 9: AI tác động trực tiếp đến SDET này vì job yêu cầu automation-first và AI-driven testing cho OESIS, bao gồm intelligent test generation, self-healing automation, smart test selection và failure analysis. Do sản phẩm liên quan đến cybersecurity và integration trên nhiều môi trường, kỹ năng AI phải đi kèm với Python/Robot Framework, API/system testing và khả năng con người phân tích lỗi, tương thích và rủi ro bảo mật.

Job 10: AI là một hướng mở rộng rõ ràng trong vị trí QC Automation Engineer vì ứng viên tham gia xây dựng framework cho AI Automation Testing và mở rộng automation coverage cho các bài toán kiểm thử liên quan đến AI. Tuy nhiên, nền tảng quan trọng vẫn là Python, Selenium/Playwright, API/database testing và khả năng manual testing để hiểu business flow trước khi tự động hóa hoặc áp dụng AI vào coverage.

Applied edits directly to Report/requirement_1.md.

Done.

- Read HW01.md and confirmed Requirement 1 needs 10 job postings with 1–2 sentence AI Impact Analysis.
- Read Report/requirement_1.md.
- Replaced all 10 TODO placeholders under #### Phân tích tác động của AI.
- Preserved the Markdown structure.
- Did not edit unrelated sections.
- Verified there are no remaining TODO matches in Report/requirement_1.md.
- Lint check reported no errors.
```
