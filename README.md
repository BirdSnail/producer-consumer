# 多线程练习：实现一个生产者-消费者模型

生产者/消费者模型是多线程领域的经典问题。请实现一个生产者/消费者模型，其中：

- 生产者生产10个随机的整数供消费者使用（随机数可以通过`new Random().nextInt()`获得）
- 消费者依次消费这10个随机的整数

标准输出应该得到这样的结果：

```
Producing 42
Consuming 42
Producing -1
Consuming -1
...
Producing 10086
Consuming 10086
Producing -12345678
Consuming -12345678
```

我们鼓励你采用不同的方法尝试，例如：

- `Object.wait/notify`
- `Lock/Condition`
- `BlockingQueue`
- `Semaphore`
- `Exchanger`
- 等等等等
