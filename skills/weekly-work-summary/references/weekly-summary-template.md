# 周报精简模板

Use this reference when writing Chinese weekly reports from rough notes.

## Default Output

```markdown
# 本周工作总结

## 一、整体情况

本周主要围绕【核心工作1】、【核心工作2】和【核心工作3】开展工作。

通过【内测/联调/核对/沟通】发现，当前主要问题集中在：【问题1】、【问题2】、【问题3】。其中，【最大风险】可能影响【验收/演示/上线/联调目标】。

下周将优先推进【动作1】、【动作2】和【动作3】，并持续跟进【外部依赖或待确认事项】。

## 二、本周完成事项

1. 完成【事项】，当前状态为【结果】，后续需【下一步】。
2. 与【系统/团队/厂商】完成【联调/沟通/确认】，剩余【风险或待办】。
3. 针对【验收/演示/生产环境】完成【准备动作】。

## 三、主要问题与风险

1. 【问题】仍待确认，影响【功能闭环/验收/演示/上线】，下一步需【处理动作】。
2. 【外部系统/厂商】尚未【接入/协调/进场】，需持续跟进【责任方】。
3. 【平台/部署/数据】存在【风险】，需确认【方案】。

## 四、下周计划

1. 保障【演示/验收/联调/上线】。
2. 根据【内测/招标文件/联调结果】调整【功能/信息项/页面】。
3. 跟进【未接入/未协调/未确认】事项。

## 五、后续待办事项

### 1. 部署相关

1. 【环境/系统/域名/硬件/网络】需【动作】，预计【时间】。

### 2. 对接相关

1. 【系统】当前【状态】，需【下一步】。

### 3. 开发相关

1. 【功能】需【开发/优化/验证】，依赖【条件】。

## 六、系统对接情况汇总

| 状态 | 系统 | 说明 |
|---|---|---|
| 已完成 | 【系统】 | 【剩余验证或生产事项】 |
| 进行中 | 【系统】 | 【阻塞或下一步】 |
| 未接入 | 【系统】 | 待厂商接入 |
| 未协调 | 【系统】 | 对接范围或数据内容待确认 |

## 七、总结

本周主要完成【成果】，当前重点已从【阶段A】转向【阶段B】。下周需重点推进【优先级1】和【优先级2】，降低【主要风险】对后续验收或交付的影响。
```

## Phrasing Patterns

- Raw: "测试不够充分，细节问题较多"
  Polished: "当前测试覆盖仍不充分，细节问题较多，需结合招标文件和演示路径继续验证。"

- Raw: "业务逻辑不能闭环"
  Polished: "当前业务逻辑尚未闭环，演示时存在解释风险，需优先调整。"

- Raw: "总包还没有推进"
  Polished: "相关事项已同步总包，目前总包反馈尚未推进，后续需持续跟进协调进度。"

- Raw: "未接入总线"
  Polished: "该系统尚未接入总线，需推动厂商明确接入计划，并在条件具备后开展联调。"

- Raw: "需要确认是否需要"
  Polished: "该事项仍待确认，需明确是否纳入本阶段范围及后续处理方式。"

## Project Delivery Checklist

When polishing project delivery weekly notes, check whether the report covers:

- tender or contract compliance;
- demo readiness and demo data;
- acceptance or supervisor inspection risk;
- production environment testing;
- external system integration status;
- owner, total contractor, vendor, or platform dependencies;
- deployment issues such as OS replacement, Redis, Nginx, domain names, network exposure, hardware resources, and operations handover.
