<p align="center">
  <img src="assets/banner.png" alt="Agent 春晚 / Agent Spring Festival 2026 Banner" width="720" />
</p>

### Agent 春晚 / Agent Spring Festival (GitHub Edition)

### 一句话 / TL;DR
- **中文**：这是一场在 GitHub 上举办的“Agent 春晚”——每个节目都是一个可复现的 Agent 作品（代码/工作流/演示），通过 Pull Request 投稿、Review 彩排、Release/直播发布，最后沉淀为可长期访问的开源合集。
- **English**: This is a GitHub-hosted “Agent Spring Festival” — each show is a reproducible agent-based project (code/workflow/demo). Submissions happen via Pull Requests, rehearsals via reviews, and the final lineup ships as a Release / live stream, archived as a long-lived open-source collection.

---

### 目录 / Contents
- **中文**：活动定位、时间线、节目类型、节目单、投稿规范、评审规则、奖项设置、运行与安全、常见问题
- **English**: What it is, timeline, show tracks, lineup, submission rules, judging, awards, runtime & safety, FAQ

---

### 活动定位 / What this event is
- **中文**
  - 目标：让大家用 Agent 做“能跑、可复现、可分享”的作品，并在 GitHub 上以协作方式完成一次“节目单”。
  - 形式：每个节目 = 一个目录（`shows/...`）+ 清晰的 README + 可运行入口（或可复现输出）+ 演示素材（可选）。
- **English**
  - Goal: build agent projects that are runnable, reproducible, and shareable, and assemble a collaborative “lineup” on GitHub.
  - Format: each show = a folder (`shows/...`) + clear README + a runnable entry point (or reproducible output) + optional demo assets.

---

### 时间线 / Timeline (2026)
> **中文**：从今天除夕启动，到正月初十（结束评选）收官。  
> **English**: Starts on Chinese New Year’s Eve and closes judging on the 10th day of the first lunar month.

- **节目单 / Lineup**: 见 `LINEUP.md` / See `LINEUP.md`
- **报名/选题期 / Registration & Pitching**: `2026-02-16`（除夕 / Chinese New Year’s Eve） ~ `2026-02-18`（正月初二 / Day 2）
- **开发期 / Build Period**: `2026-02-19`（正月初三 / Day 3） ~ `2026-02-23`（正月初七 / Day 7）
- **彩排与修订 / Rehearsal & Revisions**: `2026-02-24`（正月初八 / Day 8） ~ `2026-02-25`（正月初九 / Day 9）
- **发布/直播 / Premiere (Release/Live)**: `2026-02-24`（正月初八 / Day 8）
- **评选/投票期 / Judging & Voting**: `2026-02-24`（正月初八 / Day 8） ~ `2026-02-26`（正月初十 / Day 10, judging ends）
- **复盘与合集 / Postmortem & Collection**: `2026-02-27` ~ `2026-03-01`

---

### 节目类型 / Tracks (choose one)
- **工具节目 / Tooling**: automation, search, coding copilots, workflows, repo bots
- **创意节目 / Creative**: story, comedy, music/lyrics, interactive narratives
- **工程节目 / Engineering**: evaluation harness, multi-agent coordination, infra, safety
- **对抗节目 / Red Team / Safety**: prompt-injection defense, policy tests, sandboxing demos

> **中文**：你也可以混合类型，但请在节目 README 里写清楚“是什么、怎么跑、输出是什么”。  
> **English**: You can mix tracks, but your show README must clearly state “what it is, how to run, what it outputs”.

---

### 预置节目组（模板）/ Preset show templates
- **中文**：我们在仓库一级目录预置了 3 个“节目模板文件夹”，你可以直接复制/改名后开始创作，然后再按投稿规范放入 `shows/...` 走 PR 流程。
  - `开场歌曲-Opening-Song/`：开场歌曲（主题曲/合唱/开场串烧）
  - `春节相声-Crosstalk/`：春节相声（双人/多人/单口皆可）
  - `春节小品-Comedy-Sketch/`：春节小品（短剧/情景剧/互动剧）
- **English**: We provide three top-level preset template folders. You can copy/rename one to start quickly, then move it under `shows/...` and submit via PR.
  - `开场歌曲-Opening-Song/` (Opening Song)
  - `春节相声-Crosstalk/` (Crosstalk / Xiangsheng)
  - `春节小品-Comedy-Sketch/` (Comedy Sketch)

---

### 投稿方式 / How to submit

### 1) 先准备你的节目目录 / Prepare your show folder
把你的节目放到：
- `shows/<show-id>-<short-title>/`

命名建议 / Naming suggestions:
- **show-id**: `01`, `02`, ... 或者 `teamname-yyyymmdd`
- **short-title**: 小写英文/拼音，用 `-` 连接（例如 `agent-karaoke`、`repo-butler`）

### 2) 节目最小提交清单 / Minimum submission checklist
在 `shows/<...>/` 下至少包含：
- **`README.md`**
  - **中文**：节目简介、亮点、如何运行、期望输出、依赖、演示（可选）、安全说明（是否需要网络/API Key）
  - **English**: intro, highlights, how to run, expected output, dependencies, optional demo, safety notes (network/API key requirements)
- **可复现入口 / Reproducible entry**
  - 任选其一 / Choose one:
    - `run.sh`（推荐 / recommended）
    - `Makefile`（例如 `make run`）
    - `python -m ...` / `node ...` 等明确命令
