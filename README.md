# Differential Privacy and Privacy-Preserving Learning for Natural Language Processing

A collection of relevant papers and resources for differential privacy and privacy-preserving learning for natural language processing.

_This collection was developed by Faiaz Rahman for the course CS 677: Advanced Natural Language Processing (Fall 2021) under Dr. Dragomir Radev at Yale University._

## Differential Privacy
- Theory of Differential Privacy
  - Differential Privacy, as originally originally defined by Cynthia Dwork [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/dwork.pdf)
  - The Algorithmic Foundations of Differential Privacy [[textbook]](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf)
  - Differential Privacy and Applications [[textbook]](https://link.springer.com/content/pdf/10.1007/978-3-319-62004-6.pdf)
  - Local Differential Privacy and Its Applications: A Comprehensive Survey [[paper]](https://arxiv.org/abs/2008.03686)
  - The Complexity of Differential Privacy [[chapter]](https://link.springer.com/chapter/10.1007/978-3-319-57048-8_7)
- Differential Privacy and Machine Learning
  - Differential Privacy and Machine Learning: a Survey and Review [[paper]](https://arxiv.org/abs/1412.7584)
  - More Than Privacy: Applying Differential Privacy in Key Areas of Artificial Intelligence [[paper]](https://arxiv.org/abs/2008.01916)
- Maintaining Privacy
  - Issues Encountered Deploying Differential Privacy [[paper]](https://dl.acm.org/doi/pdf/10.1145/3267323.3268949)
  - Detecting Violations of Differential Privacy [[paper]](https://dl.acm.org/doi/pdf/10.1145/3243734.3243818)
  - Differential Privacy under Continual Observation [[paper]](https://dl.acm.org/doi/pdf/10.1145/1806689.1806787)
- Tuning Privacy
  - Differential Privacy: An Estimation Theory-Based Method for Choosing Epsilon [[paper]](https://arxiv.org/abs/1510.00917)
  - How Much Is Enough? Choosing ε for Differential Privacy [[paper]](https://link.springer.com/chapter/10.1007/978-3-642-24861-0_22)
- Scaling Privacy
  - Distributed Differential Privacy via Shuffling [[paper]](https://arxiv.org/abs/1808.01394)

## Additional Approaches to Data Privacy
- Federated Learning: Collaborative Machine Learning without Centralized Training Data [[article]](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
- Multi-view Embedding-based Synonyms for Email Search [[paper]](https://dl.acm.org/doi/10.1145/3331184.3331250)
- Learning from User Interactions in Personal Search via Attribute Parameterization [[paper]](https://dl.acm.org/doi/10.1145/3018661.3018712)

## Background and Motivation for Privacy for NLP
- Ethical Challenges in Data-Driven Dialogue Systems § 5 on Privacy [[paper]](https://dl.acm.org/doi/pdf/10.1145/3278721.3278777)
- Writer Profiling Without the Writer’s Text [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-67256-4_43)
- Understanding Unintended Memorization in Language Models Under Federated Learning [[paper]](https://aclanthology.org/2021.privatenlp-1.1/)
- Extracting Training Data from Large Language Models [[paper]](https://arxiv.org/abs/2012.07805)
- Privacy Risks of General-Purpose Language Models [[paper]](https://ieeexplore.ieee.org/document/9152761)
- Information Leakage in Embedding Models [[paper]](https://arxiv.org/abs/2004.00053)

## Privacy-Preserving Learning for NLP
- Natural Language Understanding with Privacy-Preserving BERT [[paper]](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/880bd423bc5664f9c6ebcadd76b00b945c9c3a63.pdf)
- Differential Privacy for Text Analytics via Natural Text Sanitization [[paper]](https://aclanthology.org/2021.findings-acl.337.pdf)
- Privacy- and Utility-Preserving Textual Analysis via Calibrated Multivariate Perturbations [[paper]](https://dl.acm.org/doi/pdf/10.1145/3336191.3371856)
- Privacy-preserving Neural Representations of Text [[paper]](https://aclanthology.org/D18-1001.pdf)

## Differential Privacy in Industry
- Apple's Differential Privacy Technical Overview [[article]](https://www.apple.com/privacy/docs/Differential_Privacy_Overview.pdf)
- Apple's Learning with Privacy at Scale [[article]](https://machinelearning.apple.com/research/learning-with-privacy-at-scale)
- Microsoft's Project PrivTree: Blurring your “where” for location privacy [[article]](https://www.microsoft.com/en-us/research/blog/project-privtree-blurring-location-privacy/)

## Differential Privacy Tools
- Opacus: PyTorch models with differential privacy [[site]](https://opacus.ai) [[GitHub]](https://github.com/pytorch/opacus)
- OpenDP: suite of open-source differential privacy tools originally developed by Microsoft and Harvard [[site]](https://opendp.org/#) [[GitHub]](https://github.com/opendp)
- Google Differential Privacy [[GitHub]](https://github.com/google/differential-privacy/)
