### Bài tập

Cho bảng `employees` như sau:

| id | name | age | nationality |
| --- | --- | --- | --- |
| 1 | Jessica | 22 | Ireland |
| 2 | Gabriel | 48 | France |
| 3 | Laura | 36 | USA |

Bạn hãy cho biết bảng `employees` có bao nhiêu trường? (Chọn câu trả lời đúng nhất)
Đáp án: 4

* * * * *

### Lý thuyết

Một cơ sở dữ liệu thường chứa một hoặc nhiều bảng. Trong hệ thống cơ sở dữ liệu quan hệ, một bảng có thể được xem như là một quan hệ (relation).

Bảng dùng để lưu trữ các thông tin của một đối tượng trong thực tế. Mỗi bảng được xác định bằng một tên (ví dụ như `actor` hay `film`). Một bảng có các bản ghi (dòng) và các trường (cột).

1.  Bản ghi: Chứa dữ liệu cụ thể, như thông tin về một nhân viên hoặc một sản phẩm cụ thể.

2.  Trường: Chứa dữ liệu về một khía cạnh của đối tượng của bảng như tên hoặc địa chỉ email.

Lấy bảng `actor` dưới đây làm ví dụ, ta thấy bảng `actor` chứa 5 bản ghi, mỗi bản ghi sẽ lưu thông tin về một diễn viên. Cạnh đó, bảng `actor` có 4 trường là `actor_id`, `first_name`, `last_name`, `last_update`.

| actor_id | first_name | last_name | last_update |
| --- | --- | --- | --- |
| 1 | PENELOPE | GUINESS | 2006-02-15 04:34:33 |
| 2 | NICK | WAHLBERG | 2006-02-15 04:34:33 |
| 3 | ED | CHASE | 2006-02-15 04:34:33 |
| 4 | JENNIFER | DAVIS | 2006-02-15 04:34:33 |
| 5 | JOHNNY | LOLLOBRIGIDA | 2006-02-15 04:34:33 |

