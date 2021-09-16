## 接口
``` js
// vm接口
$createElement (
  tag?: string | Component,
  data?: Object,
  children?: VNodeChildren
) => VNode;

// 柯里化逻辑
createElement (
  context: Component,
  tag: any,
  data: any,
  children: any,
  normalizationType: any,
  alwaysNormalize: boolean
) => VNode

// 最终执行逻辑
_createElement (
  context: Component,
  tag?: string | Class<Component> | Function | Object,
  data?: VNodeData,
  children?: any,
  normalizationType?: number
) => VNode
```

## 调用
``` js
new Vue({
  render (h) { return h('div')}
  render (h) { return h('div', '测试')}
  render (h) { return h('div', {}, [])}
})
```
