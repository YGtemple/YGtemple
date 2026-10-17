# 你好，我是 YGtemple 👋

> 翻译专业，写代码。做 AI 应用、游戏、自动化工具。

我把「能用」和「做得整齐」当成同一件事——所以这些仓库里的项目，大多不是一次性脚本，而是带着校验器、契约文档、版本约束的可维护工程。

下面按**技术深度**排序，不按 star 数。

---

## 🔬 一、核心工程（建议先看这几个）

<table>
<tr>
<td width="50%" valign="top">

### [Viral-meme-gengbaike](https://github.com/YGtemple/Viral-meme-gengbaike)
**LangGraph + FastAPI 网络梗 Agent**

24 个 Python 模块，多 LLM 路由 + 多搜索源故障转移。核心逻辑分三层：

- `intelligence.py`（26 KB）— 推理主链
- `llm_providers.py`（15.7 KB）— 多模型适配
- `search_providers.py`（15.1 KB）— 多搜索源降级

**看点是容错设计**：任一 provider 挂掉不影响整体，`json_repair.py` 专门处理 LLM 返回的残缺 JSON。

`Python`

</td>
<td width="50%" valign="top">

### [labyrinth-pathfinder](https://github.com/YGtemple/labyrinth-pathfinder)
**迷宫寻路：算法实现 + 实测基准**

17 个模块，附 `benchmark_results.csv` 真实性能数据与 `tests/`。

不是「跑起来就行」的演示——`algorithms.py` 里各算法的复杂度差异有实测对比，`states.py`（11.9 KB）做完整状态机管理。

**看点是数据**：性能数字是可复现跑出来的，不是估的。

`Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [dsh-multi-router-intl](https://github.com/YGtemple/dsh-multi-router-intl)
**多模型路由器的工程规范样板**

README **49 KB**、CHANGELOG **19.8 KB**，配 `upstream-lock.json`、`THIRD_PARTY_NOTICES.md`、CONTRIBUTING、DISCLAIMER 全套。

**看点是工程规范**：版本锁、上游依赖溯源、变更记录完整。是这堆仓库里流程最规范的一个。

`JavaScript`

</td>
<td width="50%" valign="top">

### [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest)
**Cocos Creator 3.8 微信小游戏**

18 种玩法 / 5 档模式 / 240 关，休闲外壳 + 分级词汇训练内核 + 萌宠养成闭环。工具链已合并进来（`tooling/`）。

**看点是多 AI 协同**：契约驱动开发——三个 AI 各管一块，靠 `CONTRACT.md` 冻结接口，用 `build.js` 的 14 个检查模块守边界。

`TypeScript`

</td>
</tr>
</table>

---

## 🎬 二、AI 内容生产

<table>
<tr>
<td width="50%" valign="top">

### [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite)
**AI 短剧全链路制作套件**

`SKILL.md` **125 KB** —— 全仓最大的单文件，覆盖剧本 → 资产 → 分镜 → 视频生成完整链路。

`cases/` 下是四部真实片子的使用记录（《反话》《国家的孩子》《一会儿》《凝视的接力》）——**方法定义 + 实际案例放在一起**。

**看点是那四份案例**：跨龄面容一致性、道具连续性表、人称表、25 部影片手法矩阵。

</td>
<td width="50%" valign="top">

### [video-prompt-master](https://github.com/YGtemple/video-prompt-master)
**四大专项 AI 视频提示词生成器**

电商 TVC / 宋式田园 / 中式巨物 / 高燃打斗四套。

**唯一有外部关注的项目**（3 star / 1 fork）。

</td>
</tr>
</table>

---

## 🛠️ 三、工具与自动化

<table>
<tr>
<td width="50%" valign="top">

### [computelevelTWOC](https://github.com/YGtemple/computelevelTWOC)
**计算机等级考试刷题系统**

`index.html` **9.3 MB 单文件**，七千余题双击即用，零依赖零部署。

**看点是极端取舍**：把所有题库、样式、逻辑塞进一个文件。工程上不优雅，但使用者成本为零。

`HTML`

</td>
<td width="50%" valign="top">

### [rongyan](https://github.com/YGtemple/rongyan)
**融研智笔 · 英语写作智能体**

含 22 MB 决赛答辩 PPTX + Qt 桌面端（1300 行，三栏布局、网络请求、状态持久化）。

`HTML` `C++`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [pptx-generator](https://github.com/YGtemple/pptx-generator)
**程序化演示文稿生成**

虚拟节点树 + 绝对坐标扁平化，解决 pptxgenjs 手算坐标的问题。配 matplotlib 算法可视化。

`JavaScript` `Python`

</td>
<td width="50%" valign="top">

### [docx-generator](https://github.com/YGtemple/docx-generator)
**程序化 Word 文档生成**

自建样式令牌系统 + 表格/徽章/分隔线组件。含中英文字体三槽位、无边框渲染等实操细节。

`JavaScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify)
**智言 · 路演表达训练平台策划**

2026 大创完整申报包：方向决策评分表、MVP 边界、调研设计、演示脚本禁语清单。

**看点是不吹**：「不把准确率、用户数写成成果，除非有真实记录」。

</td>
<td width="50%" valign="top">

