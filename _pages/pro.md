---
permalink: /pro/
title: "🛠️项目经历"
author_profile: true
---

{% include base_path %}

<h2>期刊论文</h2>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/skew.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Xiucong Sun, Jinghao Yang, Ming Xu(徐明教授，长江学者), Shengzhou Bai.<br>
      Skewed Unscented Kalman Filter Using Gaussian Sum.<br>
      <em>IEEE Transactions on Aerospace and Electronic Systems</em>, vol. 61, no. 2, pp. 3917-3935, April 2025.
      (SCI; JCR: Q1; IF: 5.7)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/10756516">[HTML]</a>
    </p>

  </div>
</div>
本文提出了首个非高斯无迹卡尔曼滤波，利用三阶中心矩信息构造非高斯分布，克服了传统算法的高斯假设对估计精度带来的限制。飞行器目标跟踪场景的位置估计误差降低17.55%。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/MaxUKF.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Xiucong Sun, Shengzhou Bai.<br>
      Modified Unscented Kalman Filter Considering Maximum Point of Probability Density Function.<br>
      <em>IEEE Transactions on Aerospace and Electronic Systems</em>, vol. 61, no. 2, pp. 4926-4944, April 2025.
      (SCI; JCR: Q1; IF: 5.7)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/10797647">[HTML]</a>
    </p>

  </div>
</div>
本文提出了首个利用众数信息的滤波算法，提出了众数随非线性变换的准确传播定理，改进了基于确定性采样的非线性卡尔曼滤波的估计精度。飞行器目标跟踪场景的位置估计误差降低10.56%，飞行器自主导航场景的位置估计误差降低17.93%。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/MMUKF.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Xinlong Wang, Yujin Zhang, Yuhan Chen, Xiao Li, Shenggang Liu.<br>
      Mode-matching universal Kalman filter based on closed skew-normal distribution.<br>
      <em>Advances in Space Research</em>, In Press.
      (SCI; JCR: Q1; IF: 2.8)
    </p>

    <p>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0273117725003205">[HTML]</a>
    </p>

  </div>
</div>
本文改进了上一篇文章中状态概率密度函数的形式，从高斯混合模型变为闭式偏斜正态（CSN）分布，计算效率极大提高。飞行器自主导航场景的计算时间仅为传统无迹卡尔曼滤波的1.05倍，几乎无需增加计算量。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/DAF.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Xiucong Sun, Yuran Chen, Xinlong Wang.<br>
      Physics-Informed Data-Driven Autoregressive Nonlinear Filter.<br>
      <em>IEEE Signal Processing Letters</em>, vol. 32, pp. 846-850, 2025.
      (SCI; JCR: Q2; IF: 3.9)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/10884033/">[HTML]</a>
    </p>

  </div>
</div>
本文提出了第一个无监督训练（不需要状态真值）的完全基于神经网络（无需任何传统滤波框架）的状态估计方法，也是第一个基于Transformer的滤波方法。无需EKF的线性化假设、UKF的高斯假设、PF的大量粒子，即可实现高精度状态估计。本文方法的估计误差为EKF的32.22%，UKF的77.70%，PF的74.40%，计算效率与UKF相当。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/DeepUKF.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Yuran Chen, Xiucong Sun, Yukai Zhu, Xinlong Wang, Haichao Gui(桂海潮教授，神十六航天员).<br>
      Finetuning the Sample Points in Gaussian Filters via Neural Networks.<br>
      <em>IEEE Signal Processing Letters</em>, vol. 33, pp. 371-375, 2026.
      (SCI; JCR: Q2; IF: 3.9)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/11302786/">[HTML]</a>
    </p>

  </div>
</div>
本文提出了第一个用神经网络生成滤波器采样点的方法，可以提高所有基于确定性采样点的高斯滤波器（UKF，CKF，GHQF等）的估计精度。本文方法可以在不增加计算时间的前提下，将基于确定性采样点的高斯滤波器的估计误差降低5~6%。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/Space.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      Han Yan(项目甲方), <strong>Hanyu Liu</strong>(学生一作), Xiucong Sun, Ming Xu(徐明教授，长江学者).<br>
      Accuracy Evaluation of Marginalized Unscented Kalman Filter.<br>
      <em>Space: Science & Technology</em>, 2023;3:0085.
      (SCI; JCR: Q1; IF: 6.8)
    </p>

    <p>
      <a href="https://spj.science.org/doi/10.34133/space.0085">[HTML]</a>
    </p>

  </div>
