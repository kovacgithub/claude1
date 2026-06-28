# Overrule

**The autopilot that fights your medical bills before you even open them.**

---

## Phase 2 — The Idea

### One-line description
Overrule connects to your health insurance account, watches every claim the moment it posts, and an AI operator automatically detects billing errors and denials, drafts and files the appeal, and chases the refund — without you lifting a finger.

### The core insight (the unfair advantage)
Every existing "fight your medical bill" product is a **portal you have to remember to use**. You have to notice the bill, feel motivated, upload a photo, and start a process while you're sick, exhausted, or grieving. That's exactly why **~80% of medical bills contain errors but fewer than 1 in 10 people ever appeal**. The blocker was never capability — it was *initiation*.

Overrule's unfair angle: **remove the human trigger entirely.** We don't wait for you to start. We sit on the EOB (Explanation of Benefits) feed inside your insurer's member portal, intercept each claim as it lands, and act *before the paper bill even reaches your mailbox.* The product that wins this category is not a better appeal tool — it's the one that fires with zero user action.

### Why NOW
1. **Voice + document AI crossed the reliability line in 2025–26.** Agents can now reliably parse an EOB, cross-reference CPT codes against a fee schedule, draft a regulator-grade appeal letter, and *hold a 25-minute phone call with a payer's billing line* — the three tasks that made this unautomatable before.
2. **Surprise-billing and price-transparency law (No Surprises Act + hospital price transparency mandates)** now force machine-readable price files into the open — giving an agent ground truth to argue against, which didn't exist three years ago.
3. **Medical debt hit ~$220B and is being pulled off credit reports**, putting the issue in every headline and making people primed to act — but still without the time or stomach to do it themselves.
4. **"Done-for-you" beat "tool" decisively in 2026.** Users no longer want software that helps them do work; they want an operator that does the work and reports back.

---

## Phase 3 — Product Definition

### 1. Target user (specific)
**Sarah, 41, the "medical CFO" of a chronically-ill household.** She manages care for a kid with Type 1 diabetes (or a parent on dialysis, or her own autoimmune condition). She receives **8–20 EOBs/bills a year**, each a wall of codes. She *knows* some are wrong. She has appealed exactly once, won, and never had the energy to do it again. She is the financial and logistical nerve center of her family and her dominant emotion around medical mail is **dread + guilt**. She is not poor — she's time-poor and decision-fatigued.

Secondary user: the **65M Americans actively managing a chronic condition**, plus anyone post-surgery or post-ER visit in an acute window.

### 2. Core problem
- **What hurts:** Opaque bills you suspect are wrong, a denial that feels final, and an appeals process designed to make you give up. Every unfought error is **$200–$2,000 silently taken** from a family already under medical strain.
- **How often:** For the target user, near-monthly. For everyone, after every meaningful medical event.
- **Why current solutions suck:** Rocket-Money-style tools negotiate consumer subscriptions, not claims. Appeal startups (upload-a-bill portals) still require the user to *initiate every single time* — so they die at the trigger. Hospital advocates cost 15–35% and only engage on huge bills. Nobody covers the **steady drip of mid-size errors** where the effort-to-payoff ratio kills DIY action.

### 3. Core feature (the heart)
**Auto-Intercept & Auto-Appeal.** The instant a claim posts to your insurer portal, the agent: (1) pulls the EOB, (2) flags errors/denials against fee schedules + plan documents + coding rules, (3) drafts the correct dispute or appeal, and (4) **files it on your behalf and tracks it to resolution.** Your only interaction: a push notification — *"Found a $480 coding error on your 6/14 claim. Appeal filed. We'll handle it from here."*

### 4. Supporting features (max 4)
1. **One-tap approve** for anything that needs your sign-off (a digital signature or a "yes, send it"). Default path requires zero taps.
2. **Deductible & out-of-pocket live tracker** — the agent already has the data, so it shows exactly where you stand and warns before you overpay.
3. **Phone-call agent** — when a payer only accepts disputes by phone, the AI places and holds the call, then logs the reference number.
4. **"Money recovered" ledger** — a running, shareable total of dollars clawed back, with receipts.

### 5. 10x advantage
Competitors convert ~3–8% of *aware* users into appeals because the user must start each one. Overrule converts a far larger share of *total errors* because **the appeal rate is decoupled from user motivation** — it runs whether or not Sarah ever opens the app. Same AI, but the trigger is automated, so realized recoveries are an order of magnitude higher per user.

