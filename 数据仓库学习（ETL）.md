# 数据仓库学习（ETL）
-------

## 一 前言
在数据仓库组呆了1年，对ETL做些总结。ETL流在每个公司都多少有差异，一家之言，仅供参考。“不过，懂分享的人一定会快乐”。

比较有特色的是，我们会用tsv这种实体往各个数据库（关系/No sql）中导入。至于为啥这么干，打死你我也不会说。

## 二 数据源导出tsv
大部分公司会考虑直接用sqoop来做，但是我们在用tsv。导出tsv的方式也是挺简单粗暴。一段sql，一个脚本，生成元数据文件的.tsv.bz2格式，rsync把数据送到该去的地方消费掉。


## 三 使用


## 六 参考资料

- [Sqoop导入关系数据库到Hive](https://segmentfault.com/a/1190000002532293#articleHeader6)
