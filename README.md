**Nội dung áp dụng** 

Tổng hợp và liên kết toàn bộ các kiến thức đã học trong Session 04 về Kỹ thuật Prompting Nâng cao (Logic & Chuỗi).

**1. Bối cảnh bài toán thực tế**

Xây dựng giải pháp hoàn chỉnh giải quyết yêu cầu tích hợp liên quan đến Chain-of-Thought, Prompt Chaining, xử lý đứt gãy.

**2. Yêu cầu chi tiết**

Thiết lập chuỗi prompt liên kết (Prompt Chaining) chạy tuần tự khép kín để giải quyết bài toán lớn.

**3. Ràng buộc kỹ thuật**

Code sạch, tối ưu token, có cơ chế bắt lỗi dữ liệu dị biệt không làm crash hệ thống.

**4. Yêu cầu đầu ra chi tiết**

1. Thiết kế giải pháp
Em xây dựng một hệ thống AI hỗ trợ quản lý đơn hàng bằng kỹ thuật Prompt Chaining. Hệ thống chia công việc thành nhiều bước nhỏ để AI dễ xử lý và hạn chế sai sót.

Quy trình gồm 4 bước: phân tích dữ liệu, kiểm tra dữ liệu, tổng hợp thông tin và xuất báo cáo.
2. Các Prompt thực hiện
Bước 1: Phân tích dữ liệu
Hãy kiểm tra danh sách đơn hàng và phân loại
đơn hàng hợp lệ, bị thiếu thông tin hoặc bị trùng.


Bước 2: Làm sạch dữ liệu
Hãy loại bỏ dữ liệu trùng lặp, sửa lỗi định dạng
và đánh dấu những đơn hàng còn thiếu thông tin.
Không tự ý thêm dữ liệu.


Bước 3: Tổng hợp
Dựa vào dữ liệu đã làm sạch, hãy tính tổng số
đơn hàng và tổng doanh thu.


Bước 4: Kiểm tra kết quả
Hãy kiểm tra lại kết quả tính toán.
Nếu phát hiện sai sót thì sửa lại.
Sau đó xuất báo cáo dưới dạng bảng.


3. Kết quả đầu ra
Sau khi chạy chuỗi Prompt, AI thu được kết quả mẫu:
Nội dung	Kết quả
Tổng đơn hàng ban đầu	5
Đơn hàng hợp lệ	3
Đơn hàng trùng lặp	1
Đơn hàng thiếu thông tin	1
Tổng doanh thu	1.000.000đ.
