# Source and experiment provenance

The CS 1998 extension is by Anant Gupta. It builds on the collaborative VLA project at https://github.com/mzkaell/vla-where-does-language-die and the working fork https://github.com/agupt0318/vla-where-does-language-die, starting from commit 6a1eceebc19842dee2d16a88083a986f22a0216a. Existing source authorship and comments are retained.

The course contribution compares the same destination probe predictions with named and motion-derived labels, evaluates held-out episodes, and adds shuffled-label and majority-motion controls. The `analysis_seed*.json` files are the canonical course analyses. `metrics.json` preserves the original inference runner's separate analysis and split.

Raw demonstrations and model weights are downloaded from their cited sources and are not redistributed. The release archive includes the measured feature cache and per-trial predictions for reanalysis. The original project manuscript is included only as referenced background; its experiments are distinct from the course extension.
