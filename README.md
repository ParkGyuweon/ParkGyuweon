![header](https://capsule-render.vercel.app/api?type=wave&color=0:83EAF1,100:63A4FF&height=300&section=header&text=Gyuweon%20Park&fontSize=55&fontColor=ffffff&animation=fadeIn&desc=%3E_%20Data%20Engineering%20%7C%20AX%20%7C%20AI-powered%20Services&descSize=20&descAlignY=30)

<p align="center">
  <img src="https://img.shields.io/badge/%3E__data_flows-63A4FF?style=for-the-badge&labelColor=1B2A4A&color=63A4FF" />
  <img src="https://img.shields.io/badge/%5BAX%5D_AI_experience-83EAF1?style=for-the-badge&labelColor=1B2A4A&color=83EAF1" />
  <img src="https://img.shields.io/badge/ship_small_useful_things-4F8CFF?style=for-the-badge&labelColor=1B2A4A&color=4F8CFF" />
</p>

<p align="center"><code>▣ ▣ ▣  build data flows · design AI experiences · keep learning  ▣ ▣ ▣</code></p>

### >_ Now Playing

[![spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/view?uid=3126pwubvrd24qcvamrmxlcv4vfq&cover_image=true&theme=spotify-embed&show_offline=false&background_color=121212&interchange=false&profanity=false&hide_remaster=false&bar_color=53b14f&bar_color_cover=false&mode=light)](https://github.com/kittinan/spotify-github-profile)

<p align="center"><code>◆◇◆</code></p>

### >_ About Me

I am a developer interested in **Data Engineering and AX (AI eXperience)**.  
I like turning raw data, user behavior, and product context into reliable data flows, recommendation logic, and AI-powered user experiences.

Double majoring in Biochemistry and Computer Science at Yonsei University, I combine analytical problem-solving with practical software engineering.

- `focus` **Data Engineering, AX, Data Modeling, Recommendation Systems**
- `learning` Distributed data processing, analytics pipelines, system design, AI-driven product workflows
- `contact` rbdnjs9@gmail.com / rbdnjs7034@naver.com
- `linkedin` [https://www.linkedin.com/in/gyuweon-park/](#)

<p align="center"><code>◆◇◆</code></p>

### >_ What I Build Toward

- **Data foundations for user-facing products**  
  Designing schemas, APIs, and data flows that make product behavior easier to observe, analyze, and improve.

- **AI-powered service experiences**  
  Connecting recommendation logic, user context, and interface design so AI features feel useful inside real workflows.

- **Reliable engineering around data**  
  Practicing database modeling, validation, logging, caching, and deployment basics to keep services understandable and maintainable.

<p align="center"><code>◆◇◆</code></p>

### >_ Tech Stack

**Languages & Core** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Backend & Frameworks** ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-ff1709?style=flat-square&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend & AX** ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

**Database, OS & Tools** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<p align="center"><code>◆◇◆</code></p>

### >_ Featured Projects

#### [01] [the_fluff_road — AI-based Pet Recommendation & Community](https://github.com/ParkGyuweon/the_fluff_road)

A map-based pet-friendly place discovery service where users can search facilities, share reviews, report place information, and receive AI-assisted recommendations.

**My Role**
- Implemented the Django/DRF service layer, recommendation flow, user/auth features, community APIs, admin tools, fixtures, and data visualization pages
- Built AI features around personalized place recommendation, weather-aware home copy, and receipt-based visit verification
- Integrated Kakao Map/Local APIs, weather API, OAuth, and Gemini through a shared service module

**Data & AI Flow**
- Modeled users, pets, places, reviews, posts, comments, reports, saved places, and recommendation relations
- Managed fixture data for 208 pet-friendly facilities and used place/category/location attributes as service data
- Built a two-step recommendation flow: content-based candidate retrieval from user likes/saves, followed by Gemini reranking and reason generation
- Added safeguards for LLM output by restricting recommendation IDs to known candidates and falling back to rule-based results when parsing fails
- Designed cache keys around user interaction counts so recommendation results refresh after likes or saves change

**Product & AX Points**
- Connected map search, filters, roadview thumbnails, reviews, place reports, and recommendations into one place-discovery journey
- Supported trust-building features such as receipt verification, user reports, admin approval, and place data correction
- Added district/category visualizations so service data could be inspected beyond individual place pages

#### [02] [bbanggeut — Motion Recognition & AI Diary Care Service](https://github.com/ParkGyuweon/bbanggeut)

A child-care service that turns screen time into motion-based play, then converts play records and child conversations into diaries and parent reports.

**My Role**
- Led frontend implementation for the child-facing and parent-facing product experience
- Integrated motion-recognition games, character conversation, child diary screens, parent report screens, and profile flows
- Worked across React, TypeScript, MediaPipe, backend APIs, and AI-server responses to connect realtime interaction with service screens

**AX Flow**
- Designed flows for four motion-based games: fruit slicing, picture matching, word matching, and recycling play
- Connected webcam-based hand/arm recognition to interactions that children can understand without extra hardware
- Organized the post-play experience from character conversation to diary creation and parent report review
- Separated child and parent contexts so the same service data could become playful feedback for children and structured observation for guardians

**Engineering Points**
- Worked in a multi-service environment using React, Spring Boot, FastAPI, Redis, Docker, Jenkins, AWS, and Grafana
- Integrated frontend screens with AI and backend services while keeping the user journey centered on play, conversation, diary, and report loops

#### [03] [multithreaded-http-proxy — HTTP Proxy Server](https://github.com/ParkGyuweon/multithreaded-http-proxy)

A plain HTTP proxy server implemented with Python sockets and threads to practice low-level networking fundamentals.

**What It Does**
- Accepts multiple client connections with one worker thread per request
- Parses HTTP requests, resolves target hosts, rewrites headers, and forwards responses back to clients
- Supports configurable URL redirection and runtime image filtering through request keywords
- Produces synchronized logs for request flow, response status, content type, and connection lifecycle

**Why I Included It**
- Shows systems-level understanding behind web services and data products
- Covers TCP sockets, HTTP forwarding, shared state, locking, and defensive handling of malformed requests
- Keeps the implementation small enough to inspect without framework noise

<p align="center"><code>◆◇◆</code></p>

### >_ Learning Direction

I am currently strengthening the bridge between **data systems** and **AI product experience**:

- Data modeling for user behavior, recommendation inputs, and service events
- SQL fundamentals for querying, aggregation, joins, and validation
- Pipeline thinking: how raw product data becomes usable signals
- AX design: how AI outputs should appear, fail, and recover inside user workflows
- System fundamentals: networking, operating systems, and algorithms as the base layer for reliable software

<p align="center"><code>◆◇◆</code></p>

### >_ Algorithm

<div align="center">
  <a href="https://solved.ac/rbdnjs7034">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=rbdnjs7034" alt="Solved.ac Profile" />
  </a>
</div>

<p align="center"><code>◆◇◆</code></p>

### >_ Certificates & Awards

- **2026.06.** SSAFY 1st Semester Excellence Award — Seoul Class 3 Rank 1
- **2026.05.** SQL 개발자(SQLD)
- **2026.04.** 삼성 SW 역량테스트 A+
- **2026.02.** Yonsei University Academic Excellence Award
- **2026.01.** SW Coding Certificate
- **2025.09.** OPIc(English) IM2
- **2025.08.** TOEIC 855
- **2023.02.** Yonsei University Academic Excellence Award
- **2022.08.** Yonsei University Academic Excellence Award

<p align="center"><code>◆◇◆</code></p>

### >_ Repository Map

- **Data / AI / AX**: recommendation services, AI-assisted workflows, motion-recognition product experiences
- **Engineering Fundamentals**: algorithms, HTTP proxying, networking, database modeling, deployment basics
- **Product Context**: projects built around real users, behavior, reports, admin flows, and service feedback loops

<p align="center"><code>[ end of file ]</code></p>

![footer](https://capsule-render.vercel.app/api?type=wave&color=0:63A4FF,100:83EAF1&width=100%&height=100&section=footer&reversal=true)
