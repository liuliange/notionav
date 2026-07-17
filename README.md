# notionav

一个使用 Notion API 作为后端的书签导航网站。

## Features

- 📚 使用 Notion 数据库管理链接
- 🎨 支持多种主题
- 🔍 实时搜索
- 📱 响应式设计
- ⚡ 基于 Next.js 14，高性能

## Environment Variables

| Variable | Description |
|----------|-------------|
| `NOTION_TOKEN` | Your Notion Integration Token |
| `NOTION_LINKS_DB_ID` | The ID of your links database |
| `NOTION_WEBSITE_CONFIG_ID` | The ID of your config database |
| `NOTION_CATEGORIES_DB_ID` | The ID of your categories database |

## Notion Database Setup

Create three databases in Notion:

1. **Links** - Store all your bookmarks
2. **Config** - Site settings
3. **Categories** - Category management

## Development

```bash
pnpm install
pnpm dev
```

## Tech Stack

- Next.js 14
- Tailwind CSS
- Notion API
- TypeScript

---

Thanks to [moyuguy/notion_bookmarks](https://github.com/moyuguy/notion_bookmarks) for the original project.

Made with ❤️ using Next.js, Tailwind CSS, and Notion API
