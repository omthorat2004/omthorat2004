# Om Thorat

Full stack engineer
B.Tech Computer Science, 2026

**Frontend** · JavaScript, TypeScript, React, Next.js, Tailwind, Electron
**Backend** · Python, FastAPI, PostgreSQL, MongoDB, Redis

[Email](mailto:omthorat1005@gmail.com) · [LinkedIn](https://linkedin.com/in/omthoratcse) · [LeetCode](https://leetcode.com/u/mugiwara12345) · [Codeforces](https://codeforces.com/profile/RyujinOm)

## Open source

10+ pull requests merged across 4 upstream repositories.

**[OpenTelemetry Ecosystem Explorer](https://github.com/open-telemetry/opentelemetry-ecosystem-explorer/pulls?q=is%3Apr+author%3Aomthorat2004)** · CNCF
3 merged: Collector component URL restructure, Java agent version as a query parameter

**[studio-json-schema](https://github.com/ioflux-org/studio-json-schema/pulls?q=is%3Apr+author%3Aomthorat2004)** · ioflux
1 merged: parent/child navigation in the node popup, with the buttons rendering only when a node has one

**[FuturamaAPI](https://github.com/koldakov/futuramaapi/pulls?q=is%3Apr+author%3Aomthorat2004)**
4 merged: password-reset flow, signup page with validation

## Projects

**[Kai](https://github.com/omthorat2004/Kai)** · [site](https://omthorat2004.github.io/Kai/) · [download](https://github.com/omthorat2004/Kai/releases/latest)
Desktop launcher for dev servers. Saved projects start with one click: live ANSI logs per app, sub-applications grouped under one project, and process-group kills so stopping a server never leaves its port bound. Ships as a dmg for Apple Silicon and Intel.
`Electron` `React` `Vite`

**[Storely](https://github.com/omthorat2004/Storely)**
Vlog archive that stores video in a Telegram channel instead of paid cloud storage. Recordings are split into 18 MiB parts, because a bot may upload 50 MB but can only fetch 20 MB back, so anything larger uploads fine and is then unreadable. Parts go up one at a time under the per-chat rate limit, with `retry_after` honoured and progress in SQLite, so an interrupted upload resumes at the part that was in flight.
`React Native` `Expo` `TypeScript` `SQLite`

**[Milo](https://github.com/omthorat2004/Milo)** · [live app](https://milo-frontend-lake.vercel.app) · [site](https://milo-nu-two.vercel.app/) · building
Privacy-conscious resume analytics. Share a link instead of the file and see views, unique viewers, downloads, traffic sources, UTM campaigns, and time per page. Never who read it: no IP, no location, no fingerprinting, and the event schema has no field for them. The PDF stays where it already lives and is rendered with pdf.js, so every save goes through a tracked download. Unique viewers come from a random 24 hour browser id, not anything about the person. Resume URLs pass an SSRF guard, and links can expire or be revoked. Layered FastAPI backend, deployed on Vercel.
`Next.js` `FastAPI` `MongoDB` `TanStack Query` `pdf.js` `Three.js`

**[Dock](https://github.com/omthorat2004/dock)** · [live](https://dock-psi-drab.vercel.app/) · building
Revision workspace: a space per lesson, topics as cards on a canvas, each opening a tutor scoped to that topic. Bring-your-own Gemini key behind a provider abstraction.
`Next.js` `FastAPI` `MongoDB`

**[SyncSpace](https://github.com/omthorat2004/SyncSpace)**
Collaborative workspace for notes, links, and code snippets. Layered FastAPI backend, role-based permissions, Redis caching.
`FastAPI` `PostgreSQL` `Redis` `React`
