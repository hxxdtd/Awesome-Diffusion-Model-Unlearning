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
| [Minimalist Concept Erasure in Generative Models](https://openreview.net/pdf?id=oBCw6PZ0fX) | 2025 | ICML 2025 |  |
| [EraseAnything: Enabling Concept Erasure in Rectified Flow Transformers](https://arxiv.org/abs/2412.20413) | 2025 | ICML 2025 | [GitHub](https://github.com/tomguluson92/EraseAnything) |
| [One Image is Worth a Thousand Words: A Usability Preservable Text-Image Collaborative Erasing Framework](https://arxiv.org/abs/2505.11131) | 2025 | ICML 2025 | [GitHub](https://github.com/Ferry-Li/Co-Erasing) |
| [Adaptive Median Smoothing: Adversarial Defense for Unlearned Text-to-Image Diffusion Models at Inference Time](https://openreview.net/pdf?id=PdBEggnDIl) | 2025 | ICML 2025 |  |
| [SAeUron: Interpretable Concept Unlearning in Diffusion Models with Sparse Autoencoders](https://arxiv.org/abs/2501.18052) | 2025 | ICML 2025 | [GitHub](https://github.com/cywinski/SAeUron) |
| [ACE: Anti-Editing Concept Erasure in Text-to-Image Models](https://arxiv.org/abs/2501.01633) | 2025 | CVPR 2025 | [GitHub](https://github.com/120L020904/ACE) |
| [Precise, Fast, and Low-cost Concept Erasure in Value Space: Orthogonal Complement Matters](https://arxiv.org/abs/2412.06143) | 2025 | CVPR 2025 | [GitHub](https://github.com/WYuan1001/AdaVD) |
| [STEREO: A Two-Stage Framework for Adversarially Robust Concept Erasing from Text-to-Image Diffusion Models](https://arxiv.org/abs/2408.16807) | 2025 | CVPR 2025 | [GitHub](https://github.com/koushiksrivats/robust-concept-erasing) |
| [Erasing Undesirable Influence in Diffusion Models](https://arxiv.org/abs/2401.05779) | 2025 | CVPR 2025 | [GitHub](https://github.com/JingWu321/EraseDiff) |
| [Fantastic Targets for Concept Erasure in Diffusion Models and Where To Find Them](https://arxiv.org/abs/2501.18950) | 2025 | ICLR 2025 | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) |
| [Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation](https://arxiv.org/abs/2410.15618) | 2024 | NeurIPS 2024 | [GitHub](https://github.com/tuananhbui89/Erasing-Adversarial-Preservation) |
| [Reliable and Efficient Concept Erasure of Text-to-Image Diffusion Models](https://arxiv.org/abs/2407.12383) | 2024 | ECCV 2024 | [GitHub](https://github.com/CharlesGong12/RECE) |
| [R.A.C.E.: Robust Adversarial Concept Erasure for Secure Text-to-Image Diffusion Model](https://arxiv.org/abs/2405.16341) | 2024 | ECCV 2024 | [GitHub](https://github.com/chkimmmmm/R.A.C.E.) |
| [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://arxiv.org/abs/2311.17717) | 2023 | ECCV 2024 | [GitHub](https://github.com/jasper0314-huang/Receler) |
| [MACE: Mass Concept Erasure in Diffusion Models](https://arxiv.org/abs/2403.06135) | 2024 | CVPR 2024 | [GitHub](https://github.com/Shilin-LU/MACE) |
| [One-Dimensional Adapter to Rule Them All: Concepts, Diffusion Models and Erasing Applications](https://arxiv.org/abs/2312.16145) | 2024 | CVPR 2024 | [GitHub](https://github.com/Con6924/SPM) |
| [SafeGen: Mitigating Sexually Explicit Content Generation in Text-to-Image Models](https://arxiv.org/abs/2404.06666) | 2024 | ACM CCS 2024 | [GitHub](https://github.com/LetterLiGo/SafeGen_CCS2024) |
| [ConceptPrune: Concept Editing in Diffusion Models via Skilled Neuron Pruning](https://arxiv.org/abs/2405.19237) | 2024 | arXiv |  |
| [Pruning for Robust Concept Erasing in Diffusion Models](https://arxiv.org/abs/2405.16534) | 2024 | arXiv |  |
| [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://arxiv.org/abs/2405.15234) | 2024 | arXiv | [GitHub](https://github.com/OPTML-Group/AdvUnlearn) |
| [Unlearning Concepts in Diffusion Model via Concept Domain Correction and Concept Preserving Gradient](https://arxiv.org/abs/2405.15304) | 2024 | arXiv |  |
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

|                            Paper                             | Year |   Venue    |                             Code                             |            Type            |
| :----------------------------------------------------------: | :--: | :--------: | :----------------------------------------------------------: | :------------------------: |
| [Memories of Forgotten Concepts](https://arxiv.org/abs/2412.00782) | 2025 | CVPR 2025  | [GitHub](https://github.com/matanr/Memories_of_Forgotten_Concepts) |  white-box, latent-level   |
| [DiffZOO: A Purely Query-Based Black-Box Attack for Red-teaming Text-to-Image Generative Model via Zeroth Order Optimization](https://arxiv.org/abs/2408.11071) | 2025 | NAACL 2025 |     [GitHub](https://github.com/CherryBlueberry/DiffZOO)     |  black-box, prompt-level   |
| [Probing Unlearned Diffusion Models: A Transferable Adversarial Attack Perspective](https://arxiv.org/abs/2404.19382) | 2024 |   arXiv    |           [GitHub](https://github.com/hxxdtd/PUND)           | gray-box, embedding-level  |
| [Circumventing Concept Erasure Methods For Text-to-Image Generative Models](https://arxiv.org/abs/2308.01508) | 2023 | ICLR 2024  | [GitHub](https://github.com/NYU-DICE-Lab/circumventing-concept-erasure) | white-box, embedding-level |
| [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://arxiv.org/abs/2310.10012) | 2023 | ICLR 2024  |     [GitHub](https://github.com/chiayi-hsu/Ring-A-Bell)      |  black-box, prompt-level   |
| [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://arxiv.org/abs/2310.11868) | 2023 | ECCV 2024  | [GitHub](https://github.com/OPTML-Group/Diffusion-MU-Attack) |  white-box, prompt-level   |

## Benchmark

|                            Paper                             | Year |    Venue     |                          Code                          |
| :----------------------------------------------------------: | :--: | :----------: | :----------------------------------------------------: |
| [Six-CD: Benchmarking Concept Removals for Benign Text-to-image Diffusion Models](https://arxiv.org/abs/2406.14855) | 2025 |  CVPR 2025   |     [GitHub](https://github.com/Artanisax/Six-CD)      |
| [UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models](https://arxiv.org/abs/2402.11846) | 2024 | NeurIPS 2024 | [GitHub](https://github.com/OPTML-Group/UnlearnCanvas) |
