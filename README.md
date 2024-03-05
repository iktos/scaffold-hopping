# Large-step Scaffold Hopping Benchmark

This repository gathers the datasets from the article [Exploring isofunctional molecules: Design of a benchmark and evaluation of prediction performance](https://doi.org/10.1002/minf.202200216) by Pinel & al.


All 144 large-step scaffold hopping examples are displayed in the file `scaffold_hopping_cases.csv`.

The detailed rankings for each case are in the files named `ranking_{ID}.csv` where ID is the ID of a specific scaffold hopping case.
In those files, experiments are conducted by taking either one of the molecules of the pair as known active (i.e., as reference), so there are two columns per method evaluated: one taking as reference the ligand 0 (thus having `|ref_0` in the column name), and one taking as reference the ligand 1 (thus having `|ref_1` in the column name).
