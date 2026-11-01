# Reels & TikTok Scriptwriter (for Claude Code and Claude)

Your personal scriptwriter for Reels, TikTok and Shorts - in **any language you choose**.
It writes the way a real, charismatic person talks to the camera: strong viral hooks, high retention, zero AI slop and zero templates.

Works **only with short vertical videos**. No posts, no articles.
Outputs **clean text to be spoken** - no stage directions, no square brackets.
A plain hyphen `-` is used everywhere instead of dashes.

---

## How it works

Anyone can drop this archive into **Claude Code** (or into a Claude chat).
Claude immediately understands its role and starts a quick onboarding with no extra talk.

### 0. Language selection (always the first question, in English)
> `Hi! Which language would you like to work in? (e.g. English, Українська, Polski, Español, Deutsch)`

*(You reply with any language. Claude saves it to `profile.md`, and from that moment every question, every reply and every script is in that language.)*

### 1. Quick introduction (2 steps, already in your language)
1. **Claude asks about your niche:**
   > `Tell me about your niche.`
   *(You just write your niche, e.g. "ads for e-commerce" or "real estate".)*
2. **Claude immediately asks for a chat sample (no silly marketing questions about target audience or pain points):**
   > `Now drop in an exported chat with someone (or paste a batch of your own messages) so I can pick up your speaking style.`
3. **You send the messages.**
4. **Claude silently saves your style to `profile.md` and replies with exactly one sentence:**
   > `I'm ready. Send me a Reel idea and I'll write the script in your own words.`

*(The lines above are shown in English. If you chose Ukrainian, Polish, Spanish or any other language, Claude says the same thing naturally in that language.)*

---

## What to do next

### Option A. Write a script from scratch
Just send an idea:
- *"I want a Reel about why clients disappear after hearing the price"*
- *"Write a Reel about why your Instagram videos don't take off"*

### Option B. Polish and improve your own Reel
Send your text or draft:
- *"Here's my Reel text, make it stronger: [your text]"*

Claude instantly cuts the fluff, adds an explosive hook, rewrites everything in lively spoken language and hands you a script ready to shoot.

### Changing the language later
Just say so (e.g. *"switch to English"* / *"давай українською"*). Claude updates `profile.md` and continues in the new language.

---

## Clean script format (no brackets, no directions)

```
Hook:
(the punchy first sentence)

Part 1:
(the viewer's pain, a situation they recognise)

Part 2:
(the insight or practical action, no fluff)

Ending:
(punchline + call to action)
```

*(The block labels are written in your chosen language, e.g. `Хук:` / `Частина 1:` / `Частина 2:` / `Кінець:` for Ukrainian.)*

---

## File structure
- `CLAUDE.md` - auto-loaded instructions for Claude Code.
- `SKILL.md` - instructions for Claude Skills.
- `profile.md` - your saved profile (language, niche and voice), updated automatically.
- `references/onboarding.md` - the quick onboarding algorithm (language -> niche -> voice).
- `references/hooks.md` - formulas for viral trigger hooks.
- `references/anti-slop.md` - filter for dead AI language, bureaucratic phrasing, dashes and stage directions.
- `references/human-techniques.md` - techniques of real creators and the draft-polishing algorithm.
