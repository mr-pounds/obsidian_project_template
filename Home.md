---
date created: 2023-04-25 13:59:19
date modified: 2023-04-25 14:46:35
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
from "1 Demands"
sort file.cday desc
```

### 版本最新动态

```dataview
table file.mday
from "Version"
where (date(today) - file.mday).day < 8
sort file.mday
limit 10
``` 

### 其他 MOC

```dataview
table company, industry
from "3 Sources"
sort file.cday desc
```
