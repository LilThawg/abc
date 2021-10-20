Câu 12: Trình bày ( bằng ngôn ngữ tựa C ) giải thuật định giá biểu thực hậu tố bằng cách dùng stack.

Ý tưởng

Ta xem biểu thức hậu tố như một dãy các thành phần, mà mỗi thành phần là toán hạng hoặc toán tử

B1: Khởi tạo 1 stack rỗng

B2: Đọc lần lượt các phần tử của biểu thức từ trái qua phải 

Nếu là toán hạng, đẩy vào stack

Nếu là toán tử X, lấy từ stack ra 2 giá trị (Y và Z) sau đó áp dụng toán tử đó vào 2 giá trị vừa lấy ra, đẩy kết quả tìm được (Z X Y) vào stack

B3: sau khi kết thúc B2, thì tất cả biểu thức hậu tố đã đọc xong, trong stack còn duy nhất 1 phần tử là giá trị của biểu thức

![image](https://user-images.githubusercontent.com/72289126/138103249-3213cff2-d316-4e3a-bd35-8e61d9e27466.png)
