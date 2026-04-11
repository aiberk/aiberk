# 👋 I'm Aby | Founder & Full-Stack Product Engineer

I ship ideas, build high-performance systems, and lead products from 0 to 1. My work spans the entire vertical stack—from low-level CUDA kernels and Go backends to AI-driven orchestration and industrial-grade UX

---

### 🏛️ What's Inside

#### [Real-Time SaaS Backend](./Real-Time%20SaaS%20Backend) — TypeScript, Supabase, Stripe, Twilio, OpenAI

| Script                                                                        | What It Shows                                                               |
| :---------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| [event-buffering-system](./Real-Time%20SaaS%20Backend/event-buffering-system) | Write buffering with chunked flush, failure recovery, and event aggregation |
| [auto-adapt-algorithm](./Real-Time%20SaaS%20Backend/auto-adapt-algorithm)     | Constrained time redistribution across timers with 3 distribution modes     |
| [brand-audit-pipeline](./Real-Time%20SaaS%20Backend/brand-audit-pipeline)     | Multi-source scraping, AI comparison, cost tracking, PDF generation         |
| [timer-state-machine](./Real-Time%20SaaS%20Backend/timer-state-machine)       | Complex React state machine with versioned persistence and auto-adapt       |
| [api-security](./Real-Time%20SaaS%20Backend/api-security)                     | Auth + rate limiting + input validation for serverless endpoints            |
| [sms-state-machine](./Real-Time%20SaaS%20Backend/sms-state-machine)           | Conversational task routing via Twilio — 15+ input types, queue management  |
| [compliance-reporting](./Real-Time%20SaaS%20Backend/compliance-reporting)     | Unified audit trail across web + SMS channels in a single PL/pgSQL RPC      |
| [response-clustering](./Real-Time%20SaaS%20Backend/response-clustering)       | K-Means clustering on OpenAI embeddings in an edge function                 |
| [organization-analytics](./Real-Time%20SaaS%20Backend/organization-analytics) | Cross-sequence analytics engine with composable RPCs                        |
| [ai-business-insights](./Real-Time%20SaaS%20Backend/ai-business-insights)     | GPT-4 operational analysis with structured prompts and 24h caching          |
| [sms-data-model](./Real-Time%20SaaS%20Backend/sms-data-model)                 | Session lock, priority queue, audit trail — partial unique indexes + RPCs   |
| [stripe-webhook](./Real-Time%20SaaS%20Backend/stripe-webhook)                 | Manual HMAC-SHA256 verification + full subscription lifecycle handling      |

#### [IoT Platform](./IoT%20Platform) — Go, Rust, C++, Arduino, TypeScript, MQTT, InfluxDB

| Script                                                                                | What It Shows                                                                        |
| :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------- |
| [concurrent-message-pipeline](./IoT%20Platform/concurrent-message-pipeline)           | Goroutine worker pool with buffered channel fan-out and per-message context timeouts |
| [conditions-engine](./IoT%20Platform/conditions-engine)                               | Event-driven rule evaluation with operator dispatch and MQTT action publishing       |
| [multi-service-health-check](./IoT%20Platform/multi-service-health-check)             | Concurrent probing across PostgreSQL, InfluxDB, and MQTT with per-service timing     |
| [influx-measurement-introspection](./IoT%20Platform/influx-measurement-introspection) | Cross-database schema discovery joining InfluxDB meta-queries with PostgreSQL        |
| [device-sdk-rust](./IoT%20Platform/device-sdk-rust)                                   | Async MQTT client with builder pattern and trait-object function dispatch            |
| [device-sdk-cpp](./IoT%20Platform/device-sdk-cpp)                                     | RAII MQTT client with `std::function` dispatch and header-only design                |
| [device-sdk-arduino](./IoT%20Platform/device-sdk-arduino)                             | Embedded MQTT client with fixed-size dispatch and non-blocking loop integration      |
| [device-sdk-go](./IoT%20Platform/device-sdk-go)                                       | Goroutine + channel MQTT client with functional options and RWMutex dispatch         |
| [iot-data-hooks](./IoT%20Platform/iot-data-hooks)                                     | Composable React hooks with polling, AbortController, and typed API responses        |

#### [AST Compilers](./AST%20Compilers) — Java, JavaCC, x86-64 Assembly

| Script                                                             | What It Shows                                                                     |
| :----------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| [c-to-python-transpiler](./AST%20Compilers/c-to-python-transpiler) | AST visitor that emits Python from a C syntax tree with indentation tracking      |
| [x86-code-generator](./AST%20Compilers/x86-code-generator)         | AST-to-assembly with stack frames, register formals, and label-based control flow |
| [type-checker](./AST%20Compilers/type-checker)                     | Bottom-up type propagation with symbol table lookup and error recovery            |

