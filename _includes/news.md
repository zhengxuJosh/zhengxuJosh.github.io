<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Container styles */
    .news-container {
      width: 100%;
      max-height: 200px; /* 高度减半 */
      overflow-y: auto;
      border: 1px solid #e0e0e0;
      border-radius: 8px; /* 圆角减小 */
      padding: 6px; /* 内边距减小 */
      font-family: 'Arial', sans-serif;
      font-size: 12px; /* 只减小新闻容器内的字体 */
      line-height: 1.3; /* 行高减小 */
      background-color: #fafafa;
      box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1); /* 阴影减小 */
    }

    /* Hover effect for container */
    .news-container:hover {
      border-color: #007bff;
      box-shadow: 0px 2px 8px rgba(0, 123, 255, 0.2);
    }

    /* News item styles */
    .news-item {
      margin-bottom: 4px; /* 间距减小 */
      padding: 5px; /* 内边距减小 */
      background-color: #ffffff;
      border-left: 3px solid #007bff; /* 边框减小 */
      border-radius: 4px; /* 圆角减小 */
      transition: all 0.2s ease;
      cursor: pointer;
    }

    /* Hover effect for news item */
    .news-item:hover {
      background-color: #e0f7fa;
      transform: translateX(3px);
    }

    /* Date styling - 继承容器字体大小 */
    .news-date {
      font-style: italic;
      color: #555;
      margin-bottom: 3px;
    }

    /* Header styles - 保持原始大小 */
    h3 {
      font-size: 22px;
      color: #333;
      font-weight: bold;
      margin-bottom: 12px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    /* Link styles - 保持原始大小 */
    a {
      color: #007bff;
      text-decoration: none;
      transition: color 0.2s ease;
      font-size: inherit; /* 继承父元素字体大小 */
    }

    a:hover {
      color: #0056b3;
    }
  </style>
</head>
<body>

  <h3></h3>
  <div class="news-container">

   <div class="news-item">
      <div class="news-date">
        2025.06: One paper accepted to BMVC 2025!
      </div>
    </div>
    
  <div class="news-item">
      <div class="news-date">
        2025.06: Four papers accepted to ICCV 2025!
      </div>
    </div>
    
  <div class="news-item">
      <div class="news-date">
        2025.06: Our paper is selected as <span style="color: red; font-weight: bold;">Best Paper</span> at CVPR 2025 @ TMM Open-World!
        <span>
          <a href="https://github.com/Chenfei-Liao/Multi-Modal-Semantic-Segmentation-Robustness-Benchmark" target="_blank">Code</a> and 
          <a href="https://arxiv.org/pdf/2503.18445" target="_blank">Paper</a>
        </span>
      </div>
    </div>
    
  <div class="news-item">
      <div class="news-date">
        2025.06: One paper accepted to IROS 2025!
        <span>
          <a href="https://github.com/iAsakiT3T/SHIFNet" target="_blank">Code</a> and <a href="https://arxiv.org/pdf/2503.02581" target="_blank">Paper</a>
        </span>
      </div>
    </div>
    
  <div class="news-item">
      <div class="news-date">
        2025.05: Two paper accepted to ACL 2025 Findings!
        <span>
          <a href="https://arxiv.org/pdf/2502.11051" target="_blank">Paper1</a> and <a href="https://arxiv.org/pdf/2412.11936" target="_blank">Paper2</a>
        </span>
      </div>
    </div>
    
    <div class="news-item">
      <div class="news-date">
        2025.05: One paper accepted to ICML 2025!
        <span>
          <a href="https://arxiv.org/pdf/2502.00848" target="_blank">Paper</a>
        </span>
      </div>
    </div>
    
    <div class="news-item">
      <div class="news-date">
        2025.04: The first RAG in CV survey released!
        <span>
          <a href="https://github.com/zhengxuJosh/Awesome-RAG-Vision" target="_blank">Code</a> and 
          <a href="https://arxiv.org/pdf/2503.18016" target="_blank">Paper</a>
        </span>
      </div>
    </div>

    <div class="news-item">
      <div class="news-date">
        2025.04: Our paper accepted to CVPR 2025 @ TMM Open-World as <span style="color: red;">Oral Presentation</span>!
        <span>
          <a href="https://github.com/Chenfei-Liao/Multi-Modal-Semantic-Segmentation-Robustness-Benchmark" target="_blank">Code</a> and 
          <a href="https://arxiv.org/pdf/2503.18445" target="_blank">Paper</a>
        </span>
      </div>
    </div>


    <div class="news-item">
      <div class="news-date">
        2025.02: Visit INSAIT as a Resident Doctoral Researcher! 
        <a href="https://www.linkedin.com/posts/insaitinstitute_insait-ai-computervision-activity-7297518558874406912-c9PO?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEnD3sQBGae5cdlTD6ToV59qsKz7e_q4uk8" target="_blank">LinkedIn</a>
      </div>
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
      <div class="news-date">2024.10: Oral presentation @ <strong>ECCV 2024</strong> Oral Session 5A: Segmentation 
        <a href="https://eccv.ecva.net/virtual/2024/session/103" target="_blank">[video]</a>
      </div>
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
