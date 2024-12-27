---
date : '2024-12-27T12:31:50+07:00'
title : 'Asyncandpromise'
---

Giới thiệu về Async và Promise:
Trong JavaScript, các phép toán bất đồng bộ (asynchronous operations) là những phép toán không chặn chương trình trong khi chờ kết quả. Các phép toán này bao gồm việc truy vấn cơ sở dữ liệu, đọc tệp, hoặc gửi yêu cầu HTTP.

Promise là một đối tượng đại diện cho giá trị chưa được trả về, và nó có thể được hoàn thành hoặc bị từ chối.
Async/Await là cú pháp mới trong JavaScript giúp làm cho mã bất đồng bộ trở nên dễ đọc và dễ bảo trì hơn.
Promise:
Promise có 3 trạng thái:

Pending: Chưa có kết quả, vẫn đang xử lý.
Resolved (fulfilled): Thành công, kết quả đã có.
Rejected: Xảy ra lỗi.
```javascript
let promise = new Promise((resolve, reject) => {
    let success = true;
    if (success) {
        resolve("Operation successful");
    } else {
        reject("Operation failed");
    }
});

promise.then(result => {
    console.log(result); // Outputs: Operation successful
}).catch(error => {
    console.log(error); // Outputs: Operation failed
});
```
Async/Await:
Async giúp khai báo một hàm bất đồng bộ, và Await được dùng trong các hàm Async để dừng và đợi kết quả trả về.

```javascript
async function fetchData() {
    let response = await fetch('https://api.example.com');
    let data = await response.json();
    console.log(data);
}

fetchData();
```