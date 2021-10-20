Câu 8. Trình bày cách Xác định độ phức tạp tính toán của giải thuật, với những nội dung: Qui tắc tổng, phép toán tích cực, thời gian chạy của các câu lệnh lặp, cho ví dụ minh họa.

Nếu thời gian thực hiện 1 giải thuật là T(n)=cn2 (c là hằng số) thì ta nói : độ phức tạp tính toán của giải thuật này có cấp là n2 và ta ký hiệu:

	T(n) = O(n2)       (ký hiệu chữ O lớn)

Một cách tổng quát có thể định nghĩa: 1 hàm f(n) được xác định là O(g(n))

	f(n) = O(g(n))

và được gọi là có cấp g(n) nếu tồn tại các hằng số c và n0 sao cho:

	f(n) <=cg(n) khi n>=n0

nghĩa là khi f(n) bị chặn trên bởi 1 hằng số nhân với g(n) với mọi giá trị của n từ một thời điểm nào đó.

Quy tắc tổng: Giả sử T1(n) và T2(n) là thời gian thực hiện của 1 đoạn chương trình P1 và P2 mà T1(n) = O(f(n)); T2(n) = O(g(n)) thì thời gian thực hiện P1 và P2  tiếp theo sẽ là: T1(n) + T2(n) = O(max(f(n),g(n)).

Ví dụ: trong 1 chương trình có 3 bước thực hiện mà thời gian thực hiện từng bước lần lượt là O(n2), O(n3) và O(n log2n) thì thời gian thực hiện 2 bước đầu là O(max(n2,n3))=O(n3) thời gian thực hiện chương trình sẽ là: 

O(max(n3, n log2n))=O(n3).

Thời gian chạy của các câu lệnh lặp: 

	Các câu lệnh lặp gồm: for, while, do.. while

Để đánh giá thời gian thực hiện 1 câu lệnh lặp, trước hết ta cần đánh giá số tối đa các lần lặp giả sử đó là L(n). Sau đó đnahs giái thời gian chạy của mỗi lần lặp, chú ý rằng thời gian thực hiện thân của 1 lệnh lặp ở các lần lặp khác nhau có thể khác nhau, giả sử thời gian thực hiện thân lệnh lặp ở lần thứ i(i=1,2,..L(n)) là Ti(n). Mỗi lần lặp, chúng ta cần kiểm tra điều kiện lặp giả sử thời gian lặp kiểm tra là T0(n). Như vậy thời gian chạy của lệnh lặp là:

∑_(i=1)^(L(n))▒( T0(n)+ Ti(n))

Công đoạn khó nhất trong đánh giá thời gian chạy của 1 lệnh lặp là đánh giá số lần lặp. Trong nhiều lệnh lặp, đặc biệt là trong các lệnh lặp For, ta có thể thấy ngay số lần lặp tối đa là bao nhiêu. Nhưng cũng không ít các lệnh lặp, từ điều kiện lặp để suy ra số tối đa các lần lặp, ta cần phải tiến hành các suy diễn không đơn giản.

Trường hợp hay gặp là kiểm tra điều kiện lặp chỉ cần thời gian O(1), thời gian thực hiện các lần lặp là như nhau và giả sử ta đánh giá được là O(f(n)); khi đó nếu đánh giá được số lần lặp là O(g(n)) thì thời gian chạy của lệnh lặp là O(g(n)).f(n)

Ví dụ: giải sử có mảng A các số thực, cỡ n và ta cần tìm xem mảng có chứa số thực x không. Điều đó có thể thực hiện bởi giải thuật tìm kiếm tuần tự như sau:

i=0;

while(i<n&& x!=A[i])

i++;

lệnh gán (1) có thời gian chạy là O(1). Lệnh lặp (2)-(3) có số tối đa các lần lặp là n, đó là trường hợp x chỉ xuất hiện ở thành phần cuối cùng của mảng A[n-1] hoặc x không có trong mảng. Thân của lệnh lặp là lệnh (3) có thời gian chạy O(1). Do đó, lệnh lặp có thời gian chạy là O(n). Giải thuật gồm lệnh gán và lệnh lặp với thời gian là O(1) và O(n), nên thời gian chạy của nó là O(n).

phép toán tích cực: Đó là phép toán thuộc giải thuật mà thời gian thực hiện không ít hơn thời gian thực hiện các phép khác hay nói cách khác: số lần thực hiện nó không kém các phép khác.

