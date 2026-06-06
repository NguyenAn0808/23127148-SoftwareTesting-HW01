# Requirement 3 – Test Cases for One Physical Product

## 1. Thông tin thiết bị được kiểm thử

- Tên thiết bị: Ấm siêu tốc / Rapid boil kettle
- Brand: [STUDENT TODO: điền brand]
- Model: [STUDENT TODO: điền model]
- Year: [STUDENT TODO: điền năm sản xuất/mua thiết bị]
- Serial number: [STUDENT TODO: điền serial number và che 4 ký tự ở giữa]
- Ảnh thiết bị + thẻ sinh viên: [STUDENT TODO: thêm ảnh thiết bị + thẻ sinh viên trong cùng khung hình]

Thiết bị được chọn là một ấm siêu tốc thật đang được sử dụng trong nhà sinh viên. Tất cả thông tin nhận dạng sản phẩm, ảnh chụp, video kiểm thử, kết quả thực tế và bằng chứng lỗi phải được sinh viên bổ sung sau khi kiểm tra thiết bị thật.

## 2. Phạm vi kiểm thử

Phạm vi kiểm thử tập trung vào các chức năng và đặc điểm có thể quan sát an toàn khi sử dụng ấm siêu tốc trong điều kiện gia đình bình thường, bao gồm: kiểm tra ngoại quan, nắp ấm, công tắc, đèn báo, khả năng đun nước, tự ngắt khi nước sôi, rò rỉ nước, dây nguồn, đế cấp điện, tay cầm, vòi rót và một số điều kiện biên cơ bản như mực nước thấp hoặc gần mức tối đa.

Các kiểm thử không bao gồm tháo rời thiết bị, can thiệp mạch điện, đo điện áp bên trong, làm hỏng linh kiện, thử nghiệm quá tải nguy hiểm, vận hành khi không có nước nếu nhà sản xuất không cho phép, hoặc bất kỳ thao tác nào có thể gây bỏng, điện giật, cháy nổ hoặc hư hỏng thiết bị.

## 3. Chiến lược thiết kế test cases

Bộ 15 test cases được thiết kế để bao phủ các nhóm rủi ro chính của ấm siêu tốc: sử dụng bình thường, an toàn khi vận hành, tính tiện dụng, điều kiện biên cơ bản và kiểm tra vật lý bên ngoài. Các test cases được viết ở mức baseline để sinh viên có thể thực thi trên thiết bị thật, ghi nhận actual result bằng bằng chứng video ngắn và chỉ tạo defect/GitHub Issue khi lỗi thật được xác nhận.

## 4. Danh sách 15 test cases

