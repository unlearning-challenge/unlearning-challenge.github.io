---
layout: page
title: FAQ
permalink: /faq/
---

For the most up to date information, please check the [Kaggle Discussion board](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning/discussion)

---

_Q: What constitutes a submission to this competition?_

Please see our [Kaggle page](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning) for information on how to make a submission. 

---

_Q: Can I participate within a team?_

A: Yes, you can participate within a team of no more than 5 individuals. Please see the rules on our Kaggle page for more info.

---

_Q: Will the forget set be randomly selected or will it be for example a specific class?_

A: The competition will focus on the setting where the forget set is sampled uniformly at random from the training dataset. Please also see [this document](https://unlearning-challenge.github.io/assets/data/Machine_Unlearning_Metric.pdf) for additional info. However, we may also evaluate submissions in different settings as part of our post-competition analyses.


---

_Q: What kind of assumptions can be made about the model and the algorithm?_

A: All models are trained using a cross-entropy loss, without data augmentation. Please also see [this document](https://unlearning-challenge.github.io/assets/data/Machine_Unlearning_Metric.pdf) for additional info.

---

_Q: Is the competition only using CIFAR-10?_

A: No, the competition will use natural datasets of human faces for evaluation. We will not release these datasets, but the participants will get feedback based on how well their submitted algorithms do on those datasets via the leaderboard. We are only using CIFAR-10 as part of the starting kit, to demonstrate the problem setting in a toy-ish manner, but we won't use CIFAR-10 for evaluation in the competition. 

---

_Q: How will submissions be evaluated?_

A: We describe our evaluation procedure in [this document](https://unlearning-challenge.github.io/assets/data/Machine_Unlearning_Metric.pdf).


---

_Q: Where can I find the link to the kaggle challenge (where to make submissions, see leaderboard etc)?_

A: This is our [Kaggle page](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning).

