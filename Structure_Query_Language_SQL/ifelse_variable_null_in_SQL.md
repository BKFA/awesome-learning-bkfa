# Các thành phần điều khiển (Control of flow)
Như BEGIN...END, BREAK, CONTINUE, GOTO, IF...ELSE, RETURN, WHILE...

# Chú thích (Comment)
T-SQL dùng kí hiệu -- để chú thích cho một dòng đơn và kí hiệu /*...*/ để chú thích cho
một nhóm dòng

Ví dụ:

/* Minh họa chú thích

Chú thích cho một dòng đơn và một nhóm các dòng*/

DECLARE @MyNumber int

-- khai báo biến

SET @MyNumber = 4 - 2 + 27

-- kết quả là 29

SELECT @MyNumber

# Giá trị NULL
Một cơ sở dữ liệu là sự phản ánh của một hệ thống trong thế giới thực, do đó các giá trị dữ liệu
tồn tại trong cơ sở dữ liệu có thể không xác định được. Một giá trị không xác định được xuất hiện
trong cơ sở dữ liệu có thể do một số nguyên nhân sau:
- Giá trị đó có tồn tại nhưng không biết.
- Không xác định được giá trị đó có tồn tại hay không.
- Tại một thời điểm nào đó giá trị chưa có nhưng rồi có thể sẽ có.
- Giá trị bị lỗi do tính toán (tràn số, chia cho không,...)

Những giá trị không xác định được biểu diễn trong cơ sở dữ liệu quan hệ bởi các giá trị NULL.

Đây là giá trị đặc biệt và không nên nhầm lẫn với chuỗi rỗng (đối với dữ liệu kiểu chuỗi) hay giá
trị không (đối với giá trị kiểu số). Giá trị NULL đóng một vai trò quan trọng trong các cơ sở dữ
liệu và hầu hết các hệ quản trị cơ sở dữ liệu quan hệ hiện nay đều hỗ trợ việc sử dụng giá trị này.
