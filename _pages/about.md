---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a Ph.D candidate for Electrical Science and Technology at the Department of Micro/Nano Electronics, Shanghai Jiao Tong University, Shanghai, China, and under the supervision of Professor Guanghui He. 

My current research interests are at the intersection of autonomous driving system, digital circuits and systems. The current focus is ASIC design for AI applications like BEV perception, point cloud processing, stochastic computing circuit design and massive MIMO wireless detector <a href='https://scholar.google.com/citations?user=K1JGQBIAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.01*: &nbsp;🎉🎉 One paper is accepted by IEEE TVLSI. 
- *2023.07*: &nbsp;🎉🎉 One paper is accepted by ICCAD 2023. 
- *2023.02*: &nbsp;🎉🎉 One paper is accepted by DAC 2023. 

# 📝 Publications 

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/TVLSI24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling]()

**Dongxu Lyu**$^{\ddagger}$, Zhenyu Li$^{\ddagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu, Guanghui He ($^{\ddagger}$: equal contribution)

- A grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. 
- It also demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds ($>10^6$ points in $\sim$2ms).
- **An extension of our DAC'24 paper**.
- *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DAC 2023</div><img src='images/DAC23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674)

**Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Ningyi Xu, Guanghui He 
- The first grid-based feature learning network accelerator with algorithm-architecture co-optimization. 
- It also achieves 13.4 − 43.3× speedup over RTX 2080Ti GPU.
- *2023 60th ACM/IEEE Design Automation Conference (DAC)*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2023</div><img src='images/ICCAD23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728)

**Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Jinming Zhang, Ningyi Xu, Guanghui He 
- A novel 3D sparse convolution accelerator that enables high-speed and energy-efficient point cloud processing. 
- SpOctA rivals the state-of-the-art SpConv accelerators by 1.1-6.9x speedup with 1.5-3.1x energy efficiency improvement on their benchmarks.
- *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*
</div>
</div>

## Full Pub List

### Efficient Hardware Accelerators for AI Computing (Jan. 2022 -- Present)
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](), **Dongxu Lyu**$^{\ddagger}$, Zhenyu Li$^{\ddagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu, Guanghui He ($^{\ddagger}$: equal contribution), in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Jinming Zhang, Ningyi Xu, Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023, pp. 1-9.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Ningyi Xu, Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023, pp. 1-6.
- ``ISCAS 2023`` [O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression](https://ieeexplore.ieee.org/abstract/document/10181731), Yuzhou Chen, Jinming Zhang, **Dongxu Lyu**, Xi Yu, Guanghui He, *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*, Monterey, CA, USA, 2023, pp. 1-5.

### Emerging Stochastic Computing Techniques for AI Computing (Sep. 2021 -- Present)
- ``TNANO 2024`` [Efficient Parallel Stochastic Computing Multiply-Accumulate (MAC) Technique Using Pseudo-Sobol Bit-Streams](), Aokun Hu, Wenjie Li, **Dongxu Lyu**, Guanghui He, in *IEEE Transactions on Nanotechnology*.
- ``NANOARCH 2022`` [An Efficient Stochastic Convolution Accelerator based on Pseudo-Sobol Sequences](https://dl.acm.org/doi/abs/10.1145/3565478.3572543), Aokun Hu, Wenjie Li, **Dongxu Lyu**, Guanghui He, *the 17th ACM International Symposium on Nanoscale Architectures (NANOARCH)*, pp. 1-6. 2022.

### Efficient Massive MIMO Detectors for 5G/6G Communication (Sep. 2019 -- Sep. 2021)
- ``TVLSI 2021`` [A 3.85-Gb/s 8 × 8 Soft-Output MIMO Detector With Lattice-Reduction-Aided Channel Preprocessing](https://ieeexplore.ieee.org/abstract/document/9266114), Zhuojun Liang, **Dongxu Lyu**Chao Cui, Hai-Bao Chen, Weifeng He, Weiguang Sheng, Naifeng Jing, Zhigang Mao, Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*, vol. 29, no. 2, pp. 307-320, Feb. 2021.


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.