### Bài tập

Trong cơ sở dữ liệu, chúng ta có bảng `film` chứa thông tin về các bộ phim. Bảng gồm có 4 trường là `film_id`, `title`, `release_year`, `length`.

Hãy xem đoạn code SQL ở bên màn hình bên phải, nhấn `Chạy thử` để kiểm tra các lỗi ở cuối mỗi Test case, sau đó hãy sửa chúng theo lỗi đã báo.

Giới hạn thời gian thực thi:  2 giây  (PosgreSQL)

* * * * *

### Lý thuyết

Nếu bạn chạy thử đoạn code ở màn hình bên phải, bạn sẽ gặp lỗi.

Lúc này, lỗi SQL sẽ được hiển thị ở dưới cùng mỗi testcase. Bạn sẽ thấy:

ERROR: relation "this_is_a_table_name" does not exist

Đoạn này sẽ cho bạn biết vấn đề bạn gặp phải trong phần code SQL của mình (bằng tiếng Anh). Ở trường hợp trên, đoạn code báo lỗi là "Không tồn tại quan hệ (bạn có thể hiểu đơn giản quan hệ chính là bảng) có tên là `this_is_a_table_name`. Để sửa nó, bạn cần thay đổi tên của mối quan hệ là `film`. Bởi vì hiện tại chúng ta chỉ có một quan hệ là `film` trong cơ sở dữ liệu.

Trong quá trình làm bài tập, ắt hẳn chúng ta sẽ không tránh khỏi việc gặp lỗi, hãy tận dụng những thông báo ERROR này nhiều nhất có thể bạn nhé!