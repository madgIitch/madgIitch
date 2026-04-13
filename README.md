# José Ortiz Roldán

**Fullstack Developer** · React / React Native · Supabase · TypeScript

Junior developer with real production experience. I build complete products — architecture, backend, frontend, and deployment — not just UI layers.

Open to **junior positions and paid internships** in web or mobile development.

📫 peorrr2@gmail.com &nbsp;·&nbsp; 📍 Sevilla (open to remote)

---

## Stack

**Mobile & Web** — React Native, Expo, React, Next.js, PWA, TypeScript  
**Backend** — Supabase (PostgreSQL + Edge Functions/Deno + Realtime), Firebase, Node.js  
**Payments & Services** — Stripe, FCM v1, RevenueCat, Plaid, Cloud Run, Docker  
**Tools** — Git, Figma, Android Studio, Expo EAS, VS Code

---

## Projects

### [HomiMatch](https://github.com/HomiMatch/HomiMatchApp) — Roommate matching app
*React Native · Expo · TypeScript · Supabase · Stripe · FCM*

Mobile platform for finding rooms and flatmates, currently in final testing before App Store / Google Play release. I built and own the entire stack.

- **Recommendation engine** with weighted scoring: 40% lifestyle · 30% budget · 20% location · 10% demographics. Separate flows for seekers and owners, with 1.4× visibility boost for premium users.
- **~45 Supabase Edge Functions** in Deno with Zod validation covering auth, matching, messaging, payments, push notifications, and admin logic.
- **Full Stripe integration**: checkout sessions, customer portal, webhooks (`subscription.updated`, `invoice.payment_failed`), transactional rollback on DB errors.
- **FCM v1 push notifications** without Firebase SDK — manually signing JWTs with `crypto.subtle` to avoid heavy Deno dependencies.
- **Real-time chat** via `postgres_changes` subscriptions scoped per conversation.
- **Rate-limited message requests**: 1 lifetime request (free) / 3 per week (premium), enforced server-side.
- **Shared lock on token refresh** to prevent concurrent JWT burns.

---

### [What's In My Fridge](https://github.com/madgIitch/What-s-in-my-fridge-) — AI kitchen assistant
*React Native · Expo · TypeScript · Firebase · WatermelonDB · Cloud Run*

Android app for scanning receipts, managing pantry inventory, and suggesting recipes.

- AI recipe import pipeline from YouTube / Instagram / TikTok / blog URLs: Whisper (audio transcription) + LLM (ingredient and step extraction).
- Containerized AI services on Cloud Run (Ollama + Whisper) integrated with Firebase Cloud Functions.
- Offline-first architecture with WatermelonDB (reactive SQLite) and bidirectional Firestore sync.
- Freemium monetization with RevenueCat: paywall, entitlements, purchase restoration, monthly usage limits.

---

### [Tonal Field](https://tonal-field.vercel.app) — Accessible color system generator
*Next.js 14 · TypeScript · TailwindCSS · Supabase · Stripe*

SaaS tool for generating color systems based on Energy & Tension dimensions using OKLCH color space.

- Interactive 2D field for exploring perceptually uniform color spaces.
- Semantic palette generation with WCAG contrast auto-fix and color blindness simulation.
- Full SaaS stack: Auth, PostgreSQL with RLS, Edge Functions, Stripe subscriptions.

---

### [FinTrack](https://github.com/madgIitch/FinTrack-main2) — Personal finance PWA
*JavaScript · Firebase · Node.js · IndexedDB · Service Workers*

Progressive Web App for income and expense tracking with full offline support.

- Real-time sync and offline-first architecture via IndexedDB + Service Workers.
- Interactive dashboards and financial visualizations.
- Bank account integration via Plaid API.

---

### [SwipeClean](https://github.com/madgIitch/SwipeClean) — Gallery cleanup for Android
*Kotlin · Jetpack Compose*

Gallery management app using multidirectional swipe gestures (delete, save, share, Zen mode).

- Zen Mode with audio, timer, and haptic feedback.
- MVVM + StateFlow, fluid animations.

