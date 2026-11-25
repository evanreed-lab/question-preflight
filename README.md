# 提问检查与澄清 · Question Preflight

一个帮助 AI 理解日常提问和任务要求的 Agent Skill。遇到“帮我看看”“按刚才那个来”或“所以是它导致的吧”这类说法时，它会结合前文，判断是直接回答、分情况回答，还是只问一个会改变结果的问题。

## 下载与安装

1. 在 [Releases](https://github.com/zhzhseven-design/question-preflight/releases/latest) 下载 `question-preflight.zip`。
2. Codex 用户可解压，将 `question-preflight` 文件夹放到项目的 `.agents/skills/` 或个人的 `~/.agents/skills/`。支持自定义技能的 Claude 用户可在 Customize → Skills 上传 ZIP。
3. 启用后照常提问。支持自动匹配的客户端会自行挑选相关技能，具体哪一轮调用由客户端决定。

[中文使用说明与中英文示例](references/guide-zh.md) · [核心规则](SKILL.md)

## 按自己的习惯使用

可以直接告诉 AI「以后我发稿子说‘帮我看看’，请只指出最影响读者理解的一处」。下次想直接拿到改稿，可以说「这次直接改」。能否跨对话保存这类偏好取决于客户端。

如果 AI 猜错了、该问时没问，或者多问了一句，可以在 [Issues](https://github.com/zhzhseven-design/question-preflight/issues/new) 分享一个脱敏例子。写明你怎么问、AI 怎么回答、你希望它怎么处理即可。

## English

Question Preflight is an Agent Skill for resolving ambiguity and evidence gaps in everyday prompts. It uses preceding context, answers directly when it can, and asks a focused question when choosing the wrong interpretation would materially change the result.

Download `question-preflight.zip` from [Releases](https://github.com/zhzhseven-design/question-preflight/releases/latest) and install it in your Agent Skills client. Automatic selection depends on your client. See the [skill instructions](SKILL.md) and [bilingual examples](references/guide-zh.md).

## License

[MIT](LICENSE)
