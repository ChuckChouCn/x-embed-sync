# X/Twitter 推文嵌入

> 粘贴推文链接，自动变成 Markdown；互动数据实时同步。专为 Obsidian 打造。

**一个工具，干两件事：**

1. **粘贴即转换** — 把 X/Twitter 链接粘贴进笔记，自动抓取并转成 Markdown 正文嵌入，不再留个裸链接
2. **数据实时同步** — 打开笔记时自动刷新互动数据（点赞 / 转发 / 浏览），数字不过期

## 安装

从 [Releases](https://github.com/ChuckChouCn/x-embed-sync/releases) 下载 `main.js`、`manifest.json`、`styles.css` 三个文件，放进 vault 的 `.obsidian/plugins/x-embed-sync/`，在「设置 → 第三方插件」里启用即可。

## 使用

粘贴推文链接 → 自动嵌入。命令面板可「保存推文为笔记」「解析已有链接」「下载远程媒体」。

其他能力：长文（X 文章）渲染、线程重构、翻译、引用推文、媒体本地下载、社区备注、作者聚合页——全部可在设置里开关。

## 隐私

只请求被抓取的推文 ID，无遥测、无分析、不上传你的笔记。

## License

[MIT](LICENSE)。本仓库为 [MathieuLohr/x-twitter-post-embed](https://github.com/MathieuLohr/x-twitter-post-embed) 的增强版 fork。
