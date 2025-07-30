Demonstrating Flaws in the Illusion of Thinking
===============================================

 * The [illusion-of-thinking-collapse.ipynb](https://github.com/attilammagyar/illusion-of-thinking-collapse/blob/gh-pages/illusion-of-thinking-collapse.ipynb)
   notebook (find the [HTML version here](https://attilammagyar.github.io/illusion-of-thinking-collapse/illusion-of-thinking-collapse.html))
   attempts to demonstrate a few problems with the methodology in the paper
   titled "[The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity](https://machinelearning.apple.com/research/illusion-of-thinking)"
   (Shojaee et al. 2025).

 * The Tower of Hanoi experiment is replicated, and the observed collapse is
   reproduced with various models.

 * Variations of the experiment demonstrate that the complexity level where the
   collapse occurs is sensitive to the prompt instructions regarding the output
   and to the token utilization of the chosen output format.

 * It is also confirmed that at high complexity levels, the output quality
   starts to degrade early into the output, long before the token budget would
   be exhausted. However, the generated reasonings reveal that the models
   often abandon the correct solutions due to the reasoning and the final
   answer token budgets.

Note: [Others also have pointed out problems with the experiments](https://arxiv.org/abs/2506.09250v1).
I was unaware of this paper when I started working on the notebook. Though this
paper [was initially intended as a joke](https://lawsen.substack.com/p/when-your-joke-paper-goes-viral)
by naming Claude Opus as the main author, it actually does point out legitimate
problems with the original experiments.
