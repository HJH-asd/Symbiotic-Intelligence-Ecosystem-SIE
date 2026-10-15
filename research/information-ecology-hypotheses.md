# Information ecology hypotheses / 信息生态假设 — v0.5

**All hypotheses are unverified. 所有假设均未验证。** Define task-relative *effective information* operationally, not as a universal scalar.

| ID | Hypothesis / 假设 | Experimental contrast / 对照 | Falsification signal / 反证信号 |
|---|---|---|---|
| IE1 | Under matched resources and nonstationary tasks, independently exploring agents may retain more useful recovery strategies than a fully homogenized population. / 相同资源与变化任务下，独立探索可能保留更多恢复策略。 | Independent vs cloned policies; hold total compute, observations and communication budget fixed. / 独立策略对照同质策略。 | No recovery benefit across preregistered shifts, or costs dominate. / 未观察到收益或成本占优。 |
| IE2 | Displacement of alternate models can reduce post-shock reachable capabilities despite improved current-task performance. / 排挤替代模型可能使当前表现提高而冲击后能力下降。 | Prune vs archive-and-validate vs protected-active alternatives. / 删除、归档验证、保留活跃备选。 | Pruned systems match or outperform alternatives on withheld shocks. / 删除组在未见冲击中不逊色。 |
| IE3 | Preserving interpretable structure and interfaces improves transfer across substrates more than preserving uninterpretable bytes alone. / 保存结构与接口比仅保留字节更利于跨载体迁移。 | Port algorithms across different simulators/hardware abstractions. / 跨平台迁移。 | No improvement under equal effort and resources. / 相同成本下无改进。 |
| IE4 | Independent, noncaptured feedback channels improve detection of shared-model errors. / 不受同一控制源支配的反馈通道可能改善共同模型错误识别。 | Independent vs centrally filtered feedback with equivalent signal budgets. / 独立与集中筛选反馈。 | No error-detection improvement or excess false alarms negate gains. / 无收益或误报代价过大。 |
| IE5 | Some integration and redundancy removal improve both present efficiency and future capability. / 某些整合和去重能同时提高当前效率与未来能力。 | Compare selective integration with indiscriminate preservation. / 有选择整合对照无差别保存。 | Integration consistently reduces future capability under test. / 整合持续损害未来能力。 |

## Proposed metrics / 建议指标
- Present-task utility and resource cost / 当前任务效用与资源成本
- Shock recovery time, performance regret, and catastrophic failure rate / 冲击恢复时间、性能遗憾与严重故障率
- Coverage of withheld task families and independently validated novel solutions / 未见任务覆盖率与独立验证的新解
- Number of *functionally distinct* surviving strategies, not raw copies / 功能上不同的策略数，而非副本数
- Cross-platform transfer success and reconstruction cost / 跨平台迁移成功率与重建成本
- Independent error-detection rate and false positives / 独立纠错检出率与误报率
- Reachability estimated by feasible actions under bounded compute/time, not claimed exact universal set / 以资源受限下可行行动近似可达空间，不宣称精确计算宇宙范围

## Experimental hygiene / 实验约束
Pre-register environments and unseen shocks; use matched budgets, multiple random seeds, confidence intervals, sensitivity analysis, and ablations. Include centralized, decentralized, and hybrid baselines; report negative results. Keep all propagation simulations sandboxed and non-executable outside controlled environments. / 预注册环境和未见冲击，匹配资源，多随机种子与置信区间，进行敏感性与消融分析；比较集中、分布与混合基线并报告负结果；传播风险仅在安全隔离环境中研究。
