# Mira

**Scan your face. See your real skin age. Let the AI fix it on autopilot.**

---

## Phase 2 — The Idea

### One-line description
Mira turns a 5-second selfie into an objective read on your skin (skin age, acne, sun damage, hydration, aging trajectory), then an AI operator builds your regimen, **ships the exact products to your door, and re-adjusts every month based on new scans** — so your skincare runs itself and you can actually *see* it working.

### The core insight (the unfair advantage)
Skincare doesn't fail because the products are bad. It fails because of **two invisible problems**:
1. **No feedback loop.** People can't tell if anything is working, so they quit at week 3 and rebuy the next hyped thing. Billions are spent thrashing between products with zero measurement.
2. **Decision fatigue.** "What do I actually need?" is paralyzing — 10,000 products, contradictory TikTok advice, no objective truth.

Mira's unfair angle: **the camera becomes the measuring instrument skincare never had.** Once you scan the same face weekly under normalized conditions, you create the *first objective, longitudinal feedback loop in consumer skincare* — and that data lets an AI both prove what's working and **decide what to ship next without the user choosing anything.** The reveal hooks them; the proof retains them; the auto-ship monetizes them.

### Why NOW
1. **Phone cameras + on-device vision crossed the line.** A 2026 phone can normalize lighting, detect texture, pores, redness, pigmentation, and fine lines reliably enough to trend over time — impossible at consumer scale a few years ago.
2. **Skincare became identity, not vanity.** "Skin age," "glass skin," and routine-as-self-care are mainstream across genders and generations (Gen Alpha/Z made it culture).
3. **DTC supply chains are turnkey.** White-label/contract-manufactured skincare + 3PL fulfillment means a startup can ship personalized product without owning a factory.
4. **"Done-for-you" beat "tools" in 2026.** People don't want another tracker — they want it handled.

---

## Phase 3 — Product Definition

### 1. Target user (specific)
**Maya, 27, the "overwhelmed optimizer."** She spends $80–$150/month on skincare, owns 14 half-used products, follows 5 skincare creators, and *still* isn't sure if her routine works. She's tried Curology-style quizzes but they felt like a guess. She's image-conscious, screenshots her good-skin days, and feels low-grade anxiety about aging and breakouts. She wants to look her best with the **least possible thinking**.

Secondary: image-conscious men 22–35 entering skincare for the first time who are intimidated by the aisle and want to be *told* exactly what to do.

### 2. Core problem
- **What hurts:** Spending real money with no idea if it's working, plus the constant low-grade anxiety of "is my skin getting worse?" and the exhaustion of choosing.
- **How often:** Daily routine, weekly anxiety spikes, monthly rebuys.
- **Why current solutions suck:** Quiz-based brands (Curology, Prose) guess once from a questionnaire and never measure results. Generic scan apps give you a score and *stop there* — they don't act. Dermatologists are expensive, slow, and don't manage your daily routine. Nobody closes the loop between **measure → act → re-measure.**

### 3. Core feature (the heart)
**Scan → Auto-Regimen → Auto-Ship → Re-Scan.** One selfie produces an objective skin read; the AI assembles the precise regimen and **ships it automatically**; every subsequent weekly scan proves progress and silently adjusts the next shipment. The user's only job is to take a 5-second selfie and apply what shows up at their door.

### 4. Supporting features (max 4)
1. **Skin Timeline** — a visual before/after that updates with every scan. This is the retention engine: people stay to watch their own skin improve.
2. **AI skin coach** — answers "can I use this with that?", "why am I breaking out?", grounded in *their* scan history, not generic advice.
3. **Product scanner** — scan any product you already own or see in a store; Mira says "yes, fits your skin / no, here's why" so you stop wasting money.
4. **Flare-up mode** — sudden breakout? Scan it, get an immediate targeted response and an expedited add-on ship.

### 5. 10x advantage
Every competitor either **measures without acting** (scan apps) or **acts without measuring** (quiz brands). Mira is the only one that does both in a closed loop — so it's the only one that can *prove ROI to the user and improve its own recommendations over time.* That measurement moat compounds: the more people scan, the better Mira predicts what works for which skin, which no quiz-brand can match.

### 6. Habit loop
- **Trigger:** weekly "time to scan" nudge + the dopamine of checking your Skin Timeline.
- **Action:** 5-second selfie scan.
- **Reward (variable):** sometimes "skin age dropped a year," sometimes "hydration up 12%," sometimes a flare to fix. The variability + visible self-improvement makes it as sticky as a fitness streak — you're literally watching yourself get better.

---

## Phase 4 — AI Agent Design

A **skin operator**, not a quiz.

