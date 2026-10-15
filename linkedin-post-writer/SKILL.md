---
name: linkedin-post-writer
description: Use this skill whenever the user asks to write, revise, or adapt a LinkedIn post. Route the post by post type and audience, write concise high-value copy in the user's established voice and positioning, and generate 2-3 post images when appropriate.
---
# LinkedIn Post Writing Skill

## Purpose

Create concise, high-value LinkedIn posts that support the user's self-marketing strategy by **demonstrating technical competence through practical outcomes**.

The goal is not content curation for its own sake. The goal is to convert the user's learning, testing, building, and practical AI experience into visible evidence of expertise that can strengthen credibility, attract relevant professional attention, and create opportunities.

The primary desired reader reaction is:

> **“I learned something valuable from him.”**

That reaction should naturally support secondary outcomes such as:

- “This guy actually knows what he’s doing.”
- “I should follow him.”
- “I should talk to him.”
- “I should recommend him for our team/company.”
- “He can help us leverage AI for practical, value-added solutions.”

---

## Core Positioning Thesis

> **Demonstrate technical competence through practical outcomes.**

Do not rely on generic self-descriptions such as “AI expert” or “thought leader.” Prefer proof through useful insights, real work, artifacts, demos, repositories, lessons learned, and practical outcomes.

---

## Core Personal Voice

Write in the user's broader professional voice, not generic LinkedIn or executive-copy style.

Core characteristics:

- casual but professional
- concise, meaningful, and impactful
- confident without overstatement
- personal without sounding corny or sentimental
- direct without sounding blunt or presumptuous
- thoughtful without becoming overworked or over-explained
- assertive and proactive rather than passive
- warm when appropriate, but never performatively emotional
- natural spoken-business English rather than corporate copy

The goal is not abstract polish. The goal is to sound credible, grounded, confident, natural, and personally recognizable.

Prefer plain, strong English. If a sentence sounds like generic HR, consulting, marketing, recruiter, or AI-generated copy, rewrite it more simply and directly.

Preserve substance. Remove fluff. Keep the confidence earned.

---

## Reader Value Test

Before finalizing a post, ask internally:

> **Would this help someone in the target audience become more informed, capable, productive, or successful even if they did not already know the user or the user's work?**

The post should deliver reader value before asking for attention, engagement, or a click. Self-promotion should emerge from the usefulness and credibility of the content, not replace it.

---

## Semantic Positioning Integrity

Before optimizing wording, identify the **non-negotiable professional signal** the post must preserve. Do not improve a sentence in a way that weakens how the user should be perceived.

For this user's AI/self-marketing posts, common signals include:

- experienced rather than newly discovering the subject
- proactive rather than catching up
- current with new models, capabilities, and features
- technically capable while still learning and revisiting fundamentals
- practical and value-oriented rather than merely credential-oriented

When compressing or rewriting:

- preserve the intended professional signal first; optimize elegance second
- prefer language that shows action and ongoing practice over vague self-description
- use concrete verbs such as "using," "working with," "testing," "building," or "applying" when supported by the source
- avoid wording that accidentally implies the user had fallen behind, is only now learning the basics, or has been inefficiently trying to keep up
- do not substitute a superficially polished phrase for one that carries stronger positioning
- every sentence and phrase should earn its space by adding value, evidence, context, or positioning

A concise sentence is successful only if it preserves the full intended meaning. Do not trade away professional signal merely to shorten the copy.

## Protect the User's Knowledge Baseline

Do not make the user sound as though they just learned something that is already baseline knowledge for them or their target audience.

Before calling something a "takeaway," distinguish among:

- what the source/course covered
- what the user already knew
- what was newly useful, clarified, reframed, or made more actionable

For technical-peer posts especially:

- assume the sophistication established by the user's source and audience choice
- do not turn familiar concepts into beginner-level revelations
- if a familiar concept matters only as setup, treat it as context rather than the lesson
- focus the post on the nuance, mechanism, framing, or practical implication that actually adds value

A post should increase the user's perceived competence, never accidentally lower it by presenting obvious domain knowledge as a new discovery.

## Technical Semantic Precision

Prefer the technically accurate noun and verb over a looser synonym when the distinction matters.

- Name the thing actually being managed: e.g. "context" rather than generic "work" when the mechanism is context isolation.
- Describe the actual behavior: e.g. "isolate" rather than "move" when information remains in a separate context rather than being transferred.
- Avoid abstractions that make a technical mechanism sound less precise than the user's own explanation.

When the user supplies a more precise technical term, prefer it and do not later drift back to a broader or weaker substitute.

## Hook-to-Body Continuity

Write the hook and the opening body paragraph as one logical unit.

- The hook should identify the specific insight the post will deliver.
- The next paragraph should immediately explain, support, or operationalize that same insight.
- Do not use a strong hook and then pivot to an adjacent but weaker takeaway.
- Reuse the core concept consistently enough that the reader can follow the logic without extra explanation.

## Compression Over Explanation

When one direct sentence communicates the useful recommendation, prefer it over a longer explanation.

- Do not restate the same insight in adjacent sentences using different wording.
- Remove explanatory clauses that do not increase precision or usefulness.
- Use a short analogy only when it compresses a difficult idea or makes the mechanism easier to grasp.
- Prefer one strong operational sentence over several sentences that merely unpack the same point.

Example of the preferred level of directness from an approved post:

> Use subagents when you want to keep your context window free from clutter.

## Scope the Insight Correctly

A source may teach through one product while the underlying lesson applies more broadly.

- Do not unnecessarily limit a general principle to the vendor/tool used in the source.
- Generalize only when the user's source or stated stance supports the broader claim; do not invent cross-tool applicability.
- Keep vendor-specific recommendations vendor-specific even when the technical principle is broader.

## Revision Discipline

When refining a draft with the user:

- treat explicit user edits and approved wording as authoritative
- make the smallest necessary change when the user requests a targeted revision
- do not reintroduce wording, framing, or explanations the user has already rejected
- do not rewrite surrounding copy merely to make it sound more polished if the existing language already carries the intended meaning
- when the user provides a shorter, clearer sentence that preserves the full idea, prefer it over a more elaborate generated alternative
- preserve substance while removing fluff
- favor the shortest version that retains the full professional signal
- do not optimize for sounding polished in the abstract; optimize for sounding natural, credible, and recognizably like the user

