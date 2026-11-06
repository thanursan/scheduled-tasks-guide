# Design the prompt

A scheduled task is only as useful as its instructions. A prompt that works for a one-off conversation may be too vague for a recurring workflow because the task needs to make the same decisions consistently over time.

## A practical structure

Use these elements as a starting point:

| Element | Question to answer |
|---|---|
| Objective | What should the task accomplish? |
| Scope | What topics, sources or locations should it cover? |
| Criteria | What makes a result relevant? |
| Exclusions | What should it ignore? |
| Time window | How new must the information be? |
| Output | How should findings be organised? |
| Change handling | What should happen when there are no new findings? |

Not every task needs every element. Include the details that materially affect the result.

## Example prompt

```text
Every Monday, identify newly announced opportunities for an
independent narrative game.

Prioritise:
- Indie showcases and festivals
- Awards with playable-entry evaluation
- Relevant streamers, reviewers and publications
- Submission deadlines that are still open

For each opportunity, include:
- Name and organiser
- Why it is relevant
- Eligibility requirements
- Deadline and cost, if published
- Official source link

Exclude opportunities that require an active X or Bluesky
presence or evaluate games only from a video submission.

Prioritise new information. Do not repeat an old opportunity
unless its status or deadline has materially changed.

Keep the report concise. If there are no worthwhile new
opportunities, say so rather than padding the report.
```

This is an illustrative prompt, not a guarantee that a task can verify every detail. Important claims should be checked against the linked primary source.

## Make exclusions explicit

A broad request such as "find game festivals" can return many technically relevant but unsuitable results. Add constraints that reflect the actual decision:

- Geographic or eligibility restrictions.
- Budget limits.
- Required social-media accounts.
- Whether a playable build must be submitted.
- Whether the opportunity is still accepting entries.

## Ask for evidence, not just conclusions

For research tasks, request direct links to official sources. Where eligibility or deadlines matter, ask the task to distinguish confirmed information from details that could not be verified.

## Keep the output usable

A recurring report should help you decide what to do next. A short ranked list with reasons is often more useful than a long catalogue. Define a maximum number of recommendations if the task tends to produce too much information.
