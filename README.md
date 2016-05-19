# HejExam
笔试
从开始读题目到全部写完大概10个小时，题目比看起来要困难，明早九点钟测试下刷新数据就提交。
## 优点
- MVP架构
- RxJava进行线程切换嵌套的异步操作，例如链式调用将data.json-> List<Message> 、 Message -> String(url) -> List<Stock> 避免回调引起的迷之缩进
- 处理了无网络，网络出错的异常情况

## 不足
- 为了完成需求，有持有其他类的静态引用的情况
- 本来想解耦的，但是横向的listview承担了model层的任务
