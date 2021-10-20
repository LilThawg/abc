Câu 15: Trình bày giải thuật duyệt cây theo thứ tự giữa bằng giải thuật ko đệ quy có sử dụng stack

Ý tưởng:

1. kiểm tra rỗng

nếu cây rỗng thì kết thúc

nếu không rỗng thì khởi tạo stack

2. thực hiện duyệt

lưu địa chỉ của nút gốc vào stack, chuyển xuống cây con trái (lặp lại bước này tới 

khi cây con trái là rỗng)

lấy phần tử trên cùng ra khỏi stack, trỏ vào vị trí của nút đó trên cây

in ra khóa của nút đang xét

trỏ đến cây con phải

.... (lặp lại cho tới khi stack rỗng)

![image](https://user-images.githubusercontent.com/72289126/138104167-8041809e-67fd-4904-b252-390c1cb41365.png)
