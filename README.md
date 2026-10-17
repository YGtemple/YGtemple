<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=190&section=header&text=YGtemple&fontSize=68&fontColor=ffffff&fontAlignY=40&desc=%E7%BF%BB%E8%AF%91%E4%B8%93%E4%B8%9A%20%C2%B7%20%E5%86%99%E4%BB%A3%E7%A0%81%20%C2%B7%20%E5%81%9A%20AI%20%E5%BA%94%E7%94%A8&descAlignY=60&descSize=15" width="100%"/>

<br/>

<a href="#-核心工程"><img src="https://img.shields.io/badge/%E6%A0%B8%E5%BF%83%E5%B7%A5%E7%A8%8B-1a1a2e?style=for-the-badge&labelColor=0f3460" height="28" alt="核心工程"/></a>
<a href="#-ai-%E5%86%85%E5%AE%B9%E7%94%9F%E4%BA%A7"><img src="https://img.shields.io/badge/AI%20%E5%86%85%E5%AE%B9%E7%94%9F%E4%BA%A7-1a1a2e?style=for-the-badge&labelColor=0f3460" height="28" alt="AI 内容生产"/></a>
<a href="#-工具%E4%B8%8E%E8%87%AA%E5%8A%A8%E5%8C%96"><img src="https://img.shields.io/badge/%E5%B7%A5%E5%85%B7%E4%B8%8E%E8%87%AA%E5%8A%A8%E5%8C%96-1a1a2e?style=for-the-badge&labelColor=0f3460" height="28" alt="工具与自动化"/></a>
<a href="#-%E6%8C%89%E7%B1%BB%E5%9E%8B%E6%89%BE"><img src="https://img.shields.io/badge/%E6%8C%89%E7%B1%BB%E5%9E%8B%E6%89%BE-1a1a2e?style=for-the-badge&labelColor=0f3460" height="28" alt="按类型找"/></a>

<br/><br/>

### 40 个公开仓库 · 5 种语言 · 从 AI Agent 到游戏引擎

**我把「能用」和「做得整齐」当成同一件事。**

所以这些项目大多不是一次性脚本，而是带着
`校验器` `契约文档` `版本约束` 的可维护工程。

</div>

<br/>

<div align="center">

| 语言 | 分布 | 仓库数 |
|:---|---:|:---:|
| **HTML** | `████████████████████████` | 7 |
| **Python** | `██████████████` | 4 |
| **JavaScript** | `██████████████` | 4 |
| **C++** | `███████` | 2 |
| **TypeScript** | `███` | 1 |
| **纯文档 / Skill** | `████████████████████████████████████████` | 22 |

</div>

---

<h2 id="-核心工程" align="center">🔬 核心工程</h2>

<div align="center"><sub>建议先看这几个 · 每一个都有可验证的技术纵深</sub></div>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [Viral-meme-gengbaike](https://github.com/YGtemple/Viral-meme-gengbaike)

**LangGraph + FastAPI 网络梗 Agent**

24 个 Python 模块 · 多 LLM 路由 · 多搜索源故障转移

| 模块 | 规模 | 职责 |
|:---|:---:|:---|
| `intelligence.py` | 26 KB | 推理主链 |
| `llm_providers.py` | 15.7 KB | 多模型适配 |
| `search_providers.py` | 15.1 KB | 多搜索源降级 |

> **看点是容错设计** —— 任一 provider 挂掉不影响整体，`json_repair.py` 专门处理 LLM 返回的残缺 JSON。

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" height="20"/>

</td>
<td width="50%" valign="top">

#### [labyrinth-pathfinder](https://github.com/YGtemple/labyrinth-pathfinder)

**迷宫寻路 · 算法实现 + 实测基准**

17 个模块 · 附 `benchmark_results.csv` · 带测试

| 模块 | 规模 | 职责 |
|:---|:---:|:---|
| `algorithms.py` | 4.2 KB | 算法与复杂度对比 |
| `states.py` | 11.9 KB | 完整状态机 |
| `hud.py` | 7.3 KB | 渲染与 HUD |

> **看点是数据** —— 性能数字是可复现跑出来的，不是估的。

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Pygame-2E7D32?style=flat-square" height="20"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [dsh-multi-router-intl](https://github.com/YGtemple/dsh-multi-router-intl)

**多模型路由器的工程规范样板**

| 文件 | 规模 |
|:---|:---:|
| `README.md` | 49 KB |
| `CHANGELOG.md` | 19.8 KB |
| `upstream-lock.json` | 版本锁 |

配 `THIRD_PARTY_NOTICES.md`、`CONTRIBUTING.md`、`DISCLAIMER.md` 全套。

> **看点是工程规范** —— 版本锁、上游依赖溯源、变更记录完整，是这堆仓库里流程最规范的一个。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" height="20"/>

</td>
<td width="50%" valign="top">

#### [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest)

**Cocos Creator 3.8 微信小游戏**

18 种玩法 · 5 档模式 · 240 关

休闲外壳 + 分级词汇训练内核 + 萌宠养成闭环。工具链已合并进 `tooling/`。

> **看点是多 AI 协同** —— 契约驱动开发，三个 AI 各管一块，靠 `CONTRACT.md` 冻结接口，用 `build.js` 的 14 个检查模块守边界。

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Cocos%20Creator-55C2E1?style=flat-square" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-ai-内容生产" align="center">🎬 AI 内容生产</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite)

