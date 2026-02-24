---
layout: none
title: TA-LHK Portfolio
---

<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { background: #0d1117; color: #e6edf3; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }

.hero {
  background: linear-gradient(135deg, #1a2a4a 0%, #0d1117 60%);
  border-bottom: 1px solid #30363d;
  padding: 60px 40px 50px;
  text-align: center;
}
.hero h1 { font-size: 2.4em; font-weight: 700; color: #58a6ff; margin-bottom: 12px; }
.hero p { font-size: 1.1em; color: #8b949e; }

.container { max-width: 900px; margin: 0 auto; padding: 48px 24px; }

h2 { font-size: 1.4em; color: #58a6ff; margin-bottom: 20px; padding-bottom: 8px;
  border-bottom: 1px solid #30363d; }

.cards { display: grid; grid-template-columns: repeat(2, 1fr); gap: 16px; margin-bottom: 48px; }
.card {
  background: #161b22;
  border: 1px solid #30363d;
  border-radius: 10px;
  padding: 24px;
  text-decoration: none;
  color: #e6edf3;
  transition: border-color 0.2s, transform 0.2s;
  display: block;
}
.card:hover { border-color: #58a6ff; transform: translateY(-2px); }
.card h3 { font-size: 1.15em; color: #58a6ff; margin-bottom: 8px; }
.card p { font-size: 0.9em; color: #8b949e; line-height: 1.5; }

.about-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-bottom: 48px; }
.about-item { background: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 16px; }
.about-item .label { font-size: 0.75em; color: #8b949e; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 4px; }
.about-item .value { font-size: 0.95em; color: #e6edf3; font-weight: 600; }

.contact a { color: #58a6ff; text-decoration: none; }
.contact a:hover { text-decoration: underline; }
</style>

<div class="hero">
  <h1>TA-LHK</h1>
  <p>Technical Artist Portfolio &mdash; Unreal Engine 5.6</p>
</div>

<div class="container">

  <h2>Categories</h2>
  <div class="cards">
    <a class="card" href="optimization/">
      <h3>Optimization</h3>
      <p>World Partition, Nanite, Lumen 최적화 및 GPU 프로파일링</p>
    </a>
    <a class="card" href="shader/">
      <h3>Shader / HLSL</h3>
      <p>Compute Shader, Custom Shading Model, 마테리얼 최적화</p>
    </a>
    <a class="card" href="pcg/">
      <h3>PCG</h3>
      <p>Procedural Content Generation, WFC, Foliage Scatter</p>
    </a>
    <a class="card" href="pipeline/">
      <h3>Pipeline</h3>
      <p>Python 자동화, 에셋 패키징, 빌드 검증</p>
    </a>
  </div>

  <h2>About</h2>
  <div class="about-grid">
    <div class="about-item"><div class="label">Engine</div><div class="value">Unreal Engine 5.6</div></div>
    <div class="about-item"><div class="label">Role</div><div class="value">Technical Artist</div></div>
    <div class="about-item"><div class="label">Focus</div><div class="value">Optimization, Shader, PCG</div></div>
  </div>

  <h2>Contact</h2>
  <div class="contact">
    <p>GitHub: <a href="https://github.com/vincentleekoo-lgtm">vincentleekoo-lgtm</a></p>
  </div>

</div>
