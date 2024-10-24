- IDOR ( Insecure Direct Object Reference ) là lỗ hổng xảy ra khi chương trình cho phép người dùng truy cập tài nguyên (dữ liệu, file, thư mục, database,..).
- Ví dụ, khi đăng nhập vào tài khoản sinh viên của mình, URL sẽ trông như này

  ```
  https://abcuniversity.example/GetStudentRecords?ID=00123456789
  ```

  Nhưng khi thay ID của mình thành một ID của học sinh khác mà vẫn truy cập, đó là một lỗ hổng IDOR

- Có 4 loại IDOR phổ biến
  - Khóa database
  - Tham số truy vấn
  - ID người dùng hoặc phiên
  - Tên 
