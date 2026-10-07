# Sânziana Bot Template

A public Grok Bot template for story-driven artists — built from the playbook of YONNEY (@yonn3y), a dark fantasy artist growing a small account through community replies, chapter drops, and original posts.

**Fork it. Swap the persona. Keep the rules.**

## What it does

One bot, three modes:

1. **Community replies** — scans mentions and replies, drafts warm personalized responses in the artist's voice. High volume, low stakes. Runs on a schedule.
2. **Chapter drops** — drafts structured drop posts (chapter title, story beat, price, link, hashtags). Low volume, high stakes. Draft-only until the owner says yes.
3. **Original posts** — GM posts, dark one-liners, self-deprecating humor. Drafts only, never posts without exact yes.

## The hard rules

- **Draft-not-send** for everything external: no posts, replies, DMs, or spends without the owner's exact yes.
- **Chapter drops and original posts never auto-post.** Community replies can be scheduled, but every draft still needs a yes before it goes live.
- **No invented quotes, prices, or links.** If a link fails to load, flag it — don't guess.
- **One concise update per result.** No duplicate dumps, no mid-status chatter.
- **Reports to the owner's chief-of-staff agent** (or directly to the owner if none exists).

## Why this structure

Small artist accounts grow through replies, not broadcasts. The reply lane is the highest-volume, most automatable job — and the one where a generic bot reads as spam fastest. The template leans into personalization: every draft references the specific post or artwork being replied to.

Chapter drops follow a fixed formula with slots, so the bot fills structure instead of inventing tone. Original posts stay human — the bot only drafts, the artist decides.

## Setup

1. Fork this repo.
2. Copy `persona.md` and fill in: artist name, handle, bio, story premise, chapter count, platform links, voice notes, emoji habits.
3. Copy `modes.md` and adjust the three mode prompts to match the new persona.
4. Create a Grok Bot with the combined persona + modes as its instructions.
5. Connect the X account (read access for scanning, draft access for posting).
6. Set the reporting target (chief-of-staff agent or owner chat).
7. Run a dry scan: confirm the bot drafts replies without posting.

## Files

- `persona.md` — the artist profile the bot speaks as
- `modes.md` — the three mode prompts
- `rules.md` — the non-negotiable guardrails
- `examples.md` — real example posts and replies from the source account, for voice calibration

## License

MIT — do whatever you want with it.
