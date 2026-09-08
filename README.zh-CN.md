# awesome-design-md 中文文档

<div align="center">

[![原项目](https://img.shields.io/badge/原项目-VoltAgent--awesome-design-md-blue?style=flat-square&logo=github)](https://github.com/VoltAgent/awesome-design-md)
[![DESIGN.md 数量](https://img.shields.io/badge/DESIGN.md%20数量-73-10b981?style=flat-square)](https://github.com/VoltAgent/awesome-design-md)
[![微信联系](https://img.shields.io/badge/微信-uaycar-brightgreen?style=flat-square&logo=wechat)](#)

</div>

> 本文档是 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 的中文翻译版。
> **代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**

---

## 📖 这是什么项目

**Awesome DESIGN.md** 是一份精选合集:从真实网站中提取并分析出 **73 份 DESIGN.md**,让 AI 编码代理(Claude Code、Cursor、Copilot、Google Stitch 等)生成与目标品牌设计语言保持一致的高质量界面。

**DESIGN.md** 是 Google Stitch 提出的新概念——一份纯文本设计系统文档。它就是一个 Markdown 文件:没有 Figma 导出,没有 JSON Schema,不需要任何特殊工具。放进项目根目录,任何 AI 编码代理都能立刻理解你的界面应该长什么样。Markdown 恰好是大语言模型最容易消化的格式,所以无需解析、无需配置。

| 文件 | 谁来读 | 定义什么 |
|------|--------|----------|
| `AGENTS.md` | 编码代理 | 项目该怎么搭 |
| `DESIGN.md` | 设计代理 | 项目该怎么"看" |

## ✨ 主要特性

- **73 份真实品牌分析**:每份都提取自真实网站,包含分析过的设计模式、设计令牌(Design Tokens)与规则,追求有深度的 UI 生成而非表层模仿
- **零工具链依赖**:纯 Markdown,复制即用
- **9 大标准章节**(基于 Stitch DESIGN.md 规范扩展):

| # | 章节 | 内容 |
|---|------|------|
| 1 | 视觉主题与氛围 | 基调、信息密度、设计哲学 |
| 2 | 调色板与色彩角色 | 语义命名 + 色值 + 功能定位 |
| 3 | 字体规则 | 字体族与完整层级表 |
| 4 | 组件样式 | 按钮、卡片、输入框、导航及各状态 |
| 5 | 布局原则 | 间距刻度、栅格、留白哲学 |
| 6 | 深度与层级 | 阴影系统、表面层级 |
| 7 | 设计禁忌 | 设计护栏与反模式清单 |
| 8 | 响应式行为 | 断点、触控目标、折叠策略 |
| 9 | Agent 提示词指南 | 配色速查 + 现成提示词 |

- 每个站点附 `DESIGN.md`(给代理读)与 `preview.html`(预览页)

## 📚 收录分类(章节标题汉化)

原仓库按领域组织,各分类代表性条目如下:

- **AI 与 LLM 平台**:Claude(暖赤陶色、编辑排版风)、ElevenLabs(深色影院感、声波美学)、Ollama(终端优先、极简单色)、xAI(硬朗黑白、未来极简)
- **开发者工具与 IDE**:Cursor(利落深色、渐变点缀)、Vercel(黑白精密、Geist 字体)、Raycast(深色质感、活力渐变)
- **后端 / 数据库 / DevOps**:Supabase(深色翡翠、代码优先)、Sentry(数据密集深色仪表盘)、MongoDB(绿色品牌、文档风)
- **效率与 SaaS**:Linear(超简约、紫色点缀)、Notion(温暖极简、衬线标题)、Zapier(暖橙、插画驱动)
- **设计与创意工具**:Figma(多彩、玩趣又专业)、Framer(黑白蓝、动效优先)、Webflow(蓝色点缀、精致营销站)
- **金融科技与加密**:Stripe(标志性紫色渐变、细字重优雅)、Binance(币安黄 × 单色、交易场紧迫感)、Coinbase(干净蓝、信任导向)
- **电商与零售**:Airbnb(暖珊瑚色、摄影驱动)、Nike(单色 UI、大写 Futura)、Starbucks(四层大地绿体系)
- **媒体与消费科技**:Apple(高级留白、SF Pro)、Spotify(深色活力绿、专辑封面驱动)、NVIDIA(绿黑能量感)
- **汽车**:Tesla(极致做减法、全屏影院摄影)、Ferrari(黑白明暗编辑风、法拉利红极克制)、Lamborghini(纯黑殿堂、金色点缀)
- **复古网页 · DESIGN.md 怀旧系列**:Dell (1996)(目录式企业网页、手工 GIF 贴纸)、Nintendo.com (2001)(Y2K 主机金属质感网页)

> 完整清单(73 份,含逐条设计点评)请看[原仓库 README](https://github.com/VoltAgent/awesome-design-md)。

## 🚀 使用方法

1. **选一份设计**:浏览原仓库 Collection,挑一个与你的产品气质匹配的品牌。
2. **复制文档**:获取该品牌的 `DESIGN.md`(每份均遵循 Stitch 规范)。
3. **放入项目根目录**:

```bash
cp DESIGN.md /path/to/your-project/DESIGN.md
```

4. **告诉你的 AI 代理**:

```text
阅读 DESIGN.md,按此设计系统生成一个落地页,
严格保持配色、字体与组件风格一致。
```

5. **按需微调**:可同时叠加你自己的品牌色覆盖文档中的部分令牌;文档末尾的 Agent Prompt Guide 提供了现成提示词模板。
6. **验证效果**:对照该站点附带的 `preview.html` 检查生成结果是否贴合目标风格。

**小技巧**:Markdown 是 LLM 最易读的格式,所以直接整份投喂即可,无需拆分或转换。想要某种没有收录的风格,可在原项目页面提交 DESIGN.md 请求(含私密定制交付)。

## 📞 联系方式

**代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**

---

> 本文档为 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 的中文翻译版本,版权归原作者所有,遵循原项目许可证。

**如果对你有帮助,请给[原项目](https://github.com/VoltAgent/awesome-design-md)点一个 Star!** ⭐
