# paper-cover-letter

一个在 **Codex** 中使用的论文投稿信 Skill。根据论文材料和目标期刊要求，生成或润色英文 Cover Letter。

## 1. 在 Codex 中安装

先安装并登录 Codex，然后在对话框发送：

```text
$skill-installer
请从 https://github.com/AphroditeYu/paper-cover-letter 仓库根目录安装 paper-cover-letter，保留完整的 Skill 文件夹。
```

安装完成后即可使用。如果无法调用，请重启 Codex 再试。安装方式参见 [Codex 官方说明](https://learn.chatgpt.com/docs/build-skills#install-curated-skills-for-local-use)。

## 2. 开始使用

在 Codex 中发送以下内容，并附上论文摘要、全文或研究要点：

```text
$paper-cover-letter
请根据我的论文材料，为 [目标期刊名称] 撰写一封英文投稿信。

论文标题：
主要发现与贡献：
期刊范围或投稿要求（链接或摘录）：
通讯作者姓名、单位和邮箱：
```

暂时缺少的信息可以留空，Codex 会提示补充。已有投稿信也可以直接附上，请它修改或润色。

## 使用提醒

研究内容应以论文为准；“未发表”“全体作者无利益冲突”等声明需由作者确认。投稿前，请核对信中的事实与声明。

[查看原始模板](assets/cover_letter_template.md) · [技能规则](SKILL.md) · [测试记录](tests/validation.md)