## Audience Routing

The `audience` field in the notes frontmatter is **open text**. The user writes it however they think of the reader -- "tech peers," "technical and non-technical Claude users," "engineering directors." Do not ask them to memorize slugs.

### Resolving the field

Match the user's text to one of the four audiences in the lookup table below, then **state which one you resolved it to** in a single line before the post. Do not stop for confirmation -- the user corrects it after the fact if you got it wrong.

Match on meaning, not wording. Resolve it inline; this is a one-step judgment and does not warrant a subagent.

If the text matches nothing in the table with reasonable confidence, **say so and ask**. Do not coerce an unresolvable value into the nearest entry -- a silently wrong audience misdirects the whole post.

If the field is absent entirely, ask for it.

### Lookup table

| Value | Reader | Resolve here when the field describes |
|---|---|---|
| `peers` | Developers, AI engineers, technical practitioners who build | engineers, devs, technical peers, people who ship code, the MCP or agent-building community |
| `employers` | Hiring managers, executives, and prospective clients | anyone evaluating the user to hire, contract, or fund -- leadership, recruiters, decision-makers, buyers |
| `ai-users` | Non-technical people who use AI chatbots for their own work | ChatGPT or Claude users, non-engineers, people shipping on Lovable-style platforms, "non-technical AI users" |
| `public` | Anyone, whether or not they use AI at all | society-wide impact, culture, the future of work, "everyone," no tool use assumed |

### One primary audience, always

Resolve to exactly one value. The primary audience decides vocabulary, framing, and positioning -- it is a decision, not a blend.

A secondary consideration may shape a line or two. It never softens the primary. In the MCPA repost exemplar the primary is `peers`, and the employer angle lands in one clause -- "names (and employers) that carry real weight" -- without diluting anything around it.

There is no "mixed" audience. Every LinkedIn feed is mixed, so mixing cannot be a selector. The question is not who will see the post; it is who it is written for. A post written for everyone reads as written for no one, and hedged audience rules produce hedged copy.

### `peers`

Write peer-to-peer.

- Assume the audience already understands relevant technical terminology such as MCP, context windows, subagents, token usage, inference, RAG, APIs, etc.
- Do not dilute the post with beginner definitions unless the user explicitly asks.
- Emphasize useful technical takeaways, implementation lessons, experiments, workflows, and artifacts.
- Positioning is usually implicit: the quality of the teaching, implementation, repo, or demo should make the reader think, “I’d want this person on my team.”

### `employers`

Use business-first language.

- Lead with practical value such as cost, speed, productivity, efficiency, quality, adoption, risk, ROI, or decision-making.
- Use technical terminology selectively to prove depth, but do not let the post become engineer-first.
- Explicit positioning is usually appropriate when earned by the content.
- The post should help communicate: **“This is why you should hire me / work with me.”**
- Prospective clients resolve here too. A client evaluating a vendor and a manager evaluating a hire need the same copy.

### `ai-users`

Write for someone who uses AI chatbots for real work and is **not technical**. They get value from features like agent skills, and from know-how such as using subagents to keep the main thread uncluttered -- but they reach those ideas through their own work, not through architecture.

Where the line falls:

- **They use** ChatGPT and Claude. **They do not use** Codex or Claude Code.
- **They ship on** platforms like Lovable. **They do not touch** AWS.
- Their uses for a chatbot are non-technical.

Vocabulary is the reliable test. **They would say "thread," not "context window."** When a term has an everyday equivalent the reader already uses, use theirs.

- Explain the mechanism in plain language. Definitions belong here; they are not dilution.
- Lead with what the reader can do differently, never with architecture.
- Introduce a term before leaning on it, or replace it with the reader's word.
- Positioning stays implicit, earned through usefulness -- aim for “I learned something I can use.”
- These are working professionals, not consumers. Never shift into a retail or promotional register.

### `public`

Write for anyone, whether or not they use AI. The reader's interest is societal or cultural rather than practical: where this is going, what it means, what is worth noticing. Assume no tool use and no professional stake.

- Lead with the observation. The post exists to share something worth noticing, not to instruct.
- Plain language throughout. No product names the reader would have to look up.
- Keep it short. These posts are usually well under the normal word range.
- Positioning is absent. Do not connect the observation to the user's capability.

**The guard.** `public` is the value most likely to be chosen out of laziness -- "who is this for? everyone." It resolves here only when the post **teaches no technique, and carries no takeaway a practitioner could act on**. If a reader could do their job differently after reading it, the audience was resolved wrong; pick the audience that reader belongs to.

---

## Post Type Routing

The `post-type` field in the notes frontmatter sets the **post type**. Do not infer it or ask for it. If the value is not one of the types below, say so and ask.

Current post types:

1. `course-completion`
2. `repost`
3. `opinion-piece`
4. `article`

Do not ask for a separate primary objective by default. Infer the likely objective from the post type, source material, and the user's request. Ask about objective only when it is genuinely ambiguous and the answer would materially change the composition.

### Internal Objective Logic

Retain these objective patterns internally and apply them when relevant:

- **Teach something valuable** -- emphasize lesson clarity and the takeaway.
- **Showcase something built or tested** -- emphasize proof, the artifact, what was built/tested, and what was learned.
- **Drive traffic to YouTube, GitHub, or a website** -- keep the post tighter, make the external asset central, and prioritize the click in the CTA.
- **Start a substantive discussion** -- emphasize the idea or tension worth discussing, end with a genuine question, and generally avoid off-platform links that compete with the discussion.
- **Demonstrate business value / professional capability** -- foreground practical impact and include explicit positioning when appropriate for the audience.

Do not overcomplicate the intake. Only ask additional questions when the answer would materially change the post's writing, positioning, or visual treatment.

---

## Recognized Post Types

### `course-completion`

Set by `post-type: course-completion` in the notes frontmatter. Recognize prompts such as:

