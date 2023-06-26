---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: The Challenge
---

<div style="width: 256px">
<img src="Unlearning-logo.png"> <br>
<p style="color: grey; font-size: 80%">Image credits: Dall-E and toppng.com</p>
</div>

## Why?

Deep neural networks are at the center of rapid progress in AI, with applications to computer vision, natural language processing, speech recognition and others. While this progress offers many exciting opportunities, it also introduces new challenges, as we researchers bear the responsibility to understand and mitigate the potential risks associated with it. Notably, a key ingredient of recent advances is the role of massive datasets combined with ever larger models. This aspect has implications for privacy, as large models tend to memorize details of their training set. Concretely, **the field faces a significant challenge meeting recent privacy regulations**, such as EU's General Data Protection Regulation ([Mantelero, 2013](https://doi.org/10.1016/j.clsr.2013.03.010)) or Canada's [Personal Information Protection and Electronic Documents Act](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/), which stipulate that **individuals have the "right to be forgotten"**.

The introduction of this legal notion has spurred the development of formal, mathematical notions of "deleting" or "obliterating" one's data, all studied under the auspices of "*machine unlearning*". Informally, unlearning refers to removing the influence of a subset of the training set from the weights of a trained model. The development of novel formal models, their theoretical limitations, and efficient and scalable algorithms is a rich and growing subfield; see for example recent surveys by [Zhang et al. (2023)](https://doi.org/10.1007/s42979-023-01767-4), [Nguyen et al. (2022)](https://arxiv.org/abs/2209.02299), [Jiang et al. (2022)](https://doi.org/10.1117/12.2660330).

Machine unlearning is a powerful tool that has the potential to address a number of important problems. As research in this area continues, we can expect to see new methods that are more efficient, effective, and ethical. We are thrilled to have the opportunity via this competition to spark interest in this field, and we are looking forward to sharing our insights and findings with the community.

## Task and Data

The challenge centers on the scenario in which an age predictor is built from face image data and, after training, a certain number of images must be forgotten to protect the privacy or rights of the individuals concerned.

The [starter kit](https://github.com/unlearning-challenge/starting-kit) provides a development (*Check* phase) dataset derived from the Face Synthetics dataset ([Wood et al., 2021](https://microsoft.github.io/FaceSynthetics/)). We assigned each synthetic face in the dataset with an age label obtained from a model trained on a public dataset of faces. The example pre-trained model to be used for unlearning was trained on this age-labeled synthetic dataset.

> **NOTE**: This dataset is meant to be used **only** for benchmarking purposes.

For the *Feedback* and *Final* phases of the challenge, participants' submitted code is evaluated on real face datasets hosted on the CodaLab platform. Those datasets are not made available to participants during the challenge.

## Timeline

**Check phase**: Begins June 28, 2023

**Feedback phase**: Begins early July, 2023, until mid September 2023

**Final phase**: From mid till end of September 2023

Winners will be announced in October 2023.

## Protocol, starter kit, evaluation metrics

More information coming soon.

# Contact

Announcements about the competition will be made on this website and on the google group [unlearning-challenge](https://groups.google.com/g/unlearning-challenge). 
