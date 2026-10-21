<!-- ═══════════════════════════  HEADER  ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:062A1F,50:0B3D2E,100:10B981&height=220&section=header&text=Yasir%20Oladimeji&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Software%20Engineer&descSize=18&descAlignY=60&descColor=b8f5d8&animation=twinkling" width="100%" alt="Yasir Oladimeji"/>

<a href="https://yasircodes.tech">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&color=10B981&center=true&vCenter=true&width=720&lines=Full+Stack+Software+Engineer;Frontend%2C+backend%2C+and+everything+in+between;Event+driven+systems+%E2%80%A2+Kafka+%E2%80%A2+Redis;Fintech+%E2%80%A2+E+commerce+%E2%80%A2+AI+%E2%80%A2+Healthtech;If+it's+solvable%2C+it's+shippable." alt="Typing intro"/>
</a>

<br/>

<a href="https://yasircodes.tech"><img src="https://img.shields.io/badge/Portfolio-yasircodes.tech-10B981?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=062A1F"/></a>
<a href="https://linkedin.com/in/yasir-oyebo0"><img src="https://img.shields.io/badge/LinkedIn-yasir--oyebo0-10B981?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=062A1F"/></a>
<a href="https://x.com/yasiroyebo"><img src="https://img.shields.io/badge/X-@yasiroyebo-10B981?style=for-the-badge&logo=x&logoColor=white&labelColor=062A1F"/></a>
<a href="mailto:yasiroyebo@gmail.com"><img src="https://img.shields.io/badge/Email-yasiroyebo@gmail.com-10B981?style=for-the-badge&logo=gmail&logoColor=white&labelColor=062A1F"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=YastecHub&label=Profile%20visits&color=10B981&style=flat-square" alt="profile views"/>

</div>

---

## 👨🏽‍💻 `whoami`

```csharp
public sealed record Engineer
{
    public string   Name     => "Yasir Oladimeji";
    public string   Role     => "Full Stack Software Engineer";
    public string   Base     => "Lagos, Nigeria 🇳🇬  (remote ready, any timezone)";
    public string[] Domains  => ["Fintech", "E commerce", "AI / LLMs", "Healthtech", "SaaS"];
    public string[] Thinks   => ["Clean Architecture", "DDD", "CQRS", "Event driven systems"];
    public string   Policy   => "If it's solvable, I'll solve it. If it's shippable, I'll ship it.";
}
```

I build **production systems that move money, serve customers and talk to AI**: wallet ledgers processing **10,000+ daily transactions**, e commerce platforms with **25+ APIs**, and LLM powered backends that win hackathons.

I work across the whole stack. Backend architecture, frontend, infrastructure, data, integrations, automation. **Hand me a problem with a solution in it, and I'll find that solution and ship it.**

---

## 🧭 How I Work

| Step | What it means |
| :-- | :-- |
| **1. Understand** | Profile the system, trace the request, read the query plan, find the *real* problem before touching code |
| **2. Design** | Pick the right tool for the job: CQRS, caching, events, or just a well placed index |
| **3. Build** | Clean, tested, containerised code with xUnit, Docker, CI/CD and zero downtime deploys |
| **4. Observe** | Serilog tracing, metrics and alerts, then iterate until it's fast and stable |

---

## 🧰 Bring Me a Problem

> No task is "not my stack". If it's solvable, here's what I'll do with it:

| You need… | I'll deliver… |
| :-- | :-- |
| 💸 Payments, wallets, ledgers | Idempotent, auditable money flows that survive retries, replays and broker restarts |
| ⚡ A slow API | Measurable speedups. I've cut **p95 latency by 45%** with indexing and query plan work |
| 🧱 A monolith that's hurting | A clean split into a modular monolith or microservices, with Kafka or RabbitMQ in between |
| 🤖 AI in your product | Resilient LLM integrations with retries, backoff and circuit breakers |
| 🔐 Auth that holds up | JWT, OAuth2, RBAC, secure cookies, layered middleware |
| 🕰️ Legacy code | Safe migrations. I took 5+ client projects from **.NET 6 to .NET 8** with zero downtime |
| 🖥️ A polished UI | React, Next.js and Tailwind front ends wired cleanly to the APIs behind them |
| 🔁 Boring manual work | Automation: background services, schedulers, WhatsApp and email bots |

---

## 📈 Impact in Numbers

<div align="center">

| 10,000+ | 45% | ~60% | 40% | 30% | 🥇 + 🥉 |
| :-: | :-: | :-: | :-: | :-: | :-: |
| daily transactions on a Kafka backed ledger | faster p95 API responses | less DB read load with Redis | fewer LLM endpoint errors | fewer production incidents | hackathon podiums |

</div>

---

## 🏗️ Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🏦 WaaS: Wallet as a Service
`Production` · `Fintech`

Wallet creation, KYC, balances and transaction history across **15+ endpoints**. Ledger extracted into its own microservice, with **idempotent Kafka consumers** that guarantee no double credit or double debit, even under network failure.

`C#` `.NET 8` `Kafka` `EF Core` `SQL Server` `Clean Architecture`

</td>
<td width="50%" valign="top">

### 🛒 GrowthGIA: E Commerce Platform
`Production` · `E commerce`

Modular monolith over **Commerce, Identity and Logistics** with **25+ REST APIs**, ACID transactions and architecture fitness tests. Redis TTL caching cut DB round trips by **~60%** at peak.

