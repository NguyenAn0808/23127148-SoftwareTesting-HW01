# G9.1 – Mindmap vai trò QA/QC theo ISTQB và quy trình kiểm thử

## 1. Mục tiêu

Tài liệu này hỗ trợ phần G9.1 Understand bằng cách sử dụng AI để tạo một mindmap ban đầu về vai trò QA/QC dựa trên khái niệm ISTQB và quy trình kiểm thử phần mềm. Mindmap này sẽ được sinh viên rà soát sau đó để tự xác định 3 lỗi hoặc điểm chưa đầy đủ.

## 2. AI-generated mindmap

- QA/QC Role
  - QA vs QC responsibilities
    - QA (Quality Assurance)
      - Tập trung vào phòng ngừa lỗi thông qua quy trình, tiêu chuẩn và cải tiến liên tục
      - Tham gia xây dựng test strategy, test plan, quy trình review và tiêu chí chất lượng
      - Đánh giá chất lượng requirement, quy trình phát triển và mức độ tuân thủ SDLC/STLC
      - Hỗ trợ team áp dụng best practices như Agile testing, risk-based testing và shift-left testing
    - QC (Quality Control)
      - Tập trung vào phát hiện lỗi trong sản phẩm thông qua hoạt động kiểm thử cụ thể
      - Thiết kế, thực thi và cập nhật test cases/test scenarios
      - Ghi nhận defects, retest sau khi developer sửa lỗi và thực hiện regression testing
      - Báo cáo kết quả kiểm thử, mức độ pass/fail và tình trạng chất lượng sản phẩm
  - Software testing lifecycle / test process
    - Test planning
      - Xác định phạm vi kiểm thử, mục tiêu, nguồn lực, lịch trình và rủi ro chính
      - Chọn test levels, test types, môi trường kiểm thử và tiêu chí bắt đầu/kết thúc
    - Test monitoring and control
      - Theo dõi tiến độ chuẩn bị test cases, execution, defects và coverage
      - Điều chỉnh kế hoạch khi requirement, deadline hoặc rủi ro thay đổi
    - Test analysis
      - Phân tích requirement, user stories, acceptance criteria và tài liệu nghiệp vụ
      - Xác định test conditions và các điểm cần kiểm chứng
    - Test design
      - Chuyển test conditions thành test cases, test data và expected results
      - Sử dụng kỹ thuật thiết kế test để tăng coverage và giảm trùng lặp
    - Test implementation
      - Chuẩn bị test suites, test environment, test data và thứ tự thực thi
      - Liên kết test cases với requirement để hỗ trợ traceability
    - Test execution
      - Chạy manual/automated tests và ghi nhận kết quả thực tế
      - So sánh actual result với expected result để xác định pass/fail
    - Test completion
      - Tổng hợp test summary report, bài học kinh nghiệm và trạng thái chất lượng cuối cùng
      - Lưu trữ testware để tái sử dụng cho regression hoặc các release sau
  - Test levels
    - Component/unit testing
      - Kiểm thử từng hàm, class hoặc module nhỏ, thường do developer thực hiện
    - Integration testing
      - Kiểm thử tương tác giữa các module, service, API hoặc hệ thống con
    - System testing
      - Kiểm thử toàn bộ hệ thống so với requirement chức năng và phi chức năng
    - Acceptance testing
      - Xác nhận sản phẩm đáp ứng nhu cầu người dùng, business process và tiêu chí nghiệm thu
      - Có thể bao gồm UAT, operational acceptance testing hoặc alpha/beta testing
  - Test types
    - Functional testing
      - Kiểm tra hệ thống có thực hiện đúng chức năng đã mô tả trong requirement hay không
      - Bao gồm UI testing, API testing, database validation và business workflow testing
    - Non-functional testing
      - Đánh giá các thuộc tính chất lượng như performance, security, usability, reliability và compatibility
      - Giúp xác định hệ thống có đủ tốt để vận hành trong điều kiện thực tế hay không
    - Black-box testing
      - Thiết kế test dựa trên đầu vào, đầu ra và hành vi quan sát được, không cần biết code bên trong
    - White-box testing
      - Thiết kế test dựa trên cấu trúc code, logic nhánh, câu lệnh và đường đi thực thi
    - Change-related testing
      - Confirmation testing/retesting để xác nhận lỗi đã được sửa
      - Regression testing để đảm bảo thay đổi mới không làm hỏng chức năng cũ
    - Exploratory testing
      - Vừa học hệ thống, vừa thiết kế test, vừa thực thi test dựa trên kinh nghiệm và quan sát thực tế
  - Test design techniques
    - Equivalence partitioning
      - Chia dữ liệu đầu vào thành các nhóm hợp lệ/không hợp lệ có hành vi kỳ vọng tương tự
    - Boundary value analysis
      - Kiểm thử tại các giá trị biên, ngay dưới biên và ngay trên biên vì lỗi thường xuất hiện ở ranh giới
    - Decision table testing
      - Kiểm thử các tổ hợp điều kiện và hành động trong nghiệp vụ có nhiều rule
    - State transition testing
      - Kiểm thử hệ thống thay đổi trạng thái theo event, ví dụ login, payment hoặc order status
    - Use case testing
      - Kiểm thử theo luồng tương tác giữa người dùng và hệ thống để xác nhận mục tiêu nghiệp vụ
    - Statement/branch coverage
      - Đo mức độ code hoặc nhánh logic đã được kiểm thử trong white-box testing
    - Error guessing
      - Dựa trên kinh nghiệm để dự đoán nơi dễ phát sinh lỗi như dữ liệu rỗng, định dạng sai hoặc thao tác bất thường
  - Defect reporting and tracking
    - Defect report content
      - Summary rõ ràng, môi trường, version/build, preconditions và test data
      - Steps to reproduce đủ chi tiết để developer có thể tái hiện lỗi
      - Actual result, expected result, evidence như screenshot/log/video và mức độ ảnh hưởng
    - Severity and priority
      - Severity mô tả mức độ nghiêm trọng về kỹ thuật hoặc tác động đến hệ thống
      - Priority mô tả mức độ cần xử lý sớm theo giá trị kinh doanh, deadline hoặc rủi ro release
    - Defect lifecycle
      - New → Assigned/Open → Fixed → Retest → Closed hoặc Reopened
      - Có thể có trạng thái Deferred, Duplicate, Cannot Reproduce hoặc Won't Fix tùy quy trình dự án
    - Tracking tools
      - Sử dụng Jira, Azure DevOps, GitLab, Redmine hoặc công cụ tương tự để quản lý defects
      - Liên kết defect với requirement, test case, release và commit khi cần traceability
  - Test automation
    - Automation scope
      - Ưu tiên test lặp lại nhiều lần, ổn định, có giá trị regression cao và ít phụ thuộc quan sát thủ công
      - Không tự động hóa mọi thứ nếu chi phí bảo trì cao hơn lợi ích kiểm thử
    - Automation levels
      - Unit tests kiểm tra logic nhỏ và chạy nhanh
      - API/service tests kiểm tra nghiệp vụ và tích hợp ở mức ổn định hơn UI
      - UI end-to-end tests kiểm tra luồng người dùng quan trọng nhưng thường chậm và dễ bị ảnh hưởng bởi thay đổi giao diện
    - Tools and frameworks
      - Web UI: Selenium, Playwright, Cypress hoặc TestComplete
      - Mobile: Appium hoặc framework native phù hợp
      - API: Postman, REST Assured, Playwright API hoặc thư viện HTTP trong Python/JavaScript
      - Test management/CI: Jenkins, GitHub Actions, GitLab CI, Azure DevOps, Xray hoặc Zephyr
    - Maintenance
      - Cập nhật locator, test data, assertion và test environment khi sản phẩm thay đổi
      - Theo dõi flaky tests để tránh làm giảm niềm tin vào automation suite
  - Risk-based testing
    - Risk identification
      - Xác định khu vực có khả năng lỗi cao hoặc tác động lớn đến người dùng/doanh nghiệp
      - Xem xét độ phức tạp kỹ thuật, thay đổi gần đây, lịch sử defect và mức độ quan trọng của chức năng
    - Risk assessment
      - Đánh giá rủi ro theo likelihood và impact
      - Ưu tiên kiểm thử chức năng có rủi ro cao trước khi kiểm thử các phần ít quan trọng hơn
    - Risk mitigation
      - Tăng coverage, review kỹ hơn, chuẩn bị test data tốt hơn hoặc bổ sung automation cho khu vực quan trọng
      - Báo cáo rủi ro còn lại để Product Owner/manager ra quyết định release có cơ sở
  - Communication with developers, business analysts, product owners, and users
    - With developers
      - Trao đổi defect bằng thông tin tái hiện rõ ràng, bằng chứng cụ thể và thái độ hợp tác
      - Làm rõ nguyên nhân kỹ thuật khi cần retest hoặc đánh giá ảnh hưởng regression
    - With business analysts
      - Làm rõ requirement, business rules, edge cases và acceptance criteria
      - Phát hiện mâu thuẫn hoặc thiếu sót trong tài liệu trước khi bắt đầu test execution
    - With product owners
      - Thống nhất priority, release risk, phạm vi kiểm thử và quyết định chấp nhận lỗi còn lại
      - Cung cấp test status/report dễ hiểu để hỗ trợ quyết định sản phẩm
    - With users
      - Thu thập phản hồi UAT, quan sát luồng sử dụng thực tế và xác nhận sản phẩm đáp ứng nhu cầu công việc
      - Diễn giải lỗi hoặc giới hạn hệ thống bằng ngôn ngữ dễ hiểu, không quá kỹ thuật
  - AI-assisted testing in modern QA/QC work
    - Test analysis support
      - Tóm tắt requirement, gợi ý test scenarios và phát hiện điểm mơ hồ trong user stories
      - Hỗ trợ tạo checklist ban đầu cho functional, regression hoặc UAT
    - Test design support
      - Gợi ý test cases, boundary values, negative cases và dữ liệu kiểm thử mẫu
      - Hỗ trợ biến acceptance criteria thành test scenarios có cấu trúc
    - Automation support
      - Gợi ý code automation, refactor test scripts và giải thích lỗi trong execution logs
      - Hỗ trợ tạo helper functions hoặc test data nhưng QA vẫn phải review và chạy xác nhận
    - Defect analysis support
      - Tóm tắt bug reports, nhóm lỗi theo pattern và hỗ trợ phân tích log dài
      - Gợi ý mức độ ảnh hưởng ban đầu nhưng quyết định severity/priority cần dựa trên bối cảnh sản phẩm
    - Limitations and responsibility
      - AI có thể sinh nội dung sai, thiếu ngữ cảnh hoặc bỏ sót rủi ro quan trọng
      - QA/QC vẫn chịu trách nhiệm cuối cùng về tính đúng đắn của test cases, kết quả kiểm thử và báo cáo chất lượng

