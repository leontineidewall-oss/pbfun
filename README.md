# pb.fun

Hold the record. Hold the fees.

A speedrun post becomes a pump.fun coin, and its creator fees go to whoever holds the verified world record on speedrun.com. When the record is beaten, fees from then on go to the new holder.

**Status: not live.** No coin has launched through pb.fun.

Single-file static site, no build step. The record lookup reads speedrun.com's public API from the visitor's browser. The fee calculator runs locally.

## Config

`index.html` → `CONFIG` near the top of the script: `x` (the X account link, once it's yours) and `github`.

## Files

| file | made by |
|---|---|
| `index.html` | hand-written |
| `og.png` | drawn in the browser by `og.js` (canvas) |
