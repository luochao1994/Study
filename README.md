SQL 基本操作

1.创建数据库
create database 数据库名 default charset utf8；

2.若要在某数据里执行操作，则应使用该数据库
use 数据库名

3.创建表格（含表头）
create table 表名（） 括号里写表头和表内容

4.表内容的格式
int整型，varchar()可变字符型 括号里为最大字符串大小，bit字节，

datetime时间，var()定长字符型，longblob二进制文件

5.更新表格（）
alter table 表格名 drop删除/set设置/add添加 column 列名

6.主外键
每个表都有自己的主键primary key 如果需要和别的表对应 则需设置自己的主
键为别的表的外键foriegn key并连接

7.插入数据
insert into 表名（*）values （值）
若*为空 则值需写出 表的每一列，若*为具体列名 则值输入对应列名的值即可

8.更新表格 update
用法和alter相同

9.查询
select * from 表名 （where 限制条件）
