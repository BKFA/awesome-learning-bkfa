# SQL là gì
## SQL là ngôn ngữ của cơ sở dữ liệu quan hệ

SQL, viết tắt của Structured Query Language (ngôn ngữ hỏi có cấu trúc), là công cụ sử dụng để tổ chức, 
quản lý và truy xuất dữ liệu đuợc lưu trữ trong các cơ sở dữ liệu. 
SQL là một hệ thống ngôn ngữ bao gồm tập các câu lệnh sử dụng để tương tác với cơ sở dữ liệu quan hệ.
Khả năng của SQL vượt xa so với một công cụ truy xuất dữ liệu, mặc dù đây là mục đích ban đầu
khi SQL được xây dựng nên và truy xuấ t dữ liệu vẫn còn là một trong những chức năng quan
trọng của nó. 

SQL được sử dụng để điều khiển tất cả các chức năng mà một hệ quản trị cơ sở dữ
liệu cung cấp cho người dùng bao gồm:
* **Định nghĩa dữ liệu**: SQL cung cấp khả năng định nghĩa các cơ sở d ữ liệu, các cấu trúc lưu trữ
và tổ chức dữ liệu cũng như mối quan hệ giữa các thành phần dữ liệu.
* **Truy xuất và thao tác dữ liệu**: Với SQL, người dùng có thể dễ dàng thực hiện các thao
tác truy xuất, bổ sung, cập nhật và loại bỏ dữ liệu trong các cơ sở dữ liệu.
* **Điều khiển truy cập**: SQL có thể được sử dụng để cấp phát và kiểm soát các thao tác của người
sử dụng trên dữ liệu, đảm bảo sự an toàn cho cơ sở dữ liệu
* **Đảm bảo toàn vẹn dữ liệu**: SQL định nghĩa các ràng buộc toàn vẹn trong cơ sở dữ liệu nhờ đó
đảm bảo tính hợp lệ và chính xác của dữ liệu trước các thao tác cập nhật cũng như các lỗi của hệ
thống.

Như vậy, có thể nói rằng SQL là một ngôn ngữ hoàn thiện được sử dụng trong các hệ thống cơ
sở dữ liệu và là một thành phần không thể thiếu trong các hệ quản trị cơ sở dữ liệu. Mặc dù SQL
không phải là một ngôn ngữ lập trình như C, C++, Java,... song các câu lệnh mà SQL cung cấp có
thể được nhúng vào trong các ngôn ngữ lập trình nhằm xây dựng các ứng dụng tương tác với cơ
sở dữ liệu.

Khác với các ngôn ngữ lập trình quen thuộc như C, C++, Java,... SQL là ngôn ngữ có tính khai
báo. Với SQL, người dùng chỉ cần mô tả các yêu cầu cần phải thực hiện trên cơ sở dữ liệu mà
không cần phải chỉ ra cách thức thực hiện các yêu cầu như thế nào. Chính vì vậy, SQL là ngôn
ngữ dễ tiếp cận và dễ sử dụng.

## Vai trò của SQL

Bản thân SQL không phải là một hệ quản trị cơ sở dữ liệu, nó không thể tồn tại độc lập. SQL
thực sự là một phần của hệ quản trị cơ sở dữ liệu, nó xuất hiện trong các hệ quản trị cơ sở dữ liệu
với vai trò ngôn ngữ và là công cụ giao tiếp giữa người sử dụng và hệ quản trị cơ sở dữ liệu.

Trong hầu hết các hệ quản trị cơ sở dữ liệu quan hệ, SQL có những vai trò như sau:
* **SQL là ngôn ngữ hỏi có tính tương tác**: Người sử dụng có thể dễ dàng thông qua các
trình tiện ích để gửi các yêu cầu dưới dạng các câu lệnh SQL đến cơ sở dữ liệu và nhận kết quả trả về từ cơ sở dữ liệu
* **SQL là ngôn ngữ lập trình cơ sở dữ liệu**: Các lập trình viên có thể nhúng các câu lệnh SQL 
vào trong các ngôn ngữ lập trình để xây dựng nên các chương trình ứng dụng giao tiếp với cơ sở dữ liệu
SQL là ngôn ngữ quản tr ị cơ sở dữ liệu: Thông qua SQL, người quản trị cơ sở dữ liệu có thể
quản lý được cơ sở dữ liệu, định nghĩa các cấu trúc lưu trữ dữ liệu, điều khiển truy cập cơ sở dữ
liệu,...
* **SQL là ngôn ngữ cho các hệ thống khách/chủ (client/server)**: Trong các hệ thống cơ sở dữ liệu
khách/chủ, SQL được sử dụng như là công cụ để giao tiếp giữa các trình ứng dụng phía máy
khách với máy chủ cơ sở dữ liệu.
* **SQL là ngôn ngữ truy cập dữ liệu trên Internet**: Cho đến nay, hầu hết các máy chủ Web cũng
như các máy chủ trên Internet sử dụng SQL với vai trò là ngôn ngữ để tương tác với dữ liệu
trong các cơ sở dữ liệu.
* **SQL là ngôn ngữ cơ sở dữ liệu phân tán**: Đối v ới các hệ quản trị cơ sở dữ liệu phân tán, mỗi
một hệ thống sử dụng SQL để giao tiếp với các hệ thống khác trên mạng, gởi và nhận các yêu cầu
truy xuất dữ liệu với nhau.
* **SQL là ngôn ngữ sử dụng cho các cổng giao tiếp cơ sở dữ liệu**: Trong một hệ thống mạng máy
tính với nhiều hệ quản trị cơ sở dữ liệu khác nhau, SQL thường được sử dụng như là một chuẩn
ngôn ngữ để giao tiếp giữa các hệ quản trị cơ sở dữ liệu.
