---
version: alpha
name: Stripi-Inspired-design-analysis
description: An inspired interpretation of Stripi's design language — a financial-infrastructure brand built on a deep navy ink, an electric indigo primary, and a recurring atmospheric gradient mesh that occupies the upper third of nearly every marketing page. The system pairs the proprietary Sohne family at thin (300) weights with negative letter-spacing for editorial-density display headlines, and uses tabular-figure body type where money and numerics matter. Buttons are tight-radius pills, cards live on near-white surfaces, and the dashboard track flips polarity to a familiar dark-app shell.

colors:
  primary: "#533afd"
  primary-deep: "#4434d4"
  primary-press: "#2e2b8c"
  primary-soft: "#665efd"
  primary-bg-subdued-hover: "#b9b9f9"
  brand-dark-900: "#1c1e54"
  ink: "#0d253d"
  ink-secondary: "#273951"
  ink-mute: "#64748d"
  ink-mute-2: "#61718a"
  on-primary: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f6f9fc"
  canvas-cream: "#f5e9d4"
  hairline: "#e3e8ee"
  hairline-input: "#a8c3de"
  ruby: "#ea2261"
  magenta: "#f96bee"
  lemon: "#9b6829"
  shadow-blue: "#003770"

typography:
  display-xxl:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 56px
    fontWeight: 300
    lineHeight: 1.03
    letterSpacing: -1.4px
    fontFeature: ss01
  display-xl:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 48px
    fontWeight: 300
    lineHeight: 1.15
    letterSpacing: -0.96px
    fontFeature: ss01
  display-lg:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 32px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.64px
    fontFeature: ss01
  display-md:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 26px
    fontWeight: 300
    lineHeight: 1.12
    letterSpacing: -0.26px
    fontFeature: ss01
  heading-lg:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 22px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.22px
    fontFeature: ss01
  heading-md:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 20px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: -0.2px
    fontFeature: ss01
  heading-sm:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 18px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: ss01
  body-lg:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: ss01
  body-md:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 15px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: ss01
  body-tabular:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: -0.42px
    fontFeature: tnum
  button-md:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 0
    fontFeature: ss01
  button-sm:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 0
    fontFeature: ss01
  caption:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: -0.39px
    fontFeature: tnum
  micro:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 11px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: ss01
  micro-cap:
    fontFamily: "sohne-var, 'SF Pro Display', system-ui, -apple-system, sans-serif"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: 0.1px
    fontFeature: ss01

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  xxl: 32px
  huge: 64px

components:
  button-primary-pill:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  button-primary-pill-pressed:
    backgroundColor: "{colors.primary-press}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  button-on-dark:
    backgroundColor: "{colors.brand-dark-900}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 8px 12px
  text-input-focused:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 8px 12px
  card-feature-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-pricing:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-pricing-featured:
    backgroundColor: "{colors.brand-dark-900}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-cream-band:
    backgroundColor: "{colors.canvas-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-dashboard-mockup:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-tabular}"
    rounded: "{rounded.lg}"
    padding: 24px
  pill-tag-soft:
    backgroundColor: "{colors.primary-bg-subdued-hover}"
    textColor: "{colors.primary-deep}"
    typography: "{typography.micro-cap}"
    rounded: "{rounded.pill}"
    padding: 4px 8px
  nav-bar-on-mesh:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xs}"
    padding: 16px 24px
  link-on-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xs}"
    padding: 0px
  footer-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-mute}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: 64px 24px
---

> 🌐 本文档由 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 翻译,英文原版见原项目。
>
> ⚠️ 本文件超过 10000 字符,仅汉化核心章节(概览 / 色彩 / 字体 / 禁忌清单);布局、组件、响应式等其余章节保留英文原版,请对照原项目阅读。

## 概览(Overview)

Stripe 的设计语言以渐变网格开场。一条由粉彩奶油色、雪柑橙、薰衣草紫、电光靛蓝和红宝石粉组成的宽幅水平色带,占据了几乎所有营销页的上三分之一——这是品牌一眼可辨的氛围背景。文字与产品 UI 模型图漂浮在其上方的 `{colors.canvas}`(白色)上,渐变同时充当装饰和视觉锚点。页面下半部分回归白色,特性说明放在 `{colors.canvas-soft}`(几乎无色调的冷白)上,仪表盘产品模型图则以深海军蓝的仿 IDE/控制台面板形式合成呈现。

