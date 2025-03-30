<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* 容器样式 */
    .news-container {
      width: 100%;
      max-height: 300px; /* 增加高度以便显示更多内容 */
      overflow-y: auto;
      border: 1px solid #e0e0e0; /* 更浅的灰色边框 */
      border-radius: 15px;  /* 增加圆角效果 */
      padding: 20px;
      font-family: 'Arial', sans-serif; /* 更现代的字体 */
      font-size: 16px; /* 更大的字体以提高可读性 */
      line-height: 1.8; /* 增加行高使文本更易读 */
      background-color: #ffffff; /* 背景色改为白色 */
      box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.1); /* 更强的阴影效果 */
      transition: all 0.3s ease;
    }

    /* 鼠标悬停时的效果 */
    .news-container:hover {
      border-color: #007bff; /* 蓝色边框 */
      box-shadow: 0px 6px 25px rgba(0, 123, 255, 0.2); /* 蓝色阴影 */
    }

    /* 新闻条目的样式 */
    .news-item {
      margin-bottom: 15px;
      padding: 15px;
      background-color: #f9f9f9; /* 微淡灰背景 */
      border-left: 6px solid #007bff; /* 更粗的蓝色左边框 */
      border-radius: 8px; /* 更圆的边角 */
      transition: all 0.3s ease;
      cursor: pointer; /* 鼠标指针效果 */
    }

    /* 鼠标悬停时的新闻条目效果 */
    .news-item:hover {
      background-color: #e3f2fd; /* 浅蓝色背景 */
      transform: translateX(8px); /* 稍微的右移效果 */
    }

    /* 日期样式 */
    .news-date {
      font-style: italic;
      color: #555;
      font-size: 14px;
    }

    /* 标题样式 */
    h3 {
      font-size: 24px;
      color: #333;
      font-weight: bold;
      margin-bottom: 20px;
      text-transform: uppercase; /* 大写字母 */
      letter-spacing: 1px; /* 字母间距 */
    }

    /* 链接样式 */
    a {
      color: #007bff;
      text-decoration: none;
      transition: color 0.2s ease;
    }

    a:hover {
      color: #0056b3; /* 悬停时的蓝色 */
    }
  </style>
</head>
<body>

  <h3>News</h3>
  <div class="news-container">
    <div class="news-item">
      <div class="news-date">2025.02: Visit INSAIT as a Resident Doctoral Researcher!</div>
    </div>
    <div class="news-item">
      <div class="news-date">2025.01: Successfully passed PhD Qualifying Examination!</div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.12: Invited as an <strong>Area Chair</strong> of PDLM @ <strong>AAAI 2025</strong>.</div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.10: One paper accepted to <strong>IEEE TPAMI</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.10: Oral presentation @ <strong>ECCV 2024</strong> Oral Session 5A: Segmentation <a href="https://eccv.ecva.net/virtual/2024/session/103" target="_blank">[video]</a></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.09: One paper accepted to <strong>Pattern Recognition</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.07: Three papers (one <strong>Oral (1.5%)</strong>) accepted to <strong>ECCV 2024</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.03: One paper accepted to <strong>IEEE CAI 2024</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.03: One paper accepted to <strong>Pattern Recognition</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.03: Five papers (one <strong>Highlight (2.8%)</strong>) accepted to <strong>CVPR 2024</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2024.02: Two papers accepted to <strong>ICRA 2024</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2023.07: Two papers accepted to <strong>ICCV 2023</strong></div>
    </div>
    <div class="news-item">
      <div class="news-date">2023.03: One paper accepted to <strong>CVPR 2023</strong></div>
    </div>
  </div>

</body>
</html>
