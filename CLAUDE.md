# BADM 554 Learning Visibility (public site)

**Type:** teaching / public write-up. **Owner and author:** Vishal Sachdev, Gies College of Business.
**Remote:** `vishalsachdev/badm554-learning-visibility`, PUBLIC since 2026-10-25 (Vishal's yes). Live: https://vishalsachdev.github.io/badm554-learning-visibility/ (Pages from `docs/`, legacy build). `context/` is local only and gitignored; never track it.

A public page on how BADM 554 (Fall 2026, online and in-person sections) makes student reasoning visible with GitHub, AI-assisted review and Canvas, what the course records show, and what they do not show yet. It carries a NotebookLM audio overview and a process note on how the page itself was built.

Start with [plan-as-approved.md](plan-as-approved.md), then [context/HISTORY.md](context/HISTORY.md).

## Rules for this repo
- Public audience. No student names, NetIDs, GitHub handles, emails or individual grades, anywhere, including `context/`. Class-level counts only; soften the smallest ones.
- No links to private repos (`vishalsachdev/badm554`, `vishalsachdev/msba-online`) on the public page. Describe cases instead. Public links are fine (Canvas help pages, `vishalsachdev/canvas-mcp`, `Business-Analytics-at-Gies/badm554-taxi-crawler`).
- Student data (issue comments, submissions, rosters, the dashboard plan) is read only through Codex Edu (`CODEX_HOME=~/.codex-edu`), which returns de-identified output. Claude never reads it directly.
- Email-style house rules apply to page prose: no em-dashes, never the word "shape". Run `python3 ~/.claude/scripts/outbound_check.py <file>` on every page before publishing.
- Gies brand: Source Sans 3, Illini Blue `#13294B`, Illini Orange `#FF5F05` (Altgeld `#C84113` for orange text on light). WCAG 2.1 AA, works at 375px and with JavaScript off.
- Making the repo public, enabling Pages, and any MarCom contact each need Vishal's explicit yes.

## Sources (gitignored symlinks)
- `sources/badm554` → `~/teaching/badm554` (course repo; student data, see rule above)
- `sources/msba-online` → `~/admin/msba-online` (program KB; Jev's original report in `_agent-inbox/done/2026-10-25-badm554-*.md`, review record in `docs/handoff-status/2026-10-25-badm554-ai-learning-visibility-report.md`)

## Session Log

### 2026-10-25
- **Created** from the msba-online session. Context, plan and assets moved here. Site not built yet.
- **Next:** build `docs/index.html` and `docs/process.html` per the plan; Vishal reviews; then public + Pages.
- **Built** (same day, session `badm554-learning-visibility`): `docs/index.html` retitled "Making Student Reasoning Visible", `docs/process.html`; audio moved to `docs/assets/`. Outbound gate clean except a verbatim "paradigm shift" in the NotebookLM transcript (Vishal: keep). 375px and no-JS checked.
- **Published:** history squashed to one commit (`context/` held private links and a personal address), repo made public, Pages on. The old SHAs were still reachable by direct URL, so the repo was deleted and recreated (Vishal's yes) and the clean history pushed; `ab67831` and `9cbe1a0` now return 404.
- **Yun Huang email** staged in Thunderbird Drafts (replaced Vishal's started draft); links to the live site. Not sent.
