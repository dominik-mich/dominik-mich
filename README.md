# Dominik Mich

I build verification systems that make complex hardware/software **provable**, **repeatable**, and **shippable**.

SWE with a strong testing background in **networking** (switching, APIs, drivers), now running **design verification** for an **audio engine**. I like clean automation, trustworthy signals, and CI pipelines that tell the truth.

---

## What I’m into (lately)

- **Design Verification**: environments that catch real bugs early
- **Networking**: switching, driver/API validation, system-level debugging
- **Automation & DX**: reducing “manual verification” to a button (or a PR)
- **CI that matters**: fast feedback, reproducible runs, actionable logs
- **Pragmatic AI in engineering workflows**: using AI to remove friction (without losing rigor)

---

## Current motto

> Make it understandable.  
> Make it deterministic.  
> Then make it fast.

---

## How I work

- Start with **observability**: logs, traces, counters, assertions—then optimize.
- Prefer **small, reviewable changes** over heroic refactors.
- Treat tests as **evidence**, not decoration.
- Automate anything that happens twice.
- If a failure can’t be diagnosed quickly, it’s not “done” yet.

---

## Stack (what I actually use)

**Verification / DV**
- **SystemVerilog**, **UVM**
- coverage, scoreboards, assertions, debug-first testbenches

**Scripting / Frameworks**
- **Python** (test orchestration, automation, tooling, data wrangling)

**Systems**
- **Linux** (daily driver)
- APIs, drivers, integration debugging across the HW/SW boundary

**Core languages (from networking & systems work)**
- **C**, **C++**, **Python**

**CI / Productivity**
- **GitHub Actions** (matrices, artifacts, reusable workflows)
- **GitHub Copilot** (scaffolding, refactors, test generation)

---

## Early adopter: AI tools (learning to use them *well*)

I’m an early adopter of AI tools like **GitHub Copilot**, **Claude**, and **GPT**—and I’m actively figuring out how to apply them more effectively in **design verification**, **triage**, **debugging**, and **code changes**.

What I want to get better at:

- **Triage acceleration**
  - summarizing failing CI runs and extracting the *first actionable clue*
  - clustering failures by signature (log patterns, assertion IDs, seeds, regressions)

- **Debugging support**
  - turning long logs/waveform notes into hypotheses to test
  - generating “next-step” debug checklists (what signals, what knobs, what seeds)

- **DV productivity**
  - drafting UVM components (monitors, sequences, scoreboards) from a clear spec
  - writing assertions/properties and coverage plans with fewer omissions

- **Safer code changes**
  - proposing minimal diffs + tests, not big rewrites
  - explaining tradeoffs and failure modes before code lands

My rule: **AI should improve throughput and clarity, but the verification story must remain deterministic and auditable.**

---

## Projects

This profile is a mix of:
- verification utilities,
- automation helpers,
- experiments that may turn into tools,
- and notes-with-batteries-included.

If something here helps you, feel free to use it, fork it, or open an issue/PR.

---

## Contact

- GitHub: **@dominik-mich**

Best way to collaborate: open an issue with **context + goal + constraints**.

---

<sub>Last updated: 2026-04-23</sub>
