# Group Hold: Navi design task (Book your show)

A clickable prototype for a 48-hour design task: **Group Hold**, a way for one person to hold 4 to 8 seats for a movie while friends pay their own share.

The app uses a placeholder name ("Book your show") and no real brand assets.

## Try it
Open `index.html` in any browser. It is one self-contained file with no install. On a laptop it shows in a phone frame. On a phone it fills the screen.

Use "Reset demo (for testers)" at the bottom of Home to start over.

## The idea
- The booker picks seats, chooses a hold time (1, 2 or 3 hours) and pays a small deposit (15%, 20% or 25% of the tickets).
- A share link is created only after the deposit is paid. Friends pay only their own seat.
- The booker sees who has paid, and can nudge, mark cash, or let unpaid seats go in the last 10 minutes. Auto-pay is optional.
- If everyone books in time, the deposit counts toward the bill. If the hold ends or is cancelled, the deposit is lost.
- Cooldown: 1 hour after any hold that ends without a booking. One hold at a time.

## Prototype notes
- Friends' payment status is simulated (a random 50 to 80% of friends show as paid).
- The friend-side screens are not part of this file.
- Payments are demo only.
