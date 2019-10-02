## Handwritten Text Recognition (HTR)
A review of some of the state-of-the-art models for HTR; in particular, those proprosed in the recent International Conference on Frontiers of Handwriting Recognition (ICFHR).

Datasets:
- IAM Handwriting Database
- RIMES
- George Washington Database

Metrics:
- Word Error Rate & Character Error Rate

Models:
1. Convolution + 1D-LSTMs (Puigcerver 2017)
Paper: http://www.jpuigcerver.net/pubs/jpuigcerver_icdar2017.pdf
Code: https://github.com/jpuigcerver/Laia/blob/master/egs/iam/README.md
Summary: Shows that expensive, multi-dimensional LTSM models (the current trend) are not neccesarily required for HTR, and that state-of-the-art performance can be achieved using convolution and a single LSTM. Also, creating new, synthetic images to train on (using distortions on actual training data) help improve performance and generalisation.
Performance:
- IAM: 3.8% CER and 13.5% WER for Validation, 5.8% CER and 18.4% WER for Testing
- RIMES: 2.2% CER and 9.6% WER for Testing

1.


To Read:
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8563230
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8583799
- https://arxiv.org/pdf/1604.00187.pdf
- https://ieeexplore.ieee.org/document/8563223
- https://ieeexplore.ieee.org/document/8563226
- 