</div>
本文针对传感器测量存在常值偏差的实际工程问题，分析了边缘无迹卡尔曼滤波的性质，给出了其与标准无迹卡尔曼滤波等价的充分条件，并通过飞行器自主导航场景进行了验证。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/Chinese.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      杨开伟(项目甲方), <strong>刘涵宇</strong>(学生一作), 孙腾达，孙秀聪，徐明(长江学者).<br>
      低轨导航增强卫星广播星历拟合模型研究.<br>
      <em>航天器工程</em>, 2023,32(04):28-36.
      (中文核心)
    </p>

    <p>
      <a href="https://kns.cnki.net/kcms2/article/abstract?v=MXvIvFkaDQw_XySxA-Okr7CE36CycuRHGcyPxePcy3ReDIDpJHHYKe7lWXDhfT8_h55BwZRTJhG3sAzhaQwTkzfHfx94FpHJoFcHjVIUVTcuOfXl53d45kvc2iMvbX_Mbe53mdAw2MSlfGPB7RikLyxm0wyePejd0mmtVLtiqT0udoxARyFGgQ==&uniplatform=NZKPT&language=CHS">[HTML]</a>
    </p>

  </div>
</div>
本文为我国低轨导航增强卫星设计了广播星历，相比于传统的中高轨导航卫星所使用的广播星历，本文增加了偏心率变化率参数以降低LEO大气阻力影响，位置拟合误差降低最多50%。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/Thrust.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      Shengzhou Bai, Yuan Wang, <strong>Hanyu Liu</strong>, Xiucong Sun.<br>
      Finite-thrust lambert transfer based on multistage constant-vector thrust control.<br>
      <em>IEEE Transactions on Aerospace and Electronic Systems</em>, vol. 59, no. 5, pp. 4947-4967, Oct. 2023.
      (SCI; JCR: Q1; IF: 5.7)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/10058148/">[HTML]</a>
    </p>

  </div>
</div>
本文提出了能量最优条件下的航天器变轨多阶段脉冲转有限策略。
<hr>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/ND.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      Shengzhou Bai, Yuan Wang, <strong>Hanyu Liu</strong>, Xiucong Sun.<br>
      Spacecraft fast fly-around formations design using the parallelogram configuration.<br>
      <em> Nonlinear Dynamics</em>, 113, 1041–1062 (2025).
      (SCI; JCR: Q1; IF: 6.0)
    </p>

    <p>
      <a href="https://link.springer.com/article/10.1007/s11071-024-10298-3">[HTML]</a>
    </p>

  </div>
</div>
本文提出了航天器平行四边形绕飞策略。
<hr>

<h2>会议论文</h2>
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 0px;">
  <!-- 左侧图片 -->
  <div style="flex: 0 0 35%;">
    <img src="/images/IAC.JPG" alt="sym" style="width: 100%; height: auto;">
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1;">

    <p>
      <strong>Hanyu Liu</strong>, Xiucong Sun, Haichao Gui(桂海潮教授，神十六航天员), Han Cai.<br>
      Data-Driven Orbit Determination for Low-Earth Orbit Space Debris Using Ground-Based Measurements.<br>
      <em> 76th International Astronautical Congress (IAC 2025)</em>, Sydney, Australia, 29 Sep-3 Oct 2025.
      (EI)
    </p>

    <p>
      <a href="https://doi.org/10.52202/083079-0067">[HTML]</a>
    </p>

  </div>
</div>
本文首次完全基于深度学习实现了轨道确定，且估计精度超过EKF，UKF，GMF。<br>
本人在国际宇航大会上对上述论文进行口头汇报（Oral）。
<img src="/images/Oral.jpg" alt="sym" style="width: 100%; height: auto;">
<hr>