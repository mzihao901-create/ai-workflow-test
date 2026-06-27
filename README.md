# ai-workflow-test

这是一个用于测试 ChatGPT + Codex + GitHub PR 协作流程的仓库。
## 当前目标

跑通一个最小流程：

1. ChatGPT 负责拆任务和审查 PR。
2. Codex 负责修改代码并提交 PR。
3. GitHub 负责保存代码、分支、提交和 PR。
4. 用户负责决定合并还是打回。

## 协作规则

每个任务都应该：

1. 从 main 分支开始。
2. 新建任务分支。
3. 修改任务相关文件。
4. 创建 Pull Request。
5. 在 docs/handoff/ 目录下写交接记录。
