- client发送sql查询到mysql server
- 查询缓存,如果命中缓存返回
- sql解析(检测关键字),预处理(检测数据库表,列,别名),然后优化器生成执行计划
- 根据执行计划调用存储引擎执行查询
- 返回结果