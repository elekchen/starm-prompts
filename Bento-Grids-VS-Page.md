# **🔖 Bento-Grids 对比着陆页 Prompt Template**
## **Bento-Grids Comparison Landing Page Prompt Template**

## **📝 提示正文 / Prompt Content**

### **❶ 背景 / Background**

请基于以下对比资料设计一个现代化的 Bento-Grids 风格着陆页：
*Please design a modern Bento-Grids style landing page based on the following comparison materials:*

**{对比文档 / Comparison Document}**

**{对象 A 名称 / Object A Name}**

**{对象 B 名称 / Object B Name}**

**[可选] 播客或音频解读链接：**
**[Optional] Podcast or audio commentary link:**

**{播客 URL / Podcast URL}**

### **❂ 目标 / Objective**

创建一个专业的 **Bento Grids** 风格的 **Landing Page**，用于展示两个对象的深度对比分析。
*Create a professional **Bento Grids** style **Landing Page** for showcasing in-depth comparison analysis between two objects.*

### **❸ 布局与内容要求 / Layout & Content Requirements**

1. **Hero 区（整行网格单元）/ Hero Section (Full-width Grid Unit)**
    - 主标题格式："{对象 A} × {对象 B}" / Title format: "{Object A} × {Object B}"
    - 一句话价值陈述（取自执行摘要或核心观点）/ One-line value proposition (from executive summary or key insights)
    - 背景动画：融合两个对象的视觉元素（颜色、形状、品牌元素等）/ Background animation: Blend visual elements from both objects (colors, shapes, brand elements, etc.)

2. **关键指标网格（2 × 3 或灵活布局）/ Key Metrics Grid (2 × 3 or flexible layout)**
    - 每个卡片包含：主题图标、对象 A 数据 vs. 对象 B 数据、简短评价（12字以内）
    - *Each card contains: Topic icon, Object A data vs. Object B data, brief assessment (within 12 characters)*
    - 使用对象 A 和对象 B 的品牌色彩作为边框区分 / Use brand colors of Object A and B for border differentiation

3. **深度分析区（多行 Bento，1/3–2/3 宽度变化）/ Deep Analysis Section (Multi-row Bento, 1/3–2/3 width variation)**
    - 根据对比主题创建子区块（如：功能特性、性能表现、用户体验、价格策略等）
    - *Create sub-blocks based on comparison themes (e.g., features, performance, user experience, pricing strategy, etc.)*
    - 插入信息图或图表，标注数据来源 / Insert infographics or charts with data source annotations

4. **洞见横条（水平滚动胶囊）/ Insights Bar (Horizontal Scrolling Pills)**
    - 3-5 个颜色胶囊显示关键洞见要点 / 3-5 colored pills showing key insight points

5. **来源与补充内容区 / Sources & Additional Content Section**
    - 列出所有引用资料标题 + 标识符，便于回溯 / List all referenced materials with identifiers for traceability
    - **[如有播客] 播客播放器 / 链接卡片** / **[If applicable] Podcast player / link card**
    - 显示节目信息与"立即收听"按钮 / Show program info with "Listen Now" button

6. **CTA 页脚 / CTA Footer**
    - "下载完整报告" + 社交分享按钮 / "Download Full Report" + social sharing buttons

7. **[如有播客] 悬浮播客按钮 / [If applicable] Floating Podcast Button**
    - 固定在右下角（60px × 60px 圆形按钮）/ Fixed at bottom-right (60px × 60px circular button)
    - 使用播客图标，点击打开播客链接 / Use podcast icon, opens podcast link on click

### **❹ 视觉与交互规范 / Visual & Interaction Guidelines**

- **字体 / Typography**：现代无衬线字体（如 Inter、SF Pro、思源黑体等）/ Modern sans-serif fonts (e.g., Inter, SF Pro, Source Han Sans, etc.)
- **配色 / Color Scheme**：基于两个对象的品牌色彩，保持对比度和可读性 / Based on brand colors of both objects, maintain contrast and readability
- **间距 / Spacing**：基线 4px；卡片圆角 12-16px；使用 Material Design 阴影系统 / 4px baseline; 12-16px card radius; use Material Design shadow system
- **动效 / Animations**：元素进入视口时的渐入动画（200-300ms）/ Fade-in animations when elements enter viewport (200-300ms)
- **图表 / Charts**：保持一致的配色方案；避免信息过载 / Maintain consistent color scheme; avoid information overload
- **可访问性 / Accessibility**：颜色对比度 ≥ WCAG AA；为图标/图表添加替代文本 / Color contrast ≥ WCAG AA; add alt text for icons/charts

### **❺ 交付物 / Deliverables**

- **1. 高保真设计稿 / High-fidelity Mockup**（Bento 网格布局）/ (Bento grid layout)
- **2. 页面文案 / Page Copy**（完全基于提供的对比文档，不得虚构）/ (Completely based on provided comparison documents, no fabrication)
- **3. HTML + CSS 代码片段 / HTML + CSS Code Snippets**
    - 主要结构、关键网格、交互元素的完整代码 / Complete code for main structure, key grids, interactive elements
    - 包含必要的注释和说明 / Include necessary comments and explanations

**悬浮按钮示例样式 / Floating Button Example Style:**

```css
.podcast-float {
  position: fixed; bottom: 24px; right: 24px;
  width: 60px; height: 60px; border-radius: 50%;
  background: var(--accent-color);   /* 根据项目调整 / Adjust based on project */
  display: flex; align-items: center; justify-content: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15); cursor: pointer;
  transition: transform 0.2s ease-out;
  z-index: 1000;
}
.podcast-float:hover { transform: scale(1.08); }
```

### **❻ 约束与指导原则 / Constraints & Guidelines**

- ✅ 仅使用提供的 **{对比文档}** 中的信息；缺失数据标注 "（资料未提及）" / Only use information from provided **{comparison document}**; mark missing data as "(Not mentioned in materials)"
- ✅ 所有数据点标注来源标识符（如：[Doc-A-Section-3]、[Chart-B-2]）/ Mark all data points with source identifiers (e.g., [Doc-A-Section-3], [Chart-B-2])
- ✅ 保持中立立场，避免偏向性表述 / Maintain neutral stance, avoid biased statements
- ✅ 确保内容的事实准确性和可验证性 / Ensure factual accuracy and verifiability of content
- ✅ 优化移动端体验，确保响应式设计 / Optimize for mobile experience, ensure responsive design

### **❼ 自定义参数 / Custom Parameters**

使用此模板时，请替换以下占位符：
*When using this template, please replace the following placeholders:*

- `{对比文档 / Comparison Document}`: 您的具体对比资料 / Your specific comparison materials
- `{对象 A 名称 / Object A Name}`: 第一个对比对象 / First comparison object  
- `{对象 B 名称 / Object B Name}`: 第二个对比对象 / Second comparison object
- `{播客 URL / Podcast URL}`: 相关播客链接（可选）/ Related podcast link (optional)

**示例 / Example:**
- 对象：Apple iPhone 15 Pro × Samsung Galaxy S24 Ultra
- 对象：Tesla Model 3 × BMW i4
- 对象：ChatGPT × Claude AI
- 对象：Netflix × Disney+