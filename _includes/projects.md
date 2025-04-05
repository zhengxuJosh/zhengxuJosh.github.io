<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* 滚动窗口容器样式 */
    .scroll-container {
      width: 100%;
      max-width: 800px; /* 最大宽度 */
      height: 200px;  /* 容器的高度 */
      overflow-x: auto;  /* 水平滚动 */
      padding: 20px;
      background-color: #f4f4f4;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    /* 内部内容容器 */
    .publication-list {
      display: flex;
      gap: 40px;  /* 项目之间的间距 */
      align-items: flex-start;  /* 上端对齐 */
      flex-wrap: nowrap;  /* 防止换行 */
    }

    /* 单个出版物样式 */
    .publication-item {
      padding: 10px;
      background-color: #ffffff;
      border-radius: 8px;
      border-left: 5px solid #007bff;  /* 蓝色边框 */
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      width: 250px;  /* 固定宽度 */
      transition: transform 0.3s ease;
    }

    /* 鼠标悬停时的效果 */
    .publication-item:hover {
      background-color: #e3f2fd;
      transform: translateY(-5px);  /* 轻微的上移效果 */
    }

    /* 标题样式 */
    h3 {
      font-size: 24px;
      color: #333;
      margin-bottom: 20px;
      text-align: center;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>

  <h3>Selected Publications</h3>
  <div class="scroll-container">
    <div class="publication-list">
      <div class="publication-item">
        <strong>TPAMI 2024</strong>: Xu Zheng, et al., 360sfuda++: Towards Source-free UDA for Panoramic Segmentation by Learning Reliable Category Prototypes.
      </div>
      <div class="publication-item">
        <strong>PR 2025</strong>: Xu Zheng, et al.,  Distilling Efficient Vision Transformers from CNNs for Semantic Segmentation.
      </div>
      <div class="publication-item">
        <strong>ECCV 2024 (Oral, 1.5%)</strong>: Xu Zheng, et al.,  Learning Modality-Agnostic Representation for Semantic Segmentation.
      </div>
      <div class="publication-item">
        <strong>ECCV 2024</strong>: Xu Zheng, et al.,  Centering the Value of Every Modality: Towards Efficient and Resilient Modality-Agnostic Semantic Segmentation.
      </div>
      <div class="publication-item">
        <strong>CVPR 2024</strong>: Xu Zheng, et al.,  EventDance: Unsupervised Source-Free Cross-Modal Adaptation for Event-Based Object Recognition.
      </div>
      <div class="publication-item">
        <strong>CVPR 2024</strong>: Yuanhuiyi Lyu*, Xu Zheng*, et al., UniBind: LLM-Augmented Unified and Balanced Representation Space to Bind Them All.
      </div>
      <div class="publication-item">
        <strong>CVPR 2024</strong>: Xu Zheng, et al.,  Semantics, Distortion, and Style Matter: Towards Source-Free UDA for Panoramic Segmentation.
      </div>
      <div class="publication-item">
        <strong>ICRA 2024</strong>: Xu Zheng, et al.,  Transformer-CNN Cohort: Semi-Supervised Semantic Segmentation by the Best of Both Students.
      </div>
      <div class="publication-item">
        <strong>ICCV 2023</strong>: Xu Zheng, et al.,  Look at the Neighbor: Distortion-Aware Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.
      </div>
      <div class="publication-item">
        <strong>CVPR 2023</strong>: Xu Zheng, et al.,  Both Style and Distortion Matter: Dual-Path Unsupervised Domain Adaptation for Panoramic Semantic Segmentation.
      </div>
    </div>
  </div>

</body>
</html>
