<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFF0F5,100:F7A8C4&height=190&section=header&fontSize=10" width="100%"/>

<img src="https://img.shields.io/badge/YGtemple-C2185B?style=for-the-badge&labelColor=F7A8C4" height="34"/>

<br/>

<sub>在做 AI 应用、游戏和自动化工具</sub>

<br/>

<a href="README.md"><img src="https://img.shields.io/badge/English-C2185B?style=flat-square&labelColor=FCE4EC" height="22" alt="English"/></a>

<br/><br/>

<a href="#ai-工具"><img src="https://img.shields.io/badge/AI%20%E5%B7%A5%E5%85%B7-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="AI 工具"/></a>
<a href="#ai-应用"><img src="https://img.shields.io/badge/AI%20%E5%BA%94%E7%94%A8-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="AI 应用"/></a>
<a href="#影视与内容"><img src="https://img.shields.io/badge/%E5%BD%B1%E8%A7%86%E4%B8%8E%E5%86%85%E5%AE%B9-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="影视与内容"/></a>
<a href="#游戏"><img src="https://img.shields.io/badge/%E6%B8%B8%E6%88%8F-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="游戏"/></a>
<a href="#其他"><img src="https://img.shields.io/badge/%E5%85%B6%E4%BB%96-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="其他"/></a>

</div>

<br/>

---

<h2 id="ai-工具" align="center">🌸 AI 工具</h2>

