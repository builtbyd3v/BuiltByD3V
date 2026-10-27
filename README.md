# Hi, I'm Dev 👋

I build AI that runs on real hardware, from voice agents in a VR headset to ML models small enough to run on a phone, and I ship full-stack products solo.

B.S. Software Engineering student at Western Governors University ('27) and a CodePath alum with honors in WEB103 and AI110. Based in Gainesville, FL. Looking for **Summer 2027 SWE & AI internships**.

## What I've built

🏆 **[Albie](https://github.com/builtbyd3v/Albie)** · **1st Place Overall + MLH Best Open Source**, Gator Hack V at UF AI Days (Oct 2026) · [Devpost](https://devpost.com/software/albie) · [Demo](https://youtu.be/28D1QIcsdzI)  
An AI gator that lives in your Meta Quest 3 and helps you code, train models, and edit CAD just by talking. On a team of 5, I designed the voice architecture (Grok Realtime for speech, with code work handed to Claude Agent SDK agents) and authored 53 of 85 merged PRs.
- Raised natural-speech accuracy from 10% to about 90% with zero missed turns, using a simulated headset and a Claude-judged eval harness (2,339 scored turns)
- Built a 60-tool registry served to Grok as function calls and to Claude as an in-process MCP server, plus a proactive watcher that speaks up on code errors, crashes, and overfitting
- Streamed VS Code into the headset over WebRTC and built the extension the agent drives (calls cut from 0.3–1.1 s to under 0.1 s)

`Python` `FastAPI` `Claude Agent SDK` `Grok Realtime API` `WebRTC` `Unity`

**[samehere.dev](https://www.samehere.dev)** · solo, launching Nov 2026  
Profiles for CS students looking for hackathon teammates. Every stat is counted from real data (Devpost-verified prizes, shipped projects, GitHub contributions), never typed in. Each profile renders a FIFA-style card as a Discord and X link preview, an image, and an Apple Wallet pass with a QR code. I cut the card's uncached render from 4.5 s to about 1 s by drawing its 424-cell heatmap as one SVG.  
`Next.js` `React` `TypeScript` `Supabase` `Tailwind CSS` `Apple Wallet`

**[checkwith.us](https://checkwith.us)** · SwampHacks XII, team lead (Oct 2026)  
An iPhone app that protects older adults from scams: it filters scam texts on device, labels scam calls, and holds risky payments until a family member approves with Face ID. When a 67 MB DistilBERT crashed iOS's Message Filter, I shipped a 1 MB n-gram model that catches 96% of scams at a 2.4% false-alarm rate on 884 real texts.  
`Swift` `SwiftUI` `Core ML` `PyTorch` `Next.js` `PostgreSQL`

**[StepSafe](https://stepsafe.miami)** · ShellHacks 2026, with Ara Babigian (Sep 2026) · [Code](https://github.com/xvedara/shellhacks-2026)  
A head-mounted iPhone app that fuses LiDAR depth with on-device object detection to warn blind and low-vision pedestrians about obstacles, drop-offs, and fast-approaching objects, plus a live hazard map whose API merges nearby reports and labels them with an LLM. Built in 36 hours.  
`Swift` `ARKit` `YOLO11s` `TypeScript` `Next.js` `MongoDB`

## Open source

5 merged PRs to **[nodeterm](https://github.com/eneskirca/nodeterm)**, a node-based terminal manager for AI coding agents (Electron, TypeScript, whisper.cpp):

- [#1284](https://github.com/eneskirca/nodeterm/pull/1284) Made macOS dictation 9x faster (5.97 s to 0.64 s) by tracing a silent CPU fallback to Metal shaders hidden in `app.asar`
- [#1279](https://github.com/eneskirca/nodeterm/pull/1279) Fixed a speech-engine crash (4 of 4 runs) caused by uninitialized whisper.cpp params
- [#1285](https://github.com/eneskirca/nodeterm/pull/1285) Raised Liquid Glass text contrast from about 1:1 to at least 3:1 at every transparency level, with no frame-time cost
- [#1128](https://github.com/eneskirca/nodeterm/pull/1128) Added Cursor's agent CLI as a built-in agent with live status, usage meters, chat, resume, and permission modes
- [#1286](https://github.com/eneskirca/nodeterm/pull/1286) Fixed the dock's add menu overflowing short windows

## Tech

**Languages:** TypeScript, JavaScript, Python, Swift, SQL, HTML, CSS

**Frameworks:** React, Next.js, SwiftUI, FastAPI, Tailwind CSS

**AI:** Claude Code, Codex, Cursor, Claude Agent SDK, MCP, LLM APIs, Core ML, PyTorch

**Tools:** Git, GitHub, PostgreSQL, Supabase, Vercel

## Connect

🌐 [builtbyd3v.com](https://builtbyd3v.com) · 💼 [LinkedIn](https://linkedin.com/in/builtbydev) · 𝕏 [@builtbydev](https://x.com/builtbydev) · 📧 [contact@builtbyd3v.com](mailto:contact@builtbyd3v.com)
