# HANDOFF — QuantumBlur

**Last updated: 2026-11-22 (America/New_York).**
**Repo:** `mhvnsnt/QuantumBlur` (PUBLIC), default branch `main`.
**Purpose of this file:** any agent that picks up work here reads this FIRST, then the linked docs. It states what we've done, where we're at, and what we're working toward — so the owner can say "go to this repo, pick up the work" and you just know. Update this file in the same PR whenever the state changes (add, don't delete).

## 1. What this repo is

QuantumBlur — a Python package for a "quantum blur" image effect, with notebooks. The repo carries no description, so what follows is only what the tree shows: `quantumblur/` (the package), `QuantumPaint.ipynb` and `QuickStart.ipynb` (the notebooks), `test_quantumblur.py`, `setup.py`, `requirements.txt`, `docs/`, `ac.png` (a sample image). Created 2026-10-06. Public.

**Plainly:** the repo does not say in its own words where the quantum blur is used or what makes it "quantum." Whoever picks this up should read `docs/`, the notebooks, and the README first and write the purpose down here before building more.

## 2. Where we're at

### DONE
- **Anti-clobber laws (2026-10-17, PR #3 merged):** the owner's anti-clobber laws landed after the DXMMII 54k-file wipe.
- **Working method statement (2026-10-27):** `WORKING-METHOD.md` landed.

### IN PROGRESS
- Nothing is actively in progress in this repo that the repo itself records. Last push was the 2026-10-27 sweep commit. No open PRs, no releases.

### BLOCKED
- Nothing recorded as blocked. The gap is a documentation gap, not a code block: the purpose is unstated (see §1).

## 3. What we're working toward

First: establish what the quantum blur is and where it is used, from the docs and notebooks, and write it into this file and the README. Then: the package installs, the tests pass, and the notebooks run end to end on a real image. The bar: a claimed effect is proven on a real image with before/after frames, not described in text.

## 4. Standing rules that apply here

- **Branch → PR → merge, always.** Never push to main directly. Add-only, zero-conflict PRs, no force pushes.
- **Checkpoint-and-save law:** CHECKPOINT.md first, update after every step; the repo is the save; resume, never restart.
- **No-temp-storage law:** nothing in /tmp or any wipeable location, ever.
- **Real-source-only:** build from the real sources, wired up fully — no hand-tooled lookalikes.
- **No shortcuts:** use the best tools available, not the quickest hack.
- **Never kill in-progress work.**

## 5. Key files and paths

| What | Where |
|---|---|
| Package | `quantumblur/` |
| Notebooks | `QuantumPaint.ipynb`, `QuickStart.ipynb` |
| Tests / install | `test_quantumblur.py`, `setup.py`, `requirements.txt` |
| Sample image | `ac.png` |
| Docs | `docs/` |
| Agent rules | `AGENTS.md` |
| Method doc | `WORKING-METHOD.md` |

## 6. Open decisions needing the owner

- **What the quantum blur is for:** the repo does not state it. Once a pickup lane reads the docs and notebooks, the purpose still needs his confirmation before it is written in as fact.
- No other decisions are recorded in this repo.

## 7. How to pick up

1. Read this HANDOFF.md first, then `README.md`, `docs/`, and the notebooks.
2. Run `test_quantumblur.py` and the QuickStart notebook before changing anything — know the real state first.
3. Check what other agents are already doing before starting anything.
4. Resume from the stated next step — never restart, never re-derive finished work.
5. Land work branch → PR → merge, add-only. Stage finished work to the repo as it lands.
6. Update this HANDOFF.md in the same PR when the state changes. Verify with your own eyes before claiming anything done.
