<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFF0F5,100:F7A8C4&height=190&section=header&fontSize=10" width="100%"/>

<img src="https://img.shields.io/badge/YGtemple-C2185B?style=for-the-badge&labelColor=F7A8C4" height="34"/>

<br/>

<sub>Building AI applications, games and automation tools</sub>

<br/>

<a href="README.zh-CN.md"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-C2185B?style=flat-square&labelColor=FCE4EC" height="22" alt="简体中文"/></a>

<br/><br/>

<a href="#ai-tools"><img src="https://img.shields.io/badge/AI%20TOOLS-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="AI Tools"/></a>
<a href="#ai-applications"><img src="https://img.shields.io/badge/AI%20APPLICATIONS-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="AI Applications"/></a>
<a href="#film--content"><img src="https://img.shields.io/badge/FILM%20%26%20CONTENT-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="Film & Content"/></a>
<a href="#games"><img src="https://img.shields.io/badge/GAMES-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="Games"/></a>
<a href="#more"><img src="https://img.shields.io/badge/MORE-C2185B?style=flat-square&labelColor=FCE4EC" height="24" alt="More"/></a>

</div>

<br/>

---

<h2 id="ai-tools" align="center">🌸 AI Tools</h2>

<sub>Automating the repetitive work — routing, documents, prompts</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [dsh-multi-router-intl](https://github.com/YGtemple/dsh-multi-router-intl)

<sub>`TypeScript`</sub>

Routes model requests across several clients, including WorkBuddy's international build.

International login, endpoints and session refresh all differ from the domestic build. Each client is reduced to one declarative entry, so the router knows no product by name — adding Trae later took one entry and no routing changes.

</td>
<td width="50%" valign="top">

#### [Viral-meme-gengbaike](https://github.com/YGtemple/Viral-meme-gengbaike)

<sub>`Python` `LangGraph` `FastAPI`</sub>

A meme-retrieval agent wired to multiple models and search engines.

Model calls, search and reasoning sit in three separate layers; when any provider fails the next one takes over.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [pptx-generator](https://github.com/YGtemple/pptx-generator)

<sub>`JavaScript` `Python`</sub>

Generates presentations in code. Elements form a tree and coordinates accumulate down the levels, so positions never need manual arithmetic.

Ships with a matplotlib script that draws the accompanying algorithm diagrams.

</td>
<td width="50%" valign="top">

#### [docx-generator](https://github.com/YGtemple/docx-generator)

<sub>`JavaScript`</sub>

Generates Word documents in code — headings, paragraphs, tables and badges are components, with Chinese/English font slots handled explicitly.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [video-prompt-master](https://github.com/YGtemple/video-prompt-master)

<sub>`Prompt`</sub>

Four prompt generators for video: commercial TVC, Song-dynasty pastoral, monumental Chinese, and high-energy action.

</td>
<td width="50%" valign="top">

#### [agent-debug-notes](https://github.com/YGtemple/agent-debug-notes)

<sub>`Markdown`</sub>

Notes on problems hit while working inside various AI tools — local deployment, builds and page adaptation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [dsh-engineering-notes](https://github.com/YGtemple/dsh-engineering-notes)

<sub>`Markdown`</sub>

Debugging notes from integrating third-party providers: transport-level investigation, plugin structure, and deployment repair on Windows.

</td>
<td width="50%" valign="top">

#### [academic-skills-max](https://github.com/YGtemple/academic-skills-max)

<sub>`Skill`</sub>

How to pick between and chain together eight academic skills.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [10router-multi-account-gateway](https://github.com/YGtemple/10router-multi-account-gateway)

<sub>`JavaScript`</sub>

Brings WorkBuddy, Trae and other platform accounts behind one OpenAI-compatible API.

Per-account scheduling, auto check-in, points sync and a monitoring dashboard are built in. Routing rules pick the next account when one is exhausted.

</td>
<td width="50%" valign="top"></td>
</tr>
</table>

---

<h2 id="ai-applications" align="center">🌸 AI Applications</h2>

<sub>Products with full interaction</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [rongyan](https://github.com/YGtemple/rongyan)

<sub>`HTML` `C++`</sub>

English writing feedback, as both a desktop app and a web page.

The web side carries scoring criteria for several exams; the desktop side is Qt — three-column layout, network requests, local state persistence, about 1,300 lines.

</td>
<td width="50%" valign="top">

#### [zhixu](https://github.com/YGtemple/zhixu)

<sub>`HTML`</sub>

An offline-first schedule assistant with multiple views, recurring tasks and natural-language entry.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [zhiyan](https://github.com/YGtemple/zhiyan)

<sub>`HTML`</sub>

Design set for a speech-training system: 17 expression profiles, scoring criteria, and the progress-flow design documents.

</td>
<td width="50%" valign="top">

#### [zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify)

<sub>`Markdown` `Python`</sub>

A product proposal for speech training — scope, research outline and demo script.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [changlong](https://github.com/YGtemple/changlong)

<sub>`HTML`</sub>

An AI park-guide proposal for Chimelong, split into before, during and after the visit.

</td>
<td width="50%" valign="top">

#### [YGknowledgeBase](https://github.com/YGtemple/YGknowledgeBase)

<sub>`CSS`</sub>

A bilingual AI glossary — every term gets a plain-language explanation and a prompt template you can copy.

</td>
</tr>
</table>

---

<h2 id="film--content" align="center">🌸 Film &amp; Content</h2>

<sub>From script to cut, plus the tooling around it</sub>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [ai-drama-master-suite](https://github.com/YGtemple/ai-drama-master-suite)

<sub>`AI Film` `Storyboard`</sub>

Breaks AI short-drama production into stages — script, assets, storyboard, video — with working methods and checks for each.

`cases/` holds production records from four actual films.

</td>
<td width="50%" valign="top">

#### [ai-story-vault](https://github.com/YGtemple/ai-story-vault)

<sub>`Python`</sub>

A reference library of successful short stories, filed so it can be searched — the more you use it, the more it holds.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [jianying-editor-skill](https://github.com/YGtemple/jianying-editor-skill)

<sub>`Skill`</sub>

Automating CapCut/JianYing, with rules and prompts included.

</td>
<td width="50%" valign="top">

#### [drama-storyboard-director](https://github.com/YGtemple/drama-storyboard-director)

<sub>`Skill`</sub>

Turns a script into a shot list, in 15-second segments.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [ai-studio-yangzi](https://github.com/YGtemple/ai-studio-yangzi)

<sub>`Skill` `Python`</sub>

Film-production tooling and project templates — 11 skills plus cross-platform install scripts.

</td>
<td width="50%" valign="top">

#### [code-animation-playbook](https://github.com/YGtemple/code-animation-playbook)

<sub>`JavaScript` `Python`</sub>

Scripts for rendering code animation and its sound.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [video-skills-collection](https://github.com/YGtemple/video-skills-collection)

<sub>`Skill` `Python`</sub>

Twenty production skills for AI video, covering topic selection, script, storyboard, assets, prompts, generation, review and delivery.

Works with any SKILL.md-compatible agent such as Claude Code or DSH.

</td>
<td width="50%" valign="top"></td>
</tr>
</table>

---

<h2 id="games" align="center">🌸 Games</h2>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

#### [word-sprite-quest](https://github.com/YGtemple/word-sprite-quest)

<sub>`TypeScript` `Cocos Creator 3.8`</sub>

A WeChat mini-game: 18 play modes, 5 difficulty tiers, 240 levels.

Gameplay and data are aligned through a contract document; configuration and levels are script-generated and validated, with the toolchain under `tooling/`.

</td>
<td width="50%" valign="top">

#### [labyrinth-pathfinder](https://github.com/YGtemple/labyrinth-pathfinder)

<sub>`Python` `Pygame`</sub>

Maze pathfinding with five algorithms and a set of measured performance comparisons.

</td>
</tr>
</table>

---

<h2 id="more" align="center">🌸 More</h2>

<br/>

<table align="center">
<tr>
<td width="25%" valign="top">

**Docs & Research**

[zhinengtiku](https://github.com/YGtemple/zhinengtiku)<br/><sub>Quiz-platform architecture docs</sub>

[legal-ai-agent-research](https://github.com/YGtemple/legal-ai-agent-research)<br/><sub>Legal-domain agent research</sub>

[China-s-Smart-Agricultural-AI-Going-Global](https://github.com/YGtemple/China-s-Smart-Agricultural-AI-Going-Global)<br/><sub>Agricultural AI going global</sub>

</td>
<td width="25%" valign="top">

**Writing & Editors**

[UItimateWriter](https://github.com/YGtemple/UItimateWriter)<br/><sub>Chinese writing assistant</sub>

[wechat-longform-article](https://github.com/YGtemple/wechat-longform-article)<br/><sub>WeChat long-form layout</sub>

[qt-learning](https://github.com/YGtemple/qt-learning)<br/><sub>Qt exercises</sub>

[cpp-course-designs](https://github.com/YGtemple/cpp-course-designs)<br/><sub>C++ coursework</sub>

</td>
<td width="25%" valign="top">

**Practice & Records**

[computelevelTWOC](https://github.com/YGtemple/computelevelTWOC)<br/><sub>Exam question bank</sub>

[doubao-free](https://github.com/YGtemple/doubao-free)<br/><sub>Browser extension</sub>

[peini-manmanlai](https://github.com/YGtemple/peini-manmanlai)<br/><sub>Growth site</sub>

[jw-monitor](https://github.com/YGtemple/jw-monitor)<br/><sub>Course-registration monitor</sub>

</td>
<td width="25%" valign="top">

**Campus & Portfolio**

[shengda-saishi-hui](https://github.com/YGtemple/shengda-saishi-hui)<br/><sub>Campus competitions directory</sub>

[resume-2040](https://github.com/YGtemple/resume-2040)<br/><sub>3D spatial résumé</sub>

[virginia-woolf-presentation](https://github.com/YGtemple/virginia-woolf-presentation)<br/><sub>Class presentation</sub>

[ComputeCommunicationAssociation](https://github.com/YGtemple/ComputeCommunicationAssociation)<br/><sub>Campus tech club page</sub>

[zhuxin](https://github.com/YGtemple/zhuxin)<br/><sub>Résumé and portfolio</sub>

</td>
</tr>
</table>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7A8C4,100:FFF0F5&height=100&section=footer" width="100%"/>

</div>
