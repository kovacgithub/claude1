# Mira

**Scan your face. See your real skin age. Get a ranked, do-this-next plan — and watch it work, week by week.**

---

## Phase 2 — The Idea

### One-line description
Mira turns a well-lit selfie into an objective read on your skin (skin age, acne, sun damage, hydration, aging trajectory), then gives you a **priority-ranked shopping list** — "buy this first, this second, skip this for now" — that **you** order yourself. You mark each item as *Ordered* or *Not ordered (and why)*, and your **weekly scans** prove what's working so the AI keeps re-ranking the list.

### The core insight (the unfair advantage)
Skincare doesn't fail because the products are bad. It fails because of **two invisible problems**:
1. **No feedback loop.** People can't tell if anything is working, so they quit at week 3 and rebuy the next hyped thing. Billions are spent thrashing between products with zero measurement.
2. **No prioritization.** "What do I actually need *first*?" is paralyzing — 10,000 products, contradictory advice, no objective truth, and limited budget.

Mira's unfair angle: **the camera becomes the measuring instrument skincare never had**, and the app becomes the **decision engine that ranks your next move** — but it never takes the buying out of your hands. You stay in control of your money; Mira just tells you the smartest order to spend it in and then *measures whether it worked.* Weekly scans + your "Ordered / Not ordered + why" feedback create the **first objective, longitudinal loop in consumer skincare.**

### Why NOW
1. **Phone cameras + on-device vision crossed the line.** A 2026 phone can normalize lighting, detect texture, pores, redness, pigmentation, and fine lines reliably enough to trend over time — *if* the lighting is good (more on that below).
2. **Skincare became identity, not vanity.** "Skin age," "glass skin," and routine-as-self-care are mainstream across genders and generations.
3. **People are tired of subscription boxes** that lock them into one brand's products. A neutral advisor that lets them buy *anywhere* is the trust play.
4. **"Done-for-you thinking" beat "done-for-you everything."** Users want the decisions made for them — not their wallet taken over.

---

## Phase 3 — Product Definition

### 1. Target user (specific)
**Maya, 27, the "overwhelmed optimizer."** She spends $80–$150/month on skincare, owns 14 half-used products, follows 5 skincare creators, and *still* isn't sure if her routine works. She likes researching and buying products herself (it's part of the fun), but she's drowning in choice and has no idea what to prioritize or whether any of it is working.

Secondary: image-conscious men 22–35 entering skincare who want to be *told exactly what to buy, in what order*, without committing to a subscription box.

### 2. Core problem
- **What hurts:** Spending real money with no idea if it's working, plus paralysis over *what to buy first* with a limited budget.
- **How often:** Daily routine, weekly anxiety spikes, monthly rebuys.
- **Why current solutions suck:** Quiz brands (Curology, Prose) lock you into *their* products via subscription and never measure results. Generic scan apps give a score and stop. Dermatologists are expensive and slow. **Nobody gives you a neutral, prioritized "buy this next" list you can act on anywhere, then proves it worked.**

### 3. Core feature (the heart)
**The Priority Plan.** One well-lit scan produces a **ranked list of what to buy — #1 highest-impact to #N nice-to-have** — each with a plain-English reason ("#1: a daily SPF 50 — your sun damage is your biggest ager; this slows it fastest"). You buy what you want, wherever you want, then tap **Ordered** (or **Skip → tell us why**). Your **weekly scan** measures the effect of what you actually bought, and the AI **re-ranks the list** for next time.

### 4. Supporting features (max 4)
1. **Ordered / Not-ordered tracking.** Every item on the plan has two buttons: **Ordered** (Mira now expects to see its effect in upcoming scans) and **Skip**, which asks a one-tap reason: *too expensive · already have something similar · don't like an ingredient · not now*. This is the feedback that makes the next plan smarter.
2. **Smart re-ranking from your choices.** Skipped #1 because it's too pricey? Mira surfaces a cheaper alternative for the same job. Said "I already have a vitamin C"? It scans that product and slots it in instead of recommending a new one.
3. **Skin Timeline.** A visual before/after that updates every scan — and links cause to effect: "since you started the SPF (ordered Mar 3), sun-damage score down 14%." This closes the loop and is the core retention hook.
4. **Product scanner.** Scan any product you own or see in a store; Mira says "fits your plan at priority #2 / skip, here's why" so you stop wasting money — and it folds owned products into the plan.

