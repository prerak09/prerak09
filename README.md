<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=200&section=header&text=Prerak%20Tanwar&fontSize=58&fontColor=FFFFFF&fontAlignY=36&desc=Trust%20nothing.%20Measure%20everything.&descSize=19&descAlignY=57&animation=fadeIn" width="100%" />

<a href="https://github.com/prerak09">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3400&pause=900&color=58A6FF&center=true&vCenter=true&width=780&lines=Top+0.005%25+of+125%2C000%2B+in+Google's+Big+Code.;I+ship+products%2C+then+audit+them+until+they+break.;Caught+my+own+benchmark+faking+a+perfect+score.;Readability+ML+running+in+real+classrooms." alt="Typing SVG" />
</a>

<br/>

<a href="https://linkedin.com/in/preraktanwar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="26" /></a>
<a href="mailto:prerak24436@iiitd.ac.in"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" height="26" /></a>
<img src="https://img.shields.io/badge/IIIT--Delhi-B.Tech%20CSE%20'28-6E40C9?style=flat-square" height="26" />
<img src="https://img.shields.io/badge/Delhi,%20India-30363D?style=flat-square&logo=googlemaps&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Open%20to-SDE%20%26%20Research%20Internships-2EA043?style=flat-square" height="26" />

</div>

<br/>

<div align="center">

## 🏆 National Rankings

<table>
<tr>
<td align="center" valign="top" width="33%">

<img src="https://img.shields.io/badge/ALL%20INDIA%20RANK-4285F4?style=for-the-badge&logo=google&logoColor=white" height="34" />

# 6

## Google Big Code

**Top 0.005% of 125,000+**

Engineering students nationwide.<br/>Multi-stage algorithmic championship.

</td>
<td align="center" valign="top" width="33%">

<img src="https://img.shields.io/badge/ALL%20INDIA%20RANK-0033A0?style=for-the-badge&logo=goldmansachs&logoColor=white" height="34" />

# 3

## Goldman Sachs Hackathon

**Topped the 12-hour round**

Individual challenge across competitive<br/>programming, CS, and quant.

</td>
<td align="center" valign="top" width="33%">

<img src="https://img.shields.io/badge/NATIONAL-FF6B00?style=for-the-badge" height="34" />

# Finalist

## WWT Unravel 2026

**ML on real datasets**

Modelling, plus the business<br/>recommendations behind it.

</td>
</tr>
</table>

</div>

<br/>

> I ship products that reach actual users: a readability ML service deployed with real schools, open transit infrastructure across 17 repositories, and memory safety work in a CNCF WebAssembly runtime.

<br/>

---

<div align="center">

## 🤖 How I Work With AI

</div>

I use AI aggressively and I disclose it. Every upstream contribution I've made carries an explicit AI assistance trailer, because the interesting part was never who typed the code. It's what I caught.

