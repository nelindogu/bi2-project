# BI2 Group Project

Replication of:
Pitsch, C., Brockhoff, T., Adams, J. N., Leemans, S. J. J., Celi, L. A., & van der Aalst, W. M. P. (2025). **Hypothesis Testing for Processes.** *2025 7th International Conference on Process Mining (ICPM).* https://doi.org/10.1109/ICPM66919.2025.11220677

## Status
We set up the authors' code and checked on one laptop that it runs (a quick test, not part of this repository). The replication itself has not started yet.

## Setup
The authors' code, in the versions used for the paper. `pcomp` is the method, `pcomp-experiments` contains the scripts for the paper's experiments, and `event_log_mutator` is used by those scripts. [uv](https://docs.astral.sh/uv/getting-started/installation/) is needed.

```bash
git clone https://github.com/cpitsch/pcomp
git clone https://github.com/cpitsch/pcomp-experiments
git clone https://github.com/cpitsch/event_log_mutator

cd pcomp && git checkout ICPM25 && uv sync && cd ..
cd pcomp-experiments && git checkout ICPM25 && cd ..
cd event_log_mutator && git checkout d2afb17 && cd ..
```

## Data
Road Traffic Fine Management Process log (not included in this repository):
https://data.4tu.nl/articles/dataset/Road_Traffic_Fine_Management_Process/12683249/1
