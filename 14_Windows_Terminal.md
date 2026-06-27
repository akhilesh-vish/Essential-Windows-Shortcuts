# 🖥️ Windows Terminal

Windows Terminal is Microsoft's modern terminal application designed for developers, system administrators, and power users. It brings together **Command Prompt (CMD)**, **PowerShell**, **PowerShell 7**, **Windows Subsystem for Linux (WSL)**, **Azure Cloud Shell**, and other command-line tools into a single, highly customizable interface.

Unlike the traditional console window, Windows Terminal supports **multiple tabs, split panes, GPU-accelerated rendering, Unicode, UTF-8, customizable themes, transparency, command palettes, and extensive keyboard shortcuts**.

Whether you're writing scripts, managing servers, developing software, or simply navigating your system, mastering these shortcuts will significantly improve your workflow.

> [!TIP]
> Think of Windows Terminal as the **Visual Studio Code of command-line applications**—one window capable of hosting multiple shells, tabs, and workspaces simultaneously.

---

# 📖 Table of Contents

* [⌨️ Keyboard Shortcuts](#️-keyboard-shortcuts)

  * General
  * Tabs
  * Split Panes
  * Navigation
  * Command Palette
  * Editing
  * Window Management
* [⭐ Most Useful Shortcuts](#-most-useful-shortcuts)
* [💡 Productivity Tips](#-productivity-tips)
* [📝 Notes](#-notes)
* [⚙️ Requirements](#️-requirements)
* [💭 Did You Know?](#-did-you-know)

---

# ⌨️ Keyboard Shortcuts

## 🚀 General

| Shortcut                 | Description                                              |
| ------------------------ | -------------------------------------------------------- |
| **Ctrl + Shift + T**     | Open a new terminal tab.                                 |
| **Ctrl + Shift + W**     | Close the active tab.                                    |
| **Ctrl + Shift + P**     | Open the Command Palette.                                |
| **Ctrl + Shift + F**     | Search within the terminal buffer (if enabled).          |
| **Ctrl + Shift + Space** | Open the profile selection menu (default configuration). |

---

## 📑 Tabs

| Shortcut                        | Description                                                             |
| ------------------------------- | ----------------------------------------------------------------------- |
| **Ctrl + Tab**                  | Switch to the next tab.                                                 |
| **Ctrl + Shift + Tab**          | Switch to the previous tab.                                             |
| **Ctrl + Page Up**              | Move to the previous tab.                                               |
| **Ctrl + Page Down**            | Move to the next tab.                                                   |
| **Alt + 1–9**                   | Switch directly to a specific tab.                                      |
| **Ctrl + Shift + Number (1–9)** | Open a new tab using the corresponding profile (default configuration). |

---

## 🪟 Split Panes

| Shortcut                     | Description                                     |
| ---------------------------- | ----------------------------------------------- |
| **Alt + Shift + D**          | Duplicate the current pane.                     |
| **Alt + Shift + -**          | Split the current pane horizontally.            |
| **Alt + Shift + +**          | Split the current pane vertically.              |
| **Alt + Arrow Keys**         | Move focus between split panes.                 |
| **Alt + Shift + Arrow Keys** | Resize the active pane (default configuration). |
| **Ctrl + Shift + W**         | Close the active pane or tab when appropriate.  |

---

## 🧭 Navigation

| Shortcut                 | Description                                                         |
| ------------------------ | ------------------------------------------------------------------- |
| **Ctrl + Shift + ↑ / ↓** | Scroll through the terminal buffer while keeping the prompt active. |
| **Ctrl + Home**          | Jump to the beginning of the scrollback buffer.                     |
| **Ctrl + End**           | Jump to the bottom of the scrollback buffer.                        |
| **Page Up / Page Down**  | Scroll one page at a time.                                          |

---

## ✏️ Editing

| Shortcut               | Description                                                                             |
| ---------------------- | --------------------------------------------------------------------------------------- |
| **Ctrl + C**           | Copy selected text or interrupt the currently running process when no text is selected. |
| **Ctrl + Shift + C**   | Copy selected text to the clipboard.                                                    |
| **Ctrl + Shift + V**   | Paste clipboard contents into the terminal.                                             |
| **Ctrl + A**           | Select all text in the active buffer (where supported).                                 |
| **Ctrl + Mouse Wheel** | Zoom the terminal text in or out.                                                       |

---

## 🎛️ Command Palette

| Shortcut             | Description                                            |
| -------------------- | ------------------------------------------------------ |
| **Ctrl + Shift + P** | Open the Command Palette.                              |
| **Arrow Keys**       | Navigate available commands.                           |
| **Enter**            | Execute the selected command.                          |
| **Esc**              | Close the Command Palette without executing a command. |

---

## 🖥️ Window Management

| Shortcut        | Description                                     |
| --------------- | ----------------------------------------------- |
| **Alt + Enter** | Toggle Full Screen mode.                        |
| **F11**         | Toggle Full Screen mode (if configured).        |
| **Alt + F4**    | Close Windows Terminal.                         |
| **Win + ↑**     | Maximize the terminal window.                   |
| **Win + ↓**     | Restore or minimize the terminal window.        |
| **Win + ← / →** | Snap the terminal to either side of the screen. |

---

# ⭐ Most Useful Shortcuts

These shortcuts will provide the biggest productivity boost when using Windows Terminal.

| Shortcut               | Why It's Useful                                                           |
| ---------------------- | ------------------------------------------------------------------------- |
| **Ctrl + Shift + T**   | Open another terminal without launching a new window.                     |
| **Ctrl + Tab**         | Quickly switch between open terminal tabs.                                |
| **Alt + Shift + +**    | Split the current tab vertically for side-by-side work.                   |
| **Alt + Shift + -**    | Split the current tab horizontally for stacked views.                     |
| **Ctrl + Shift + P**   | Access nearly every Windows Terminal feature through the Command Palette. |
| **Ctrl + Shift + C**   | Copy output cleanly to the clipboard.                                     |
| **Ctrl + Shift + V**   | Paste commands or scripts safely.                                         |
| **Ctrl + Mouse Wheel** | Zoom text without changing your Windows display settings.                 |

---

# 💡 Productivity Tips

* Keep **PowerShell**, **Command Prompt**, and **WSL** open in separate tabs instead of opening multiple terminal windows.
* Use **Split Panes** when working on related tasks—for example, editing files in one pane while monitoring logs in another.
* Learn the **Command Palette** (`Ctrl + Shift + P`). It's one of Windows Terminal's most powerful features and provides quick access to nearly every command.
* If you frequently use multiple profiles, customize your startup configuration so your preferred shell opens automatically.
* Use tabs to organize projects, and split panes to organize tasks within a project.
* Take advantage of GPU-accelerated rendering and customizable themes to improve readability during long terminal sessions.

---

# 📝 Notes

> [!NOTE]
> Windows Terminal is separate from Command Prompt and PowerShell. It serves as a modern host that can run multiple command-line environments simultaneously.

> [!NOTE]
> Many keyboard shortcuts can be customized through Windows Terminal's **Settings** file or graphical settings interface.

> [!NOTE]
> Some shortcuts may differ if you've customized your key bindings.

> [!NOTE]
> Windows Terminal supports profiles for Command Prompt, Windows PowerShell, PowerShell 7, Azure Cloud Shell, WSL distributions, and many third-party shells.

---

# ⚙️ Requirements

| Requirement                  | Details                                                               |
| ---------------------------- | --------------------------------------------------------------------- |
| **Operating System**         | Windows 10 (version 1903 or later) or Windows 11                      |
| **Windows Terminal**         | Must be installed from the Microsoft Store or GitHub releases.        |
| **PowerShell / CMD / WSL**   | Optional, depending on which terminal profiles you use.               |
| **Administrator Privileges** | Required for administrative shells or elevated commands.              |
| **GPU Acceleration**         | Supported hardware is recommended for the best rendering performance. |

---

# 💭 Did You Know?

> 💡 **Windows Terminal can run multiple shells simultaneously.**
> You can have Command Prompt, PowerShell, PowerShell 7, WSL, and Azure Cloud Shell open in separate tabs within the same window.

---

> 💡 **Every shortcut is customizable.**
> Nearly every keyboard shortcut in Windows Terminal can be remapped, allowing you to create a workflow tailored to your preferences.

---

> 💡 **The Command Palette is inspired by Visual Studio Code.**
> Press **Ctrl + Shift + P** to quickly access terminal commands without remembering every shortcut.

---

> 💡 **Split panes can replace multiple terminal windows.**
> Instead of opening several terminal instances, use vertical and horizontal panes to monitor logs, run scripts, and execute commands side by side.

---

> 💡 **Windows Terminal is open source.**
> Microsoft develops Windows Terminal as an open-source project, allowing the community to contribute new features, improvements, and bug fixes.

---
