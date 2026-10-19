---
theme: jekyll-theme-cayman
title: Home
---

# Hi, I am just tryin to figure out life 👋

Welcome to my personal website!

## About Me
![My Photo](test0.jpg)

I'm a junior interested in tech, new ideas and learning new things.
I'm pretty good at overthinking, judging people and getting into trouble.

## Interests 
<!-- - AI (bruh idk this was AI Generated) -->
- Programming (lmao no way)
- Math
- Insta reels

## What I'm doing (actually, not doing)
- Studying (bruhh)
- Building projects (faahhh)
- Writing notes 


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ketan Reddy Yeruva | Personal Site</title>
  <style>
    :root {
      --bg: #0f172a;
      --card-bg: #1e293b;
      --accent: #38bdf8;
      --text: #f8fafc;
      --subtext: #94a3b8;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2rem 1rem;
    }

    .container {
      max-width: 750px;
      margin: 0 auto;
    }

    .hero {
      display: flex;
      align-items: center;
      gap: 2rem;
      margin-bottom: 2.5rem;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--accent);
    }

    h1 { font-size: 2rem; margin-bottom: 0.5rem; }
    .subtitle { color: var(--subtext); font-size: 1.1rem; }

    .section {
      background: var(--card-bg);
      padding: 1.5rem;
      border-radius: 12px;
      margin-bottom: 1.5rem;
      border: 1px solid rgba(255,255,255,0.05);
    }

    .section h2 {
      color: var(--accent);
      margin-bottom: 1rem;
      font-size: 1.25rem;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .tag {
      background: rgba(56, 189, 248, 0.1);
      color: var(--accent);
      padding: 0.3rem 0.8rem;
      border-radius: 20px;
      font-size: 0.9rem;
    }

    ul { list-style-type: none; }
    li { margin-bottom: 0.5rem; color: var(--subtext); }
    li::before { content: "⚡ "; }

    @media (max-width: 600px) {
      .hero { flex-direction: column; text-align: center; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="hero">
      <img src="test0.jpg" alt="Ketan Reddy Yeruva" class="avatar" />
      <div>
        <h1>Ketan Reddy Yeruva 👋</h1>
        <p class="subtitle">Junior • Tech Explorer • Lifelong Learner</p>
      </div>
    </header>

    <main>
      <section class="section">
        <h2>About Me</h2>
        <p>I'm interested in building cool tech, exploring new ideas, and constantly learning. When I'm not overthinking or getting into trouble, you can find me experimenting with code.</p>
      </section>

      <section class="section">
        <h2>Interests & Tech</h2>
        <div class="tags">
          <span class="tag">Programming</span>
          <span class="tag">Mathematics</span>
          <span class="tag">Artificial Intelligence</span>
          <span class="tag">Web Development</span>
        </div>
      </section>

      <section class="section">
        <h2>Current Focus</h2>
        <ul>
          <li>Building real-world coding projects</li>
          <li>Deepening computer science concepts</li>
          <li>Writing tech notes and docs</li>
        </ul>
      </section>
    </main>
  </div>
</body>
</html>