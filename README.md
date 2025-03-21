# Awesome-Visual-Autoregressive-Models

A curated list of autoregressive models for visual generation, editing, understanding, etc.


## Table of Contents <!-- omit in toc -->

[//]: # (- [Basemodel]&#40;#&#41;)

- [Visual Autoregression Paradigm](#visual-autoregression-paradigm)
- [Visual Tokenizer](#Tokenizer)
- [AR-based Text-to-image Generation](#evaluation-benchmarks-and-metrics)
- [AR-based Text-to-video Generation](#evaluation-benchmarks-and-metrics)

And the ultimate one!

- [Unified Multimodal Generation & Understanding](#evaluation-benchmarks-and-metrics)



----
### Visual Autoregression Paradigm

+ Mar 2025: [Direction-Aware Diagonal Autoregressive Image Generation](https://arxiv.org/abs/2503.11129), PKU&Xiaomi, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11129)

+ Mar 2025: [Neighboring Autoregressive Modeling for Efficient Visual Generation](https://github.com/ThisisBillhe/NAR), ZJU, Shanghai AI Lab&UAdelaide [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10696)
  [![Star](https://img.shields.io/github/stars/ThisisBillhe/NAR.svg?style=social&label=Star)](https://github.com/ThisisBillhe/NAR) 

+ Mar 2025:  [Autoregressive Image Generation with Randomized Parallel Decoding](https://github.com/hp-l33/ARPG), WestlakeU&CAS, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10568)
  [![Star](https://img.shields.io/github/stars/hp-l33/ARPG.svg?style=social&label=Star)](https://github.com/hp-l33/ARPG) 

+ Mar 2025:  [NFIG: Autoregressive Image Generation with Next-Frequency Prediction](https://arxiv.org/pdf/2503.07076), TeleAI, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07076)

+ Mar 2025:  [Frequency Autoregressive Image Generation with Continuous Tokens](https://yuhuustc.github.io//projects/FAR.html), Alibaba, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05305)
 [![Star](https://img.shields.io/github/stars/yuhuUSTC/FAR.svg?style=social&label=Star)](https://github.com/yuhuUSTC/FAR)  [![Website](https://img.shields.io/badge/Website-9cf)](https://yuhuustc.github.io//projects/FAR.html)

+ Feb 2025:  [Beyond Next-Token: Next-X Prediction for Autoregressive Visual Generation](https://oliverrensu.github.io/project/xAR/), JHU&ByteDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20388)
 [![Star](https://img.shields.io/github/stars/OliverRensu/xAR.svg?style=social&label=Star)](https://github.com/OliverRensu/xAR)  [![Website](https://img.shields.io/badge/Website-9cf)](https://oliverrensu.github.io/project/xAR/)

+ Feb 2025:  [FlexVAR: Flexible Visual Autoregressive Modeling without Residual Prediction](https://github.com/jiaosiyu1999/FlexVAR), BJTU,UTS,Meituan&Georgia Tech, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20388)
 [![Star](https://img.shields.io/github/stars/OliverRensu/xAR.svg?style=social&label=Star)](https://github.com/OliverRensu/xAR)  [![Website](https://img.shields.io/badge/Website-9cf)](https://oliverrensu.github.io/project/xAR/)


+ Dec 2024: [Next Patch Prediction for Autoregressive Visual Generation](https://github.com/PKU-YuanGroup/Next-Patch-Prediction), PKU, PengCheng Lab, NUS, HKUST, UCF, Everlyn&Rabbitpre AI, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15321)
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Next-Patch-Prediction.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Next-Patch-Prediction) 

+ Dec 2024 (**CVPR25**):  [Parallelized Autoregressive Visual Generation]( https://epiphqny.github.io/PAR-project), HKU, ByteDance&PKU, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15119)
  [![Star](https://img.shields.io/github/stars/Epiphqny/PAR.svg?style=social&label=Star)](https://github.com/Epiphqny/PAR) [![Website](https://img.shields.io/badge/Website-9cf)](https://epiphqny.github.io/PAR-project/)

+ Dec 2024 (**CVPR25**):  [RandAR: Decoder-only Autoregressive Visual Generation in Random Orders](https://rand-ar.github.io/), UIUC, MIT&Adobe, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01827)
  [![Star](https://img.shields.io/github/stars/ziqipang/RandAR.svg?style=social&label=Star)](https://github.com/ziqipang/RandAR) [![Website](https://img.shields.io/badge/Website-9cf)](https://rand-ar.github.io/)


+ Nov 2024:  [Randomized Autoregressive Visual Generation](https://arxiv.org/abs/2411.00776), BetyDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00776)
  [![Star](https://img.shields.io/github/stars/bytedance/1d-tokenizer.svg?style=social&label=Star)](https://github.com/bytedance/1d-tokenizer) [![Website](https://img.shields.io/badge/Website-9cf)](https://yucornetto.github.io/projects/rar.html)


+ Apr 2024 (**NeurIPS24 Oral**):  [Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction](https://arxiv.org/abs/2404.02905), BetyDance,  **Best Paper Award** [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02905)
  [![Star](https://img.shields.io/github/stars/FoundationVision/VAR.svg?style=social&label=Star)](https://github.com/FoundationVision/VAR)

----
### Visual Tokenizer

+ Mar 2025:  [V2Flow: Unifying Visual Tokenization and Large Language Model Vocabularies for Autoregressive Image Generation](https://arxiv.org/abs/2503.07493), Du Xiaoman Financial, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07493)
  [![Star](https://img.shields.io/github/stars/zhangguiwei610/V2Flow.svg?style=social&label=Star)](https://github.com/zhangguiwei610/V2Flow)

+ Feb 2025:  [FlexTok: Resampling Images into 1D Token Sequences of Flexible Length](https://flextok.epfl.ch/), Apple&EPFL, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.13967)
 [![Website](https://img.shields.io/badge/Website-9cf)](2502.13967)

+ Dec 2024:  [Spectral Image Tokenizer](https://arxiv.org/abs/2412.09607), CMU, Adobe&MBZUAI, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09607)

+ Dec 2024:  [Infinity: Scaling Bitwise AutoRegressive Modeling for High-Resolution Image Synthesis](https://arxiv.org/abs/2412.04431), BetyDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04431)
  [![Star](https://img.shields.io/github/stars/FoundationVision/Infinity.svg?style=social&label=Star)](https://github.com/FoundationVision/Infinity) [![Website](https://img.shields.io/badge/Website-9cf)](https://foundationvision.github.io/infinity.project/)

+ Nov 2024:  [Factorized Visual Tokenization and Generation](https://showlab.github.io/FQGAN/), NUS, FDU&Amazon, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16681)
  [![Star](https://img.shields.io/github/stars/showlab/FQGAN.svg?style=social&label=Star)](https://github.com/showlab/FQGAN) [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/FQGAN/)

+ Oct 2024 (**ICLR25**):  [ImageFolder: Autoregressive Image Generation with Folded Tokens](https://arxiv.org/abs/2410.01756), BetyDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.01756)
  [![Star](https://img.shields.io/github/stars/lxa9867/ImageFolder.svg?style=social&label=Star)](https://github.com/lxa9867/ImageFolder) [![Website](https://img.shields.io/badge/Website-9cf)](https://lxa9867.github.io/works/imagefolder/index.html)

----
### AR-based Text-to-image Generation

+ Dec 2024:  [Infinity: Scaling Bitwise AutoRegressive Modeling for High-Resolution Image Synthesis](https://arxiv.org/abs/2412.04431), BetyDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04431)
  [![Star](https://img.shields.io/github/stars/FoundationVision/Infinity.svg?style=social&label=Star)](https://github.com/FoundationVision/Infinity) [![Website](https://img.shields.io/badge/Website-9cf)](https://foundationvision.github.io/infinity.project/)

+ Oct 2024:  [FLUID: Scaling AutoRegressive Text-to-image Generative Models with Continuous Tokens](https://arxiv.org/abs/2410.13863), DeepMind&MIT, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13863)

[//]: # (  [![Star]&#40;https://img.shields.io/github/stars/FoundationVision/Infinity.svg?style=social&label=Star&#41;]&#40;https://github.com/FoundationVision/Infinity&#41; [![Website]&#40;https://img.shields.io/badge/Website-9cf&#41;]&#40;https://foundationvision.github.io/infinity.project/&#41;)

----
### AR-based Text-to-video Generation

+ Oct 2024:  [Loong: Generating Minute-level Long Videos with Autoregressive Language Models](https://arxiv.org/abs/2410.02757), HKU&BetyDance, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02757)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://epiphqny.github.io/Loong-video/)


----
### Unified Multimodal Generation & Understanding
+ Mar 2025: [Unified Autoregressive Visual Generation and Understanding with Continuous Tokens](https://arxiv.org/pdf/2410.13848), DeepMind&MIT, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.13436)
  

+ Oct 2024: [Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation](https://arxiv.org/pdf/2410.13848), DeepSeek, HKU&PKU, [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04431)
  [![Star](https://img.shields.io/github/stars/deepseek-ai/Janus.svg?style=social&label=Star)](https://github.com/deepseek-ai/Janus)  [![Demo](https://img.shields.io/badge/demo-gree)](https://huggingface.co/spaces/deepseek-ai/Janus-1.3B)

