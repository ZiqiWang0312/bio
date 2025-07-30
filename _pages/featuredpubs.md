---
layout: archive
title: "Featured Publications"
permalink: /feapub/
author_profile: true
---

<li style="margin-bottom: 2rem; line-height: 1.8;">
  <strong>Online Workload Scheduling for Social Welfare Maximization in the Computing Continuum</strong><br/>
  <em>IEEE Transactions on Services Computing (TSC), 2025</em>
  <a href="https://ZiqiWang0312.github.io/bio/files/TSC.pdf" target="_blank" style="margin-left:8px;">[PDF]</a>
  
  <div style="font-size:0.95em; margin-top:0.3rem;">
    Citation: H. Zhao Z. Wang, G. Cheng, W. Qian, P. Chen, J. Yin, S. Dustdar, and S. Deng, 
    "Online Workload Scheduling for Social Welfare Maximization in the Computing Continuum," 
    IEEE Transactions on Services Computing, doi: 10.1109/TSC.2025.3570845.
  </div>

  <p style="text-align: justify; font-weight: bold; margin-top: 0.8rem; margin-bottom: 1rem;"> 
    Computing ecosystems are shifting toward a computing continuum paradigm designed to handle the diverse 
    and dynamic nature of computing resources spread across various locations. It demonstrates significant 
    potential in providing high-bandwidth and low-latency services for users. However, as a large number of 
    users request services from distributed computing continuum systems, it is critical to schedule numerous 
    delay-sensitive, fractional workloads and maximum parallelism-bound jobs to appropriate backend resources, 
    e.g., cloud container instances. In addition, the scheduling strategy also needs to maximize the social 
    welfare that incorporates the utilities of jobs and the revenue of service providers. However, current 
    workload scheduling algorithms are based on simple heuristics and lack performance guarantees. Due to the 
    unpredictability of online requests, the distribution of requests should not be assumed. Therefore, 
    designing an online workload scheduling strategy without assumptions on request distributions is essential 
    for balancing the online workload. This work first establishes a spatiotemporal integrated resource pool 
    to reflect the computational resources provided by distributed computing continuum systems. Then, several 
    pseudo-social welfare functions and marginal cost functions are constructed, where the latter is used to 
    estimate the marginal cost of provisioning services to each newly arrived job based on the current resource 
    surplus. We propose an online workload scheduling strategy named \( \texttt{OnSocMax} \) to solve the above 
    problems. It operates by following the solutions to several convex pseudo-social welfare maximization 
    problems and is proven to be \( \alpha \)-competitive for some \( \alpha \) with a value of at least 2. 
    The evaluation results demonstrate that \( \texttt{OnSocMax} \) outperforms several benchmark strategies in 
    maximizing social welfare.
    <div style="text-align:center; margin-top: 0.5rem;">
        <img src="https://ZiqiWang0312.github.io/bio/files/OnSocMax_framework.svg" alt="Framework Overview" width="600" style="margin:0;"/>
    </div>
  </p>
</li>




<li style="margin-bottom: 2rem; line-height: 1.8;">
  <strong>Self-adaptive Teaching-learning-based Optimizer with Improved RBF and Sparse Autoencoder for Complex Optimization Problems</strong><br/>
  <em>2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom</em>
  <a href="https://ZiqiWang0312.github.io/bio/files/ICRA2.pdf" target="_blank" style="margin-left:8px;">[PDF]</a>
  
  <div style="font-size:0.95em; margin-top:0.3rem;">
    Citation: J. Bi, Z. Wang, H. Yuan, J. Qiao, J. Zhang and M. Zhou, "Self-adaptive Teaching-learning-based Optimizer with Improved RBF and Sparse Autoencoder for Complex Optimization Problems," 2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom, 2023, pp. 7966-7972.
  </div>

  <p style="text-align: justify; font-weight: bold; margin-top: 0.8rem; margin-bottom: 1rem;"> 
  Evolutionary algorithms are commonly used to solve many complex optimization problems in such fields as robotics, industrial automation, and complex system design. Yet, their performance is limited when dealing with high-dimensional complex problems because they often require enormous computational resources to yield desired solutions, and they may easily trap into local optima. To solve this problem, this work proposes a Self-adaptive Teaching-learning-based Optimizer with an improved Radial basis function model and a sparse Autoencoder (STORA). In STORA, a Self-adaptive Teaching-learning-based Optimizer is designed to dynamically adjust parameters for balancing exploration and exploitation during its solution process. Then, a sparse autoencoder (SAE) is adopted as a dimension reduction method to compress search space into lower-dimensional one for more efficiently guiding population to converge towards global optima. Besides, an Improved Radial Basis Function model (IRBF) is designed as a surrogate model to balance training time and prediction accuracy. It is adopted to save computational resources for improving overall performance. In addition, a dynamic population allocation strategy is adopted to well integrate SAE and IRBF in STORA. We evaluate it by comparing it with several state-of-the-art algorithms through six benchmark functions. We further test it by applying it to solve a real-world computational offloading problem.
    <div style="text-align:center; margin-top: 0.5rem;">
        <img src="https://ZiqiWang0312.github.io/bio/files/STORA_framework.svg" alt="Framework Overview" width="600" style="margin:0;"/>
    </div>
  </p>
</li>


<li style="margin-bottom: 2rem; line-height: 1.8;">
  <strong>Long-Term Water Quality Prediction With Transformer-Based Spatial-Temporal Graph Fusion</strong><br/>
  <em>IEEE Transactions on Automation Science and Engineering</em>
  <a href="https://ZiqiWang0312.github.io/bio/files/TASE.pdf" target="_blank" style="margin-left:8px;">[PDF]</a>
  
  <div style="font-size:0.95em; margin-top:0.3rem;">
    Citation: J. Bi, Z. Wang, H. Yuan, X. Wu, R. Wu, J. Zhang and M. Zhou, "Long-Term Water Quality Prediction With Transformer-Based Spatial-Temporal Graph Fusion," IEEE Transactions on Automation Science and Engineering, vol. 22, pp. 11392-11404, Jan. 2025.
  </div>

  <p style="text-align: justify; font-weight: bold; margin-top: 0.8rem; margin-bottom: 1rem;"> 
  Over the past decades of rapid development, the global water pollution problem became prominent. Accurate water quality prediction can detect the trend and anomaly of water quality changes in advance, thereby taking timely measures to avoid water quality problems. Traditional statistical methods for water quality prediction tend to fail to capture the complex relationship among multiple water quality variables. Deep learning models face a challenge to capture both temporal dependence and spatial correlation of the water quality series data. To solve the above problems, this work proposes an adaptive and dynamic graph fusion water quality prediction model based on a spatiotemporal attention mechanism named \underline{S}patial-\underline{T}emporal \underline{G}raph \underline{F}usion \underline{T}ransformer (STGFT). It integrates a spatial attention encoder, a temporal attention encoder, an adaptive dynamic adjacency matrix generator, and a multi-graph fusion layer. Among them, the first two are adopted to capture the spatial correlations and temporal characteristics among different water quality monitoring stations, respectively. The generator can produce adaptive and dynamic adjacency matrices to reflect potential spatial relationships in a river network. Experimental results with real-life water quality datasets reveal that the prediction accuracy of STGFT outperforms the existing state-of-the-art models.
    <div style="text-align:center; margin-top: 0.5rem;">
        <img src="https://ZiqiWang0312.github.io/bio/files/STGFT_framework.svg" alt="Framework Overview" width="600" style="margin:0;"/>
    </div>
  </p>
</li>