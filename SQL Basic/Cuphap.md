# Cú pháp----------------------------------------[Mục lục](https://github.com/Zenfection/SQL)

## 1. ![icons8-table.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/09-23-47-06-icons8-table.png) Database Tables

`Database` thường chứa một hoặc nhiều `tables`. Mỗi `tables` xác định bởi `name`. `Tables` chứa hồ sơ (*cột*) với `data`.

**Ví dụ**: Dưới đây là một `table` về **Customers** : 

| CustomersID | CustomerName            | Andress     | Sex    |
| ----------- | ----------------------- | ----------- | ------ |
| 1           | Lê Tuấn Kiệt            | 3/2 Cần thơ | Male   |
| 2           | Nguyễn Huỳnh Thanh Trúc | Long Xuyên  | Female |
| 3           | Nguyễn Khoa             | Long Xuyên  | Male   |
| 4           | Zenfection              | An Giang    | Male   |
| 5           | Taurus                  | Sài Gòn     | Female |

> Đây là bảng chứa cột 5 `Customers` và 4 hàng (`CustomerID`,`CustomerName`,`Andress`,`Sex`)

---

## 2. Câu lệnh SQL

Hầu hết các hành động trên `Database` bạn đều dùng các câu lệnh `SQL`  như sau : 

```sql
SELECT * FROM Customers;
```

> ⚠️ `SQL` không phân biệt hoa thường ==> `SELECT` và `select` là tương đương ==> Tuy nhiên khuyết khích viết **IN HOA**
> 
> ⚠️ Sử dụng dấu `;` để phân cách một câu lệnh

Một số lệnh quan trọng nhất trong `SQL` : 

| Lệnh                            | Mô tả                                         |
| ------------------------------- | --------------------------------------------- |
| SELECT                          | trích xuất dữ liệu từ `database`              |
| UPDATE                          | cập nhật dữ liệu trong `database`             |
| DELETE                          | xoá dữ liệu từ một `database`                 |
| INSERT INTO                     | thêm một dữ liệu vào `database`               |
| CREATE DATABASE<br>CREATE TABLE | tạo một `database` mới<br>tạo một `table` mới |
| ALTER DATABASE<br>ALTER TABLE   | sửa đổi `database`<br>sửa đổi `table`         |
| DROP TABLE                      | Xoá một `table`                               |
| CREATE INDEX                    | Tạo một chỉ mục (*từ khoá tìm kiếm*)          |
| DROP INDEX                      | Xoá một chỉ mục                               |
