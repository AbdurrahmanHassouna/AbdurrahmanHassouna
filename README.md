<div align="center">

# Hi there, I'm Abdurrahman Hassouna 👋

### .NET Backend & Software Engineer | Clean Architecture • High-Concurrency APIs • Distributed Systems

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=512BD4&center=true&vCenter=true&width=750&lines=Building+Resilient+%26+Scalable+Cloud+Backends;Domain-Driven+Design+%26+Clean+Architecture;High-Concurrency+Database+Locking+%26+Distributed+Systems;ASP.NET+Core+%7C+EF+Core+%7C+MediatR+%7C+Redis" alt="Typing SVG Banner" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<p align="center">
  <a href="https://github.com/AbdurrahmanHassouna"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/abdurrahman-hassouna"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Status-Open_to_Engineering_Opportunities-brightgreen?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Architecture-Clean_%2F_CQRS_%2F_DDD-blue?style=flat-square" alt="Architecture" />
  <img src="https://img.shields.io/badge/Focus-High--Concurrency_APIs-orange?style=flat-square" alt="Focus" />
</p>

</div>

---

## ⚡ About Me & Engineering Focus

I am a **.NET Backend & Software Engineer** passionate about architecting scalable, resilient, and enterprise-grade distributed systems. My engineering philosophy centers on clean code, domain isolation, deterministic concurrency control under heavy load, and robust security posture.

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                               ENGINEERING SPECIALIZATIONS                               │
│    .NET & C#   •   Clean Architecture   •   CQRS / MediatR   •  Domain-Driven Design    │
│  Distributed Caching (Redis) • sp_getapplock & rowversion  •  JWT / OAuth2 / Identity  │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

### 🏛️ Core Pillars & Technical Capabilities

- **Production-Grade Backend Architecture (.NET & ASP.NET Core)**
  - Designing modular enterprise backends utilizing **Clean Architecture**, **Domain-Driven Design (DDD)**, and **CQRS** patterns powered by **MediatR**.
  - Enforcing strict boundary separation between Domain, Application, Infrastructure, and Presentation layers with zero leaky abstractions.
  - Decoupling business rules into rich domain aggregates, entity state transitions, and asynchronous domain event handlers.

- **High-Concurrency, Locking & Data Integrity**
  - Tackling high-contention race conditions in mission-critical transactions (e.g., booking engines, inventory allocation, financial workflows).
  - Implementing **dual-layer concurrency control**: pairing database-level pessimistic application locks via SQL Server **`sp_getapplock`** with EF Core optimistic concurrency tokens (**`rowversion`**) to prevent double-booking and phantom updates.
  - Designing robust **multi-timezone engines** handling complex daylight saving time (DST) shifts, UTC normalization, and midnight-crossing schedules across distributed nodes.

- **Distributed Caching & High-Throughput Scaling**
  - Eliminating database bottlenecks through **Redis** distributed caching patterns (Cache-Aside, Write-Through).
  - Formulating structured **prefix-based cache invalidation strategies** to ensure zero stale reads while maintaining near-instant lookup latencies.

- **Enterprise Security, Authentication & Traffic Governance**
  - Securing APIs with **ASP.NET Core Identity**, stateless **JWT Bearer Authentication**, and **OAuth 2.0** flows.
  - Enforcing granular authorization policies using Role-Based (RBAC) and Claim/Policy-Based Access Control.
  - Implementing partitioned **Rate Limiting** to protect endpoints against brute-force attacks, DDoS, and noisy-neighbor exhaustion.

---

## 🛠️ Tech Stack & Architectural Competencies

<table>
  <thead>
    <tr>
      <th width="28%">Domain</th>
      <th width="72%">Technologies & Architectural Capabilities</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Languages & Core</strong></td>
      <td>
        <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
        <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
        <img src="https://img.shields.io/badge/ASP.NET%20Core%20Web%20API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core Web API" />
        <img src="https://img.shields.io/badge/ASP.NET%20Core%20MVC-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core MVC" />
        <img src="https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
      </td>
    </tr>
    <tr>
      <td><strong>Architecture & Patterns</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Clean%20Architecture-00599C?style=for-the-badge" alt="Clean Architecture" />
        <img src="https://img.shields.io/badge/Layered%20(N--Tier)-0078D4?style=for-the-badge" alt="Layered Architecture" />
        <img src="https://img.shields.io/badge/CQRS%20Pattern-4B6EAF?style=for-the-badge" alt="CQRS" />
        <img src="https://img.shields.io/badge/MediatR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="MediatR" />
        <img src="https://img.shields.io/badge/FluentValidation-2D8C3C?style=for-the-badge" alt="FluentValidation" />
        <img src="https://img.shields.io/badge/Repository%20%26%20Unit%20of%20Work-0E7090?style=for-the-badge" alt="Repository & UoW" />
        <img src="https://img.shields.io/badge/Domain--Driven%20Design-107C41?style=for-the-badge" alt="DDD" />
      </td>
    </tr>
    <tr>
      <td><strong>Data, Caching & Concurrency</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
        <img src="https://img.shields.io/badge/Entity%20Framework%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
        <img src="https://img.shields.io/badge/SQL%20App%20Locks%20(sp__getapplock)-00599C?style=for-the-badge" alt="SQL App Locks" />
        <img src="https://img.shields.io/badge/Optimistic%20Concurrency%20(RowVersion)-234975?style=for-the-badge" alt="Optimistic Concurrency" />
      </td>
    </tr>
    <tr>
      <td><strong>Security, DevOps & Tooling</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose" />
        <img src="https://img.shields.io/badge/ASP.NET%20Core%20Identity-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="Identity" />
        <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
        <img src="https://img.shields.io/badge/OAuth%202.0-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="OAuth 2.0" />
        <img src="https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger" />
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
        <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" alt="Visual Studio" />
        <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
      </td>
    </tr>
  </tbody>
