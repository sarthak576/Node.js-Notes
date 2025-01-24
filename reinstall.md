# 📒 Node.js Notes

Your ultimate guide to managing Node.js with `nvm`! Learn how to uninstall, reinstall, and check the installed versions of Node.js with ease. 🎯

---

## 🚀 How to Uninstall Node.js

1. **Remove Node.js Installed via nvm:**
   ```bash
   nvm uninstall <version>
   ```
   Replace `<version>` with the specific Node.js version you want to remove.

2. **Check Active Node.js Version:**
   If the version is currently active, switch to another version before uninstalling:
   ```bash
   nvm use <another-version>
   ```

---

## 🌟 How to Reinstall Node.js Using nvm

1. **Install the Latest LTS Version:**
   ```bash
   nvm install --lts
   ```

2. **Set the Default Version:**
   ```bash
   nvm alias default <version>
   ```
   This ensures the specified version is used by default.

3. **Verify Installation:**
   ```bash
   node -v
   npm -v
   ```

---

## 🔍 How to Check Node.js Versions on Your System

1. **List All Installed Node.js Versions:**
   ```bash
   nvm list
   ```
   This shows all installed versions and highlights the active one.

2. **Find the Node.js Binary File:**
   ```bash
   which node
   ```
   This displays the path to the Node.js executable.

---

## ✨ Additional Tips

- Always use `nvm` for managing multiple Node.js versions efficiently.
- If `nvm` is not installed, set it up quickly:
  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
  ```
- Reload your shell and verify installation:
  ```bash
  source ~/.bashrc
  nvm --version
  ```

---

Enjoy seamless Node.js management! 💻✨

