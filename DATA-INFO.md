# 数据说明

## 数据来源

- 官方网站：http://fzjh.xiaohoutiaotiao.com/list/12
- 总公告数：145条
- 已处理：152条（2019年1月 - 2026年6月）

## 更新类型说明

| 类型 | 说明 |
|------|------|
| 新增 | 新武学、新招式、新残页的上线 |
| 调整 | 武学数值、效果、冷却时间等的平衡性调整 |
| 重构 | 武学招式的重新设计，通常伴随动画和效果的全面更新 |
| 修复 | 武学相关的Bug修复 |

## 数据文件

| 文件名 | 说明 |
|--------|------|
| `updatelog.md` | 武学更新记录（按时间线整理） |
| `martial_arts_updates_full.json` | 完整的结构化武学更新数据 |
| `martial_arts_updates.json` | 简化版数据 |
| `DATA-INFO.md` | 本文件，数据说明 |

## 数据结构（JSON）

```json
{
  "metadata": {
    "totalAnnouncements": 145,
    "processedAnnouncements": 40,
    "extractionDate": "2026-06-19",
    "source": "http://fzjh.xiaohoutiaotiao.com"
  },
  "martialArtsUpdates": [
    {
      "date": "YYYY-MM-DD",
      "title": "更新标题",
      "url": "公告链接",
      "martialArts": [
        {
          "name": "武学名称",
          "type": "新增/调整/修复/重构",
          "description": "具体变化描述"
        }
      ]
    }
  ]
}
```

## 后续计划

- [ ] 补充2021年及更早的更新记录（剩余59条公告）
- [ ] 添加武学分类标签（拳脚、兵器、轻功、内功、暗器等）
- [ ] 添加门派分类标签
- [ ] 添加武学获取方式说明

