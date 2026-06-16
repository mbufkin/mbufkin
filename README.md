## Michael Bufkin

I build AI systems on hardware you can actually afford.

Everything I make runs local-first — no cloud dependencies, no API keys required, no data leaving the network. I work with what I can get my hands on: a Lenovo ThinkStation, a Raspberry Pi, a MacBook Air. If it runs on my desk, it can run in a school, a small business, or anywhere that doesn't have a data center budget.

---

### What I'm working on

**[Choros](https://github.com/mbufkin/choros)** — Cohort AI teacher. Year-long classroom system: upload curriculum docs, crystallize into a structured map, generate lessons, track student misconceptions across the cohort. Runs on local hardware.

**[Trias](https://github.com/mbufkin/trias)** — LLM-powered security code review. Two-pass architecture: detection → trace verification. Currently benchmarking against OWASP test suite on a single 35B model. No rules engine, no pattern database — just architecture and principles.

**[Phren](https://github.com/mbufkin/phren)** — Personal AI tutor. Upload any document, get an interactive course with deterministic mastery scoring and AI coaching. Zero-build, vanilla JS + Python stdlib.

**[London Tutor](https://github.com/mbufkin/london-tutor)** — Chess AI tutor. The prototype that started everything. Bloom's taxonomy, deterministic scoring, transparent mastery. Built for a job interview, kept because it works.

---

### How I build

- **Local-first.** No cloud unless you choose it. Your data stays yours.
- **Tested on real hardware.** Every project lists the specs it was built and tested on. Pi, Lenovo, Mac — if it ran there, it's in the README.
- **Zero-build frontends.** HTML, vanilla JS, Python stdlib. Nothing to install. No npm, no bundler, no framework.
- **Methodology over magic.** I publish the architecture decisions, not just the code. What worked, what broke, what I'd do differently.
- **Open to discussion.** Every repo is a conversation. If you see something, say something. I'm here to learn.

---

### Hardware I test on

| Machine | Specs | Used for |
|---------|-------|----------|
| Lenovo ThinkStation PGX | GB10, 119GB, Ollama | Model hosting, Trias benchmarks, Choros processing |
| Raspberry Pi 5 | 8GB | Hermes agent, local automation |
| MacBook Air M1 | 8GB | Development, iOS builds |

---

### Get in touch

Open an issue, start a discussion, or find me here. I read everything.
