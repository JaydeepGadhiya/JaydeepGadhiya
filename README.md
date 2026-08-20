<h1 align="center">Hi, I'm Jaydeep Gadhiya 👋</h1>

<h3 align="center">Senior Laravel Developer &nbsp;•&nbsp; CI/CD Developer &nbsp;•&nbsp; Team Lead</h3>

<p align="center">
  <em>"I build Laravel apps &amp; the tools that debug them."</em>
</p>

<p align="center">
  7+ years building scalable Laravel applications, developer security tooling, and AI-powered real-time systems.<br />
  Based in Surat, India.
</p>

<p align="center">
  <a href="https://jaydeepgadhiya.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-jaydeepgadhiya.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/JaydeepGadhiya">
    <img src="https://komarev.com/ghpvc/?username=JaydeepGadhiya&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />
  </a>
  <a href="https://github.com/JaydeepGadhiya?tab=followers">
    <img src="https://img.shields.io/github/followers/JaydeepGadhiya?label=Followers&style=flat&color=0e75b6" alt="GitHub followers" />
  </a>
</p>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,laravel,mysql,mongodb,redis,nodejs,express,vue,js,git,githubactions,docker,linux,vscode,phpstorm" />
</p>

---

## 📦 Open Source

Six MIT-licensed developer tools across the Laravel and Node.js ecosystems.

### 🛡️ Laravel Security Packages

A suite of security-focused Laravel packages for detecting vulnerabilities, inspecting application internals, and validating deployment readiness.

