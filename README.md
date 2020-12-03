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

### Architecture
- Song J. et al. [An 11.5 TOPS/W 1024-MAC butterfly structure dual-core sparsity-aware neural processing unit in 8nm flagship mobile SoC](https://ieeexplore.ieee.org/abstract/document/8662476) (Samsung Electronics, Hwaseong & SAIT. **ISSCC**, 2019)
- Kim Y.D. et al. [A 7nm High-Performance and Energy-Efficient Mobile Application Processor with Tri-Cluster CPUs and a Sparsity-Aware NPU](https://ieeexplore.ieee.org/abstract/document/9062907) (Samsung Electronics, Hwaseong. **ISSCC**, 2020)
- Chae D., Kapoor P. [Centralized Generic Interfaces in Hardware/Software Co-design for AI Accelerators](https://dl.acm.org/doi/pdf/10.1145/3387940.3392225) (Samsung Research. **ICSEW**, 2020)
- Hwang J. et al. [Low Power SOC Based on High Density MIM Capacitor for beyond Moore Era by Robust Power Integrity Achievement](https://ieeexplore.ieee.org/abstract/document/9159268) (Samsung S.LSI. **ECTC**, 2020)
- Lee H. et al. [Extracting power supply current profile by using interposer-based low-noise probing technique for PDN design of high-density POP](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9159523) (Samsung S.LSI. ECTC, 2020)
- Hwang S. et al. [Effective Substrate Thermal Conductivity Modeling Method Extracted from Detailed Pattern for Premium SOC Packages](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9190556) (Samsung Electronics, Hwaseong. **ITherm**, 2020)

### Comparison
- Ignatov A. et al. [AI benchmark: All about deep learning on smartphones in 2019](https://arxiv.org/pdf/1910.06663.pdf) (ETHZ, Google, Samsung, Huawei, Qualcomm, MediaTek, Unisoc. **ICCVW**, 2019)
  > we evaluate the performance and compare the results of all chipsets from Qualcomm, HiSilicon, Samsung, MediaTek and Unisoc that are providing hardware acceleration for AI inference
- Lee M.Y. et al. (in Korean) [Trends in AI Processor Technology](https://www.koreascience.or.kr/article/JAKO202056463863281.pdf) (ETRI. **Electronics and Telecommunications Trends**, 2020)
  - compares Apple, Huawei, Samsung, Qualcomm, MediaTek, ARM, CEVA, Gyrfalcon & Hailo processors

### Compiler
- Das S. et al. [A Systolic Dataflow Based Accelerator for CNNs](https://ieeexplore.ieee.org/abstract/document/9180403) (Samsung. **ISCAS**, 2020)

### Verification
- Bhattacharya S. et al. [Countering Acoustic Adversarial Attacks in Microphone-equipped Smart Home Devices](https://dl.acm.org/doi/pdf/10.1145/3397332) (Samsung AI Center & Cambridge. **IMWUT**, 2020)
  - cites a Song et al paper describing Samsung NPU device
- Jung J., Park J., Kumar A. [A Verification Framework of Neural Processing Unit for Super Resolution](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9027227) (Samsung Research. MTV, 2019)

### Optimization
- Oh J. et al. [Weight Equalizing Shift Scaler-Coupled Post-training Quantization](https://arxiv.org/pdf/2008.05767.pdf) (Samsung Research. arXiv, 2020)


## Benchmarks

- [AI Benchmark](http://ai-benchmark.com/) - benchmark for DNN tasks on Mobile phones
