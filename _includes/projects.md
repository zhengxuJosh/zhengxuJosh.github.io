<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Container styles */
    .publications-container {
      width: 100%;
      max-height: 200px;
      overflow-y: auto;
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
    .publications-container:hover {
      border-color: #007bff;
      box-shadow: 0px 2px 8px rgba(0, 123, 255, 0.2);
    }

    /* Publication item styles */
    .publication-item {
      margin-bottom: 4px;
      padding: 5px;
      background-color: #ffffff;
      border-left: 3px solid #007bff;
      border-radius: 4px;
      transition: all 0.2s ease;
      cursor: pointer;
    }

    /* Hover effect for publication item */
    .publication-item:hover {
      background-color: #e0f7fa;
      transform: translateX(3px);
    }

    /* Conference styling */
    .publication-conference {
      font-weight: bold;
      color: #333;
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

  <h3>Selected Publications</h3>
  <div class="publications-container">
    <div class="publication-item">
      <div class="publication-conference">ICCV 2025</div>
      Xu Zheng, et al., Reducing unimodal bias in multi-modal semantic segmentation with multi-scale functional entropy regularization.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">ICCV 2025</div>
      Ding Zhong*, Xu Zheng*, et al., Omnisam: Omnidirectional segment anything model for uda in panoramic semantic segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">TPAMI 2024</div>
      Xu Zheng, et al., 360sfuda++: Towards Source-free UDA for Panoramic Segmentation by Learning Reliable Category Prototypes.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">PR 2025</div>
      Xu Zheng, et al., Distilling Efficient Vision Transformers from CNNs for Semantic Segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">ECCV 2024 (Oral, 1.5%)</div>
      Xu Zheng, et al., Learning Modality-Agnostic Representation for Semantic Segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">ECCV 2024</div>
      Xu Zheng, et al., Centering the Value of Every Modality: Towards Efficient and Resilient Modality-Agnostic Semantic Segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      Xu Zheng, et al., EventDance: Unsupervised Source-Free Cross-Modal Adaptation for Event-Based Object Recognition.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      Yuanhuiyi Lyu*, Xu Zheng*, et al., UniBind: LLM-Augmented Unified and Balanced Representation Space to Bind Them All.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">CVPR 2024</div>
      Xu Zheng, et al., Semantics, Distortion, and Style Matter: Towards Source-Free UDA for Panoramic Segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">ICRA 2024</div>
      Xu Zheng, et al., Transformer-CNN Cohort: Semi-Supervised Semantic Segmentation by the Best of Both Students.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">ICCV 2023</div>
      Xu Zheng, et al., Look at the Neighbor: Distortion-Aware Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.
    </div>
    
    <div class="publication-item">
      <div class="publication-conference">CVPR 2023</div>
      Xu Zheng, et al., Both Style and Distortion Matter: Dual-Path Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.
    </div>
  </div>

</body>
</html>
