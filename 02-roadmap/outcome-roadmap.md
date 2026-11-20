# Outcome Roadmap & Trade-off Memo: Fable Growth

> Module 2 · Turn Your Strategy into an Outcome Roadmap

## 1. Trade-off memo

> **Rock 1:** Add AI-generated daily check-in prompts personalized to user history (supports KR2): Personalised by AI daily check-ins, use this data to built on each user's own history, give 'high-engagement users' a reason to keep practising after their crisis passes. They support KR2: weekly practice from day 90 to 180 rising from ~15% to 30%, whilst the check-ins also capture the wellbeing scores.
>
> **Rock 2:** Fix the notification system (wrong times, timezone bug) (supports KR3): The opt in check-ins required of KR3 depend on notifications arriving at the right time, and the timezone bug breaks Rock 1 and KR3. It’s low effort and high impact for the KR3 results strategy to work.
>
> **Rock 3:** Add a daily streak feature to drive habit formation (supports KR1): A gentle weekly wellness streak, personalised by the AI to what matters to each user that week, builds a steady habit without guilt over missed days. It supports KR1: 120-day retention rises from ~30% to 45%. Streaks are standard in other wellness apps like Headspace and Calm and those deployed in Fable stand out because they adapt to each user's history.
>
> **Hard no 1:** Launch a premium tier with therapist-matching: It's clinical, which our strategy rules out, and it's high effort (a therapist network, licensing and liability). We say no even though the CEO asked for it.
>
> **Hard no 2:** Build a social layer: share your progress with friends: It's our Module 1 hard no. One bet, one team of 14; we'll revisit in a later phase once personalisation has proven itself.
>
> **Hard no 3:** Introduce “Fable for Teams”, a B2B workplace wellbeing offer: It's a different customer (B2B employers), so it would pull the team away from keeping our existing users.

## 2. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | (KR2) We bet that AI daily check-ins built on each user's own history of what helped will keep users practising weekly after their first hard stretch passes, for high-engagement users from day 60 to day 180<br>(KR3) We bet that notifications arriving at the right local time will raise check-in opt-in and early tough-period flags, for high-engagement users in every timezone<br>(KR1) We bet that a gentle weekly streak, adapted by the AI to each user's week, will carry practice past the 90–120-day drop-off, for high-engagement users approaching day 60–90 | Product, AI/ML, Clinical, Privacy & Legal<br>Engineering, Growth<br>Growth, Design, AI/ML | Weekly practice from day 90 heads towards 30%, and all AI output passes guardrail review<br>Notifications land on time, and opt-in and flag rates rise<br>Streak users' 120-day retention beats the control group and heads towards 45% |
| Next (3 to 6 mo) | Flexible premium (pause / reactivate): it needs Now's working notifications and flags to time the pause offer<br>Personalised win-back for lapsed users: it needs the user history that the check-ins build first<br>Content library and the podcast format, tagged for AI surfacing: check-in data shows what to make<br>AI model grounded on Fable's data (first version of the co-pilot): it scales once the guardrail and consent processes have been proven on check-ins<br>Load time under 2s, plus WCAG 2.1 accessibility: these protect retention gains once Now shows which journeys matter | Growth, Finance, Engineering<br>Growth, AI/ML, Content<br>Content, Clinical, AI/ML<br>AI/ML, Clinical, Privacy & Legal, Data<br>Engineering, Design, Legal | 50% of departing premium users pause rather than cancel<br>35% of lapsed users return within 6 months<br>Completion of AI-surfaced content rises<br>Co-pilot is rated helpful, with zero guardrail breaches<br>Load time is under 2s on 4G and the WCAG audit passes |
| Later (6 to 12 mo) | Bet: a full AI co-pilot that guides users through future hard stretches faster<br>Bet: hybrid pay-as-you-go pricing for users whose engagement drops between day 60 and day 90<br>Bet: early, consented detection that stress is returning, so Fable reaches out first<br>Bet: onboarding rebuilt as a personalisation intake<br>Bet: revisit the social layer once personalisation has proven itself<br>(None of these are commitments.) | AI/ML, Product, Clinical<br>Growth, Finance<br>AI/ML, Clinical, Privacy & Legal<br>Product, Design<br>Product, Research | Users return sooner when stress recurs<br>Premium reactivation rises<br>Users who get outreach come back faster, with no privacy complaints<br>More users finish onboarding with consent set<br>Research shows demand from the retained cohort |
