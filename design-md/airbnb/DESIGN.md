---
version: alpha
name: Airbnb-design-analysis
description: A warm, generous consumer marketplace anchored on a clean white canvas and Airbnb Rausch (#ff385c), the single brand voltage that carries every primary CTA, search-button orb, and rating dot. Type runs Airbnb Cereal VF at modest weights — display sits at 22–28px in weight 500/600 rather than the heavy 700+ that fintech and enterprise systems use; the brand trusts photography and generous whitespace over typographic muscle. Three product entries (Homes, Experiences, Services) sit in the top nav with hand-illustrated 32-icon glyphs and "NEW" badges, signaling a marketplace expansion rather than a feature dump. Pill-shaped search bars (`{rounded.full}`), softly rounded property cards (`{rounded.lg}` ~14px), and 32px button radii read as friendly and human — there is no hard corner anywhere except the body grid.

colors:
  primary: "#ff385c"
  primary-active: "#e00b41"
  primary-disabled: "#ffd1da"
  primary-error-text: "#c13515"
  primary-error-text-hover: "#b32505"
  luxe: "#460479"
  plus: "#92174d"
  ink: "#222222"
  body: "#3f3f3f"
  muted: "#6a6a6a"
  muted-soft: "#929292"
  hairline: "#dddddd"
  hairline-soft: "#ebebeb"
  border-strong: "#c1c1c1"
  canvas: "#ffffff"
  surface-soft: "#f7f7f7"
  surface-card: "#ffffff"
  surface-strong: "#f2f2f2"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  legal-link: "#428bff"
  star-rating: "#222222"
  scrim: "#000000"

typography:
  display-xl:
    fontFamily: "'Airbnb Cereal VF', Circular, -apple-system, system-ui, Roboto, 'Helvetica Neue', sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  display-lg:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.18
    letterSpacing: -0.44px
  display-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 21px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  display-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: -0.18px
  title-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  title-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  rating-display:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -1px
  body-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  caption:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.29
    letterSpacing: 0
  caption-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.23
    letterSpacing: 0
  badge:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.18
    letterSpacing: 0
  micro-label:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.33
    letterSpacing: 0
  uppercase-tag:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 8px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0.32px
    textTransform: uppercase
  button-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  button-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.29
    letterSpacing: 0
  link:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  nav-link:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0

rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 14px
  lg: 20px
  xl: 32px
  full: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  base: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 64px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    height: 48px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    rounded: "{rounded.sm}"
    padding: 13px 23px
    height: 48px
  button-tertiary-text:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
  button-pill-rausch:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.full}"
    padding: 10px 20px
  search-orb:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
    height: 48px
  icon-button-circle:
    backgroundColor: "{colors.surface-strong}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    height: 32px
  icon-button-outline:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    height: 40px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 80px
  product-tab-active:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
  product-tab-inactive:
    backgroundColor: transparent
    textColor: "{colors.muted}"
    typography: "{typography.nav-link}"
  search-bar-pill:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: 14px 24px
    height: 64px
  search-field-segment:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    padding: 8px 24px
  category-strip:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.muted}"
    typography: "{typography.button-sm}"
  category-tab-active:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.none}"
  property-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
  property-card-photo:
    rounded: "{rounded.md}"
  experience-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.md}"
  city-link-block:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
  rating-display-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.rating-display}"
  guest-favorite-badge:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.badge}"
    rounded: "{rounded.full}"
    padding: 4px 10px
  new-tag:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.uppercase-tag}"
    rounded: "{rounded.full}"
    padding: 2px 6px
  amenity-row:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    padding: 12px 0
  reviews-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
  host-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 24px
  reservation-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 24px
  date-picker-day:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
  date-picker-day-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 14px 12px
    height: 56px
  footer-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    padding: 48px 80px
  footer-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
  legal-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.muted}"
    typography: "{typography.caption-sm}"
---

> 🌐 本文档由 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 翻译,英文原版见原项目。
>
> ⚠️ 本文件超过 10000 字符,仅汉化核心章节(概览 / 色彩 / 字体);布局、组件、响应式等其余章节保留英文原版,请对照原项目阅读。

## 概览(Overview)

