# appthitracnghiem
Đề tài 1a: Xây dựng hệ thống trắc nghiệm qua mạng LAN Mục đích của đề tài:
- Sinh viên tập làm quen với việc phân tích và thiết kế hệ thống 
- Sinh viên tập làm việc nhóm và học một số công cụ quản lý source code (Git) 
- Sinh viên thực hành lập trình hướng đối tượng 
- Sinh viên thực hành thiết kế và truy vấn cơ sở dữ liệu 
- Sinh viên làm quen với việc lập trình ứng dụng giao diện 
- Xây dựng ứng dụng thi trắc nghiệm đơn giản gồm 2 bản cho nhân viên quản lý và người dự thi Yêu cầu của hệ thống: 
- Người quản lý có thể đăng nhập vào ứng dụng quản lý bằng 1 tài khoản cố định 
- Người quản lý tạo môn thi, chủ đề thi (có thể có các chủ đề con) 
- Người quản lý nhập câu hỏi và câu trả lời, độ khó (từ 1 đến 5), phân loại môn học và chủ đề 
- Người quản lý tạo đề thi bằng cách chọn môn học -> chủ đề, số lượng câu theo từng độ khó, thời gian thi. 
- Hệ thống tạo ra đề bài bằng cách lấy ngẫu nhiên các câu hỏi thuộc môn học và chủ đề tương ứng, sao cho thoả mãn số lượng câu có độ khó đã định từ trước. Sau đó sáo thứ tự câu có cùng độ khó và thứ tự câu trả lời để được 12 mã đề. (Các câu từ 1 đến N có độ khó tăng dần) 
- Người quản lý tạo danh sách thí sinh, và sinh ra mã số dự thi (MSDT) kèm một mật khẩu. MSDT là duy nhất trong hệ thống, mật khẩu dự thi là chuỗi ngẫu nhiên có 10 ký tự (các ký tự a-z, A-Z, 0-9) 
- Người dự thi đăng nhập vào ứng dụng thi bằng MSDT và mật khẩu tương ứng được cung cấp bởi người quản lý. Mỗi MSDT chỉ đăng nhập được trên một máy tính 
- Khi người dự thi ấn bắt đầu thi, họ sẽ nhận được 1 mã đề và bắt đầu thời gian thi. 
- Hết thời gian thi, hệ thống sẽ tự động logout và hiện kết quả. Đồng thời lưu kết quả của thí sinh vào cơ sở dữ liệu. Sau khi bị logout, người dự thi sẽ không login được vào hệ thống nữa. 
Công nghệ đề xuất: 
- Ngôn ngữ Java 
- Hệ quản trị cơ sở dữ liệu: MySQL 
- IDE:​Netbeans​
- Source:​Github​