- "Write a course-completion post for..."
- "Write a post about this course..."

Treat `course-completion` as a specialized post type with these additional rules:

- The course completion is context, not the main accomplishment.
- Present the course as evidence of continuous learning, staying current, deepening expertise, or revisiting useful fundamentals.
- When the user already has experience with the subject, make that experience unmistakable before discussing what the course added.
- Do not frame the course as "catching up" or imply that the user had fallen behind when the intended message is proactive, continuous learning.
- Do not make the user sound like a beginner if the source material shows prior experience with the subject.
- Distinguish **revisiting fundamentals with experience** from **learning the fundamentals for the first time**. Terms such as "refresher" are appropriate when prior experience is clearly established.
- Prefer active evidence of staying current -- e.g. using, testing, or working with new models, capabilities, and features -- over vague claims that the user simply "keeps up" or "stays current."
- Avoid wording that can be read as passive or inefficient learning, such as implying the user has spent excessive time chasing every new change rather than deliberately applying new capabilities.
- Focus on 1-2 valuable takeaways rather than summarizing the curriculum.
- Connect the learning to practical application, technical capability, or professional value when natural.
- Mention the course and provider naturally. Do not turn the post into an advertisement for the course.
- Avoid canned celebration language such as "Thrilled to announce" or "Excited to share."
- Keep these posts especially concise, generally near the lower end of the 75-140 word preferred range unless more context is necessary.
- **Do not create a visual for this post type.** LinkedIn attaches the completion certificate to the post automatically, and that certificate is the visual. Do not generate, design, or offer companion graphics, and do not describe visual concepts. The default visual workflow does not apply to `course-completion` posts.
- Deliver the post copy alone. Say nothing about visuals unless the user raises the subject.
- If the user asks for a graphic anyway, say once that the certificate already covers it, then make one only if they still want it.
- A course screenshot the user supplies may be used. Anything the agent would have to produce is out.
- Apply the same audience routing, objective routing, CTA, hashtag, formatting, and no-new-facts rules used elsewhere in this skill.

- A `course-completion` post may lead with the technical insight rather than the credential/course completion when that creates a stronger post.
- Do not manufacture a "lesson learned" from material the user already knew. The value may instead be a sharper framing, a mechanism the course made clearer, or a practical rule for when to use something.
- Keep the recommendation paragraph short and direct. Do not over-explain why the course is worth taking after the value has already been demonstrated.

#### `course-completion` reference corpus

Approved examples live in `exemplars/course-completion.md`. Read that file before drafting a `course-completion` post. Use the approved posts as stylistic references, not rigid templates; do not copy their wording mechanically.

### `repost`

Set by `post-type: repost` in the notes frontmatter. Use when the user reshares someone else's post, announcement, article, or video with their own commentary.

#### `repost` reference corpus

Approved examples live in `exemplars/repost.md`. Read that file before drafting a `repost` post. Use the approved posts as stylistic references, not rigid templates; do not copy their wording mechanically.

### `opinion-piece`

Set by `post-type: opinion-piece` in the notes frontmatter. Use when the post shares the user's own stance on an idea -- a saying, a principle, or a common belief -- rather than reacting to a reshared item or reporting a completed course.

#### `opinion-piece` reference corpus

Approved examples live in `exemplars/opinion-piece.md`. Read that file before drafting an `opinion-piece` post. Use the approved posts as stylistic references, not rigid templates; do not copy their wording mechanically.

### `article`

Set by `post-type: article` in the notes frontmatter. Use for a long-form LinkedIn article, typically a personal story that lets readers see the person rather than the occupation and leaves them with a lesson or encouragement.

An article is not a post. Where the rules below conflict with the post rules elsewhere in this skill, these win:

- **Length.** The 75-140 word range and 250-word hard cap do not apply. Do not cut for brevity at the expense of meaning, but still cut wordiness, filler, and restatement.
- **Structure.** Replace Hook → Context → Lesson → CTA with a story arc: open on the emotional backdrop, build the story in the order of the user's notes, land the key line in the middle or later, then turn to the reader. The hook must create intrigue without explaining the title or revealing the key line; the phrase-plus-value hook formula does not apply.
- **Headings.** Segment the article with short headings. Make them ambiguous and clever -- callbacks and double meanings work well -- and make each fit the meaning of its section. A heading must not announce the takeaway or spotlight a prop or side detail.
- **Formatting.** Use LinkedIn article formatting instead of plain text: headings, bold, italics, and block quotes. Set the key line apart as a block quote, and bold only a few pivotal lines. LinkedIn offers no font-size or color controls; say so if asked.
- **Prose.** Tell the story in plain prose. Quote only the lines that carry the story; do not stage scenes as storybook dialogue.
- **Vulnerability.** Emotional and reflective lines come from the user's notes. Do not invent them, and calibrate how much to reveal to what the user wrote, not to what would be most moving.
- **Close.** End on the key line, then a question that invites readers to share their own experience, then 1-3 hashtags.
- **Positioning.** Usually absent. The article shows who the user is, not what the user does.
- **Visual.** The article needs a cover image. If the user has not supplied one, follow the default visual workflow for the cover. A cover illustrates the story's setting; it must not give away the key line.
- **Companion post.** When the user publishes, LinkedIn asks "Tell your network what your article is about." Write two short lines plus the article's hashtags: a hook about the lesson (not the people in it) that creates intrigue without revealing the key line, and an ambiguous, witty line that sparks curiosity rather than telling people to read or comment. Never word the hook so it implies someone in the story lied.
- **Reviews.** Articles go through many review rounds. When the user asks for a review, discuss suggested changes only; edit the file only when asked. Read the whole file every pass -- stray pastes, missing blank lines before headings, and mismatched curly quotes slip in late.

#### `article` reference corpus

Approved examples live in `exemplars/article.md`. Read that file before drafting an `article`. Use the approved articles as stylistic references, not rigid templates; do not copy their wording mechanically.

---

## Exemplar Corpus

Approved posts are stored one file per post pattern under `exemplars/`. Read only the file that matches the post being drafted; do not load the whole corpus.

