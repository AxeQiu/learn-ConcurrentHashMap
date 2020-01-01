# learn-ConcurrentHashMap

* **Similarly, Iterators, Spliterators and Enumerations return elements reflecting the state of the hash table at some point at or since the creation of the iterator/enumeration. They do not throw ConcurrentModificationException. However, iterators are designed to be used by only one thread at a time.**

* ConcurrentHashMap的迭代器反映在迭代器创建时点的元素的状态。当Map本身的结构发生改变时，迭代器不会抛出ConcurrentModificationException，但是需要注意的是该类的迭代器是设计为供单线程调用的。
