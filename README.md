# 🍕🌌 Cosmic Pizza - Slideware Prototype  

This repository contains the **Cosmic Pizza** prototype, built as a **slideware prototype** for rapid UX exploration. The application imagines a **space-themed gourmet pizza experience**, where ordering a pizza becomes an intergalactic journey.  

> 📌 This project was approached as a UX case study, covering concept, task flows, design patterns, slideware prototyping, and iteration.  

---

## 📝 What is Slideware in UI/UX?  

In the context of UI/UX and **rapid prototyping**, *slideware* refers to prototypes created using presentation tools, such as PowerPoint, Google Slides, etc.  

- **Purpose:** Quickly simulate flows and interfaces for early validation.  
- **Speed:** Faster than high-fidelity prototyping tools.  
- **Use Cases:** Ordering workflows, interactive menus, progress indicators, and usability demonstrations.  

Slideware prototypes help UX designers validate ideas early, before investing in high-fidelity designs or engineering.  

---

## 🚀 Theme Description  

**Name:** *Cosmic Pizza*  
**Theme:** A **space-themed gourmet pizza experience**. Each pizza is tied to a celestial object or cosmic theme, making the ordering process feel like a journey through the stars.  

---

## 🎨 Problem Space  

Many online food ordering apps focus on speed and function, but lack delight and theme. The goal of Cosmic Pizza was to imagine how a playful, space-themed ordering experience could engage users while still being functional and clear.  

---

## 🎯 Core Functionality  

1. **Create Your Pizza**  
   - Order a fully customized pizza (size, crust, sauce, toppings).  
   - Monthly “Special Pizza” option available.  

2. **Checkout & Confirmation**  
   - Order summary with size, crust, toppings, quantity, and pricing.  
   - Includes stepper inputs for adjusting quantity.  
   - Exit button returns to Create Your Pizza.  

3. **Progress Indicator**  
   - Order status represented with **mini pizza icons** (Placed → In Oven → Complete).  
   - Refresh button updates progress; Exit button allows returning to start.  

---

## 📖 Case Study Tasks  

### **Basic Task 1:** Order 1 Small Custom Pizza  
**Prompt:** Order a small pizza with a deep dish crust, salsa sauce, and smoked salmon topping.  
**Step-by-Step:**  
1. Select *Pluto Small* (size).  
2. Select *Black Hole Deep Dish* (crust).  
3. Dropdown → choose *Celestial Salsa* (sauce).  
4. Add *Stellar Smoked Salmon* (topping).  
5. Checkout → Place Order → Refresh → Oven → Refresh → Complete.  

### **Basic Task 2:** Order 2 October Specials  
**Prompt:** Order 2 *Small Venus Veggie Delight* pizzas.  
**Step-by-Step:**  
1. Select *Small Venus Veggie Delight* (special).  
2. Checkout → update quantity to 2 → Place Order.  
3. Refresh → Oven → Refresh → Complete.  

---

## 🧩 Design Patterns  

- **Progress Indicator:** Uses evolving mini pizza icons to show status.  
- **Undo:** Radio, checkbox, and dropdown selections can be deselected.  
- **List-Builder:** Step-by-step custom pizza builder (size → crust → sauce → toppings).  
- **Confirmation Page:** Order summary, pricing, and adjustable quantities before submission.  

---

## 🎛 Interactive Elements  

- **Radio buttons:** For pizza size, crust, or selecting a Special.  
- **Dropdowns:** For sauces.  
- **Checkboxes:** For toppings.  
- **Action buttons:** Navigate flows (Checkout, Place Order, Exit).  
- **Stepper inputs:** +/– buttons to adjust quantity.  

---

## 🔄 Revisions & Additions (Based on User Feedback)  

After an initial task walkthrough and **testing with three participants**, I made several changes to improve clarity and usability:  

- **Action buttons resized:**<br>
Shrunk the purple footer buttons so they look more like true buttons rather than part of the layout.  
- **Pricing transparency:**<br>
Added pizza prices to the "Create Your Pizza" screen, so users could better evaluate their order.  
- **Step-by-step guidance:**<br>
Added "Step 1, Step 2…" labels in the builder to reinforce the list-builder pattern and guide users incrementally.  
- **Confirmation page introduced:**<br>
Provided an order summary with stepper inputs for adjusting quantity, total price, and an exit option.  
- **Progress indicator refined:**<br>
Included mini pizza icons with refresh and exit options to show real-time order status.  
- **Improved linking:**<br>
Added more complete linking between screens (and self-links), so accidental clicks wouldn't pull users away from the intended flow.  

---

## 👥 Lessons Learned from Testing  

From the **three test participants**, I observed several consistent themes:  

- **User flow clarity:**<br>
Some testers weren't sure how to move from selecting toppings to checkout, so I added clearer linking and instructions.  
- **Orientation & navigation:**<br>
Extra self-links were helpful in keeping users grounded within a screen.  
- **Error prevention:**<br>
Testers suggested disabling out-of-order selections (like toppings before crust). Future iterations could implement stronger error handling.  
- **Inactive elements:**<br>
Leaving inactive choices unlinked reduced confusion and improved flow consistency.  

---

## 📊 Fidelity & Inspirations  

- **Information Design:** Medium fidelity (clear steps, pizza builder flow).  
- **Interaction Design:** High fidelity (click-through tasks, progress indicator).  
- **Visual Branding:** High fidelity (space theme, cosmic names, stylized components).  
- **Editorial Content:** High fidelity (funny cosmic names, themed pizza descriptions).  

**Inspirations:** Domino’s Pizza Tracker, space-themed games/apps, stepper-style e-commerce flows.  

---

## 📂 Repository Contents  

- **cosmic_pizza_sketches.png** – Early concept sketches of the prototype flow and theming.
- **cosmic_pizza_final.pptx** – Editable slideware prototype file with all interactive linking.
- **cosmic_pizza_final.pdf** – Exported slideware prototype for easy viewing and sharing.  

---

> 📌 Cosmic Pizza demonstrates how slideware prototyping can make ordering workflows fun, testable, and engaging, while validating usability patterns before high-fidelity design. 
