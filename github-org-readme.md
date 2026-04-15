<div align="center">

![Aevyra](https://raw.githubusercontent.com/aevyraai/.github/main/profile/aevyra-logo-final.svg)

</div>

---

Aevyra is an open-source org building infrastructure for large language models. Not wrappers around existing APIs — tooling that works at the layers below that: benchmarking, adaptation, and the runtime systems that make models actually useful in production.

The projects are connected by a shared thesis: the interesting work in AI right now is infrastructure, not prompting.

## What we're building

**[Verdict](https://github.com/aevyraai/verdict)** — LLM benchmarking. Run your prompts across any combination of models, score the responses with pluggable metrics, and get a side-by-side comparison. The foundation for model selection, prompt engineering, and knowing whether your fine-tuning is actually working. `pip install aevyra-verdict`

**Reflex** — Agentic runtime. Models are only as useful as the systems they operate within. Reflex is a runtime for building agents that reason, act, and recover from failure — built around the idea that reliable agentic behavior requires more than a loop and a tool list. *In development.*

**Fine-tuning infrastructure** — Closing the loop between evaluation and training. Good fine-tuning requires good data curation, careful eval design, and knowing when to stop — none of which scales with manual iteration. A pipeline that automates the cycle: evaluate, curate, train, repeat. *Coming soon.*

## Where this is heading

Once you can evaluate, fine-tune, and run agents reliably, the next question is what you build with all of that. One direction we're thinking about: personal intelligence systems — persistent-context architectures that know what you're working on, how you think, and what you've already decided. Not a chatbot with memory bolted on, but something built from first principles. More on this as it takes shape.

## Status

Verdict v0.1.0 is released on [PyPI](https://pypi.org/project/aevyra-verdict/). Everything else is in active development. Watch the org or reach out if you want to follow along.

## Get involved

- 📬 [ankithgunapal@gmail.com](mailto:ankithgunapal@gmail.com)

---

<div align="center">
<sub><i>intelligence from beyond</i></sub>
</div>
