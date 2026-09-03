<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:000000,100:2b2b2b&height=250&section=header&text=HÜSEYİN%20AYHAN&fontSize=80&desc=Software%20Developer%20%7C%20DevSecOps%20%7C%20Automotive%20%7C%20Game%20Dev&descAlignY=70&fontColor=ffffff&descAlign=62&animation=twinkling" width="100%" />
</div>

## 📌 About Me
**Software Engineer focused on DevSecOps Tools, Automotive Telemetry, and Game Development.**  
I build high-performance developer tooling, low-level hardware interfaces, and immersive game mechanics. From engineering local-first Git secret scanners and automotive ECU tuning suites to designing 2D/3D simulations, I bridge systems programming, security engineering, and interactive software using TypeScript, C#, .NET, and Unity.
<br/>
<p align="center">
  <a href="https://www.instagram.com/huseyyin.ayhann/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

## 🛠️ Tech Stack & Engines

<p align="center">
  <b>Languages & Runtimes</b><br/><br/>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,nodejs,cs,dotnet,py,git,github,sqlite,unity" alt="Tech Stack" />
  </a>
</p>

<p align="center">
  <b>Security & Tooling</b><br>
  <img src="https://img.shields.io/badge/DevSecOps-000000?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Secret_Scanning-E0234E?style=for-the-badge&logo=owasp&logoColor=white" />
  <img src="https://img.shields.io/badge/CLI_Tooling-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

<p align="center">
  <b>Hardware & Automotive Protocols</b><br>
  <img src="https://img.shields.io/badge/OBD1%20/%20OBD2-000000?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/CH341A_Dev-2088FF?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Serial_COM-FF7139?style=for-the-badge&logo=rs-components&logoColor=white" />
</p>
<br/>

## 🎯 Areas I Work In
<table align="center" width="100%">
  <tr>
    <td align="center" width="25%">
      <b>🛡️ DevSecOps & CLI</b><br>
      <sub>Static analysis, Git hooks, leak-proof credential auditing.</sub>
    </td>
    <td align="center" width="25%">
      <b>🏎️ Auto Telemetry</b><br>
      <sub>OBD2 communication, serial injection, and live mapping.</sub>
    </td>
    <td align="center" width="25%">
      <b>🖥️ Desktop Tools</b><br>
      <sub>.NET 8, WinForms GDI+ rendering, EEPROM burner hooks.</sub>
    </td>
    <td align="center" width="25%">
      <b>🕹️ Game Development</b><br>
      <sub>Unity, C#, 2D physics, and high-density entity pooling.</sub>
    </td>
  </tr>
</table>

<br/>

## 🏆 Selected Work

<!-- GITLEAK RADAR VITRIN KARTI -->
<table align="center" width="100%">
  <tr>
    <td>
      <h4>🛡️ GitLeak Radar (v1.0.0)</h4>
      <p>A production-ready, zero-telemetry CLI secret scanner and pre-commit hook written in strict TypeScript. Audits staged Git changes or full repositories locally to block hardcoded API keys, tokens, and database credentials before commits hit version control.</p>
      <sub><b>Built with:</b></sub><br>
      <code>TypeScript</code> <code>Node.js</code> <code>Commander</code> <code>Zod</code> <code>Vitest</code>
      <br/><br/>
      <b>Highlights:</b>
      <ul>
        <li><b>Leak-Safe Findings:</b> Strict masking policy ensures plaintext secrets never enter data models or console/JSON reports.</li>
        <li><b>Git Index Aware:</b> Native <code>--staged</code> auditing with nested directory resolution and automated pre-commit hook installation.</li>
        <li><b>Pipeline Hardened:</b> Deterministic POSIX exit codes (0/1/2) and 10MB memory-safe circuit breaker.</li>
      </ul>
      <a href="https://github.com/gecekusu1979/gitleak-radar">
        <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
  </tr>
</table>

<br/>

<!-- DIGER PROJELER -->
<table align="center" width="100%">
  <tr>
    <!-- SOL TARAFTAKI HONDA TUNER PROJESI -->
    <td width="50%" valign="top">
      <h4>🏎️ HondaTuner V2</h4>
      <p>An open-source, bilingual (EN/TR) .NET 8 telemetry and ECU tuning suite for Honda vehicles. Built as a completely free alternative to legacy graphical platforms.</p>
      <sub><b>Built with:</b></sub><br>
      <code>C#</code> <code>.NET 8</code> <code>WinForms</code> <code>SQLite</code>
      <br/><br/>
      <b>Features:</b>
      <ul>
        <li>Direct physical hardware OBD <code>0x43/0x44</code> serial packet injection.</li>
        <li>Real-time graphical telemetry, data-logging, and live interpolation.</li>
        <li>Native hardware hooks for CH341A / TL866 EPROM reading and saving.</li>
      </ul>
      <a href="https://github.com/gecekusu1979/honda">
        <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
    
    <!-- SAG TARAFTAKI ABONDEATH OYUN PROJESI -->
    <td width="50%" valign="top">
      <h4>💀 Abondeath</h4>
      <p>An action-packed 2D horde-survival game engineered in Unity. Features custom physics and scripts designed to handle massive entity counts without performance degradation.</p>
      <sub><b>Built with:</b></sub><br>
      <code>Unity</code> <code>C#</code> <code>2D Physics</code>
      <br/><br/>
      <b>Features:</b>
      <ul>
        <li>Optimized 2D object pooling for dense enemy waves.</li>
        <li>Custom weapon mechanics, skill trees, and wave progression.</li>
        <li>Modular combat state machines and responsive input handling.</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

---

### 📊 GitHub Overview
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gecekusu1979&theme=tokyonight" alt="Ayhan's Stats" width="60%" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=gecekusu1979&theme=tokyonight&utcOffset=3" alt="Commits" width="60%" />
</p>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=gecekusu1979&label=Profile%20Views&color=00B4DB&style=flat-square" alt="Ayhan's Profile Views" />
</div>
<br>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gecekusu1979/gecekusu1979/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gecekusu1979/gecekusu1979/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Snake" src="https://raw.githubusercontent.com/gecekusu1979/gecekusu1979/output/github-contribution-grid-snake.svg">
  </picture>
</div>
