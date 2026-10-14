<div align="center">

# 🎬 lark-contact

## 「给张三发消息」——名字先变 open_id，一步不猜错人
## From a name to the right open_id—no more messaging the wrong person

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个通讯录解析技能：按姓名或邮箱解析出 open_id，也能用 open_id 反查姓名、部门、邮箱、联系方式、个人状态和签名。它还支持按关键词搜索当前用户可见的机器人 / 智能体（agent）。当用户提到一个名字要接着发消息或排日程，或拿到 open_id 想查具体信息时使用。部门树遍历、按部门列员工、组织架构图不在范围内，这些需求走原生 OpenAPI。

### ✨ 能做什么

- 姓名 / 邮箱 → open_id，解析不到就说解析不到
- open_id → 姓名 / 部门 / 邮箱 / 联系方式 / 个人状态 / 签名
- 按关键词搜索当前用户可见的机器人 / 智能体
- 遇到「名字是人还是机器人」先做歧义判别再选命令
- 明确划出边界：部门树、按部门列员工、组织架构图不在本技能内

### 📦 包含的技能

- `lark-contact` —— 见 [`lark-contact/SKILL.md`](lark-contact/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/lark-contact.git
cp -r lark-contact/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A directory-resolution skill: turn a name or email into an open_id, and reverse-lookup open_id into name, department, email, contact details, status, and signature. It can also keyword-search the bots and agents visible to the current user. Use it when a name must become an ID before messaging or scheduling, or when an open_id needs to be resolved into real details. Department-tree traversal, listing employees by department, and org charts are out of scope—those go to the native OpenAPI.

### ✨ What it does

- Name or email → open_id, with an explicit 'not found' instead of a guess
- open_id → name, department, email, contact info, status, and signature
- Keyword-search the bots and agents visible to the current user
- Disambiguates person vs bot/agent before choosing a command
- Draws a hard boundary: department trees, per-department listings, org charts are excluded

### 📦 Skills included

- `lark-contact` — [`lark-contact/SKILL.md`](lark-contact/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/lark-contact.git
cp -r lark-contact/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
