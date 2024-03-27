# Tracking small molecules ML methods on popular benchmarks
A repo containing raw data for small molecules benchmarks and ML model performance for popular benchmarks.

Data was collected manually combing through the literature citing the source of the benchmark or the first significant paper that suggested it as a benchmark, using Scopus (scopus.com). For every calendar year, I would take the top 10 cited papers that had results for the benchmark to reduce the amount of papers I had to review. 

Classification of ML model type (e.g. graph neural network (GNN), transformer, convolutional neural network (CNN)) was done by me but can be redone by reviewing the literature and their links.

The following benchmarks have had results collected for:

| Benchmark Name         | Task                                             | Metric             | DOI                                            |
|------------------------|--------------------------------------------------|--------------------|------------------------------------------------|
| CASF 2016              | Binding affinity prediction for protein-ligand complexes | Pearson's R        | [URL](https://doi.org/10.1021/acs.jcim.8b00545) |
| USPTO-50k              | Single-step retrosynthesis prediction           | Top-1 Accuracy (%) | [URL](https://doi.org/10.1021/acscentsci.7b00355) |
| HIV Protease Activity  | Activity classification for single targets (QSAR) | AUROC              | [URL](https://doi.org/10.1039/C7SC02664A)        |


All data is provided in the [data](https://github.com/guydurant/tracking_small_molecules_benchmarks/tree/main/data) folder.
