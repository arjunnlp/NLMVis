# NLMVis
A tool to visualize language models; preleminary experiments so far.

### Usage

Prepare the data using notebooks in ./pp

1) Split and pack data
2) Preprocess

Run the baselines in ./baselines

1) Use notebooks in ./pp for additional preprocessing, if necessary
2) Run the baselines in the notebooks

Top baseline with no balancing of the data or any special tricks, just base TfIdf is **NB-SVM** (variation of J. Howard's kaggle implementation for multi-label problems):

```
accuracy_score: 0.371

roc_auc_score: 0.766

hamming_loss:   0.221
```

### Run main experiments in .

1) Preprocess using respective notebooks in '.', if needed
2) Train/finetune language models
3) Train classifiers

### TODO: Visualize using tools in 'vis'



