# worst-cancel-page
ClingStream+ — The Worst Cancel Screen Ever
Keytos Hack · Mini-Challenge 01 entry.

A cancellation flow for ClingStream+, a made-up streaming service, built to be as hostile and confusing as possible while staying possible to escape. Every trick is logged live in a Dark Pattern Dex side panel (24 patterns).

Run it: download and open cancel-form.html in any browser. No install, no build, no server. One self-contained HTML file.

The flow
Account page. Upgrading is one click. The only way to cancel is a tiny 9px grey "cancellation policy" link next to the big buttons.
Cancel options. A big green "Keep my membership" button, a pre-ticked Platinum upgrade box that blocks you until you untick it, and a "Don't not keep my membership" button (which keeps you).
Pay-to-leave. "Express Cancellation: Pay $200 & skip the form." Checkout shows $300 after drip fees and a pre-ticked trial. Every payment method is fake, and payment is always declined, sending you to the free form. No real payment fields exist.
Unskippable ads. Ad breaks between form parts. "Skip Ad" upsells you and restarts the countdown, the ad pauses whenever you look away, and "Ad 1 of 1" becomes "Ad 2 of 2".
The never-ending form (4 parts). Every field is required, with minimum-length essays ("Describe the moment you fell in love with ClingStream+", "Explain why it's our fault and not yours"), an apology to Mochi that must include "sorry", a 1–10 scale where anything below 8 is "for Platinum members", and a security question (Mochi's middle name) answerable only by reading the Terms of Service.
Legal part. A trap checkbox that keeps your subscription, an oath you must type by hand (paste blocked) while fake autocorrect turns "leaving" into "staying", and a mouse-drawn signature that must be "long enough".
Ending. "Received! Processing time: 6–8 business weeks", unless you find the tiny "process my cancellation now" link. Then the subscription is cancelled, with a scorecard of time, ads endured and patterns survived.
Also: vague errors on the first failed submit, a part counter and "time remaining" that grow as you go, and a fake "your session will expire" scare.

How to escape (spoilers)
Account page: click the tiny cancellation policy link beside "Manage plan".
Untick the Platinum box before choosing a cancel option.
Mochi's middle name: Aurelius (clause 7 of the Terms).
In the oath, when a word gets "autocorrected", press Backspace once to undo it.
Presenter shortcut: press ] (outside a text box) to finish an ad or fill the current form part.
Files
cancel-form.html: the main entry.
index.html: first draft ("Cancel Quest"), a game-styled version with a runaway button, a phone menu (mash 0 to reach a human) and stacked "Are you sure?" dialogs.
Everything is fictional: no real accounts, payments or personal data.
