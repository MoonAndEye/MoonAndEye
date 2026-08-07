## 👋 Marvin Lin · MoonAndEye

**iOS/macOS developer in Taipei. 9+ years shipping production apps.**
Right now I'm building my own agent from scratch — and publishing a build log every single day.

▶️ **[Subscribe to Marvin Builds AI on YouTube](https://www.youtube.com/@MarvinBuildsAI?sub_confirmation=1)** — real AI-agent workflows, hands-on.

[![YouTube](https://img.shields.io/badge/YouTube-Marvin%20Builds%20AI-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@MarvinBuildsAI)
[![Blog](https://img.shields.io/badge/Blog-marvinswift.com-2563EB)](https://www.marvinswift.com)
[![X](https://img.shields.io/badge/X-@atimisMoon-000000?logo=x&logoColor=white)](https://x.com/atimisMoon)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marvin%20Lin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marvinswift/)

---

## 🎥 Marvin Builds AI

[**Marvin Builds AI**](https://www.youtube.com/@MarvinBuildsAI) is my YouTube channel about real AI-agent workflows. I hand agents actual tasks and watch how they read requirements, run code, fix mistakes, deploy, and verify results.

Not demo reels — the point is the control flow behind the demo: how coding agents and automation become workflows you can verify, reuse, and actually keep control of.

▶️ **[Watch the latest videos](https://www.youtube.com/@MarvinBuildsAI/videos)** · **[Subscribe](https://www.youtube.com/@MarvinBuildsAI?sub_confirmation=1)**

---

## 🤖 Building now: a custom agent for acceptance testing

Not another coding agent — those already exist and they're good. Mine solves a different problem.

**It's built for whoever does the acceptance testing.** In most teams that's PM and QA, and they're the ones actually blocked: they can't build the latest branch, and they can't easily prove a bug is really fixed in *this* build. Codex and Claude are available to them, but someone still has to set up the repo, environment, credentials and workflow first. The tools exist; the barrier doesn't go away.

So the agent wraps what developers have already set up, and hands it over as something a non-developer can just use:

> *"Build me the latest version."*
> *"Confirm whether this bug is fixed."*
> *"Verify this feature against the ticket."*

**First capability — specification acceptance testing.** Start from a Jira ticket or plain-language acceptance criteria → switch to the target branch → prepare the environment → build for iOS Simulator or Android Emulator → drive the app → capture screenshots as evidence → generate HTML and PDF reports → deliver to a chat channel.

**Signature Abilities** — capabilities unique to this agent, each with its own GUI page so they're usable directly instead of staying buried behind a prompt. The first is **spec-diff**: give it an old spec and a new spec, get back a structured, human-readable report of what changed, what was added, and what was removed. It generalized further than planned — contracts, architecture designs, even trading rules.

Currently in **Alpha**.

📓 **[Agent Build Log](https://www.marvinswift.com/en/programming/)** — one episode a day, bilingual (繁體中文 / English).

---

## 🚀 Shipped

| Project | What it is |
|---|---|
| [**Earnings Rosetta**](https://earningsrosetta.com/en?utm_source=github) | U.S. earnings-call platform — verbatim transcripts with AI-generated summaries, so you can grab the highlights fast. [iOS & Android](https://earningsrosetta.com/en/download?utm_source=github) |
| [**Stock Toolbar**](https://apps.apple.com/tw/app/id6455497589) | macOS menu-bar app: type a ticker, get the Taiwan stock price — without leaving what you're doing. |
| [**King of Song Quiz**](https://apps.apple.com/tw/app/king-of-song-quiz/id1273605195) | Song-guessing game. Five songs a round, faster correct guess scores higher. My first shipped game. |
| **Backwards Clock** | iOS tribute to Grace Hopper's counter-clockwise office clock. *(Off the App Store)* |

---

## 🧰 Stack

**Mobile** — Swift · SwiftUI · Objective-C · Flutter/Dart · Kotlin
**Backend** — Cloudflare Workers · D1 · KV · Python (Django / FastAPI)
**Practice** — clean architecture · unit testing · CI/CD · serverless

---

## ✍️ Writing

Bilingual posts (繁體中文 / English) on **[marvinswift.com](https://www.marvinswift.com)**:
[Agent & Programming](https://www.marvinswift.com/en/programming/) ·
[Swift](https://www.marvinswift.com/en/swift/) ·
[Unit testing](https://www.marvinswift.com/en/unitTesting/) ·
[Videos](https://www.marvinswift.com/en/videos/)
