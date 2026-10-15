<div align="center">

<p>
  <a href="./README.md">English</a> · <strong>中文</strong>
</p>

# 胡天禹

对 AI 和软件工程感兴趣，正在通过开源项目积累经验。

[![GitHub](https://img.shields.io/badge/GitHub-lonelyhty-181717?style=for-the-badge&logo=github)](https://github.com/lonelyhty)
[![Public PRs](https://img.shields.io/badge/公开%20PR-31-181717?style=for-the-badge)](https://github.com/search?q=is%3Apr+author%3Alonelyhty+is%3Apublic&type=pullrequests)
[![Merged PRs](https://img.shields.io/badge/已合并%20PR-15-2da44e?style=for-the-badge)](#已合并的-pr)
[![Open PRs](https://img.shields.io/badge/开放%20PR-11-0969da?style=for-the-badge)](#其他提交)
[![Project Stars](https://img.shields.io/badge/参与项目%20stars-2.63M%2B-f9c513?style=for-the-badge&logo=github)](#项目数据)

</div>

你好，我是胡天禹，GitHub 上叫 `lonelyhty`。我对 AI 工具和软件开发感兴趣，正在通过参与开源熟悉实际项目。这里放了一些我做过的代码修复和文档维护。

截至 **2026 年 10 月 15 日**，我向 27 个项目提交了 **31 个公开 PR**：**15 个已合并**，11 个仍开放，5 个已关闭且未合并。已经合并的 PR 分布在 13 个项目中。

## 做过的两个代码修复

### lobsters 的标题搜索

在 lobsters 中，`title:xz` 这样的查询原来不能被正确解析。关键词太短时，还可能触发不合适的标题全文搜索。

我修改了 Ruby 解析器和后续的查询处理，让短关键词仍然归到标题搜索中，并给出更清楚的提示。同时补上了解析和搜索相关的回归测试，提交时运行的 **109 个 RSpec 测试全部通过**。

已合并：[lobsters #2053](https://github.com/lobsters/lobsters/pull/2053)

### Logisim 的数值编辑器

在 Windows 的一些显示缩放设置下，Logisim 的引脚数值编辑窗口会把输入框裁掉一部分。

我调整了输入框的布局和边距，让十进制和浮点数编辑器都能留出合适的空间。改动在 Java Swing 界面代码中，提交前通过了 Gradle 编译和 Checkstyle 检查。

已合并：[logisim-evolution #2629](https://github.com/logisim-evolution/logisim-evolution/pull/2629)

## 已合并的 PR

<details>
<summary><strong>展开全部 15 个 PR，涉及 13 个项目</strong></summary>

| 项目 | Stars / Forks | 具体改了什么 | PR |
| --- | ---: | --- | --- |
| [lobsters/lobsters](https://github.com/lobsters/lobsters) | 4,852 / 993 | 修复短标题关键词的解析和查询处理，补充相关测试。 | [#2053](https://github.com/lobsters/lobsters/pull/2053) |
| [logisim-evolution/logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) | 7,774 / 1,034 | 调整数值编辑器的布局，解决输入框显示不全的问题。 | [#2629](https://github.com/logisim-evolution/logisim-evolution/pull/2629) |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | 20,633 / 2,922 | 更新 Pydantic Evals 文档中 Ragas 项目的链接。 | [#5759](https://github.com/pydantic/pydantic-ai/pull/5759) |
| [xLLM-AI/xllm](https://github.com/xLLM-AI/xllm) | 1,601 / 311 | 修正中文 README 中许可证链接的相对路径。 | [#1634](https://github.com/xLLM-AI/xllm/pull/1634) |
| [dipakkr/awesome-ai-engineering](https://github.com/dipakkr/awesome-ai-engineering) | 22,385 / 4,835 | 清理失效链接，更新 UCI、Weaviate Academy 和 Hugging Face 资源地址。 | [#1498](https://github.com/dipakkr/awesome-ai-engineering/pull/1498) |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | 519,268 / 37,479 | 把 AppImage 资源列表的链接更新到当前地址。 | [#4229](https://github.com/sindresorhus/awesome/pull/4229) |
| [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 399,089 / 66,921 | 更新几处交互式编程教程的链接，直接指向迁移后的页面。 | [#13292](https://github.com/EbookFoundation/free-programming-books/pull/13292) |
| [vinta/awesome-python](https://github.com/vinta/awesome-python) | 327,559 / 28,929 | 更新 Python 资源清单中已迁移的项目链接。 | [#3177](https://github.com/vinta/awesome-python/pull/3177) |
| [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) | 286,757 / 36,615 | 移除失效的 Scotch 教程，更新 DigitalOcean 教程和 Write You A Scheme 的链接。 | [#875](https://github.com/practical-tutorials/project-based-learning/pull/875)、[#876](https://github.com/practical-tutorials/project-based-learning/pull/876) |
| [MunGell/awesome-for-beginners](https://github.com/MunGell/awesome-for-beginners) | 90,281 / 8,022 | 从新手项目清单的 JSON 数据中移除两个已归档项目。 | [#2034](https://github.com/MunGell/awesome-for-beginners/pull/2034) |
| [enaqx/awesome-react](https://github.com/enaqx/awesome-react) | 74,910 / 7,672 | 更新 React 资源清单中的仓库地址。 | [#1736](https://github.com/enaqx/awesome-react/pull/1736) |
| [qazbnm456/awesome-web-security](https://github.com/qazbnm456/awesome-web-security) | 13,901 / 1,841 | 修复 GitHub Enterprise 安全资料和 OWASP Juice Shop 的链接。 | [#182](https://github.com/qazbnm456/awesome-web-security/pull/182)、[#183](https://github.com/qazbnm456/awesome-web-security/pull/183) |
| [firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions) | 56,361 / 111,066 | 按项目的入门流程，给贡献者名单加上自己的名字。 | [#118084](https://github.com/firstcontributions/first-contributions/pull/118084) |

</details>

## 其他提交

下面这 **11 个 PR** 还没有合并，目前仍是开放状态，涉及 9 个项目。

<details>
<summary><strong>AI 与开发工具</strong></summary>

| 项目 | Stars / Forks | 具体改了什么 | PR |
| --- | ---: | --- | --- |
| [thu-HZML/SmartPaste](https://github.com/thu-HZML/SmartPaste) | 6 / 2 | 去掉写死在代码里的开发者本机 Live2D 模型路径。 | [#131](https://github.com/thu-HZML/SmartPaste/pull/131) |
| [kalinplus/baoyan_teacher_search](https://github.com/kalinplus/baoyan_teacher_search) | 0 / 1 | 修正 Scholar 客户端重试时的超时设置，与现有测试保持一致。 | [#1](https://github.com/kalinplus/baoyan_teacher_search/pull/1) |
| [tingyunaiai9/345-ai-assistant](https://github.com/tingyunaiai9/345-ai-assistant) | 7 / 1 | 让搜索功能正确地从环境变量读取 SerpApi 密钥。 | [#1](https://github.com/tingyunaiai9/345-ai-assistant/pull/1) |
| [Goldentrii/AgentRecall-X](https://github.com/Goldentrii/AgentRecall-X) | 371 / 58 | 修复同步目录在不同操作系统上的路径处理问题。 | [#19](https://github.com/Goldentrii/AgentRecall-X/pull/19) |
| [qhy991/Awesome-LLM-Kernel-Agent](https://github.com/qhy991/Awesome-LLM-Kernel-Agent) | 21 / 2 | 修正 README 中的徽章和论文引用链接。 | [#2](https://github.com/qhy991/Awesome-LLM-Kernel-Agent/pull/2) |

</details>

<details>
<summary><strong>教程与资源整理</strong></summary>

| 项目 | Stars / Forks | 具体改了什么 | PR |
| --- | ---: | --- | --- |
| [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 553,346 / 51,886 | 补充 WebRTC 教程，更新已迁移的教程仓库链接。 | [#1792](https://github.com/codecrafters-io/build-your-own-x/pull/1792)、[#1793](https://github.com/codecrafters-io/build-your-own-x/pull/1793) |
| [Hack-with-Github/Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) | 122,656 / 10,838 | 修复贡献者名单里的个人主页链接。 | [#218](https://github.com/Hack-with-Github/Awesome-Hacking/pull/218) |
| [prakhar1989/awesome-courses](https://github.com/prakhar1989/awesome-courses) | 71,904 / 8,449 | 修正 Cornell CS3152 课程链接，更新清单中的 GitHub 地址。 | [#387](https://github.com/prakhar1989/awesome-courses/pull/387)、[#388](https://github.com/prakhar1989/awesome-courses/pull/388) |
| [tiimgreen/github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) | 59,673 / 5,458 | 修复 Git and GitHub Secrets 演讲的链接。 | [#386](https://github.com/tiimgreen/github-cheat-sheet/pull/386) |

</details>

## 项目数据

表中的 star 和 fork 数量记录于 **2026 年 10 月 15 日**。上面列出的 22 个项目合计有 **2,633,355 stars（263 万+）**，其中已合并 PR 涉及的 13 个项目合计有 **1,825,371 stars（182 万+）**，每个项目只计算一次。这里的 star 都是项目本身收到的收藏数。

完整记录：[全部 PR](https://github.com/search?q=is%3Apr+author%3Alonelyhty+is%3Apublic&type=pullrequests) · [已合并](https://github.com/search?q=is%3Apr+author%3Alonelyhty+is%3Apublic+is%3Amerged&type=pullrequests) · [仍开放](https://github.com/search?q=is%3Apr+author%3Alonelyhty+is%3Apublic+is%3Aopen&type=pullrequests)

## 接下来

想继续多做一些 AI 工具相关的代码贡献，比如配置、测试和跨平台兼容方面的问题，也慢慢熟悉这些项目背后的设计。

欢迎交流，也欢迎对上面的 PR 提建议。

更多记录：[开源贡献整理](./OPEN_SOURCE_RESUME.md)
