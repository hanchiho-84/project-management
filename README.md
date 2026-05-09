# GanttPro — Project Management

A single-file, browser-based project management app with an interactive Gantt chart. No installation or internet connection required — just open `gantt.html` in any modern browser.

Supports **English and Traditional Chinese (繁體中文)** — toggle with the EN / 中文 button in the toolbar.

---

## Getting Started

1. Download `gantt.html`
2. Open it in Chrome, Edge, or Firefox
3. Start adding goals, projects, and tasks

No sign-up. No server. All data is saved locally in your browser.

---

## Features

- **Gantt chart** with draggable bars for moving and resizing tasks
- **Task dependencies** — link tasks by dragging from the right dot of one bar to another
- **Goals, Projects, and Tasks** — three levels of hierarchy to structure your work
- **Progress tracking** — set completion percentage per task; parent projects roll up automatically
- **Stats dashboard** — overview of active projects, completed tasks, overdue items, and team workload
- **Overdue alerts** — dedicated page listing all late tasks with days overdue
- **Team management** — add team members and assign tasks to them
- **Bilingual UI** — switch between English and Traditional Chinese at any time
- **Color coding** — assign colors to projects for visual clarity
- **Timeline views** — switch between Day, Week, Month, and Quarter views

---

## How to Use

### Adding Items

| Button | Shortcut | What it creates |
|--------|----------|-----------------|
| + Add Goal | `G` | A high-level objective (purple) |
| + Add Project | `P` | A project under a goal |
| + Add Task | `N` | A task under a project |

Click any button in the toolbar or press the keyboard shortcut. Fill in the name, dates, assignee, and completion percentage in the modal that appears.

### Gantt Chart

- **Move a task** — drag its bar left or right
- **Resize a task** — drag the right edge of the bar
- **Link tasks** — drag from the circular dot on the right end of a bar to another bar to create a dependency arrow
- **Edit a task** — click the pencil icon on the task row, or double-click the bar
- **Delete a task** — click the trash icon on the task row, or select it and press `Del`
- **Reorder tasks** — drag a row in the task list up or down
- **Scroll to today** — click the **Today** button in the toolbar

### Timeline Views

Use the **Day / Week / Month / Quarter** selector in the toolbar to zoom in or out on the timeline.

### Stats Page

Click the chart icon in the left sidebar to see:
- Summary cards (total projects, tasks, completed, overdue, ahead of schedule)
- Per-person workload breakdown
- Project progress bars

### Overdue Page

Click the alert icon in the left sidebar to see all tasks past their end date, sorted by how many days late they are.

### Team Page

Click the people icon in the left sidebar to manage team members. Add a name, email, and role. Members appear in the assignee dropdown when creating tasks.

### Language Toggle

Click **EN** in the top-right of the toolbar to switch to English. Click **中文** to switch back to Traditional Chinese. Your project data is unaffected.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `N` | Add new task |
| `P` | Add new project |
| `G` | Add new goal |
| `Del` | Delete selected task |

---

## Data & Privacy

All data is stored in your browser's **localStorage** — nothing is sent to any server. Clearing your browser data will erase your projects, so export or back up your data if needed.

---

## Requirements

Any modern browser — Chrome, Edge, Firefox, or Safari. No internet connection needed after the file is downloaded.
