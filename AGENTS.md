# AGENTS.md

本仓库使用 ChatGPT + Codex + GitHub PR 的协作流程。

## 核心原则

用户是最终决策者。
ChatGPT 负责规划和审查。
Codex 负责实现和提交 PR。
GitHub 负责记录代码、分支、提交和 Pull Request。

## 分支规则

每个任务必须从 main 分支创建新分支。

分支命名格式：

task_编号_简短名

示例：

task_001_readme_intro

## 提交规则

提交前必须运行：

git status

禁止直接使用：

git add .

只允许添加本次任务相关文件。

commit message 格式：

task_编号: 简短说明

示例：

task_001: add ai workflow section

## PR 规则

每个任务完成后必须创建 Pull Request 到 main。

PR 描述必须包含：

1. 任务目标
2. 修改了哪些文件
3. 没有修改哪些范围
4. 如何验证
5. handoff 文件路径
6. 是否存在遗留问题

## Handoff 规则

每个任务完成后，必须在 docs/handoff/ 下创建一份交接记录。

handoff 文件命名格式：

task_编号_简短名.md

handoff 内容必须包含：

- 任务目标
- 本次修改
- 修改文件
- 未修改范围
- 验证方式
- 遗留问题
- 下一步建议

## 安全规则

不要提交无关文件。
不要提交视频、压缩包、临时文件、缓存文件。
不要提交密钥、token、密码、API key。
不要修改与任务无关的文件。
