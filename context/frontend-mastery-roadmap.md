# 🏆 Frontend Mastery Reading Timeline & Progress Tracker

> A structured 12–18 month roadmap to world-class frontend engineering, mapped to levels with trackable tasks.

---

## 📊 Progress Overview

| Level                              | Status        | Progress |
| ---------------------------------- | ------------- | -------- |
| 🟢 Level 1 — Foundations            | `Not Started` | `0/8`    |
| 🔵 Level 2 — Core Craft             | `Not Started` | `0/10`   |
| 🟣 Level 3 — Architecture & Systems | `Not Started` | `0/10`   |
| 🟠 Level 4 — AI-Native & Edge       | `Not Started` | `0/8`    |
| 🔴 Level 5 — Elite Engineer         | `Not Started` | `0/8`    |

---

## 🟢 Level 1 — Foundations (Months 1–2)

*Solidify the bedrock every great engineer stands on. Speed through what you know; deep-dive what you don't.*

### 📚 Reading List

- [ ] **"JavaScript: The Good Parts"** by Douglas Crockford *(if skipped before)*
- [ ] **"You Don't Know JS" (YDKJS)** — Scope & Closures + This & Object Prototypes *(Kyle Simpson)*
- [ ] **MDN Deep Dives**: Event Loop, Call Stack, Promises, Async/Await
- [ ] **"Refactoring UI"** by Adam Wathan & Steve Schoger *(design intuition for engineers)*
- [ ] **Google Web.dev** — Core Web Vitals guides (all 3 metrics)

### 🛠️ Practical Tasks

- [ ] Build a **vanilla JS SPA** (no framework) with routing, state management, and DOM diffing to understand the "magic" React abstracts
- [ ] Implement a **custom Promise** from scratch
- [ ] Rebuild one of your old projects using only the **Composition API** patterns (preparing for React Server Components thinking)
- [ ] Audit 3 of your repos with **Lighthouse**; open issues for every score under 95
- [ ] Read the **React source code** (just the reconciler and hooks implementation — 2 weekends)
- [ ] Watch **"What the heck is the event loop anyway?"** (Philip Roberts, JSConf) and explain it to someone
- [ ] Complete **TypeScript Documentation** — Advanced Types section end-to-end
- [ ] Build a **commit-message linting CI pipeline** for one project (extend your existing convention)

### 🎯 Level 1 Completion Criteria

- [ ] All reading complete with notes saved in your second brain (Notion/Obsidian)
- [ ] Vanilla JS project pushed to GitHub with README explaining architecture decisions
- [ ] Lighthouse scores documented in a tracking sheet
- [ ] Blog post #1: "What React's reconciler taught me about app architecture"

---

## 🔵 Level 2 — Core Craft (Months 3–5)

*Become dangerous at the intersection of performance, TypeScript, and component architecture.*

### 📚 Reading List

- [ ] **"Designing Data-Intensive Applications"** (DDIA) by Martin Kleppmann — Chapters 1–5 *(data model & storage thinking)*
- [ ] **"Effective TypeScript"** by Dan Vanderkam — 62 specific items
- [ ] **"Web Performance in Action"** by Jeremy Wagner
- [ ] **React Docs (Beta/New)** — Server Components, Suspense, Transitions *(official docs — read every page)*
- [ ] **"The Elements of UI Engineering"** by Dan Abramov (blog series)
- [ ] **Next.js 15+ docs** — App Router, caching semantics, Server Actions

### 🛠️ Practical Tasks

- [ ] Build a **design system monorepo** (Turborepo + Changesets + Storybook) with 10+ components; publish to npm
- [ ] Achieve **100/100/100/100 Lighthouse** on a real project (Performance, Accessibility, Best Practices, SEO)
- [ ] Profile a React app with **React DevTools Profiler + Chrome Performance tab**; fix 3 real re-render leaks
- [ ] Learn and apply **Web Vitals monitoring** (Vercel Analytics or custom web-vitals library)
- [ ] Implement **virtual scrolling** from scratch for a 10,000-item list
- [ ] Write a **custom ESLint rule** for your team's coding standards
- [ ] Refactor an old project to use **React Server Components** end-to-end
- [ ] Build a **real-time sync engine** with WebSockets (collaborative todo list)
- [ ] Deep-dive **CSS containment, `content-visibility`, and `contain`** in a performance-critical component
- [ ] Open a **PR to an open-source library** you use (even docs or types count)