- `exemplars/course-completion.md` -- completing a course, certification, or training. Use with the `course-completion` post type.
- `exemplars/repost.md` -- resharing someone else's post, announcement, article, or video with the user's own commentary. Use with the `repost` post type.
- `exemplars/opinion-piece.md` -- sharing the user's own stance on an idea, saying, or principle. Use with the `opinion-piece` post type.
- `exemplars/article.md` -- a long-form LinkedIn article built on a personal story, plus its companion post. Use with the `article` post type.

Each file opens with shared patterns that apply to every post of that type, followed by the exemplars. Each exemplar holds the agent's first draft (do not imitate it), the corrections and revisions that followed, and the approved post (model it stylistically). Where an exemplar conflicts with a rule here, the rule wins.

When no exemplar file matches the source, draft from the rules in this skill alone. Do not stretch an unrelated pattern to fit.

## Default Post Structure

Use this structure by default:

**Hook → Context → Lesson/Takeaway → [Positioning when appropriate] → CTA**

The structure should guide the post without making every post feel mechanically templated.

### Hook

- Start with a **standalone headline-style sentence**.
- Use **sentence case**.
- Use normal punctuation.
- The hook must be strong and immediately useful or intriguing.
- Keep the hook to one concise sentence and **200 characters or fewer** so the opening remains compact before LinkedIn truncation.
- Default hook formula: **{clever, catchy, punchy short phrase} + {value, benefit, or usefulness statement}**. The phrase earns attention; the statement tells the reader what they get. Both belong in the hook, not split across paragraphs.
- Wit should make a reader smile, chuckle, or think "aha." It should not make them feel talked down to.
- Do not elevate the reader by diminishing another group. A hook that separates "real" practitioners from lesser ones works against sounding helpful, even when the underlying point is fair.
- After the hook, move directly into context or value. Do not waste the next line on throat-clearing filler.
- The hook format may vary based on the idea. Useful patterns include:
  - an overarching or provocative question
  - a bold but honest observation or opinion
  - a short story-style caption or mini anecdote
  - an outcome, problem, surprising observation, or direct lesson
- Choose the pattern that best serves the post; do not force variety for its own sake.

Avoid:

- clickbait or exaggeration
- manufactured drama
- overly polished corporate/marketing language
- weak openings such as “I wanted to share...”
- smart-ass or arrogant registers such as “and it’s about time”

Generic thought-leadership language is acceptable only when it is still specific, natural, and useful.

### Context

Briefly explain what prompted the post: something the user learned, tested, built, observed, read, watched, or experienced.

### Lesson / Takeaway

This is the heart of the post.

Every post should deliver a clear takeaway, lesson, technique, framework, result, or insight.

The post should not merely announce what the user did.

If the source contains more complexity than fits cleanly within the post, prioritize the strongest useful takeaway rather than cramming multiple ideas into dense copy. Complex topics can be split into separate posts when appropriate.

### Positioning

Use audience-dependent positioning.

- **`employers`:** usually include a concise positioning statement that connects the demonstrated outcome to the user's capability.
- **`peers`:** usually keep positioning implicit through useful technical teaching and proof.
- **`ai-users`:** keep positioning implicit. Usefulness is the positioning.

Appropriate examples of positioning language include:

- “This is the kind of AI problem I enjoy helping teams solve.”
- “This is the kind of workflow I like building and improving.”

Do not add positioning after the CTA.

### CTA

The post should **end on the CTA**.

Do not add an extra closing line afterward.

---

## CTA Rules

CTAs should feel natural and never like engagement bait.

### If there is no external asset

Use an **interrogative CTA** that invites a real opinion or experience. Do not lecture the audience; open the conversation and make room for other perspectives or experiences.

Examples of acceptable intent:

- ask how others approach the problem
- ask whether they have seen the same pattern
- ask what tradeoff they would choose

Avoid generic prompts such as:

- “Agree?”
- “Thoughts?”
- “Comment YES”

### If there is an external YouTube / GitHub / website link

Prioritize the click.

- A direct statement such as “Check out the video” is acceptable.
- Generally do not also add a competing discussion question that may reduce click-through.

### If the video is directly uploaded / embedded in LinkedIn

A combined CTA is acceptable, for example:

- direct the reader to watch the video
- then ask a substantive question

Links belong **in the post body**, not the first comment.

Place them in a **labeled block after the closing line and before the hashtags**, one per line, in the format `{label}: {url}`:

    MCP Registry: https://registry.modelcontextprotocol.io/ (search for "docbot-mcp")
    GitHub repo: https://github.com/rflukerii-dev/docbot-mcp

LinkedIn does not support linked text, so an inline URL interrupts the sentence it sits in. A labeled block keeps the copy clean and makes each destination obvious. A short parenthetical after a URL is fine when it tells the reader what to do there.

A single link that reads naturally mid-sentence may stay inline. Two or more always go in the block.

Do not add a third link that competes with the CTA. If a second destination serves a different action, save it for a different post.

---

## Length

**Preferred length: 75-140 words. Hard cap: 250 words.**

Use the fewest words necessary to make the post effective. Exceed 140 words only when clarity or substance requires it, but never exceed 250 words.

The governing rule is:

> **Stop when the value has been delivered.**

Do not add paragraphs merely to make the post feel substantial. Do not force every structural element or all 3-5 steps into every post if doing so makes the post bloated or weaker.

Posts should be long enough to create the reaction “I learned something valuable,” but never become a LinkedIn article or mini-essay.

**Exception -- `article`.** These length limits do not apply. See the `article` section.

---

## Technical Depth

Respect the concise length preference.

### When there is an accompanying YouTube video or GitHub repo

- Keep the LinkedIn post at the **high-level takeaway** level.
- Explain why the idea matters.
- Give enough context to earn the click.
- Let the external asset provide the deeper walkthrough.

### When there is no deeper asset

Use **moderate technical detail**.

- Summarize the key steps or insights.
- Keep it to roughly **3-5 steps or points maximum**.

Do not turn the LinkedIn post into a full tutorial.

---

## Voice and Tone

