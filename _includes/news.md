<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  /* 容器样式 */
  .news-container {
    width: 100%;
    max-height: 200px; /* 可以根据需要调整窗口的高度 */
    overflow-y: auto;  /* 垂直滚动 */
    border: 1px solid #ddd; /* 淡灰色的边框 */
    border-radius: 10px;  /* 圆角边框 */
    padding: 15px;
    font-family: inherit; /* 确保继承外部字体 */
    font-size: inherit;   /* 确保字体大小一致 */
    line-height: 1.5;     /* 设置行高，确保行间距适当 */
    background-color: #f9f9f9;  /* 背景色 */
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1); /* 轻微阴影效果 */
    transition: all 0.3s ease;  /* 添加平滑的过渡效果 */
  }

  /* 鼠标悬停时的效果 */
  .news-container:hover {
    border-color: #007bff; /* 当鼠标悬停时，边框颜色变为蓝色 */
    box-shadow: 0px 4px 15px rgba(0, 123, 255, 0.2); /* 增加阴影 */
  }

  /* 新闻条目的样式 */
  .news-item {
    margin-bottom: 10px;
    padding: 8px;
    background-color: #ffffff; /* 白色背景 */
    border-left: 5px solid #007bff; /* 左侧蓝色条纹 */
    border-radius: 5px; /* 圆角效果 */
    transition: all 0.3s ease;  /* 为每条新闻添加过渡效果 */
  }

  /* 鼠标悬停时的新闻条目效果 */
  .news-item:hover {
    background-color: #f0f8ff; /* 背景变为浅蓝色 */
    transform: translateX(5px); /* 向右轻微偏移 */
  }

  /* 日期样式 */
  .news-date {
    font-style: italic;
    color: #555;
  }

  /* 设置标题样式 */
  h3 {
    font-size: 18px;
    color: #333;
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
