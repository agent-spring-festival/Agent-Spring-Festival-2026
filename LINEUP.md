### 节目单 / Lineup (Agent 春晚 2026)

### 总览 / Overview
- **中文**：本文件用于维护最终“节目单”（上线顺序 + 节目信息 + 链接），便于发布日/直播日直接照单执行。
- **English**: This file maintains the final lineup (order + metadata + links) so the premiere/live day can run straight from it.

---

### 关键日期 / Key dates (2026)
- **启动 / Kickoff**: `2026-02-16`（除夕 / Chinese New Year’s Eve）
- **发布/直播 / Premiere (Release/Live)**: `2026-02-24`（正月初八 / Day 8）
- **评选结束 / Judging ends**: `2026-02-26`（正月初十 / Day 10）

---

### 节目单（占位）/ Lineup (placeholders)
> **中文**：节目合并到 `shows/` 后，在这里补上链接与顺序。  
> **English**: Once shows are merged under `shows/`, fill in links and order here.

| 顺序 Order | 节目 Show | 类型 Track | 作者 Authors | 目录/链接 Path/Link | 状态 Status |
|---:|---|---|---|---|---|
| 01 | 开场歌曲 / Opening Song（马年 / Horse Year） | Creative | Organizers | `shows/01-opening-song/` | Draft |
| 02 | 春节相声 / Crosstalk | Creative | TBD | `shows/02-crosstalk/` | Draft |
| 03 | 春节小品 / Comedy Sketch | Creative | TBD | `shows/03-comedy-sketch/` | Draft |
| 04 | （待定 / TBD） | Tooling/Engineering/Safety | TBD | `shows/04-.../` | Draft |
| 05 | （待定 / TBD） | Tooling/Engineering/Safety | TBD | `shows/05-.../` | Draft |

---

### 如何更新（给主办方）/ How to maintain (for organizers)
- **中文**
  - 合并 PR 后，把节目追加到表格，填上：顺序、类型、作者、目录路径。
  - 发布/直播前 24h：把状态统一改为 `Final`，并锁定顺序（之后只允许修复性改动）。
  - 推荐每个节目目录内都有清晰的 `README.md` 和一条“复现命令”。
- **English**
  - After merging a PR, append the show to the table with order, track, authors, and folder path.
  - 24h before premiere: switch statuses to `Final` and freeze the order (only fixes afterward).
  - Each show folder should include a clear `README.md` and a reproducible run command.

