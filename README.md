# A Distant Supervision Approach with Heuristic-Augmented Denoising on IndoBERTweet-CRF for Crypto Assets Named Entity Recognition on Indonesian Twitter 

Abstract— The rapid expansion of the digital asset market in
Indonesia has fostered a highly active cryptocurrency
community on Twitter (X), necessitating automated systems to
monitor discussions and mitigate associated financial risks.
However, extracting entities from informal social media text is
challenging due to the community's complex linguistic registers,
high out-of-vocabulary rates, and the critical scarcity of
domain-specific annotated datasets for the Indonesian language.
To address dataset scarcity, this study proposes a hybrid Named
Entity Recognition (NER) pipeline utilizing an IndoBERTweet-
CRF architecture. A Distant Supervision approach is employed
to automate the labeling of a Silver Standard dataset using the
CoinGecko API as a Local Knowledge Base, integrated with a
Heuristic-Augmented Denoising mechanism to mitigate label
noise arising from lexically ambiguous terms. The base model is
subsequently fine-tuned on a Gold Standard corpus comprising
1,461 manually annotated tweets. Evaluated through 5-Fold
Cross-Validation, the proposed model achieves a mean
Precision of 77.48% and an F1-Score of 70.76%, while the
Conditional Random Field (CRF) layer successfully prevents all
structurally invalid label sequences. Although the approach
significantly reduces the time and resources required for
manual annotation, the model remains vulnerable to cross-
domain lexical ambiguity and exhibits reduced confidence when
processing formal, news-style prose lacking community slang
markers. The code for this project can be accessed
via the following GitHub link:
https://github.com/SauHin/crypto-ner-indobertweet-crf.

Keywords— Named Entity Recognition (NER), Crypto assets,
Distant supervision, IndoBERTweet-CRF, Indonesian Twitter.

