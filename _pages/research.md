---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}


## Dissertation: Enhancing Translation Systems for Low-resourced Scenarios

### Machine Translation (MT)

##### Robustness
Neural Machine Translation (NMT) systems are known to degrade when confronted with noisy data, especially when the system is trained only on clean data. However, some types of noise are very common, particularly for low-resource languages. Handling code-switched, transliterated, ungrammatical, miss spelling, and dialectal inputs is essential for deploying systems in the wild.

##### Terminology
As NMT systems become an important part of professional translator pipelines, a growing body of work focuses on combining NMT with terminologies. In many scenarios, particularly in domain adaptation cases, one expects the MT output to adhere to the constraints provided by a terminology.

##### Evaluation
Is it possible to build a general and automatic MT evaluation metric? Regarding performance, existing metrics are either unsatisfactory or restricted to tasks where large human ratings are already available.

##### Low-resource
There has traditionally been a significant concentration of MT research on a few languages - usually Indo-European. Data scarcity has hindered the progress of many languages with millions of speakers. We aim to reverse the trend by focusing on low-resource languages that have been traditionally ignored by mainstream research.

#### Dictionary
Dictionaries are the easiest resource one can find or the quickest resource to create when translating from one language to another. Can we use these external resources and traditional parallel data to create MT models for low-resourced languages?

### Speech Translation (ST)

#### Filtering
In this era, much data can be mined from the internet. However, the issue in most cases is the alignment between the source and target. For low-resourced languages, another issue is the poor language identification model. Thus, data mined is really noisy. Can we create easy filtering methods to find the highly noisy data? Can we use this knowledge to further improve the mining model?

#### Augmentation
Low-resourced languages lack parallel data. Can we create synthetic parallel data of good quality to make the ST models more robust? One way is to do a Text-to-Speech transition, as we have a lot of Text-to-text parallel data.
