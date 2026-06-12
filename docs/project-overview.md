# orbit 项目说明

- 更新时间：`2026-06-08T18:00:05.741370+00:00`
- 项目路径：`<PROJECT_ROOT>`
- GitHub private：`<PRIVATE_REPO>` (enabled)
- GitHub public：`YaofeiHe/orbit-public`
- Feishu 长期文档同步：`enabled`

## 项目定位

`orbit` 是由 Nexus 管理的项目，要求同时维护完整需求主文档、项目说明文档、操作指南、飞书记录和受控同步能力。

## 项目命名说明

- 项目当前使用名称 `orbit`，因为用户在初始化输入中已明确指定该项目名。
- 名称校验：用户显式指定的项目 slug，已通过路径安全校验；不适用真实五字母英文词规则。

## 文档体系

- `docs/intent/original-requirement.md`：原始需求归档。
- `docs/intent/normalized-requirement.md`：完整规范化需求主文档。
- `docs/project-overview.md`：项目说明文档。
- `docs/operation-guide.md`：操作指南。
- `docs/feishu-records.md`：飞书同步记录。

## 当前目录结构摘要

- `docs/`
- `.nexus/`
- `.github/`

## 关键运行与同步约束

- 长期文档默认同步到飞书，并复用已有线上文档绑定。
- GitHub private 是默认同步能力；GitHub public 仍需要显式确认。
- 任何超出安全边界的自动化动作都必须先审批。
