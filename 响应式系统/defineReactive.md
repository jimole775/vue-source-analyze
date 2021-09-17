## 接口
``` java
defineReactive (
  obj: Object,
  key: string,
  val: any,
  customSetter?: ?Function,
  shallow?: boolean // 是否用观察者模式封装，比如：如果val是一个基础类型的数据，就设置为false
) => void
```