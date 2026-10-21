<div align="center">

# 🗄️ Kins Vault

**日常思考的收纳盒 —— 把脑子里的想法，做成能点开的 HTML。**

[![Pages](https://img.shields.io/badge/在线浏览-立即打开-4f6bed?style=flat-square&logo=githubpages&logoColor=white)](https://kinsluck.github.io/kins-vault/)
[![Made with](https://img.shields.io/badge/made%20with-HTML-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4?style=flat-square)](#-反馈与建议)

**24 个页面 · 6 个分类 · 单文件 · 零依赖**

</div>

---

> 💡 与其让想法烂在备忘录里，不如把它变成一张能点开、能分享的网页。

## 📖 这是什么

**Kins Vault** 是我日常思考与总结的公开存档。

平时遇到一个问题、想通一个道理、整理出一套方法，我会顺手把它整理成一个**网页**：不用装环境、不用跑构建，点开就能看，也能直接发给别人。

这里放的就是这些页面。它们大多不是什么严肃的项目，而是**思考的副产品**——可能是某个概念的图解、一次踩坑的记录、一份调研结论，或者只是一张用来理清思路的图。

除了自己想的，这里也会收录**整理自他人的优质内容**（视频、文章、论坛帖、游戏 Wiki 等）。这类内容会尽量标注出处，详见下方[关于转载与来源](#-关于转载与来源)。

## 🚀 如何浏览

| 方式 | 怎么做 |
| :--- | :--- |
| 🌐 **在线看**（推荐） | 打开 **[kinsluck.github.io/kins-vault](https://kinsluck.github.io/kins-vault/)**，卡片式索引页，支持搜索筛选 |
| 📁 **仓库里看** | 按下方索引进入对应文件夹，点开 `.html` 文件 |
| 💻 **拉到本地** | 见下方命令，然后双击任意 `.html` |

```bash
git clone https://github.com/kinsluck/kins-vault.git
cd kins-vault
# 双击 index.html 即可本地浏览
```

## 🗂️ 目录结构

```
kins-vault/
├── index.html                          # 📇 卡片式导航首页（支持搜索）
├── README.md
├── LICENSE
│
├── games/                              # 🎮 游戏攻略
│   ├── baldurs-gate-3-walkthrough/     #   含 198 张实机截图
│   ├── tales-of-destiny-2-guide.html   #   宿命传说2攻略
│   ├── sekiro-upgrade-guide.html       #   只狼 · 一周目升级路线
│   └── root-board-game-quickref.html   #   茂林源记规则速查
├── dev/                                # 🧑‍💻 开发与编程
├── visual/                             # 📊 数据可视化
├── life/                               # 🏠 生活指南
├── gear/                               # 🔧 硬件与装备
└── reading/                            # 📚 阅读笔记
```

## 📚 内容索引

### 🎮 游戏攻略

| 页面 | 简介 |
| :--- | :--- |
| [**博德之门3 · 任务全流程图文攻略**](https://kinsluck.github.io/kins-vault/games/baldurs-gate-3-walkthrough/) | 逐幕推进的全任务流程，198 张实机截图对照，跟着走不迷路 |
| [**宿命传说2攻略**](https://kinsluck.github.io/kins-vault/games/tales-of-destiny-2-guide.html) | 战斗系统与流程要点整理，传说系列的经典一作 |
| [**茂林源记 · 规则速查**](https://kinsluck.github.io/kins-vault/games/root-board-game-quickref.html) | 桌游 Root 的快速回忆卡：先串一遍全局流程，再随时翻派系细节 |
| [**只狼 · 影逝二度 — 一周目升级路线完全指南**](https://kinsluck.github.io/kins-vault/games/sekiro-upgrade-guide.html) | 四条升级线怎么分配：技能点分级、P1–P5 加点节奏、三大流派与忍具、琉璃升级优先级 |

### 🧑‍💻 开发与编程

| 页面 | 简介 |
| :--- | :--- |
| [**Godot 游戏开发学习路径**](https://kinsluck.github.io/kins-vault/dev/godot-learning-path.html) | 汇总顶级开发者建议的学习路线：从入门到能独立做出游戏的推荐顺序 |
| [**图片压缩方案调研与实测**](https://kinsluck.github.io/kins-vault/dev/image-compression-research.html) | 各家压缩方案横向实测对比：体积、画质与实际使用取舍 |
| [**离线工具箱 · 九个常用小工具**](https://kinsluck.github.io/kins-vault/dev/offline-toolbox.html) | 金额大写 / 二维码 / **截图套壳**（iPhone 15–18 Pro、一加 13T，iPhone 用 Apple 官方 Product Bezels 真机边框，批量套壳 + 打包 ZIP）/ **视觉无损图片压缩**（SSIM 判据，批量+打包）/ JSON / 时间戳 / 文本对比 / **列转行**（竖排转一行，分隔符自定义）/ **三姑六婆**（亲戚称谓计算）：单文件零依赖，断网可用，数据不出本机 |

### 📊 数据可视化

| 页面 | 简介 |
| :--- | :--- |
| [**大理 · 逐日气温湿度可视化**](https://kinsluck.github.io/kins-vault/visual/dali-climate.html) | 2025.01.01 – 2026.10.07 逐日气温 / 湿度 / 体感温度 |
| [**佛山 · 逐日气温湿度可视化**](https://kinsluck.github.io/kins-vault/visual/foshan-climate.html) | 同一区间，可与其他城市横向对照 |
| [**京都 · 逐日气温湿度可视化**](https://kinsluck.github.io/kins-vault/visual/kyoto-climate.html) | 同一区间，四季分野一目了然 |

### 🏠 生活指南

| 页面 | 简介 |
| :--- | :--- |
| [**大理洱海边各区域租房调研**](https://kinsluck.github.io/kins-vault/life/dali-erhai-rental-research.html) | 洱海边各区域的租金、环境与生活便利度对比总结 |
| [**原木风装修避坑指南**](https://kinsluck.github.io/kins-vault/life/wood-style-renovation-guide.html) | 「十几万的高级感，都是实木给的」—— 落地要点与避坑清单 |
| [**装修全流程总结**](https://kinsluck.github.io/kins-vault/life/renovation-full-process-guide.html) | 不误工期、不被忽悠、不踩坑 —— 从开工到验收的完整流程梳理 |
| [**啤酒探索清单**](https://kinsluck.github.io/kins-vault/life/beer-exploration-list.html) | 以施纳德 5 号 / 督威三花 / 金麦为基准的风味坐标 |
| [**普通男生快速脱单法**](https://kinsluck.github.io/kins-vault/life/dating-guide.html) | 「记住这两点就够了」：打破资源边界、只做筛选不做改变 |
| [**0-3 岁婴幼儿养育照护手册**](https://kinsluck.github.io/kins-vault/life/baby-care-handbook.html) | 从出生开始的衣食住行速查：喂养、睡眠、穿盖、日常护理要点 |

### 🔧 硬件与装备

| 页面 | 简介 |
| :--- | :--- |
| [**小米 Redmi G27U 显示器评测笔记**](https://kinsluck.github.io/kins-vault/gear/redmi-g27u-monitor-review.html) | 4K 160Hz 双模 IPS 实测：色域、亮度、接口与调校取舍 |
| [**主机模拟器开发现状报告 · 2026**](https://kinsluck.github.io/kins-vault/gear/emulator-report-2026.html) | 第七世代 → 第九世代，各家模拟器现状横向盘点 |
| [**猛玛 LARK A1 无线麦克风 · 说明书**](https://kinsluck.github.io/kins-vault/gear/hollyland-lark-a1-manual.html) | 离线速查版说明书：配对、按键、指示灯与常见问题 |
| [**家电甜点级选购体系**](https://kinsluck.github.io/kins-vault/gear/home-appliance-buying-framework.html) | 24 类家电的关键指标、达标线与甜点线 —— 不买参数最高的，只买核心技术已成熟、再加钱收益迅速下降的 |

### 📚 阅读笔记

| 页面 | 简介 |
| :--- | :--- |
| [**Nature 重磅综述：2型糖尿病**](https://kinsluck.github.io/kins-vault/reading/nature-t2dm-review.html) | 「根本不是血糖高那么简单」—— 关于 2 型糖尿病的认知重塑 |
| [**柳叶刀：吃饭习惯与肠癌风险**](https://kinsluck.github.io/kins-vault/reading/lancet-colorectal-cancer-notes.html) | 饮食结构与结直肠癌风险的关联研究，观点整理 |
| [**为什么跑得再多还是脂肪肝？**](https://kinsluck.github.io/kins-vault/reading/fatty-liver-notes.html) | 「一周跑四次五公里依然中招」背后的机制，观点整理 |
| [**LDL-C 为什么会升高？— 2026 循证病因地图**](https://kinsluck.github.io/kins-vault/reading/ldl-c-causes-report.html) | 汇总 2023–2026 指南与共识：「进、出、调」三本账、20 个高频原因、化验单排查路径与 7 个常见误解 |

## ✨ 收录原则

|  ✅ 会放进来 |  ❌ 不会放进来 |
| :--- | :--- |
| 想清楚一件事后的**总结与图解** | 未整理的草稿与半成品 |
| 整理自他人的**攻略 / 干货**（注明出处） | 需要复杂构建/依赖的项目 |
| 能**独立打开**的网页 | 纯个人隐私内容 |
| 有复用价值的**小工具** | 来源不明又无法标注的内容 |
| 踩坑记录与**最佳实践** | 纯搬运、零加工的内容 |

**技术取向**：优先单文件、零依赖、开箱即用。能用原生 HTML / CSS / JS 解决就不引框架。

## 📌 关于转载与来源

这个仓库**不全是原创**。

有一部分是我从别处收集、整理来的——视频、公众号与博客文章、论坛帖子、游戏 Wiki 等，把它们重新组织成了更好读、更好存的网页。有些页面本身就是「某个视频的图文整理」，标题里也会写出来。

对这类内容，我的态度是：

- 📎 **尽量标注来源** —— 能考证到的，会写在页面里或下方索引中（部分页面的出处还在补）
- ©️ **版权归原作者** —— 整理只是重新排版组织，我不主张任何原创权利
- 🗑️ **有异议随时下架** —— 如果你是被引用的作者，觉得不妥，开个 [Issue](https://github.com/kinsluck/kins-vault/issues) 说一声，我会直接删除，不会多问
- 🙋 **欢迎指正** —— 自己写的部分难免有错漏，看到欢迎提出来

目的很简单：把散落各处、容易失效的好内容，变成一个自己随时能翻、也方便分享给别人的地方。

## 🤝 反馈与建议

- 觉得某个页面有意思、或者哪里说错了 → 欢迎提 [Issue](https://github.com/kinsluck/kins-vault/issues)
- 想补充自己的想法 → 欢迎提 PR
- 单纯路过点个 ⭐ 也很快乐 :)

## 📄 许可证

本仓库的**代码与页面结构**采用 [MIT License](LICENSE)。

收录的**内容**情况不一：自己写的部分欢迎自由取用，注明出处即可；**转载整理的部分，版权归原作者所有**，二次使用请回到原始出处确认授权。

<div align="center">

<sub>用 ❤️ 和一点点强迫症维护着</sub>

</div>
