# Contributing · 参与贡献

[English](#english) | [中文](#中文)

<a id="english"></a>

## English

Thanks for helping improve the playbook. Good contributions include:

- **A new scenario** — add `scenarios/<id>/README.md` and `scenarios/<id>/prompts/<bot>.md` (1 supervisor + 3–4 specialists), then add a row to both READMEs.
- **Better prompts** — keep all **7 components** (role, scope & boundaries, output format, tone, workflow, when to ask, collaboration).
- **Translations** — add a sibling file (e.g. `lead.en.md`) rather than replacing the Chinese original.

Every prompt must:

- keep anything outbound (email, posts, messages) as **drafts that wait for user confirmation**;
- forbid irreversible actions (sending, paying, trading, deleting, committing to terms) without the user;
- never fabricate facts — mark unknowns as "unknown" / 【待核实】;
- write only to its own folder under `/workspace/shared/<team>/<bot>/`;
- avoid invented product menu paths — describe setup generically (create bot → paste prompt as description → connect tools → set routines).

Before opening a PR, check that relative links resolve and that the scenario's acceptance criteria are checkable item by item.

<a id="中文"></a>

## 中文

欢迎贡献：

- **新场景**：新增 `scenarios/<id>/README.md` 与 `scenarios/<id>/prompts/<bot>.md`（1 个主管 + 3–4 个专员），并在两份 README 的场景表中各加一行。
- **改进提示词**：保持 **7 个部分**齐全（角色定位、任务范围与边界、输出格式、语气、工作流程、何时询问用户、与其他 bot 的协作）。
- **翻译**：新增同名文件（如 `lead.en.md`），不要覆盖中文原版。

每份提示词必须：

- 对外内容（邮件、帖子、消息）只出**草稿，等用户确认**；
- 发送、付款、交易、删除、合同承诺等不可逆操作先问用户；
- 不编造事实，拿不到的写"未知"或【待核实】；
- 只写自己的目录 `/workspace/shared/<名称>/<bot>/`；
- 不编造产品菜单路径，配置步骤用通用说法（创建 bot → 粘贴提示词为描述 → 连接工具 → 设置例行任务）。

提交 PR 前，请确认相对链接可用、验收标准可逐条打勾。
