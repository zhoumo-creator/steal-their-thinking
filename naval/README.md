# 纳瓦尔：特长 × 杠杆 × 担当

把纳瓦尔（Naval Ravikant）关于财富和判断的思维模型，做成一个可以直接装进 AI 的 Skill。它会先问你问题，再按你的情况给出分析和下一步行动。

> 根据纳瓦尔公开的推文串、播客整理稿和《纳瓦尔宝典》改写，**不是纳瓦尔本人编写，也未经他认可**。

## 三种人，三个模式

| 模式 | 适合谁 | 它帮你回答 | 最后你会拿到 |
|---|---|---|---|
| [01 · 起步](modes/01-起步-找到你的杠杆.md) | 学生、刚工作几年的人 | 我的优势是什么，从哪开始？ | 一句话特长 + 3 个零成本方案 + 7 天行动 |
| [02 · 放大](modes/02-放大-给生意加杠杆.md) | 已经有生意、但生意离不开自己的老板 | 生意卡在我身上，怎么放大？ | 时间审计 + 四种杠杆体检 + 30 / 90 天计划 |
| [03 · 照镜子](modes/03-照镜子-看清自己的判断.md) | CEO、创始人、管理者 | 我是怎么做决定的，盲点在哪？ | 镜子报告 + 三条决策规则 + 决策日志 |

不用自己选：开始时它会先问你属于哪一种。

## 怎么用

**Claude Code**

```bash
git clone https://github.com/zhoumo-creator/steal-their-thinking.git
cp -r steal-their-thinking/naval ~/.claude/skills/
```

然后对它说："用纳瓦尔的方法帮我看看……"

**其他支持 Skill 的工具**：把 `naval` 文件夹放进它的 skills 目录。

**不支持 Skill 的 AI 对话**：把 [SKILL.md](SKILL.md) 和你要用的那个模式文件一起粘贴进去，再说"按这份说明开始"。

## 文件

```
naval/
├── SKILL.md      # 入口：分流 + 共用框架 + 共用规则和红线
├── modes/        # 三个模式，各自的访谈、分析步骤和输出格式
└── quotes.md     # 可以引用的纳瓦尔原话及出处
```

## 它不会做的事

- 不承诺收入或增长，不给"月入 X 万"之类的数字
- 不鼓励借钱、贷款、炒币，不建议辞职、退学或交钱报课
- 不替你做最终决定
- 不编造纳瓦尔的话：只引用 [quotes.md](quotes.md) 里核对过的原句

## 参考来源

- 纳瓦尔，《How to Get Rich (without getting lucky)》推文串，2018-05-31：https://x.com/naval/status/1002103360646823936
- 纳瓦尔，《How to Get Rich: Every Episode》播客整理稿：https://nav.al/rich
- Eric Jorgenson 编，《纳瓦尔宝典》（The Almanack of Naval Ravikant）：https://www.navalmanack.com/
- 灵感来源：Alex Prompter 把纳瓦尔的框架做成 Skill 的帖子：https://x.com/alex_prompter/status/2066494688560058727

---

[← 返回系列首页](../README.md)
