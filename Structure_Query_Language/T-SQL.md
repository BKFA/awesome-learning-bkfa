# Giới thiệu sơ lược về Transact SQL (T-SQL)
Transact-SQL  là ngôn ngữ SQL mở rộng dựa trên SQL chuẩn của ISO (International
Organization for Standardization) và ANSI (American National Standards Institute) được sử
dụng trong SQL Server khác với P-SQL (Procedural-SQL) dùng trong Oracle.

SQL chuẩn bao gồm khoảng 40 câu lệnh. Trong các hệ quản trị cơ sở dữ liệu khác nhau, mặc dù
các câu lệnh đều có cùng dạng và cùng mục đích sử dụng song mỗi một hệ quản trị cơ sở dữ liệu
có thể có một số thay đổi nào đó. Điều này đôi khi dẫn đến cú pháp chi tiết của các câu lệnh có
thể sẽ khác nhau trong các hệ quản trị cơ cơ sở dữ liệu khác nhau.

T-SQL được chia làm 3 nhóm:
* **Ngôn ngữ định nghĩa dữ liệu** (Data Definition Language – DDL)

  Đây là những lệnh dùng để tạo (create), thay đổi (alter) hay xóa (drop) các đối tượng
trong CSDL. Các câu lệnh DDL thường có dạng:

  **Create object**

  **Alter object**

  **Drop object**

  Trong đó object có thể là: table, view, storedprocedure, function, trigger…

* **Ngôn ngữ điều khiển dữ liệu** (Data control language – DCL)
  Đây là các lệnh quản lý quyền truy cậ p lên các object (table, view, storedprocedure…). Bao
gồm:

  **Grant**
  
  **Deny**
  
  **Revoke**

* **Ngôn ngữ thao tác dữ liệu** (Data manipulation language – DML)
  Đây là các lệ nh phổ biến dùng để xử lý dữ liệu. Bao gồm:

  **Select**

  **Insert**

  **Update**

  **Delete**