| ID | Objective | Input | Steps | Expected result | Actual result | Verdict | Evidence/video link | Ghi chú |
|---|---|---|---|---|---|---|---|---|
| TC-KETTLE-01 | Kiểm tra thông tin nhận dạng và tình trạng ngoại quan của thiết bị | Ấm siêu tốc thật, thẻ sinh viên, camera | 1. Đặt ấm và thẻ sinh viên trong cùng khung hình.<br>2. Chụp ảnh mặt ngoài thiết bị.<br>3. Ghi nhận brand, model, year và serial number đã che 4 ký tự ở giữa.<br>4. Quan sát vỏ ấm, đáy ấm, nắp, tay cầm và dây nguồn. | Thiết bị được nhận dạng rõ ràng; không có hư hỏng ngoại quan nghiêm trọng có thể gây nguy hiểm khi kiểm thử. | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | [STUDENT TODO: thêm ảnh/video kiểm thử ≤ 60 giây] | Dự kiến thực thi trên thiết bị thật. |
| TC-KETTLE-02 | Kiểm tra nắp ấm đóng/mở đúng cách | Ấm rỗng, không cắm điện | 1. Đặt ấm trên mặt phẳng khô.<br>2. Mở nắp ấm.<br>3. Đóng nắp ấm lại.<br>4. Kiểm tra nắp có khít và không bị kẹt hay không. | Nắp mở/đóng trơn tru, đóng khít, không bị lỏng bất thường hoặc kẹt cơ học. | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | [STUDENT TODO: thêm video kiểm thử ≤ 60 giây] | Dự kiến thực thi trên thiết bị thật. |
| TC-KETTLE-03 | Kiểm tra ấm nhận điện khi đặt đúng lên đế | Nước ở mức an toàn, đế cấp điện, nguồn điện gia đình | 1. Đổ nước vào ấm trong khoảng min-max.<br>2. Đặt ấm lên đế cấp điện.<br>3. Cắm điện.<br>4. Bật công tắc đun.<br>5. Quan sát đèn báo hoặc dấu hiệu thiết bị bắt đầu hoạt động. | Khi đặt đúng lên đế và bật công tắc, ấm bắt đầu đun; đèn báo hoặc trạng thái hoạt động hiển thị rõ. | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | [STUDENT TODO: thêm video kiểm thử ≤ 60 giây] | Dự kiến thực thi trên thiết bị thật. |
| TC-KETTLE-04 | Kiểm tra chức năng đun nước trong sử dụng bình thường | Nước sạch ở mức trung bình trong giới hạn min-max | 1. Đổ nước sạch vào ấm ở mức trung bình.<br>2. Đóng nắp.<br>3. Đặt ấm lên đế và bật công tắc.<br>4. Quan sát quá trình đun cho đến khi nước sôi hoặc thiết bị tự ngắt. | Ấm đun nước đến trạng thái sôi và không có dấu hiệu bất thường như mùi khét, khói, tia lửa, rò nước hoặc tiếng động nguy hiểm. | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | [STUDENT TODO: thêm video kiểm thử ≤ 60 giây] | Dự kiến thực thi trên thiết bị thật. |
| TC-KETTLE-05 | Kiểm tra cơ chế tự ngắt sau khi nước sôi | Nước sạch trong giới hạn min-max | 1. Đổ nước vào ấm ở mức an toàn.<br>2. Đóng nắp.<br>3. Bật công tắc đun.<br>4. Chờ đến khi nước sôi.<br>5. Quan sát công tắc và đèn báo sau khi nước sôi. | Sau khi nước sôi, ấm tự ngắt; công tắc chuyển về trạng thái tắt hoặc đèn báo tắt theo thiết kế của thiết bị. | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | [STUDENT TODO: thêm video kiểm thử ≤ 60 giây] | Dự kiến thực thi trên thiết bị thật. |
| TC-KETTLE-06 | Kiểm tra rò rỉ khi ấm chứa nước trước khi đun | Nước sạch trong giới hạn min-max, khăn giấy khô | 1. Đổ nước vào ấm trong giới hạn cho phép.<br>2. Đặt ấm lên khăn giấy khô trong 1-2 phút khi chưa cắm điện.<br>3. Quan sát quanh thân, đáy ấm và khăn giấy. | Không có nước rò ra từ thân, đáy, nắp hoặc khu vực tiếp giáp với đế ấm. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không thực thi trong baseline. |
| TC-KETTLE-07 | Kiểm tra rò rỉ khi rót nước sau khi đun | Nước đã đun, ly/cốc chịu nhiệt | 1. Đun nước trong điều kiện bình thường.<br>2. Sau khi ấm tự ngắt, nhấc ấm khỏi đế.<br>3. Rót nước chậm vào ly/cốc chịu nhiệt.<br>4. Quan sát vòi rót, nắp và thân ấm. | Nước chảy ra từ vòi rót ổn định; không rò mạnh từ nắp, thân hoặc đáy ấm; người dùng có thể rót an toàn. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Cần thao tác cẩn thận để tránh bỏng. |
| TC-KETTLE-08 | Kiểm tra tay cầm khi cầm ấm có nước nóng | Ấm có nước nóng sau khi đun | 1. Đun nước trong điều kiện bình thường.<br>2. Sau khi ấm tự ngắt, chờ vài giây để hơi nước giảm.<br>3. Cầm ấm bằng tay cầm.<br>4. Không chạm vào thân kim loại/thân nóng của ấm.<br>5. Ghi nhận cảm giác an toàn khi cầm. | Tay cầm chắc chắn, không lỏng, không quá nóng đến mức không thể cầm trong thao tác rót bình thường. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Chỉ cầm vào tay cầm; không chạm vào bề mặt nóng. |
| TC-KETTLE-09 | Kiểm tra công tắc bật/tắt thủ công | Nước trong giới hạn an toàn, nguồn điện | 1. Đổ nước vào ấm.<br>2. Đặt ấm lên đế và cắm điện.<br>3. Bật công tắc.<br>4. Sau vài giây, tắt công tắc thủ công nếu thiết kế cho phép.<br>5. Quan sát trạng thái hoạt động. | Công tắc có thể bật/tắt rõ ràng; khi tắt thủ công, quá trình đun dừng và đèn báo tắt hoặc trạng thái hoạt động dừng theo thiết kế. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không ép công tắc nếu thiết kế không cho phép tắt thủ công. |
| TC-KETTLE-10 | Kiểm tra hoạt động với mực nước gần mức tối thiểu | Nước sạch ở gần vạch minimum nhưng không thấp hơn minimum | 1. Đổ nước gần mức minimum theo vạch trên ấm.<br>2. Đóng nắp.<br>3. Bật công tắc đun.<br>4. Quan sát quá trình đun và tự ngắt. | Ấm hoạt động bình thường với mực nước hợp lệ gần minimum và tự ngắt khi nước sôi. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không đun dưới mức minimum nếu thiết bị có quy định. |
| TC-KETTLE-11 | Kiểm tra hoạt động với mực nước gần mức tối đa | Nước sạch ở gần vạch maximum nhưng không vượt quá maximum | 1. Đổ nước gần mức maximum nhưng không vượt vạch.<br>2. Đóng nắp.<br>3. Bật công tắc đun.<br>4. Quan sát khi nước nóng lên và khi tự ngắt. | Ấm đun bình thường; nước không trào ra ngoài trong quá trình đun nếu không vượt quá vạch maximum. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không đổ quá vạch maximum. |
| TC-KETTLE-12 | Kiểm tra độ ổn định của đế và ấm trên mặt phẳng | Ấm có nước ở mức trung bình, mặt bàn phẳng và khô | 1. Đặt đế trên mặt bàn phẳng, khô.<br>2. Đặt ấm có nước lên đế.<br>3. Quan sát độ cân bằng.<br>4. Xoay nhẹ ấm theo phạm vi đặt bình thường nếu thiết kế cho phép. | Đế và ấm đứng ổn định, không nghiêng bất thường, không trượt dễ dàng trên mặt phẳng khô. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không lắc mạnh hoặc làm đổ nước. |
| TC-KETTLE-13 | Kiểm tra dây nguồn và phích cắm bằng quan sát bên ngoài | Dây nguồn, phích cắm, ổ cắm đang tắt/chưa cắm | 1. Đảm bảo phích cắm chưa cắm điện.<br>2. Quan sát dây nguồn từ đầu phích đến đế.<br>3. Quan sát phích cắm và khu vực nối dây.<br>4. Ghi nhận dấu hiệu nứt, hở, cháy xém hoặc lỏng bất thường nếu có. | Dây nguồn và phích cắm không có hư hỏng ngoại quan nguy hiểm; không thấy lõi dây hở, cháy xém hoặc biến dạng nghiêm trọng. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm ảnh/video nếu thực thi ≤ 60 giây] | Chỉ quan sát bên ngoài; không tháo phích cắm hoặc đế. |
| TC-KETTLE-14 | Kiểm tra cảnh báo hoặc ký hiệu an toàn trên thiết bị | Thân ấm, đế ấm, nhãn sản phẩm | 1. Quan sát nhãn hoặc ký hiệu trên thân/đế ấm.<br>2. Tìm các thông tin như điện áp, công suất, mức nước min/max hoặc cảnh báo bề mặt nóng nếu có.<br>3. Ghi nhận thông tin nhìn thấy được. | Các nhãn/ký hiệu quan trọng còn đọc được đủ để người dùng nhận biết thông tin sử dụng và an toàn cơ bản. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm ảnh/video nếu thực thi ≤ 60 giây] | Không tự tạo thông tin nếu nhãn bị mờ; chỉ ghi nhận thực tế. |
| TC-KETTLE-15 | Kiểm tra thao tác vệ sinh bên ngoài sau khi sử dụng | Ấm đã nguội, khăn mềm khô hoặc hơi ẩm | 1. Đảm bảo ấm đã rút điện và nguội.<br>2. Lau nhẹ bên ngoài thân ấm bằng khăn phù hợp.<br>3. Tránh để nước vào đế điện hoặc đầu nối điện.<br>4. Quan sát bề mặt sau khi lau. | Người dùng có thể vệ sinh bên ngoài ấm một cách an toàn khi đã rút điện và để nguội; không có dấu hiệu nước vào khu vực điện. | Chưa thực thi | Chưa thực thi | [STUDENT TODO: thêm video nếu thực thi ≤ 60 giây] | Không ngâm ấm hoặc đế vào nước. |

