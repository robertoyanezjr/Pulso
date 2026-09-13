# Nutrition & Training Profile — Roberto

**Last updated:** 2026-08-17
_Update this file whenever your weight, targets, or preferences change — it's the source of truth the coach reads from._

**Mission:** not just a macro tracker — a simple optimization dashboard for a clean, healthy lifestyle aimed at longevity. Nutrition is the core mechanism; recovery, training, sleep, bloodwork, and daily activity are the supporting pillars.

## Stats
- Age: 61
- Sex: Male
- Height: 5'8" (172.7 cm) — _confirm if "58" in chat meant something else_
- Current weight: 198 lb (as of 2026-08-19)
- Goal weight: 187 lb (−11 lb)
- Waist: 40 in (first reading, 2026-08-19)
- Occupation: Executive, desktop job (sedentary most of the day), frequent business travel
- Training: Tonal (resistance training), every other day, ~20 min/session
- Family: married, two adult kids (27, 29)

## Devices
- **Smart ring:** generic/white-label model ("TK5 41CD"), not a recognized major brand (Oura/WHOOP/Ultrahuman) — no known public API. **Import path: screenshot of the app's home/health screen**, same as meals. Tracks sleep, resting HR, HRV, SpO2, blood pressure, and usually step count.
- **Tonal:** no confirmed public API either (see `SETUP_GUIDE.md`). **Import path: screenshot the end-of-workout summary screen** (total volume, duration, calories) — a mid-set screenshot only shows one exercise, so the summary screen is the useful one to send.
- All three log into the `Training & Recovery` tab in `Pulso-Macro-Tracker.xlsx` — sleep and steps included alongside the existing vitals/Tonal columns, same screenshot-based workflow.

## Tracked fields & governance
Core (always logged, never questioned regardless of gaps): nutrition, bodyweight.
Supplementary (10-day-silent rule applies — see below): Recovery reading (ring: sleep, RHR, HRV, SpO2, BP), Tonal Training, Bloodwork, Waist circumference (added 2026-08-19 — logs into `Daily Log` column N alongside weight, same sheet/workflow).

**Steps — dropped 2026-08-21.** Never once logged in the week it was on the dashboard; retired per Roberto's own review rather than waiting out the 10-day idle clock. History preserved (there was none to lose) — the `Field Status` row shows it as retired, same treatment as a retired Advisory Board member.

**10-day idle rule:** the `Field Status` table at the bottom of `Training & Recovery` tracks Last Logged / Days Idle / Status for each supplementary field. Any field that goes 10+ real days without new data flips to `REVIEW` — that's a notify-Roberto trigger, never an auto-drop. The coach names the idle field and asks whether to keep watching for it or retire it from the dashboard. Bloodwork's clock only starts after its first real entry, not from today — it's expected to be empty until ~8/26.

**Panel updates:** the SENARA Health Read panel republishes the same turn any new data comes in — no batching, no waiting for "enough." It has no live clock of its own, so it does not roll over at midnight unattended — the next day's view appears the next time data is logged or the panel is asked for. Nothing is ever deleted: every day is permanent in `Daily Log`, every week permanent in `Weekly Summary`.

**Week convention:** weeks run real Sunday–Saturday calendar weeks (not "7 days since day 1") — see `Weekly Summary` in `Pulso-Macro-Tracker.xlsx`. The panel's 7-Day Snapshot follows the same boundary.

## Advisory Board
A named panel that gives a simulated daily read on the log — clearly labeled as inference from each person's public work, never their real opinion or an actual review by them.

Current roster (trimmed 2026-08-18 for a leaner daily read): Peter Attia, Andrew Huberman, Layne Norton, Benjamin Bikman, Brad Schoenfeld, Gary Brecka.

Retired, history preserved (not deleted) in `Advisory Board Log`: William Li, Jessie Inchauspé, Mark Hyman, Rena Malik, Andy Galpin, Arthur C. Brooks, Chip Conley — mostly single- or zero-flag voices, or angles (well-being/purpose) that didn't fit a lean nutrition/longevity dashboard. Can be reinstated any time; nothing about them was deleted.

**Governance:** each evaluated day gets a row in `Pulso-Macro-Tracker.xlsx → Advisory Board Log` (who flagged, who approved). Once 10+ real days are logged, the sheet's `Board Status` table flags any advisor silent for 10 straight days as `REVIEW`. That's a notify-Roberto trigger, not an auto-remove — the coach tells him who's been quiet and suggests possible replacements; he decides.

## Lifestyle
- Sleep: in bed ~9:30pm, asleep ~10:30pm most nights — solid, consistent routine
- Compliance: follows a plan well once it's clear — coaching can be direct/prescriptive, doesn't need much hand-holding
- Vitamins/supplements: none currently
- Bloodwork: panel drawn 2026-08-13, **final** report back 2026-08-19 (logged in the `Bloodwork` tab). No lipid panel this round. Headline finding: **ApoB 130 mg/dL, flagged High** (desirable <90, high 100–130) — the primary cardiovascular risk marker in this dashboard's Attia-influenced coaching style, worth raising with Dr. Aldrich directly. Cardiac hs-CRP 0.84 mg/L is Low risk (good, low inflammation). Also: A1C 5.6% (top of normal), glucose 104 mg/dL flagged High but fasting status wasn't recorded so it's not conclusive alone, vitamin D 30.8, testosterone 631 (free 10.2), IGF-1 167 (normal). Not medical advice — flag ApoB + glucose to Dr. Aldrich.
- Travel: on the road often; needs restaurant/no-kitchen strategies that hold the line on protein and processed food, not just "do your best"

