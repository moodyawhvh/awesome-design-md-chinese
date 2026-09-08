---
version: alpha
name: Claude-design-analysis
description: A warm-canvas editorial interface for Anthropic's Claude product. The system anchors on a tinted cream canvas with serif display headlines, warm coral CTAs, and dark navy product surfaces (code editor mockups, model showcase cards). Brand voltage comes from the cream/coral pairing — deliberately warm and humanist where most AI brands use cool blue + slate. Type voice runs a slab-serif display ("Copernicus" / Tiempos Headline) for h1/h2 and a humanist sans for body. The signature Anthropic black-radial-spike mark anchors the wordmark.

colors:
  primary: "#cc785c"
  primary-active: "#a9583e"
  primary-disabled: "#e6dfd8"
  ink: "#141413"
  body: "#3d3d3a"
  body-strong: "#252523"
  muted: "#6c6a64"
  muted-soft: "#8e8b82"
  hairline: "#e6dfd8"
  hairline-soft: "#ebe6df"
  canvas: "#faf9f5"
  surface-soft: "#f5f0e8"
  surface-card: "#efe9de"
  surface-cream-strong: "#e8e0d2"
  surface-dark: "#181715"
  surface-dark-elevated: "#252320"
  surface-dark-soft: "#1f1e1b"
  on-primary: "#ffffff"
  on-dark: "#faf9f5"
  on-dark-soft: "#a09d96"
  accent-teal: "#5db8a6"
  accent-amber: "#e8a55a"
  success: "#5db872"
  warning: "#d4a017"
  error: "#c64545"

typography:
  display-xl:
    fontFamily: "Copernicus, Tiempos Headline, serif"
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -1.5px
  display-lg:
    fontFamily: "Copernicus, Tiempos Headline, serif"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: -1px
  display-md:
    fontFamily: "Copernicus, Tiempos Headline, serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: -0.5px
  display-sm:
    fontFamily: "Copernicus, Tiempos Headline, serif"
    fontSize: 28px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: -0.3px
  title-lg:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 1.5px
  code:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  button:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0
  nav-link:
    fontFamily: "StyreneB, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
    height: 40px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
    height: 40px
  button-secondary-on-dark:
    backgroundColor: "{colors.surface-dark-elevated}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
  button-text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  button-icon-circular:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 36px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 64px
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-xl}"
    padding: 96px
  hero-illustration-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
  feature-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  product-mockup-card-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  code-window-card:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.code}"
    rounded: "{rounded.lg}"
    padding: 24px
  model-comparison-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  pricing-tier-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  pricing-tier-card-featured:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  callout-card-coral:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  connector-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.lg}"
    padding: 20px
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 10px 14px
    height: 40px
  text-input-focused:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  cookie-consent-card:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  category-tab:
    backgroundColor: transparent
    textColor: "{colors.muted}"
    typography: "{typography.nav-link}"
    padding: 8px 14px
    rounded: "{rounded.md}"
  category-tab-active:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.md}"
  badge-pill:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-coral:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption-uppercase}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  cta-band-coral:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  cta-band-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-soft}"
    typography: "{typography.body-sm}"
    padding: 64px
---

> 🌐 本文档由 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 翻译,英文原版见原项目。
>
> ⚠️ 本文件超过 10000 字符,仅汉化核心章节(概览 / 色彩 / 字体 / 布局 / 禁忌清单);组件明细、响应式、迭代指南等其余章节保留英文原版,请对照原项目阅读。

## 概览(Overview)

