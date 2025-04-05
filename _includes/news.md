<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Container styles */
    .news-container {
      width: 100%;
      max-height: 400px; /* Increased container height */
      overflow-y: auto;
      border: 1px solid #e0e0e0;
      border-radius: 12px; /* Rounder corners */
      padding: 15px; /* Slightly larger padding */
      font-family: 'Arial', sans-serif;
      font-size: 14px;
      line-height: 1.6; /* Increased line height */
      background-color: #fafafa;
      box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
    }

    /* Hover effect for container */
    .news-container:hover {
      border-color: #007bff;
      box-shadow: 0px 4px 15px rgba(0, 123, 255, 0.2);
    }

    /* News item styles */
    .news-item {
      margin-bottom: 12px;  /* Increased margin for better spacing */
      padding: 12px; /* Slightly larger padding */
      background-color: #ffffff;
      border-left: 6px solid #007bff; /* Thicker left border */
      border-radius: 8px; /* Rounder edges */
      transition: all 0.3s ease;
      cursor: pointer;
    }

    /* Hover effect for news item */
    .news-item:hover {
      background-color: #e0f7fa;
      transform: translateX(5px); /* Slightly more pronounced effect */
    }

    /* Date styling */
    .news-date {
      font-style: italic;
      color: #555;
      font-size: 13px; /* Slightly larger font size for dates */
      margin-bottom: 8px; /* Added space after the date */
    }

    /* Header styles */
    h3 {
      font-size: 22px; /* Increased header size */
      color: #333;
      font-weight: bold;
      margin-bottom: 20px; /* Larger gap after the title */
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    /* Link styles */
    a {
      color: #007bff;
      text-decoration: none;
      transition: color 0.2s ease;
    }

    a:hover {
      color: #0056b3;
    }
  </style>
</head>
<body>

  <h3>Latest News</h3>
  <div class="news-container">
    <div class="news-item">
      <div class="news-date">
        2025.04: MMSS robustness benchmark accepted to CVPR 2025 @ TMM Open-World!
        <span>
          <a href="https://github.com/Chenfei-Liao/Multi-Modal-Semantic-Segmentation-Robustness-Benchmark" target="_blank">code</a> and 
          <a href="https://arxiv.org/pdf/2503.18445" target="_blank">paper</a>
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
      <a href="https://ieeexplore.ieee.org/abstract/document/10741594" target="_blank">[paper]</a>
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
