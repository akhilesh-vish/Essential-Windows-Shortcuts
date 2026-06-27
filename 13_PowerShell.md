# ⚡ PowerShell

PowerShell is Microsoft's modern command-line shell and scripting language, designed for automation, system administration, and advanced task management. Unlike the traditional Command Prompt, PowerShell works with **objects instead of plain text**, making it significantly more powerful for scripting, managing Windows, and interacting with cloud services.

Whether you're an IT professional, developer, system administrator, or simply a Windows enthusiast, mastering PowerShell shortcuts will help you work more efficiently and reduce repetitive tasks.

> [!TIP]
> PowerShell isn't just another command prompt. It's an automation platform capable of managing Windows, Active Directory, Azure, Microsoft 365, and much more.

---

# 📖 Table of Contents

* [⌨️ Keyboard Shortcuts](#️-keyboard-shortcuts)

  * Navigation
  * Editing
  * Command History
  * Auto-Completion
  * Window Management
* [⭐ Most Useful Shortcuts](#-most-useful-shortcuts)
* [💡 Productivity Tips](#-productivity-tips)
* [📝 Notes](#-notes)
* [⚙️ Requirements](#️-requirements)
* [💭 Did You Know?](#-did-you-know)

---

# ⌨️ Keyboard Shortcuts

## 🧭 Navigation

| Shortcut         | Description                                              |
| ---------------- | -------------------------------------------------------- |
| **Home**         | Move the cursor to the beginning of the current command. |
| **End**          | Move the cursor to the end of the command.               |
| **Ctrl + ← / →** | Move one word at a time.                                 |
| **Ctrl + Home**  | Scroll to the beginning of the console buffer.           |
| **Ctrl + End**   | Scroll to the end of the console buffer.                 |

---

## ✏️ Editing

| Shortcut             | Description                                                 |
| -------------------- | ----------------------------------------------------------- |
| **Ctrl + C**         | Cancel the currently running command or copy selected text. |
| **Ctrl + V**         | Paste text from the clipboard.                              |
| **Ctrl + A**         | Select all visible console output.                          |
| **Backspace**        | Delete the previous character.                              |
| **Delete**           | Delete the character under the cursor.                      |
| **Ctrl + Backspace** | Delete the previous word.                                   |
| **Ctrl + Delete**    | Delete the next word.                                       |
| **Esc**              | Clear the current command line.                             |

---

## 📜 Command History

| Shortcut     | Description                                        |
| ------------ | -------------------------------------------------- |
| **↑**        | Recall the previous command.                       |
| **↓**        | Move forward through command history.              |
| **F7**       | Display the complete command history.              |
| **F8**       | Search command history based on the current input. |
| **Alt + F7** | Clear the command history for the current session. |

---

## ⚡ Auto-Completion

| Shortcut         | Description                                                              |
| ---------------- | ------------------------------------------------------------------------ |
| **Tab**          | Auto-complete cmdlets, parameters, variables, paths, and filenames.      |
| **Shift + Tab**  | Cycle backward through available completions.                            |
| **Ctrl + Space** | Display IntelliSense suggestions (PowerShell ISE and supported editors). |

---

## 🖥️ Window Management

| Shortcut               | Description                                                                     |
| ---------------------- | ------------------------------------------------------------------------------- |
| **Alt + Enter**        | Toggle Full Screen mode (legacy support).                                       |
| **Alt + F4**           | Close the PowerShell window.                                                    |
| **Ctrl + Mouse Wheel** | Zoom the console text (supported in Windows Terminal and modern console hosts). |

---

# ⭐ Most Useful Shortcuts

If you're new to PowerShell, start by learning these shortcuts first.

| Shortcut             | Why It's Useful                                                                        |
| -------------------- | -------------------------------------------------------------------------------------- |
| **Tab**              | Auto-complete commands, paths, and parameters, saving time and reducing typing errors. |
| **↑ / ↓**            | Reuse previously executed commands instantly.                                          |
| **Ctrl + C**         | Stop a running command safely.                                                         |
| **F7**               | Display your recent command history in one place.                                      |
| **Ctrl + ← / →**     | Navigate long commands word by word.                                                   |
| **Esc**              | Clear the current command without affecting previous output.                           |
| **Ctrl + V**         | Paste complex commands or scripts directly from documentation.                         |
| **Ctrl + Backspace** | Quickly delete entire words while editing long commands.                               |

---

# 💡 Productivity Tips

* Let **Tab Completion** do the typing for you. It works with cmdlets, file paths, parameters, variables, and even module names.
* Press **F7** whenever you can't remember a command you ran earlier—it provides a searchable history of your session.
* Instead of manually typing long file paths, type the first few letters and press **Tab** until the correct folder or file appears.
* Use **Ctrl + C** to safely stop commands that are taking too long without closing the PowerShell window.
* If you're learning PowerShell, focus on understanding cmdlets and their parameters rather than memorizing every command.
* Keep your commands short and readable by using **aliases** while learning, but prefer full cmdlet names in scripts for clarity.

---

# 📝 Notes

> [!NOTE]
> PowerShell is object-oriented, meaning it passes structured objects between commands rather than plain text. This makes automation and scripting much more powerful than traditional command-line tools.

> [!NOTE]
> Some shortcuts, such as **Ctrl + Space**, are available only in PowerShell ISE or editors with IntelliSense support.

> [!NOTE]
> When PowerShell is hosted inside **Windows Terminal**, additional shortcuts become available. These are covered in the next chapter.

> [!NOTE]
> Most keyboard shortcuts work in both **Windows PowerShell 5.1** and **PowerShell 7+**, although newer versions provide improved editing through the PSReadLine module.

---

# ⚙️ Requirements

| Requirement                  | Details                                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Operating System**         | Windows 10 or Windows 11                                                                                            |
| **PowerShell Version**       | Windows PowerShell 5.1 or PowerShell 7+                                                                             |
| **PSReadLine Module**        | Installed by default on modern PowerShell versions and provides enhanced editing, history, and prediction features. |
| **Administrator Privileges** | Required for many system administration cmdlets.                                                                    |
| **Windows Terminal**         | Optional, but recommended for the best PowerShell experience.                                                       |

---

# 💭 Did You Know?

> 💡 **PowerShell is much more than a command-line interface.**
> It's a full scripting language capable of automating everything from file management to cloud administration.

---

> 💡 **The Tab key is your best friend.**
> It doesn't just complete filenames—it can auto-complete cmdlets, parameters, variables, providers, and module names, dramatically reducing typing.

---

> 💡 **PowerShell keeps getting smarter.**
> Modern versions include command prediction powered by **PSReadLine**, offering suggestions based on your command history as you type.

---

> 💡 **Many Windows administration tools are built on PowerShell.**
> Behind the scenes, applications such as Microsoft 365, Exchange, Azure, Hyper-V, and Windows Server rely heavily on PowerShell for automation and management.

---
