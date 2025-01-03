<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danh mục Bài Viết</title>
    <style>
         .post-list {
        list-style: none;
        padding: 0;
    }
    .post-item {
        display: flex;
        align-items: flex-start;
        margin-bottom: 30px; /* Tăng khoảng cách giữa các mục */
        border: 1px solid #ddd;
        border-radius: 8px;
        overflow: hidden;
        padding: 10px; /* Thêm khoảng cách bên trong */
    }
    .post-item img {
        width: 180px; /* Tăng kích thước ảnh */
        height: 120px;
        object-fit: cover;
        margin-right: 20px; /* Thêm khoảng cách giữa ảnh và nội dung */
    }
    .post-content {
        padding: 10px;
    }
    .post-content a {
        font-size: 22px; /* Tăng kích thước chữ tiêu đề */
        font-weight: bold;
        color: #007bff;
        text-decoration: none;
    }
    .post-content a:hover {
        text-decoration: underline;
    }
    .post-content p {
        margin: 10px 0 0; /* Tăng khoảng cách giữa đoạn văn */
        color: #555;
        font-size: 18px; /* Tăng kích thước chữ mô tả */
    }
    </style>
</head>
<body>
    <h1>Danh mục Bài Viết</h1>
    <ul class="post-list">
        <li class="post-item">
            <img src="/img/java-topic-advanced.png" alt="Java Cơ Bản">
            <div class="post-content">
                <a href="/blog/javacoban/huong-dan-java">Java Cơ Bản</a>
                <p>Hướng dẫn cơ bản về ngôn ngữ Java dành cho người mới bắt đầu.</p>
            </div>
        </li>
        <li class="post-item">
            <img src="/img/javascript1.jpg" alt="JavaScript Cơ Bản">
            <div class="post-content">
                <a href="/blog/javascriptcoban/huong-dan-javascript">JavaScript Cơ Bản</a>
                <p>Khám phá JavaScript cơ bản và cách sử dụng nó trong phát triển web.</p>
            </div>
        </li>
        <li class="post-item">
            <img src="/img/java1.jpg" alt="Giới thiệu về Java">
            <div class="post-content">
                <a href="/blog/gioithieujava/gioi-thieu-java">Giới thiệu về Java</a>
                <p>Lịch sử và ứng dụng của Java trong các lĩnh vực lập trình.</p>
            </div>
        </li>
        <li class="post-item">
            <img src="/img/java-topic-advanced.png" alt="Giới thiệu về JavaScript">
            <div class="post-content">
                <a href="/blog/gioithieujavascript/gioi-thieu-javascript">Giới thiệu về JavaScript</a>
                <p>Những điều bạn cần biết về ngôn ngữ JavaScript.</p>
            </div>
        </li>
         <li class="post-item">
            <img src="/img/game.jpg" alt="Giới thiệu hướng dẫn lập trình java game">
            <div class="post-content">
                <a href="/blog/huongdanlaptrinhgamejava/game">Giới thiệu về lập trình java game</a>
                <p>Những điều bạn cần biết khi lập trình bằng java.</p>
            </div>
        </li>
         <li class="post-item">
            <img src="/img/dom.jpg" alt="Giới thiệu về Dom">
            <div class="post-content">
                <a href="/blog/javacriptdom/dom">Giới thiệu về Dom</a>
                <p>Những điều bạn cần biết về dom của javascript.</p>
            </div>
        </li>
         <li class="post-item">
            <img src="/img/async.jpg" alt="Giới thiệu về JavaScript">
            <div class="post-content">
                <a href="/blog/JavaScriptAsyncandPromise/asyncandpromise">Giới thiệu về Javascript Async và Promise</a>
                <p>Những điều bạn cần biết về async và promise.</p>
            </div>
        </li>
         <li class="post-item">
            <img src="/img/oop.jpg" alt="Giới thiệu về Java và OOP">
            <div class="post-content">
                <a href="/blog/JavavaOOP/JavavaOOP">Giới thiệu về Java và OOP</a>
                <p>Những điều bạn cần biết về lập trình hướng đối tượng.</p>
            </div>
        </li>
         <li class="post-item">
            <img src="/img/java-topic-advanced.png" alt="Giới thiệu về Java nâng cao">
            <div class="post-content">
                <a href="/blog/javanangcao/java-nang-cao">Giới thiệu về Java nâng cao</a>
                <p>Những điều bạn cần biết về Java nâng cao.</p>
            </div>
        </li>
    </ul>
</body>
</html>
