---
name: Button
route: /Button
order: 3
---


## 用法

```jsx
import { Button } from 'dumi-component-lib'

export default () => {
  return (
    <div>
      {/* 基本用法 */}
      <Button type="primary">按钮</Button>
      <Button type="warning">按钮</Button>
      <Button type="info">按钮</Button>
      <Button type="pure">按钮</Button>
      <Button type="primary" shape="circle">按钮的命运</Button><br />
      

      {/* 块按钮block */}
      <div>
        <Button block>按钮</Button><br />
        <Button type="primary" block>按钮</Button><br />
        <Button type="warning" block>按钮</Button><br />
        <Button type="info" block>按钮</Button><br />
        <Button type="pure" block>按钮</Button><br />
        <Button type="primary" shape="circle" block>按钮</Button><br />
      </div> 
    </div>
  )
}
```

## API文档
|  参数  |  说明  |  类型  |  默认值  |
|  ---   |  ---  |  ---  |  ---  |
|  className  |  自定义类名  |  string  |  |
|  type  |  按钮类型 primary | warning | info | default | pure  |  string  |  default  |
|  shape  |  按钮形状circle | radius(默认)  |  string  |  radius  |
|  onClick  |  对外暴露的点击事件  |  func  |  |
