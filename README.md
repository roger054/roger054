<!-- README.md -->

<p align="center">
  <!-- Inline SVG Snake animation -->
  <svg width="200" height="80" viewBox="0 0 200 80" fill="none" xmlns="http://www.w3.org/2000/svg" >
    <style>
      .snake-body {
        stroke: #FF6B6B;
        stroke-width: 6;
        fill: none;
        stroke-linecap: round;
        animation: dash 2s linear infinite;
      }
      @keyframes dash {
        to {
          stroke-dashoffset: -1000;
        }
      }
    </style>
    <path class="snake-body" stroke-dasharray="200" stroke-dashoffset="0"
      d="M10 40 Q 40 10, 70 40 T 130 40 T 190 40" />
  </svg>
</p>

<h1 align="center">
  <span class="animated-text">Hi there! 👋 I'm <strong>roger054</strong></span>
</h1>

<style>
  .animated-text {
    display: inline-block;
    font-size: 3em;
    font-weight: 700;
    background: linear-gradient(90deg, #FF6B6B, #FFD93D);
    -webkit-background-clip: text;
    color: transparent;
    transition: transform 0.3s ease, filter 0.3s ease;
    cursor: pointer;
  }
  .animated-text:hover {
    transform: scale(1.1) rotate(3deg);
    filter: drop-shadow(2px 4px 6px rgba(255, 107, 107, 0.7));
  }

  /* Progress bars container */
  .progress-bar {
    background: #eee;
    border-radius: 20px;
    overflow: hidden;
    margin: 8px 0;
    width: 100%;
    max-width: 400px;
    height: 22px;
  }
  .progress-fill {
    background: linear-gradient(90deg, #FF6B6B, #FFD93D);
    height: 100%;
    width: 0;
    border-radius: 20px;
    animation: fillbar 2s ease forwards;
  }
  @keyframes fillbar {
    from { width: 0; }
    to { width: var(--fill-width); }
  }

  /* Animated hover for skill text */
  .skill-text {
    font-weight: 600;
    font-size: 1.2em;
    transition: color 0.3s ease;
    cursor: default;
  }
  .skill-text:hover {
    color: #FF6B6B;
    text-shadow: 0 0 8px #FF6B6B;
  }
</style>

---

## 👨‍💻 About Me

<span class="animated-text" style="font-size:1.5em; cursor:pointer;">
  Passionate full-stack dev, embedded systems fan & cybersecurity explorer.
</span>

---

## 🛠️ Tech Stack & Skills

<div>
  <span class="skill-text">C++</span>
  <div class="progress-bar" aria-label="C++ skill level">
    <div class="progress-fill" style="--fill-width: 95%;"></div>
  </div>
</div>

<div>
  <span class="skill-text">C#</span>
  <div class="progress-bar" aria-label="C# skill level">
    <div class="progress-fill" style="--fill-width: 85%; animation-delay: 0.3s;"></div>
  </div>
</div>

<div>
  <span class="skill-text">Java</span>
  <div class="progress-bar" aria-label="Java skill level">
    <div class="progress-fill" style="--fill-width: 75%; animation-delay: 0.6s;"></div>
  </div>
</div>

<div>
  <span class="skill-text">Python</span>
  <div class="progress-bar" aria-label="Python skill level">
    <div class="progress-fill" style="--fill-width: 70%; animation-delay: 0.9s;"></div>
  </div>
</div>

<div>
  <span class="skill-text">JavaScript</span>
  <div class="progress-bar" aria-label="JavaScript skill level">
    <div class="progress-fill" style="--fill-width: 65%; animation-delay: 1.2s;"></div>
  </div>
</div>

<div>
  <span class="skill-text">Arduino</span>
  <div class="progress-bar" aria-label="Arduino skill level">
    <div class="progress-fill" style="--fill-width: 60%; animation-delay: 1.5s;"></div>
  </div>
</div>

---

## 🚀 Featured Projects

- **DeepDomain v2.0** – Subdomain enumeration tool [Repo](https://github.com/roger054/DeepDomain)  
  Animated, multi-tech scanning, API integration.

- **IoT & Embedded** – Arduino & ESP32 projects: CAN bus, home automation.

- **Web & Mobile** – React, Node.js & Flutter full-stack apps.

---

## 📫 Contact Me

<p>
  <a href="mailto:your-email@example.com" title="Email">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/your-linkedin" title="LinkedIn" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://twitter.com/your-twitter" title="Twitter" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
</p>

---

<p align="center" style="font-style: italic; color: #666;">
  “Code is like humor. When you have to explain it, it’s bad.” – Cory House
</p>
