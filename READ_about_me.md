<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="400" viewBox="0 0 1200 400">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#f7f4ee"/>
      <stop offset="1" stop-color="#efeae2"/>
    </linearGradient>
  </defs>
  <style>
    .sans { font-family: 'Segoe UI', 'Helvetica Neue', Helvetica, Arial, sans-serif; }
    .mono { font-family: Consolas, 'Courier New', monospace; font-size: 14px; }
    .fade { opacity: 0; animation: fade 1.2s ease-out forwards; }
    .d1 { animation-delay: .2s } .d2 { animation-delay: .5s } .d3 { animation-delay: .8s } .d4 { animation-delay: 1.1s } .d5 { animation-delay: 1.4s }
    @keyframes fade { from { opacity: 0; transform: translateY(8px) } to { opacity: 1; transform: translateY(0) } }
    .drift { animation: drift 14s ease-in-out infinite; }
    .drift2 { animation: drift 18s ease-in-out infinite 3s; }
    @keyframes drift { 0%,100% { transform: translateY(0) } 50% { transform: translateY(-10px) } }
  </style>

  <rect width="1200" height="400" rx="20" fill="url(#bg)"/>

  <circle class="drift" cx="1080" cy="70" r="120" fill="#d6e2d9" opacity="0.6"/>
  <circle class="drift2" cx="1150" cy="330" r="90" fill="#e8d5d0" opacity="0.55"/>
  <circle class="drift2" cx="80" cy="370" r="70" fill="#dcd9ea" opacity="0.5"/>

  <text class="sans fade d1" x="70" y="115" font-size="16" fill="#8fae9b" letter-spacing="2">HELLO, I'M</text>
  <text class="sans fade d2" x="68" y="178" font-size="56" font-weight="700" fill="#2f3440">Nisha Karthikeyan</text>
  <text class="sans fade d3" x="70" y="220" font-size="22" fill="#4a505c">Software Engineer @ Xenovex Technologies</text>
  <text class="sans fade d3" x="70" y="250" font-size="16" fill="#8a8f98">Backend systems · Production APIs · Applied AI</text>

  <g class="fade d4" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="14" font-weight="600">
    <rect x="70" y="278" width="84" height="32" rx="16" fill="#d6e2d9"/>
    <text x="112" y="299" text-anchor="middle" fill="#4f6f5b">Django</text>
    <rect x="164" y="278" width="68" height="32" rx="16" fill="#dcd9ea"/>
    <text x="198" y="299" text-anchor="middle" fill="#5d5783">.NET</text>
    <rect x="242" y="278" width="112" height="32" rx="16" fill="#e8d5d0"/>
    <text x="298" y="299" text-anchor="middle" fill="#8a5a52">PostgreSQL</text>
    <rect x="364" y="278" width="116" height="32" rx="16" fill="#d6e2d9"/>
    <text x="422" y="299" text-anchor="middle" fill="#4f6f5b">LLMs &amp; RAG</text>
    <rect x="490" y="278" width="88" height="32" rx="16" fill="#dcd9ea"/>
    <text x="534" y="299" text-anchor="middle" fill="#5d5783">Angular</text>
  </g>

  <g class="fade d5">
    <circle cx="76" cy="342" r="5" fill="#8fae9b"/>
    <text class="sans" x="90" y="347" font-size="14" fill="#8a8f98">Chennai, India · Open to backend &amp; full-stack roles</text>
  </g>

  <g class="fade d4">
    <rect x="710" y="80" width="410" height="250" rx="16" fill="#ffffff" stroke="#e4ded4"/>
    <circle cx="738" cy="106" r="5.5" fill="#e8d5d0"/><circle cx="756" cy="106" r="5.5" fill="#efe2c4"/><circle cx="774" cy="106" r="5.5" fill="#d6e2d9"/>
    <text class="mono" x="738" y="148" fill="#8a8f98">// currently</text>
    <text class="mono" x="738" y="176"><tspan fill="#8fae9b">shipped</tspan><tspan fill="#4a505c"> = [</tspan></text>
    <text class="mono" x="758" y="200" fill="#4a505c">"govt forest platform",</text>
    <text class="mono" x="758" y="224" fill="#4a505c">"medical platform ui"</text>
    <text class="mono" x="738" y="248" fill="#4a505c">]</text>
    <text class="mono" x="738" y="282"><tspan fill="#9b8fc2">building</tspan><tspan fill="#4a505c"> = "order matching engine"</tspan></text>
    <text class="mono" x="738" y="306"><tspan fill="#c49a91">learning</tspan><tspan fill="#4a505c"> = ["rag", ".net"]</tspan></text>
  </g>
</svg>

<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Nisha Karthikeyan"/>
</p>

<p align="center">
  <a href="https://nishakarithikeyan.framer.website"><img src="https://img.shields.io/badge/Portfolio-8fae9b?style=flat-square&logo=framer&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/nisha-karthikeyan/"><img src="https://img.shields.io/badge/LinkedIn-9b8fc2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://leetcode.com/u/nisha_karithikeyan/"><img src="https://img.shields.io/badge/LeetCode-c49a91?style=flat-square&logo=leetcode&logoColor=white"/></a>
  <a href="https://medium.com/@nishakarithikeyan"><img src="https://img.shields.io/badge/Medium-8a8f98?style=flat-square&logo=medium&logoColor=white"/></a>
  <a href="mailto:nishakarithikeyan@gmail.com"><img src="https://img.shields.io/badge/Email-8fae9b?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<br/>

### About

```python
class Nisha:
    role      = "Software Engineer @ Xenovex Technologies"
    location  = "Chennai, India"
    shipped   = ["Government forest-management platform (Django + PostgreSQL)",
                 "Production medical platform frontend (Angular)"]
    building  = "Real-time order matching engine (ASP.NET Core)"
    exploring = ["LLMs", "RAG", "FastAPI"]
```

<br/>

### Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,cs,dotnet,postgres,mysql,redis,docker,angular,react,ts,tailwind,git,linux&theme=light&perline=15" />
</p>

<br/>

### Projects

| | Project | Stack |
|---|---|---|
| 🍽️ | **[RestroHub](https://github.com/nisha-karithikeyan/restrohub-django)** — food ordering and time-slot table booking with auth and admin tools | Django · PostgreSQL |
| 🧠 | **[Zenith](https://github.com/nisha-karithikeyan/zenith)** — [one line: what it does] | Python · [AI stack] |
| 🗂️ | **[ERD Generator](https://github.com/nisha-karithikeyan/erd-generator-postgres)** — [one line: what it does] | Python · PostgreSQL |

<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nisha-karithikeyan/nisha-karithikeyan/output/snake-dark.svg" />
    <img alt="contributions" src="https://raw.githubusercontent.com/nisha-karithikeyan/nisha-karithikeyan/output/snake-light.svg" />
  </picture>
</p>
