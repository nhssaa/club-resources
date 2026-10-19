# Chunking the game

Video models lose the plot on long footage. What worked in testing: split the game into 6 roughly equal segments (about 10-15 minutes each for a school game) and analyze each one separately.

- Cut on natural breaks where possible (quarter/half boundaries, timeouts) so plays do not split mid-action.
- A 10-15 second overlap between segments means a play at the boundary is never lost. Dedupe the overlap events when you assemble the report.
- Upload each segment to the model's file API, run the analysis pass per segment, then merge the structured outputs (timeline, shot log, notes) in order.
- Keep each segment's raw model output. When a coach asks "are you sure?", you can point at the exact segment and minute.
