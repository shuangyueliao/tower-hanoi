# Tower Hanoi

Free single-file HTML5 Tower of Hanoi. Move the whole stack from the left peg to the
right peg — one disk at a time, never a big disk on a smaller one. 3 to 8 disks,
classic rules, PERFECT gold star for matching the 2^N−1 optimum. One HTML file, zero assets.

**Play:** https://shuangyueliao.github.io/tower-hanoi/

- Click a peg to lift its top disk (it floats and follows your pointer), click again to drop — or just drag
- Illegal placements are rejected with a shake; hints (3 per game, H key) always show a move on an optimal path
- Demo mode: watch the AI play a full optimal solution (7–255 moves by difficulty)
- Win celebration: disks glow one by one plus fireworks; best score per disk count saved in localStorage
- Procedural graphics (canvas) and synth sounds (WebAudio), mute toggle, mobile touch + desktop mouse + keyboard
- No dependencies, no tracking, no external links; works offline once loaded
