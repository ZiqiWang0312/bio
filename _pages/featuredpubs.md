---
layout: archive
title: "Featured Publications"
permalink: /feapub/
author_profile: true
---

  <li>
    <strong>Online Workload Scheduling for Social Welfare Maximization in the Computing Continuum</strong><br/>
    <em>IEEE Transactions on Services Computing (TSC), 2025</em>
    <div>
        <a href="https://ZiqiWang0312.github.io/bio/files/TSC.pdf" target="_blank">[PDF]</a><br/>
        Citation: H. Zhao Z. Wang, G. Cheng, W. Qian, P. Chen, J. Yin, S. Dustdar, and S. Deng, "Online Workload Scheduling for Social Welfare Maximization in the Computing Continuum," IEEE Transactions on Services Computing, doi: 10.1109/TSC.2025.3570845.<br/>
    </div>
    <div style="line-height: 1.8;">  </div>
    <p style="text-align: justify; font-weight: bold;"> 
    Computing ecosystems are shifting toward a computing continuum paradigm designed to handle the diverse and dynamic nature of computing resources spread across various locations. It demonstrates significant potential in providing high-bandwidth and low-latency services for users. However, as a large number of users request services from distributed computing continuum systems, it is critical to schedule numerous delay-sensitive, fractional workloads and maximum parallelism-bound jobs to appropriate backend resources, e.g., cloud container instances. In addition, the scheduling strategy also needs to maximize the social welfare that incorporates the utilities of jobs and the revenue of service providers. However, current workload scheduling algorithms are based on simple heuristics and lack performance guarantees. Due to the unpredictability of online requests, the distribution of requests should not be assumed. Therefore, designing an online workload scheduling strategy without assumptions on request distributions is essential for balancing the online workload. This work first establishes a spatiotemporal integrated resource pool to reflect the computational resources provided by distributed computing continuum systems. Then, several pseudo-social welfare functions and marginal cost functions are constructed, where the latter is used to estimate the marginal cost of provisioning services to each newly arrived job based on the current resource surplus. We propose an online workload scheduling strategy named \( \texttt{OnSocMax} \) to solve the above problems. It operates by following the solutions to several convex pseudo-social welfare maximization problems and is proven to be \( \alpha \)-competitive for some \( \alpha \) with a value of at least 2. The evaluation results demonstrate that \( \texttt{OnSocMax} \) outperforms several benchmark strategies in maximizing social welfare. </p><br/>
    <div style="text-align:center;">
        <img src="https://ZiqiWang0312.github.io/bio/files/OnSocMax_framework.svg" alt="Framework Overview" width="600"/>
    </div>
  </li>