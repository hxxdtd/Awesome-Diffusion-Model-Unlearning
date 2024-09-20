# Awesome Diffusion Model Unlearning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of academic articles, resources, and datasets on the subject of **machine unlearning for diffusion models**.

> [!NOTE]
> If you believe a paper on diffusion model unlearning is not included, or if you find a mistake, typo, or information that is not up to date, please open an issue, and I will address it as soon as possible.

## Table of Contents

- [Concept Unlearning](#concept-unlearning)
- [Concept Restoration](#concept-restoration)
- [Benchmark](#benchmark)

## Concept Unlearning

| Paper                                                        | Year | Venue     | Code                                                         |
| :----------------------------------------------------------: | :--: | :-------: | :----------------------------------------------------------: |
| [Reliable and Efficient Concept Erasure of Text-to-Image Diffusion Models](https://arxiv.org/abs/2407.12383) | 2024 | ECCV 2024 | [GitHub](https://github.com/CharlesGong12/RECE) |
| [R.A.C.E.: Robust Adversarial Concept Erasure for Secure Text-to-Image Diffusion Model](https://arxiv.org/abs/2405.16341) | 2024 | ECCV 2024 | [GitHub](https://github.com/chkimmmmm/R.A.C.E.) |
| [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://arxiv.org/abs/2311.17717) | 2023 | ECCV 2024 | [GitHub](https://github.com/jasper0314-huang/Receler) |
| [MACE: Mass Concept Erasure in Diffusion Models](https://arxiv.org/abs/2403.06135) | 2024 | CVPR 2024 | [GitHub](https://github.com/Shilin-LU/MACE) |
| [One-Dimensional Adapter to Rule Them All: Concepts, Diffusion Models and Erasing Applications](https://arxiv.org/abs/2312.16145) | 2024 | CVPR 2024 | [GitHub](https://github.com/Con6924/SPM) |
| [ConceptPrune: Concept Editing in Diffusion Models via Skilled Neuron Pruning](https://arxiv.org/abs/2405.19237) | 2024 | arXiv |  |
| [Pruning for Robust Concept Erasing in Diffusion Models](https://arxiv.org/abs/2405.16534) | 2024 | arXiv |  |
| [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://arxiv.org/abs/2405.15234) | 2024 | arXiv | [GitHub](https://github.com/OPTML-Group/AdvUnlearn) |
| [Unlearning Concepts in Diffusion Model via Concept Domain Correction and Concept Preserving Gradient](https://arxiv.org/abs/2405.15304) | 2024 | arXiv |  |
| [SafeGen: Mitigating Sexually Explicit Content Generation in Text-to-Image Models](https://arxiv.org/abs/2404.06666) | 2024 | ACM CCS 2024 | [GitHub](https://github.com/LetterLiGo/SafeGen_CCS2024) |
| [Robust Concept Erasure Using Task Vectors](https://arxiv.org/abs/2404.03631) | 2024 | arXiv |  |
| [Separable Multi-Concept Erasure from Diffusion Models](https://arxiv.org/abs/2402.05947) | 2024 | arXiv | [GitHub](https://github.com/Dlut-lab-zmn/SepCE4MU) |
| [EraseDiff: Erasing Data Influence in Diffusion Models](https://arxiv.org/abs/2401.05779) | 2024 | arXiv | [GitHub](https://github.com/JingWu321/EraseDiff) |
| [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12807) | 2023 | AAAI 2024 |                                                              |
| [SalUn: Empowering Machine Unlearning via Gradient-based Weight Saliency in Both Image Classification and Generation](https://arxiv.org/abs/2310.12508) | 2023 | ICLR 2024 | [GitHub](https://github.com/OPTML-Group/Unlearn-Saliency) |
| [Unified Concept Editing in Diffusion Models](https://arxiv.org/abs/2308.14761) | 2023 | WACV 2024 | [GitHub](https://github.com/rohitgandikota/unified-concept-editing) |
| [Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models](https://arxiv.org/abs/2305.10120) | 2023 | NeurIPS 2023 | [GitHub](https://github.com/clear-nus/selective-amnesia)     |
| [Ablating Concepts in Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.13516) | 2023 | ICCV 2023 | [GitHub](https://github.com/nupurkmr9/concept-ablation)      |
| [Erasing Concepts from Diffusion Models](https://arxiv.org/abs/2303.07345) | 2023 | ICCV 2023 | [GitHub](https://github.com/rohitgandikota/erasing)          |
| [Degeneration-Tuning: Using Scrambled Grid shield Unwanted Concepts from Stable Diffusion](https://arxiv.org/abs/2308.02552) | 2023 | ACM MM 2023 |  |
| [Implicit Concept Removal of Diffusion Models](https://arxiv.org/abs/2310.05873) | 2023 | arXiv |  |
| [Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.17591) | 2023 | arXiv     | [GitHub](https://github.com/SHI-Labs/Forget-Me-Not)          |

## Concept Restoration

|                            Paper                             | Year |   Venue   |                             Code                             |            Type            |
| :----------------------------------------------------------: | :--: | :-------: | :----------------------------------------------------------: | :------------------------: |
| [Probing Unlearned Diffusion Models: A Transferable Adversarial Attack Perspective](https://arxiv.org/abs/2404.19382) | 2024 |   arXiv   |           [GitHub](https://github.com/hxxdtd/PUND)           | black-box, embedding-level |
| [Circumventing Concept Erasure Methods For Text-to-Image Generative Models](https://arxiv.org/abs/2308.01508) | 2023 | ICLR 2024 | [GitHub](https://github.com/NYU-DICE-Lab/circumventing-concept-erasure) | white-box, embedding-level |
| [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://arxiv.org/abs/2310.10012) | 2023 | ICLR 2024 |     [GitHub](https://github.com/chiayi-hsu/Ring-A-Bell)      |  black-box, prompt-level   |
| [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://arxiv.org/abs/2310.11868) | 2023 | ECCV 2024 | [GitHub](https://github.com/OPTML-Group/Diffusion-MU-Attack) |  white-box, prompt-level   |

## Benchmark

|                            Paper                             | Year | Venue |                          Code                          |
| :----------------------------------------------------------: | :--: | :---: | :----------------------------------------------------: |
| [UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models](https://arxiv.org/abs/2402.11846) | 2024 | arXiv | [GitHub](https://github.com/OPTML-Group/UnlearnCanvas) |