### 6. Habit loop
- **Trigger (external):** a push notification — *"We just recovered $312 from your March ER claim."*
- **Action:** open app, one tap to approve the next pending appeal (or just bask).
- **Reward (variable):** dollars recovered + relief of an avoided fight. The variability (sometimes $0, sometimes $1,400) makes the notification a slot-machine of relief. Over time the app becomes the thing that makes medical mail *stop being scary* — the deepest possible retention hook.

---

## Phase 4 — AI Agent Design

This is a **persistent operator**, not a chatbot.

### Inputs (data sources)
- **Insurer member-portal connection** (read access to claims/EOB feed) — the primary live signal.
- **Connected email** to catch paper-bill PDFs and provider statements.
- **Public ground truth:** Medicare fee schedules, hospital machine-readable price files, CPT/HCPCS coding rules, NCCI edits, and the user's own plan Summary of Benefits.
- **Outcome feedback:** which appeals win/lose, by payer, by argument type — fed back into the model.

### Decisions it makes autonomously
- Is this claim wrong? (duplicate charge, upcoding, unbundling, out-of-network misapplied, deductible miscalc, balance-billing violation, wrongful denial).
- What's the *winning* argument and the correct channel (portal form vs. fax vs. phone vs. state regulator).
- Whether to act silently (clear error), require one-tap approval (medium stakes), or escalate to a human advocate (rare, high-dollar).
- When to follow up, re-file, or escalate to the state insurance commissioner.

### Tasks it COMPLETELY replaces
Reading the EOB, knowing the rules, deciding if it's worth fighting, writing the letter, filing it, **calling the payer**, tracking the timer, and following up. The entire job.

### How it reduces thinking
Sarah's mental model collapses from *"I should probably look into that bill someday"* to *"Overrule's on it."* She makes zero decisions in the default path.

### Why it feels like a personal operator
It reports outcomes, not tasks. It speaks in done-deeds: *"Handled. $480 back."* It works while she sleeps. It's the difference between a calculator and a CFO.

---

## Phase 5 — User Experience

### First 60 seconds (onboarding)
1. "Which insurance do you have?" → secure portal connection (the one real step).
2. The agent immediately **back-scans the last 12 months of claims.**
3. Within ~60–90 seconds: *"We scanned 14 claims and found 3 likely errors worth an estimated $1,260. Want us to start fighting them?"* → **one tap.**

### First wow moment
The **back-scan reveal.** Before the user has done anything beyond connecting, they're staring at real, specific, recoverable money they didn't know they were owed. That single screen is the entire pitch, personalized.

### Daily/ongoing flow
The app is mostly silent. Then: ping → *"Coding error caught on yesterday's claim. Appeal drafted — tap to send or we'll auto-send in 24h."* Tap. Done. Weeks later: ping → *"Won. $312 credited."* The ledger ticks up.

### Why it's effortless and addictive
Effort trends to zero (default is no-tap auto-send). The reward is real money and the disappearance of dread. It's addictive the way a thermostat you never think about is indispensable — until you imagine living without it.

---

## Phase 6 — Monetization

**Model: performance-based + thin subscription floor (hybrid, but performance-led).**

- **Free to install and scan.** The back-scan and error-detection are free — this is the hook and removes all risk.
- **Overrule keeps 25% of money it actually recovers.** You only pay when you win. Psychologically unbeatable: it's *found* money, and 75% of something beats 100% of the nothing they'd have gotten alone.
- **Optional "Overrule+" at $12/mo** for power households: unlimited phone-agent calls, deductible forecasting, and priority human-advocate escalation on 5-figure bills — converts the heaviest users to predictable revenue and caps their contingency fees.

### Why users gladly pay
The alternative isn't "do it cheaper myself" — it's "do nothing and lose 100%." Contingency pricing aligns perfectly: Overrule literally cannot charge unless it makes you money.

### Expansion potential
- Add **prescription price optimization** and **provider price-shopping** (same data, same trust).
- **B2B2C:** sell as a benefit through employers/HR platforms and chronic-care clinics (huge distribution, recurring contracts).
- Move upmarket into **full medical-bill management** for the household.

---

## Phase 7 — MVP (buildable in ≤30 days)

