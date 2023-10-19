# Facing the small data reality in event-related potential BCI protocols

## Speaker
[Michael Tangermann](https://neurotechlab.socsci.ru.nl/author/michael-tangermann/): Associate Professor, Dept. Artificial Intelligence, Donders Institute, Radboud University, Nijmegen, The Netherlands

The talk covers work of my research lab, with strong focus on the PhD topic(s) of [Jan Sosulski](https://neurotechlab.socsci.ru.nl/author/jan-sosulski/)

## Abstract
Machine learning methods that are capable of decoding brain states in a single trial play a role not only in closed-loop neurotechnological systems such as brain-computer interfaces (BCI) but also allow to obtain immediate feedback for participants who participate in studies that address fundamental research. Training such a decoding model typically requires labelled training data from an individual participant / BCI user obtained at the beginning of a session. Recording this data limits the duration of the following online  experiment or BCI application. In my talk, I will first provide an overview of mitigations of this problem, which all have in common that they try to minimize the need for individual data for a novel user or session, before zooming into three recently developed classification methods for event-related potential data, that make use of domain-specific regularization to minimize the need of training data.

## Resources
The two videos provide examples of a visual ERP BCI application:
*  File [p300_row_col_simple.avi](p300_row_col_simple.avi) shows a (traditional) row-column highlighting (despite for a photo browser application instead of text spelling)
*  File [p300_pseudo_random_complex.avi](p300_pseudo_random_complex.avi) shows an optimized highlighting scheme of the same application with pseudo-random items per group, contrastive grid overlay, and brief animation, which leads to stronger ERP responses and higher decoding performance and which is used in many of my lab's visual ERP protocols.
  
## References
The core of my talk refers to the three classification methods described in these publications:
* Time-Decoupled Linear Discriminant Analysis [TD-LDA](https://link.springer.com/article/10.1007/s12021-020-09501-8)
* Block-Toeplitz Linear Discriminant Analysis [Toeplitz-LDA](https://iopscience.iop.org/article/10.1088/1741-2552/ac9c98/meta)
* Unsupervised Mean-difference Maximization [UMM](https://arxiv.org/abs/2306.11830)
