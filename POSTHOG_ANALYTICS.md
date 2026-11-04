# PostHog Analytics · ruxiangsuisu（入乡随俗）

Project property: `ruxiangsuisu` · EU ingest · 家族共享 sbf-uid

| 事件 | 属性 | 触发 |
|------|------|------|
| `page_view` | `ref` · `sport`（pb/bd/tt） | 页面加载 |
| `sport_switch` | `to` | 切换运动 tab |
| `search_used` | — | 输入第 3 个字符时（搜索参与信号） |
| `page_leave` | `dwell_ms` · `scroll_pct` | 页面隐藏/关闭 |

分析口径：`search_used` 占比 = 工具属性验证（是查词工具还是浏览页）；`sport_switch` 分布 = 哪项运动的术语需求最大。
