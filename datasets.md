---
title: Datasets and Models
permalink: /datasets
---


## Neural Models

- I was involved in the creation and release of **CamemBERT**, the first BERT-based language model released for a language other than English. In particular, I can take credit for pushting our minimal pre-training data size argument, required to reach state-of-the-art performance, and on the transfer-learning setup for parsing tasks.

- I was also deeply involved in early efforts aimed at replicating GPT2 language models beyond English. With the startup LightOn, we released **PagnolXL**, the first French generative model at roughly GPT-2 scale. Around the same period, together with Benoit Sagot and Pedro Ortiz, I was also involved in the initial **BigScience** proposal.

- Through the work of my PhD student Arij Riabi, I was strongly involved in the release of **CharacterBERT-UGC**, a character-based model for user-generated content in French and North African dialectal Arabic. Despite being trained on only 99k sentences, it achieved performance comparable to models trained on orders of magnitude more data.

- Together with my PhD student Wissam Antoun and Benoit Sagot, we released several models, such as **CamemBERTa**, **CamemBERT v2**, and later **CamemBERTa v2**, a series of highly data-efficient French language models based on DeBERTa-v3-style training objectives. More recently, we also released a **ModernBERT-based variant** of CamemBERT v2.

- More recently, I led the **GAPeron** project, a series of French LLMs ranging from 1.5B to 24B parameters and trained on up to 4T tokens. The core implementation and training work was carried out by Nathan Godey, Wissam Antoun, and Rian Touchent, while Rachel Bawden, Eric de la Clergerie, Benoit Sagot, and I ensured the scientific follow-up of the project.

All those models are available in the [ALMAnaCH's Hugginface space](https://huggingface.co/almanach/models) and or through the [ALMAnaCH's models page](https://almanach.inria.fr/software_and_resources-en.html).

## Datasets
- **Scribe Finance** A Q&A multimodal dataset (text+images) focusing on the French financial domain. Include multiturn evaluation.  [repo](https://github.com/dseddah/Scribe_finance)
- **Multimodal FactChecking for French and German** Two new, up-to-date large-scale datasets for French and German containing claims, debunking articles, visual media, and evidence categorized according to journalistic verification practices. (to appear)
- **Counter Dataset** An online multilingual (fr, en, ar) radicalisation dataset, with semantic pseudo-anonymisation (NER, Radical level detection, Calk for action). Multivieuw annotations. Covers most social medias. [repo](https://gitlab.inria.fr/ariabi/counter-dataset-public/)
- **Adversarial GPT** An adversarial dataset in French designed to fool chatGPT and other LLM-generated content detectors. First of its kind, released in early 2023. [repo](https://gitlab.inria.fr/wantoun/robust-chatgpt-detection)
- **NArabizi Treebank** — The first treebank for North-African Dialectal Arabic written in Arabizi (transliterated Arabic to Latin script). [v2 repo](https://gitlab.inria.fr/ariabi/release-narabizi-treebank)
- **French Social Media Bank (Cr\#pBank)** — A French treebank made of Facebook(c), Twitter(c), Doctissimo (medical forum) and JeuxVideos.com (a video game forum). First annotated Facebook data set [Download v0.9.1]({{ '/assets/FrenchSocialMediaBank-v0.9.1beta.tar.gz' | relative_url }})
- **Sequoia Treebank** — one of the first freely available French treebanks, with data from Wikipedia, news, Europarl, and biomedical text.
- **Deep Sequoia Treebank** — an updated version with an extra annotation layer in deeper syntax. Done in collaboration with the Nancy Semagramme team [web](https://deep-sequoia.inria.fr)
- **Deep FTB** — an instance of the French Treebank (used for the SPRML Shared tasks) with the same deep syntax annotation layer as the Deep Sequoia. ''(contact me or Marie Candito for the data set, you need a free licence of the original FTB.)
- **French QuestionBank** — First treebank made of questions, besides English. First 1800 sentences, out of 2600, are aligned with the English QuestionBank (Judge et al, 2006).Available in const, surface and deep dependencies. [webpage](http://alpage.inria.fr/Treebanks/FQB/) Now available in Universal Dependencies.
- **SPMRL 2013/2014 dataset** — a set of treebanks for 9 morphologically-rich languages (Arabic, Basque, French, German, Hebrew, Hungarian, Korean, Polish, Swedish) that were used for the two SPMRL Shared tasks (2013,2014) and are still used today (especially for constituant parsing evaluation). They were the first shared tasks to propose an end-to-end evaluation with non gold tokens Overview paper shared task page (data set still available). Bonus: both const and dependency trees are aligned at the token level. Also contains a few LCFRS treebanks (const trees with crossing branches). [webpage](https://web.archive.org/web/20151030034817/https://dokufarm.phil.hhu.de/spmrl2013/doku.php)








## Note
 this page is still in construction, I will add all my other contributions later.