# Chapter01 线程安全的对象生命期管理

如何避免对象析构时可能存在的 race condition（竞态条件）是 C++ 多线程编程面临的基本问题，可以借助 Boost 库中的 `shared_ptr` 和 `weak_ptr` 完美解决。


