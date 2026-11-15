# 姜圣涛 · Jiang Shengtao

**Python · 数据分析 · 机器学习 · AI 数据工具**

围绕实际问题构建可复现的个人项目，关注数据质量、指标口径与可追溯的分析结果。

## 项目导航

以下链接直接进入已实现的升级分支，包含运行说明与演示数据。相关 Pull Request 尚未合并到主分支。

| 项目 | 解决的问题 | 主要技术 |
| --- | --- | --- |
| **[电商数据分析](https://github.com/ddnevergiveu/data-analysis/tree/codex/reproducible-analytics-20261114)** | 订单指标、RFM 客户分群、月度留存与离线报告 | Python · pandas · Matplotlib |
| **[客户价值与复购预测](https://github.com/ddnevergiveu/machine-learning-project1/tree/codex/customer-ml-upgrade-20261114)** | 使用历史行为预测未来窗口的高价值客户和复购 | scikit-learn · Pipeline · 模型评估 |
| **[行情数据与策略研究](https://github.com/ddnevergiveu/stock-da/tree/codex/market-research-toolkit-20261114)** | 行情校验、增量入库、SQL 分析与含成本的均线回测 | Python · SQLite · 时间序列 |
| **[Evidence Data Copilot](https://github.com/ddnevergiveu/data-analysis/tree/codex/evidence-data-copilot-20261114/projects/evidence-data-copilot)** | 分析问题 → 受检 SQL → 数据库计算 → 可重放结果 | MCP · DuckDB · SQLGlot · Pydantic |

## 近期技术项目 · Evidence Data Copilot

可独立安装的数据分析工具，位于 `data-analysis/projects/evidence-data-copilot`。

- 通过 MCP 提供数据结构与只读查询工具。
- 内置六类离线规则问题，可选本机 Ollama 结构化规划。
- 校验 SQL 结构与访问范围，限制执行时间和返回行数。
- 导出 JSON / Markdown，保留执行语句、数据指纹与证据 ID。
- 通过 `verify` 重放查询，复核保存的结果。

[项目与快速开始](https://github.com/ddnevergiveu/data-analysis/tree/codex/evidence-data-copilot-20261114/projects/evidence-data-copilot) · [查看 PR #2](https://github.com/ddnevergiveu/data-analysis/pull/2)

## 工程实践

**数据口径清晰** · **自动测试与 GitHub Actions** · **命令行运行** · **合成演示数据** · **结果与方法边界说明**

## 更新记录

[电商分析升级](https://github.com/ddnevergiveu/data-analysis/pull/1) · [客户预测升级](https://github.com/ddnevergiveu/machine-learning-project1/pull/1) · [行情研究升级](https://github.com/ddnevergiveu/stock-da/pull/1)

## 学习资源

[Microsoft · Machine Learning for Beginners](https://github.com/microsoft/ML-For-Beginners)
