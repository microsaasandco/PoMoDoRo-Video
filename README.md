## Main Markdown Files

- [README.md](README.md)
- [AI_CONTEXT.md](AI_CONTEXT.md)
- [PRIVACY.md](PRIVACY.md)
- [STORE_DESCRIPTION.md](STORE_DESCRIPTION.md)
- [SUBMISSION_CHECKLIST.md](SUBMISSION_CHECKLIST.md)

# PoMoDoRo – Chrome Extension

MicroSaaS PoMoDoRo is a professional, privacy-first Pomodoro timer extension for Chrome, designed for makers, freelancers, and developers.

## Features
- **Pomodoro Technique**: Focus/break cycles with fully customizable durations
- **Modern UI**: Compact, dark, and accessible webview (tab-based UI)
- **Notifications**: Optional desktop notifications and in-app toasts at session transitions
- **Local Storage**: All data stays on your device (no analytics, no tracking)
- **Settings**: Auto-start, durations, notifications, chime, and more
- **About Page**: Explains usage, benefits, and Pomodoro history

## Usage
1. Click the extension icon to open the timer in a new tab
2. Set your focus and break durations in the settings
3. Start your session – notifications and chime will alert you at each step
4. Use the About link for a quick guide and Pomodoro history

## Tech Stack
- Chrome Extension Manifest V3
- Vanilla JavaScript (ES modules)
- HTML5 & CSS (dark mode, responsive)
- Service Worker for background logic (alarms, tab opening)

## Privacy
No data is sent to any server. All settings and session data are stored locally in your browser. See [PRIVACY.md](PRIVACY.md).

## Chrome Web Store Submission
- Fully compliant with Chrome Web Store quality and privacy requirements
- See [SUBMISSION_CHECKLIST.md](SUBMISSION_CHECKLIST.md)
- Store description: [STORE_DESCRIPTION.md](STORE_DESCRIPTION.md)

## Installation (Development)
1. Download or clone this repository
2. Go to `chrome://extensions` in your browser
3. Enable "Developer mode"
4. Click "Load unpacked" and select the project folder

## Codebase Structure
- `manifest.json`: Extension manifest (MV3)
- `webview/`: UI, logic, and styles for the webview/tab
- `background/`: Service worker
- `webview/js/`: Modular JS (constants, storage, timer, ui, popup, help)

## License
MIT

---

Made with ❤️ by MicroSaaS & Co.
