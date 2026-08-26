# Component previews

Not the live profile. GitHub only renders `README.md` on [github.com/remi-9](https://github.com/remi-9). Open this file in the editor **Markdown preview** so the SVGs load. They use your public data; first load can take a few seconds.

Rule used here: **at most two visual widgets** plus your existing copy. More than that is the cluttered look everyone scrolls past.

---

## Composed looks (pick one)

Same headline and projects as the current README. Only the visual layer changes.

### A — Skill strip (minimum visual, still clean)

Best default if you want “interesting” without looking generated.

**Jeremias Pablo**

Working toward data science and machine learning. Python is the default: datasets, models, metrics, and whether a prediction can be explained.

The projects below are that loop in practice — applied ML, analytics, and a few products around the edges.

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,java,ts,react,git&theme=light" alt="Skill icons, light" />
</p>

Then the current project table + LinkedIn. No stats cards.

Dark GitHub users would get the dark strip instead (`#gh-dark-mode-only` / `#gh-light-mode-only`). Dark variant:

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,java,ts,react,git&theme=dark" alt="Skill icons, dark" />
</p>

---

### B — Copy + compact languages (two column)

Popular layout. One small card, not a widget wall. Languages will skew toward C/HTML from coursework unless we hide those langs — shown honestly first.

<table>
<tr>
<td valign="top" width="50%">

**Jeremias Pablo**

Working toward data science and machine learning. Python is the default: datasets, models, metrics, and whether a prediction can be explained.

The projects below are that loop in practice.

</td>
<td valign="top" width="50%">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=remi-9&layout=compact&theme=transparent&hide_border=true&langs_count=6" alt="Top languages compact" />

</td>
</tr>
</table>

Optional: hide coursework langs with `&hide=c,html,php` so the card matches the DS/ML story:

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=remi-9&layout=compact&theme=transparent&hide_border=true&langs_count=6&hide=c,html,php" alt="Top languages with coursework hidden" />

---

### C — Repo cards instead of the table (most visual, still quiet)

Niche-popular: [github-readme-stats pin cards](https://github.com/anuraghazra/github-readme-stats). Replaces the markdown table. Two-by-two, transparent, no rank chrome.

<table>
<tr>
<td>
<a href="https://github.com/remi-9/fslr-transformer-vs-iv3gru">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=remi-9&repo=fslr-transformer-vs-iv3gru&theme=transparent&hide_border=true&description_lines_count=2" alt="PANSINAYAN" />
</a>
</td>
<td>
<a href="https://github.com/remi-9/Saklolo-Hub">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=remi-9&repo=Saklolo-Hub&theme=transparent&hide_border=true&description_lines_count=2" alt="Saklolo Hub" />
</a>
</td>
</tr>
<tr>
<td>
<a href="https://github.com/remi-9/SmishKaBa">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=remi-9&repo=SmishKaBa&theme=transparent&hide_border=true&description_lines_count=2" alt="SmishKaBa" />
</a>
</td>
<td>
<a href="https://github.com/remi-9/JobTracker">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=remi-9&repo=JobTracker&theme=transparent&hide_border=true&description_lines_count=2" alt="JobTracker" />
</a>
</td>
</tr>
</table>

Keep a one-line caption under each card if GitHub’s repo description is empty (SmishKaBa and JobTracker have no description — those cards will look thin until the repo description is set).

---

### D — Skill strip + one stats card

Popular combo. Stop here; do not add streak or graph on top.

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,java,ts,react,git&theme=light" alt="Skills" />
</p>

<img src="https://github-readme-stats.vercel.app/api?username=remi-9&show_icons=true&hide_rank=true&theme=transparent&hide_border=true" alt="GitHub stats" />

---

## Individual components

### Use (low clutter)

**Skill icons** — [skillicons.dev](https://skillicons.dev). One row, six icons. Replaces the `Python · PyTorch · …` text line.

![skills](https://skillicons.dev/icons?i=py,pytorch,java,ts,react,git&theme=light)

**Compact top langs** — [github-readme-stats](https://github.com/anuraghazra/github-readme-stats). Smallest useful stats widget.

![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=remi-9&layout=compact&theme=transparent&hide_border=true&langs_count=6)

**Repo pin card** — same project, one card. Use as a set (layout C) or not at all.

![pin](https://github-readme-stats.vercel.app/api/pin/?username=remi-9&repo=fslr-transformer-vs-iv3gru&theme=transparent&hide_border=true&description_lines_count=2)

**Monochrome shields** — [Shields.io](https://shields.io) + [Simple Icons](https://simpleicons.org). Quieter than skill icons; good if you dislike icon tiles.

![Python](https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-111111?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-111111?style=flat-square&logo=pytorch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-111111?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-111111?style=flat-square&logo=openjdk&logoColor=white)

**LinkedIn as a single badge** (instead of a text link):

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeremias-pablo-898422253)

**Mermaid loop** — niche, no third-party image, matches the DS/ML headline. GitHub renders it natively.

```mermaid
flowchart LR
  data[Data] --> model[Model]
  model --> metrics[Metrics]
  metrics --> explain[Explain]
```

---

### Optional (one of these, never all)

**Full stats card** — fine alone; skip if you already use langs or pins.

![stats](https://github-readme-stats.vercel.app/api?username=remi-9&show_icons=true&hide_rank=true&theme=transparent&hide_border=true)

**Streak** — [denvercoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats). Adds a second card for little career signal.

![streak](https://streak-stats.demolab.com/?user=remi-9&theme=transparent&hide_border=true)

**Activity graph** — [Ashutosh00710/github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph). Distinctive, wide, easy to dominate the page.

![graph](https://github-readme-activity-graph.vercel.app/graph?username=remi-9&theme=minimal&hide_border=true&area=true)

**Repos-per-language summary** — [vn7n24fzkq/github-profile-summary-cards](https://github.com/vn7n24fzkq/github-profile-summary-cards). One card is niche and clean; the usual 4-card grid is clutter.

![summary](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=remi-9&theme=transparent)

---

### Skip (shown so you can see why)

**Typing SVG** — motion without information.

![typing](https://readme-typing-svg.demolab.com?font=Inter&size=20&pause=1200&color=58A6FF&vCenter=true&width=520&lines=Data+science+%C2%B7+Machine+learning+%C2%B7+Python)

**Trophies** — [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy). Game UI on a hiring profile.

![trophies](https://github-profile-trophy.vercel.app/?username=remi-9&theme=flat&no-frame=true&column=6&margin-w=8)

**Visitor counter** — looks like 2013.

![views](https://komarev.com/ghpvc/?username=remi-9&style=flat-square)

**Rainbow `for-the-badge` stack** — loud, repeats the skill-strip job worse.

![py](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pt](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ts](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

## Pairing guide

| If you pick | Add | Do not also add |
| --- | --- | --- |
| A Skill strip | Optional LinkedIn badge | Stats, streak, graph, trophies |
| B Langs column | Keep the text table | Skill strip *and* stats *and* pins |
| C Repo cards | One-line captions where GitHub descriptions are empty | The markdown table (duplicate) |
| D Strip + stats | Nothing else | Streak, graph, trophies, typing |

Recommended pairing for this profile: **A + keep the table**, or **C** if you want the page to feel designed. Set GitHub descriptions on `SmishKaBa` and `JobTracker` before choosing C.
