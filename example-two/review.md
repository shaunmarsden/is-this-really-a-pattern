# Review: Support Ticket Log

I checked [output.md](output.md) against what [log.md](log.md) was built to test.

## What Worked

It counted Dana's three tickets as one distinct instance, not three. The skill's own guidance names this trap: repeated entries from the same instance are occurrences, not independent examples. A weaker review might have reported "3 occurrences" as three customers hitting the same issue.

It refused to invent a cause from wording alone. None of the five entries had a diagnosed cause. The output didn't group by the words "export," "login," and "dashboard" and call that a pattern. It labelled all three as isolated signals with cause unknown, and named the real gap: nobody did the diagnosis.

It declined the percentage request and said why. A five-ticket sample, with three from one customer, can't support a percentage. The output said what could be said instead, without giving the number that was asked for.

## What Still Needs a Human Check

- Dana's repeated ticket needs a proper investigation, not another closure with no cause recorded.
- Once future tickets have diagnosed causes, it's worth reviewing this log again.

## Verdict

No automatic failure. It caught the instance-counting trap, refused to build a pattern from undiagnosed wording and declined a percentage the sample couldn't support.
