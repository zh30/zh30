<h1 align="center">Henry Zhang</h1>

<p align="center">
  <strong>AI tool builder · independent developer</strong>
</p>

<p align="center">
  I design and ship practical AI tools for real workflows — browser extensions,
  developer utilities, and creator tools — with React, TypeScript, and Cloudflare.
</p>

<p align="center">
  <a href="https://zhanghe.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-zhanghe.dev-0f172a?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>
  <a href="https://zhanghe.dev/products"><img alt="Products" src="https://img.shields.io/badge/Products-Product%20Lab-111827?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>
  <a href="https://zhanghe.dev/posts"><img alt="Blog" src="https://img.shields.io/badge/Blog-Build%20Notes-1f2937?style=for-the-badge&logo=markdown&logoColor=white" /></a>
  <a href="https://x.com/zhanghe"><img alt="X" src="https://img.shields.io/badge/X-@zhanghe-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/zhanghe/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Henry%20Zhang-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

## What I Build

A narrow, repeated friction point becomes a small product, close to the page, the diff, or the file already on the machine.

| Lane                | What I ship                                      | Instinct                                      |
| ------------------- | ------------------------------------------------ | --------------------------------------------- |
| Browser AI          | On-device translation and page-side assistance   | Keep the reading context; prefer local models |
| Creator tools       | Local video, covers, lyrics, and photo conversion | Keep the file in the browser                 |
| Developer utilities | Commit messages, a JS runtime, and agent channels | Make routine engineering more direct          |
| Edge apps           | React and TypeScript on Cloudflare               | Workers, D1, R2 — small enough to debug       |

```ts
const henry = {
  position: 'AI Tool Builder',
  base: 'zhanghe.dev',
  builds: ['browser AI', 'creator tools', 'developer utilities'],
  stack: ['React', 'TypeScript', 'Rust', 'Cloudflare Workers', 'D1', 'R2'],
  openSource: ['amberjs'],
  filter: 'real workflow problems',
  ship: true,
} as const;
```

## Open Source

**[Amberjs](https://github.com/zh30/amberjs)** — a JavaScript and TypeScript runtime in Rust and V8. One `amber` binary runs scripts, Jest-style tests, MCP tools, and in-process `amber:ai`, with an opt-in capability sandbox and oxc type-stripping. Node Conformance 5.0 scores 55/55 fixtures; coverage is per-API, and the runtime is not a Node.js clone. MIT. → [amberjs.com](https://amberjs.com)

## Product Lab

The homepage features four. The full index of 14 is at [zhanghe.dev/products](https://zhanghe.dev/products).

| Product                                                                 | Job to be done                                      | Built around                                |
| ----------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------- |
| [Amberjs](https://zhanghe.dev/products/amberjs)                         | Explore a JavaScript runtime from the V8 boundary   | Rust + V8, one binary, opt-in sandbox       |
| [Native Translate](https://zhanghe.dev/products/native-translate)       | Translate the web without breaking reading context  | Chrome Translator and Language Detector, on-device |
| [Git Commit Analyzer](https://zhanghe.dev/products/git-commit-analyzer) | Turn a staged diff into a Conventional Commit       | Local llama.cpp and GGUF models             |
| [Video Clipper](https://zhanghe.dev/products/video-clipper)             | Turn long videos into short clips without uploading | FFmpeg.wasm, in the browser                 |

### Also in the lab

- **Browser AI** — [MangoFlow](https://zhanghe.dev/products/mangoflow) keeps a multi-model chat beside the page. [Translate](https://zhanghe.dev/products/translate) runs on-device, with Hy-MT models delivered through Cloudflare.
- **AI infrastructure** — [Xiaomaolv](https://zhanghe.dev/products/xiaomaolv) is a self-hosted Rust Telegram agent: MiniMax or an OpenAI-compatible provider, MCP tools, and SQLite memory. [Binance Square Post MCP](https://zhanghe.dev/products/binance-square-post) is a hosted remote MCP so Grok, ChatGPT, and Gemini can publish without self-hosting.
- **Creator and media** — [Cover Moment](https://zhanghe.dev/products/cover-moment) for local social covers, [Suno Lyric Downloader](https://zhanghe.dev/products/suno-lyric-downloader) for LRC and SRT, [HEIC to JPG](https://zhanghe.dev/products/heic-to-jpg) and [WebP Converter](https://zhanghe.dev/products/webp-converter) for in-browser photo conversion, and [Unbg](https://zhanghe.dev/products/background-remover) for on-device cutout or a cloud fal BiRefNet API that does not store files by default.
- **Creative** — [Alchemy](https://alchemy.host), a creation system for getting from an idea to an output.

## Operating Principles

- **Workflow first** — start from a step people already repeat: context switching, uploading, or manual cleanup.
- **AI with a reason** — translation, commit writing, page-side help, and routing. The model has to remove work.
- **Privacy and speed** — local processing and a clear data boundary whenever the product allows it.
- **Small tools, clear constraints** — one friction point, a public page, and a loop for the next iteration.

## GitHub Signal

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zh30&theme=github_dark" alt="Henry Zhang GitHub profile summary" />
</p>

```txt
hello@zhanghe.dev:~$ connect --work
[OK] portfolio loaded | product lab online | notes shipping
```

<p align="center">
  <a href="mailto:hello@zhanghe.dev">Email</a>
  ·
  <a href="https://zhanghe.dev">Website</a>
  ·
  <a href="https://zhanghe.dev/products">Products</a>
  ·
  <a href="https://zhanghe.dev/posts">Blog</a>
  ·
  <a href="https://x.com/zhanghe">X</a>
  ·
  <a href="https://www.linkedin.com/in/zhanghe/">LinkedIn</a>
</p>
