# Is This Really a Pattern?

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Review a log of similar-sounding instances, complaints, feedback, incidents, and separate genuine repeated causes from similar wording that hides different problems.

## Why

The same word can hide two different problems, and two different descriptions can hide the same problem. A recurring issue log gets this wrong in both directions: merging things that only sound alike, and missing a real pattern because it was described differently each time.

![A two by two grid showing when repeated wording is a genuine pattern and when it is misleading.](assets/diagrams/02-is-this-really-a-pattern.svg)

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in your log. It produces:

- **Genuine patterns**, different wording, the same diagnosed cause, at least two distinct instances
- **Misleading surface patterns**, similar wording, different causes, named explicitly so a fix does not get misdirected
- **Isolated signals**, real but not yet a pattern with only one instance
- A confidence level for each finding, never a percentage from a sample too small to support one

<details>
<summary><strong>See exactly what it produces</strong></summary>

1. Genuine patterns, the same diagnosed cause across at least two distinct instances
2. Misleading surface patterns named explicitly, so a fix does not get aimed at the wrong cause
3. Isolated signals kept apart from confirmed patterns, with cause marked unknown where the log does not actually establish one
4. A confidence level per finding, never a percentage from a sample too small to support one

</details>

See [the worked example](example/): a fictional team's retrospective feedback across four sprints, where the shared word "communication" hides two genuinely different issues, and two very differently worded complaints turn out to share the same real cause. For the harder case, one customer's repeat complaints miscounted as several instances, a log with no diagnosed causes at all, and a request for a percentage a small sample cannot support, read [the second worked example](example-two/).

Use [the blank template](templates/pattern-review-template.md) for your own log, and [the review checklist](checks/checklist.md) before acting on any finding.

No installation, project, or coding required to try it once.

## Before You Use It

This reviews the log; it does not decide anything. Whether a finding is worth acting on, and any resulting fix or process change, stays your own call.

## Licence

MIT.

## Feedback

Used it on a real log? [Start a discussion](https://github.com/shaunmarsden/is-this-really-a-pattern/discussions) if a grouping did not fit.

## Part of a Family

This is one of a family of free tools generalising [practical-ai-sales-workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows) patterns beyond sales. See [sibling-projects](https://github.com/shaunmarsden/sibling-projects) for the rest, or use [the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md) if you are not sure which one actually fits.
