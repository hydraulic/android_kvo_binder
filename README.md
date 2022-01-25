# 一个Android端的kvo实现

作为端上的开发，不论是客户端还是前端，一个很重要的框架就是数据的绑定和通知框架，像WPF的Dependency Property(同时MVVM这种框架也是微软先提出来的)，vue的属性绑定，iOS自带的kvo/kvc机制，同时Android端也有LiveData；相比于其他的数据变更通知框架，Android的LiveData显得比较简陋，


## 我的思考
对于自己做端上的架构经验来说，一个很重要的思路就是：业务逻辑和界面分离，同时围绕数据的流动和管理为核心来构建；

1. 业务逻辑和界面分离；
2. 数据治理；
    1. 数据存储；
    2. 数据的管理归属；
    3. 数据通知；

## 设计思路
1. 分层；

2. 功能简单完备；