### 5. 10x advantage
Every competitor either **measures without acting** (scan apps), **acts without measuring** (quiz brands), or **traps you in their store** (subscription boxes). Mira is the only one that gives a **neutral, prioritized, buy-anywhere plan** *and* **measures whether it worked** *and* **learns from what you actually ordered and why.** That measurement-plus-choice loop compounds: the more people scan and mark Ordered/Skip, the better Mira predicts which products move which skin — a moat no quiz-brand or box can copy.

### 6. Habit loop
- **Trigger:** weekly "time to scan" nudge + the pull of checking your Skin Timeline.
- **Action:** one well-lit selfie scan, then quickly mark anything you bought as **Ordered**.
- **Reward (variable):** sometimes "skin age dropped a year," sometimes "hydration up 12%," sometimes a re-ranked plan with a new #1. Watching your own face objectively improve — tied directly to the products you chose — is as sticky as a fitness streak.

---

## Phase 4 — AI Agent Design

A **skin advisor and analyst**, not a quiz — and not a vending machine. It decides *what you should do and in what order*, then measures the result. **It never spends your money for you.**

### Inputs (data sources)
- **Normalized facial scans over time** (texture, pigmentation, redness, pores, fine lines, hydration proxies) — only counted when lighting/conditions pass quality checks.
- **Your Ordered / Skip signals + skip reasons** — the single most valuable feedback: what you'll actually buy, your budget ceiling, your ingredient preferences.
- **Self-reported context:** sleep, cycle, stress, climate/season, sun exposure.
- **Product response data:** which ordered products preceded which scan changes → which ingredients actually move *this* person's skin.
- **Population-level outcomes:** aggregated, anonymized results across many skin types feeding the ranking model.

### Decisions it makes autonomously
- What the skin's real issues and trajectory are.
- **The priority ranking** — the highest-impact next purchase given results *and* the user's revealed budget/preferences.
- How to ramp safely (e.g., introduce retinoids slowly) and AM/PM sequencing for whatever the user has ordered.
- When to substitute a cheaper or different-ingredient alternative after a Skip, when to dial back (irritation seen on scan), and when to flag a possible medical issue and route to a dermatologist.

### Tasks it COMPLETELY replaces
The *thinking*: figuring out what your skin needs, what to buy first vs. later, whether it's working, and what to change. The user keeps the *buying* — Mira removes the decision fatigue, not the agency.

### How it reduces thinking
Maya goes from "10,000 products, no idea, no budget plan" to "a ranked list of exactly what to buy next, why, and proof it's working." Zero prioritization decisions left to her.

### Why it feels like a personal operator
It speaks in outcomes and instructions, not data dumps: "Your SPF is working — sun damage down 14%. Next priority: a niacinamide serum for the redness on your cheeks. Here are three at different price points — tap Ordered when you grab one." It's a dermatologist + a savvy shopping strategist that remembers everything and never upsells you junk.

---

## Phase 5 — User Experience

### First 60 seconds (onboarding)
1. "Let's see your skin" → guided selfie. **Mira coaches you into good lighting first:** face a window or soft front light, no harsh overhead/backlight, and the app shows a live "lighting: good ✅ / too dark / too uneven" indicator and won't scan until it's good. (Consistent lighting is what makes week-to-week comparison trustworthy.)
2. ~10 seconds of analysis.
3. The reveal: **"Skin age: 31 (you're 27). Top issues: sun damage, mild dehydration. Trajectory if you do nothing — vs. if you follow your plan."** Two projected faces, side by side.
4. **The Priority Plan appears, ranked #1→#N**, each with a reason and Ordered/Skip buttons.

### First wow moment
The **skin-age reveal + a clear, ranked "do this first" plan.** Most apps leave you with a scary number and no next step. Mira hands you the number *and* the exact, prioritized move — and lets you act on it on your own terms.

