---
date : '2024-12-27T12:30:21+07:00'
title : 'Dom'
---

Giới thiệu về DOM:
DOM (Document Object Model) là một mô hình đối tượng đại diện cho cấu trúc của một tài liệu HTML hoặc XML. Mỗi phần tử trong tài liệu (như thẻ <div>, <p>, hoặc các thuộc tính HTML) là một đối tượng trong DOM.

Thông qua DOM, JavaScript có thể truy xuất và thao tác với nội dung của tài liệu web. DOM cho phép bạn thay đổi, thêm, xóa các phần tử và nội dung của trang web một cách động.

Cấu trúc DOM:
Mỗi tài liệu HTML là một cây DOM, trong đó:

Các thẻ HTML trở thành các đối tượng trong cây.
Các thuộc tính của thẻ trở thành các thuộc tính của các đối tượng đó.
Nội dung văn bản trở thành các nút văn bản trong cây.
Ví dụ thao tác với DOM:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>DOM Example</title>
</head>
<body>
    <h1 id="heading">Hello, World!</h1>
    <button onclick="changeText()">Change Text</button>

    <script>
        function changeText() {
            document.getElementById("heading").innerHTML = "Text changed!";
        }
    </script>
</body>
</html>
```