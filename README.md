# Jan Stavěl — Platform / Automation Engineer, Clojure, spec-first engineering

> Stories bring the power to know; success fuels the power to grow.
> Trust builds joy, and shared joy is twice the joy.
>
> Python and Perl by hand, Clojure by heart, TypeScript with agents, Terraform with respect.
> I build systems whose output can be verified, not merely demonstrated.
> I cherish the fleeting moments that remind me I am still growing.

24 years on Linux. Ten years of enterprise test automation (Red Hat). Currently
building in public: every project below has its specification, ADRs, and tests
in the repo — the way of working is as much the deliverable as the code.

I work **spec-first**: the specification is the contract between me, the AI
agents that do the building, and the reviewer — frozen after approval,
renegotiated explicitly, never drifted. Each repo shows the same pattern:
spec → ADR → plan → implementation → independent verification.

Infrastructure gets the same discipline: Terraform with respect — plan
before apply, pinned artifacts, and an awareness that every change has a
blast radius beyond my own console.

---

## 🚀 Flagship projects

### [janbot](https://github.com/jstavel/janbot) — Autonomous AI career assistant
A spec-driven RAG pipeline (DSPy, Python/FastAPI) deployed to **GCP Cloud Run**
with Terraform, a guardrail layer (answer cache, rate limits, hard quota,
deterministic over-claiming guard), and contract-based evaluation against a
pinned baseline. Live demo: [jstavel.github.io/janbot](https://jstavel.github.io/janbot/)
— the spec, ADRs and evaluation records are in the repo.

*What it demonstrates:* end-to-end ownership — evaluation design, infrastructure
as code, and the discipline to ship a baseline over an unverified optimization.

### [reactive_testing](https://github.com/jstavel/reactive_testing) — Spec-first testware
Event-driven testing: validate what a system *actually did* from its own runtime
data, beyond pass/fail. TypeScript + Playwright.

*What it demonstrates:* testing architecture as a design problem, not a checklist.

### [krakatoa](https://github.com/jstavel/krakatoa) — Polyglot matching engine
High-performance matching engine in **Clojure/Rust** on Polylith architecture,
ZeroMQ transport, Kafka event sourcing, chaos testing.

*What it demonstrates:* Clojure as a first-class systems language, next to Rust.

### [gtd-org](https://github.com/jstavel/gtd-org) — GTD in org-mode
Personal productivity system ("mind like water") implemented in org-mode and
Clojure — built and refined over years. Today it is in maintenance rather than
daily use; its living part is the Plaud-downloader component (ClojureScript)
that pulls my own voice recordings into a searchable knowledge base.

*What it demonstrates:* the tooling philosophy — build tools, not tickets.

### [audio_transcriber](https://github.com/jstavel/audio_transcriber) — AI transcription pipeline
Python + Playwright pipeline that turns audio recordings into a searchable,
structured knowledge base — my own second brain, running on real data.

*What it demonstrates:* AI engineering applied to a real personal workload,
not a demo dataset.

---

## 🧭 How I work

- **Spec-first:** the specification is the interface between me, the AI agents
  that build, and reviewers — frozen after approval, renegotiated explicitly,
  never drifted.
- **Artifacts in git:** decisions (ADRs), plans, and verification records are
  versioned and addressable; "trust me" is not an artifact.
- **Human-owned review:** the builder can be an agent; the problem definition,
  the review, and the evidence that it works are always mine.
- **Failure is data:** each repo's history includes what was rejected and why.
- **Published claims are measured:** the demo answers from a pinned corpus, and
  its evaluation gate is pre-registered against a fixed reference.

> "I believe the core requirement for a team to grow is that each brain in the
> team is learning. I thrive on mindful tasks and constant challenges; once a
> task becomes routine, I look for the next peak to climb."

---

## 🛠️ Core skills

Clojure · ClojureScript · Python · Rust (basic) · TypeScript · Terraform ·
GCP (Cloud Run, Artifact Registry, Secret Manager, Firestore) · Ansible ·
Podman/containers · CI/CD · Playwright · Robot Framework · DSPy · FastAPI · Linux

---

## 🐐 Beyond code

I keep goats and maintain a smallholding — a different kind of mindful task,
where the feedback loop is measured in seasons, not sprints.

---

## 📫 Contact

[LinkedIn — linkedin.com/in/janstavel](https://www.linkedin.com/in/janstavel/) ·
[CV — PDF](https://jstavel.github.io/cv-en.pdf)
