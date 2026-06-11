<!-- Animated Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d9488&height=200&section=header&text=Moses%20Maina&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Systems-Driven%20Full-Stack%20Engineer%20|%20AI-Augmented%20Development&descAlignY=55&descSize=18" />
</p>

<!-- Dynamic Typing -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Building%20secure%20products%20end-to-end;AI-assisted%20workflows%20%26%20performance;Turning%20ideas%20into%20production%20systems&center=true&width=600&height=50&color=0d9488&font=Inter&pause=1000" />
</p>

<p align="center">
  <em>Mid-level engineer shipping real-world impact through clean systems and intelligent automation</em>
</p>

<!-- Socials -->
<p align="center">
  <a href="https://linkedin.com/in/moses-ongware" title="LinkedIn">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://moses-maina-portfolio.vercel.app/" title="Portfolio">
    <img src="https://img.shields.io/badge/Portfolio-%230d9488.svg?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  <a href="mailto:cmosesmaina@gmail.com" title="Email">
    <img src="https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About Me

I'm a systems-driven full-stack engineer who builds scalable applications with Node.js, React, and PostgreSQL, but no stack defines me. I decompose messy problems, trace root causes, and design stable architectures before writing code.

My workflow centers on systems thinking, clear abstractions, and deliberate tradeoffs. I care about reliability, performance, cost, and long-term maintainability.

AI is core to how I work, not as a shortcut, but as a thinking partner. Through agentic coding, I challenge assumptions, validate decisions, and prototype deliberately. Strong judgment plus effective AI collaboration makes engineers unbreakable.

I own what I build, from architecture to production. I mentor, review ruthlessly, and communicate tradeoffs clearly, because clarity scales better than cleverness.

I'm interested in projects and teams that value system design, long-term scalability, and deliberate engineering over rushed solutions.

---

## What I Do

<table>
<tr>
<td width="50%">

**Product Engineering**
- Full-stack applications **end-to-end**
- **Performance & optimization** for real users
- **Security, auth & access control** by design

</td>
<td width="50%">

**AI Integration**
- **AI-assisted workflows** that multiply productivity
- **Prompt engineering** for decision-making
- Turning complexity into **clean, scalable systems**

</td>
</tr>
</table>

> *I care equally about **product impact** and **technical depth** - good systems do both.*

---

## Now Building

<div align="center">

