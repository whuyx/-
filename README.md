# DDPM 数学推导

这是一篇关于去噪扩散概率模型（Denoising Diffusion Probabilistic Models, DDPM）数学原理的中文推导文章。

文章重点包括：

- 正向扩散过程的定义
- 多步加噪闭式公式的推导
- 贝叶斯公式在反向后验中的使用
- 真实反向后验 \(q(\mathbf{x}_{t-1}\mid \mathbf{x}_t,\mathbf{x}_0)\) 的详细推导
- 变分下界（ELBO）的展开
- KL 散度如何转化为均方误差
- 噪声预测目标与采样公式

## 文件说明

- `DDPM数学推导.pdf`：文章 PDF 版本
- `ddpm_math_principles_detailed_latex.txt`：LaTeX 源文本，保存为 `.txt` 格式

## 说明

本文用于学习和交流 DDPM 的数学基础，尽量以较详细的步骤解释公式来源，适合对扩散模型原理感兴趣的读者阅读。
