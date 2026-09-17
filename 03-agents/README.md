# Module 3: Introduction to Agents

## Introduction

An agent is Claude working through a task by taking a series of actions on its own, rather than just replying with text. Instead of only answering a question, an agent can decide what steps are needed, use tools (like searching the web, reading files, or running code) to carry those steps out, and keep going until the task is done or it needs your input.

This matters because it changes what you can ask for. A chat gets you an answer. An agent can actually go do something: look something up, fill out a form, organize files, monitor for a change, and take the next step based on what it finds, without you manually approving each individual action. This module explains what a basic agent is, walks through a real world use case, and covers the safety basics you should know before letting an agent take action on your behalf.

## Lesson 1: What a Basic Agent Is

**Explanation**

At its simplest, an agent follows a loop: look at the goal and the current situation, decide on the next action, take that action using a tool, look at the result, and repeat until the goal is met. The difference from a regular chat is that the agent decides its own next steps along the way, rather than you specifying each one.

A "tool" here just means some capability beyond generating text: searching the web, reading or writing a file, running a calculation, calling another piece of software. An agent is only as useful as the tools it has access to and how well it uses them.

**Example**

Say you ask a plain chat assistant "what's the cheapest flight from Chicago to Denver next Friday?" It can only answer from what it already knows, which might be outdated or missing.

An agent version of the same request can actually search a flight booking tool, look at real current results, compare a few options, and come back with an actual answer based on live information, because it took real actions rather than just recalling information.

## Lesson 2: A Simple Real World Use Case

**Explanation**

A good beginner use case for an agent is something with a clear goal, a few concrete steps, and low stakes if something needs correcting. Research and organization tasks are a common starting point: the agent gathers information from multiple places and turns it into something useful, without you having to do each lookup yourself.

**Example**

Use case: "Find 5 highly rated coffee shops within 2 miles of downtown that have wifi and are open before 8am, and put them in a simple list with their address and hours."

To do this, an agent would need to search for coffee shops, check reviews or ratings, check hours and wifi availability, and then compile the results into the list format you asked for. That's several steps and a couple of tools (search, and organizing the output), handled as one request instead of you doing each search yourself.

## Lesson 3: Safety Basics — Human Review Before Action

**Explanation**

The more autonomy an agent has, the more important it is to stay in the loop, especially for anything that has a real world effect: sending a message, spending money, deleting a file, posting something publicly, or changing an account setting. A good habit is to treat agent output the same way you'd treat a draft from a new employee: useful and often accurate, but worth checking before it goes live.

A simple rule of thumb: the more reversible and low stakes an action is (like drafting a document), the more comfortable you can be letting an agent just do it. The more permanent or high stakes an action is (like sending an email to a client, making a purchase, or deleting data), the more it's worth having the agent stop and show you the result before it actually happens.

**Example**

Lower stakes, fine to let it just happen: "Research these 3 competitors and draft a comparison summary." Nothing external happens until you decide to use the draft.

Higher stakes, worth a review step: "Draft a cancellation email to this vendor, but don't send it. Show me the draft first so I can approve it before it goes out."

Adding "don't send it, show me first" is a small change that keeps you in control of the one step that actually matters: the moment something becomes irreversible.

## Try It Yourself

**Exercise 1: Identify agent vs. chat**

Which of these is better suited to a basic agent, and which is fine as a regular chat question? Explain why.

a) "What's the capital of Australia?"
b) "Check the weather for the next 5 days in three cities I'm considering visiting, and tell me which one has the best weather for outdoor activities."

**Exercise 2: Design a low stakes use case**

Write a one paragraph description of a simple, low stakes task you could hand to an agent, that involves gathering information from more than one source and combining it into a single result.

**Exercise 3: Add a safety check**

Take this request and rewrite it to include a human review step before any real world action is taken:

"Find the 3 best rated plumbers near me and book an appointment with the top one for this week."

## Answer Key

**Exercise 1 (example solution)**

a) This is fine as a regular chat question. It's a single fact that doesn't require taking any actions or gathering current information.

b) This is better suited to an agent. It requires checking current weather data for three separate locations across several days and combining that into a comparison, which involves multiple real steps rather than a single recalled fact.

**Exercise 2 (example solution)**

"Gather the top 5 highest rated Italian restaurants within walking distance of a given address, along with their price range and whether they take reservations, and put the results into a simple comparison table."

Any task that involves looking things up from more than one source and combining them into one output works, as long as the stakes are low (nothing gets booked, sent, or purchased).

**Exercise 3 (example solution)**

"Find the 3 best rated plumbers near me. Show me the list with their ratings and availability, and I'll tell you which one to book once I've reviewed it."

The fix removes the automatic booking step and replaces it with showing the research first, so a real world action (booking an appointment) only happens after you've explicitly reviewed and approved it.