## 3. Student review to find >= 3 issues

```text
Lỗi 1: Black-box testing và White-box testing bị xếp nhầm vào "Test types"
Theo ISTQB FL, black-box và white-box là các nhóm kỹ thuật thiết kế test
(test design technique categories), không phải test types. Test types bao gồm:
functional, non-functional, structural và change-related testing.
Sửa: chuyển black-box và white-box sang mục "Test design techniques".

Lỗi 2: Exploratory testing bị xếp nhầm vào "Test types"
Theo ISTQB FL 4.4, exploratory testing là một experience-based test technique,
không phải test type. Mindmap đã có mục "Test design techniques" riêng nhưng
lại không đặt exploratory testing vào đó.
Sửa: chuyển exploratory testing sang mục "Test design techniques" cùng
với error guessing.

Lỗi 3: Test completion thiếu bước đánh giá exit criteria
Mindmap chỉ mô tả hai hoạt động: viết test summary report và lưu trữ testware.
Theo ISTQB FL 5.3, Test Completion còn phải bao gồm việc đánh giá xem exit
criteria đã được đáp ứng chưa trước khi kết thúc giai đoạn kiểm thử chính thức.
Sửa: bổ sung "Đánh giá exit criteria để xác nhận giai đoạch kiểm thử
có thể kết thúc" vào mục Test completion.
```
