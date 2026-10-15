# Exemplars: Course-Completion Posts

**Use when:** the post type is `course-completion`.

**Objective:** Turn the user's experience and takeaways from a completed
LinkedIn course into a LinkedIn post that shares one useful insight for
the post reader.

**How to use:** Study all exemplars collectively. Do not map a draft to
any single exemplar; instead, learn what to avoid from Corrections and
Revisions, and what to model from each Approved Post.

**Shared patterns:** Apply these guidelines to every course-completion post.

- The course completion is context; the user's takeaway is the post.
- Close with a one- or two-sentence recommendation or a genuine discussion question.
- No canned celebration language (e.g., "thrilled to announce"), emojis, or @mentions.
- Never generate a custom graphic, and do not offer one.

---

## Exemplar 1 -- Claude Code 101 by Anthropic

**Audience:** `peers`

### Agent's First Draft

Important: Do not imitate this copy. It shows the starting point, which required revision.

```text
I've been using Claude Code for more than a year and I still picked up something new from this course.

It's like reading a book for the second time. The first pass, it's new information. The second pass, you pick up on things you missed, because you didn't have the experience yet. It was a good refresher on best practices for managing context windows, plus how-tos for subagents, SKILL.md, MCP, and hooks.

Fundamentals are worth revisiting once you have the know-how to apply them.

Whether you're starting out with Claude Code or you've been at it a while, I'd recommend this course. It's an hour well spent.

#ClaudeCode #AI #SoftwareDevelopment
```

### Corrections and Revisions

Challenges to the user's claims and changes to the draft, in the order they happened.

1. Hook
   - Before: "I've been using Claude Code for more than a year and I still picked up something new from this course."
   - After: "I've been using Claude Code for more than a year, working with new models, capabilities, and features as they roll out--this course was a good refresher on the fundamentals."
   - Why: The hook implied a first viewing while the analogy implied a second. Lead with experience, frame the course as a refresher, and show active practice ("as they roll out") rather than exposure to change. Rejected along the way: "More than a year into using Claude Code, I still found value in going back to the basics" (passive; "going back" sounds like regressing), "with how fast it changes" and "after getting caught up in all the fast changes" (sound overwhelmed), "after spending so much time focused on the latest changes" (sounds inefficient, not proactive), "make a point of staying current" (wordy), "mastering" (overstates), and "leveraging" (corporate).

2. Analogy
   - Before: "The first pass, it's new information. The second pass, you pick up on things you missed, because you didn't have the experience yet."
   - After: "The first time, it's all new information; the second pass, you notice things you missed because now you have the experience to understand why they matter"
   - Why: "First time" echoes "second time" in the preceding sentence. "The second" alone misreads on first encounter ("the second you open the door"), so keep "the second pass." Frame experience as something gained, not lacked.

3. Topic list
   - Before: "It was a good refresher on best practices for managing context windows, plus how-tos for subagents, SKILL.md, MCP, and hooks."
   - After: "--things like context windows, subagents, and hooks." (folded into the analogy sentence)
   - Why: Three examples signal substance without turning the sentence into an inventory. Rejected along the way: a new "For me, that meant..." paragraph and a standalone "The course reinforced..." sentence (both wordy and redundant).

4. Fundamentals line
   - Before: "Fundamentals are worth revisiting once you have the know-how to apply them." (standalone paragraph)
   - After: the same sentence, moved to close the analogy paragraph
   - Why: It is the analogy's payoff, not a separate inspirational statement.

### Approved Post

Model this copy stylistically. It reflects the user's voice and approved wording.

```text
I've been using Claude Code for more than a year, working with new models, capabilities, and features as they roll out--this course was a good refresher on the fundamentals.

It's like reading a book for the second time. The first time, it's all new information; the second pass, you notice things you missed because now you have the experience to understand why they matter--things like context windows, subagents, and hooks. Fundamentals are worth revisiting once you have the know-how to apply them.

Whether you're starting out with Claude Code or you've been at it a while, I'd recommend this course. It's an hour well spent.

#ClaudeCode #AI #SoftwareDevelopment
```

---

## Exemplar 2 -- Introduction to Subagents by Anthropic

**Audience:** `peers`

### Agent's First Draft

Important: Do not imitate this copy. It shows the starting point, which required revision.

