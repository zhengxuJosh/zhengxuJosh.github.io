<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .person-container {
      width: 100%;
      max-height: 200px;
      overflow-y: auto;
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      padding: 6px;
      font-family: 'Arial', sans-serif;
      font-size: 12px;
      line-height: 1.4;
      background-color: #fafafa;
      box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
    }

    .person-container:hover {
      border-color: #007bff;
      box-shadow: 0px 2px 8px rgba(0, 123, 255, 0.2);
    }

    .person-item {
      margin-bottom: 4px;
      padding: 5px;
      background-color: #ffffff;
      border-left: 3px solid #007bff;
      border-radius: 4px;
      transition: all 0.2s ease;
      cursor: default;
    }

    .person-item:hover {
      background-color: #e0f7fa;
      transform: translateX(3px);
    }

    h3 {
      font-size: 20px;
      color: #333;
      font-weight: bold;
      margin-bottom: 12px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>

  <h3>Researchers mentored</h3>
  <div class="person-container">
    <div class="person-item">Yuanhuiyi Lyu, Ph.D. student @ HKUST(GZ)</div>
    <div class="person-item">Mengzhen Chi, Ph.D. student @ NEU</div>
    <div class="person-item">Chenfei Liao, M.Phil. student @ HKUST(GZ)</div>
    <div class="person-item">Ding Zhong, Master’s student @ Umich</div>
    <div class="person-item">Zihao Dongfang, Research Assistant @ HKUST(GZ)</div>
    <div class="person-item">Ziqiao Weng, Undergraduate student @ SCU</div>
    <div class="person-item">Yulong Guo, Master’s student @ ZJU</div>
    <div class="person-item">Kaiyu Lei, Undergraduate student @ XJTU</div>
    <div class="person-item">Junha Moon (문준하), M.Phil. student @ HKUST(GZ)</div>
    <div class="person-item">Zhenquan Zhang, M.Phil. student @ SCUT</div>
    <div class="person-item">Boyuan Zheng, M.Phil. student @ TongJi</div>
    <div class="person-item">Jiahao Zhang, Research Assistant @ HKUST(GZ)</div>
    <div class="person-item">Zhengxuan Jiang, M.Phil. student @ ZJU</div>
    <div class="person-item">Leyi Sheng, Undergraduate student @ HKUST(GZ)</div>
  </div>

</body>
</html>
