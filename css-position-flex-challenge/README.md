# CSS Layout Exercise: Flexbox & Position

You have been given:

- An **HTML file without CSS**
- A **screenshot of the final design** located in `/assets/expected-result.png`

Your task is to recreate the layout and visual style shown in the screenshot **using only CSS**. You are not supposed to edit the HTML file.

![Expected result](assets/expected-result.png)

---

## 🎯 Objective

The goal of this exercise is to practice:

- **CSS selectors and combinators**
- **Flexbox layout**
- **CSS `position` property**
- **Any other CSS properties you know**
- Clean and readable CSS (Tip: Try to sort the selectors in the CSS file by ordering them, whenever possible and makes sense, from most generic to most specific)

---

## 📐 Layout Requirements

Using the screenshot as reference, your CSS should include:

### 1. Navigation Bar

- Positioned at the top of the page
- Horizontal layout
- Logo on the left, menu items on the right
- Should remain visible when scrolling (hint: use the `position` property)

### 2. Hero Section

- Centered content (title, text, button)
- Vertical and horizontal alignment using **Flexbox**
- A background with a **gradient color**

### 3. Items Section

- A group of cards/items
- Layout created with **Flexbox**
- Items should **wrap** on smaller screens
- There should be some space between items
- When you **hover over** one of the elements, it should appear a few pixels larger and its background color should change
- Pay attention to the **"Special Item"** message on one of the cards

### 4. Footer

- Located at the bottom of the page
- Centered content
- Footer links aligned horizontally

### 5. "Back to top" Button

- Located at the bottom right of the page
- Should remain visible and in the same position when scrolling

---

## 📌 CSS Position Requirements

Your solution must include examples of:

- `position: relative`
- `position: absolute`
- `position: fixed`
- `position: sticky`
- `display: flex`

Each value should be used **intentionally** and make sense in the layout.

---

## 📱 Responsive Behavior

- The layout should adapt as much as possible to smaller screens (hints: use `relative widths` and `flex containers` when it is necessary)
- Items section should wrap correctly

---

## 🧠 Tips

- Do not focus on matching colors exactly — focus on **layout and behavior**
- Use comments in your CSS to explain your decisions
- Think about **why** each `position` or Flexbox property is used

---

Good luck — and have fun experimenting with CSS! 🚀
