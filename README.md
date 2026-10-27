# AI 话题深挖

围绕一个具体关键词（公司、产品、技术、事件）拉出 AITOP 的话题聚合视图：AI 综述、共现话题、首次出现时间与相关报道。用于“XX 这事儿到底怎么回事”“帮我梳理一下 XX 这条线”“XX 和 YY 有什么关系”“XX 最早什么时候出现的”“关于 XX 的资料都给我”等需要跨条目串联的请求。只想看某个词最新几条新闻请用 ai-news。

| | |
|---|---|
| 版本 | `1.7.0` |
| 站点 | [https://airebao.com](https://airebao.com)（AI热报） |
| SkillHub | https://skillhub.cn/skills/user_507a5056/ai-topic |
| 仓库 | https://github.com/Airebao/ai-topic |

## 安装

```bash
skillhub install ai-topic
```

也可以直接把 `SKILL.md` 放进你的 skill 目录——它是完整的 skill 正文，
里面写明了 Base URL、请求头和参数约定。

## 文件

- `SKILL.md` — skill 正文（frontmatter 的 `name` / `description` 即安装入口）
- `_meta.json` — 发布元数据（slug / version / displayName / summary / license / edition）

## 相关

- 全部 skill 索引：https://github.com/Airebao/aitop-skills
- 英文版：https://github.com/Airebao/ai-topic-en

## License

MIT