</table>

### 🏛️ End-to-End Clean Architecture Execution Flow

Below is the request lifecycle implemented across my production-grade .NET Clean Architecture solutions:

```mermaid
flowchart LR
    Client(["🌐 Client Request"]) --> RateLimiter["🛡️ Rate Limiting & Auth<br/>(JWT / Google OAuth)"]
    RateLimiter --> Controllers["🎮 ASP.NET Core API Controllers"]
    Controllers --> MediatR["⚡ MediatR CQRS Pipeline<br/>(FluentValidation + Logging)"]
    MediatR --> Domain["🧠 Domain & Concurrency Coordinator<br/>(App Locks / Idempotency / Business Logic)"]
    Domain --> Cache[("⚡ Redis<br/>Distributed Cache")]
    Domain --> EFCore["📦 EF Core & Unit of Work"]
    EFCore --> DB[("🗄️ SQL Server<br/>(sp_getapplock / RowVersion)")]
```

> 💡 **Architectural Tenets:**
> - **Strict Domain Isolation:** Business rules and domain invariants remain independent of frameworks, external databases, or third-party SDKs.
> - **Zero-Overbooking Guarantees:** Critical booking/reservation transactions are guarded with transaction-scoped `sp_getapplock` and EF Core `RowVersion` optimistic tokens.
> - **Resilient CQRS Request Pipeline:** Validation, logging, and performance telemetry execute seamlessly via MediatR pipeline behaviors before domain handlers are invoked.
> - **High-Efficiency Distributed Caching:** Cache-aside pattern via Redis with prefix-based invalidation policies prevents stale reads and minimizes SQL Server query load.

---

## 🚀 Featured Engineering Projects

### ⚽ [PitchReserve](https://github.com/AbdurrahmanHassouna/PitchReserve) — High-Concurrency Sports Venue Booking Engine
> **Stack:** `.NET` • `C#` • `Clean Architecture` • `CQRS (MediatR)` • `EF Core` • `SQL Server` • `Redis` • `Docker`

A production-grade sports venue reservation engine architected for zero double-booking tolerance under high-concurrency traffic spikes.

* **Dual-Layer Concurrency Control:**
  * **Database-Level Synchronization:** Custom `SqlServerTransactionCoordinator` utilizing `sp_getapplock` to serialize concurrent reservation requests for the exact same pitch and time slot.
  * **Optimistic Token Validation:** EF Core `rowversion` concurrency tokens to eliminate race conditions and prevent ghost updates.
* **Complex Scheduling & Timezone Engine:** Custom `Africa/Cairo` timezone engine with full support for midnight-crossing slots, dynamic blackout periods, and variable slot durations.
* **Two-Stage Cash Settlement State Machine:** Deterministic finite-state workflow governing reservations, deposit verifications, operator confirmations, and automated timeout releases.
* **Performance & Protection:** Redis distributed caching with prefix-based bulk invalidation strategies alongside partitioned rate limiting to safeguard against booking abuse.
* **Comprehensive REST API:** 32 cleanly segregated CQRS endpoints with cross-cutting pipeline behaviors for validation and structured logging.

---

### 📚 [BookStoreDotNetCore (AprilBookStore)](https://github.com/AbdurrahmanHassouna/BookStoreDotNetCore) — Enterprise Clean Architecture E-Commerce Platform
> **Stack:** `.NET` • `ASP.NET Core MVC` • `EF Core` • `ASP.NET Core Identity` • `Google OAuth 2.0` • `SQL Server`

An enterprise e-commerce platform built around strict separation of concerns and maintainable domain-driven design principles.

* **4-Layer Clean Architecture:** Strictly decoupled into `Domain`, `Application`, `Infrastructure`, and `Web` layers, guaranteeing testability and preventing infrastructure leakage into core business rules.
* **Auditing & Soft-Delete Pipeline:** Custom EF Core `AuditableEntityInterceptor` for automated temporal tracking (`CreatedAt`, `ModifiedAt`, `CreatedBy`) combined with global query filters for soft-delete enforcement.
* **Identity & Granular Authorization:** Multi-tier role- and policy-based access control (`SuperAdmin`, `Admin`, `User`) coupled with Google OAuth 2.0 external authentication.
* **Automated Data Lifecycle:** Self-executing database migration and deterministic data-seeding pipeline for zero-friction local and staging deployments.

