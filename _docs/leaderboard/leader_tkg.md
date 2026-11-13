---
title: Leaderboards for TKG Link Property Prediction
permalink: /docs/leader_tkg/
---

### Check leaderboards for
#### - [tkgl-smallpedia](#tkgl-smallpedia)
#### - [tkgl-polecat](#tkgl-polecat)
#### - [tkgl-icews](#tkgl-icews)
#### - [tkgl-wikidata](#tkgl-wikidata)

The **bold** method name indicates that the implementation is **official** (by the author of the original paper). <br/>
**Package** denotes the required package version for each dataset to be eligible for the leaderboard.


<a name="tkgl-smallpedia"/>
-------

### Leaderboard for [tkgl-smallpedia](../tkg/#tkgl-smallpedia)
##### The MRR score on the test and validation sets. The higher, the better.

#### Package: >=2.0.0

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **TRACE (per-timestamp)**  | 0.661 ± 0.002 | 0.690 ± 0.001 | [Ken Wu (Independent researcher)](mailto:wooqianghao@gmail.com) | [Paper](https://github.com/KenWuqianghao/trace-tgb/blob/main/report/TRACE-report.pdf), [Code](https://github.com/KenWuqianghao/trace-tgb) | Nov. 13th, 2026 |
|  2  |  **Recurrency Baseline(train)**  | 0.655 | 0.694 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  3  |  **CountTRuCoLa**  | 0.644 ± 0.001   | 0.666 ± 0.001 | [Julia Gastinger (University of Mannheim)](mailto:julia.gastinger@uni-mannheim.de) | [Paper](https://arxiv.org/pdf/2509.09474), [Code](https://github.com/JuliaGast/counttrucola_submission) | Nov 13th, 2026 |
|  4  |  **CEN**  | 0.612 ± 0.001   | 0.646 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://aclanthology.org/2022.acl-short.32.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  5  |  **TLogic**  | 0.595 ± 0.001   | 0.631 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://cdn.aaai.org/ojs/20330/20330-13-24343-1-2-20220628.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  6  |  **RE-GCN**  | 0.594 ± 0.001   | 0.631 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://dl.acm.org/doi/10.1145/3404835.3462963), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  7  |  **Recurrency Baseline(default)**  | 0.570 | 0.640 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  8  |  **EdgeBank(tw)**  |  0.353 | 0.457 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  9  |  **EdgeBank(unlimited)**  |  0.333 | 0.401 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |




<a name="tkgl-polecat"/>
-------

### Leaderboard for [tkgl-polecat](../tkg/#tkgl-polecat)
##### The MRR score on the test and validation sets. The higher, the better.

#### Package: >=2.0.0

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **CountTRuCoLa**  | 0.256 ± 0.001 | 0.262 ± 0.001 | [Julia Gastinger (University of Mannheim)](mailto:julia.gastinger@uni-mannheim.de) | [Paper](https://arxiv.org/pdf/2509.09474), [Code](https://github.com/JuliaGast/counttrucola_submission) | Nov 13th, 2026 |
|  2  |  **TRACE (per-timestamp)**  | 0.250 ± 0.001 | 0.258 ± 0.001 | [Ken Wu (Independent researcher)](mailto:wooqianghao@gmail.com) | [Paper](https://github.com/KenWuqianghao/trace-tgb/blob/main/report/TRACE-report.pdf), [Code](https://github.com/KenWuqianghao/trace-tgb) | Nov. 13th, 2026 |
|  3  |  **TLogic**  | 0.228 ± 0.001   | 0.236 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://cdn.aaai.org/ojs/20330/20330-13-24343-1-2-20220628.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  4  |  **Recurrency Baseline(train)**  |  0.198 | 0.203 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  5  |  **CEN**  | 0.184 ± 0.002   | 0.204 ± 0.002 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://aclanthology.org/2022.acl-short.32.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  6  |  **RE-GCN**  | 0.175 ± 0.002   | 0.191 ± 0.003 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://dl.acm.org/doi/10.1145/3404835.3462963), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  7  |  **Recurrency Baseline(default)**  | 0.167 | 0.170 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  8  |  **EdgeBank(tw)**  |  0.056  | 0.058 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  9  |  **EdgeBank(unlimited)**  |  0.045 | 0.048 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |





<a name="tkgl-icews"/>
-------

### Leaderboard for [tkgl-icews](../tkg/#tkgl-icews)
##### The MRR score on the test and validation sets. The higher, the better.

#### Package: >=2.0.0

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **CountTRuCoLa**  | 0.214 ± 0.001 | 0.333 ± 0.001 | [Julia Gastinger (University of Mannheim)](mailto:julia.gastinger@uni-mannheim.de) | [Paper](https://arxiv.org/pdf/2509.09474), [Code](https://github.com/JuliaGast/counttrucola_submission) | Nov 13th, 2026 |
|  2  |  **Recurrency Baseline(train)**  | 0.211 | 0.270 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  3  |  **Recurrency Baseline(default)**  | 0.206 | 0.264 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://arxiv.org/abs/2404.16726), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  4  |  **CEN**  | 0.187 ± 0.003  | 0.244 ± 0.002 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://aclanthology.org/2022.acl-short.32.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  5  |  **TLogic**  | 0.186 ± 0.001   | 0.287 ± 0.001 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://cdn.aaai.org/ojs/20330/20330-13-24343-1-2-20220628.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  6  |  **RE-GCN**  | 0.182 ± 0.003   | 0.232 ± 0.003 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://dl.acm.org/doi/10.1145/3404835.3462963), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  7  |  **EdgeBank(tw)**  |  0.020  | 0.020 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  8  |  **EdgeBank(unlimited)**  |  0.009 | 0.008 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |






<a name="tkgl-wikidata"/>
-------

### Leaderboard for [tkgl-wikidata](../tkg/#tkgl-wikidata)
##### The MRR score on the test and validation sets. The higher, the better.

#### Package: >=2.0.0

| Rank  | Method | Test MRR | Validation MRR | Contact | References | Date 
|:----:|:-----:|:------:|:-----:|:-----:|:-----:|-----:|
|  1  |  **CountTRuCoLa**  | 0.609 ± 0.001 | 0.708 ± 0.001 | [Julia Gastinger (University of Mannheim)](mailto:julia.gastinger@uni-mannheim.de) | [Paper](https://arxiv.org/pdf/2509.09474), [Code](https://github.com/JuliaGast/counttrucola_submission) | Nov 13th, 2026 |
|  2  |  **EdgeBank(tw)**  |  0.535  | 0.633 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |
|  3  |  **EdgeBank(unlimited)**  |  0.535 | 0.632 | [TGB team](mailto:shenyang.huang@mail.mcgill.ca) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/d49042a5d49818711c401d34172f9900-Paper-Datasets_and_Benchmarks.pdf), [Code](https://github.com/JuliaGast/TGB2) | June 11th, 2024 |