## 5. Các test cases dự kiến thực thi

| Test case ID | Execution date | Video link under 60 seconds | Actual result | Verdict | Notes |
|---|---|---|---|---|---|
| TC-KETTLE-01 | [STUDENT TODO: điền ngày thực thi] | [STUDENT TODO: thêm ảnh/video ≤ 60 giây] | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | Ghi nhận bằng chứng thiết bị thật và thẻ sinh viên trong cùng khung hình. |
| TC-KETTLE-02 | [STUDENT TODO: điền ngày thực thi] | [STUDENT TODO: thêm video ≤ 60 giây] | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | Kiểm tra nắp khi thiết bị chưa cắm điện. |
| TC-KETTLE-03 | [STUDENT TODO: điền ngày thực thi] | [STUDENT TODO: thêm video ≤ 60 giây] | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | Kiểm tra ấm nhận điện và bắt đầu hoạt động. |
| TC-KETTLE-04 | [STUDENT TODO: điền ngày thực thi] | [STUDENT TODO: thêm video ≤ 60 giây] | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | Kiểm tra quá trình đun nước thông thường. |
| TC-KETTLE-05 | [STUDENT TODO: điền ngày thực thi] | [STUDENT TODO: thêm video ≤ 60 giây] | [STUDENT TODO: điền kết quả thực tế sau khi kiểm thử] | [STUDENT TODO: điền verdict sau khi kiểm thử] | Kiểm tra tự ngắt sau khi nước sôi. |

