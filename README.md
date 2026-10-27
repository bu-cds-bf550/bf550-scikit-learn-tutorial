# BF550 · scikit-learn tutorial

One notebook, `scikit-learn-tutorial.ipynb`, for the lab block of Wed Oct 28. It shows how a
scikit-learn model is an object, and what `.fit`, `.predict`, `.score`, a splitter and
`cross_val_score` do, on the unit 7 lab's ten isolates. PS8 and every unit from 8 on use these
calls. You work through it during lab time, with instructors and TAs in the room. Nothing here
is submitted and nothing here is graded.

## Before you open it

scikit-learn is not yet in the `bf550` environment. Install it once, from a terminal where your
environment lives:

```bash
conda install -n bf550 -c conda-forge scikit-learn
```

Then open the notebook in VS Code and pick the `bf550` kernel, the environment your problem
sets ship. There is no second environment.

## Self-checks

The notebook carries its own self-checks. They report and never grade: ⬜ not attempted, ❌ not
passing yet with a hint, ✅ passing. Run a check as often as you like. It only reads your work.

## Break it

This notebook is for changing. Move a line, predict what happens, run it, find out whether you
were right. Every cell is editable on purpose. If you wreck one beyond repair,
`git checkout scikit-learn-tutorial.ipynb` puts it back the way it shipped. Commit and push
whenever you like; this repository is yours.

Everything else about the course, including the schedule and the textbook, is at
[bu-cds-bf550.github.io](https://bu-cds-bf550.github.io).