### [agent-debug-notes](https://github.com/YGtemple/agent-debug-notes)
**Agent 调试经验手册**

从 Codex/Trae/WorkBuddy 三个 Agent 的 39 个真实会话里提炼的踩坑记录。ComfyUI 部署、Cocos 构建、响应式布局。

</td>
</tr>
</table>

---

## 📂 四、按类型找（新内容往哪放）

### A 类 · 架构设计文档包

完整的产品架构文档，通常是 HTML + docx 双版本。

| 仓库 | 内容 |
|---|---|
| [zhinengtiku](https://github.com/YGtemple/zhinengtiku) | 智能题库平台：6 套架构文档（战略/架构/API/数据库/AI服务/安全合规/运维）+ 圆桌评审 |

**新文档放法**：按 `0X-主题名称` 编号，HTML 与 docx 同名配对，不要打 zip 包。

### B 类 · 调研与研究笔记

纯文本研究，无代码。结论与原始素材分开放。

| 仓库 | 结构与放法 |
|---|---|
| [legal-ai-agent-research](https://github.com/YGtemple/legal-ai-agent-research) | `research/` 放原始调研，`report/` 放结论 |
| [China-s-Smart-Agricultural-AI-Going-Global](https://github.com/YGtemple/China-s-Smart-Agricultural-AI-Going-Global) | 单篇 README，内容还不多，可以继续扩充 |

**新的调研类内容**：放 `research/`；形成结论了再写 `report/`。

### C 类 · 可执行的工具 / Skill

有代码或 `SKILL.md`，能直接跑或直接用。

| 仓库 | 实际内容 |
|---|---|
| [code-animation-playbook](https://github.com/YGtemple/code-animation-playbook) | `render.js` 46 KB + `sfx.py` + `metrics.py` + ROADMAP，代码动画渲染引擎 |
| [jianying-editor-skill](https://github.com/YGtemple/jianying-editor-skill) | `SKILL.md` 16.3 KB + `docs/` `prompts/` `rules/` 三目录，剪映自动化 |
| [UItimateWriter](https://github.com/YGtemple/UItimateWriter) | `ultimate-writing/` 技能包，中文写作系统 |
| [wechat-longform-article](https://github.com/YGtemple/wechat-longform-article) | `template.html` 31.5 KB，公众号长文排版模板 |
| [drama-storyboard-director](https://github.com/YGtemple/drama-storyboard-director) | `SKILL.md` + `references/`，剧本转分镜表 |
| [ai-studio-yangzi](https://github.com/YGtemple/ai-studio-yangzi) | 11 个影视 Skill + 项目模板 |

**新的 Skill 放法**：`SKILL.md` + `references/`（参考库）+ `docs/`（说明）。如果有可复用规则，单独开 `rules/`。

### D 类 · 学习记录

技术学习过程的笔记与练习代码。

| 仓库 | 内容 |
|---|---|
| [qt-learning](https://github.com/YGtemple/qt-learning) | Qt6 练习集，含手写表达式解析与跨线程隐患分析 |
| [cpp-course-designs](https://github.com/YGtemple/cpp-course-designs) | C++ 课程设计（职工管理、通讯录） |
| [doubao-free](https://github.com/YGtemple/doubao-free) | 浏览器扩展源码研读 |
| [peini-manmanlai](https://github.com/YGtemple/peini-manmanlai) | 陪伴类应用实践 |
| [jw-monitor](https://github.com/YGtemple/jw-monitor) | 选课监测脚本 |
| [ComputeCommunicationAssociation](https://github.com/YGtemple/ComputeCommunicationAssociation) | 校园 AI 小组官网 |
| [zhuxin](https://github.com/YGtemple/zhuxin) | 单文件静态简历与作品集 |

---

## 我的工作方式

**1. 契约先行。** 多个 AI 协同做一件事时，先把接口冻成 `CONTRACT.md`，再用校验脚本守住它。改契约要升版本号，不能悄悄改。

**2. 把设计意图写成可验证的断言。** 比如游戏里「体力不足必须给免费入口，不能硬阻塞」——这条不是写在文档里就算，`validate_meta.js` 会检查 `redLine` 字段还在不在。

**3. 保留错误的痕迹。** 学习记录里注释掉的试错代码、`v1 误写单眼皮作废` 这种修正说明，比正确版本更能说明问题在哪。

**4. 不写没验证过的数字。** 大创材料里明确要求：不把准确率、用户数、营收写成成果，除非有真实记录。

---

## 仓库整理说明

**已合并的重复仓库**（原仓库保留为归档，README 已标注指向新位置）：

| 原仓库 | 并入 |
|---|---|
| `word-sprite-quest-tooling` | [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest) `tooling/` |
| `word-sprite-quest-v13-toolchain` | [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest) `tooling/config/` |
| `ai-film-production` | [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite) `cases/` |
| `ai-drama-asset-prompts` | [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite) `cases/` |

合并原则：**只有同一方法体系的「定义」与「案例」、或同一个项目被拆开的产物才合并**。内容不相干的仓库各自独立，不硬凑。

---

<sub>翻译专业 · 关注 AI 应用工程化 · 欢迎交流</sub>
