---
schemaId: urn:gala:schema:content-frontmatter:2.0.0
schemaVersion: 2.0.0
id: 01a168c5-c8e4-77cf-8281-a1bc8531f97c
kind: article
title: Build Your First AI Agent in 10 Minutes — No Coding
description: Build a useful AI agent in plain English with Claude, with no coding. Here is the daily research agent I set up and how to make it run every morning.
language: en-US
authors:
- 01a168d7-065a-78e9-a300-2a07b659a4a8
tags:
- ai-agents
- claude
- automation
- no-code
status: published
createdAt: '2026-09-05T12:00:00.000Z'
publishedAt: '2026-09-05T12:00:00.000Z'
slug: build-your-first-ai-agent-in-10-minutes-no-coding
hero:
  path: assets/content-build-your-first-ai-agent-in-10-minutes-no-coding-hero.jpg
  alt: Thumbnail of the video "Build Your First AI Agent in 10 Minutes — No Coding"
  role: informative
redirects: []
extensions: {}
---
*Adapted from the video [Build Your First AI Agent in 10 Minutes — No Coding](https://www.youtube.com/watch?v=7ReHiROdPbE)*

> **TL;DR:** AI agents sound far more complicated than they are. An agent is an AI you give a job or an outcome, not a single question, and it works through the steps itself. I build a daily AI news agent in Claude Cowork by describing the finished result in plain English, testing it, and improving it. Give it only the tools it needs, schedule it to run every morning and save to Google Drive, and keep a review step for risky actions.

AI agents are everywhere right now, but I think we have made them sound way more complicated than they actually are. When someone says "build an AI agent," you probably imagine coding, APIs, automation tools, and one of those giant workflows with 20 different boxes connected together.

Your first AI agent doesn't need any of that. I'm going to show you one of the easiest ways to build a genuinely useful agent using Claude. We describe what we want in normal English, give the AI a job, test the result, improve it, and then make it run automatically. No coding at all.

## What an AI agent actually is

*[Watch from 0:45](https://www.youtube.com/watch?v=7ReHiROdPbE&t=45s)*

Normally, when you use an AI chatbot, you ask it a question, it gives you an answer, and that interaction is basically finished. An AI agent is slightly different. Instead of giving the AI one question, we give it a job, or an outcome we want it to achieve.

The AI can then work through the steps required to complete that job. Depending on the task, it might search the internet, read multiple sources, compare information, work with files, use connected apps, organize everything, and then give you the final result.

## The agent we're building: a daily AI research agent

*[Watch from 1:20](https://www.youtube.com/watch?v=7ReHiROdPbE&t=80s)*

I want to keep our first agent really simple, but still build something I would actually use. So we're going to create a daily AI research agent. Every morning, I want it to search the web and find the five most important AI stories from the previous 24 hours.

I don't want every tiny funding announcement or random AI update. I want it to figure out which stories are actually important, give me a short summary of each one, explain why each story matters, and include links to the original sources. Once we know the agent is doing a good job, we'll make it run automatically every morning and save the finished report straight into Google Drive.

You can replace this example with almost anything you want. You could create:

- a stock research agent
- a competitor research agent
- a job search agent
- a travel search agent
- a content idea agent
- an agent that checks information from your connected apps and tells you what needs your attention

But for your first one, I would highly recommend choosing one very clear job instead of trying to build an agent that does everything.

## Describe the job, not the steps

*[Watch from 2:31](https://www.youtube.com/watch?v=7ReHiROdPbE&t=151s)*

I'm going to build this using Claude Cowork. If you have used Claude before, you're probably familiar with normal chat, a back-and-forth conversation. Cowork is designed more around giving Claude larger tasks and letting it work through them for you. Open Claude, preferably on your desktop, and switch from chat to Cowork near the message box. That is our workspace for building the agent.

The first thing is to explain the job clearly, and this is where people sometimes make agents unnecessarily complicated. You don't need to write some massive technical prompt. Just describe what you want the finished result to look like. For example, I could say:

> Research the five most important artificial intelligence stories from the last 24 hours. Prioritize major AI product launches, new AI models, important research, and significant announcements from companies like OpenAI, Anthropic, Google, Apple, Meta, and Microsoft. For each story, give me a short summary, explain why it matters, and include links to reliable original sources. Avoid duplicate stories and minor announcements.

That's already enough to give Claude a very clear job. Did you notice that I mainly described the outcome? I'm not telling Claude to first search this website, then open that website, compare these three articles, then create a document. Claude can figure out many of those intermediate steps itself. Then we let Claude run the research. It has the goal, it understands the output I want, and it can work through the steps necessary to get there.

## A word from HubSpot

*[Watch from 4:01](https://www.youtube.com/watch?v=7ReHiROdPbE&t=241s)*

I want to quickly thank HubSpot for sponsoring this part of the video. If you enjoyed building this agent and want to experiment with more advanced ones, HubSpot partnered with Futurepedia to create a completely free build-your-first-AI-agent course. It's a really useful next step after what we just built.

There are 18 hands-on videos where they walk you through building different agents using tools like N8N. It's not just explaining what an AI agent is; you're actually building things. For example, you will learn how to:

- connect an agent to Gmail, Google Calendar, and Google Sheets
- build a personal assistant
- create an agent that turns YouTube scripts into LinkedIn posts and short-form scripts
- build a customer support agent trained on a website

They also give you the actual system prompts and explain the really simple brain, memory, and tools frameworks that you can reuse when building your own agents. My favorite part is that it's very hands-on, and you connect the agents to tools you already use. The whole course is free, so I'll leave the HubSpot link below if you want to check it out.

## Improve the first version

*[Watch from 5:30](https://www.youtube.com/watch?v=7ReHiROdPbE&t=330s)*

Once Claude finishes, look at the results. Your first version probably won't be perfect, and that's completely normal. You can improve the agent. I can say, "Keep each story under 100 words," and I can revise further and customize it with all my requirements. Now the agent becomes much more useful, because it understands the actual workflow I'm trying to accomplish.

## Tools: give it only what it needs

*[Watch from 6:00](https://www.youtube.com/watch?v=7ReHiROdPbE&t=360s)*

Agents become much more powerful when they have access to tools, but again, this sounds more technical than it really is. A tool is simply something the AI is allowed to use. Web search is a tool. Google Drive can be a tool. Gmail can be a tool. Your calendar can be a tool. Different services and connectors give an agent access to different information or actions.

If you connect Google Drive, you could create an agent that works with information stored inside your drive, rather than manually copying and pasting everything into Claude. If you connect an email service, you could build workflows around finding messages that need your attention, summarizing certain emails, or helping you prepare responses.

For our AI news agent, we honestly don't need many tools. Web research is enough, and I would recommend keeping your first agent this simple. Don't connect 10 different apps just because you can. The more access you give an agent, the more complicated the workflow becomes. Start by asking what the agent actually needs to complete its job, and only give it those tools.

## Make it run every morning

*[Watch from 7:15](https://www.youtube.com/watch?v=7ReHiROdPbE&t=435s)*

At this point our research agent already works, but there is one problem: I have to remember to come into Claude and ask it to do the research every morning. So the final step is to automate that part.

Inside Claude Cowork, I go to the schedule section and create a new scheduled task. I'm going to call mine "daily AI news brief." Then I use essentially the same instructions we just tested, plus one more thing. I've connected Google Drive, so I tell Claude: every morning, create this AI news brief and save the finished report to my daily AI news briefs folder in Google Drive, with the date in the file name. To run it every day, I simply say: run this workflow every day at 8:00 a.m. as a scheduled task.

Now Claude does the research, creates the report, and saves a new dated copy into my Google Drive every day. I don't even have to remember to come back and run it myself.

## Why this is more than pasting a prompt

*[Watch from 8:16](https://www.youtube.com/watch?v=7ReHiROdPbE&t=496s)*

You might think: couldn't I just paste this exact prompt into normal Claude every morning? Absolutely, you could. The difference is that you would still be responsible for starting and managing that process every single morning.

Here, we have given Claude the goal and instructions about what a good result looks like. It can use tools like web research to gather the information, it can work through multiple steps to complete the task, and we have told it to repeat that task on a schedule. That's really the easiest mental model for an AI agent:

- It has a goal.
- It has instructions.
- It has tools.
- It can work through multiple steps to complete the job.

And if the task happens repeatedly, automation makes it even more useful.

## Be careful how much control you give

*[Watch from 9:01](https://www.youtube.com/watch?v=7ReHiROdPbE&t=541s)*

One thing to keep in mind before connecting everything: be careful how much control you give an agent. There is a big difference between letting it research or summarize information and letting it edit files, send messages, delete data, or take actions inside your accounts.

Start with low-risk tasks like research, planning, organization, and drafting. For anything that can make important changes or communicate on your behalf, keep a review step in place until you're confident the workflow is reliable.

That's really all you need to build your first AI agent. Let us know in the comments about the interesting agents you have built or are going to build. I'll catch you in the next one.

*[Watch the full video on YouTube](https://www.youtube.com/watch?v=7ReHiROdPbE)*
