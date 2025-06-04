
# 🧲 Drag and Drop – Day 19 of 30 Days of JavaScript

A simple and interactive **drag-and-drop interface** using **HTML**, **CSS**, and **JavaScript**. Users can drag list items between two containers — simulating a task organizer or sortable list UI.

---

## ✨ Features

- 🔀 Drag and drop list items between boxes
- 🎯 Works in both directions (left ↔ right)
- 🖱️ Native HTML5 drag-and-drop API
- 💅 Minimal and visually clean layout

---

## 🛠️ Built With

- HTML5 (with native `draggable="true"` attributes)
- CSS3 (Flexbox, dashed borders, icons)
- JavaScript (DOM events: `dragstart`, `dragover`, `drop`)

---

## 📸 Preview

Here’s a look at the Drag and Drop App:

![App Preview](https://raw.githubusercontent.com/Qasim-Rokeeb/drag-and-drop/main/screenshot.png)

---

## 🌐 Live Demo

🔗 [View Live Project](https://qasim-rokeeb.github.io/drag-and-drop)

---

## 📁 Project Structure

```bash
Drag-and-Drop/
├── index.html         # Main HTML layout
├── drag_drop_icon.png # Icon used in list items
├── screenshot.png     # Preview image
└── README.md          # Project documentation
```

---

## 💡 How It Works

- Each `.list` item is set as `draggable="true"`.
- When dragging starts, the selected item is saved.
- Both boxes listen for `dragover` (to allow dropping).
- On `drop`, the item is appended to the target container.

---

## 🔄 Two-Way Drag Support

✅ Drag from **left** ➡ **right**  
✅ Drag from **right** ➡ **left**

This adds flexibility and makes it reusable for task management interfaces.

---

## 🧠 What I Learned

- HTML5 Drag and Drop API basics
- Managing drag events (`dragstart`, `dragover`, `drop`)
- Appending elements dynamically via JavaScript
- Building responsive and interactive UIs

---

## 📅 Challenge

This is **Day 19** of my **30 Days of JavaScript** challenge.  
Follow my journey and future projects 👇

📲 [@qasimrokeeb](https://x.com/qasimrokeeb)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
````