```text
Subagents are really a context-management decision.

I completed Introduction to Subagents by Anthropic, and the most useful takeaway was a simple rule: does the intermediate work matter?

If not, delegate it. Research, codebase exploration, and reviews can happen in a separate context window, keeping the main Claude Code thread focused on the information needed to move forward.

But when each step depends on what happened before--debugging, sequential workflows, or tests where the full output matters--using a subagent can actually work against you by compressing or hiding useful context.

The lesson for me: don't use subagents just because you can. Use them when isolating the work protects the context you actually need.

#ClaudeCode #AI #SoftwareDevelopment #AIAgents
```

### Corrections and Revisions

Challenges to the user's claims and changes to the draft, in the order they happened.

1. Hook
   - Before: "Subagents are really a context-management decision."
   - After: "The best reason to use a subagent isn't delegation. It's context control."
   - Why: Open with a value signal ("The best reason") that tells an interested reader this is worth reading, then land it in a short, punchy second sentence. Rejected along the way: "Subagents aren't just about delegation--they're about protecting your context window" (better, still not punchy) and "isn't specialization" (delegation is the misconception worth correcting).

2. Course mention
   - Before: "I completed Introduction to Subagents by Anthropic, and the most useful takeaway was..."
   - After: "One takeaway from this course:"
   - Why: The certificate already says the course was completed. Refer to "this course" and spend the words on the insight.

3. Mechanism
   - Before: "return only the useful result"
   - After: "return just the answer--not all the problem-solving that produced it"
   - Why: "Useful result" implies there are non-useful results. Say what is actually returned: the answer, not the process.

4. When and when not
   - Before: "Subagents work well when you need the result, but not the intermediate work--research, codebase exploration, or an independent code review. They work less well when each step depends on the last, such as debugging, sequential workflows, or tests where the full output matters."
   - After: "Use subagents when you want to keep your context window free from clutter"
   - Why: Direct, actionable phrasing beats abstraction. Compress to the plainest phrase and leave the when-not detail to the course. Rejected along the way: "when the intermediate work is disposable" (abstract) and "free from the volume of research and reasoning" (over-engineered).

5. Closing
   - Before: "My recommendation: use a subagent when you want to isolate the work; keep it in the main thread when you need to preserve the reasoning trail."
   - After: "...and check out this course to learn when--and when not--to use subagents."
   - Why: Be conversational, not authoritative. Tilt toward the course without saying "I recommend," and fold the recommendation into the actionable line. Rejected along the way: "For me, the rule is simple..." (absolute) and "If you're using Claude Code, this course is worth the time for learning when subagents help--and when keeping the work in the main thread is the better choice" (wordy).

6. Baseline knowledge
   - Before: "One takeaway from this course: every action--search, file read, tool call, etc.--consumes context."
   - After: (removed)
   - Why: Actions consuming context is baseline knowledge for this audience; calling it a takeaway makes the user look inexperienced. The takeaway is what subagents do about it, which also lets the hook flow straight into the mechanism.

7. Scope
   - Before: "keeping the main Claude Code thread focused" and "If you're using Claude Code..."
   - After: no Claude Code qualifier in the body
   - Why: The principle applies to all coding agents. Don't limit a general principle to the course's vendor.

8. Mechanism wording
   - Before: "a subagent can move that work into a separate context window and return just the answer--not all the problem-solving that produced it. Subagents isolate the 'thinking' and return only the output the main agent needs--like a function call."
   - After: "a subagent can isolate that context in a separate window and return only what the main agent needs--like a function call."
   - Why: The added sentence restated the mechanism; keep only the function-call analogy, which compresses it. "Isolate" describes separation, not relocation. "Context" reinforces the hook. "Separate window" avoids repeating "context."

9. Hashtags
   - Before: "#ClaudeCode #AIAgents #AI #SoftwareDevelopment"
   - After: "#ClaudeCode #AIAgents #SoftwareDevelopment"
   - Why: The skill caps hashtags at three; drop the most generic.

### Approved Post

Model this copy stylistically. It reflects the user's voice and approved wording.

```text
The best reason to use a subagent isn't delegation. It's context control.

One takeaway from this course: a subagent can isolate that context in a separate window and return only what the main agent needs--like a function call.

Use subagents when you want to keep your context window free from clutter, and check out this course to learn when--and when not--to use subagents.

#ClaudeCode #AIAgents #SoftwareDevelopment
```