**I don't accept output I can't falsify.** In my [WasmEdge fix](https://github.com/WasmEdge/WasmEdge/pull/5225) for undefined behaviour in a hash routine, the patch was two lines. The work was proving the regression test wasn't passing vacuously: I reverted the fix, kept the test, and showed the sanitizer firing four times. A test that passes either way is worse than no test.

**I assume my own system is lying until it's measured.** [Auditing ThreatIQ](https://github.com/prerak09/ThreatIQ/pull/1), I found the benchmark scoring `F1 = 1.000` because the fraud and legitimate distributions never overlapped, so a single `if` statement could win it. Dashboards were animating charts from `Math.random()`. The README claimed cryptographic schemes that existed nowhere in the codebase. I tore all of it out, published the honest number, and wrote tests so it can't silently return.

**Fundamentals are what make the AI useful.** You cannot tell that a `span::last<16>()` wraps on unsigned arithmetic, or that a 20 sample retraining buffer is quietly destroying production precision, by reading confident prose. You have to know.

<br/>

---

<div align="center">

## 👥 Built With Real Users, Not For Imaginary Ones

</div>

**Glide runs in real schools.** I work directly with the institutions deploying it, which means the feedback loop is teachers and students telling me what actually fails, not a backlog someone handed me.

**My research work put me in front of users around the world.** At the Complex Systems Laboratory under Dr. Ganesh Bagler, I ran usability studies with participants internationally and turned those findings into high fidelity prototypes and interface specifications across 9 design iterations. I then validated the web and mobile interfaces against WCAG 2.1 AA with automated audit tooling: 50 issues resolved across 20 iterations, zero critical violations left standing.

Before that I shipped production frontend and API work at Hemploom India, cutting client side rendering latency 35% and holding live API responses under 200ms.

<br/>

---

<div align="center">

## 🚀 Products I Own

</div>

### 🧠 [Glide](https://github.com/prerak09/Glidev2) · Cognitive Accessibility Engine &nbsp;<img src="https://img.shields.io/badge/500%2B%20users-2EA043?style=flat-square" /> <img src="https://img.shields.io/badge/deployed%20in%20schools-1F6FEB?style=flat-square" />

**The problem:** the web is unreadable for neurodivergent learners, and generic "simplify this" tools can't tell you whether they made anything easier.

**The build:** a Python/FastAPI microservice that *scores* readability with a **scikit-learn Ridge Regression model trained on spaCy NLP features**, then drives a real time transformation pipeline (simplification, summarization, text to speech) against that score rather than against a guess. Multi provider LLM orchestration with caching, automatic retries, and provider fallback lifted reliability **60%**, with unit and integration coverage across the API and scoring layers.

**Where it runs:** live with real schools, serving 500+ users.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" /> <img src="https://img.shields.io/badge/Multi--LLM%20Orchestration-412991?style=flat-square&logo=openai&logoColor=white" />

---

### 🔎 [Verity](https://github.com/prerak09/Verity) · Verified startup and internship platform &nbsp;<a href="https://verity-gold.vercel.app"><img src="https://img.shields.io/badge/live-000000?style=flat-square&logo=vercel&logoColor=white" /></a>

**The problem:** students apply into listings nobody has verified, at companies nobody has checked.

**The build:** mine end to end, schema through deploy. Role based access control enforced at the data layer, Postgres full text search, an admin verification and moderation queue, transactional notifications, a cron driven digest.

Then I audited my own product and [remediated 20+ findings in one PR](https://github.com/prerak09/Verity/pull/36): an auth bypass footgun where demo mode could have disabled authentication in production, a middleware lockout bouncing every anonymous visitor into a sign in loop, and a landing page quoting trust metrics and partner logos that were simply invented. A platform selling verification cannot ship fabricated numbers.

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white" />

---

### ⚔️ [ThreatIQ](https://github.com/prerak09/ThreatIQ) · Adversarial fraud detection &nbsp;<a href="https://iqthreat.vercel.app"><img src="https://img.shields.io/badge/live-000000?style=flat-square&logo=vercel&logoColor=white" /></a>

**The problem:** fraud detectors get benchmarked against attackers that don't adapt, so the reported numbers mean nothing in production.

**The build:** attacker and detector policies co-evolve in a multi agent RL loop (PPO, with a REINFORCE fallback). Rebuilding the generator around **tiered operator sophistication**, where advanced operators sit inside the legitimate distribution, took the honest ensemble to **F1 0.858 against a 0.583 trivial baseline** and separated recall by tier so the hard cases stay visible instead of averaged away. That honest benchmark then exposed an online retraining loop taking live precision from 86% to 24%, now gated behind a champion/challenger promotion test.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/PPO%20%2F%20REINFORCE-5C2D91?style=flat-square" /> <img src="https://img.shields.io/badge/SHAP-1F77B4?style=flat-square" />

---

### 💰 [SpendWise](https://github.com/prerak09/SpendWise) · Personal finance management

12+ shipped features (budgets, savings goals, recurring transactions, bill reminders) over a normalized **11 entity PostgreSQL schema** with row level security, transactional triggers, and audit logging holding consistency under concurrent writes.

<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Recharts-FF6384?style=flat-square" />

<br/>

---

<div align="center">

## 🌐 Open Source

</div>

**I work in Google Summer of Code and LFX Mentorship organisations, outside the programs.** WasmEdge and p4c on the LFX side, JabRef, scikit-bio and Extralit on the GSoC side. I'm not a selected contributor in either program and I'm not waiting to be. These are codebases with real problems in them, the contribution window is always open, and my merged WasmEdge fixes came out of that rather than out of a program cycle.

**[Transport Stack](https://github.com/transport-stack)** maintainer. An organisation building open public transit infrastructure: **17 Apache-2.0 repositories** covering a journey planner, ETA calculation, bus bunching detection, schedule adherence, park and ride trip planning, ONDC micro mobility and bus connectors, and the open transit data service APIs behind the operations dashboard. *Python, Django, Java, JavaScript*

**[WasmEdge](https://github.com/WasmEdge/WasmEdge)** contributor. C++ core and plugin layer of a CNCF WebAssembly runtime powering serverless, edge, and embedded workloads. Memory safety, bounds correctness, sanitizer verified regression tests. *C++, CMake, ASan/UBSan*

**[JabRef](https://github.com/JabRef/jabref)**. Java desktop reference manager for BibTeX and BibLaTeX.

<br/>

---

<div align="center">

## ⚙️ Toolkit

<img src="https://skillicons.dev/icons?i=cpp,c,python,java,ts,js,postgres,mysql&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=fastapi,django,nextjs,nodejs,prisma,supabase,docker,aws&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,git,github,vercel,firebase,cmake,linux&theme=dark" />

</div>

**Languages:** C++, C, Python, Java, TypeScript, JavaScript, SQL (PostgreSQL, MySQL)
**Backend and Systems:** FastAPI, Django, Node.js, Next.js, Prisma, Supabase, REST APIs, Docker, AWS, microservices, caching, RBAC
**Machine Learning:** scikit-learn, PyTorch, spaCy, NumPy, Pandas, SHAP, Ridge Regression, NLP, reinforcement learning (PPO, REINFORCE), multi-LLM orchestration
**Fundamentals:** Data Structures and Algorithms, Operating Systems, Computer Organization, Object-Oriented Programming, Database Management Systems
**Tooling:** Git, GitHub, CMake, AddressSanitizer, UndefinedBehaviorSanitizer, Vercel, Firebase, Linux, SDLC

<br/>

---

<div align="center">

## 📌 Off the keyboard

</div>

Joint Technical Secretary at IIIT-Delhi. Event Coordinator for **E-Summit 2026**, a national entrepreneurship summit with 5000+ attendees, covering cross functional teams, sponsorships, speaker engagement, and logistics. Student Representative on the Student Council, primary liaison to administration for 700+ students.

<br/>

---

<div align="center">

### Open to SDE and research internships

Happy to talk about backend systems, memory safety, or why your benchmark is probably easier than you think.

<a href="mailto:prerak24436@iiitd.ac.in"><img src="https://img.shields.io/badge/prerak24436@iiitd.ac.in-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/preraktanwar"><img src="https://img.shields.io/badge/preraktanwar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,50:1F6FEB,100:0D1117&height=120&section=footer" width="100%" />

</div>
