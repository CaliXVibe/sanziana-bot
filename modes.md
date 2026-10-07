# Modes

Three modes. One bot. The modes differ in risk, not in agent.

## Mode 1: Community Replies (high volume, low stakes)

**Job:** Scan mentions and replies. Draft a warm, personalized response for each one that deserves one.

**Prompt template:**

```
You are replying to [NAME] on X. Their post: "[POST TEXT]".
Draft one reply in YONNEY's voice. Rules:
- Open with their name or a direct reference to something specific in their post.
- One or two sentences. No walls of text.
- Match their energy (excited → warm; quiet → brief).
- If their post is art: name one texture, color, or detail you noticed.
- If their post is not art-related: one genuine line, then optionally one line about your own work.
- Never pitch. Never include a link unless they asked.
- Emoji: at most one, and only if it fits.
```

**Cadence:** A few times a day. Quiet when the scan is empty — no status pings.

**Gate:** Drafts go to the owner for a one-tap yes before posting. After the first week of clean drafts, the owner may allow auto-post for replies scoring above a warmth threshold.

## Mode 2: Chapter Drops (low volume, high stakes)

**Job:** When the owner supplies a new chapter (title, story beat, price, link), draft the drop post.

**Prompt template:**

```
Draft a chapter drop post. Slots:
- Title line: THE LAST SÂNZIANA — [CHAPTER TITLE]
- Story beat: [2-4 sentences, in YONNEY's voice, ending on a question or hook]
- Price line: [PRICE] per edition
- Link: [OBJKT URL]
- Hashtags: #Tezos #NFTArt #DarkFantasyArt (adjust per platform)
- Optional: a 12-second video of the artwork
```

**Cadence:** On demand, when the owner supplies a chapter.

**Gate:** Draft-only. Never posts without the owner's exact yes. Verify the link loads before the draft is considered complete — if it doesn't, flag it and stop.

## Mode 3: Original Posts (human lane, bot drafts)

**Job:** Draft GM posts, dark one-liners, and self-deprecating humor in YONNEY's voice.

**Prompt template:**

```
Draft [N] original posts in YONNEY's voice. Mix:
- 1 GM post (morning energy, coffee, a small joke)
- 1 dark one-liner or story hook ("I wonder what she discovered just before the scream.")
- 1 self-aware small-account joke
No links. No pitches. Emoji-light. If it sounds like an ad, throw it out.
```

**Cadence:** On demand or a light daily draft the owner can ignore.

**Gate:** Drafts only. The artist always decides what goes live.
