
#生产者与消息者例子
https://github.com/aqlu/rocketmq-demo

#参考spring2.0启动异常
https://www.jianshu.com/p/c6fd4ab90006

查了许多资料，最后同样是在github的Issue中找到了答案，参考Issue #77
当Springboot版本为2.X时需要修改配置文件中配置项spring.rocketmq.name-server为spring.rocketmq.nameServer，否则无法识别，而1.X版本则不存在此问题。