### Daily/ongoing flow
- **When you buy something** (anywhere — Sephora, Amazon, a pharmacy), open Mira and tap **Ordered** on that item. If you decide to skip Mira's #1, tap **Skip** and pick a one-tap reason.
- **Weekly:** nudge → set up good lighting → 5-second scan → Timeline updates → plan re-ranks based on what you ordered and what your skin did.
- That's it. No box to manage, no lock-in.

### Why it feels effortless and addictive
One well-lit selfie a week plus a couple of taps to log purchases. The reward is **watching your own face objectively improve, attributed to the choices *you* made** — the most personal, motivating progress bar there is. You stay in control of spending, which builds trust instead of subscription resentment.

---

## Phase 6 — Monetization

**Model: subscription for the intelligence + affiliate revenue on what you choose to buy.** (No inventory, no fulfillment, no lock-in.)

- **Free forever:** scanning, skin age, Timeline, and a basic Priority Plan. Viral top of funnel, zero risk to try.
- **Mira Pro — $9.99/mo (or ~$60/yr):** the full ranked plan with reasons, weekly trend analytics, smart re-ranking + alternatives after Skips, the AI skin coach, and the product scanner. **People pay for the brain, not for products.**
- **Affiliate commissions:** because users buy through Mira's recommended links (Amazon, Sephora, brand DTC), Mira earns a cut **only when the user freely chooses to buy** — perfectly aligned, since Mira ranks by *what works*, not by who pays most. (Guardrail: ranking is always results-first; affiliate is a tiebreaker at most, and disclosed.)

### Why users gladly pay
$9.99/mo is trivial against the $80–150/mo they already spend — and Mira *makes that spend smarter and proves it worked.* It's the opposite of a subscription box: no commitment to anyone's products, just better decisions.

### Pricing psychology
The free reveal creates desire and loss-aversion ("here's your face in a year if you do nothing"). Pro is framed as "spend the money you're already spending — but on the *right* things, in the *right* order, with proof." Annual plan bridges skincare's slow payoff (results take 8–12 weeks).

### Expansion potential
- New scan verticals on the same engine + trust: **scalp/hair, body skin, sunscreen habits, supplements.**
- **Tele-derm referral** for prescription actives → referral revenue + higher trust.
- A **brand-analytics product** (later, carefully): anonymized "what actually improves which skin types" insights, sold to manufacturers — without ever compromising the results-first ranking.

---

## Phase 7 — MVP (buildable in ≤30 days)

### Include
1. **Guided, lighting-gated selfie scan.** On-screen lighting coach + a live "good lighting ✅" check that blocks bad scans. This is non-negotiable — it's what makes the data trustworthy.
2. **A vision model** scoring a few high-confidence, defensible metrics (skin age estimate, redness, pigmentation/sun spots, texture). Narrow and accurate beats broad and shaky.
3. **The reveal screen** (skin age + simple projection) — the conversion moment, polish it most.
4. **The Priority Plan:** a ranked list from a curated catalog of ~25–40 well-known products, each with a plain-English reason, generated by an LLM over dermatologist-written rules. **No fulfillment** — just affiliate/buy links out.
5. **Ordered / Skip(+reason) buttons** and a **weekly re-scan** that updates the **Skin Timeline.**

### Remove for now
Any product fulfillment/inventory, custom formulation, tele-derm, full product scanner, scalp/body verticals, brand-analytics. All later.

### Tech stack
- **Frontend:** React Native (camera + push + a solid lighting-check UX).
- **Vision:** off-the-shelf skin-analysis API / vision-capable LLM for v1; train your own model once you have proprietary scan + outcome data.
- **Reasoning/ranking:** an LLM (Claude) over a structured product catalog + dermatologist-written prioritization & safety rules.
- **Backend:** Supabase/Postgres; affiliate-link management; **no 3PL needed.**

### How to fake/shortcut complexity
- **Recommend, don't fulfill** — you ship *decisions*, so there's no supply chain to build.
- **Wizard-of-Oz the rankings** for the first cohorts: a part-time licensed esthetician/derm reviews the AI's Priority Plans behind the scenes (quality, safety, and training data) before you trust it to run solo.
- **Get lighting right cheaply** with framing guides + a simple brightness/white-balance check before investing in fancy calibration.

