 +++
title = "Blog của Nguyễn Quang Hùng"
date = "2024-12-25T18:04:59+07:00"
description = "Giới thiệu về bản thân và kinh nghiệm lập trình"
css = ["/css/styles.css"]
+++
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CV Nguyễn Quang Hùng</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    .container {
      max-width: 900px;
      margin: 20px auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px;
    }
    .header {
      text-align: center;
    }
    .header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 10px;
    }
    .header h1 {
      margin: 10px 0;
      font-size: 24px;
    }
    .header p {
      margin: 5px 0;
      color: #555;
    }
    .section {
      margin: 20px 0;
    }
    .section h2 {
      font-size: 20px;
      margin-bottom: 10px;
      color: #444;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }
    .section ul {
      list-style-type: none;
      padding: 0;
    }
    .section ul li {
      margin-bottom: 10px;
    }
    .footer {
      text-align: center;
      margin-top: 20px;
      font-size: 14px;
      color: #666;
    }
      .education, .achievements {
      margin: 20px 0;
    }
    .education-card {
      background: #f9f9f9;
      padding: 15px;
      border-radius: 8px;
      border: 1px solid #ddd;
    }
    .certificates {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .certificate {
      background: #fff;
      width: 250px;
      margin: 10px;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.3s, box-shadow 0.3s;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .certificate:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    }
    .certificate img {
      width: 100%;
      height: auto;
    }
    .certificate h3 {
      text-align: center;
      padding: 10px;
      font-size: 16px;
      color: #333;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <div class="header">
      <img src="/img/avatar1.png" alt="Nguyễn Quang Hùng">
      <h1>Nguyễn Quang Hùng</h1>
      <p>Backend Developer</p>
      <p><i class="fa fa-envelope"></i> nguyenquanghung@gmail.com</p>
      <p><i class="fa fa-phone"></i> 0337070369</p>
    </div>
    <div class="section">
      <h2>Giới thiệu</h2>
      <p>Tôi mong muốn trở thành một chuyên gia lập trình backend, nắm vững các công nghệ và kỹ thuật tiên tiến để xây dựng các ứng dụng web và di động chất lượng cao. Đồng thời, tôi không ngừng học hỏi và cải thiện bản thân để đóng góp tốt nhất vào sự phát triển của đội ngũ.</p>
    </div>
    <div class="section">
      <h2>Kỹ Năng</h2>
      <ul>
        <li>Thành thạo Java và JavaScript</li>
        <li>Làm việc với Spring Boot, Hibernate, Spring Data JPA</li>
        <li>Phát triển ứng dụng di động bằng Flutter</li>
        <li>Quản lý cơ sở dữ liệu: MySQL, PostgreSQL</li>
        <li>Sử dụng thành thạo Git và các công cụ CI/CD</li>
      </ul>
    </div>
    <div class="section">
      <h2>Kinh Nghiệm và Dự Án</h2>
      <ul>
        <li>Phát triển ứng dụng web với Spring Boot, xây dựng API RESTful và tích hợp Hibernate</li>
        <li>Thiết kế hệ thống API hỗ trợ giao tiếp frontend-backend</li>
        <li>Xây dựng ứng dụng di động sử dụng Flutter</li>
        <li>Làm việc với các hệ thống cơ sở dữ liệu lớn</li>
      </ul>
    </div>
    <div class="section">
      <h2>Hoạt Động</h2>
      <ul>
        <li>Tham gia các cuộc thi lập trình</li>
        <li>Học hỏi và chia sẻ công nghệ tại các hội thảo</li>
      </ul>
    </div>
    <div class="education section">
      <h2>Học vấn</h2>
      <div class="education-card">
        <p><strong>Kỹ sư Công nghệ phần mềm</strong></p>
        <p>Đại học công nghệ Thành phố Hồ Chí Minh - HUTECH</p>
        <p>GPA: 3.25/4.0</p>
        <p>Đang trong quá trình học tập và rèn luyện tại trường Đại học công nghệ Thành phố Hồ Chí Minh - HUTECH.</p>
      </div>
    </div>
  <div class="achievements section">
  <h2>Thành tựu</h2>
  <div class="certificates">
    <div class="certificate">
      <a href="https://drive.google.com/file/d/1CpY9An5-eCchn3v-yrn2HHNL_LGWSM5e/view?usp=drive_link" target="_blank">
        <img src="/img/javascript-essentials-1.png" alt="JavaScript Essentials 1">
      </a>
      <h3>JavaScript Essentials 1 course</h3>
      <p>Tôi đã hoàn thành chứng chỉ khóa học JavaScript cơ bản 1 tại Cisco Networking Academy</p>
    </div>
    <div class="certificate">
      <a href="https://drive.google.com/file/d/1h0Dee40AN6I_j4WTEzHIVY5KkznZUMPl/view?usp=drive_link" target="_blank">
        <img src="/img/networking-basics.png" alt="Networking Basics">
      </a>
      <h3>Networking Basics course</h3>
      <p>Chứng chỉ này ghi nhận khả năng thiết kế và quản lý hệ thống mạng cơ bản.</p>
    </div>
    <div class="certificate">
      <a href="https://drive.google.com/file/d/1DmYSbvXP0E6XLXtzbmBfVOE4Uut5BVqs/view?usp=drive_link" target="_blank">
        <img src="/img/javascript-essentials-2.png" alt="JavaScript Essentials 2">
      </a>
      <h3>JavaScript Essentials 2 course</h3>
      <p>Tôi đã hoàn thành khóa học JavaScript nâng cao tại Cisco Networking Academy</p>
    </div>
  </div>
</div>

    </div>
  </div>
</body>
</html>