# 派活消息模板（主管 → 专员）· Handoff template

> 一条消息只派一个任务。验收标准写成能逐条打勾的条件（数量、范围、格式、来源、"不出现 X"）。
> One task per message. Acceptance criteria must be checkable item by item.

```text
@<专员名> 新任务（来自「<主管名>」）

【任务】...
【背景】...（相关文件路径）
【交付物】
- ...
【验收标准】
1. ...（可检查、可量化）
【截止时间】...
【保存路径】/workspace/shared/<名称>/<专员 id>/（文件名：YYYY-MM-DD-简短任务名）
【回报方式】完成后回复我：文件路径 + 3 行摘要 + 逐条自检结果 + 未解决问题。信息不足请先提问，不要猜测。
```

## 填写要点

- 【背景】附上相关文件的完整路径，专员从共享文件夹读取。
- 【验收标准】避免"写得好一点"这类无法验收的描述。
- 需要多人配合时分别派活，并说明先后依赖。

示例见各场景 README 中的「派活示例」，如 [`scenarios/sales/README.md`](../scenarios/sales/README.md)。
