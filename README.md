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

[**View Tasks**](tasks/) · [**Submit Update**](updates/) · [**See Contributions**](https://github.com/justlab-ai/weekly-tasks/graphs/contributors)

</div>

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

[Commit History](https://github.com/justlab-ai/weekly-tasks/commits/main) · [Contributors Graph](https://github.com/justlab-ai/weekly-tasks/graphs/contributors)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%">

</div>
