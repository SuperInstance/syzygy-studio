# syzygy-studio

The public face of the Syzygy program: a hand-written static site — no
build step, one small stylesheet, no scripts — that makes the whole
program digestible for three kinds of reader: the curious, builders,
and agents.

**Live:** https://superinstance.github.io/syzygy-studio/

| page | what it is |
|---|---|
| `index.html` | The front door — what Syzygy is, the Sitka docks video (opt-in, poster-first), the captain line |
| `watch.html` | Simulation — the playable ASCII demo, its invariants, and its honest latency |
| `learn.html` | Learn at three levels — Curious / Builders / Agents (the agent track carries the reading procedures + measured baseline) |
| `uses.html` | Applications — one camera, one job: harbor walker, forklift, grabber, overseer |
| `results.html` | Receipts — the reading experiment's numbers, the kernel's golden hash, and what is not true yet |
| `docs/` | The citations in raw form (experiment RESULTS, the frozen reading guide) |
| `media/` | The docks side-by-side render (`docks.mp4`, web encode of the syzygy-video master), its poster, and the demo screenshot |

Page weight is deliberate: HTML pages are a few KB each; the 19 MB
video is `preload="none"` behind a poster, for metered connections.

Part of the Syzygy program — kernel:
[SuperInstance/Syzygy](https://github.com/SuperInstance/Syzygy) ·
video: [syzygy-video](https://github.com/SuperInstance/syzygy-video) ·
demo: [syzygy-demo](https://github.com/SuperInstance/syzygy-demo).

Syzygy measures; it does not judge.
