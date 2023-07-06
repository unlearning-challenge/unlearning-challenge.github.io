---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:
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

<a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiRnut8P03hlk5tKJPEEsqUl1DSlqN2ScdJeiaRfC3mWbQ_PBBwf7wBU9xgxuzr1GoqgkB6MwCa6Zrdo6LQxSOIPXIUrl1Yug73k2Q2zFI61VDAi9K21JOPox0Hc1CIh6ShKxW9Tgy45TYV3p3r5IiI7yxzzzOpzvbJ-5o3QVtjZn6vhDZLntnCcUSi1mb_/s720/image1.png" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="405" data-original-width="720" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiRnut8P03hlk5tKJPEEsqUl1DSlqN2ScdJeiaRfC3mWbQ_PBBwf7wBU9xgxuzr1GoqgkB6MwCa6Zrdo6LQxSOIPXIUrl1Yug73k2Q2zFI61VDAi9K21JOPox0Hc1CIh6ShKxW9Tgy45TYV3p3r5IiI7yxzzzOpzvbJ-5o3QVtjZn6vhDZLntnCcUSi1mb_/s16000/image1.png"></a>
<p style="text-align: center; font-size: 80%; font-color: gray; font-style: italic"><b>Anatomy of unlearning.</b> An unlearning algorithm takes as input a pre-trained model and one or more samples from the train set to unlearn (the "forget set"). From the model, forget set, and retain set, the unlearning algorithm produces an updated model. An ideal unlearning algorithm produces a model that is indistinguishable from the model trained without the forget set.</p>

The [starting kit](https://github.com/unlearning-challenge/starting-kit) provides an example of unlearning algorithms for participants to build their unlearning models upon.

For the *Feedback* and *Final* phases of the challenge, participants' submitted code is evaluated on real face datasets hosted on Kaggle. Those datasets are not made available to participants during the challenge.

## Timeline

**Check phase**: Begins June 28, 2023. Initial announcement and availability of the "starting kit", containing a notebook with an example simple unlearning algorithm and a simple metric for evaluation, so that participants can start practicing.

**Feedback phase**: Begins mid July, 2023, until mid September 2023. Submission site opens and participants can start making submissions on Kaggle.

**Final phase**: From mid till end of September 2023. During this phase, the organizers can run additional analyses on the submitted unlearning algorithms, including different metrics and datasets.

Winners will be announced in October 2023.


# Contact

Announcements about the competition will be made on this website and on the google group [unlearning-challenge](https://groups.google.com/g/unlearning-challenge). 
