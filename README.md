# 阅读源码点滴
通过阅读Lock的实现类ReentrantLock的lock()方法，有一个方法不明白是什么意思，记录入下：
setExclusiveOwnerThread(current);//设置占用排它锁的线程是当前线程 
