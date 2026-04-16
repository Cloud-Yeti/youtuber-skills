# youtube-creator-skills

Claude Code skills for YouTube creators. Research-backed techniques from MrBeast, Paddy Galloway, George Blackman, Jake Thomas, Ali Abdaal, Roberto Blake, Derral Eves, and others — turned into runnable skills.

Each skill is one `SKILL.md` file. Install any skill, invoke it, and get actionable output in seconds.

## Skills

| Skill | What It Does |
|-------|-------------|
| [title-formula](title-formula/) | Generate 10+ title options using Jake Thomas's 3 Click Triggers, IMPACT framework, and 7 proven formulas. Scores each for CTR potential. |
| [thumbnail-psychology](thumbnail-psychology/) | Design brief for thumbnails using research-backed rules: face close-ups (+35-50% CTR), 4 words max (+30% CTR), high contrast (+20-40% CTR), dark mode optimized. |
| [mrbeast-packaging](mrbeast-packaging/) | The MrBeast pre-production method: 50+ title/thumbnail concepts BEFORE filming. Title + thumbnail set the ceiling. Video is built to match. |
| [script-hook-framework](script-hook-framework/) | Write scripts using George Blackman's Target-Transformation-Stakes hook + Setup-Tension-Payoff body. Mini-payoffs every 60-90 seconds. |
| [retention-surgeon](retention-surgeon/) | Diagnose retention problems. Identify which of the 4 curve shapes you have, apply the right cutting pattern, fix the first 30 seconds. |
| [algorithm-2026](algorithm-2026/) | Optimize for the 2026 YouTube algorithm. Satisfaction > watch time. Series formats prioritized. Shorts decoupled from long-form. |
| [shorts-strategy](shorts-strategy/) | Decide when to use Shorts vs long-form. Shorts = discovery ($0.01-0.06 RPM). Long-form = revenue ($1-30 RPM). Both = 3x subscriber growth. |
| [seo-discovery](seo-discovery/) | YouTube SEO: keyword placement, description optimization, search vs browse vs suggested strategy. 35% of traffic still comes from search. |
| [monetization-stack](monetization-stack/) | Build a creator revenue stack beyond AdSense. Framework from Colin & Samir, Roberto Blake, Ali Abdaal. Platform ownership > marketplace splits. |
| [production-ops](production-ops/) | Production systems from MrBeast's handbook and Paddy Galloway's 12-month plan. A/B/C player hiring, 100 ideas/week, bottleneck management. |
| [outlier-hunter](outlier-hunter/) | Find outlier videos (3x+ above channel average) across niches. Extract the FORMAT, not the topic. Adapt with your brand voice. MrBeast's "copy with taste." |
| [virality-gate](virality-gate/) | Pre-publish quality gate. 8 checks a video must pass before going live. Kill weak videos before they hurt your channel. |

## Install

```bash
# Clone the repo
git clone https://github.com/Cloud-Yeti/youtube-creator-skills.git

# Symlink all skills to Claude Code
for skill in youtube-creator-skills/*/; do
  name=$(basename "$skill")
  ln -sf "$(pwd)/$skill" "$HOME/.claude/skills/$name"
done
```

Or install a single skill:

```bash
ln -sf "$(pwd)/youtube-creator-skills/title-formula" "$HOME/.claude/skills/title-formula"
```

## Usage

In Claude Code:

```
/title-formula "AWS Bedrock crash course for engineers who hate overpaying"
/thumbnail-psychology "comparison video, me vs enterprise AI spend"
/virality-gate (run on your current video before publishing)
/outlier-hunter "cloud computing tutorials" (find what's working in your niche)
```

## Research Sources

Built from deep research across 10+ top creators and strategists:

- **MrBeast** — Production handbook, A/B testing, "every second earns its place"
- **Jake Thomas (Creator Hooks)** — 408-title database, 3 Click Triggers, IMPACT framework
- **George Blackman** — Target-Transformation-Stakes, Setup-Tension-Payoff, scriptwriting system
- **Paddy Galloway** — 12-month growth system, CCN framework, 280% avg first-year viewership increase
- **Ali Abdaal** — HIVE framework, monetization stack, Part-Time YouTuber Academy
- **Roberto Blake** — Big Creator Energy, One Tribe/One Theme/Five Topics
- **Colin & Samir** — Revenue diversification, creator economy economics
- **Derral Eves** — The YouTube Formula, algorithm mechanics, Squatty Potty case study
- **Film Booth** — 4-beat storytelling structure
- **vidIQ / Think Media** — SEO, algorithm 2025-2026, discovery mechanics
- **AIR Media-Tech** — 5 cutting patterns, retention editing

Full research notes: see `RESEARCH.md`

## Who Made This

Built by [CloudYeti](https://cloudyeti.io) — AI and Cloud Cost Optimization consulting. 13x AWS certified, ex-Amazon, 15K+ YouTube subscribers.

If you're a creator trying to grow a technical channel, these skills encode the playbook we use on our own channel.

## License

MIT