**AI 短剧全链路制作套件**

`SKILL.md` **125 KB** —— 全仓最大的单文件，覆盖剧本 → 资产 → 分镜 → 视频生成完整链路。

`cases/` 下是四部真实片子的使用记录 —— **方法定义 + 实际案例放在一起**。

**四份案例各自的看点：**

| 片子 | 看点 |
|:---|:---|
| 反话 | 道具连续性表（白橡皮跨 10 场八个状态） |
| 国家的孩子 | 35 帧景别统计反推叙事重心 |
| 一会儿 | 把主观争议转成人称表 |
| 凝视的接力 | 评估维度里含 AI 可行性 |

<img src="https://img.shields.io/badge/AI%20Film-6A1B9A?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Storyboard-E65100?style=flat-square" height="20"/>

</td>
<td width="50%" valign="top">

#### [video-prompt-master](https://github.com/YGtemple/video-prompt-master)

**四大专项 AI 视频提示词生成器**

| 专项 | 风格 |
|:---|:---|
| 电商 TVC | 商业广告 |
| 宋式田园 | 古风写意 |
| 中式巨物 | 宏大叙事 |
| 高燃打斗 | 动作场面 |

**唯一有外部关注的项目**

<img src="https://img.shields.io/badge/%E2%98%85%203-FFD54F?style=flat-square&logoColor=black" height="20"/> <img src="https://img.shields.io/badge/Fork%201-90A4AE?style=flat-square" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-工具与自动化" align="center">🛠️ 工具与自动化</h2>

<br/>

<table align="center">
<tr>
<td width="33%" valign="top">

#### [computelevelTWOC](https://github.com/YGtemple/computelevelTWOC)

**计算机等级刷题系统**

`index.html` **9.3 MB 单文件**

七千余题，双击即用，零依赖零部署。

> **看点是极端取舍** —— 把所有题库、样式、逻辑塞进一个文件。工程上不优雅，但使用者成本为零。

<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

#### [pptx-generator](https://github.com/YGtemple/pptx-generator)

**程序化演示文稿生成**

虚拟节点树 + 绝对坐标扁平化，解决 pptxgenjs 手算坐标的问题。

配 matplotlib 算法可视化配图。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

#### [docx-generator](https://github.com/YGtemple/docx-generator)

**程序化 Word 文档生成**

自建样式令牌系统 + 表格 / 徽章 / 分隔线组件。

含中英文字体三槽位、无边框渲染等实操细节。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/>

</td>
</tr>
<tr>
<td width="33%" valign="top">

#### [rongyan](https://github.com/YGtemple/rongyan)

**融研智笔 · 英语写作智能体**

含 22 MB 决赛答辩 PPTX + Qt 桌面端 1300 行（三栏布局、网络请求、状态持久化）。

<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

#### [zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify)

**智言 · 路演表达训练平台策划**

2026 大创完整申报包：方向决策评分表、MVP 边界、调研设计、演示脚本禁语清单。

> **看点是不吹** —— 「不把准确率、用户数写成成果，除非有真实记录」。

<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

#### [agent-debug-notes](https://github.com/YGtemple/agent-debug-notes)

**Agent 调试经验手册**

从 Codex / Trae / WorkBuddy 三个 Agent 的 39 个真实会话里提炼的踩坑记录。

ComfyUI 部署、Cocos 构建、响应式布局。

<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-按类型找" align="center">📂 按类型找</h2>

<div align="center"><sub>新内容往哪放，看这四类</sub></div>

<br/>

<details>
<summary><b>A 类 · 架构设计文档包</b> &nbsp;—&nbsp; 完整的产品架构，通常是 HTML + docx 双版本</summary>

<br/>

