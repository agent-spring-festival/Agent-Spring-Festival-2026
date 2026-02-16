### 开场歌曲 / Opening Song — 创作要求（模板 / Template）

### 目标 / Goal
- **中文**：做一个“能开场”的 Agent 歌曲节目：可以是主题曲、合唱、串烧、或带互动的开场秀。重点是**可复现**与**可展示**。
- **English**: Create an “opening-ready” agent-powered song show (theme song / chorus / medley / interactive opener). Prioritize **reproducibility** and **presentability**.

---

### 交付物 / Deliverables
- **必需 / Required**
  - **`README.md`（本文件，需补全 / fill in）**
  - **歌词 / Lyrics**：`lyrics.md`（中英不限，建议标注段落/主副歌）
  - **生成方式 / Generation method**：清晰说明使用的模型/工具/提示词与参数（可放 `prompts/`）
  - **可复现入口 / Reproducible entry**：`run.sh` 或 `Makefile` 或明确命令
  - **期望输出 / Expected output**：运行后会生成什么（例如：歌词文件、音频文件、MIDI、分轨说明、或一份报告）
- **可选 / Optional**
  - **音频 / Audio**：`audio/`（如体积过大请外链，并在 README 标注）
  - **伴奏/谱 / Instrumental / Score**：MIDI/简谱/和弦进行
  - **舞台说明 / Stage direction**：开场口播、灯光/节奏点、互动段落

---

### 约束 / Constraints
- **安全 / Safety**：不得提交任何密钥（API Key/Token）。运行脚本默认应安全（不做破坏性操作）。
- **版权 / Copyright**：若引用旋律/素材/采样，请明确来源与授权；尽量使用原创或可自由使用素材。
- **成本 / Cost**：若调用付费 API，请提供离线/降级方案（例如只生成歌词、或用本地模型）。

---

### 节目说明（请填写）/ Show description (fill in)
- **标题 / Title**:
- **作者 / Authors**:
- **风格 / Style**: (pop/rap/folk/opera/EDM/…)
- **时长 / Duration**: (e.g. 60–180s)
- **亮点 / Highlights**:
- **使用的 Agent 能力 / Agent capabilities used**: (planning/tools/music generation/voice synthesis/…)

---

### 如何运行 / How to run
> 目标是“一条命令可复现”。/ Aim for one-command reproducibility.

- **依赖 / Dependencies**:
  - (e.g. Python/Node/Docker + package list)
- **运行命令 / Run command**:
  - (e.g. `bash run.sh`)
- **输出 / Output**:
  - (e.g. `out/lyrics.txt`, `out/report.md`, `audio/demo.mp3`)

---

### 验收标准（建议）/ Acceptance criteria (suggested)
- **可复现 / Reproducible**：维护者在干净环境能按 README 跑通或得到同等输出。
- **可展示 / Presentable**：结果适合在发布日展示（文本/音频/视频任一形式）。
- **说明清晰 / Clear docs**：读者能理解你做了什么、为什么有趣、如何复现。

---

### 投稿提示 / Submission hint
- **中文**：完成后将本模板文件夹复制/改名，放入 `shows/<show-id>-<short-title>/`，然后提 PR。
- **English**: Once done, copy/rename this folder into `shows/<show-id>-<short-title>/` and open a PR.