色彩系统有两个主要角色。**靛蓝**(`{colors.primary}` — `#533afd`)是品牌标志性的 CTA 色,使用克制:每个区块只有一个实心药丸按钮。**深海军蓝**(`{colors.ink}` — `#0d253d`)是通用的正文色,也是仪表盘模型图、精选定价档、仪表盘轨道上深色应用表面的填充色。红宝石色(`{colors.ruby}`)和品红(`{colors.magenta}`)出现在渐变网格和产品 UI 模型图的强调圆点中;从不用作按钮色。

字体体系围绕字重 300、负字距的 **Sohne** 构建——这是品牌编辑密度的展示签名。展示字号(32–56px)使用 -1.4px 至 -0.64px 字距;正文字号为 0;表格说明字号(涉及金额与数字之处)启用 OpenType `tnum` 特性并收紧至 -0.36 至 -0.42px 字距。`ss01` 风格集在所有角色上全局启用。

**关键特征:**
- 每个营销 Hero 都有渐变网格背景——奶油/橙/薰衣草/靛蓝/红宝石横向铺满页面上三分之一。
- 单一靛蓝 CTA 层级:实心 `{colors.primary}` 药丸是营销表面上唯一的实心按钮。
- Sohne 细体(字重 300)展示层级,负字距随字号在 -1.4px 至 -0.2px 之间变化。
- 表格数字正文字体(`tnum`)用于任何包含金额或数字的单元格——品牌对金融数据属性的安静宣示。
- 深色应用仪表盘轨道:深海军蓝产品 UI 模型图合成在白色画布之上,内部常带有渲染好的代码或仪表盘表格。
- 药丸形按钮(`{rounded.pill}` 9999px)配紧凑的 `8px 16px` 内边距——短促、果断、交易感。
- 奶油色区块特性卡片(`{colors.canvas-cream}`)在蓝白章节之间插入一段暖色间奏,却不破坏品牌的色彩逻辑。

## 色彩(Colors)

> **来源页面:** 首页(`/`)、`/payments`、`/pricing`、`dashboard.stripe.com/register/payments`。

### 品牌与强调色
- **靛蓝**(`{colors.primary}` — `#533afd`):品牌标志性 CTA 色。实心药丸按钮、链接强调、渐变锚点。
- **深靛蓝**(`{colors.primary-deep}` — `#4434d4`):更深的靛蓝,用于渐变中间节点,也是按压态的更暖替代。
- **靛蓝按压态**(`{colors.primary-press}` — `#2e2b8c`):主色的按压态加深。
- **浅靛蓝**(`{colors.primary-soft}` — `#665efd`):较亮的靛蓝,用于产品 UI 强调和图表高亮。
- **弱化靛蓝**(`{colors.primary-bg-subdued-hover}` — `#b9b9f9`):苍白靛蓝填充,用作柔和标签背景。
- **品牌深色 900**(`{colors.brand-dark-900}` — `#1c1e54`):深海军蓝,用于精选定价档与仪表盘外壳。
- **红宝石**(`{colors.ruby}` — `#ea2261`):渐变强调与图表高亮;绝不做按钮。
- **品红**(`{colors.magenta}` — `#f96bee`):渐变网格中更亮的粉色节点。
- **柠檬**(`{colors.lemon}` — `#9b6829`):渐变背景中的暖雪柑节点。

### 表面
- **画布**(`{colors.canvas}` — `#ffffff`):默认页面背景。
- **柔和画布**(`{colors.canvas-soft}` — `#f6f9fc`):冷调灰白,用于渐变 Hero 下方的特性区块。
- **奶油画布**(`{colors.canvas-cream}` — `#f5e9d4`):暖奶油色,用作特性区块填充——品牌的色彩间奏。
- **发丝线**(`{colors.hairline}` — `#e3e8ee`):卡片与表格的 1px 边框。
- **输入框发丝线**(`{colors.hairline-input}` — `#a8c3de`):表单输入框上略冷的发丝线。

### 文字
- **墨色**(`{colors.ink}` — `#0d253d`):全品牌默认正文色。深海军蓝,从不用纯黑。
- **次要墨色**(`{colors.ink-secondary}` — `#273951`):白底上的次要文字。
- **弱化墨色**(`{colors.ink-mute}` — `#64748d`):辅助文字、说明、表格标签。
- **弱化墨色 2**(`{colors.ink-mute-2}` — `#61718a`):导航中使用的近似 ink-mute 色。
- **主色上的文字**(`{colors.on-primary}` — `#ffffff`):靛蓝 / 深海军蓝表面上的文字。

