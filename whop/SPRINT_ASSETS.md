# WinningWeekly — Validation Sprint Assets

**Landing URL (after deploy):** https://aidia.uk/whop
**Threshold:** ≥10 waitlist signups / 48h → GO build MVP

---

## Muslih pre-flight (before broadcasting)

1. **Create Tally form** at https://tally.so → free account → "+ New form" → fields:
   - Email (required)
   - "Are you currently dropshipping?" (multiple choice: Yes, full-time / Yes, side / Starting out / Exploring)
   - "What's your biggest pain with spy tools?" (short text, optional)
2. Grab Tally form ID from URL (`tally.so/r/XXXXX` — the XXXXX part)
3. Open `/root/aidia-site/whop/index.html`, replace both `REPLACE_WITH_TALLY_FORM_ID` strings
4. `git add whop/ && git commit -m "Add /whop validation landing" && git push` → Vercel auto-deploys
5. Verify https://aidia.uk/whop loads + form opens

---

## Reddit posts (value-first, NOT spam)

**Rule:** share insight/experience, mention waitlist in 1 line at the end. Mods nuke pitchy posts. Pick the sub, read last 10 posts, mirror the tone.

### r/dropship — Post A (pain-led)

**Title:** I tracked my spy-tool usage for 30 days. 4 hours/week sifting, 0 launches.

**Body:**
> I pay for Minea ($99/mo). I spend ~4 hours/week filtering ads, bookmarking "winners," and then… not launching. Why? Because nothing is ranked. 1,200 ads match my filters. I have no idea which 5 actually matter this week.
>
> I started logging my time. Last month:
> - 17 hours sifting filters
> - 43 products bookmarked
> - 2 launched
> - 0 scaled
>
> Meanwhile the tool keeps charging. The "data" is there. The judgment isn't.
>
> I'm prototyping a fix — a weekly list of 5 ranked picks (not 500 filtered), with supplier + ad angle included. Putting up a waitlist if anyone else feels this: [aidia.uk/whop]
>
> What's your current workflow? Are you actually shipping from these tools or just bookmarking?

### r/dropship — Post B (community-led)

**Title:** Serious question: how many of you launch from Minea/Adspy picks weekly?

**Body:**
> Not trying to shit on spy tools. Just curious about ship rate.
>
> When I actually look at my launch history vs my bookmark list, the ratio is depressing. 5% of what I save ever gets tested. Most of it I never revisit.
>
> Wondering if the issue is: too much data, not enough opinion. A 1,200-ad result feed with no "these 5 matter this week" curation = analysis paralysis.
>
> Interested in what actually converts bookmark → launch for you guys. Tool? Ritual? Accountability?
>
> (Context: I'm building something in this space. Waitlist at aidia.uk/whop if it resonates, but genuinely curious first.)

### r/ecommerce — Post (tool-fatigue angle)

**Title:** Is anyone else paying for 2-3 spy tools and still guessing what to launch?

**Body:**
> Minea + Adspy + PipiAds = ~$250/mo combined for me. All showing roughly the same ads. All ending at "here's the data, good luck."
>
> The actual bottleneck isn't discovery. It's post-discovery: supplier vetting, hook writing, margin sanity-check. Spy tools ignore all of it.
>
> Am I the only one frustrated here or is this universal? If there was a $25/mo service that gave you 5 ranked picks + supplier + ad angles every Monday, would you drop the $250 stack?
>
> (Building exactly that. Waitlist at aidia.uk/whop for anyone curious — free Week 0 preview.)

### r/shopify — Post (beginner angle)

**Title:** First-time dropshippers: how are you picking products in 2026?

**Body:**
> Been talking to people starting dropship stores this year and the #1 blocker is product pick, not store setup.
>
> The advice loop is brutal: "Use Minea!" → beginner signs up → stares at 10K ads → closes tab → tries again next week → rinse/repeat.
>
> The tools are built for operators with taste already. Beginners need a starting point, not a firehose.
>
> What's working for y'all who started this year? Are you using spy tools, copying competitors, asking in Discords?
>
> (Side note: I'm waitlisting a weekly 5-pick product feed with supplier + ad angle, aimed at exactly this beginner gap — aidia.uk/whop if it sounds useful.)

---

## Twitter/X DMs (10 targets)

**Who to DM:** Indie-hacker dropshippers with 1K-20K followers who post about ad creatives, spy tools, or product research. Avoid influencer-guru types with 100K+.

**Find them:** Search "Minea" / "Adspy" / "dropship winners" — reply to anyone venting about tool UX.

### DM template A (peer-to-peer)

> Hey [name] — saw your [post/comment] about [Minea filter pain / tool sub stacking / finding winners]. Felt that.
>
> I'm prototyping something for exactly that gap: weekly 5 ranked picks with supplier + ad angles, $25/mo. AI does scan, I verify. No 500-product firehose.
>
> Not pitching — just curious if this actually solves what you posted about, or if I'm reading it wrong. Mind checking the waitlist page and telling me what's missing? aidia.uk/whop
>
> No worries if not — just valuable to hear from people who actually ship.

### DM template B (direct ask)

> [name] — quick one. How are you currently picking products to test?
>
> Reason I ask: I'm building a weekly curated list (5 winners, ranked, with supplier) at $25/mo and trying to figure out if there's real demand or if existing tools cover it.
>
> Landing at aidia.uk/whop if you want to skim — but honestly more interested in a 2-line reply about your workflow than a signup. Thanks in advance 🙏

---

## IG Story (1 frame + swipe-up)

**Frame 1 (design):**
- Dark background
- Big text: "Paying $99/mo for Minea. Launching 2 products a month."
- Small text: "Something's broken."
- Bottom: link sticker → aidia.uk/whop
- CTA sticker: "swipe up if you feel this"

**Alt caption (if lu juga post feed):**
> Tested this theory on myself for 30 days: more spy-tool data → fewer launches.
>
> Too many ads = analysis paralysis. Filters don't rank. Discovery ends where real work starts.
>
> Prototyping a fix — 5 curated picks every Monday, ranked, with supplier + ad angles. $25/mo. Waitlist: aidia.uk/whop
>
> Free Week 0 preview for founding waitlist.

---

## Tracking (update during sprint)

| Channel | Posted/Sent | Comments | DMs back | Signups |
|---|---|---|---|---|
| r/dropship Post A | | | | |
| r/dropship Post B | | | | |
| r/ecommerce | | | | |
| r/shopify | | | | |
| X DM batch (10) | | | | |
| IG story | | | | |

---

## Critical reminders

- **Don't pitch first. Ask first.** Every channel opens with their pain, not your product.
- **Value of this sprint ≠ signups alone.** Every reply/DM = pain signal for Week 0 content. Log verbatim quotes in Notion under Metrics.
- **Kill criteria locked:** <5 signups in 48h → kill Jalur A, pivot to Jalur C (AdReader). Don't extend past 48h just because emotional sunk cost.
- **If signup but zero DM replies:** means copy works but audience is passive. Different problem than "no demand." Note it.