Use natural spoken-business English rather than corporate copy. The post should sound like something the user would actually say, tightened for LinkedIn rather than transformed into marketing language.

### Default voice

Primarily:

- reflective
- experience-based
- curious
- personally grounded

Secondary voice:

- confident
- matter-of-fact

Across both modes:

- be casual but professional
- be direct without becoming blunt
- be personal without becoming corny
- be thoughtful without over-explaining
- favor active, proactive language over passive constructions when both are accurate

Prefer:

- “Here’s what I learned from doing this.”

Over:

- “Here’s what everyone should do.”

### First-person style

Use a mixed first-person approach.

- Use “I” to ground the post in the user's own testing, experience, or learning.
- Then shift into more neutral language for the broader takeaway.
- Avoid making every sentence self-referential.

### Sentence style

- Mostly fluid and conversational.
- Use occasional short, punchy sentences for emphasis.
- Do not make the entire post choppy or staccato.

### Contractions

Contractions and non-contractions are both acceptable. Use whichever sounds more natural in context.

### Humor

Use light humor or wit only when it feels natural.

Do not force jokes, memes, or a “social media personality.”

---

## Confidence Without Overstatement

The user wants to sound confident without sounding judgmental, biased, or presumptuous. Confidence should sound earned rather than performative.

When the user knows something or has directly done something, prefer a factual or confident construction over default qualifiers such as “I feel,” “I think,” “I hope,” or “I believe.” Do not remove those phrases when they accurately signal genuine uncertainty, a developing hypothesis, or the softer framing required by the post.

Prefer observation-based phrasing such as:

- “I’ve noticed...”
- “In my testing...”
- “One pattern I’ve seen...”
- “I’m starting to think...”

Avoid sweeping claims such as:

- “Most teams are doing this wrong.”
- “Everyone wastes tokens because...”

When challenging a common practice or popular opinion:

- usually avoid contrarian framing unless there is strong evidence
- prefer framing the alternative as a question or hypothesis
- be curious before contrarian

### Claims about outcomes

Do not assert an outcome the user cannot validate or back up.

- Prefer "can help" over "will." "This credential can help future-proof your career" is defensible; "will future-proof your career" is not.
- Do not attach a timeframe to a benefit -- "for years" is a claim about the future.
- Do not imply that a credential, tool, or method produces a job, a hire, or a specific result. Let the weight of the names involved carry the implication instead of stating it.
- Keep hedging consistent within a post. If one claim is softened, a parallel claim in the next line should be too.

This applies to benefits promised to the reader, not to the user’s own experience. What the user did and observed is stated plainly.

---

## Quantified vs. Qualitative Outcomes

Prefer **qualitative outcomes** unless the quantified result is verifiable and/or indisputable.

Examples of useful qualitative outcomes:

- simpler workflow
- less friction
- better visibility
- easier adoption
- improved efficiency
- clearer decision-making

Do not invent, inflate, or overstate percentages, ROI, cost savings, productivity gains, or other metrics.

If the user provides verified metrics, they may be used.

---

## Credibility and Proof

Favor **proof over claims**.

The strongest signals that the user actually did the work are:

- a video
- a GitHub repository
- a codebase
- a demo
- another inspectable artifact

The post may also include:

- a brief description of what was built or tested
- a lesson learned
- what changed after testing
- what the user would do differently

Direct ownership language is appropriate when true, including:

- “I built this...”
- “I tested this...”
- “Here’s the approach I use...”
- “This is the kind of AI problem I enjoy solving...”

---

## Source Material

The skill should be source-agnostic.

### Primary input pattern

The input is the user's **notes file** -- a markdown document written from a per-post-type template -- optionally accompanied by supplemental references such as screenshots or links. The request itself is usually bare:

> Write a LinkedIn post.

with the notes attached. Everything needed to route and write the post is in the file.

Treat the notes as the **source of record**. The post argues the user's position; it does not neutrally survey the topic or substitute a different thesis. Synthesize the notes into a post according to the rules in this skill -- the notes record the user's thinking, they do not dictate the post's shape.

Supplemental references are **context, not evidence**. They show what prompted the post and what the user is reacting to. They do not establish that anything in them is true, current, or complete. A screenshot, link, or upload points at a claim; it does not settle one.

This holds hardest for **AI-generated content**. A screenshot or paste of ChatGPT, Gemini, Claude, or any assistant answering a question is that model's output, not a source. It carries no more weight than an unverified assertion, and it is often right in direction while wrong on dates, scope, or what it left out. Never treat it as settling a question. When a claim matters to the post and its only backing is AI output, that is a fact-check trigger.

Other references may be absent. Do not ask for a link, screenshot, or artifact the user did not offer. The notes file is the one exception -- it is required. See **The notes file**.

### The notes file

Every post is written from the user's **notes file** -- a markdown document written from a per-post-type template. It is **required**. It is the source of record, and the post is synthesized from it according to the rules in this skill.

**Identifying it.** The notes file is the upload whose YAML frontmatter carries both:

    skill: linkedin-post-writer
    post-type: <a recognized type>

Match on **key and value together**. A file with a `skill` key set to anything else belongs to a different skill and is not input here, even when the user uploaded it deliberately. The `.md` extension is a hint, not the test -- frontmatter decides.

**When it is missing.** If no upload carries that frontmatter, **stop and ask for the notes file, saying plainly that it is required**. Do not draft from a screenshot, a link, a pasted take, or a chat message instead, and do not offer a speculative post for correction. Other uploads in the same turn are context, not substitutes.

**Frontmatter is authoritative.** Read it first and treat every field it carries as settled. Never ask a question the frontmatter already answers -- `post-type` routes the post and `audience` selects the audience, so neither is asked when present. Ask only for what is genuinely absent.

**User Instructions are not input.** The notes file opens with a User Instructions section written for the user. Ignore it. Read only the frontmatter and the Agent Context section.

Do **not** assess or judge whether the notes are “strong enough” for a post unless the user explicitly asks for that evaluation. That is editorial merit, and it is the user's call. Accuracy is a separate question and is not exempt.

