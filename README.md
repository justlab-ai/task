<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Weekly%20Tasks&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=JustLab%20AI%20Team%20Progress%20Tracker&descSize=18&descAlignY=52">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Weekly%20Tasks&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=JustLab%20AI%20Team%20Progress%20Tracker&descSize=18&descAlignY=52">
  <img alt="Header" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Weekly%20Tasks&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=JustLab%20AI%20Team%20Progress%20Tracker&descSize=18&descAlignY=52" width="100%">
</picture>

<div align="center">

[![Contributors](https://img.shields.io/github/contributors/justlab-ai/weekly-tasks?style=for-the-badge&color=blue)](https://github.com/justlab-ai/weekly-tasks/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/justlab-ai/weekly-tasks?style=for-the-badge&color=green)](https://github.com/justlab-ai/weekly-tasks/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/justlab-ai/weekly-tasks?style=for-the-badge&color=orange)](https://github.com/justlab-ai/weekly-tasks)

</div>

---

<div align="center">

### Quick Actions

<a href="tasks/">
  <img src="https://img.shields.io/badge/VIEW_TASKS-📋_See_Assignments-blue?style=for-the-badge&logoColor=white" alt="View Tasks">
</a>
&nbsp;&nbsp;
<a href="updates/">
  <img src="https://img.shields.io/badge/SUBMIT_UPDATE-✏️_Add_Progress-green?style=for-the-badge&logoColor=white" alt="Submit Update">
</a>
&nbsp;&nbsp;
<a href="templates/">
  <img src="https://img.shields.io/badge/TEMPLATES-📄_Get_Started-orange?style=for-the-badge&logoColor=white" alt="Templates">
</a>

</div>

---

## Quick Links

| Resource | Description | Link |
|:---------|:------------|:----:|
| **Current Tasks** | View this week's task assignments | [tasks/](tasks/) |
| **Submit Updates** | Add your weekly progress | [updates/](updates/) |
| **Task Template** | Template for creating new tasks | [task-template.md](templates/task-template.md) |
| **Update Template** | Template for member updates | [update-template.md](templates/update-template.md) |
| **Contributors** | See team contribution graph | [View](https://github.com/justlab-ai/weekly-tasks/graphs/contributors) |
| **Commit History** | Track all changes | [View](https://github.com/justlab-ai/weekly-tasks/commits/main) |

---

## How It Works

<details>
<summary><b>For Task Assigners</b></summary>

1. Create a new folder: `tasks/YYYY-WXX/` (e.g., `tasks/2025-W49/`)
2. Copy `templates/task-template.md` to `tasks/YYYY-WXX/tasks.md`
3. Fill in tasks and assignees

> **Tip:** Use `@username` to mention team members in task descriptions

</details>

<details>
<summary><b>For Team Members</b></summary>

**First time setup:**
```bash
git clone https://github.com/justlab-ai/weekly-tasks.git
```

**Weekly workflow:**
```bash
# 1. Get latest changes
git pull

# 2. Create your update file
# Location: updates/YYYY-WXX/[your-name].md

# 3. Submit your update
git add .
git commit -m "Update: [your-name] Week XX"
git push
```

> **Tip:** Check the [template](templates/update-template.md) for the update format

</details>

<details>
<summary><b>Folder Structure</b></summary>

```
weekly-tasks/
├── tasks/           # Weekly task assignments
│   └── YYYY-WXX/
│       └── tasks.md
├── updates/         # Team member progress
│   └── YYYY-WXX/
│       └── [name].md
└── templates/       # Templates
```

</details>

---

## Team

| Name | GitHub | Role |
|:-----|:-------|:-----|
| TBD  | @username | Role |

---

<div align="center">

**All contributions are transparent**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%">

</div>
