---
name: Spin
route: /Spin
order: 12
sidebar: true
---


## 用法

``` js
import { Spin } from 'dumi-component-lib'

// 导入
<Spin />

// 线性加载
<Spin type="line" />

// 改变颜色
<Spin bgColor="orange" />
```

## API文档
|  参数  |  说明  |  类型  |  默认值  |
|  ---   |  ---  |  ---  |  ---  |
|  isLoading  |  加载中状态，默认为true  |  bool  |  |
|  loadingText  |  加载状态的文本  |  string  |  |
|  hiddenText  |  是否隐藏加载状态的文本  |  bool  |  |
|  type  |  spin的类型，目前有ball和line两种  |  string  |  |
|  bgColor  |  加载动画颜色  |  string  |  |