### 🎯 Level 2 Completion Criteria

- [ ] Design system published on npm with semantic versioning
- [ ] Case study blog post #2: "How I achieved 100 Lighthouse on [project]"
- [ ] 3 recorded screen-share demos of performance wins
- [ ] First open-source contribution merged

---

## 🟣 Level 3 — Architecture & Systems (Months 6–9)

*Think like a staff engineer. Systems over components. Tradeoffs over defaults.*

### 📚 Reading List

- [ ] **"Designing Data-Intensive Applications"** — Chapters 6–12 *(distributed systems, consistency, consensus)*
- [ ] **"The Staff Engineer's Path"** by Tanya Reilly
- [ ] **"Building Micro-Frontends"** by Michael Geers
- [ ] **"System Design Interview"** by Alex Xu — Vol. 1 (at minimum the frontend chapter + CDN/caching sections)
- [ ] **Vercel Engineering Blog** — Read every post from 2023–2026 on Turborepo, Next.js internals, edge
- [ ] **"Clean Architecture"** by Robert C. Martin *(apply frontend-specific thinking)*
- [ ] **"A Philosophy of Software Design"** by John Ousterhout

### 🛠️ Practical Tasks

- [ ] Architect a **frontend platform** for a hypothetical 50-engineer team: monorepo structure, shared CI/CD, deployment graph, testing strategy
- [ ] Design and build a **distributed state system** (Zustand + server state sync, or experiment with Tinybase/Redux-offline)
- [ ] Implement a **feature-flag system** from scratch with A/B test support
- [ ] Build a **micro-frontend** setup with module federation or iframe-based isolation; document tradeoffs
- [ ] Design a **caching strategy document** for a Next.js app at scale (ISR patterns, Stale-While-Revalidate, tag-based revalidation)
- [ ] Create an **RFC template** and write 3 RFCs for real technical decisions at Interswitch
- [ ] Lead a **frontend guild meeting** or tech talk in your organization
- [ ] Mentor a junior engineer through their first significant feature (document the journey)
- [ ] Build a **fully accessible component library** — WCAG 2.2 AA compliant; test with screen readers
- [ ] Write a **testing strategy** for a complex UI: unit, integration, visual regression, E2E (Playwright)

### 🎯 Level 3 Completion Criteria

- [ ] Architecture document published (blog or internal wiki)
- [ ] One mentee ships a feature to production
- [ ] Blog post #3: "Designing a frontend platform for 50 engineers"
- [ ] Accessibility audit report for your design system

---

## 🟠 Level 4 — AI-Native & Edge (Months 10–13)

*Build the future. AI-augmented interfaces, edge-native apps, and real-time collaborative systems.*

### 📚 Reading List

- [ ] **"Hands-On Large Language Models"** by Jay Alammar & Maarten Grootendorst
- [ ] **"Building LLM Applications"** by Chip Huyen (free online)
- [ ] **Vercel AI SDK documentation** — read every page and example
- [ ] **OpenAI / Anthropic cookbooks** — build 5 examples from their official guides
- [ ] **"Fundamentals of Data Engineering"** by Joe Reis & Matt Housley *(pick chapters on streaming and real-time)*
- [ ] **Fly.io / Cloudflare Workers docs** — edge runtime deep dive
- [ ] **Liveblocks / PartyKit / Yjs** documentation and architecture blogs

### 🛠️ Practical Tasks

- [ ] Build an **AI-native UI** with streaming responses, tool-calling, and "thinking" states (like Cursor or ChatGPT)
- [ ] Implement **RAG (Retrieval-Augmented Generation)** with a frontend that visualizes source documents
- [ ] Integrate **multi-modal AI** (vision + text) into a project — image analysis UI
- [ ] Deploy a Next.js app to the **edge** with geo-distributed read replicas; measure latency globally
- [ ] Build a **real-time collaborative canvas** (like Figma or your Ghost AI project) with CRDTs or Operational Transform
- [ ] Experiment with **WebGPU** for client-side ML inference (TensorFlow.js or ONNX Runtime Web)
- [ ] Create an **AI agent loop** in a frontend: tool definitions, execution planning, and UI state machines
- [ ] Ship a **production app** that uses LLMs as a core feature (not just a chatbot — integrated into workflow)

