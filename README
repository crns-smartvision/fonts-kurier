# Kurier Font Installation Guide (Linux)

This repository provides instructions for installing the **Kurier** font on a Linux system.

## 📦 Installation Steps

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2. Copy the font files

Create the local fonts directory if it does not already exist:

```bash
mkdir -p ~/.local/share/fonts
```

Copy the `kurier` folder into your local fonts directory:

```bash
cp -r kurier ~/.local/share/fonts/
```

### 3. Refresh the font cache

After copying the fonts, update the system font cache:

```bash
fc-cache -f -v
```

## ✅ Verify Installation

To confirm that the Kurier font is correctly installed, run:

```bash
fc-list | grep -i kurier
```

If installed properly, you should see entries corresponding to the Kurier font files.

## 🎨 Testing the Font

You can test the font using a graphical application such as **Inkscape**:

1. Open Inkscape
2. Create a new document
3. Select the text tool
4. In the font selection dropdown, search for **Kurier**
5. Apply it to your text

If the font appears and renders correctly, the installation was successful.

## 🧹 Troubleshooting

* If the font does not appear:

  * Restart the application (e.g., Inkscape)
  * Log out and log back in
  * Ensure the font files are valid (`.ttf`, `.otf`)

* Rebuild font cache again if needed:

  ```bash
  fc-cache -f -v
  ```

## 📁 Expected Directory Structure

```
~/.local/share/fonts/
└── kurier/
    ├── Kurier-Regular.ttf
    ├── Kurier-Bold.ttf
    ├── Kurier-Italic.ttf
    └── ...
```

## 📌 Notes

* This installation is **user-specific** (no root required).
* For system-wide installation, fonts can be placed in `/usr/share/fonts/` (requires sudo).

---

You're ready to use Kurier across your Linux applications 🎉