### 语义色
营销系统中品牌不使用独立的语义色板——错误 / 成功状态只存在于仪表盘产品 UI 中。

## 字体(Typography)

### 字体族

展示与 UI 层级使用 **Sohne**(专有字体,授权自 Klim Type Foundry),字重 300(细体)与 400(常规)。可变字体(`sohne-var`)以 `font-feature-settings: "ss01"` 全局加载——该风格集替换单层 `a` 等字符变体,是品牌字体签名的一部分。

Sohne 不可用时,回退到细字重的 **SF Pro Display**,再退到 system-ui。追求最大品牌保真度时,开源的 **Inter**(字重 300,启用 `font-feature-settings: "ss01"`,展示字号加 `letter-spacing: -1.4px`)能很接近地还原其节奏。

### 层级(Hierarchy)

| Token | Size | Weight | Line Height | Letter Spacing | 用途 |
|---|---|---|---|---|---|
| `{typography.display-xxl}` | 56px | 300 | 1.03 | -1.4px | Hero 标题 |
| `{typography.display-xl}` | 48px | 300 | 1.15 | -0.96px | 区块开场 |
| `{typography.display-lg}` | 32px | 300 | 1.1 | -0.64px | 卡片标题 / 子区块 |
| `{typography.display-md}` | 26px | 300 | 1.12 | -0.26px | 紧凑卡片标题 |
| `{typography.heading-lg}` | 22px | 300 | 1.1 | -0.22px | 定价档位名 |
| `{typography.heading-md}` | 20px | 300 | 1.4 | -0.2px | 区块副标题 |
| `{typography.heading-sm}` | 18px | 300 | 1.4 | 0 | 迷你区块标签 |
| `{typography.body-lg}` | 16px | 300 | 1.4 | 0 | 营销正文导语 |
| `{typography.body-md}` | 15px | 300 | 1.4 | 0 | 默认 UI 正文 |
| `{typography.body-tabular}` | 14px | 300 | 1.4 | -0.42px | 金额 / 数字表格(启用 `tnum`) |
| `{typography.button-md}` | 16px | 400 | 1.0 | 0 | 药丸按钮标签 |
| `{typography.button-sm}` | 14px | 400 | 1.0 | 0 | 紧凑药丸标签 |
| `{typography.caption}` | 13px | 400 | 1.4 | -0.39px | 辅助文字、表格标签 |
| `{typography.micro}` | 11px | 300 | 1.4 | 0 | 细则 |
| `{typography.micro-cap}` | 10px | 400 | 1.15 | 0.1px | 全大写眉题 |

### 原则(Principles)
- **细体就是品牌。** 展示层级一律以字重 300 渲染。提到 400+ 会毁掉品牌的编辑气质。
- **展示字号负字距。** 56px 处 -1.4px,按比例递减到 20px 处 -0.2px。负字距是品牌的字体签名。
- **金额用表格数字。** 任何渲染货币、交易金额或数字计数的单元格都使用 `font-feature-settings: "tnum"` 加收紧字距。品牌通过这个微细节安静地宣示自己的金融基因。
- **全局 `ss01`。** 在 body 元素上应用 `font-feature-settings: "ss01"`,让风格集替换对所有文字角色生效。

### 字体替代说明(Note on Font Substitutes)
Sohne 为专有字体。展示层级可使用 **Inter**(Google Fonts 开源)字重 300,加 `letter-spacing: -1.4px` 与 `font-feature-settings: "ss01"`——Inter 是最接近的开源近似。正文字号同样用 Inter 300,适用处启用 `font-feature-settings: "tnum"`,这是标准替代。避免 Helvetica 或 system-ui 默认值——它们比品牌需要的更重。

## Layout

### Spacing System
- **Base unit**: 8px (with 2 / 4 / 12 sub-tokens for fine work).
- **Tokens**: `{spacing.xxs}` 2px · `{spacing.xs}` 4px · `{spacing.sm}` 8px · `{spacing.md}` 12px · `{spacing.lg}` 16px · `{spacing.xl}` 24px · `{spacing.xxl}` 32px · `{spacing.huge}` 64px.
- **Section padding**: 64–96px on marketing surfaces; 32–48px on dashboard / product surfaces.
- **Card internal padding**: 32px on feature cards; 24px on dashboard mockups.

### Grid & Container
- Marketing pages center in a ~1200px container with the gradient mesh extending edge-to-edge above.
- Pricing collapses 4-up → 2-up → 1-up at 1024 / 768 breakpoints.
- Dashboard product mockups use their own internal grids (12-col tables, 3-col card grids) rendered as static composites.

