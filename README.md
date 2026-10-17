<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=180&section=header&fontSize=10&fontColor=ffffff" width="100%"/>

### YGtemple

在做 AI 应用、游戏和自动化工具

<br/>

<a href="#-ai-应用"><img src="https://img.shields.io/badge/AI%20%E5%BA%94%E7%94%A8-1a1a2e?style=for-the-badge&labelColor=0f3460" height="26" alt="AI 应用"/></a>
<a href="#-%E5%86%85%E5%AE%B9%E7%94%9F%E4%BA%A7"><img src="https://img.shields.io/badge/%E5%86%85%E5%AE%B9%E7%94%9F%E4%BA%A7-1a1a2e?style=for-the-badge&labelColor=0f3460" height="26" alt="内容生产"/></a>
<a href="#-%E5%B7%A5%E5%85%B7%E4%B8%8E%E8%84%9A%E6%9C%AC"><img src="https://img.shields.io/badge/%E5%B7%A5%E5%85%B7%E4%B8%8E%E8%84%9A%E6%9C%AC-1a1a2e?style=for-the-badge&labelColor=0f3460" height="26" alt="工具与脚本"/></a>
<a href="#-%E5%85%B6%E4%BB%96"><img src="https://img.shields.io/badge/%E5%85%B6%E4%BB%96-1a1a2e?style=for-the-badge&labelColor=0f3460" height="26" alt="其他"/></a>

</div>

---

<h2 id="-ai-应用" align="center">AI 应用</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

**[Viral-meme-gengbaike](https://github.com/YGtemple/Viral-meme-gengbaike)**

基于 LangGraph 与 FastAPI 的网络梗检索 Agent，接入了多个模型和搜索引擎。

实现上把模型调用、搜索、推理拆成三层，任意一家服务不可用时自动切到下一个。返回的 JSON 格式不规范时，由 `json_repair.py` 修补。

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" height="20"/>

</td>
<td width="50%" valign="top">

**[ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite)**

把 AI 短剧的制作流程拆成剧本、资产、分镜、视频生成几个阶段，每个阶段都有对应的工作方法和检查项。

`cases/` 里放了四部片子的实际制作记录。

<img src="https://img.shields.io/badge/AI%20Film-6A1B9A?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Storyboard-E65100?style=flat-square" height="20"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[video-prompt-master](https://github.com/YGtemple/video-prompt-master)**

四套视频提示词生成器，分别面向电商广告、古风写意、宏大叙事和动作场面。

<img src="https://img.shields.io/badge/Prompt-455A64?style=flat-square" height="20"/>

</td>
<td width="50%" valign="top">

**[rongyan](https://github.com/YGtemple/rongyan)**

英语写作批改的桌面端与网页端。

网页端支持多种考试的评分标准；桌面端用 Qt 实现了三栏布局、网络请求与本地状态保存，约 1300 行。

<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-内容生产" align="center">内容生产</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

**[word-sprite-quest](https://github.com/YGtemple/word-sprite-quest)**

Cocos Creator 3.8 做的微信小游戏，18 种玩法、5 档模式、240 关。

玩法层与数据层通过一份契约文档对齐，配置和关卡由脚本生成并校验，工具链放在 `tooling/` 里。

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Cocos%20Creator-55C2E1?style=flat-square" height="20"/>

</td>
<td width="50%" valign="top">

**[labyrinth-pathfinder](https://github.com/YGtemple/labyrinth-pathfinder)**

迷宫寻路的实现，包含几种算法和一组跑出来的性能对比数据。

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Pygame-2E7D32?style=flat-square" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-工具与脚本" align="center">工具与脚本</h2>

<br/>

<table align="center">
<tr>
<td width="33%" valign="top">

**[dsh-multi-router-intl](https://github.com/YGtemple/dsh-multi-router-intl)**

多模型请求的分发与切换，带依赖版本锁和变更记录。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/>

</td>
<td width="33%" valign="top">

**[pptx-generator](https://github.com/YGtemple/pptx-generator)**

用代码生成 PPT。把元素组织成树形结构，坐标逐层累加，省去手工计算位置。

另配一套 matplotlib 画图的脚本，用来生成算法图示。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

**[docx-generator](https://github.com/YGtemple/docx-generator)**

用代码生成 Word 文档，封装了标题、段落、表格、徽章等常用组件和中英文字体设置。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="20"/>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**[computelevelTWOC](https://github.com/YGtemple/computelevelTWOC)**

计算机等级考试的题库与刷题页面，题库和界面打包在同一个小文件里，双击就能用。

<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

**[agent-debug-notes](https://github.com/YGtemple/agent-debug-notes)**

整理了在不同 AI 工具里调试时遇到的问题和处理办法，涉及本地部署、构建和页面适配。

<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" height="20"/>

</td>
<td width="33%" valign="top">

**[zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify)**

一个表达训练产品的方案文档，包含产品范围、调研提纲和演示脚本。

<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" height="20"/>

</td>
</tr>
</table>

---

<h2 id="-其他" align="center">其他</h2>

<br/>

<details>
<summary><b>文档与研究</b></summary>

<br/>

| 仓库 | 内容 |
|---|---|
| [zhinengtiku](https://github.com/YGtemple/zhinengtiku) | 题库平台的架构文档，含战略、架构、接口、数据库、AI 服务、安全与运维 |
| [legal-ai-agent-research](https://github.com/YGtemple/legal-ai-agent-research) | 法律领域智能体的调研与方案 |
| [China-s-Smart-Agricultural-AI-Going-Global](https://github.com/YGtemple/China-s-Smart-Agricultural-AI-Going-Global) | 农业 AI 出海方向的整理 |

</details>

<details>
<summary><b>写作与编辑器</b></summary>

<br/>

| 仓库 | 内容 |
|---|---|
| [UItimateWriter](https://github.com/YGtemple/UItimateWriter) | 中文写作辅助，按场景区分的写作方法 |
| [wechat-longform-article](https://github.com/YGtemple/wechat-longform-article) | 公众号长文的排版模板 |
| [jianying-editor-skill](https://github.com/YGtemple/jianying-editor-skill) | 剪映的自动化操作 |
| [drama-storyboard-director](https://github.com/YGtemple/drama-storyboard-director) | 把剧本整理成镜头表 |
| [code-animation-playbook](https://github.com/YGtemple/code-animation-playbook) | 代码动画的渲染与音效脚本 |
| [ai-studio-yangzi](https://github.com/YGtemple/ai-studio-yangzi) | 影视制作相关的若干工具与项目模板 |

</details>

<details>
<summary><b>练习与记录</b></summary>

<br/>

| 仓库 | 内容 |
|---|---|
| [qt-learning](https://github.com/YGtemple/qt-learning) | Qt 练习，含表达式解析、定时器、网络与多线程 |
| [cpp-course-designs](https://github.com/YGtemple/cpp-course-designs) | C++ 课程设计，职工管理系统与通讯录 |
| [doubao-free](https://github.com/YGtemple/doubao-free) | 浏览器扩展 |
| [peini-manmanlai](https://github.com/YGtemple/peini-manmanlai) | 陪伴类小应用 |
| [jw-monitor](https://github.com/YGtemple/jw-monitor) | 选课状态监测 |
| [ComputeCommunicationAssociation](https://github.com/YGtemple/ComputeCommunicationAssociation) | 校园技术小组的页面 |
| [zhuxin](https://github.com/YGtemple/zhuxin) | 个人简历与作品集页面 |

</details>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=90&section=footer" width="100%"/>

</div>
