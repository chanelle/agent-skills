---
name: measured-time-estimates
description: Give task durations as a measured range with a step breakdown and confidence, then report actuals and recalibrate the rest. Use for any time estimate, especially a list of tasks.
---

# Measured time estimates

## Break the work into timed parts

- Split each estimate into the steps the work actually takes, such as retrieve, draft or build, verify and fix, and deliver.
- Time the agent steps separately from the user steps, because agent drafting usually takes minutes while retrieval and verification take most of the elapsed time.
- Name any usage cost or heavy run separately before starting, instead of folding it silently into a duration.
- Leave out any step the task does not need, and say which step dominates the range when one step is much larger than the others.

## State the estimate honestly

- Give every duration as a range with a breakdown and a confidence level, never as a single confident number with no basis.
- Say plainly when a number is unmeasured, and base it on the closest completed task you can point to instead of on human assistant hours.
- Anchor a new estimate to a measured actual from earlier work whenever one exists, and name that anchor beside the estimate.
- Round a low-confidence estimate wider rather than padding every line, so the user can see where the uncertainty sits.

## Report actuals and recalibrate

- Record the actual time for the first completed item and report it next to its estimate without being asked.
- Re-estimate every remaining item from that actual in the same message, and show the revised range before continuing.
- Keep reporting actuals as later items finish, so a long list converges on measured times instead of staying on first guesses.
- Admit a miss plainly in the same turn when the actual lands far outside the range, then keep working from the corrected numbers.

## Present a list the user can decide from

- Show each item with its range, breakdown, confidence, and what is needed from the user, in a short scannable list rather than a wall of text.
- Put the fastest high-value items first when the user is choosing where to start, and mark any item whose estimate is still a guess.
- Stop and ask only when a missing input changes the estimate itself, and do the work for every item whose inputs are already in hand.

## Alternatives for better results

- Run one small item first as a timing probe when a long list has no measured anchor, then estimate the rest from that probe.
- Give a count-based range, such as per file or per page, when items repeat and a single total would hide the driver.
- Offer a lighter path with its own shorter range when the full version is heavy, so the user chooses the cost knowingly.
