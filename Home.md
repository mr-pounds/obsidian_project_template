---
date created: 2023-04-25 13:59:19
date modified: 2023-04-25 15:18:28
---

# Home

## 代办任务

```dataview
table dated from #todo and -"4 Extra"
```

## 启动板

您的启动板和大本营，就在这里。

### Roadmaps

| 版本号 | 产品经理 | MOC |
| ------ | -------- | --- |
| v1.0   |          |     |

### 需求 MOC

```dataview
table company, industry
from "1 Demands" and -"1 Demands/About Demands"
sort file.cday desc
```

### 版本最新动态

```dataview
table file.cday
from "2 Versions" and -"2 Versions/About Versions"
where (date(today) - file.mday).day < 8
sort file.cday
limit 10
``` 

### 其他 MOC

```dataview
table company, industry
from "3 Sources" and -"3 Sources/About Sources"
sort file.cday desc
```
