# Apktool-M-translations
Tệp ngôn ngữ cho Apktool M.

Để gửi yêu cầu chỉnh sửa
1. Fork kho lưu trữ này;
2. Chỉnh sửa;
3. Commit và gửi Pull request tới nhánh main của Maximoff;

[Tài liệu GitHub](https://help.github.com/articles/using-pull-requests/ "Документация GitHub")

Vui lòng sử dụng trình dịch tích hợp sẵn của Apktool M, hoặc tự sửa thủ công các ký tự sau:
1. `<` thành `&lt;`.
2. `&` thành `&amp;`.
3. `"` thành `\"`.
3. `'` thành `\'`.
4. Ký tự `%` phải viết thành `%%`, nếu không dùng để định dạng chuỗi, hoặc thêm thuộc tính `formatted="false"` nếu muốn giữ nguyên.

Hãy xóa các chuỗi trong `strings.xml` có tên bắt đầu bằng `"abc_..."`, vì chúng không cần thiết.
Ngoài ra, các string sau không cần dịch:
```
beta
dot
rarrow
lock_icon
block_icon
clock_icon
list_icon
prev_icon
next_icon
search_menu_title
status_bar_notification_info_overflow
```
