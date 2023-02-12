---
name: Tag
route: /Tag
order: 14
sidebar: true
---


## 使用

``` js
import { Tag } from 'dumi-component-lib'

// 基本使用
<Tag color="#06c">标签</Tag>
<Tag color="red">标签</Tag>
<Tag color="orange">标签</Tag>
<Tag >标签</Tag><br />
<Tag color="green" closable>标签</Tag>
<Tag closable>标签</Tag>


// 关闭时的回调
<Tag color="green" closable onClose={() => {alert('tag关闭')}}>标签</Tag>
```

## API文档
|  参数  |  说明  |  类型  |  默认值  |
|  ---   |  ---  |  ---  |  ---  |
|  closable  |  是否可关闭  |  bool  |  false  |
|  onClose  |  标签关闭时的回调  |  func  |   |
|  color  |  标签的颜色,不设置则为默认颜色  |  string  |  '#fafafa'  |