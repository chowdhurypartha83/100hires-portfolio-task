# 100hires-portfolio-task

\## Tools Installed

\- Cursor IDE

\- Claude Code (CLI extension, installed via npm, logged in with Claude subscription)

\- Codex (CLI extension, installed via npm, logged in with ChatGPT Go account)

\- Git for Windows



\## Steps Completed

1\. Installed Cursor IDE from cursor.com

2\. Installed Claude Code via `npm install -g @anthropic-ai/claude-code`, ran `claude`, and logged in via browser OAuth

3\. Installed Codex via `npm install -g @openai/codex`, ran `codex`, and signed in with ChatGPT

4\. Set up Codex's default sandbox for safe file/command execution

5\. Created a public GitHub repository (`100hires-portfolio-task`)

6\. Installed Git for Windows, since it wasn't present on this machine

7\. Cloned the repository locally and opened it in Cursor

8\. Edited and committed this README.md



\## Issues Ran Into

\- Cursor's UI in this version doesn't have a classic "Extensions" marketplace panel, so I installed Claude Code and Codex via the integrated terminal using npm instead of through an Extensions search.

\- Git wasn't installed on my system. I downloaded and installed Git for Windows from git-scm.com, then restarted the terminal so PATH changes would take effect.

\- Codex's sandbox setup took a few minutes to complete on first run; just needed to wait it out.

\- Claude Code initially showed a "credit balance too low" message because it's billed via Anthropic Console API usage, separate from any Claude.ai subscription.



---

# Research Project — AI-Powered SEO Content Production

## What This Covers
This repo contains a research project on **AI-powered SEO content production** — finding and documenting genuinely strong practitioners (not generic listicle voices) who actively use AI in real SEO/content workflows, with visible proof through data, case studies, or hands-on demonstrations.

## Why These 10 Experts
Selection criteria: people who *practice* what they teach, with concrete evidence (named clients, real data, live demos) rather than secondhand commentary. Full rationale for each expert is in `research/sources.md`. In short:
- **Mike King, Lily Ray, Kevin Indig, Marie Haynes** — among the most credible voices analyzing how AI Search/AI Mode actually works, backed by original research and data.
- **Oleg, Authority Hacker** — hands-on AI content/SEO operators with proven business track records (sold sites, 500+ podcast episodes, real client work).
- **Alex Birkett & Allie Decker, Devesh Khanal** — agency operators (Omniscient Digital, Grow and Convert) who publish real client case studies and original data studies on AI visibility.
- **Arthur Andreyev, Ben Goodey** — practitioners who document specific, transparent case studies (real traffic/visibility numbers) rather than generic advice.

## What Was Collected
- **`research/sources.md`** — All 10 experts, with links and rationale for each.
- **`research/youtube-transcripts/`** — 6 transcripts from Mike King (iPullRank), Authority Hacker, and Marie Haynes, fetched via yt-dlp (using Codex to automate the search and download process).
- **`research/linkedin-posts/`** — 20 LinkedIn posts total (4 each) from Lily Ray, Kevin Indig, Alex Birkett, Devesh Khanal, and Ben Goodey, manually collected (not scraped, per LinkedIn's terms of service) and organized by author.

## Selection Approach for Individual Posts
For each LinkedIn expert, posts were chosen for: original data/case studies (not just opinions), clear frameworks or methodologies, honest acknowledgment of nuance or uncertainty, and topic diversity (avoiding multiple posts on the same narrow theme). Generic shares, event announcements, and posts with no added commentary were excluded.

## Process Notes
- Commits were made incrementally by source (not as one final dump), per the task's request.
- LinkedIn content was collected manually through direct browsing, in line with LinkedIn's terms of service prohibiting scraping.
- YouTube transcript collection used Codex with yt-dlp (a standard, legitimate open-source tool) to fetch official captions/subtitles only — no video/audio downloaded.