<sub>把重复的活交给脚本——路由、文档、演示、素材</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [dsh-multi-router-intl](https://github.com/YGtemple/dsh-multi-router-intl)

<sub>`TypeScript`</sub>

让模型的请求能在多个客户端之间分发和切换，包括 WorkBuddy 的国际版。

国际版的登录流程、接口地址、会话续期都和国内版不同。实现上把每个客户端压成一份描述，分发层不认识任何具体产品——后来接 Trae 时只加了一份描述，路由代码没动。

</td>
<td width="50%" valign="top">

#### [Viral-meme-gengbaike](https://github.com/YGtemple/Viral-meme-gengbaike)

<sub>`Python` `LangGraph` `FastAPI`</sub>

网络梗检索 Agent，接入了多个模型和搜索引擎。

把模型调用、搜索、推理拆成三层，任意一家服务不可用时自动切到下一个。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [pptx-generator](https://github.com/YGtemple/pptx-generator)

<sub>`JavaScript` `Python`</sub>

用代码生成 PPT。把元素组织成树形结构，坐标逐层累加，省去手工计算位置。

另配一套 matplotlib 画图的脚本，用来生成算法图示。

</td>
<td width="50%" valign="top">

#### [docx-generator](https://github.com/YGtemple/docx-generator)

<sub>`JavaScript`</sub>

用代码生成 Word 文档，封装了标题、段落、表格、徽章等常用组件和中英文字体设置。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [video-prompt-master](https://github.com/YGtemple/video-prompt-master)

<sub>`Prompt`</sub>

四套视频提示词生成器，分别面向电商广告、古风写意、宏大叙事和动作场面。

</td>
<td width="50%" valign="top">

#### [agent-debug-notes](https://github.com/YGtemple/agent-debug-notes)

<sub>`Markdown`</sub>

整理了在不同 AI 工具里调试时遇到的问题和处理办法，涉及本地部署、构建和页面适配。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [dsh-engineering-notes](https://github.com/YGtemple/dsh-engineering-notes)

<sub>`Markdown`</sub>

接入第三方服务时的调试记录，包括传输层排查、插件结构和 Windows 下的部署修复。

</td>
<td width="50%" valign="top">

#### [academic-skills-max](https://github.com/YGtemple/academic-skills-max)

<sub>`Skill`</sub>

8 个学术类技能的选型与串联说明。

</td>
</tr>
</table>

---

<h2 id="ai-应用" align="center">🌸 AI 应用</h2>

<sub>带完整交互的产品</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [rongyan](https://github.com/YGtemple/rongyan)

<sub>`HTML` `C++`</sub>

英语写作批改的桌面端与网页端。

网页端支持多种考试的评分标准；桌面端用 Qt 实现了三栏布局、网络请求与本地状态保存，约 1300 行。

</td>
<td width="50%" valign="top">

#### [zhixu](https://github.com/YGtemple/zhixu)

<sub>`HTML`</sub>

离线优先的日程助手，支持多视图、周期任务和自然语言录入。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [zhiyan](https://github.com/YGtemple/zhiyan)

<sub>`HTML`</sub>

表达训练系统的设计集，包含 17 项表达画像、评分标准和进步流的设计文档。

</td>
<td width="50%" valign="top">

#### [zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify)

<sub>`Markdown` `Python`</sub>

一个表达训练产品的方案文档，包含产品范围、调研提纲和演示脚本。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [changlong](https://github.com/YGtemple/changlong)

<sub>`HTML`</sub>

长隆主题公园的 AI 智慧伴游方案，分游前、游中、游后三个阶段。

</td>
<td width="50%" valign="top">

#### [YGknowledgeBase](https://github.com/YGtemple/YGknowledgeBase)

<sub>`CSS`</sub>

双语 AI 术语知识库，每个术语配通俗解释和可直接复制的提问模板。

</td>
</tr>
</table>

---

<h2 id="影视与内容" align="center">🌸 影视与内容</h2>

<sub>从剧本到成片，以及围绕它的工具</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite)

<sub>`AI Film` `Storyboard`</sub>

把 AI 短剧的制作流程拆成剧本、资产、分镜、视频生成几个阶段，每个阶段都有对应的工作方法和检查项。

`cases/` 里放了四部片子的实际制作记录。

</td>
<td width="50%" valign="top">

#### [ai-story-vault](https://github.com/YGtemple/ai-story-vault)

<sub>`Python`</sub>

爆款故事短片的素材库，把案例整理成可检索的结构，用起来会越积越多。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [jianying-editor-skill](https://github.com/YGtemple/jianying-editor-skill)

<sub>`Skill`</sub>

剪映的自动化操作，附带规则与提示词。

</td>
<td width="50%" valign="top">

#### [drama-storyboard-director](https://github.com/YGtemple/drama-storyboard-director)

<sub>`Skill`</sub>

把剧本整理成镜头表，按 15 秒分段。

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [ai-studio-yangzi](https://github.com/YGtemple/ai-studio-yangzi)

<sub>`Skill` `Python`</sub>

影视制作的工具与项目模板，包含 11 个 Skill 和跨平台安装脚本。

</td>
<td width="50%" valign="top">

#### [code-animation-playbook](https://github.com/YGtemple/code-animation-playbook)

<sub>`JavaScript` `Python`</sub>

代码动画的渲染与音效脚本。

</td>
</tr>
</table>

---

<h2 id="游戏" align="center">🌸 游戏</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest)

<sub>`TypeScript` `Cocos Creator 3.8`</sub>

微信小游戏，18 种玩法、5 档模式、240 关。

玩法层与数据层通过一份契约文档对齐，配置和关卡由脚本生成并校验，工具链放在 `tooling/` 里。

</td>
<td width="50%" valign="top">

#### [labyrinth-pathfinder](https://github.com/YGtemple/labyrinth-pathfinder)

<sub>`Python` `Pygame`</sub>

迷宫寻路的实现，包含五种算法和一组跑出来的性能对比数据。

</td>
</tr>
</table>

---

<h2 id="其他" align="center">🌸 其他</h2>

<br/>

<table align="center">
<tr>
<td width="33%" valign="top">

**文档与研究**

[zhinengtiku](https://github.com/YGtemple/zhinengtiku)<br/><sub>题库平台的架构文档</sub>

[legal-ai-agent-research](https://github.com/YGtemple/legal-ai-agent-research)<br/><sub>法律领域智能体的调研与方案</sub>

[China-s-Smart-Agricultural-AI-Going-Global](https://github.com/YGtemple/China-s-Smart-Agricultural-AI-Going-Global)<br/><sub>农业 AI 出海方向的整理</sub>

</td>
<td width="33%" valign="top">

**写作与编辑器**

[UItimateWriter](https://github.com/YGtemple/UItimateWriter)<br/><sub>中文写作辅助</sub>

[wechat-longform-article](https://github.com/YGtemple/wechat-longform-article)<br/><sub>公众号长文排版</sub>

[qt-learning](https://github.com/YGtemple/qt-learning)<br/><sub>Qt 练习</sub>

[cpp-course-designs](https://github.com/YGtemple/cpp-course-designs)<br/><sub>C++ 课程设计</sub>

</td>
<td width="33%" valign="top">

**练习与记录**

[computelevelTWOC](https://github.com/YGtemple/computelevelTWOC)<br/><sub>等级考试题库</sub>

[doubao-free](https://github.com/YGtemple/doubao-free)<br/><sub>浏览器扩展</sub>

[peini-manmanlai](https://github.com/YGtemple/peini-manmanlai)<br/><sub>成长站点</sub>

[jw-monitor](https://github.com/YGtemple/jw-monitor)<br/><sub>选课状态监测</sub>

[virginia-woolf-presentation](https://github.com/YGtemple/virginia-woolf-presentation)<br/><sub>课堂演讲演示</sub>

[ComputeCommunicationAssociation](https://github.com/YGtemple/ComputeCommunicationAssociation)<br/><sub>校园技术小组页面</sub>

[zhuxin](https://github.com/YGtemple/zhuxin)<br/><sub>个人简历与作品集</sub>

</td>
</tr>
</table>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7A8C4,100:FFF0F5&height=100&section=footer" width="100%"/>

</div>