---

### 🩺 [SkinCA Platform (`SkinCaLayered` & `SkinCaApp`)](https://github.com/AbdurrahmanHassouna/SkinCaLayered) — AI-Assisted Dermatology & Healthcare Ecosystem
> **Stack:** `ASP.NET Core` • `N-Tier Layered Architecture` • `EF Core` • `JWT Bearer Auth` • `RESTful API` • `Swagger/OpenAPI`

A digital healthcare back-end ecosystem integrating automated diagnostic classification with real-time tele-health workflows.

* **AI/ML Diagnostics Integration:** Secure REST pipeline interfacing with machine learning models for automated dermatological skin lesion analysis and risk assessment.
* **Role-Segregated Medical Auth:** Stateless JWT authentication securing confidential medical records across distinct patient and physician personas.
* **Geospatial Doctor Directory:** Location-aware provider directory enabling patients to discover and filter verified dermatologists by proximity and specialty.
* **Real-Time Clinical Chat API:** Direct patient-to-physician communication channels supporting consultation records and attachment handling.
* **OpenAPI Specification:** Full Swagger/OpenAPI documentation defining explicit contracts, request schemas, and token authorization flows.

---

### 📊 Repository Architecture & Engineering Matrix

| Repository | Architecture Pattern | Technology Stack | Key Engineering Solved |
| :--- | :--- | :--- | :--- |
| **[PitchReserve](https://github.com/AbdurrahmanHassouna/PitchReserve)** | Clean Architecture + CQRS | .NET, EF Core, SQL Server, Redis, Docker | Zero double-bookings via `sp_getapplock` + `rowversion`, midnight-crossing timezone logic, Redis cache prefix invalidation |
| **[BookStoreDotNetCore](https://github.com/AbdurrahmanHassouna/BookStoreDotNetCore)** | 4-Layer Clean Architecture | .NET, ASP.NET Core MVC, EF Core, Identity, Google OAuth | Automated `AuditableEntityInterceptor`, global soft deletes, multi-tier RBAC (`SuperAdmin`/`Admin`/`User`), migration seeding |
| **[SkinCaLayered](https://github.com/AbdurrahmanHassouna/SkinCaLayered)** | N-Tier Layered Architecture | ASP.NET Core, EF Core, JWT, Swagger/OpenAPI | Machine learning lesion analysis pipeline, medical JWT auth, geospatial doctor directory search |
| **[SkinCaApp](https://github.com/AbdurrahmanHassouna/SkinCaApp)** | RESTful Healthcare API | ASP.NET Core, EF Core, Identity, JWT | AI-assisted skin lesion classification endpoints, clinical identity & authentication |
| **[BookStoreDotNetFramework](https://github.com/AbdurrahmanHassouna/BookStoreDotNetFramework)** | Classic 3-Tier MVC | ASP.NET MVC, .NET Framework, SQL Server | Relational catalog management, shopping cart session lifecycle, classic .NET enterprise web architecture |

---

<h2 align="center">📊 GitHub Activity & Metrics</h2>

<div align="center">
  <a href="https://github.com/AbdurrahmanHassouna">
    <img src="https://github-readme-stats.vercel.app/api?username=AbdurrahmanHassouna&show_icons=true&theme=tokyonight&hide_border=true" alt="Abdurrahman's GitHub Stats" height="165" />
  </a>
  <a href="https://github.com/AbdurrahmanHassouna">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbdurrahmanHassouna&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
  </a>
</div>
<br />
<div align="center">
  <a href="https://github.com/AbdurrahmanHassouna">
    <img src="https://streak-stats.demolab.com?user=AbdurrahmanHassouna&theme=tokyonight&hide_border=true" alt="Abdurrahman's Streak Stats" />
  </a>
</div>

<br />

---

<h2 align="center">🤝 Let's Connect & Collaborate</h2>

<p align="center">
  Whether you want to discuss backend architecture, distributed systems, open-source projects, or potential engineering opportunities—feel free to reach out!
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdurrahman-hassouna" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/AbdurrahmanHassouna" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" />
  </a>
</p>

<br />

> ### 💼 Open to Opportunities
>
> 🎯 **Actively seeking roles as a .NET Backend Engineer / Software Engineer.**  
> Dedicated to building high-performance APIs, robust distributed systems, and reliable cloud-native solutions using modern .NET, Clean Architecture, and best engineering practices.
>
> *Always enthusiastic about backend system design collaborations and engineering discussions!*

<br />

<div align="center">
  <sub>Crafted with passion for clean code & scalable systems • © Abdurrahman Hassouna</sub>
</div>
