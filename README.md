# SpaceTech Open Mission Lab

**An open-source Arabic–English STEM mission-design platform for school students, educators, and clubs.**

SpaceTech Open Mission Lab helps learners move from a real-world problem to a structured engineering mission in three tracks:

- 🛰️ **CubeSat & Satellite Mission Design**
- 🚁 **Drone & UAV Mission Engineering**
- 🤖 **Robotics & Smart Systems**

The repository combines a working browser-based mission builder, three 8-session curricula, student project briefs, assessment rubrics, and launch documentation.

## Live MVP

Open `web/index.html` in any modern browser. No installation or internet connection is required.

### Features

- Arabic and English interface
- Three mission-design tracks
- Guided mission builder
- Track-specific project idea library
- Automatic mission report generation
- Export to Markdown
- Print-friendly project report
- Local browser autosave
- Teacher-ready curriculum and rubrics

## Repository Structure

```text
spacetech-open-mission-lab/
├── web/                    # Working static web application
├── curricula/              # 8-session course packs and rubrics
│   ├── cubesat/
│   ├── drones/
│   └── robotics/
├── projects/               # 15 ready-to-use project briefs
│   ├── cubesat/
│   ├── drones/
│   └── robotics/
├── docs/                   # Architecture, feature plan, launch roadmap
├── LICENSE                 # MIT License for software
├── LICENSE-EDUCATIONAL     # CC BY 4.0 notice for educational content
├── CONTRIBUTING.md
└── CODE_OF_CONDUCT.md
```

## Quick Start

### Option 1 — Open locally

1. Download or clone the repository.
2. Open `web/index.html`.
3. Choose a track and start building a mission.

### Option 2 — Run a local server

```bash
cd web
python -m http.server 8000
```

Then visit `http://localhost:8000`.

### Option 3 — Publish with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Set the folder to `/web`.

## Educational Use

Teachers can run each track as an 8-session program. Every curriculum includes:

- Learning outcomes
- Session flow
- Student deliverables
- Project milestones
- Assessment checkpoints
- Final presentation rubric

## Licensing

- Source code: **MIT License**
- Curricula, worksheets, project briefs, and educational text: **Creative Commons Attribution 4.0 International (CC BY 4.0)**

Attribution suggestion:

> Adapted from SpaceTech Open Mission Lab by SpaceTech Academy.

## Version 1.0 Scope

- Working bilingual mission builder
- 3 complete curriculum architectures
- 15 project briefs
- 3 final project rubrics
- 30-day public launch roadmap
- GitHub-ready documentation

## Planned Next Releases

- PDF report export
- Teacher dashboard
- Student accounts and team collaboration
- Orbit and power-budget calculators
- Arduino code examples
- Public community project gallery

## Maintainer

**SpaceTech Academy**  
Open knowledge. Real engineering. Opportunities for everyone.
