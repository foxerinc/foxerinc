<h1 align="center">Hey, I'm Dedi 👋</h1>
<p align="center">
  💻 Junior Full-Stack Engineer · Go Backend · React Frontend · 📱 Android Dev
</p>

---

### 👨‍💻 A bit about me

I’m Dedi — a junior engineer who started on Android, got curious about “what actually happens on the server”, and ended up enjoying the whole stack.

I studied Computer Science at **Universitas Kristen Duta Wacana** on a full scholarship and graduated with a **3.92 GPA**. These days my time is split between:

- building REST APIs in **Go** with **PostgreSQL**
- wiring up UIs in **React + TypeScript**
- and still shipping the occasional **Kotlin / Jetpack Compose** app when Android Studio calls my name again

I like code that’s easy to read six months later, clear boundaries between layers, and systems that behave well under stress instead of “only works on my machine”.

If you want the longer story with demos and screenshots:  
👉 **[my portfolio](https://my-portfolio-foxerincs-projects.vercel.app/)**

---

### 🧩 How I work

- I treat side projects like “mini-production” apps: ERDs, migrations, API contracts, and a README that actually explains how to run things.
- I’m comfortable jumping between frontend and backend as long as the **data flow makes sense**.
- I’d rather ship something small, tested, and observable than a huge feature nobody can debug.
- I’m not allergic to refactoring. Someone has to clean up the TODOs. 😄

---

### 🛠 Tech stack

I don’t know everything (no one does), but these are the tools and concepts I actually use.

#### 🖥️ Backend

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gin%20(REST)-008ECF?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-025E8C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

- Language: **Go**
- API style: **RESTful APIs**, resource-based routing, query params for pagination/sorting/filtering
- Auth: **JWT-based authentication** (login, protected endpoints)
- Database: **relational databases** (PostgreSQL), migrations, SQL joins, indexes, constraints, transactions
- Caching: basic **Redis** usage (lookups, simple caching) *(delete this if you haven’t actually used Redis yet)*
- Patterns: layered / **clean architecture** (handler → service/use case → repository)
- Concurrency: **goroutines & channels**, `context` for cancellation & deadlines
- Testing & API tooling: Postman/Insomnia, basic unit & integration tests
- Perf & debugging: basic load testing with **k6**, logs and simple profiling

> OAuth2 / Google login: currently learning and experimenting with auth flows.

#### 💻 Frontend

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/shadcn/ui-111827?style=for-the-badge&logo=radixui&logoColor=white"/>
</p>

- Core: **React**, **TypeScript**, JavaScript, **HTML5**, **CSS3**
- Routing: **React Router** (nested routes, protected routes)
- Data fetching: **TanStack Query (React Query)** for server state, caching, loading/error states, plus **Axios** for HTTP requests
- Frameworks & tooling: basic **Next.js**, **Vite** for fast dev/build
- State management: **Zustand** (slices, derived state, middlewares like `persist` / `devtools`), React context where it’s enough
- Styling & UI: **TailwindCSS**, **shadcn/ui** (Radix-based components), responsive layouts
- Testing: **Vitest** for unit tests and simple component tests
- UX basics: form handling & validation, error states, loading skeletons, toasts

#### 📱 Mobile (Android)

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpack-compose&logoColor=white"/>
</p>

- Stack: **Kotlin**, Android Native, **Jetpack Compose**
- Architecture: **MVVM**, Clean Architecture, modularization, SOLID principles
- Libraries: Room, Retrofit, Coroutines, Hilt (DI), WorkManager, Navigation, ViewModel
- Backend integration: REST APIs, auth flows, Firebase (Auth, Realtime DB, FCM)

#### 🛠️ Tools & DevOps

<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white"/>
</p>

- Version control: **Git**, GitHub (branching, pull requests, code review)
- CI/CD: basic **GitHub Actions** workflows
- Containers: **Docker**, Docker Compose for local dev setups
- Environment: Linux as daily dev OS, VS Code, Android Studio, Postman/Insomnia
- Docs: **Swagger / OpenAPI** for API documentation

#### 📚 Fundamentals & concepts

No fancy badges here, just the foundations:

- **OOP**: encapsulation, abstraction, inheritance, polymorphism (practiced mainly in Kotlin/Android)
- **DSA basics**: arrays, maps, sets, stacks/queues, simple graph/tree usage
- **HTTP & REST**: methods, status codes, idempotency, request/response lifecycle
- **Relational modeling**: ERDs, one-to-many / many-to-many, practical normalization
- **Clean code**: separation of concerns, smaller functions, meaningful naming
- Debugging: reading stack traces, logs, using breakpoints instead of guessing

#### 🌱 Currently exploring

- Using **Redis** more seriously for caching and rate limiting
- Deeper **observability** (structured logs, metrics, traces)
- Stronger testing strategies for Go services (table-driven tests, mocks)

---

### 📦 Projects (high-level view)

> I’m currently cleaning up and open-sourcing a few production-style projects.  
> Repos will ship with a proper README, ERD and “how to run it” instructions.

- 🏦 **E-Wallet API — Go · PostgreSQL · Docker**  
  REST API for wallet, top-up and transfer. Clean architecture, transaction-safe flows, pagination/filtering, and basic load tests with k6.

- 📚 **Library Service — Go · PostgreSQL**  
  Borrow/return system with penalties, sorting and filtering, and indexes to keep queries responsive as data grows.

- 💊 **Pharmacy / Healthcare Web App — React · TypeScript · Zustand**  
  Product listing, pharmacist management and authenticated user flows with a responsive UI.

- 📱 **BearBull – Portfolio Management (Android)**  
  Kotlin app with MVVM, Room, Hilt and WorkManager for tracking trades and portfolio performance.

- 🧬 **Fingerprint Gender Classification (Python)**  
  Final thesis project using LBP and ridge density features with an SVM classifier.

More context and live demos live in the portfolio:  
👉 **[my-portfolio-foxerincs-projects.vercel.app](https://my-portfolio-foxerincs-projects.vercel.app/)**

---

### 🏅 A few things I’m proud of

- Developer Certification for Android (**DCA**, Dicoding)  
- Full scholarship winner – **Online Scholarship Competition (OSC)** by Metro Group  
- Graduated as **top student** in Informatics at Universitas Kristen Duta Wacana (highest GPA)

I’m not perfect, but I take learning seriously and I ship regularly. That combination tends to age well in a codebase.

---

### 📫 Let’s talk

<p align="center">
  <a href="https://www.linkedin.com/in/dedi-yanto-776b861b4/">
    <img src="https://img.shields.io/badge/LinkedIn-Dedi%20Yanto-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://my-portfolio-foxerincs-projects.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-my--portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="mailto:dediyanto180@gmail.com">
    <img src="https://img.shields.io/badge/Email-dediyanto180%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
