Câu 16: Tìm kiếm nhị fân

Ý tưởng:

giả sử dãy ban đầu được sắp xếp theo thứ tự tăng dần (K0<K1<...<Kn)

ta chọn khóa ở "giữa" (giả sử Kg) của dãy đang xét để so sánh

+ nếu x = Kg : tìm thấy x trong dãy, dừng quá trình tìm kiếm

+ nếu x < Kg : nếu x có trong dãy thì x nằm ở nửa bên trái của Kg

+ nếu x > Kg : nếu x có trong dãy thì x nằm ở nửa bên phải của Kg

việc tìm kiếm x trên nửa bến trái (hoặc bên phải) của Kg được thực hiện như việc tìm x trên cả dãy ban đầu.

![image](https://user-images.githubusercontent.com/72289126/138104526-f55338bd-8418-4868-b997-71c8b15fc900.png)

![image](https://user-images.githubusercontent.com/72289126/138104694-2712c9cd-c2c1-4ce8-8dca-16141e699ea0.png)



