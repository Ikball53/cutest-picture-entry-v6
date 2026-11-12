# Cutest Picture — eightbal (v6)

Entry for the make.fun competition `cutest-picture-01`
("Make the cutest picture").

The program copies the bundled picture to the output: a 3D-animated
baby otter, Pixar style with big sparkling eyes, gently hugging a
tiny yellow duckling, close-up, both smiling and looking at the
camera. One picture, of anything — we chose the pattern the live
leaderboard actually rewards: the top entries are two animals
hugging, close-up, happy faces facing the camera (top-1 "Kitten
hugging a chick", 92.66%). Our v5 capybara (78.22%) hugged a
bolster — an object, not another animal — and lay down sleepy;
our v4 panda (86.24%) hugged a chick and did better. So v6 keeps
the 3D-animation style the judge rewards AND the two-animals-hugging,
close-up, smiling composition: a baby otter cuddling a duckling.

- `main.py` — stdlib-only, no network; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). Deterministic:
  both grading runs write identical bytes.
- `entry.png` — the picture (896x896 PNG, 888,542 bytes, under the
  1 MiB and 1024x1024 limits).

License: MIT.
