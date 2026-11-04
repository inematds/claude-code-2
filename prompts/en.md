# The 13 prompts from the Claude Code 2.0 in practice guide

Copy, paste into Claude and swap the names for yours. Full guide: https://inematds.github.io/claude-code-2/guia/en/

## 01. Sections by project

```text
Organize this folder for my "AI Spreadsheets" course.
Create a task list for this week: lesson 1 script (save in lesson-1/script.md), 5 exercises, and 1 announcement post.
Check off each item as you finish it.
Save everything in a folder called "lesson-1".
Ask before changing or deleting any files that are already here.
```

## 02. Side chat

```text
What’s a short synonym for “impressionante” that would work in a video title?
```

## 03. Split view

```text
Write this week's community post based on the script in lesson-1/script.md.
120 words, simple language, and a question at the end for people to answer.
Don't publish it. Show me the draft.
```

## 04. Helpers (subagents)

```text
Turn lesson 1 (lesson-1/script.md) into:
1. A lesson summary
2. 5 ideas for short clips with timestamps
3. 3 short social media posts
4. A community post
Use one subagent for each item. Each one handles only its part and returns the result.
At the end, review all four, fix anything that doesn’t match, and give me a short summary.
```

## 05. Background computer use

```text
Use background computer use without taking over my screen.
Organize the screenshots on my Desktop into a folder for each month inside "Screenshots".
Don’t delete anything.
Let me know when you’re done and how many files you moved.
```

## 06. Projects in the cloud

```text
Research what has changed in AI video creation tools over the past 30 days.
List 5 new developments, with a source link for each one.
Then write 3 title ideas for a video about this, each under 60 characters.
Save everything in research.md.
```

## 07. Remote Control

```text
/remote-control
```

## 08. Built-in browser

```text
Open my YouTube channel dashboard in the browser. I'm already signed in.
Find the latest video and read its page.
Come up with 5 clip ideas with timestamps, a new description, and a community post.
Don't publish or change anything on the site.
```

## 09. Slides, designs, and dashboards

```text
Create a 7-slide presentation summarizing lesson 1 (lesson-1/script.md).
One idea per slide, large text, black and yellow.
Put the lesson’s best line on slide 1.
```

## 10. Shared docs

```text
Create a doc to track this month's livestream guests.
A table with: name, topic, date, and status (invited, confirmed, recorded).
Make it ready for me to share with the team.
```

## 11. Slash commands

```text
/output-style concise
```

## 12. Mods

```text
I want to install this Claude Code mod: [paste the GitHub link]
Before installing, read the code and run claude plugin validate in its folder.
Tell me in simple terms what it can access: my files, commands, and the internet.
If it’s safe, install it and tell me how to turn it off.
No link? Then create a small mod: [say what you want to see, e.g., a bar showing how much of the conversation has been used].
```

## 13. Claude Duet

```text
Every morning, look at my course and channel work in Claude.
Bring me the task that will save me the most time today.
Draft it and ask me before sending, publishing, or deleting anything.
```
