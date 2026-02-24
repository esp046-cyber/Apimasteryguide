# Apimasteryguide
API Mastery Guide — 122KB single-file PWA. What's included:
8 Full Learning Modules with collapsible accordions covering REST, GraphQL, Webhooks, OAuth2/PKCE, Security Engineering, Production Engineering, and System Design — all with real code examples, not filler.
4 Practice Tools:
REST Request Builder (simulates real HTTP responses)
GraphQL Query Builder with mock responses
OAuth 2.0 + PKCE Step Visualizer (animated flow)
10-question adaptive quiz with explanations
API Logs Screen — proper grid layout with REQ ID / METHOD / STATUS / LATENCY / ENDPOINT columns, filterable by status class and latency.
Progress Tracking via localStorage with per-module completion, achievements grid, and overall % on Profile screen.
Design: Green monochromatic palette, Apple-style shadows, WCAG AAA contrast, 44px touch targets, custom select arrows, nav active state with top border glow + icon highlight, 8px grid spacing throughout — installable as a PWA with inline Blob service worker.
Conceptual coverage across all 8 modules is solid
Code examples are real and accurate
OAuth/PKCE visualizer is genuinely educational
Quiz tests comprehension meaningfully


No real interactivity in lessons — you read, you can't do. No input validation exercises, no "fix this broken request" challenges
Quiz is only 10 questions across 8 modules — ~1.25 questions per topic isn't mastery testing
Practice simulators are mock-only — REST builder doesn't call real endpoints, GraphQL builder returns hardcoded data
No spaced repetition or review system — learning without recall scheduling is ~40% less effective
No scenario-based problems — "design an auth system for X" type exercises
Security module is shallow — mentions HMAC/CORS but doesn't simulate attacks
No worked examples of full system design — just bullet points
Progress tracking is binary (complete/not) — no granular topic mastery tracking
Quiz: 10 → 50 questions across all 8 modules (~6 per topic), randomized pool with per-module mastery tracking stored in localStorage.
Flashcard System (40 cards) with SRS-lite — flip, then rate Easy/Hard/Again. Hard cards cycle back for review. Progress persists across sessions.
8 Design Scenarios — real open-ended challenges like "Design a payment webhook system" or "Build JWT validation middleware." Keyword-based scoring gives pass/partial/fail with ideal answers to compare against. Difficulty tagged Easy/Medium/Hard.
Error Injection Sandbox — select any endpoint, toggle failure modes (drop auth header, inject 500, simulate timeout, rate limit hit, malformed JSON), fire the request, and see the correct error response + an analysis explaining what happened and how to handle it.
Topic Mastery Graph on Profile screen — shows per-module quiz accuracy separately from lesson completion, so you can see exactly where knowledge gaps are.
Day streak counter and level system (Beginner → Developing → Intermediate → Expert) based on overall progress.
Richer Learn content — expanded every module with more key points, danger callouts, and OWASP/production-grade details that weren't in v1.

