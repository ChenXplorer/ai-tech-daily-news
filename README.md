# AI Tech Daily News

用于按天保存自动抓取的 AI 与科技新闻，便于后续检索、去重、汇总和分析。

## 数据目录

新闻文件统一存放在 `data/YYYY/MM/YYYY-MM-DD.jsonl`，每行一条 JSON 记录。例如：

```text
data/2026/08/2026-08-31.jsonl
```

建议每条记录至少包含：

```json
{
  "title": "新闻标题",
  "url": "https://example.com/news",
  "source": "来源名称",
  "published_at": "2026-08-31T08:00:00+08:00",
  "fetched_at": "2026-08-31T09:00:00+08:00",
  "summary": "新闻摘要",
  "tags": ["AI", "模型"]
}
```

## 基本约定

- 文件编码使用 UTF-8。
- 时间使用带时区的 ISO 8601 格式。
- 使用原始文章 URL 去重。
- 不提交密钥、令牌或本地配置文件。

