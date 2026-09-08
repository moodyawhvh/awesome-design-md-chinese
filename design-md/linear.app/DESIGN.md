---
version: alpha
name: Linear-design-analysis
description: "A near-black product-focused marketing canvas built around #010102 (the deepest dark surface of any tool in this collection), light gray text (#f7f8f8), and the signature Linear lavender-blue (#5e6ad2) used as the single chromatic accent. The system reads as software-craft documentation: dense, technical, and quietly luxurious. Display type is set in the Linear custom sans (SF Pro Display fallback) at 500–700 with measured negative tracking. Cards live as charcoal panels (#0f1011) with hairline borders. The accent lavender appears on the brand mark, focus rings, and a few intentional CTAs — never decoratively. Page rhythm leans on product UI screenshots framed in dark panels rather than atmospheric color."

colors:
  primary: "#5e6ad2"
  on-primary: "#ffffff"
  primary-hover: "#828fff"
  primary-focus: "#5e69d1"
  ink: "#f7f8f8"
  ink-muted: "#d0d6e0"
  ink-subtle: "#8a8f98"
  ink-tertiary: "#62666d"
  canvas: "#010102"
  surface-1: "#0f1011"
  surface-2: "#141516"
  surface-3: "#18191a"
  surface-4: "#191a1b"
  hairline: "#23252a"
  hairline-strong: "#34343a"
  hairline-tertiary: "#3e3e44"
  inverse-canvas: "#ffffff"
  inverse-surface-1: "#f5f6f6"
  inverse-surface-2: "#f6f7f7"
  inverse-ink: "#000000"
  brand-secure: "#7a7fad"
  semantic-success: "#27a644"
  semantic-overlay: "#000000"

typography:
  display-xl:
    fontFamily: Linear Display
    fontSize: 80px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -3.0px
  display-lg:
    fontFamily: Linear Display
    fontSize: 56px
    fontWeight: 600
    lineHeight: 1.10
    letterSpacing: -1.8px
  display-md:
    fontFamily: Linear Display
    fontSize: 40px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -1.0px
  headline:
    fontFamily: Linear Display
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: -0.6px
  card-title:
    fontFamily: Linear Display
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: -0.4px
  subhead:
    fontFamily: Linear Display
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.40
    letterSpacing: -0.2px
  body-lg:
    fontFamily: Linear Text
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: -0.1px
  body:
    fontFamily: Linear Text
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: -0.05px
  body-sm:
    fontFamily: Linear Text
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0
  caption:
    fontFamily: Linear Text
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.40
    letterSpacing: 0
  button:
    fontFamily: Linear Text
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.20
    letterSpacing: 0
  eyebrow:
    fontFamily: Linear Text
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.30
    letterSpacing: 0.4px
  mono:
    fontFamily: Linear Mono
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  xxl: 24px
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
    padding: 8px 14px
  button-primary-pressed:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 8px 14px
  button-tertiary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 8px 14px
  button-inverse:
    backgroundColor: "{colors.inverse-canvas}"
    textColor: "{colors.inverse-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 8px 14px
  pricing-card:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  pricing-card-featured:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  feature-card:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  product-screenshot-card:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 24px
  testimonial-card:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  customer-logo-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subtle}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: 16px
  text-input:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  text-input-focused:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  pricing-tab-default:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subtle}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 6px 14px
  pricing-tab-selected:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 6px 14px
  cta-banner:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    typography: "{typography.headline}"
    rounded: "{rounded.lg}"
    padding: 48px
  changelog-row:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.xs}"
    padding: 24px 0
  status-badge:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink-muted}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 2px 8px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.xs}"
    height: 56px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subtle}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: 64px 32px
---

> 🌐 本文档由 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) 翻译,英文原版见原项目。
>
> ⚠️ 本文件超过 10000 字符,仅汉化核心章节(概览 / 色彩 / 字体 / 禁忌清单);布局、组件、响应式等其余章节保留英文原版,请对照原项目阅读。

## 概览(Overview)

Linear 的营销画布是本合集中最深的暗色表面——`{colors.canvas}` 为 #010102,几乎是带一丝蓝调的纯黑。其上是四级表面阶梯(`{colors.surface-1}` 到 `{colors.surface-4}`),承载卡片、面板和浮起磁贴,发丝线边框从 `{colors.hairline}`(#23252a)延伸到 `{colors.hairline-strong}` 和 `{colors.hairline-tertiary}`。浅灰文字(`{colors.ink}` #f7f8f8)承担正文与标题。

