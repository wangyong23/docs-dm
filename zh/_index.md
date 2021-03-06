---
title: TiDB Data Migration 用户文档
summary: 了解 TiDB Data Migration 用户文档。
---

# TiDB Data Migration 用户文档

[TiDB Data Migration](https://github.com/pingcap/dm) (DM) 是一体化的数据同步任务管理平台，支持从 MySQL 或 MariaDB 到 TiDB 的全量数据迁移和增量数据同步。使用 DM 工具有利于简化错误处理流程，降低运维成本。

<NavColumns>
<NavColumn>
<ColumnTitle>关于 TiDB Data Migration</ColumnTitle>

- [性能数据](benchmark-v1.0-ga.md)
- [Table routing](key-features.md#table-routing)
- [Black & White Lists](key-features.md#black--white-table-lists)
- [Binlog Event Filter](key-features.md#binlog-event-filter)
- [同步延迟监控](key-features.md#同步延迟监控)
- [Online-ddl-scheme](feature-online-ddl-scheme.md)
- [分库分表合并同步](feature-shard-merge.md)

</NavColumn>

<NavColumn>
<ColumnTitle>快速上手</ColumnTitle>

- [应用场景](scenarios.md)
- [部署集群](quick-start-with-dm.md)
- [同步任务](replicate-data-using-dm.md)

</NavColumn>

<NavColumn>
<ColumnTitle>部署使用</ColumnTitle>

- [软硬件要求](hardware-and-software-requirements.md)
- [使用 DM-Ansible 部署集群](deploy-a-dm-cluster-using-ansible.md)
- [使用 Binary 部署集群](deploy-a-dm-cluster-using-binary.md)
- [使用 DM 同步数据](replicate-data-using-dm.md)
- [监控与告警设置](monitor-a-dm-cluster.md)
- [性能测试](performance-test.md)

</NavColumn>

<NavColumn>
<ColumnTitle>运维操作</ColumnTitle>

- [版本升级](dm-upgrade.md)
- [集群操作](cluster-operations.md)
- [任务管理](dmctl-introduction.md)
- [手动处理 Sharding DDL Lock](manually-handling-sharding-ddl-locks.md)
- [告警处理](handle-alerts.md)
- [日常巡检](daily-check.md)

</NavColumn>

<NavColumn>
<ColumnTitle>教程</ColumnTitle>

- [简单的从库同步场景](usage-scenario-simple-replication.md)
- [分库分表合并场景](usage-scenario-shard-merge.md)
- [从 Aurora 迁移到 TiDB](migrate-from-mysql-aurora.md)
- [分表合并数据迁移最佳实践](shard-merge-best-practices.md)
- [DM-worker 在上游 MySQL 主从间切换](usage-scenario-master-slave-switch.md)

</NavColumn>

<NavColumn>
<ColumnTitle>参考指南</ColumnTitle>

- [DM 架构](overview.md)
- [DM 命令行参数](command-line-flags.md)
- [配置概述](config-overview.md)
- [监控指标](monitor-a-dm-cluster.md)
- [告警信息](alert-rules.md)
- [错误码](error-handling.md#常见故障处理方法)

</NavColumn>

</NavColumns>