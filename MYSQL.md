# 脏页
缓存数据和数据库数据不一致，称为脏页
# 聚簇索引(主键索引或一级索引)
顺序存储的索引，一个表只能有一个聚簇索引，即主键索引,存取所有字段的数据
# 辅助索引(非聚簇索引或二级索引)
除了主键外，剩余的都是辅助索引，查询到主键id，必须查询多一次获取所有数据,只存储索引列
# 联合索引
多个字段索引，最左原则
# 覆盖索引(索引覆盖)
所有字段都建索引，查询一次数据就可以返回