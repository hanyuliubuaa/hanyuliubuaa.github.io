---
permalink: /pub/
title: "📄学术成果"
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
      <strong>Hanyu Liu</strong>, Xiucong Sun, Jinghao Yang, Ming Xu（徐明教授，长江学者）, Shengzhou Bai.<br>
      Skewed Unscented Kalman Filter Using Gaussian Sum.<br>
      <em>IEEE Transactions on Aerospace and Electronic Systems</em>, vol. 61, no. 2, pp. 3917-3935, April 2025.
      (JCR: Q1; IF: 5.7)
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
      (JCR: Q1; IF: 5.7)
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
      (JCR: Q1; IF: 2.8)
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
      (JCR: Q2; IF: 3.9)
    </p>

    <p>
      <a href="https://ieeexplore.ieee.org/document/10884033/">[HTML]</a>
    </p>

  </div>
</div>
本文提出了第一个无监督训练（不需要状态真值）的完全基于神经网络的状态估计方法，也是第一个基于Transformer的滤波方法。无需EKF的线性化假设、UKF的高斯假设、PF的大量粒子，即可实现高精度状态估计。本文方法的估计误差为EKF的32.22%，UKF的77.70%，PF的74.40%，计算效率与UKF相当。
<hr>