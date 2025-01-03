---
date : '2024-12-27T12:32:54+07:00'
---

# Giới thiệu về OOP trong Java:
Lập trình hướng đối tượng (OOP) là một phương pháp lập trình dựa trên việc sử dụng các đối tượng và lớp để tổ chức mã nguồn. Java là một ngôn ngữ lập trình hướng đối tượng hoàn toàn, điều này có nghĩa là mọi thứ trong Java đều là một đối tượng, và mỗi đối tượng được tạo ra từ các lớp.

# Các nguyên lý cơ bản của OOP:
1. Encapsulation (Đóng Gói)
Đóng gói là việc ẩn giấu thông tin chi tiết của một lớp và chỉ cung cấp các phương thức công khai (public) để tương tác với dữ liệu của lớp đó.
Điều này giúp bảo vệ dữ liệu khỏi bị truy cập trái phép hoặc thay đổi ngoài ý muốn.
Ví dụ: Sử dụng các phương thức get và set để truy xuất hoặc thay đổi giá trị của thuộc tính trong một lớp.
```java
class Student {
    private String name;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }
} 
```
Inheritance (Kế thừa): Cho phép một lớp kế thừa các thuộc tính và phương thức từ lớp cha, giúp tái sử dụng mã nguồn và giảm thiểu sự trùng lặp.

```java
class Animal {
    public void eat() {
        System.out.println("This animal eats food.");
    }
}

class Cat extends Animal {
    public void meow() {
        System.out.println("The cat meows.");
    }
}
```
Polymorphism (Đa hình): Cho phép các đối tượng của các lớp khác nhau có thể được xử lý thông qua cùng một phương thức hoặc lớp cơ sở.
```java
class Shape {
    public void draw() {
        System.out.println("Drawing a shape");
    }
}

class Circle extends Shape {
    @Override
    public void draw() {
        System.out.println("Drawing a circle");
    }
}

class Main {
    public static void main(String[] args) {
        Shape shape = new Circle();
        shape.draw();  // Outputs: Drawing a circle
    }
}
```
Abstraction (Trừu tượng): 
Trừu tượng là việc che giấu các chi tiết triển khai cụ thể và chỉ cung cấp giao diện bên ngoài để người dùng tương tác.
Java cung cấp hai cách để đạt được tính trừu tượng:
Abstract Class: Lớp trừu tượng có thể chứa các phương thức không được triển khai.
Interface: Giao diện chứa các phương thức trừu tượng hoàn toàn.
```
abstract class Animal {
    abstract void makeSound();

    public void eat() {
        System.out.println("This animal eats food.");
    }
}

class Dog extends Animal {
    @Override
    void makeSound() {
        System.out.println("Dog barks");
    }
}
```
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
# Lợi Ích Của OOP

- **Tái sử dụng mã nguồn**: Kế thừa giúp giảm sự trùng lặp và dễ dàng tái sử dụng mã.
- **Dễ duy trì và nâng cấp**: Các lớp độc lập và đóng gói giúp quản lý dự án lớn hiệu quả hơn.
- **Tăng tính bảo mật**: Encapsulation bảo vệ dữ liệu, kiểm soát cách truy cập và sửa đổi.
- **Tính linh hoạt cao**: Polymorphism cho phép xử lý các đối tượng một cách thống nhất.