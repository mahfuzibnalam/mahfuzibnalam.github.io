---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}


## Dissertation: [Enhancing Translation Systems for Low-resourced Scenarios](https://www.proquest.com/openview/1473da96caf7e0681041e94444f2e6b4/1?pq-origsite=gscholar&cbl=18750&diss=y)

### Machine Translation (MT)

##### Robustness
Neural Machine Translation (NMT) systems often struggle when faced with noisy inputs, especially if trained only on clean data. In real-world scenarios, handling noise is crucial—this includes code-switching, transliteration, ungrammatical sentences, misspellings, and dialectal variations. Our research aims to make NMT systems robust to these common challenges, particularly for low-resource languages.

##### Terminology Integration
As NMT becomes a key tool in professional translation pipelines, it is important for models to respect domain-specific terminologies. We explore methods to incorporate terminological constraints into NMT systems, ensuring that translations remain accurate and consistent with specialized vocabulary.

##### Evaluation
Evaluating MT quality remains challenging. Existing metrics often require large human-rated datasets or fail to generalize across languages and domains. Our work investigates methods for building reliable, automatic evaluation metrics that can assess translation quality even in low-resource settings.

##### Low-Resource Focus
Most MT research has historically focused on a small set of well-resourced languages, leaving millions of speakers underserved. Our goal is to shift the focus toward traditionally ignored languages, creating translation systems that serve diverse linguistic communities.

##### Dictionaries as Resources
Dictionaries are often the easiest or quickest resource available for low-resource languages. We investigate how external resources, combined with limited parallel data, can be leveraged to build effective MT models for these languages.

### Speech Translation (ST)

##### Data Filtering
Much of the data available online is noisy or misaligned, especially for low-resource languages. Poor language identification and alignment issues exacerbate this problem. We focus on developing filtering techniques to identify high-quality data and improve the reliability of mined datasets.

##### Data Augmentation
Low-resource languages often lack sufficient parallel speech-text datasets. To address this, we explore methods for generating synthetic parallel data, such as leveraging Text-to-Speech technologies, to augment existing datasets and build more robust Speech Translation models.
