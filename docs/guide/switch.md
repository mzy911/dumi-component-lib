---
name: Switch
route: /Switch
order: 13
sidebar: true
---

## 使用

```js
import { Switch } from 'dumi-component-lib'

// 基本设置
<Switch /> <br /><br />
<Switch checked />


// 控制大小
<Switch size="small" /> <br /><br />
<Switch /> <br /><br />
<Switch size="large" />


// 开关文本
<Switch onText="开" offText="关" />
```

## API 文档

| 参数     | 说明               | 类型   | 默认值    |
| -------- | ------------------ | ------ | --------- |
| onClick  | 对外暴露的点击事件 | func   |           |
| checked  | 是否被选中         | bool   | false     |
| disabled | 是否被禁用         | bool   | false     |
| offText  | 关闭状态的文本     | string | ''        |
| onText   | 开启状态的文本     | string | ''        |
| size     | 组件的尺寸         | string | 'default' |
