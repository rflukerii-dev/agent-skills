User: Now some updates are needed to the exemplars. Continue this thread in Cowork

Claude: I can't move this thread to Cowork, but here's a handoff to paste there:

```
Update exemplars/course-completion.md: add Exemplar 3.

Source: "Claude and ChatGPT Skills Explained" (Stephanie Hiewobea-Nyarko)
Audience: ai-users
Objective: teach; lead with the insight; correct a misconception

[paste final post here]

Traits to preserve:
- Hook pairs the misconception with the reader benefit
- States daily practice plainly ("most of this course wasn't new to me"), not "refresher"
- Parallel-cadence analogy: human skill vs. agent skill
- Scopes the capability claim to the example so it stays accurate
- Credits the course's rule of thumb in own words
- CTA echoes the hook ("re-explaining")

Rejected wording: "light lift," "familiar ground," "refresher"
Keep "agent skills" in the practice line

Pressure-test note: original take ("skills add context, not capability") overreached -- skills can bundle tools. Corrected before drafting.
```

User: No, I need this chat verbatim. Never mind, we'll update the exemplars here and I simply download the file

Claude: I added this post as **Exemplar 3**, with its traits and the pressure-test note. I also updated the shared patterns to allow a closing discussion question alongside a closing recommendation, since this post ends on a question. The file is below.

User: Now let's re-evaluate how exemplars work in general. There are two things on my mind (1) the format for each exemplar should be broken down into these sections: Original Post (by agent) | Lessons Learned (push back on user assumptions/claims or steering Claude's writing) | Approved Post (collectively by user and agent) (2) Due to the level of detail, exemplars should be broken out into separate documents. Let's work on #1 first and save #2 for later

Claude: Clear on #1. For Exemplar 3, I have everything: my first draft, each pushback and correction, and the approved post.

Exemplars 1 and 2 are the gap -- the file only holds their approved posts, not the originals or the back-and-forth behind them.

Do you have those original drafts, or should those sections be marked "not recorded"?

User: I might have them, but let's discuss my suggestions. Do you think the format is missing anything currently in the exemplars? What would we be excluding from the current exemplars? What should each of the three sections be called to be the most effective for an agent? What would you do as far as pushbacks and corrections; summarize in a paragraph; verbatim? These are questions that I have, but do not answer all in one fell swoop. Use these questions as a guide to discuss how we can improve the exemplars. Do you think my suggestions are an improvement? Why?

Claude: Yes, it's an improvement. The current format shows only the finished post, so an agent sees the target but not the gap between its default output and what you approved. That gap is the most useful signal: it shows where agents drift, like "light lift" or overreaching claims.

One risk worth designing around: an agent could imitate the original draft instead of learning from it. Section naming will matter for that.

Want to take naming next?

User: Sure

Claude: I'd name them by role, so an agent knows how to treat each one:

- **Agent First Draft -- do not imitate:** marks it as a starting point, not a model
- **Corrections:** more concrete than "Lessons Learned"; says something was fixed
- **Approved Post -- model this:** tells the agent which text to copy stylistically

The inline instructions matter most. Headers alone don't tell an agent what to do with the text.

User: I think the instruction should be on a separate line from the heading and labeled as "Note" or "Important" especially for "do not imitate. I also think the headings and instructions need to be more precise. "Agent's First Draft", "Draft Revisions". I think "Approved Post" works well—better than "Final Post". And "Do not imitate this copy; it is a reference to the starting point which ultimately required revision". And "Model this copy stylistically..."

Claude: Agreed on separate labeled lines, and "Approved Post" is the right call.

One scope issue with "Draft Revisions": this section also holds pushback on your claims, and some of that happens before any draft exists. In Exemplar 3, the "context, not capability" correction came first. "Revisions" would imply only draft edits.

**"Corrections and Revisions"** covers both. Does that work?

User: Yes

Claude: Here's the structure with notes:

**Agent's First Draft**  
Important: Do not imitate this copy. It shows the starting point, which required revision.

**Corrections and Revisions**  
Note: Pushback on claims and changes to the draft, in the order they happened.

**Approved Post**  
Note: Model this copy stylistically. It reflects the user's voice and approved wording.

Next question: how to record corrections — verbatim or summarized?

User: "Pushback" reads like a verb, not a noun. Especially following, "Note". I don't think "Note" is required for the last two sections. I'd keep "important" because it is crucial that the agent doesn't follow the draft copy

Claude: Agreed. Updated:

**Agent's First Draft**  
Important: Do not imitate this copy. It shows the starting point, which required revision.

