<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Container styles */
    .news-container {
      width: 100%;
      max-height: 200px; /* Removed sliding behavior */
      overflow-y: hidden; /* Hide overflow */
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      padding: 6px;
      font-family: 'Arial', sans-serif;
      font-size: 12px;
      line-height: 1.3;
      background-color: #fafafa;
      box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
    }

    /* Hover effect for container */
    .news-container:hover {
      border-color: #007bff;
      box-shadow: 0px 2px 8px rgba(0, 123, 255, 0.2);
    }

    /* News item styles */
    .news-item {
      margin-bottom: 4px;
      padding: 5px;
      background-color: #ffffff;
      border-left: 3px solid #007bff;
      border-radius: 4px;
      transition: all 0.2s ease;
      cursor: pointer;
    }

    /* Hover effect for news item */
    .news-item:hover {
      background-color: #e0f7fa;
      transform: translateX(3px);
    }

    /* Date styling */
    .news-date {
      font-style: italic;
      color: #555;
      margin-bottom: 3px;
    }

    /* Header styles */
    h3 {
      font-size: 22px;
      color: #333;
      font-weight: bold;
      margin-bottom: 12px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    /* Link styles */
    a {
      color: #007bff;
      text-decoration: none;
      transition: color 0.2s ease;
      font-size: inherit;
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
        2025.06: Our paper is selected as <span style="color: red; font-weight: bold;">Best Paper</span> at CVPR 2025 @ TMM Open-World!
        <span>
          <a href="https://github.com/Chenfei-Liao/Multi-Modal-Semantic-Segmentation-Robustness-Benchmark" target="_blank">Code</a> and 
          <a href="https://arxiv.org/pdf/2503.18445" target="_blank">Paper</a>
        </span>
      </div>
    </div>
    
    <!-- Other news items go here (repeat the same structure) -->

    <div class="news-item" style="display:none;">
      <div class="news-date">
        2025.06: One paper accepted to IROS 2025!
        <span>
          <a href="https://github.com/iAsakiT3T/SHIFNet" target="_blank">Code</a> and <a href="https://arxiv.org/pdf/2503.02581" target="_blank">Paper</a>
        </span>
      </div>
    </div>

    <!-- Example of the remaining items, each with style="display:none;" to hide them initially -->

    <!-- More items hidden by default -->
    <div id="more-news" class="news-item" style="display:none;">
      <div class="news-date">2025.05: Two papers accepted to ACL 2025 Findings!</div>
    </div>

    <!-- More button -->
    <div id="more-button" class="news-item" style="cursor: pointer; color: blue; font-weight: bold;" onclick="toggleMoreNews()">More</div>
  </div>

  <script>
    // Toggle the visibility of additional news items
    function toggleMoreNews() {
      var moreNews = document.querySelectorAll("#more-news");
      var moreButton = document.getElementById("more-button");

      moreNews.forEach(function(item) {
        item.style.display = (item.style.display === "none" || item.style.display === "") ? "block" : "none";
      });

      // Change the button text to 'Less' when items are visible
      if (moreNews[0].style.display === "block") {
        moreButton.innerHTML = "Less";
      } else {
        moreButton.innerHTML = "More";
      }
    }
  </script>

</body>
</html>
