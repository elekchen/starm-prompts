# 📖 Bento-Grids 对比着陆页使用指南
## Bento-Grids Comparison Landing Page Usage Guide

## 🎯 概述 / Overview

这是一个专门用于创建双对象对比的 Bento-Grids 风格着陆页的通用 Prompt 模板。它可以帮助您快速生成专业、美观且信息丰富的对比页面。

*This is a universal Prompt template specifically designed for creating Bento-Grids style landing pages for dual-object comparisons. It helps you quickly generate professional, beautiful, and informative comparison pages.*

## ✨ 特性 / Features

- 🎨 **现代化设计**：采用流行的 Bento-Grids 布局 / **Modern Design**: Uses popular Bento-Grids layout
- 🔄 **高度通用**：适用于任何两个对象的对比 / **Highly Universal**: Suitable for comparing any two objects
- 🌐 **中英双语**：完整支持中英文内容 / **Bilingual**: Full support for both Chinese and English content
- 📱 **响应式设计**：优化移动端体验 / **Responsive Design**: Optimized for mobile experience
- 🎙️ **播客集成**：可选的播客/音频内容支持 / **Podcast Integration**: Optional podcast/audio content support
- ♿ **可访问性**：遵循 WCAG 可访问性标准 / **Accessibility**: Follows WCAG accessibility standards

## 🚀 快速开始 / Quick Start

### 步骤 1：准备对比资料 / Step 1: Prepare Comparison Materials

在使用此 Prompt 之前，确保您有：
*Before using this Prompt, make sure you have:*

- ✅ **完整的对比文档**：包含两个对象的详细信息 / **Complete comparison document**: Contains detailed information about both objects
- ✅ **明确的对比维度**：如功能、性能、价格等 / **Clear comparison dimensions**: Such as features, performance, pricing, etc.
- ✅ **可靠的数据来源**：确保信息准确性 / **Reliable data sources**: Ensure information accuracy
- ✅ **[可选] 播客链接**：相关的音频解读内容 / **[Optional] Podcast link**: Related audio commentary content

### 步骤 2：替换模板参数 / Step 2: Replace Template Parameters

将以下占位符替换为您的实际内容：
*Replace the following placeholders with your actual content:*

```markdown
{对比文档 / Comparison Document} → 您的具体对比资料
{对象 A 名称 / Object A Name} → 第一个对比对象
{对象 B 名称 / Object B Name} → 第二个对比对象
{播客 URL / Podcast URL} → 相关播客链接（可选）
```

### 步骤 3：选择AI工具 / Step 3: Choose AI Tool

推荐使用以下 AI 工具：
*Recommended AI tools:*

- 🥇 **Gemini 2.5 Pro + Canvas**：最佳选择，支持实时预览 / **Best choice with real-time preview**
- 🥈 **Claude AI**：优秀的设计理解能力 / **Excellent design understanding**
- 🥉 **ChatGPT-4**：良好的代码生成能力 / **Good code generation capabilities**

## 📋 使用示例 / Usage Examples

### 示例 1：科技产品对比 / Example 1: Tech Product Comparison

```markdown
{对比文档}: iPhone 15 Pro vs Samsung Galaxy S24 Ultra 详细评测报告
{对象 A 名称}: Apple iPhone 15 Pro
{对象 B 名称}: Samsung Galaxy S24 Ultra
{播客 URL}: https://example.com/tech-podcast-episode-123
```

**适用场景 / Use Cases:**
- 📱 智能手机对比 / Smartphone comparisons
- 💻 笔记本电脑评测 / Laptop reviews
- 🎮 游戏设备对比 / Gaming device comparisons

### 示例 2：商业服务对比 / Example 2: Business Service Comparison

```markdown
{对比文档}: Netflix vs Disney+ 流媒体服务深度分析
{对象 A 名称}: Netflix
{对象 B 名称}: Disney+
{播客 URL}: (留空，无播客内容)
```

**适用场景 / Use Cases:**
- 🎬 流媒体平台对比 / Streaming platform comparisons
- 🏢 SaaS 服务评估 / SaaS service evaluations
- 💳 金融产品对比 / Financial product comparisons

### 示例 3：AI 模型对比 / Example 3: AI Model Comparison

```markdown
{对比文档}: GPT-4 vs Claude-3.5 性能基准测试报告
{对象 A 名称}: OpenAI GPT-4
{对象 B 名称}: Anthropic Claude-3.5
{播客 URL}: https://example.com/ai-analysis-podcast
```

**适用场景 / Use Cases:**
- 🤖 AI 模型评估 / AI model evaluations
- 🛠️ 开发工具对比 / Development tool comparisons
- 📊 数据分析平台比较 / Data analytics platform comparisons

## 🎨 设计定制指南 / Design Customization Guide

