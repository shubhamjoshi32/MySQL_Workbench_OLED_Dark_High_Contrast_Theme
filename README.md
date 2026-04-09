# 🌑 MySQL Workbench OLED Dark High Contrast Theme

A **True Black (#000000)** theme for MySQL Workbench. This theme is specifically optimized for OLED displays, reduce eye strain during long sessions and for dark theme lovers.

---

## ✨ Features
* **True OLED Black:** Background set to `#000000` for perfect blacks.
* **Vibrant Syntax:** High-visibility neon palette for keywords, functions, and identifiers.
* **Future-Proof:** Easily updatable without breaking core Workbench settings.

---

## 📸 Preview
![Theme Preview](screenshot\Black_Oled_High_Contrast.png)

---

## 🚀 Installation

### Option 1: Quick Replacement (Recommended)
(Please check path on your systems before attempting changes, some paths mentioned here are from ai (Linux* and MacOS*))

1. **Locate your config folder:**
   - **Windows:** `C:\Program Files\MySQL\MySQL Workbench X.0\data`
   - **Linux:** `~/.mysql/workbench/`
   - **macOS:** `~/Library/Application Support/MySQL/Workbench/`
2. **Back up** your existing `code_editor.xml` (rename it to `code_editor_backup.xml`).

3. **Download** the `code_editor.xml` from this repo and place it in that folder.

4. **Restart** MySQL Workbench completely (ensure it is closed in Task Manager first).

### Option 2: Safe Manual Paste (Future-Proof)
Use this method if a software update has changed the file structure and you want to ensure compatibility:

1. Open your local `code_editor.xml` in a text editor (like VS Code or Notepad++).

2. Find the `<globals>` tag. Replace that entire block with the one from this repo to fix the cursor/selection colors.

3. Find the `<language name="SCLEX_MYSQL">` tag.
4. Delete everything **between** the opening `<language...>` and closing `</language>` tags.

5. Paste the style IDs from this repo into that section.

6. Save and restart.

---

## ⚠️ Important Note on UI Compatibility
**This theme only affects the SQL Query Editor.** MySQL Workbench does not currently support a native "Global Dark Mode" for its entire interface (Sidebars, Result Grid, and Menus) on Windows or Linux. 
* The **Code Editor** will be True OLED Black.
* The **Surrounding UI** (Schema navigator, buttons, etc.) will remain the default system color (usually light gray).

---

## ⚖️ License
This project is licensed under the **MIT License**. Feel free to fork, modify, and share.

---

## 👤 Credits
**Developed (Modded) by:** Shubham Joshi