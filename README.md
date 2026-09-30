# Week 6 Homework: StoryChatPro Research Skills

Two Claude skills built for Week 6 of Applied AI Foundations ("Build a Research Skill") by Melissa Forte, co-founder of StoryChatPro. They work as a pair: the first finds out what's happening, and the second turns those findings into content.

| Skill | What it does | Run it by saying |
|---|---|---|
| **[Visibility Scan](visibility-scan/README.md)** | Checks whether screenwriters looking for script feedback can find StoryChatPro, and compares it with the alternatives they find instead. Produces a dashboard, an Excel workbook and a short summary. | "Run my StoryChatPro visibility scan." |
| **[Content Planner](content-planner/README.md)** | Turns the scan's findings into a month of draft marketing content (calendar, blog posts, newsletter, social posts) written for a co-founder to rewrite in his own voice. | "Plan StoryChatPro content for [month]" and attach the scan workbook |

## How the repository is organized

- **`main` branch:** the README files that describe each skill.
- **`feature/skill` branch:** the `.skill` files themselves, each in its skill's folder. The visibility scan folder also has a sample dashboard from the first run.

```
visibility-scan/
  README.md
  storychatpro-visibility-scan.skill      (feature/skill branch)
  StoryChatPro Visibility Radar.html      (feature/skill branch, sample output)
content-planner/
  README.md
  storychatpro-content-planner.skill      (feature/skill branch)
```

To install a skill, download its `.skill` file from the `feature/skill` branch and add it to Claude.
