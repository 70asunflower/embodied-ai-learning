# Embodied AI Learning Journey 🤖🦾

> A collection of resources, notes, code, and project explorations in Embodied AI — from VLA models to sim-to-real robotics.

---

## Wiki Navigation

<details open>
<summary><b>📚 Resources</b></summary>

<details>
<summary>1-Papers</summary>

_Empty — add your first paper!_

</details>

<details>
<summary>2-Frameworks-Tools</summary>

_Empty — add your first framework!_

</details>

<details>
<summary>3-Datasets</summary>

_Empty — add your first dataset!_

</details>

<details open>
<summary>4-Tutorials-Courses</summary>

- [台大机器人学之运动学——林沛群](0-Resources/4-Tutorials-Courses/ntu-robotics-kinematics-lin-peiqun.md) — 台大专项课程，B站搬运+课件，含正逆运动学与 Jacobian
- [📄 Tutorials Index](0-Resources/4-Tutorials-Courses/README.md)

</details>

<details>
<summary>5-Projects-OpenSource</summary>

_Empty — add your first project!_

</details>

[📋 Full Resource Index](0-Resources/0-Index.md)

</details>

<details open>
<summary><b>📝 Personal Notes</b></summary>

<details open>
<summary>1-Foundations</summary>

- [台大机器人学 Lecture 1: 道沦](1-Notes/1-Foundations/ntu-robotics-kinematics-lecture1.pdf)
- [台大机器人学 Lecture 2: 旋转矩阵与坐标系变换](1-Notes/1-Foundations/ntu-robotics-kinematics-lecture2.pdf)

</details>

<details>
<summary>2-Models</summary>

_Empty — add your first model note!_

</details>

<details>
<summary>3-Simulation</summary>

_Empty — add your first simulation note!_

</details>

[📋 Note Template](1-Notes/0-Template.md)

</details>

<details>
<summary><b>💻 Code & Projects</b></summary>

<details>
<summary><a href="2-Code/README.md">Code Examples</a></summary>

<details>
<summary>ros2-examples</summary>

_Empty — add a ROS2 example!_

</details>

<details>
<summary>mujoco-environments</summary>

_Empty — add a MuJoCo environment!_

</details>

<details>
<summary>vla-inference</summary>

_Empty — add a VLA inference script!_

</details>

</details>

<details open>
<summary><a href="3-Projects/README.md">Projects</a></summary>

<details>
<summary>pick-and-place</summary>

_Empty — start the pick-and-place project!_

</details>

<details>
<summary>navigation</summary>

_Empty — start the navigation project!_

</details>

</details>

</details>

---

## Directory Structure

```
embodied-ai-learning/
├── 0-Resources/              # External resources
│   ├── 0-Index.md            # Full resource index
│   ├── 1-Papers/             # Important papers
│   ├── 2-Frameworks-Tools/   # Frameworks & tools (Isaac Sim, LeRobot, ManiSkill, etc.)
│   ├── 3-Datasets/           # Datasets (Open X-Embodiment, Bridge, etc.)
│   ├── 4-Tutorials-Courses/  # Tutorials, blogs, courses
│   └── 5-Projects-OpenSource/# Open-source projects
├── 1-Notes/                  # Personal study notes
│   ├── 1-Foundations/        # Core concepts (RL, visuomotor, calibration, etc.)
│   ├── 2-Models/             # Model-specific notes (VLA, ACT, Diffusion Policy, etc.)
│   └── 3-Simulation/         # Simulation notes (Isaac Sim, MuJoCo, SAPIEN, etc.)
├── 2-Code/                   # Runnable code
│   ├── ros2-examples/        # ROS2 integration examples
│   ├── mujoco-environments/  # Custom MuJoCo environments
│   └── vla-inference/        # VLA model inference scripts
├── 3-Projects/               # Comprehensive projects
│   ├── pick-and-place/       # Pick-and-place task
│   └── navigation/           # Autonomous navigation task
└── README.md
```

## How to Update

### Adding a New Resource (0-Resources/)

1. Create a `.md` file in the correct subfolder (e.g. `0-Resources/2-Frameworks-Tools/lerobot.md`)
2. Start with this frontmatter:
   ```markdown
   ---
   source: <original URL>
   date: YYYY-MM-DD
   tags: [tag1, tag2]
   ---
   ```
3. Write the content: summary, key points, or full notes with source attribution
4. End with: `_Last updated: YYYY-MM-DD_`
5. Add it to the folder's `README.md` index
6. Add it to the wiki nav in this file under `<details>`
7. Add it to `0-Resources/0-Index.md`

### Adding a New Note (1-Notes/)

1. Create a `.md` file in the correct subfolder (e.g. `1-Notes/2-Models/vla-october.md`)
2. Start with the same frontmatter as above
3. Write your personal understanding, code experiments, gotchas
4. End with: `_Last updated: YYYY-MM-DD_`
5. Add the link to the folder's `README.md` index
6. Add the link to the wiki nav in this file

### Adding to Code Examples (2-Code/)

1. Create a subfolder: `2-Code/<project-name>/`
2. Include: `main.py`, `requirements.txt`, `README.md`
3. Add it to `2-Code/README.md`

### Key Rules

- **File names**: lowercase, hyphen-separated (e.g. `diffusion-policy.md`)
- **Wiki nav**: every new file must be linked in this README
- **Resource Index**: `0-Index.md` mirrors all resources — keep it in sync
- **Always include `Last updated`**: every resource/note file ends with `_Last updated: YYYY-MM-DD_`

## Changelog

| Date       | Content                                       |
|------------|-----------------------------------------------|
| 2026-03-31 | Repository init, directory structure, wiki nav|
| 2026-03-31 | Added note template                           |
