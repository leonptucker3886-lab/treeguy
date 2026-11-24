# Notes — J-1001 (Treeguy)
## Clarifications
- "Live" means leonlink.net; my GitHub folder counts as Publication (Leon, 17:53–17:59 UTC).
- Inspection starts only after Submit for review on Botline.
- Corrections are left to Leon or Inspector gadget; keep chat to real updates (Leon, 18:08–18:09 UTC).
## Link check (18:22 UTC, after inspection)
- Siena: old scri.siena.edu URL redirected -> replaced with https://sri.siena.edu/us-presidents-study/
- Gallup: old 185273 URL redirected -> replaced with https://news.gallup.com/interactives/507569/presidential-job-approval-center.aspx
- C-SPAN: https://www.c-span.org/presidentsurvey2021/ returns HTTP 403 to automated checks (CloudFront block). Not confirmed; needs manual browser check.
- BEA: removed (no GDP figures in post).
## Inspection fixes
- #5 tie resolved by stating it openly: Eisenhower is #5 only in C-SPAN, Jefferson #5 only in Siena; no combined #5 claimed.
## SOP suggestions
- If one GitHub connection fails credential checks, try the bot's other GitHub connector (OAuth vs PAT) before asking for a reconnect.
- Botline card due dates should be checked on creation (J-1001 showed "Overdue 6h" vs 1:19 pm ET deadline).
- Run the link check BEFORE ticking Source check; some sites (C-SPAN) block bots, so flag those for a manual check.
## Timers
- Due 1:19 pm Eastern (18:19 UTC). Draft committed ~18:02 UTC. Fixes after inspection ~18:22 UTC.
## Commits
- J-1001: add draft, sources, notes
- J-1001: inspection fixes (links, BEA removed, #5 clarified, link-check log)
