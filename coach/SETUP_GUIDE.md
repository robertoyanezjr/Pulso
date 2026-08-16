# Setup Guide — Your Daily Macro Coach

## 1. Fill in your food preferences
Open `PROFILE.md` and fill in the "Food preferences / restrictions" section (likes, dislikes, allergies, go-to meals). This is the biggest lever on how useful the daily recommendations are — skip it and you'll get generic advice.

## 2. Create the Claude Project
1. Go to claude.ai → **Projects** → **Create project**. Name it something like "Pulso Macro Coach."
2. Open **Project settings → Set custom instructions**, and paste in everything from `CLAUDE_PROJECT_INSTRUCTIONS.md` (the part below the line).
3. Under **Project knowledge**, upload `PROFILE.md`. Re-upload it whenever you edit it (new weight, new targets, updated preferences).

## 3. Daily use
1. Each day, open the Project and start (or continue) a chat.
2. When you eat, snap a photo of the plate and send it with a short note if useful ("grilled, no oil," "restaurant portion," etc.).
3. I'll estimate calories/macros, log it against your daily target, and tell you where you stand.
4. Keep using the **same chat thread all day** so the running total carries over. Start a fresh chat the next morning.
5. Ask "what should I eat for dinner" any time — I'll answer based on what's left in your budget for the day.

## 4. Weekly
- Weigh yourself the same morning each week (e.g., Monday, after waking, before eating) and tell me the number.
- I'll compare it to prior weeks and tell you if you're tracking toward 187 lb at a healthy pace, or if we need to tighten calories.
- Log the weigh-in and daily totals in `Pulso-Macro-Tracker.xlsx` if you want a persistent written history outside the chat (the chat itself doesn't remember previous days once you close it — the spreadsheet is your long-term record).

## 5. Recalibrate every 2 weeks
Weight and metabolism drift as you lose fat. Every 2 weeks, check the trend in your tracker:
- Losing ~1 lb/week → targets are working, keep going.
- Losing faster than ~1.5 lb/week → consider adding 100–150 kcal back (protect muscle/energy).
- Stalled 2+ weeks → cut ~100–150 kcal, re-check adherence first (is protein and calorie logging actually accurate?).

Update the numbers in `PROFILE.md` when you do, so the coach stays current.

## Alternative: skip the Project, just use a Claude chat
If you don't want to set up a formal Project, you can get the same behavior in any Claude conversation (like this one) by pasting `CLAUDE_PROJECT_INSTRUCTIONS.md` and `PROFILE.md` at the start of the chat, then sending photos. You'll just need to re-paste them each time you start a new conversation, since a plain chat doesn't retain Project knowledge automatically.
