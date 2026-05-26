# FGCU R.I.S.E. Weekly Hours Log

A lightweight, standalone web form for [R.I.S.E. (Real Independence, Successful Employment)](https://www.fgcu.edu/rise) interns to log their weekly work hours and send them directly to their job coach.

**Live form:** https://fgcurise.github.io/fgcurise_worklog

---

## How it works

Students open the link on any device (phone, tablet, or computer) — no account, no login, no app required. They:

1. Select their name from the dropdown
2. Tap the days they worked that week
3. Pick the date, clock-in time, and clock-out time for each day
4. Add any optional comments for their job coach
5. Tap **Send to Job Coach** — this opens their email app with everything pre-filled, ready to send to rise@fgcu.edu

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The complete self-contained form (logo, styles, and logic all embedded) |
| `README.md` | This file |

---

## Updating the student list

Open `index.html` in any text editor and find the `<select id="studentName">` block. Add or remove `<option>` lines as the cohort changes. Commit the updated file to this repository and the live link updates automatically.

## Updating the job coach email

Search for `rise@fgcu.edu` in `index.html` and replace it with the new address.

---

## Built for

**FGCU R.I.S.E. Program** — Comprehensive Transition Program (CTP) for adults with intellectual and developmental differences.  
Florida Gulf Coast University, Fort Myers, FL.
