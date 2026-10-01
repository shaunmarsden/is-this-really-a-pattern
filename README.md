# Is This Really a Pattern?

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Review a log of similar-sounding entries, such as complaints, feedback or incidents, and tell real repeated causes apart from similar wording that hides different problems.

## Why

The same word can hide two different problems, and two different descriptions can hide the same one. Issue logs get this wrong both ways. They merge things that only sound alike, and they miss a real pattern because people described it differently each time.

[![A two by two grid showing when repeated wording is a genuine pattern and when it is misleading.](assets/diagrams/02-is-this-really-a-pattern.svg)](SKILL.md)

**Not what you need?** This looks for a real repeated cause across many similar entries in one log. If you have two records, kept separately, that should each show the same thing, try [Do These Actually Match?](https://github.com/shaunmarsden/do-these-actually-match).

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini or similar), then paste in your log. It produces:

- Genuine patterns, where different wording hides the same diagnosed cause across at least two distinct instances
- Misleading surface patterns, where similar wording hides different causes, named so a fix doesn't go to the wrong place
- Isolated signals, which are real but have only one instance so far
- A confidence level for each finding, never a percentage from a sample too small to support one

<details>
<summary><strong>See what it produces</strong></summary>

1. Genuine patterns, with the same diagnosed cause across at least two distinct instances
2. Misleading surface patterns, named so a fix isn't aimed at the wrong cause
3. Isolated signals kept apart from confirmed patterns, with the cause marked unknown where the log doesn't establish one
4. A confidence level for each finding, never a percentage from a sample too small to support one

</details>

[The worked example](example/) is a fictional team's retrospective feedback over four sprints. The shared word "communication" hides two different issues, and two very differently worded complaints turn out to share the same cause. [The second worked example](example-two/) is harder. One customer's repeat complaints could be miscounted as several instances, the log has no diagnosed causes at all, and someone asks for a percentage a small sample can't support.

Use [the blank template](templates/pattern-review-template.md) for your own log, and [the review checklist](checks/checklist.md) before you act on any finding.

You don't need to install anything, set up a project or write code to try it.

## Before You Use It

This reviews the log; it doesn't decide anything. Whether a finding is worth acting on, and any fix or process change that follows, is your call.

## Feedback

Used it on a real log? [Start a discussion](https://github.com/shaunmarsden/is-this-really-a-pattern/discussions) if a grouping didn't fit.

## Part of a Family

This is one of a family of free tools that take patterns from [practical-ai-sales-workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows) beyond sales. [sibling-projects](https://github.com/shaunmarsden/sibling-projects) lists the rest. Not sure which one fits? Try [the interactive picker](https://shaunmarsden.github.io/sibling-projects/), which shows clickable cards, or paste a description into an AI chat with [the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md).
