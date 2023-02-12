---
name: Input
route: /input
order: 8
sidebar: true
---


## 用法

``` js
import { Input, Icon } from 'dumi-component-lib'

// 导入
<Input /> <br />


// Input带图标（搜索）
<Input icon={<Icon type='FaSistrix' />} onIconClick={(v) => {alert(`输入的是: ${v}`)}} />


// 自动聚焦
<Input autoFocus />
```

## API文档
|  参数  |  说明  |  类型  |  默认值  |
|  ---   |  ---  |  ---  |  ---  |
|  icon  |  是否带icon  |  ReactNode |  |
|  defaultValue  |  输入框默认内容  |  string |  |
|  id  |  输入框id  |  string |  |
|  className  |  输入框的类名  |  string |  |
|  style  |  输入框的样式  |  object |  |
|  placeholder  |  输入框的占位符  |  string |  |
|  type  |  输入框类型  |  string |  |
|  autoFocus  |  输入框是否自动聚焦  |  bool |  |
|  value  |  输入框的值  |  string |  |
|  onChange  |  输入框变化时的回调  |  func |  |
|  onIconClick  |  当icon按钮点击时的回调  |  func |  |
