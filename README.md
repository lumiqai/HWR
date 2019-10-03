# Handwritten Text Recognition (HTR)
A review of some proprosed state-of-the-art models for HTR, as well as existing tools in the market.

Datasets:
- IAM Handwriting Database
- RIMES (French)
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

Transkribus and other projects
Transkribus is	a	platform	for	the	automated	recognition,	transcription	and	searching	of	handwritten	historical	 documents.	 Transkribus	 is	 part	 of	 the	 EUfunded Recognition	and	Enrichment	of	Archival	Documents (READ) project.		The	core	mission	of	the	READ	
project	is	 to	make	 archival	material	more	 accessible	
through	the	development	and	dissemination	of	Handwritten	 Text	 Recognition	 (HTR)	 and	 other	 cuttingedge	technologies.	

Transkribus is the READ project’s comprehensive platform for the automated recognition, transcription and searching of historical documents.  The main objective of Transkribus is to support users who are engaged in the transcription of printed or handwritten documents, namely humanities scholars, archives, volunteers and computer scientists.

Transkribus offers a number of tools for the automated processing of documents, such as:
Handwritten Text Recognition (HTR)
Layout Analysis
Document Understanding
Keyword Spotting
Optical Character Recognition (OCR) using ABBYY Finereader Engine 11

Claims to achieve 5-10% CER in general.

- https://transkribus.eu/Transkribus/
- https://dh2017.adho.org/abstracts/649/649.pdf
- https://github.com/Transkribus
- https://play.google.com/store/apps/details?id=at.ac.tuwien.caa.docscan
- https://read.transkribus.eu/
- https://scantent.eu/en/
- https://read.transkribus.eu/wp-content/uploads/2018/11/LEIFERT-CITLAB.pdf
- https://www.academia.edu/8601748/Preprint_Handwritten_Text_Recognition_HTR_of_Historical_Documents_as_a_Shared_Task_for_Archivists_Computer_Scientists_and_Humanities_Scholars._The_Model_of_a_Transcription_and_Recognition_Platform_TRP_





- http://openaccess.thecvf.com/content_ECCV_2018/papers/Curtis_Wigington_Start_Follow_Read_ECCV_2018_paper.pdf
 - https://arxiv.org/pdf/1904.09150.pdf
- https://dl.acm.org/citation.cfm?id=3222229
- http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2018/word-spotting-recognition.pdf
- https://ieeexplore.ieee.org/document/8563226
- https://ieeexplore.ieee.org/abstract/document/8270041
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8563230
- https://arxiv.org/pdf/1604.00187.pdf

