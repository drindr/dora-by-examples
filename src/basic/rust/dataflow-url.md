# Rust网址数据流

> 地址：examples/rust-dataflow-url
>
> 关键词：url

> [!WARNING]
> 由于Dora官方在发布新版本时已经不再包含rust-node的动态库文件，因此，此样例无法正确运行。

并非所有共享节点的作者都乐意通过git的形式进行共享，
于是Dora提供了另外一种更为通用的方式，即通过HTTP协议进行数据流传输。
这种方式还为二进制分发提供了便利。

```bash
$ dora build dataflow.yml
$ dora run dataflow.yml
```
