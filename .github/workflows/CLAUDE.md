# workflows/
> L2 | 父级: ../CLAUDE.md

成员清单
actionlint.yml: 复用上游规则检查 workflow 语法。
autobump.yml: 定时或按请求更新 Cask 版本。
cache.yml: 仅 Homebrew 上游预热 Gems；矩阵为 macos-15、macos-26 与 ubuntu-latest，缓存键按 runner 隔离。
check-issues.yml: 复用上游 Issue 检查。
check-prs.yml: 复用上游 PR 检查。
ci-retry.yml: 重试失败的 CI job。
ci.yml: 验证 Cask 变更。
clean-up-closed-prs.yml: 清理已关闭 PR 的附属状态。
google-fonts.yml: 同步 Google Fonts Cask。
remove-disabled-packages.yml: 移除已禁用的软件条目。
scheduled.yml: 定时执行在线检查。
stale-issues-and-prs.yml: 复用上游闲置 Issue 与 PR 规则。
triage.yml: 执行 PR 分流任务。

[PROTOCOL]: 变更时更新此头部，然后检查 CLAUDE.md
