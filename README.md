# 🌞 Light Mode UI Stylesheet

Welcome to the **Light Mode UI Stylesheet** — a clean, modern CSS foundation for building visually appealing, accessible, and user-friendly web interfaces with light theme aesthetics.

This stylesheet provides a full suite of reusable UI components and utilities, perfect for modern web projects that require a consistent and elegant light mode look.

---

## 🚀 Key Features

* Elegant **light mode theming**  
*Responsive button variants**: primary, secondary, outline, ghost
*Form state styling**: success, error, disabled  
*Scroll-to-top** floating button
*Custom **scrollbar styling**
*Reusable **tooltips and badges**
*Smooth **CSS loader animation**  
*Stylish **sponsors, FAQ, and announcement** sections  
*Handy **utility classes** for padding, text alignment, and spacing

---

## 📁 Organized Styling Structure

The stylesheet is structured with modular sections for clarity and reusability:

| Section                     | Purpose |
|----------------------------|---------|
| `body.light-mode`          | Core color and background themes for light mode |
| `.btn`, `.btn-*`           | Button variants with transitions and effects |
| `input.success / error`    | Input field feedback styling |
| `.scroll-to-top`           | Sticky floating scroll-to-top button |
| `.tooltip`                 | Interactive tooltip design |
| `.badge`, `.badge-*`       | Label indicators with styles |
| `.loader`                  | CSS animated spinner loader |
| `.sponsors-grid`           | Responsive sponsor logos grid |
| `.announcement`            | Highlight box for news or alerts |
| `.faq-item`                | Collapsible FAQ blocks |

---

## 🎨 Required CSS Variables

Before using the stylesheet, ensure your global CSS (`:root`) includes these variables for colors and transitions:

```css
:root {
  --primary: #6200ea;
  --accent: #03dac6;
  --dark: #1e1e2f;
  --light: #ffffff;
  --card-gradient: linear-gradient(135deg, #667eea, #764ba2);
  --transition: all 0.3s ease;
  --shadow: 0 4px 6px rgba(0,0,0,0.1);
  --shadow-hover: 0 6px 12px rgba(0,0,0,0.15);
}
