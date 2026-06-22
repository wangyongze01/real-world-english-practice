# Real-World English Practice

一个用于 Codex 的英语实战练习 skill。它通过真实问题模拟来练英语：先设定场景，再指定训练焦点，然后进行有边界的角色扮演、即时纠错、结束复盘，并可把复盘归档到飞书文档。

## 内容

- `real-world-english-practice/`：Codex skill 目录，可复制到 `~/.codex/skills/` 使用。
  - `SKILL.md`：核心训练流程、模式、纠错规则和复盘格式。
  - `references/scenarios.md`：扩展场景库，供需要更多场景或挑战练习时使用。
- `real-world-english-practice-usage.md`：日常使用说明和提示词模板。

## 安装

把 skill 目录复制到 Codex skills 目录：

```powershell
Copy-Item -Recurse .\real-world-english-practice "$env:USERPROFILE\.codex\skills\real-world-english-practice"
```

macOS / Linux:

```bash
cp -R ./real-world-english-practice ~/.codex/skills/real-world-english-practice
```

然后新开一个 Codex 会话，使用：

```text
用 $real-world-english-practice 陪我练一个酒店换房场景。
我的水平是中级。
本轮重点练时态。
使用标准练习模式。
```

## 训练焦点

- Comprehensive：全面练习
- Tense：时态
- Collocations：固定搭配
- Idiomatic expression：地道表达
- Conditionals/subjunctive：虚拟语气 / 条件句
- Tone and politeness：语气和礼貌
- Fluency and structure：表达结构和流畅度
- Pronunciation-oriented phrasing：口语节奏、分块和适合朗读的自然表达
- Writing clarity：写作清晰度、语气和行动导向

## 训练模式

- Warm-up：3-5 轮热身，适合快速开口
- Role-play：标准真实场景对话
- Drill：围绕一个句型或语言点反复练
- Rewrite：把一句话或一小段改得更自然
- Writing：邮件、消息、投诉、面试 follow-up 等真实写作
- Shadowing-style：给适合跟读的自然表达
- Challenge：加入拒绝、误解、协商和时间压力

## 飞书文档

使用说明文档已同步到飞书：

https://my.feishu.cn/docx/Dw7ldwtE6oAruGxHC5gcVrPznuP

练习复盘主文档：

https://my.feishu.cn/docx/SpqLdhXe1o8TNYxqp5WcDTvbnkf
