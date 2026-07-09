# Final Helper

*A single static page that turns four Concordia finals into a day-by-day study plan and tracks whether you're keeping up.*

Winter 2026, four exams inside two weeks:

- COMP 352, Data Structures & Algorithms — April 17
- ENGR 202, Sustainable Development — April 20
- ELEC 275, Principles of Electrical Engineering — April 30
- COMP 335, Theoretical Computer Science — May 1

The plan runs 33 days, March 30 through May 1, two courses a day at 3.5 hours. The left card shows one day at a time, navigable by arrow keys or the dot strip, listing each subject's exact topics: ELEC 275 by chapter section (2.1–2.7 up through electric machines in 19–20), COMP 335 by its L0–L21 lectures (DFAs to Turing machines), COMP 352 by structure, ENGR 202 by its six slide decks. The right card is the master topic checklist, and because each day's study blocks reference checklist groups directly, ticking a topic in one place updates the other.

A banner up top counts down to each exam and marks you behind, on-track, or ahead based on how many past days you've actually checked off. There's also a scratch to-do list.

It's all one `index.html` — data, CSS, and JS inline — with progress kept in `localStorage`, so no build step and no backend. The course outlines and slide lists it was built from sit in the repo next to it.
