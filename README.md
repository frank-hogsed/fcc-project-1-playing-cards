				# HTML & CSS Playing Cards

A clean, responsive **HTML and CSS implementation of classic playing cards** (Ace through 5) built using modern layouts like Flexbox and CSS Grid. 

This project demonstrates semantic HTML structures, custom grid mappings for card suit pips, and smooth interactive hover states.

## 🚀 Features

* **Pure HTML & CSS:** No JavaScript or external framework dependencies.
* **Modern Layouts:** Uses **Flexbox** for global card alignment and internal structural distribution (Left, Middle, Right) alongside **CSS Grid** for precise pip placements.
* **Semantic HTML Entities:** Uses native HTML entities (`&spades;`, `&clubs;`, `&hearts;`, `&diams;`) for sharp, high-quality vector rendering.
* **High Contrast Friendly:** Incorporates `forced-color-adjust: none` to protect red suit visibility across different system accessibility themes.
* **Responsive Layout:** Flex-wrap configuration allows the cards to dynamically flow on different screen widths.

## 🛠️ Tech Stack

* **HTML5:** Semantic architecture.
* **CSS3:** Flexbox, CSS Grid, custom transitions, and CSS transforms (`rotate(180deg)`) for inverted card corners.

## 📁 Project Structure

```text
├── index.html   # Main markup containing cards (Ace of Spades to 5 of Clubs)
└── styles.css   # Layout, Grid templates, variables, and animations
```

## 💻 Getting Started

To view and play around with this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Open the project folder:**
   ```bash
   cd YOUR_REPO_NAME
   ```
3. **Launch the project:**
   Simply double-click the `index.html` file to open it in your favorite web browser.

## 🧠 What I Learned / Project Highlights

* **Inverting Elements:** Used `transform: rotate(180deg)` to successfully invert the suit and values on the bottom-right corner of each card.
* **Grid Spanning:** Used `grid-column: span 2` to perfectly center the 3rd pip on the 5 of Clubs card layout between a 2-column grid.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
