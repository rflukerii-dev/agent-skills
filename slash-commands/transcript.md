---
description: Export a verbatim transcript of this thread, ignoring all attachments
---

If `$ARGUMENTS` is non-empty, use it as the slug. If it is empty, ask the
user whether to specify a slug or let you infer one from the conversation
topic, and wait for their answer before writing.

The slug must be kebab-case. If it is not, convert it and state the
converted value before writing.

Write this entire conversation verbatim to `transcript--<slug>.md`,
formatted as "User: {prompt}\n\nClaude: {response}" for every turn in order.
Do not summarize, condense, sanitize, or clean up wording.

Exclude files uploaded as prompt-context by the user and files output as
response-artifacts by Claude--do not reference either.