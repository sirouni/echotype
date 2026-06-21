# Reddit Posts

---

## Post 1: r/typing

**Title:** I built a typing trainer that haunts you with your own mistakes

**Body:**

I've been using MonkeyType for a year. I got my WPM from 55 to 72, then completely plateaued. The problem? MonkeyType tells you how fast you are, but not WHY you're stuck.

So I built EchoType. It tracks every single error you make — not just "you got this word wrong", but:
- Which specific key pairs slow you down (e.g., "th" takes you 180ms but "qu" takes 420ms)
- Which substitutions you make repeatedly (typing "r" instead of "t")
- Where in a word you mess up (beginning vs end)

Then it generates text loaded with YOUR specific weak patterns. It's like a personal coach that only makes you practice what you're bad at.

After 2 weeks of using it myself, my weak bigrams improved by ~30%. Not because I'm special — because I was finally practicing the right things.

It's free, runs in your browser, no account needed: [link]

Would love feedback from this community. What would make this more useful for your practice?

---

## Post 2: r/learnprogramming

**Title:** I made a free typing trainer specifically for programmers — it adapts to your weak spots

**Body:**

As a programmer, I type all day but never really "trained" my typing. I used MonkeyType for speed tests but it didn't help me actually improve.

So I built EchoType — a typing practice tool that:
1. Tracks which key combinations slow you down
2. Generates practice text targeting your specific weaknesses
3. Has a "Custom Text" mode where you paste your own code to practice on

The corpus includes programming-specific sentences like "deploy the application to the staging server" and "the function returns a boolean value" — not just generic English.

It also has a unique "Flow Score" (0-100) that combines speed + accuracy + consistency into one number. More useful than raw WPM because it rewards clean typing, not just fast typing.

Free, browser-based, no signup: [link]

Built it in a weekend. What features would you want for programming-specific typing practice?

---

## Post 3: r/mechanicalkeyboards

**Title:** Built a typing trainer with a keyboard heatmap that shows exactly which keys you fumble

**Body:**

[Screenshot of keyboard heatmap]

I made a typing practice tool that gives you a real-time heatmap of your error-prone keys. The redder the key, the more you mess it up.

But the cool part: it doesn't just show you the data — it then generates practice text that's loaded with your worst key combinations. So if your right pinky is weak (p, semicolons, brackets), you'll get text heavy on those characters.

It also generates a unique "Typing DNA" fingerprint visualization based on your error patterns. Everyone's looks different.

Free, no account, works in any browser: [link]

Would love to see what your error heatmaps look like after a few rounds.

---

## Post 4: r/SideProject

**Title:** EchoType — adaptive typing trainer that learns your weaknesses (free, no backend)

**Body:**

**What it does:** A typing practice tool where your mistakes become your future challenges. It builds a model of your typing errors and generates text targeting your weak patterns.

**Tech stack:** Pure HTML/CSS/JS, hosted on Cloudflare Pages, zero backend. User data stays in localStorage. 2000+ sentence corpus with pre-computed bigram indexing for fast adaptive text selection.

**Differentiator vs MonkeyType/Keybr:** MonkeyType = speed test (measures). Keybr = uses fake words (not transferable). EchoType = uses real sentences adaptively selected for YOUR weaknesses.

**Metrics so far:** Just launched, looking for first users and feedback.

**Business model:** Free tier with core features. Planning Pro tier ($5/mo) for advanced analytics, custom text import, and data export. Validating demand first.

Link: [link]

---

## Post 5: r/InternetIsBeautiful

**Title:** EchoType — a typing trainer that generates a unique "DNA fingerprint" of your typing patterns

**Body:**

EchoType analyzes your typing at the character level and generates a radar-chart "fingerprint" that's unique to you — showing which keys you're strong/weak on, what character pairs slow you down, and where in words you tend to make mistakes.

Then it uses that fingerprint to generate practice text that specifically targets your weak areas.

It's free and runs entirely in your browser: [link]
