# 🚀 UI Kit - Molecules & Organisms (Project 2)

Welcome to the **UI Kit** repository developed by Valentin. This project implements the **Atomic Design** methodology to build modular, scalable, and aesthetic web interfaces, specifically tailored for an **Eventbrite-style** application.

---

## 🌓 Visual Identity
This project strictly follows a **Dark Mode** identity for visual comfort and a modern professional look.
* **Base Theme**: Bootswatch Darkly (Bootstrap 4).
* **Color Palette**: Deep Charcoal background (`#222`), Anthracite cards (`#303030`), and Primary accents (`#375a7f`).
* **Typography**: Montserrat (Headings) and Roboto (Body text).

---

## 🏗️ Project Structure
The project is divided into autonomous organisms to ensure seamless integration into a future **Ruby on Rails** architecture.

### 1. Foundations & Navigation
* **`navbar.html`**: A responsive navigation bar featuring discovery links and call-to-action buttons.
* **`footer.html`**: A professional 4-column footer including a newsletter molecule and social media links.
* **`index.html`**: A visual dashboard serving as a central hub to explore every component of the kit.

### 2. Content Molecules
* **`cards.html`**: Displays vertical event cards (perfectly aligned via Flexbox) and horizontal participant molecules.
* **`comments.html`**: A messaging system including the "Post" molecule and a complete "Comment Section" organism.

### 3. Layout Organisms
* **`banner.html`**: High-impact banners with dark overlays to ensure text legibility over background images.
* **`presentation_ressource.html`**: A "Show" page layout (8-column Visual / 4-column Ticketing block).
* **`element_presentation.html`**: Marketing sections with alternating text/image layouts and vertical centering.
* **`pricing.html`**: A pricing table organism designed for event organizers.

---

## 🛠️ Installation & Usage
1. Clone the repository.
2. Open `index.html` in any browser to access the Dashboard.
3. Every page links to the central **`style.css`** file to maintain visual unity.

---

## 🧪 Technical Highlights
* **Flexbox Alignment**: Heavy use of `display: flex` and `flex-grow` to ensure all cards in a row share the same height, regardless of content length.
* **Smart Targeting**: The CSS uses specific logic (such as the `:has(.card)` selector) to prevent layout overrides on simple text-based pages.
* **Zero "White Flash"**: Background colors are forced via `!important` to respect the dark identity across all browsers.



---

## 🖋️ Author

- **Valentin** (Fullstack Developer @ THP)

_The Hacking Project 2026_
