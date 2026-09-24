# Todo App

A simple Todo application with user login. The app is served at `http://localhost:3000` and includes end-to-end (E2E) tests written with **Cucumber** and **Playwright**.

## Requirements

| Requirement | Version |
|-------------|---------|
| **Node.js** | **>= 20** (required by Playwright) |
| npm        | Comes with Node.js |

> Playwright (used for E2E tests) requires Node.js 20 or higher. Using an older version will cause the tests to fail.

---

## Install Node.js

### Linux (Ubuntu / Debian)

```bash
# Using NodeSource (recommended)
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs

# Verify
node --version   # should be v20.x or higher
npm --version
```

### Linux (Fedora / RHEL / CentOS)

```bash
sudo dnf install nodejs
# or for a specific major version via NodeSource:
curl -fsSL https://rpm.nodesource.com/setup_20.x | sudo bash -
sudo dnf install -y nodejs

node --version
npm --version
```

### Windows

1. Download the **LTS** installer (v20 or newer) from [https://nodejs.org](https://nodejs.org).
2. Run the installer and follow the prompts.
3. Open a new **Command Prompt** or **PowerShell** window and verify:

```powershell
node --version
npm --version
```

### macOS

**Option 1 – Official installer**

1. Download the macOS LTS installer from [https://nodejs.org](https://nodejs.org).
2. Open the `.pkg` and follow the installation steps.
3. Verify in Terminal:

```bash
node --version
npm --version
```

**Option 2 – Homebrew**

```bash
brew install node@20
# or the latest LTS
brew install node

node --version
npm --version
```

---

## Project setup

```bash
# Enter the project directory
cd todo-app-private

# Install dependencies
npm install

# Install Playwright browsers (required for E2E tests)
npx playwright install
```

---

## How to run the app

The Todo app listens on **port 3000**. Start it in one terminal, then open a browser or run the E2E tests against it.

### Linux / macOS

```bash
# From the project root
npm start
```

Then open: [http://localhost:3000](http://localhost:3000)

Default login credentials (from the E2E tests):

| Username | Password |
|----------|----------|
| `admin`  | `admin`  |

### Windows (Command Prompt / PowerShell)

```powershell
cd todo-app-private
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

