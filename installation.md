# Install Node.js on Ubuntu using NVM and NPM

Welcome! This guide will help beginners install the latest version of Node.js on Ubuntu using NVM (Node Version Manager) and NPM (Node Package Manager). Follow the steps below to get started. 🚀

---

## Prerequisites
1. A machine running **Ubuntu**.
2. Basic knowledge of using the **terminal**.

---

## Step 1: Update and Upgrade Ubuntu
Before we begin, update your system packages to ensure compatibility. 🛠️
```bash
sudo apt update && sudo apt upgrade -y
```

---

## Step 2: Install Curl
Curl is needed to download the NVM installation script. 📥
```bash
sudo apt install curl -y
```

---

## Step 3: Install NVM (Node Version Manager)
NVM makes it easy to install and manage Node.js versions. Run the following command to install NVM:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

### Verify NVM Installation
Close and reopen your terminal, or run:
```bash
source ~/.bashrc
```
Then check if NVM is installed:
```bash
nvm --version
```
If you see a version number, NVM is successfully installed! 🎉

---

## Step 4: Install the Latest Node.js Version
Now that NVM is installed, use it to install Node.js:
```bash
nvm install node
```
This will install the latest version of Node.js. 🚀

### Verify Node.js Installation
Check the installed Node.js version:
```bash
node --version
```

---

## Step 5: Verify NPM Installation
NPM comes bundled with Node.js. Check its version to confirm:
```bash
npm --version
```

---

## Step 6: Set Default Node.js Version (Optional)
To make the latest Node.js version the default for new terminal sessions:
```bash
nvm alias default node
```

---

## Troubleshooting
- If you face issues, make sure your terminal is reloaded by running:
  ```bash
  source ~/.bashrc
  ```
- For permissions errors, use `sudo` where needed. ❗

---

## Additional Resources
- 🌐 [Node.js Official Download Page](https://nodejs.org/en/download)
- 📚 [Install and Uninstall Node.js on Ubuntu](https://www.digitalocean.com/community/tutorials/install-uninstall-nodejs-ubuntu) - This helped me learn the basics of Node.js installation!
- [NVM Documentation](https://github.com/nvm-sh/nvm)
- [Node.js Official Website](https://nodejs.org/)

Happy coding! 🚀

