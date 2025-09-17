---
layout: default
title: Home
---

<style>
body {
  margin: 0;
  font-family: sans-serif;
  background-color: #111;
  color: white;
}

/* 顶部标题 */
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

/* 主内容区：左列（头像） + 中列（四个卡片） */
.main-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin: 2rem;
}

/* 左列头像 */
.left-column {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-width: 180px;
}

.left-column img.profile {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 4px solid #00ff00;
  object-fit: cover;
}

/* 中列：四个模块卡片 */
.center-column {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.5rem;
  flex: 1;
}

.module-card {
  background: rgba(0,0,0,0.7);
  color: white;
  width: 220px;
  padding: 1.5rem;
  text-align: center;
  border-radius: 12px;
  text-decoration: none;
  transition: transform 0.3s, background 0.3s, box-shadow 0.3s;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

.module-card:hover {
  transform: scale(1.08);
  background: rgba(0,0,0,0.85);
  box-shadow: 0 8px 16px rgba(0,0,0,0.5);
}

.module-card h2 {
  margin: 0.5rem 0;
  font-size: 1.5rem;
}

.module-card p {
  font-size: 1rem;
  color: #ccffcc;
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
  .module-card {
    width: 160px;
    padding: 1rem;
  }
}
</style>

<!-- 顶部标题 -->
<div class="hero">
  <h1>Welcome to Ariel's World 🌌</h1>
  <p>The world in my eyes</p>
</div>

<!-- 主内容区 -->
<div class="main-content">
  <!-- 左列：头像 -->
  <div class="left-column">
    <img class="profile" src="/assets/images/my_photo.jpg" alt="Ariel's Photo">
  </div>

  <!-- 中列：四个模块 -->
  <div class="center-column">
    <a class="module-card" href="/works/">
      <h2>Works</h2>
      <p>Poetry, Novel, Play, Zine</p>
    </a>
    <a class="module-card" href="/research/">
      <h2>Research</h2>
      <p>Essays, Analysis, Studies</p>
    </a>
    <a class="module-card" href="/community/">
      <h2>Community Service</h2>
      <p>Projects, Volunteering</p>
    </a>
    <a class="module-card" href="/other/">
      <h2>Other</h2>
      <p>Travel, Photography, Online Media</p>
    </a>
  </div>
</div>
