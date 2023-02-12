---
name: Badge
route: /Badge
order: 2
sidebar: true
---

## 用法

``` js
import { Badge } from 'dumi-component-lib'

<Badge />

// 默认用法
<Badge count={99}>react</Badge>


// 设置overflowCount，展示封顶的数字
<Badge count={129} overflowCount={99}>react+vue</Badge>
<Badge count={129} overflowCount={99} style={{backgroundColor: 'green'}}>Node</Badge>

// 只展示一个小圆点
<Badge count={1} dot>javascript</Badge>

// 展示指示状态
<Badge status="success"></Badge>
<Badge status="warning"></Badge>
<Badge status="error"></Badge>
<Badge status="processing"></Badge>
<br /><br />

<Badge status="success" text="成功"></Badge><br />
<Badge status="error" text="错误"></Badge><br />
<Badge status="processing" text="进行中"></Badge><br />
<Badge status="warning" text="警告"></Badge>

```


## API文档
|  参数  |  说明  |  类型  |  默认值  |
|  ---   |  ---  |  ---  |  ---  |
|  style |  更改badge样式  |  object  |  |
|  color |  自定义小圆点的颜色  |  string  |  'red'  |
|  count |  展示的数字  |  number  |  0  |
|  dot |  不展示数字,只展示一个小圆点  |  bool  |  false  |
|  offset |  设置状态点的偏移  |  array  |    |
|  overflowCount |  展示封顶的数字  |  number  |    |
|  showZero |  当数值为0时是否展示Badge  |  bool  |  false  |
|  status |  设置badge为状态点, 类型有success|warning|error|default|processing  |  string  |  'default'  |
|  text |  当设置status时状态点的文本  |  string  |    |