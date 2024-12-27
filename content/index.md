<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Giới thiệu về bản thân và kinh nghiệm lập trình">
    <meta name="date" content="2024-12-25T18:04:59+07:00">
    <title>Blog của Nguyễn Quang Hùng</title>
    <link rel="stylesheet" href="/css/styles.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .container {
            position: relative;
        }
        .image {
            max-width: 200%;
            width:800px;
            height: 400px;
            border-radius: 10px;
        }
        .text-box {
            position: absolute;
            top: 50%;
            right:-300px;
            transform: translate(-50%, -50%);
            color: white;
            text-align: center;
            background-color: rgba(36, 224, 86, 0.8);
            padding: 20px;
            border-radius: 10px;
        }
        .text-box h1,
        .text-box p {
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 2s forwards;
        }
        .text-box h1 {
            font-size: 2rem;
            margin: 0;
            color:red;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .text-box p {
            font-size: 1.2rem;
            margin: 10px 0 0;
            color: witdh;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
        }
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div style="position: relative;">
        <img src="/img/basic.png" alt="Quang Hung" class="image">
        <div class="text-box">
            <h1>Bắt Đầu Lập Trình Java Và JavaScript</h1>
            <p>cùng với QuangHungBlog</p>
        </div>
    </div>
</div>

<script>
    window.addEventListener('load', () => {
        const textElements = document.querySelectorAll('.text-box h1, .text-box p');
        textElements.forEach(element => {
            element.style.animation = 'fadeIn 2s forwards';
        });
    });
</script>

</body>
</html>
