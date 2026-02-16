### Agent 春晚 2026 — 开场歌曲统一 Prompt / Universal Opening Song Prompt

### 使用说明 / How to use
- **中文**：把下面的 **User Prompt** 原样粘贴到任意模型；只修改“参数区”即可。为公平对比，不要再追加额外要求。
- **English**: Paste the **User Prompt** into any model; only edit the “Parameters” section. For fairness, don’t add extra constraints beyond that.

---

### 可选的 System Prompt（如平台支持）/ Optional System Prompt (if supported)
你是一个严谨的音乐节目策划与歌词创作助手。你输出的内容必须可执行、结构清晰、便于舞台呈现；避免侵权与不当内容；不要泄露或索取任何密钥。  
You are a rigorous music show planner and lyric-writing assistant. Your output must be actionable, well-structured, stage-ready; avoid copyright issues and unsafe content; do not request or reveal secrets.

---

### User Prompt（复制这段）/ User Prompt (copy this)

你要为一个开源活动“Agent 春晚 2026（GitHub Edition）”创作一首**开场歌曲**。请严格按以下要求输出，并用指定格式排版。

#### Parameters（只改这里 / only edit here）
- Date: 2026-02-16 (Lunar New Year’s Eve)
- Theme: Spring Festival + Year of the Horse (马年)
- Duration target: 90–120 seconds
- Language: Chinese-dominant, allow 10–30% English lines (optional)
- Style: modern pop with festive elements (可替换为：rap / folk / EDM / rock / choral)
- Audience: open-source builders, agent developers, creators
- Constraints:
  - Must be original; **do not** imitate any specific singer/band; **do not** quote existing copyrighted lyrics/melodies
  - No hate/harassment/illegal content; keep it warm, inclusive, celebratory

#### Task
请生成一个“可上台就能演”的开场节目方案，包含：
1) **Opening VO（开场口播）**：20–40 秒，可由主持人或合唱团引入；要提到 GitHub、开源协作、以及“今晚开场”的氛围。
2) **Lyrics（歌词）**：必须包含明确段落结构（例如：Intro / Verse 1 / Pre-Chorus / Chorus / Bridge / Final Chorus / Outro）。
3) **Musical plan（音乐方案）**：给出建议的 BPM、调性（Key）、和弦进行（每段至少 1 条）、配器建议（鼓/贝斯/吉他/唢呐或锣鼓点等“年味”元素任选）。
4) **Stage plan（舞台方案）**：灯光、视觉（LED 文案）、以及一个 call-and-response 互动点（观众一句口号即可）。
5) **Reproducibility note（可复现说明）**：列出“如果别的模型用同样 Prompt，哪些部分应保持一致、哪些允许变化”，用 5 条要点说明。

#### Content requirements（内容硬性要求）
- Spring Festival imagery: 至少 6 个不同意象（例：灯笼/春联/年夜饭/拜年/红包/团圆/烟花/爆竹/饺子/福字/舞龙舞狮…）
- Horse-year motif: 至少 2 处与马相关的意象（例：骏马/奔腾/千里/踏春/马到成功…）
- Open-source/Agent motif: 必须出现“open source / 开源”和“agent / 智能体”相关表达各至少 1 次（可中英混用）
- Hook: 副歌必须有一句**可被观众合唱**的口号式短句（≤ 12 个汉字或 ≤ 8 个英文词），并在歌词中重复至少 2 次

#### Output format（严格按此格式输出）
输出必须是 Markdown，并包含以下一级标题（顺序不变）：
1. # Opening VO
2. # Lyrics
3. # Musical Plan
4. # Stage Plan
5. # Reproducibility Note

在 “Lyrics” 里，用二级标题标注段落（例如：## Verse 1）。  
在 “Musical Plan” 里，和弦用简写（例如：C - G - Am - F）。  
不要输出任何额外解释、免责声明或“作为 AI…”之类的话。

