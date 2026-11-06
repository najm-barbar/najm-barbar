# Najm Barbar

Senior full-stack engineer. Realtime video, multiplayer games and the Firebase/GCP backends behind them.
Ten years in, solo owner of production systems since 2020, fully remote since 2018.

## What I build

| Product | What it is | My role |
|---|---|---|
| [Perfogram Studio](https://studio.perfogram.ai) | Live-broadcast studio (StreamYard-class): hosts, guests, overlays, polls and quizzes on a virtual stage streamed to YouTube, RTMP and HLS. White-labelled for three brands. | Sole backend engineer since 2020; 48 Cloud Functions, the Agora RTC stack, distribution pipeline and the 2026 AI features. |
| [Kroot](https://playkroot.com) | Multiplayer card-game platform for the MENA market: Trix, Tarneeb, Hand and Banakil on one shell, web and native apps. | Sole engineer. Server-authoritative engines with AI opponents, native shell with a versioned web bridge, economy, ads and IAP. |
| No Laugh (ممنوع تضحك) | Flutter "don't laugh" game: ML Kit smile detection ends the round, face-to-face duels over Agora video. | Specified, directed and reviewed an AI-built codebase; shipped to iOS and Android. |
| Guess the Flag (تحدّي الأعلام) | Offline-first Arabic flag quiz with a custom Arabic keyboard and phonetic answer matching; 1v1 online play with a bot fallback. | Same AI-directed delivery, with a pure TypeScript match reducer mirrored line-for-line in Dart and kept identical by golden tests. |

## Things I am proud of

- Cut Perfogram's end-of-broadcast teardown from 13–36 seconds to about 3 by reworking the recording choreography, and brought the go-live intro into sync with a pre-warmed cloud player.
- Designed Kroot's native-shell bridge: an append-only, capability-gated protocol with a remote kill switch, so the web app ships daily while App Store builds lag behind. CI rejects breaking changes.
- Took a Firebase bill apart before launch and removed roughly 840k Firestore reads a day at the design load by replacing listener stacks and heartbeats with event-driven state.
- Built live host transcription over the OpenAI realtime API and an in-studio assistant whose tool calls execute in the browser, with per-account gating and a cost ledger.
- Traced a "video loader stuck" bug across React stale closures and the Agora SDK's mute semantics, and replaced the publish chain with a serial track-sync queue.

## How I work

I own systems end to end: product conversations, architecture, implementation, rules and security, deploys, cost, and the 2 a.m. incident. For React, React Native, Node and Firebase I write the code by hand. For Flutter I have no hands-on background; the two Flutter apps above were built by AI coding agents working to my specs and reviews, and I say so on my CV.

## Why there is no public code here

Everything I have built in the last ten years is commercial and private. The contribution graph reflects that private work. I am happy to walk through any of these systems' architecture in a call.

## Contact

- Email: eng.barbar@gmail.com
- Based in Damascus, Syria. Remote, open to relocation. Argentine and Syrian citizen.
- Arabic (native), English (fluent), Spanish (conversational).
