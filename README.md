# CS 521 HW3

Brian Kim (bmkim2)

| Problem | Notebook |
|---|---|
| 1. PGD adversarial training | [q1_adv_training/q1_adversarial_training.ipynb](q1_adv_training/q1_adversarial_training.ipynb) |
| 2. SynCode + Phi-2 | [q2_syncode/q2_syncode.ipynb](q2_syncode/q2_syncode.ipynb) |
| 3. Multi-norm adversarial training | [q3_multinorm/multi_norm_adversarial_training_cifar10.ipynb](q3_multinorm/multi_norm_adversarial_training_cifar10.ipynb) |

All notebooks run in Google Colab with a T4 GPU and download their data themselves
(the CIFAR-10 subsets and the base model of Problem 3 are not stored in this repository).
Problem 2 defines `run_syncode(textual_query)`, which returns `(operands_list, operator_str, answer_float)`.