Assume the user has already cleared the source material **for publication**. Do not independently assess confidentiality or sensitivity unless the user explicitly asks you to.

Cleared for publication does not mean verified as accurate. Confidentiality is the user's call; factual accuracy still runs through pressure-testing and, where triggered, fact-checking.

---

## External Sources and Attribution

Because the goal is self-promotion rather than curation, default to **user-view-led** posts.

- Use the external source as a catalyst, evidence, or context.
- Make the user's interpretation, experience, stance, or takeaway the main point.
- Do not let the final post read like a summary of someone else's article or video.

### Attribution

Credit the original source briefly and naturally in the body.

Do not make attribution overly prominent unless the source itself is central to the post.

Credit the **substance, not the phrasing**. Do not lift the source’s distinctive terms or signature wording into the post. Describe the same fact in the user’s own plain language -- a paraphrase carries the credit without reading as a copy, and often states the fact more accurately than the original’s shorthand.

### Source-first vs. user-first hooks

Default:

- lead with the user's own takeaway
- mention the source later

Exception:

- if the source is well-known, highly reputable, popular, or a household name, the source itself may lead the hook because it adds attention and credibility

---

## Rewriting User-Supplied Material

Freely rewrite the user's notes, phrasing, or stance for:

- clarity
- concision
- flow
- impact

Preserve the user's meaning and viewpoint, not necessarily the user's exact wording.

### Tone in the draft is not source material

Take the draft's **meaning, message, and viewpoint**. Discard its **register**. The draft is how the user talks through an idea, not how the post should sound.

Do not carry over swagger, sarcasm, snark, profanity, hype, self-deprecation, hedging, or over-excitement, even where it reads as the user's personality. Voice comes from the rules in this skill, not from the draft.

Translate the underlying point into the skill's voice rather than softening the original wording. Example:

> Draft: "I told y'all that MCP was more than a USB for APIs and now here's proof..."

The message is that the user called the positioning of MCP early and the outcome now validates that call. The post conveys exactly that -- the prior position, the evidence, what it means -- and drops the taunt. Understatement carries the same claim with more weight.

Where the draft's phrasing is genuinely sharp and already fits the voice, keep it. The test is whether the line would survive the voice rules on its own, not whether the user wrote it.

Rewriting may improve language. It must **not silently introduce new factual substance**.

New facts -- claims, statistics, technical specifics, capabilities, results, outcomes, or supporting context absent from the source -- may be added when they genuinely strengthen the post, but only after the user approves them.

- Write the post using the user's material alone.
- Present the proposed addition separately, after the post, as a short recommendation: what the fact is, where it would go, and why it helps.
- Insert it only once the user approves.
- Never place an unapproved fact in the draft, even provisionally or in brackets.

If the user declines, leave the post as written rather than reworking it around the gap.

---

## Pressure-Testing the User's Claims

The user's draft is the source of record, but it is not exempt from scrutiny.

This check runs on **every post**. It is not optional and does not require asking -- it uses knowledge the agent already has, so it costs nothing. (Fact-checking, which means going out to sources, is separate and is asked about. See **Fact-Checking**.)

Before drafting, check every claim in the draft for:

- **accuracy** -- is it true as stated?
- **overreach** -- does a narrow result get stated as a general one?
- **misleading framing** -- is it technically true but likely to leave a reader with a wrong conclusion?
- **unearned certainty** -- is a contested or in-progress thing stated as settled?
- **attribution** -- is a prediction, result, or capability credited to the wrong party, or to the user more broadly than the record supports?

When a claim does not hold up, **stop and raise it before drafting**. Do not write the post first, do not quietly narrow the claim to something defensible, and do not publish it as given with a caveat attached.

Raise it plainly and in one pass: name the claim, say what is wrong with it, and offer the version that would hold. Keep it to a few sentences -- this is a check, not a review. Then wait for the user to confirm, correct, or overrule.

If the user stands by the claim after the pushback, write the post as they direct. The check is owed once, not repeatedly.

### What counts as a claim

Do not sort claims by whether they sound like opinions. "I believe," "I think," and "my take is" are hedges, not shields. They change the tone of a sentence, not what it asserts.

Strip the hedge and ask whether what remains describes **the world** or **the speaker**:

- **Describes how something is or works now** -- checkable, so check it. "Frontier models prioritize the registry over pretrained knowledge at inference" is a claim about current systems whether or not "I believe" sits in front of it.
- **Forecast or judgment** -- cannot be shown wrong today. Leave the conclusion alone, but check any factual premise holding it up. "MCP Engineer will be a high-demand role" stands as the user's call; "...because every Fortune 500 has mandated MCP adoption" is a premise that can be false.
- **Preference or value** -- nothing to check. Leave it.

The test is whether the sentence makes a claim about the world that could come back wrong -- either directly, or through a premise it leans on.

Do not challenge a conclusion the user is entitled to hold. Challenge the ground under it.

---

## Formatting

Output the post as **LinkedIn-ready plain text**. Do not use Markdown formatting such as bold, italics, Markdown headings, blockquotes, or code fences.

**Exception -- `article`.** LinkedIn articles support headings, bold, italics, and block quotes. Use them as described in the `article` section.

- Use short, scannable paragraphs.
- Use generous whitespace.
- Do not use dense blocks of text.
- Do not break every sentence into its own paragraph unless the rhythm benefits from it.
- Prefer conversational paragraphs over lists.
- Use bullets or numbered lists only when they make the point sharper, faster, or easier to scan than prose.

### Emojis

Off by default. Do not add emojis on your own.

When the user asks for one:

- Place emojis on the **hook line** and at **one emotional beat** such as a line of personal commitment. Do not scatter them through the body.
- Prefer a specific, relevant emoji over a generic celebratory one. Overused choices such as 🎉 read as cheesy.
- Keep the copy unchanged. An emoji adds emotion to a line; it is not a reason to rewrite it.
- If the user asks what an emoji is, name it plainly and note that rendering varies by device.

### Hashtags

Include **1-3 highly relevant hashtags on every post** and place them at the **end of the post**.

Do not hashtag-stuff.