### Inputs (data sources)
- **Normalized facial scans over time** (the core signal — texture, pigmentation, redness, pores, fine lines, hydration proxies).
- **Self-reported context:** sleep, cycle, stress, diet flags, climate/season, sun exposure.
- **Product response data:** what was shipped, what the next scan showed → which ingredients actually move *this* person's skin.
- **Population-level outcomes:** aggregated (anonymized) results across millions of skin types feeding the recommendation model.

### Decisions it makes autonomously
- What the skin's actual issues and trajectory are.
- The exact regimen (actives, concentrations, sequence, AM/PM) and how to ramp it (e.g., introduce retinoids slowly to avoid irritation).
- **What to ship next month** and when to reorder before you run out.
- When to dial back (irritation detected on scan), escalate to a tele-dermatologist partner, or trigger flare-up mode.

### Tasks it COMPLETELY replaces
Choosing products, sequencing them, reordering, deciding if it's working, and adjusting. The entire "what do I do about my skin" job.

### How it reduces thinking
Maya goes from "10,000 products and no idea" to "take a selfie, apply what arrives." Zero product decisions in the default path.

### Why it feels like a personal operator
It doesn't hand her a report — it hands her *results and a box on her doorstep.* It speaks in outcomes: "Your retinoid is working — skin age down 1.2 years. I've added a brightening serum for the sun spots; it ships Tuesday." It's a dermatologist + concierge + supply chain that never sleeps.

---

## Phase 5 — User Experience

### First 60 seconds (onboarding)
1. "Let's see your skin" → guided selfie with on-screen framing/lighting normalization.
2. ~10 seconds of analysis animation.
3. The reveal: **"Skin age: 31 (you're 27). Top issues: sun damage on cheeks, mild dehydration. Here's your trajectory if you do nothing — vs. with Mira."** Two side-by-side projected faces.
4. "Want me to build and ship your routine?" → checkout.

### First wow moment
The **skin-age reveal + 12-month projection.** Seeing a real, personalized "this is your face now, this is your face in a year if you do nothing vs. with us" is visceral and impossible to ignore. That single screen sells the product.

### Daily/ongoing flow
Morning: apply the AM products that arrived (clearly labeled 1-2-3). Weekly: nudge → 5-second scan → Timeline updates → occasional "skin age dropped" hit. Monthly: a box just shows up, already adjusted. She basically never *decides* anything.

### Why it's effortless and addictive
Effort is one selfie a week. The reward is **watching your own face objectively improve** — the most personal progress bar imaginable — plus products that arrive without thought. It's a streak you can see in the mirror.

---

## Phase 6 — Monetization

**Model: freemium scan → product subscription (the money is in the auto-ship).**

- **Free forever:** scanning, skin age, Timeline, basic insights. This is the viral top of funnel and removes all risk to try.
- **Mira Routine subscription:** personalized products auto-shipped, **$45–$75/month** depending on regimen depth. This is the core revenue — recurring, high-margin (white-label COGS), and naturally expanding.
- **Mira+ ($9.99/mo, optional):** advanced analytics, unlimited AI coach, flare-up priority, tele-derm escalation credits — for power users who want more than the products.

### Why users gladly pay
They're *already* spending $80–150/month on skincare that thrashes. Mira isn't new spend — it's **replacing wasted spend with measured, working, no-thought spend.** And because the scan proves results, churn drops: you don't cancel something you can *see* working.

### Pricing psychology
The free reveal creates desire and loss-aversion ("look what happens if you do nothing"). The subscription is framed as *less than you already waste,* with proof attached. Annual plan at a discount locks in the slow-payoff nature of skincare (results take 8–12 weeks — exactly long enough that monthly churners quit before seeing results, so you nudge them to annual).

### Expansion potential
- **Add-on categories:** sunscreen, supplements, body skin, hair/scalp scans — same engine, same trust.
- **Tele-derm upsell** for prescription actives (tretinoin) → higher ARPU.
- **Retail/brand partnerships:** Mira's product-scanner becomes a recommendation layer; brands pay for placement against matching skin profiles (later, carefully).

---

## Phase 7 — MVP (buildable in ≤30 days)

