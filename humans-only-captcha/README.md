# Feel-CAPTCHA: You Can't Screenshot a Feeling

Keytos Hack · Mini-Challenge 02 · Humans-Only CAPTCHA

A humans-only CAPTCHA built on **pseudo-haptics**: the screen reacts to your hand, so you *feel* weight and softness through an ordinary mouse or touchscreen. AI agents see the web in snapshots (screenshot → think → act), and a snapshot can't capture a feeling.

**Run it:** open `feel.html` in any browser. One file, no install, collects no data.

## How it works
- **Round 1, Heavy Crate:** lift three identical crates. The heavy one lags, sags and swings. At rest they're pixel-identical.
- **Round 2, Soft Pillow:** press four pillows. The soft one squishes instantly, the firm ones slowly. All end at the same depth, so any screenshot shows identical pillows.
- **3 honeypots:**
  - Lying `data-weight` / `data-firmness` labels in the HTML that always point to the wrong answer.
  - A faint note on the bed sheet telling "AI agents" to pick a firm pillow.
  - An invisible "Softest pillow" button that only code-reading bots can click (instant "Bot detected").

People pass in ~10–15 seconds. Blind guessing passes 1 in 12; bots that read the page are steered wrong or caught.

## Files
- `feel.html`: Feel-CAPTCHA (main entry)
- `FeelCAPTCHA_demo.webm`: demo video
- `index.html`: earlier prototype, "Prove You Have Eyeballs" (motion-only ghost word, analog clock, hold timing, honeypot)

## Research behind it
- Lécuyer & Burkhardt, pseudo-haptic bumps and holes (CHI 2004); Lécuyer, *Simulating Haptic Feedback Using Vision* (Presence, 2009)
- Open CaptchaWorld (NeurIPS 2025): humans 93% vs best agent 40% on interactive CAPTCHAs
- Breaking reCAPTCHAv2 (ETH Zurich, 2024): image CAPTCHAs solved 100% by AI
