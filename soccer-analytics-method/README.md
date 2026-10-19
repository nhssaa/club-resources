# Game analytics for school sports departments: the method

How a chapter can give its school's teams real video analysis with a phone, a laptop and a couple of dollars a game. Built and tested on real varsity soccer and a public basketball clip.

**Before anything else: check with your athletic director and school before filming or analyzing any team.** Schools and leagues have their own rules about filming minors, and they win. Never publish footage, player names or identifiable data about minors. Method and templates only - that is all this package is.

## The pipeline in one paragraph

Film the game on one phone from an elevated sideline spot, chunk the video into 6 segments, run each chunk through a video-capable AI with the structured prompts in `03-prompts.md`, assemble the segment outputs with the report template in `04-report-template.md`, and publish to a private scouting site (`05-scouting-site.md`). Total model cost is about $2 per game (`06-cost-guide.md`). A full worked demo on a public, openly licensed clip is in `07-demo.md`.

## Files

- `01-capture.md` - one-camera filming setup that works.
- `02-chunking.md` - how and why to chunk the game.
- `03-prompts.md` - the analysis prompts, the clip taxonomy, and the reviewer prompt.
- `04-report-template.md` - the coach-facing report template.
- `05-scouting-site.md` - the private site layout for the team.
- `06-cost-guide.md` - what it costs, line by line, and the free options.
- `07-demo.md` - the basketball demo on a public CC BY clip.

## The standing rules (from the NHSSAA house rules, applied here)

1. No footage, player names, opponent player data or school-specific data in git. Ever. The repo holds the method; footage and reports live in private storage.
2. Honesty labels: the model marks guesses as inferred, and every report carries a limits section. Coaches trust what they can verify.
3. Anything you contribute to NHSSAA repos is public commons for others to use (see CONTRIBUTING.md).
