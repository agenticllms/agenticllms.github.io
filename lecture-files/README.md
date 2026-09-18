# Agentic AI — Lecture Files

Notebooks and code from class, one folder per session (W02b, W03a, ...).

This folder lives inside the course repository. Clone the repository into your
course project folder and name it `course-files`:

```
your-course-folder/
├── .venv/            your environment (created once, see the setup guide)
├── .env              your API keys (copy from example.env)
├── course-files/     the course repo — class files are in lecture-files/ inside it
│   └── lecture-files/
│       └── W02b/     one folder per class day
└── W02b/             your working copy of a day's files
```

Setup instructions: see the Week 2b setup guide on the course site.

To get each day's files, pull and then work in a copy:

```bash
cd course-files
git pull
cd ..
cp -r course-files/lecture-files/W03a W03a   # then open the copy, not the original
```

Treat `course-files` as read-only. Running a notebook saves outputs into it,
which counts as a local edit and will block a future pull. If that happens:
`git restore .` from inside course-files, then pull again.
