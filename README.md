# Deepak Ezhumalai

Independent ML researcher. I pre-register experiments, publish code and raw results, and report what doesn't work as well as what does.

## Current work

**[VersionOutcomes](https://github.com/DeepakEz/versionoutcomes)**: can a model predict what a real code change does to a concrete call?
- The data: 1,973 executed before/after outcome pairs from 16 Python libraries.
- The finding: Gemma 4 12B spotted 31 of 42 real behaviour changes with two false alarms, but predicted the new result in only 19.

**[Cross-scroll ink detection](https://github.com/ScrollPrize/villa/pull/2512)** for the Vesuvius Challenge (reading the Herculaneum scrolls):
- A scan-type conversion raises ROC-AUC on an unseen scroll by +0.024 across three seeds.
- Self-training lifts never-adapted regions by +0.018.
- The code is under review in the challenge codebase, and the [checkpoints are on Hugging Face](https://huggingface.co/TequilaYuen/vesuvius-ink-9um-cross-scroll).

**[Luck, not efficiency](https://github.com/DeepakEz/arc-agi-3-luck-not-efficiency)**: ARC Prize 2026 paper on where LLM agents lose points on ARC-AGI-3.
- Agents rarely waste moves. They fail to work out games, and whether they do is largely luck.
- A pre-registered 12-run test of a design-principles prompt was null: +2.5 points, 95% CI −3.6 to +8.7.

**[Dandelion](https://github.com/DeepakEz/dandelion)**: a pre-registered continual-learning research programme on a localized "petal" unit.
- It beat Gaussian RBF units by +2.04 balanced-accuracy points on 17 untouched datasets, under one shared training recipe.
- It showed no established advantage over tanh units.

Kaggle: [kradle2grave](https://www.kaggle.com/kradle2grave) · Hugging Face: [TequilaYuen](https://huggingface.co/TequilaYuen)

<sub>Much of the implementation is done with AI coding agents under my direction; design, decisions and claims are mine.</sub>
