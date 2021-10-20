Câu 5 : Phương pháp thiết kế Top_Down

Ngày nay công nghệ thông tin đã và đang được ứng dụng trong mọi lĩnh vực của cuộc sống, bởi vậy các bài toán giải được trên máy tính điện tử rất đa dạng vào phức tạp, các giải thuật và chương trình để giải chúng cũng có quy mô ngày càng lớn , nên càng khó thì ta càng muốn tìm hiểu và thiết lập chúng.

Tuy nhiên ta cũng thấy rằng mọi việc  sẽ đơn giản hơn nếu như có thể phân chia bài toán lớn thành các bài toán nhỏ hơn. Điều đó cũng có nghã là nếu coi bài toán của ta như một mô đun chính thì cần chia nó thành các mô đun con, và dĩ nhiên, với tinh thần như thế, đến lượt nó, mỗi mô đun con này lại tiếp tục được chia tiếp cho tới những mô đun ứng với các phần việc cơ bản mà ta đã biết cách giải quyết. Như vậy việc tổ chức lời giải của các bài toán sẽ được thể hiện  theo một cấu trúc nhân cấp có dạng như sau :

Cách giải quyết bài toán theo hình như vậy được gọi là chiến thuật “ chia để trị” . Để thể hiện chiến thuật đó, người ta dùng cách thiết kế “ đinh_xuống” (top-down design). Đó là cách phân tích tổng quát toàn bộ vấn đề, xuất phát từ dữ kiện và các mục tiêu đặt ra để đề cập đến những công việc chủ yếu trước, rồi sau đó mwosi đi dần vào giải quyết các phần việc cụ thể một cách chi tiết hơn, cũng vì vậy mà người ta còn gọi cách thiết kế này là cách thiết kế từ khái quát đến chi tiết.

Ví dụ: để viết chương trình quản lí bán hàng chạy trên máy tính, với các yêu cầu là : hàng ngày phải nhập các hóa đơn bán hàng, hóa đơn nhập hàng, tìm kiếm các hóa đơn đã nhập để xem hoặc sửa lại. in các hóa đơn cho khách hàng; tính doanh thu, lợi nhuận trong khoảng thời gian bất  kì; tính tổng hợp kho, tính doanh số của từng mặt hàng, từng khách hàng.

Xuất phát từ những yêu cầu trên ta không thể có ngay giải thuật để xử lí, mà nên chia bài toán thành 3 nhiệm vụ chính cần giải quyết như sau:

Xử lí các danh mục để quản lí và theo dõi các thông tin về hàng hóa và khách hàng.

Xử lí dữ liệu về các hóa đơn bán hàng, hóa đơn nhập hàng.

In các báo cáo về doanh thu, lợi nhuận.

Có thể hình dung cách thiết kế này theo sơ đồ cấu trúc sau:

![image](https://user-images.githubusercontent.com/72289126/138100879-b6a9fbe8-b995-406e-9c77-6c6bba0f1773.png)

Các nhiệm vụ ở mức đầu này thường vẫn còn tương đối phức tạp, nên cần phải chia tiếp thành các nhiệm vụ con. Chằng hạn nhiệm vụ “ xử lí doanh mục” được chia thành hai là “ danh mục hàng hóa” và “ danh mục khách hàng”.

Trong danh mục hàng hóa lại có thể chia thành các nhiệm vụ nhỏ hơn như:

Thêm hàng mới

Tìm kiếm hàng

Tổng hợp kho

![image](https://user-images.githubusercontent.com/72289126/138101068-7957b29c-5c09-4d1b-b9f4-592424f624f6.png)

Cách thiết kế giải thuật theo kiểu top-down như trên giúp cho việc gải quyết bài toán được  định hướng rõ ràng , tránh sa đà ngay vào các chi tiết phụ. Nó cũng là các nền tảng cho việc lập trình có cấu trúc.

Thông thường, đối với các bài toán lớn, việc giải quyết nó phải do nhiều người cùng làm . Chính phương pháp mô đun hóa sẽ cho phép tách bài toán ra thành các phần độc lập, tạo điều kiện cho các nhóm giải quyết phần việc của mình mà không ảnh hưởng gì đến nhóm khác. Với chương trình được xây dựng trên cơ sở của các giải thuật được thiết kế theo cách này , thì việc tìm hiểu cũng như sửa chữa, chỉnh lí sẽ đơn giản hơn.

Trong thực tế, việc phân tích bài toán thành các bài toán con như thế không phải là việc dễ dàng. Chính vì vậy mà có những bài toán, nhiệm vụ phân tích và thiết kế giải thuật giải bài toán còn mất nhiều thời gian và công sức hơn cả nhiệm vụ lập trình.





