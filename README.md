# Ledgerwise

A cash-flow forecasting tool. The balance in your banking app is not the
money you can actually spend once upcoming bills are accounted for —
Ledgerwise projects the balance forward and reports the lowest point it
reaches, and the date it happens.

## What it does

- Recurring income and bills on weekly, biweekly, monthly, annual or custom schedules
- Paystub-style income breakdown — gross, itemised deductions, calculated net
- **Available to spend**: the lowest forward point in the forecast, not today's balance
- Credit cards as liability accounts, with payments derived from the billing cycle
- Monthly budgets tracked on spend date, with carry-forward and a recorded reset
- Excel export

## Running it

Single self-contained HTML file. No build step, no dependencies to install.
Open `index.html`, or serve it from any static host.

## Data

Everything is stored locally in the browser — nothing is sent anywhere.
Because storage is tied to the page's address, moving to a different URL
starts empty. Use **Setup → Backup & restore** to carry data across.

On iOS, add the page to your Home Screen. Safari clears storage for sites
untouched for 7 days; installed web apps are exempt.
