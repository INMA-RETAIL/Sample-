# Doc Dr. demo

A try-it demo of Doc Dr., a receipt, invoice and estimate tool for small trades businesses.

Open `index.html` in a browser. No build step and no outside files.

## What works
- Switching between Receipt, Invoice and Estimate
- Typing in any field
- Line items with sales tax by area (Spokane County, effective 01/01/2026) and whole-cent totals
- Signature pads
- Paid in full stamp

## What does not
Print / PDF, Share PDF, Open, Import contact, Backup, Make invoice, Mark paid and business settings
open a note with an "Email Jake to unlock all features" link.

The code for those features is not in this build. Nothing is saved; reloading the page brings back
the sample. Printing from the browser prints a demo notice instead of the form. A SAMPLE mark
covers the sheet on screen.

## Change the unlock email
`UNLOCK_EMAIL` near the top of the script in `index.html`.