## 6. Defect log từ thiết bị thật

Các dòng dưới đây chỉ là placeholder để sinh viên điền sau khi kiểm thử thiết bị thật. Không có defect nào được xác nhận trong bản baseline này. Chỉ ghi defect khi có bằng chứng thực tế và có thể mô tả rõ điều kiện tái hiện.

| Defect ID | Related test case | Mô tả defect nghi ngờ | Bằng chứng thực tế | Mức độ ảnh hưởng | Trạng thái |
|---|---|---|---|---|---|
| DEF-KETTLE-01 | [STUDENT TODO: điền test case liên quan nếu có] | [STUDENT TODO: chỉ điền sau khi xác nhận lỗi thật] | [STUDENT TODO: thêm ảnh/video/log liên quan] | [STUDENT TODO: điền mức độ] | Chưa xác nhận |
| DEF-KETTLE-02 | [STUDENT TODO: điền test case liên quan nếu có] | [STUDENT TODO: chỉ điền sau khi xác nhận lỗi thật] | [STUDENT TODO: thêm ảnh/video/log liên quan] | [STUDENT TODO: điền mức độ] | Chưa xác nhận |
| DEF-KETTLE-03 | [STUDENT TODO: điền test case liên quan nếu có] | [STUDENT TODO: chỉ điền sau khi xác nhận lỗi thật] | [STUDENT TODO: thêm ảnh/video/log liên quan] | [STUDENT TODO: điền mức độ] | Chưa xác nhận |
| DEF-KETTLE-04 | [STUDENT TODO: điền test case liên quan nếu có] | [STUDENT TODO: chỉ điền sau khi xác nhận lỗi thật] | [STUDENT TODO: thêm ảnh/video/log liên quan] | [STUDENT TODO: điền mức độ] | Chưa xác nhận |
| DEF-KETTLE-05 | [STUDENT TODO: điền test case liên quan nếu có] | [STUDENT TODO: chỉ điền sau khi xác nhận lỗi thật] | [STUDENT TODO: thêm ảnh/video/log liên quan] | [STUDENT TODO: điền mức độ] | Chưa xác nhận |

## 7. GitHub Issues evidence

- GitHub repository link: [STUDENT TODO: thêm link GitHub repository]
- Screenshot of GitHub Issues page showing student username: [STUDENT TODO: thêm screenshot sau khi có repository/issues]
- GitHub Issue links for confirmed defects: [STUDENT TODO: chỉ thêm link issue sau khi defect thật được xác nhận]

GitHub Issues chỉ nên được tạo sau khi sinh viên đã thực thi test trên thiết bị thật và xác nhận có defect thực tế. Không tạo GitHub Issue cho placeholder hoặc lỗi chưa được xác nhận.