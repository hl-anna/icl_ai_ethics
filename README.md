# icl_ai_ethics

The main task of the assignment is to study model selection process (when training ML models) that takes into account accuracy and fairness metrics.
The task is to compare standard ML models versus fairness-based ML models with three model selection criteria:

*   Most accurate
*   Most fair
*   Most accurate & fair

This repository contains two colab notebooks: 

- ML_Fairness_main.ipynb - main notebook that contains code for analysing two data sets from the aif360 library, the AdultDataset and the CompasDataset.
- ML_Fairness_Cw_additional.ipynb - where fairness of models is explored when sensitive features are exculded from the data.

These can be run out of the box and each notebook has an outline for easier navigation.

Note: One of the aif360 module import fails sometimes and gives an error. If that happens, one only needs to re-run the cell (this import cell is the 4th cell in all three notebooks) and the error disappears.
