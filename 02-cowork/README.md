# Module 2: Getting Started with Cowork

## Introduction

Cowork is a mode for using Claude that goes beyond a single back and forth chat. Instead of just answering questions, Claude works more like a teammate: it can read and create files, run multi step tasks, keep working while you're away, and hand back finished results for you to review.

This matters because a lot of real work isn't a single question with a single answer. It's a project: research this, draft that, organize these files, check this list against that spreadsheet. Cowork is built for that kind of work. This module covers what Cowork actually is, how to set it up, how to hand it a multi step task, and how to review what it produces before you use it.

## Lesson 1: What Cowork Is

**Explanation**

In a normal chat, you ask Claude something and it answers right there in the conversation. Cowork is different in a few important ways. Claude gets its own private workspace where it can create and edit files, run scripts, and work through several steps on its own. You can hand it a task and let it work, even if that task takes several minutes or involves multiple stages, and check back once it's done or as it progresses.

Think of the difference like this: a regular chat is like asking a coworker a question at their desk and waiting for the answer. Cowork is like assigning a coworker a task, walking away, and coming back to review what they produced.

**Example**

In a regular chat, you might ask: "What's a good subject line for a product launch email?" and get a few suggestions instantly.

In Cowork, you might ask: "Draft the full product launch email, create a short social post to go with it, and save both as separate files I can review." Claude will work through each part, produce actual files, and let you know when it's done, rather than just replying with text in the chat.

## Lesson 2: Setting It Up

**Explanation**

Getting started with Cowork mainly means giving Claude what it needs to do the work you want: context, files, and sometimes access to other tools or your own computer.

A few basics: if the task involves specific files (a spreadsheet, a document, a set of notes), attach them or point Claude to them directly rather than describing them from memory. If Claude needs to save results somewhere specific, like a folder on your computer, that connection needs to be set up first. If a task will take a while or run unattended, it helps to state clearly what "done" looks like, so Claude knows when to stop and what to hand back.

You don't need to configure much to get started. Most setup is really just being clear about what you want and giving Claude access to the material it needs.

**Example**

Before asking Claude to "clean up my expense spreadsheet," you'd attach the spreadsheet itself, or connect the folder it lives in. Then your request might be: "Clean up this expense spreadsheet: fix inconsistent date formats, flag any entries over $500, and save the cleaned version as a new file so the original is untouched."

Now Claude has the actual data it needs and a clear description of what to do with it.

## Lesson 3: Delegating a Multi Step Task

**Explanation**

A multi step task is one that has several distinct parts, especially parts that depend on each other. Cowork is well suited to this because Claude can plan out the steps, work through them in order, and use the output of one step as the input to the next, all without you having to manually pass information between messages.

When delegating a multi step task, it helps to describe the end goal and the key steps or constraints, rather than trying to micromanage every action. Claude will often show its plan or its progress, especially for longer tasks, so you can see what it's doing along the way.

**Example**

"I'm planning a small team offsite. Research 3 venues in Austin that can host 15 people for a day, compare their prices and amenities, and put together a one page summary comparing the three so I can decide. Save the summary as a document."

This single request actually breaks down into research, comparison, and document creation. You don't have to ask for each step separately. Claude works through them and gives you one finished result.

## Lesson 4: Reviewing Its Output

**Explanation**

Cowork can do a lot of the work for you, but you're still the one responsible for the final result. Reviewing means actually checking what Claude produced before you use it, send it, or rely on it, the same way you'd check a draft from a colleague.

A good review checks three things: did it actually do what you asked, is the information accurate (especially anything factual, like numbers or names), and does it match how you'd want it presented. If something's off, you can ask Claude to fix just that part rather than starting over.

**Example**

Claude finishes the offsite venue comparison document from the example above. Before you send it to your team, you'd open the file and check: are the three venues actually real and in Austin, are the prices reasonable and clearly labeled, is the formatting clean, and did it miss anything you care about, like parking or catering. If the prices look off, you'd reply: "Double check the pricing for the second venue, that seems high for a day rate," rather than assuming it's correct.

## Try It Yourself

**Exercise 1: Describe a multi step task**

Think of a real task you do that has 2 to 3 distinct parts (for example: research something, summarize it, and format it into a document). Write out how you'd delegate it to Claude in Cowork in a single request.

**Exercise 2: Set up for a file based task**

Imagine you want Claude to reorganize a folder of photos by date. What would you need to set up or provide before making this request, and what would the request itself say?

**Exercise 3: Practice a review**

Imagine Claude just handed you a one page summary comparing two software tools, but you notice it only mentions pricing for one of them. Write the follow up message you'd send to get it fixed.

## Answer Key

**Exercise 1 (example solution)**

"Research the top 3 project management tools for small teams, compare their pricing and key features, and write up a short recommendation document explaining which one you'd suggest and why."

This works because it names a real multi part task (research, compare, recommend and write) in a single clear request. Any task with genuinely separate steps works here.

**Exercise 2 (example solution)**

Setup: connect or attach the folder containing the photos so Claude can actually see and access the files.

Request: "Look through this photo folder and reorganize the photos into subfolders by month and year, based on each photo's date. Don't delete or rename the original files, just sort copies into the new folders."

The key details are giving Claude access to the actual files and being specific about what "reorganize" means (by date, non destructively) so there's no ambiguity.

**Exercise 3 (example solution)**

"This looks good, but I noticed the pricing is only listed for the first tool. Can you add the pricing for the second tool as well, and make sure both are compared using the same plan tier?"

A good answer points out specifically what's missing or wrong and asks for a targeted fix, rather than a vague "this isn't right" or a request to redo the whole thing.
