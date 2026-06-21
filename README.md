# Real-World English Practice

一个用于 Codex 的英语实战练习 skill。它通过真实问题模拟来练英语：先设定场景，再指定训练焦点，然后进行有边界的角色扮演、即时纠错、结束复盘，并可把复盘归档到飞书文档。

## 内容

- `real-world-english-practice/`：Codex skill 目录，可复制到 `~/.codex/skills/` 使用。
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

## 飞书文档

使用说明文档已同步到飞书：

https://my.feishu.cn/docx/Dw7ldwtE6oAruGxHC5gcVrPznuP

练习复盘主文档：

https://my.feishu.cn/docx/SpqLdhXe1o8TNYxqp5WcDTvbnkf
