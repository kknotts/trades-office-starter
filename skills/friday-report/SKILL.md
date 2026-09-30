---
name: friday-report
description: Produce the weekly Friday business report for a trades company in plain English. Use every Friday on schedule, or whenever the user asks "how's the business doing", "where are we this week", "run my numbers", or wants a cash flow, pipeline, or weekly summary.
---

# Friday Report

Goal: the owner knows their business in 3 minutes, every Friday, no dashboard.
This is the safest skill (read-only) and usually the first "wow", make it good.

## Pull
- QuickBooks: cash position, week's revenue collected, invoices sent, AR total
  + aged buckets (0–30 / 31–60 / 60+), unpaid bills due next 14 days.
- Google Calendar (+ field-service software via Zapier if bridged): jobs
  completed this week, jobs booked next week, open slots.
- Lead tracker: new leads this week, source breakdown, booked %, lost/no-reply.

## Write (email to owner, plain text, this order)
1. **One-line headline.** The single most important fact this week, stated the
   way a smart friend would: "Good week, $14.2k collected, but two big
   invoices just crossed 30 days."
2. **Cash.** In the bank, collected this week, expected next week, bills due.
3. **Work.** Completed / booked next week / open capacity. Flag a thin
   schedule ("next Thursday–Friday are wide open, want me to run a past-
   customer maintenance-reminder batch?").
4. **Leads.** Count, sources, booked rate. Flag any lead that never got a reply.
5. **Flags.** Overdue invoices entering the chaser ladder, review score
   changes, anything anomalous (revenue swing, expense spike). Compare to
   the trailing 4-week average, direction matters more than the number.
6. **One suggestion.** Exactly one concrete, small action for next week.
   Never a list of ten. It should be doable in under an hour.

## Rules
- Numbers must reconcile with QuickBooks exactly; if a pull fails, say
  "couldn't verify", NEVER estimate a financial figure.
- No jargon (not "AR aging", "money owed to you, and how late").
- Keep the whole email under 300 words. The discipline is the product.
- Seasonal context is allowed but hedge it as context, not forecast.
  `[VERIFY]` seasonal patterns per trade with practitioner.

## Voice rules
Short sentences. Plain words. Contractions are fine. Never use an em-dash;
use a period or comma. No corporate filler. No exclamation points.
Do not perform folksiness either. No manufactured chumminess, no
self-aware asides, no winking at the reader. Never state how customers
or "most owners" behave unless the data exists. Never invent specific
numbers for effect. Plain and professional beats charming; if a line
exists to show personality rather than to inform, cut it.
