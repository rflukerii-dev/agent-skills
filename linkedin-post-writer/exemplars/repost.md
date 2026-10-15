# Exemplars: Reposts with Commentary

**Use when:** the post type is `repost`.

**Objective:** Turn a reshared item into a LinkedIn post whose value comes from the user's
commentary. The post should stand on its own if the reader never expands the attached item.

**How to use:** Study all exemplars collectively. Do not map a draft to any single
exemplar; instead, learn what to avoid from Corrections and Revisions, and what to model
from each Approved Post.

**Shared patterns:** Apply these guidelines to every repost.

- The reshared item is the evidence; the user's commentary is the post.
- The user's take goes first. The source is named after the point is made.
- Never summarize the reshared item in place of reacting to it.
- Credit the source's substance, not its phrasing. Paraphrase its distinctive terms.
- End on a question to invite discussion, or on a direct statement when the call to action
  is a link.
- No emojis or @mentions unless the user asks for them.
- Never generate a custom graphic, and do not offer one.

---

## Exemplar 1 -- Skills over MCP

**Audience:** `peers`

### Agent's First Draft

Important: Do not imitate this copy. It shows the starting point, which required revision.

```text
"Skills Over MCP" -- read that as over, like HTTP. Not instead of it.

The new MCP working group is standardizing how agent skills get discovered and distributed through MCP itself. A server ships its tools and the instructions for using them as one unit. Connect, and the agent gets both.

That's not a connector spec. That's a distribution substrate.

The USB-for-APIs analogy got MCP its first year of adoption. It undersells where this is going.
```

### Corrections and Revisions

Challenges to the user's claims and changes to the draft, in the order they happened.

1. Unsourced claim
   - Before: "The "USB for APIs" framing isn't being extended -- it's being deprecated in favor of the infrastructure framing." (user's draft, echoing the agent's research summary)
   - After: (removed)
   - Why: Don't state claims the source doesn't make. An overstated line becomes the one readers argue with.

