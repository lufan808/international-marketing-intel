---
name: international-marketing-intel
description: "Research an internationally recognized marketing or advertising practitioner before a meeting, focusing on recent public signals, behavioral-marketing ideas, self-versus-others contrasts, and practical conversation points. Use when the user asks to find, understand, or prepare to meet a strong international marketer."
---

# International Marketing Intel

Prepare a concise, source-backed pre-meeting brief on an international marketing practitioner. The goal is not a generic biography; it is to identify what the person is doing and saying now, how the marketing community interprets them, and what a meeting partner can say next.

## Scope and routing

Use this skill for marketers, advertising strategists, brand leaders, growth practitioners, behavioral-science experts, and marketing authors with meaningful international public activity.

- If the user names a person, research that person after resolving identity.
- If the user asks to “找一个国际营销很厉害的人” without naming one, recommend one candidate first. Prefer a person with strong recent public signals and a clear marketing specialty; state the selection rationale briefly. Good candidate categories include brand strategy, behavioral marketing, B2B growth, content-led growth, or global CMO leadership.
- If the user supplies a company, product, or meeting purpose, use it to calibrate the talking points.
- Do not turn this into a company memo, industry report, or generic list of famous marketers. Route those requests to the appropriate company or analytics workflow.

## Research workflow

### 1. Resolve identity and scope

Set a signal window of the last 90 days unless the user specifies another period. Record the exact start and end dates.

Resolve at least two identity anchors before synthesis:

- official or employer bio;
- personal site, LinkedIn, official newsletter, podcast feed, or other clearly attributable channel.

If the name is ambiguous, stop and ask the user to confirm the intended person. Do not merge similarly named people.

### 2. Collect four evidence lines

Search in parallel where possible, and sort by date rather than search relevance:

1. **Own voice** — recent essays, interviews, talks, podcasts, newsletters, official posts, product or course launches.
2. **Industry coverage** — trade press, professional associations, conference pages, publisher pages, or analyst commentary.
3. **Community reaction** — Reddit, specialist forums, public comments, or practitioner discussion. Treat this as sentiment evidence, not proof of factual claims.
4. **Baseline identity** — official bio, employer page, book publisher, TED or conference profile.

For each usable signal, capture:

- exact date and venue;
- the concrete action, claim, or idea;
- one short verbatim quote only when the source is accessible;
- how it differs from or reinforces the person’s public self-description;
- source URL and source type;
- confidence: \`HIGH ✓\`, \`BREAKING ⚠\`, or \`LOW\`.

### 3. Apply source discipline

- Only cite URLs that were actually opened successfully during research. If a site blocks access, use a verified fallback or omit the claim.
- Never invent a social-media post URL or status ID. Use the account homepage with a manual-location note when necessary.
- Keep claims tied to sources. Label inference as inference.
- Use primary sources for the person’s own words and reputable trade or professional sources for industry framing.
- Keep community criticism separate from verified facts. Do not treat a single Reddit comment as a prevailing view.
- If current public signals are sparse, say so explicitly and downgrade the brief to background intelligence.
- Keep verbatim excerpts short and within applicable copyright limits; paraphrase the rest.

### 4. Synthesize the current narrative

Identify the strongest current story in one sentence:

- What does the person want the market to believe now?
- What are they actively building, teaching, promoting, or challenging?
- Where does their own framing differ from industry or community framing?

For a marketing practitioner, look specifically for:

- the tension between brand and performance measurement;
- how they define value, attention, trust, differentiation, or customer behavior;
- whether they advocate exploration versus optimization;
- whether marketing is framed as a department, a growth lever, or an organization-wide way of thinking;
- concrete examples that reveal their working method.

### 5. Write the brief

Use the six-section structure in [references/output-template.md](references/output-template.md). Keep it readable in a 10–15 minute scan.

Required sections:

1. identity card and anchor sentence;
2. background timeline with at least three stages;
3. recent 90-day events, each with “what they said” and “how others framed it”;
4. self versus others, including meaningful contrasts;
5. depth profile and three calibrated talking points;
6. confidence, source limitations, and follow-up questions.

Talking points must be directly speakable, specific, and end with a question. They should reference a recent idea, action, or phrase and connect it to the user’s stated context. For an international subject, provide Chinese and English versions when a meeting is likely to happen in English.

### 6. Deliver the artifact

Prefer a saved Markdown artifact in the user’s workspace. If a supported Feishu document workflow is available and the user has not asked for chat-only output, create the Feishu document after the Markdown passes the checklist. If Feishu tooling is unavailable, do not block: save the full Markdown locally and say that the environment used the local fallback.

Use a title such as:

\`会前情报｜{name} @ {company or specialty}｜{YYYY-MM-DD}\`

## Quality checklist

Before finishing, verify:

- identity is unambiguous;
- the signal window and generation date are explicit;
- there are at least three dated recent signals when public evidence allows;
- every material claim has a source or is clearly labeled as inference;
- dates, amounts, percentages, and meaningful scale numbers are visually emphasized;
- every level-two heading has a semantic emoji anchor;
- comparison sections use a structured table rather than a loose bullet dump;
- talking points are concrete, bilingual when useful, and calibrated to the meeting context;
- limitations include blocked sources, missing recent signals, and any unverified community claims;
- no placeholder text remains.
