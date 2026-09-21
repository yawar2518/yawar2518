<a href="https://yawarabbas.vercel.app">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:050811,50:0a2540,100:FFB547&height=200&section=header&text=Yawar%20Abbas&fontSize=70&fontColor=F4F4F0&animation=fadeIn&fontAlignY=38&desc=I%20build%20software%20that%20survives%20real%20infrastructure%2C%20not%20just%20localhost&descSize=18&descAlignY=60&descColor=FFB547" alt="Yawar Abbas banner" />
</a>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=FFB547&center=true&vCenter=true&width=800&lines=Full+Stack+Developer+working+with+Django+and+React;AI+and+Agentic+Systems+Engineer;Cofounder+of+a+Fiber+ISP+with+over+300+customers;I+build+production+systems%2C+not+assignments)](https://git.io/typing-svg)

</div>

<div align="center">

<img src="https://img.shields.io/badge/Location-Lahore%2C_Pakistan-050811?style=for-the-badge&labelColor=FFB547&color=0a2540" alt="Location" />
<img src="https://img.shields.io/badge/Availability-Open_to_Remote_Work-050811?style=for-the-badge&labelColor=00D4FF&color=0a2540" alt="Remote" />
<img src="https://img.shields.io/badge/Availability-Open_to_Internships-050811?style=for-the-badge&labelColor=FFB547&color=0a2540" alt="Open to work" />

<br/><br/>

<a href="https://www.linkedin.com/in/yawar-abbas-5b2773275/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://yawarabbas.vercel.app"><img src="https://img.shields.io/badge/Portfolio-FFB547?style=for-the-badge&logo=vercel&logoColor=050811" alt="Portfolio"/></a>
<a href="mailto:1yawarabbas1@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<br/>

## Who I Am

```python
class YawarAbbas:
    def __init__(self):
        self.role         = "Full Stack and AI Systems Developer"
        self.education    = "BS Software Engineering at UMT Lahore, 2023 to 2027"
        self.company      = "SE Intern at AgileTech Studio"
        self.venture      = "Cofounder of a Fiber ISP, grew from 20 to over 300 customers in 9 months"
        self.building     = "asmaan.com, a satellite first real estate marketplace"
        self.focus        = ["backend architecture", "agentic AI", "geospatial", "devops"]

    def ships(self):
        return "production systems that are deployed, monitored, and actually used"
```

> Before I wrote a line of Django, I was in the field, splicing fiber and knocking on doors in
> Choti Zareen. I convinced customers to pre pay before a single cable was laid, set up the
> server room, and configured the MikroTik routers. Growing an ISP from zero taught me more about
> execution and trust than any course could. Now I bring that same *"make it actually work"*
> mindset to code.

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Argus, Parking Ops Intelligence](https://argu.live)
**B2B SaaS, sole developer, live in production**

Real time parking facility intelligence platform. Ingests live IoT sensor data over **MQTT**,
stores it in **TimescaleDB** hypertables, detects anomalies with **Isolation Forest**, and
forecasts occupancy with **Prophet**, then pushes the results live to a dashboard over **WebSocket**.

Built and deployed solo: 9 Docker services on Oracle Cloud, Nginx with SSL, RBAC, and 26 tests.

`Django 5` `FastAPI` `Celery` `TimescaleDB` `MQTT` `WebSocket` `Prophet` `Docker`

[![Repo](https://img.shields.io/badge/Source-facility--intelligence-181717?style=flat-square&logo=github)](https://github.com/yawar2518/facility-intelligence)
[![Live](https://img.shields.io/badge/Live-argu.live-FFB547?style=flat-square&logo=vercel&logoColor=050811)](https://argu.live)

</td>
<td width="50%" valign="top">

### [Fyt, AI Powered Job Matching](https://fyt-opal.vercel.app)
**AI SaaS, solo build, live in production**

Job boards match on keywords, so you miss roles if you don't name the exact skill. Fyt reads a
plain English description of who you are, infers your skills and level, scrapes live LinkedIn
listings, and ranks every match from 0 to 100 with matching skills, missing skills, and an honest concern.

Includes a **CV Studio** for ATS review and wizard based CV generation, plus Claude powered
company research and cover letter tailoring.

`Next.js 16` `React 19` `FastAPI` `Supabase` `Claude API` `Solari SDK`

[![Repo](https://img.shields.io/badge/Source-solari--cookbook-181717?style=flat-square&logo=github)](https://github.com/yawar2518/solari-cookbook)
[![Live](https://img.shields.io/badge/Live-fyt--opal.vercel.app-FFB547?style=flat-square&logo=vercel&logoColor=050811)](https://fyt-opal.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Agentic IoT Controller](https://agentic-iot-controller.vercel.app/)
**LLM connected to real hardware, live demo**

An LLM agent that controls **physical hardware** through natural language. Say *"the room's too
hot, cool it down"* and the agent reads live **ESP32** sensor data, reasons over it, and flips a
real relay that switches on a fan.

A true feedback loop between a language model and the physical world, with tool calling, memory,
guardrails, and voice control.

`FastAPI` `Groq LLM` `ESP32` `MicroPython` `JWT` `React` `CI/CD`

[![Repo](https://img.shields.io/badge/Source-agentic--iot--controller-181717?style=flat-square&logo=github)](https://github.com/yawar2518/agentic-iot-controller)
[![Live](https://img.shields.io/badge/Live-Demo-FFB547?style=flat-square&logo=vercel&logoColor=050811)](https://agentic-iot-controller.vercel.app/)

</td>
<td width="50%" valign="top">

### [AI Voice Cloning for IVR](https://github.com/yawar2518/ivr-voice-cloning)
**Self hosted TTS, backend and AI engineer**

Replaces the voice actor and studio loop for business phone systems. Clone a voice once, then
generate unlimited IVR prompts from a dashboard. Self hosted **Chatterbox TTS** on GPU, a
seven step approval workflow, and **EBU R128** audio quality gates before anything goes live.

Wrote a formal API contract together with the frontend engineer before writing any code.

`Django` `FastAPI` `Celery` `PyTorch` `Chatterbox` `FFmpeg` `S3` `Docker`

[![Repo](https://img.shields.io/badge/Source-ivr--voice--cloning-181717?style=flat-square&logo=github)](https://github.com/yawar2518/ivr-voice-cloning)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [asmaan.com, My Startup](https://yawarabbas.vercel.app)
**Satellite first real estate, team lead**

Pakistan's first real estate marketplace where you browse properties on **satellite imagery**
instead of stock photos. Leading a 3 person team: **PostGIS** geospatial queries, live **Mapbox**
price pins, a listing verification state machine, and an **XGBoost** neighbourhood scoring model.

A Jira backlog of more than 170 tasks, agile sprints, and a production stack.

`Django 5` `React 18` `PostGIS` `GeoDjango` `Mapbox GL JS` `XGBoost`

[![Portfolio](https://img.shields.io/badge/About-Portfolio-00D4FF?style=flat-square&logo=vercel&logoColor=050811)](https://yawarabbas.vercel.app)

</td>
<td width="50%" valign="top">

<br/>

*Argus, the Agentic IoT Controller, and the IVR voice cloning system were built during my
software engineering internship at **AgileTech Studio**. Fyt and asmaan.com are my own products.*

</td>
</tr>
</table>

<br/>

## Tech Arsenal

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend and AI**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white)

**Data, Infra, and DevOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

</div>

<br/>

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats-eight-topaz.vercel.app/api?username=yawar2518&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=050811&title_color=FFB547&icon_color=00D4FF&text_color=F4F4F0&ring_color=FFB547" alt="GitHub Stats" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=yawar2518&hide_border=true&background=050811&ring=FFB547&fire=00D4FF&currStreakLabel=FFB547&sideLabels=F4F4F0&currStreakNum=F4F4F0&sideNums=00D4FF&dates=8B8B8B&stroke=FFB547" alt="GitHub Streak" />

</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yawar2518/yawar2518/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yawar2518/yawar2518/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/yawar2518/yawar2518/output/github-contribution-grid-snake-dark.svg" width="95%" />
</picture>

</div>

<div align="center">

<img src="https://github-trophies.vercel.app/?username=yawar2518&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=4&margin-h=4" alt="Trophies" />

</div>

<br/>

## Currently in 7th Semester

<div align="center">

`Machine Learning` `Information Retrieval` `Software Quality Engineering` `Software Project Management` `Software Reengineering`

</div>

<br/>

<div align="center">

### Let's build something worth shipping

<img src="https://komarev.com/ghpvc/?username=yawar2518&style=for-the-badge&color=FFB547&label=PROFILE+VIEWS" alt="Profile views" />

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFB547,50:0a2540,100:050811&height=120&section=footer" alt="footer" />

</div>
