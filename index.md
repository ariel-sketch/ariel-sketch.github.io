---
layout: default
title: Home
---

<style>
body {
  margin: 0;
  font-family: sans-serif;
}

/* 顶部欢迎区 */
.hero {
  text-align: center;
  color: #00ff00;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
  padding: 2rem 1rem;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.hero p {
  font-size: 1.5rem;
  color: #66ff66;
  margin-bottom: 1rem;
}

/* 主内容区，左右两列布局 */
.main-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin: 2rem;
}

/* 左侧块 */
.left-column {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 300px;
}

/* 信息卡片 */
.card {
  background: rgba(0,0,0,0.7);
  color: white;
  padding: 1rem;
  border-radius: 12px;
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0,0,0,0.5);
}

/* 头像 */
.left-column img.profile {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 4px solid #00ff00;
  margin-top: 1rem;
  object-fit: cover;
}

/* 右侧背景装饰或额外内容 */
.right-column {
  flex: 1;
  background-image: url('/assets/images/my_bg.jpg');
  background-size: cover;
  background-position: center;
  border-radius: 12px;
  min-height: 400px;
}

/* 响应式 */
@media (max-width: 768px) {
  .main-content {
    flex-direction: column;
    align-items: center;
  }
  .left-column img.profile {
    width: 120px;
    height: 120px;
  }
  .right-column {
    width: 100%;
    min-height: 250px;
  }
}
</style>

<div class="hero">
  <h1>Welcome to Ariel's World 🌌</h1>
  <p>The world in my eyes</p>
</div>

<div class="main-content">
  <div class="left-column">
    <div class="card">
      <h2>Ariel's Personal Website</h2>
      <p>Introduction and latest updates</p>
    </div>
    <div class="card">
      <h2>Theme</h2>
      <p>High-end, clean, modern design</p>
    </div>
    <img class="profile" src="/assets/images/my_photo.jpg" alt="Ariel's Photo">
  </div>

  <div class="right-column">
    <!-- 可以留空或者加装饰 -->
  </div>
</div>
