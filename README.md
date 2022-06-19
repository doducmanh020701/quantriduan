# Quan-tri-du-an
Quan tri du an
 Viết hướng dẫn chạy project
 
 Bước 1. Cài đặt các phần mềm, công cụ hỗ trợ bao gồm
Xampp phiên bản php 7x . Các bạn có thể download tại đây (Link này dành cho bạn nào dùng window nhé :https://www.apachefriends.org/xampp-files/7.4.19/xampp-windows-x64-7.4.19-0-VC15-installer.exe)
Visualstudio các bạn download tại đây :https://code.visualstudio.com/

Bước 2. Cấu hình biến môi trường cho php
Vì sao phải cấu hình biến môi trường, thực ra mình hay sử dụng lệnh, và run server ảo nên mình mới cần tạo biến môi trường. Đối với việc tạo biến môi trường thì mỗi bản window đều có cách tạo khác nhau nên các bạn đang dùng win bao nhiêu thì các bạn search ntn nhé
Tạo biến môi trường php cho win 7
Tạo biến môi trường php cho win 8 
......
Và các bạn làm theo hướng dẫn của họ nhé. Vì có khá là nhiều bài hướng dẫn rồi nên mình ko hướng dẫn lại nữa
Sau khi bạn cài đặt biến môi trường xong bạn mở teminal hoạc git lên chạy lệnh php -v  và hiện thị kết quả như ảnh sau thì là thành công nhé
![image](https://user-images.githubusercontent.com/104112030/174473654-47ac75dc-0271-428f-b027-7ef7c7e814b4.png)

Bước 3. Các bạn download source mình gủi và đưa vào htdocs và giải nén nhé.
Bước này các bạn chú ý là khi giải nén thì các bạn làm như sau
Click phải chuột vào thư mục cần giải nén, chọn Extract here để tập tin sau khi giải nén sẽ ở ngay vị trí hiện tại của thư mục nén.

Bước 4. Cập nhật thay đổi thông tin kết nối CSDL
Mình sẽ giải thích 1 số thông tin và 1 số thông tin cần đổi lại như sau
127.0.0.1 các bạn dữ nguyên nhé
root => root thứ nhất là user đăng nhập phpmyadmin của bạn
root => root thứ 2 là mật khẩu, thông thường window ko có mật khẩu thì các bạn xoá nó đi
Nếu bạn có mật khẩu cho phpmyadmin thì các bạn thay vào nhé
Và cuối cùng 8888 là port

Bước 5. Chạy project
Sau khi hoàn thành các bước trên bạn mở teminal như lúc chạy php -S ấy. sau đó bạn đánh php -S localhost:8000 và lên trình duyệt gõ

http://localhost:8000 để xem kết quả nhé.
