# CSS Animation

`CSS-transition`

```
- transition-property: Khai báo những thuộc tính áp dụng transition
- transition-duration: Khai báo khoảng thời gian giữa 2 lần thay đổi diễn ra bao lâu
- transition-delay: Sau khoảng thời gian tùy chỉnh nó sẽ áp dụng thuộc tính transition-duration
- transition-timing-function: Dùng để tính toán thay đổi 1 giá trị nào đó (cubic-bezier())
```

`CSS-animation`

```
@keyframes: Nó là khái niệm chung trong khoa học máy tính
Mô tả cho từng khung hình

- animation-name: Khai báo tên animation
- animation-duration: Khai báo khoảng thời gian diễn ra animation
- animation-interation-count: Lặp lại animation bao nhiêu lần | Sử dụng vô hạn: infinite
- animation-direction: Thay đổi hướng di chuyển của animation
- animation-delay: au khoảng thời gian tùy chỉnh nó sẽ áp dụng thuộc tính animation-duration
- animation-timing-function: Dùng để tính toán thay đổi 1 giá trị nào đó (cubic-bezier())

* Khi kết thúc thuộc tính animation thì nó sẽ trả về thuộc tính ban đầu

* Nếu sử dụng % thì mỗi % là quá trình biến đổi trong khoảng thời gian animation-duration

* Nếu khai báo animation mà không khai báo giá trị nó sẽ lấy giá trị ở vị trí đầu tiên của những animation trước đó

!Lợi ích:
- Không cần thao tác, tương tác lên UI mà vẫn có thể tạo được những hiệu ứng animation
- Muốn animation này có thể lặp lại bao nhiêu lần
- Muốn khai báo 1 animation-direction để đổi hướng về hướng cũ
- Giống transition thì animation áp dụng nhiều animation khác nhau, keyframes khác nhau
```

```
Tài liệu tham khảo

- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations
- https://cubic-bezier.com/
```