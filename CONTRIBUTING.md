# 贡献指南

首先，感谢你考虑为 HenosisLab 做出贡献！

## 如何贡献

### 报告 Bug

在提交 Bug 报告前，请先搜索现有 Issues 避免重复。

使用提供的 Bug 报告模板，包含：
- 预期行为和实际行为
- 复现步骤
- 环境信息（OS、版本等）
- 日志或截图（如适用）

### 提出功能建议

我们欢迎新功能的想法。请使用功能请求模板，说明：
- 这个功能解决什么问题
- 你建议的解决方案
- 替代方案（如果有）

### 提交代码

1. Fork 相关仓库
2. 创建功能分支：`git checkout -b feature/amazing-feature`
3. 提交更改：`git commit -m 'feat: add amazing feature'`
4. 推送到分支：`git push origin feature/amazing-feature`
5. 打开 Pull Request

### Commit 规范

我们采用 [Conventional Commits](https://www.conventionalcommits.org/)：

| 类型 | 说明 |
|------|------|
| `feat:` | 新功能 |
| `fix:` | Bug 修复 |
| `docs:` | 文档更新 |
| `style:` | 代码格式（不影响功能） |
| `refactor:` | 重构（不是新功能也不是修复） |
| `perf:` | 性能优化 |
| `test:` | 测试相关 |
| `chore:` | 构建/工具相关 |

示例：`feat: add memory persistence to agent`

### Pull Request 要求

- 通过所有 CI 检查
- 更新相关文档
- 添加测试（如适用）
- 保持 PR 小而聚焦

## 开发流程

### 本地环境设置

请参考每个仓库根目录的 `README.md` 或 `CONTRIBUTING.md`。

### 代码审查

所有 PR 需要至少一名维护者的批准。请耐心等待审查。

## 行为准则

参与本项目即表示你同意遵守[行为准则](CODE_OF_CONDUCT.md)。

## 问题和讨论

- [GitHub Discussions](https://github.com/orgs/henosislab/discussions)：技术讨论和想法
- [Discord](https://discord.gg/henosislab)（如有）：实时交流

感谢你让 HenosisLab 变得更好！
