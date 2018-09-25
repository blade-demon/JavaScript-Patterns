# JavaScript 常见设计模式

学习了 JavaScript 这么久，但是好多设计模式一直没有时间总结归纳，其实我们在日常的工作中，经常会使用到这些设计模式。下面就来好好温习归纳常见的设计模式。

## 单例模式

**单例模式的两个条件：** 只有一个实例，全局访问
**常见使用场景：** 网页的对话框，数据的缓存

## 观察者模式

当观察的数据对象发生变化的时候，自动调用相应的函数。
**常见使用场景：** vue 双向数据绑定

## 发布-订阅模式

事件发布/订阅模式 (PubSub) 在异步编程中帮助我们完成更松的解耦，甚至在 MVC、MVVC 的架构中以及设计模式中也少不了发布-订阅模式的参与。
**常见使用场景：** jquery 事件触发
**优点：** 在异步编程中实现更深的解耦
**缺点：** 过多使用发布订阅模式会增加维护难度
