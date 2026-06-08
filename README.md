# Interim Rental Calculator

A self-contained web calculator for Paymentsave interim rental charges.

## What it does
Enter a start date, end date and the monthly rental amount. It computes:
- a daily rate = monthly rental ÷ number of days in the **end-date's** month (handles 28/29/30/31),
- interim rental = daily rate × the number of days between the two dates,
- plus 20% VAT, giving the total inc. VAT.

## How to publish (GitHub Pages)
1. Create a new **public** repository on GitHub.
2. Upload `index.html` (and this README).
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, Save.
4. After ~1 minute your link appears: `https://<your-username>.github.io/<repo-name>/`

## Notes
- Everything (logo, styles, logic) is embedded in `index.html` — no internet or server needed to run it.
- Developed by the Finance Team.
