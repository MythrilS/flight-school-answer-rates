# Flight School Answer-Rate Audit

**49 flight schools across 6 states. 61% couldn't get a prospective student to a human during business hours.**

A lead ready to book a discovery flight — and spend $12,000–18,000 on a pilot program — reaches an actual human less than 40% of the time. Three schools' listed phone numbers were simply disconnected.

---

## The finding

| Outcome | Schools | Share |
|---|---:|---:|
| Human answered | 19 | 39% |
| Voicemail | 21 | 43% |
| Phone tree / auto-attendant, no human | 6 | 12% |
| Disconnected number | 3 | 6% |
| **Total** | **49** | **100%** |

**30 of 49 schools (61%)** could not connect a would-be student to a person during business hours.

### By state

| State | Answered | Voicemail | Phone tree | Disconnected | Total |
|---|---:|---:|---:|---:|---:|
| FL | 5 | 1 | 2 | 1 | 9 |
| NY | 1 | 5 | 1 | 1 | 8 |
| TX | 4 | 4 | 0 | 0 | 8 |
| CO | 2 | 4 | 1 | 1 | 8 |
| AZ | 3 | 4 | 1 | 0 | 8 |
| CA | 4 | 3 | 1 | 0 | 8 |
| **Total** | **19** | **21** | **6** | **3** | **49** |

The three disconnected numbers: **Yoanna Flight School** (Fort Myers, FL), **Dunkirk Aviation Sales & Services** (Dunkirk, NY), **Springs Aviation** (Peyton, CO).

## Methodology

- **Sample:** 49 flight schools across 6 states (FL, NY, TX, CO, AZ, CA).
- **Method:** one phone call per school, placed during local business hours, as a prospective student asking to book a discovery flight.
- **Outcome coding:**
  - `answered` — a human picked up.
  - `voicemail` — rang through to voicemail / no answer.
  - `auto-attendant` — phone tree or IVR with no path to a human.
  - `disconnected` — number out of service.
- **Dates:** calls placed 2026-09-29 and 2026-09-30.

## Caveats

- This is a **single-call snapshot**, not a longitudinal study. One missed call doesn't mean a school is unresponsive.
- The sample is **small and non-random** — six states, roughly eight schools each. It's directional, not a national census.
- "Disconnected" reflects the public directory listing at the time of the call. Numbers change, and a school may have moved to a new line.
- This measures the **phone answerability of public listings**, not school quality.

## Data

- [`data/flight-school-answer-rates.csv`](data/flight-school-answer-rates.csv) — the full call log (state, school, city, airport, outcome).

## Reproduce it

Pick a niche. Call *N* businesses during business hours as a prospective customer. Log answered / voicemail / phone-tree / disconnected. The finding writes itself.

---

*Collected and published by [Oystx](https://oystx.com). Questions: michael@oystx.com.*
