---
layout: default
title: Home
---

<style>
  .hero {
    background-image: url('/assets/images/my_bg.jpg'); /* 替换为你上传的图片路径 */
    background-size: cover;
    background-position: center;
    height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #00ff00; /* 标题鲜绿色 */
    text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
  }
  .hero p {
    font-size: 1.5rem;
    color: #66ff66; /* 段落浅绿色 */
    text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
  }

  /* 响应式，手机屏幕下字体自适应 */
  @media (max-width: 768px) {
    .hero h1 {
      font-size: 2rem;
    }
    .hero p {
      font-size: 1.2rem;
    }
  }
</style>

<div class="hero">
  <h1>Welcome to Ariel's World 🌌</h1>
  <p>The world in my eyes</p>
</div>

