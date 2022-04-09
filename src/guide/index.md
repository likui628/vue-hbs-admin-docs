# 贡献指南

你好！很高兴你有兴趣为 [vue-hbs-admin](https://github.com/Hongbusi/vue-hbs-admin) 做贡献。在提交您的贡献之前，请务必花点时间阅读以下指南：

[[toc]]

## 开发设置

你将需要 [Node.js](https://nodejs.org) 版本 16+ 和 [pnpm](https://github.com/pnpm/pnpm)。

我们还建议安装 [ni](https://github.com/antfu/ni) 以帮助使用不同的包管理器在 repos 之间切换。`ni` 还提供了方便的 `nr` 命令，可以更轻松地运行 npm 脚本。

## 任务状态

- issue 存在 `label` 为 `Developer`、`Developer:username` 时，表示任务已被领取。
- issue 下有人留言要去做这个功能，表示任务已被领取。
- 否则，视为未被领取。

::: warning 注意
一周内未提交任何相关 PR，视为放弃任务。
:::

## 领取任务

- 项目成员：对应 issue 添加 `label`，格式为：`Developer:username`。
- 非项目成员：对应任务 issue 下留言，项目成员看见会为你添加 `label` -> `Developer`。

## 提交 PR 指南

- 如果添加新功能：
  - 在 PR 描述中添加 `close #1`。
- 如果修复错误：
  - 如果您正在解决一个特殊问题，请在您的 PR 标题中添加（#xxxx 问题 ID）以获得更好的发布日志，例如 `update entities encoding/decoding (fix #1)`。
  - 在 PR 中提供错误的详细描述。
- 在 PR 上进行多个小提交是可以的 - GitHub 可以在合并之前自动压缩它们。

## 最后

祝，编码快乐，收获满满，玩的愉快...