# 提问检查与澄清 · Question Preflight

[English](#english)

**刚开始用 AI，知道想做什么，却不确定怎么开口？** 这个 Agent Skill 让你用平时说话的方式提问，也能拿到靠谱、能用的结果。

- 问得太宽泛或疑似笔误说反：在**开头**先把更具体、清晰的问法亮出来再回答，一眼就能核对方向。
- 信息没说全：先给你一版，说明可改哪里；缺具体时间、地点、金额时留 `[待填]`，不瞎编。
- 选错会白做：默认只问一个问题（复杂任务最多合并列 3 个关键问题），附选项和推荐答案；普通任务你说「随便」就按推荐推进，外发、删除等不可逆动作必先等你明确确认。
- 涉及归因、猜动机、预测未来或方案选型：把已证实事实、预测成立条件和不同优先级下的取舍讲清楚。
- 可复用的工作任务在追问或补默认信息后，末尾附一句「💡 下次可以这样说」（开头已示范新问法或日常小问题时不打扰，说「不用提示」即可关闭）。

## 两个常见例子

- **写材料时没说全**：你说「帮我写份本月工作总结」。AI 先给一版（具体数据留 `[待填]`），末尾注明「按给直属领导看、500 字左右、分进展/问题/下月计划写的」，再附上：
  > 💡 下次可以这样说：帮我写份本月工作总结，给直属领导看，500 字左右，分进展、问题、下月计划。
- **问得太宽泛**：你贴了一段发给供应商的催货消息，问「这个怎么样？」。AI 在**开头**先亮出优化后的问法：「我按‘这条催货消息语气是否得体、截止时间和后果有没有说清’来帮你看：……」，直接给出评估与修改建议。

涵盖咨询问题、提供服务、撰写报告、简单数据分析、PPT/Word 制作、客户/供应商沟通、跨人材料交接等日常工作场景。更多示例见 [中文使用说明](references/guide-zh.md) 和 [场景示例与表达原则](references/phrasing.md)。

## 下载与安装

1. 在 [Releases](https://github.com/evanreed-lab/question-preflight/releases/latest) 下载 `question-preflight.zip`。
2. Codex：解压后把 `question-preflight` 文件夹放到 `~/.agents/skills/` 或项目的 `.agents/skills/`。Claude：在 Customize → Skills 上传 ZIP。
3. 启用后照常提问。是否在某一轮调用由客户端决定。

[中文使用说明](references/guide-zh.md) · [场景示例与原则](references/phrasing.md) · [核心规则](SKILL.md) · [更新记录](CHANGELOG.md)

如果 AI 猜错了、该问没问、多问了，或提示不合适，欢迎在 [Issues](https://github.com/evanreed-lab/question-preflight/issues/new) 分享脱敏例子：你怎么问、AI 怎么答、你希望它怎么做。

## English

**New to AI and unsure how to ask?** Question Preflight helps you get usable results from everyday requests. When it substantially reframes, narrows, or corrects a likely slip in your question, it states the sharper question right at the start before answering. If task details are missing, it delivers a first version on sensible defaults (leaving `[TBD]` placeholders for concrete facts like dates or prices) and tells you what you can change. When a wrong guess would waste work, it asks one focused question by default (or groups up to three independent gaps for complex tasks) with options and recommended defaults — while always requiring explicit confirmation before external or irreversible actions. It also states conditions on predictions and priorities on trade-offs, and adds a short "Next time you can say" tip when helpful (turn off by saying "no tips").

Download `question-preflight.zip` from [Releases](https://github.com/evanreed-lab/question-preflight/releases/latest). In Codex, move the folder to `~/.agents/skills/` or your project's `.agents/skills/`. In Claude, upload the ZIP under Customize → Skills.

## License

[MIT](LICENSE)
