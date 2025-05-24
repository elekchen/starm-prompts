# 📖 Bento-Grids 对比着陆页使用指南

> [English](./usage-guide.en.md) | **中文**

## 🎯 概述

这是一个专门用于创建双对象对比的 Bento-Grids 风格着陆页的通用 Prompt 模板。它可以帮助您快速生成专业、美观且信息丰富的对比页面。

## ✨ 特性

- 🎨 **现代化设计**：采用流行的 Bento-Grids 布局
- 🔄 **高度通用**：适用于任何两个对象的对比
- 🌐 **中英双语**：完整支持中英文内容
- 📱 **响应式设计**：优化移动端体验
- 🎙️ **播客集成**：可选的播客/音频内容支持
- ♿ **可访问性**：遵循 WCAG 可访问性标准

## 🚀 快速开始

### 步骤 1：准备对比资料

在使用此 Prompt 之前，确保您有：

- ✅ **完整的对比文档**：包含两个对象的详细信息
- ✅ **明确的对比维度**：如功能、性能、价格等
- ✅ **可靠的数据来源**：确保信息准确性
- ✅ **[可选] 播客链接**：相关的音频解读内容

### 步骤 2：替换模板参数

将以下占位符替换为您的实际内容：

```markdown
{对比文档} → 您的具体对比资料
{对象 A 名称} → 第一个对比对象
{对象 B 名称} → 第二个对比对象
{播客 URL} → 相关播客链接（可选）
```

### 步骤 3：选择AI工具

推荐使用以下 AI 工具：

- 🥇 **Gemini 2.5 Pro + Canvas**：最佳选择，支持实时预览
- 🥈 **Claude AI**：优秀的设计理解能力
- 🥉 **ChatGPT-4**：良好的代码生成能力

## 🌟 实际案例展示

### 真实范例：Google I/O 2025 vs Microsoft Build 2025

这是使用本 Prompt 模板创建的真实案例，展示了完整的 Bento-Grids 对比页面效果：

- **📊 实际生成页面**：[查看完整案例](https://gemini.google.com/share/2e2cd57a973e)
- **🎥 制作过程视频**：[X/Twitter 演示视频](https://x.com/elekchen/status/1925915733680144669)

**案例特点：**
- ✨ 完整的 Bento-Grids 布局设计
- 📱 响应式移动端适配
- 🎨 Google 和 Microsoft 品牌色彩融合
- 📊 清晰的数据对比可视化
- 🎙️ 集成播客内容入口

**学习价值：**
- 了解真实的设计输出效果
- 参考具体的内容组织方式
- 学习品牌色彩的协调运用
- 掌握信息层级的构建方法

> 💡 **提示**：建议在使用本模板前先查看这个实际案例，有助于更好地理解 Prompt 的应用效果。

## 📋 使用示例

### 示例 1：科技产品对比

```markdown
{对比文档}: iPhone 15 Pro vs Samsung Galaxy S24 Ultra 详细评测报告
{对象 A 名称}: Apple iPhone 15 Pro
{对象 B 名称}: Samsung Galaxy S24 Ultra
{播客 URL}: https://example.com/tech-podcast-episode-123
```

**适用场景：**
- 📱 智能手机对比
- 💻 笔记本电脑评测
- 🎮 游戏设备对比

### 示例 2：商业服务对比

```markdown
{对比文档}: Netflix vs Disney+ 流媒体服务深度分析
{对象 A 名称}: Netflix
{对象 B 名称}: Disney+
{播客 URL}: (留空，无播客内容)
```

**适用场景：**
- 🎬 流媒体平台对比
- 🏢 SaaS 服务评估
- 💳 金融产品对比

### 示例 3：AI 模型对比

```markdown
{对比文档}: GPT-4 vs Claude-3.5 性能基准测试报告
{对象 A 名称}: OpenAI GPT-4
{对象 B 名称}: Anthropic Claude-3.5
{播客 URL}: https://example.com/ai-analysis-podcast
```

**适用场景：**
- 🤖 AI 模型评估
- 🛠️ 开发工具对比
- 📊 数据分析平台比较

## 🎨 设计定制指南

### 颜色方案

根据对比对象选择合适的颜色方案：

```css
/* 品牌色彩示例 */
:root {
  /* Apple vs Samsung */
  --brand-a: #007AFF;  /* Apple Blue */
  --brand-b: #1428A0;  /* Samsung Blue */
  
  /* Netflix vs Disney+ */
  --brand-a: #E50914;  /* Netflix Red */
  --brand-b: #113CCF;  /* Disney+ Blue */
  
  /* 中性色彩 */
  --background: #F8F9FA;
  --text-primary: #212529;
  --text-secondary: #6C757D;
}
```

### 字体选择

推荐的字体组合：

- **现代简洁**: Inter + SF Pro
- **中文友好**: 思源黑体 + PingFang SC
- **多语言**: Noto Sans + Roboto

### 布局调整

根据内容长度调整网格布局：

- **内容较少**: 2×2 主网格
- **标准内容**: 3×3 主网格  
- **内容丰富**: 4×4 或更大

## ⚙️ 高级功能

### 数据可视化

集成图表类型：

- 📊 **对比柱状图**
- 📈 **趋势线图**
- 🥧 **占比饼图**
- 🎯 **雷达图**

### 交互元素

增强用户体验：

- 🖱️ **悬停效果**
- 📱 **触摸友好**
- 🔄 **平滑动画**
- 📖 **展开/折叠**

### SEO 优化

结构化数据建议：

```html
<!-- Schema.org 结构化数据 -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ComparisonTable",
  "name": "{对象A} vs {对象B} 对比",
  "description": "详细对比分析..."
}
</script>
```

## 🔧 故障排除

### 常见问题

**Q: 生成的页面在移动端显示异常？**

A: 检查 CSS 媒体查询设置，确保使用了响应式断点。

**Q: 颜色对比度不够，影响可读性？**

A: 使用在线对比度检查工具，确保达到 WCAG AA 标准（4.5:1）。

**Q: 播客按钮没有正确显示？**

A: 检查 z-index 设置和 CSS 定位属性。

### 性能优化

- 🖼️ **图片优化**：使用 WebP 格式，启用懒加载
- 📦 **资源压缩**：压缩 CSS/JS 文件
- 🚀 **CDN 加速**：使用内容分发网络

## 📚 相关资源

### 设计灵感

- [Bento Grids 设计模式](https://bentogrids.com)
- [Material Design Guidelines](https://m3.material.io/)
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)

### 技术文档

- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [Responsive Design Patterns](https://responsivedesign.is/patterns/)

## 🤝 贡献与反馈

如果您有改进建议或发现了问题，欢迎：

- 📧 发送邮件反馈
- 🐛 报告使用问题  
- 💡 分享创意想法
- 🌟 展示您的作品

---

## 🏷️ 版本信息

- **当前版本**: v1.0
- **最后更新**: 2024年11月
- **兼容性**: Gemini 2.5 Pro, Claude AI, ChatGPT-4
- **许可证**: MIT

---

*祝您设计愉快！* 🎨✨ 