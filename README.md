# simple-redis

一个简单的 redis server 实现

参考文档: resp 协议

encode / decode

添加 cargo 依赖 enum_dispatch：可以用于轻松地重构动态分派的 trait 访问

bytes：提供了一组宏和数据结构，用于处理字节数据，具有零拷贝网络编程、避免借用检查器问题和高性能等优势

thiserror：提供了一个方便的 derive 宏，用于标准库的 std::error::Error 特征，简化了自定义错误类型的实现，使你的代码更加简洁和表达力强。

lazy_static：是 Rust 语言中的一个宏，它允许你定义在运行时第一次被访问时才初始化的静态变量。Rust 的 static 变量需要在编译时就确定其值，而 lazy_static 允许延迟初始化，这意味着可以使用非常量表达式作为静态变量的初始值。使用内部锁来确保初始化过程只执行一次，即使在多线程环境中也是安全的。
