# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答：编写代码同时写注释。
在取名时使用有意义的名字。
数据处理尽量放在后端。
同一个HTML文件中尽量使用不同的id。
JS文件中尽量减少全局变量的使用，避免重复定义。
尽量减少闭包的使用，避免内存溢出。
统一入口函数init(),方便维护。

## 请问以下代码做了什么事情

```js
  const getLoglevel = () => {
    return localStorage.loglevel ?? 'INFO';
  };
```

答：只知道localStorage是前端缓存，loglevel是日志
