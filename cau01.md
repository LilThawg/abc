Câu 1: Trình bày mối quan hệ giữa cấu trúc dữ liệu và giải thuật. Cho ví dụ minh họa

Cấu trúc dữ liệu và giải thuật có mối quan hệ mật thiết.

Giải thuật là một hệ thống chặt chẽ và rõ ràng các qui tắc nhằm xác định 1 dãy các thao tác trên những đối tượng, sao cho sau 1 số bước hữu hạn thực hiện các thao tác đó ta thu được kết quả mong muốn.

Cấu trúc dữ liệu: là cách tổ chức, lưu trữ dữ liệu trong MTDT 1 cách có thứ tự, có hệ thống nhằm sử dụng dữ liệu 1 cách hiệu quả

Ctdl và gt có mối liên hệ chặt chẽ với nhau, chúng luôn tồn tại song song đi kèm nhau theo công thức: ctdl+gt=ctrinh

Bản thân các phần tử của dữ liệu thường có mối quan hệ với nhau, ngoài ra nếu biết tổ chức chúng theo các cấu trúc dữ liệu thích hợp thì việc thực hiện các phép xử lý trên các dữ liệu sẽ càng thuận lợi hơn, đạt hiệu quả cao hơn. Với 1 ctdl đã chọn ta sẽ có giải thuật xử lý tương ứng. Ctdl thay đổi thì giải thuật cũng thay đổi theo. Để có 1 ctrinh tốt, ta cần phải chọn được ctdl phù hợp và chọn được 1 gt đúng đắn 

Vd: Giả sử ta có 1 danh sách các trường đại học và cao đẳng trên cả nước mỗi trường có các thông tin sau: Tên trường, địa chỉ, sđt phòng đào tạo. Ta muốn viết một chương trình trên máy tính điện tử để khi cho biết “tên trường” máy sẽ hiện ra màn hình cho ta: “địa chỉ” và “số điện thoại phòng đào tạo” của trường đó.

1 cách đơn giản là cứ duyệt tuần tự các tên trường trong dnah sách cho tới khi tìm thấy trên trường cần tìm thì sẽ đói chiếu ra “địa chỉ” và “số điện thoại phòng đào tạo” của trường đó. Cách tìm tuần tự này rõ ràng chỉ chấp nhận được khi danh sách ngắn còn danh sách dài thì rất mất thời gian.

Nếu ta biết tổ chức lại danh sách bằng cách sắp xếp theo thứ tự từ điển của tên trường, thì có thể áp dụng 1 giải thuật tìm kiếm khác tốt hơn, tương tự như ta vẫn thường làm khi tra từ điển. Cách tìm này nhanh hơn cách trên rất nhiều nhưng không thể áp dụng được với dữ liệu chưa được sắp xếp.

Nếu lại biết tổ chức thêm 1 bảng mục lục chỉ dẫn theo chữ cái đầu tiên của tên trường, thì khi tìm “địa chỉ” và “số điện thoại phòng đào tạo” của Hvktmm ta sẽ bỏ qua được các tên trường mà chữ cái đầu không phải là “H”.

Như vậy giữa cấu trúc dl và gt có mqh mật thiết. Có thể coi chúng như hình với bóng, không thể nói gới cái này mà không nhắc tới cái kia.