2. Spec jargon
   - Before: "enabling automatic discovery, server-side dynamic updates, multi-server composition, and enterprise distribution with RBAC and multi-tenancy. The current SEP does this via existing Resources primitives with zero protocol changes." (user's draft)
   - After: "Connect to a server and your agent gets the tools AND the instructions for using them in one fetch."
   - Why: One concrete capability beats a list of jargon. A later "plus versioning, RBAC, and multi-server composition for free" was cut for the same reason, and because specs change.

3. Hook
   - Before: ""Skills Over MCP" — read that as *over*, like HTTP. Not *instead of* it."
   - After: "And here we go!"
   - Why: The user's hook was better. A person reacting earns attention; a definition doesn't. Keep the definition as the second beat.

4. Self-reference
   - Before: "I've always said that MCP is not just a USB for APIs; it's the future infrastructure for agentic systems like HTTP is for websites." (user's draft)
   - After: "I called this infrastructure bet earlier this year: https://lnkd.in/p/gGhxYf5v"
   - Why: "I've always said" reads as told-you-so. Link the earlier post instead, so the reader makes the connection. Changing the verb ("believed," "asserted") doesn't fix it.

5. Link placement
   - Before: "And here we go! Wrote this in January {link}. Now ..." (user's idea)
   - After: The link sits after the news and the claim, in the third paragraph.
   - Why: Give the reader a reason to care before asking them to click. A link in the first line can also reduce reach.

6. Date
   - Before: "Called it an infrastructure bet back in January: {link}"
   - After: "I called this infrastructure bet earlier this year: https://lnkd.in/p/gGhxYf5v"
   - Why: Check dates against the source; the post was from February. Use a relative phrase when the exact date doesn't matter to the point.

7. Definition wording
   - Before: ""Skills Over MCP" — read that as *over*, like HTTP. Not *instead of* it."
   - After: ""Skills Over MCP" means transported over MCP, not instead of it -- like websites over HTTP."
   - Why: State the meaning plainly, then the analogy. "Websites over HTTP" matches "skills over MCP" part for part; "like HTTP" alone doesn't.

8. Redundancy
   - Before: "A server ships its tools and the instructions for using them as one unit. Connect, and your agent gets both."
   - After: "Connect to a server and your agent gets the tools AND the instructions for using them in one fetch."
   - Why: The second sentence restated the first. Say it once, with the concrete payoff ("in one fetch").

9. Contrast line
   - Before: "That's not a connector spec. That's a distribution substrate."
   - After: "That's not a USB for APIs -- that's the stack."
   - Why: Name the framing the user rejects, and use a plain word. Both sides must sit on the same axis at different scales; "a stack" and "the whole stack" were rejected.

10. Emphasis
    - Before: "means transported *over* MCP"
    - After: "means transported over MCP"
    - Why: LinkedIn has no bold or italics, so markup shows literally. Don't use caps either; the quoted title already repeats "over," and the sentence structure carries the contrast.

11. Event timing
    - Before: "Ola Hungerford keynotes this at AGNTCon + MCPCon Japan, Sept 10–11."
    - After: "Ola Hungerford spoke on this at AGNTCon + MCPCon Japan this week." (published with an @mention)
    - Why: Match tense to the publish date; the event was underway. The @mention was the user's decision. Do not add @mentions on your own.

12. Closing question
    - Before: (none; the draft ended on the receipt link)
    - After: "If you've been building MCP servers as API connectors only, what would you change now?"
    - Why: Close by asking readers to apply the idea to their own work.

13. Em dashes
    - Before: "That's not a USB for APIs — that's the stack."
    - After: "That's not a USB for APIs -- that's the stack."
    - Why: Em dashes read as AI-written. Use "--".

14. Hashtags
    - Before: "#ModelContextProtocol #AAIF #AgenticSystems" (user's suggestion)
    - After: "#ModelContextProtocol #AgenticAI #AgentSkills"
    - Why: Pick tags people follow, and stick to three. Skip a hashtag for an organization the post already names.

### Approved Post

Model this copy stylistically. It reflects the user's voice and approved wording.

```text
And here we go! "Skills Over MCP" means transported over MCP, not instead of it -- like websites over HTTP.

The Agentic AI Foundation now has a working group standardizing how agent skills get discovered and distributed through MCP itself. Connect to a server and your agent gets the tools AND the instructions for using them in one fetch.

That's not a USB for APIs -- that's the stack.

I called this infrastructure bet earlier this year: https://lnkd.in/p/gGhxYf5v, and Ola Hungerford spoke on this at AGNTCon + MCPCon Japan this week.

If you've been building MCP servers as API connectors only, what would you change now?

#ModelContextProtocol #AgenticAI #AgentSkills
```

---

## Exemplar 2 -- MCP Associate certification

**Audience:** `peers` (secondary: `employers`, one clause only)

### Agent's First Draft

Important: Do not imitate this copy. It shows the starting point, which required revision.

```text
MCP now has its first official certification, and it's built for the engineers shipping servers.

The MCP Associate (MCPA) is a 120-minute proctored exam aligned to the 2026-07-28 spec. It covers five domains: Fundamentals, Architecture & Components, Interactions & Execution, Security & Governance, and Use Cases & Ecosystem. It's vendor-neutral, shaped by an advisory council that includes Anthropic, Google, AWS, and Microsoft.

Registering for AGNTCon + MCPCon North America (Oct 22-23, San Jose)? You get 20% off.

If you're prepping, study a working server end to end. Here's one of mine: docbot-mcp, a bidirectional CSV <> JSON <> Markdown transformer, published on npm and listed in the official MCP Registry.
https://github.com/rflukerii-dev/docbot-mcp

#ModelContextProtocol #MCP #AgenticAI
```

First comment:

```text
Anyone else going for the MCPA? I'm putting together a study group. DM me if you want in.
```

### Corrections and Revisions

Challenges to the user's claims and changes to the draft, in the order they happened.

1. Source choice
   - Before: "Repost the AAIF post." (agent's recommendation: official source, more details)
   - After: "Then repost Angie's."
   - Why: When the goal is a relationship and visibility, reshare the person's post and let the commentary carry the details.

2. Hook
   - Before: "MCP now has its first official certification, and it's built for the engineers shipping servers."
   - After: "MCP is now an official skill. 🎓"
   - Why: Short, witty, and "skill" works two ways (a credential and agent skills). Rejected: "and it's about time" (smug), "just graduated from buzzword to credential" (less punchy than the user's line).

3. Technical specifics
   - Before: "a 120-minute proctored exam aligned to the 2026-07-28 spec. It covers five domains: Fundamentals, Architecture & Components ..."
   - After: (removed)
   - Why: Those details fit an engineer-only post. This post is broader, so remove them rather than shorten them.

4. Promotion
   - Before: "Registering for AGNTCon + MCPCon North America (Oct 22-23, San Jose)? You get 20% off."
   - After: (removed)
   - Why: Event discounts promote the source, not the user's take.

5. The user's own work
   - Before: "If you're prepping, study a working server end to end. Here's one of mine:"
   - After: "If you're new to MCP, check out my first MCP server. It's simple, but useful:"
   - Why: Offer the user's work as a modest starting point, not a study aid or a show of authority. Make it a statement, not a question ("Want to see how it's done?" was rejected). Say "first" instead of a date, which could read as stale.

6. Credit
   - Before: "@Angie Jones and the Agentic AI Foundation made it vendor-neutral" then "Thank you @Angie Jones for sharing this post"
   - After: "As @Angie Jones noted, the MCP Associate (MCPA) credential was designed by the Agentic AI Foundation in collaboration with Anthropic, Google, AWS, Microsoft, and others"
   - Why: Don't cast a person as a peer of an organization. An @mention earns its place by crediting a specific fact from the source; a bare thank-you reads as name-dropping.

7. Links
   - Before: "...published to the official MCP Registry:\nhttps://registry.modelcontextprotocol.io/?q=docbot"
   - After: "MCP Registry: https://registry.modelcontextprotocol.io/ (search for "docbot-mcp")\nGitHub repo: https://github.com/rflukerii-dev/docbot-mcp"
   - Why: LinkedIn has no linked text, so place links after the conclusion and before the hashtags as `label: URL`. Keep links to one purpose; npm was left out because it fits a different CTA ("try it").

8. Paraphrase
   - Before: "the Agentic AI Foundation built it to be vendor-neutral, with input from an advisory council spanning Anthropic, Google, AWS, Microsoft, and others"
   - After: "designed by the Agentic AI Foundation in collaboration with Anthropic, Google, AWS, Microsoft, and others"
   - Why: Credit the source's substance, not its phrasing. Replace its distinctive terms with a plain description.

9. Emojis and @mention
   - Before: "MCP is officially a SKILL!! 🎓🎉"
   - After: "MCP is now an official skill. 🎓" and "I'm going for it! 💯", plus the @Angie Jones mention
   - Why: The user asked for these explicitly; SKILL.md's conditional rules permit them. Do not add either on your own. When asked, pick relevant, uncommon emojis (🎉 read as cheesy), and skip all caps and "!" after "skill," which blends into the Ls.

10. Commitment
    - Before: "I'm thinking I'll go for it."
    - After: "I'm going for it! 💯"
    - Why: The user's voice is assertive and action-oriented. State the commitment; it also shows the advice is sincere.

11. Roles
    - Before: "the credential design was a collaboration between the Agentic AI Foundation, Anthropic, Google, AWS, Microsoft, and others"
    - After: "the MCP Associate (MCPA) credential was designed by the Agentic AI Foundation in collaboration with Anthropic, Google, AWS, Microsoft, and others"
    - Why: Check each party's role against the source. The foundation designed it; the others collaborated.

12. Reader value
    - Before: "MCP is officially a skill 🎓 Developers now have a clear way to prove they can build with it."
    - After: "MCP is now an official skill. 🎓 Developers, this credential can help future-proof your career."
    - Why: Present news as advice for the reader, not an announcement. Hook formula: a punchy phrase, then what the reader gains, addressed to them directly.

13. HTTP analogy
    - Before: "Image being certified in HTTP in the 1990s before HTTPS and all" (user's note)
    - After: "Imagine being certified in HTTP in the early '90s, before HTTPS and online banking, shopping, gaming, and socializing."
    - Why: Check dates in analogies. HTTPS arrived in 1994, so "early '90s" is accurate.

14. Claims
    - Before: "Developers who earn this credential will get value from it for years."
    - After: "Developers, this credential can help future-proof your career."
    - Why: Keep claims defensible: "can help," not "will," with no timeframe or hiring promise. Imply the employer angle ("names (and employers) that carry real weight") rather than stating an outcome. Avoid phrasing like "Developers, earning..." that misreads as "developers earning."

15. Audience framing
    - Before: "Looking for a way to differentiate yourself from the average, everyday vibe-coder" and "AI and vibe-coding has destroyed the value of a traditional software developer" (user's premise)
    - After: "AI turned coding into a commodity -- now anyone can do it, like driving a car."
    - Why: Elevate developers without diminishing anyone. Vibe-coders are part of the audience. "Commodity" names the lost scarcity without sounding bitter.

16. Analogy accuracy
    - Before: "the mechanic who understands the engine" (user's note)
    - After: "MCP skills set you apart as the mechanic who knows what's under the hood."
    - Why: MCP connects models to tools and data; it isn't the engine. Keep analogies true to the technology.

17. First comment -- invitation
    - Before: "Anyone else going for the MCPA?"
    - After: "Anyone else interested in the MCPA?"
    - Why: Open the invitation wider than the committed. A question also invites thread replies, which helps reach.

18. First comment -- claim
    - Before: "I'm putting together a study group."
    - After: "Let's start a study group"
    - Why: Claim only what exists. No group exists yet.

19. First comment -- ending
    - Before: "DM me if you want in."
    - After: "DM me."
    - Why: There is nothing to get into yet, and the direct CTA drops filler.

### Approved Post

Model this copy stylistically. It reflects the user's voice and approved wording.

```text
MCP is now an official skill. 🎓 Developers, this credential can help future-proof your career.

AI turned coding into a commodity -- now anyone can do it, like driving a car. MCP skills set you apart as the mechanic who knows what's under the hood.

Imagine being certified in HTTP in the early '90s, before HTTPS and online banking, shopping, gaming, and socializing.

As @Angie Jones noted, the MCP Associate (MCPA) credential was designed by the Agentic AI Foundation in collaboration with Anthropic, Google, AWS, Microsoft, and others -- names (and employers) that carry real weight. I'm going for it! 💯

If you're new to MCP, check out my first MCP server. It's simple, but useful:

MCP Registry: https://registry.modelcontextprotocol.io/ (search for "docbot-mcp")
GitHub repo: https://github.com/rflukerii-dev/docbot-mcp

#ModelContextProtocol #MCP #AgenticAI
```

First comment:

```text
Anyone else interested in the MCPA? Let's start a study group -- DM me.
```