#### [Markdown Rendering Engine](./Markdown%20Rendering%20Engine) — TypeScript, React, Puppeteer

| Script                                                                               | What It Shows                                                                   |
| :----------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| [markdown-to-pdf-pipeline](./Markdown%20Rendering%20Engine/markdown-to-pdf-pipeline) | Hand-rolled parser + Puppeteer slide rendering + pdf-lib merging                |
| [browser-markdown-parser](./Markdown%20Rendering%20Engine/browser-markdown-parser)   | Zero-dependency tokenizer with layout recognition and discriminated union types |
| [chart-hydration-system](./Markdown%20Rendering%20Engine/chart-hydration-system)     | Dual-context lazy loading: React.lazy for browser, DOM hydration for PDF        |
| [hybrid-markdown-editor](./Markdown%20Rendering%20Engine/hybrid-markdown-editor)     | Segment-aware editing with line-accurate source splicing                        |
| [slide-renderer](./Markdown%20Rendering%20Engine/slide-renderer)                     | Token-to-React pipeline with widget detection and theme-aware rendering         |

#### [Offline-First PWA](./Offline-First%20PWA) — TypeScript, React, WebRTC, IndexedDB

| Script                                                                       | What It Shows                                                                     |
| :--------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| [p2p-sync-engine](./Offline-First%20PWA/p2p-sync-engine)                     | WebRTC state machine with retry logic, timeout handling, and auto-reconnect       |
| [sync-ux-orchestration](./Offline-First%20PWA/sync-ux-orchestration)         | Multi-flow dialog with QR codes, OTP input, and state-driven UI                   |
| [offline-persistence-layer](./Offline-First%20PWA/offline-persistence-layer) | IndexedDB via Dexie with typed error hierarchy and atomic sync import             |
| [offline-first-store](./Offline-First%20PWA/offline-first-store)             | Zustand store with sync import, demo mode, and cross-entity referential integrity |

#### [D3 Data Visualization](./D3%20Data%20Visualization) — Next.js, TypeScript, D3.js

| Script                                                                           | What It Shows                                                                   |
| :------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| [nested-lookup-data-layer](./D3%20Data%20Visualization/nested-lookup-data-layer) | O(1) country × year access via nested Record for real-time choropleth rendering |
| [d3-brush-linked-charts](./D3%20Data%20Visualization/d3-brush-linked-charts)     | Interactive brush on a bar chart driving a filtered line chart in real time     |

#### [Search and Data Layer](./Search%20and%20Data%20Layer) — TypeScript, Node.js, MongoDB, Elasticsearch

| Script                                                                                             | What It Shows                                                                      |
| :------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- |
| [elasticsearch-resource-discovery](./Search%20and%20Data%20Layer/elasticsearch-resource-discovery) | Multi-field fuzzy search with relevance scoring, faceted filtering, and highlights |
| [bulk-write-optimization](./Search%20and%20Data%20Layer/bulk-write-optimization)                   | Replacing N sequential `save()` calls with a single MongoDB `bulkWrite`            |

#### [Java Thread Pipeline](./Java%20Thread%20Pipeline) — Java, Concurrency

| Script                                                                            | What It Shows                                                               |
| :-------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| [concurrent-pipe-simulator](./Java%20Thread%20Pipeline/concurrent-pipe-simulator) | Thread-per-filter pipeline with blocking queues and poison pill termination |

---

### 🛠 Tools of the Trade

| Category      | Stack                                                      |
| :------------ | :--------------------------------------------------------- |
| **Low-Level** | Go, Rust, C, C++, **CUDA**, Zig, Arduino                   |
| **AI / ML**   | Vanilla AI Orchestration, vLLM, Claude, Prompt Engineering |
| **Backend**   | Node.js, Express, Deno, Supabase/Vercel Edge Functions     |
| **Data**      | PostgreSQL, InfluxDB, MongoDB, Elasticsearch, Redis, S3    |
| **Frontend**  | React, Next.js, TypeScript, Tailwind, D3.js, Framer JS     |
| **Scripting** | Python, Pandas                                             |
| **Protocols** | MQTT, WebRTC, WebSockets, GraphQL, I2C, mDNS               |
| **Infra**     | Raspberry Pi, AWS, Vercel, Heroku                          |

---

### 🚦 Current Status

![Status](https://img.shields.io/badge/Status-Building_Actus_Logic-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-CUDA_Neural-Mesh-green?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Product_Engineering_&_CUDA-blue?style=flat-square)

---

### 📫 Let's Connect

- **LinkedIn:** [/in/abyiber](https://linkedin.com/in/abyiber)
- **Website:** [abyiber.com](https://abyiber.com)
- **Email:** [hello@abyiber.com](mailto:hello@abyiber.com)