唯一的彩色强调是 **Linear 薰衣草蓝** `{colors.primary}`(#5e6ad2)——用于品牌标识、焦点环和主 CTA 按钮。更亮的悬停态(`{colors.primary-hover}` #828fff)与焦点着色变体(`{colors.primary-focus}` #5e69d1)延伸同一色相。Linear 在营销画布上回避高饱和的绿、橙、红等——唯一的语义色是 `{colors.semantic-success}`(#27a644),用于状态药丸和罕见的成功指示。

展示字体使用 Linear 自研无衬线(回退 `SF Pro Display`),字重 500–700,负字距从 80px 处的 -3.0px 递减到正文的 0。正文家族是 Linear 的文本裁切版,Linear Mono 保留给产品截图中的代码片段。

页面节奏是**高密度产品截图**——Linear 的营销以高保真的产品 UI 截图(issue 列表、项目视图、仪表盘)领衔,装在带 `{rounded.xl}` 16px 圆角的 `{colors.surface-1}` 面板中。页面外壳刻意极简,让应用截图扛起主角。

**关键特征:**
- **暗色画布营销系统**——`{colors.canvas}`(#010102)是本合集中最深的暗色。
- **薰衣草蓝品牌强调**(`{colors.primary}` #5e6ad2)——克制地用于品牌标识、焦点态和主 CTA。
- 四级表面阶梯(canvas → surface-1 → surface-2 → surface-3 → surface-4)在不依赖阴影的情况下承载层级。
- 展示字距激进地为负(80px 处 -3.0px);正文保持在 -0.05px。
- 卡片使用 `{rounded.lg}` 12px 圆角加 1px 发丝线边框——绝不用药丸形,很少用 16px。
- **产品 UI 截图**主导页面。营销外壳只是应用的暗色画框。
- 没有第二种彩色。没有氛围渐变。没有聚光卡片。

## 色彩(Colors)

> 来源页面:linear.app(首页)、/intake、/pricing、/contact/sales、/build。

### 品牌与强调色
- **薰衣草蓝**({colors.primary}):Linear 的标志性强调色——主 CTA、品牌标识、链接强调。
- **薰衣草悬停态**({colors.primary-hover}):更亮的薰衣草(#828fff)——主 CTA 的悬停状态。
- **薰衣草焦点态**({colors.primary-focus}):焦点环色调(#5e69d1)——聚焦的输入框与按钮。
- **品牌安全色**({colors.brand-secure}):弱化的薰衣草灰(#7a7fad)——用于"Linear Security"相关表面。

### 表面
- **画布**({colors.canvas}):默认页面背景——#010102,近纯黑带一丝蓝调。
- **表面 1**({colors.surface-1):比画布高一级——特性卡片、定价卡片、产品截图面板。
- **表面 2**({colors.surface-2}):高两级——精选定价卡、悬停卡片。
- **表面 3**({colors.surface-3}):高三级——line-tertiary 背景、子导航。
- **表面 4**({colors.surface-4}):高四级——bg-level-3,最深的浮起表面。
- **发丝线**({colors.hairline}):卡片与分隔线的 1px 边框。
- **加重发丝线**({colors.hairline-strong}):更强的 1px 边框——输入框焦点环。
- **三级发丝线**({colors.hairline-tertiary):嵌套表面的三级边框。
- **反转画布**({colors.inverse-canvas}):纯白——少数区块开场中反转药丸 CTA 的表面。
- **反转表面 1**({colors.inverse-surface-1}):比反转画布高一级。
- **反转表面 2**({colors.inverse-surface-2}):比反转画布高两级。

### 文字
- **墨色**({colors.ink}):所有标题与强调正文——浅灰 #f7f8f8。
- **弱化墨色**({colors.ink-muted}):#d0d6e0 的次要文字——Hero 面板上的元信息。
- **更弱墨色**({colors.ink-subtle}):#8a8f98 的三级文字——未选中的定价页签、页脚栏目。
- **三级墨色**({colors.ink-tertiary}):#62666d 的四级文字——禁用态、脚注。

### 语义色
- **成功绿**({colors.semantic-success}):状态药丸、成功指示。营销面上唯一的语义色。
- **遮罩**({colors.semantic-overlay}):弹窗用的纯黑遮罩层。

## 字体(Typography)

### 字体族

- **Linear Display** — Linear 自研展示无衬线;回退 `SF Pro Display, -apple-system, system-ui, Segoe UI, Roboto`。承担 display-xl 至 subhead。
- **Linear Text** — Linear 自研正文无衬线(为正文尺寸微调的另一裁切版);回退栈相同。承担正文尺寸、按钮标签、说明文字。
- **Linear Mono** — Linear 自研等宽;回退 `ui-monospace, SF Mono, Menlo`。用于产品截图中的代码片段和状态 / ID 令牌。

营销面把 Display 与 Text 视为同一连续声线;字体族的切换是无声的。

### 层级(Hierarchy)

| Token | Size | Weight | Line Height | Letter Spacing | 用途 |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 80px | 600 | 1.05 | -3.0px | 最大 Hero 标题 |
| `{typography.display-lg}` | 56px | 600 | 1.10 | -1.8px | 区块开场标题 |
| `{typography.display-md}` | 40px | 600 | 1.15 | -1.0px | 子区块标题 |
| `{typography.headline}` | 28px | 600 | 1.20 | -0.6px | 定价档位标题、CTA 横幅标题 |
| `{typography.card-title}` | 22px | 500 | 1.25 | -0.4px | 特性卡片标题 |
| `{typography.subhead}` | 20px | 400 | 1.40 | -0.2px | 导语正文、介绍段落 |
| `{typography.body-lg}` | 18px | 400 | 1.50 | -0.1px | Hero 副标题、导语段落 |
| `{typography.body}` | 16px | 400 | 1.50 | -0.05px | 默认正文 |
| `{typography.body-sm}` | 14px | 400 | 1.50 | 0 | 卡片正文、页脚栏目 |
| `{typography.caption}` | 12px | 400 | 1.40 | 0 | 说明、元信息、状态 |
| `{typography.button}` | 14px | 500 | 1.20 | 0 | 所有按钮标签 |
| `{typography.eyebrow}` | 13px | 500 | 1.30 | 0.4px | 区块眉题(轻微正字距) |
| `{typography.mono}` | 13px | 400 | 1.50 | 0 | 产品截图代码用 Linear Mono |

### 原则(Principles)

- **展示字号激进负字距**(80px 处 -3.0px ≈ 字号的 4%)。
- **从展示到正文一个声线。** display-xl 用 600 → 正文用 400——同一家族,更窄的字重区间。
- **眉题使用正字距**(+0.4px)——与负字距的展示标题形成对比,把眉题标记为"分类信息"。
- **等宽只出现在代码语境。** Linear Mono 只活在产品截图里——不上营销外壳。

### 字体替代说明(Note on Font Substitutes)

Linear 的自研字体不公开分发;文档化的回退 `SF Pro Display, -apple-system, system-ui` 是 macOS 上的推荐替代。跨平台实现时,**Inter**(字重 500 / 600 / 700)是最接近的免费替代。**Geist Sans** 也可行。等宽方面,**JetBrains Mono** 或 **Geist Mono**(字重 400)能很好近似 Linear Mono。

## Layout

### Spacing System

- **Base unit**: 4px.
- **Tokens (front matter)**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 96px.
- Card interior padding: `{spacing.lg}` 24px on feature/pricing cards; `{spacing.xl}` 32px on testimonial cards; `{spacing.xxl}` 48px on CTA banners.
- Pill button padding: 8px vertical · 14px horizontal — Linear's compact button spec.
- Form input padding: 8px vertical · 12px horizontal.

### Grid & Container

- Max content width sits around 1280px.
- Card grids are 3-up at desktop, 2-up at tablet, 1-up at mobile.
- Pricing tier grid is 3-up; comparison strip below shows checkmarks per tier.
- Product screenshot panels span full content width — they're the protagonist.

### Whitespace Philosophy

The dark canvas IS the whitespace. Sections separate by lift onto surface-1 panels, not by gaps in white. Within a panel, generous `{spacing.lg}` 24px gaps between content blocks; `{spacing.section}` 96px between sections.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 (flat) | No shadow, no border | Default for body type, hero text, footer |
| 1 (charcoal lift) | `{colors.surface-1}` background on canvas, 1px `{colors.hairline}` | Default cards, product panels |
| 2 (surface-2 lift) | `{colors.surface-2}` background, 1px `{colors.hairline-strong}` | Featured pricing card, hovered cards |
| 3 (surface-3 lift) | `{colors.surface-3}` background | Sub-nav, dropdown menus |
| 4 (focus ring) | 2px `{colors.primary-focus}` outline at 50% opacity | Focused input, focused button |

Linear's depth is carried by surface ladder + hairline borders. The brand resists drop shadows on dark almost entirely.

### Decorative Depth

- **Product UI screenshots** dominate as decorative depth.
- **No atmospheric gradients, no spotlight cards.**
- **Subtle white edge highlight** on the top edge of lifted panels — gives the dark surface a faint "pixel rendered" feel.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | Small chips, status badges |
| `{rounded.sm}` | 6px | Inline tags |
| `{rounded.md}` | 8px | All buttons, form inputs |
| `{rounded.lg}` | 12px | Pricing cards, feature cards, testimonial cards |
| `{rounded.xl}` | 16px | Product screenshot panels |
| `{rounded.xxl}` | 24px | Oversized CTA banners (rare) |
| `{rounded.pill}` | 9999px | Pricing tab toggles, status pills |
| `{rounded.full}` | 9999px | Avatar circles |

### Photography & Illustration Geometry

- Product UI screenshots dominate; they sit in `{rounded.xl}` 16px tiles with `{spacing.lg}` 24px outer padding.
- Customer logo tiles render at small sizes (~24px logo height) on `{colors.canvas}` with no border.
- Avatar circles in testimonial cards use `{rounded.full}` at 32–40px sizes.

## Components

### Buttons

**`button-primary`** — Lavender CTA. The default primary CTA across all pages.
- Background `{colors.primary}`, text `{colors.on-primary}`, type `{typography.button}`, padding 8px 14px, rounded `{rounded.md}`.
- Pressed state lives in `button-primary-pressed` (background shifts to `{colors.primary-focus}`).
- Hover state lives in `button-primary-hover` (background shifts to `{colors.primary-hover}` lighter lavender).

**`button-secondary`** — Charcoal button. Used for secondary CTAs ("Sign in", "Read changelog").
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.button}`, padding 8px 14px, rounded `{rounded.md}`. 1px `{colors.hairline}` border.

**`button-tertiary`** — Plain text button.
- Background `{colors.canvas}`, text `{colors.ink}`, type `{typography.button}`, rounded `{rounded.md}`, padding 8px 14px.

**`button-inverse`** — White-on-dark inverse CTA.
- Background `{colors.inverse-canvas}`, text `{colors.inverse-ink}`, type `{typography.button}`, rounded `{rounded.md}`, padding 8px 14px.

### Pricing Tabs

**`pricing-tab-default`** + **`pricing-tab-selected`** — Pill-toggle on `/pricing`.
- Default: `{colors.canvas}` background, `{colors.ink-subtle}` text, rounded `{rounded.pill}`, padding 6px 14px.
- Selected: `{colors.surface-2}` background, `{colors.ink}` text — selected = surface lift.

### Cards & Containers

**`pricing-card`** — Each tier on `/pricing`.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.lg}`, padding 24px. 1px `{colors.hairline}` border.

**`pricing-card-featured`** — Recommended tier — surface lift to surface-2.
- Background `{colors.surface-2}`, otherwise identical structure.

**`feature-card`** — Generic feature highlight tile.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.lg}`, padding 24px.

**`product-screenshot-card`** — The dominant card type — frames a high-fidelity Linear app UI screenshot.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.xl}`, padding 24px.

**`testimonial-card`** — Customer quote with avatar + name + role.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.body-lg}`, rounded `{rounded.lg}`, padding 32px.

**`customer-logo-tile`** — Small tile in the customer marquee.
- Background `{colors.canvas}`, text `{colors.ink-subtle}`, type `{typography.caption}`, rounded `{rounded.xs}`, padding 16px.

**`cta-banner`** — Closing CTA panel near page bottom.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.headline}`, rounded `{rounded.lg}`, padding 48px.

### Inputs & Forms

**`text-input`** + **`text-input-focused`** — Form fields on `/contact/sales` and signup overlays.
- Background `{colors.surface-1}`, text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.md}`, padding 8px 12px.
- Focused state retains the same surface; the focus ring is a 2px `{colors.primary-focus}` outline at 50% opacity.

### Status & Build Page

**`changelog-row`** — Each row in `/build` (changelog page) listing version, date, and changes.
- Background `{colors.canvas}`, text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.xs}`, padding 24px 0. 1px `{colors.hairline}` bottom rule.

**`status-badge`** — Small status pill.
- Background `{colors.surface-2}`, text `{colors.ink-muted}`, type `{typography.caption}`, rounded `{rounded.pill}`, padding 2px 8px.

### Navigation

**`top-nav`** — Sticky dark bar with the Linear wordmark left, primary nav links centered, and a `button-secondary` ("Sign in") + `button-primary` ("Get started") pair right.
- Background `{colors.canvas}`, text `{colors.ink}`, type `{typography.body-sm}`, height 56px.

### Footer

**`footer`** — Dense link grid on `{colors.canvas}` with the Linear wordmark left.
- Background `{colors.canvas}`, text `{colors.ink-subtle}`, type `{typography.caption}`, padding 64px 32px.

## 应做与禁忌(Do's and Don'ts)

### 应做(Do)

- 把 `{colors.canvas}`(#010102)作为系统的锚定表面——那丝蓝调是刻意的。
- `{colors.primary}` 薰衣草蓝只用于:品牌标识、主 CTA、焦点环、链接强调。
- 用四级表面阶梯表达层级。避免跳级。
- 展示字重 600 配正文字重 400——Linear 抗拒 700+ 的展示字重。
- 展示字号大胆应用负字距。
- 让产品 UI 截图成为每个区块的主角。
- CTA 一律 `{rounded.md}` 8px 圆角。

### 禁忌(Don't)

- 不要发布浅色模式的营销页。
- 不要把薰衣草蓝用作区块背景或卡片填充。
- 不要引入第二种彩色强调(营销用的橙、粉、绿)。
- 不要添加氛围渐变或聚光卡片。
- 不要把 CTA 做成药丸形。
- 不要用 `#000000` 真黑当画布。
- 不要在产品截图模型图中混用多种亮色强调。

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Desktop-XL | 1440px | Default desktop layout |
| Desktop | 1280px | Card grid 3-up maintained |
| Tablet | 1024px | Card grid 3-up → 2-up |
| Mobile-Lg | 768px | Pricing comparison becomes accordion; nav hamburger |
| Mobile | 480px | Single-column; display-xl scales 80px → ~36px |

### Touch Targets

- CTAs hold ≥40px tap height across viewports.
- Pricing tab pills hold ≥36px tap height; touch viewports grow to ≥44px.
- Form inputs hold ≥44px tap target on touch.

### Collapsing Strategy

- **Top nav**: links collapse to hamburger below 768px.
- **Card grids**: 3-up → 2-up at 1024px → 1-up below 768px.
- **Pricing comparison**: per-tier accordion below 768px.
- **Display type**: `{typography.display-xl}` 80px scales toward `{typography.display-md}` 40px on mobile.

### Image Behavior

- Product UI screenshots maintain aspect ratio and never crop.
- Customer logos in the marquee may collapse from 6-up to 3-up below 768px.

## Iteration Guide

1. Focus on ONE component at a time and reference it by its `components:` token name.
2. When introducing a section, decide first which surface lift it lives on.
3. Default body to `{typography.body}` at weight 400.
4. Run `npx @google/design.md lint DESIGN.md` after edits.
5. Add new variants as separate component entries.
6. Treat lavender as scarce: brand mark, primary CTA, focus, link emphasis.
7. Lead every section with a product UI screenshot.

## Known Gaps

- The four-step surface ladder values are extracted directly from Linear's `--color-bg-level-3`, `--color-line-tint`, etc. CSS variables; they are Linear's canonical surface spec.
- Form-field error and validation styling is not visible on the inspected pages.
- Light mode is not documented because the marketing site does not ship a light theme.
- Linear's actual product UI uses a richer color-tag palette (red, orange, yellow, green, blue, purple) for issue priorities and project labels — those colors live in the in-product surfaces shown in mockups.
- The custom display, text, and mono families are proprietary; an open-source substitute is acceptable.
