# 👋 I'm Aby | Founder & Full-Stack Product Engineer

I ship ideas, build high-performance systems, and lead products from 0 to 1. My work spans the entire vertical stack, from TS, Go and Rust backends, React or Vanilla JS Frontends, to AI-driven orchestration and industrial-grade UX

---

### 🏛️ What's Inside

#### ⭐ Highlight Reel

| Project                                                                                                     | What It Shows                                                                        |
| :---------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- |
| [raft-consensus](https://github.com/aiberk/distributed-systems/tree/main/raft-consensus)                    | Leader election, log replication, crash recovery, and re-election                    |
| [p2p-sync-engine](https://github.com/aiberk/offline-first-pwa/tree/main/p2p-sync-engine)                    | WebRTC state machine with retry logic, timeout handling, and auto-reconnect          |
| [concurrent-message-pipeline](https://github.com/aiberk/iot-platform/tree/main/concurrent-message-pipeline) | Goroutine worker pool with buffered channel fan-out and per-message context timeouts |
| [auto-adapt-algorithm](https://github.com/aiberk/real-time-saas-backend/tree/main/auto-adapt-algorithm)     | Constrained time redistribution across timers with iterative constraint satisfaction |
| [byzantine-generals](https://github.com/aiberk/distributed-systems/tree/main/byzantine-generals)            | Consensus with traitors, proving the 3f+1 bound with configurable generals           |
| [wal-crash-recovery](https://github.com/aiberk/distributed-systems/tree/main/wal-crash-recovery)            | Write-ahead log with simulated crash and full replay recovery                        |
| [sms-state-machine](https://github.com/aiberk/real-time-saas-backend/tree/main/sms-state-machine)           | Conversational task routing via Twilio, 15+ input types, queue management            |
| [file-based-db](https://github.com/aiberk/distributed-systems/tree/main/file-based-db)                      | Fixed-size records with O(1) seek, status sentinel, and tombstone deletes            |
| [http-server](https://github.com/aiberk/distributed-systems/tree/main/http-server)                          | HTTP/1.1 from raw TCP sockets, no net/http, hand-rolled request parsing              |
| [response-clustering](https://github.com/aiberk/real-time-saas-backend/tree/main/response-clustering)       | K-Means clustering on OpenAI embeddings in an edge function                          |

---

#### [Real-Time SaaS Backend](https://github.com/aiberk/real-time-saas-backend) — TypeScript, Supabase, Stripe, Twilio, OpenAI

| Script                                                                                                      | What It Shows                                                               |
| :---------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| [event-buffering-system](https://github.com/aiberk/real-time-saas-backend/tree/main/event-buffering-system) | Write buffering with chunked flush, failure recovery, and event aggregation |
| [auto-adapt-algorithm](https://github.com/aiberk/real-time-saas-backend/tree/main/auto-adapt-algorithm)     | Constrained time redistribution across timers with 3 distribution modes     |
| [timer-state-machine](https://github.com/aiberk/real-time-saas-backend/tree/main/timer-state-machine)       | Complex React state machine with versioned persistence and auto-adapt       |
| [api-security](https://github.com/aiberk/real-time-saas-backend/tree/main/api-security)                     | Auth + rate limiting + input validation for serverless endpoints            |
| [sms-state-machine](https://github.com/aiberk/real-time-saas-backend/tree/main/sms-state-machine)           | Conversational task routing via Twilio — 15+ input types, queue management  |
| [compliance-reporting](https://github.com/aiberk/real-time-saas-backend/tree/main/compliance-reporting)     | Unified audit trail across web + SMS channels in a single PL/pgSQL RPC      |
| [response-clustering](https://github.com/aiberk/real-time-saas-backend/tree/main/response-clustering)       | K-Means clustering on OpenAI embeddings in an edge function                 |
| [organization-analytics](https://github.com/aiberk/real-time-saas-backend/tree/main/organization-analytics) | Cross-sequence analytics engine with composable RPCs                        |
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

#### [School Work](https://github.com/aiberk/distributed-systems) - Go, Rust, Zig, Java, TypeScript

| Script                                                                                                   | What It Shows                                                                                |
| :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------- |
| [c-to-python-transpiler](https://github.com/aiberk/distributed-systems/tree/main/c-to-python-transpiler) | AST visitor that emits Python from a C syntax tree with indentation tracking                 |
| [x86-code-generator](https://github.com/aiberk/distributed-systems/tree/main/x86-code-generator)         | AST-to-assembly with stack frames, register formals, and label-based control flow            |
| [type-checker](https://github.com/aiberk/distributed-systems/tree/main/type-checker)                     | Bottom-up type propagation with symbol table lookup and error recovery                       |
| [dining-philosophers](https://github.com/aiberk/distributed-systems/tree/main/dining-philosophers)       | Resource hierarchy deadlock prevention with configurable philosophers and starvation metrics |
| [reliable-transport](https://github.com/aiberk/distributed-systems/tree/main/reliable-transport)         | Selective Repeat sliding window with per-packet timers over a lossy channel                  |
| [replicated-kv-store](https://github.com/aiberk/distributed-systems/tree/main/replicated-kv-store)       | Master/follower quorum writes (2 of 3) with WAL, fan-in ACKs, and crash demo                 |
| [map-reduce](https://github.com/aiberk/distributed-systems/tree/main/map-reduce)                         | Goroutine-parallel map/shuffle/reduce with word count and inverted index                     |
| [byzantine-generals](https://github.com/aiberk/distributed-systems/tree/main/byzantine-generals)         | Consensus with traitors, proving the 3f+1 bound with configurable generals                   |
| [raft-consensus](https://github.com/aiberk/distributed-systems/tree/main/raft-consensus)                 | Leader election, log replication, crash recovery, and re-election                            |
| [bloom-filter](https://github.com/aiberk/distributed-systems/tree/main/bloom-filter)                     | Probabilistic set membership with measured vs theoretical false positive rates               |
| [wal-crash-recovery](https://github.com/aiberk/distributed-systems/tree/main/wal-crash-recovery)         | Write-ahead log with simulated crash and full replay recovery                                |
| [http-server](https://github.com/aiberk/distributed-systems/tree/main/http-server)                       | HTTP/1.1 from raw TCP sockets, no net/http, hand-rolled request parsing                      |
| [custom-shell](https://github.com/aiberk/distributed-systems/tree/main/custom-shell)                     | Zig shell with fork/execvp and I/O redirection via dup2                                      |
| [page-replacement-sim](https://github.com/aiberk/distributed-systems/tree/main/page-replacement-sim)     | LRU cache in Rust with Rc/RefCell doubly linked list + HashMap                               |
| [thread-safe-task-queue](https://github.com/aiberk/distributed-systems/tree/main/thread-safe-task-queue) | Producer/consumer with backpressure, load shedding, and autoscaling modes                    |
| [bst-visualizer](https://github.com/aiberk/distributed-systems/tree/main/bst-visualizer)                 | AVL tree in TypeScript with D3.js rotation visualization                                     |
| [file-based-db](https://github.com/aiberk/distributed-systems/tree/main/file-based-db)                   | Fixed-size records with O(1) seek, status sentinel, and tombstone deletes                    |

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
