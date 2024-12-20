collab link for this :- https://colab.research.google.com/drive/1PN0SKbmOgy5a1MfmC46XEHKQapBCz2Nt?usp=sharing

<p align="center">
  <img src="https://github.com/AnMaster15/Topsis-for-pre-trainned/blob/main/model_rankings.png" width="60%" />
</p>

## Model Performance Comparison

### TOPSIS Scores
| Model | Score |
|-------|--------|
| facebook/bart-large-cnn | 0.787 |
| sshleifer/distilbart-cnn-12-6 | 0.765 |
| facebook/bart-large-xsum | 0.416 |
| t5-base | 0.351 |
| google/pegasus-cnn_dailymail | 0.227 |

### Detailed Metrics
| Model | ROUGE-1 F1 | ROUGE-2 F1 | ROUGE-L F1 | Inference Time | Model Size |
|-------|------------|------------|------------|----------------|------------|
| facebook/bart-large-cnn | 0.402 | 0.204 | 0.312 | 0.683 | 1549.875 |
| sshleifer/distilbart-cnn-12-6 | 0.363 | 0.170 | 0.300 | 0.430 | 1165.430 |
| facebook/bart-large-xsum | 0.301 | 0.107 | 0.227 | 0.565 | 1549.875 |
| t5-base | 0.316 | 0.135 | 0.232 | 1.198 | 850.310 |
| google/pegasus-cnn_dailymail | 0.332 | 0.143 | 0.244 | 1.403 | 2177.418 |
