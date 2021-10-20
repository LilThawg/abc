Câu 14: Trình bày (nn tựa C) giải thuật duyệt cây theo thứ tự trước, ko đệ quy, dùng stack

Ý tưởng:

1. kiểm tra rỗng

nếu cây rỗng thì kết thúc

nếu không rỗng thì khởi tạo stack

2. thực hiện duyệt

in ra khóa của nút gốc

nếu cây con phải khác rỗng thì lưu địa chỉ gốc cây con phải vào stack

chuyển xuống cây con trái, in ra khóa của nút con trái... (lặp lại)

![image](https://user-images.githubusercontent.com/72289126/138103848-196fb7c3-78b0-48ee-9239-91be00ff27ec.png)
