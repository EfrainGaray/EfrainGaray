# Hi, I'm Efrain Garay
## Independent Researcher · Software Engineer · Founder of Hegga

![GitHub-Mark-Light](./white_logo.svg#gh-light-mode-only)![GitHub-Mark-Dark](./dark_logo.svg#gh-dark-mode-only)

---

## Research Projects

### [Agatha](https://github.com/EfrainGaray/agatha) — Binary Transport via YouTube VP9 4K

A system that encodes arbitrary binary files into 4K grayscale video frames (1 bit/pixel), uploads them to YouTube, and recovers the original data with 100% fidelity using BCH(t=16) error correction. YouTube's H.264/VP9 transcoding degrades the signal, but ECC corrects all introduced errors.

- Validated at **300 MB** with SHA256-verified recovery at 30 fps and 60 fps
- Two deployment channels: **VP9 4K Morton Full** (throughput) and **Color Carrier** modes (stealth)
- Maximum-stealth operating point (C16): BER=0 embedded in real video, visually indistinguishable
- Academic paper available at [agatha.efra.dev](https://agatha.efra.dev)

**Stack:** Python · FFmpeg · BCH ECC · YouTube Data API v3 · Astro 5 SSR

---

### [NEXCOMP](https://github.com/EfrainGaray/nexcomp) — Adaptive Lossless Compressor

Per-block codec selection compressor that outperforms bzip2 across standard benchmarks.

| Corpus | NEXCOMP | bzip2 | gzip |
|--------|---------|-------|------|
| Calgary | 2.072 bpb | 2.109 bpb | 2.592 bpb |
| Canterbury | 1.278 bpb | 1.545 bpb | 2.072 bpb |
| Silesia | 2.022 bpb | 2.057 bpb | — |

Decompression throughput ~50 MB/s (vs bzip2 ~17 MB/s).

**Stack:** Rust

---

## Tech Stack

We work with:

- [Angular.io](https://angular.io) — HTML enhanced for web apps
- [NestJS](https://nestjs.com) — Progressive Node.js framework
- [Flutter](https://flutter.dev/) — Cross-platform mobile & desktop
- [Svelte](https://svelte.dev/) — Radical new approach to UI
- [Spring Boot](https://spring.io/) — Java application framework

---

## Stats

<div>
  <a href="https://github.com/EfrainGaray">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=EfrainGaray&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=EfrainGaray&layout=compact&langs_count=7&theme=dracula&include_all_commits=true&count_private=true"/>
  </a>
</div>
