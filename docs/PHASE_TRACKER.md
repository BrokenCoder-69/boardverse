# 🎲 BoardVerse — Phase Tracker

> Rule: only ONE phase at a time. A phase is done only when it is
> tested AND approved ("Phase X approved. Start Phase Y.").

Status values: NOT STARTED · IN PROGRESS · BLOCKED · TESTING · READY FOR REVIEW · APPROVED

---

## Phase 0 — Environment & Project Setup
- **Status:** READY FOR REVIEW
- **Objective:** Install tools, create the project structure, run Django for the first time.
- **Features:** Python venv, packages installed, Django project `config`, Git repo, docs.
- **Files created:** `backend/requirements.txt`, `backend/manage.py`, `backend/config/*`, `.gitignore`, `docs/PHASE_TRACKER.md`
- **Automated tests:** none yet (the test setup comes in Phase 1)
- **Manual tests:**
  - [x] `python -m django --version` → 5.2.18
  - [ ] `python manage.py migrate` runs without errors
  - [ ] Rocket page shows at http://127.0.0.1:8000/
  - [ ] First Git commit created
- **Known issues:** Python 3.14 is very new; watch for package compatibility.
- **Acceptance criteria:** Server starts, rocket page loads, first commit exists.
- **Docs:** this file
- **Git commit:** `chore: initial Django project setup`

---

## Phase 1 — Core Backend (settings, security, accounts, social login, guest mode)
- **Status:** NOT STARTED

## Phase 2 — Core Frontend (design system, layout, shared components, auth pages)
- **Status:** NOT STARTED

## Phase 3 — Game Framework (registry, engine interface, lobby, bots, rooms, guide system)
- **Status:** NOT STARTED

## Phase 4 — Game #1: Tic-Tac-Toe
- **Status:** NOT STARTED

## Phase 5+ — One new game per phase (Connect Four → Snakes & Ladders → Ludo …)
- **Status:** NOT STARTED