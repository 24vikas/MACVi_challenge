# LOOKOUT visual odometry — full development release v0.1

Published 23 September 2026. All 92 development clips: 68 training and 24 validation.

From this directory, verify the files with `sha256sum --check CHECKSUMS.sha256`.
Read LICENSE.txt (dataset: CC BY-NC 4.0), CODE_LICENSE.txt (starter: MIT), RULES.md
and QUICKSTART.md. Follow the pinned CUDA setup for DPVO inference, then run:

```bash
python starter/infer.py --dataset release_manifest.json --clips clip_000 --output runs/demo
python starter/evaluate.py --dataset release_manifest.json --clips clip_000 --predictions runs/demo
```

The videos, calibration, released timing and references are unchanged from the
maintainer's full development archive (SHA-256
41991869ed787d706f37b0bb0e9a80a1ef9b7a94db4cd85eca0f29d97b077d58).
This public package adds the corrected starter, explicit code license and release
notes, and removes internal source commentary. Public starter source: commit
fa6ea97 at https://github.com/LOOKOUT-AI/lookout-vo-challenge.

Read RELEASE_STATUS.md for validation and timing limitations. An independent GPU
baseline reproduction remains pending. The release supports local development;
online submissions, leaderboard and competition dates will follow.

Challenge page: https://macvi.org/workshop/macvi27/challenges/lookout
