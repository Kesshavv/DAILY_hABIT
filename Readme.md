# 🌱 Daily Habit Builder — UX Design Assignment

> A minimal mobile app that helps users build **one daily habit** and actually stick to it.  
> Designed to extend user retention from the typical 2–3 days to **7+ days**.

---

## 📱 Prototype Preview

| Onboarding | Daily Action | Missed Day | Progress Viz |

| Pick a habit in under 30s | One-tap completion | Guilt-free comeback | Chain + Heatmap |

> 🔗 **[View Interactive Prototype →](https://github.com/Kesshavv)**  
> Built as a fully clickable HTML prototype — all 5 flows, 3 screens, zero setup needed.



## 🎯 Problem Statement

Most habit apps lose users within **2–3 days** — not because users stop wanting the habit, but because **the app itself becomes a chore**.

The moment an app demands more willpower than the habit, users quietly abandon it.

This design addresses that gap with three principles:

- **Radical simplicity** — the daily action takes under 10 seconds
- **Visible momentum** — streaks and chains make progress feel owned
- **Guilt-free recovery** — missing a day doesn't mean starting over

---

## 🗂 Flows Designed

### 1. 🚀 Onboarding (Quick Setup)
- 6 preset habits shown immediately — no blank slate paralysis
- Optional reminder time in one tap (morning / midday / evening)
- No account, no paywall, no tutorial
- **Under 30 seconds from open to first habit set**

### 2. ✅ Daily Action Screen
- Single large tap button — the only interaction on screen
- Habit name, icon, and today's week strip visible at a glance
- Completion triggers a full-screen celebration + streak pop animation
- **Designed to feel effortless and satisfying, not transactional**

### 3. 📊 Progress & Consistency
- Live streak badge (🔥) on the main screen
- Weekly strip shows the last 7 days at a glance
- Progress screen: streak count, weekly %, total days completed
- Monthly calendar — green dots form a visual "wall" users want to fill

### 4. 💬 Re-engagement (Missed Day)
- Opens with warm language: *"Hey, you okay? 👋"* — no shame, no broken streak graphic
- **Streak Freeze** — one grace day per week to protect the chain during genuinely busy days
- Instant one-tap restart: "Mark today as done →" is the first action
- Notification concept: gentle, habit-specific reminder (not generic push spam)

### 5. 📈 Progress Visualization
- **Chain View** — a scrollable dot-per-day chain; green = done, red = missed, black = today
- **Heatmap View** — weekly intensity grid showing monthly patterns
- Best streak callout card + month-on-month bar chart
- **Makes consistency visible and meaningful, not just numerical**

---

## 🧠 Why Users Come Back Daily

### The Seinfeld Method (Don't Break the Chain)
Once users hit 5+ consecutive days, the psychological cost of breaking the chain becomes a motivator stronger than any notification. The chain visualization makes this visceral — users can *see* what they'd be destroying.

### Retention by Day Range

| Days | What keeps them coming back |
|------|----------------------------|
| **Day 1–2** | Completion animation + instant streak feedback creates a positive first impression |
| **Day 3–5** | Streak number becomes personally meaningful; week strip shows a growing green row |
| **Day 6–7** | Full-week milestone is significant; chain visualization makes it feel like an achievement |
| **Day 8+** | Momentum compounds; breaking the chain now has real perceived cost |

### Why Missed Days Don't Kill Retention
The standard habit app failure mode: user misses day → sees broken streak → feels shame → quits.

This design breaks that loop:
1. Warm, non-judgmental tone on the missed-day screen
2. Streak Freeze removes the all-or-nothing pressure
3. Recovery friction is zero — one tap and the new streak begins

---

## 🚫 Constraints Respected

This design deliberately excludes:

- ❌ Social / sharing features
- ❌ AI suggestions or smart scheduling
- ❌ Complex dashboards or analytics
- ❌ Multiple habits
- ❌ Points, badges, or heavy gamification

> **Focus beats features.** One habit, done daily, tracked simply.

---

## 🛠 Design Decisions

| Decision | Reason |
|----------|--------|
| Single habit only | Reduces cognitive load; users who try to track 5 habits track 0 |
| Preset habit options | Eliminates blank-slate paralysis on day 1 |
| Streak freeze | Prevents all-or-nothing abandonment after one missed day |
| Warm missed-day copy | Shame is the #1 reason users don't return |
| Two progress views | Chain = daily accountability; Heatmap = long-term pattern recognition |
| Bottom nav with only 2 tabs | Every extra tab is a decision; minimize decisions |



## 📐 Fidelity

- **Low to medium fidelity** — focus on interaction patterns over visual polish
- All screens designed for **320px mobile viewport**
- Typography: Sora (headings) + DM Sans (body)
- Color system: Sage green (primary) · Amber (streak) · Warm cream (backgrounds)



## 📁 Deliverables

```
habit-builder-ux/
├── prototype/          # Interactive HTML prototype (all 5 flows)
├── explanation.pdf     # 2-page design rationale
└── README.md           # This file
```



## 👤 Author

**Kesshavv**  
[github.com/Kesshavv](https://github.com/Kesshavv)

