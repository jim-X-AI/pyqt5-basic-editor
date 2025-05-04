
# PyQt5 Basic Editor

A simple PyQt5-based desktop application with a graphical user interface (GUI) that includes basic menu actions: **New**, **Save**, **Copy**, and **Paste**. This project serves as a template or starting point for building more complex PyQt5 applications.

---

## 🖥️ Overview

This is a basic GUI application built using **PyQt5**, featuring:

- A main window with a label.
- Menu bar with two menus: `file` and `edit`.
- Actions:
  - File: `new`, `save`
  - Edit: `copy`, `paste`

Although currently minimal, this structure provides a clean foundation for adding functionality such as text editing, file handling, and clipboard operations.

---

## 🧰 Features

- PyQt5 UI loaded from `.ui` file (can be edited visually using Qt Designer).
- Keyboard shortcuts:
  - `Ctrl+N` – New
  - `Ctrl+S` – Save
  - `Ctrl+C` – Copy
  - `Ctrl+V` – Paste
- Status tips for each action.

---

## 🛠️ Technologies Used

- Python 3.x
- PyQt5

---

## 📦 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/pyqt5-basic-editor.git
   ```

2. Navigate into the directory:

   ```bash
   cd pyqt5-basic-editor
   ```

3. Install dependencies:

   ```bash
   pip install pyqt5
   ```

4. Run the app:

   ```bash
   python main.py
   ```

> Note: You can rename `main.py` to match the actual name of your Python script if different.

---

## 📁 Project Structure

```
.
├── main.py            # Main PyQt5 application script
└── text1.ui           # Qt Designer UI file (optional, not required at runtime)
```

> If you're distributing this app, make sure to include the `.ui` file if others may want to modify the UI design.

---

## 🔧 To Add Later (Optional Enhancements)

You can expand this app by connecting the menu actions to custom functions, such as:

- Opening a new file dialog (`new`)
- Saving text to a file (`save`)
- Implementing copy/paste functionality using `QClipboard`

---

## 📬 Contact

If you have any questions or suggestions:

- 📧 Email: [jamiuabdulazeez689@gmail.com](mailto:jamiuabdulazeez689@gmail.com)
- 💼 Twitter/X: [@JamiuOladi55000](https://x.com/JamiuOladi55000?t=AfyCwGxAg0OnFC0EBw1nqw&s=09)

---

## 📜 License

MIT License – see [`LICENSE`](LICENSE) for details.
```
