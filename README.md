# 随身学（English Commute）落地页

GEO 优化产品落地页，用于 AI 搜索引擎（ChatGPT/Perplexity/Gemini）抓取及用户下载引导。

## 技术栈

- 纯静态 HTML5 + Tailwind CSS（CDN）
- 语义化 HTML + JSON-LD 结构化数据（SoftwareApplication + FAQ Schema）
- Google Analytics 4 埋点（已预留，待配置）

## 文件结构

```
├── index.html        # 主落地页
├── llms.txt          # AI 名片（AI 爬虫第一读取文件）
├── llms-full.txt     # 完整产品文档（AI 深度投喂）
├── robots.txt        # 爬虫策略（允许 GPTBot/Claude-Web/Google-Extended/CCBot/PerplexityBot）
├── README.md         # 本文件
├── CONTEXT.md        # 设计上下文
└── vercel.json       # Vercel 部署配置
```

## 部署

### Vercel（推荐）

```bash
# 安装 Vercel CLI
npm install -g vercel

# 部署
vercel --prod
```

或直接将此文件夹拖拽到 [vercel.com](https://vercel.com) 导入。

### 本地预览

直接用浏览器打开 `index.html` 即可，无需构建步骤。

## 待办上线前

- [ ] 替换 `G-XXXXXXXXXX` 为真实的 GA4 测量 ID（注释中）
- [ ] 替换下载链接为真实的 App Store / Google Play 链接（当前为 `#` 占位）
- [ ] 添加产品 Logo
- [ ] 产品截图上线后替换手机 Mockup 占位区域
- [ ] 绑定自定义域名（可选）
