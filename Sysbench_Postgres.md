>SysBench is an open-source benchmarking program originally targeted for use on MySQL databases. It can also be used for a variety of low-level system tests, from CPU to disk I/O.
When running the more complicate OLTP tests included, it has been known to some issues with locking on PostgreSQL, but at least read-only it seems to work fine.

>SysBench，开源测试工具，最初用于对mysql进行压测，当然也可以用于一些低级别的 CPU以及I/O性能测试
>对于Postgresql而言，Sysbench对于lock的处理有些问题。 不过，对于read-only的库，it works fine .

