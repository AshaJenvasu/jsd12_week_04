# 📂 jsd12_week_04

This week focuses on accelerating front-end development using **Tailwind CSS** and mastering **Flexbox** layouts through comprehensive practical exercises.

---

## 📑 Topics Covered

### 1. Master Class: Flexbox Deep Dive 📦
Comprehensive practice of the Flexbox model to achieve precise layout control:
- **Direction & Wrapping**: Mastering `flex-direction` and `flex-wrap`.
- **Alignment**: Practical use of `justify-content`, `align-items`, and `align-content`.
- **Item Specifics**: Controlling individual items with `flex-grow`, `flex-shrink`, `flex-basis`, and `align-self`.
- **Reordering**: Utilizing the `order` property for visual hierarchy adjustments.

### 2. Modern Styling with Tailwind CSS 🌊
Transitioning from standard CSS to a Utility-First workflow:
- **Utility Classes**: Learning to style directly in HTML using Tailwind's predefined classes.
- **Configuration**: Understanding `tailwind.config.js` for custom themes and extensions.
- **Responsive Utilities**: Applying mobile-first prefixes (e.g., `md:`, `lg:`) to build adaptive designs faster.

---

## 📁 Repository Structure

### 🏗️ `/flexbox-ex-jsd-main`
- `01-10`: A step-by-step progression through Flexbox properties, ending with a functional **Flexbox Navbar** challenge.

### 💨 `/tailwind`
- `exercise-1.html` to `exercise-3.html`: Practice sessions implementing layouts and UI components using Tailwind CSS.
- `tailwind.config.js`: Custom configuration for the Tailwind environment.

### 🎨 `/CSS`
- Basic box styling and standard CSS index to compare with the new utility-first approach.

---

## 💻 Code Highlight: Tailwind Approach

```html
<div class="flex items-center justify-center min-h-screen bg-gray-100">
  <div class="p-6 bg-white rounded-xl shadow-lg flex items-center space-x-4">
    <div class="shrink-0">
      <img class="h-12 w-12" src="/img/logo.svg" alt="ChitChat Logo">
    </div>
    <div>
      <div class="text-xl font-medium text-black">ChitChat</div>
      <p class="text-slate-500">You have a new message!</p>
    </div>
  </div>
</div>
