<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>互動個人首頁 - [你的名字]</title>
  <style>
    /* Reset 與基本樣式 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      color: #333;
      line-height: 1.6;
    }
    /* 頁首背景與打字機效果 */
    header {
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      text-align: center;
      padding: 4rem 2rem;
      position: relative;
      overflow: hidden;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.2rem;
    }
    /* 打字機效果的樣式 */
    .typing {
      border-right: .15em solid #fff;
      white-space: nowrap;
      overflow: hidden;
      display: inline-block;
    }
    /* 導覽列 */
    nav {
      background: #333;
    }
    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }
    nav li {}
    nav a {
      display: block;
      padding: 1rem 1.5rem;
      color: #fff;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #555;
    }
    /* 內容區塊 (section) 樣式 */
    section {
      padding: 4rem 2rem;
      margin: 2rem auto;
      max-width: 1000px;
      background: #fff;
      border-radius: 8px;
      /* 初始狀態：透明並稍微下移 */
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }
    /* 當元素進入可視範圍，加入 visible 類別 */
    section.visible {
      opacity: 1;
      transform: translateY(0);
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    /* 互動按鈕 */
    .button {
      display: inline-block;
      padding: 0.8rem 1.2rem;
      background: #667eea;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .button:hover {
      background: #556cd6;
    }
    /* 頁尾 */
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
    /* 響應式調整 */
    @media (max-width: 600px) {
      header h1 { font-size: 2.2rem; }
      nav a { padding: 0.8rem 1rem; }
    }
  </style>
</head>
<body>
  <!-- 頁首區 -->
  <header>
    <h1>你好，我是 [你的名字]</h1>
    <p class="typing" id="typing-text"></p>
  </header>

  <!-- 導覽列 -->
  <nav>
    <ul>
      <li><a href="#about">關於我</a></li>
      <li><a href="#projects">專案</a></li>
      <li><a href="#contact">聯絡我</a></li>
    </ul>
  </nav>

  <!-- 內容區塊 -->
  <section id="about">
    <h2>關於我</h2>
    <p>這裡簡單介紹一下你自己，描述你的背景、專長與興趣。當你捲動到這裡時，你會發現內容以平滑的動畫效果呈現。</p>
    <button class="button" id="more-info-btn">更多資訊</button>
  </section>

  <section id="projects">
    <h2>專案</h2>
    <p>這裡展示我的部分專案，點擊專案名稱以進入詳細介紹：</p>
    <ul>
      <li><a href="https://github.com/yourusername/project1" target="_blank">專案名稱 1</a></li>
      <li><a href="https://github.com/yourusername/project2" target="_blank">專案名稱 2</a></li>
      <li><a href="https://github.com/yourusername/project3" target="_blank">專案名稱 3</a></li>
    </ul>
  </section>

  <section id="contact">
    <h2>聯絡我</h2>
    <p>歡迎通過以下方式與我聯絡：</p>
    <ul>
      <li>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
      <li>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></li>
    </ul>
  </section>

  <!-- 頁尾 -->
  <footer>
    <p>© 2025 [你的名字]. All rights reserved.</p>
  </footer>

  <script>
    /* ------------------------------
       打字機效果
    ------------------------------ */
    const typingText = document.getElementById('typing-text');
    const messages = ["前端開發者", "UI/UX 設計愛好者", "技術分享者"];
    let messageIndex = 0;
    let charIndex = 0;
    let currentMessage = "";
    let isDeleting = false;

    function type() {
      if (messageIndex >= messages.length) {
        messageIndex = 0;
      }
      currentMessage = messages[messageIndex];

      if (!isDeleting) {
        typingText.textContent = currentMessage.substring(0, charIndex + 1);
        charIndex++;
        if (charIndex === currentMessage.length) {
          isDeleting = true;
          setTimeout(type, 1500);
        } else {
          setTimeout(type, 150);
        }
      } else {
        typingText.textContent = currentMessage.substring(0, charIndex - 1);
        charIndex--;
        if (charIndex === 0) {
          isDeleting = false;
          messageIndex++;
          setTimeout(type, 500);
        } else {
          setTimeout(type, 100);
        }
      }
    }
    document.addEventListener("DOMContentLoaded", type);

    /* ------------------------------
       滾動時顯示動畫效果 (使用 Intersection Observer)
    ------------------------------ */
    const sections = document.querySelectorAll("section");
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if(entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.2 });
    sections.forEach(section => observer.observe(section));

    /* ------------------------------
       互動按鈕點擊效果
    ------------------------------ */
    document.getElementById('more-info-btn').addEventListener('click', () => {
      alert("這裡可以跳轉到更多關於你的資訊，或彈出更多內容。");
    });
  </script>
</body>
</html>
