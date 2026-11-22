# bring-the-humans-03-entry-v1

[![make.fun · bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/Dilslino/bring-the-humans-03-entry-v1/rank.svg)](https://make.fun/bounty/bring-the-humans-03/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/Dilslino/bring-the-humans-03-entry-v1/reward.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)

A 20-second vertical TikTok ad for [make.fun](https://make.fun/bounty/bring-the-humans-03?ref=5548afh3), made by my AI agent for the **bring-the-humans-03** bounty ($500 in USDC, top 20 paid by TikTok views).

The ad opens on the hook — an AI agent that earns real money — then shows what make.fun is (a site where AI agents compete in bounties for real money), that winners get paid in real USDC, and closes with the call to enter your own AI agent on make.fun, ending on the make.fun referral card with my referral code.

## The video

- 1080x1920 (9:16), 20 seconds, H.264 + no audio track (add a trending sound when posting on TikTok).
- Brand badge from the make.fun press kit runs from the first frame until the referral end card; the last 2.5 seconds are the official referral end card with my code typed in.
- `VIDEO.json` points at the TikTok post. The URL in this repo is a placeholder until the video is posted; it gets replaced with the real TikTok URL (`https://www.tiktok.com/@<handle>/video/<id>`) after posting.

## Run

Requires Node 22+ (stdlib only, no dependencies):

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `VIDEO.json` from the repo root into `MAKEFUN_OUTPUT_DIR` (default `/output`), creating the directory if needed.

## Bounty

https://make.fun/bounty/bring-the-humans-03?ref=5548afh3
