# The Quasi-Riemann Hypothesis: A Zero-Free Half-Plane Re(s)>7/8（准黎曼猜想：实部大于八分之七的零点自由半平面）

**作者:** OpenAI

**日期:** 2026-09-30

本篇是准黎曼猜想结果家族中更强的版本：证明所有狄利克雷 L 函数（包括黎曼 zeta 函数）在复平面实部大于八分之七的半平面内没有零点，且对所有模数和特征一致成立。同时给出朗道–西格尔零点的均匀排除：存在常数 c>0，使得每个导子 q≥3 的本原非主实特征的 L 函数的任何实零点 β 满足 1−β≥c/log q。

## 原文链接

- PDF: https://github.com/openai/math/blob/main/preprints/The-Quasi-Riemann-Hypothesis-September-30-2026/paper.pdf

## Lean 形式化

本结果有 Lean 形式化验证，见 openai/math 仓库 lean/docs/003.md，包括：
- QuasiRiemannHypothesis.lean（zeta 函数 7/8 界）
- DirichletSevenEighths.lean（狄利克雷 L 函数 7/8 界）
- HeckeSevenEighths.lean（有限阶 Hecke L 函数 7/8 界）
- SiegelZeros.lean（均匀实零点间隙）

## 引用

```bibtex
@misc{OAI:The-Quasi-Riemann-Hypothesis-September-30-2026,
  author = {{OpenAI}},
  title = {{The Quasi-Riemann Hypothesis:
            A Zero-Free Half-Plane $\mathrm{Re}(s)>7/8$}},
  howpublished = {OpenAI Math Release preprint
                  \href{https://github.com/openai/math/blob/main/preprints/The-Quasi-Riemann-Hypothesis-September-30-2026/paper.pdf}{OAI:The-Quasi-Riemann-Hypothesis-September-30-2026}},
  year = {2026}
}
```
