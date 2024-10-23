---
title: Leaderboards for Dynamic Link Property Prediction
permalink: /docs/leader_linkprop/
---

### Check leaderboards for
#### - [tgbl-wiki-v2](#tgbl-wiki-v2)
#### - [tgbl-review-v2](#tgbl-review-v2)
#### - [tgbl-coin-v2](#tgbl-coin-v2)
#### - [tgbl-comment](#tgbl-comment)
#### - [tgbl-flight-v2](#tgbl-flight-v2)

The **bold** method name indicates that the implementation is **official** (by the author of the original paper). <br/>
**Package** denotes the required package version for each dataset to be eligible for the leaderboard.


<a name="tgbl-wiki-v2"/>
-------

### Leaderboard for [tgbl-wiki-v2](../linkprop/#tgbl-wiki-v2)
##### **Please update your package >= `0.7.5`**. In version 2 of `tgbl-wiki`, we have included all possible negative destinations for each positive edge thus increasing the task difficulty.  For submissions, please submit to this version.  Previous version of the dataset leaderboard is [tgbl-wiki-v1](../leader_linkprop_old/#tgbl-wiki-v1). The MRR score on the test and validation sets. The higher, the better.

#### Package: >=0.7.5

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **DyGFormer**  | 0.798 ± 0.004   | 0.816 ± 0.005 | [Le Yu (Beihang University)](mailto:yule@buaa.edu.cn) | [Paper](https://openreview.net/forum?id=xHNzWHbklj), [Code](https://github.com/yule-BUAA/DyGLib_TGB) | August 22nd, 2023 |
|  2  |  **NAT**  | 0.749 ± 0.010   | 0.773 ± 0.011 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/pdf?id=EPUtNe7a9ta), [Code](https://github.com/shenyangHuang/TGB) | August 22nd, 2023 |
|  3  |  **TGR-TNCN**  | 0.724 ± 0.011  | 0.751 ± 0.005 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  4 |  **TNCN**  | 0.718 ± 0.001   | 0.741 ± 0.001 | [Xiaohui Zhang (PKU)](mailto:huihuang@stu.pku.edu.cn) | [Paper](https://arxiv.org/pdf/2406.07926), [Code](https://github.com/GraphPKU/TNCN) | August 25th, 2024 |
|  5  |  **CAWN**  | 0.711 ± 0.006   | 0.743 ± 0.004 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](http://snap.stanford.edu/caw/), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  6  |  **TGR-TGN**  | 0.589 ± 0.048  | 0.642 ± 0.047 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  7  |  **EdgeBank(tw)**  | 0.571   | 0.600 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  8  |  **EdgeBank(unlimited)**  |  0.495   |  0.527 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  9  |  **TGN**  | 0.396 ± 0.060   | 0.435 ± 0.069 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2006.10637), [Code](https://github.com/shenyangHuang/TGB) | August 7th, 2023 |
|  10  |  **TCL**  | 0.207 ± 0.025   | 0.198 ± 0.016 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2105.07944), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  11  |  **TGAT**  | 0.141 ± 0.007   | 0.131 ± 0.008 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/pdf/2002.07962.pdf), [Code](https://github.com/shenyangHuang/TGB) | August 22th, 2023 |
|  12  |  **GraphMixer**  | 0.118 ± 0.002   | 0.113 ± 0.003 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=ayPPc0SyLv1), [Code](https://github.com/shenyangHuang/TGB) | August 7th, 2023 |
|  13  |  **DyRep**  | 0.050 ± 0.017   | 0.072 ± 0.009 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=HyePrhR5KX), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |





<a name="tgbl-review-v2"/>
-------

### Leaderboard for [tgbl-review-v2](../linkprop/#tgbl-review-v2)
##### **Please update your package >= `0.7.5`**. In version 2 of `tgbl-review`, we have included 100 negative destinations for each positive edge thus increasing the task difficulty. For submissions, please submit to this version.  Previous version of the dataset leaderboard is [tgbl-review-v1](../leader_linkprop_old/#tgbl-review-v1). The MRR score on the test and validation sets. The higher, the better. 

