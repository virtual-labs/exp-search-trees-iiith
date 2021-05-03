 Data structures supporting dictionary operations, primarily insert(), delete(), and find(), play an important role. To support dictionary operations, one can use a hash table. But a hash table can only support these operations on O(1) average time. The worst case time could be very high.

When using binary search trees, one can support all these operations in O(log n) time, in most cases. Moreover, a hash table cannot be used to support extended dictionary operations such as findMin() and findMax(). A binary tree can support these operations also efficiently.

