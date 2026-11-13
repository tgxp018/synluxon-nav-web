# synluxon-nav-web

`@SynluxonBot` 菜单里「打开导航网页」按钮打开的页面。

单文件静态页：`index.html`。无构建、无依赖包。

## 部署

仓库已配好 GitHub Actions（`.github/workflows/pages.yml`），推送到 `main` 自动发布到
`https://tgxp018.github.io/synluxon-nav-web/`。

Pages 源需设为 **GitHub Actions**（Settings → Pages → Build and deployment → Source）。

## 改内容

全部在 `index.html`：

- 已上线卡片：`<a class="card" href="https://t.me/xxx">`，`data-k` 控制搜索关键词
- 筹备中列表：`<a class="row" href="https://t.me/xxx">`，上线后挪到上面并删掉 `em` 标签
- 顶部三个数字（已上线 / 筹备中 / 官方频道）手动同步
- 搜索框旁 `19 项` 与 `#hits` 的初始文案同步

## 链接清单（2026-11-14 实测）

| 服务 | 目标 |
|---|---|
| 记账对账 | `@SynluxonBooksBot` |
| 抽奖机器人 | `@SynluxonDropbot` |
| 体育比分 | `@SynluxonSportsBot` |
| 考勤助手 | `@SynluxonClockBot` |
| 音乐下载 | `@SynluxonMusicApp`（备用 `@Yinyueshebot`） |

筹备中 14 项先指向同名频道：`SynluxonPay` `Relay` `Fetch` `Flow` `Hub` `Support` `Ask` `Guard` `Drive` `Vault` `Shop` `Help` `Find` `Boss`。

- 官方频道：`https://t.me/synluxon`
- 官网：`https://synluxon.com`
