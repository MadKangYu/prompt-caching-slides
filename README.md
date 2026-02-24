# Prompt Caching Is Everything

> Lessons from Building Claude Code — Thariq Shafi, Anthropic (Feb 2026)

**[Live Presentation →](https://madkangyu.github.io/prompt-caching-slides/)**

---

## What Is This

A 12-slide HTML presentation distilling Anthropic's engineering insights on how prompt caching shaped every design decision in Claude Code.

Built with the **Terminal Green** preset — JetBrains Mono, GitHub dark theme, CRT scan lines.

## Key Topics

| Slide | Topic |
|-------|-------|
| 01 | Cache Rules Everything Around Me |
| 02 | How prefix matching works |
| 03 | Static-first architecture (the 4-layer stack) |
| 04 | System messages vs system prompt updates |
| 05 | Why switching models mid-session costs more |
| 06 | Plan Mode as a tool, not a config switch |
| 07 | Tool Search with `defer_loading` stubs |
| 08 | Cache-safe compaction (context forking) |
| 09 | Cost math: $30 uncached vs $3.60 cached per session |
| 10 | Manus independently confirms KV-cache as #1 metric |
| 11 | 6 key takeaways |

## Navigation

| Input | Action |
|-------|--------|
| `↑` `↓` `←` `→` | Navigate slides |
| `Space` | Next slide |
| `Home` / `End` | First / last slide |
| Scroll wheel | Navigate slides |
| Swipe (touch) | Navigate slides |
| Right-side dots | Jump to slide |

## Tech

- **Zero dependencies** — single `index.html`, all CSS/JS inline
- **Responsive** — viewport-fitted slides (`100dvh`), `clamp()` typography, height breakpoints at 700/600/500px
- **Accessible** — `prefers-reduced-motion` support, ARIA labels, keyboard navigation
- **Effects** — CRT scan lines, terminal glow, blinking cursor, staggered reveal animations

## Source

Based on [Thariq Shafi's thread](https://x.com/trq212/status/2024574133011673516) and [Implicator.ai analysis](https://www.implicator.ai/anthropic-says-cache-misses-are-production-incidents-reveals-caching-shaped-claude-code/).

## License

MIT
