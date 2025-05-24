# **🔖 Bento-Grids Comparison Landing Page Prompt Template**

> **English** | [中文](./prompt.md)

## **📝 Prompt Content**

### **❶ Background**

Please design a modern Bento-Grids style landing page based on the following comparison materials:

**{Comparison Document}**

**{Object A Name}**

**{Object B Name}**

**[Optional] Podcast or audio commentary link:**

**{Podcast URL}**

### **❷ Objective**

Create a professional **Bento Grids** style **Landing Page** for showcasing in-depth comparison analysis between two objects.

### **❸ Layout & Content Requirements**

1. **Hero Section (Full-width Grid Unit)**
    - Title format: "{Object A} × {Object B}"
    - One-line value proposition (from executive summary or key insights)
    - Background animation: Blend visual elements from both objects (colors, shapes, brand elements, etc.)

2. **Key Metrics Grid (2 × 3 or flexible layout)**
    - Each card contains: Topic icon, Object A data vs. Object B data, brief assessment (within 12 characters)
    - Use brand colors of Object A and B for border differentiation

3. **Deep Analysis Section (Multi-row Bento, 1/3–2/3 width variation)**
    - Create sub-blocks based on comparison themes (e.g., features, performance, user experience, pricing strategy, etc.)
    - Insert infographics or charts with data source annotations

4. **Insights Bar (Horizontal Scrolling Pills)**
    - 3-5 colored pills showing key insight points

5. **Sources & Additional Content Section**
    - List all referenced materials with identifiers for traceability
    - **[If applicable] Podcast player / link card**
    - Show program info with "Listen Now" button

6. **CTA Footer**
    - "Download Full Report" + social sharing buttons

7. **[If applicable] Floating Podcast Button**
    - Fixed at bottom-right (60px × 60px circular button)
    - Use podcast icon, opens podcast link on click

### **❹ Visual & Interaction Guidelines**

- **Typography**: Modern sans-serif fonts (e.g., Inter, SF Pro, Source Han Sans, etc.)
- **Color Scheme**: Based on brand colors of both objects, maintain contrast and readability
- **Spacing**: 4px baseline; 12-16px card radius; use Material Design shadow system
- **Animations**: Fade-in animations when elements enter viewport (200-300ms)
- **Charts**: Maintain consistent color scheme; avoid information overload
- **Accessibility**: Color contrast ≥ WCAG AA; add alt text for icons/charts

### **❺ Deliverables**

- **1. High-fidelity Mockup** (Bento grid layout)
- **2. Page Copy** (Completely based on provided comparison documents, no fabrication)
- **3. HTML + CSS Code Snippets**
    - Complete code for main structure, key grids, interactive elements
    - Include necessary comments and explanations

**Floating Button Example Style:**

```css
.podcast-float {
  position: fixed; bottom: 24px; right: 24px;
  width: 60px; height: 60px; border-radius: 50%;
  background: var(--accent-color);   /* Adjust based on project */
  display: flex; align-items: center; justify-content: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15); cursor: pointer;
  transition: transform 0.2s ease-out;
  z-index: 1000;
}
.podcast-float:hover { transform: scale(1.08); }
```

### **❻ Constraints & Guidelines**

- ✅ Only use information from provided **{Comparison Document}**; mark missing data as "(Not mentioned in materials)"
- ✅ Mark all data points with source identifiers (e.g., [Doc-A-Section-3], [Chart-B-2])
- ✅ Maintain neutral stance, avoid biased statements
- ✅ Ensure factual accuracy and verifiability of content
- ✅ Optimize for mobile experience, ensure responsive design

### **❼ Custom Parameters**

When using this template, please replace the following placeholders:

- `{Comparison Document}`: Your specific comparison materials
- `{Object A Name}`: First comparison object  
- `{Object B Name}`: Second comparison object
- `{Podcast URL}`: Related podcast link (optional)

**Examples:**
- Objects: Apple iPhone 15 Pro × Samsung Galaxy S24 Ultra
- Objects: Tesla Model 3 × BMW i4
- Objects: ChatGPT × Claude AI
- Objects: Netflix × Disney+ 