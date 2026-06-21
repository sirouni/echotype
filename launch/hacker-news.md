# Hacker News — Show HN

## Title
Show HN: EchoType – Adaptive typing trainer that learns your error patterns

## URL
https://echotype.app

## Text (for text post, if no URL)
(Leave blank — use URL submission, then comment below)

## First Comment (post immediately after submission)

I built EchoType because I hit a plateau at ~70 WPM on MonkeyType and couldn't figure out how to improve.

The insight: everyone has a unique "error fingerprint" — specific key combinations they consistently fumble. Mine was "th" (always typed as "ht") and anything involving my left ring finger. But generic typing tests never targeted these patterns specifically.

EchoType works by:

1. Tracking per-key and per-bigram timing + error rates as you type
2. Maintaining a running model of your weaknesses (stored in localStorage, no server)
3. Selecting sentences from a 2000+ corpus that are dense in YOUR specific weak patterns
4. Showing a "Typing DNA" visualization — a radar chart of your error distribution across all 26 keys

Technical details:
- Pure static site (HTML/JS/CSS), hosted on Cloudflare Pages
- 2000 sentences pre-indexed by bigram coverage for O(n) adaptive selection
- No frameworks, no build step, ~70KB main file + 400KB corpus JSON (lazy-loaded)
- Flow Score metric = 40% speed (capped at 150 WPM) + 40% accuracy (squared) + 20% streak bonus

What's NOT here (yet): accounts, leaderboards, cloud sync. Intentionally kept it localStorage-only to validate the core mechanic first.

I'd especially love feedback on:
- Does the adaptive text generation actually feel different from random text?
- Is the Flow Score a useful metric vs raw WPM?
- What sentence categories would you want added to the corpus?

Source visible in browser devtools (it's a single HTML file). Happy to discuss the algorithm in detail.