Airbnb 是"慷慨的、摄影驱动的消费级市场"的教科书范例。基础画布是**纯白**(`{colors.canvas}` — #ffffff),标题与正文用深近黑墨色(`{colors.ink}` — #222222),唯一的电压来自**Rausch 珊瑚红**(`{colors.primary}` — #ff385c)——承担所有主 CTA、搜索按钮圆球、收藏红心以及行内品牌链接。主线营销没有第二品牌色——**Luxe 紫**(`{colors.luxe}` — #460479)与 **Plus 品红**(`{colors.plus}` — #92174d)是子品牌强调色,只出现在 Airbnb Luxe / Plus 语境中。

字体使用 **Airbnb Cereal VF**(Airbnb 授权的自研可变字体),历史备选是自家的 **Circular**,底下再垫系统字体栈。Cereal 保持在克制字重——展示标题以 22–28px、字重 500–600 渲染,不是金融或企业系统偏好的 700+ 重字重。首页 Hero h1("Inspiration for future getaways")只有 28px / 700,放在典型 SaaS 页面上会显得小;在这里却成立,因为版式靠摄影(城市拼贴、房源卡片)承担视觉重量,而不是靠字体肌肉。

形状语言是**柔软的**。按钮 8px 圆角(`{rounded.sm}`),房源卡片约 14px(`{rounded.md}`),搜索栏完全是药丸形(`{rounded.full}`),心愿红心和搜索圆球是圆形(`{rounded.full}`),分类条圆角达 32px(`{rounded.xl}`)。除正文栅格本身外几乎不存在硬角——每个可交互元素都是圆润的。

**关键特征:**
- 单一强调色:`{colors.primary}`(#ff385c — "Rausch")承担所有主 CTA、搜索圆球、收藏红心和品牌字标。使用克制——多数页面是 90% 白 + 墨色,只点缀一两个 Rausch 时刻。
- 自研可变字体:`Airbnb Cereal VF`。展示字重 500–700,正文 400。克制的字重是刻意的——系统信任摄影来提供视觉分量。
- 三产品顶部导航:Homes、Experiences、Services——各配手绘风 32px 图标,两个较新的产品带 "NEW" 徽章(`{component.new-tag}`)。激活页签用下划线规则(`{component.product-tab-active}`)。
- 药丸形全局搜索栏:白色表面,全圆角(`{rounded.full}`),用 1px 发丝线分隔为 Where / When / Who 三段,末端是一个圆形 Rausch 搜索圆球(`{component.search-orb}`)。
- 房源卡片照片优先:定宽高比的矩形配 `{rounded.md}` 圆角裁切、可滑动图片轮播、左上角"Guest favorite"悬浮徽章、右上角红心图标,下面是 4–5 行元信息。
- 编辑式下拉(页脚、语言选择器)是白底上的干净文字栏——没有卡片表面,没有阴影。
- 设计系统把层级封顶在单一阴影档(`box-shadow: rgba(0,0,0,0.02) 0 0 0 1px, rgba(0,0,0,0.04) 0 2px 6px, rgba(0,0,0,0.1) 0 4px 8px`)——用于悬停浮起的卡片和搜索/账户下拉。
- 8px 基础间距系统,主要区块间距 `{spacing.section}`(64px)——慷慨但不足以显得像编辑杂志;市场密度要求每屏滚动容纳更多卡片。

## 色彩(Colors)

### 品牌与强调色
- **Rausch**(`{colors.primary}` — #ff385c):唯一的品牌色。用于主 CTA 背景(Reserve、Continue)、搜索圆球、房源卡片上的收藏红心、行内品牌链接。消费级旅行领域最具辨识度的颜色。
- **Rausch 激活态**(`{colors.primary-active}` — #e00b41):按压 / 指针按下变体——饱和度略高。用于 `{component.button-primary-active}`。
- **Rausch 禁用态**(`{colors.primary-disabled}` — #ffd1da):苍白色调,用于禁用 CTA。
- **Luxe 紫**(`{colors.luxe}` — #460479):Airbnb Luxe 的子品牌强调色。只出现在 Luxe 品牌表面——绝不上主线营销。
- **Plus 品红**(`{colors.plus}` — #92174d):Airbnb Plus 的子品牌强调色。与 Luxe 同样的作用域——仅限子产品。

### 表面
- **画布**(`{colors.canvas}` — #ffffff):所有公开页面的默认底色。Airbnb 公开网页不提供暗色模式。
- **柔和表面**(`{colors.surface-soft}` — #f7f7f7):最浅的填充——用于禁用字段、子导航悬停背景和行内搜索筛选条。
- **加重表面**(`{colors.surface-strong}` — #f2f2f2):略重的填充——圆形图标按钮表面(如面包屑返回箭头和房源工具栏按钮)。

### 发丝线与边框
- **发丝线**(`{colors.hairline}` — #dddddd):默认 1px 边框色调——搜索栏分隔线、表格分隔、页脚栏目分割线、卡片 1px 边框。
- **柔和发丝线**(`{colors.hairline-soft}` — #ebebeb):更浅的分隔线,用于长滚动的编辑式正文分隔。
- **加重边框**(`{colors.border-strong}` — #c1c1c1):更重的描边,用于禁用的描边按钮和聚焦后的表单输入框轮廓。

### 文字
- **墨色**(`{colors.ink}` — #222222):浅色表面上的主导文字色。展示标题、正文段落、主导航链接和多数行内链接文字。从不用纯黑。
- **正文**(`{colors.body}` — #3f3f3f):次要行文色,用于长篇点评和设施描述等墨色会显得过重的场合。
- **弱化**(`{colors.muted}` — #6a6a6a):城市链接块内的副标题("Cottage rentals"、"Villa rentals")、未激活的产品页签标签、页脚分类子标签、"View all" 链接。
- **更弱化**(`{colors.muted-soft}` — #929292):禁用链接文字。使用非常克制。
- **星级评分**(`{colors.star-rating}` — #222222):与墨色同一令牌——Airbnb 的星星图标和 "4.81" 评分数字都用墨色渲染,而非黄/金色,这是刻意的品牌选择(黄星星在旅行语境里显得廉价)。
- **主色上的文字**(`{colors.on-primary}` — #ffffff):Rausch CTA 上的白色文字。

### 语义色
- **错误**(`{colors.primary-error-text}` — #c13515):表单校验的行内错误文字。与 Rausch 区分开——略深、更饱和的红。
- **错误悬停**(`{colors.primary-error-text-hover}` — #b32505):链接悬停时加深。
- **法务链接蓝**(`{colors.legal-link}` — #428bff):法务文案(Privacy、Terms)内的行内链接。只在法务子区块中使用。

### 遮罩
- **遮罩**(`{colors.scrim}` — #000000,50% 不透明度):全局弹窗背景色调——日期选择器、登录对话框、语言选择器。存储为基础十六进制值;不透明度在渲染时应用。

## 字体(Typography)

### 字体族
整个系统只用 **Airbnb Cereal VF**——展示、正文、导航、说明、微文案。回退栈为 `Circular, -apple-system, system-ui, Roboto, "Helvetica Neue", sans-serif`。**Circular** 是历史上的自研字体,仍作为第一个非可变回退保留;系统字体栈再兜底。

没有独立的展示字族。可变字体承担整个字号阶梯。

### 层级(Hierarchy)

| Token | Size | Weight | Line Height | Letter Spacing | 用途 |
|---|---|---|---|---|---|
| `{typography.rating-display}` | 64px | 700 | 1.1 | -1px | 房源详情评分展示("4.81") |
| `{typography.display-xl}` | 28px | 700 | 1.43 | 0 | 首页 h1("Inspiration for future getaways") |
| `{typography.display-lg}` | 22px | 500 | 1.18 | -0.44px | 房源详情 h1("Close to Fethiye Aliyah Bali Beach…") |
| `{typography.display-md}` | 21px | 700 | 1.43 | 0 | 房源详情内的区块标题("What this place offers") |
| `{typography.display-sm}` | 20px | 600 | 1.20 | -0.18px | 子区块标题("Things to know") |
| `{typography.title-md}` | 16px | 600 | 1.25 | 0 | 城市链接块标题("Wilmington"、"Athens") |
| `{typography.title-sm}` | 16px | 500 | 1.25 | 0 | 页脚栏目头("Support"、"Hosting"、"Airbnb") |
| `{typography.body-md}` | 16px | 400 | 1.5 | 0 | 房源文案内的默认行文 |
| `{typography.body-sm}` | 14px | 400 | 1.43 | 0 | 卡片元信息行、日期、价格、距离文字 |
| `{typography.caption}` | 14px | 500 | 1.29 | 0 | 搜索字段段标签("Where"、"When"、"Who") |
| `{typography.caption-sm}` | 13px | 400 | 1.23 | 0 | 页脚法务行("© 2026 Airbnb, Inc.") |
| `{typography.badge}` | 11px | 600 | 1.18 | 0 | "Guest favorite" 悬浮徽章文字 |
| `{typography.micro-label}` | 12px | 700 | 1.33 | 0 | 卡片设施微标签("Inline 6") |
| `{typography.uppercase-tag}` | 8px | 700 | 1.25 | 0.32px(大写) | 产品导航页签上的 "NEW" 徽章 |
| `{typography.button-md}` | 16px | 500 | 1.25 | 0 | 主 CTA 按钮标签 |
| `{typography.button-sm}` | 14px | 500 | 1.29 | 0 | 药丸按钮标签(分类条) |
| `{typography.link}` | 14px | 400 | 1.43 | 0 | 行内正文链接 |
| `{typography.nav-link}` | 16px | 600 | 1.25 | 0 | 顶部产品导航标签(Homes、Experiences、Services) |

### 原则(Principles)
展示字重保持克制。首页 h1 只有 28px / 700,是刻意的小——它收在搜索栏下方,让摄影和城市链接网格承担视觉层级。房源详情 h1 只有 22px / 500,更加安静;上方的房源照片横幅才是主角。

整个系统中唯一字体上"响亮"的时刻,是房源页的**评分展示**(`{typography.rating-display}` — 64px / 700)。这是系统唯一单纯信任字体来承载层级的地方——评分数字是信任度的峰值信号,所以得到最响亮的处理。

### 字体替代说明(Note on Font Substitutes)
如果 Airbnb Cereal VF 和 Circular 都不可用,**Inter** 是最接近的开源替代。展示标题的行高再下调约 2% 以匹配 Cereal 略紧的大写字高;其余比例可以干净地迁移。

## Layout

### Spacing System
- **Base unit:** 4px (with 2px micro-step).
- **Tokens:** `{spacing.xxs}` 2px · `{spacing.xs}` 4px · `{spacing.sm}` 8px · `{spacing.md}` 12px · `{spacing.base}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 64px.
- **Section padding (vertical):** `{spacing.section}` (64px) for major page bands; tighter than typical SaaS marketing (80–96px) because marketplace pages need higher card density per scroll.
- **Card internal padding:** `{spacing.lg}` (24px) for `{component.host-card}` and `{component.reservation-card}`; `{spacing.base}` (16px) for property-card meta block; `{spacing.sm}` (8px) for caption / date-row gutters.
- **Gutters:** `{spacing.base}` (16px) between cards in the homepage city grid; `{spacing.lg}` (24px) inside footer column gutters; `{spacing.xs}` (4px) on dense category-strip dividers.

### Grid & Container
- **Max content width:** ~1280px centered on the homepage and editorial pages. Listing detail pages cap closer to 1080px to keep the photo banner and reservation rail readable.
- **City link grid (homepage footer):** 6-column grid at desktop with each cell housing a city name in `{typography.title-md}` and a category sub-label in `{typography.body-sm}` muted.
- **Listing detail:** 2-column with photo / amenity body on the left (~64% width) and a sticky reservation card (`{component.reservation-card}`) on the right (~32%).
- **Footer:** 3-column link list (Support / Hosting / Airbnb) at desktop, collapsing to 1-column on mobile.

### Whitespace Philosophy
The system gives editorial bands 64px of vertical breathing room but compresses card grids — property and city-link cards sit just 16px apart. The contrast is intentional: the page reads as "open hero, dense marketplace below," reinforcing the marketplace nature without overwhelming the visitor at the fold.

## Elevation

The system has essentially **one shadow tier** plus the flat baseline.

- **Flat (no shadow):** Body, hero, footer, all editorial bands — 95% of surfaces.
- **Card hover float:** `box-shadow: rgba(0, 0, 0, 0.02) 0 0 0 1px, rgba(0, 0, 0, 0.04) 0 2px 6px 0, rgba(0, 0, 0, 0.1) 0 4px 8px 0` — applied to property cards on pointer hover, the search bar at rest, and the dropdown menus (account menu, language picker, date picker). This is the single shadow definition in the entire system.
- **Modal scrim:** `{colors.scrim}` rendered at 50% opacity — the global modal backdrop. Used on date pickers, login dialogs, language picker.

There are no progressive elevation tiers — the system either has the one shadow or none. Depth comes from photography, the white-on-white surface separation, and rounded-corner clipping rather than from layered shadows.

## Components

### Buttons

**`button-primary`** — Rausch fill, white text, 8px radius, 14×24px padding, 48px height, weight 500. The most common CTA across the system: "Reserve", "Continue", "Search", account-flow primaries.

**`button-primary-active`** — The press state. Background flips to `{colors.primary-active}`. No transform, no shadow change.

**`button-primary-disabled`** — Pale Rausch tint at #ffd1da with white text. Cursor not-allowed.

**`button-secondary`** — White fill with ink text and a 1px ink outline. 8px radius. Used for "Save", "Cancel", and inverse CTAs over Rausch surfaces.

**`button-tertiary-text`** — Plain ink text, no surface, no border. Underlined on hover. Used for "Show more" type links and modal close labels.

**`button-pill-rausch`** — A pill-shaped Rausch CTA used on featured cells (e.g., "Become a host" sub-CTA) — 9999px radius, 10×20px padding, 14px label.

### Search Surface

**`search-bar-pill`** — The signature global search bar. White fill, 9999px radius, 64px height, 1px hairline 1px-shadow border. Internally divided by vertical hairline rules into `{component.search-field-segment}` cells (Where / When / Who). Each segment holds an uppercase caption label above a placeholder line in `{typography.caption}`.

**`search-orb`** — The circular Rausch orb terminating the right edge of the search bar. 48×48px, fully rounded, white magnifying-glass icon centered. The hottest single color moment on the homepage.

### Top Navigation

**`top-nav`** — White surface, 80px height, 1px bottom hairline. The Airbnb wordmark sits flush left, the three product tabs (Homes / Experiences / Services) sit in the dead center, and account utilities (host link, language globe, account menu) sit flush right.

**`product-tab-active`** — Ink label in `{typography.nav-link}`, 32px hand-illustrated icon, 2px ink underline rule beneath the icon-label pair.

**`product-tab-inactive`** — Muted label, illustrated icon, no underline. Becomes active on click.

**`new-tag`** — A tiny rounded-pill badge (`{rounded.full}`) anchored top-right of an icon, carrying the uppercase "NEW" label in `{typography.uppercase-tag}` (8px / 700 with 0.32px tracking, uppercase). Used on Experiences and Services to signal recency.

### Listing Cards

**`property-card`** — A photo-first card. 1:1 aspect-ratio image with `{rounded.md}` corner clipping, image carousel dots overlay, "Guest favorite" floating badge top-left (`{component.guest-favorite-badge}`), and a heart icon top-right (`{component.icon-button-circle}` in default outlined state, Rausch-filled when saved). Beneath the image: 4–5 lines of meta — title (`{typography.title-md}`), distance / dates (`{typography.body-sm}` muted), and price ("$X night") right-aligned.

**`property-card-photo`** — The photo plate itself, separated as a token because some surfaces (wishlist, search results) reuse just the photo without the meta block.

**`experience-card`** — A taller-aspect card (4:5) for experience listings. Same `{rounded.md}` clipping, floating "NEW" badge top-left, heart top-right, and a single-line title beneath.

**`guest-favorite-badge`** — White rounded pill (`{rounded.full}`) at 11px / 600 weight. Sits over the photo with the system's only shadow tier applied for elevation.

### Listing Detail

**`rating-display-card`** — The signature listing-detail moment. A 64px / 700 rating number ("4.81") flanked left and right by tiny laurel-wreath SVG ornaments. Beneath the rating: "Guest favorite" tagline and a row of ink stat columns. The largest typographic weight in the whole system.

**`amenity-row`** — A 1-column list of amenity icons + ink labels in `{typography.body-md}`. 12px row padding, no border between rows; section is closed by a 1px hairline divider above and below.

**`reviews-card`** — A 2-column grid of review excerpts. Each column holds an author row (avatar, name, date) above a 3-line excerpt with "Show more" tertiary link.

**`host-card`** — A white card with `{rounded.md}` rounding and 24px padding holding a host avatar, name, "Superhost" badge, response-rate stat, and a "Contact host" `{component.button-secondary}`.

**`reservation-card`** — The sticky right-rail card on listing detail pages. White surface, `{rounded.md}` rounding, 1px hairline border, 1px shadow tier elevation, 24px padding. Contains: nightly price (`{typography.display-md}` ink), date-range selector, guest-count stepper, "Reserve" primary CTA full-width, and a fee breakdown stack beneath in `{typography.body-sm}`.

### Date Picker

**`date-picker-day`** — A 40×40px circular cell carrying the day number in `{typography.body-sm}`. Default state is transparent fill, ink text.

**`date-picker-day-selected`** — Ink fill, white text, full circle (`{rounded.full}`). Range states between two selected days carry a `{colors.surface-soft}` lozenge background that connects them.

### Forms

**`text-input`** — White surface, 1px hairline outline, `{rounded.sm}` 8px radius, 56px height, 14×12px padding. Stacked label above (in `{typography.caption}` muted), placeholder text in `{typography.body-md}` muted. On focus, the border thickens to 2px ink and the border color flips to `{colors.ink}` — no glow, no ring.

### Footer

**`footer-light`** — White surface (matches the page canvas — Airbnb has no contrast footer), 48×80px padding. Three columns of link blocks (Support / Hosting / Airbnb), separated by generous 24px gutters. Each column heads with a `{typography.title-sm}` ink label and stacks `{component.footer-link}` rows in `{typography.body-sm}` ink.

**`legal-band`** — A bottom strip beneath the footer columns carrying the copyright line, language picker (globe icon + "English (US)" link), currency picker, and social icons (Facebook, X, Instagram). All text in muted `{colors.muted}` at `{typography.caption-sm}`.

## Responsive Behavior

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 744px | Top nav collapses to logo + hamburger; product tabs hide behind a sheet; search bar collapses to a single tappable pill; property cards stack 1-up; city grid 1-column; listing detail collapses reservation card to a sticky bottom bar. |
| Tablet | 744–1128px | Top nav keeps product tabs but search bar narrows; property cards 2-up; city grid 2–3 column; reservation card stays sticky right-rail at narrower width. |
| Desktop | 1128–1440px | Full top nav with three product tabs centered; search bar at full pill width with all 3 segments visible; property cards 4-up; city grid 6-column; listing detail 2-column with reservation rail. |
| Wide | > 1440px | Content width caps at 1440px on listing/search pages and ~1280px on editorial; gutters absorb the rest. |

### Touch Targets
- Primary CTAs at minimum 48×48px (above WCAG AAA).
- Search orb is 48×48px circular — the most-tapped element on the page.
- Heart save button is 32×32px circular — borderline for AAA but compensated by a generous 12px padding inside the photo card.
- Date-picker day cells are 40×40px circular.

### Collapsing Strategy
- Top product tabs collapse into a hamburger sheet below 744px.
- Search bar's 3 segments collapse into a single-tap entry that opens a full-screen search overlay on mobile.
- Property and city-link grids drop column counts cleanly at each breakpoint — never reflow rows; always reduce columns.
- Reservation card on listing detail switches from sticky right-rail to a sticky bottom bar on mobile, carrying just the "Reserve" CTA + nightly price summary.

## Known Gaps

- **Hover state colors:** intentionally not documented per the global no-hover policy — Airbnb's actual `:hover` styling for property cards is a subtle elevation lift, but precise extraction is unreliable.
- **Loading states / skeleton screens:** not visible on the extracted surfaces.
- **Map view styling:** the search-results map uses Mapbox-tinted tiles with custom Rausch markers; not captured here.
- **Form input error states:** error text color (`{colors.primary-error-text}`) is documented, but the full input outline + helper-text combination on validation failure was not visible in the captured surfaces.
- **Sub-brand palettes:** Luxe (`{colors.luxe}`) and Plus (`{colors.plus}`) are documented as tokens, but their full sub-system (typography overrides, surface treatment) lives on separate sub-domains and is not captured here.
