# K-Means-xử lí ảnh

**Unit này sẽ dùng thuật toán Kmeans để xử lý ảnh, bạn có thể làm với bất cứ bức ảnh nào. 
Thuật toán sẽ tìm ra 1 số mầu phổ biến nhất của bức ảnh và thay thế ảnh gốc với ảnh mới gồm K số màu đó. 
Về cơ bản, ảnh gồm nhiều pixels, mỗi pixels và 1 vector trong không gian 3 chiều.
Sau đó dùng K-Means với đống vector trong không gian 3 chiều này như ở Unit trước.

Bài 3: Chạy Kmeans với từng pixel của ảnh.

Bài 4: Hiển thị ảnh mới bằng numpy.
 Nếu để số k cao như khoảng 16-24, bạn sẽ thu được 1 bức ảnh mới có cùng độ phân giải với ảnh gốc nhưng sẽ ít mầu hơn, nhìn sẽ gần giống, ảnh mới sẽ nhẹ hơn ảnh cũ khoảng 10 lần mà chất lượng khá giống nhau.
Đây cũng là 1 cách để nén/làm nhẹ một bức ảnh.

Bài 5: Tự reshape ma trận bằng tay, không dùng thư viện.
 

