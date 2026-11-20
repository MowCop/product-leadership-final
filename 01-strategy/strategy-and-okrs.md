# Course Hub - Module 1 - Lab 1 - Pressure Test

AI pressure-test (Lab B, step 2). Round 1 run in Claude on 17 Nov 2026 14:40; round 2 on 20 Nov 2026 03:16 against the updated strategy. Claude played a skeptical Chief Strategy Officer.

## Round 1 — skeptical CSO (17 Nov)

**1. Biggest assumption that could be wrong.** That people who feel fine will practise to stay fine. Fable's own churn data says users stop when they feel better; personalisation makes content a better match but doesn't create a need. If users treat Fable like a painkiller, KR2 fails whatever the AI recommends. Also: "data only Fable has" is weaker than claimed — Headspace and Calm have more users and longer post-recovery histories.

**2. The board question Karl can't yet answer.** If half of departing premium users pause instead of cancelling, and paused users pay little or nothing, what happens to revenue? How many paused users return to full premium, and how many would-be payers pause instead?

**3. Outputs disguised as outcomes.** KR3's pause target measures adoption of a shipped feature; KR3's "new high-stress period" trigger can't be observed for lapsed users; KR2 sessions are activity, not benefit; no KR measures the Winning Aspiration; "high-engagement cohort" undefined.

**4. Reconsider the hard no (community).** Community could fill the calm-period gap by giving recovered users a role, and is harder for AI-first competitors to copy; moderation risk manageable with light formats.

**5. Strategy or wish list?** A real strategy with a wish list attached: genuine core choices, but too many builds for a team of 14, and no KR measures the aspiration.

## Round 2 — skeptical CSO on the updated strategy (20 Nov)

**1. Biggest assumption.** That people who feel fine will *opt in to and answer* check-ins. Almost everything now runs through them: Rock 1, KR2's wellbeing score, KR3's "helped by check-ins", the AI-adapted streak. Daily prompts to calm users risk notification fatigue; low opt-in would break the mechanism and the measurement at once. Stress recurrence is still untested.

**2. Board question.** How many of the 4.2M are in the high-engagement cohort, and what is one percentage point of 120-day retention worth in revenue? Without sizing, the board can't weigh +15 points of retention against the cost of an AI model, guardrails, consent and new pricing with 14 people.

**3. Outputs disguised as outcomes.** KR3's pause target is still an output (unchanged from round 1). KR2's wellbeing score counts only responders — users who drift stop answering, so report response rate alongside. KR3's "helped by check-ins" is attribution that can't be measured without comparing opted-in vs not.

**4. Reconsider: "chasing new users in a hard stretch".** Every high-engagement user starts as a new user in a hard stretch — the source of the cohort. Starve that intake and retention % can rise while the number of users kept falls.

**5. Strategy or wish list?** Now a strategy — clear choices, measurable outcomes — but the 12-month plan asks 14 people to ship an AI model and co-pilot, guardrails, consent design, pause and pay-as-you-go pricing, a podcast format and a research programme, and it all hangs on users opting in to something they no longer feel they need.

**Claude's view:** the most serious hit is #1 (check-in opt-in). Cheap protection: weekly rather than daily check-ins, and opt-in rate as an early signal in Management Systems. Not yet decided by Karl whether to update the Module 1 step 03 answers from round 2.

## Karl's step 03 answers (saved in the guide, 17 Nov 15:14; Change sentence updated 19 Nov)

**Most valid challenge:** None of my KRs measures what my Winning Aspiration promises, and KR3 can't be measured as written. There is no data I can use to see when a lapsed user's new high-stress period starts. I would be judging the strategy on activity (sessions, pause uptake) rather than on whether users actually stay well and recover faster.

**Change:** Add opt-in check-ins to get insights into when high-stress periods start — e.g. a short monthly "how's this week been?" by text or email that users agree to before they lapse — keeping the user in control. Define the high-engagement cohort as users with 3+ sessions a week in their first 60 days. Add a KR on self-reported wellbeing from those check-ins (now in KR2). KR3 now measures returns within 6 months, which Fable can track today, with opt-in check-ins as the way to raise it.

