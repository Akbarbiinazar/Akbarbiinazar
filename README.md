## Hi, I'm Akbar 👋

I'm a Fullstack Engineer with 4+ years of commercial experience building production applications with React, Next.js, TypeScript, NestJS, and PostgreSQL. My recent work includes AI-powered features for insurance analytics, customer conversations, and document processing.
I work across frontend, backend, integrations, and delivery. I use AI coding agents to move faster, but I write the implementation plan, review generated changes and tests, and verify behavior before release.

📍 Bishkek, Kyrgyzstan · UTC+6 · Open to remote Fullstack / AI Engineer and Software Engineer roles

---

### What I'm building

**[Fibe](https://apps.apple.com/app/fibe/id6761101346)** — Event-discovery product for Kyrgyzstan. Grew it from 0 to
**1200+ users organically**, with no paid marketing. Built the NestJS backend, the
interactive map system with event pins tied to real locations, and real-time event
flows; delivered the marketing site and organizer admin panel in React.
`NestJS · React · TypeScript · interactive maps · dynamic OG generation`
*Source is private (commercial product). Happy to walk through the code on a call.*

**Operonyx** — B2B automation for trucking dispatch, **running in production** with a
real carrier. AI pipelines that extract structured data from freight documents (email,
Telegram, PDFs), plus driver/dispatcher revenue automation and Telegram bot integrations.
`React · Next.js · TypeScript · NestJS · LLM pipelines`
*Private product, internal admin panel only. Happy to demo on a call.*

**[Throughline](https://throughline-beryl.vercel.app/)** *(in progress)* — An AI platform that maintains a startup's decision
registry and generates task specs from it, with every field traced back to its source.
Provenance is enforced as an architectural constraint, so the model structurally cannot
fabricate a citation. Business invariants live in the database schema, not in the prompt.
`Next.js 15 · TypeScript · Postgres + pgvector · Drizzle · Anthropic API`

Sales & Marketing CRM — multi-tenant platform & WhatsApp AI assistant | Independent / Contract
Built a multi-tenant CRM for sales teams, including pipelines, deals, contacts, appointments, custom fields, permissions, analytics, and WhatsApp integration. Extended the system with an AI assistant for customer conversations, released to client environments after pilot testing and fixes.
- Built a WhatsApp-based conversational AI assistant that answers initial customer questions from the company's published services, business details, and FAQ. Company admins can configure its name, greeting, and communication style.
- Supported Russian and Kyrgyz conversation flows, with language selection based on the customer's messages. Real-world Kyrgyz dialogue quality requires continued evaluation.
- Implemented lead qualification with configurable questions, and CRM updates for permitted contact/deal fields while preserving existing custom-field values.
- Connected the assistant to real appointment availability: it can suggest available slots and create an appointment only after the customer confirms a specific time. The backend generates the final appointment confirmation.
- Added human handoff: automation stops, an employee notification is created, and an actionable task can be assigned when someone is available.
- Kept critical actions under server-side validation: permissions, available appointment slots, and booking operations are enforced in application code rather than trusted to model instructions.
- Built AI evaluation and monitoring workflows, measured conversation/model usage, identified failures in intent handling and appointment booking, corrected those issues, and rolled out the assistant to clients.
Stack: Next.js · React · TypeScript · NestJS · PostgreSQL · Prisma · WebSockets · WhatsApp

AI & reliability: Conversational AI · LLM Integration · CRM Integration · Tool Calling · Intent Handling · AI Evals · Human-in-the-Loop · Server-Side Validation · Production Monitoring

Commercial product; source code and customer conversations are private.

Insurance platform — architecture modernization & AI analytics | Entwicklerburg (Staff-Eye Group)
Worked on an insurance platform and initiated an architectural refactor to support the product's next stage of development.
- Proposed a monorepo structure and Feature-Sliced Design (FSD) for the frontend, with clearer boundaries between application features and shared code.
- Considered future AI integrations during the architectural redesign, making it easier to introduce and coordinate AI capabilities without tightly coupling them to the UI.
- Added a Retrieval-Augmented Generation (RAG) capability and an AI chatbot for insurance data analytics, enabling users to explore insurance-related information through natural-language questions.
- Worked across architecture, frontend, and backend integration to bring the AI experience into the existing application.
Focus: System Architecture · Monorepo · Feature-Sliced Design · RAG · LLM Integration · Conversational AI · Insurance Analytics

Client project; implementation details and source code are not public.

---

### Where I've worked

**Entwicklerburg** (Staff-Eye Group) — Full stack cycle across multiple client projects
in an outsourcing setup: requirements, system design, frontend, backend, delivery.
Worked full-stack on [European Peace Ride](https://play.google.com/store/apps/details?id=com.staffeye.epr),
the official app for a cross-border cycling event (~250 riders), building event listings,
group chats, and broadcasts. Built the project's initial MVP solo beforehand (interactive
map, GPX routes, real-time tracking). Also built internal automation tools full-stack.

**wedevx** — Owned large features end to end on an edtech platform. Shipped an interactive
Linux environment for students and, working with DevOps, cut server costs from $8,000 to
$1,000/month through idle-detection and shutdown logic. Ran a full site redesign that
lifted conversion from 6% to 13%, and refactored the platform to Next.js 13 with RTK Query,
Zustand, and a Feature-Sliced monorepo.

**Discovery Studio** — Delivered client web products in a fast-paced outsourcing team:
real-time price comparison and an emergency-assistance service. Cut load times by 25%
through frontend performance work and built real-time features over WebSocket.

---

### What I work with

**Frontend** React · TypeScript · Next.js · Redux Toolkit · React Query · Zustand · Tailwind · SCSS
**Backend** NestJS · Node.js · PostgreSQL · REST · WebSockets · GraphQL
**AI** Claude / Anthropic API · LLM pipelines · prompt engineering · pgvector · agentic coding
**Tooling** Vite · Jest · Playwright · Docker · Git · Feature-Sliced Design

---

### How to reach me

[LinkedIn](https://linkedin.com/in/akbar-biinazar) · [Email](mailto:akbarbiinazar1@gmail.com) · [Telegram](https://t.me/akbonito)

Open to full-stack and frontend roles. I'm most useful where a product needs someone
who can take a feature from the interface through the API to the AI underneath.
