# 💸 Flex Budget

**Adaptive budgeting for irregular income earners.**

Flex Budget helps freelancers, gig workers, and anyone with variable income make smarter spending decisions — no rigid monthly salary required.

---

## The Problem

Most budgeting tools assume you earn the same amount every month. If your income fluctuates (freelance projects, gig work, seasonal jobs), those tools either don't work or give you misleading advice.

## The Solution

Flex Budget adapts to *your* income pattern. It analyzes your current month against your recent history and gives you a **confidence score** — a real-time indicator of how stable your income is — then suggests spending and savings allocations accordingly.

---

## Features

| Feature | Description |
|---|---|
| 🔢 **Multi-source income** | Log income from multiple streams in one place |
| 🎯 **Confidence Score** | Rates income stability (Stable / Variable / Irregular) based on recent trends |
| ⚠️ **Surge Warning** | Alerts you when income is unusually high, so you save before you spend |
| 🏅 **Compliance Badge** | Visual reward for staying within your safe spending limit |
| 📊 **Spending Tracker** | Log expenses by category and track them against your budget |
| 🍩 **Visual Breakdown** | Interactive donut chart showing spending by category |

---

## How the Confidence Score Works

Flex Budget compares your current income to the past 2 months:

- **Stable (75–100%)** → 70% spend / 20% save / 10% buffer
- **Variable (45–74%)** → 60% spend / 25% save / 15% buffer
- **Irregular (0–44%)** → 50% spend / 30% save / 20% buffer

The more variable your income, the more the app protects you with a larger savings buffer.

---

## Tech Stack

- **HTML5** — structure
- **CSS3** — custom design system with CSS variables
- **Vanilla JavaScript** — all logic, no frameworks
- **Chart.js** — interactive donut chart
- **localStorage** — session persistence

---

## Getting Started

No install needed. Just open the file:

```bash
git clone https://github.com/YOUR-USERNAME/flex-budget.git
cd flex-budget
open index.html   # or double-click the file
```

---

## Project Background

Built as a personal finance tool targeting a gap in budgeting apps for irregular earners. Features were scoped using a value-vs-effort framework, prioritizing behavioral impact over complexity. Early feedback informed the confidence-based logic and surge warning system.

---

## Roadmap

- [ ] Monthly history view
- [ ] CSV export
- [ ] Category spending limits
- [ ] Mobile PWA support

---

*Made for the freelancers, the hustle, and the irregular paycheck.*
