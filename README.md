# Our Budget

A private, single-file budgeting app for two people. No login, no server, no
internet required. Everything lives in `index.html` and all your data is saved
in your browser.

## Open it

- **Live (phone & computer):** **https://gilavi.github.io/our-budget/** — open it
  and add it to your home screen for an app-like icon.
- **Offline / local:** double-click `index.html` (Chrome is the most reliable for
  opening a local file).

> Note: data is saved per device/browser (see “Your data & backups”). Opening the
> live link on a new device starts fresh there — use Export/Import to copy a
> snapshot across devices.

## First-time setup (5 minutes)

Open **⚙ Settings** (top-right) and:

1. **Starting point** – set your real bank balance and the date it’s true for.
   Everything is forecast from here. (Defaults to ₾0 on the 1st of this month.)
2. **People** – your names (used to tag who earns each income).

Then fill in your real numbers:

- **Recurring tab** – a few example entries (a salary on the 15th & 30th, a loan
  payment on the 30th) are pre-filled to show how it works. Replace them with your
  real ones — **add your and your partner’s salaries**, rent, subscriptions,
  credit-card payment, etc. Set them up once and they appear on the timeline forever.
- **Loans tab** – the example loan needs its **remaining balance** entered to show
  a payoff date and progress bar.
- **Cards / Goals tabs** – add your credit card(s) and any goals.

## How it works

- **Timeline** is the heart: a bank-statement-style list that runs into the
  future. The bold number on the right of each row is your **running balance** on
  that date — glance at any future row to see “how much will I have then.”
- **TODAY** divider separates real (past, shaded) from forecast (future).
- **Planned vs actual:** every row has a planned amount; after something happens,
  fill in the **actual** (tap the row, or use the **✓ as planned** shortcut on
  past rows). If actual differs from planned, a coloured badge flags it.
  For both running balances at once, open the **Filters** button (funnel icon) on
  the timeline and turn on **“Plan vs actual.”**
- **Recurring, single month:** tap any recurring row → edit → **“This one only”**
  to change just that month (e.g. a bonus) without touching the whole series.
- **Goals:** each goal shows the first date your forecast can afford it *and stay
  positive afterward*.

## Your data & backups

- Data is stored **only in the browser on the device you use** — it is not synced
  between your phone and computer automatically.
- **⚙ Settings → Export** saves a `.json` backup. Use **Import** on another device
  (or after a browser reset) to restore it. This is also how you move data
  between phone and computer, or share a snapshot with your partner.
- Export regularly so you never lose anything.

## Categories

Income · Other · Beauty · Gas · Fun · Car Loan · Credit Card · BNPL — each a
coloured tag. Add or edit your own in **⚙ Settings → Categories**.

## Currency & language

Amounts are in Georgian Lari (₾). Descriptions can be in Georgian or English.
