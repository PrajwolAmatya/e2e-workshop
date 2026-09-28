# Todo App

A simple Todo application with user login. The app is served at `http://localhost:3000` and includes end-to-end (E2E) tests written with **Cucumber** and **Playwright**.

# Requirements

| Requirement | Version            |
| ----------- | ------------------ |
| **Node.js** | **>= 20**          |
| npm         | Comes with Node.js |

## Install Node.js
### Windows
1. Download the LTS installer from https://nodejs.org/en/download
2. Download the `Windows Installer (.msi)`
3. Run the installer and follow the prompts.
4. Open a new `Command Prompt` or `Powershell` window and verify:

```
node --version
npm --version
```

## Linux (Ubuntu/Debian)
```
# Using NodeSource
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs

# Verify
node --version
npm --version
```

## macOS
**Option 1 - Official installer**
1. Download the macOS LTS installer from https://nodejs.org/en/download
2. Download the `macOS Installer (.pkg)`
3. Open the `.pkg`  and follow the installation steps.
4. Verify in terminal:

```
node --version
npm --version
```

**Option 2 - Homebrew**
```
brew install node

# verify
node --version
npm --version
```

# Project Setup

1. Goto https://github.com/PrajwolAmatya/e2e-workshop
2. Click on `Code`
3. Then download the zip by clicking `Download ZIP`
4. Extract the project
5. Enter the project directory
```
cd e2e-workshop
```
6. Install dependencies
```
npm install
```
7. Install Playwright
```
npx playwright install
```

## Run the app
```
npm start
```

Then open: http://localhost:3000

Default login credentials (from the E2E tests):

| Username | Password |
|----------|----------|
| `admin`  | `admin`  |
