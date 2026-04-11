# 👋 I'm Aby | Founder & Full-Stack Product Engineer

I ship ideas, build high-performance systems, and lead products from 0 to 1. My work spans the entire vertical stack, from Go and Rust backends to AI-driven orchestration and industrial-grade UX

---

### 🏛️ What's Inside

#### [Real-Time SaaS Backend](https://github.com/aiberk/real-time-saas-backend) — TypeScript, Supabase, Stripe, Twilio, OpenAI

| Script                                                                                                      | What It Shows                                                               |
| :---------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| [event-buffering-system](https://github.com/aiberk/real-time-saas-backend/tree/main/event-buffering-system) | Write buffering with chunked flush, failure recovery, and event aggregation |
| [auto-adapt-algorithm](https://github.com/aiberk/real-time-saas-backend/tree/main/auto-adapt-algorithm)     | Constrained time redistribution across timers with 3 distribution modes     |
| [brand-audit-pipeline](https://github.com/aiberk/real-time-saas-backend/tree/main/brand-audit-pipeline)     | Multi-source scraping, AI comparison, cost tracking, PDF generation         |
| [timer-state-machine](https://github.com/aiberk/real-time-saas-backend/tree/main/timer-state-machine)       | Complex React state machine with versioned persistence and auto-adapt       |
| [api-security](https://github.com/aiberk/real-time-saas-backend/tree/main/api-security)                     | Auth + rate limiting + input validation for serverless endpoints            |
| [sms-state-machine](https://github.com/aiberk/real-time-saas-backend/tree/main/sms-state-machine)           | Conversational task routing via Twilio — 15+ input types, queue management  |
| [compliance-reporting](https://github.com/aiberk/real-time-saas-backend/tree/main/compliance-reporting)     | Unified audit trail across web + SMS channels in a single PL/pgSQL RPC      |
| [response-clustering](https://github.com/aiberk/real-time-saas-backend/tree/main/response-clustering)       | K-Means clustering on OpenAI embeddings in an edge function                 |
| [organization-analytics](https://github.com/aiberk/real-time-saas-backend/tree/main/organization-analytics) | Cross-sequence analytics engine with composable RPCs                        |
| [ai-business-insights](https://github.com/aiberk/real-time-saas-backend/tree/main/ai-business-insights)     | GPT-4 operational analysis with structured prompts and 24h caching          |
| [sms-data-model](https://github.com/aiberk/real-time-saas-backend/tree/main/sms-data-model)                 | Session lock, priority queue, audit trail — partial unique indexes + RPCs   |
| [stripe-webhook](https://github.com/aiberk/real-time-saas-backend/tree/main/stripe-webhook)                 | Manual HMAC-SHA256 verification + full subscription lifecycle handling      |

#### [IoT Platform](https://github.com/aiberk/iot-platform) — Go, Rust, C++, Arduino, TypeScript, MQTT, InfluxDB

| Script                                                                                                                | What It Shows                                                                        |
| :-------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- |
| [concurrent-message-pipeline](https://github.com/aiberk/iot-platform/tree/main/concurrent-message-pipeline)           | Goroutine worker pool with buffered channel fan-out and per-message context timeouts |
| [conditions-engine](https://github.com/aiberk/iot-platform/tree/main/conditions-engine)                               | Event-driven rule evaluation with operator dispatch and MQTT action publishing       |
| [multi-service-health-check](https://github.com/aiberk/iot-platform/tree/main/multi-service-health-check)             | Concurrent probing across PostgreSQL, InfluxDB, and MQTT with per-service timing     |
| [influx-measurement-introspection](https://github.com/aiberk/iot-platform/tree/main/influx-measurement-introspection) | Cross-database schema discovery joining InfluxDB meta-queries with PostgreSQL        |
| [device-sdk-rust](https://github.com/aiberk/iot-platform/tree/main/device-sdk-rust)                                   | Async MQTT client with builder pattern and trait-object function dispatch            |
| [device-sdk-cpp](https://github.com/aiberk/iot-platform/tree/main/device-sdk-cpp)                                     | RAII MQTT client with `std::function` dispatch and header-only design                |
| [device-sdk-arduino](https://github.com/aiberk/iot-platform/tree/main/device-sdk-arduino)                             | Embedded MQTT client with fixed-size dispatch and non-blocking loop integration      |
| [device-sdk-go](https://github.com/aiberk/iot-platform/tree/main/device-sdk-go)                                       | Goroutine + channel MQTT client with functional options and RWMutex dispatch         |
| [iot-data-hooks](https://github.com/aiberk/iot-platform/tree/main/iot-data-hooks)                                     | Composable React hooks with polling, AbortController, and typed API responses        |

#### [AST Compilers](https://github.com/aiberk/ast-compilers) — Java, JavaCC, x86-64 Assembly

| Script                                                                                             | What It Shows                                                                     |
| :------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| [c-to-python-transpiler](https://github.com/aiberk/ast-compilers/tree/main/c-to-python-transpiler) | AST visitor that emits Python from a C syntax tree with indentation tracking      |
| [x86-code-generator](https://github.com/aiberk/ast-compilers/tree/main/x86-code-generator)         | AST-to-assembly with stack frames, register formals, and label-based control flow |
| [type-checker](https://github.com/aiberk/ast-compilers/tree/main/type-checker)                     | Bottom-up type propagation with symbol table lookup and error recovery            |

#### [Markdown Rendering Engine](https://github.com/aiberk/markdown-rendering-engine) — TypeScript, React, Puppeteer

| Script                                                                                                             | What It Shows                                                                   |
| :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| [markdown-to-pdf-pipeline](https://github.com/aiberk/markdown-rendering-engine/tree/main/markdown-to-pdf-pipeline) | Hand-rolled parser + Puppeteer slide rendering + pdf-lib merging                |
| [browser-markdown-parser](https://github.com/aiberk/markdown-rendering-engine/tree/main/browser-markdown-parser)   | Zero-dependency tokenizer with layout recognition and discriminated union types |
| [chart-hydration-system](https://github.com/aiberk/markdown-rendering-engine/tree/main/chart-hydration-system)     | Dual-context lazy loading: React.lazy for browser, DOM hydration for PDF        |
| [hybrid-markdown-editor](https://github.com/aiberk/markdown-rendering-engine/tree/main/hybrid-markdown-editor)     | Segment-aware editing with line-accurate source splicing                        |
| [slide-renderer](https://github.com/aiberk/markdown-rendering-engine/tree/main/slide-renderer)                     | Token-to-React pipeline with widget detection and theme-aware rendering         |

#### [Offline-First PWA](https://github.com/aiberk/offline-first-pwa) — TypeScript, React, WebRTC, IndexedDB

| Script                                                                                                       | What It Shows                                                                     |
| :----------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| [p2p-sync-engine](https://github.com/aiberk/offline-first-pwa/tree/main/p2p-sync-engine)                     | WebRTC state machine with retry logic, timeout handling, and auto-reconnect       |
| [sync-ux-orchestration](https://github.com/aiberk/offline-first-pwa/tree/main/sync-ux-orchestration)         | Multi-flow dialog with QR codes, OTP input, and state-driven UI                   |
| [offline-persistence-layer](https://github.com/aiberk/offline-first-pwa/tree/main/offline-persistence-layer) | IndexedDB via Dexie with typed error hierarchy and atomic sync import             |
| [offline-first-store](https://github.com/aiberk/offline-first-pwa/tree/main/offline-first-store)             | Zustand store with sync import, demo mode, and cross-entity referential integrity |

#### [D3 Data Visualization](https://github.com/aiberk/d3-data-visualization) — Next.js, TypeScript, D3.js

| Script                                                                                                         | What It Shows                                                                   |
| :------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| [nested-lookup-data-layer](https://github.com/aiberk/d3-data-visualization/tree/main/nested-lookup-data-layer) | O(1) country × year access via nested Record for real-time choropleth rendering |
| [d3-brush-linked-charts](https://github.com/aiberk/d3-data-visualization/tree/main/d3-brush-linked-charts)     | Interactive brush on a bar chart driving a filtered line chart in real time     |

#### [Search and Data Layer](https://github.com/aiberk/search-and-data-layer) — TypeScript, Node.js, MongoDB, Elasticsearch

| Script                                                                                                                         | What It Shows                                                                      |
| :----------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- |
| [elasticsearch-resource-discovery](https://github.com/aiberk/search-and-data-layer/tree/main/elasticsearch-resource-discovery) | Multi-field fuzzy search with relevance scoring, faceted filtering, and highlights |
| [bulk-write-optimization](https://github.com/aiberk/search-and-data-layer/tree/main/bulk-write-optimization)                   | Replacing N sequential `save()` calls with a single MongoDB `bulkWrite`            |

#### [Java Thread Pipeline](https://github.com/aiberk/java-thread-pipeline) — Java, Concurrency

| Script                                                                                                          | What It Shows                                                               |
| :-------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| [concurrent-pipe-simulator](https://github.com/aiberk/java-thread-pipeline/tree/main/concurrent-pipe-simulator) | Thread-per-filter pipeline with blocking queues and poison pill termination |

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
![Status](https://img.shields.io/badge/Status-Learning_CUDA_&_Parallel_Systems-blueviolet?style=flat-square&logo=nvidia)
![Focus](https://img.shields.io/badge/Focus-High_Performance_Computing_&_AI-blue?style=flat-square)

---

### 📫 Let's Connect

- **LinkedIn:** [/in/abyiber](https://linkedin.com/in/abyiber)
- **Website:** [abyiber.com](https://abyiber.com)
- **Email:** [hello@abyiber.com](mailto:hello@abyiber.com)
