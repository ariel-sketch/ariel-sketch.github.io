---
layout: default
title: Home
---

<style>
.hero {
  /* background-image: url('/assets/images/my_bg.jpg'); 取消背景图 */
  background-size: cover;
  background-position: center;
  height: 40vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #00ff00; /* 标题文字绿色 */
  text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
}
.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}
.hero p {
  font-size: 1.5rem;
  color: #66ff66; /* 副标题浅绿色 */
  margin-bottom: 0;
}

.modules {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 2rem 0;
  gap: 1rem;
}
.module-card {
  background: rgba(0,0,0,0.6);
  color: white;
  width: 200px;
  padding: 1rem;
  text-align: center;
  border-radius: 8px;
  text-decoration: none;
  transition: transform 0.2s, background 0.2s;
}
.module-card:hover {
  transform: scale(1.05);
  background: rgba(0,0,0,0.8);
}
.module-card h2 {
  margin: 0.5rem 0;
}

/* 响应式，手机屏幕下 */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2rem;
  }
  .hero p {
    font-size: 1.2rem;
  }
  .module-card {
    width: 150px;
  }
}
</style>

<div class="hero">
  <h1>Welcome to Ariel's World 🌌</h1>
  <p>The world in my eyes</p>
</div>

<div class="modules">
  <a class="module-card" href="/works/">
    <h2>Works</h2>
    <p>Poetry, Novel, Play, Zine</p>
  </a>
  <a class="module-card" href="/research/">
    <h2>Research</h2>
    <p> </p>
  </a>
  <a class="module-card" href="/community/">
    <h2>Community Service</h2>
    <p> </p>
  </a>
  <a class="module-card" href="/other/">
    <h2>Other</h2>
    <p>Travel, Photography, Online Media</p>
  </a>
</div>

