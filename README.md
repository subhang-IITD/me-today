# 📅 me-today

A beautiful Claude-style terminal dashboard that reads your `.ics` calendar file and displays today's schedule alongside a persistent to-do list.

## ✨ Features

- 🕐 **Live clock** with contextual greetings (morning/afternoon/evening/night)
- 📅 **ICS calendar parsing** — import your schedule from macOS Calendar, Google Calendar, etc.
- ✅ **Persistent to-do list** — tasks saved locally as JSON
- 📊 **Progress bar** — visual task completion tracking
- 🎨 **Claude-style UI** — minimal, elegant, color-coded terminal interface
- ⚡ **Instant setup** — just point to your `.ics` file and go

## 🚀 Quick Start

Run it instantly with npx (no install needed):

```bash
npx @subhang.exe/me-today
```

Or install globally:

```bash
npm install -g @subhang.exe/me-today
me-today
```

## 📸 Demo

<!-- Paste your demo video URL here -->

## 🛠️ Commands

| Command | Description |
|---------|-------------|
| `add <task>` | Add a new task |
| `done <number>` | Mark a task as complete |
| `undo <number>` | Unmark a completed task |
| `remove <number>` | Delete a task |
| `clear` | Remove all tasks |
| `setup` | Add or change your `.ics` calendar file |
| `quit` / `exit` | Exit the app |

## 📅 Calendar Setup

1. Export your calendar as an `.ics` file:
   - **macOS Calendar**: File → Export → Export...
   - **Google Calendar**: Settings → Import & Export → Export
   - **Outlook**: File → Open & Export → Import/Export

2. Run `me-today` and it'll ask for the path on first launch
3. Type `setup` anytime to change the calendar file

## 🏗️ Built With

- [Ink](https://github.com/vadimdemedes/ink) — React for the terminal
- [node-ical](https://github.com/jens-maus/node-ical) — ICS calendar parsing
- [chalk](https://github.com/chalk/chalk) — Terminal styling

## 📦 NPM

[![npm version](https://img.shields.io/npm/v/@subhang.exe/me-today)](https://www.npmjs.com/package/@subhang.exe/me-today)

## 📄 License

MIT © [subhang-IITD](https://github.com/subhang-IITD)