### Include
1. **Single-insurer connection** (start with the 1–2 largest national payers' portals) OR, to dodge integration risk on day one, **email + photo-upload of EOBs** as the ingestion path.
2. **AI error-detection engine** over the EOB: flag duplicates, denials, deductible miscalcs, obvious upcoding/unbundling against Medicare rates.
3. **Auto-drafted appeal letter** generated to a proven template, payer-specific.
4. **One-tap "file it"** that, in the MVP, routes the finished appeal as a **PDF + fax/portal submission performed manually by a human ops person behind the curtain** (Wizard-of-Oz the filing).
5. **Recovery ledger + push notifications.**

### Remove for now
Live portal auto-intercept, the voice phone-agent, deductible forecasting, multi-payer support, human-advocate escalation. All later.

### Tech stack
- **Frontend:** React Native (one codebase, push notifications native).
- **Backend:** Supabase/Postgres + a worker queue.
- **Document AI:** a vision-capable LLM for EOB parsing; a reasoning LLM (Claude) for error classification and appeal drafting, grounded with retrieval over Medicare fee schedules + coding rules.
- **Filing:** human-in-the-loop ops dashboard (manual fax/portal submit) for v1.

### How to fake/shortcut complexity
- **Wizard-of-Oz the filing and the phone calls** with a small human ops team — users experience "done-for-you" while you learn which appeals actually win before automating.
- Skip portal scraping: launch with **email-forward + photo upload**, prove value, then build live intercept once you know it's worth it.

---

## Phase 8 — Go-To-Market (first 1,000 users)

### Where they already are
Disease-specific communities, not generic health forums. **r/diabetes, r/Type1Diabetes, dialysis and cancer caregiver Facebook groups, chronic-illness TikTok, and patient-advocacy nonprofits.** These people already swap "I fought my bill and won" stories — Overrule is the punchline they've been waiting for.

### How to reach them
1. **The back-scan as the ad.** Run a dead-simple landing flow: "Upload one EOB, we'll tell you for free if you're being overcharged." That single free result is the entire funnel.
2. **Creator seeding:** partner with chronic-illness and "medical-bill-fighting" creators (a hot 2026 niche) — let them run their *own* bills through Overrule on camera. The reveal screen is inherently viral content.
3. **Nonprofit + clinic partnerships** for high-trust distribution to exactly the right people.

### Launch strategy
"Show me your scariest medical bill" campaign: people submit a bill, get a free instant verdict on whether it's wrong and how much they could recover. Free verdicts drive shares; recoveries convert.

### Viral / shareable mechanic
The **"We recovered $X" receipt card** — auto-generated, screenshot-ready, status-signaling ("I beat the insurance company"). Every win is shareable proof, and every share is a personalized ad showing real dollars.

---

## Phase 9 — Brutal Validation

### Why it might fail
1. **Payer/portal access is hostile.** Insurers don't want a bot reading the EOB feed; portals lack APIs and may block scraping or change ToS.
2. **Filing automation is legally sensitive.** Submitting appeals on someone's behalf can brush against the unauthorized practice of law/insurance and requires solid authorization (HIPAA/PHI handling, power-of-attorney-style consent).
3. **Trust to connect insurance + health data** is a steep first ask.
4. **Win-rate uncertainty** on subtle errors; contingency revenue dies if recoveries are small or slow.
5. **Acute-event usage** can look one-and-done — retention risk outside the chronic-illness core.

### Biggest risks
Access/integration (#1) and regulatory framing (#2) are existential. Everything else is solvable with execution.

### The assumption that MUST be true
**A large fraction of routine medical claims contain machine-detectable, appealable errors, AND the appeal can be reliably filed at low marginal cost.** If errors are rare or filing stays expensive/manual, the unit economics collapse.

### Improvements to fix the weaknesses
1. **Sidestep portal access at launch** with email-forward + photo ingestion (consent-clean, no scraping); pursue official payer data partnerships and patient-authorized data-access rights (HIPAA right-of-access) as the durable moat — not fragile scraping.
2. **Position as a document-prep + filing-assistance service with licensed human oversight** on contested cases, keeping the AI as drafter and a compliant human/entity as filer to stay clear of UPL lines.
3. **Lead with the free, zero-data-connection back-scan** (just upload one bill) so the first value arrives *before* the trust-heavy insurance connection is requested — connection becomes an upgrade, not a gate.
4. **Anchor on the chronic-illness core** (recurring claims = recurring recoveries = real retention and predictable contingency revenue), then expand outward to acute events.
5. **Build the win-rate flywheel deliberately:** start narrow on a few error types with proven high win rates (duplicate charges, deductible miscalcs, clear coding errors), bank credibility and data, then widen.

---

### Bottom line
The category isn't "AI for medical bills." It's **removing the human trigger from getting your own money back.** Whoever automates the *initiation* — not just the appeal — wins a market where 90%+ of recoverable money is currently left on the table out of pure exhaustion. That's Overrule.
