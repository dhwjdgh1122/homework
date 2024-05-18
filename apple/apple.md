# 과제
- 카드 컴포넌트 하나도 제대로 작성하지 못했다.. 과제를 원활하게 수행하게끔 기초 환경 세팅을 해준 슬비쌤에게 매우 죄송합니다..!
- 최근 컨디션 관리도 실패했고, 갈비뼈 골절로 강의를 완벽히 수강하지 못한 점
- 핑계이지만.. 부족한 내용은 충분히 복습해오겠습니다........


 link : http://127.0.0.1:5501/apple/apple.html

# HTML
      <!DOCTYPE html>
      <html lang="ko">
        <head>
          <meta charset="UTF-8" />
          <meta name="viewport" content="width=device-width, initial-scale=1.0" />
          <title>Apple</title>
          <link rel="icon" href="./favicon/apple-favicon.svg" />
          <link rel="apple-touch-icon" href="./favicon/apple-favicon.svg" />
          <link href="https://cdn.jsdelivr.net/gh/sun-typeface/SUIT/fonts/variable/woff2/SUIT-Variable.css" rel="stylesheet" />
          <link rel="stylesheet" href="./styles/apple.css" />
        </head>
        <body>
          <main class="main-content">
            <!-- iPad Pro Section -->
            <section class="product-section" id="ipad-pro">
                <div class="content">
                    <h1 class="large-text">iPad Pro</h1>
                    <p class="mid-text">놀라우리만치 얇다. <br>엄청나게 강력하다.</p>
                    <p class="small-text">출시일 추후 공개</p>
                    <div class="buttons">
                        <a href="#" class="btn learn-more">더 알아보기</a>
                        <a href="#" class="btn buy">가격 보기</a>
                    </div>
                </div>
                <img src="./products/ipad_pro.jpeg" alt="iPad Pro" class="product-image">
            </section>

        </main>
      </body>
      </html>

# CSS

    /* Reset some default browser styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
      color: #333;
      background-color: #000;
      line-height: 1.6;
    }

    .main-content {
      overflow-x: hidden;
    }

    .product-section {
      text-align: center;
      padding: 60px 20px;
      position: relative;
    }

    #ipad-pro {
      background-color: #000;
      color: #fff;
    }

    .product-section .content {
      position: relative;
      z-index: 10;
      padding: 20px;
    }

    .product-section h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    .product-section p {
      font-size: 1.5rem;
      margin-bottom: 20px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 20px;
    }

    .btn {
      padding: 10px 20px;
      border-radius: 20px;
      text-decoration: none;
      color: #fff;
      font-size: 1rem;
    }

    .learn-more {
      background-color: #0071e3;
    }

    .buy {
      border: 1px solid #0071e3;
    }

    .product-image {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px auto 0;
    }

