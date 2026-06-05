---
source: https://github.com/datawhalechina/learn-world-model
date: 2026-06-05
tags: [world-model, tutorial, datawhale, rl, rssm, dreamer]
---

# Learn World Model — Datawhale

> 从直觉到实现：世界模型理论 + 5 个实战项目，中英双语

## 基本信息

| 项目 | 详情 |
|------|------|
| **组织** | Datawhale China |
| **Star** | 173 |
| **许可证** | MIT |
| **语言** | TypeScript (VitePress) |
| **在线版** | [datawhalechina.github.io/learn-world-model/](https://datawhalechina.github.io/learn-world-model/) |
| **状态** | Alpha Preview |

## 课程结构

### 5 讲理论 (Lectures)

| # | 标题 | 核心内容 |
|---|------|----------|
| L01 | Internal Simulation & Historical Context | Craik 心智模型、预测编码、世界模型四阶段演进史 |
| L02 | Observation Encoding & Latent Dynamics | VAE、CNN Encoder、ELBO、GRU → MDN-RNN → RSSM |
| L03 | Architecture Patterns & Planning | 七种架构族、CEM-MPC、latent Actor-Critic、TD-MPC |
| L04 | Evaluation by World Model | FID、reward correlation、consistency loss、PSNR、horizon drift |
| L05 | Frontier Debates | Language vs physical grounding、Bitter Lesson、AGI |

### 5 个实战项目 (Projects)

| # | 项目 | 内容 |
|---|------|------|
| P01 | Train a VAE Encoder | 64×64 像素小 CNN VAE，ELBO loss 曲线，latent slider |
| P02 | Build an RSSM Dynamics Model | GRU/MDN-RNN/RSSM 对比，prior vs posterior rollout |
| P03 | Train a Dreamer Agent | 完整 Dreamer 训练循环 |
| P04 | Swap the Dynamics Backbone | 用因果 Transformer 替代 RSSM (STORM 风格) |
| P05 | World Model Evaluation Dashboard | 多模型指标对比：FID、reward correlation、PSNR、latent drift |

## 推荐学习路径

L01 → L02 → P01 → P02 → L03 → P03 → P04 → L04 → P05 → L05

## 为什么值得关注

- **国内最系统的世界模型教程**：从理论（RSSM/Dreamer）到实践（5个项目）全链路
- **中英双语**：适合学习 + 输出
- **与具身智能强相关**：RSSM/Dreamer/TD-MPC 是 World Models + 机器人决策的核心方法

_Last updated: 2026-06-05_
