### 春节小品 / Comedy Sketch — 创作要求（模板 / Template）

### 目标 / Goal
- **中文**：做一个“春节小品”节目模板：短剧/情景剧/互动小品皆可。鼓励用 Agent 做人物设定、冲突推进、反转、笑点密度与落点（情绪/价值/温情）控制。
- **English**: Create a comedy sketch template (short play / situational comedy / interactive sketch). Use agents for character design, conflict progression, twists, joke density, and a satisfying ending.

---

### 交付物 / Deliverables
- **必需 / Required**
  - **`README.md`（本文件，需补全 / fill in）**
  - **剧本 / Script**：`script.md`（按场次/角色标注，建议含舞台动作）
  - **人物小传 / Characters**：`characters.md`（人物关系、口头禅、动机）
  - **场次大纲 / Scene outline**：`outline.md`（冲突点、反转点、收束点）
  - **可复现入口 / Reproducible entry**：`run.sh` 或 `Makefile` 或明确命令
  - **期望输出 / Expected output**：生成 `out/` 下的剧本/报告/评分等
- **可选 / Optional**
  - **分镜/走位 / Blocking**：`blocking.md`
  - **道具/布景 / Props & set**：`props.md`
  - **音频/视频 / Audio/Video**：外链或 `assets/`
  - **互动版本 / Interactive version**：观众给“地点/职业/关键词”，Agent 生成新一版小品

---

### 约束 / Constraints
- **安全 / Safety**：默认运行安全；不执行破坏性操作；不提交密钥。
- **合规 / Compliance**：避免侵权与不当内容；如使用公开素材请标注来源。
- **可复现 / Reproducible**：尽量固定版本/种子；输出包含生成时间与版本信息（可选）。

---

### 节目说明（请填写）/ Show description (fill in)
- **标题 / Title**:
- **作者 / Authors**:
- **类型 / Sub-genre**: (家庭/职场/校园/科幻/古风/…)
- **角色数 / Cast size**:
- **时长 / Duration**: (e.g. 5–12 min text / 3–8 scenes)
- **主题 / Theme**:
- **亮点 / Highlights**:
- **使用的 Agent 能力 / Agent capabilities used**:

---

### 如何运行 / How to run
- **依赖 / Dependencies**:
- **运行命令 / Run command**:
- **输出 / Output**:

---

### 验收标准（建议）/ Acceptance criteria (suggested)
- **人物立得住 / Strong characters**：每个角色至少一个鲜明特征与一致口吻。
- **冲突推进 / Conflict progression**：每 1–2 场有推进或升级；至少一次反转或误会加深。
- **收束有落点 / Solid ending**：笑点之外有明确落点（温情/反思/反转回收）。
- **可复现 / Reproducible**：按 README 能生成同等结构的成品或报告。

---

### 投稿提示 / Submission hint
- **中文**：完成后将本模板文件夹复制/改名，放入 `shows/<show-id>-<short-title>/`，然后提 PR。
- **English**: Once done, copy/rename this folder into `shows/<show-id>-<short-title>/` and open a PR.

