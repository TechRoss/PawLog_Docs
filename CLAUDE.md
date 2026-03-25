# PawLog_Docs — Claude Code Context

## Repository Purpose
This repository contains the user-facing help documentation for the PawLog app.
It will be published as a GitHub Wiki on the PawLog_Docs repository.

## Related Repository
The main PawLog app source code lives at: `D:\Dev\PawLog`

## Structure
Each `.md` file is a separate wiki page. File names use hyphens and match the wiki page titles.

| File | Topic |
|---|---|
| `Home.md` | Landing page — app overview and quick links |
| `Getting-Started.md` | First launch and initial setup |
| `Managing-Your-Pets.md` | Add, edit, delete pets and profile photos |
| `Home-Screen.md` | Home tab layout, weather safety, emergency button |
| `Routine-Tab.md` | Daily task list, completing, skipping, streaks |
| `Managing-Tasks.md` | Add/edit/delete/reorder tasks, walk tracking toggle |
| `Health-Tab.md` | Health hub overview, Due Today section |
| `Medications.md` | Adding meds, split doses, stock tracking |
| `Weight-Tracking.md` | Logging weight, kg/lbs toggle, history chart |
| `Vet-Visits.md` | Recording visits, all fields, detail view |
| `Walk-Tracking.md` | Enabling, starting, multi-pet, ending, GPS |
| `History-Tab.md` | Awards and Walks sub-tabs |
| `Achievements-and-Streaks.md` | How streaks work, achievements table |
| `Emergency-Features.md` | Emergency button, vet screen, info card |
| `Emergency-Contacts.md` | Adding, calling, navigating, editing contacts |
| `Notifications.md` | Setup, reminders, medication alerts, Android permission |
| `Holiday-Mode.md` | Date range, what it does, streak protection |
| `Backup-and-Restore.md` | Export, what's included, restore warning |
| `Settings-Overview.md` | More tab overview |
| `Tips-and-Tricks.md` | Shortcuts and useful suggestions |
| `_Sidebar.md` | GitHub wiki sidebar navigation |

## Screenshot Placeholders
Every page contains `📷` placeholders marking where screenshots should be inserted.
Screenshots have not yet been added — this is still outstanding.

**TODO: Add screenshots**
- Go through each `.md` file and find every `📷 *Screenshot: ...*` placeholder
- Take the described screenshot on an Android device or emulator
- Insert the image into the markdown using: `![description](images/filename.png)`
- Store images in an `images/` subfolder

## Publishing to GitHub Wiki
These files are intended to be pushed to the **Wiki tab** of the PawLog_Docs GitHub repo,
not the main repo file browser. See instructions below.

**TODO: Publish to GitHub Wiki** — not yet done, waiting for screenshots first.

Steps when ready:
1. Enable the Wiki on the GitHub repo (Settings → Features → Wiki)
2. Create the first page manually on GitHub to initialise the wiki repo
3. Clone the wiki repo: `git clone https://github.com/TechRoss/PawLog_Docs.wiki.git`
4. Copy all `.md` files from this folder into the cloned wiki repo
5. Commit and push

## Style Guide
Matches the main PawLog app:
- Warm, friendly, non-technical tone — written for pet owners
- Bold for UI element names: **Save**, **Routine** tab
- Numbered lists for step-by-step instructions
- Bullet lists for feature descriptions
- Example pet: Rigby (Cavapoo)
