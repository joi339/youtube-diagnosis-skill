# YouTube Diagnosis: a free Claude skill

Find out why your video isn't growing, and get **one thing to fix on your next video.** Every time you use it, it learns more about *your* channel.

## Download

**[Download youtube-diagnosis.zip](https://github.com/joi339/youtube-diagnosis-skill/releases/latest/download/youtube-diagnosis.zip)**, then follow the install steps below.

The skill files are also in the [`youtube-diagnosis`](youtube-diagnosis) folder.


## How it works

1. After a video has been up for **7 days**, open YouTube Studio and get these numbers:
   - Reach tab: impressions, CTR, traffic sources
   - Engagement tab: average view duration, % still watching at 0:30
2. Say **"diagnose my video"** and give Claude the numbers in whichever way you prefer:
   - **Type them in** (safest)
   - **Upload the Studio export** (Advanced mode → Export current view)
   - **Upload screenshots** (crop out your email and revenue first)
3. You get:
   - a one-line diagnosis
   - **ONE action item** for your next video
   - how you'll know it worked
4. Next time, it checks whether last time's action item worked before diagnosing the new video.

## It grows with your channel

| Videos logged | Stage | What it compares you to |
|---|---|---|
| Under 20 | Borrow data | General YouTube ranges and your competitors' outliers |
| 20–49 | Own data | Your own averages |
| 50+ | Proven rules | Your own averages, plus the fixes that have already worked twice on your channel |

Everything is kept in a file called `channel-log.md`.

## Install

**Claude.ai (web or app)**
1. Go to Settings → Capabilities → Skills and upload this folder as a .zip.
2. Make a Project for your channel.
3. After each diagnosis, save the updated `channel-log.md` Claude gives you into the Project files.

**Claude Code / Cowork**
1. Copy the `youtube-diagnosis` folder into your skills folder (`~/.claude/skills/`).
2. Run it from a folder for your channel. The log saves there automatically.

## Something not working?

Say **"report a problem"**. Claude writes a short, anonymous report with no channel name, titles or numbers unless you choose to add them. It also gives you a link that opens a GitHub problem report already filled in, so you just check it and press **Create**. Nothing is ever sent unless you press Create.

- You need a free GitHub account to report a problem.
- Reports are **public**, so don't add your channel name or numbers unless you're happy for others to see them.
- Report page: https://github.com/joi339/youtube-diagnosis-skill/issues/new?template=problem-report.yml

## Privacy

- **The skill never needs your login, password or access to your channel.** Don't share them with any tool that asks.
- It only uses the numbers you give it.
- Your numbers stay in your own Claude account and your own log file.
