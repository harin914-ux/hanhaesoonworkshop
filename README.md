# hanhaesoonworkshop
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>한해순공작소</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #333;
      text-align: center;
    }

    /* 상단 자동 슬라이드 */
    .slider-container {
      width: 100%;
      overflow: hidden;
      background: #f7f7f7;
      padding: 20px 0;
    }

    .slide-track {
      display: flex;
      width: calc(250px * 20);
      animation: scroll 40s linear infinite;
    }

    .slide {
      width: 250px;
      height: 250px;
      margin: 0 10px;
      border-radius: 10px;
      background-size: cover;
      background-position: center;
      background-color: #ddd;
    }

    @keyframes scroll {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    /* 대표상품 버튼 영역 */
    .button-section {
      margin: 40px 0;
    }

    .product-btn {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      background: #ff7f32;
      color: #fff;
      font-size: 18px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.2s;
    }

    .product-btn:hover {
      background: #e66f2c;
    }

    /* 플랫폼 링크 영역 */
    .platform-section {
      margin-top: 30px;
    }

    .platform-btn {
      display: inline-block;
      margin: 8px;
      padding: 12px 24px;
      border: 2px solid #333;
      border-radius: 6px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
      transition: 0.2s;
    }

    .platform-btn:hover {
      background: #333;
      color: #fff;
    }
  </style>
</head>
<body>

  <!-- 흐르는 후기 사진 영역 -->
  <div class="slider-container">
    <div class="slide-track">
      <!-- 이미지 20개 넣을 자리 (같은 이미지 반복 가능) -->
      <div class="slide" style="background-image:url('img/sample1.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample2.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample3.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample4.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample5.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample1.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample2.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample3.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample4.jpg');"></div>
      <div class="slide" style="background-image:url('img/sample5.jpg');"></div>
    </div>
  </div>

  <!-- 대표상품 버튼 -->
  <div class="button-section">
    <a href="#platforms" class="product-btn">대표상품 보러가기</a>
  </div>

  <!-- 플랫폼 섹션 -->
  <div id="platforms" class="platform-section">
    <a class="platform-btn" href="https://smartstore.naver.com/hanhaesoon" target="_blank">네이버 스토어</a>
    <a class="platform-btn" href="https://instagram.com" target="_blank">인스타그램</a>
    <a class="platform-btn" href="#" target="_blank">Kerara 카테고리</a>
    <a class="platform-btn" href="#" target="_blank">이벤트 페이지</a>
  </div>

</body>
</html>