### 颜色方案 / Color Schemes

根据对比对象选择合适的颜色方案：
*Choose appropriate color schemes based on comparison objects:*

```css
/* 品牌色彩示例 / Brand Color Examples */
:root {
  /* Apple vs Samsung */
  --brand-a: #007AFF;  /* Apple Blue */
  --brand-b: #1428A0;  /* Samsung Blue */
  
  /* Netflix vs Disney+ */
  --brand-a: #E50914;  /* Netflix Red */
  --brand-b: #113CCF;  /* Disney+ Blue */
  
  /* 中性色彩 / Neutral Colors */
  --background: #F8F9FA;
  --text-primary: #212529;
  --text-secondary: #6C757D;
}
```

### 字体选择 / Font Selection

推荐的字体组合：
*Recommended font combinations:*

- **现代简洁 / Modern & Clean**: Inter + SF Pro
- **中文友好 / Chinese-friendly**: 思源黑体 + PingFang SC
- **多语言 / Multilingual**: Noto Sans + Roboto

### 布局调整 / Layout Adjustments

根据内容长度调整网格布局：
*Adjust grid layout based on content length:*

- **内容较少 / Less content**: 2×2 主网格 / 2×2 main grid
- **标准内容 / Standard content**: 3×3 主网格 / 3×3 main grid  
- **内容丰富 / Rich content**: 4×4 或更大 / 4×4 or larger

## ⚙️ 高级功能 / Advanced Features

### 数据可视化 / Data Visualization

集成图表类型：
*Integrated chart types:*

- 📊 **对比柱状图** / Comparison Bar Charts
- 📈 **趋势线图** / Trend Line Charts
- 🥧 **占比饼图** / Proportion Pie Charts
- 🎯 **雷达图** / Radar Charts

### 交互元素 / Interactive Elements

增强用户体验：
*Enhance user experience:*

- 🖱️ **悬停效果** / Hover Effects
- 📱 **触摸友好** / Touch-friendly
- 🔄 **平滑动画** / Smooth Animations
- 📖 **展开/折叠** / Expand/Collapse

### SEO 优化 / SEO Optimization

结构化数据建议：
*Structured data recommendations:*

```html
<!-- Schema.org 结构化数据 / Schema.org Structured Data -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ComparisonTable",
  "name": "{对象A} vs {对象B} 对比",
  "description": "详细对比分析..."
}
</script>
```

## 🔧 故障排除 / Troubleshooting

### 常见问题 / Common Issues

**Q: 生成的页面在移动端显示异常？**
**Q: Generated page displays abnormally on mobile?**

A: 检查 CSS 媒体查询设置，确保使用了响应式断点。
*A: Check CSS media query settings, ensure responsive breakpoints are used.*

**Q: 颜色对比度不够，影响可读性？**
**Q: Insufficient color contrast affecting readability?**

A: 使用在线对比度检查工具，确保达到 WCAG AA 标准（4.5:1）。
*A: Use online contrast checking tools, ensure WCAG AA standard (4.5:1) is met.*

**Q: 播客按钮没有正确显示？**
**Q: Podcast button not displaying correctly?**

A: 检查 z-index 设置和 CSS 定位属性。
*A: Check z-index settings and CSS positioning properties.*

### 性能优化 / Performance Optimization

- 🖼️ **图片优化**：使用 WebP 格式，启用懒加载 / **Image optimization**: Use WebP format, enable lazy loading
- 📦 **资源压缩**：压缩 CSS/JS 文件 / **Resource compression**: Compress CSS/JS files
- 🚀 **CDN 加速**：使用内容分发网络 / **CDN acceleration**: Use content delivery network

## 📚 相关资源 / Related Resources

### 设计灵感 / Design Inspiration

- [Bento Grids 设计模式](https://bentogrids.com) / [Bento Grids Design Patterns](https://bentogrids.com)
- [Material Design Guidelines](https://m3.material.io/)
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)

### 技术文档 / Technical Documentation

- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [Responsive Design Patterns](https://responsivedesign.is/patterns/)

## 🤝 贡献与反馈 / Contribution & Feedback

如果您有改进建议或发现了问题，欢迎：
*If you have improvement suggestions or found issues, feel free to:*

- 📧 发送邮件反馈 / Send email feedback
- 🐛 报告使用问题 / Report usage issues  
- 💡 分享创意想法 / Share creative ideas
- 🌟 展示您的作品 / Showcase your work

---

## 🏷️ 版本信息 / Version Info

- **当前版本 / Current Version**: v1.0
- **最后更新 / Last Updated**: 2024年11月
- **兼容性 / Compatibility**: Gemini 2.5 Pro, Claude AI, ChatGPT-4
- **许可证 / License**: MIT

---

*Happy designing! 祝您设计愉快！* 🎨✨ 