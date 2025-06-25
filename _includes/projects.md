<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Global styles */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }

    /* Header styles */
    h3 {
      font-size: 24px;
      color: #333;
      font-weight: bold;
      margin: 20px;
      text-transform: uppercase;
      letter-spacing: 1px;
      text-align: center;
    }

    /* Container styles */
    .publications-container {
      width: 100%;
      max-height: 400px;
      overflow-y: auto;
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      padding: 16px;
      background-color: #ffffff;
      box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.1);
      margin: 0 auto;
      max-width: 800px;
    }

    /* Hover effect for container */
    .publications-container:hover {
      border-color: #007bff;
      box-shadow: 0px 2px 10px rgba(0, 123, 255, 0.2);
    }

    /* Publication item styles */
    .publication-item {
      margin-bottom: 10px;
      padding: 10px;
      background-color: #ffffff;
      border-left: 4px solid #007bff;
      border-radius: 6px;
      transition: all 0.3s ease;
      cursor: pointer;
    }

    /* Hover effect for publication item */
    .publication-item:hover {
      background-color: #e3f2fd;
      transform: translateX(4px);
    }

    /* Conference styling */
    .publication-conference {
      font-weight: bold;
      color: #007bff;
      margin-bottom: 6px;
      font-size: 14px;
    }

    /* Item text styling */
    .publication-item p {
      margin: 0;
      font-size: 14px;
      color: #333;
    }

    /* Link styles */
    a {
      color: #007bff;
      text-decoration: none;
      font-size: 14px;
    }

    a:hover {
      color: #0056b3;
    }
  </style>
</head>
<body>

  <h3>Selected Publications</h3>

  <div class="publications-container">

    <div class="publication-item">
      <div class="publication-conference">ICCV 2025</div>
      <p>Xu Zheng, et al., <em>Reducing unimodal bias in multi-modal semantic segmentation with multi-scale functional entropy regularization.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">ICCV 2025</div>
      <p>Ding Zhong*, Xu Zheng*, et al., <em>Omnisam: Omnidirectional segment anything model for uda in panoramic semantic segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">TPAMI 2024</div>
      <p>Xu Zheng, et al., <em>360sfuda++: Towards Source-free UDA for Panoramic Segmentation by Learning Reliable Category Prototypes.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">PR 2025</div>
      <p>Xu Zheng, et al., <em>Distilling Efficient Vision Transformers from CNNs for Semantic Segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">ECCV 2024 (Oral, 1.5%)</div>
      <p>Xu Zheng, et al., <em>Learning Modality-Agnostic Representation for Semantic Segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">ECCV 2024</div>
      <p>Xu Zheng, et al., <em>Centering the Value of Every Modality: Towards Efficient and Resilient Modality-Agnostic Semantic Segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      <p>Xu Zheng, et al., <em>EventDance: Unsupervised Source-Free Cross-Modal Adaptation for Event-Based Object Recognition.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      <p>Yuanhuiyi Lyu*, Xu Zheng*, et al., <em>UniBind: LLM-Augmented Unified and Balanced Representation Space to Bind Them All.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      <p>Xu Zheng, et al., <em>Semantics, Distortion, and Style Matter: Towards Source-Free UDA for Panoramic Segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">ICRA 2024</div>
      <p>Xu Zheng, et al., <em>Transformer-CNN Cohort: Semi-Supervised Semantic Segmentation by the Best of Both Students.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">ICCV 2023</div>
      <p>Xu Zheng, et al., <em>Look at the Neighbor: Distortion-Aware Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.</em></p>
    </div>

    <div class="publication-item">
      <div class="publication-conference">CVPR 2023</div>
      <p>Xu Zheng, et al., <em>Both Style and Distortion Matter: Dual-Path Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.</em></p>
    </div>

  </div>

</body>
</html>
