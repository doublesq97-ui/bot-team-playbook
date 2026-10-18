# 回报消息模板（专员 → 主管）· Report template

> 完成后回消息：文件路径、3 行以内摘要、逐条自检结果、未解决的问题。
> Reply with: file path, ≤3-line summary, per-criterion self-check, open issues.

```text
@<主管名> 任务已完成：「<任务>」

【文件】/workspace/shared/<名称>/<专员 id>/YYYY-MM-DD-任务名.md
【摘要】（3 行以内）
【自检】
1. <验收标准 1> —— ✅ 已满足 / ⚠️ 部分满足（原因）
【未解决问题】（如无写"无"）
```

## 规则

- 成果保存到自己的目录，文件名 `YYYY-MM-DD-简短任务名`。
- 自检逐条对应派活消息里的验收标准，不合并、不省略。
- 信息不足时先向主管提问，不要猜测。