### 🎯 Level 4 Completion Criteria

- [ ] AI-native app deployed and used by real people (even just your team)
- [ ] Technical blog post #4: "Building real-time collaborative AI interfaces"
- [ ] Conference talk proposal submitted (React Conf, Next.js Conf, or local meetup)
- [ ] One experimental repo with 50+ GitHub stars

---

## 🔴 Level 5 — Elite Engineer (Months 14–18+)

*Impact at scale. Thought leadership. Building other engineers.*

### 📚 Reading List

- [ ] **"The Mythical Man-Month"** by Frederick Brooks
- [ ] **"High Output Management"** by Andrew Grove
- [ ] **"An Elegant Puzzle"** by Will Larson
- [ ] **"Staff Engineer: Leadership Beyond Management"** by Will Larson
- [ ] **Google's Site Reliability Engineering (SRE) book** — Frontend reliability chapters
- [ ] **"The DevOps Handbook"** — relevant chapters on CI/CD and deployment
- [ ] **Subscribe to and read**: Vercel Engineering, Linear's blog, Figma's engineering blog, and Dan Abramov's essays

### 🛠️ Practical Tasks

- [ ] **Define and ship** a frontend platform initiative at Interswitch that affects 10+ engineers
- [ ] **Speak at a tech conference** or host a well-attended meetup talk
- [ ] **Publish a technical book or course** (even a short ebook or video course on a platform like Egghead)
- [ ] **Maintain an open-source project** with active collaborators (not just your own code)
- [ ] **Write a technical strategy document** for your org's next 2 years of frontend architecture
- [ ] **Interview 5 senior/staff engineers** about their career paths; publish findings
- [ ] **Build a personal brand**: consistent technical writing, Twitter/X threads, or YouTube
- [ ] **Lead a hiring process**: define an interview loop for senior frontend engineers at your company

### 🎯 Level 5 Completion Criteria

- [ ] Public talk delivered (conference, meetup, or recorded webinar)
- [ ] Technical content published consistently for 6+ months
- [ ] One open-source project with active community
- [ ] Promoted to Senior/Staff or equivalent, or validated equivalent impact

---

## 🗓️ Weekly Rhythm Template

| Day           | Focus                                                          |
| ------------- | -------------------------------------------------------------- |
| **Monday**    | Read for 1 hour + implement one micro-task                     |
| **Tuesday**   | Build — active coding on your learning project                 |
| **Wednesday** | Read for 1 hour + review and reflect on Monday's work          |
| **Thursday**  | Build — active coding + experiment with new concepts           |
| **Friday**    | Write — blog post, documentation, or notes summing up the week |
| **Weekend**   | Deep work block (3–4 hours) for hard projects or books         |

---

## 📈 Progress Tracking Rules

1. **Check the box only after you can explain the concept to someone else** (Feynman technique).
2. **Every level must have at least one shipped project or published post** before advancing.
3. **Revisit prior levels** if you find gaps during implementation.
4. **Update this file monthly** — strike through completed items, add notes, and reflect.

---

## 📝 Monthly Reflection Prompts

At the end of each month, answer these in a new note:

1. What did I build this month?
2. What did I learn that surprised me?
3. What do I still not understand?
4. What will I focus on next month?
5. Am I on track for my current level's completion criteria?

---

## 💡 Motivation Anchors

> *"The world doesn't need another React developer. It needs frontend engineers who can design performant, accessible, AI-native systems — and communicate why it matters."*

> *"You already have the right sensibility. Scale it by shipping more, teaching more, and going deeper into the stack."*

---

**Last Updated:** 2026-05-02
**Started:** ___________
**Current Level:** 🟢 Level 1 — Foundations
**Next Milestone:** Complete Level 1 + publish first blog post
