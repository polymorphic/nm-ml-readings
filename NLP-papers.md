# NLP Papers

For each paper on this reading list:

0. Read the paper
1. Write a short summary
2. What is/are the key takeaway(s) from this paper?
3. What was hard to understand?
4. How do you imagine applying the ideas from this paper?
5. What references piqued your curiosity such that you'd like to take a closer look into?

Note: you may not understand everything, and that's OK. Your understanding will improve as you learn about this space.

Submit 1-5 above as
a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
for this repository.

## Large Language Models Can Self-improve, by Jiaxin Huang et al.

Online at [arxiv.org/pdf/2210.11610.pdf](https://arxiv.org/pdf/2210.11610.pdf)

> Large Language Models (LLMs) have achieved excellent performances in vari- ous tasks. However, fine-tuning an LLM
> requires extensive supervision. Human, on the other hand, may improve their reasoning abilities by self-thinking with-
> out external inputs. In this work, we demonstrate that an LLM is also capable of self-improving with only unlabeled
> datasets. We use a pre-trained LLM to gener- ate “high-confidence” rationale-augmented answers for unlabeled questions
> using Chain-of-Thought prompting and self-consistency, and fine-tune the LLM using those self-generated solutions as
> target outputs. We show that our approach im- proves the general reasoning ability of a 540B-parameter LLM (
> 74.4%→82.1%
> on GSM8K, 78.2%→83.0% on DROP, 90.0%→94.4% on OpenBookQA, and 63.4%→67.9% on ANLI-A3) and achieves
> state-of-the-art-level performance, without any ground truth label. We conduct ablation studies and show that fine-
> tuning on reasoning is critical for self-improvement.


## CLIPTEXT: A New Paradigm for Zero-shot Text Classification, by Libo Qin et al.

Online at [aclanthology.org/2023.findings-acl.69.pdf](https://aclanthology.org/2023.findings-acl.69.pdf)

> While CLIP models are useful for zero-shot vision-and-language (VL) tasks or computer vision tasks, little attention
> has been paid to the application of CLIP for language tasks. Intu- itively, CLIP model have a rich representation
> pre-trained with natural language supervision, in which we argue that it is useful for language tasks. Hence, this work
> bridge this gap by in- vestigating a CLIP model for zero-shot text classification. Specifically, we introduce CLIP-
> TEXT, a novel paradigm for zero-shot text clas- sification, which reformulates zero-shot text classification into a
> text-image matching prob- lem that CLIP can be applied to. In addi- tion, we further incorporate prompt into CLIP-
> TEXT (PROMPT-CLIPTEXT) to better derive knowledge from CLIP. Experimental results on seven publicly available zero-shot
> text classi- fication datasets show that both CLIPTEXT and PROMPT-CLIPTEXT attain promising per- formance. Besides,
> extensive analysis further verifies that knowledge from CLIP can bene- fit zero-shot text classification task. We hope
> this work can attract more breakthroughs on applying VL pre-trained models for language tasks.

AI image generation such as Stable Diffusion leverage CLIP Text; some references on the topic include:

* http://jalammar.github.io/illustrated-stable-diffusion/
* https://paperswithcode.com/paper/high-resolution-image-synthesis-with-latent
* https://arxiv.org/abs/2006.11239
* https://paperswithcode.com/method/u-net
