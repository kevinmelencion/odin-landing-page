# Odin Landing Page

A fully structured, modern desktop landing page built from scratch as part of **The Odin Project** foundations curriculum. This project brings together semantic HTML architecture and advanced CSS Flexbox layout principles.

## 📸 Final Design Preview

![Odin Landing Page Final Outcome](./images/image-01.png)

---

## 🚀 Features & Implementation Details

* **Semantic HTML5 Skeleton:** Structured cleanly into 4 distinct macro-sections (Hero, Info Grid, Testimonial, Call to Action) topped with a global navigation header and anchored with a copyright footer.
* **Flexbox Layout Architecture:** Built entirely without rigid float hacks or absolute positioning. Utilizes flexible row/column flows, absolute item centring, and space-distribution utilities (`justify-content: space-between`).
* **Maintainable Styling Rules:** Styled using a single external stylesheet emphasizing strict CSS reset standards and clean container isolation.

## 🛠️ Color & Typography Specifications

* **Primary Font:** Roboto
* **Dark Neutral Backgrounds:** `#1F2937`
* **Light Neutral Backgrounds:** `#E5E7EB`
* **Accents & Callouts:** `#3882F6` (Odin Blue)
* **Main Hero Text Size:** 48px (Font-weight: 900)

---

## 💡 Key Takeaways

While working through this layout milestone, I reinforced several essential front-end concepts:
1.  **Atomic Git Commit Workflow:** Adhered to the *Conventional Commits* specification, isolating structural markup iterations (`feat(html)`) cleanly from styling layers (`feat(css)`).
2.  **Structural Containment:** Learned that resolving complex multi-column grids requires wrapping child elements inside dedicated flex-containers rather than manipulating individual nodes out in the open.
3.  **The Power of Display Blocks:** Explored how forcing block context onto inline elements like anchor (`<a>`) tags stretches their click-targets for a significantly better user experience.