[![guarddog](https://img.shields.io/packagist/v/jaydeep/laravel-guarddog?style=flat&label=guarddog)](https://packagist.org/packages/jaydeep/laravel-guarddog)
[![Downloads](https://img.shields.io/packagist/dt/jaydeep/laravel-guarddog?style=flat&color=brightgreen)](https://packagist.org/packages/jaydeep/laravel-guarddog)
[![xray](https://img.shields.io/packagist/v/jaydeep/laravel-xray?style=flat&label=xray)](https://packagist.org/packages/jaydeep/laravel-xray)
[![Downloads](https://img.shields.io/packagist/dt/jaydeep/laravel-xray?style=flat&color=brightgreen)](https://packagist.org/packages/jaydeep/laravel-xray)
[![preflight](https://img.shields.io/packagist/v/jaydeep/laravel-preflight?style=flat&label=preflight)](https://packagist.org/packages/jaydeep/laravel-preflight)
[![Downloads](https://img.shields.io/packagist/dt/jaydeep/laravel-preflight?style=flat&color=brightgreen)](https://packagist.org/packages/jaydeep/laravel-preflight)

| Package | What it does | Packagist | Source |
|---|---|---|---|
| laravel-guarddog | Security scanner for SQL injection, missing auth middleware, and XSS risks | [packagist.org](https://packagist.org/packages/jaydeep/laravel-guarddog) | [GitHub](https://github.com/JaydeepGadhiya/laravel-guarddog) |
| laravel-xray | Architecture visualization, dead code detection, and dependency mapping for large apps | [packagist.org](https://packagist.org/packages/jaydeep/laravel-xray) | [GitHub](https://github.com/JaydeepGadhiya/laravel-xray) |
| laravel-preflight | Upgrade compatibility checker scanning for breaking changes across Laravel 8–13 | [packagist.org](https://packagist.org/packages/jaydeep/laravel-preflight) | [GitHub](https://github.com/JaydeepGadhiya/laravel-preflight) |

### 🔍 Laravel Developer Tools

Observability and profiling packages for understanding what your Laravel application does at runtime.

[![time-machine](https://img.shields.io/packagist/v/jaydeep/laravel-time-machine?style=flat&label=time-machine)](https://packagist.org/packages/jaydeep/laravel-time-machine)
[![Downloads](https://img.shields.io/packagist/dt/jaydeep/laravel-time-machine?style=flat&color=brightgreen)](https://packagist.org/packages/jaydeep/laravel-time-machine)
[![queue-monitor](https://img.shields.io/packagist/v/jaydeep/laravel-queue-monitor?style=flat&label=queue-monitor)](https://packagist.org/packages/jaydeep/laravel-queue-monitor)
[![Downloads](https://img.shields.io/packagist/dt/jaydeep/laravel-queue-monitor?style=flat&color=brightgreen)](https://packagist.org/packages/jaydeep/laravel-queue-monitor)

| Package | What it does | Packagist | Source |
|---|---|---|---|
| laravel-time-machine | Request profiler and debugger with millisecond timelines, SQL query capture, and a Gantt-style dashboard | [packagist.org](https://packagist.org/packages/jaydeep/laravel-time-machine) | [GitHub](https://github.com/JaydeepGadhiya/laravel-timemachine) |
| laravel-queue-monitor | Full queue job lifecycle tracking (pending/running/completed/failed) with a web dashboard and Artisan command | [packagist.org](https://packagist.org/packages/jaydeep/laravel-queue-monitor) | [GitHub](https://github.com/JaydeepGadhiya/laravel-queue-monitor) |

### ⚡ Installation

Install any package via Composer:

```bash
# Security tooling
composer require jaydeep/laravel-guarddog --dev
composer require jaydeep/laravel-xray --dev
composer require jaydeep/laravel-preflight --dev

# Developer tooling
composer require jaydeep/laravel-time-machine --dev
composer require jaydeep/laravel-queue-monitor
```

All packages support **Laravel 8–13** and **PHP 7.4–8.4**, with zero-config auto-discovery. See each package's README for usage details and available Artisan commands.

### 🟢 Node.js & Express Tooling

Static analysis for Node.js and Express apps — parses actual code structure (scope trees, module graphs, route models) instead of matching patterns, so it catches bugs that normally only surface in production.

[![npm](https://img.shields.io/npm/v/@jaydeepgadhiya/guarddog?style=flat&label=express-guarddog&color=cb3837)](https://www.npmjs.com/package/@jaydeepgadhiya/guarddog)
[![Downloads](https://img.shields.io/npm/dt/@jaydeepgadhiya/guarddog?style=flat&color=brightgreen)](https://www.npmjs.com/package/@jaydeepgadhiya/guarddog)

| Package | What it does | npm | Source |
|---|---|---|---|
| express-guarddog | 61 security rules across injection, Express, async, Mongoose, crypto, and logic — auth bypasses, unawaited promises, schema typos, unprotected routes, JWT misconfig — with severity/confidence scoring and HTML + JSON reports | [npmjs.com](https://www.npmjs.com/package/@jaydeepgadhiya/guarddog) | [GitHub](https://github.com/JaydeepGadhiya/express-guarddog) |

```bash
# Run it without installing
npx @jaydeepgadhiya/guarddog scan

# Or add it to the project
npm install --save-dev @jaydeepgadhiya/guarddog
```

Zero config for **JavaScript, TypeScript, JSX, and TSX** on **Node 16+**, with CommonJS and ES module support. Accepted risks can be silenced with suppression comments.

---

## 🚀 Featured Projects

| Project | Description | Link |
|---|---|---|
| **Portfolio** | The full rundown — packages, client work, skills, and experience since 2019. | [Visit](https://jaydeepgadhiya.netlify.app) |
| **ToolForge** | Free, browser-based developer toolkit — JSON formatter, Base64, UUID generator, hash tools, URL encoder, and more. Runs entirely client-side, no sign-up. | [Launch](https://jaydeepgadhiya.github.io/toolforge/) |
| **CodeYard** | Free, structured frontend learning platform — 20 modules, 121 lessons, 10 portfolio projects, and 9 achievement badges across 7 zones. | [Start Learning](https://codeyard.pages.dev) |
| **Snake Puzzle Adventure** | HTML5 logic puzzle built with Phaser 3 — 50 BFS-verified solvable levels, solver-backed hints, mobile-ready via Capacitor. | [Play](https://snake-puzzle-adventure.netlify.app) |
| **GitHub Badges & Achievements** | Community guide to unlocking GitHub profile badges the legitimate way, with difficulty ratings and time estimates. | [View Guide](https://jaydeepgadhiya.github.io/github-badges-achievements) |

---

## 🌐 Community

**DevNest** — a daily.dev Squad for developers sharing Laravel, PHP, DevOps, and open-source finds. Posts, discussions, and tools worth bookmarking, all in one feed.

<p align="center">
  <a href="https://daily.dev/squads/devnest" target="_blank">
    <img src="https://img.shields.io/badge/Join%20DevNest%20Squad-daily.dev-CE3DF3?style=for-the-badge&logo=dailydotdev&logoColor=white" alt="Join DevNest on daily.dev" />
  </a>
</p>

<p align="center">
  <a href="https://daily.dev/jaydeepgadhiya" target="_blank">
    <img src="https://img.shields.io/badge/Follow%20me%20on%20daily.dev-@jaydeepgadhiya-1a1a1a?style=for-the-badge&logo=dailydotdev&logoColor=CE3DF3" alt="Follow Jaydeep Gadhiya on daily.dev" />
  </a>
</p>

---

## 🤝 Connect

<p align="center">
  <a href="https://jaydeepgadhiya.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-jaydeepgadhiya.netlify.app-00C7B7?style=flat&logo=netlify&logoColor=white" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="https://github.com/JaydeepGadhiya" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-JaydeepGadhiya-181717?style=flat&logo=github" alt="GitHub" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/jaydeep-gadhiya/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-jaydeep--gadhiya-0077B5?style=flat&logo=linkedin" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://jaydeepgadhiya.blogspot.com" target="_blank">
    <img src="https://img.shields.io/badge/Blog-jaydeepgadhiya-FF5722?style=flat&logo=blogger&logoColor=white" alt="Blog" />
  </a>
  &nbsp;
  <a href="https://daily.dev/jaydeepgadhiya" target="_blank">
    <img src="https://img.shields.io/badge/daily.dev-jaydeepgadhiya-CE3DF3?style=flat&logo=dailydotdev&logoColor=white" alt="daily.dev" />
  </a>
  &nbsp;
  <a href="mailto:jaydeepgadhiya5699@gmail.com">
    <img src="https://img.shields.io/badge/Email-jaydeepgadhiya5699@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

<p align="center"><em>Building products instead of just projects.</em></p>
