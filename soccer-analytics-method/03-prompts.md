# Prompts

## The structured analysis pass (one per segment)

Paste the segment to your video-capable model with this shape. Adjust the sport terms; keep the structure and the honesty rules.

> Analyze this game segment as an assistant coach. Teams are WHITE and DARK; use jersey numbers only, never names. Output exactly these sections:
> 1. Segment summary (3 sentences).
> 2. Event timeline: minute, team, event type, one line.
> 3. Shot/chance log: minute, team, jersey, location, outcome.
> 4. Defensive notes: formation or press reads, where attacks came from.
> 5. Rotation and pace observations.
> 6. Three coaching takeaways.
> Tag anything you are guessing as [inferred]. If the camera angle makes something unverifiable, leave it out and say so.

## The clip taxonomy (what to cut for players)

Each clip gets: category, team, minute, do/don't, one-line coaching point.

- Goals/scores and set plays.
- DO: good tackles and stops; using the body to shield; simple pass-and-go; switching the ball; through balls breaking a high line; tracking back.
- DON'T: dribbling through multiple defenders; ball-watching; caught in no man's land; hopping in front of the ball instead of tackling.
- Anything illustrating generally accepted principles of the sport.
- If camera distance makes a category unverifiable, skip it. No padding.

Every opponent report ends with two lines: where we can attack, and where we must defend well.

## The reviewer prompt (verification path)

Give this plus the report to a second person or agent before the coach sees it:

> Check this analysis against the source segments. For every claim with a minute mark, say whether the footage supports it. List anything that is wrong, unverifiable or missing. Do not be polite; be accurate.
