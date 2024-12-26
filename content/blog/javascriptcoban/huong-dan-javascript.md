---
title: "Hướng Dẫn JavaScript Cơ Bản"
date: 2024-12-25
---
JavaScript là ngôn ngữ lập trình phổ biến trên web, dùng để tạo các trang web tương tác. Bài viết này sẽ hướng dẫn bạn các khái niệm cơ bản về JavaScript cùng với ví dụ minh họa.

1. Khai báo biến
Trong JavaScript, bạn có thể khai báo biến bằng var, let, hoặc const.

```javascript
// Sử dụng var (ít dùng trong ES6 trở đi)
var x = 10;

// Sử dụng let (dùng khi giá trị biến có thể thay đổi)
let y = 20;

// Sử dụng const (dùng cho giá trị không thay đổi)
const z = 30;

console.log(x, y, z);
``` // Kết quả: 10 20 30
2. Câu lệnh điều kiện
Câu lệnh điều kiện (if, else if, else) giúp kiểm tra điều kiện và thực hiện hành động tương ứng.

```javascript
let age = 18;

if (age < 18) {
  console.log("Bạn chưa đủ tuổi.");
} else if (age === 18) {
  console.log("Chúc mừng bạn vừa đủ tuổi!");
} else {
  console.log("Bạn đã đủ tuổi.");
}
```
3. Vòng lặp
Vòng lặp dùng để thực hiện một hành động nhiều lần.

Ví dụ vòng lặp for:

```javascript
for (let i = 1; i <= 5; i++) {
  console.log("Số: " + i);
}
// Kết quả: 1, 2, 3, 4, 5
Ví dụ vòng lặp while:

javascript
Sao chép mã
let i = 1;
while (i <= 5) {
  console.log("Số: " + i);
  i++;
}
```
4. Hàm (Functions)
Hàm là khối mã thực hiện một nhiệm vụ cụ thể.

Khai báo hàm:

```javascript
function greet(name) {
  return "Xin chào, " + name + "!";
}

console.log(greet("Hùng")); // Kết quả: Xin chào, Hùng!
Hàm mũi tên (Arrow Function):

javascript
Sao chép mã
const add = (a, b) => a + b;
console.log(add(5, 10)); // Kết quả: 15
```
5. Mảng (Arrays)
Mảng là danh sách các giá trị.

Khai báo và sử dụng mảng:

```javascript
let fruits = ["Táo", "Chuối", "Cam"];

console.log(fruits[0]); // Kết quả: Táo

fruits.push("Xoài"); // Thêm phần tử vào cuối
console.log(fruits); // Kết quả: ["Táo", "Chuối", "Cam", "Xoài"]
```