**Defend:** Personalisation as the "how to win". The community social layer as the hard no for this initiative: splitting a team of 14 across two bets (AI + social layer) would mean neither gets a fair test, and personalisation built on each user's own history keeps Fable's private and trusted role.

## Final OKRs (as in the repo, 19 Nov — supersede all earlier versions)

**Objective:** Make Fable the app high-engagement users keep after their first hard stretch, and come straight back to when stress returns.

- **KR1:** Raise 120-day retention for the high-engagement cohort (users with 3+ sessions a week in their first 60 days) from ~30% to 45% (estimated baseline: most highly engaged users leave at 90–120 days, so fewer than a third stay). Retention here means still using Fable (at least one session in the 14 days up to day 120), not just 'still subscribed', so free and premium users both count.
- **KR2:** The share of high-engagement users doing at least one session in every week from day 90 to day 180 rises from ~15% to 30%, and their average self-reported wellbeing score from opt-in check-ins is 10% higher at day 180 than at day 90 (among users who respond at both points). Users keep practising and feel better for it.
- **KR3:** Of high-engagement users who lapse, 35% return within 6 months (up from ~15% today), helped by opt-in check-ins that let users flag a tough period. Half of departing premium users choose to pause rather than cancel; today the pause rate is 0% because Fable has no pause option.

## How the KRs fit together (Q&A, 17–18 Nov)

- **HEU (high-engagement users)** = 3+ sessions a week in the first 60 days. An assumption, tunable with real data. Defined by usage, so free and premium both count (report KR1 split by tier; premium renewal sits in Management Systems).
- **KR1 is a checkpoint; KR2 is a habit.** KR1: active in the 14 days up to day 120 (end of the 90–120 day drop-off window). KR2: active in *every one* of the 13 weeks from day 90 to day 180 — a stricter test, so its number is lower.
- **Worked example (1,000 HEU, today):** ~300 active around day 120 (KR1 30%); ~150 of those active every week from day 90 to 180 (KR2 15%); the other ~150 drop in and out — the best target.
- **KR2 can never exceed KR1.** Target 30% ≤ 45% ≈ two-thirds of retained users practising weekly (was ~half). 40% was cut to 30% as unbelievable.
- **14-day window for KR1** removes the luck of a single-week snapshot.
- **Wellbeing caveat:** measured among users who respond at both day 90 and day 180; "10% higher" is relative to each user's day-90 score.
- **KR3 baseline:** a check-in-triggered return rate can't have a baseline before check-ins exist, so KR3 measures returns within 6 months (trackable today), with check-ins as the lever.

## Repo commits (01-strategy/strategy-and-okrs.md)
- 17 Nov 15:19 `bb46110` — first full Module 1 deliverable
- 17 Nov 15:22 `976e23e` — README one-sentence strategy
- 17 Nov 16:54 `1b6028d` — KR1 retention definition, KR2 wellbeing window, Where to Play exclusions
- 18 Nov 12:05 `419640c` — Karl: KR2 "in every week" wording
- 18 Nov 12:34 `1cae970` — KR1 14-day window; KR2 30% target and clearer wellbeing measure
- 18 Nov 13:04 `9379cb5` / 13:15 `4082429` — Karl: KR3 6-month version; Change sentence updated
- 19 Nov 11:21 `5782564` — sync with Karl's guide edits ("I leave out" list, Capabilities, Management Systems)
- 19 Nov 11:23 `ce25b76` — Management Systems targets current cohort plus lapsed users (win-back)

Commits by Claude are made through GitHub in Karl's Chrome (Claude's GitHub app isn't installed on the repo). Guide and repo are in sync as of 19 Nov 11:23.

**Deliverable 1 done.**

## Not yet addressed (for later modules)
- Check-in opt-in risk (round 2 #1) → weekly cadence, opt-in rate as an early signal
- Cohort sizing and revenue per retention point (round 2 #2) → Module 5 business case
- Revenue impact of pausing; pause uptake still an output inside KR3 → Module 5 / Management Systems
- Response-rate reporting for the wellbeing score
- Intake of new users as the source of the cohort (round 2 #4)
- Uniqueness of Fable's data vs Headspace/Calm