[![WhatsApp Product Verification](https://img.shields.io/badge/%F0%9F%93%B1%20WhatsApp%20Product%20Verification-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=1e293b)](https://drive.google.com/file/d/1BdUkJHmL-Ukdo0jpJoPSkKfXYp_lkJei/view?usp=drive_link)

</div>

<p align="center">
  <strong>Enterprise system helping brands fight counterfeiting via WhatsApp verification</strong><br>
  <em>React • Node.js • PostgreSQL • Meta WhatsApp API • QR Generation • Row-level locking</em>
</p>

**Priorities:** Security-first • Sub-2 second response • Scale to millions • Real-time fraud detection

---

**Also seeking:**
- Internship opportunities
- Freelance collaborations  
- Early-stage startup ventures

---

## Engineering Philosophy

<div align="center">

| Principle | Stance |
|:----------|:-------|
| Plan first, code second | Agree |
| AI is a multiplier, not a replacement | Agree |
| Simple systems beat clever ones | Agree |
| Security and correctness are non-negotiable | Agree |
| *Better to build small with real impact than massive without* | **Core belief** |

</div>

---

## Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,typescript,nodejs,express,postgres,mongodb,prisma" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=tailwind,materialui,flutter,docker,git,github,vercel,vite" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=fastapi,python,javascript,figma,redux,nginx,redis" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextauth,jwt,openai,meta" />
  </a>
</p>

## Breakdown:
- **Frontend:** Next.js, React 19, TypeScript, Vite, Flutter, React Router DOM 7, React Hook Form
- **UI & Design:** Tailwind CSS 4, Material-UI, Shadcn/ui, Lucide React, Recharts, Figma
- **Backend & APIs:** Node.js, Express 4, FastAPI, Python, JavaScript, TypeScript, Axios, Winston, Zod 3, NextAuth
- **Database & Persistence:** PostgreSQL 14+, MongoDB, Prisma, Redis (Upstash), node-pg, connection pooling
- **Security & Auth:** JWT, Bcrypt, Helmet 7, CORS, Rate Limiter Flexible, HMAC-SHA256 validation, input sanitization, XSS prevention, role-based access control
- **Testing & Performance:** Jest 29, Supertest, React Testing Library, k6 (load testing)
- **DevOps & Deployment:** Docker, Git, GitHub, Vercel, Render, Nginx
- **Integrations:** Meta Cloud API v18, OpenAI, Webhooks, E.164 phone validation, rate limiting (10/hour)
- **Utilities:** QRCode, UUID, CSV parser, Fast-CSV 5, Dotenv 16

---

## Featured Projects
### WhatsApp Product Verification — Anti-Counterfeiting Platform

<div style="border: 1px solid #334155; border-radius: 12px; padding: 20px; margin: 16px 0; background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);">

**Enterprise-grade anti-counterfeiting platform** processing millions of product verifications via WhatsApp with sub-24ms response times and zero failed requests under peak load.

**Database Architecture**
- PostgreSQL row-level locking (`SELECT FOR UPDATE`) preventing race conditions and duplicate activations across concurrent verification requests
- Strategic indexing (batch_no, status, created_at, verified_at) achieving O(log n) query complexity
- Optimized connection pooling (50 concurrent) with prepared statement caching for sustained high-throughput

**Security Implementation**
- HMAC-SHA256 webhook signature validation ensuring cryptographically verified Meta WhatsApp API messages
- JWT authentication with role-based access control (RBAC) and 24h token expiry
- Dual-layer rate limiting: 10 verifications/hour per phone, 100 requests/minute per IP preventing brute force
- Cryptographically secure code generation excluding ambiguous characters (O,0,I,1) enabling 34B+ unique combinations

**API Engineering**
- Sub-24ms p95 response times validated through k6 load testing at 200 concurrent users
- JSONB metadata storage capturing complete audit trails with full verification traceability
- Field-selective database queries minimizing payload overhead

**Core Features**
- Real-time React admin dashboard with live verification metrics and batch analytics
- Batch management system allowing instant blocking of entire production batches
- QR code generation for printable product stickers with embedded verification URLs
- Multi-format export (CSV/Excel) with embedded QR codes for distribution
- Complete audit logging tracking every verification attempt with phone, timestamp, and result

Built with **Node.js · TypeScript · PostgreSQL · React · Meta WhatsApp Cloud API**

</div>

<p align="right">
  <a href="https://drive.google.com/file/d/1BdUkJHmL-Ukdo0jpJoPSkKfXYp_lkJei/view?usp=drive_link">
    <img src="https://img.shields.io/badge/Live_Demo-0d9488?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

### TaskFlow — Project Management Platform

<div style="border: 1px solid #334155; border-radius: 12px; padding: 20px; margin: 16px 0; background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);">

**High-performance project management platform** engineered for sub-50ms API response times at 1000+ task scale.

**Database Optimization**
- Compound MongoDB indexes (project+status, column+board, tasks) achieving O(log n) query complexity
- Aggregation pipelines for analytics — eliminated N+1 queries, reduced DB round-trips by 60%
- Strategic schema design with embedded task references for O(1) board loads

**Caching Architecture**
- Tiered Redis TTL strategy: 15-min static boards, 2-min volatile tasks, 2-min dashboard stats
- Intelligent cache invalidation on mutations + warming on project creation
- Stale-while-revalidate pattern — instant UI with background data refresh

**API Engineering**
- Single-purpose endpoints: `/dashboard/stats` aggregates 4 collections server-side vs 2 separate calls
- Field-selective MongoDB projections reducing payload sizes by 70%
- Request timing middleware for production bottleneck detection (>500ms alerts)

**Core Features**
- Secure JWT authentication with email verification and password recovery
- Interactive Kanban workflow with drag-and-drop across customizable columns
- Real-time task assignment with priority levels, due dates, and progress tracking
- Analytics dashboard with visual progress indicators and activity feeds

Built with **Next.js · TypeScript · MongoDB · Redis · React Query**

</div>

<p align="right">
  <a href="https://taskflow-zeta-dusky.vercel.app/">
    <img src="https://img.shields.io/badge/Live_Demo-0d9488?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

### AI-Powered Fitness & Wellness Platform

<div style="border: 1px solid #334155; border-radius: 12px; padding: 20px; margin: 16px 0; background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);">

**Full-stack health tracking ecosystem** combining workout analytics, nutrition monitoring, and mental health assessment with real-time ML-powered recommendations serving personalized insights with sub-500ms response times.

**Microservices Architecture**
- 3-tier decoupled design: React frontend → Node.js API gateway → Python Flask ML service
- Socket.IO WebSocket clusters enabling real-time gamification updates and live activity feeds
- Horizontal scaling support with stateless JWT authentication and isolated service deployment

**Machine Learning Engine**
- 3 production-grade RandomForest classifiers (scikit-learn) trained on 30K+ synthetic samples
- Feature engineering with one-hot encoding for categorical data (moods, activity types)
- Confidence-scored predictions with graceful fallback to rule-based logic when ML uncertainty > 0.4
- Time-weighted trend analysis using exponential decay (recent check-ins weighted 2-3x higher)
- Volatility detection algorithms classifying patterns as consistent/moderate/fluctuating

**Performance Engineering**
- HTTP keep-alive connection pooling reducing TCP handshake overhead by ~65% for ML service calls
- Multi-layer caching strategy: Flask bounded LRU (100 entries, 5-min TTL) + Node.js LRU (4-min TTL) + client SessionStorage
- Batch API endpoint (`/api/ai/all`) parallelizing 3 recommendation streams into single request (~350ms latency reduction)
- Async model loading eliminating cold-start timeouts on Render free tier (server ready in <2s vs 8s)
- Optimized cache key bucketing improving hit rates from ~10% to ~70% through value quantization

**Database Architecture**
- MongoDB with strategic compound indexing (userId + date) achieving O(log n) query complexity for time-series health logs
- 5 specialized schemas: User (embedded device tokens), Workout, Nutrition, MentalHealth, Gamification
- Atomic streak calculations with concurrent update protection via Mongoose optimistic locking

**Security Implementation**
- JWT access/refresh token rotation with bcryptjs password hashing (salt rounds: 10)
- OAuth2 flows for Google Fit and Fitbit integrations with automatic token refresh
- Express-rate-limit: 100 requests per 15-minute window with IP + userId dual key generation
- CORS whitelist with origin validation and credential-safe cross-origin policies
- Environment-based secrets management with render.yaml zero-config deployment

**Device Integration**
- Google Fit API: calories.expended + heart_rate.bpm real-time synchronization
- Fitbit Web API: activities + heart rate intraday data with automatic reconnection
- Token refresh handling with automatic disconnect on persistent auth failures

**Core Features**
- **Workout Intelligence**: Heart rate zone analysis (Tanaka formula), ML-generated intensity recommendations, weekly volume tracking
- **Nutrition Analytics**: Macronutrient ratio analysis, meal timing pattern detection, age/gender-specific caloric guidance
- **Mental Health Insights**: Mood trend analysis with volatility tracking, stress level progression monitoring, personalized coping strategies
- **Gamification Engine**: Point accrual across 3 categories, streak maintenance with anti-cheat validation, achievement unlock system with confetti rewards
- **Real-time Dashboard**: Chart.js visualizations with ApexCharts integration, live notification feed via Socket.IO rooms

Built with **React 18 · Node.js · Express · MongoDB · Python Flask · scikit-learn · Socket.IO · Docker-ready**

</div>

<p align="right">
  <a href="https://drive.google.com/file/d/1X5lo3IBWAwOMf14NYUZI8D0OR4TGH0tR/view?usp=drive_link">
    <img src="https://img.shields.io/badge/Live_Demo-0d9488?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

</div>

---

## GitHub Stats

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=CamlineKe&show_icons=true&theme=dark&hide_border=true&bg_color=0f172a&title_color=0d9488&icon_color=0d9488&cache_seconds=1800" />
    </td>
    <td>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=CamlineKe&theme=dark&hide_border=true&background=0f172a&ring=0d9488&fire=0d9488&currStreakLabel=0d9488&cache_seconds=1800" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CamlineKe&theme=dark&hide_border=true&bg_color=0f172a&title_color=0d9488&layout=compact&cache_seconds=1800" />
    </td>
  </tr>
</table>

---

## Credibility

- Computer Science Graduate
- Freelance experience shipping **production systems used by real users**
- Built and maintained **secure, high-performance applications**

---

## Let's Build Something

<p align="center">
  <strong>Open for:</strong> Full-time roles • Freelance work • Collaborations • Startup ideas
</p>

<p align="center">
  <a href="https://linkedin.com/in/moses-ongware">
    <img src="https://img.shields.io/badge/Hire%20me%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:cmosesmaina@gmail.com">
    <img src="https://img.shields.io/badge/Discuss%20an%20idea-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## Beyond Code

- I enjoy **breaking complex systems into simple parts**
- I like **teaching what I learn**
- I care deeply about **clean abstractions and long-term maintainability**

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d9488&height=100&section=footer" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CamlineKe&color=0d9488&style=flat-square" alt="Profile views" />
</p>
