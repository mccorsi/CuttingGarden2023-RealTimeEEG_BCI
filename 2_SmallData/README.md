# Facing the small data reality in event-related potential BCI protocols

## Speaker
[Michael Tangermann](https://neurotechlab.socsci.ru.nl/author/michael-tangermann/): Associate Professor, Dept. Artificial Intelligence, Donders Institute, Radboud University, Nijmegen, The Netherlands

The talk covers work of my research lab, with strong focus on the PhD topic(s) of [Jan Sosulski](https://neurotechlab.socsci.ru.nl/author/jan-sosulski/)

## Abstract
Machine learning methods that are capable of decoding brain states in a single trial play a role not only in closed-loop neurotechnological systems such as brain-computer interfaces (BCI) but also allow to obtain immediate feedback for participants who participate in studies that address fundamental research. Training such a decoding model typically requires labelled training data from an individual participant / BCI user obtained at the beginning of a session. Recording this data limits the duration of the following online  experiment or BCI application. In my talk, I will first provide an overview of mitigations of this problem, which all have in common that they try to minimize the need for individual data for a novel user or session, before zooming into three recently developed classification methods for event-related potential data, that make use of domain-specific regularization to minimize the need of training data.

## References
The core of my talk refers to the three classification methods described in these publications:
* Time-Decoupled Linear Discriminant Analysis [TD-LDA](https://link.springer.com/article/10.1007/s12021-020-09501-8)
* Block-Toeplitz Linear Discriminant Analysis [Toeplitz-LDA](https://iopscience.iop.org/article/10.1088/1741-2552/ac9c98/meta)
* Unsupervised Mean-difference Maximization [UMM](https://arxiv.org/abs/2306.11830), an unsupervised method that does not require a change to the user interface (cp. to learning from label proportions, LLM) and can be applied instantaneously on data of a single trial, i.e. without any historic data.

## Resources

### Examples of ERP-BCI applications
Going beyond the widely-used visual ERP based spelling applications:
* [BCI-supported language training](https://academic.oup.com/braincomms/article/4/1/fcac008/6524563) as a tool for the rehabilitation of stroke patients with aphasia.
* [BCI-controlled chess gaming](https://doi.org/10.1080/2326263X.2020.1741072) showing the capacity of three unsupervised ERP-decoding approaches based on (1) expectation maximization, (2) learning from label proportions, (3) a mixed method using the former two. Please note, that learning from label proportions (LLM) requires slight [changes to the user interface](https://doi.org/10.1371/journal.pone.0175856).


### Comparison of highlighting schemes
The two videos allow you to compare the visual impression of two highlighting schemes:
*  File [p300_row_col_simple.avi](p300_row_col_simple.avi) shows a (traditional) row-column highlighting (despite for a photo browser application instead of text spelling)
*  File [p300_pseudo_random_complex.avi](p300_pseudo_random_complex.avi) shows an optimized highlighting scheme of the same application with pseudo-random items per group, contrastive grid overlay, and brief animation, which leads to stronger ERP responses and higher decoding performance and which is used in many of my lab's visual ERP protocols.
  
