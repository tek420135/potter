# PotGrowHub — The Socket (GanjaGuru AI)

PotGrowHub is a full-stack, community-first cannabis ecosystem that combines AI, AR/VR, and 3D print-on-demand to make growing, designing, and consuming smarter, more interactive, and highly personalized.

Core components

1. GanjaGuru AI Budtender — A conversational, voice-enabled AI that provides personalized strain recommendations, dosing tips, accessory suggestions, and business insights for growers or sellers. Multimodal: text, voice, and integration with AR/VR previews.
2. AR/VR & Virtual Grow Rooms — Place virtual cannabis accessories in your real environment (AR) or explore fully immersive virtual grow rooms (VR) for planning, education, and visualization.
3. 3D Print-on-Demand (3DPoD) — Design custom bongs, bowls, and merch with parametric customization and AR previews. Orders route to printers/suppliers for zero-inventory fulfillment.
4. Smart E-Commerce & Dropshipping — AI-driven product recommendations, dynamic pricing, automated supplier selection, shipping/tax calculations. No warehouse required.
5. Gamification & Community — Budz currency, Nugz reputation tiers, quests, badges, leaderboards, and trade circles to encourage engagement.
6. Onboarding & Support — Voice-first onboarding, community chat, expert guidance, and ticketing.
7. Sustainability & Legal Compliance — Eco-friendly materials, biodegradable packaging, and clear legal/age compliance flows. Users are responsible for local legality.

Value proposition

PotGrowHub is the "Socket": the infrastructure that connects creators, makers, growers, and consumers across the cannabis ecosystem. It reduces fragmentation by bringing AI guidance, immersive visualization, customization, and fulfillment into one platform.

Minimum Lovable Product (MLP) — the 1-week hook

Ship an AR demo that nails the magic moment:
- One high-quality 3D bong model
- Simple sticker/decal editor (upload or choose art)
- Instant WebAR placement (mobile-first) showing the customized bong on a real table
- One-click export/submit (mock order) and a visible CTA to "Design & AR demo — no signup"

Repository layout (suggested)

- /prototype — front-end demo (three.js / model-viewer / webxr)
- /api — backend endpoints for mock suppliers, orders, and file parsing
- /datasets — curated open datasets for strains, cultivation, slang, product specs
- README.md, ROADMAP.md, DESIGN.md, LEGAL.md

Getting started (developer)

1. Clone repo
2. Open /prototype/index.html (or run a static server: `npx serve .`)
3. Mobile: open the AR demo page in Safari (iOS) or Chrome (Android) with WebXR/model-viewer support

Contributing

Start by working on the AR demo in /prototype. Create issues for small, testable pieces (load model, apply decal, AR placement, mock checkout). Use the ROADMAP.md for priorities.

License

MIT