#### Package: >=0.7.5

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **TGR-TGN**  | 0.854 ±  0.011  | 0.834 ± 0.012 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  2  |  **TGR-TNCN**  | 0.599 ± 0.045  | 0.511 ± 0.054 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  3  |  **GraphMixer**  | 0.521 ± 0.015   | 0.428 ± 0.019 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=ayPPc0SyLv1), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  4 |  **TNCN**  | 0.377 ± 0.010   | 0.325 ± 0.003 | [Xiaohui Zhang (PKU)](mailto:huihuang@stu.pku.edu.cn) | [Paper](https://arxiv.org/pdf/2406.07926), [Code](https://github.com/GraphPKU/TNCN) | August 25th, 2024 |
|  5  |  **TGAT**  | 0.355 ± 0.012   | 0.324 ± 0.006 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/pdf/2002.07962.pdf), [Code](https://github.com/shenyangHuang/TGB) | August 22th, 2023 |
|  6  |  **TGN**  | 0.349 ± 0.020   | 0.313 ± 0.012 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2006.10637), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  7  |  **NAT**  | 0.341 ± 0.020   | 0.302 ± 0.011 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/pdf?id=EPUtNe7a9ta), [Code](https://github.com/shenyangHuang/TGB) | August 22nd, 2023 |
|  8  |  **DyGFormer**  | 0.224 ± 0.015   | 0.219 ± 0.017 | [Le Yu (Beihang University)](mailto:yule@buaa.edu.cn) | [Paper](https://openreview.net/forum?id=xHNzWHbklj), [Code](https://github.com/yule-BUAA/DyGLib_TGB) | September 21st, 2023 |
|  9  |  **DyRep**  | 0.220 ± 0.030   | 0.216 ± 0.031 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=HyePrhR5KX), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  10  |  **CAWN**  | 0.193 ± 0.001   | 0.200 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](http://snap.stanford.edu/caw/), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  11  |  **TCL**  | 0.193 ± 0.009   | 0.199 ± 0.007 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2105.07944), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  12  |  **EdgeBank(tw)**  | 0.025   | 0.024 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |
|  13  |  **EdgeBank(unlimited)**  | 0.023   | 0.023 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | July 27th, 2023 |



<a name="tgbl-coin-v2"/>
-------

### Leaderboard for [tgbl-coin-v2](../linkprop/#tgbl-coin-v2)
##### **Please update your package >= `0.9.0`**. In version 2 of `tgbl-coin`, we fixed an error where a small portion of edges are not sorted chronologically. For submissions, please submit to this version.  Previous version of the dataset leaderboard is [tgbl-coin-v1](../leader_linkprop_old/#tgbl-coin-v1). The MRR score on the test and validation sets. The higher, the better. 


#### Package: >=0.9.0

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **TGR-TNCN**  | 0.783 ± 0.033  | 0.769 ± 0.025 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  2 |  **TNCN**  | 0.762 ± 0.004   | 0.740 ± 0.002 | [Xiaohui Zhang (PKU)](mailto:huihuang@stu.pku.edu.cn) | [Paper](https://arxiv.org/pdf/2406.07926), [Code](https://github.com/GraphPKU/TNCN) | August 25th, 2024 |
|  3  |  **TGR-TGN**  | 0.755 ±  0.088  | 0.734 ± 0.082 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  4  |  **DyGFormer**  | 0.752 ± 0.004   | 0.730 ± 0.002 | [Le Yu (Beihang University)](mailto:yule@buaa.edu.cn) | [Paper](https://openreview.net/forum?id=xHNzWHbklj), [Code](https://github.com/yule-BUAA/DyGLib_TGB) | November 2nd, 2023 |
|  5  |  **TGN**  | 0.586 ± 0.037   | 0.607 ± 0.014 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2006.10637), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  6  |  **EdgeBank(tw)**  | 0.580   |   0.492 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  7  |  **DyRep**  | 0.452 ± 0.046   | 0.512 ± 0.014 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=HyePrhR5KX), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  8  |  **EdgeBank(unlimited)**  | 0.359   |  0.315 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |


<a name="tgbl-comment"/>
-------

### Leaderboard for [tgbl-comment](../linkprop/#tgbl-comment)
##### The MRR score on the test and validation sets. The higher, the better.

#### Package: >=0.7.5

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **TGR-TNCN**  | 0.891 ± 0.056  | 0.899 ± 0.014 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  2  |  **TGR-TGN**  | 0.836 ±  0.079  | 0.826 ± 0.091 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  3 |  **TNCN**  | 0.697 ± 0.006   | 0.643 ± 0.003 | [Xiaohui Zhang (PKU)](mailto:huihuang@stu.pku.edu.cn) | [Paper](https://arxiv.org/pdf/2406.07926), [Code](https://github.com/GraphPKU/TNCN) | August 25th, 2024 |
|  4  |  **DyGFormer**  | 0.670 ± 0.001   | 0.613 ± 0.003 | [Le Yu (Beihang University)](mailto:yule@buaa.edu.cn) | [Paper](https://openreview.net/forum?id=xHNzWHbklj), [Code](https://github.com/yule-BUAA/DyGLib_TGB) | September 21st, 2023 |
|  5  |  **TGN**  | 0.379 ± 0.021  | 0.356 ± 0.019 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2006.10637), [Code](https://github.com/shenyangHuang/TGB) | June 7th, 2023 |
|  6  |  **DyRep**  | 0.289 ± 0.033   | 0.291 ± 0.028 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=HyePrhR5KX), [Code](https://github.com/shenyangHuang/TGB) | June 7th, 2023 |
|  7  |  **EdgeBank(tw)**  | 0.149   |  0.124 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | June 7th, 2023 |
|  8  |  **EdgeBank(unlimited)**  | 0.129  |  0.109 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | June 7th, 2023 |



<a name="tgbl-flight-v2"/>
-------

### Leaderboard for [tgbl-flight-v2](../linkprop/#tgbl-flight-v2)
##### **Please update your package >= `0.9.2`**. In version 2 of `tgbl-flight`, we fixed an error where a small portion of edges are not sorted chronologically. For submissions, please submit to this version.  Previous version of the dataset leaderboard is [tgbl-flight-v1](../leader_linkprop_old/#tgbl-flight-v1). The MRR score on the test and validation sets. The higher, the better. 

#### Package: >=0.9.2

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **TGR-TNCN**  | 0.851 ± 0.011  | 0.854 ± 0.014 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  2 |  **TNCN**  | 0.820 ± 0.004   | 0.831 ± 0.003 | [Xiaohui Zhang (PKU)](mailto:huihuang@stu.pku.edu.cn) | [Paper](https://arxiv.org/pdf/2406.07926), [Code](https://github.com/GraphPKU/TNCN) | August 25th, 2024 |
|  3  |  **TGR-TGN**  | 0.814 ±  0.023  | 0.818 ± 0.018 |[Katarina Petrović (University of Oxford)](mailto:katarina.petrovic@st-hildas.ox.ac.uk) | [Paper](https://arxiv.org/abs/2406.02362), [Code](https://github.com/kpetrovicc/TGR) | October 23rd, 2024
|  4  |  **TGN**  | 0.705 ± 0.020  | 0.731 ± 0.010 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2006.10637), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  5  |  **DyRep**  | 0.556 ± 0.014   | 0.573 ± 0.013 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=HyePrhR5KX), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  6  |  **EdgeBank(tw)**  | 0.387   |  0.363 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
|  7  |  **EdgeBank(unlimited)**  | 0.167  |  0.166 |[TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://openreview.net/forum?id=1GVpwr2Tfdg), [Code](https://github.com/shenyangHuang/TGB) | September 27th, 2023 |