**Corrections and Revisions**  
Challenges to the user's claims and changes to the draft, in the order they happened.

**Approved Post**  
Model this copy stylistically. It reflects the user's voice and approved wording.

User: Ok. Now be prescriptive. How should we cover the corrections and revisions

Claude: Use one short entry per correction, with three parts: **Before**, **After**, and **Why**. Quote the changed wording verbatim and keep Why to one line naming the principle. Skip the surrounding conversation.

Example:

- Before: "this course was a light lift for me"
- After: "most of this course wasn't new to me"
- Why: Idioms read as soft and cheesy; state experience plainly.

Verbatim wording shows exactly what failed. A one-line Why lets the agent generalize the lesson instead of memorizing a phrase ban.

User: Yeah, and it follows the same pattern as the document if you switched the order to Draft, Approved, Corrections. Not saying that you should change the order, just saying that the pattern is consistent

Claude: Right -- the entries mirror the document's before-to-after shape. The current order also matches how the work actually happens, so the Approved Post reads as the result of the corrections.

Next from your list: what the new format would drop. Traits to Preserve, Known Deviation, and the audience/objective header don't have a home yet. Want to tackle those?

User: Yeah. First, the Audience can stay where it is directly below the Exemplar title. Objective and visuals are not needed for a course completed post

Claude: Agreed on Visual -- it's always the certificate, so it's redundant.

I'd keep Objective, though. Your exemplars take different shapes for different reasons: Exemplar 1 leads with experience, while 2 and 3 lead with the insight. Objective tells the agent **which exemplar fits** the post it's drafting. Without it, the agent has to guess why each one looks the way it does.

Keep it, trimmed to one line?

User: Wait. First, I never wrote those objectives; they were AI generated and I didn't catch them before. If you notice, they are essentially redundant; that's because the objective applies to course completed posts overall. So I'd agree with keeping the objective, if it has a document-wide scope. The agent should not be mapping its composition to one specific exemplar—all of them should be collectively examined; the idea is that at some point, enough examples should make the agent get it right every time—if that's a misconception or inaccurate assumption, let me know. Furthermore, the corrections and revisions section, I'd expect, would cover anything an objective would convey; perhaps it would be implied where as an objective is { opposite of impled? }, but again, I think a doc-scoped objective is enough

Claude: Agreed: one document-wide objective, and the agent studies the exemplars collectively. The word you're after is **"explicit."**

One correction: more examples won't get the agent right every time. Past a handful, returns flatten, and a large set can push it toward averaging or reusing phrases. **Variety beats volume** -- exemplars that each teach a different correction do more than many similar ones.

Want to draft the document-wide objective next?

User: Good point—variety beats volume. However, not something we can control—we can't tell the agent to "get it wrong in a way that's different than before". This is definitely something to consider as new exemplars are added

Claude: Right -- you can't control the drafts, but you can control curation. When a new post arrives, add it only if its Corrections teach something the file doesn't already cover. If they repeat known lessons, skip it or swap it in for a weaker exemplar.

That rule could sit in the document header. Draft the objective next?

User: Yes. And the rule I guess if they both belong in the header

Claude: 

```
# Exemplars: Course Completion

**Use when:** the source is a completed course, certification, or
training and the post type is `course-completion`.

**Objective:** Turn a completed course into one useful insight for the
reader. The completion is context; the user's experience and the
takeaway are the post.

**How to use:** Study all exemplars together. Do not map a draft to any
single exemplar. Learn what to avoid from Corrections and Revisions,
and what to model from each Approved Post.

**Adding exemplars:** Add a post only if its Corrections and Revisions
teach something this file doesn't already cover. Otherwise, skip it or
replace a weaker exemplar.
```

User: Should we say `# Exemplars: Course-Completion Posts  
"Use when" can simply be "the post type is..."  
"Useful insight for the post reader"  
"The course completion is context..."  
"Study all exemplars collectively..."  
Adding exemplars shouldn't be in this doc; it should be in the skill

Claude: Agreed on all of it, including moving the curation rule into the skill. We'll add it there when we get to #2.

```
# Exemplars: Course-Completion Posts

**Use when:** the post type is `course-completion`.

**Objective:** Turn a completed course into one useful insight for the
post reader. The course completion is context; the user's experience
and the takeaway are the post.

