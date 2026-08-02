# Is This Really a Pattern?

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Review a log of similar-sounding instances, complaints, feedback, incidents, and separate genuine repeated causes from similar wording that hides different problems.

## Why

The same word can hide two different problems, and two different descriptions can hide the same problem. A recurring issue log gets this wrong in both directions: merging things that only sound alike, and missing a real pattern because it was described differently each time.

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in your log. It produces:

- **Genuine patterns**, different wording, the same diagnosed cause, at least two distinct instances
- **Misleading surface patterns**, similar wording, different causes, named explicitly so a fix does not get misdirected
- **Isolated signals**, real but not yet a pattern with only one instance
- A confidence level for each finding, never a percentage from a sample too small to support one

See [the worked example](example/): a fictional team's retrospective feedback across four sprints, where the shared word "communication" hides two genuinely different issues, and two very differently worded complaints turn out to share the same real cause.

Use [the blank template](templates/pattern-review-template.md) for your own log.

No installation, project, or coding required to try it once.

## Before You Use It

This reviews the log; it does not decide anything. Whether a finding is worth acting on, and any resulting fix or process change, stays your own call.

## Licence

MIT.

## Feedback

Used it on a real log? [Start a discussion](https://github.com/shaunmarsden/is-this-really-a-pattern/discussions) if a grouping did not fit.
