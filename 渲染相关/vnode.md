## 接口，实例化的参数几乎和createElement对应
``` java
VNode (
  tag?: string,
  data?: VNodeData,
  children?: ?Array<VNode>,
  text?: string,
  elm?: Node,
  context?: Component,
  componentOptions?: VNodeComponentOptions,
  asyncFactory?: Function
)
```
## 解读
vnode可以当成是vdom树的一个描述对象