## Coaching style
Longevity / metabolic-health approach (Peter Attia / Andrew Huberman–style):
- Protein-forward eating, prioritized above hitting exact carb/fat numbers — the goal is losing fat while keeping the muscle you have at 61
- Fiber and micronutrient density over ultra-processed calories
- Minimal added sugar and alcohol; treat both as planned exceptions, not daily habits
- Light nutrient timing around training days (a bit more carbs on lift days, a bit less on rest days)
- Judge progress on the **weekly weight trend**, not single-day swings

## Calculated targets
**Revised 2026-08-22** (manual update, replacing the raw Mifflin-St Jeor output below — protein moved down, fat and carbs moved up):

| | Target | Working range |
|---|---|---|
| **Calories** | **1,850 kcal/day** | 1,800–1,900 |
| **Protein** | **155 g** (~34%) | 150–160 g |
| **Carbs** | **160 g** (~35%) | 145–175 g |
| **Fat** | **65 g** (~32%) | 55–65 g |
| **Fiber** | **35 g/day minimum** | 30–40 g |
| **Alcohol** | minimize; budget ~150 kcal into the day's total if you have a drink | — |

Recorded but **not tracked day-to-day** (per Roberto, 2026-08-22): saturated fat (≤12 g/day) and added sugar (≤20–25 g/day, lower preferred). Meal estimates only break out total fat and total carbs — no per-meal saturated-fat/added-sugar split, and neither shows on the panel. Revisit if he wants that estimation started.

Was 1,825 kcal / 187g protein / 141g carbs / 57g fat / <25g added sugar (Mifflin-St Jeor BMR ~1,691 kcal, TDEE ~2,325 kcal, ~500 kcal deficit, "lightly active" multiplier — see `Pulso-Macro-Tracker.xlsx → Targets` for the underlying calc, kept as reference; the revised numbers above are now the live targets used everywhere in the panel and spreadsheet). Recalculate every 2 weeks against your actual weigh-in trend (see `SETUP_GUIDE.md`).

## Pace to goal
11 lb at ~1 lb/week ≈ 11 weeks → roughly **early November 2026**, updated 2026-08-19 off the 198 lb weigh-in (was 14 lb / late Nov off the 8/15 reading). The 201→198 move in 4 days is faster than the 1 lb/week target — normal for the first week and likely includes some water/travel effect, not pure fat loss. Don't recalibrate the daily targets off one reading; hold the plan and re-check the trend at the next 2-week mark (see `SETUP_GUIDE.md`). A faster cut (~1,600 kcal/day) is possible but raises the risk of muscle loss and burnout at your training frequency, so it's not the default recommendation.

## Food preferences / restrictions
- **Proteins (liked):** salmon, NY strip steak, ground beef, egg whites with one whole egg (breakfast go-to), hard-boiled eggs
- **Vegetables/sides (liked):** broccoli, arugula salad, sweet potatoes
- **Beverages:** black coffee and/or espresso, water — no complaints on either
- **Sweets:** easy to avoid, not a struggle point — don't need to spend coaching effort here
- **Dislikes/allergies:** none flagged yet
- **Eating window / fasting:** none specified — standard 3-meal-plus-snack pattern assumed unless told otherwise

## Sample day at 1,825 kcal / 187g protein / 57g fat / 141g carbs
Built from your actual liked foods:
- **Breakfast:** egg whites + 1 whole egg (or hard-boiled eggs) + black coffee/espresso — ~35–40g protein
- **Lunch:** grilled salmon or NY strip + arugula salad + broccoli — ~45–55g protein
- **Snack:** hard-boiled eggs or Greek yogurt — ~15–25g protein
- **Dinner:** ground beef (lean) or salmon + broccoli + small portion sweet potato (bigger portion on Tonal days) — ~50g protein
- Adjust portions to hit the day's numbers; swap freely among the liked-foods list above as long as protein and calories land close. Sweet potato is the one carb-dense item in regular rotation — lean on it more on training days, less on rest days.

## Travel game plan (no kitchen, restaurant/hotel-dependent)
Standing order for any restaurant, any city: **"Grilled or blackened [protein], double the vegetables, no starch, sauce/dressing on the side."** That single line hits protein, skips the bread basket/fries/rice, and puts you in control of added fat — which matters given fat is the macro most likely to run over when eating out (see Debrief history).
- **Flights/airports:** hard-boiled eggs or a protein shake before you go if possible; black coffee is a free pass. Avoid the pretzels/snack-mix reflex — they're pure processed carbs for no protein.
- **Restaurant ordering:** grilled/blackened salmon, steak, or a burger patty with no bun are all easy protein anchors on almost any menu. Ask for broccoli, salad, or any non-starchy veg instead of fries/rice/mash.
- **Hotel breakfast:** eggs (any style) + fruit is usually available even at a basic continental spread; skip the pastries and cereal.
- **Snacking on the road:** hard-boiled eggs (grab extras from breakfast), Greek yogurt, nuts (measured, not from the bag), string cheese — all fine, all better than the minibar.
- **Alcohol:** if there's a work dinner, one drink budgeted at ~150 kcal is fine per the standing rule — just count it.
- Log what you can from photos same as at home — a restaurant plate is estimable the same way.

## Notes
This is nutrition coaching, not medical advice. Check with a physician before starting a sustained calorie deficit, especially given age and any medications or cardiometabolic conditions.