### Whitespace Philosophy
The gradient mesh occupies the upper third of the page; the white canvas below is generously padded. Section gaps tend toward 96px, with content tightening to 32px on dashboard / pricing pages where users compare and act.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 | Flat | Default surface |
| 1 | `box-shadow: rgba(0,55,112,0.08) 0 1px 3px` | Card lift on white |
| 2 | `box-shadow: rgba(0,55,112,0.08) 0 8px 24px, rgba(0,55,112,0.04) 0 2px 6px` | Floating panels, dashboard mockup chrome |
| 3 | Gradient mesh backdrop | The brand's primary depth medium — atmospheric color rather than literal shadow |

### Decorative Depth
The gradient mesh IS the depth system. Implemented as a layered SVG or large background image rather than CSS gradients (the actual mesh has organic blob shapes that aren't CSS-renderable). The mesh provides the brand's signature lift; literal shadows are reserved for product-UI mockups and stay subtle.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | Hairline tags, table chrome |
| `{rounded.sm}` | 6px | Form inputs |
| `{rounded.md}` | 8px | Compact cards, alerts |
| `{rounded.lg}` | 12px | Pricing cards, feature cards |
| `{rounded.xl}` | 16px | Dashboard product mockup chrome |
| `{rounded.pill}` | 9999px | All buttons, tag pills |

### Photography Geometry
The brand uses **product UI mockups** more than photography. Dashboard composites render as faux IDE/terminal/dashboard chrome inside `{rounded.lg}` 12px containers with a subtle `box-shadow`. Real photography appears in customer logo strips and the rare case-study card; treated as inset 4:3 with no shadow.

## Components

### Buttons

**`button-primary-pill`** — the dominant CTA system-wide.
- Background `{colors.primary}`, text `{colors.on-primary}`, type `{typography.button-md}`, padding `{spacing.sm} {spacing.lg}` (8px 16px), rounded `{rounded.pill}` 9999px.
- Pressed state `button-primary-pill-pressed` shifts background to `{colors.primary-press}`.

**`button-secondary`** — outline-style alternative.
- Background `{colors.canvas}`, text `{colors.primary}`, 1px solid `{colors.primary}` border, same pill geometry.

**`button-on-dark`** — used on dashboard / dark surfaces.
- Background `{colors.brand-dark-900}`, text `{colors.on-primary}`, same pill geometry.

### Cards & Containers

**`card-feature-light`** — feature explanation card on white.
- Background `{colors.canvas}`, padding `{spacing.xxl}`, rounded `{rounded.lg}` 12px, 1px `{colors.hairline}` border, optional Level 1 shadow.

**`card-pricing`** — standard pricing tier.
- Background `{colors.canvas}`, padding `{spacing.xxl}`, rounded `{rounded.lg}`, 1px `{colors.hairline}` border. Title `{typography.heading-lg}`, price `{typography.display-md}`, body `{typography.body-md}`, CTA pinned bottom as `button-primary-pill`.

**`card-pricing-featured`** — the inverted dark featured tier.
- Background `{colors.brand-dark-900}`, text `{colors.on-primary}`, otherwise identical structure to `card-pricing`. The deep-navy fill is the brand's distinctive featured-tier choice.

**`card-cream-band`** — warm interlude card.
- Background `{colors.canvas-cream}`, text `{colors.ink}`, padding `{spacing.xxl}`, rounded `{rounded.lg}`. Used to break up the indigo / white rhythm with warmth.

**`card-dashboard-mockup`** — composited dashboard / product UI screenshot.
- Background `{colors.canvas}`, type `{typography.body-tabular}` (with `tnum`), padding `{spacing.xl}` 24px, rounded `{rounded.lg}` 12px, Level 2 shadow. Often contains nested mini-mockups: code preview + dashboard table + chart card.

### Inputs & Forms

**`text-input`** — standard form field.
- Background `{colors.canvas}`, text `{colors.ink}`, type `{typography.body-md}`, padding `{spacing.sm} {spacing.md}` (8px 12px), rounded `{rounded.sm}` 6px, 1px `{colors.hairline-input}` border.
- Focus state `text-input-focused`: border swaps to `{colors.primary}`.

### Navigation

**`nav-bar-on-mesh`** — top nav floating over the gradient hero.
- Background `{colors.canvas}` (or transparent depending on scroll), text `{colors.ink}`, padding `{spacing.lg} {spacing.xl}`. Logo wordmark on the left, primary nav center, sign-in + filled `button-primary-pill` on the right.

### Pills, Tags, and Chips

**`pill-tag-soft`** — subdued indigo tag.
- Background `{colors.primary-bg-subdued-hover}`, text `{colors.primary-deep}`, type `{typography.micro-cap}`, padding `4px 8px`, rounded `{rounded.pill}`.

### Signature Components

**Gradient Mesh Backdrop** — pastel cream → sherbet orange → lavender → indigo → ruby pink stops blurred horizontally across the upper third of the page. Implemented as SVG or a large background image — not a flat CSS gradient (the real mesh has organic blob shapes).

**Composited Dashboard Mockup** — multi-layer faux-product-UI compositions: an IDE panel on the left, a dashboard table center, a chart card on the right, all rendered at small scale inside `{rounded.lg}` containers with subtle Level 2 shadows. The composite is the brand's most-photographed feature.

**Tabular-Figure Money Type** — every number rendering money, count, or transaction value uses `font-feature-settings: "tnum"`. The brand's quiet signal that it's a financial-infrastructure platform.

**`link-on-light`** — inline links on light surfaces.
- Text `{colors.primary}` rendered in `{typography.body-md}`, no underline by default.

**`footer-light`** — site-wide footer.
- Background `{colors.canvas}`, text `{colors.ink-mute}`, type `{typography.caption}`, padding `{spacing.huge} {spacing.xl}` (64px 24px). Holds 4–6 columns of link groups, social icons, and a small legal row.

## 应做与禁忌(Do's and Don'ts)

### 应做(Do)
- 把 `{colors.primary}` 留给实心 CTA 和行内链接强调——它应当克制出现,每个区块一个实心按钮。
- 每个营销 Hero 都应用渐变网格;裸画布 Hero 会显得脱离品牌。
- 展示层级以字重 300 加负字距渲染——细体字距就是字体签名。
- 每个金额 / 数字单元格都启用 `font-feature-settings: "tnum"`。
- 在 body 元素上全局应用 `font-feature-settings: "ss01"`。
- 每段特性说明都配一张合成产品 UI 模型图;品牌的论据就是"看真实产品"。

### 禁忌(Don't)
- 不要把展示字重提到 300 以上——到 400 品牌的编辑气质就塌了。
- 不要添加文档化渐变节点(奶油 / 橙 / 薰衣草 / 靛蓝 / 红宝石 / 品红)之外的新强调色。
- 不要把靛蓝 `{colors.primary}` 当正文字色——它是 CTA 和链接色,不是正文尺寸的字体色。
- 不要把按钮内边距压到 `8px 16px` 以下——紧凑药丸是品牌交易感的一部分。
- 不要渲染没有 `tnum` 的金额单元格——那会破坏安静的金融数据签名。
- 不要用圆角矩形替代按钮的药丸形。

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Wide | ≥ 1440px | Full gradient mesh edge-to-edge; dashboard composite at full scale |
| Desktop | 1024–1440px | Default content max-width; pricing 4-up |
| Tablet | 768–1023px | Pricing 2-up; dashboard composite simplifies to 2 panels |
| Mobile | < 768px | Pricing 1-up; hamburger nav; display drops 56 → 36px |

### Touch Targets
- Pill buttons hit ≥ 40×40px on mobile via padding scaling. On smaller screens, buttons size up to 44×44px to maintain WCAG AAA.
- Form fields stay at 40px minimum height.

### Collapsing Strategy
- Display tiers stair-step 56 → 48 → 32 → 26 → 22px through the breakpoints.
- Gradient mesh re-tiles on mobile to preserve the wash without disappearing.
- Dashboard composites simplify to single-panel mockups on mobile; the multi-layer composition only renders at desktop+.
- Pricing tiers stair-step 4-up → 2-up → 1-up.

### Image Behavior
Product UI composites use `srcset` with art-direction crops at major breakpoints. Mobile crops focus on the most actionable inner panel; desktop crops show the full multi-layer composition.

## Iteration Guide

1. Focus on ONE component at a time.
2. Reference component names and tokens directly (`{colors.primary}`, `{button-primary-pill}-pressed`, `{rounded.pill}`).
3. Run `npx @google/design.md lint DESIGN.md` after edits.
4. Add new variants as separate entries.
5. Default body to `{typography.body-md}` (15px); use `{typography.body-tabular}` for any money / numeric cell.
6. Apply `ss01` globally on the body; apply `tnum` per-element on numeric content.
7. The gradient mesh is non-negotiable on marketing heroes — bare-canvas heroes break the brand.
