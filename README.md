# DBMS-Database-Management-System-
## DBMS (Database Management System) "hệ thống quản lý cơ sở dữ liệu (DBMS)" <br>
**SQL (Structured Query Language)** và **NoSQL (Not Only SQL)** là hai loại hệ thống quản lý cơ sở dữ liệu **(DBMS)** phổ biến, mỗi loại có những đặc điểm và ưu điểm riêng biệt: <br><br>

### SQL (Relational Database Management Systems - RDBMS)   <br><br>

**1.Cấu trúc Dữ liệu:** Sử dụng các bảng có cấu trúc cố định với **hàng và cột**. Mỗi bảng thường tương ứng với một loại đối tượng và mối quan hệ giữa các đối tượng được định nghĩa thông qua các **khóa ngoại.** <br><br>

**2.Ngôn ngữ Truy vấn:** **SQL**, một ngôn ngữ truy vấn mạnh mẽ và chuẩn hóa, cho phép thực hiện các truy vấn phức tạp. <br><br>

**3.Tính nhất quán**: Mạnh về tính nhất quán **(ACID - Atomicity, Consistency, Isolation, Durability)** trong giao dịch. <br><br>

**4.Mô hình:** Thích hợp cho mô hình dữ liệu có cấu trúc và không thay đổi thường xuyên. <br><br>

**Ví dụ: MySQL, PostgreSQL, Oracle, SQL Server.** <br><br>

Đây là công cụ chính cho việc tương tác với dữ liệu quan hệ, cho phép người dùng thực hiện các thao tác như: <br><br>
![image](https://github.com/Experimenters1/DBMS-Database-Management-System-/assets/64000769/cfbfdc53-f966-4b0b-bfc2-2309412f16c3) <br><br>

### NoSQL (Non-Relational or Distributed Database System)  <br><br>

**1.Cấu trúc Dữ liệu:** Linh hoạt, không có cấu trúc cố định. Có thể lưu trữ dữ liệu dưới dạng **key-value, document, wide-column, hoặc graph.** <br><br>
     +) **Cơ sở dữ liệu cặp khóa-giá trị (Key-Value Stores)**: Lưu trữ dữ liệu dưới dạng cặp **khóa-giá trị**, rất đơn giản và nhanh chóng trong việc truy xuất. **Ví dụ: Redis, DynamoDB.** <br><br>
     +) **Cơ sở dữ liệu tài liệu (Document-Oriented Databases):** Dữ liệu được lưu trữ dưới dạng tài liệu **(documents)**, thường là ở định dạng **JSON, BSON, hoặc XML. Ví dụ: MongoDB, CouchDB.** <br><br>
     +) **Cơ sở dữ liệu cột (Column-Family Stores):** Tối ưu cho việc lưu trữ và truy vấn lượng lớn dữ liệu. Dữ liệu được tổ chức theo cột thay vì theo hàng. **Ví dụ: Cassandra, HBase.** <br><br>
     +) **Cơ sở dữ liệu đồ thị (Graph Databases):** Dùng để lưu trữ thông tin dưới dạng các đồ thị, với các nút, cạnh, và thuộc tính, rất hiệu quả cho việc biểu diễn mối quan hệ phức tạp. **Ví dụ: Neo4j, Amazon Neptune.** <br><br>
**2.Ngôn ngữ Truy vấn:** Không có chuẩn chung; mỗi hệ thống NoSQL có thể sử dụng ngôn ngữ truy vấn riêng.<br><br>

**3.Tính nhất quán:** Hỗ trợ mô hình nhất quán cuối cùng **(eventual consistency)** và có thể tối ưu hóa cho việc đọc và ghi dữ liệu lớn. <br><br>

**4.Mô hình:** Thích hợp cho dữ liệu có cấu trúc động, phân tán và cần quy mô lớn. <br><br>

**Ví dụ: MongoDB, Cassandra, Redis, Neo4j.** <br><br>

### So sánh Chính <br><br>

**1.Cấu trúc:** **SQL** sử dụng cấu trúc cố định **(schematics)**, trong khi **NoSQL** linh hoạt hơn về cấu trúc dữ liệu. <br><br>

**2.Quy mô:** **NoSQL** thường tốt hơn trong việc xử lý dữ liệu lớn và phân tán. <br><br>

**3.Tính nhất quán:** **SQL** mạnh mẽ hơn về tính nhất quán và tính toàn vẹn dữ liệu. <br><br>

**4.Truy vấn:** **SQL** hỗ trợ truy vấn phức tạp, còn **NoSQL** thì đơn giản hơn nhưng ít mạnh mẽ. <br><br>


Lựa chọn giữa **SQL và NoSQL** phụ thuộc vào yêu cầu cụ thể của dự án, bao gồm cấu trúc dữ liệu, quy mô, tính nhất quán, và tính phức tạp của các truy vấn.  <br><br>
