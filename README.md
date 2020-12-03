# Yet another survey of compilers for AI models

This survey is intended to cover research on compilers for AI domain. Some of these compilers are widely known as NPU/TPU compilers.

It's built not by a professional, just for studying.

## What is this similar to?

Of course, this survey is not the first one in this domain. Here is the quickly found list of similar GitHub surveys. You're better to see them first:

- :star: [awesome-tensor-compilers](https://github.com/merrymercy/awesome-tensor-compilers)
- [DL-on-Silicon](https://github.com/gopala-kr/DL-on-Silicon)
- [SpikeNN](https://github.com/gopala-kr/Quantum-Dots/blob/5f678284a308292a44fa7578814860528c5e1d04/05-BCI_Neuromorphic/SpikeNN.md)

## What is not covered here?

Several closely related adjacent areas are not covered here:

- AI for compilers, see [awesome-machine-learning-in-compilers](https://github.com/zwang4/awesome-machine-learning-in-compilers)
- AI chips, see [AI-Chip](https://github.com/basicmi/AI-Chip)
- AI for software engineering, see [Allamanis survey](https://ml4code.github.io/) and [former src-d survey](https://github.com/src-d/awesome-machine-learning-on-source-code)

## Existing paper surveys

- Li et al. [The Deep Learning Compiler: A Comprehensive Survey](https://arxiv.org/pdf/2002.03794.pdf) (Beihang & Tsinghua Universities. arXiv, 2020)
  > To the best of our knowledge, this is the first paper that provides a comprehensive survey on the design of DL compiler.

## Samsung papers

We pay special attention to papers devoted to products of Samsung company.

### Samsung NPU architecture
- Song J. et al. [7.1 An 11.5 TOPS/W 1024-MAC butterfly structure dual-core sparsity-aware neural processing unit in 8nm flagship mobile SoC](https://ieeexplore.ieee.org/abstract/document/8662476) (Samsung. **ISSCC**, 2019)
- Ignatov A. et al. [AI benchmark: All about deep learning on smartphones in 2019](https://arxiv.org/pdf/1910.06663.pdf) (ETHZ, Google, Samsung, Huawei, Qualcomm, MediaTek, Unisoc. **ICCVW**, 2019)
  > we evaluate the performance and compare the results of all chipsets from Qualcomm, HiSilicon, Samsung, MediaTek and Unisoc that are providing hardware acceleration for AI inference

### Samsung NPU compiler
- Das S. et al. [A Systolic Dataflow Based Accelerator for CNNs](https://ieeexplore.ieee.org/abstract/document/9180403) (Samsung. **ISCAS**, 2020)