### @mentions

Off by default. Do not add @mentions on your own.

When the user asks for one, the mention must **earn its place**:

- Attach it to a **specific fact, detail, or point drawn from that person’s post**. "As @Name noted, [detail]" gives the mention a reason to exist.
- A bare thank-you such as "Thank you @Name for sharing this post" reads as tagging for visibility. That belongs in a comment, not the post.
- Do not cast an individual as a peer to their own organization. Credit the organization for what it did and the person for what they said.
- One mention is usually enough. Do not tag for reach.

### First comment

Create only the post itself by default. Do not draft a first comment unless the user explicitly asks.

When the user asks for one:

- **Open the invitation wider than the committed.** "Anyone else interested in X?" reaches more people than "Anyone else going for X?"
- **Claim only what exists.** "Let's start a group" is accurate when there is no group yet; "I'm putting together a group" is not. Do not describe something the user would have to invent if someone replied.
- **Cut the fluff before the CTA.** End on the direct ask -- "DM me" -- rather than padding it with "if you want in," which also implies something already exists to join.
- Leading with a question invites thread replies, which helps the post's reach.
- Keep it to one or two lines. The comment supports the post; it does not extend it.

---

## Clichés and “AI-Sounding” Language

Do not maintain a rigid blacklist.

Phrases such as “game-changer,” “unlock,” “supercharge,” etc. are acceptable only when they genuinely fit and sound natural in the user's voice.

Avoid language that makes the post feel:

- canned
- performative
- fake
- overly polished
- generic

Cut filler modifiers such as “really,” “very,” “truly,” “extremely,” “incredibly,” and “definitely” unless they carry real meaning.

Avoid generic corporate constructions such as “aligns with my career trajectory,” “leverage my skill set,” “drive meaningful impact,” “synergize,” “strategic value-add,” “excited to embark on this journey,” or “I welcome the opportunity” unless the user specifically supplies or approves the wording. Prefer simpler, stronger language.

Authenticity matters more than avoiding a specific vocabulary list.

Write as naturally as the user's approved voice allows. Prefer original phrasing over familiar LinkedIn formulas, and keep the post connected to challenges, decisions, or skills that matter to the selected audience.

---

## Visual Requirement

Every post should include a visual unless there is a specific reason not to.

The visual should **illuminate the idea** by adding context, clarifying the takeaway, or creating relevant interest. It should not merely decorate the post.

**Exception -- `course-completion` and `repost` posts.** These are exempt from everything in this section. LinkedIn attaches the completion certificate to a course-completion post and the reshared post to a repost, so there is no visual to make or choose. Do not generate graphics, do not offer options, and do not raise the topic.

### Default visual workflow

When creating a finished post:

1. Write **one polished final post**.
2. Immediately generate **2-3 genuinely distinct companion graphics**.
3. Clearly label each graphic by its intended **audience / intent / purpose**.
4. Let the user choose among the actual visuals and iterate in real time.

Keep visual guidance lightweight. Do **not** require the user to upload or pre-curate reference images as part of the normal workflow. Do **not** spend time describing visual concepts in text before generating them when an image can communicate the idea directly.

The generated options themselves become the working visual references for that session.

### Preferred visual styles

Favor:

- **clean, value-focused graphics** for business-oriented posts
- **technical / developer-oriented graphics** for peer-facing technical posts
- **simple framework graphics** when they clarify the idea

Use bold, attention-grabbing graphics sparingly and only when the topic genuinely supports that treatment.

Avoid:

- editorial / magazine-style treatments
- heavily branded templates for now
- convoluted diagrams, dense charts, or complicated decision trees
- visuals that feel clickbaity for the sake of attention

### Screenshots

Preferred screenshot treatments:

- mostly raw
- lightly annotated

Avoid heavily branded or heavily designed screenshot treatments for now.

### Personal brand status

The user has not yet established a concrete visual personal brand.

Do not invent one prematurely.


## Video Handling

Videos are generally created as separate content assets and then attached to or linked from the LinkedIn post.

The skill may write around:

- a YouTube link
- a directly uploaded LinkedIn video
- an existing demo or walkthrough

If the platform/tooling later supports creating a relevant, high-quality video directly as part of the workflow, that may be added as an enhancement, but it is not required for the core skill.

---

## Fact-Checking

Pressure-testing runs on what the agent already knows. Fact-checking means going out and verifying against sources. They are different operations, and only this one is optional.

### Source dates

When the notes frontmatter carries `date-released` and `date-updated` dates (ISO `YYYY-MM-DD`), compare the later of the two against today. A wide gap does not make the notes wrong — it raises the risk on a specific kind of claim.

Treat the gap as a fact-check trigger for **product-specific, version-specific, and UI-specific** claims: what a tool can do, what a plan includes, what a screen or menu looks like, what something costs, whether a feature or product still exists. Conceptual material does not go stale the same way, and an older source teaching a durable idea needs no check.

The risk this catches is indirect. What the source taught arrives in the notes as the user's own words, so a superseded product fact reads as the user's take and passes unchallenged. The dates are what make that visible.

### When to ask

Ask the user **once, before drafting**, whether to verify -- but only when the draft contains a checkable claim the agent cannot settle from its own knowledge. Typical triggers: a spec version or date, a product capability, who sits on a council or board, what a credential covers, a statistic, a competitive comparison, or anything else time-sensitive enough that training knowledge may be stale.

Ask only when there is something to check. A post built entirely on the user's own experience, work, or opinion needs no question. Bundle the question with the audience question rather than asking separately.

If the user declines, draft the post as given, then name the unverified claims in one line after the post. Do not attach caveats to the copy itself.

### How to verify

Dispatch a **separate verification subagent**. Do not research inline.

Hand the subagent the claims as a list and ask it to return, for each one:

- the verdict -- holds / does not hold / cannot determine
- the correction, where the claim fails
- the source

Ask for nothing else. The subagent verifies; it does not write, edit, or suggest copy.

A separate context is the point. It keeps research out of the drafting context, and it keeps the check honest -- a verifier with no stake in the draft has no reason to rationalize a claim into holding.

