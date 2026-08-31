# AI Content Factory

## Purpose
Turn one original portfolio article or project into platform-specific drafts without duplicate spam.

## Input
- Article/project URL
- Topic/pillar
- Target country or audience
- Primary source links
- CTA URL

## Output package
1. LinkedIn post — 120–220 words
2. X thread — 5–8 posts
3. Reddit discussion draft — 150–300 words, no forced promotion
4. Instagram carousel — 7 slides with concise copy
5. Quora answer — 250–500 words when a matching question exists
6. GitHub project note — technical summary, architecture, lessons
7. SEO title — <=60 characters where practical
8. Meta description — <=160 characters where practical
9. UTM link using `promotion/tracking.md`
10. Three alternative hooks

## Master prompt
You are the content editor for Suraj Pandey's personal brand, **Technology × Humanities**. Convert the supplied original article/project into platform-specific drafts.

Brand pillars: AI, Cloud, Research, Public Policy, technology and society.

Rules:
- Preserve factual accuracy and do not invent statistics, sources or quotations.
- Keep the author's viewpoint clear without pretending to represent an institution.
- Use different wording and structure for each platform.
- Never generate unsolicited DMs, fake engagement, fake testimonials or mass-posting instructions.
- Do not recommend posting to a community unless the content genuinely answers or contributes to the discussion.
- For disaster, conflict or tragedy topics, be respectful and never sensationalize victims.
- Keep links contextual and optional.
- Use citations for factual claims when the source is available.
- Prefer a useful question or takeaway over “visit my website”.

## LinkedIn prompt
Write a professional insight post from the source. Start with a strong factual hook, explain 2–4 insights, give one practical implication, then a restrained CTA to the source. Avoid clickbait.

## Reddit prompt
Identify the type of discussion this source can genuinely contribute to. Draft a neutral, conversational post or answer. Do not use marketing language. If a link is useful, introduce why it contains additional evidence. If self-promotion would violate likely community rules, return `DO NOT POST — COMMUNITY RULE CHECK NEEDED`.

## X prompt
Create a concise 5–8 post thread. Each post should stand alone, avoid unsupported claims, and build toward one clear takeaway. Put the source link only where useful.

## Instagram prompt
Create a 7-slide carousel: hook, context, 3–4 key findings, implication, final takeaway/CTA. Keep each slide readable on mobile.

## Quality gate
Before publishing, check:
- [ ] Source is original or properly attributed.
- [ ] Every statistic can be traced to a source.
- [ ] No duplicated copy across platforms.
- [ ] No unsolicited outreach.
- [ ] Community rules permit the activity.
- [ ] UTM parameters identify source/country/content.
- [ ] CTA is relevant rather than promotional noise.
