<div align="center">

# 飞花 ✿ flyingpetals520

*THU PhD · Attention 炼丹师 ⚡ · 折腾 Vibe coding工具链*

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/🤗_Transformers-FFD21E?style=for-the-badge&logoColor=black" alt="Transformers" />
<img src="https://img.shields.io/badge/FLA-000000?style=for-the-badge" alt="FLA (Fused Linear Attention)" />

</div>

<br/>

<!-- 方案 A：右上角飘猫 -->
<img align="right" width="130" src="https://cdn.jsdelivr.net/gh/flyingpetals520/whiskershelf@main/static/cat_src_2.png" alt="🐈 伸懒腰的黑猫" />

</div>

<!-- 顶部波浪已删 -->

---

## 🐾 About Me

> THU PhD 在读，主攻 AI/ML 领域交叉方向，不是CS科班，比较菜。
> 日常：广读 AI 领域论文、搓搓本地小工具、致力于把 agent 嵌进日常研究流程、喜欢哈基米。

**最近在想的事：**

- 🧠 **大语言模型前沿** —— Linear Attention、Sparse Attention、SSM、Agentic reasoning、Alignment...
- 🤖 **Agent for Autoresearch** —— 让 Claude Code 真正参与读论文 → 想法碰撞 → 实验 → 高质量产出的闭环（成熟框架太多了，还在 explore）
- 🐈 **共情设计** —— 好看温馨的 GUI 界面，严肃工具也可以有温度

---

## 🛠️ 正在搓的轮子

由于本人平时主要以 academic research 为主，精力主要不在这儿，所以项目可能简陋些，有需求就 vibe 一下热热身搓一个自己用，不过还是希望帮到大家，也在不断查找不足和迭代！不是单品玩家，是希望构建**一整套本地 AI reserach 工具链**——围绕"读论文 → 标注 → 引用 → idea火花碰撞 → 复现 →高质量产出"的完整研究循环：

<table>
<tr>
<td width="50%" valign="top">

### 🐾 [WhiskerShelf](https://github.com/flyingpetals520/whiskershelf) ⭐

**A cozy local AI paper library — with a cat on the shelf.**

- 💡 **Idea Spark** —— 选 2-4 篇论文，AI brainstorm 碰撞出可执行的研究方向
- 🚀 **Claude Code 集成** —— 一键导出 brief 项目直接当 CC 任务
- 🧠 **5 个 自己搓的 Skills** —— 让 CC 真正成为研究伙伴 （可以搭配其他更成熟的 skills 食用）
- 🐈 小黑随机出现趴在"最近阅读"上
- 🔌 零三方依赖（Python stdlib + Vanilla JS）

`MIT` · `Python 3.8+` · `176+ PDFs`

</td>
<td width="50%" valign="top">

### 🖼️ [MLLM 智能图像标注](https://github.com/flyingpetals520/Intelligent-image-annotation-web-tool-based-on-multimodal-LLM)

**Local multimodal LLM annotation for image dataset.**

- 🎨 文生图数据集 + 姿态识别 + 二次元数据合成
- 🔌 三种模式：**本地 VLM** / **远程 API** / **人工校正**
- 🧠 支持 Qwen3.5 (4B/27B/35B) 等本地部署 VLM
- 🎯 vibe-coded with **GLM-5.1 agent**
- 📦 自建 10w+ 张高质量二次元图片数据集

