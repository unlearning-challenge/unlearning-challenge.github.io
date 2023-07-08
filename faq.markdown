---
layout: page
title: FAQ
permalink: /faq/
---

_Q: I see the example notebooks use PyTorch. Can I use another library instead?_

A: Yes, participants can use any Python library that can be installed through `pip`. Note however that the `unlearning` function that constitutes the submission to the challenge takes as input a Pytorch model and some Pytorch loaders and expects as output a Pytorch model. Hence, to use a different framework than Pytorch, the participant will need to make the conversions between Pytorch models and loaders and those of the chosen framework.

---

_Q: Can I participate within a team?_

A: Yes, you can participate within a team of no more than 5 individuals.

---

_Q: Will the forget set be randomly selected or will it be for example a specific class?_

A: The competition will focus on the setting where the forget set is sampled uniformly at random from the training dataset. However, we may also evaluate submissions in different settings as part of our post-competition analyses.


---

_Q: What kind of assumptions can be made about the model and the algorithm?_

A: All models are trained using a cross-entropy loss and data augmentation during training. We will post the exact details on the the training (algorithm, learning rate, and exact data augmentation) by mid July.

---

_Q: Is the competition only using CIFAR-10?_

A: No, the competition will use natural datasets of human faces for evaluation. We will not release these datasets, but the participants will get feedback based on how well their submitted algorithms do on those datasets via the leaderboard. We are only using CIFAR-10 as part of the starting kit, to demonstrate the problem setting in a toy-ish manner, but we won't use CIFAR-10 for evaluation in the competition. We will also soon release an additional notebook in the starting kit that is based on a dataset of synthetic faces, to provide a dataset that is a bit closer to the ones that will be used for evaluation.

---

_Q: How will submissions be evaluated?_

A: We will only disclose the details of our evaluation procedure to participants after the challenge is over, as we don't want submitted unlearning algorithms to accidentally "overfit" the metric. The metric used uses ideas from MIAs as well as other statistical tools for evaluation. Intuitively, the goal of an unlearning algorithm can be thought of as matching the behaviour of the oracle unlearning method that retrains the model from scratch without the forget set. For example, if we were to simply inspect the accuracy of the unlearned model on the retain, forget, and test sets, we ideally want those to be similar to the accuracy that that oracle would have on each of those sets, respectively. Note that, on examples from the forget set, this means that we want the unlearned model to perform equally well as a model that truly never saw those examples. More generally, we may desire that the two distributions of models obtained from retraining and from unlearning are very close to each other, and there can be different ways of measuring this. While we purposefully won't disclose the details of exactly how we will construct our metric, as mentioned above, it is designed to capture these intuitions. Our metric will also capture the desire to perform well not only in terms of forgetting quality, but also to not sacrifice the "utility" of the model (performance on retained and held-out examples).


---

_Q: Where can I find the link to the kaggle challenge (where to make submissions, see leaderboard etc)?_

A: The Kaggle website is not yet public. Its scheduled to go live by mid July. When this happens we will announce it on the mailing list and post the link in the main page of this website.

