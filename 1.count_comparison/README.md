## General remarks
Scripts in this directory have been used to check the ATAC-seq peaks from
the 8 stages of iPSC differentiation.
This directory is not essential for the next steps. It provides a few simple
preliminary scripts to count and visually compare the different filtering
methods available in the Kundaje Pipeline (applied to the same biological data).
These are:
- The original output of the pipeline.
- 1CPM filtering.
- And conservative filtering.

After assessing the test accuracies in the next directory (training), a single
best model was chosen. The best model was trained on the 1CPM dataset.