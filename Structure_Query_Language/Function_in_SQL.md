# Hàm (Function)
Có 2 loạ i hàm: một loại là được xây dựng sẵn trong SQL Server 2005 Edition (built-in) và một
loại do người dùng tự định nghĩa (user-defined) Các hàm Built-In được chia làm 3 nhóm:

**Rowset Functions**: Loại này thường trả về một object và được đối xử như một table. Ví dụ như
hàm OPENQUERY sẽ trả về một recordset và có thể đứng vị trí của một table trong câu lệnh
Select.

**Aggregate Functions**: Loại này làm việ c trên một số giá trị và trả về một giá tr ị đơn hay là các
giá trị tổng. Ví dụ như hàm AVG sẽ trả về giá trị trung bình của một cột.

**Scalar Functions**: Loại này làm việc trên một giá trị đơn và trả về một giá trị đơn. Trong loại
này lại chia làm nhiều  loại nhỏ như các hàm về toán học, về thời gian, xử lý kiểu dữ liệu
String....Ví dụ như hàm MONTH('2002-09-30') sẽ trả về tháng 9.

**Các hàm User-Defined** (được tạo ra bởi câu lệnh CREATE FUNCTION và phần body thường
được gói trong cặp lệnh BEGIN...END) cũng được chia làm các nhóm như sau:

Scalar Functions: Loại này cũng trả về một giá trị đơn bằng câu lệnh RETURNS.

Table Functions : Loại này trả về một table
