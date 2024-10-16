## Backup: RocksDB version compatible with ZenFS

ZenFS 需要 Linux 内核版本 5.9 或更高。使用的内核必须配置启用分区块设备支持。

ZenFS 使用 libzbd 库。必须先编译并安装这个库的最新版本，然后才能构建和安装 ZenFS。

ZenFS 嵌入在 RocksDB 中。它作为 RocksDB 的子模块提供，并且在编译 RocksDB 时必须显式启用。
