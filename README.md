# FocusMask

A privacy and focus veil for your screen: it dims or blurs everything except the spot where you are working.

- The spotlight follows the mouse, the text caret, or both
- Ellipse, rectangle or reading-band spotlight, sized by dragging
- Fixed regions that always stay covered (chats, email, sensitive data)
- One shortcut to cover the whole screen, and optional cover when you step away
- Profiles to save and recall a whole setup
- Optional floating on/off button, tray icon, customizable global shortcuts
- English and Arabic

## Download

Get the newest version from the **[latest release](https://github.com/aeghub/focusmask-releases/releases/latest)**.

| System | File |
| --- | --- |
| Windows 10/11, installer | `FocusMask-<version>-windows-x64-setup.exe` |
| Windows 10/11, portable (no install) | `FocusMask-<version>-windows-x64-portable.zip` |
| macOS 11 or later, Apple silicon and Intel | `FocusMask-<version>-macos-universal.dmg` |
| Linux, experimental | `.AppImage` or `.deb` |

Installed copies check for new versions and update themselves from **Settings → General → Updates**. The portable copy tells you when a new version is out and opens this page.

### Notes

- **Windows**: SmartScreen may warn about an unrecognized app the first time. Choose *More info → Run anyway*.
- **Windows portable**: unzip anywhere and run `FocusMask.exe`. Settings are kept in the same folder.
- **macOS**: the app is not notarized by Apple. After copying it to Applications, right-click it and choose *Open* the first time. Following the text caret needs the Accessibility permission.
- **Linux**: experimental and untested. X11 only, no blur and no text-caret tracking.

## Default shortcuts

| Shortcut | Action |
| --- | --- |
| `Alt+Shift+F` | Turn the veil on / off |
| `Alt+Shift+C` | Cover everything |
| `Alt+Shift+P` | Next profile |
| `Alt+Shift+W` | Show / hide the floating button |
| `Alt+Shift+=` / `Alt+Shift+-` | Bigger / smaller spotlight |
| `Alt+Shift+M` | Cycle follow mode (mouse, caret, auto) |
| `Alt+Shift+R` | Draw fixed regions |

All of them can be changed in **Settings → Shortcuts**. On macOS, Alt is ⌥ Option.
