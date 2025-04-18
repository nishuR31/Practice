
# 🎨 Change My Color! – Interactive Text Color Playground

> An interactive webpage that lets users **change the color of a heading in real-time**, using pre-defined buttons, a color picker, and dynamic button generation.

---

## 🧠 Features

- 🖌️ Editable heading (`contenteditable`) for instant customization.
- 🔘 Pre-built color buttons (Red, Green, Blue, etc.) to change the heading's color instantly.
- 🎨 Live color picker to choose custom colors.
- ➕ Dynamically add new buttons based on selected custom color.
- 🔄 Reset button to restore the default style (black).
- 💥 Fun animation effect (`shake`) when a color is applied or reset.
- 🧾 Input field auto-syncs with the color picker.
- 👨‍🎨 Stylish UI with shadows, transitions, and animations.
- 📦 All functionality in a **single HTML file** — no external dependencies.

---

## 🧰 Tech Stack

- **HTML5** for structure
- **CSS3** for styling and animations
- **Vanilla JavaScript** for DOM manipulation and event handling

---

## 🚀 How to Use

1. **Clone or download** this repository.
2. Open the `index.html` file in any modern web browser.
3. Start clicking color buttons or use the color picker to see the magic happen!

---

## ✨ Custom Usage

- **Want to add your own color?**
  - Pick a color using the color input.
  - Click `Add button` and a new button with your selected color will appear.
- **Want to reset?**
  - Click the `Reset` button to bring the heading back to black.

---

## 📸 Screenshots

> Add your own screenshots or screen recordings here for extra ✨

---

## 📁 Project Structure

```bash
📁 your-folder/
└── index.html       # Main HTML file containing all styles, script, and layout
```

---

## 📌 Developer Notes

- Uses `element.style.color` and `element.style.borderBottom` for live updates.
- Utilizes `animation` for visual feedback (`shake` keyframes).
- Graceful fallback for invalid color inputs with warning messages.
- Fully responsive layout with `flexbox`.

---

## ✅ To-Do / Possible Improvements

- [ ] Add localStorage to save custom colors between sessions.
- [ ] Add support for deleting custom buttons.
- [ ] Improve accessibility (keyboard nav, ARIA roles).
- [ ] Mobile optimization and touch interaction polish.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Made with ❤️ and JavaScript magic.
