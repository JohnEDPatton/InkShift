# Hub — Your Personal Productivity System

A private, offline-first productivity app that lives in your browser. No account. No subscription. No cloud. Your data stays on your device.

---

## What It Does

Hub connects your notes, tasks, and people in one place — so nothing slips through. You can type notes, scan handwritten paper notes with your phone camera, and ask AI questions across all your data.

---

## Getting Started

### First-Time Setup

1. Open the app in Safari on your iPhone
2. Tap **Share → Add to Home Screen → Add** to install it like a native app
3. Go to **Settings → AI Assistant** and add your Anthropic API key to unlock AI chat and paper scanning
   - Get a free key at [console.anthropic.com](https://console.anthropic.com)

---

## The Six Screens

### Today
Your home base. Everything you need to start the day.

- **Quick capture bar** at the top — type a task or note and tap +
- **Top 3** — the three tasks you're committing to today. Tap "Pick / Change" to set them. Unfinished tasks carry forward automatically each morning.
- **Needs Attention** — any overdue tasks surface here automatically
- **7-day chart** — shows how many tasks you've completed each day

### Notebook
Your running journal of notes and meeting records.

- Tap the **scan icon** (top right) to photograph handwritten notes — AI will transcribe them, extract tasks, detect people, and flag anything urgent
- Tap **New Note** to type an entry directly
- Filter by Work, Personal, or Project using the pills at the top
- Notes are grouped by month, newest first
- Tap any note to read it in full, add tasks to it, or edit it

### Tasks
Your full task list across everything.

- Filter by Starred, Overdue, High Priority, tag, or person
- Tap the **checkbox** to complete a task — it auto-archives after 24 hours
- Tap the **star** to mark it as a Top 3 candidate
- Tap any task to edit it — add notes, a due date, a person, or change priority
- Archived tasks are still visible under the **Archived** filter

### People
Cards for anyone you work with or mention in notes.

- Each person shows their linked tasks and notes in one place
- People are created automatically when you mention names in notes or scans
- Tap any person to see everything connected to them
- Add tasks directly from a person's card

### Ask AI
Chat with your data using plain language.

- "What do I have overdue?"
- "What did I commit to with [name]?"
- "Summarize my Project notes from last month"
- "What's on my plate this week?"

Requires an Anthropic API key (set in Settings). Your key is stored only on this device.

### Settings
- **API Key** — add or update your Anthropic key
- **Export** — download a JSON backup of all your data
- **Import** — restore or merge data from a backup file (useful for moving data between phone and laptop)
- **Clear Archived** — permanently delete archived items to free space
- **Add to Home Screen** — step-by-step guide for iPhone
- **Reset** — wipe everything and start fresh

---

## Tags

Every note and task has one of three tags:

| Tag | Use for |
|-----|---------|
| **Work** | Professional tasks and notes |
| **Personal** | Personal tasks and notes |
| **Project** | Project-specific items |

Filter by tag on any screen using the pills at the top.

---

## Scanning Paper Notes

1. Go to **Notebook** and tap the scan icon in the top right
2. Your iPhone camera opens — take one or more photos of your notes
3. AI processes the images and returns:
   - Cleaned transcription of your notes
   - Extracted tasks (you choose which to keep)
   - People detected by name (you confirm)
   - Urgent items flagged in red
   - Uncertain words highlighted in amber for your review
4. Edit anything on the review screen, then tap **Save to Notebook**

The note saves to your Notebook and all extracted tasks go into your Tasks list automatically.

---

## Using Phone and Laptop Together

Data is stored per device in your browser. To move data between your iPhone and laptop:

1. On the source device: **Settings → Export** — downloads a JSON file
2. On the destination device: **Settings → Import** — select the file
3. Import merges the data — it won't create duplicates

---

## Privacy

- All data is stored in your browser's IndexedDB — it never leaves your device
- Your API key is stored locally and only sent to Anthropic's API when you use AI features
- No analytics, no tracking, no account required
- The app code is hosted on Netlify — your data is not

---

## Tips

- Use **Quick Capture** on the Today screen for the fastest way to add a task
- Star tasks throughout the week, then use **Pick / Change** each morning to commit to your Top 3
- After a meeting, scan your notes the same day — the AI is better with fresh context
- Use the **Ask AI** screen at end of week to review commitments: *"What did I say I'd do for [name] this week?"*
- Export a backup once a week if you're using the app heavily