| 仓库 | 内容 |
|---|---|
| [zhinengtiku](https://github.com/YGtemple/zhinengtiku) | 智能题库平台：6 套架构文档（战略 / 架构 / API / 数据库 / AI 服务 / 安全合规 / 运维）+ 圆桌评审 |

**新文档放法**：按 `0X-主题名称` 编号，HTML 与 docx 同名配对，不要打 zip 包。

</details>

<details>
<summary><b>B 类 · 调研与研究笔记</b> &nbsp;—&nbsp; 纯文本研究，无代码，结论与素材分开</summary>

<br/>

| 仓库 | 结构与放法 |
|---|---|
| [legal-ai-agent-research](https://github.com/YGtemple/legal-ai-agent-research) | `research/` 放原始调研，`report/` 放结论 |
| [China-s-Smart-Agricultural-AI-Going-Global](https://github.com/YGtemple/China-s-Smart-Agricultural-AI-Going-Global) | 单篇 README，内容还不多，可以继续扩充 |

**新的调研类内容**：放 `research/`；形成结论了再写 `report/`。

</details>

<details>
<summary><b>C 类 · 可执行的工具 / Skill</b> &nbsp;—&nbsp; 有代码或 SKILL.md，能直接跑或直接用</summary>

<br/>

| 仓库 | 实际内容 |
|---|---|
| [code-animation-playbook](https://github.com/YGtemple/code-animation-playbook) | `render.js` 46 KB + `sfx.py` + `metrics.py` + ROADMAP，代码动画渲染引擎 |
| [jianying-editor-skill](https://github.com/YGtemple/jianying-editor-skill) | `SKILL.md` 16.3 KB + `docs/` `prompts/` `rules/` 三目录，剪映自动化 |
| [UItimateWriter](https://github.com/YGtemple/UItimateWriter) | `ultimate-writing/` 技能包，中文写作系统 |
| [wechat-longform-article](https://github.com/YGtemple/wechat-longform-article) | `template.html` 31.5 KB，公众号长文排版模板 |
| [drama-storyboard-director](https://github.com/YGtemple/drama-storyboard-director) | `SKILL.md` + `references/`，剧本转分镜表 |
| [ai-studio-yangzi](https://github.com/YGtemple/ai-studio-yangzi) | 11 个影视 Skill + 项目模板 |

**新的 Skill 放法**：`SKILL.md` + `references/`（参考库）+ `docs/`（说明）。如果有可复用规则，单独开 `rules/`。

</details>

<details>
<summary><b>D 类 · 学习记录</b> &nbsp;—&nbsp; 技术学习过程的笔记与练习代码</summary>

<br/>

| 仓库 | 内容 |
|---|---|
| [qt-learning](https://github.com/YGtemple/qt-learning) | Qt6 练习集，含手写表达式解析与跨线程隐患分析 |
| [cpp-course-designs](https://github.com/YGtemple/cpp-course-designs) | C++ 课程设计（职工管理、通讯录） |
| [doubao-free](https://github.com/YGtemple/doubao-free) | 浏览器扩展源码研读 |
| [peini-manmanlai](https://github.com/YGtemple/peini-manmanlai) | 陪伴类应用实践 |
| [jw-monitor](https://github.com/YGtemple/jw-monitor) | 选课监测脚本 |
| [ComputeCommunicationAssociation](https://github.com/YGtemple/ComputeCommunicationAssociation) | 校园 AI 小组官网 |
| [zhuxin](https://github.com/YGtemple/zhuxin) | 单文件静态简历与作品集 |

</details>

---

<h2 id="-我的工作方式" align="center">💡 我的工作方式</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

**1 · 契约先行**

多个 AI 协同做一件事时，先把接口冻成 `CONTRACT.md`，再用校验脚本守住它。

改契约要升版本号，不能悄悄改。

<br/>

**2 · 把设计意图写成可验证的断言**

「体力不足必须给免费入口，不能硬阻塞」—— 这条不是写在文档里就算，`validate_meta.js` 会检查 `redLine` 字段还在不在。

</td>
<td width="50%" valign="top">

**3 · 保留错误的痕迹**

学习记录里注释掉的试错代码、`v1 误写单眼皮作废` 这种修正说明，比正确版本更能说明问题在哪。

<br/>

**4 · 不写没验证过的数字**

不把准确率、用户数、营收写成成果，除非有真实记录。

</td>
</tr>
</table>

---

<h2 id="-仓库整理说明" align="center">🧹 仓库整理说明</h2>

<br/>

**已合并的重复仓库**（原仓库保留为归档，README 已标注指向新位置）

| 原仓库 | 并入 |
|:---|:---|
| `word-sprite-quest-tooling` | [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest) `tooling/` |
| `word-sprite-quest-v13-toolchain` | [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest) `tooling/config/` |
| `ai-film-production` | [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite) `cases/` |
| `ai-drama-asset-prompts` | [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite) `cases/` |

> **合并原则**：只有同一方法体系的「定义」与「案例」、或同一个项目被拆开的产物才合并。内容不相干的仓库各自独立，不硬凑。

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Translation-1a1a2e?style=for-the-badge" height="26"/>
<img src="https://img.shields.io/badge/AI%20Engineering-16213e?style=for-the-badge" height="26"/>
<img src="https://img.shields.io/badge/Game%20Dev-0f3460?style=for-the-badge" height="26"/>

<br/><br/>

<sub>翻译专业 · 关注 AI 应用工程化 · 欢迎交流</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

</div>
