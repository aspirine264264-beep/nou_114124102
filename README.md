[Uploading index.html…]()
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黃姿婷的個人介紹</title>

    <!-- 分頁小圖示 (已更換為臘腸狗圖片) -->
    <link rel="icon" href="https://upload.wikimedia.org/wikipedia/commons/b/be/%EB%8B%A5%EC%8A%A4%ED%9B%88%ED%8A%B8%28%EB%8B%A8%EB%AA%A8%EC%A2%85%29_%28Dachshund_%28Short%29%29.jpg" type="image/jpeg">

    <!-- CSS 樣式：白色背景 + 設定標題顏色 -->
    <style>
        body {
            background-color: #ffffff; /* 純白背景 */
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
            color: #333333; /* 內文預設深灰色 */
        }

        /* 標題顏色設定 */
        h1 {
            color: #1a5fb4; /* H1 大標題：質感深藍色 */
        }

        h2 {
            color: #26a269; /* H2 次標題：質感墨綠色 */
        }

        h3 {
            color: #e66100; /* H3 小標題：溫暖橘棕色 */
        }

        /* 針對文字強調 span 加上黃色螢光背景 */
        span {
            background-color: #ffff99;
            padding: 2px 5px;
            border-radius: 3px;
        }

        /* 程式碼區塊背景色 (淺灰底) */
        pre {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
        }

        /* 引用區塊樣式 */
        blockquote {
            background-color: #f9f9f9;
            border-left: 4px solid #ccc;
            margin: 10px 0;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
      <h1>黃姿婷的個人介紹(已更新)</h1>
    </header>
    
    <!-- 移到上方的歡迎區塊 -->
    <main>
      <h1>歡迎來到我的網頁！</h1>
      <p>這是一個經過 <span>精心設計</span> 的段落文字。</p>
    </main>

    <p>這是第一段重要文字。</p>
    <p>這是第二段重要文字。</p>
    <div>這是一個重要區塊。</div>

    <h2>關於我</h2>
    <p>大家好，我的學號是114124102</p>
    <h2>我的興趣</h2>
    <ul>
      <li>看小說</li>
      <li>拼樂高</li>
      <li>作微縮模型</li>
    </ul>

    <h2>我的學習目標</h2>
    <p>我的學習目標是拿到學歷考取工作用證照</p>
    <h2>我喜歡的網站</h2>
    <p><a href="http://www.google.com">google</a></p>

    <p>這是第一段的內容。</p>

    <hr>

    <p>這是第二段的內容，下面我有一段保留空格的程式碼：</p>

    <pre>
  function sayHello() {
      console.log("Hello World!");
  }
    </pre>

    <p>愛因斯坦曾經說過一段非常有名的話：</p>

    <blockquote cite="https://bookzone.cwgv.com.tw/article/19595">
      一個從未犯錯的人，是因為他從未嘗試過任何新事物。
      這句話提醒我們，不要害怕失敗，因為失敗是學習的一部分。
    </blockquote>

    <p>這句話激勵了無數正在面對挑戰的人。</p>

    <h3>買菜清單（順序沒關係，用 ul）</h3>
    <ul>
      <li>蘋果</li>
      <li>香蕉</li>
      <li>牛奶</li>
    </ul>

    <hr>

    <h3>泡麵三步驟（順序很重要，用 ol）</h3>
    <ol>
      <li>把撕開的調味包倒進碗裡。</li>
      <li>加入熱水並蓋上蓋子。</li>
      <li>耐心等待三分鐘後即可享用。</li>
    </ol>

    <h3>大寫羅馬數字清單</h3>
    <ol type="I">
      <li>網頁基本骨架</li>
      <li>文字與標題</li>
      <li>多媒體標籤</li>
    </ol>

    <h3>大寫英文字母清單</h3>
    <ol type="A">
      <li>打開瀏覽器</li>
      <li>輸入網址</li>
      <li>按下 Enter 鍵</li>
    </ol>

    <ol start="4" type="A">
      <li>這是項目 C</li>
      <li>這是項目 D</li>
    </ol>

    <p>
      今天的天氣真是太棒了，天空出現了
      <span>美麗的彩虹</span>！
    </p>

    <p>5 &lt; 10 &amp; Tom 說 &quot;嗨&quot;</p>

    <p>這是一本名為 <cite>網頁魔法書</cite> 的著作。</p>

    <p>原價 <s>NT$ 500</s>，現在特價只要 <strong>NT$ 290</strong>！</p>

    <p>最新公告：<del>舊的規定</del> <ins>新規定自即日起實施</ins>。</p>

    <p>數學題：2<sup>3</sup> = 8 ； 化學題：CO<sub>2</sub> 是二氧化碳。</p>

    <p><small>※ 本網站保留最終活動解釋權。</small></p>

    <header>
      <h1>美味食譜網</h1>
      <nav>
        <a href="#">首頁</a> | <a href="#">中式料理</a> |
        <a href="#">西式甜點</a>
      </nav>
    </header>

    <main>
      <article>
        <hgroup>
          <h2>如何烤出完美的巧克力蛋糕</h2>
          <p>新手必學的零失敗烘焙指南</p>
        </hgroup>

        <section>
          <h3>第一步：準備材料</h3>
          <p>你需要麵粉、砂糖和可可粉...</p>
        </section>

        <section>
          <h3>第二步：攪拌與烘烤</h3>
          <p>將烤箱預熱至 180 度...</p>
        </section>
      </article>

      <aside>
        <h3>作者簡介</h3>
        <p>小明，擁有十年烘焙經驗的專業主廚。</p>
      </aside>
    </main>

    <img alt="小貓" src="https://thumb.wikimedia.org/wikipedia/commons/thumb/4/4d/Cat_November_2010-1a.jpg/500px-Cat_November_2010-1a.jpg">

    <footer>
      <p>© 2026 美味食譜網 版權所有</p>
    </footer>
</body>
</html>