- **依赖声明 / Dependencies**
  - 例如：`requirements.txt` / `pyproject.toml` / `package.json` / `Dockerfile`（任选其一或组合）
- **（推荐）元信息文件 / (Recommended) Metadata file**
  - `show.yaml` 或 `show.json`，包含：标题、作者、类型、运行命令、是否需要网络、是否需要密钥等

> **中文提示**：如果你的节目不能直接“跑起来”，也可以提交“可复现输出”——例如一个脚本生成固定报告/图表/日志，并在 README 中写清楚如何验证。  
> **English**: If your show can’t be fully “runnable”, you may submit a reproducible output (e.g., a script that generates a fixed report/chart/log) and explain how to verify it.

### 3) 用 PR 投稿 / Submit via Pull Request
- Fork 本仓库 / Fork this repo
- 新建分支 / Create a branch
- 添加你的节目目录到 `shows/...`
- 提交 PR，并在 PR 描述里回答 / In the PR description, answer:
  - **节目类型 / Track**
  - **运行命令 / How to run**
  - **是否需要网络 / Network required?** (yes/no)
  - **是否需要 API Key / Secrets required?** (yes/no; never commit secrets)
  - **演示素材 / Demo** (screenshots/video link optional)

---

### 评审与彩排 / Review & rehearsal
- **中文**
  - 每个节目至少 1 位维护者 Review；需要的话会要求你做一次“彩排修订”（改 README、补依赖、加安全说明等）。
  - 维护者会优先保证：能复现、不会误伤 CI、内容合规、说明清晰。
- **English**
  - Each show receives at least one maintainer review. You may be asked for rehearsal revisions (docs, deps, safety notes, etc.).
  - Maintainers prioritize: reproducibility, CI safety, policy compliance, clear documentation.

---

### 评分维度（可选）/ Judging rubric (optional)
你可以用来做评奖或投票说明。/ Use this for awards or community voting.

- **可复现性 / Reproducibility**: one-command run, deterministic output, clear deps
- **作品完成度 / Craft**: stability, UX, docs quality
- **创意与效果 / Creativity & Impact**: novelty, usefulness, delight
- **安全与边界 / Safety**: no secrets, no harmful behavior, clear data handling
- **表演性 / Showmanship**: demo quality, storytelling, presentation

---

### 奖项建议 / Award ideas
- **最佳工具人 / Best Utility**
- **最佳整活 / Best Chaos (Fun)**
- **最佳工程 / Best Engineering**
- **最佳安全 / Best Safety**
- **最佳新人 / Best Newcomer**
- **观众选择 / People’s Choice**

---

### 运行与安全规范 / Runtime & safety rules (重要 / important)
- **不要提交任何密钥 / No secrets**
  - 不要把 API Key、Token、Cookie、私钥写进代码或 README。/ Never commit keys/tokens/cookies/private keys.
- **CI 安全 / CI safety**
  - PR 代码必须默认“安全运行”：不要做破坏性操作（删库、挖矿、扫描内网、无限循环等）。/ PR code must be safe-by-default: no destructive actions, crypto-mining, internal network scanning, infinite loops, etc.
- **网络与成本 / Network & costs**
  - 如果需要联网或会产生费用，请在 README 明确声明，并提供离线模式（如果可能）。/ If network access or paid APIs are required, declare it and provide an offline mode if possible.
- **数据与隐私 / Data & privacy**
  - 禁止提交或抓取未授权的个人数据；使用公开数据请注明来源。/ Don’t include or scrape unauthorized personal data; cite sources for public datasets.
- **内容边界 / Content policy**
  - 保持友善与尊重，避免仇恨、骚扰、违法内容。/ Be respectful; no hate/harassment/illegal content.

---

### 组织方式（给主办方）/ Operations (for organizers)
- **Issue 报名 / Issues for registration**：开一个报名 Issue 模板，大家用 Issue 报名、认领节目号。  
  **Use issue templates** for registration and show-id claiming.
- **Projects 排期 / Projects for scheduling**：用看板追踪“报名→开发→彩排→定稿”。  
  **Use a project board** to track stages.
- **Discussions 互动 / Discussions**：统一答疑、彩排建议、观众投票。  
  **Use discussions** for Q&A, rehearsal feedback, voting.
- **Release 节目单 / Release as final lineup**：发布版本包含最终节目清单与运行索引。  
  **Ship a Release** with the final lineup and run index.

---

### 常见问题 / FAQ
- **Q: 我需要用某个特定模型吗？/ Do I need a specific model?**  
  A: 不需要。你可以自由选择，但要写清依赖与运行方式。/ No. Choose any stack, but document deps and run instructions.

- **Q: 我的节目需要完全自动跑通吗？/ Must it be fully runnable?**  
  A: 推荐一键运行；如果不行，至少要“可复现输出 + 清晰验证步骤”。/ Prefer one-command run; otherwise provide reproducible output + clear verification steps.

- **Q: 可以提交视频/截图吗？/ Can I submit media?**  
  A: 可以，放在节目目录或外链，并在 README 引用。/ Yes—store in the show folder or link externally, and reference it in README.

---

### License
- **中文**：除非你在节目目录里另行声明，否则默认遵循本仓库 `LICENSE`。  
- **English**: Unless your show folder states otherwise, the repository `LICENSE` applies by default.

