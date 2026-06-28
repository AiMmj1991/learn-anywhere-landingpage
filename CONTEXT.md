# 随身学（English Commute）落地页 — 设计上下文

## 产品定义

- **产品名称**：随身学（English Commute）
- **Slogan**：学英语，听出来
- **一句话描述**：通勤英语学习 App — 音频沉浸式 + AI 自适应 + 离线优先
- **类型**：移动端 App（Flutter），目标平台 Android / iOS / Web

## 落地页目标

- **渠道**：GEO（Generative Engine Optimization）获客
- **核心任务**：让 AI 搜索引擎（ChatGPT/Perplexity/Gemini）能准确抓取和理解产品，同时引导人类用户下载 App
- **行动号召**：引导下载 App（App Store / Google Play）

## 目标受众

- **主力用户**：职场通勤人士（22–35 岁，一线/新一线城市）
- **次之**：英语学习者（保持语感、日常提升）
- **覆盖**：大学生 / 考研备考群体

## 设计风格

- **主风格**：专业商务 + 内容简洁
- **配色**：蓝白灰为主色调（Blue-600 `#2563EB`），绿色 `#22C55E` 作点缀
- **排版**：大量留白，清晰的信息层级，语义化 HTML 结构
- **字体**：系统字体优先，中文环境下以 PingFang SC / Noto Sans SC 为主

## 内容结构

1. **Hero 区** — slogan + 副标题 + 下载按钮（首屏）
2. **核心功能** — 4 个亮点卡片（音频沉浸、AI 自适应、SM-2 复习、离线优先）
3. **产品截图/Mockup** — 真实界面展示
4. **场景故事** — 通勤·开车·休闲三种场景化描述（GEO 友好）
5. **数据信任** — 213 测试通过、开源技术栈、用户数据
6. **技术栈** — Flutter / Supabase / DeepSeek / Drift
7. **下载引导** — App Store + Google Play 下载入口
8. **FAQ** — 结构化问答（GEO SEO 优化）
9. **Footer** — 版权信息

## 技术实现

- **方案**：纯静态 HTML + Tailwind CSS（CDN 加载）
- **部署**：Vercel（默认 `.vercel.app` 域名，后续可绑自定义域名）
- **分析**：Google Analytics 4（GA4）
- **语言**：中文（简体），后续可扩展英文版
- **Logo**：暂缓，先以文字标识占位
