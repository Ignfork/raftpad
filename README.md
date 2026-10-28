# Raftpad ($RAFTPAD) · Bonk edition

Single-file site: `index.html` (no build step, no folders). Deploy as-is on Vercel or GitHub Pages.

Coins launch on bonk.fun (Raydium LaunchLab) and graduate at ~85 SOL into a Raydium pool.

## Set your links
Near the top of the script in `index.html`:

```js
var CONFIG={xUrl:'',xHandle:'',ca:'',buyUrl:''};
```

- `xUrl`: your X profile link
- `ca`: contract address (blank until launch; page says "CA posted on X at launch")
- `buyUrl`: buy link once live (e.g. your bonk.fun coin page)

## Notes
- Coins, stats and the tide log are samples; simulator fees are examples.
- Footer states Raftpad is independent and not affiliated with Floatpad, bonk.fun, BONK or Raydium.
