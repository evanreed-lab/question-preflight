# 提问检查与澄清 · Question Preflight

[English](#english)

**刚开始用 AI，知道自己想做什么，却不确定怎么开口？** 《提问检查与澄清》主要面向刚开始用 AI、还在摸索怎么描述任务的使用者，尤其适合用 AI 改稿、整理信息或比较方案时试用。

技能启用后，你可以用平时说话的方式提问。它会结合前文理解你的目标。意思已经清楚时，直接回答。几种理解都说得通时，可以分情况回答。如果选错方向会影响结果，它会问一个能决定下一步的问题。你也可以从这些追问里看出，下次主动说清哪一点能省掉来回确认。

## 一个例子

你贴了一份通知，说「帮我看看」。如果前文还没说清你要什么，AI 可以问「你想先听修改意见，还是希望我直接改一版？」你可以选一个，也可以补充自己的要求。

下次有类似需求，你可以直接说「帮我看看这份通知。只指出最容易让读者误解的一处，并说明原因。先保留原文。」

## 下载与安装

1. 在 [Releases](https://github.com/evanreed-lab/question-preflight/releases/latest) 下载 `question-preflight.zip`。
2. Codex 用户可解压，将 `question-preflight` 文件夹放到项目的 `.agents/skills/` 或个人的 `~/.agents/skills/`。支持自定义技能的 Claude 用户可在 Customize → Skills 上传 ZIP。
3. 启用后照常提问。支持自动匹配的客户端会自行挑选相关技能，具体哪一轮调用由客户端决定。

[中文使用说明与中英文示例](references/guide-zh.md) · [核心规则](SKILL.md)

## 按自己的习惯使用

可以直接告诉 AI「以后我发稿子说‘帮我看看’，请只指出最影响读者理解的一处」。下次想直接拿到改稿，可以说「这次直接改」。能否跨对话保存这类偏好取决于客户端。

如果 AI 猜错了、该问时没问，或者多问了一句，可以在 [Issues](https://github.com/evanreed-lab/question-preflight/issues/new) 分享一个脱敏例子。写明你怎么问、AI 怎么回答、你希望它怎么处理即可。

## English

**New to AI and unsure how to ask for what you need?** Question Preflight is an Agent Skill for people getting started with AI chat, especially when reviewing a draft, organizing information, or comparing options.

Ask in your own words. The skill uses the conversation so far to understand what you want. If your request is clear, it answers directly. If several interpretations are plausible, it can give an answer for each. When choosing the wrong one would change the result, it asks a focused question. That question can show you what to mention up front next time.

### Example

You paste a draft announcement and say, “Can you take a look?” If the context leaves your goal open, the AI can ask, “Would you like feedback first, or should I rewrite it?” You can pick one or explain what you have in mind.

Next time, you might ask, “Review this announcement. Point out the one thing readers are most likely to misunderstand, and explain why. Leave the draft as is for now.”

### Install and share feedback

Download `question-preflight.zip` from [Releases](https://github.com/evanreed-lab/question-preflight/releases/latest). In Codex, unzip it and move the `question-preflight` folder to your project's `.agents/skills/` or your own `~/.agents/skills/`. In Claude accounts with custom skills enabled, upload the ZIP under Customize → Skills. Automatic selection depends on your client. [Skill instructions](SKILL.md) · [Bilingual examples](references/guide-zh.md)

If the AI guessed wrong, missed a question, or asked an unnecessary one, share an example with personal details removed. Include what you asked, what the AI did, and what you wanted it to do. [Open an issue](https://github.com/evanreed-lab/question-preflight/issues/new)

## License

[MIT](LICENSE)
