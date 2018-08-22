# Cú pháp của T-SQL
Các đối tượng trong cơ sở dữ liệu dựa trên SQL (table, view, index, stored procedure…) được xác
định thông qua tên của đối tượng (hay còn gọi là identifier). Tên của các đối tượng là duy nhất
trong mỗi cơ sở dữ liệu. Tên được sử dụng nhiều nhất trong các truy vấn SQL và được xem là
nền tảng trong cơ sở dữ liệu quan hệ là tên bảng và tên cột.

Có hai loại identifiers một loại thông thường (Regular Identifier) và một loại gọi là Delimited
Identifier, loại này cần có dấu "" hay dấu [] để ngăn cách. Loại Delimited được dùng đối với các
chữ trùng với từ khóa của SQL Server (reserved keyword) hay các chữ có khoảng trống.

Ví dụ:

`
Select *
From "My table"
Where [sum] = 10
`

Trong các cơ sở dữ li ệu lớn với nhiều người sử dụng, khi ta chỉ định tên của một bảng nào đó
trong câu lệnh SQL, hệ quản trị cơ sở dữ liệu hiểu đó là tên của bảng do ta sở hữu (tức là bảng do
ta tạo ra). Thông thường, trong các hệ quản trị cơ sở dữ liệu này cho phép những người dùng khác
nhau tạo ra những bảng trùng tên với nhau mà không gây ra xung đột về tên. Nếu trong một câu
lệnh SQL ta cầ n chỉ đến một bảng do một người dùng khác sở hữu (hiển nhiên là phải được phép)
thì tên của bảng phải được viết sau tên của người sở hữu và phân cách với tên người sở hữu bởi
dấu chấm:

tên_người_sở_hữu.tên_bảng

Một số đối tượng cơ sở dữ liệu khác (như khung nhìn, thủ tục, hàm), việc sử dụng tên cũng tương
tự như đối với bảng.

Ta có thể sử dụng tên cột một cách bình thường trong các câu lệnh SQL bằng cách chỉ
cần chỉ định tên của cột trong bảng. Tuy nhiên, nếu trong câu lệnh có liên quan đến hai cột trở
lên có cùng tên trong các bảng khác nhau thì bắt buộc phải chỉ định thêm tên bảng trước tên
cột; tên bảng và tên cột được phân cách nhau bởi dấu chấm

Ví dụ: Giả sử chúng ta có CSDL như sau:

Để tìm ra thông tin cầu thủ đá cho câu lạc bộ nào, ở vị trí nào, câu truy vấn như
sau:

`
select HOTEN,VITRI,TENCLB
from CAUTHU,CAULACBO
where (CAUTHU.MACLB=CAULACBO.MACLB)and (HOTEN = N'Nguyễn Công Vinh')`