`Apache 2.0` · `PyTorch` · `Flask`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📜 [Paper Reference Check Helper](https://github.com/flyingpetals520/Paper-Reference-Check-Helper)

**Effective and light-flash assistant for checking references.**

- 📚 上传 `.bib` + `.tex`，自动找引用错误
- ⚡ 写论文 / 改 literature review 时救命
- 🪶 单文件 GUI，PyInstaller 一键打包 exe
- 🎓 "Be flash and beautiful, not bloated and paid"

`Python 3.9+` · `pybtex` · 单文件

</td>
<td width="50%" valign="top">

### 🌐 [flyingpetals520.github.io](https://flyingpetals520.github.io)

**An interactive AI evolution timeline.**

- 📅 主流模型发布、巨头突破、研究里程碑的可视化时间线且可编辑更新
- 🧭 精选 AI 评测平台 & 新闻源导航
- 💾 离线持久化（localStorage + JSON 导入/导出）
- 🎨 静态站点，无后端依赖

`HTML/CSS/JS` · 静态站

</td>
</tr>
</table>

---

## 🐈 此刻的桌面

```text
📖  WhiskerShelf 开着，左边栏 Idea Spark 在等一个新Idea 冒出来
🔧  刷着 X，导致 Skills 又下了几个黑科技
🖼️  MLLM 标注工具在跑 Qwen3.5-27B，标注 10w+ 图
🤖  Claude Code 正在 vibe-coding，写不动了就调动 superpowers 老祖让它接着写
📚  Mamba-3 / Gated DeltaNet-2 / Kimi Linear 一大堆在论文队列里等着读
```

---

## 🤖 我怎么用 agent

不是"按个按钮 AI 就搞定一切"那种视频。**真正的协作长这样：**

1. **想清楚要什么** —— prompt 描述，比写代码还重要，做真正的产品经理
2. **拆解成可执行的小任务** —— agent 干一行就 commit
3. **让它出方案 + 计划** —— review 完再让它动
4. **review 它的设计，不只是结果** —— 风格、命名、工程结构
5. **用 Skills 把经验沉淀下来** —— 不让它每次都从零学
6. **公开 cat 也得让 agent 看** —— 它也需要上下文

> "vibe coding 不是什么黑科技，是把'写需求'的本事练到极致。"

---

## 📊 GitHub 数据流

<table align="center">
<tr>
  <td><img height="180em" src="https://github-readme-stats.vercel.app/api?username=flyingpetals520&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats" /></td>
  <td><img height="180em" src="https://streak-stats.demolab.com?user=flyingpetals520&theme=tokyonight&hide_border=true" alt="GitHub Streak" /></td>
  <td><img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=flyingpetals520&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" /></td>
</tr>
</table>

---

## 🌱 长期关注的技术 Long-term Vision && Research Intersest 

不希望发 agent 水文，更关注于基础模型的构建和训练这一长期主义工程，长期探究如何让注意力机制跑得更高效聪明而非更沉重，尤其看好线性注意力和稀疏注意力对长序列建模的解放和 scaling 的潜力。同时也在探索视觉-语言多模态基础模型的统一架构，想找一种更本质的方式把不同模态融进同一个全模态全双工框架。我相信，只有当注意力足够高效，甚至放弃反向传播，统一多模态模型才能真正摆脱算力束缚，走得更远。
```text
🧠  LLM 架构    Mamba · RWKV · DeltaNet · Linear Attn · MoE · Diffusion LM 
🎨  多模态     VLM · Diffusion · Pose Estimation · 3D Generation
🤖  Agent       Claude Code · Tool Use · ReAct · Planning · Multi-Agent
🔧  Infra       vLLM · SGLang · KV Cache · Quantization · Speculative Decoding
🧬  Bio-inspired  SNN · Spiking Attention · Predictive Coding · HTM
🌍  World Model  JEPA · Sora · Genesis · Video Prediction
```

<!-- 方案 C：猫爪 emoji 分隔线 -->

<div align="center">

`·  🐾  ·  🌿  ·  🐾  ·  🍵  ·  🐾  ·  🌸  ·  🐾  ·`

</div>

## 📬 Find Me

- 🐙 **GitHub Issues** —— [WhiskerShelf/issues](https://github.com/flyingpetals520/whiskershelf/issues) 是最快的入口
- 🐦 **X (Twitter)** —— [@flyingpetal472](https://x.com/flyingpetal472)
- 💬 **QQ** —— 1665395842

---

<!-- 底部波浪已删 -->

<div align="center">

*"每只猫都值得一个温暖的书架，每篇论文都值得一个会思考的伙伴，每个 agent 都值得一个靠谱的协作框架。"*

**made with 🐾 and 🧠 by [flyingpetals520](https://github.com/flyingpetals520)**

<sub>📌 顶图那只猫的灵感来自 `cat_src_2.png`（伸懒腰，最有性格）</sub>

</div>
