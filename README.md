# 你好，我是 jjh-python667

[个人作品集](https://jjh-python667.github.io/) · [案头办公 Agent](https://github.com/jjh-python667/antou-office-agent)

我是一名大一学生，正在学习 Python，也在尝试把 AI 工具用到自己的学习项目中。

目前更关注：把小项目跑起来、理解代码为什么这样写、遇到问题后能复现并修复。项目会如实标注参考来源和 AI 辅助开发情况。

## 主要项目

### [资讯台 · Newsdesk](https://github.com/jjh-python667/newsdesk)

自己的 AI、科技与商业资讯收件箱，部署在 Cloudflare Workers 与 D1。

- 内置 25 个 RSS / Atom 来源，定时采集、分类搜索、收藏和已读同步。
- 来源限流与超时有限重试，单源失败隔离，保留最近尝试和最近成功诊断。
- 原生浏览器开场与滚动动效，适配手机、深色和减少动态效果。
- 新版前端 24 项本地模拟接口回归通过；线上实例仅本人可登录，36氪采集存在来源拦截限制。

[查看源码](https://github.com/jjh-python667/newsdesk) · [项目介绍与本地演示截图](https://jjh-python667.github.io/projects/newsdesk.html)

### [案头 · ANTOU Office Agent](https://github.com/jjh-python667/antou-office-agent)

**v3.2 · 本地办公助手原型**。角色助手用于讨论与写作，执行 Agent 连续调用文件工具，处理资料、汇总 Excel 并生成 Word。

- Python、SQLite、原生前端、GSAP；预设 7 种模型接入方式。
- 支持正文流式显示、任务停止、上下文预算、本机会话与任务历史。
- Windows / Linux 各 47 项自动测试通过，包含模拟上游与应用进程重启续接；真实云端 Key 联调和 Office 应用内版式验收待补。
- 在 AI 助手辅助下开发、审查和验证，保留版本说明与能力边界；公开仓库不包含办公资料、运行数据库或密钥。

[查看源码](https://github.com/jjh-python667/antou-office-agent) · [项目介绍与真实本地截图](https://jjh-python667.github.io/projects/antou-office-agent.html) · [v3.2 改动说明](https://github.com/jjh-python667/antou-office-agent/blob/main/CHANGES-v3.2.md)


### [学习搭子 · Personal Learning Agent](https://github.com/jjh-python667/personal-learning-agent)

**v0.4.0 · 当前公开版本**。通过网页和官方 QQ 机器人使用自己的资料库，按步骤完成讲解、出题、答题和继续学习。

- Python、FastAPI、SQLite、DeepSeek API。
- 支持 PDF、DOCX、TXT、Markdown 的文字导入。
- 保存课程、会话与学习任务，支持暂停与继续，并记录实际工具执行结果。
- v0.4.0 增加邀请登录和按用户隔离的资料与进度，详见已合入的 PR #1。
- 代码、测试与部署使用 AI 助手辅助，能力边界和验证范围写在仓库 README 中。

[查看源码](https://github.com/jjh-python667/personal-learning-agent) · [第一版发布记录](https://github.com/jjh-python667/personal-learning-agent/releases/tag/v0.1.0)

### [大肥鱼 · 雨酱](https://github.com/jjh-python667/yujiang-deepseek)

基于 DeepSeek 工作台和开源 SurfCore 搭建的个人 AI 助手，接入 QQ、B 站和本地桌宠。我用 AI 助手协助部署、排错和验收，重点练习跨平台接入和本地服务运维。

- QQ 接入文字、表情和语音，已验证两套语音都能送达。语音模型按需启动，空闲时释放资源。
- B 站接入回复和 @ 监听，已验证从真实 @ 触发助手到原评论下回复。学习流程结合字幕与抽帧。
- 接入豆包 Seedream 生图。跨平台记忆按来源管理，QQ 私聊仅以脱敏主题摘要参与同步。

已按 MIT 许可开源 QQ / OneBot 登录账号校验和 B 站收件箱读取两项组件。

[查看项目仓库](https://github.com/jjh-python667/yujiang-deepseek) · [查看开源组件与使用方法](https://github.com/jjh-python667/yujiang-deepseek/blob/main/docs/open-source.md)

## 学习记录与练习

- [python-learning](https://github.com/jjh-python667/python-learning)：从基础语法和简单练习开始的 Python 学习记录。
- [star-wars-mini](https://github.com/jjh-python667/star-wars-mini)：参考教材完成的 Pygame 射击小游戏练习。
- [grokbot-workflow-notes](https://github.com/jjh-python667/grokbot-workflow-notes)：个人 AI 工具工作流的概念笔记。

## 接下来想做

- 把 Python 基础补扎实，能自己解释和修改关键代码。
- 为学习 Agent 增加有实际用途的测试，继续修复真实使用中的问题。
- 保留学习过程和参考来源，不把尚未验证的能力写成已经完成。

欢迎交流学习过程，或到项目的 Issues 提出问题。