`.NET 10` `PostgreSQL` `Redis` `DDD` `Vertical Slice`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 [HostelSync AI](https://github.com/YastecHub/hostelsync-ai)
`🥇 1st Place · UNILAG Hackathon`

Two stage AI allocation engine (Housing Vulnerability Index + spatial optimisation) that processes **3,000+ applications in 0.34s**, a **16× lift** in bed assignments for the lowest income students.

`Python` `AI` `Optimisation`

</td>
<td width="50%" valign="top">

### 🩺 Sentra: AI Health & Accessibility
`🥉 3rd Place · TOS Hub Hackathon`

LLM powered healthcare backend unifying symptom analysis, voice to diagnosis, OCR and obstacle detection behind **10+ documented endpoints**.

`TypeScript` `NestJS` `LLMs` `Swagger`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏛️ WhitteIntelCoop
`Production` · `Whitteintel`

Versioned (v1/v2) API with **CQRS + MediatR** splitting reads from writes, fine grained **RBAC**, Unit of Work, xUnit coverage, Docker Compose and Serilog tracing.

`ASP.NET Core` `CQRS` `MediatR` `JWT` `xUnit`

</td>
<td width="50%" valign="top">

### 🤖 [Telex AI Agent](https://github.com/telexintegrations/SocialMediaAgent)
`HNG Finalist`

GroqAI LLM integration for Telex with retry, exponential backoff and circuit breakers, cutting the error rate by **40%** under high concurrency.

`C#` `.NET` `GroqAI` `Resilience patterns`

</td>
</tr>
</table>

<sub>More builds: [MediVoice](https://github.com/YastecHub/medi-voice) (healthcare language bridge) · [Paystack × ASP.NET Core](https://github.com/YastecHub/PayStackImplementationTesting) (end to end payment integration)</sub>

---

## 🧬 Career Log

```text
$ git log --oneline --graph yasir/career

* 2026  (HEAD -> main)  Software Engineer        @ Whitteintel Limited         ·  CQRS, RBAC, xUnit, Docker, Serilog
* 2025                  Full Stack Engineer      @ Codefactory Innovative Hub  ·  WaaS, Kafka ledger, GrowthGIA, 45% faster p95
* 2025                  .NET Backend Developer   @ Teknikforce (Delhi, IN)     ·  .NET 6 to 8 across 5+ client projects
* 2024                  Backend Intern           @ HNG Tech                    ·  GroqAI × Telex, Finalist
* ----  (root)          Doctor of Pharmacy       @ University of Lagos         ·  where the problem solving started
```

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Runtimes**<br/>
<img src="https://skillicons.dev/icons?i=cs,dotnet,ts,js,py,nodejs&theme=dark" />

**Backend Frameworks**<br/>
<img src="https://skillicons.dev/icons?i=nestjs,express,fastapi&theme=dark" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite&theme=dark" />

**Messaging · Caching · Data**<br/>
<img src="https://skillicons.dev/icons?i=kafka,rabbitmq,redis,postgres,mongodb,sqlite,supabase,firebase&theme=dark" />

**Cloud · DevOps · Tooling**<br/>
<img src="https://skillicons.dev/icons?i=docker,azure,aws,gcp,githubactions,nginx,vercel,git,postman,figma&theme=dark" />

**Now Learning**<br/>
<img src="https://skillicons.dev/icons?i=java,spring,azure&theme=dark" />

<br/>

`SQL Server` `EF Core` `LINQ` `MediatR` `Serilog` `xUnit` `Swagger/OpenAPI` `JWT` `OAuth2` `RBAC` `Twilio` `GroqAI` `YarnGPT`

**Patterns I reach for:** Clean Architecture · DDD · CQRS · Vertical Slice · Repository + Unit of Work · SOLID · API Versioning · Idempotency · Circuit Breakers

</div>

---

## 🔭 Right Now

- 🧴 **Building:** engineering at a health tech startup on a mission to put your skin first, making expert skincare smarter, more personal and easier to reach. More to share soon.
- 📚 **Learning:** Java, system design, Azure, and the deeper corners of the .NET ecosystem
- ☕ **Focus:** my frontend game is sharpened, so the spotlight is now on Java and the JVM
- 🤝 **Open to:** full stack work. Frontend, backend, or the whole thing end to end

> ⚡ **Fun fact:** I read query plans for fun. On purpose. Voluntarily.

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YastecHub&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=10B981&icon_color=10B981&text_color=C9D1D9&ring_color=10B981" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YastecHub&layout=compact&hide_border=true&bg_color=0D1117&title_color=10B981&text_color=C9D1D9&langs_count=8" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=YastecHub&hide_border=true&background=0D1117&ring=10B981&fire=10B981&currStreakLabel=10B981&sideLabels=C9D1D9&dates=8B949E&stroke=1F2937&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YastecHub&bg_color=0D1117&color=C9D1D9&line=10B981&point=FFFFFF&area=true&area_color=10B981&hide_border=true&custom_title=Contribution%20pulse" width="100%" alt="Contribution graph"/>

</div>

---

<div align="center">

### 📬 Got something that needs building?

**Frontend, backend or both. Send it over and let's ship it.**

<a href="mailto:yasiroyebo@gmail.com"><img src="https://img.shields.io/badge/Let's_talk-yasiroyebo@gmail.com-10B981?style=for-the-badge&logo=gmail&logoColor=white&labelColor=062A1F"/></a>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:10B981,50:0B3D2E,100:062A1F&height=120&section=footer" width="100%"/>

</div>