---

## Exemplar 3 -- Claude and ChatGPT Skills Explained by Stephanie Hiewobea-Nyarko

**Audience:** `ai-users`

### Agent's First Draft

Important: Do not imitate this copy. It shows the starting point, which required revision.

```text
A skill doesn't make ChatGPT or Claude smarter. It gives them your playbook.

I build and use skills in my own AI work, and this course sharpened how I explain them. "Skill" sounds like talent, but a human skill is ability: can you build a website at all? An AI skill is closer to a standing instruction: build it this way, with these tools, every time.

The model's ability stays the same. What changes is consistency -- saved instructions, reference files, and sometimes small tools it can run, so you stop re-explaining the same task in every chat.

A good rule of thumb from the course: use a skill when a task repeats, follows a pattern, and is worth getting right.

What task do you keep re-explaining to your chatbot?

Course: https://www.linkedin.com/learning/claude-and-chatgpt-skills-explained-a-quick-guide-to-repeatable-ai-workflows/what-are-ai-skills?u=0

#AI #ChatGPT #Claude
```


### Corrections and Revisions

Challenges to the user's claims and changes to the draft, in the order they happened.

1. Claim (raised before drafting)
   - Before: "SKILL.md gives persistent context to steer the chatbot's native abilities" rather than augmenting capability.
   - After: "Chatbots can build sites on their own; the skill steers how."
   - Why: A claim about how something works is checkable. Skills can bundle scripts or tools that add capability, so scope the claim to an example that holds.

2. Hook
   - Before: "A skill doesn't make ChatGPT or Claude smarter. It gives them your playbook."
   - After: "Skills don't make chatbots smarter -- they stop you from re-explaining yourself in every chat."
   - Why: Name the reader's concrete benefit instead of a metaphor.

3. Experience line
   - Before: "I build and use skills in my own AI work, and this course sharpened how I explain them."
   - After: "I build agent skills daily, so most of this course wasn't new to me, but it still sharpened one point worth passing on."
   - Why: State practice and prior knowledge plainly. Rejected along the way: "familiar ground," "a light lift" (soft, cheesy idioms), and dropping "agent" (weakens the professional signal).

4. Pivot line
   - Before: "'Skill' sounds like talent, but..."
   - After: "'Skill' is misleading."
   - Why: A short standalone line sets up the analogy; surrounding context already implies chatbots.

5. Analogy
   - Before: "a human skill is ability: can you build a website at all? An AI skill is closer to a standing instruction: build it this way, with these tools, every time."
   - After: "A human skill is an ability -- you can build a website or you can't. An agent skill is a playbook -- build websites this way, every time."
   - Why: Parallel cadence makes the contrast land.

6. Redundant paragraph
   - Before: "The model's ability stays the same. What changes is consistency -- saved instructions, reference files, and sometimes small tools it can run, so you stop re-explaining the same task in every chat."
   - After: (removed)
   - Why: The hook and analogy already carry both points; repeating them adds nothing.

7. Rule of thumb
   - Before: "worth getting right."
   - After: "worth getting right the first time around."
   - Why: Names the payoff -- no rework.

8. Hashtags
   - Before: "#AI"
   - After: "#AgentSkills"
   - Why: Prefer a specific hashtag over a generic one. Avoid hyphens; LinkedIn hashtags break at them.

### Approved Post

Model this copy stylistically. It reflects the user's voice and approved wording.

```text
Skills don't make chatbots smarter -- they stop you from re-explaining yourself in every chat.

I build agent skills daily, so most of this course wasn't new to me, but it still sharpened one point worth passing on.

"Skill" is misleading.

A human skill is an ability -- you can build a website or you can't. An agent skill is a playbook -- build websites this way, every time. Chatbots can build sites on their own; the skill steers how.

A good rule of thumb from the course: use a skill when a task repeats, follows a pattern, and is worth getting right the first time around.

What task do you keep re-explaining to your chatbot?

Course: https://www.linkedin.com/learning/claude-and-chatgpt-skills-explained-a-quick-guide-to-repeatable-ai-workflows/what-are-ai-skills?u=0

#AgentSkills #ChatGPT #Claude
```
