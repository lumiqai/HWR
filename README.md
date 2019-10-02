# Handwritten Text Recognition (HTR)
A review of some proprosed state-of-the-art models for HTR, as well as existing tools in the market.

Datasets:
- IAM Handwriting Database
- RIMES
- George Washington Database

Metrics:
- Word Error Rate & Character Error Rate

Models:

### Convolution + 1D-LSTMs (Puigcerve, 2017)

#### Paper: 
http://www.jpuigcerver.net/pubs/jpuigcerver_icdar2017.pdf

#### Code:
https://github.com/jpuigcerver/Laia/blob/master/egs/iam/README.md

#### Summary: 
Shows that expensive, multi-dimensional LTSM models (the current trend) are not neccesarily required for HTR, and that state-of-the-art performance can be achieved using convolution and a single LSTM. Also, creating new, synthetic images to train on (using distortions on actual training data) help improve performance and generalisation.

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8583799, https://github.com/josarajar/HTRTF shows that by applying transfer learning (TL) across different databases, this model is able to achieve remarkable generalization results for small historical databases once it has been pre-trained over a large database.

#### Performance:
IAM: 3.8% CER and 13.5% WER for Validation, 5.8% CER and 18.4% WER for Testing

RIMES: 2.2% CER and 9.6% WER for Testing

To Read:
- https://transkribus.eu/Transkribus/
- http://openaccess.thecvf.com/content_ECCV_2018/papers/Curtis_Wigington_Start_Follow_Read_ECCV_2018_paper.pdf
 - https://arxiv.org/pdf/1904.09150.pdf
- https://dl.acm.org/citation.cfm?id=3222229
- http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2018/word-spotting-recognition.pdf
- https://ieeexplore.ieee.org/document/8563226
- https://ieeexplore.ieee.org/abstract/document/8270041
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8563230
- https://arxiv.org/pdf/1604.00187.pdf