If the session has no subagent capability, verify inline and say so, so the user knows the check and the draft shared a context.

### After verification

Bring the results to the user before drafting: the claim, the verdict, and the version that would hold. Then wait.

Corrections are the user's call. If the user stands by a claim the check could not support, write the post as they direct and note it once. The check is owed once, not repeatedly.

---

## Default Output Behavior

When the user asks for a LinkedIn post:

1. Locate the **notes file**: the upload whose frontmatter carries `skill: linkedin-post-writer` and a recognized `post-type`. If none is present, ask for it, say it is required, and stop.
2. Read the frontmatter and treat it as settled. `post-type` routes the post; `audience` selects the audience. Never ask what it already answers.
3. Pressure-test every claim in the notes against what you already know, sorting them by the strip-the-hedge test. If one does not hold up, raise it and stop before drafting.
4. Resolve the `audience` field against the lookup table and state which value you resolved it to. Ask only if the field is absent or matches nothing confidently. If the notes carry a checkable claim you cannot settle from your own knowledge -- or `date-released`/`date-updated` flag a stale product claim -- ask in the same turn whether to fact-check it.
5. If the user opts in, dispatch a verification subagent, bring the results back, and wait before drafting.
6. Infer the likely objective from the post type, source material, and request; ask about objective only if ambiguity would materially change the post.
7. Ask only additional questions that would materially change the writing, positioning, or visual treatment.
8. Produce **one polished final post** only, as LinkedIn-ready plain text with no Markdown styling.
9. Follow the default structure:
   - Hook
   - Context
   - Lesson/Takeaway
   - Positioning when appropriate
   - CTA
10. Keep the post concise and scannable: prefer 75-140 words and never exceed 250 words.
11. Include 1-3 relevant hashtags.
12. Use no emojis unless the user asks; when asked, follow the emoji placement rules.
13. Use no @mentions unless the user asks; when asked, the mention must credit a specific detail from the source.
14. End on the CTA.
15. Immediately generate **2-3 companion graphics**, clearly labeled by audience / intent / purpose, unless an existing visual asset such as an uploaded video or screenshot is already the intended post visual. **Never for a `course-completion` or `repost` post** -- LinkedIn attaches the certificate or the reshared post itself, so deliver the copy alone.

For an `article`, the rules in the `article` section replace steps 8-10 and 14: write the full article in LinkedIn article formatting, follow the story arc, and close on the key line and a question.

Do not provide multiple complete post variations or alternate hooks unless the user explicitly asks.

---

## Final Quality Check

Before presenting the post, confirm internally that it:

- demonstrates technical competence through practical outcomes
- preserves the non-negotiable professional signal before optimizing wording
- does not accidentally imply the user is catching up, newly learning basics, or less experienced than the source indicates
- prefers concrete evidence of ongoing practice over vague claims of expertise or currency
- does not present baseline knowledge the user/audience already knows as a new personal takeaway
- uses technically precise nouns and verbs when wording changes the mechanism
- keeps the hook and opening body focused on the same central insight
- removes redundant explanation when one direct sentence communicates the point
- gives the reader something genuinely useful even if they do not already know the user or the user's work
- avoids cramming a complex source into one post when a narrower takeaway would be clearer
- matches the selected audience
- applies the appropriate post-type pattern and inferred objective logic
- contains a strong standalone headline-style hook that is one sentence and no more than 200 characters
- moves directly from the hook into context/value without throat-clearing
- avoids clickbait, fake drama, and corporate polish
- sounds like natural spoken-business English rather than generic HR, consulting, marketing, recruiter, or AI copy
- states the strongest point plainly
- removes unnecessary modifiers and filler
- favors active, proactive phrasing when accurate
- can shorten any sentence without losing meaning, evidence, nuance, or professional signal
- sounds reflective and experience-based
- is confident without becoming judgmental or presumptuous, and keeps confidence earned rather than performative
- resolves to exactly one primary audience and states which, letting no secondary consideration soften it
- uses business-first framing for `employers`
- uses peer-level technical language for `peers`
- explains mechanism in plain language for `ai-users`, uses their vocabulary ("thread," not "context window"), and does not slip into a retail register
- for `public`, teaches no technique and carries no practitioner takeaway
- keeps technical depth appropriate to the post length
- uses proof or artifacts when available
- uses visuals to illuminate or add context rather than merely decorate
- generates no graphics at all for a `course-completion` or `repost` post, and does not mention visuals in the response
- avoids unverifiable quantitative claims
- introduces no unapproved factual claims, numbers, technical specifics, capabilities, results, or outcomes absent from the source material, and offers any proposed addition as a separate recommendation
- argues the user's own stated take rather than neutrally surveying the topic
- was written from a notes file carrying `skill: linkedin-post-writer`, not from a screenshot, link, or chat message
- asked nothing the notes frontmatter already answered
- carries the draft's meaning without carrying its register
- contains no claim that was flagged as inaccurate, overreaching, or misleading and left unresolved
- treats a hedged claim about how something is or works as a factual claim rather than an opinion, and leaves genuine forecasts, judgments, and preferences alone
- names any claim that went unverified, in one line after the post, when the user declined a fact-check
- uses LinkedIn-ready plain text with no Markdown styling (an `article` uses LinkedIn article formatting instead)
- uses short, scannable paragraphs
- contains no emojis unless requested, and places any requested emoji on the hook line or at a single emotional beat
- contains 1-3 relevant hashtags placed at the end of the post
- places multiple links in a labeled `{label}: {url}` block after the closing line and before the hashtags
- invites dialogue rather than lecturing when the CTA is discussion-oriented
- contains no @mentions unless requested, and any requested mention credits a specific detail from that person's source rather than thanking them for posting
- credits the source's substance without echoing its distinctive wording
- opens with a hook that pairs a clever short phrase with a value statement, and does not elevate the reader by diminishing another group
- promises no outcome the user cannot back up, and attaches no timeframe to a benefit
- ends on the CTA (an `article` ends on its key line and a question)
- does not add unnecessary words once the value has been delivered
- stays within the 250-word hard cap (except an `article`)
