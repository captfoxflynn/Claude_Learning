# Module 1: Writing Clear, Effective Prompts

## Introduction

A prompt is just the instruction you give Claude. It can be a question, a task, or a request for something to be written or built. How you write that instruction has a huge effect on the quality of what you get back.

This matters because Claude cannot read your mind. It only has the words you give it, plus anything else you attach (files, examples, context). Vague prompts get vague answers. Specific prompts get useful ones. Learning to write good prompts is the single highest leverage skill for working with Claude, and it applies whether you're asking a quick question or kicking off a big project.

This module covers four core habits: being specific, giving examples, formatting your output requests, and iterating when the first answer isn't quite right.

## Lesson 1: Being Specific

**Explanation**

"Specific" means telling Claude the who, what, and how of what you want, not just the topic. A vague prompt forces Claude to guess your intent, your audience, and your constraints. It will guess reasonably, but a guess is still a guess. When you add specifics, you remove that guesswork.

Good specifics usually cover a few things: the audience, the length or scope, the tone, and any hard constraints (must include X, must avoid Y).

**Example**

Vague prompt:
"Write something about our return policy."

Specific prompt:
"Write a short return policy for an online clothing store. It should cover a 30 day return window, require the original tags, and explain that sale items are final sale. Keep it under 150 words and write it in plain, friendly language for customers, not legal language."

The second version gives Claude everything it needs to produce something you could use immediately, rather than something you'd have to rewrite.

## Lesson 2: Giving Examples

**Explanation**

Sometimes it's hard to describe exactly what you want in words, but easy to show it. This is called few shot prompting: giving Claude one or two examples of the input and the output you're looking for. Claude picks up on the pattern, the tone, and the structure from your examples far more reliably than from a description alone.

This is especially useful for things like matching a specific writing style, following a particular data format, or making consistent judgment calls (like categorizing items the same way each time).

**Example**

Prompt:
"Rewrite these product titles to be shorter and punchier. Here's the pattern I want:

Original: 'Men's Lightweight Running Shoes with Breathable Mesh Upper, Size 10'
Rewritten: 'Men's Lightweight Running Shoes'

Now rewrite these:
1. 'Women's Stainless Steel Water Bottle, 32oz, Leak Proof Lid, Blue'
2. 'Kids' Waterproof Rain Jacket with Hood, Ages 5-7, Yellow'"

Because you showed one full example, Claude knows exactly how much detail to strip out for the rest.

## Lesson 3: Formatting Your Output

**Explanation**

If you care about the shape of the answer, say so. Claude can produce plain paragraphs, bullet lists, numbered steps, tables, JSON, code blocks, headers, and more, but by default it will guess a reasonable format based on your request. If you have a format in mind (for a report, a spreadsheet, a script, or a specific document), state it directly.

Being clear about format upfront saves you a round trip of "actually, can you put that in a table instead."

**Example**

Prompt:
"List 5 pros and 5 cons of working from home. Present it as a two-column table with 'Pros' and 'Cons' as headers, one point per row, each point a single short sentence."

Without the formatting instruction, Claude might give you two paragraphs of prose instead. With it, you get exactly the table you can paste into a doc.

## Lesson 4: Iterating on Results

**Explanation**

Your first prompt rarely needs to be perfect, and it usually won't produce a perfect result. Treat your first message as a starting point, not a final exam. If the answer is close but not quite right, tell Claude specifically what to change, rather than starting over from scratch. Claude keeps the context of the conversation, so follow ups like "make it shorter," "use a more casual tone," or "keep the structure but replace the second example" build directly on what it already produced.

Iterating is faster and gets better results than trying to write the one perfect prompt up front.

**Example**

First prompt: "Write a welcome email for new gym members."

Claude's draft comes back a bit too formal. Instead of rewriting your whole prompt, you follow up:

"This is good, but make the tone more casual and upbeat, like a friendly trainer talking to a new member. Also add a line encouraging them to book their first free session."

Claude revises the existing draft rather than starting fresh, and you get to your final version in two short steps instead of one long, overloaded prompt.

## Try It Yourself

**Exercise 1: Add specifics**

Take this vague prompt and rewrite it to be specific. Include an audience, a length, and a tone:

"Write about the benefits of exercise."

**Exercise 2: Write a few shot prompt**

You want to turn casual meeting notes into professional action items. Write a prompt that includes one example pair (a rough note and its cleaned up action item version), then asks Claude to convert two more notes using that pattern.

**Exercise 3: Iterate on a draft**

Ask Claude (in a real conversation, if you have access) to write a two sentence product description for a reusable coffee mug. Once you get a response, write a one line follow up prompt asking it to change the tone or emphasize a different feature.

## Answer Key

**Exercise 1 (example solution)**

"Write a 150 word explanation of the benefits of regular exercise, aimed at busy adults who don't currently work out. Use an encouraging, non judgmental tone, and focus on energy and mood benefits rather than weight loss."

Any answer that adds a clear audience, length, and tone counts as correct. There's no single right wording, just make sure the vagueness is gone.

**Exercise 2 (example solution)**

"Convert these rough meeting notes into professional action items. Here's the pattern:

Note: 'sarah needs to send the deck to the client, probably by friday'
Action item: 'Sarah: Send the client deck by Friday.'

Now convert these:
1. 'someone should follow up with the vendor about pricing, no rush'
2. 'i think we agreed mike is fixing the login bug this week'"

Check that your version includes exactly one clear example pair before asking for more conversions in the same format.

**Exercise 3 (example solution)**

Initial prompt: "Write a two sentence product description for a reusable stainless steel coffee mug."

Follow up: "Make it sound more playful and mention that it keeps drinks hot for 6 hours."

The key is that the follow up references the existing draft and gives one or two specific, actionable changes rather than repeating the whole request from scratch.
