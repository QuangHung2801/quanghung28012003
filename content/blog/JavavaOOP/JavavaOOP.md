---
date : '2024-12-27T12:32:54+07:00'
title : 'JavavaOOP'
---

Giới thiệu về OOP trong Java:
Lập trình hướng đối tượng (OOP) là một phương pháp lập trình dựa trên việc sử dụng các đối tượng và lớp để tổ chức mã nguồn. Java là một ngôn ngữ lập trình hướng đối tượng hoàn toàn, điều này có nghĩa là mọi thứ trong Java đều là một đối tượng, và mỗi đối tượng được tạo ra từ các lớp.

Các nguyên lý cơ bản của OOP:
Encapsulation (Đóng gói): Là việc ẩn giấu thông tin bên trong một lớp và chỉ cung cấp các phương thức để tương tác với dữ liệu của lớp đó. Điều này giúp bảo vệ dữ liệu khỏi các thay đổi ngoài ý muốn.
Inheritance (Kế thừa): Cho phép một lớp kế thừa các thuộc tính và phương thức từ lớp cha, giúp tái sử dụng mã nguồn và giảm thiểu sự trùng lặp.
Polymorphism (Đa hình): Cho phép các đối tượng của các lớp khác nhau có thể được xử lý thông qua cùng một phương thức hoặc lớp cơ sở.
Abstraction (Trừu tượng): Là việc che giấu các chi tiết triển khai và chỉ cung cấp các giao diện cần thiết để sử dụng.
Ví dụ mã nguồn đơn giản:
```java
class Animal {
    public void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    @Override
    public void sound() {
        System.out.println("Dog barks");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal animal = new Animal();
        animal.sound();
        
        Animal dog = new Dog();
        dog.sound();  // Outputs: Dog barks
    }
}
```