**How to use:** Study all exemplars collectively. Do not map a draft to
any single exemplar. Learn what to avoid from Corrections and
Revisions, and what to model from each Approved Post.
```

User: Do not map a draft to any single exemplar; instead, learn what to avoid from Corrections and Revisions, and what to model from each Approved Post.

Claude: ```
**How to use:** Study all exemplars collectively. Do not map a draft to
any single exemplar; instead, learn what to avoid from Corrections and
Revisions, and what to model from each Approved Post.```

User: Anything else before updating the doc?

Claude: Two open items:

**Traits to Preserve** -- I'd drop it. Each Why line in Corrections and Revisions carries the same lesson, tied to real evidence.

**Known Deviation** -- Exemplar 2 has four hashtags against the three-hashtag limit. I'd simply cut one from the Approved Post rather than carry an exception.

Also, Exemplars 1 and 2 would show "Not recorded" in their first two sections until you find the drafts. Good to proceed on those terms?

User: Yes

Claude: The doc is updated below. Exemplar 3 has eight corrections, and Exemplar 2 dropped \#AI.

One flag I left alone: the first Shared Patterns bullet ("The completion is context...") now repeats the header objective. It's safe to cut.

User: How about? Turn the user's experience of completing a LinkedIn course into a LinkedIn post that shares one useful insight for the post reader. The course completion is context; the user's takeaway is the post.

Claude: Close, with two tweaks folded into one line:

**Objective:** Turn a completed course into a LinkedIn post that shares one useful insight for the post reader. The course completion is context; the user's experience and takeaway are the post.

"LinkedIn course" would exclude certifications and training from other providers. And keeping "experience" preserves the signal that you're practiced, not just learning.

User: There will only be LinkedIn courses. Re-asses

Claude: Understood. Then "LinkedIn course" is accurate:

**Objective:** Turn the user's experience of completing a LinkedIn course into a LinkedIn post that shares one useful insight for the post reader. The course completion is context; the user's experience and takeaway are the post.

My one remaining edit is adding "experience" to the last sentence, so the post signals practice, not just learning.

User: Redundant. Now what?

Claude: Fair -- your version is in. The updated doc is below.

Next up is #2: splitting exemplars into separate documents, plus adding the curation rule to the skill. Ready to start there?

User: The instruction lines needs to be labeled, or syntactically or structurally or semantically separated from the beginning of the actual post:
\---
Model this copy stylistically. It reflects the user's voice and approved wording.  
I've been using Claude Code for more than a year, working with new models,

Claude: I wrapped each post (both drafts and approved posts) in a `text` code block, so the instruction line sits outside and the copy starts cleanly inside. That's the strongest structural separation for an agent. The updated doc is below.

User: Shared patterns should be placed directly below "How to use". THoughts?

Claude: Agreed. The agent should read the rules before the examples, so the patterns frame everything that follows instead of arriving as an afterthought.

Moved. Shared Patterns now sits right after How to Use, before Exemplar 1. The updated doc is below.

User: Cut "The course completion is context; the user's takeaway is the post." from Objective and replace "The completion is context. The insight is the post" with it.  
Remove horizontal rule following "How to use".  
Format "Shared patterns..." like "How to use"

Claude: All three edits are done, and the updated doc is below. The horizontal rule now sits only between Shared Patterns and Exemplar 1.

User: It didn't refresh

Claude: The edits were saved, but the file card was likely cached. I saved a fresh copy as **course-completion-v2.md**, shown below — rename it to course-completion.md when you drop it into the skill.

User: Shared patterns should get an instruction line

Claude: Added: **"Apply these to every course-completion post."** It sits inline after the label, matching How to Use. The fresh copy, v3, is below.

User: "Apply these guidelines"

Claude: Updated to "Apply these guidelines to every course-completion post." The fresh copy, v4, is below.

User: Turn the user's experience and knowledge gained (or something like knowledge gained, it feels generic to me)

Claude: Try **"takeaways"**: specific, and it covers both sharpened framing and new insight.

"Knowledge gained" also carries a risk: it nudges the agent to frame you as learning basics, which the skill works to avoid.

**Objective:** Turn the user's experience and takeaways from a completed LinkedIn course into a LinkedIn post that shares one useful insight for the post reader.

Apply it?

User: It's redundant with shared patterns "takeaways", but it also draws a connection between the objective and the patterns. Go ahead an apply it

Claude: Applied — the objective now reads "experience and takeaways from a completed LinkedIn course." The fresh copy, v5, is below.

User: You haven't pushed back on anything. You're just making the edits I suggest. Is that what you're supposed to do?

Claude: Fair question -- no. Agreeing is right when an edit holds up, but I should be checking each one, not just applying it. And I missed something.

The shared pattern says **roughly 75-110 words**, but two of your three approved posts break it: Exemplar 2 runs 63 words, and Exemplar 3 runs 116. An agent will notice that conflict and has no way to resolve it.

I'd change it to **"roughly 60-120 words"** so the rule matches the posts you actually approved. Apply it?

User: No, we need to find a better way to state it or else we'll be adjusting every time an exemplar barely breaks the pattern

Claude: Agreed. The fix is one source of truth: drop the number here and point to the skill, which already sets the range and hard cap.

"Keep it short: stop once the insight lands. The skill's length rules set the limits."

Exemplars then show what "short" looks like without competing with the rule. Apply it?

User: Seems ambiguous. I'd drop it or come up with something better

Claude: I dropped the length bullet. The skill already sets length, including keeping course-completion posts near the low end, so the exemplar file doesn't need its own rule. The fresh copy, v6, is below.

User: So, the word count and and something else needed to go into the skill

Claude: The skill already covers length: 75-140 words preferred, with course-completion posts kept near the low end. It also already says a rule wins when an exemplar conflicts with it. So nothing new is needed there.

The "something else" is the **curation rule**: add an exemplar only if its Corrections and Revisions teach something new. That's still pending for the skill, and it fits with #2.

User: "No 'thrilled to announce'" sounds too specific with anything categorize the form of speech, impact, or something. "No emojis, no @mentions" is good—those are specific things to avoid

Claude: Name the category, with one example to anchor it -- the skill already calls this "canned celebration language":

"- No canned celebration language (e.g., "thrilled to announce"), emojis, or @mentions."

The category covers "excited to share" and its variants, while the example shows the agent what it means. Apply it?

User: Good. Now we can drop "The certificate image is the visual, attached by LinkedIn automatically." and "for these posts," and "Deliver the copy alone."

Claude: Both edits are applied, and the fresh copy, v7, is below. Dropping the certificate reason is safe, since the skill already explains why course-completion posts get no graphic.

User: "Not recorded" needs to be in a text code fence

Claude: I'd push back on this one. A fence signals "this is post copy," so an agent could read "Not recorded." as the literal draft. The Corrections sections aren't fenced either, since they hold entries, not copy.

Instead, italicize it as a status: _**Not recorded.**_ That keeps it visually distinct from copy without implying it is copy. Apply that?

User: Never mind for now. Here is the full chat verbatim for Claude Code 101. Now you can get the Agent's First Draft as well as Corrections and Revisions

Claude: The transcript covers Claude Code 101 fully, plus the start of the Subagents post (two first drafts, but not the revisions that led to its approved version).

One wrinkle for Claude Code 101: the starting copy was **your own post**, not an agent draft. ChatGPT's first rewrite came after ("More than a year into using Claude Code...").

For "Agent's First Draft," should I use ChatGPT's first rewrite, or your original with the section retitled?

User: My first post was a continuity prompt or branched

Claude: Exemplar 1 is filled in: the branched-chat text serves as the first draft, followed by four corrections. The rejected hook attempts are folded into the Hook entry's Why, so the agent sees every phrasing you turned down and the reason for each. The fresh copy, v8, is below.

The transcript also holds ChatGPT's first Subagents draft. Want me to use it for Exemplar 2's first draft, leaving its corrections as "Not recorded"?

User: I think I want you to use this one for Exemplar 2, though it may be the same

Claude: It wasn't the same chat. This one produced your approved Subagents post, so it was the right source. Exemplar 2 now has its first draft and nine corrections, and no "Not recorded" sections remain.

Two liberties in the first draft: I stripped ChatGPT's bold markup and swapped its em dashes for "\---" to match the file. The fresh copy, v9, is below.

User: Now do the same for repost.md. I know you'll need info from the original threads, but fill in whatever you can for now. Use lorem ipsum text for placeholders—that will help me spot the info that you neede

Claude: repost.md is below, in the new format with lorem ipsum wherever the original threads are needed. The main judgment calls:

- **Traits and Known Deviations** became correction entries. A new shared pattern -- no emojis or @mentions unless asked -- keeps agents from copying the deviations.
- **Modes** moved into the header, replacing the per-exemplar Objective and Visual.
- **Word counts** were dropped, matching course-completion.

One flag: Exemplar 3's first-comment entries (7-9) may describe hypothetical contrasts, not actual earlier drafts. Confirm them against the thread.

User: First, the mode should not be in the title of the exemplar. Instead, do one of two things. Either (1) make the mode meta data, below audience for each exemplar or (2) make the mode a second-level heading and each exemplar a third-level. Do you prefer one of those ideas over another? Or neither one because you have something rather different, and better?

Claude: I prefer **option 1**, metadata below Audience, for two reasons:

- It survives the upcoming split. Once each exemplar is its own document, mode headings have nothing to group, but a metadata line travels with the file.
- It matches "study all exemplars collectively." Grouping by mode nudges the agent to read only one section, and it pushes the three sections down to fourth-level headings.

Apply it?

User: Yes

Claude: Titles now name only the topic, and each exemplar has a **Mode** line below Audience. I added a blank line between the two, since back-to-back bold lines render as one line in most Markdown viewers. The fresh copy, v2, is below.

User: I think, drop the categories: "substantive commentary" and "light reaction"; the posts should not be grouped like that—I can explain if necessary. What the agent should learn is what was the first draft, approved post, what changed, and why. Then take that collective knowledge along with a screenshot of the post and the user's note about the post. The attached document is the notes we feed as context for course-completion posts; we need something similar for reposts. Thoughts?

Claude: Agreed. Dropping modes works if the notes carry what modes were doing: telling the agent **how you want to react**. The course template says "Tone doesn't matter," but for reposts it does, since a joke and an industry announcement need different handling.

So a repost template would mirror the course one, with one addition: a short **Reaction** line (e.g., "funny," "I called this," "career advice for devs"). Your take then covers meaning, and the reaction covers tone.

Want me to draft it?

User: The course notes template likely needs to be reformatted. Some of the content is instruction for the user. The purpose of this template is for the user to take notes while watching the course. "Tone doesn't matter. Meaning does" is guiding the user what to write for notes. Repost notes will likely be handled differently because the post being re-shared could be anything—not just a joke or an industry announcement. The overall point is that I need some type of "notes" context to feed the agent to write a repost; I will also include a screen shot of the post. Thoughts.

Claude: Two thoughts:

**Course template:** Mark user guidance so the agent can skip it. HTML comments (`<!-- -->`) work well: you see them while writing, they're hidden in preview, and the skill can say "ignore comments; they're prompts for the user." That also stops "Tone doesn't matter" from reading as an instruction.

**Repost notes:** Since the source can be anything, the notes should capture only what the screenshot can't: why you're sharing it, your take, and any proof or links (like your earlier post).

Want to start with the course template?

User: No. We're getting off track. I only mentioned the course-notes template because we were talking about the categories for reposts (substantive vs. light). I wanted you to understand that we will feed notes as context which could include a field such as "post-style" which could cover those categories. Understand? For now, we need to finish the repost exemplars. I'm looking for the original threads to feed the frist draft and corrections sections

Claude: Understood -- post style will come from your notes, so the exemplars don't need modes. I'll drop them now so the file is ready for your threads.

Modes are out: I removed the header line and the three Mode lines. I also reworded the ending rule to apply "when the post has a call to action," since Exemplar 2 has none. The fresh copy, v3, is below.

Send the threads when you find them, and I'll replace the lorem ipsum.

User: Here's the one for robots

Claude: Exemplar 2 is filled in: the first draft plus five corrections. Entry 3 (the "Not sure if this is real" line) is marked as your addition, since it came after the chat.

One lorem ipsum remains there: the **emoji entry's Before** line. The published version with emojis isn't in this transcript, so paste it when you find it — or I can drop that entry. The fresh copy, v4, is below.

User: Robots may not be a good exemplar. I ended up changing it later because "apparently they learned the most human response to automation" contains an opinion not a validated claim about the most-human response. These type of reposts will be one-off for me. Also, I'm not even sure I should have re-shared this particular source—I don't even know what 3.0 University is

Claude: I'd drop it. The exemplar file doesn't match what you actually published, the source is unverified, and you say these posts are one-offs. An exemplar that shows a pattern you won't repeat mostly adds noise.

One lesson is worth keeping as a shared pattern, though: **"If you can't verify the source, say so plainly, or don't reshare it."** That covers both your doubt about 3.0 University and the "not sure if this is real" move.

Drop Exemplar 2 and add that pattern?

User: Add what pattern?

Claude: This line, added to the Shared Patterns list:

"- If the source can't be verified, say so plainly in the post, or don't reshare it."

It keeps the one useful lesson from the Robots post after the exemplar is gone.

User: No. I simply won't repost unknown sources. It's not about verifying the source, it's simply that I'm unfamiliar with the source. As a matter of fact this post seems more like an ad or gimmick that real news. I don't know if that's what you meant by can't be verified

Claude: Got it -- that's a choice you make before reposting, not a writing rule, so it doesn't belong in the file. I'll just drop Exemplar 2.

Robots is out, and MCP Associate is now Exemplar 2. The fresh copy, v5, is below.

Both remaining exemplars still need their threads for the lorem ipsum sections.