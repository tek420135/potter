# PotGrowHub Roadmap (concise)

Vision: Build the Socket — an AI-powered cannabis metaverse that lets users design, preview, and procure cannabis-related products with AR/VR, 3D PoD, and voice-first AI guidance.

Phases & Priorities

Phase 0 — Legal & Data (week 0)
- LEGAL.md: age verification and compliance notes
- DATA_INDEX.md: curate open datasets (strains, cultivation, product catalogs)

Phase 1 — AR Demo & Core UX (week 1)
- Task 1.1: AR demo page (one GLTF bong + web AR placement)
- Task 1.2: Sticker/decal editor (upload + choose assets)
- Task 1.3: Apply decal to 3D preview (three.js)
- Task 1.4: AR preview with decal applied (model-viewer/WebXR)
- Task 1.5: Mock order flow (add to cart → mock supplier quote → checkout simulation)

Phase 2 — Chat MVP & File Upload (weeks 2–6)
- Task 2.1: Minimal chat UI (text) with send, history, and persona config
- Task 2.2: File upload + basic parsing (txt, md, pdf)
- Task 2.3: Small RAG pipeline (vector DB + retrieval of curated docs)

Phase 3 — 3DPoD Integration & Supplier Orchestration (weeks 6–12)
- Task 3.1: Connect one 3DPoD partner (or mock) for GLTF/STL submission
- Task 3.2: Supplier adaptor microservice and webhook handling
- Task 3.3: Order tracking UI (map-dot mock)

Phase 4 — Voice, Gamification & Monetization (months 3–6)
- Task 4.1: Voice input (Web Speech API) + TTS
- Task 4.2: Budz/Nugz reward engine (basic)
- Task 4.3: Initial marketing automation hooks (SEO templates)

Phase 5 — Scale & IoT (post-MVP)
- Delivery & rideshare integrations, advanced AR/VR rooms, IoT growroom control, supplier network expansion.

MVP Acceptance Criteria (short)
- Mobile AR demo: user customizes decal, places the bong in AR, and can submit a mock order.
- Chat: basic text chat responds with curated content and acknowledges uploaded files.
- No inventory: all orders route to mock supplier flows.

Immediate next tasks (high priority)
1. Build AR demo page (prototype/index.html)
2. Sticker editor and decal upload
3. 3D preview update to reflect decal
4. AR placement with model-viewer or WebXR
5. Mock supplier API + simulated checkout
6. LEGAL.md with age gating and disclaimers

Contact

Repo owner: tek420135
