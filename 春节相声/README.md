### 春节相声 / Crosstalk (Xiangsheng) — 创作要求（模板 / Template）

### 目标 / Goal
- **中文**：做一个“相声节目”模板：可以是双人相声、群口、单口（脱口秀风格也可）。鼓励用 Agent 做结构、包袱、梗回收、观众互动等。
- **English**: Create a crosstalk show template (two-person / ensemble / solo). Use agents for structure, punchlines, callbacks, and optional audience interaction.

---

### 交付物 / Deliverables
- **必需 / Required**
  - **`README.md`（本文件，需补全 / fill in）**
  - **台本 / Script**：`script.md`（建议按角色分栏或用明确标注）
  - **结构大纲 / Outline**：`outline.md`（段落、包袱点、回收点）
  - **可复现入口 / Reproducible entry**：`run.sh` 或 `Makefile` 或明确命令（生成台本/大纲/评测报告均可）
  - **期望输出 / Expected output**：例如生成 `out/script.md` + `out/score.json`
- **可选 / Optional**
  - **表演版 / Performance version**：口语化润色版、分镜/节奏点
  - **音频/视频 / Audio/Video**：外链或 `assets/`
  - **互动模式 / Interactive mode**：观众给关键词，Agent 即兴生成“现挂”

---

### 约束 / Constraints
- **安全与礼貌 / Safety & respect**
  - 禁止仇恨、骚扰、歧视、隐私泄露与违法内容。/ No hate/harassment/discrimination/privacy leakage/illegal content.
- **不要提交密钥 / No secrets**：API Key/Token 不得入仓。
- **可复现 / Reproducible**：请提供确定的运行方式与固定种子/版本（如果可能）。

---

### 节目说明（请填写）/ Show description (fill in)
- **标题 / Title**:
- **作者 / Authors**:
- **角色 / Roles**: (逗哏/捧哏/群口…)
- **时长 / Duration**: (e.g. 3–8 min text / 2–5 pages)
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
- **结构完整 / Complete arc**：起、承、转、合清楚；有至少 2 次“梗回收/呼应”。
- **可读可演 / Performable**：台词顺口、角色区分明确、节奏点标注清晰（可选）。
- **可复现 / Reproducible**：按 README 一次生成同等质量的产物或报告。

---

### 投稿提示 / Submission hint
- **中文**：完成后将本模板文件夹复制/改名，放入 `shows/<show-id>-<short-title>/`，然后提 PR。
- **English**: Once done, copy/rename this folder into `shows/<show-id>-<short-title>/` and open a PR.