---

## Phase 8 — Go-To-Market (first 1,000 users)

### Where they already are
**Skincare TikTok and Instagram** — the most concentrated, highest-intent audience for this — plus r/SkincareAddiction, r/30PlusSkinCare, and "skincare routine" / "get ready with me" content.

### How to reach them
1. **The scan IS the content.** The reveal screen (skin age + before/after projection) is built to be screenshotted and stitched into videos. Sharing is one tap.
2. **Creator seeding:** send the app to mid-tier skincare creators; let them **scan their own face on camera** and react to their skin age and Priority Plan. Their reaction is irresistible content *and* a live demo. Bonus: creators love it because it's neutral (not shilling one brand) and works with affiliate links they may already use.
3. **The "Skin Age Challenge":** free, no-purchase campaign — "Scan your face, post your skin age vs. real age." Pure top-of-funnel virality.

### Launch strategy
Lead with the **free skin-age scan as a standalone viral object.** Millions of scans → convert fixable-issue users to Pro via the projection ("here's your skin in a year if you do nothing — and here's your ranked plan to change it").

### Viral / shareable mechanic
The **Skin Age card** ("my skin age is 24 at 29 💅") and, after a few months, the **before/after Timeline reel** — auto-generated from the user's own scans and tied to the products they chose. The most credible, shareable asset in skincare, made automatically.

---

## Phase 9 — Brutal Validation

### Why it might fail
1. **Scan accuracy & lighting consistency.** If lighting/angle make "skin age" jump around, trust dies instantly. The measurement is the whole moat. *(This is exactly why lighting is gated, not optional.)*
2. **Medical/regulatory line.** Detecting "acne/aging" is fine; implying diagnosis/treatment — or missing a melanoma — is legal and ethical danger.
3. **Body-image harm.** A harsh "your skin is old" reveal can hurt vulnerable users.
4. **Slow payoff vs. fast churn.** Results take 8–12 weeks; users may churn before proof.
5. **Will users log purchases?** The Ordered/Skip loop is only as good as user diligence in tapping it.

### Biggest risks
Scan reliability (#1) is existential. Regulatory framing (#2) is a hard guardrail. The Ordered/Skip logging habit (#5) is what makes the learning loop work — if people don't log, the AI flies blind.

### The assumption that MUST be true
**Well-lit phone scans can track real skin change reliably over weeks, AND enough users will mark Ordered/Skip for the loop to learn, AND visible measured progress retains them better than ordinary skincare habits.** If the measurement is noise or the loop stays empty, it degrades to "another scan app."

### Improvements to fix the weaknesses
1. **Spend the first dollar on lighting + normalization.** Live good-lighting gating, color correction, and "conditions match — comparison valid" checks. Never show a jumpy number; only show trends at high confidence.
2. **Frame strictly cosmetic, never medical,** and add a **safety layer that flags suspicious lesions → "please see a dermatologist."** Turns the scariest risk into a trust feature.
3. **Make the reveal empowering, not shaming** — lead with the fixable trajectory and the ranked plan, not a harsh verdict.
4. **Beat the logging problem:** make Ordered/Skip one tap, prompt right after a scan ("did you buy any of these?"), and reward logging by showing attribution in the next Timeline ("because you ordered X, here's what changed"). Where possible, offer optional receipt/email parsing to auto-detect purchases.
5. **Fight slow-payoff churn** with early leading indicators (hydration/redness move in 1–2 weeks) so users see *something* fast, plus annual plans to bridge the proof gap.
6. **Differentiate hard:** never "personalized skincare" (crowded). Position as **"the only skincare advisor that ranks what to buy next — and proves it worked."**

---

### Bottom line
The skincare market is enormous but built on faith — people spend billions and *never know if it worked, or what to buy first.* Mira's product isn't products and it isn't a box you're locked into. It's **prioritized decisions + proof.** Good-lit weekly scans make progress measurable; the ranked plan tells you exactly what to buy next; the Ordered/Skip loop teaches the AI your budget, your taste, and what actually moves your skin. Free reveal → AI does the thinking → you stay in control of the buying → you can finally *see* it working.