### Include
1. **Guided selfie scan** + a vision model that scores a few high-confidence, defensible metrics (skin age estimate, redness, pigmentation/sun spots, texture). Start narrow and accurate, not broad and shaky.
2. **The reveal screen** (skin age + simple projection) — this is the conversion moment, polish it most.
3. **AI-generated regimen** from a curated catalog of ~15–25 white-label products (don't formulate custom chemistry yet — *select and sequence* from proven off-the-shelf actives).
4. **Auto-ship via a 3PL** + monthly re-scan reminder.
5. **Skin Timeline** (before/after).

### Remove for now
Custom-formulated products, tele-derm integration, product scanner, flare-up mode, men's vertical, supplements. All later.

### Tech stack
- **Frontend:** React Native (camera + push).
- **Vision:** start with a vision-capable LLM / off-the-shelf skin-analysis API for v1 metrics; fine-tune your own model later once you have proprietary scan data.
- **Reasoning/regimen:** an LLM (Claude) over a structured product catalog + dermatologist-written rules (sequencing, contraindications, ramp schedules).
- **Backend:** Supabase/Postgres; **fulfillment via a 3PL + a contract manufacturer's stock catalog.**

### How to fake/shortcut complexity
- **Don't manufacture — curate.** Ship existing white-label products; you're selling the *intelligence and the loop*, not chemistry.
- **Wizard-of-Oz the hard regimen calls** with a part-time licensed esthetician/derm reviewing AI recommendations behind the scenes for the first cohorts (quality + safety + training data).
- **Normalize scans cheaply** with on-screen framing guides + simple color/lighting correction before investing in fancier calibration.

---

## Phase 8 — Go-To-Market (first 1,000 users)

### Where they already are
**Skincare TikTok and Instagram** — the single most concentrated, highest-intent audience on earth for this. Plus r/SkincareAddiction, r/30PlusSkinCare, and "get ready with me" / "skincare routine" content ecosystems.

### How to reach them
1. **The scan IS the content.** The reveal screen (skin age + before/after projection) is built to be screenshotted and stitched into videos. Make sharing one tap.
2. **Creator seeding:** send the app to mid-tier skincare creators and let them **scan their own face on camera** and react. Their reaction to their "skin age" is irresistible content — and it's a live demo.
3. **The "Skin Age Challenge":** a free, no-purchase-needed campaign — "Scan your face, post your skin age vs. real age." Pure top-of-funnel virality; conversion happens after the reveal.

### Launch strategy
Lead with the **free skin-age scan as a standalone viral object** (you don't even need to buy anything). Get millions of scans → convert the ones with fixable issues into the auto-ship subscription via the projection ("here's your skin in a year if you do nothing").

### Viral / shareable mechanic
The **Skin Age card** — auto-generated, beautiful, status-flavored ("my skin age is 24 at 29 💅"). And the **before/after Timeline reel** after a few months — the single most shareable, credibility-building asset in skincare, generated automatically from the user's own scans.

---

## Phase 9 — Brutal Validation

### Why it might fail
1. **Scan accuracy & consistency.** If lighting/angle make "skin age" jump around, trust dies instantly. The measurement is the whole moat — if it's noisy, there's no product.
2. **Medical/regulatory line.** Detecting "acne/aging" is fine; implying diagnosis or treatment of skin *conditions* (or worse, missing a melanoma) is legal and ethical danger.
3. **Body-image harm.** A "skin age worse than your real age" reveal can hurt vulnerable users — brand and ethics risk if done cruelly.
4. **Slow payoff vs. fast churn.** Skincare results take 8–12 weeks; subscriptions can churn before users see proof.
5. **Crowded-ish space** (Curology, Prose, scan apps) — must be clearly differentiated or it blurs into "another skincare quiz."

### Biggest risks
Scan reliability (#1) is existential — everything else is manageable. Regulatory framing (#2) is a hard guardrail you must respect from day one.

### The assumption that MUST be true
**Phone-camera scans can be normalized enough to track real skin change over weeks reliably, AND that visible, measured progress meaningfully reduces churn vs. ordinary skincare subscriptions.** If the measurement is noise, or proof doesn't retain people, the model collapses to "yet another skincare box."

### Improvements to fix the weaknesses
1. **Invest first dollar in scan normalization** (lighting/angle guidance, color correction, "scan conditions match — comparison is valid" gating). Only show trends when confidence is high; never show a jumpy number.
2. **Frame strictly cosmetic, never medical.** Add a **safety layer that flags suspicious lesions and routes to "please see a dermatologist"** — turning the biggest risk (missing something serious) into a trust-building feature, while staying clear of diagnosis.
3. **Make the reveal empowering, not shaming.** Lead with the *trajectory you can change*, not a harsh verdict. "Here's what's fixable and how fast" beats "your skin is old."
4. **Fight slow-payoff churn** with early *leading indicators* (hydration/redness move in 1–2 weeks, before deep aging metrics) so users see *something* working fast, plus annual plans priced to bridge the proof gap.
5. **Differentiate hard on the closed loop.** Never position as "personalized skincare" (crowded) — position as **"the only skincare that proves it's working."** Measurement is the wedge no incumbent has.

---

### Bottom line
The skincare market is enormous but built on faith — people spend billions and *never know if it worked.* Mira's real product isn't products; it's **proof.** The free skin-age scan is the most shareable hook in the category, the closed measure→act→re-measure loop is the moat no quiz-brand can copy, and the auto-ship turns proven results into recurring revenue. Same winning shape as Overrule: **free reveal → AI does the work → you pay for the outcome.**
