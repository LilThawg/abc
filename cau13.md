Câu 13: chuyển đổi biểu thức trung tố sang hậu tố

Ý tưởng:

1. khởi tạo 1 ngăn xếp (stack) rỗng

2. đọc lần lượt các thành phần trong biểu thức

nếu X là toán hạng thì viết nó vào biểu thức hậu tố (in ra)

nếu X là phép toán thì thực hiện:

+ nếu stack không rỗng thì: nếu phần tử ở đỉnh stack là phép toán có độ ưu tiên cao hơn hoặc bằng phép toán hiện thời (X) thì phép toán đó được kéo ra khỏi stack và viết vào biểu thức hậu tố (lặp lại bước này)

+ nếu stack rỗng hoặc phần ử ở đỉnh ngăn xếp là dấu mở ngoặc hoặc phép toán ở đỉnh ngăn xếp có quyền ưu tiên thấp hơn phép toán hiện thời (X) thì phép toán hiện thời được đẩy vào ngăn xếp

nếu X là dấu mở ngoặc thì nó được đẩy vào stack

nếu X là dấu đóng ngoặc thì thực hiện:

+ (bước lặp):loại các phép toán ở đỉnh ngăn xếp và viết vào biểu thức dạng hậu tố cho tới khi đỉnh ngăn xếp là dấu mở ngoặc

+ loại dấu mở ngoặc khỏi ngăn xếp

3. sau khi toàn bộ biểu thức dạng trung tố được đọc, loại lần lượt các phép toán ở đỉnh stack và viết vào biểu thức hậu tố cho tới khi stack rỗng

![image](https://user-images.githubusercontent.com/72289126/138103623-a839ea6b-fa32-42b9-9c3f-00e7c931d6b8.png)
