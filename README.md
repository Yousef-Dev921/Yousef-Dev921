# Yousef

**iOS Security Researcher**

[@yousef_dev921](https://x.com/yousef_dev921)

## About

I do security research on Apple platforms — iOS and macOS internals,
code‑signing (CoreTrust / AMFI), image and file‑format parsers, and
jailbreak tooling (rootless tweaks for Dopamine).
I report what I find to Apple Product Security and publish the
write‑ups once disclosure is complete.

Outside research, I build production software for Saudi companies and institutions.

**Currently:** auditing Apple's open‑source components toward an Apple Security Bounty submission.

## Findings

**libAppleEXR — unbounded `dataWindow` extents** · macOS 26.5, still reproduces on 27.0.1\
A 384‑byte EXR drives ~1.85 GiB resident commit; Quick Look hangs.\
Reported to Apple Product Security — closed as non‑security (DoS class).\
→ [AppleEXR-DataWindow-PoC](https://github.com/Yousef-Dev921/AppleEXR-DataWindow-PoC)

**ImageIO — unchecked ICNS chunk length** · macOS 26.5 (no longer reproduces on 27.0.1)\
A 796‑byte ICNS commits ~2.37 GiB to render a thumbnail (Quick Look, Preview).\
Reported to Apple Product Security — closed as non‑security (DoS class).\
→ [ImageIO-ICNS-ChunkLength-PoC](https://github.com/Yousef-Dev921/ImageIO-ICNS-ChunkLength-PoC)

## Research & tools

- [**Coretrust-IOS-History**](https://github.com/Yousef-Dev921/Coretrust-IOS-History) — how TrollStore bypassed AMFI and CoreTrust for permanent sideloading (EN / AR report)
- [**MuteLock**](https://github.com/Yousef-Dev921/MuteLock) — rootless tweak that blocks camera and microphone access on jailbroken iOS 15–16.5
- [**Cydia / Sileo repo**](https://github.com/Yousef-Dev921/repo) — package repository for my tweaks

## Things I build

Independent developer of ERP systems and private web platforms running
in production — plus native apps and a PDF editor with full Arabic support.

**Languages** — PHP · TypeScript · Swift · Objective‑C · C · C# · Python · Go · Shell

**Web** — Laravel · Inertia · React · Filament · Tailwind CSS · PostgreSQL · Vite\
**Apple** — Swift / SwiftUI · Objective‑C · Theos (rootless tweaks) · Firebase\
**Desktop** — C# / .NET (Windows)\
**Research tooling** — C · LLDB · Python · Shell

### Open source contributions

- **PdfCraft** (16k★) — Arabic RTL text editing — open PRs
  [#3465](https://github.com/storytold/pdfcraft/pull/3465) ·
  [#2186](https://github.com/storytold/pdfcraft/pull/2186) ·
  [#2222](https://github.com/storytold/pdfcraft/pull/2222)