Claude.com 是 AI 产品品类中最温暖、最具编辑排版气质的界面。整体氛围建立在**带色调的米白画布**(`{colors.canvas}` — #faf9f5)之上——明显偏暖,刻意避开其他 AI 品牌千篇一律的冷灰白。标题使用**粗衬线展示字体**("Copernicus" / Tiempos Headline),字重 400、负字距,正文搭配 **StyreneB / Inter** 人文无衬线体。整体气质像一本文学出版物,而不是 SaaS 营销页。

品牌张力来自**米白 + 珊瑚色的配对**——珊瑚色(`{colors.primary}` — #cc785c)是 Anthropic 的标志性强调色,用于所有主 CTA、品牌字标以及通栏提示卡片。这种珊瑚色温暖、略微收敛,绝不用青色/蓝色——刻意与 OpenAI 的冷 slate 灰、Google 的高饱和蓝、Microsoft 的企业青形成反差定位。

该系统有三种表面模式,在页面间交替出现:
1. **米白画布**(`{colors.canvas}`)——默认页面底色
2. **浅米色卡片**(`{colors.surface-card}`)——特性卡片背景
3. **深色产品表面**(`{colors.surface-dark}`)——代码编辑器模型图、模型展示卡片、页脚前 CTA、页脚本身

深色表面是 Claude 展示产品外壳的地方——代码块、终端输出、模型对比表、代理流程图。米白到深色的对比构成了页面的节奏感。

**关键特征:**
- 暖米白画布(`{colors.canvas}` — #faf9f5)配深暖墨色文字(`{colors.ink}` — #141413)。这是品牌最具定义性的色彩选择。
- 珊瑚色主 CTA(`{colors.primary}` — #cc785c)。在单个按钮上克制使用,在通栏珊瑚提示卡片上大量使用。
- Copernicus / Tiempos Headline 粗衬线展示标题,字重 400、负字距。与人文无衬线正文搭配,形成文学化的编辑声音。
- 深色产品模型卡片(`{colors.surface-dark}` — #181715)承载代码块、终端面板、模型对比数据——品牌直接大规模展示真实产品外壳,而非抽象营销插画。
- 浅米色特性卡片(`{colors.surface-card}` — #efe9de)——比画布略深,用于内容驱动的特性说明。
- Anthropic 放射星标——一个类似星号的小黑色图形(四辐条放射状)——作为品牌字标前缀和内容标记出现。
- 圆角分层明确:`{rounded.md}`(8px)用于按钮与输入框,`{rounded.lg}`(12px)用于内容与产品卡片,`{rounded.xl}`(16px)用于 Hero 插画容器,`{rounded.pill}` 用于徽章。
- 区块节奏 `{spacing.section}`(96px)——现代 SaaS 标准。卡片内边距保持宽裕的 `{spacing.xl}`(32px)。

## 色彩(Colors)

### 品牌与强调色
- **珊瑚色 / 主色**(`{colors.primary}` — #cc785c):Anthropic 标志性的暖珊瑚色。用于所有主 CTA 背景、通栏珊瑚提示卡片、品牌字标点缀。除放射星标 logo 外最具辨识度的 Anthropic 色彩。
- **珊瑚色激活态**(`{colors.primary-active}` — #a9583e):按压/悬停时的加深变体。
- **珊瑚色禁用态**(`{colors.primary-disabled}` — #e6dfd8):去饱和的米白调禁用状态。
- **强调青绿**(`{colors.accent-teal}` — #5db8a6):少量用于次要产品表面(终端状态指示、连接器页的"已连接"圆点)。
- **强调琥珀**(`{colors.accent-amber}` — #e8a55a):用于分类徽章与行内高亮的小面积暖色伴生色。

### 表面
- **画布**(`{colors.canvas}` — #faf9f5):默认页面底色。带色调的米白——温暖,刻意不用纯白。
- **柔和表面**(`{colors.surface-soft}` — #f5f0e8):分区隔断、极柔和的带状背景。
- **卡片表面**(`{colors.surface-card}` — #efe9de):特性卡片、内容卡片。比画布深一档。
- **浓米色表面**(`{colors.surface-cream-strong}` — #e8e0d2):最深的米色变体,用于部分分类标签与强调区块带。
- **深色表面**(`{colors.surface-dark}` — #181715):代码编辑器模型图、模型展示卡片、页脚。主导深色表面。
- **深色浮起表面**(`{colors.surface-dark-elevated}` — #252320):深色区块内的浮起卡片(模型图中的设置面板)。
- **柔和深色表面**(`{colors.surface-dark-soft}` — #1f1e1b):略浅的深色,用于大深色卡片内部的代码块背景。
- **发丝线**(`{colors.hairline}` — #e6dfd8):米色表面上的 1px 边框色调。与 `{colors.primary-disabled}` 同色——边框读起来像一级高差,而不是墨线。
- **柔和发丝线**(`{colors.hairline-soft}` — #ebe6df):同一区块内几乎不可见的分隔线。

### 文字
- **墨色**(`{colors.ink}` — #141413):所有标题与主要文字。暖深色,略偏离纯黑。
- **正文强调**(`{colors.body-strong}` — #252523):强调段落、导语。
- **正文**(`{colors.body}` — #3d3d3a):默认行文颜色。
- **弱化**(`{colors.muted}` — #6c6a64):子标题、面包屑、页脚附近的次要文字。
- **更弱化**(`{colors.muted-soft}` — #8e8b82):说明文字、细则、版权行。
- **主色上的文字**(`{colors.on-primary}` — #ffffff):珊瑚色按钮上的文字。
- **深色上的文字**(`{colors.on-dark}` — #faf9f5):深色表面上带米调的白色(呼应画布色调)。
- **深色上的次要文字**(`{colors.on-dark-soft}` — #a09d96):页脚正文、深色模型图中的次要标签。

### 语义色
- **成功**(`{colors.success}` — #5db872):绿色状态圆点、"可用"指示。
- **警告**(`{colors.warning}` — #d4a017):警告提示(营销表面少见)。
- **错误**(`{colors.error}` — #c64545):校验错误。

## 字体(Typography)

### 字体族
系统使用 **Copernicus**(替代:**Tiempos Headline**)作为标题的粗衬线展示字体,**StyreneB**(替代:**Inter**)作为正文、导航和 UI 标签的人文无衬线体,**JetBrains Mono** 负责代码块。回退字体栈:展示字体为 `Tiempos Headline, Garamond, "Times New Roman", serif`,正文为 `Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif`。

展示/正文的分工是编辑式的:
- Copernicus 衬线(字重 400,负字距)→ h1、h2、h3、Hero 展示标题
- StyreneB 无衬线(字重 400-500)→ 正文、导航、按钮、说明文字、标签
- JetBrains Mono → 所有代码块与终端文字

### 层级(Hierarchy)

| Token | Size | Weight | Line Height | Letter Spacing | 用途 |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 64px | 400 | 1.05 | -1.5px | 首页 h1("Meet your thinking partner")— Copernicus 衬线 |
| `{typography.display-lg}` | 48px | 400 | 1.1 | -1px | 区块标题 — Copernicus |
| `{typography.display-md}` | 36px | 400 | 1.15 | -0.5px | 子区块标题、模型名 — Copernicus |
| `{typography.display-sm}` | 28px | 400 | 1.2 | -0.3px | 定价档位名、提示标题 — Copernicus |
| `{typography.title-lg}` | 22px | 500 | 1.3 | 0 | 定价方案规格标签 — StyreneB |
| `{typography.title-md}` | 18px | 500 | 1.4 | 0 | 特性卡片标题、引导段落 |
| `{typography.title-sm}` | 16px | 500 | 1.4 | 0 | 连接器磁贴标题、列表标签 |
| `{typography.body-md}` | 16px | 400 | 1.55 | 0 | 默认行文 — StyreneB |
| `{typography.body-sm}` | 14px | 400 | 1.55 | 0 | 页脚正文、细则 |
| `{typography.caption}` | 13px | 500 | 1.4 | 0 | 徽章标签、说明文字 |
| `{typography.caption-uppercase}` | 12px | 500 | 1.4 | 1.5px | 分类标签、"NEW" 徽章 |
| `{typography.code}` | 14px | 400 | 1.6 | 0 | 代码块 — JetBrains Mono |
| `{typography.button}` | 14px | 500 | 1.0 | 0 | 标准按钮文字 |
| `{typography.nav-link}` | 14px | 500 | 1.4 | 0 | 顶部导航菜单项 |

### 原则(Principles)
展示字号使用字重 400(常规),从不加粗。负字距(-0.3 至 -1.5px)必不可少——没有它的 Copernicus 一眼就不对味。衬线特质赋予了 Anthropic 文学般、深思熟虑的声音;换成无衬线展示字体会让 Claude 变得和其他 AI 工具毫无区别。

正文字重保持 400,标签和强调短语用 500。无衬线正文是人文风格的(StyreneB)——绝不是几何风格。Inter 因相近的人文比例是可接受的替代;Helvetica 或 Arial 过于中性,会破坏暖色编辑气质。

### 字体替代说明(Note on Font Substitutes)
如果 Copernicus / Tiempos Headline 不可用,**Cormorant Garamond**(字重 500、-0.02em 字距)是最接近的开源近似。**EB Garamond** 为后备。StyreneB 的最接近替代是 **Inter**——两者都是为屏幕阅读设计的人文无衬线体。有授权条件时 **Söhne** 也是接近的选择。

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 96px.
- **Section padding:** `{spacing.section}` (96px) — modern-SaaS rhythm.
- **Card internal padding:** `{spacing.xl}` (32px) for feature cards, pricing tier cards, model comparison cards; `{spacing.lg}` (24px) for code-window cards and connector tiles.
- **Callout / CTA bands:** `{spacing.xxl}` (48px) inside coral callout cards; 64px inside the larger dark CTA band.

### Grid & Container
- **Max content width:** ~1200px centered.
- **Editorial body:** Single 12-column grid; hero often uses 6/6 split (h1 left, illustration right).
- **Feature card grids:** 3-up at desktop, 2-up at tablet, 1-up at mobile.
- **Connector tile grids:** 4-up or 6-up at desktop, 2-up at tablet, 1-up at mobile.
- **Pricing grid:** 3-up at desktop (Free / Pro / Team / Enterprise often), 1-up at mobile.

### Whitespace Philosophy
The cream canvas + serif display + generous internal padding create an editorial pacing — Claude reads like a long-form magazine column rather than a marketing template. Whitespace between bands stays uniform at 96px; whitespace inside cards is generous (32px), letting type breathe.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Body sections, top nav, hero bands |
| Soft hairline | 1px `{colors.hairline}` border | Inputs, sub-nav, occasionally on cards |
| Cream card | `{colors.surface-card}` background — no shadow | Feature cards, content cards |
| Dark surface card | `{colors.surface-dark}` background — no shadow | Code editor mockups, model showcase cards |
| Subtle drop shadow | Faint shadow at low alpha | Hover-elevated states (the system uses `0 1px 3px rgba(20,20,19,0.08)` rarely) |

The elevation philosophy is **color-block first, shadow rare**. Most depth comes from the cream-vs-dark surface contrast. Shadows are minimal. The dark surface mockups have their own internal product chrome (code editor scrollbars, line numbers, syntax highlighting) which adds detail without needing external shadows.

### Decorative Depth
- The Anthropic spike-mark glyph (4-spoke radial asterisk) appears as a small black mark in the brand wordmark and inline as a content marker.
- Code editor mockups carry their own internal depth: syntax-highlighted text in muted blues / oranges / grays, line numbers in `{colors.muted-soft}`, status bars at the bottom in `{colors.surface-dark-elevated}`.
- Some hero illustrations use simple line-art with coral and dark-navy strokes on cream — minimal, hand-drawn-feeling, never photorealistic.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | Reserved for badge accents and tiny dropdowns |
| `{rounded.sm}` | 6px | Small inline buttons, dropdown items |
| `{rounded.md}` | 8px | Standard CTA buttons, text inputs, category tabs |
| `{rounded.lg}` | 12px | Content cards (feature, pricing, code-window, model-comparison) |
| `{rounded.xl}` | 16px | Hero illustration container, the larger marquee components |
| `{rounded.pill}` | 9999px | Badge pills, "NEW" tags |
| `{rounded.full}` | 9999px / 50% | Avatar substitutes, icon buttons |

### Photography & Illustrations
Claude's hero rarely uses photography. Instead it uses:
- Simple line-art illustrations with coral + dark-navy strokes on the cream canvas
- Code editor mockups (the dominant "hero" treatment on developer-focused pages)
- Terminal output mockups with monospace text on dark
- Model comparison cards (Opus / Sonnet / Haiku) with abstract geometric thumbnails

When photography is used (rare — mostly testimonials), avatars crop to perfect circles at 40px diameter.

## Components

### Top Navigation

**`top-nav`** — Cream nav bar pinned to the top of every page. 64px tall, `{colors.canvas}` background. Carries the Anthropic spike-mark + "Claude" wordmark at left, primary horizontal menu (Product, Solutions, Use Cases, Pricing, Research, Company) center-left, right-side cluster with "Sign in" text-link, "Try Claude" `{component.button-primary}` (coral). Menu items in `{typography.nav-link}` (StyreneB 14px / 500).

### Buttons

**`button-primary`** — The signature coral CTA. Background `{colors.primary}` (#cc785c), text `{colors.on-primary}` (white), type `{typography.button}` (StyreneB 14px / 500), padding 12px × 20px, height 40px, rounded `{rounded.md}` (8px). Active state `button-primary-active` darkens to `{colors.primary-active}` (#a9583e).

**`button-secondary`** — Cream button with hairline outline. Background `{colors.canvas}`, text `{colors.ink}`, 1px hairline border, same padding + height + radius as primary.

**`button-secondary-on-dark`** — Used over `{colors.surface-dark}` cards. Background `{colors.surface-dark-elevated}` (#252320), text `{colors.on-dark}`. Stays dark — the system never inverts to a light secondary on dark surfaces.

**`button-text-link`** — Inline text button, no background. Used for "Sign in" in the top nav and inline CTA links.

**`button-icon-circular`** — 36px circular icon button. Background `{colors.canvas}`, hairline border, ink-color icon. Used for carousel arrows, share, "view more".

**`text-link`** — Inline body links in `{colors.primary}` (the coral). Underlined on press; the coral inline link is one of the system's most distinctive small details.

### Cards & Containers

**`hero-band`** — Cream-canvas hero with a 6-6 grid: h1 + sub-headline + button row on the left, hero illustration card or product mockup card on the right. Vertical padding `{spacing.section}` (96px).

**`hero-illustration-card`** — A larger card holding the hero's right-side artifact — sometimes a coral-stroke line illustration on cream background, sometimes a dark code editor mockup. Background `{colors.canvas}` or `{colors.surface-dark}` depending on context, rounded `{rounded.xl}` (16px).

**`feature-card`** — Used in 3-up feature grids. Background `{colors.surface-card}` (#efe9de — slightly darker cream), rounded `{rounded.lg}` (12px), internal padding `{spacing.xl}` (32px). Carries a small icon at top, an `{typography.title-md}` headline, and a body description in `{typography.body-md}`.

**`product-mockup-card-dark`** — Dark navy card showing actual Claude product chrome (chat interface, code editor, agent controls). Background `{colors.surface-dark}`, rounded `{rounded.lg}`, internal padding `{spacing.xl}` (32px). Carries text labels in `{colors.on-dark}` and product UI fragments below.

**`code-window-card`** — A specialized dark card showing a code editor with line numbers, syntax-highlighted code in `{typography.code}` (JetBrains Mono), and sometimes a "Run" button or terminal output panel below. Background `{colors.surface-dark}` with `{colors.surface-dark-soft}` for the inner code block, rounded `{rounded.lg}`, padding `{spacing.lg}` (24px). The signature visual element of Claude Code product pages.

**`model-comparison-card`** — Used on the homepage's "Which problem are you up against?" section comparing Opus / Sonnet / Haiku. Background `{colors.canvas}` with hairline border, rounded `{rounded.lg}`, internal padding `{spacing.xl}` (32px). Carries the model name, a short capability blurb, and a `{component.text-link}` to learn more.

**`pricing-tier-card`** — Standard tier card. Background `{colors.canvas}` with hairline border, rounded `{rounded.lg}`, padding `{spacing.xl}` (32px). Carries the plan name in `{typography.title-lg}` (StyreneB), price in `{typography.display-sm}` (Copernicus serif!), feature checklist in `{typography.body-md}`, and a `{component.button-primary}` at the bottom.

**`pricing-tier-card-featured`** — The featured tier (typically "Pro" or "Team"). Background flips to `{colors.surface-dark}`, text inverts to `{colors.on-dark}`. The dark surface IS the featured-tier signal.

**`callout-card-coral`** — A full-bleed coral card carrying a major call-to-action. Background `{colors.primary}` (#cc785c), text `{colors.on-primary}` (white), rounded `{rounded.lg}`, padding `{spacing.xxl}` (48px). The coral surface IS the voltage; the CTA inside uses an inverted button style (cream/canvas button on coral).

**`connector-tile`** — Used on the connectors page's integration grid. Background `{colors.canvas}` with hairline border, rounded `{rounded.lg}`, padding 20px. Each tile carries a logo at top, a `{typography.title-sm}` connector name, and a short description.

### Inputs & Forms

**`text-input`** — Standard text input. Background `{colors.canvas}`, text `{colors.ink}`, type `{typography.body-md}`, rounded `{rounded.md}` (8px), padding 10px × 14px, height 40px. 1px hairline border in `{colors.hairline}`.

**`text-input-focused`** — Focus state. Border thickens or shifts to `{colors.primary}` (coral) for emphasis. Carries a 3px coral-at-15%-alpha outer ring.

**`cookie-consent-card`** — Bottom-right floating dark cookie banner. Background `{colors.surface-dark}`, text `{colors.on-dark}`, rounded `{rounded.lg}`, padding `{spacing.lg}` (24px). One of the few places dark surface appears at small scale on cream pages.

### Tags / Badges

**`badge-pill`** — Small pill label used for category tags. Background `{colors.surface-card}`, text `{colors.ink}`, type `{typography.caption}` (13px / 500), rounded `{rounded.pill}`, padding 4px × 12px.

**`badge-coral`** — Coral-fill badge for "NEW", "BETA", featured highlights. Background `{colors.primary}`, text `{colors.on-primary}`, type `{typography.caption-uppercase}` (12px / 500 / 1.5px tracking), rounded `{rounded.pill}`, padding 4px × 12px.

### Tab / Filter

**`category-tab`** + **`category-tab-active`** — Used in sub-nav rows on solutions / connectors pages. Inactive: transparent background, `{colors.muted}` text. Active: `{colors.surface-card}` background, `{colors.ink}` text. Padding 8px × 14px, rounded `{rounded.md}`.

### CTA / Footer

**`cta-band-coral`** — A pre-footer "Try Claude" CTA card. Full-width coral fill, white type, rounded `{rounded.lg}`, padding 64px. Carries an h2 in `{typography.display-sm}` (still serif!), a sub-line, and a cream-button CTA.

**`cta-band-dark`** — Alternative pre-footer band on developer-focused pages. Background `{colors.surface-dark}`, text `{colors.on-dark}`, rounded `{rounded.lg}`, padding 64px. Often pairs with a code-window card.

**`footer`** — Dark navy footer that closes every page. Background `{colors.surface-dark}` (#181715), text `{colors.on-dark-soft}`. 4-column link list at desktop covering Product / Company / Resources / Legal. Vertical padding 64px. The Anthropic spike-mark + "Anthropic" wordmark sits at the top in `{colors.on-dark}`. The footer never inverts.

## 应做与禁忌(Do's and Don'ts)

### 应做(Do)
- 每个页面都锚定在米白画布上。纯白会读成"随便哪个 AI 工具";暖色调才是品牌差异点。
- 所有展示标题都用 Copernicus 衬线,搭配 StyreneB 无衬线正文。展示字号的负字距没有商量余地。
- 把 `{colors.primary}`(珊瑚色)留给主 CTA 和通栏 `{component.callout-card-coral}` 时刻。不要在其他强调处随意涂珊瑚色。
- 用 `{component.product-mockup-card-dark}` 和 `{component.code-window-card}` 展示真实的 Claude 产品外壳。能放真代码就别画营销插画。
- 让 `{component.feature-card}`(米色)与 `{component.product-mockup-card-dark}`(深色)在相邻区块交替出现。米白到深色的节奏就是品牌的呼吸机制。
- 用 Anthropic 放射星标图形作为品牌字标前缀。字标内部绝不反白放在深色上。
- 主要区块之间应用 `{spacing.section}`(96px)。

### 禁忌(Don't)
- 不要用冷灰或纯白做画布。米白就是品牌。
- 不要加粗衬线展示字重。Copernicus 用 700 会显得浮夸;系统保持在 400。
- 不要用冷蓝或高饱和青色当品牌强调色。珊瑚色才是品牌电压。
- 不要把珊瑚色铺满页面。它在单个元素上稀缺,只在通栏珊瑚提示卡片上慷慨。
- 不要用 Inter 做展示标题。衬线特质就是品牌声音。
- 不要在相邻两个区块重复同一表面模式。节奏必须交替:米白 → 米色卡片 → 深色模型图 → 米白 → 珊瑚提示 → 深色页脚。
- 不要添加系统未编码的悬停样式——主按钮按压时加深,其余一律不变。

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Hamburger nav; hero h1 64→32px; hero-illustration-card stacks below content; feature grids 1-up; connector tiles 2-up; pricing 1-up; footer 4 cols → 1 |
| Tablet | 768–1024px | Top nav stays horizontal but tightens; feature cards 2-up; connector tiles 3-up; pricing 2-up |
| Desktop | 1024–1440px | Full top-nav with all menu items; 3-up feature cards; 4-up or 6-up connector tiles; 3-up pricing tiers |
| Wide | > 1440px | Same as desktop with more outer breathing room; max content width caps at 1200px |

### Touch Targets
- `{component.button-primary}` at minimum 40 × 40px.
- `{component.button-icon-circular}` at exactly 36 × 36 — slightly under WCAG 44 but visually centered.
- `{component.text-input}` height is 40px.
- Connector tile entire card area is tappable; effective tap area >> 44px.

### Collapsing Strategy
- Top nav collapses to hamburger at < 768px; menu opens as a full-screen cream sheet.
- Hero band's 6-6 grid collapses to single-column on mobile — h1 + sub-head + buttons first, then the illustration / mockup card below.
- Feature grids reduce columns rather than scaling cards down.
- Pricing tier cards collapse 4 → 2 → 1; featured-tier dark surface stays visually distinct at every breakpoint.
- Code-window cards retain code legibility at every breakpoint by allowing horizontal scroll within the card rather than wrapping code lines.

### Image Behavior
- Code blocks inside dark mockups stay at fixed font-size; horizontal scroll on mobile rather than wrapping.
- Hero illustrations scale proportionally; line-art strokes thin slightly on mobile.
- Avatar photos in testimonials crop to circles at every breakpoint.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key (`{component.feature-card}`, `{component.code-window-card}`).
2. Variants of an existing component (`-active`, `-disabled`, `-focused`) live as separate entries in `components:`.
3. Use `{token.refs}` everywhere — never inline hex.
4. Never document hover. Default and Active/Pressed states only.
5. Display headlines stay Copernicus serif 400 with negative tracking. Body stays StyreneB / Inter 400. The split is unbreakable.
6. Cream + coral + dark navy is the trinity. Don't introduce a fourth surface tone (no purple cards, no green sections).
7. When in doubt about emphasis: bigger Copernicus serif before bolder weight.

## Known Gaps

- Copernicus and StyreneB are licensed Anthropic typefaces and not available as public web fonts. Substitutes (Tiempos Headline / Cormorant Garamond / EB Garamond for serif; Inter / Söhne for sans) are documented in the typography section.
- The Anthropic radial-spike-mark is a brand glyph rendered as inline SVG; it's not formalized as a system token here. Treat it as a logo asset.
- Animation and transition timings (chat message reveal, code block typewriter effect on the homepage, agentic-flow diagram animations) are not in scope.
- Form validation states beyond `{component.text-input-focused}` are not extracted — error / success states would need a sign-up or feedback flow to confirm.
- The actual Claude product surface (claude.ai chat interface) shares some tokens with the marketing site but adds many product-specific components (chat bubbles, message tools, file upload chips, conversation history sidebar) that are out of scope for this marketing-surface document.
- The "agent" / "computer use" demo cards on certain pages display animated Claude controlling a browser — the static screenshot doesn't fully capture the animation chrome.
